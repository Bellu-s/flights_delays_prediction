# About Dataset
## Context

The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled, and diverted flights is published in DOT's monthly Air Travel Consumer Report and in this dataset of 2015 flight delays and cancellations.


**airlines.csv**
- IATA_CODE 
- AIRLINE


**airports.csv**
- IATA_CODE = Location Identifier
- AIRPORT = Airport's Name
- CITY = City name
- STATE = State name
- COUNTRY = Country name
- LATIDUTE = Latitude of the Airport 
- LONGITUDE = Longitude of the Airport


**Jan_2020_ontime.csv** 
- DAY_OF_MONTH           
- DAY_OF_WEEK            
- OP_UNIQUE_CARRIER = Unique Carrier Code. When the same code has been used by multiple carriers, a numeric suffix is used for earlier users, for example, PA, PA(1), PA(2). **DELETED**
- OP_CARRIER_AIRLINE_ID = An identification number assigned by US DOT to identify a unique airline (carrier). A unique airline (carrier) is defined as one holding and reporting under the same DOT certificate regardless of its Code, Name, or holding company/corporation.
- OP_CARRIER = Code assigned by IATA and commonly used to identify a carrier. As the same code may have been assigned to different carriers over time, the code is not always unique.
- OP_CARRIER_FL_NUM
- ORIGIN_AIRPORT_ID = Origin Airport, Airport ID. An identification number assigned by US DOT to identify a unique airport. 
- ORIGIN_AIRPORT_SEQ_ID = Origin Airport, Airport Sequence ID. An identification number assigned by US DOT to identify a unique airport at a given point of time. **DELETED**
- ORIGIN                 
- DEST_AIRPORT_ID = Destination Airport, Airport ID. An identification number assigned by US DOT to identify a unique airport.  
- DEST_AIRPORT_SEQ_ID = Destination Airport, Airport Sequence ID. An identification number assigned by US DOT to identify a unique airport at a given point of time. **DELETED**
- DEST                   
- DEP_TIME = Actual Departure Time (local time: hhmm)      
- DEP_DEL15 = Departure Delay Indicator, 15 Minutes or More (1=Yes, 0=No)         
- DEP_TIME_BLK = Departure Time Block, Hourly Intervals     
- ARR_TIME = Actual Arrival Time (local time: hhmm)           
- DIVERTED = Diverted Flight Indicator (1=Yes, 0=No)            
- ARR_DEL15 = Arrival Delay Indicator, 15 Minutes or More (1=Yes, 0=No)         
- CANCELLED = Cancelled Flight Indicator (1=Yes, 0=No)            
- DISTANCE = Distance between airports (miles)

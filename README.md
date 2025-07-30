TASK 1:The Five V's of Big Data

1. Variety
- The data is structured, it is organized in to a formatted way.
-It is following a structure of "sensor-id", "timestamp", "location"

2. Because the data is limited which makes it more easier to flow
 than having more data than an organization can handle.

3.It present confidence level
-"sensor_id": "TC-05-GER" because it have a null.

4.If we have a collecting data of 10000 sensors we can run out 
of storage.
-We can also have slowly processing memory.

5.Helps monitor and respond to environmental and traffic conditions
in real time to protect public health and improve city planning.

Use Case: Alert citizens and reroute traffic during poor air quality
periods using combined air, traffic, and noise sensor data.

TASK 2: Data Quality Assessment

1.Data quality is how accurate, complete, consistent, and reliable data is.
2. a) Inconsistent Timestamp formats "timestamp": "2025-07-29T08:46:15Z" 
(ISO 8601), "timestamp": "29/07/2025 08:47:00" (DD/MM/YYYY),"timestamp": 
"July 29 2025, 09:15:03 AM" (long format)
 b)Null data fields which means not reliable (in "sensor_id": "TC-05-GER")
 c) Invalid values e.g "value":-10

TASK 3: Data Governance & Security

1.{
    "sensor_id": "AQ-01-GER",
    "timestamp": "2025-07-29T08:45:10Z",
    "location": { "latitude": -26.2253, "longitude": 28.1613 },
    "data": { "type": "air_quality", "value": 45.5, "unit": "AQI" },
    "data_source_veracity": 0.95,
    "security":"Public"
  }
  
2. Competition will be higher another company can optimize their delivery
3.  routes of using data by reducing fuel costs and improve time to deliver.
- Trust will be lost together with reputation because everyone can view the
 systems which hackers can easily attack data.

3. The authority to define access levels should rest with a Data Governance
Officer or Data Steward, who understands compliance and data policies.
 Developers or project managers typically lack the oversight and accountability
 for setting proper data access controls.

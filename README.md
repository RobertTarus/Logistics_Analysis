# Logistics_Analysis

## Overview
This project analyzes shipment data generated using the Faker library. It includes data on shipments, delivery statuses, and customer information.

## Creating Dataset using Python
The following is the explanation of each of the columns of the Dataset:

### Customer Details:

-CustomerID: Unique identifier for each customer.
 
-CustomerName: Name of the customer.

-CustomerType: Type of customer (e.g., Government, Private, NGO).

-CustomerCategory: Segment of the customer (e.g., Large Enterprise, SME).

### Shipment Details:

### ShipmentID: Unique identifier for each shipment.

-BILL_NUMBER: Unique identifier for the billing or invoice.

-STATUS: Current status of the shipment (e.g., in transit, delivered).

-CURRENT_ZONE: Current geographic zone where the shipment is located.

-DEL_TERM: Delivery terms or conditions.

-PU_DATE: Pickup date.

-PU_TIME: Pickup time.

-RDD: Requested delivery date.

-ACTUAL_DEL: Actual delivery date.

-ACTUAL_TIME: Actual delivery time.

-PIECES: Number of pieces or units in the shipment.

-WEIGHT: Weight of the shipment.

-SHIPPING_COST: Cost of shipping.

-DISTANCE_TRAVELLED: Distance covered during the shipment.

-TEMP_CONTROL: Indicator if temperature control is required.

-DELIVERY_MODE: Mode of delivery (e.g., road, rail, sea, air).

### Commodity Details:

-COMMODITY: Description of the goods being shipped.

-COMMODITY_TYPE: Type of goods (e.g., Dangerous, High Value, Standard).

-HAZARDOUS: Indicator if the goods include hazardous materials.

-HAZARD_CLASS: Class of the hazardous materials (if any).

-GOODS_VALUE: Value of the goods being transported.

### Shipper Details:

-ShipperID: Unique identifier for the shipper.

-SHIPPER_NAME: Name of the shipper.

-SHIPPER_CITY: City where the shipper is located.

-SHIPPER_PROV: Province where the shipper is located.

-ORIGIN_COUNTRY: Country of the shipper.

### Consignee Details:

-ConsigneeID: Unique identifier for the consignee.

-CONSIGNEE_NAME: Name of the consignee.

-CONSIGNEE_ADDRESS: Address of the consignee.

-CONS_CITY: City of the consignee.

-CONS_PROV: Province of the consignee.

-DEST_COUNTRY: Country of the consignee.

### Appointment and Delivery Details:

-APPT_REQ: Indicator if an appointment is required.

-APPT_MADE: Indicator if an appointment has been made.

-DLRY_BY_DATE: Date by which the delivery should be made.

-DLRY_BY_TIME: Time by which the delivery should be made.

-ARRCONS: Arrival time at consignee’s location.

-DEPCONS: Departure time from consignee’s location.

-SPTUNLD: Special unloading requirements or notes.

-ATMPTDLVRY: Indicator if delivery was attempted but not completed.

### Delay and Issue Details:

-DELAY: General delay information.

-DLY_FERRY: Delay due to ferry transportation.

-DLY_MECHAN: Delay due to mechanical issues.

-DLY_RAIL: Delay due to rail transportation issues.

-DLY_WEATHR: Delay due to weather conditions.

-CUSTLATE: Indicator if the customer was late in some aspect.

-NOFREIGHT: Indicator if no freight was found or present.

-WEATHER: Weather conditions at the time of the shipment.

-ISSUE_REPORTED: Indicator if any issues were reported.

-ISSUE_DESCRIPTION: Description of the issues reported (if any).

-SECURITY_INCIDENTS: Indicator if any security incidents occurred.

-INCIDENT_DETAILS: Details of the security incidents (if any).



## Breakdown of each line of code:



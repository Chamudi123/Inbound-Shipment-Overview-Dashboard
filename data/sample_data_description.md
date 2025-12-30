# Sample Data Description

The dashboard is built on structured shipment-level data.

## Expected Fields
- Shipment ID
- Origin
- Destination
- Shipper
- Consignee
- Product Category
- HS Code
- Package Count
- Weight (KG)
- Declared Value ($)
- Routing Status

## Notes
- Missing HS Codes are flagged using helper columns
- Misrouted shipments are identified using routing status flags
- Data can be refreshed by updating the source table and refreshing pivots

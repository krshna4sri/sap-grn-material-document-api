# sap-grn-material-document-api
API for Creating Goods Receipt Note (GRN) To create a GRN with reference to a material in SAP S/4HANA Cloud, use the Material Document API.  Correct API Endpoint
Here's a GitHub post template with masked values:

```markdown
# Creating Goods Receipt Note (GRN) in SAP S/4HANA Cloud

This guide demonstrates how to create a Goods Receipt Note (GRN) using the Material Document API in SAP S/4HANA Cloud.

## API Endpoint

```
POST /sap/opu/odata/sap/API_MATERIAL_DOCUMENT_SRV/A_MaterialDocumentHeader
```

## Example Payload

```json
{
    "PostingDate": "YYYY-MM-DDT00:00:00",
    "DocumentDate": "YYYY-MM-DDT00:00:00",
    "GoodsMovementCode": "XX",
    "to_MaterialDocumentItem": [
        {
            "Material": "XXXXXXXX",
            "Plant": "XXXX",
            "StorageLocation": "XXXX",
            "GoodsMovementType": "XXX",
            "EntryUnit": "XX",
            "QuantityInEntryUnit": "XX"
        }
    ]
}
```

## Instructions

1. Replace the masked values with actual data specific to your company.
2. Send the request to the specified API endpoint.

## Additional Resources

For more details, refer to the [SAP Help Portal](https://help.sap.com/docs/SAP_S4HANA_CLOUD/3f57e7df4a114edabffe8b2d581a59ed/8bb0d08295044ee3af444b4f2a6e4457.html).
```

Replace the placeholders (e.g., `YYYY-MM-DD`, `XXXXXXXX`) with actual values relevant to your company's data and setup. This template ensures sensitive or company-specific information is not shared publicly.

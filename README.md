# OCDS 1.2 Draft Extension

Adds fields, definitions and codelists from the draft version of OCDS 1.2 for use in [OCDS for eForms](https://standard.open-contracting.org/profiles/eforms/latest/en/).

## Legal context

In the European Union, this extension's fields correspond to the following [eForms business terms](https://docs.ted.europa.eu/eforms/latest/reference/business-terms/):

* BT-660 (Framework Re-estimated Value)
* BT-709 (Framework Maximum Value)
* BT-708 (Documents Official Language)

For correspondences to eForms fields, see [OCDS for eForms](https://standard.open-contracting.org/profiles/eforms/latest/en/).

## Example

```json
{
  "tender": {
    "documents": [
      {
        "id": "1",
        "languages": [
          "en"
        ]
      }
    ]
  },
  "awards": [
    {
      "id": "1",
      "estimatedValue": {
        "amount": 4500,
        "currency": "EUR"
      },
      "maximumValue": {
        "amount": 5000,
        "currency": "EUR"
      }
    }
  ]
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

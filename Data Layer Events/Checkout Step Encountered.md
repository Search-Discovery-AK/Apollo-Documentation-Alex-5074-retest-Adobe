# Checkout Step Encountered

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Checkout Step Encountered",
    "listingItemClicked": {
        "listing": [
            {
                "location": {
                    "locationId": "<locationId>"
                }
            }
        ]
    },
    "transaction": {
        "total": {
            "currency": "<currency>"
        }
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingItemClicked.listing[n].location.locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|transaction.total.currency|string|Currency of the transaction. ISO 4217 \(3 character alpha\), uppercase |USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||





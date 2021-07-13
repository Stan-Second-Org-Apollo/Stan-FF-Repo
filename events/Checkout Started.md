# Checkout Started

### 

## Javascript Code
```js
window.appEventData098 = window.appEventData098 || [];
appEventData098.push({
  "event": "Checkout Started",
    "product": [
        {
            "price": {
                "sellingPrice": "<sellingPrice>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|sellingPrice|string|String representation of the price paid after coupons or discounts. Positive. Up to two decimal places for cents. No currency symbol.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||

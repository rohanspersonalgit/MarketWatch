# Get the company with largest price transaction

Go through all the transactions and find the company with that has the most expensive price per share for the transaction

**URL** : `http://localhost:3005/largestPriceTx`

**Method** : `GET`

**Data constraints**

None.

## Success Response

**Condition** : If everything is OK and stock purchase was successful.

**Code** : `200 OK`

**Content example**

```json
{
    "companyid": "AAPL"
}
```

## Error Response

**Condition** : If database query encountered an error.

**Code** : `500 Internal Server Error`

**Content** : `{error: error message}`
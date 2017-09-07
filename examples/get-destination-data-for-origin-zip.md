### Request

```
curl -X GET "https://api-beta.arity.com/shared-mobility-insights/v1/zip-codes/60654/destination-zip-codes?tripType=Personal&startDayOfWeek=Monday&startHour=6&duration=4"
```

### Response

```json
{
  "originZipCode": {
    "zipCode": "60654",
    "relativityScore": 0.42,
    "averageTripMiles": 1.97,
    "averageTripDuration": 11.97
  },
  "destinationZipCodes": [
    {
      "zipCode": "60654",
      "tripPercentage": 0.4474,
      "averageTripMiles": 0.79,
      "averageTripDuration": 8.44
    },
    {
      "zipCode": "60612",
      "tripPercentage": 0.0965,
      "averageTripMiles": 3.58,
      "averageTripDuration": 17.28
    },
    {
      "zipCode": "60607",
      "tripPercentage": 0.0789,
      "averageTripMiles": 2.67,
      "averageTripDuration": 20.34
    },
    {
      "zipCode": "60642",
      "tripPercentage": 0.0702,
      "averageTripMiles": 1.65,
      "averageTripDuration": 11.12
    },
    {
      "zipCode": "60611",
      "tripPercentage": 0.0614,
      "averageTripMiles": 0.76,
      "averageTripDuration": 7.4
    },
    {
      "zipCode": "60610",
      "tripPercentage": 0.0614,
      "averageTripMiles": 1.24,
      "averageTripDuration": 8.61
    },
    {
      "zipCode": "60614",
      "tripPercentage": 0.0439,
      "averageTripMiles": 3.08,
      "averageTripDuration": 17.48
    },
    {
      "zipCode": "60618",
      "tripPercentage": 0.0263,
      "averageTripMiles": 5,
      "averageTripDuration": 21.46
    },
    {
      "zipCode": "60621",
      "tripPercentage": 0.0263,
      "averageTripMiles": 10.1,
      "averageTripDuration": 18.24
    },
    {
      "zipCode": "60606",
      "tripPercentage": 0.0088,
      "averageTripMiles": 1,
      "averageTripDuration": 9.95
    },
    {
      "zipCode": "60661",
      "tripPercentage": 0.0088,
      "averageTripMiles": 0.2,
      "averageTripDuration": 5.75
    },
    {
      "zipCode": "60603",
      "tripPercentage": 0.0088,
      "averageTripMiles": 1.4,
      "averageTripDuration": 9.25
    },
    {
      "zipCode": "60625",
      "tripPercentage": 0.0088,
      "averageTripMiles": 9.2,
      "averageTripDuration": 43.33
    },
    {
      "zipCode": "60602",
      "tripPercentage": 0.0088,
      "averageTripMiles": 1.4,
      "averageTripDuration": 9.35
    },
    {
      "zipCode": "60622",
      "tripPercentage": 0.0088,
      "averageTripMiles": 2.4,
      "averageTripDuration": 11.83
    },
    {
      "zipCode": "60616",
      "tripPercentage": 0.0088,
      "averageTripMiles": 5.1,
      "averageTripDuration": 19.57
    },
    {
      "zipCode": "60653",
      "tripPercentage": 0.0088,
      "averageTripMiles": 7.5,
      "averageTripDuration": 18.73
    },
    {
      "zipCode": "60601",
      "tripPercentage": 0.0088,
      "averageTripMiles": 0.2,
      "averageTripDuration": 2.6
    },
    {
      "zipCode": "60608",
      "tripPercentage": 0.0088,
      "averageTripMiles": 5.3,
      "averageTripDuration": 27.98
    }
  ]
}
```

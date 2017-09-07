### Request

```
curl -X GET "https://api-beta.arity.com/shared-mobility-insights/v1/zip-codes/60654/origin-zip-codes?tripType=Personal&startDayOfWeek=Monday&startHour=6&duration=4"
```

### Response

```json
{
  "destinationZipCode": {
    "zipCode": "60654",
    "relativityScore": 0.73,
    "averageTripMiles": 4.18,
    "averageTripDuration": 22.77
  },
  "originZipCodes": [
    {
      "zipCode": "60654",
      "tripPercentage": 0.2462,
      "averageTripMiles": 0.79,
      "averageTripDuration": 8.28
    },
    {
      "zipCode": "60618",
      "tripPercentage": 0.0718,
      "averageTripMiles": 6.01,
      "averageTripDuration": 31.86
    },
    {
      "zipCode": "60622",
      "tripPercentage": 0.0667,
      "averageTripMiles": 3.32,
      "averageTripDuration": 23.28
    },
    {
      "zipCode": "60657",
      "tripPercentage": 0.0564,
      "averageTripMiles": 4.22,
      "averageTripDuration": 22.41
    },
    {
      "zipCode": "60607",
      "tripPercentage": 0.0462,
      "averageTripMiles": 2.1,
      "averageTripDuration": 13.54
    },
    {
      "zipCode": "60647",
      "tripPercentage": 0.041,
      "averageTripMiles": 5.68,
      "averageTripDuration": 27.51
    },
    {
      "zipCode": "60610",
      "tripPercentage": 0.0359,
      "averageTripMiles": 1.04,
      "averageTripDuration": 6.94
    },
    {
      "zipCode": "60612",
      "tripPercentage": 0.0359,
      "averageTripMiles": 3.5,
      "averageTripDuration": 25.36
    },
    {
      "zipCode": "60611",
      "tripPercentage": 0.0359,
      "averageTripMiles": 0.71,
      "averageTripDuration": 5.69
    },
    {
      "zipCode": "60661",
      "tripPercentage": 0.0308,
      "averageTripMiles": 1.95,
      "averageTripDuration": 17.31
    },
    {
      "zipCode": "60640",
      "tripPercentage": 0.0256,
      "averageTripMiles": 7.08,
      "averageTripDuration": 28.31
    },
    {
      "zipCode": "60642",
      "tripPercentage": 0.0256,
      "averageTripMiles": 1.8,
      "averageTripDuration": 17.06
    },
    {
      "zipCode": "60632",
      "tripPercentage": 0.0256,
      "averageTripMiles": 7.04,
      "averageTripDuration": 35.84
    },
    {
      "zipCode": "60625",
      "tripPercentage": 0.0205,
      "averageTripMiles": 9.18,
      "averageTripDuration": 45.48
    },
    {
      "zipCode": "60626",
      "tripPercentage": 0.0205,
      "averageTripMiles": 10.5,
      "averageTripDuration": 24.59
    },
    {
      "zipCode": "60613",
      "tripPercentage": 0.0205,
      "averageTripMiles": 5.45,
      "averageTripDuration": 27.22
    },
    {
      "zipCode": "60609",
      "tripPercentage": 0.0205,
      "averageTripMiles": 11.35,
      "averageTripDuration": 63.89
    },
    {
      "zipCode": "60645",
      "tripPercentage": 0.0154,
      "averageTripMiles": 11.73,
      "averageTripDuration": 43.37
    },
    {
      "zipCode": "60615",
      "tripPercentage": 0.0154,
      "averageTripMiles": 8.37,
      "averageTripDuration": 25
    },
    {
      "zipCode": "60608",
      "tripPercentage": 0.0154,
      "averageTripMiles": 5.67,
      "averageTripDuration": 33.28
    },
    {
      "zipCode": "60659",
      "tripPercentage": 0.0154,
      "averageTripMiles": 10.93,
      "averageTripDuration": 58.04
    },
    {
      "zipCode": "60614",
      "tripPercentage": 0.0154,
      "averageTripMiles": 2.93,
      "averageTripDuration": 20.93
    },
    {
      "zipCode": "60616",
      "tripPercentage": 0.0103,
      "averageTripMiles": 3.7,
      "averageTripDuration": 31.24
    },
    {
      "zipCode": "60601",
      "tripPercentage": 0.0103,
      "averageTripMiles": 1.05,
      "averageTripDuration": 8.55
    },
    {
      "zipCode": "60636",
      "tripPercentage": 0.0103,
      "averageTripMiles": 11.4,
      "averageTripDuration": 55.05
    },
    {
      "zipCode": "60605",
      "tripPercentage": 0.0103,
      "averageTripMiles": 3.1,
      "averageTripDuration": 17.7
    },
    {
      "zipCode": "60644",
      "tripPercentage": 0.0051,
      "averageTripMiles": 9.1,
      "averageTripDuration": 51.88
    },
    {
      "zipCode": "60623",
      "tripPercentage": 0.0051,
      "averageTripMiles": 8.3,
      "averageTripDuration": 42.07
    },
    {
      "zipCode": "60606",
      "tripPercentage": 0.0051,
      "averageTripMiles": 2.6,
      "averageTripDuration": 22.58
    },
    {
      "zipCode": "60660",
      "tripPercentage": 0.0051,
      "averageTripMiles": 9.4,
      "averageTripDuration": 29.32
    },
    {
      "zipCode": "60637",
      "tripPercentage": 0.0051,
      "averageTripMiles": 11.1,
      "averageTripDuration": 40.6
    },
    {
      "zipCode": "60641",
      "tripPercentage": 0.0051,
      "averageTripMiles": 7.2,
      "averageTripDuration": 28.45
    },
    {
      "zipCode": "60652",
      "tripPercentage": 0.0051,
      "averageTripMiles": 16.7,
      "averageTripDuration": 87.45
    },
    {
      "zipCode": "60631",
      "tripPercentage": 0.0051,
      "averageTripMiles": 14.2,
      "averageTripDuration": 67.68
    },
    {
      "zipCode": "60630",
      "tripPercentage": 0.0051,
      "averageTripMiles": 9.4,
      "averageTripDuration": 60.5
    },
    {
      "zipCode": "60018",
      "tripPercentage": 0.0051,
      "averageTripMiles": 16.7,
      "averageTripDuration": 70.32
    },
    {
      "zipCode": "60602",
      "tripPercentage": 0.0051,
      "averageTripMiles": 2.3,
      "averageTripDuration": 16.08
    }
  ]
}
```

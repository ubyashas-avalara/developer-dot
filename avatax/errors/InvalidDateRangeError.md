---
layout: page
title: InvalidDateRangeError
number: 81
categories: [AvaTax Error Codes]
disqus: 0
---

## Summary

You specified a date outside of the allowable range.

## Example

    {
      "code": "InvalidDateRangeError",
      "target": "Unknown",
      "details": [
        {
          "code": "InvalidDateRangeError",
          "number": 81,
          "message": "An invalid date range was provided.",
          "description": "The -0- has to be in  between -1- and -2-.",
          "faultCode": "Client",
          "helpLink": "http://developer.avalara.com/avatax/errors/InvalidDateRangeError",
          "severity": "Error"
        }
      ]
    }

## Explanation

Please check your API call and specify a valid date within the defined range.
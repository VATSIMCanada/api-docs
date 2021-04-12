[![VATSIM Canada](https://i.imgur.com/l6ZwnfT.png)](https://vatcan.ca)
# About
[VATSIM Canada](https://vatcan.ca) API Documentation.

## Authentication
Most routes on the API require authentication, if you are a VATCAN Webmaster, you
can generate your API key by going to Facility Management, then Web Configuration.

You can pass your API key in the Authorization Header:
```
Token (API Key here)
```

Or, you may pass it in the query string:
```
http://vatcan.ca/api/v2/someroute?api_key=(API KEY Here)
```

## Not a VATCAN FIR Webmaster?
The VATCAN API is mostly for our FIRs, there is limited integration for non authenticated
requests.

If your project requires an API key, send an email to `tech@vatcan.ca`.

## Want to contribute?
Feel free to make a PR and add to Swagger. We are still trying to get everything
added, so things may be missing in some places (ie response codes, response examples, models, etc)

## Contributors
```
Jordan Jolenaar     (1429747) - github.com/JordannDev
Kolby Dunning       (1427371) - github.com/kolbyd
```


## Rate Limit
Simple RESTfull api service.

Endpoints:

http://homestead.app/api/greet/{name} -> return a json response with the name passed in the url.
Rate limit set to 10 requests per minute: created custom middleware that extend the Throttle class and override the buildResponse method.








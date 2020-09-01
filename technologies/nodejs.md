1. [Frameworks](#frameworks)
1. [Code style](#code-style)
1. [Best practices](#best-practices)

## Frameworks
Prefer NestJS over other frameworks for general use cases.

## Code style
We try to follow the most popular code style per language and respect the code styles of particular frameworks. 
For JavaScript in general, well written Airbnb code style guide is recommended.
https://github.com/airbnb/javascript

## Best practices

### Returning errors in API
Blindly following REST approach and return error code as HTTP status is not recommended. 
Prefer to return sinlge HTTP status 500 but with meangful JSON object of `errorCode` and `errorMessage`.
See more:
- https://www.baeldung.com/rest-api-error-handling-best-practices

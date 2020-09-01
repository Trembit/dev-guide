1. [Frameworks](#frameworks)
1. [Coding Standards](#coding-standards)
1. [Best practices](#best-practices)

## Frameworks
Prefer NestJS over other frameworks for general use cases.

## Coding Standards
We try to follow the most popular code style per language and respect the code styles of particular frameworks. 
For JavaScript in general, well written Airbnb code style guide is recommended.
https://github.com/airbnb/javascript

## Best practices

### Database migrations
TODO

### Unit and integrational testing
TODO

### File upload
We don't keep files on server but upload to AWS S3. User appropriate library.

### Returning errors in API
Blindly following REST approach and return error code as HTTP status is not recommended. 
Prefer to return sinlge HTTP status 500 but with meangful JSON object of `errorCode` and `errorMessage`.
See more:
- https://www.baeldung.com/rest-api-error-handling-best-practices

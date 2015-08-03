#rest-api-essentials

Basics for RESTFul APIs in a demystified way

##Features
*	**SecurityChain** - Simplified authorization and user roles check using *SecurityHelper* interface
*   **ExceptionHandlingFilter** - Annoying non-api exceptions won't be written within responses (empty *InternalServerError* instead)
*	**API Exceptions** - HTTP status: [*RFC2616*](http://tools.ietf.org/html/rfc2616) and [*RFC4918*](http://tools.ietf.org/html/rfc4918) compliance:
  * 400 - BadRequestException
  * 401 - UnauthorizedException
  * 402 - PaymentRequiredException
  * 407 - ProxyAuthenticationRequiredException
  * 408 - RequestTimeoutException
  * 409 - ConflictException
  * 412 - PreconditionFailedException
  * 413 - RequestEntityTooLargeException
  * 415 - UnsupportedMediaTypeException
  * 416 - RequestedRangeNotSatisfiableException
  * 417 - ExpectationFailedException
  * 422 - UnprocessableEntityException
  * 424 - FailedDependencyException
  * 502 - BadGatewayException
  * 503 - ServiceUnavailableException

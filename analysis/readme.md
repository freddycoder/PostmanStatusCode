# Analysis

This folder contains a collection with every client error status code. 

Each case from 400 to 499 has been created. 29 / 100 test passed. Here is the list of status codes that work well with the postman mock server. 

> The test has been executed on 7 November 2020.
> The column Name (System.Net.HttpStatusCode) is the enum in the dotnet core 3.1 SDK.

| Status code | Name (wiki)                          | Name (System.Net.HttpStatusCode) | Support of Postman mock server |
|-------------|--------------------------------------|----------------------------------|--------------------------------|
| 400         | Bad Request                          | BadRequest                       | ✔️                             |
| 401         | Unauthorized                         | Unauthorized                     | ✔️                             |
| 402         | Payment Required                     | PaymentRequired                  | ✔️                             |
| 403         | Forbidden                            | Forbidden                        | ✔️                             |
| 404         | Not Found                            | NotFound                         | ✔️                             |
| 405         | Method Not Allowed                   | MethodNotAllowed                 | ✔️                             |
| 406         | Not Acceptable                       | NotAcceptable                    | ✔️                             |
| 407         | Proxy Authentication Required        | ProxyAuthenticationRequired      | ✔️                             |
| 408         | Request Time-out                     | RequestTimeout                   | ✔️                             |
| 409         | Conflict                             | Conflict                         | ✔️                             |
| 410         | Gone                                 | Gone                             | ✔️                             |
| 411         | Length Required                      | LengthRequired                   | ✔️                             |
| 412         | Precondition Failed                  | PreconditionFailed               | ✔️                             |
| 413         | Request Entity Too Large             | RequestEntityTooLarge            | ✔️                             |
| 414         | Request-URI Too Long                 | RequestUriTooLong                | ✔️                             |
| 415         | Unsupported Media Type               | UnsupportedMediaType             | ✔️                             |
| 416         | Requested range unsatisfiable        | RequestedRangeNotSatisfiable     | ✔️                             |
| 417         | Expectation failed                   | ExpectationFailed                | ✔️                             |
| 418         | I’m a teapot                         |                                  | ✔️                             |
| 419         |                                      |                                  | ❌                             |
| 420         |                                      |                                  | ❌                             |
| 421         | Bad mapping / Misdirected Request    | MisdirectedRequest               | ✔️                             |
| 422         | Unprocessable entity                 | UnprocessableEntity              | ✔️                             |
| 423         | Locked                               | Locked                           | ✔️                             |
| 424         | Method failure                       | FailedDependency                 | ✔️                             |
| 425         | Too Early                            |                                  | ✔️                             |
| 426         | Upgrade Required                     | UpgradeRequired                  | ✔️                             |
| 427         |                                      |                                  | ❌                             |
| 428         | Precondition Required                | UpgradeRequired                  | ✔️                             |
| 429         | Too Many Requests                    | TooManyRequests                  | ✔️                             |
| 430         |                                      |                                  | ❌                             |
| 431         | Request Header Fields Too Large      | RequestHeaderFieldsTooLarge      | ✔️                             |
| 432         |                                      |                                  | ❌                             |
| 433         |                                      |                                  | ❌                             |
| 434         |                                      |                                  | ❌                             |
| 435         |                                      |                                  | ❌                             |
| 436         |                                      |                                  | ❌                             |
| 437         |                                      |                                  | ❌                             |
| 438         |                                      |                                  | ❌                             |
| 439         |                                      |                                  | ❌                             |
| 440         |                                      |                                  | ❌                             |
| 441         |                                      |                                  | ❌                             |
| 442         |                                      |                                  | ❌                             |
| 443         |                                      |                                  | ❌                             |
| 444         |                                      |                                  | ❌                             |
| 445         |                                      |                                  | ❌                             |
| 446         |                                      |                                  | ❌                             |
| 447         |                                      |                                  | ❌                             |
| 448         |                                      |                                  | ❌                             |
| 449         | Retry With                           |                                  | ❌                             |
| 449         | Blocked by Windows Parental Controls |                                  | ❌                             |
| 451         | Unavailable For Legal Reasons        | UnavailableForLegalReasons       | ✔️                             |
| 452         |                                      |                                  | ❌                             |
| 453         |                                      |                                  | ❌                             |
| 454         |                                      |                                  | ❌                             |
| 455         |                                      |                                  | ❌                             |
| 456         | Unrecoverable Error                  |                                  | ❌                             |
| 457         |                                      |                                  | ❌                             |
| 458         |                                      |                                  | ❌                             |
| 459         |                                      |                                  | ❌                             |
| 460         |                                      |                                  | ❌                             |
...

When there is no support for Postman mock server, code 200 is returned instead.

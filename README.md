# Authenticated ToDo List
REST API example with API key and OpenAPI documentation.

## Usage

### Authentication
An API key `X-API-Key` with the hardcoded value `mysecureapikey123` is expected.

### Endpoints

|Method|Endpoint|Body params|
|-|-|-|
|GET|/todos||
|GET|/todos/:id||
|POST|/todos|id, task, done|
|PUT|/todos/:id|task, done|
|DELETE|/todos/:id||

### API Documentation
Available at `<SERVER_URL>/docs`.

## Tools
Flask / Python

## Author
Kesha Williams, from her LinkedIn Learning course [*Programming Foundations: APIs and Web Services*](https://www.linkedin.com/learning/programming-foundations-apis-and-web-services-27993033) ([Original source](https://github.com/LinkedInLearning/programming-foundations-apis-and-web-services-3811153/tree/main/03_02)).
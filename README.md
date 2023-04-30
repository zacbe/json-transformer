# JSON transformer service
This project is to develop a service that transforms incoming JSON objects into a transformed version using JSONata transformers. The service supports schema and transformer updates, batching of multiple object transformations, and offers pub/sub methods to post resulting transformations. It caches frequently used transformers for efficiency, and provides JSON or CSV output formats. The goal is to provide an efficient and user-friendly JSON object transformation service.

## Functional requirements:

- The service should transform incoming JSON objects and return the transformed version.
- The service should store object type schemas and corresponding JSONata transformers.
- The service should provide a Restful API.
- The service should allow batching of multiple object transformations.
- The service should offer a pub/sub method to post resulting transformations.
- The service should allow updating object schemas and transformers.
- The service should provide both JSON and CSV output formats.

## Non-functional Requirements:

- The service should efficiently cache commonly used object type transformers.

Lab Explanation

This lab introduces students to a basic serverless API pattern in AWS using API Gateway, Lambda, and CloudWatch Logs. The goal is to show that a client can send an HTTP request to an API endpoint, API Gateway can route that request to a Lambda function, and the Lambda function can process the request and return a response without the student managing any servers.

The lab uses two Lambda functions written in different languages so students understand that AWS Lambda is not “a Python thing.” It is a runtime-based execution model that supports multiple languages and lets teams choose the right tool for the job. This helps break the common beginner assumption that cloud automation and serverless work are tied to a single programming language.

The use case is intentionally simple and easy to remember: a request is sent with a name, and each Lambda responds in its own way. One may return a greeting with a timestamp, and the other may return a transformed version of the input. This keeps the cognitive load low so students can focus on the architecture, request flow, and operational visibility.

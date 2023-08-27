# aws-servereless-developer
This GitHub repository for applications that demonstrate the use of Java in AWS Lambda along with API Gateway, AWS DynamoDB and SAM

# What is serverless?
Serverless workloads are “event-driven workloads that aren’t concerned with aspects normally handled by server infrastructure.” Concerns like “how many instances to run” and “what operating system to use” are all managed by a Function as a Service platform (or FaaS), leaving developers free to focus on business logic.

# Serverless characteristics?
Serverless applications have a number of specific characteristics, including:

- Event-driven code execution with triggers
- Platform handles all the starting, stopping, and scaling chores
- Scales to zero, with low to no cost when idle
- Stateless

# Spring and Serverless

The Spring portfolio provides a robust collection of functionality for use within serverless applications. Whether accessing data with Spring Data, using the enterprise integration patterns with Spring Integration, or using the latest in reactive programming with Spring Framework and Project Reactor, Spring lets developers be productive in a serverless environment from day one.

Spring also helps your functions avoid vendor lock-in. The adapters provided by Spring Cloud Function let you decouple from vendor-specific APIs when running your code on their platform.

# In detail: Spring Cloud Function
Spring Cloud Function provides capabilities that lets Spring developers take advantage of serverless or FaaS platforms.

The java.util.function package from core Java serves as the foundation of the programming model used by Spring Cloud Function. In a nutshell, Spring Cloud Function provides:

Choice of programming styles: reactive, imperative, or hybrid.
Function composition and adaptation (such as composing imperative functions with reactive).
Support for reactive function with multiple inputs and outputs to let functions handle merging, joining, and other complex streaming operations.
Transparent type conversion of inputs and outputs.
Packaging functions for deployments, specific to the target platform (such as Project Riff, AWS Lambda, and more; see below).
Functions with flexible signatures (POJO functions) - “if it looks like a function, it’s a function”
All other benefits of Spring's idioms and programming model.


# References
https://docs.aws.amazon.com/lambda/latest/dg/lambda-java.html

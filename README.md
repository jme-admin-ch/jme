# JME - jEAP Microservice Examples

Welcome to the **jEAP Microservice Examples (JME)** umbrella repository. JME provides a suite of
example microservices designed to demonstrate the development of jEAP-based microservices. Each JME repository
focuses on a specific jEAP functionality.

## Purpose

The jEAP microservice examples offer developers a collection of ready-to-run microservices that demonstrate best
practices for leveraging specific jEAP features. The examples address common challenges and cross-cutting concerns in
enterprise application development.

## Getting Started

This umbrella repository provides guidance on the individual jEAP microservice examples in the JME suite. Explore each
example to see how specific jEAP functionalities can be applied to your projects.

## License

This repository is Open Source Software licensed under the [Apache License 2.0](./LICENSE).

## Repository List

Below you will find an overview of all repositories included in the JME umbrella, each with a short description of its
focus and functionality:

* _(Repository list coming soon. Stay tuned for updates!)_

## Building a jEAP Microservice Example

jEAP Microservice Examples use Apache Maven for building and may include multiple microservices and additional Maven 
modules within a single example. To build all microservices and additional modules in an example, navigate to the
example's root directory and run the Maven Wrapper script as shown below. This will compile all microservices and
additional modules and install them to your local Maven repository:

```shell
./mvnw install
```

Note that jEAP microservice examples may require specific build prerequisites, such as a particular Java version.
Always consult the example repository's `README.md` or `pom.xml` for detailed build instructions and requirements.

## Running a jEAP Microservice Example

Before running a microservice, you will typically need to start the required services (such as databases and message
brokers) using the Docker Compose file located in the `./docker` directory. Navigate to this directory and execute the
following command:

```shell
docker-compose up
```

Each jEAP microservice example provides a `README.md` with detailed instructions for running its microservices. In most
cases, you can start a microservice by navigating to its directory and running the following command:

```shell
./mvnw spring-boot:run
```
Refer to a specific example's `README.md` for any additional configuration or setup required to run the microservices.

## Reporting Security Vulnerabilities

If you would like to report a potential security issue in a JME repository, please follow the procedure described in
[SECURITY.md](./SECURITY.md).

## External contributions cannot be accepted currently

At this point in time, JME is released as open source software based on the
[EMBAG](https://www.fedlex.admin.ch/eli/cc/2023/682/de) law.

We do not currently accept external contributions. Please refrain from providing code changes or pull requests as we are
unable to accept them.

## Contact

For questions, please contact the maintainers at `jeap-community@bit.admin.ch`.

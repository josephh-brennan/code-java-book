# Core Java Project

This is a basic Maven-based Java project set up with JUnit 5 for testing.

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

## Building the Project

To build the project, run:

```bash
mvn clean install
```

## Running Tests

To run the tests:

```bash
mvn test
```

## Running the Application

To run the main class:

```bash
mvn exec:java -Dexec.mainClass="com.example.Main"
```

## Project Structure

- `src/main/java` - Source code files
- `src/test/java` - Test files
- `pom.xml` - Maven project configuration 
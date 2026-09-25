# EWUMate Lite

A lightweight JavaFX desktop companion application for EWUMate students, natively interacting with the Supabase backend. It features native Windows UI components, a scheduling system mapping makeup/cancelled events, and dashboard rules consistent with the mobile version.

## Setup & Requirements

- Java Development Kit (JDK) 17 or higher
- Apache Maven (for dependency resolution and building)

The project runs entirely on Maven, ensuring consistent execution across devices.

## Running the Application Locally

You can launch the application directly from source code using the JavaFX Maven plugin:

```bash
mvn clean javafx:run
```

## Compiling for Distribution

To compile the application into a standalone shaded executable JAR (bundling dependencies like PostgreSQL, JSON handling, and JavaFX SDK):

```bash
mvn clean package -DskipTests
```

The output will be available in `target/` as:

`EwuMateLite-1.0-SNAPSHOT.jar`

# Fit Logger

Fit Logger is a Spring Boot application for tracking fitness activities and logging workout data.

## Tech Stack

- **Spring Boot** (Java 17)
- **MongoDB** (NoSQL database)
- **Maven** (Build tool)

## Prerequisites
- Java 17 (OpenJDK 17)
- Maven 3.6+
- MongoDB (running locally or accessible remotely)
- Docker (for containerization and deployment)
- Swagger (API documentation available via Swagger UI)

## Getting Started
 
1. **Clone the repository:**
   ```bash
   git clone https://github.com/rashmijannu/fit-logger.git
   cd fit-logger
   ```

2. **Install dependencies and build:**
   ```bash
   mvn clean install
   ```

3. **Run the application:**
   ```bash
   mvn spring-boot:run
   ```
   Or run the jar directly:
   ```bash
   java -jar target/fit-logger-0.0.1-SNAPSHOT.jar
   ```

## Configuration
Edit `src/main/resources/application.properties` to customize application settings, including MongoDB connection details.

## Testing
Run tests with:
```bash
mvn test
```

## Troubleshooting
- Ensure you are using Java 17. Run `java -version` to check.
- If you see `release version 17 not supported`, update your Java version.
- Make sure MongoDB is running and accessible.

## License
MIT


# Codetickets

Project based on the course "Java e Spring Realizando processamento em lote com Spring Batch Java" - Alura

## Description

Codetickets is a sample application that processes CSV files containing fictitious import tickets concert data, using the Spring Batch framework to orchestrate jobs, steps, and data reading/writing.

## Project Structure
- `src/main/java/br/com/alura/codetickets/` - Main source code
- `src/main/resources/` - Configuration files and resources
- `files/dados.csv` - Example data file
- `imported-files/` - Folder for imported files

## Configuration
- Database and Spring Batch settings are in `src/main/resources/application.properties`.
- The project can be run with Docker Compose, as defined in the `docker-compose.yml` file.

## How to Run
1. Make sure you have Java 17+ and Maven installed.
2. Run the command:
   ```sh
   ./mvnw spring-boot:run
   ```
   or, on Windows:
   ```cmd
   mvnw.cmd spring-boot:run
   ```
3. The batch processing will start according to the Spring Batch configuration.

## About
This is a study project based on Alura's Spring Batch courses.

---

**Author:** walyson-scarazzati

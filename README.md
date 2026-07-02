# Nova Bank

JavaFX-based banking management system with MySQL backend.

## Tech Stack
- Java 11, JavaFX, JDBC
- MySQL
- Maven

## Architecture
3-layer design: DAO → Service → GUI

## Schema
12 normalized tables with CHECK constraints, FOREIGN KEYs, and cascading deletes

## Key Features
- Role-based access (Client/Staff/Admin)
- Fund transfers with validation and manual rollback
- Loan processing and approval workflow
- Admin analytics and reporting

## Run
```bash
mvn clean install
mvn javafx:run

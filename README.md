# 221028-DevOps-Lab-Exam
## Services Overview

### Database Service (PostgreSQL)
The **Database Service** uses **PostgreSQL** to manage data storage and retrieval. It is responsible for handling all persistent data needs for the application, ensuring reliable and structured data storage.

### Cache Service (Redis)
The **Cache Service** uses **Redis** to store frequently accessed data in memory. This improves application performance by reducing database load, enabling faster access to commonly used data.

## Running Services with Docker Compose

To run both services using Docker Compose, follow these steps:

1. Ensure Docker and Docker Compose are installed on your system.
2. Clone this repository and navigate to the project directory:

   ```bash
   git clone https://github.com/your-username/221028-DevOps-Lab-Exam.git
   cd 221028-DevOps-Lab-Exam
   
## Running Services with Docker Compose

To run both services, execute:
```bash
docker-compose up -d
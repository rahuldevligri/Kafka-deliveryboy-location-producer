# deliveryboy-location-producer

This project is a Spring-based Kafka producer application that simulates the delivery boy's location updates and sends them to a Kafka topic. The application provides an endpoint (`/location/update`) to trigger location updates, which are then sent to the Kafka broker.

## Technologies Used
- **Spring Boot**: To build and configure the application.
- **Apache Kafka**: For message streaming and topic-based messaging.
- **Spring Kafka**: Spring integration for Kafka.
- **SLF4J**: For logging messages.
- **Maven**: For managing dependencies.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/deliveryboy-location-producer.git

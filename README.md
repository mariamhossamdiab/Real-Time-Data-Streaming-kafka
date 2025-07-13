# Real-Time CDC Streaming Pipeline with Kafka, Debezium, and Clickhouse
This project demonstrates a real-time Change Data Capture (CDC) streaming pipeline that captures changes from a postgress source
database using Debezium, processes them through Apache Kafka, and kafka sink the data into clickhouse using the Kafka clickhouse Connector.
![pipline](https://github.com/user-attachments/assets/c5d5cff9-7849-4d1b-8177-6f73204bae21)

 * Build a real-time Change Data Capture (CDC) pipeline using Apache Kafka Connect as the integration layer.

 * Use the Debezium PostgreSQL connector to capture real-time changes from a PostgreSQL source database.

 * Debezium streams all change events into Kafka topics in a structured format.

 * Deploy the Kafka-ClickHouse connector to consume messages from Kafka topics and write them to ClickHouse.
   
# kafka topics

<img width="1920" height="1080" alt="Screenshot from 2025-07-13 00-42-39" src="https://github.com/user-attachments/assets/e9e318cb-cc11-48ea-b11e-0c248b06124b" />

<img width="1920" height="1080" alt="Screenshot from 2025-07-13 00-42-56" src="https://github.com/user-attachments/assets/974237be-3201-4df6-a600-afc5f162b798" />

# clickhouse warehouse

<img width="1920" height="1080" alt="Screenshot from 2025-07-13 00-10-22" src="https://github.com/user-attachments/assets/6dbe2b66-7816-4e64-8ea1-bf0bccdd4045" />

<img width="1920" height="1080" alt="Screenshot from 2025-07-13 00-41-13" src="https://github.com/user-attachments/assets/b697388c-6d72-492c-b324-d4868f2b23d0" />

<img width="1920" height="1080" alt="Screenshot from 2025-07-13 00-41-55" src="https://github.com/user-attachments/assets/2a3691c3-fa83-4cf9-b261-e34a66f08477" />
# docker containers
<img width="403" height="453" alt="Screenshot from 2025-07-13 00-33-55" src="https://github.com/user-attachments/assets/3bb00bcf-f266-487f-b93f-99590cbac7d6" />

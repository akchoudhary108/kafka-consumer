# Kafka Consumer using Spring Boot
![image](https://github.com/user-attachments/assets/74b305a1-0e9c-4eb2-9411-80675dd303b3)
_____________________________________________________________________________________________________
##  Required Dependency
> Spring for Apache Kafka
> ![image](https://github.com/user-attachments/assets/31df9019-0b9a-4dbc-b94a-e479cbe609d0)
_____________________________________________________________________________________________________
##  To consume messages from Kafka topics with Spring Boot

> ### 1. Run the Apache Zookeeper server
> #### C:\kafka>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
> ![image](https://github.com/user-attachments/assets/f8161510-d738-4adf-a05a-ed61f3fe4e78)
> ### 2. Run the Apache Kafka  server
> #### C:\kafka>.\bin\windows\kafka-server-start.bat .\config\server.properties
> ![image](https://github.com/user-attachments/assets/be02536b-1c7c-4585-b562-d9521f18b670)
> ### 3. Send the messages from Kafka Topics
> #### C:\kafka>.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic NewTopic
> ![image](https://github.com/user-attachments/assets/62363342-5cb7-41df-a9d2-8235b29f4a26)

_____________________________________________________________________________________________________

## Final Output
> ![image](https://github.com/user-attachments/assets/a9e573db-e780-4bc7-a16e-0f793e32fc8d)
> ![image](https://github.com/user-attachments/assets/7f55548d-a6c0-4854-bc0c-4eb9e75235c1)


# !! Thank You !!


# Streaming Kafka python  

Step 1: Install Kafka and Dependencies
•	Open a terminal on our Ubuntu machine.
•	Install Java Development Kit (JDK)
sudo apt update
sudo apt install default-jdk

Download Kafka from the Apache Kafka website:
wget https://downloads.apache.org/kafka/2.13-3.4.0.tgz/kafka_2.13-3.4.0.tgz
Extract the downloaded archive:
tar -xzf kafka_2.13-3.4.0.tgz
Move to the Kafka directory:
cd kafka_2.13-3.4.0


Step 2: Start ZooKeeper
bin/zookeeper-server-start.sh config/zookeeper.properties

![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/3a820b2d-3e4c-4d0e-ad48-864e0d27a982)



Step 3: Start Kafka Broker
bin/kafka-server-start.sh config/server.properties

![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/58bf55d3-7164-4c4c-9330-ada9eeda347d)


Step 4: Create a Kafka Topic
bin/kafka-topics.sh --create --topic test_topic --bootstrap-server localhost:9092 --partitions 1 --replication-factor 1


![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/f70b69fc-891f-4d57-b95d-f22e7a190ddc)






Step 5: Install Kafka Python Library


![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/895d77c9-2997-47bd-8edd-9dd809102ee9)



Step 6: Write Consumer Code

![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/b23033ef-2b14-444d-90e9-33702c93d38f)



Step 7: Write Producer Code

![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/4b2c98ff-091e-44bd-a485-1315310a505c)



Step 8: Run the Consumer and Producer

![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/e6136573-eb3b-49be-93db-7acdc3b1122b)
![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/49dc7c37-76d7-426f-98fb-779de08c6e7e)
![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/79563ec0-1d7d-4972-9a51-9db985aede4d)
![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/c32908d0-5e1c-4424-9df2-8b6e81e8c6d3)
![image](https://github.com/omara2001/Kafka-python-read-data-by-producer-and-consumer/assets/66154169/f65b8f7b-3030-4d5a-bb46-b90cdbabbfc3)





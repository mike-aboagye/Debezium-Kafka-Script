
![debezium image](https://www.paradigmadigital.com/wp-content/uploads/2017/06/debezium-1.png)
![Apache Kafka](https://icon-icons.com/icon/apache-kafka/138937)


## Purpose of bash script:  

This bash script contains three function as shown below:   

**extract_function** : This function extracts the archived connector file downloaded from [Debezium](https://debezium.io/documentation/reference/1.6/install.html) website. It extracts the archived file via the current/session user. So the current user needs to be a privileged user.  


**auth_user** : This function checks if a user is a privileged/root user or not. If the user executing the script is not a root user or a user without privileged capabilities, then the script does not execute. 

**attach_plugin** : This function attaches the debezium connector to a kafka broker and restarts kafka broker.

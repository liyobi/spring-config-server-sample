# spring-config-server-sample
Spring Cloud Config Server & Client Test


#config server url
- http://localhost:8888/config-server-client/local

#config server client  url
- http://localhost:9000/test

#config test
1.config-server-client-*.yml 
 - Property Value Change
 - githup push
 
2.http://localhost:9000/test
 -  old value only

3.http://localhost:9000//actuator/refresh    using POST method
 - To reflect the new value, refresh the configuration

4.http://localhost:9000/test
 - You can see the changed value

# CS520 Final Project : **Campus Job Board**
## Team Members: Lokesh Tangella, Vauynandhan Reddy, Venkata Sai Phanindra Pamidimukkala

Please clone this repository using *git clone --recurse-submodules https://github.com/PVSPHANINDRA/CampusJobBoard.git* command. This pulls all the submodules as well.


The high level architecture diagram is as shown below: 

![image](https://user-images.githubusercontent.com/30817222/208218120-874c4bbd-ee12-4c74-a9e0-2010f7f38258.png)


The Project contains 4 Backend microservices and a frontend service. 

This Repository contains 5 submodules one each for a microservice of this project. 

<ins>Each of the Microservice has its own run instructions, Please check the Readme.md file of each of the submodule and follow the instructions accordingly to run the corresponding microservice.</ins>

The frontend application binds to the port dynamically whichever is free whereas the other Microservice need a specific port to run.
Please make sure the below ports are free so that the entire application can run seamlessly.
* 8080
* 8081
* 8000
* 8060

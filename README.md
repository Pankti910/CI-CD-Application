# CI-CD-Application

## Purpose of this repo

This project is meant to be helpful in **Devlopment operations** (DevOps) for Integreation and Deployment of an application.

## Features

* Fetching source code from Remote Source/Version control (currently Github only)
* Store code on physical disk
* Build the code
  * Event Based
  * Timer Based
* Deployment on the machine

## Development Stack

* Enterprise Java (Java Beans in back-end)
* JAX-RS (RESTful client)
* JSF (front-end)
* JGit (Github API)
* SocketXP (webhook request tunneling software)

## Build Commands Format

###### ('stag1'){command 1}
###### ('stag2'){command 2}
###### ...
###### ('stagN'){command N}

### For example (Java programme)
###### ('Compile'){javac \<name\>.java}
###### ('run'){java \<name\>}



![Home Page](https://github.com/PoojanSmart/CI-CD-Application/blob/main/CICDApp/imgs/home.png)

## Authentication
* Global Roles-Application Level Rights
* Local Roles-Project Level Rights
## Request serves base on rights


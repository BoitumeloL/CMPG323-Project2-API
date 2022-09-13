# CMPG323-Project2-API
This repository is for Project 2 which is making an API that will manage the IoT devices

## API DESCRIPTION
This API will be used as a system to keep track of IoT devices in an organisation. It will allow the users to record and store data about these devices.

## METHODS IN API (Endpoints)
The database is scaffolded and we have 3 controllers that represent the 3 tables (Category, Devices and zones) in the database. These controllers have the methods: GET, POST, PUT and DELETE.
The methods are described below:
### GET:
Retrive entries from the database

### POST:
Insert entries into the database

### PUT:
Update the entries in the database

### DELETE:
Remove an existing entry in the database

These are the endpoints created in the API and will allow the user to retrieve specific data about a device, insert data, update the data of an existing device and or remove the device along with its related information from the database.

## API MANAGEMENT
This project also includes API management, will help secure the API and reduce the risk of potential attacks by not directly exposing it to microservices

![API MANAGEMENT](https://user-images.githubusercontent.com/110591480/189844938-ac407916-2455-4792-9288-f69fa7cb48ff.png)
![image](https://user-images.githubusercontent.com/110591480/189845191-e978ebbb-8455-4b9c-b8af-5078690d239e.png)



## STORAGE OF SENSITIVE INFORMATION AND FILES THAT GIT SHOULD NOT TRACK
A .gitignore file will be used to ignore files that need not be tracked by git, such files are (and are not limited to) connection.udl, .vs, bin, etc

##IMPLEMENTATION OF SECURITY 

## BRANCHING STRATEGY
The git workflow branching strategy is used as mentioned in CMPG323- Overview.
All of the work, such as develeoping the API and adding the required features is done in the development branch and then pushed into the main branched (ready for production - in this case - the final project)

##REFERENCES 

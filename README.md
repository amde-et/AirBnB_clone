### 0x00.AirBnB Clone - The Console

## Functionalities of this command interpreter:
* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc...
* Do operations on objects (count, compute stats, etc...)
* Update attributes of an object
* Destroy an object
## Environment
This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3)

## Installation
* Clone this repository: git clone "https://github.com/kiya3300/AirBnB_clone.git"
* Access AirBnb directory: cd AirBnB_clone
* Run hbnb(interactively): ./console and enter command
* Run hbnb(non-interactively): echo "<command>" | ./console.py

## Description
 This team project is part of alx  Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone.
 This first step consists of a custom command-line interface for data management,and the base classes for the storage of this data.
## Console and Command Usage
The console is a Unix shell-like command line user interface provided by the python CmdModule It prints a prompt and waits for the user for input, for our project we used (hbnb)

| Command | Example   |
| ------- | --------- |
|Display commands help| (hbnb) help <command>             
|Create object (prints its id)	      | (hbnb) create <class>)|
|Destroy object	                      | (hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)                  |
|Show object                          | (hbnb) show <class> <id> or (hbnb) <class>.show(<id>)                        |
|Show "all" objects or instances class|	(hbnb) all or (hbnb) all <class>                                             |
|Run console	                      | ./console.py                                                                 |
|Quit console                         | (hbnb)quit                                                                   |

Help command example


(hbnb) help

## Documented commands (type help <topic>):
EOF  all  count  create  destroy  help  quit  show  update
## Class Models Used

|  File	            |  Description  |   Attributes  |
|-----------------  | ------------- | ------------  |
| base_model.py     |The BaseModel class is inherited by other |id, created_at, updated_at |
|user.py            |User class stores user-related info          |email, password, first_name, last_name |
|city.py	    |City class stores city-specific information  |state_id, name |
|state.py	    |State class stores state-specific information|	name                                            |
|                   |                                             |                                                     |
|place.py	    |Place class stores full detailed outline     |                                                     |
|                   |of rental unit features	                  |city_id, user_id, name, description,number_rooms,    |
|                   |                                             |number_rooms, number_bathrooms, max_guest,           |
|                   |                                             |price_by_night, latitude, longitude, amenity_ids     |
|review.py          |Review class stores previous customer reviews|place_id, user_id, text                              |                  
|                   |and opinions                                 |                                                     |
|amenity.py         |Amenity class stores highlighted amenity     | name                                                |
|                   |information                                  |                                                     |

## Tests

All the code is tested with the unittest module. The test for the classes are inthe`test_models folder`.
## Authors
* Abel Yitages - [Abel](https://github.com/kiya3300)
* Mehamud Salih - [Mehamud](https://github.com/Mehamud-salih)
 
 
 

# AirBnB_clone_v2     ------- HBNB
AirBnB clone - MySQL  (Group project Python OOP Back-end SQL MySQL ORM SQLAlchemy)


![image](https://github.com/Michafolab/AirBnB_clone_v2/assets/117805721/ef9ab2f4-ec63-4bae-9f1a-a2df2e11c75f)


This is the console /command interpreter for the Holberton Airbnb clone project. The console can be used to store objects in and retrieve objects from a JSON.

**Supported classes:**
**BaseModel**


User


State


City


Amenity


Place


Review




**Commands:**


create - create an object


show - show an object (based on id)


destroy - destroy an object


all - show all objects, of one type or all types


quit/EOF - quit the console


help - see descriptions of commands


To start, navigate to the project folder and enter ./console.py in the shell.



**Create**
create <class name> Ex: create BaseModel



**Show**
show <class name> <object id> Ex: show User my_id



**Destroy**
destroy <class name> <object id> Ex: destroy Place my_place_id



**All**
all or all <class name> Ex: all or all State



**Quit**
quit or EOF



**Help**
help or help <command> Ex: help or help quit

Additionally, the console supports <class name>.<command>(<parameters>) syntax. Ex: City.show(my_city_id)

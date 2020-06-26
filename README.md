

# Foto-Grafi

#### 26/06/2020
#### By **Jorim Midumbi Okong'o Opondo**

## Description
This is a Django application for a personal photos gallery that allows a user to upload images for others to see and be able to to share by copying the image link.

You can view the site at:[Heroku](https://foto-grafi.herokuapp.com/)


## User Stories
* View different photos that interest them  
* Click a single image to expand it and view the details of that photo  
* Search for different categories   
* Copy a link to the photo to share with my friends.  
* View photos based on the location they were taken.  
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/JORIM1981/Foto-Grafi.git 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Foto-Grafi pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv venv - source venv/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations pictures 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  




## Technology used

* [Python3.8](https://www.python.org/)
* [Django3.0.7](https://docs.djangoproject.com/en/2.2/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [okongo.midumbi.opondo@gmail.com]

## License:

- _MIT License:_[LICENSE MIT](./LICENSE)

- Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**



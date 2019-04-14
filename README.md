## Contains the project for our submission at Ultrahack

###### Includes the algorithm (Uses nltk, gensim, PIL, moviepy and more)
###### Contains the django backend with djang_rest_framework deployed.


# Python 2.7 is required for this project.

## HOW TO SET UP THE PROJECT LOCALLY : 

###### cd to a favourable location to initialize your project and a virtual environment.
```shell
foo@bar:~$ virtualenv -p my_project
foo@bar:~$ source my_project/bin/activate
```
###### Clone the repostory.
```shell
foo@bar:~$ git clone https://github.com/keshavvinayak01/hackDelhi
```

###### Install all the requirements
```shell
foo@bar:~$ cd hackDelhi
foo@bar:~/hackDelhi$ pip install -r requirements.txt
```

###### move to the project folder and initialize the database
```shell
foo@bar:~/hackDelhi$ cd backend/hackdelhi
foo@bar:~/hackDelhi/backend/hackdelhi$ pip manage.py migrate
foo@bar:~/hackDelhi/backend/hackdelhi$ pip manage.py makemigrations
```

###### runserver.
```shell
foo@bar:~/hackDelhi/backend/hackdelhi$ pip manage.py runserver
```


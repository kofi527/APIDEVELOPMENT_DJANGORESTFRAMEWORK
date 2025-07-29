### DJANGORESTAPIDEV

![django and python](https://github.com/user-attachments/assets/03c4c47d-69d2-41ff-88b4-d83710ee43f5)


 ### DJANGO AND PYTHON

 STEPS TO PROJECT EXECUTION
 
1.	Create a virtual environment to with the formula “virtualenv env” in the selected project folder
2.	API RESTFRAMEWORK IS AN APPLICATION THAT WORKS IN DJANGO  that has the ability of converting it into an API
3.	We will be creating a model that saves movie details
•	Service oriented architecture 
•	Django and Django restframework installation within our virtual environment = it is an app the runs on top of Django that has the ability of converting your application into an API

1.  Hey , we start of the project by creating a virtual environment within our project folder at the command line, note to use pip for windows and sudo for mac users
   ![0  install virtualenvironmet with the pip install command](https://github.com/user-attachments/assets/ad2dd075-d7af-4871-816e-b8c88df8c23f)

2. The Virtual environment is activated using the following command    Scripts\activate.bat.
   
![2  activating virtual environment with scripts](https://github.com/user-attachments/assets/894b1b6c-2d9a-4a4c-8363-6e7ef0dabd11)

3. The next step is to install django into your project directory.

 ![3  install django in your project folder](https://github.com/user-attachments/assets/56416e7e-bc33-4973-b3be-7df14ac927db)

4. Your next step is to install Djangorestframework

   ![4  install djangorestframework](https://github.com/user-attachments/assets/a44835bf-bda3-4c76-85d7-64e8c02f4375)

5. Create an admin project with the command
   "django-admin startproject mysite"
   "django-admin startapp my app"

   ![5  cret the start project, cd into mysite and create a django app in it](https://github.com/user-attachments/assets/06da29be-969b-4fbe-82e7-38b66d5c83f5)

6. Hey We create our firs Model in Visual Studio code that gives details of the descriptions.
   
   ![5  model description](https://github.com/user-attachments/assets/022203eb-1ea6-4661-a0a2-d8a7e41a144c)

7.   We Navigate to the settings.py file and add myapps to the settings.py file witch is located within your project directory.

    ![6  Navigate to the settings py file and add myapps to the installed apps this is part of migrations](https://github.com/user-attachments/assets/f3de50c9-6718-4b82-a5ea-97253fc1a756)

8. Make migrations with the command manage.py to make migrations to the model being created.

   ![7 with the command python manage py makemigrations](https://github.com/user-attachments/assets/63933d00-af74-4cd2-8833-104d6bd9ea8b)

9. we make migrations with manage.py at our command line
    
    ![8  python manage py migrate](https://github.com/user-attachments/assets/36e9c5e8-a296-4579-aa6a-5ef5541f3999)

10. A Superuesr have been created successfullly
    
  ![9  Superuser created successfully](https://github.com/user-attachments/assets/d403615e-4ab8-419a-a2a4-3fcbf602b12a)

11. Now we run server that generates the local host for the commandline (python manage.py runserver )

![10 now we runserver with python manage py runserver](https://github.com/user-attachments/assets/30f5e561-6bc7-4129-923a-29d32cfe2502)

12. try and identify the username used for the migrations

  ![10 0 try and identify the username you used for the migrations](https://github.com/user-attachments/assets/73d9e5e0-f097-4fb8-8ef9-e9dd9c8a8ee1)

13.   Navigate to the admin page and enter passward and username.

   ![11  navigate to  admin and enter the password and username](https://github.com/user-attachments/assets/22b8da1c-1e23-461a-8adc-1254893d8371)

14. Navigate and write the command python.py 
   ![7 with the command python manage py makemigrations](https://github.com/user-attachments/assets/b2032d5e-ddc2-48f3-b9aa-253b8e50cc96)

 15.    Sueperuser has been created successfully

    ![9  Superuser created successfully](https://github.com/user-attachments/assets/c40a16a8-acbc-4911-ba72-0d57ec3ccb8e)

16. it is important to always identify the various usernames used for the following migrations.
    ![10 0 try and identify the username you used for the migrations](https://github.com/user-attachments/assets/f306925e-4be9-4744-b7dd-40bdd9ad2581)

17. we navigate to the admin panel and enter the password usernames
    ![11  navigate to  admin and enter the password and username](https://github.com/user-attachments/assets/55b224bd-27ce-4016-b3f6-4814271d21b8)

18. The administraiton page for your application has been setup

    ![12  welcome to the admi page of my application](https://github.com/user-attachments/assets/fe0a828e-57ce-4b8e-ac1c-6a7b888aea62)


 18.   the model is now registered in the admi.py

     ![14  Registration of model in admi py 1](https://github.com/user-attachments/assets/eaf954fb-0c64-4b9d-ac2e-28e1c62169d7)


19. Movie model when aded is save as an object
   ![16  when a movie is added it is saved as an object](https://github.com/user-attachments/assets/68619957-6c83-44a9-9da6-9516ef9f1e38)

20. Initializing display name of your movie in the admi directory
   ![17  initializing this code displays the name of your movie in the admi direcotry  return self](https://github.com/user-attachments/assets/d95c1f42-62d7-467c-8937-ce68f7619b4c)


21. Rest Framework is added to our installed existing applications
    ![19  we add the rest framework to our installed apps at the settings py diretory](https://github.com/user-attachments/assets/47099713-cff5-4a34-998f-560e892462fe)

22. New api is created within our environment variables
![20  then create a new api  older within our environmenta variables with the name movie api](https://github.com/user-attachments/assets/357a0f98-cde6-412a-a89a-2c68b446484d)


# set up to run project on local machine
* Firstly if django is not insatalled into machine then download latest version of django.
* Download zip file and extraxt it.
* Open command promot and go into the project directory.
* Run this coomand:-python manage.py runserver.
* A URL will be showned,copy paste that URL in browser.
* In our project only superuser can add resturant.so for adding an resturant first you need to create superuser and then go to Django administration using url http://127.0.0.1:8000/admin and then add owner of resturant in owner model.after creating a onwer you can login in resturant(using owner's credantinal) using url http://127.0.0.1:8000/owner_login/
* For creating superuser go into the project directory and run this command "python manage.py createsuperuser" and after that fill the requested credantials and by using these credantials you can login in Django administration.
* If you still facing some difficulity during restaurant owner login,then use these credantials for owner login "username:-rohit password:-1234". 
* Now you can explore project.



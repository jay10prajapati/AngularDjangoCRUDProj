# AngularDjangoCRUDProj
Angular 10 with Django, implemented CRUD operation. Angular-Django-boilerplate


## FrontEnd Setup
1. Install Angular latest version
  - https://www.javatpoint.com/angular-8-installation
2. Get current project on your local system using git.
    - git clone "project_name"</b>
3. go to project folder and run following cmd.
    - npm install
4. Check if is setup properly by following cmd.
    - ng serve
      - Once above cmd works/compiles successfully check on browser: http://localhost:4200 


## Backend Setup
1. install mysql using following reference link on windows 10
  - https://www.onlinetutorialspoint.com/mysql/install-mysql-on-windows-10-step-by-step.html
    
    - default mysql connection setting for this project
      - DATABASES = {
            'default': {
                'ENGINE': 'django.db.backends.mysql',
                'NAME': 'saranglib',
                'USER': 'root',
                'PASSWORD': '1234',
                'HOST': '127.0.0.1',
                'PORT': '3306',
            }
        }
2. install python using following reference link on windows 10
    - https://phoenixnap.com/kb/how-to-install-python-3-windows
3. go to "AngularDjangoCRUDProj\restApisMySQL" location in cmd line and run following cmd to install all requierments using pip.
    - pip install -r requirements.txt
4. Check if is setup properly by following cmd (Location shoule be:"AngularDjangoCRUDProj\restApisMySQL").
    -  python manage.py runserver 8080
        - once above cmd works/compiles successfully check on browser (result should be emplty list []): http://localhost:8080/api/tutorials   

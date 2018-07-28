# angular6
I have develop basic angular 6 demo.

Following some command to setup environment for angular 6.


Install

sudo apt-get update
sudo apt-get install nodejs

sudo apt-get install npm


nodejs -v

node -v

Inastall

npm install -g @angular/cli

ng help

Generating and serving an Angular project via a development server
ng new PROJECT-NAME
cd PROJECT-NAME
ng serve

Run Angular CLI Project
ng serve --host 0.0.0.0 --port 4201


Generating Components, Directives, Pipes and Services
You can use the ng generate (or just ng g) command to generate Angular components:

ng generate component my-new-component
ng g component my-new-component # using the alias 
 
# components support relative path generation 
# if in the directory src/app/feature/ and you run 
ng g component new-cmp

# your component will be generated in src/app/feature/new-cmp 
# but if you were to run 
ng g component ./newer-cmp

# your component will be generated in src/app/newer-cmp 
# if in the directory src/app you can also run 
ng g component feature/new-cmp

# and your component will be generated in src/app/feature/new-cmp 


Create New Project
ng new ng6_nik --style=scss --routing


Run 
ng serve -o


ng generate service data

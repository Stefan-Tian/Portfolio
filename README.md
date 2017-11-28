### Step one
- rails new `project name` -T --database=postgresql(-T means no tests)
- rails s (to start the server)
- rails db:create 
- rails db:migrate
- rails g scaffold Blog title:string body:text
- rails db:migrate
- delete the scaffold.scss in app/assets/stylesheets
- rails g controller Pages home about contact
- rails g model Skill title:string percent_utilized:integer
- rails g resource Portfolio title:string subtitle:string body:text `main_page`:text `thumb_image`:text
_check rails -j= to add angular/react_
_I can interact with database through rails -c_
*rails new my_api --api (to not include frontend)*

- git push origin controller-generator
###MVC - Model - View - Controller


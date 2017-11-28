### Step one
- rails new `project name` -T --database=postgresql(-T means no tests)
- rails s (to start the server)
- rails db:create 
- rails db:migrate
- rails g scaffold Blog title:string body:text
- rails db:migrate
- delete the scaffold.scss in app/assets/stylesheets
* check rails -j= to add angular/react
* rails new my_api --api (to not include frontend)
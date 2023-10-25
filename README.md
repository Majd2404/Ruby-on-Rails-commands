##In Ruby on Rails, there are several commonly used commands that developers use throughout the development lifecycle. 
Here are some of the most frequently used Rails commands:

Create a New Rails Application:

rails new app_name

Generate a Resource (Model, View, and Controller):

rails generate scaffold ModelName attribute1:type attribute2:type

Database Migrations:

rails db:migrate

Rollback Database Migrations:

rails db:rollback

Generate a Controller:

rails generate controller ControllerName


Starts the Rails server, which listens for incoming HTTP requests and generates responses:

rails server 

Generates new code for models, controllers, views, and other Rails components:
rails generate

Starts the Rails console, which is a REPL (read-eval-print loop) that allows you to interact with the Rails application directly:
rails console

Runs all of the application's automated tests.

rails test

Generate a Migration for Adding/Removing Columns:

rails generate migration AddColumnToTableName column_name:datatype
rails generate migration RemoveColumnFromTableName column_name:datatype

Update Bundler:

bundle update

Install Dependencies:

bundle install

Generate a Secret Key:

rails secret

Database Seed:

rails db:seed

Show Routes:

rails routes

Destroy a Resource:

rails destroy scaffold ModelName

Run a Task:

rails runner 'SomeModel.some_method'

Update Rails Version:

bundle update rails

command will change the database adapter for your Rails application to PostgreSQL. It will do this by updating your database.yml file and adding the pg gem to your Gemfile. It will also remove the sqlite gem from your Gemfile if it is present.

rails db:system:change --to=postgresql 

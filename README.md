# Ruby on Rails Commonly Used Commands

In Ruby on Rails, there are several commonly used commands that developers use throughout the development lifecycle. Here are some of the most frequently used Rails commands:

### Create a New Rails Application:

```bash
rails new app_name
```


### Generate a Resource (Model, View, and Controller):

```bash
rails generate scaffold ModelName attribute1:type attribute2:type
```
### Database Migrations:

```bash
rails db:migrate
```
### Rollback Database Migrations:

```bash
rails db:rollback
```
### Generate a Controller:

```bash
rails generate controller ControllerName
```

### Starts the Rails server, which listens for incoming HTTP requests and generates responses:

```bash
rails server 
```
### Ruby on Rails provides a wide range of commands to assist developers throughout the development lifecycle. Below is a comprehensive list of commonly used commands:

```bash
rails generate
```
Starts the Rails console, which is a REPL (read-eval-print loop) that allows you to interact with the Rails application directly:

```bash
rails console
```
### Runs all of the application's automated tests.

```bash
rails test
```
### Generate a Migration for Adding/Removing Columns:

```bash
rails generate migration AddColumnToTableName column_name:datatype
rails generate migration RemoveColumnFromTableName column_name:datatype
```
### Update Bundler:

```bash
bundle update

### Install Dependencies:

```bash
bundle install
```
### Generate a Secret Key:

```bash
rails secret
```
### Database Seed:

```bash
rails db:seed
```
### Show Routes:

```bash
rails routes
```
### Destroy a Resource:

```bash
rails destroy scaffold ModelName
```
### Run a Task:

```bash
rails runner 'SomeModel.some_method'
```
### Update Rails Version:

```bash
bundle update rails
```
### Command will change the database adapter for your Rails application to PostgreSQL. It will do this by updating your database.yml file and adding the pg gem to your Gemfile. It will also remove the sqlite gem from your Gemfile if it is present.

```bash
rails db:system:change --to=postgresql 
```

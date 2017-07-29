Welcome to Task Management App!
===================

### Setting up the development environment

1. Get the code. Cloning this git repo is probably easiest way:

  ```bash
  git@github.com:manishnagdewani96170/task_mgmt_app.git
  ```

1. Navigate to the Taskapp project root directory.

  ```bash
  cd taskapp
  ```

1. Install the required gems by running the following command in the project root directory:

  ```bash
  bundle install
  ```

1. Create a database.yml file by copying the example database configuration:

  ```bash
  cp config/database.example.yml config/database.yml
  ```

1. Add your database configuration details to `config/database.yml`. You will probably only need to fill in the password for the database(s).

1. Create the database:

  ```bash
  bundle exec rake db:create
  ```
### Instructions for application after setup

1. Create an user if you did not sign-up till yet using following link:

  ```bash
  http://localhost:3000/users/sign_up
  ```
1. After sign-up you would redirect to task index page where you can delete, create and show task and if yo don't have any task you can  create task using below link:

  ```bash
  http://localhost:3000/tasks/new
  ```
1. After create task on new page you can edit task detail on that page.

1. If you want edit profile you can use below link:

  ```bash
  http://localhost:3000/users/edit
  ```
1. If you want log-out you can use below link:

  ```bash
  http://localhost:3000/users/sign_out
  ```


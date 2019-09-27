# Task Manager Application

This is a web application created by following the Rails tutorial found [here](https://github.com/turingschool-examples/task_manager_rails/blob/master/README.md). This application allows the user to view a list of current tasks, create new tasks, edit existing tasks, and delete tasks. I referenced Traversy Media's [Ruby on Rails Tutorial](https://www.youtube.com/watch?v=pPy0GQJLZUM) for the addition of Bootstrap CSS and functionality where the user is unable to create blank tasks.

## Setup

To get this repository cloned down and set up locally:

```
$ git clone git@github.com:johnktravers/task_manager.git
$ cd task_manager
$ bundle install
$ rake db:{drop,create,migrate}
```

## Running Locally

After completing the setup, you can now start your server with `$ rails s` and navigate to [http://localhost:3000/](http://localhost:3000/)


# Full-Stack-App-1

## Initial steps to setup the project.

1. Create a Backend Folder

2. Creating a React Application using terminal

This will create a new Frontend folder for us

```bash
npm create vite@latest frontend -- --template react
```

To install the necessary packages for our react application

```bash
cd frontend
```

```bash
npm install
```

2. Creating the backend

In this case it is going to be a CRUD Backend

CRUD stands for CREATE, READ, UPDATE, DELETE

Lets go to the backend Folder

Now we are going to change directories

```bash
cd..
```

```bash
cd backend
```

Now we are going to install few different python modules which are required

```bash
pip3 install flask
```

This is an ORM Object Relational Mapping which allows us to connect to a SQL database and map the entries in SQL to a Python object so we can operate on our objects easily.

```bash
pip3 install flask-SQLAlchemy
```

This will allow us to have cross-origin requests

```bash
pip3 install flask-cors
```

4. Setting up files in backend

Now we are going to create different files in the backend

- main.py contains main roots or main endpoints
- models.py contains all of our database models
- config.py contains the main configuration of our application
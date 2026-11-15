# CS208 Full Stack Lab 12 - TODO List

- Name: Matthew England
- GitHub: https://github.com/matthewengland06
- Term: Fall 2026

## Project Description

This is a full-stack application for CS208 Lab 12, built with node.js, and uses 
Express for the backend and MariaDB/MySQL for the database. This web application
allows users to create a simple TODO list, with the ability to add tasks, mark 
them as complete, change their description, and delete them.

## Install the Database

To set up the database, run the `install_db.sh` script in the setup_scripts
directory. This script will install MariaDB and start the server running. You
only need to run this script once per Codespace.

```bash
./setup_scripts/install_db.sh
```

## Create the Database Tables

Create the initial tables by running the following command:

```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

## Install Dependencies

Install the required dependencies using npm:

```bash
npm install
```

## Run the Application

Start the application using the following command:

```bash
npm start
```

## Access the Application

On Codespaces, you can access the application by forwarding port 3000. Open the
forwarded port in your browser to view the application.
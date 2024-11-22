## FreeCodeCamp Relational Database Projects
This repository contains projects completed as part of the FreeCodeCamp Relational Database course. Each project showcases the use of PostgreSQL to manage and manipulate relational databases, with the help of Bash scripting for automation and interaction.
### Table of Contents
* Number Guessing Game
* Periodic Table
* Salon Appointment Scheduler
* World Cup Database

### Project Overview
### Number Guessing Game
A command-line game where a user guesses a secret number between 1 and 1000. User data and game statistics are stored in a PostgreSQL database. A Bash script facilitates user interaction, database queries, and game logic.
#### Features:
* Bash script handles game interaction.
* PostgreSQL database for storing user statistics.
* Feedback system guiding users if their guess is higher or lower.

### Periodic Table
A database project managed through Bash and SQL, which provides information about elements in the periodic table. SQL queries are executed using Bash scripts to fetch data based on user input.

#### Features:
* Store and retrieve detailed information for each element.
* Bash integration for interactive data retrieval.
* SQL scripts for managing chemical properties.

### Salon Appointment Scheduler
An appointment booking system for a salon, managed via Bash scripts that interact with a PostgreSQL database. It handles scheduling, customer management, and service offerings.

#### Features:
* Bash script-driven interaction for customers.
* PostgreSQL database stores customer and appointment data.
* User-friendly interface for booking, updating, and canceling appointments.

### World Cup Database
A database of historical World Cup data, with Bash scripts enabling data import, analysis, and complex queries. This project supports detailed insights on World Cup matches, teams, and statistics.

#### Features:
* Historical match data stored in a PostgreSQL database.
* Complex queries executed via Bash.
* Data analysis for winners, scores, and more.

### Technologies Used
* PostgreSQL: For database management.
* Bash: For scripting, automation, and SQL query execution.
* SQL: For database queries.
* Git: Version control for project management.

### How to Use
Running the Projects
* Number Guessing Game: Run the Bash script to start the game.
```
./number_guess.sh
```
The script will guide you through entering a username, guessing a number, and interacting with the database to save your game statistics.

* Periodic Table: Use the Bash script to query and interact with the periodic table data.
```
./periodic_table.sh
```
Follow the prompts to retrieve data about elements by atomic number or name.

* Salon Appointment Scheduler: Run the Bash script to manage appointments.
```
./salon.sh
```
The script allows customers to book, update, and cancel appointments, interacting with the database in real-time.

* World Cup Database: Use Bash scripts to import data, perform analysis, and retrieve insights.
```
./queries.sh
```
The script will execute SQL queries to analyze World Cup data, such as retrieving winners, match statistics, etc.


MYSQL - PHP - PYTHON - HTML - CSS - JS

1 - Introduction

This project is an exercise proposed in the Fullstack PHP module, where the teacher asked us to implement a web app with the following features:

    * implement a single-page web app (main backend: php) that can manage a generic sales list; each sale should record the following input:
        - name of the sales agent (required)
        - sale's date (required)
        - sale amount (required)
        - agent's commision (optional)
    * main features: insert, edit and delete a sale;
    * implement the database;
    * Implement a Python script to automatically calculate and insert 10% commissions where missing; it has to be indipendent from  the main php application;
    * with Javascript, implement a system that can update the browser page each 60 seconds and that can show the latest commission calculated and added by the python indipendent script;

2 - Stack description

The project use this stack technologies:
        - database: MySQL
        - backend: PHP + PYTHON
        - frontend: HTML/CSS/JS

3 - Installation

    1: create an empty folder, then with promtp command type "git clone https://github.com/SuperPorz/Fullstack_sales_manager.git";
    2: type "cd Fullstack_sales_manager" to ensure your prompts will run from inside the project folder;
    3: if composer package is installed, type "composer update" (otherwise install it first);
    4: create a DB on your MySQL DBMS by using the .sql script in sql folder;
    5: setup python environment: "py -m venv venv" (oppure usare 'python' al posto di 'py); 
    6: axtivate the virtual env: "venv\Scripts\activate";
    7: install dependencies: "pip install -r requirements.txt" ;
    8: activate the backend python app: "py api/python/provvigioni.py";
    9: activate your web server app like XAMPP or NGINX, also remeber to open and enable the DB connection;
    10: by opening the browser, go to "http://localhost/Fullstack_sales_manager/public/" and test the app.
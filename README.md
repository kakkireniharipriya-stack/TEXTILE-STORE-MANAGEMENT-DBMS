# TEXTILE-STORE-MANAGEMENT-DBMS
A DBMS project on Textile Store Management using StreamLit-Python for the frontend app and a ```mysql``` database as backend

## SYNOPSIS

A DBMS mini project on Textile Store Management System where we use streamlit python for front-end and ```mysql database``` as the backend. Apart from that we have multiple mysql queries based on :
- Joins, comprising natural, inner, outer, etc...
- Aggregation & Set operations
- Views
- Triggers & Cursors
- Procedures & Functions

## INSTRUCTIONS
- Install the latest version of ```XAMPP``` or any other mysql equivalent workspace
- Download the project, or enter the following in terminal ```if you have git installed``` :-
```bash 
git clone https://github.com/kakkireniharipriya-stack/TEXTILE-STORE-MANAGEMENT-DBMS.git

```
### DATABASE
- Start your ```XAMPP server``` → open ```phpMyAdmin```

Create a new database with any name

Select the database → click ```Import``` → upload the .sql file from the database folder

Update your database connection details in ```.streamlit/secrets.toml```

Refer to the ER-Diagrams folder for ```E-R diagrams``` and ```Relational Schema```

### FRONTEND
- Before entering the front-end, *(Python should be already installed)* *Install required Python packages:
```pip install streamlit
   pip install plotly```


- Navigate to your project’s frontend folder:
  ```bash 
  cd TEXTILE-STORE-MANAGEMENT-DBMS/SRC-APP
  ```
- Run the Streamlit app: Open a terminal here and run 
  ```bash 
  steamlit run app.py
  ```
- Make sure the ```database name``` in database.py matches the database you created in the Database Setup step.
- Hence, you have the entire project running successfully.
- For deeper understanding of the DBMS project, look into the ```REPORT PDF``` uploaded for visualizing the outputs for database and front-end.

#### ENJOY !!!

NOTE : 
For any queries/corrections, please feel free to mail:```kakkireniharipriya@gmail.com```

  

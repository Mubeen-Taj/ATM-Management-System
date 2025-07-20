# ATM-Management-System
STEP-1 --->Create a DataBase in SQL workbench

how to download SQLworkbench for creating a database for the project use this link
"https://youtu.be/v8i2NgiM5pE?si=FSpqz1PSCF9LEo3b"

"CREATE DATABASE atm_system;

USE atm_system;

CREATE TABLE accounts (
    account_number INT AUTO_INCREMENT PRIMARY KEY,
    user_name VARCHAR(100),
    balance DOUBLE,
    pin_hash VARCHAR(256)
);"------> use this code to create a Schema(make sure you run it as whole One time)




STEP-2 --->In ATMManager.java in line 11 replce the password 5426 in SQL workbench with the password you use to create a database in SQL workbench

STEP-3 --->to run Main java make sure JDK environment in VS CODE is set if not follow this link
    "https://youtu.be/4v6ua2_S5jI?si=0J-I61Ei6lNcVzXI"




STEP-4--->before runnig the main.java 
download JDBC driver for MySQL from this link "https://youtu.be/8aTpDfsYTNQ?si=oCJTXUz9saIERqYn"

after downloading use the command make sure path should be correct

java -cp ".;C:\Users\ADMIN\Downloads\mysql-connector-j-9.3.0\mysql-connector-j-9.3.0\mysql-connector-j-9.3.0.jar" Main.java use this command to run the code 



STEP-5---> to see the data run only this query in SQL workbench SELECT * FROM accounts;

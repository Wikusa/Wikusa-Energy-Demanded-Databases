[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6874734&assignment_repo_type=AssignmentRepo)

## CAB Energy Demand Project
- Provides a database that holds information of TCNJ building's and their enegry consumption. Webview component to query database. 
- Allows TCNJ sustainbility team a simple view to access TCNJ building data.
- Implements PostgreSQL and Python Flask. 

### Steps for Installation
1. Navigate to ```src/``` and run setup.sh
  ```./bash setup.sh```
2. Navigate to web_app/ and run the following commands:
  ```
  FLASK_APP=app.py
  flask run
  ```
3. Input the following url ```127.0.0.1:5000``` in any modern web-browser
4. "Enjoy this brilliant application we made" -Andrew M.

### Steps for Deleting the Database 
1. Navigate to ```src/``` and run: ```./bash drop.sh ```
2. Done. It's as easy as that.

## How to Use the Web App:

### Obtaining General Statistics for a Building
1. Select the 'Energy Data Retrieval' tab from the header
2. Select the desired building from the drop-down menu
3. Select the 'Basic Statistics' radio button
4. Click 'Submit' button

Returned Result:
![image](https://user-images.githubusercontent.com/44705804/166807060-9307e052-135d-444a-ae32-1fdc5a12a274.png)


### Obtaining Energy Demanded for a Building
1. Select the 'Energy Data Retrieval' tab from the header
2. Select the desired building from the drop-down menu
3. Select the 'Energy Demanded' radio button
4. Type in the desired date ranges for the 'Start date' and 'End date' text boxes (If an internal server error is displayed there are no values for the given range selected)
5. Click 'Submit' button

### Obtaining Energy Demanded by Seasonality

1. Select the 'Energy Data Retrieval' tab from the header
2. Select the desired building from the drop-down menu
3. Select the 'Seasonality Comparison' radio button
4. Select the desired year from the drop-down menu
5. Click 'Submit' button



<img src="https://github.com/marinamen/unit3_project/blob/main/images/66fda593be195cc.gif" width=90% height=90%>

*Fig.1 (https://es.pixilart.com/photo/coffee-shop-66fda593be195cc)*
 
   ༘⋆ ❅ ･:*:｡ ❆༄༄
   
   *coffee shop app*
   
   ༘⋆ ❅ ･:*:｡ ❆༄༄

# Unit 3: An Application for May's Coffee Shop


<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/cofeegif3.gif" width=25% height=25%>

*Fig.2*

## Criteria A: Planning

## Problem definition

*My client, a local coffee shop owner, is facing operational challenges three months into her business. She lacks standardized systems for menus and costs, leading to inconsistent drink recipes and customer wait times. Pricing irregularities arise from fluctuating ingredient costs, and manual revenue counting exposes her to financial inaccuracies and potential employee fraud. She's in dire need of a management platform to streamline her operations and safeguard her business.*



<img src="https://github.com/marinamen/unit3_project/blob/main/images/download.png" width=20% height=20%>

*Fig.3*


## Proposed Solution

 
I propose a Coffee Shop Management app to tackle my client's operational issues, featuring order tracking, inventory management, and secure employee logins. Developed using Pycharm, Python, and KivyMD for an intuitive interface, plus a SQL database for robust data handling, this solution aims to enhance efficiency, reduce errors, and secure transactions. Designed within a 6-week development period, the app will be assessed on its ability to streamline operations, ensuring a smoother customer experience and improved financial accuracy in the coffee shop.



## Rationale


I propose developing a comprehensive Coffee Shop Management application utilizing Python, KivyMD, and SQLite, tailored to address the unique challenges faced by my client's coffee shop business. This desktop application will feature a secure login and signup system for employees, enhancing accountability and reducing the risk of internal fraud. An intuitive order page will be implemented to streamline the recording of customer orders, ensuring accuracy and efficiency in service delivery.

Additionally, the application will include an inventory management module where ingredients can be meticulously tracked and purchased, addressing the issue of pricing irregularities due to fluctuating ingredient costs. This module will not only facilitate smoother operations but also contribute to more accurate financial management and cost control.

Python was chosen for its versatility and wide adoption in the tech industry, making it accessible for future development and maintenance. Its rich library ecosystem allows for efficient application development. 

<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/Python-logo-notext.svg.png" width=10% height=10%>


KivyMD, a user-friendly framework for creating responsive interfaces, will ensure the application is both visually appealing and functional, offering customizability and ease of use for the shop's staff.


<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/kivy%20logo.png" width=10% height=10%>

SQLite will serve as the database management system, chosen for its simplicity, reliability, and the ability to handle large volumes of data without the need for a separate server process. It is very straightforward and is easy to filter, insert, remove...etc. Convinient for a begginer UX app for Client.

<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/SQLiteLogo.svg.png" width=20% height=20%>


This solution is designed to revolutionize the management of my client's coffee shop, turning the current challenges into opportunities for growth and improved customer satisfaction. By integrating these technologies, the Coffee Shop Management application will provide a robust platform for order accuracy, inventory control, and financial transparency, setting the foundation for the business's future success.

## Approval from Client

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Screenshot%202024-03-11%20at%2004.05.08.png" width=90% height=90%>
Fig.4


## Success Criteria

1. The application has a sign up and login system, which aditionally distinguises between admin & employer.

2. The user can create orders realtime, while also being able to look and filter through previous orders.

3. The application allows for the user to create and log orders given from customers, and update their shipping status.

4. The application allows the admin to view the revenue and finances.

5. The application allows the user to track the store's inventory, such as viewing the amount left and buying more resources.

6. The application displays a Menu with recipe's of each drink.


# Criteria B: Design

## Wireframe Diagram

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Home.png" width=100% height=100%>

## System Diagram 
![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/SYSTEM%20DIAGRAM.png)



## UML Diagram 

![](https://github.com/marinamen/unit3_project/blob/main/images/Untitled%20(2).jpg)

The UML diagram for the object-oriented programming classes depicts the structure and interactions of the classes used in the application's development. It features two main superclass entities, MDApp and MDScreen, from which all other classes derive their methods and properties. This inheritance relationship is represented through the directional arrows on the diagram.


## ER Diagram 

![](https://github.com/marinamen/unit3_project/blob/main/images/Screenshot%202024-03-11%20at%2003.34.51.png)

 An entity relationship (ER) diagram is a type of flowchart that illustrates how “entities,” such as people, objects, or concepts relate to each other within a system. In this case my two databases, each employee can have many orders assigned to them but an order can only have 1 ownner hence the 1:m.

## Record of Tasks
| Task No | Planned Action                                                | Planned Outcome                                                                                                                 | Design cycle | Time Estimate | Completion date | Criterion |
|---------|---------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|--------------|---------------|-----------------|-----------|
| 1       | First meeting with client                                     | To understand client problem and requirements                                                                                   | Planning     | 15min         | 1 March         | A         |
| 2       | Start writing down all the requirements & success criteria    | To list down the first success criteria                                                                                         | Planning     | 20min         | 1 March         | A         |
| 3       | Meet with the client to discuss the success criteria.         | Have in mind all of the modifications needed and reach an agreement                                                             | Planning     | 1h            | 1 March         | A         |
| 4       | Finalise  and modify success criteria                         | Prepare a satisfactory criteria according to my client's feedback and mail it to them.                                          | Planning     | 20min         | 1 March         | A         |
| 5       | Draft the Proposed Solution and                               | Have problem definition which will identify who client is and the product that the client wants                                 | Planning     | 20min         | 2 March         | A         |
| 6       | Research and develop a rationale for the proposed solution.   | Finish rationale for proposed solution                                                                                          | Planning     | 20min         | 2 March         | A         |
| 7       | Create ER diagram including descriptions                      | Create an ER diagram that illustrates the tables and attributes of the solution with a brief explanation                        | Planning     | 30min         | 3 March         | B         |
| 8       | Create System Diagram                                         | Develop a clear idea of the hardware and software requirements for the proposed solution                                        | Design       | 40min         | 3 March         | B         |
| 9       | Design Wireframe Diagram and details                          | Wireframe diagram that is clear for my client and visually appleasing                                                           | Design       | 30min         | 3 March         | B         |
| 10      | Produce Flow diagrams including descriptions                  | Flowcharts and a brief explanation for each section of the solution to obtain a clearer understanding of the code's proccess,   | Design       | 45min         | 3 March         | B         |
| 11      | Design UML Diagram                                            | Diagram illustrating the solution's classes, objects, and methods, as well as a brief explanation                               | Design       | 20min         | 3 March         | B         |
| 12      | Start coding Welcome Screen                                   | have an inviting screen for client to use                                                                                       | Development  | 30min         | 3 March         | C         |
| 13      | Code login and registration system and screens                | A working login and register screen with Python and KivyMD with a GUI                                                           | Development  | 1h            | 4 March         | C         |
| 14      | Create show password function                                 | make the application more simple for use                                                                                        | Development  | 30min         | 4 March         | C         |
| 15      | Create home/welcome screen according to the wireframe diagram | screen that contains all the available functions of the program                                                                 | Development  | 30min         | 4 March         | C         |
| 16      | Set up Screen correspondences and changes.                    | Python and KivyMD with a GUI are used to switch between screens.                                                                | Development  | 30min         | 4 March         | C         |
| 17      | Set up databases                                              | insert and store inputs of users and items into the database                                                                    | Development  | 1h            | 4 March         | C         |
| 18      | Create Profile Screen                                         | A functional page that allows the user to see their information                                                                 | Development  | 40min         | 4 March         | C         |
| 19      | Create Order Screen                                           | A functional page that allows the user to input the clients order                                                               | Development  | 1.5h          | 4 March         | C         |
| 20      | Enhance Order Screen with additonal Widgets                   | Add kivy md widgets that are convenient for the order screen such as the date picker                                            | Development  | 25min         | 5 March         | C         |
| 21      | Add check boxes                                               | make it more convenient for the client to classify the food into a category                                                     | Development  | 40min         | 5 March         | C         |
| 22      | Show add item screen to client                                | ensure that all elements the client wanted regarding the item are present                                                       | Evaluation   | 30min         | 6 March         | A         |
| 23      | Create table to show items                                    | food item table that shows up on the database                                                                                   | Development  | 30min         | 6 March         | C         |
| 24      | Code table screen                                             | screen that shows the table in the database                                                                                     | Development  | 30min         | 6 March         | C         |
| 25      | Code delete item function                                     | function that allows the client to remove the item from the database (for exmaple if they ate it)                               | Development  | 15min         | 6 March         | C         |
| 26      | Code search item function                                     | allows the client to conveniently search up the object they are looking for by entering any element about the item in the table | Development  | 1h            | 8 March         | C         |
| 27      | Show list screen to client                                    | ensure that all elements the client wanted regarding the list are present                                                       | Evaluation   | 20min         | 8 March         | A         |
| 28      | Create occupancy screens                                      | screens that each showcases the amount of space the food has filled up the fridge in a visually pleasing manor                  | Development  | 1h            | 8 March         | C         |
| 29      | Code occupancy function                                       | Allow the client to get a clear visual representation of how full the fridge is                                                 | Development  | 1h            | 9 March         | C         |
| 30      | Finalise program                                              | Test all the functions and beautify to present to the client                                                                    | Development  | 30min         | 9 March         | C         |
| 31      | Write Criteria C                                              | Write all of the app development, code description and details of tecniques implemented                                         | Evaluation   | 2h            | 9 March         | A         |
| 32      | Finish test plans                                             | contains the procedures for testing the application as well as the expected results of each test.                               | Planning     | 45min         | 10 March        | B         |
| 33      | Screen Record App for Criteria D                              | Video demonstration of all success criterias operating and functioning within the built application                             | Evaluation   | 10min         | 10 March        | D         |                                                                                                              

## Task Record

| Description               | Test Type                    | Input                                                                                                                                                                           | Expected output                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------------------|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SignUp System             | Functional: Unit test        | 1. Run the program 2. Click the "Register" button 3.Input username 4. Input password 5. Confirm password 6. Click register                                                      | After entering all of the relevant data in each textfields and clicking the register button, the user information should be stored into the database, and stored in the 'users' table. The user will then be directed to the login  screen along with a pop-up message indicating that the user is registered. If the user already exists, a pop-up  will show informing the user that the username is already in use. |
| Login System              | Functional: Unit test        | 1. Run the program 2. Click the "Login" button 3.Input username 4. Input password 6. Click login                                                                                | If the username and password input is correct, the user will be directed to the Home screen, if not, the helper text for both the username and password will show up telling the user to re-check their input again.                                                                                                                                                                                                   |
| Order System              | Functional: Unit test        | 1. Run the program 2. Click the New Order Button 3. Fill up Client ID 4.Click Drinks ordered 5.Checkout                                                                         | After this, the transaction should be saved into the ledger, and a new order should be added there,, additionally  the price label should be reset.                                                                                                                                                                                                                                                                    |
| Log out System            | Functional: Unit test        | 1. Run the program 2. Login 3. Logout                                                                                                                                           | After clicking the "Log out", the user will be directed to the Welcome screenq                                                                                                                                                                                                                                                                                                                                         |
| app_project3 database     | Functional: Integration test | 1. Run the program 2. Login 3. Click "Add item" button 4. Input owner, title 5. Select Drink 6. Input Client Id  8. Click add item 9. Check 'items' table in app_project3.db.db | All relevant data regarding the food information should be stored in the database, and stored in the 'items' table.  The table in the database should be updated whenever a new item is added or removed.                                                                                                                                                                                                              |
| Inventory System & Screen | Functional: Unit test        | 1. Run the program 2. Login 3. Click Inventory  4.Click Plus                                                                                                                    | From clicking the buttons I will be able to see if the added product was d                                                                                                                                                                                                                                                                                                                                             |
| MDTable System            | Functional: Unit test        | 1. Run the program 2. Login 3. Click "view list" button 4. Click on checkboxes  of the item(s) that the user wants to delete 5. Click "delete item" button                      | A checkmark will show up inside the box when the user selects the checkbox next to the item. The selected item(s)  should then be deleted from the table when they click the delete item button.                                                                                                                                                                                                                       |
| Navigation                | Functional: Integration test | 1. Run the program 2. Login 3. Click on Menu 4.Click on the Navigation Bar 5. Click on any of the icons                                                                         | When clicking on the navigation bar icons, it should take you to the selected screen.                                                                                                                                                                                                                                                                                                                                  |
| Menu                      | Functional: Unit test        | 1. Run the program 2. Login 3. Click the Menu 4. Click on drink 5.Click on recipe                                                                                               | When the menu appears, there should be a functionality where you click MDDIALog should appear with the recipe to the drink clicked.                                                                                                                                                                                                                                                                                    |
| Code review               | Non-functional: code review  | assessing the code in project3.py to see whether the variable names, function names,  and comments are suitable                                                                 | The user can better grasp how the code works according to the variable names and comment. The code should be simple to understand and easy to follow.                                                                                                                                                                                                                                                                  |


## Flow Diagrams

### Sign Up 

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Untitled%20(3).jpg" width=90% height=90%>

Fig.14: The flow diagram abovs illustrates the SignUp proccess for the user, as shown above there is alot of requirements for a successful sign up.


### Log in

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Untitled%20(7).jpg" width=90% height=90%>

Fig.15: The flow diagram abovs illustrates the Login proccess for the employee, as shown above there is one main operation which is checking that the password corresponds the employee_no and the inputted password matches with the stored password. It's checked through my CheckHash Function.


### Buy Material

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Untitled%20(4).jpg" width=90% height=90%>

Fig.16: When a new itemis bought such a milk, the inventory is updated through the proccess above, aditionally the transaction is saved in the ledger table in order to ensure financial transparency to my Client.

### Checkout

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Untitled%20(5).jpg" width=90% height=90%>

Fig.17: Checkout is a function that takes place in the OrderScreen after the employee has taken the order of a client, it adds the transaction to the ledger and classifies it as profit.

### Pre Enter (Table)

<img src="https://github.com/marinamen/unit3_project/blob/main/images/Untitled%20(6).jpg" width=90% height=90%>

Fig.18: On_pre_enter method is used in KivyMD to specify the actions to be taken before a screen is shown. In this case, the method creates a MDDataTable object. When the Data is collected a few things need to be taken in mind in order to mantain the FInancial Screen functional.



Figure 5: The flow diagram above illustrates the Python function that retrieves sensor data from the local server. The function uses a known sensor ID value to take that sensor's specific values. It requests the sensor readings from the API using the IP and HTTP get from the server. It creates a dictionary with the readings as the key and an empty list. Then for every value in the sensor readings, it appends the data ti the corresponding list in the dictionary. Finally, if there are no values left it returns the list.

# Criteria C: Development

## Techniques used
  
1. KivyMD Library
2. OOP pattern
3. Relational databases
4. SQLite, ORM
5. Classes
6. Functions
7. If statements
8. For loop
   

## Computational thinking
  
1. Decomposition
2. Pattern Recognition
3. Algorithm Thinking
4. Abstraction 
  
## Python file: "mainfile.py"
  
  
### 1.Setting up the file
After I got approval from my client I inmediately started setting up the file, while not all of these were imported when I started, they were eventually added throughout the proccess when any additional features were added
```.py
import sqlite3
```
In order to store the data collected from the app, which ranges from orders database to users database, i needed a lightweight disk-based database that doesn't require a separate server process and additionally sqlite3 allows relational databases that are useful, for example to see which orders what employee did, so a 1 to many relationship.

```.py
from kivy.lang import Builder
from kivy.uix.widget import Widget

```
Using KivyMD's Builder makes creating your app's look easier and faster. It lets you separate the design from the code, making changes and updates simpler. This approach is great for quickly trying out new ideas and keeping your project easy to understand and work on.

```.py

from kivy.uix.screenmanager import ScreenManager
from kivymd.app import MDApp
from kivy.core.window import Window

```
The essential components in order to run a multiscreen kivy app.

```.py
from kivymd.uix.datatables import MDDataTable
from kivymd.uix.list import TwoLineRightIconListItem, TwoLineIconListItem, IconRightWidget, TwoLineListItem
from kivymd.uix.navigationrail import MDNavigationRail
from kivymd.uix.screen import MDScreen
from kivymd.uix.button import MDFlatButton, MDRectangleFlatIconButton, MDIconButton
from kivymd.uix.dialog import MDDialog
from kivymd.icon_definitions import md_icons
from kivymd.uix.scrollview import MDScrollView
from kivymd.uix.textfield import MDTextField
import datetime

```
Additional feautures.


```.py
from my_lib import DatabaseWorker, encrypt,checkHash , popupGo, adminYN
```
A library I created that contains Database worker class and several functions that enable me to call them instead of losing time and lines rewriting them, to facilitate the whole proccess.


## 2.My_Lib features.

my_lib.py file can be divided by 4 majors components:

**DatabaseWorker Class**
frsddfcfc

**Hashing Function**

**Popup Function**



## 3.First Success Criteria, Login and Sign up system.

### Registering  

#### Try Tecnique

```.py
    def signup(self):

        timeN=time.asctime()
        try:
            email = self.ids.email.text
            employee_no = self.ids.employee_no.text
            fullname = self.ids.full_name.text
            password = self.ids.password.text
            timeIn=timeN
```

Using a try block in the signup  is beneficial because it allows for the safe execution of code that might raise exceptions, particularly when retrieving data from the ids attribute, which could potentially be missing or improperly formatted by the employees. If any of these attributes (email, employee_no, fullname, password) do not exist or an error occurs during their retrieval, the try block will catch the exception, preventing the entire application from crashing which saves alot of time and prevents minor erros.  This approach is a robust error handling method, allowing for handling of unexpected situations or invalid user input. The ids here just retrieves the text written in the Text Fiedl.

#### Ensuring Correct Format

```.py
            if '@' not in email:
                popupGo(self," Email must contain '@' ")
                return

            if len(password) <= 8:
                popupGo(self," Password must be longer than 8 characters ")
                return

```
With my popupGO function that I explained previously, I put in place some rules so that no frauds are able to get away without personal identification, and for passwords to be secure enough (even if they are stored in hash), an 8 word password can still be a potential risk but it is safer than a shorter one.


#### Ensuring Correct Format

```.py

            cursor.execute("SELECT * FROM users WHERE employee_no = ? OR email = ?", (employee_no, email))
            if cursor.fetchone():
                popupGo(self," Error: Employee number or email already in use")
                return
```
This first part uses my DatabaseWorker, and verifies whether this user has been registered before via a sqlite query, employee numbers can only be associated with one account in order to satisfy my Clients requirement to lessen potential threats.

#### Continuing the Proccess
```.py

            encryptedpass=encrypt(password)
            run_query = "INSERT INTO users (email, employee_no, fullname, password,login_time) VALUES (?, ?, ?, ?,?)"
            cursor.execute(run_query, (email, employee_no, fullname, encryptedpass,timeIn))
            m.commit()
            self.manager.current="HomeScreen"

```
 If all the criteria has been completed, my encrypt function will hash the password and run a sql query to insert all of the data collected into the users database, and then it will take you to the home screen.

### Login

#### Verifying Employee User

```.py
            if row:
                stored_password = row[0]
                if checkHash(input_password, stored_password):
                    print("Login successful!")
                    m.commit()
                    self.manager.current = "HomeScreen"
                else:
                    popupGo(self, "Error! Invalid password")

            else:
                print("Error: Employee number not found")
```
Login is slightly different to the sign up for the key reason that the password has to be checked and compared with the hash, though my check_hash function. What this does is essentially de-encrypts the database retrieved hash and compares it to the password inputted. Since realistically two hashes cannot be the same even if they actually are the same word, due to the nature of the sha.256 algorithm


### Additional Feauture

In order to make it as close as possible to a downloadable app, I made the password be hidden when written by simply using the kivy command password, however I also added a Show Password function in order to maximise the UX.

```.py
    def show_password(self,checkbox,value):
        if value:
            self.ids.inputpassword.password=False
            self.ids.pass_text.text="Hide Password"
        else:
            self.ids.inputpassword.password=True
            self.ids.pass_text.text="Show Password"

```

As shown above when the checkbox was pressed```.py        on_active:root.show_password(*args )``` , the show_password function would start, and what this would do is it would check whether if Kivy detects the Password Text Field as a Password, if it does then that means it is not Visible so the label will be Show Password, however if the 









h respect to the independent variable `time_in_hours`. It initializes the parameter values with ones and attempts to find the optimal parameters for the quadratic polynomial model.

```.py
degree = 2
popt, pcov = curve_fit(polynomial_model, time_in_hours, averageTI, p0=[1] * (degree + 1))
```

Next, `y_poly` computes polynomial values using optimized parameters popt for extended input `x_extended` using the `polynomial_model` function.
```.py
y_poly = polynomial_model(x_extended, *popt)
```

<img src="https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%2008.08.42.png" width=65% height=65%>

*Fig.2.1*


Next is the linear model,

It runs through the same exact proccess but with a degree of 1

<img src="https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%2008.08.22.png" width=65% height=65%>

*Fig.2.2*


## 3.Client Requested a program that worked under low connection to network without major malfunctioning

Since the program needed to run under low connection to the network without malfunctioning. We implemented some safe fails. So that if the network doesn’t work or the server times out the conputer has multipletries to upload the data. To make sure the data is configured correctly and no data points are missing or formatted incorectly we use try and except function. The try tests to make sure the decoded data string is a valid float. If it is valid the program continues. If it doesn’t it excepts the value error and prints that the line is in an invalid data line then continues pulling up the next line [^8]. Figure(4.1) To make sure the server doesn’t time out after logging in once we implemented within the if statement the login cookie again so that if the device has lost connection with the server, it can reconnect before appending the sensor data. Figure(4.2) These both help the program run smoothly under a low connection and minimizes malfunctions.

Figure (4.1) Checks if there is an invalid data format from the decode Ardunio data and skips that line or continues the program
```.py
try:
   temperature = float(decoded_data[temperature_start:temperature_end].strip())
   humidity = float(decoded_data[humidity_start:humidity_end].strip())
except ValueError:
   print("Invalid data format. Skipping line.")
   continue
```
Figure (4.2) Part of the code that Appends data specifically the part where the failsafe reconnect to the server is
```.py
if len(sensor_data) == 3:
   with open(fileName, "a") as file:
       file.write(f"{sensor_data['1'][0]},{sensor_data['1'][1]},"
                  f"{sensor_data['2'][0]},{sensor_data['2'][1]},"
                  f"{sensor_data['3'][0]},{sensor_data['3'][1]},"
                  f"{datetime.datetime.now()}\n")
   answer = requests.post(f'http://{ip}/login', json=user)
   print(answer.json())
   cookie = answer.json()["access_token"]


   record = {'sensor_id': 80, 'value': f"{sensor_data['1'][0]}"}
   answer = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
```



## 4.Client Requested two copies of Data Collected, one in a local CSV and the second uploaded realtime to API Server.

To ensure that the data from the indoor sensors is saved, the client requested that the data be kept in a CSV along with being uploaded to a local server API. Using the library date time we can track every time mark it uploads to the server. We did this by creating a user with the local server and gaining a cookie access token. The cookie allowed us to add data to the server. The purpose of using a cookie to log in was to maintain security and prevent unauthorized access. Figure (5.1) Next, we implemented a while loop in our program to continuously check for data from the Arduino. The data was decoded using a UTF 8 decoder that utilized the ASCII table.Figure(5.2) The program then used an if statement to check if the line contained any sensor data. The sensor data under the sensor ID was then stored in a dictionary where the keys were the sensor number, and the values were Temperature and Humidity. Now, using an if statement, for every sensor data length equal to three. The values of that sensor were put into the local server under that sensor ID, along with the sensor values being appended to the CSV file and with time stamps. Once those values are put into the server/CSV the dictionary resets and takes the next line of data from the Ardunio. See Figure(5.3)



Figure (5.1) User created to access and login to the local server API
```.py
user = {'username':"keelarina","password":"iloveroky"}
#login


answer = requests.post(f'http://{ip}/login', json=user)
print(answer.json())
cookie = answer.json()["access_token"]
```
Figure (5.2) This code reads data from a serial port connected to an Arduino for the number of values that the ardunio takes. It decodes the binary data into a string using UTF-8 encoding and prints the resulting decoded data.
```.py
while line <= samples:
 
   # Reads data from the serial port that connected to the Ardunio
   data = ser.readline()


   # Decodes the binary data into a string using UTF-8 
   decoded_data = data.decode('utf-8', errors='ignore').strip()


   # Prints decoded data
   print(decoded_data)
```
Figure(5.3) This code appends the temperature and humidity values from three sensors, along with a timestamp, to a CSV file. It then logs into a local server, obtains an access token (cookie), and uploads the sensor readings for each sensor
```.py
if len(sensor_data) == 3:
   with open(fileName, "a") as file:
       file.write(f"{sensor_data['1'][0]},{sensor_data['1'][1]},"
                  f"{sensor_data['2'][0]},{sensor_data['2'][1]},"
                  f"{sensor_data['3'][0]},{sensor_data['3'][1]},"
                  f"{datetime.datetime.now()}\n")
   answer = requests.post(f'http://{ip}/login', json=user)
   print(answer.json())
   cookie = answer.json()["access_token"]


   record = {'sensor_id': 80, 'value': f"{sensor_data['1'][0]}"}
   answer = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
   record = {'sensor_id': 75, 'value': f"{sensor_data['1'][1]}"}
   answer5 = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
   print(answer5.json())
   record = {'sensor_id': 76, 'value': f"{sensor_data['2'][0]}"}
   answer1 = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
   print(answer1.json())
   record = {'sensor_id': 77, 'value': f"{sensor_data['2'][1]}"}
   answer2 = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
   print(answer2.json())
   record = {'sensor_id': 78, 'value': f"{sensor_data['3'][0]}"}
   answer3 = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
   print(answer3.json())
   record = {'sensor_id': 79, 'value': f"{sensor_data['3'][1]}"}
   answer4 = requests.post(f'http://{ip}/reading/new',
                          json=record,
                          headers={'Authorization': f'Bearer {cookie}'})
   print(answer4.json())


   # Resets the dictionary
   sensor_data = {}
```
Figure(5.4): CSV FILE Temp 1, Humidity 1, Temp 2, Humidity 2, Temp 3, Humidity 3, Time Uploaded/saved to CSV

<img src ="https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%2010.32.10%20AM.png" width=35% height=35% >


## 5.Client Requested a 12 hour prediction sampled from the Data Collected the previous 48 hours.
>We used two methods to predict data, here we'll talk about the second.Using the data recorded between the 24th and 36th hour, we projected the temperature and humidity for the upcoming 12 hours, incorporating a margin of error at 2.5% for temperature and a range of ±2.5% for humidity. This margin was determined by evaluating the variance in historical data and the accuracy of past predictions. To visually convey this uncertainty, we utilized plt.fill_between and plt.errorbar functions, providing a clear graphical representation of the expected range. This approach effectively meets criteria 5 by ensuring the client has a tangible understanding of the potential fluctuations in the environment. The

**Temperature Prediction**


It starts by initializing empty lists pred_12l and pred_12h, as well as an empty list x_pred. It then iterates 144 times, calculating values for pred_12h and pred_12l based on elements from an existing list averageTI, these values are modified by scaling factors and added to their respective lists.


```.py
pred_12l = []
pred_12h = []
x_pred = []
fig = plt.figure(figsize=(10, 6))
grid = GridSpec(2, 4, figure=fig)

for i in range(144):  
    pred_12h.append(averageTI[
      i + 144] * 1.045)  
    pred_12l.append(averageTI[i + 144] * 0.955)
```
Moving on, the variable `x_pred` is populated with values, calculated as i divided by 12 in a loop ranging from 0 to 143. These values are used to create a filled region between two curves defined by `pred_12l` and pred_12h using `plt.fill_between.` Additionally, a line plot is drawn using plt.plot with data from `averageTI[144:288]`.

```.py
    x_pred.append(i / 12)
plt.fill_between(x_pred, pred_12l, pred_12h, alpha=.5, linewidth=0)
plt.plot(x_pred, averageTI[144:288], linewidth=2,color="#0090d2")
```



<img src="https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%2008.08.08.png" width=65% height=65%>
Fig5.1 Displays the subsequent 12 hour Linear prediction for the Indoor Temperature


**Humidity Prediction**

This snippet predicts high and low humidity levels for a 12-hour period. For each hour, it calculates the high estimate by increasing the average historical humidity `averageHI` by 20%, and the low estimate by reducing it by 20%, it also tracks the time in hours for y axis

```.py
predHumh = []
predHuml = []
x_pred = []


for i in range(144):  # 576 readings for 48 hours-> 144 for 12h
    predHumh.append(averageHI[
                                         i + 144] * 1.2)  
    predHuml.append(averageHI[i + 144] * 0.8)
    x_pred.append(i / 12)
```

Next,its a quadratic polynomial to a subset of historical humidity data `averageHI`, then calculates and plots the fitted values (y_quad) against x_pred, representing time. It also visualizes the potential error in predictions using an error bar with a fixed value of 2.5 margin

```.py
y_quad = []
p0, p1, p2 = np.polyfit(x_pred, averageHI[288:(288 + len(x_pred))], 2)  # 2 means power of 2
for i in x_pred:
    y_quad.append(p0 * (i ** 2) + p1 * i + p2)
plt.plot(x_pred, y_quad, color="#0090d2")
plt.errorbar(x_pred,y_quad,2.5,color='#ffc200')
```
<img src="https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%2008.07.59.png" width=35% height=35%>
Fig5.2 Displays the subsequent 12 hours, with errorbars.

## 6.Client Requested a visual representation of Data collected, both locally and remotely.
To fulfill the client's request for a visual representation of the data. Since all the data of both indoor and outdoor data, was on the server. We used the get sensor function which accesses the local server's readings through get requests and then outputs the data for the specific sensor. Figure(6.1) Using this we’re able to take all the indoor sensors and outdoor sensors for temperature and humidity and create a graph using Matplot Library to help illustrate the values over the 48-hour period. Once we call all the sensor data from the server, we create a subplot to generate our graph. In the subplot, we set up the x and y axis to the appropriate measurement and time. We then used the library NumPY, a library that works with arrays[^10], to create the average value for each of the indoor and outdoor temp and humidity sensors. The values for each sensor were also graphed.Figure code (6.2)Figure graph (6.3) 
IMPORTANT NOTE: THE SECOND OUTDOOR SENSOR WAS BROKEN SO THE VALUES ARE NOT GRAPHED.

The average graphs also had median, maximum, and minimum lines. The median is the value in the middle of the dataset. The maximum is the largest value in the data set. The minimum value is the lowest value in the data set.


Figure(6.1) This is the function that took the sensor readings from the API
```.py
def get_sensor(id: int = 1, ip: str = "192.168.6.153"):
   request = requests.get(f'http://{ip}/readings', )
   data = request.json()
   sensors = data['readings'][0]
   sensor = []
   for s in sensors:
       if s['sensor_id'] == id:
           sensor.append(s['value'])
   return sensor






# DTH11 1- Indoor
t1 = get_sensor(80)
h1 = get_sensor(75)
# DTH11 2- Indoor
t2 = get_sensor(76)
h2 = get_sensor(77)
# DTH11 3 - Indoor
t3 = get_sensor(78)
h3 = get_sensor(79)


# DTH11 1- Outdoor
to1 = get_sensor(1)
ho1 = get_sensor(4)
# DTH11 3 - Outdoor
to3 = get_sensor(2)
ho3 = get_sensor(5)
```

Figure(6.2) This is the code that was used to graph the plots of each sensor temperature/humidity indoor and outdoor,s along with the average.
```.py
fig = plt.figure(figsize=(10, 6))
grid = GridSpec(2, 4, figure=fig)


plt.subplots_adjust(wspace=.5)


tempIndoor = fig.add_subplot(grid[:, :])


plt.ylim([5, 90])
plt.xlim([0, 596])




plt.plot(ho1, color="#0090d2",label="Sensor 2")
plt.plot(ho3,color="#d0f2ef",label="Sensor 3")
plt.xlabel("Time (hours)")
plt.ylabel("Humidity (%)")
num_data_points = len(t1)
time_ticks = np.arange(0, num_data_points, 60)  # Ticks every 10 hours
time_labels = [f"{i*5//60} hours" for i in range(0, num_data_points, 60)]
ticker.NullFormatter()
plt.grid()




plt.xticks(time_ticks, time_labels)






plt.plot(averageHO, color="#f89cc4", linewidth=2, label="Average",linestyle ='-.')
plt.legend()
plt.title("Humidity Outdoor Sensors")
```
Figure(6.3) This is one of the average graphs for the sensors. It's important to note the minimum an maximum lines which represent the minimum value and the maximum value in the data set.

<img src = "https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%207.24.48%20PM.png" width=90% height=90%>

Figure(6.4) This graph displays the median line for the graph of the outdoor humidity sensors. To calculate the average only two sensors were used because the second sensor was broken.

<img src ="https://github.com/marinamen/unit2_project/blob/main/images/Screenshot%202023-12-14%20at%203.02.07%20PM.png" width=50% height=50%>
## 7.Login and Register System

The UWC ISAK Weather Station Server operates under specific rules and terminations. 

Our code implementation involved several steps: initially, we registered a new user and established a password. 
```.py
def register(ip="192.168.6.153",):
  new_user = {'username': '#####', 'password':'#####'}
  req = requests.post(url+"/register", json=new_user)
  print(req.json())
```

Following this, we logged into the server using the newly created credentials

 ServerLogin, sends a POST request to the API address with default values. It includes a JSON payload containing a username and password, it then prints the response JSON, extracts an access token from it, and returns it as an authorization header for future requests, typically used for privacy purposes.

```.py
def serverLogin(ip="192.168.6.153", user={"username": "keelarina", "password": "iloveroky"}):
    req = requests.post(f"http://{ip}/login", json=user)
    print(req.json())
    cookie = req.json()["access_token"]
    return {"Authorization": f"Bearer {cookie}"}
```

# Criteria D: Functionality

A 7 min video demonstrating the proposed solution with narration

[click here](https://drive.google.com/drive/u/0/folders/1wc02hAbefVOhRh0PKFGidpggd4kH6zbF)



<sub> 

[^1]: SQL Lite (n.d).
https://www.python.org/about/success/
[^2]: Rose, J. (2020). Why Python is so popular with developers: 3 reasons the language has exploded. TechRepublic. https://www.techrepublic.com/article/why-python-is-so-popular-with-developers-3-reasons-the-language-has-exploded/
[^3]: KivyMD. (n.d.). KivyMD: Introduction. https://kivymd.readthedocs.io/en/latest/introduction/
[^4]: Kivy. (n.d.). User Interface - Widgets. https://kivy.org/doc/stable/gettingstarted/widgets.html
[^5]: Smith, L. (2021). Flutter vs Kivy: Which One is Better for Cross-Platform App Development? Medium. https://levelup.gitconnected.com/flutter-vs-kivy-which-one-is-better-for-cross-platform-app-development-f38d73624e6b
[^6]: SQLite. (n.d.). SQLite Features. https://www.sqlite.org/features.html
[^7]: IBM. (2021). IBM Db2. https://www.ibm.com/products/db2-database
[^8]: SQL Tutorial. (n.d.). What is SQLite? https://www.sqlitetutorial.net/what-is-sqlite/


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

3. Admin is able to see Employees Purchases and Orders and Log in times.

4. The application allows the admin to view the revenue and and an admin specific screen.

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
| 28      | Create occupancy screens                                      | screens that each showcases the amou in a visually pleasing manor                  | Development  | 1h            | 8 March         | C         |
| 29      | Code Menu function                                       | Allows the employee to check up on recipes when making them                                                 | Development  | 1h            | 9 March         | C         |
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
```.py
import sqlite3

class DatabaseWorker:
    def __init__(self, name: str):
        self.name_db = name
        self.connection = sqlite3.connect(self.name_db)
        self.cursor = self.connection.cursor()


    def run_query(self, query: str):
        self.cursor.execute(query)  
        self.connection.commit() 

    def search(self, query: str, multiple: bool = False):
        results = self.cursor.execute(query)
        self.run_query(query)
        if multiple:
            return results.fetchall()  
        else:
            return results.fetchone()  

    def close(self):
        self.connection.close()
```

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

As shown above when the checkbox was pressed```.py        on_active:root.show_password(*args )``` , the show_password function would start, and what this would do is it would check whether if Kivy detects the Password Text Field as a Password, if it does then that means it is not Visible so the label will be Show Password, however if the Password is visible the label will change to Hide Password.  Very useful function since often we input incorrect passwords by mistakes because we cannot see what we are typing. Enhances UX experience.



## 4.Second Success Criteria, Orders and Orders Table.

### Displays the table on the screen

```.py
def on_pre_enter(self, *args):
    self.data_table = MDDataTable(
        size_hint = (.9, .8),
        pos_hint = {"center_x":.5, "center_y":.5},
        use_pagination = True,
        check = True,
        column_data = [("Client_Id", 40), ("Ordered_item", 50), ("Amount", 40),
                       ("aid", 45),
    )
    self.add_widget(self.data_table)
    self.update()
```
Above is shown how I am able to display a table with data onto the screen, I use a select query previous to this in order to retrieve all of the necessary data and then display it onto the table using the program above. 
I applied this strategy in different sections of the application, such as the order search system. However, when it came to integrating a table for data presentation, I encountered a hurdle with closing the table. Initially, I experimented with a pop-up window, but ultimately, I opted for a more user-friendly and aesthetically pleasing solution by incorporating a button to close the table view.

### Checkout User orders
```.py

    def checkout(self):
        client_id = self.ids.client.text
        total_price = self.total

        cursor.execute("INSERT into orders (client_id, paid, date) VALUES (?, ?, CURRENT_TIMESTAMP);", (client_id, total_price))
        m.commit()  

        for item_name, item_price in self.ordered:
            current_time = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
            cursor.execute("INSERT INTO ledger (item, cost, amount, date) VALUES (?, ?, ?, ?)", (item_name, item_price, 1, current_time))
        m.commit()

        self.total = 0
        self.ordered = []
        self.ids.price.text = "0¥"
        popupGo(self, "Checkout complete. Thank you for your order!")

```

I implemented a checkout function to process orders efficiently. Upon invoking this function, I capture the client's ID and the total price from the UI and insert these details into an 'orders' database table, timestamping each order to mark its completion. To handle the breakdown of each order into individual items, I employed Decomposition by iterating over self.ordered, which contains the items. For each item, I record its name, cost, and a quantity of 1 in the 'ledger' table, tagging each entry with the current time. This approach is a clear demonstration of Algorithmic Thinking, allowing me to systematically process and log each item. After processing an order, I reset self.total and self.ordered to their initial states and update the UI to show a zero price, ensuring the system is ready for the next customer. I also implemented a popup message to confirm the successful checkout, enhancing the user experience. This comprehensive approach not only makes the checkout process seamless but also ensures accurate record-keeping for each transaction. This was especially useful since users tend to order more than one product.


## 5.Third Success Criteria Employee Info.

The admin is essentially employer with employee_no = 111, the reason why I chose this is to keep the Employees history tied with their Work ID instead of their usual one. This also allows for less tresspassers to sign in since essentially they need to have an employee NO to sign up, which has to fall under the below requirements.

```.py

        if not employee_no.isdigit() or not 100 <= int(employee_no) <= 999:
            popupGo(self, "Employee number must be a number between 100 and 999")
            return
```


Additionally I added a system that keeps track of the Login Times of each employee just in case if an issue occurs during shift the admin will be able to know who it was

```.py

update_query = "UPDATE users SET login_time = ? WHERE employee_no = ?"
cursor.execute(update_query, (current_time, employee_no))
m.commit()  #
```

## 6.Fourth Success Criteria Admin Privileges.

In order for the admin to be recognised as I mentioned before, I define it as the employee_no = 101.

The Revenue Screen diplays two graphs plotted using matplotlib and kivy garden to incorporate it into the application. The additonal Screen is only called when the a user presses into the Safebox in the revenue screen and:

```.py
        try:
            if userNow == 101:  # Check if the employee_no indicates admin rights
                self.manager.current = "AdminScreen"  # Navigate to AdminScreen if user is admin
            else:
                popupGo(self, "Access Denied: You are not an admin")
```

This ensures the access is limited to the Admin by checking the employee_no

The additional Screen displays, revenue, balance and no_coffees sold per day, simply performed by sqllie comands such as sum.

## 6.Fifth Success Criteria Track Inventory.

#### Buy Item in Inventory

```.py
cursor.execute("UPDATE inventory SET amount = amount + 1 WHERE item = 'item_name'"):
m.commit()
```
 In this line, I'm updating the inventory in my database. Specifically, I'm increasing the amount of 'item_name' by 1 in the inventory table. This is executed when an item is purchased or restocked.

```.py
cursor.execute("SELECT cost_per_unit_euro, distributor FROM inventory WHERE item = 'item_name'")
```
With this line, I'm retrieving the cost per unit and the distributor's name for 'item_name' from the inventory table. This information is essential for logging the transaction in the ledger.

```.py
cost, distributor = cursor.fetchone()
```
This line assigns the fetched cost per unit and distributor's name to the variables cost and distributor, respectively. The fetchone() function returns the next row of the query result, which in this case, contains the cost and distributor of 'cow milk'.

```.py
current_time = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
```

 Here, I'm getting the current time and formatting it as a string in the format "YYYY-MM-DD HH:MM:SS". This timestamp is used to record when the transaction occurred.

```.py
cursor.execute("INSERT INTO ledger (item, cost, amount, date) VALUES (?, ?, ?, ?)", ('cow milk', cost, 1, current_time))
m.commit()
```
In this line, I'm inserting a new record into the ledger table. This record logs the purchase of 'item_name', including the item name, cost, quantity purchased (which is 1 in this case), and the timestamp of the transaction.

```.py
cursor.execute("SELECT amount FROM inventory WHERE item = 'item_name'")
l=cursor.fetchone()
new_amount=l[0]
```
 This line fetches the updated amount of 'item_name from the inventory after the purchase/restock.

```.py
self.ids.itemT.text=f"{new_amount}":
```
 Finally, I'm updating the text of the Label  to display the new amount of item in the inventory. This ensures that the UI reflects the most current inventory level after the transaction.

#### Display of Inventory Screen Kivy

Below is a short segment of my kivy code, this falls under the <InventoryScreen> and it is the display of a label that contains the amount of the item and the plus button to purchase more of it. I will run down a bit of kivymd language in order to show profound depth of knowledge.
```.py
    MDLabel:
        id:chocsyrupT
        text:root.new_amount
        size_hint:.3,.3
        pos_hint:{'center_x':0.49,'center_y':0.66}

    MDIconButton:
        id:chocsyrup
        icon:"plus"
        md_bg_color:"#fbebf3"
        size:0.2,0.2
        pos_hint:{'center_x':0.43, 'center_y':0.65}
        on_release:root.buy_item()

```
The MDLabel displays a text with no functionality, but it can be changed using the code i previously mentioned, using the ID to identify it and replacing the no root.new_amount, which automatically takes the amount of the item in the inventory database and puts it into the label.

The MDIconButton is a button that in this case I have displayed a plus that triggers the buy_item().

## 7. Computational thinking
  
### 1. Decomposition

In this app, I've broken down the complex task of managing a coffee shop into smaller, more manageable pieces by creating different classes for each part of the app, like SignUpScreen, HomeScreen, and OrderScreen. Each class deals with a specific piece of the app's functionality. For instance, the OrderScreen class focuses only on handling orders. This approach makes the code easier to understand and work with because I can focus on one small part at a time, making the whole system more organized.

### 2. Pattern Recognition

For pattern recognition in my coffee shop app, I noticed that certain elements, like background images and color themes, were reused across different screens. Additionally, the functionality to navigate back to the home screen was common throughout the app. To make my code more efficient and avoid repetition,I took advantage and added a Navigation Widget that allowed me to only insert the name and size and it facilitated the whole proccess.

### 3. Algorithm Thinking

I used algorithmic thinking  in the buy_item methods within the InventoryScreen class, where a systematic process is followed to update inventory levels, record transactions in the ledger, and reflect changes in the UI. This method involves a sequence of steps: updating the inventory database, fetching updated cost and distributor information, inserting a new record into the ledger, and finally updating the UI to show the new inventory level. This methodical approach ensures that all aspects of the inventory update process are addressed in a logical order, minimizing errors and ensuring data integrity.

### 4. Abstraction 

I demostrated Abstracion through the use of high-level KivyMD widgets (MDLabel, MDIconButton, etc.....) and custom methods (buy_choco, signup, etc....) that hide the complexity of underlying operations. For instance, MDIconButton abstracts away the details of rendering a button and detecting touch events, allowing me to focus on specifying button properties and behavior (like on_release) relevant to the application's context. Similarly, the signup method in the SignUpScreen class abstracts the process of registering a new user, encapsulating database interactions, input validation, and UI updates. This abstraction enables me to manage complexity by concentrating on higher level functionality rather than low level details.




# Criteria D: Functionality

A 3 min video w the proposed solution

[click here](https://drive.google.com/drive/u/0/folders/1qj2vpnNSFAbFG0RT5rMpL5yer8p_rzJo)



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

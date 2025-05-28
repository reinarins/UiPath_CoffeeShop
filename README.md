# UiPath Coffee Shop (Smart Café Station)
An RPA project developed with UiPath Studio using State Machines, simulating a real coffee shop machine. The bot allows employees to log in with their ID, select products, insert payment, and receive a printed custom receipt.

# Objectives
- Practice and demonstrate the use of <b>State Machines</b> in UiPath Studio.
- Handle structured data: <b>Dictionaries</b>, <b>Excel reading</b>, <b>Input Dialogs</b>.
- Simulate a <b>real-world business use case</b>: a vending/ticketing system.
- Generate <b>custom receipts</b> with user's name, products, total payment details, and current date and time.

# Features
- Employee validation from Excel (ID + Name)
- Product selection via dynamic Input Dialog (menu generated from Dictionaries).
- Credit management: user can insert coins or bills (1€, 2€, 5€, 10€) until total is reached.
- If credit is insufficient, three options are displayed: a) Change products; b) Add more credit; c) Cancel order.
- Automatic change calculation
- <b>Custom receipt</b>: employee's name, selected items, total paid, change returned, current date and time.

# Screenshots
![image](https://github.com/user-attachments/assets/c631c759-7a80-40a1-ac3e-ffacd55d80ab)
<p align="right"><small><i>State Machine architecture</i></small></p>

![image](https://github.com/user-attachments/assets/eb959f36-2f73-470a-bbc1-230551d49a15)
<p align="right"><small><i>To avoid typing all the products manually into the Input Dialog, I previously stored all the product names and their respective prices in two separated dictionaries (Beverages & Food). This way, the products are easier to update.</i></small></p>

![image](https://github.com/user-attachments/assets/73849d9e-3e4f-4e14-9e4f-92dbabe384b2)
<p align="right"><small><i>Custom welcome message</i></small></p>

![image](https://github.com/user-attachments/assets/a6b7efda-aa2c-4ce9-8471-29eef60f4526)
<p align="right"><small><i>Hot Beverages and Cold Drinks Menu</i></small></p>

![image](https://github.com/user-attachments/assets/bd46d5a7-e4cc-47dd-a184-ce71f45ce116)
<p align="right"><small><i>Payment Options</i></small></p>

![image](https://github.com/user-attachments/assets/f04301de-fda5-49ed-b0cf-68de9762d0d4)
<p align="right"><small><i>Custom receipt sample</i></small></p>

![image](https://github.com/user-attachments/assets/65a73bcd-f353-4c10-a5ec-2113222ce1a5)
![image](https://github.com/user-attachments/assets/ebc69414-a4bd-41d9-b843-39d632adf19a)
<p align="right"><small><i>In case of insufficient credit, user can go back to the payment window and add more coins/bills</i></small></p>

![image](https://github.com/user-attachments/assets/86ec9fac-687a-43f8-abae-7231b577f95b)
<p align="right"><small><i>Goodbye message</i></small></p>

# What I worked with
- UiPath Studio (https://www.uipath.com/)
- State Machine architecture
- Excel file handling (Read Range / For Each Row)
- Dictionaries and String manipulation
- Input Dialogs, Message Boxes
- DateTime formatting
- Control flow with IF conditions and loops

# How to run the Smart Café Station bot
1. Clone or download this repository.
2. Open Main.xaml in UiPath Studio.
3. Make sure Employees_ID.xlsx is in the right path.
4. Run the bot. Enter a valid Employee ID from the file (numbers from 1 to 9).
5. Enjoy your coffee ☕🍪!

# Future improvements
- Support for discounts or promotions
- Print receipts as PDF
- Connect to real coffee machines? 🔍

# Author
Developed by <a href="https://github.com/reinarins">@reinarins</a>
<br>
RPA Developer | UiPath | Digital innovation from a human and ethical perspective
<br>
Feel free to connect on <a href="https://www.linkedin.com/in/irisfrro/">LinkedIn</a>!

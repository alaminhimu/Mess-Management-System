# Mess-Management-System
This C++ project is a simple, console-based Mess Management System built using Object-Oriented Programming (OOP).

Here's a summary of its features:

OOP Design: The core of the project is an abstract MenuItem class, which defines a template for all food items. Specific items like RiceAndEgg, Mutton, and Chicken are child classes that inherit from MenuItem and have their own prices.
User Registration: The program features a main menu where the user must first "register" (by entering a username and password) before they can access other features.
Menu and Ordering: Once registered, a user can view a list of four food items and select one to "purchase."
Balance Management: The system manages a user's funds. It starts everyone with a totalBalance of 1000 BDT. When a user orders an item, the program checks if they have enough money and subtracts the item's price from their balance.
View Balance: The user can check their remaining balance at any time from the main menu.

The project also has a "Total Meal" option, but in its current state, it only shows the last item selected, not a running total.

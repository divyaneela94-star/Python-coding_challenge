# 1. 🎓 Student Profile Creator 

## 📌 Project Overview
This project simulates a simple student information system for a school. 
It stores basic student details such as **name, age, and favourite subjects**,
and displays them in a structured manner. It also demonstrates how to update the student’s list of interests.

---

## 🎯 Objectives
- Create and store information using variables
- Work with Python lists
- Display data clearly using formatted strings
- Modify and print updated values

---

## 🧠 Concepts Covered
✔ Variables  
✔ Lists & `.append()`  
✔ String formatting (`f""`)  
✔ Loops (`for`)  
✔ Print formatting  

------------------------------
------------------------------


# 2.🔐 Secret Message Decoder – Python Project

## 📌 Project Overview
This project decodes hidden messages by transforming and cleaning a given input text. The original message may include random characters, symbols, and numbers, and the program extracts meaningful output **without using `in`, `if`, or `for` loops.**

This project demonstrates beginner-level string manipulation in Python.

---

## 🎯 Features
✔ Accepts user input  
✔ Converts the message to UPPERCASE  
✔ Replaces spaces with underscores  
✔ Extracts every 3rd character using slicing  
✔ Reverses the message using slicing  
✔ Uses only allowed functions/methods: `len()`, `.upper()`, `.replace()`, slicing  
✔ Follows restriction: **No `in`, `if`, `for`**

---

## 🧠 Python Concepts Used
- `input()`
- `len()`
- String methods (`upper()`, `replace()`)
- Slicing (`[::-1]`, `[::3]`)
- Printing formatted output
- No loops or conditionals

-------------------------------
-------------------------------


# 3.🛒 Retail Inventory Manager (Python Mini Project)

## 📌 Project Overview
This project simulates a simple inventory management system for a retail store. 
The product categories are fixed (stored using a **tuple**), 
while the list of products is **mutable**, allowing users to add and remove items.

---

## 🎯 Objectives
- Use a tuple for non-editable product categories
- Use a list for editable product inventory
- Allow user to add items dynamically
- Allow user to remove an item using an index
- Display updated inventory and categories

---

## 🧠 Key Python Concepts Used
✔ Tuple (immutable)  
✔ List (mutable)  
✔ `.append()`  
✔ `.pop()`  
✔ User input  
✔ Index-based operations  
✔ `if` condition for validation  


----------------------------------------------------------------
----------------------------------------------------------------

# 4. 📘 Contact Directory

A simple Python-based contact management system that allows users to store, view, search, and sort contact information using list methods and slicing.

## 🎯 How It Works

-The program asks for three student names and their grades.

-It then asks for three hobbies and stores them in a set.

-The hobby set is converted into a frozenset for safe long-term storage.

-All collected data is displayed at the end. Project Overview

-This project demonstrates the use of 2D lists, sorting, slicing, and partial string matching in Python.

## Each contact is stored as a list containing:

-Name

-Phone Number

-Email Address

-All contacts together form a 2D list.

## ✨ Features
✔ Add a New Contact

Users can input a name, phone number, and email, which is then added to the directory.

✔ Alphabetical Sorting

The full list of contacts is automatically sorted alphabetically by name.

✔ Display Contacts

## All contacts are shown after sorting.

✔ Show Only the First 3 Contacts

Uses slicing (contacts[:3]) to display only the first three entries.

✔ Search by Name (Partial Match Supported)

Users can search using full or partial names.
Example: searching "al" will match "Alice Johnson".

## 🧠 Concepts Covered

2D Lists

Appending to lists

Sorting with key functions

List slicing

String methods (lower(), substring matching)

----------------------------------------------
----------------------------------------------


# 5.🎓 Student Grades & Hobbies Tracker

## 📌 Project Overview

This project tracks academic and activity information for students. It uses three important Python data structures:

## 1.📘 Dictionary

Used to store student names and their grades.

Keys = Student names

Values = Grades

Allows easy updates when a student’s grade changes.

## 2.✨ Set

Used to store hobbies.

Automatically removes duplicates.

Great for collecting unique items.

## 3.🧠 Frozenset

An immutable version of a set.

Prevents accidental modification.

Useful for permanently storing the final hobby list.

## 🎯 How It Works

The program asks for three student names and their grades.

It then asks for three hobbies and stores them in a set.

The hobby set is converted into a frozenset for safe long-term storage.

All collected data is displayed at the end.

-----------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------
# 6.📘 BMI Calculator

A simple Python program that calculates a user’s Body Mass Index (BMI) and classifies their health category using basic operators and conditional statements.

## 📌 Overview

This tool helps users quickly compute their BMI using their weight and height. After calculation, the program displays the BMI value along with the corresponding health classification.

## ✨ Features

Accepts integer inputs for weight (kg) and height (cm).

Converts height to meters before performing calculations.

Computes BMI using the formula:

BMI = weight / (height_in_meters²)


## Classifies BMI into:

Underweight

Normal weight

Overweight

Obese

Displays results clearly and neatly.

## 🧮 How to Use

Run the Python script.

Enter weight in kilograms when prompted.

Enter height in centimeters when prompted.

View your calculated BMI and health category.

## 💻 Example
Enter your weight in kilograms (integer): 72
Enter your height in centimeters (integer): 175

Your BMI is: 23.51
Health category: Normal weight

# Interactive Personal Data Collector 🐍

## 📌 About the Project

**Interactive Personal Data Collector** is a beginner-friendly Python project that collects basic personal information from the user through the `input()` function.

The program asks the user to enter their:

* Name
* Age
* Height
* Favourite Number

After collecting the information, the program displays each value along with its **Python data type**. It also calculates the user's approximate birth year based on their age.

This project is designed to practice basic Python concepts such as **input, variables, data types, type conversion, arithmetic operations, and output**.

🌐 live project link:
https://onlinegdb.com/msR5_htCb

🎥 Project Explanation Video:

https://drive.google.com/drive/folders/1ZZFvQSBt94pn0aPVDpRda1lwEQUw3Pfp?usp=drive_link


## 🎯 Objectives

The main objectives of this project are:

* To understand how `input()` works in Python.
* To store user information in variables.
* To understand different Python data types.
* To practice type conversion using `int()` and `float()`.
* To perform basic arithmetic operations.
* To display information using `print()`.

## 🛠️ Technologies Used

* **Python 3**
* `input()`
* `print()`
* `int()`
* `float()`
* Variables
* Arithmetic operators
* `type()`

## 📂 Project Structure

```text
interactive-data-collector/
│
└── Project-1/
    └── p-1.py
```

## ⚙️ How the Program Works

The program follows these basic steps:

1. Displays a welcome message.
2. Asks the user to enter their name.
3. Asks for their age.
4. Asks for their height.
5. Asks for their favourite number.
6. Displays the entered information.
7. Displays the data type of each value.
8. Calculates the approximate birth year.
9. Displays the calculated birth year.

## 💻 Example

### Input

```text
Welcome to the Interactive Personal Data Collecter!

Please enter your name :- Prachi
Please enter your age :- 20
Please enter your height :- 5.5
Please enter your favourite number :- 7
```

### Output

```text
Name: Prachi
Type: <class 'str'>

Age: 20
Type: <class 'int'>

Height: 5.5
Type: <class 'float'>

Favourite Number: 7
Type: <class 'int'>

Your birth is approximately: 2006
```

## 📚 Python Concepts Used

### 1. String

The user's name is stored as a string.

```python
name = input("Please enter your name :-")
```

### 2. Integer

Age and favourite number are converted into integers.

```python
age = int(input("Please enter your age :-"))
favnumber = int(input("Please enter your favourite number :-"))
```

### 3. Float

Height is stored as a floating-point number.

```python
height = float(input("Please enter your height :-"))
```

### 4. Type Checking

The `type()` function is used to identify the data type of each variable.

```python
print(type(name))
print(type(age))
print(type(height))
print(type(favnumber))
```

### 5. Arithmetic Operation

The approximate birth year is calculated using:

```python
birthyear = 2026 - age
```

## ▶️ How to Run

### Step 1: Install Python

Make sure Python 3 is installed on your computer.

### Step 2: Clone the Repository

```bash
git clone https://github.com/prachi-kukadiya/interactive-data-collector.git
```

### Step 3: Open the Project

```bash
cd interactive-data-collector
```

### Step 4: Run the Python File

```bash
python Project-1/p-1.py
```

## 🌱 Learning Outcomes

After completing this project, you will understand:

* How to take input from users.
* How to create and use variables.
* The difference between `str`, `int`, and `float`.
* How type conversion works in Python.
* How to use the `type()` function.
* How to perform calculations using variables.
* How to display formatted information using `print()`.

## 🚀 Future Improvements

The project can be improved by adding:

* Email and phone number collection.
* Gender or city information.
* Better input validation.
* Automatic current-year detection instead of using a fixed year.
* Error handling for invalid inputs.
* A menu-based interface.
* Saving collected information to a file.

## 👩‍💻 Author

**Prachi Kukadiya**

📸 Output screenshots:
<img width="936" height="341" alt="image" src="https://github.com/user-attachments/assets/e8d2e552-9d91-47cf-899e-4ab9f61f2d1a" />
<img width="630" height="345" alt="image" src="https://github.com/user-attachments/assets/65f9fba1-0d44-4a72-b097-cb1a50697d18" />



GitHub: [prachi-kukadiya](https://github.com/prachi-kukadiya)


## 📄 License

This project is created for **learning and educational purposes**.

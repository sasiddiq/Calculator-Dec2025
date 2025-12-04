

# 🧮 Simple Java Calculator

A beginner-friendly console-based calculator program written in Java.
This program allows the user to input two numbers and choose an operation: **Addition, Subtraction, Multiplication, or Division**. It also includes basic input validation such as preventing division by zero.

---

## 🚀 Features

* Accepts **two numeric inputs** from the user
* Provides **four basic arithmetic operations**:

  * ➕ Addition
  * ➖ Subtraction
  * ✖️ Multiplication
  * ➗ Division
* Handles **invalid menu choices**
* Prevents **division by zero**
* Uses the `Scanner` class to take user input

---

## 📂 Code Structure

The entire program is contained within a single class:

```
Calculator
 └── main(String[] args)
```

Key components inside `main()`:

* Reading user input using `Scanner`
* Displaying operation menu
* Using conditional statements (`if-else`) to perform the selected operation
* Printing the result or error message

---

## 📝 How It Works

1. The program asks the user to enter the **first number**
2. Then asks for the **second number**
3. Displays a menu of operations:

   ```
   1. Addition
   2. Subtraction
   3. Multiplication
   4. Division
   ```
4. The user selects an option by entering a number (1–4)
5. The calculator performs the operation and prints the result
6. If the user enters an invalid choice or attempts division by zero, an appropriate error message is shown

---

## ▶️ Running the Program

1. Save the file as **Calculator.java**
2. Compile the program:

```
javac Calculator.java
```

3. Run the program:

```
java Calculator
```

4. Follow the prompts in the console.

---

## 📌 Example Interaction

```
Enter the first number
10
Enter the second number
5
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
3
Result: 50.0
```

---

## ⚠️ Error Handling

* If user selects an invalid menu option → `Invalid Choice`
* If user tries to divide by zero → `Error: Division by zero is not allowed`

---

## 💡 Future Improvements (Optional Enhancements)

* Support for more operations (modulus, power, etc.)
* Loop until user chooses to exit
* Input validation for non-numeric values
* Switch-case instead of if-else for cleaner structure



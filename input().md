# About input() function

---

## What is `input()`, what can it do?

- `input()` is a built-in Python function used to take input from the user.
- input("Enter your name: ") # This line displays the message "Enter your name:", and the program waits for the user to type something and press Enter.

---

## How is it written incorrectly, and how is it written correctly?

### ✅ Correct Way to Use `input()`

input("What is your name? ")

#### Explanation:

- `input` is the name of the function.

- "What is your name?" is the prompt shown to the user.

- The text must be in quotes.

- The function must include parentheses.

## ❌ Incorrect Examples and Errors

### 1. ❌ Missing parentheses:

input "What is your name?"

🛑 Error: `SyntaxError: invalid syntax`
✅ Correct: `input("What is your name?")`

### 2. ❌ No quotes around the text:

input(What is your name?)

🛑 Error: `NameError: name 'What' is not defined`
✅ Correct: `input("What is your name?")`

### 3. ❌ Capitalized `Input`:

Input("Enter something")

🛑 Error: NameError: `name 'Input' is not defined`
✅ Correct: `input("Enter something")`

### 4. ❌ Unclosed quotes:

input("What is your name?)

🛑 Error: SyntaxError: `EOL while scanning string literal`
✅ Correct: `input("What is your name?")`

### 5. ❌ Unclosed parentheses:

input("What is your name?"

🛑 Error: SyntaxError: `unexpected EOF while parsing`
✅ Correct: `input("What is your name?")`

---

## Example with `print()` and `input()`

- Code:
print("2+2=")
input("Enter the ansver: ")
Result:
2+2=
Enter the ansver: 4
- Code:
print("Hello,", input("What is your name: "))
Result:
What is your name: Abubakr
Hello Abubakr
# 📊 Grade Calculator

---

## 📌 Project Overview and Objectives

This project is a simple **Grade Calculator** built using Python. It allows users to input their marks and automatically calculates the corresponding grade along with a motivational message.

### 🎯 Objectives:

* To understand basic Python programming concepts
* To implement conditional statements (`if-elif-else`)
* To use loops for input validation
* To create a user-friendly command-line application

---

## ⚙️ Setup and Installation Instructions

### 🔹 Requirements:

* Python 3.x
* Google Colab 

### 🔹 Steps to Run:

#### Option 1: Google Colab

1. Open the `.ipynb` file in Google Colab
2. Click **Run All**
3. Enter marks when prompted

#### Option 2: Local Machine

1. Install Python
2. Download the project file
3. Run the script:

```bash
python grade_calculator.py
```

---

## 🧩 Code Structure Explanation

The project contains a single main function:

### 🔹 `grade_system()`

* Takes user input for marks
* Validates input using a `while` loop
* Uses `if-elif-else` conditions to assign grades

### 🔹 Logic Flow:

1. User enters marks
2. Program checks if input is valid (0–100)
3. If invalid → asks again
4. If valid → assigns grade:

   * 90–100 → Grade A
   * 80–89 → Grade B
   * 70–79 → Grade C
   * 60–69 → Grade D
   * Below 60 → Grade F

## ✅ Explanation of How Technical Requirements Are Met

✔ **User Input Handling**

* Used `input()` function to accept marks

✔ **Input Validation**

* Implemented `while` loop to ensure marks are between 0–100

✔ **Conditional Logic**

* Used `if-elif-else` statements to assign grades

✔ **Function Usage**

* Encapsulated logic inside `grade_system()` function

✔ **User Feedback**

* Displayed motivational messages for each grade

---

## 🎯 Conclusion

This project demonstrates fundamental Python skills such as input handling, loops, and conditional logic. It serves as a beginner-friendly application to understand real-world problem-solving using Python.

---

## 🙌 Author

**Zahadana Haneef**

  

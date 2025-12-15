**Student Result Calculator**

**Project Overview**:

The Student Result Calculator is a python based application that allows users to calculate and display individual subject grades, total marks & average marks for students. The application features a graphical user interface (GUI) built with Tkinter and supports 5 subjects along with roll.no input for each student.


This project is ideal for learning python programming, GUI design and sofware testing techniques, including Black Box Testing.



**Features:**

1. Input roll.no and marks for 5 subjects and marks for 5 subjets: Maths Physics Chemistry English & Bio

2. Automate grade calculation for each subject based on marks.

3. Total marks and average displayed for quick evaluation.

4. Individual subject grades displayed with subject names.

5. Error handling for invalid inputs, including:
    i) Missing roll.no or marks
   ii) Marks out of range(0-100)
  iii) Non Numeric Numbers

6. Simple and user friendly Tkinter GUI.


**Installation:**

1. Clone the repository:
   git clone <repo-url>

2. Navigate to the project Folder:
   cd StudentResultCalculator

3. Install Dependencies:
   pip install -r requirements.txt

4. Run the application:
   python app.py



**Usage:**
1. Enter the roll.no
2. Enter marks for each of the 5 subjects
3. Click the "Calculate" button
4. View the individual grades, total marks, and average in the GUI
5. For invalid inputs, the application displays appropriate error messages


**Grade Criteria:**

90-100 - A+
80-89 - A
70-79 - B+
60-69 - B
50-59 - C
40-49 - D
0-39 - F


**Testing:**

The application has been designed to support black box testing. Key test scenarios include :

    1. Valid Roll.no and marks
    2. Missing all roll.no or subject marks
    3. Marks out of range (negatuve or > 100)
    4. Non-numeric inputs
    5. Boundary cases (0 and 100) marks

Test cases can be found in tests/test_cases.txt



**License:**

This project is open-source and free to use for educational puposes.



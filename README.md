# TCL-Workshop-by-VSD
# TCL WORKSHOP: FROM INTRODUCTION TO ADVANCED SCRIPTING by VSD

![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/TCL-Workshop1-2048x1448.jpg?raw=true)

# Workshop content
- Day 1: Introduction to TCL and VSDSYNTH Toolbox Usage
- Day 2: Variable Creation and Processing Constraints from CSV
- Day 3: Processing Clock and Input Constraints
- Day 4: Complete Scripting and Yosys Synthesis Introduction
- Day 5: Advanced Scripting Techniques and Quality of Results Generation

# Tools Used:
- Yosys
- OpenTimer
- TCL development suite
- Libraries (associated with TCL)

## Day-1
- Task1: User doesn't provide an input CSV file
   - Input:![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day%201/Screenshot%202023-08-23%20113033.png?raw=true)
   - Output:![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day%201/Screenshot%202023-08-23%20220231.png?raw=true)
- Task2/3: User providing incorrect CSV or typing "-help"
   - Input: ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day%201/Screenshot%202023-08-23%20220811.png?raw=true)
   - Output: ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day%201/Screenshot%202023-08-23%20220539.png?raw=true)

## Day-2
- Task1: Variable Creation
- CSV File
  
 ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day2/csv%20file.png)
 
 ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day2/task1.png)
 
- Task2: Checking the existence of files and folders mentioned in design_details.csv
  
 ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day2/task2.png)
 
- Task3: Script thrown an error if wrong path was provided
  
 ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day2/task3.png)
 
- Task4: Compute row and column number using complex matrix processing

 ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day2/task4.png)
 
 ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day2/task4_1.png)

## Day-3

- Task1: Creating complete clock constraints

  - Code for generating clock constraints
    
   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day3/input%20code.png)

  - Terminal log output

   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day3/day3_task1.png)
  
  - Generated SDC File

   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day3/SDC%20file.png)
  
- Task2: Generation of input constraints generation and bits/bussed differentiation

   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day3/day3_task2.png)

  - Generated SDC File with Input Constraints

   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day3/input_delay.png)

## Day-4

- Task1: Generation of output constraints

   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day4/day4_task1.png)

  - Generated SDC File with Ouput Constraints

   ![image](https://github.com/aryavivek/TCL-Workshop-by-VSD/blob/main/Workshop%20Scripts/Day4/output%20delay.png)

## Task 3 Questions
![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![Python](https://img.shields.io/badge/Python-3776AB?logo=Python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyterlab-F37626?logo=Jupyter&logoColor=white)

### Questions on Dictionary :
1. Write a Python Program to sort (ascending and descending) a dictionary by value.

2. Write a Python Program to add a key to a dictionary. 
   ```{python}
      Sample Dictionary : {0: 10, 1: 20}
      Expected_Result : {0: 10, 1: 20, 2: 30} 
   ```
   
3. Write a  program asks for City name and Temperature and builds a dictionary using that Later on you can input City name and it will tell you the Temperature of that City.

4. Write a Python program to convert list to list of dictionaries. 
   ```{python}
      Sample lists: ["Black", "Red", "Maroon", "Yellow"], ["#000000", "#FF0000", "#800000", "#FFFF00"]
      Expected Output: [
                        {'color_name': 'Black', 'color_code': '#000000'}, 
                        {'color_name': 'Red', 'color_code': '#FF0000'}, 
                        {'color_name': 'Maroon', 'color_code': '#800000'}, 
                        {'color_name': 'Yellow', 'color_code': '#FFFF00'}
                       ]
   ```
   
5. We have following information on Employees and their Salary (Salary is in lakhs),
   |Employee|Salary|
   | :-:    |:-:   |
   |John	   |14    |
   |Smith	|13    |
   |Alice	|32    |
   |Daneil	|21    |

   1. Using above create a dictionary of Employees and their Salary
   2. Write a program that asks user for three type of inputs,
     - **print:** if user enter print then it should print all Employees with their Salary in this format,
    
    ```{python}
       John ==>14
       Smith ==>13
       Alice ==>32
       Daneil ==>21
    ```
    
      - **add:** if user input adds then it should further ask for an Employee name to add. If Employee already exists in our dataset then it should print that it exists and do nothing. If it doesn't then it asks for Salary and add that new Employee/Salary in our dictionary and print it
      - **remove:** when user inputs remove it should ask for an Employee to remove. If an Employee exists in our dictionary then remove it and print a new dictionary using format shown above in (a). Else print that Employee doesn't exist!
      - **query:** on this again ask the user for which Employee he or she wants to query. When a user inputs that Employee it will print the Salary of that Employee.
 
#### Questions on Sets :   
1. What is the difference between a set and a frozenset? Create any set and try to use frozenset(setname).  
2. Find the elements in a given set that are not in another set

    ```{python}
       set1 = {10,20,30,40,50}
       set2 = {40,50,60,70,80}
    ```
    Difference between set1 and set2 is `{10,20,30}`.

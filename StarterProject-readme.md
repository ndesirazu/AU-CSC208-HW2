For this assignment imagine you are a software engineer who has been tasked with design and development of an employee management software for a company. You use object-oriented design principles to develop the software.

You first implement a **Person class** that will hold such details as First Name, Last Name, Date of Birth, and any other details that you feel are necessary at this level.

You then implement an **Employee class as a child of the Person class**. The Employee class in addition to all the details of the Person class will hold additional details such as Employee ID (this is a randomly generated number between 1 and 999, and no two employees can have the same employee ID), Year of Join, Department, Supervisor name, Current Salary, Last increment date, last increment percentage and any other details as you deem necessary. In addition to the getter setter methods you also implement a few additional methods such as show employee info that presents the employee information in a readable format. You will also implement the following method: 
          1.	Increase salary – this method takes a percentage and increases the salary by that percent. You will include try-except error handling to ensure                that the %age increase value is not 0 or a negative number. The method will consider the last date of increase and will administer an increase                 only if the last increase was more than a year ago. If the last increase was less than a year ago you will provide a message as to why the                     increase cannot happen at this time. If the increment does happen then you will update the last increment date with today’s date.
              a.	Write unit tests to test all possible conditions of this method


You will create an **EmployeeManager class** that will maintain all the employees. This is a container class. This class will allow you to add new employees, remove an employee and free up the employee ID to be reused, search for an employee based on their Employee ID, find all employees who are ready for the 10-year employee bonus based on their year-of-join.

Finally create a **‘main’ program** file that implements a EmployeeManager class provides a menu option (as learnt in class) that will allow a user to manage employees of this company. 

Ensure that each of the classes is defined in its own python file. Use any additional python built-in modules as necessary. Do not use any modules that are not built-in into the interpreter. 

Provide code comments as necessary to enable someone to understand the logic of your code (the more the better).

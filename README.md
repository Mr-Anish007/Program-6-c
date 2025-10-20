# Program-6-c
## C-Module 6
## EX_NO-06)c)-User Defined Datatype
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
C program to read and print an employee's detail using structure
## ALGORITHM:
1. Start the program.
2. Define a structure named employee with three members: 

    a. name (character array of size 20)  

    b. id (integer)  

    c. salary (float)  

3. Declare a variable of type struct employee.
4. Read the employee details (name, id, salary) from the user using scanf.
5. Print the entered details using printf in a formatted manner.
6. End the program.

## PROGRAM:
```
#include<stdio.h>
    struct employee
    {
        char name[20];
        int id;
        float salary;
    };
    int main()
    {
        struct employee e1;
        scanf("%s %d %f",e1.name,&e1.id,&e1.salary);
        printf("Entered detail is:\nName: %s\nId: %d\nSalary: %.2f",e1.name,e1.id,e1.salary);
    }
```
## OUTPUT:
<img width="841" height="259" alt="Screenshot 2025-10-20 094133" src="https://github.com/user-attachments/assets/b0f39204-1fc6-4965-8181-47027eda4994" />

## RESULT:
Thus the program to read and print an employee's detail using structure has been executed successfully

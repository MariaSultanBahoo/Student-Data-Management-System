The Student Data Management System has been made by using the C++ language. The program uses C++ syntax including
1.Structures: To make a record
2.Arrays: may be used in program may be in a structure.
3.Loops: To add multiple records.
4.Pointers: Use some functions to pass values by address
5.Files: To store the data on permanent storage
->Features & Applications:
A user can log into this system and Enter, Display, Update, Search and Delete student records. A user can also exit the entered data. The purpose of this management system is to keep a record of students’ data and make the editing process easier. The Student Data Management System can be beneficial for educational institutes like schools, colleges and universities.


                                                             ->DETAILS ABOUT THE PROJECT

->HEADER FILES USED:

#include<iostream>  ---- USED FOR INPUT OUTPUT DISPLAY 
 
#include<windows.h> ----USED FOR SLEEP() FUNCTION IN THE PROGRAM                                                        
                                                
#include<conio.h>  ------ USED FOR getch() and (“CLS”) 

#include<fstream>  ------ USED FOR FILE CREATION

 #include<string>  ----- USED FOR USING STRINGS

->RUNNING OF THE PROGRAM:
The programs starts by showing the names of the group members who created the program.
This is done by the use of pointers to copy the name of the group members to the  character string.
Next the program askes the user to sign up by enter the username and password on the console screen. The program then compares the entered data by using conditional statements and checks it when the user is asked to log into the system. 
When the log in is successful the MENU screen is displayed having 7 options. By the use of switch case statements the user can enter any number and the program will take the use to the selected option. The selected option is opens. This happens when the corresponding function is called by the switch case statements.

->MENU OPTIONS AND FUNCTIONS:

On pressing 1 the user is asked to enter the data by the use of Enter_data function. Here is where structures come into the picture. The structure in this program is able to store data of 50 students. This option uses the structures to store the info of the students, the info is of different data type so the use of structure allows to store it efficiently.
On pressing 2, the entered data is displayed when the function Display_data is called. Again the data stored by the use of structures is displayed on the screen.
On pressing 3, Update_data function is called and the  user is asked to enter the ID of the student they want to update the data of. The ID is checked in the existing data (stored by the use of structures).
If the ID doesn’t match the program shows “No such  record found”. When ID matches the user can enter new data. 
On pressing 4, Search_data function is called. The program asks for ID and when the ID matches the student data previously stores is displayed on the console.
On pressing 5, Delete_data function is called. The function shows two option first to delete all the entered record in the structure or to delete a specific record. ID is entered and the for loop runs to find the entered id and matches it with the specific data stored in the structure. When the specific data is deleted the loop replaces the index numbers of the data and this allows the organization of the data .
On pressing 6, the Logout_data function is called and with the logout option the data can be deleted from the system. 
On pressing 7, the login function is called. And the user can again log into the system.

->USE OF FILES:
The file used in the program is the fstream file. It allows to read and write data. The opening mode of the file is (ios::app) append. The use of this opening mode appends the entered data in the text file created in the computer memory.

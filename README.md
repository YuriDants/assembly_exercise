# Assembly Exercise
1. Write a program in Assembly for MIPS, which when simulated performs the following operations:
<br>a) Send the message: "Type your registration number";
<br>b) Receive 9 numerical digits corresponding to a registration number;
<br>c) If the registration number is all zero, end the program (call the system with the exit operation)
<br>d) Search the registration numbers stored as constants in the program
<br>&nbsp;&nbsp;&nbsp;&nbsp;d.1) If you find the registration number, present the text:
"The registration number XXXXXXXXXXXXX corresponds to the student YYYYYYYY."
<br>&nbsp;&nbsp;&nbsp;&nbsp;d.2) If you cannot find the registration number, present the text:
"The registration number XXXXXXXXX was not found"
<br>&nbsp;&nbsp;&nbsp;&nbsp;d.3) If the registration number corresponds to your registration number, present the text:
"It's me! I'm YYYYY YYYYY YYYY, and I have registration number XXXXXXXXX"
<br>e) Go back to step a;
<br>
<br><b>Additional Information:<b>
<br>&nbsp;&nbsp;&nbsp;&nbsp;i. the list of names and registration numbers of students in the class will be upload on this repository;
<br>&nbsp;&nbsp;&nbsp;&nbsp;ii. Names must be stored using .asciiz and registration numbers must be stored as a 32-bit integer, formatted as BCD, that is, every 4 bits we have a decimal digit. The first license plate number is always 1 and must not be stored. Example number plate: 112345678 will be stored in hexadecimal
as
12345678h (binary 0001_0010_0011_0100_0101_0110_0111_1000);
  <br><h1> in this repository I will present 4 methods to solve this problem.<h1>

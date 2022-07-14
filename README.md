# StudentGrader
Grading Program

Write a grading program for a class with the following grading policies:

a. There are three quizzes, each graded on the basis of 100 points. 
The lowest quiz score is dropped.

b. There is one midterm exam, graded on the basis of 100 points.

c. There is one final exam, graded on the basis of 100 points.

The final exam counts for 45% of the grade. The midterm counts for 35% of the grade. 
The three quizzes together count for a total of 20% of the grade; the lowest quiz
score is dropped. 

Any grade of 90 or more is an A, any grade of 80 or more (but less than 90) is a B,
any grade of 70 or more (but less than 80) is a C, any grade of 60 or more
(but less than 70) is a D,and any grade below 60 is an F.

The client program should read in the student’s name and scores and output the student’s record, 
which consists of three quiz scores and two exam scores, as well as the student’s overall numeric
score for the entire course and final letter grade.

Sample run:
Enter student's name:
Ada Lovelace
Enter the three quiz scores:
90 50 80
Enter the midterm score:
70
Enter the final exam score:
75

StudentRecord created...

Student: Ada Lovelace

quiz1: 90     
quiz2: 50      
quiz3: 80     
midterm: 70      
final exam: 75         
overall grade: 75.25            
letter grade:  C          

Define and use a class for the student record. The class should have instance variables for their
name, quizzes, midterm, and final exam. 

The overall numeric score is a decimal number in the range 0 to 100, which represents the weighted
average of the student’s work. The class should have methods to compute the overall numeric 
grade and the final letter grade. Your class should have a toString method that returns
a String representation of the StudentRecord object. You may add other methods if you wish.

Note: You should have two classes for this program. One class will be 
called ```StudentRecord.java``` to encapsulate the student's record along with any methods
that operate on this data. A second class will be the client class, 
called ```StudentGrader.java```.  The client class will contain the main() method.

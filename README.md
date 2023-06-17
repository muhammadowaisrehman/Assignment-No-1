# Assignment-No-1
void main () {
// Student Name: Muhammad Owais

// question no 1: Create two integer variables length and breadth and assign values then check if they are square values or rectangle values.
ie: if both values are equal then it's square otherwise rectangle.

 int length = 10;
 int breadth = 20;
if(length==breadth)
{print("square");}
else
{print("rectangle"); }

//output = rectangle

//   question 2: Take two variables and store age then using if/else condition to determine oldest and youngest among them.

  int saqib = 19;
  int owais = 18;
  if(saqib>owais){
    print("saqib is older and owais is younger");
  }else if(saqib == owais){
    print("both are equal ");
  }else{
    print("saqib is younger and owais is older");
  }

//output = saqib is older and owais is younger

//   question 3: A student will not be allowed to sit in exam if his/her attendance is less than 75%. Create integer variables and assign value:
Number of classes held = 16,
Number of classes attended = 10,
and print percentage of class attended.
Is student is allowed to sit in exam or not?

int numofclassheld = 16;
 int numofclassattended = 10;
  double percentage = (numofclassattended/numofclassheld)*100;
 print("$percentage %");
  if (percentage<75)
{print("not allowed to sit in exam");}
 else
{print("allowed in exam");}  

//output = 62.5 %
not allowed to sit in exam

//   question 4: Create integer variable assign any year to it and check if a year is leap year or not.
If a year is divisible by 4 then it is leap year but if the year is century year like 2000, 1900, 2100 then it must be divisible by 400.
i.e: Use % ( modulus ) operator.

  num year = 1992;

  if (year % 4 != 0) {
    print('$year is a common year.');
  } else if (year % 100 != 0) {
    print('$year is a leap year.');
  } else if (year % 400 != 0) {
    print('$year is a common year.');
  } else {
    print('$year is a leap year.');
  }

//output = year is a leap year
//   question 5: Write a program to read temperature in centigrade and display a suitable message according to temperature:
You have num variable temperature = 42;
Now print the message according to temperature:
temp < 0 then Freezing weather
temp 0-10 then Very Cold weather
temp 10-20 then Cold weather
temp 20-30 then Normal in Temp
temp 30-40 then Its Hot
temp >=40 then Its Very Hot

num temp = 40;
if(temp<0){
  print("freezing weather");}
  else if(temp>0 && temp <10){
  print("very cold weather");}
  else if(temp>10 && temp <20){
  print("cold weather");}
  else if(temp>20 && temp <30){
  print("normal in temp");}
  else if(temp>30 && temp <40){
  print("its hot");}
  else if(temp>=40){
  print("its very hot");}

//output = its very hot
//   question 6: Write a program to check whether an alphabet is a vowel or consonant.

String alphabet = "a";
  if(alphabet =="a" || alphabet =="e" || alphabet =="i" || alphabet =="o" || alphabet =="u")
  {print("vowel");}
  else
  {print("consonent");}
//output = its vowel

//   question 7: Write a program to calculate and print the Electricity bill of a given customer. Create variable for customer id, name, unit consumed by the user, bill_amount and print the total amount the customer needs to pay. The charge are as follow :

Unit    Charge/unit
upto 199    @1.20
200 and above but less than 400    @1.50
400 and above but less than 600    @1.80
600 and above             @2.00;

Test Data :
id: 1001
name: James
units: 800
Expected Output :
Customer IDNO :1001
Customer Name :James
unit Consumed :800
Amount Charges @Rs. 2.00 per unit : 1600.00
Net Bill Amount : 1600.00

int CustomerIDNO = 1001;
String CustomerName = "James";
int unitConsumed = 800;
double AmountChargesRsPerUnit = 2.00; 
 if(unitConsumed<=199)
 {print(unitConsumed*1.20);}
  else if(unitConsumed>=200 && unitConsumed<400)
  {print(unitConsumed*1.50);}
   else if(unitConsumed>=400 && unitConsumed<600)
  {print(unitConsumed*1.80);}
   else if(unitConsumed>=600)
  {print(unitConsumed*2.00);}
//output = 1600

//   question 8: Create a marksheet using operators of at least 5 subjects and output should have Student Name, Student Roll Number, Class, Percentage, Grade Obtained etc.
i.e: Percentage should be rounded upto 2 decimal places only.

String studentName = "OWAIS";
  int rollNumber = 12345;
  String className = "10TH";
  int physicsMarks = 85;
  int chemistryMarks = 92;
  int mathMarks = 78;
  int englishMarks = 88;
  int computerMarks = 90;

  int totalMarks = 500;
  int obtainedMarks = physicsMarks + chemistryMarks + mathMarks + englishMarks + computerMarks;
  double percentage = (obtainedMarks / totalMarks) * 100;
  

  if (percentage >= 90) 
  {print("Grade Obtained:A+");} 
  else if (percentage >= 80) 
  {print("Grade Obtained:A");} 
  else if (percentage >= 70) 
  {print("Grade Obtained:B");}
  else if (percentage >= 60)
  {print("Grade Obtained:C");} 
  else if (percentage >= 50) 
  {print("Grade Obtained:D");} 
  else 
  {print("Grade Obtained:F");}

  print("Student Name: $studentName");
  print("Roll Number: $rollNumber");
  print("Class: $className");
  print("Percentage: $percentage%");

//output = Grade 
Obtained:A
Student Name: OWAIS
Roll Number: 12345
Class: 10TH
Percentage: 86.6%


//   question 9: Check if the number is even or odd, If number is even then check if this is divisible by 5 or not & if number is odd then check if this is divisible by 7 or not.

int number = 25; 

  if (number % 2 == 0) 
  {print("The number is even.");}
   else 
   {print("The number is odd.");}

  if (number % 5 == 0) 
    {print("The number is divisible by 5.");} 
   else
    {print("The number is not divisible by 5.");}

  if(number % 7 == 0)
    {print("The number is divisible by 7.");}  
  else 
  {print("The number is not divisible by 7.");} 

//output = 
The number is odd.
The number is divisible by 5.
The number is not divisible by 7.

//   question 10: Write a program that takes three numbers from the user and prints the greatest number & lowest number.


//output = 

//   question 11: Write a program to calculate root of any number.
i.e: √y = y½


//output = 

//   question 12: Write a program to convert Celsius  to Fahrenheit   .
i.e: Temperature in degrees Fahrenheit (°F) = (Temperature in degrees Celsius (°C) * 9/5) + 32


//output = 




}

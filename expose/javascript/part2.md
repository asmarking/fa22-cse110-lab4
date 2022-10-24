1. it will print "3" to the console since i was decalred using var its scope is the
   whole function.
2. It will print "150" ot the console since disocuntedprice was declared with var its 
   scope is the whole function
3.  It will print 150 to the console since finalPrice has scope of the whole fucntion
4. returns an array cotaining [50,100,150] because those are the values pushed to 
   discounted during the for loop and the scope of discounted is the whole function
5. Error because i is out of scope, since i was declared with let its scope is
   just the for loop
6. error because discoutend price is out of scope
7. 150 will be printed to the console because finalPrice is in scope
8. returns an array cotaining [50,100,150] since discounted has scope of the function discountPrice. 
9. this will cause an error because i is out of scope (its scope is just the for loop
    block)
returns an array cotaining [50,100,150] since discounted has scope of the entire discountPrice function. 

DATA TYPES
12. 
  a) student.name
  b) student["Gread Year"]
  c) student.greeting()
  d) student["favorite teacher"].name
  e) student.courseLoad[0]

BASIC OPERATORS AND TYPE CONVERSION
13.
 A. '32' since since 3 is of type string it converts to string and concatenates
 B. returns 1 since there is no string operation using '-' js turns the 3 into a number
 C. returns 3 since 3 is a number it converts null to a number 
 D. returns '3null' since '3' is a string it treats null as a string
 E. returns 4 since true maps to 1
 F. returns 0 since false maps to zero and null is turned to a number
 G. returns 3undefiend since '3' is a string it convert undefined to a stirng
 H. returns Nan since theres no operation like this for strings
14.
 A.‘2’ > 1 returns true since when comparing different types js turns them into numbers
 B.‘2’ < ‘12’ returns false since 2 > 1
 C. 2 == ‘2’ returns true since both are converted to numbers
 D. 2 === ‘2’ returns false since they are of different types
 E. true == 2 returns false since true == 1
 F. true === Boolean(2) returns true since boolean2 evaluates to 1
15. == converts the variable values to the same type before performing comparison, whereas === does not.
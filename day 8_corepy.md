                        CORE OF PYTHON PROGRAMMING
            Indexing
        ● On lists, we have seen about index numbers.
           language=["python","swift","c++"]
                      "python"  "swift"   "c++"
            index->      0         1        2
        ● Negative indexing
                    "python"   "swift"    "c++"
    negative index->   -3         -2        -1          
            Note: The list index always starts with 0. Hence, the first element of a list is present at index 0, not 1.
        Cont…
        ● Calling texts by indexes also works for strings & tuples
           example ->   name=('hello',22,23)
                        print(name[2])   #output: 22
                                Slicing
        ● In Python it is possible to access a section of items from the list using the slicing operator ‘ : ‘ , not just a single item. 
        ● Syntax: 
              ○ Mylist[ start : stop : step ] 
        ● Slicing is indexing syntax that extracts a portion from a list. If a is a list, then a[m:n] returns the portion of a: 
             ○ Starting with postion m                       example-> name=('no 1 is nathan)  
             ○ Up to but not including n                               print(name[8:14:1])
             ○ Negative indexing can also be used                       #output: nathan
        ● It is more applicable for strings.
        ● Python uses default step as 1, sometimes no need to tell/put it 
        ● Also default stopping index is the ﬁnal, still no need to tell for this kinda purpose
            Cont…
         There are more writing features.
       examples-> name=('ethiopia','kenya','apple')
                print(name[::])     #output: all list      
                          User Input handling
             ● On python there are 2 types of inputs 
                 ○ By input function 
                 ○ By Arguments 
    1) By input functions, 
       ○ Syntax:    var = input(“Text you like to display: ”) 
       ○ Will accept the input and stores on variable
           eg-> name=input("what is your name?\n name: ")      #output:   what is your name? name:'nathan'
                 print(f"hello {name}!")                                   hello nathan!                  
              Cont…
          You can change the input type to int() ﬂoat() eval() str()….
             Cont…
    2) Arguments
         ● This help us to get the input from the command lines 
         ● Shell: python gtst.py arg1 arg2 arg3 
          ● Syntax:  important sys
                      name=sys.arg[1]
                      print(f"hello{name}!")  this out put is in terminal first name
            Cont…  
           ● Have You seen the output? 
               ○ We entered -> Nathan Hailu 
               ○ Output: Hello Nathan! 
                Further…
         -> You can do more inputs
         -> You can create variable until n times 
                                  Operators
          ● Operators are special symbols that perform operations on variables and values. 
          For example, 
          ● There are lots of operators type on python: 
          a. Arithmetic operators 
          b. Assignment Operators 
          c. Comparison Operators 
          d. Logical Operators 
          e. Bitwise Operators 
          f. Special Operators
        A) Arithmetic Operators They are a simple maths operations
           -> Inputs have to be in int,eval, ﬂoat only
        B) Assignment Operators
           ● Assignment operators are used to assign values to variables 
           ● You do the arithmetic operators 1st , then the equal sign.
        C) Comparison operators
           ● Used to compare to variables and return boolean result 
           ● Boolean means either  TRUE or FALSE 
        D) Logical Operators
           ● They are used to check if an expression is TRUE or FALSE ● They use Truth tables to compare. 
                Truth table for and / እና  ( && )
           ● Only True and True is True
             Truth table for or / ወይም  ( || ) 
           ● Only False and False is False
             Truth table for not / አይደለም
           ● It is just opposite.
        E) Bitwise Operators
           ● Computers Work with Binarys 
           ● On our computer everything have a binary value.  ( also called bit) 
           ● On python there is a keyword called bin(YourDecimal) this helps to Show you the binary value of YourDecimal 
           ● True have a value of 1 
           ● False have a value of 0 
           ● Bitwise Operators Used to do maths(Logical operations) on The binary value of The expression. 
           ● There are ○ Compliment ( Not) (~) 
            ○ And ( & ) 
            ○ Or ( | ) 
            ○ Xor ( ^ ) 
            ○ Left Shift (<<) 
            ○ Right shift (>>) If you work on CryptoGraphy on hacking this is must!
                Complement( NOT ) ( ~ )
          ● It will convert the ﬁrst value to binary  and it will reverse each bit then converts to decimal. 
          ● In simple maths, it will add 1 to the number and then makes it negative.
                     And( & )
          ● You can add 0 before the binary of any number if it is not 4 digit binary 
          ● bin(7)  -> 111  , but we can do 0111 too
                     OR ( | )
          -> SAME AS AND but the logic operator will be changed.
                     XOR ( ^ )
          ● It is like and , or but the difference is the logic here is 
            ○ If they are same = 0     1^1 = 0    ,    0^0 = 0 
            ○ If they are different = 1     1^0  =  1     ,   0^1  = 1
                   Left Shift ( << )
         ● Every Numbers have .0 at the end   
           =>    1.0 ,32.0 ….
                Right shift ( >> )
                    indentations
        ● Are Just a WhiteSpace which python uses for some of its function. If there is no proper indentation error then you are doomed. 
                     If-else conditions
        ● In computer programming, we use the if statement to run a block code only when a certain condition is True.
             -> For example, assigning grades (A, B, C) based on marks obtained by a student. 1. if the percentage is above 90, assign grade A 2. if the percentage is above 75, assign grade B 3. if the percentage is above 65, assign grade C 
        ● In Python, there are three forms of the if...else statement. 1. if statement 2. if...else statement 3. if...elif...else statement
                    If statement 
        ● The if statement evaluates condition. 
            ○ If condition is evaluated to True, the code inside the body of if is executed. 
            ○ If condition is evaluated to False, the code inside the body of if is skipped. 
                            Indentation
                  If…else statement
          -> An if statement can have an optional else clause.
          -> The syntax of if...else statement is:
                 If…elif…else Statement
            1. Here, 
            2. If condition1 evaluates to True, code block 1 is executed. 
            3. If condition1 evaluates to False, then condition2 is evaluated. 
            4. If condition2 is True, code block 2 is executed. 
            5. If condition2 is False, code block 3 is executed.
                Nested if statements
        ● We can also use an if statement inside of an if statement. This is known as a nested if statement. 
        ● Here two requirements have to be true to run the body of condition2 
                              Logical Errors ( Exceptions)
        ● Errors that occur at runtime (after passing the syntax test) are called exceptions or logical errors. 
        ● For instance, they occur when we ○ try to call an index that is greater than the list have causes ( IndexError ) 
           ○ try to divide a number by zero (ZeroDivisionError) 
           ○ When you have error on your syntax (NameError) and so on. 
        ● So specially when errors occur on runtime this causes a huge damage on our program so we have to handle it.
                  Error handling
            ● For handling errors we use try…except blocks.
                    Python Loops
           ● In computer programming, loops are used to repeat a block of code. 
           ● For example, if we want to show a message 100 times, then we can use a loop. And print(100) It's just a simple example; you can achieve much more with loops. 
           ● There are 2 types of loops in Python: 
                 ○ For Loop 
                 ○ While Loop
                        For loop
            ● In Python, the for loop is used to run a block of code for a certain number of times. It is used to iterate over any sequences such as list, tuple, string, etc.
            ● Syntax:  
                   ○ Sequence is a list,tuple,string or range. 
                   ○ Val is a variable which will hold the iteration from the sequence.
                Cont…
            -> %% Range keyword
           -> A range is series of values between two numeric intervals.    range(size)
             -> %% len keyword
                -> A len is used to show the length of a sequence may be list,tuple or stafﬁng.     
                len(list)
              While loops
             ● Python while loop is used to run a speciﬁc code until a certain condition is met.
           Cont…
        1) You can do inﬁnite loops
           Difference between for and while 
                 ● The for loop is usually used when the number of iterations is known. 
                 ● And while loop is usually used when the number of iterations are unknown. When we have condition. 
                 ● If you have a case that wanted to check level of a user and displays “ you have passed {n}th level” n is sequence. Until the user level and the class level is equal. What do u do?
                ● For loops: ends when the iterable is ﬁnished. 
                ● While loops: end when the condition is false.
                          break
                Break used to exit from an inﬁnite loop
             -> Write a program that helps to check a code , if the users errors are 5 close the program and display “ try again next time” else repeat and ask the code
<h1>Creating a Simple Password Strength Checker: In Python</h1>


 ### [Medium Blog ](https://medium.com/@michaellopezcs17/creating-a-simple-password-strength-checker-in-python-30656096ade8)


<h2>Description</h2>
<b>In this repository i’m going to show you how i created this script in python that prompts the user to enter password and checks against a set of predefined rules for password strength.
</b>
<br />
<br />
<p align="center">
<img src="https://imgur.com/ciwlCWa.png" (https://imgur.com/ciwlCWa ) height="85%" width="85%" Python photo"/>
</p>







<h2>Things we need to implement</h2>

<b>1.Minimum length of 12 characters.</b>

<b>2.At least one lowercase letter.</b>

<b>3.At least one uppercase letter.</b>

<b>4.At least one digit.</b>

<b>5.At least one special character.</b>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/D9Et6GZ.png" (https://imgur.com/D9Et6GZ) height="85%" width="85%" alt="Python Scripts"/>
</p>
<p align="center">
<img src="https://i.imgur.com/ExIET0F.png" (https://imgur.com/ExIET0F ) height="85%" width="85%" alt="Terminal Results"/>
</p>
<b>Meaning of Keywords:

1. Import re. Line 2

Re: A regular expression (or RE) specifies a set of strings that matches it; the functions in this module let you check if a particular string matches a given regular expression (or if a given regular expression matches a particular string, which comes down to the same thing).

2.Input function: Ex: password = input (“Enter Your Password. “) Line 5

The input function is used to ask the user of the program (not the programmer) a question, and then wait for a typed response. The typed number is then returned as the result of the function, and should usually be stored in a variable.

3.Using “if”: Ex: if len(password) < 12: Llines 6, and 19.

An “if” statement is a condition statement used to check a condition, and execute it if the condition holds true. It is also a control flow statement, which utilizes decision-making to control the flow of execution.

4. Print(): EX: print(“Password must be at least 12 characters long.”) Lines 7,10,13,16,and 20.

The print() function prints the specified message to the screen, or other standard output device. The message can be a string, or any other object, the object will be converted into a string before being written to the screen.

5.elif: Ex: elif not re.search(“[A-Z]”, password): Lines 9,12, and 15.

elif is short for “else if” and is used when the first if statement isn’t true, but you want to check for another condition.

6. Else: Ex (“Strong: Password meets the criteria.”)

The else keyword is used in conditional statements (if statements), and decides what to do if the condition is False.

[In The Terminal] it Shows Password Input and Checks the password against Predefined Rules for strength.

The Results: Checks Out.
</b>






 

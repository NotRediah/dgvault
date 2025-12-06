---
{"dg-publish":true,"permalink":"/week-1-c/","created":"2025-12-06T14:10:04.474+05:00","updated":"2025-12-06T14:35:47.073+05:00"}
---

# Hello World
![image-9.webp](/img/user/zawaruto-assets/attachments/image-9.webp)
- Difference between print and printf
	can format with printf
- /n
	escape sequence that creates a new line
- Header Lines (e.g studio.h)
	  includes libraries
- how would you go abuot typing '',\,"" inside of the printf function 
	  you use a backlash before it  
	  e.g 
	  ![Screenshot_20251206-132245.jpg](/img/user/zawaruto-assets/attachments/Screenshot_20251206-132245.jpg)
```  
{

    printf("hello, \"world\"\n");

}
```


> [!NOTE] Note
> For libraries manual pages (manpages) do exist and cs50 makes shit easier for you [here](manual.cs50.io)
# Ask user for name
  ![image-10.webp](/img/user/zawaruto-assets/attachments/image-10.webp)
```
  # include <stdio.h>
# include <cs50.h>

int main(void)
{
    string answer = get_string("What's your name? ");
    printf ("hello, %s\n", answer);
}


```
-  here %s represents the place holder for the string and other inputs can be separrated by comma in printf func e.g
```
{
printf ("you are gay","sissy"); 
} 
```
- the above code is actually incorrect dumbass and here's why
	This C code is **not valid** because the `printf` function is called with the wrong number of arguments and an incorrect **format specifier**.

	The line in question is:
	
	```
	printf ("hello, \n", "sisy");
	```
	
	Here's a breakdown of the two main issues:
	
	### 1. 🛑 Incorrect Format String
	
	The **format string** is the first argument to `printf`, which is `"hello, \n"`.
	
	- A format string can contain ordinary characters (like `h`, `e`, `l`, `l`, `o`, `,`, and space) which are printed as is.
	    
	- It can also contain **format specifiers**, which start with a percent sign (`%`), such as `%d` (for an integer) or `%s` (for a string).
	    
	
	Your format string, `"hello, \n"`, contains **no format specifiers**. It only includes the text "hello, " and a newline character (`\n`). This means `printf` expects **only one argument**: the format string itself.
	
	### 2. 🔢 Too Many Arguments
	
	Since the format string contains no specifiers, `printf` is expecting only one argument. However, you provided **two arguments**:
	
	1. The format string: `"hello, \n"`
	    
	2. An extra string literal: `"sisy"`
	    
	
	When the number of arguments doesn't match the number of format specifiers, it leads to **Undefined Behavior** (a critical error). The compiler detects this mismatch and signals that the code is invalid.
	
	---
	
	### ✅ The Fix
	
	To make the code valid, you should either remove the extra argument or include a format specifier to accept the argument.
	
	#### Option A: Correctly Print "hello, " (Simplest Fix)
	
	Remove the unused string `"sisy"`:
	
	C
	
	```
	#include <stdio.h>
	
	int main(void)
	{
	    printf ("hello, \n"); // Only one argument (the format string)
	    return 0; // It's good practice to return 0 from main
	}
	```
	
	#### Option B: Print "hello, sisy"
	
	Include the `%s` format specifier to correctly print the string `"sisy"`:
	
	C
	
	```
	#include <stdio.h>
	
	int main(void)
	{
	    printf ("hello, %s\n", "sisy"); // Two arguments: format string with %s, and the string to insert
	    return 0;
	}
	```
	
	This version would correctly output:
	
	```
	hello, sisy
	```
# Conditionals
![Screenshot_20251206-140755.jpg|466x209](/img/user/zawaruto-assets/attachments/Screenshot_20251206-140755.jpg) 
```
if (x < y)
{

}
else if (x > y)
{

}
else if (x == y)
{

}
```
- Why the double equal ==
	that's because equal is also used to assign a return valude e.g in
	```
 	string answer = get_string("What's your name? ");
 	```
- Why is this code not optimal
	- equal argument at the end isn't need if it isn't greater or less than it can only be equal
	```
		  
	if (x < y)
	{
	printf(" x is smaller to y")
	}
	else if (x > y)
	{
	printf(" x is greater to y")
	}
	else 
	{
	printf(" x is equal to y")
	}
	```
# Operators

![image-14.webp|466x247](/img/user/zawaruto-assets/attachments/image-14.webp)
```
- = return value
- < less than
- <= less than or equal to
- > greater than
- >= greater than or equal to
- == equal to
- != not equal to
```
- = 
- < 
- <= 
- > 
- >= 
- == 
- != 

> [!NOTE] Note
> ! exclamation mark a.k.a bang is generally used to invert operators

# Variables
 
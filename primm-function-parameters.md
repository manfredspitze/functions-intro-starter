**PRIMM / Python /** **Functions & Parameters**

**Objectives:**

* Students will be able to explain the difference between a function parameter and a function argument  
* Students will be able to write a Python function that takes one or more parameters  
* Students will be able to write a Python function that returns a value

**Task 1 / Predict / Pairs**

*Study the code snippet below and write out what you think the code will do when you run it.*

```python
function average_score(score1, score2):
     total_points = score1 + score2
     num_scores = 2
     average_score = total_points / num_scores
     return average_score

print(f'Your quiz average is: {average_score(85, 92)}')
```

| *Your prediction…* |  |
| :---- | ----- |

**Task 2 / Run**

Download and run the starter code in your code editor.  Does the code behave as you predicted it would?  If not, what changes could you make to the code so that it does run as expected?

| *Your answer…* |  |
| :---- | ----- |

**Task 3 / Investigate / Pairs**

*Several new concepts are part of this script.  With your assigned partner, answer the following questions after you’ve discussed the code with one another and run the script a few times to see what it does.*

```python
def get_formatted_name(first_name, last_name, middle_name=''):
    if middle_name:
        full_name = f"{first_name} {middle_name} {last_name}"
    else:
        full_name = f"{first_name} {last_name}"
    return full_name.title()
    
musician1 = get_formatted_name('jimi', 'hendrix')
print(musician1)

musician2 = get_formatted_name('john', 'jenkins', 'lee')
print(musician2)

```

| What is the name of the function used in the code snippet? |
| :---- |
| ***Answer…*** |
| Name the parameters used in the script. |
| ***Answer…*** |
| Which arguments are passed to the function for the first musician? |
| ***Answer…*** |
| Which arguments are passed to the function for the **second** musician? |
| ***Answer…*** |

**Task 4 / Modify / Pairs**  
**In pairs**, complete these challenges:

1. Write a function that takes one parameter, first_name.  The function should print to the screen a welcome message.  The message should welcome the user by their first name to Career Tech.  Make sure the user’s first name is capitalized correctly in the welcome message, even if the user passes the first name to the function in all lowercase characters.  

```py
# The correct output should be something like this:
Welcome to Career Tech, Alyssa! 
# The output below is not the correct output
Welcome to Career Tech, alyssa!
```

2. Write a function, **convert_height()**, that takes one parameter, *height\_in\_inches*.  The function should convert the user’s height from inches to centimeters and display on the screen the user’s height in centimeters.  Use an f-string to create your output string.

3. **Extension:** Write a function named `mini_bio` that takes two parameters, *city* and *citizenship*.  The *citizenship* parameter should have **a default value of Canadian**.  The function should display on the screen a sentence that says what city the user lives in and what citizenship they hold.  For example:  
* Elizabeth lives in Toronto and has Canadian citizenship.  
* Michael lives in San Francisco and has British citizenship.

	**Call the function at least two times**, once with just the name of the city as an argument, and another time with both arguments (one for the city, one for the person’s citizenship).

**Task 5 / Make / Individual**  
Use what you’ve learned from the previous tasks to write a new function called `make_shirt( )` that takes two parameters, *size* and *shirt_text*.  The function should print a sentence summarizing the size of the shirt and the message to be printed on the shirt.  Set the *size* parameter to **large by default**.  Call the function twice, the first time using size and shirt text arguments, and the second time using only a shirt text argument.

Add your finished script to your GitHub repo for this assignment.  Submit the URL (web address) that points to the repo on Google Classroom.
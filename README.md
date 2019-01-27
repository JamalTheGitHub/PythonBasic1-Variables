# PythonBasic1-Variables

Prerequisite => From this tutorial onwards, it is expected that you have the following extensions in your Visual Studio Code;

1)<strong>Code Runner</strong>
2)<strong>Python</strong>

If you want to know more on how to get Python on Visual Studio Code, google it.

First thing first, create a file called called whatever you want it to be called and save it as ".py". For example like this, "PythonTutorial.py". Navigate to that file and do your coding there.

================================================================================================


<u><strong>print()</strong></u> Function

    print("Hello Python")

    print('Hello Python')

Notice that the single quotes and double quotes will yield the same output. To do this press "Ctrl", "Alt" and "n" on the keyboard simultaneously. This will use the "Code Runner" extension and run the code. If you want to do it manually, You could type in the terminal python <filename>.py provided that you are in the directory where your file was created and saved.

Besides that, you can also use the same function to print integer like;

    print(3)

In which it will yield the integer "3". Now that We have understood the simple concept of the <strong>print()</strong> function, we can move on to Variables.


================================================================================================


<u>What are <strong>Variables?</strong></u>

    a = 6

"a" is a <strong>variable</strong>. "6" is an integer that is assigned to that variable, hence <strong>a = 6</strong>. Now if we use to the print function to print a like below,

    print(a)

We will get 6 as the output. Okay let's get complicated!

    a = 1
    b = 2
    c = "OMG"

    d = 1

    print(a)
    print(b)
    print(c)
    print(d)

Upon running the code, we can see that the value of 1 is assigned to two <strong>variables</strong>, "<strong>a</strong>" and "<strong>d</strong>". What this means is that a same value can be assigned to 1 or more <strong>variables</strong>. Now let us make it more crazier!

    a = 1
    b = 2
    c = "OMG"

    d = 1
    c = "Nah Man"
    b = 1

    print(a)
    print(b)
    print(c)
    print(d)

Now what happens when We run the code? Well, notice previously that We found out that the same value can be assigned to more than 1 variable. However the same cannot be said to a <strong>variable</strong>. A <strong>variable</strong> can only be assigned to <strong>one thing</strong>. Therefore, if the same <strong>variable</strong> is to be assigned to something new, it will remove it's attachment to whatever that it was assigned to previously and attached itself to a new one just like the case of the above example, we can see that <strong>b</strong> is equals to 2 and then <strong>b</strong> is equals to 1. The same can be said to the <strong>variable c</strong>.

Well that was pretty interesting and all but the question is, what happens if you try to print a <strong>variable</strong> that does not exist? Let's try it out!

    print(z)

Surely, the <strong>variable z</strong> was not assigned and this will give us an error. To be precise, it will give a <strong>NameError</strong> where it will say that <strong>'z' is not defined</strong>. In order to fix this, we just need to assign a value of some sort to the <strong>variable z</strong>.

Okay, the next question is, is it possible to assigned a <strong>variable</strong> to another <strong>variable</strong>? The answer is yes and let's try it out!

    b = 2
    a = b
    b = 3

    print(a)
    print(b)

What do you think the output will be? Well, the output will be <strong>print(a) = 2 , print(b) = 3</strong>. Okay let us inspect closer on what is going on here. Initially we assigned the value of 2 to "b". Then we take "a" and assigned it to "b". This will make "a" have the value of 2. In layman's term, we could write something like <strong>a = b = 2</strong>, therefore "a" = 2. After that we reassigned "b" to 3. Note that even if we reassigned "b" to 3, it will not change the value of "a". This is because "a" was assigned to "b" when "b" had the value of 2 and because we reassigned "b" to have a value of 3, "b" no longer equals to 2 but 3. Initially we have the equation of something like "<strong>a = b = 2</strong>", now it is just "<strong>a = 2</strong>" because "b" has been reassigned. One <strong>key note</strong> to take into account is that the ordering of execution matters.

That is basically it for <strong>variables</strong>. Bare in mind that this is just the concept to understand how we can use <strong>variables</strong> in Python. Practice makes perfect.

================================================================================================

Okay, now given the knowledge of how We could use <strong>variables</strong>, here are simple exercises that you may attempt to further your understanding regarding <strong>variables</strong>.

1) Assign a string, "Hello, I am a string!", to a variable and print it.
2) Assign an integer, 44, to a variable and print it.

<u>Tricky Exercises!</u>

1) Given a = 3 and b = 2, perform a simple addition in the print function to get the output 5 shown.
2)    
    GIVEN <strong>a = "First String"</strong> AND <strong>b = "Second String"</strong>

Given the above variables, swap the position in a way that when using the print function for a, it will print "Second String" and a print function for b, it will print "First String". You are not allowed to change the values ASSIGNED to the variables.
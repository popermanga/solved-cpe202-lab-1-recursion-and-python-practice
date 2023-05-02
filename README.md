Download Link: https://assignmentchef.com/product/solved-cpe202-lab-1-recursion-and-python-practice
<br>
: Experienced programmers know how important it is to understand the problem and develop a solution before writing any code.  Why?  Because this saves time and effort in the long run.  Drawing pictures and writing pseudo code clarify both the problem and how to solve it.  If you cannot solve simple versions of the problem by hand using your algorithm, how can you expect to write a program that will solve the problem.

When writing pseudo-code, at first do <strong><u>not</u></strong> give a complete program. Give just enough detail that your intentions are clear and unambiguous, but do not provide extraneous details (complex syntax and/or variable declarations) which are <strong>otherwise obvious</strong>.  Thinking through examples is especially important.  This saves much time later in reducing rework, finding problems, etc.

Lab 1: Recursion and Python practice

<ul>

 <li>Write an iterative function to find the maximum in a list of integers. (do not use library function like max or sort.)</li>

 <li>Write a recursive function to reverse a string (do not use reverse library function).</li>

 <li>Write a recursive function to search a list of integers using binary search along with test cases. The function returns its index if the <strong>target</strong> of the search is in the list else return <strong>None</strong>. If the list is empty, it returns <strong>None</strong>.</li>

</ul>

<strong>Details: </strong>Download the files:  (Read the section below if you are new to Python/CalPoly)

<ul>

 <li><strong>py </strong></li>

 <li><strong>py </strong><strong>Test Cases </strong></li>

</ul>

Many people tend to focus on writing code as the singular activity of a programmer, but testing is one of the most important tasks that one can perform while programming. Proper testing provides a degree of confidence in your solution.  Systematic testing helps you to discover and then fix bugs (i.e., debug). Writing high quality test cases can greatly simplify the tasks of both finding and fixing bugs and, as such, <strong>will save you time during development</strong>.  However, testing does not guarantee that your program is correct.

For this part of the lab you will practice writing some simple test cases to gain experience with the unittest framework.  I recommend watching the first 20 minutes or so of the following video if you are unfamiliar with testing in Python.   <a href="https://www.youtube.com/watch?v=6tNS--WetLI">https://www.youtube.com/watch?v=6tNS–WetLI</a>

Using your editor/IDE of choice, open the <em>lab1_test_cases.py</em> file. This file defines, using code that we will treat as a boilerplate for now, a testing class with a single testing function.

In the <em>test_expressions</em> function you will see a single test case already provided. You must add additional test cases to verify that you binary search program is correct.

<strong><em>Submission: Submit two files to PolyLearn and Demo your work. </em></strong>

<ul>

 <li>py : Correct and well documented iterative max_list, recursive reverse, and recursive binary search based on the template provided</li>

 <li>py : test max_list_iter, test reverse_rec, and a complete set of test cases for your</li>

</ul>

recursive binary search function<strong>. (5 tests: exist in first half, exist in second half, middle element, not exist, and empty list)</strong>Your test cases should test boundary conditions and other possible errors based on the structure of your program.  (white box testing)  For each test provide a comment that explains what it is testing.

<strong>For folks new to Python or who need review </strong>

<strong><em>The basic Python Tutorial  </em></strong>

<a href="https://docs.python.org/3/tutorial/">https://docs.python.org/3/tutorial/</a>

<strong><em>This site gives the essentials. </em></strong>

Python for Java Programmers: <a href="http://python4java.necaiseweb.org/Fundamentals/Fundamentals">http://python4java.necaiseweb.org/Fundamentals/Fundamentals</a>  <strong><em>Videos on specific topics you will need to know. </em></strong>

<strong>Installing Python on Mac/Windows</strong>:   <a href="https://www.youtube.com/watch?v=YYXdXT2l-Gg&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU">https://www.youtube.com/watch?v=YYXdXT2l-Gg&amp;list=PL</a><a href="https://www.youtube.com/watch?v=YYXdXT2l-Gg&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU">osiE80TeTt2d9bfVyTiXJA-UTHn6WwU</a>

<strong>Strings</strong>:  <a href="https://www.youtube.com/watch?v=k9TUPpGqYTo&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=2">https://www.youtube.com/watch?v=k9TUPpGqYTo&amp;list=PL-osiE80TeTt2d9bfVyTiXJA</a><a href="https://www.youtube.com/watch?v=k9TUPpGqYTo&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=2">UTHn6WwU&amp;index=2</a>

<strong>Lists, etc.  (Lists are what you need for now)</strong> <a href="https://www.youtube.com/watch?v=W8KRzm-HUcc&amp;index=4&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU">https://www.youtube.com/watch?v=W8KRzm-</a>

<a href="https://www.youtube.com/watch?v=W8KRzm-HUcc&amp;index=4&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU">HUcc&amp;index=4&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU</a>

<strong>Conditionals:</strong>  <a href="https://www.youtube.com/watch?v=DZwmZ8Usvnk&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=6">https://www.youtube.com/watch?v=DZwmZ8Usvnk&amp;list=PL-osiE80TeTt2d9bfVyTiXJA</a><a href="https://www.youtube.com/watch?v=DZwmZ8Usvnk&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=6">UTHn6WwU&amp;index=6</a>

<strong>Loops:</strong> <a href="https://www.youtube.com/watch?v=6iF8Xb7Z3wQ&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=7">https://www.youtube.com/watch?v=6iF8Xb7Z3wQ&amp;list=PL-osiE80TeTt2d9bfVyTiXJA</a><a href="https://www.youtube.com/watch?v=6iF8Xb7Z3wQ&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=7">UTHn6WwU&amp;index=7</a>

<strong>Functions</strong>:  <a href="https://www.youtube.com/watch?v=9Os0o3wzS_I&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=8">https://www.youtube.com/watch?v=9Os0o3wzS_I&amp;list=PL-osiE80TeTt2d9bfVyTiXJA</a><a href="https://www.youtube.com/watch?v=9Os0o3wzS_I&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=8">UTHn6WwU&amp;index=8</a>

<strong>Modules:</strong> <a href="https://www.youtube.com/watch?v=CqvZ3vGoGs0&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=9">https://www.youtube.com/watch?v=CqvZ3vGoGs0&amp;list=PL-osiE80TeTt2d9bfVyTiXJA</a><a href="https://www.youtube.com/watch?v=CqvZ3vGoGs0&amp;list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&amp;index=9">UTHn6WwU&amp;index=9</a>

<h1>For folks new to Cal Poly: Unix Environment <em>Unix </em></h1>

The lab machines run a distribution of the Linux operating system. For simplicity, and to gain experience in a, potentially, new environment, we will do our coursework in this environment.

Open a terminal window. To do so, from the system menu on the desktop toolbar,

select <strong>Applications</strong> <sub>→</sub> <strong>System Tools</strong> <sub>→</sub> <strong>Terminal</strong>. The Terminal program will present a window with a command-line prompt. At this prompt you can type Linux commands to list files, move files, create directories, etc. For this lab you will use only a few commands. Additional commands can be found at:

<ul>

 <li>Unix Tutorial o <a href="http://www.ee.surrey.ac.uk/Teaching/Unix/">Tutorials 1 &amp; 2</a> o         <a href="http://people.ischool.berkeley.edu/%7Ekevin/unix-tutorial/toc.html">Parts 1-5</a></li>

 <li>Editors o <a href="http://xahlee.org/emacs/emacs.html">emacs tutorial</a> o <a href="http://www.unix-manuals.com/tutorials/vi/vi-in-10-1.html">vi tutorial</a></li>

</ul>

In the terminal, type <strong>ls</strong> at the prompt and hit &lt;Enter&gt;. This command will list the files in the current directory.

(also know as a folder.) If you type <strong>pwd</strong>, the current directory will be printed (it is often helpful to

type <strong>pwd</strong> while you are navigating directories). If you type <strong>tree</strong>, then you will see a tree-like listing of the directory structure rooted at the current directory.

Create a new directory for your coursework by typing <strong>mkdir cpe202</strong>. Use <strong>ls</strong> again to see that the new directory has been created.

Change into this new directory with <strong>cd</strong> by typing <strong>cd cpe202</strong>. To move back “up” one directory, type <strong>cd ..</strong>.

To summarize

<ul>

 <li><strong>ls</strong> list files in the current directory</li>

 <li><strong>cd</strong> change to another directory</li>

 <li><strong>mkdir</strong> create a new directory</li>

 <li><strong>pwd</strong> print (the path of) the current directory</li>

</ul>

Though these basic commands are enough for now, consider working through a Unix tutorial. <strong><em>Executing a Program </em></strong>

Download the <strong>.py</strong> files for lab1 from polylearn into the <strong>cpe202</strong> directory created above; this can be done via the browser (by selecting the location to save to), via the graphical file manager, or through the use of the <strong>mv </strong>command in the terminal window (e.g., from the <strong>cpe202</strong> directory, after downloading,  type <strong>mv ~/Downloads/lab1.zip . </strong>). If you need assistance doing this, please ask.




A Python program is written in a plain text file. The program can be run by using a Python interpreter. You can see the contents of <em>lab1.py</em> by typing       <strong>more lab1.py</strong> or   <strong>cat lab1.py </strong>           at the command-line prompt.

To execute the program, type             <strong>python  lab1.py</strong>          at the command-line prompt.

To summarize

<ul>

 <li><strong>mv</strong> move files</li>

 <li><strong>more or cat </strong>display contents of a file</li>

 <li><strong>python</strong> python interpreter used to execute a program by specifying name of program file</li>

</ul>

<strong><em>Editing </em></strong>

There are many options for editing a Python program. On the department machines, you will find vi, emacs/xemacs, nano, gedit, and some others. The editor that one uses is often a matter of taste. You are not required to use a specific editor, but we will offer some advice (and we will try to help with whichever one you choose).  There is lots more information here:  <a href="http://users.csc.calpoly.edu/%7Eakeen/courses/csc101/handouts/labs/lab1.html">http://users.csc.calpoly.edu/~akeen/courses/csc101/handouts/labs/lab1.html</a>  <strong><em>Interactive Interpreter </em></strong>

The Python interpreter can be used in an interactive mode. In this mode, you will be able to type a statement and immediately see the result of its execution. Interactive mode is very useful for experimenting with the language and for testing small pieces of code, but your general development process with be editing and executing a file as discussed previously.

Start the interpreter in interactive mode by typing <strong>python</strong> at the command prompt. You should now see something like the following.

Python 2.6.6 (r266:84292, Jan 22 2014, 09:42:36)

[GCC 4.4.7 20120313 (Red Hat 4.4.7-4)] on linux2

Type “help”, “copyright”, “credits” or “license” for more information.

&gt;&gt;&gt;

The &gt;&gt;&gt; is the interpreter’s prompt. You can type an expression at the prompt to see what it evaluates to. Type each of the following (hit enter after each one) to see the result. When you are finished, you can exit the interpreter by typing ctrl-D (i.e., hold the control key and hit d).

<ul>

 <li>0 + 1</li>

 <li>2 * 2</li>

 <li>19 // 3</li>

 <li>19 / 3</li>

 <li>19 / 3.0</li>

 <li>0 / 3.0</li>

 <li>4 * 2 + 27 // 3 + 4</li>

 <li>4 * (2 + 27) // 3 + 4</li>

</ul>
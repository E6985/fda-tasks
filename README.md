< [GMIT Data Analytics](https://web.archive.org/web/20201029063153/https://www.gmit.ie/computer-science-and-applied-physics/higher-diploma-science-computing-data-analytics-ict) | [Table of Contents](https://github.com/E6985) | [README](https://github.com/E6985/fda-tasks/blob/main/README.md) >

![GMIT](https://github.com/E6985/pda-numpy-random/blob/main/img/gmit.png?raw=true)

## Fundamentals of Data Analysis - Tasks 2020
## Due: last commit on or before December 18th, 2020

Undergraduate of Computing (Data Analytics) at Galway-Mayo Institute of Technology. This repository contains the instructions for the Tasks assessment for the ``Fundamentals of Data Analysis`` module in 2020. The assessment is worth 50% of the marks for the module. Four tasks will be presented at different times during the semester and all will be completed in a single [Jupyter Notebook](https://github.com/E6985/fda-tasks/blob/main/Fundamentals-of-Data-Analysis-Tasks-2020.ipynb)

## Assignment

These are the instructions for the assignment (Tasks assessment) for Fundamentals of Data Analysis in 2020.

### Task 1

Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ``['A', 'A', 'B', 'C', 'A']`` should have output ``{'A': 3, 'B': 1, 'C': 1}``. Your code should not depend on any module from the standard library or otherwise. By the standard library, we mean the modules and packages that come as standard with Python. Anything built-in that can be used without an import statement can be used. You should research the task first and include a description with references of your algorithm in the notebook.

- Keywords: Outstanding - Revert before deadline.
- Summary: Outstanding - Revert before deadline - Detail approach. 

### Task 2

Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice ``k`` and the number of times to roll the dice ``n``. The function should simulate randomly rolling ``k`` dice ``n`` times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as ``diceroll(k=2, n=1000)`` should return a dictionary like:

> ``{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}``

> You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

- Keywords: Outstanding - Revert before deadline.
- Summary: Outstanding - Revert before deadline - Detail approach. 

### Task 3

The ``numpy.random.binomial`` function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

- Keywords: Outstanding - Revert before deadline.
- Summary: Outstanding - Revert before deadline - Detail approach. 

### Task 4

Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big dataset. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x , y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.

- Keywords: Outstanding - Revert before deadline.
- Summary: Outstanding - Revert before deadline - Detail approach. 

#### Marking Scheme

1. ``25%`` - Research - Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used.

2. ``25%`` - Development - Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind.

3. ``25%`` - Consistency - Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others.

4. ``25%`` - Documentation - Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README.

#### Getting Started

- Keeping in mind the impression given to someone who is looking at this repository, this submission is to provide direct evidence of each of the items listed in each category - ``Research`` - ``Development`` - ``Consistency`` - ``Documentation`` - refer ``Marking Scheme`` above.

1. Research:

	- ***Evidence of research performed on topic***: Each topic/section will have its own ``Reference`` area - topic/section 1 will be referenced as ``1.?`` - topic/section 2 will be referenced as ``2.?`` - and so on. Where possible references will be in the format:

		- [task-number.number] authorNames, referenceTitle, locationWebsiteBookVideo, dateMonthYear.

	- ***Submission based on referenced literature, particularly academic literature***: Start within Wikipedia using academic literature references specified. Demonstrating work completed in the submission with good references and not just for the problem but for level of understanding of the problem.

	- ***Evidence of understanding of the documentation for any software or libraries used***: Code comments will include details of package, module, function, object, method, attribute if applicable to demonstrate understanding of software documentation and libraries used.

2. Development:

	- ***Environment can be set up as described***: Follow exact instruction regarding number of Notebooks/files required.

	- ***Code works without tweaking and as described***: Using Jupyter Notebook markdown cells to summarise concise workings. 

	- ***Code is efficient, clean, and clear***: Individual code statements will have single Jupyter Notebook code cell unless user-defined functions are created. 

	- ***Evidence of consideration of standards and conventions appropriate to code of this kind***: As much as possible use ``Style Guide for Python Code`` [Guido van Rossum](https://web.archive.org/web/20201029095211/https://www.python.org/dev/peps/pep-0008/). User-defined coding conventions to be given separate section - refer ``Coding Conventions`` - within README as and when presented (note good commits do not change many different files - when a user-defined coding convention is represented within a Jupyter Notebook then the commit completed will include an update to this README file - this will be the only time this will happen given that to update README every time is wasteful):- 

3. Consistency:

	- ***Evidence of planning and project management***: This README will form the template for this and all future tasks/projects. Git commit to include within the blurb the number of days outstanding before deadline.

	- ***Pragmatic attitude to work as evidenced by well-considered commit history***: Endeavour to submit work every day worthy of a git commit. At best 4/5 times per week. Later presentation of topics/sections will require more commits to ensure equal proof of work for all before the deadline.

	- ***Commits are of a reasonable size***: Correctly use git history by putting in a little blurb - 2/3 lines. 

	- ***Consideration of how commit history will be perceived by others***: Commits to highlight changes made since the last commit so that reviews of the git history can demonstrate compartmentation of work into the different sections.   

4. Documentation - 

	- ***Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code***: Separate section - refer ``Environment`` - within README - to be completed closer to the deadline.

	- ***Concise descriptions of code in comments and README***: Comments to be very concise for ease of readability. Descriptions of code requiring further explanation will be presented in Jupyter Notebook markdown cells prior to code execution.   

#### Considerations

- The four listed categories - ``Research`` - ``Development`` - ``Consistency`` - ``Documentation`` - are each worth 25%. 

- Designed not only to be about programming but also about looking at information - data - manipulating the data and coming up with techniques. 

- Sometimes the most complex algorithms are counter-intuitive but do work and have been proven to work. Sometimes only a few lines of code is required to complete a topic/section but to obtain full marks it is not good enough to submit the lines of code. Must explain how the algorithm was developed and the reasoning behind why/how the code works.

- Jupyter Notebook text formatting/presentation to be tidied up closer to the deadline.

#### Coding Conventions

| Example       | Signify 			      |
| ------------- |:-----------------------:|
|	C        	|	class   		      |
|	d    		|	module first letter   |
|	e			|	class any letter      |
|	l			|	class final letter    |

```python
n___
```

| Example       | Signify 		          |
| ------------- |:-----------------------:|
|	n        	|	name - no variables   |

#### Prerequisites

- Require Python to be loaded on your local machine. Recommend downloading and installing Anaconda.

https://www.anaconda.com/download/

#### Execute Jupyter Notebook

- The software must be downloaded and run on a machine as follows:

	- Clone the repository with the following command:

	``git clone https://github.com/E6985/fda-tasks.git``

    - Run Jupyter Notebooks from the repository with the following command:

	``jupyter notebook``

    - Open notebook - Fundamentals-of-Data-Analysis-Tasks-2020.ipynb

    - Once running within the Jupyter environment can navigate with ease - links are plentiful.

	- Notebook links will not work on github given that github renders as static HTML.

- If not running Jupyter notebook code cells - alternative to downloading and running on a machine: 

	- Render Jupyter notebook [here](https://nbviewer.jupyter.org/github/E6985/fda-tasks/blob/main/Fundamentals-of-Data-Analysis-Tasks-2020.ipynb)
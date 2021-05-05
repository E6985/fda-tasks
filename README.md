< [GMIT Data Analytics](https://web.archive.org/web/20201029063153/https://www.gmit.ie/computer-science-and-applied-physics/higher-diploma-science-computing-data-analytics-ict) | [Table of Contents](https://github.com/SeanOhAileasa) | [README](https://github.com/SeanOhAileasa/fda-tasks/blob/main/README.md) >

![GMIT](https://github.com/SeanOhAileasa/pda-numpy-random/blob/main/img/gmit.png?raw=true)

## Fundamentals of Data Analysis - Tasks 2020
## Due: last commit on or before December 18th, 2020

Undergraduate of Computing (Data Analytics) at Galway-Mayo Institute of Technology. This repository contains the instructions for the Tasks assessment for the ``Fundamentals of Data Analysis`` module in 2020. The assessment is worth 50% of the marks for the module. Four tasks were presented at different times during the semester and all were to be completed in a single [Jupyter Notebook](https://github.com/SeanOhAileasa/fda-tasks/blob/main/Fundamentals-of-Data-Analysis-Tasks-2020.ipynb).

## Assignment

These are the instructions for the assignment (Tasks assessment) for Fundamentals of Data Analysis in 2020.

### Task 1

Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ``['A', 'A', 'B', 'C', 'A']`` should have output ``{'A': 3, 'B': 1, 'C': 1}``. Your code should not depend on any module from the standard library or otherwise. By the standard library, we mean the modules and packages that come as standard with Python. Anything built-in that can be used without an import statement can be used. You should research the task first and include a description with references of your algorithm in the notebook.

- **Keywords**: list - dictionary - key:value pairs - counts - collections - smalltalk - bag - multiset theory - object-oriented - duplicates - sort tally 

### Task 2

Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice ``k`` and the number of times to roll the dice ``n``. The function should simulate randomly rolling ``k`` dice ``n`` times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as ``diceroll(k=2, n=1000)`` should return a dictionary like:

> ``{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}``

> You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

- **Keywords**: die - dice - face value - diceroll - numpy.random.Generator.choice - roll die - probability - roll dice

### Task 3

The ``numpy.random.binomial`` function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

- **Keywords**: Bernoulli - Law of Large Numbers - trail - tails - heads - gamblers fallacy - discrete variable - binomial distribution - simulation

### Task 4

Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big dataset. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x , y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.

- **Keywords**: SARS-CoV-2 - CFR - simulation - contrived dataset - plotting - least squares polynomial fit - collinear

### Coding Conventions

```python
n___
```

| Example       | Signify 		          |
| ------------- |:-----------------------:|
|	n        	|	name - no variables   |

### Prerequisites

- Require Python to be loaded on your local machine. Recommend downloading and installing Anaconda.

https://www.anaconda.com/download/

### Execute Jupyter Notebook

- The notebook must be downloaded and run on a machine as follows:

	- Clone the repository with the following command:

	``$ git clone https://github.com/SeanOhAileasa/fda-tasks.git``

    - Run Jupyter Notebooks from the directory it was cloned with the following command:

	``$ jupyter notebook``

    - Open notebook - Fundamentals-of-Data-Analysis-Tasks-2020.ipynb

    - Once running within the Jupyter environment can navigate with ease - links are plentiful.

	- Notebook links will not work on github given that github renders as static HTML.

- If not running Jupyter notebook from local machine can alternatively use nbviewer: 

	- Render Jupyter notebook [here](https://nbviewer.jupyter.org/github/SeanOhAileasa/fda-tasks/blob/main/Fundamentals-of-Data-Analysis-Tasks-2020.ipynb)
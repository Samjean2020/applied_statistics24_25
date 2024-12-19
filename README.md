# applied_statistics24_25

![lecture](https://github.com/user-attachments/assets/d88a1f95-b2cb-4e3a-9710-a58893718b49)

# My Assessment Repository.
### by Jean-Samuel Bonsenge-Bokanga(G00387887@atu.ie)

This repository contains my assessment submission for the Applied Statistics module.

For the purpose of the above assessment, I have to demonstrate the following:

1. Describe the stochastic nature of real-world measurements,
2. Source documentation to programmatically perform a statistical test,
3. Select an appropriate statistical test to investigate a claim, and
4. Perform a statistical test on a data set.

# Tasks
## Instructions
Complete all tasks in a notebook called tasks.ipynb in your repository.

For each task, you should write your code in code cells while using MarkDown cells to give explanations and insights into your code. Break up your code into smaller, manageable cells whenever possible. Each code cell should focus on a single step in your overall solution.

Include comments in all code cells to tell the reader what each statement does. Write clean, readable, and efficient code, using meaningful variable names and consistent formatting. You should follow Python coding standards and guidelines such as PEP8.

Make regular commits to your repository while completing the tasks. Your commit history should demonstrate how each solution to each task evolved. There should be several commits for each task demonstrating incremental improvements, clarifications, and revisions.

## Task 1: Permutations and Combinations
Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.
Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

Would you accept two errors? Explain.

## Task 2: numpy's Normal Distribution
In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.
Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.
Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.

## Task 3: t-Test Calculation
Consider the following dataset containing resting heart rates for patients before and after embarking on a two-week exercise program.

Patient ID	0	1	2	3	4	5	6	7	8	9
Before	63	68	70	64	74	67	70	57	66	65
After	64	64	68	64	73	70	72	54	61	63

Calculate the t-statistic based on this data set, using Python. Compare it to the value given by scipy.stats. Explain your work and list any sources used.

## Task 4: ANOVA
In this test we will estimate the probability of committing a type II error in specific circumstances. To begin, create a variable called no_type_ii and set it to 0.
Now use a loop to perform the following test 10,000 times.

   1. Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and 
   the third a mean of 5.1.

   2. Perform one-way anova on the three samples and add 1 to no_type_ii whenever a type II error occurs.

Summarize and explain your results.

# Project
Complete the project in a single notebook called project.ipynb in your repository. The same style should be used as detailed above: explanations in MarkDown and code comments, clean code, and regular commits. Use plots as appropriate.

In this project, you will analyze the PlantGrowth R dataset. You will find a short description of it on Vicent Arel-Bundock's Rdatasets page. The dataset contains two main variables, a treatment group and the weight of plants within those groups.

Your task is to perform t-tests and ANOVA on this dataset while describing the dataset and explaining your work. In doing this you should:

   1. Download and save the dataset to your repository.
   2. Describe the data set in your notebook.
   3. Describe what a t-test is, how it works, and what the assumptions are.
   4. Perform a t-test to determine whether there is a significant difference between the two treatment groups trt1 and trt2. 
   5. Perform ANOVA to determine whether there is a significant difference between the three treatment groups ctrl, trt1, and trt2.

Explain why it is more appropriate to apply ANOVA rather than several t-tests when analyzing more than two groups.

## How to run the programs:
* Set up a-Python 3.12.4 friendly environment and import its various libraries including Numpy, SciPy, MatplotLib.pyplot, Seaborn and Pandas downloaded from Anaconda 3. 
* Use Jupiter Notebook text-editor to run all the programs (tasks.ipynb and project.ipynb). Make sure the Jupiter Notebook Kernel is ready and Trusted when running the programs. Save the file at Save and Checkpoint when you finish running the programs.
*You can also run the program on command line on Cmder (Console Emulator) and VSC (Visual Studio Code) console, Codespaces via GitHub account(GitHub Codespaces gets you up and coding faster with fully configured, secure cloud development environments native to GitHub), and other text editors. 
* Note that both programs, tasks.ipynb and project.ipynb are written under Windows OS (Operation Systems); in which relevant commands are required for the OS functionality.
* Download the dataset PlantGrowth R csv file or their URL: PlantGrowth function - RDocumentation for data manipulation, analysis and visualisation, using Pandas DataFrame() function.
* Use the dataset provided on the assessment description for Task 3: t-Test Calculation
for Patients Resting Heart Beat rates before and after embarking on a two-week exercise program, data manipulation, analysis and data visualization using Pandas for DataFrame and sciPy-stats for t-Tests and ANOVA computations and operations. Matplolib.pyplot has been used for several plotting within both notebooks.
* Regarding images included in both Jupiter Notebooks, they are available online and from the lecture notes.

## Credits
I have used extensive online sources to build-up this repository. References included on each Jupiter Notebook are useful and can be consulted if there is a need to go further on Applied Statistics, particularly with SciPy-Stats on performing t-tests and ANOVA. I have also used Laerd Statistics (SPSS) for Assumptions. Their link address is: https://statistics.laerd.com/spss-tutorials/one-way-anova-using-spss-statistics.php. You can also access SPSS Statistics Tutorials and Statistical Guides via the following link: https://statistics.laerd.com/.

## Conclusion and lessons learned
tasks.ipynb and project.ipynb are both programs included in this repository for Applied Statistics Assessment. They are written in Python Programming Language. I have included a requirements.txt file on how to run both Notebooks. As lessons learned, I have deepened my understanding on how to perform t-Tests and ANOVA on datasets and probability error I and error II, from the Lady Tasting Tea experiment (altered) in performing permutations and Combinations, and furthermore.

# End.

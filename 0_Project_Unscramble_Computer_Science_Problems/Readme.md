# Investigating Texts and Calls

## Project Overview
In this project, I completed five tasks based on a fabricated set of calls and texts exchanged during September 2016. I used Python to analyze and answer questions about the texts and calls contained in the dataset. Lastly, I performed run time analysis of my solution and determine its efficiency.

#### What will I learn?
In this project, I have:

- Applied Python knowledge to breakdown problems into their inputs and outputs.
- Performed an efficiency analysis of the solution.
- Warm up Python skills for the course.

#### Why this Project?
I applied the skills I've learned so far in a more realistic scenario. The five tasks are structured to give the experience with a variety of programming problems. 

## Step 1 - Download the Files
Download and open the zipped folder [here](https://github.com/saurabhsoni5893/Udacity-Data-Structure-and-Algorithms/blob/master/0_Project_Unscramble_Computer_Science_Problems/Project%20Files.zip). In the folder, there are five python files Task0.py, Task1.py, ...,Task4.py and two csv files calls.csv and texts.csv

#### About the data
The text and call data are provided in csv files.

- The text data [text.csv](https://github.com/saurabhsoni5893/Udacity-Data-Structure-and-Algorithms/blob/master/0_Project_Unscramble_Computer_Science_Problems/texts.csv) has the following columns: sending telephone number (string), receiving telephone number (string), timestamp of text message (string).

- The call data [call.csv](https://github.com/saurabhsoni5893/Udacity-Data-Structure-and-Algorithms/blob/master/0_Project_Unscramble_Computer_Science_Problems/calls.csv) has the following columns: calling telephone number (string), receiving telephone number (string), start timestamp of telephone call (string), duration of telephone call in seconds (string)

- All telephone numbers are 10 or 11 numerical digits long. Each telephone number starts with a code indicating the location and/or type of the telephone number. 
- There are three different kinds of telephone numbers, each with a different format:

 - Fixed lines start with an area code enclosed in brackets. The area codes vary in length but always begin with 0. Example: "**(022)**40840621".
 - Mobile numbers have no parentheses, but have a space in the middle of the number to help readability. The mobile code of a mobile number is its first four digits and they always start with 7, 8 or 9. Example: "**93412** 66159".
 - Telemarketers' numbers have no parentheses or space, but start with the code 140. Example: "**140**2316533".

## Step 2 - Implement the Code
Complete the five tasks (Task0.py, Task1.py, ...,Task4.py). Do not change the data or instructions, simply add your code below what has been provided. Include all the code that needed for each task in that file.

In Tasks 3 and 4, use in-built methods sorted() or list.sort() for sorting which are the implementation of Timsort and Samplesort, respectively. Both these sorting methods have a worst-case time-complexity of O(n log n). Check the below links to learn more about these methods:

- How to use the above methods - https://docs.python.org/3/howto/sorting.html
- Complexity analysis of Timsort and Samplesort - http://svn.python.org/projects/python/trunk/Objects/listsort.txt

The solution outputs for each file should be the print statements described in the instructions. 

## Step 3 - Calculate Big O
Once I completed the solution for each problem, performed a run time analysis (Worst Case Big-O Notation) of my solution. Documented this for each problem.

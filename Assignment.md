

# Assignment 1

## Data Science (in Bash)

### Due: 2024-05-30

This assignment will require you to use Bash commands to answer questions about a data file.
You will need **all** the commands and concepts taught, including, but not limited to

* `cat`
* `head`, `tail`
* `wc`
* `sort`, `uniq`
* `grep`

as well as the following commands (use the `man` command and help text):
* `cut`
* `tr`
* `sort` (with options for numerical sorting and reverse sorting)

### Instructions

Download the data file [data-no-header.csv](assets/data-no-header.csv) 

You can download also download the data file with a header, for viewing in Excel [data.csv](assets/data.csv)

For each task below, unless stated otherwise, answer with a **single** Bash command to solve the problem. 
Include a screenshot of your output.

Using the data file `data-no-header.csv`.

1. How many rows are in the data file?

2. How many columns are in the data file?
    Hint: You can use `head`, `tr` and `wc` to count the number of columns in the first row.

3. How many cities are in the data file?

4. What is the range of **temperatures** in the data file? 
    Hint: No need to subtract the max and min, just find the minimum and maximum values.
          You may use two commands, one for the minimum and one for the maximum.

5. What is the range of **rainfall** for **Kigali**?
   Hint: Same as above, but for Kigali only.

## Challenge (Optional)

You can use the following rules to challenge yourself
1. Do not use the `uniq` command

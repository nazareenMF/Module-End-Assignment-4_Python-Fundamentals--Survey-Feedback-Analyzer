#  Survey Feedback Analyzer – Python Fundamentals

##  Project Overview

The **Survey Feedback Analyzer** is a Python-based project designed to collect, clean, and analyze customer survey feedback.

The project uses Python fundamentals such as dictionaries, lists, loops, conditional statements, string manipulation, and user-defined functions to extract meaningful insights from textual feedback.

It helps understand customer opinions, identify commonly used words, and analyze feedback ratings.

##  Project Objectives

- Store survey feedback using a dictionary of lists.
- Collect additional feedback from users.
- Clean textual data by removing punctuation and extra spaces.
- Convert feedback into lowercase.
- Count feedback entries containing specific words.
- Calculate the average rating.
- Identify the feedback with the longest comment.
- Extract all unique words from feedback entries.
- Sort feedback based on ratings.

##  Technologies Used

- **Programming Language:** Python
- **Platform:** Jupyter Notebook

##  Project Structure

```text
Survey-Feedback-Analyzer/
│
├── Survey Feedback Analyzer.ipynb
└── README.md
```

##  Key Features

### 1. Preloaded Feedback Data
- Starts with 10 predefined survey feedback entries.
- Stores serial numbers, customer names, feedback comments, and ratings.

### 2. Add New Feedback
- Allows users to enter additional feedback.
- Collects customer name, written feedback, and rating.
- Automatically generates serial numbers.

### 3. Text Cleaning
Performs the following cleaning operations:

- Removes punctuation (., !, ?).
- Removes unnecessary spaces.
- Eliminates leading and trailing spaces.
- Converts all feedback into lowercase.

### 4. Word Count Analysis
Uses a user-defined function:

`count_word_in_feedbacks(word)`

Counts the number of feedback entries containing a specified word.

The analysis includes:
- Good
- Poor
- Excellent

### 5. Summary and Insights

Generates the following insights:

- Displays the final cleaned feedback dictionary.
- Calculates the average customer rating.
- Identifies the longest feedback comment based on word count.
- Extracts all unique words without duplicates.
- Sorts feedback entries by rating from highest to lowest.

##  Python Concepts Practiced

| Concept | Application |
|---|---|
| Dictionary | Storing feedback data |
| Lists | Managing multiple feedback entries |
| For Loop | Iterating through feedback |
| If Condition | Checking word matches |
| Functions | Counting specific words |
| String Methods | Cleaning textual data |
| `append()` | Adding new feedback |
| `split()` | Separating words |
| `join()` | Removing multiple spaces |
| `set()` | Extracting unique words |
| `zip()` | Combining multiple lists |
| `sorted()` | Sorting feedback by rating |
| `sum()` and `len()` | Calculating average rating |

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open the Jupyter Notebook file.
3. Run the cells sequentially.
4. Enter additional feedback when prompted.
5. View the cleaned feedback data and generated insights.

## 📈 Learning Outcomes

Through this project, I gained practical experience in:

- Working with dictionary-based datasets.
- Collecting and managing user inputs.
- Performing basic text preprocessing.
- Developing reusable Python functions.
- Extracting insights from textual data.
- Applying Python fundamentals to a real-world data analysis problem.

This project demonstrates the application of basic Python programming concepts in a simple survey feedback analysis scenario.

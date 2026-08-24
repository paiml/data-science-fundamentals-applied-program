<h1 align="center">Data Science Fundamentals Applied Program</h1>

<p align="center">Beginner, project-based, portfolio-first data science</p>

<div align="center">

<a href="https://ds500.paiml.com"><img src="https://img.shields.io/badge/Platform-Pragmatic_AI_Labs-blue" /></a>
<a href="https://ds500.paiml.com/mailing"><img src="https://img.shields.io/badge/Newsletter-Join-blue" /></a>
<a href="https://discord.gg/JJEcK7uzFS"><img src="https://img.shields.io/discord/973306113946681374" /></a>

</div>

<p align="center">
  <a href="https://ds500.paiml.com/learn/applied-program/data-science-fundamentals"><img src="resources/applied-program.png" alt="Banner" /></a>
</p>

An 8-week, project-based, beginner program that teaches core data science with Python (pandas, NumPy, data cleaning) by building a real data-quality tool. No prior data science experience required — ship a working project that detects problems in a real dataset. **Add to your calendar and start building**

<div align="center">

<a href="https://ds500.paiml.com/learn/applied-program/data-science-fundamentals/calendar.html?calendar=google"><img src="https://img.shields.io/badge/Add_to_Calendar-Google-4285F4?logo=googlecalendar" /></a>
<a href="https://ds500.paiml.com/learn/applied-program/data-science-fundamentals/calendar.html?calendar=outlook"><img src="https://img.shields.io/badge/Add_to_Calendar-Outlook-0078D4?logo=microsoftoutlook&logoColor=white" /></a>
<a href="https://ds500.paiml.com/learn/applied-program/data-science-fundamentals/calendar.html?calendar=ics"><img src="https://img.shields.io/badge/Download-.ics-6E6E6E?logo=icalendar&logoColor=white" /></a>

</div>

<details>
  <summary><b>Table of Contents</b></summary>
  <br>

* [How this program works](#how-this-program-works)
* [Prerequisites](#prerequisites)
* [Week 1: Python for Data Science + Choosing a Dataset](#week-1-python-for-data-science--choosing-a-dataset)
* [Week 2: Data Structures for Data Work](#week-2-data-structures-for-data-work)
* [Week 3: Pandas Basics](#week-3-pandas-basics)
* [Week 4: Working with DataFrames](#week-4-working-with-dataframes)
* [Week 5: NumPy Basics](#week-5-numpy-basics)
* [Week 6: Data Cleaning & Scaling](#week-6-data-cleaning--scaling)
* [Week 7: Feature Engineering & Visualization](#week-7-feature-engineering--visualization)
* [Week 8: Ship & Finalize](#week-8-ship--finalize)
* [The Project](#the-project)
* [Community](#community)
* [PROJECT.md](./PROJECT.md) — full project guidance

</details>

[The Project](./PROJECT.md) · [Self-Assessment Checklist](./SELF_ASSESSMENT.md)

## How this program works

There's no grading, no enrollment gate, and no required login. Everything you need to complete the program is in this repository.

There are two ways to run through it:

* **Rolling (self-paced):** Start whenever you want. No meetings, no cohort — you work through the 8 weeks on your own schedule and self-assess your project against the [checklist](./SELF_ASSESSMENT.md).
* **Cohort:** Runs alongside a shared start date with a dedicated Discord channel and an end-of-run call where participants demo their projects to each other (peer feedback, not grading).

Each week lists a plain-language objective, supporting resources, and a demo video prompt. The video prompt is worth doing even outside a cohort — it's the habit that turns a week of work into a LinkedIn post and a portfolio entry.

> [!IMPORTANT]
> You are not required to watch or read every resource listed. Nothing here is graded. Use the content as support for your project, not as a checklist to complete for its own sake.

> [!NOTE]
> **Diversity Statement:** We share a commitment to diversity and equity, removing barriers to learning so that everyone can participate fully. This program is meant to be useful to people with a wide range of backgrounds, identities, and learning styles, whether you found it through a cohort or on your own on GitHub.

### Prerequisites

No prior data science experience required. Basic comfort using a terminal helps. Python experience is a plus but not required — Python basics are covered in Weeks 1-2.


**Python**

* [Python Essentials for MLOps – Week 1: Introduction to Python](https://ds500.paiml.com/course/o184n/1) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)


**Command Line Basics**

If you've never used a terminal before, start here: [Linux and Bash for Data Engineering](https://ds500.paiml.com/course/nyu26) · [Coursera](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)


#### Additional support resources

* [Python Essentials for MLOps](https://ds500.paiml.com/course/o184n) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [MLOps Platforms: Amazon SageMaker and Azure ML](https://ds500.paiml.com/course/y7ji0) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Advanced Data Engineering](https://ds500.paiml.com/course/cf1x4) · [Coursera](https://www.coursera.org/learn/advanced-data-engineering)


## 8-Week Syllabus


### Week 1: Python for Data Science + Choosing a Dataset

1. Choose the dataset your project will analyze, and what "a problem" means for it (see [PROJECT.md](./PROJECT.md))
2. Set up Python and a notebook/editor environment for data work
3. Learn core Python variables, data types, and conditionals


* [Meet your course instructor Alfredo DEZA](https://ds500.paiml.com/course/o184n/1/1/1) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Lesson introduction variables and types](https://ds500.paiml.com/course/o184n/1/2/2) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Working with different data types](https://ds500.paiml.com/course/o184n/1/2/4) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Conditionals and evaluations](https://ds500.paiml.com/course/o184n/1/2/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Catching and handling exceptions](https://ds500.paiml.com/course/o184n/1/2/6) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)


**Weekly demo video prompt:** Introduce the dataset you chose, where it came from, and what kinds of problems you expect to find in it. Use the [Public Speaking](https://github.com/microsoft/workshop-library/tree/main/short/public-speaking) guidelines to deliver a clear demo.


### Week 2: Data Structures for Data Work

1. Learn lists, dictionaries, tuples, and sets in Python
2. Practice iterating over and extracting data from collections
3. Load your dataset's raw rows into plain Python structures before touching pandas


* [Introduction to lists](https://ds500.paiml.com/course/o184n/1/3/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Creating and Iterating over lists](https://ds500.paiml.com/course/o184n/1/3/4) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Introduction to dictionaries](https://ds500.paiml.com/course/o184n/1/3/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Creating and Iterating over dictionaries](https://ds500.paiml.com/course/o184n/1/3/6) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Extracting data from lists](https://ds500.paiml.com/course/o184n/1/4/4) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Extracting data from dictionaries](https://ds500.paiml.com/course/o184n/1/4/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)


**Weekly demo video prompt:** Show a small piece of your dataset represented as plain Python lists/dicts, and one thing that already looks off about it.


### Week 3: Pandas Basics

1. Load your dataset into a pandas DataFrame
2. Learn core DataFrame exploration (head, info, describe, dtypes)
3. Write your first exploratory pass over the data


* [Lesson introduction basic Pandas usage](https://ds500.paiml.com/course/o184n/4/1/2) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Introduction to Pandas](https://ds500.paiml.com/course/o184n/4/1/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Loading data into Pandas](https://ds500.paiml.com/course/o184n/4/1/4) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Writing data from Pandas Dataframes](https://ds500.paiml.com/course/o184n/4/1/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Exploratory analysis with Pandas](https://ds500.paiml.com/course/o184n/4/1/6) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)


**Weekly demo video prompt:** Show your dataset loaded into a DataFrame and walk through what .info()/.describe() tell you about it.


### Week 4: Working with DataFrames

1. Learn common DataFrame operations, filtering, and text manipulation
2. Apply functions across columns to compute derived values
3. Build the first pass of your data-quality checks (missing values, duplicates)


* [Common Dataframe operations](https://ds500.paiml.com/course/o184n/4/2/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Manipulating text in Dataframes](https://ds500.paiml.com/course/o184n/4/2/4) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Applying functions with Pandas](https://ds500.paiml.com/course/o184n/4/2/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Visualizing data with Pandas](https://ds500.paiml.com/course/o184n/4/2/6) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)


**Weekly demo video prompt:** Demo the first data-quality checks you wrote (missing values, duplicates) running against your dataset.


### Week 5: NumPy Basics

1. Learn NumPy arrays and vectorized operations
2. Use NumPy to compute statistics (mean, std, percentiles) for outlier detection
3. Add a numeric outlier check to your project (e.g. values outside N standard deviations)


* [Lesson introduction Numpy basics](https://ds500.paiml.com/course/o184n/4/3/2) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Introduction to Numpy Arrays](https://ds500.paiml.com/course/o184n/4/3/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Common Numpy array operations](https://ds500.paiml.com/course/o184n/4/3/4) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [More Numpy array operations](https://ds500.paiml.com/course/o184n/4/3/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)


**Weekly demo video prompt:** Show the outlier-detection check you built with NumPy and one real outlier it found in your data.


### Week 6: Data Cleaning & Scaling

1. Learn common data-cleaning techniques (handling nulls, fixing types, deduplication)
2. Learn when and why to scale numeric data
3. Extend your project to flag inconsistent types and out-of-range categorical values


* [Cleaning up data](https://ds500.paiml.com/course/y7ji0/2/1/3) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Scaling data](https://ds500.paiml.com/course/y7ji0/2/1/4) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Labeling data](https://ds500.paiml.com/course/y7ji0/2/1/5) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Cleaning and Normalizing data](https://ds500.paiml.com/course/cf1x4/2/3/7) · [Coursera](https://www.coursera.org/learn/advanced-data-engineering)


**Weekly demo video prompt:** Show a "before and after" of one column in your dataset once your cleaning logic ran against it.


### Week 7: Feature Engineering & Visualization

1. Learn basic feature engineering and feature extraction concepts
2. Build simple visualizations (distributions, bar charts) to surface data problems visually
3. Turn your project's findings into a clear, readable report (console output, Markdown, or a notebook)


* [Identifying and Extracting features](https://ds500.paiml.com/course/y7ji0/2/2/2) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Feature engineering concepts](https://ds500.paiml.com/course/y7ji0/2/2/3) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Graphing data](https://ds500.paiml.com/course/y7ji0/2/3/2) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Data Visualization](https://ds500.paiml.com/course/0mcoe/20/1/2)


**Weekly demo video prompt:** Walk through your project's generated report and show one chart that makes a data problem obvious at a glance.


### Week 8: Ship & Finalize

1. Run your project against the [self-assessment checklist](./SELF_ASSESSMENT.md)
2. Polish the README with real setup/usage instructions and sample output
3. Publish the repository publicly and write a short portfolio/LinkedIn post linking to it


* [Lesson Recap working with Dataframes](https://ds500.paiml.com/course/o184n/4/2/7) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Clustering data](https://ds500.paiml.com/course/y7ji0/2/3/3) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)


**Weekly demo video prompt:** Give a full demo of the finished data-quality tool against your dataset, and one problem it caught that you didn't expect.

Finish the project: publish the repository, run it against the [self-assessment checklist](./SELF_ASSESSMENT.md), and write a short portfolio/LinkedIn post pointing at the repo. Rolling learners get a closing email when they hit this week; cohort learners present on the end-of-run call instead of (or in addition to) posting.


## The Project

The whole program is built around a single project you start in Week 1 and ship in Week 8: a data-quality/profiling tool that detects problems in a real dataset you choose. See [PROJECT.md](./PROJECT.md) for what that means and how to scope it, and the [self-assessment checklist](./SELF_ASSESSMENT.md) for what "done" looks like.

> [!IMPORTANT]
> **Pick a dataset you actually care about**, not a pristine textbook CSV. Messy, real data (yours, your workplace's, or a public dataset with known quirks) makes for a far more interesting project — details in [PROJECT.md](./PROJECT.md).

The primary two resources for building an LLM solution on a local API:

1. [Python Essentials for MLOps](https://ds500.paiml.com/course/o184n) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)



#### Data Science References

* [Using public Datasets for data science](https://ds500.paiml.com/course/9dyuw/4/3/7) · [Coursera](https://www.coursera.org/learn/data-engineering-rust)
* [Aws resources for Exploratory data analysis](https://ds500.paiml.com/course/y7ji0/2/1/6) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [MLOps Platforms: Amazon SageMaker and Azure ML](https://ds500.paiml.com/course/y7ji0) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)


### Referenced Media and Resources

* [Python MLOps Cookbook](https://github.com/noahgift/Python-MLOps-Cookbook)
* [GitHub Codespaces](https://github.com/features/codespaces)


<details>
<summary><b>Optional supplementary readings & media</b></summary>

* [Python for Data Science with Colab and Pandas in One Hour](https://ds500.paiml.com/course/o184n/4/1/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Data Science, Pandas, and Colab](https://ds500.paiml.com/course/o184n/4/1/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Linux and Bash for Data Engineering](https://ds500.paiml.com/course/nyu26) · [Coursera](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)

</details>

## Community

Join the shared PAIML Discord to ask questions, share progress, and post your weekly demos. If you're in a cohort, you'll also get invited to a dedicated channel for your run, alongside the shared server.

# Astronaut Occupation Counts by Gender
This repository was created for a data exploration project using Python and pandas, based on a dataset originally provided by Tidy Tuesday. It focuses on breaking down astronaut occupation data by gender, then counting and comparing how often each occupation appears for male vs. female astronauts.

## What's in this repository?
* `astronauts.csv` – the original raw dataset from Tidy Tuesday
* `Sex_Occupation_Counts.csv` – a cleaned, subsetted version of the data that shows a count of occupations separated by gender
* A Python notebook documenting each step used to process and clean the data

## What is the purpose of this repository?
The goal of this project is to explore how occupations among astronauts vary by gender. After filtering the dataset by gender, we created counts of each unique occupation for males and females, then combined that information into a single, clean table for easier analysis or visualization.
This kind of exploration can:
* Give insight into gender representation in space-related careers
* Help anyone interested in gender equity in STEM fields
* Provide a beginner-friendly Python example of subsetting and value counting using `pandas`

## Where did the data come from?
The data in this project comes from **Tidy Tuesday**, a weekly social data project hosted in the [R4DS (R for Data Science) GitHub repository](https://github.com/rfordatascience/tidytuesday). Each week, they release a new, publicly available dataset to encourage data exploration, visualization, and storytelling.
>The astronaut data featured in this repository was pulled from one of these weekly challenges. It was originally shared in `.csv` format and includes information like astronaut names, missions, occupations, and more.
To get started with the data, head over to the notebook
>[`How to Create Subset.ipynb`](./How_to_Create_Subset.ipynb)  
It walks you through how the data was cleaned, filtered by gender, and turned into a clear table showing occupation counts for male and female astronauts.

## Visualization
To highlight differences in astronaut occupations by gender, a **side-by-side bar chart** was created using **Tableau**. This visualization allows for an easy comparison of how frequently different occupations appear among male and female astronauts in the dataset.
The chart visually supports the analysis by making gendered trends in occupation more apparent at a glance.
### Gender Distribution of Astronaut Occupations
![Visualization](https://github.com/user-attachments/assets/43204416-08d4-451b-8817-0cf38d19815b)
>Bar Chart created with Tableau

## Maintainers & Contributors
This repository is maintained by **unc-jpquinn** as part of an ENGL105 course project. All contributions were made by the repository owner.

## Need Help?
This repository was created for a course project and isn’t actively maintained.  
You’re welcome to [open an issue](../../issues) if you have a question, but responses aren’t guaranteed.

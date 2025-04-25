# :rocket: Astronaut Occupation Counts by Gender :couple:
This repository was created for a data exploration project using Python and pandas, based on a dataset originally provided by Tidy Tuesday. It focuses on breaking down astronaut occupation data by gender, then counting and comparing how often each occupation appears for male vs. female astronauts.

## :file_folder: What's in this repository?
* `astronauts.csv` – the original raw dataset from Tidy Tuesday
* `Sex_Occupation_Counts.csv` – a cleaned, subsetted version of the data that shows a count of occupations separated by gender
* A Python notebook documenting each step used to process and clean the data

## :books: What is the purpose of this repository?
The goal of this project is to explore how occupations among astronauts vary by gender. After filtering the dataset by gender, we created counts of each unique occupation for males and females, then combined that information into a single, clean table for easier analysis or visualization.
This kind of exploration can:
* Give insight into gender representation in space-related careers
* Help anyone interested in gender equity in STEM fields
* Provide a beginner-friendly Python example of subsetting and value counting using `pandas`

## :globe_with_meridians: Where did the data come from?
The data in this project comes from **Tidy Tuesday**, a weekly social data project hosted in the [R4DS (R for Data Science) GitHub repository](https://github.com/rfordatascience/tidytuesday). Each week, they release a new, publicly available dataset to encourage data exploration, visualization, and storytelling.
>The astronaut data featured in this repository was pulled from one of these weekly challenges. It was originally shared in `.csv` format and includes information like astronaut names, missions, occupations, and more.
To get started with the data, head over to the file `How to Create Subset`
It walks you through how the data was cleaned, filtered by gender, and turned into a clear table showing occupation counts for male and female astronauts.

## :open_file_folder: How do I get started?
To get started with this project, you have a few options depending on your goals:
1. **Learn how the data was cleaned and subsetted**:  
   If you're interested in learning how to process data using Python, open the [`How to Create Subset.ipynb`](https://github.com/unc-jpquinn/engl105_astronaut_data/blob/main/How%20To%20Create%20Subset.ipynb) file. This is a notebook that walks you through the steps to filter the dataset by gender, count astronaut occupations, and clean the data for easier analysis.
2. **Examine the original raw data**:  
   If you prefer to work with the original dataset or just want to explore the data in its raw form, open the [`astronauts.csv`](https://github.com/unc-jpquinn/engl105_astronaut_data/blob/main/astronauts.csv) file. This will give you access to the full dataset with astronaut names, missions, occupations, and other details.
3. **Explore the cleaned dataset**:  
   If you're only interested in the results, you can check out the [`Sex_Occupation_Counts.csv`](https://github.com/unc-jpquinn/engl105_astronaut_data/blob/main/Sex_Occupation_Counts.csv) file, which contains the cleaned data showing the occupation counts separated by gender.

Each of these options will help you interact with the data in different ways, depending on what you're looking to achieve!

## :bar_chart: Visualization
To highlight differences in astronaut occupations by gender, a **side-by-side bar chart** was created using **Tableau**. This visualization allows for an easy comparison of how frequently different occupations appear among male and female astronauts in the dataset.
The chart visually supports the analysis by making gendered trends in occupation more apparent at a glance.
### Gender Distribution of Astronaut Occupations
![Visualization](https://github.com/user-attachments/assets/43204416-08d4-451b-8817-0cf38d19815b)
>Bar Chart created with Tableau

## :question: Getting Help
This repository was created for a course project and isn’t actively maintained.  
You’re welcome to [open an issue](../../issues) if you have a question, but responses aren’t guaranteed.

## :bust_in_silhouette: Maintainers & Contributors
This repository is maintained by **unc-jpquinn** as part of an ENGL105 course project. All contributions were made by the repository owner.

## :envelope: License
This project is for educational purposes and does not include a specific license. Please refer to the original Tidy Tuesday license terms for dataset use.

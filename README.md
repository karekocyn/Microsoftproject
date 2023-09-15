# Microsoftproject
Film Success Analysis: Language , Budget and Movie Category
By Kareko Cynthia Vanessa 

Overview

Microsoft, a global technology giant known for its software and hardware products, has 
ventured into the entertainment industry by establishing its own movie studio. Film 
production encompasses the critical business aspects, including box office performance, 
budget allocation, and audience engagement among other variables. Our methods 
encompassed exploratory data analysis and visualizations. Key findings include the most 
common language used in movies, the success of franchises as compared to stand alone 
movies, and the correlation between production budget and gross earnings. We have also 
included recommendations to guide Microsoft’s film production strategy.

Business understanding

In response to the evolving landscape of the entertainment industry, Microsoft embarked on 
an initiative to establish its own movie studio. The objective was to explore the creation of 
original video content. This project aims to provide actionable insights to guide Microsoft's 
new movie studio in deciding what types of films to create.
Data Understanding
The data used was sourced from popular movie data sites i.e., Box Office Mojo (Box Office), 
The Movie Database (TMDb), and The Numbers (TN). The datasets contain columns and key 
variables helpful to our analysis; Movie title, original language, domestic gross, worldwide 
gross, popularity and production budget.

• Data cleaning
We started by inspecting the dataset to gain an understanding of its structure and content.
We then handled the missing data by identifying them and either dropping or imputing 
depending on the analysis.
Next, we detected duplicate records by Identifying and removing duplicate rows from the 
dataset. Duplicate records can skew statistical analyses and produce inaccurate results.
Finally, we converted data types to ensure that data types are consistent with the intended 
analysis by:
 Converting data to the appropriate data types (e.g., dates, integers, strings).
 Standardizing data formats to ensure that data is consistently formatted (e.g., date formats, 
currency symbols).

Data Analysis

1.Evaluating Franchise Success
The chart below illustrates the average worldwide gross earnings for two movie categories: 
franchise and standalone. The horizontal axis (x-axis) represents the movie categories: 
"Franchise" and "Standalone." The vertical axis (y-axis) represents the average worldwide 
gross earnings in dollars ($). Franchise movies have a significantly higher average worldwide 
gross compared to standalone movies. The data suggests that, on average, movies associated 
with a franchise tend to perform substantially better in terms of worldwide box office 
earnings compared to standalone movies.

2. Identifying most common movie language
The chart below illustrates the distribution of movies across various languages. English, 
represented by the tallest bar, is by far the most common language in which movies are 
produced. Other languages, indicated by shorter bars, have significantly fewer movies 
associated with them. The data clearly illustrates that English dominates the film industry, 
serving as the primary language for a large majority of movies. The substantial number of
English-language movies suggests the global influence and reach of English-speaking cinema.

4. Investigating the relationship between production budget and gross earnings
These plots illustrate the relationship between production budgets and movie earnings, both 
domestically and worldwide. In both plots, there is a concentration of movies with low 
budgets and correspondingly lower gross earnings. However, movies with medium or higher 
budgets are spread out more evenly across different levels of gross earnings. Some highbudget movies have achieved high gross earnings, while others have only reached average or 
lower gross figures. The data suggests that a significant portion of movies operates within 
limited budgets, and their earnings tend to align with their budget levels.

Conclusion

The analysis conducted in this project yields valuable insights for microsoft's entry into the film industry.Here are the key takeways and recommendations::

Movie category(franchise & standalone) vs gross earnings - In conclusion,franchise movies have a substantially higher average worldwide gross compared to standalone movies, suggesting the potential advantages of investing in established franchises in the film industry.

Language analysis - In conclusion, the bar chart underscores the overwhelming prevalence of English-language movies in the film industry, highlighting the significance of English as a dominant language in global cinema.

Budget vs gross earnings -In summary, the scatter plots reveal that while the majority of movies are concentrated in the low-budget and lower-gross region, those with medium or higher budgets are scattered across various levels of gross earnings, emphasizing the complex relationship between production budgets and box office performance.

## Repository Structure

The project repository is organized as follows:

- 📁 **data**: Contains datasets used for analysis.
  - 📄 `tmdb.movies.csv`: The main dataset used for analysis.
  - 📄 `tn.movie_budgets.csv`: Additional datasets for reference.
  - `   bom.movies_csv`: Additional datasets for reference.

- 📁 **images**: Contains visualizations and plots.
  - 📄 `bargraph.png` : image of the bar graph
  - 📄 -bargraph.png  : image of the bar graph
  - 📄 `scatterplot.png`: image of the boxplot

  
- 📁 **presentation**: Presentation slides summarizing the project.
  - 📄 `project report.pdf`: The document containing the detailed information concerning the analysis
  -  📄 `project slides.pdf`: This is a document that contains slides that are a summary of the analysi

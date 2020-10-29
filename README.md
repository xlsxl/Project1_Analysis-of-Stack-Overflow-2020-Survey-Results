
### Analysis of Stack Overflow 2020 Survey Results



### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Below libraries are required in execution of the codes that i supplied in Jupyter Notebook.<br>
   * Pandas
   * Numpy
   * Matplotlib
   * Seaborn
   * Sklearn

I donwloaded the Stack Overflow 2020 survey data using this [link].<br>
For the Population 2020 data, i downloaded the data from [kaggle], thanks to Tanu N Prabhu.<br>

[link]: http://insights.stackoverflow.com/survey/ 
[kaggle]:https://www.kaggle.com/tanuprabhu/population-by-country-2020


## Project Motivation<a name="motivation"></a>

For this project, I analyzed the Stack Overflow data from 2020 and tried to cover below topics:

1. How is the distribution of the respondents according to countries, does the distribution represents<br> 
the countries well according to their population ?<br>

2. What are the most popular (currently being worked and desired to work next year) programing languages<br>
in mostly represented countries ?<br>

3. How is the distribution of following features in those countries ?<br>
   * Job satisfaction
   * Primary field of study
   * Education Level
   * Employment and Job seeking status
   * Education importance<br>
   
4. What are the most effected features on job satistaction ? <br>

   I created a Logistic Regression Model, in order to predict the job satisfaction status. <br>
   Very dissatisfied and Slightly dissatisfied values are labelled as Dissatisfied; <br>
   Neither satisfied nor dissatisfied values are deleted from data and Slightly satisfied and Very satisfied are labelled as Satisfied. <br>
   
 5. Conclusions <br> 

## File Descriptions <a name="files"></a>

There is only one [jupyter notebook] available including complete study on above questions. <br>

[jupyter notebook]: https://github.com/xlsxl/Project1_Analysis-of-Stack-Overflow-2020-Surveys-Results/blob/main/Project1_Analysis-of-Stack-Overflow-2020-Survey-Results.ipynb


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://ozkanoztork.medium.com/you-are-a-satisfied-developer-arent-you-95170cc45ad4).<br>

Summary of the results:<br>
Having the top respondent density and greater positive effect ratio on satisfaction, Sweden seems to have the most satisfied developers.<br>
Although Pakistan has the greatest positive effect ratio on job satisfaction; because it has lowest respondent density, i can not conclude that it has the satisfied developers.<br>

We can conclude that most dissatisfied developers are from Israel, due to it’s respondent density is higher and it has top negative effect ration among the countries.<br>
As programing languages, Python and TypeScript have increasing popularity, however JavaScript is still mostly used language.<br>

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

You can find the Licensing for the Population 2020 data at Kaggle link available [here](https://www.kaggle.com/tanuprabhu/population-by-country-2020).<br>

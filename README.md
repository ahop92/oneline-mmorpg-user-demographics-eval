# Online MMORPG User Demographics Evaluation


## Background 

One script was developed to evaluate different profit data from a software/gaming company. The raw data was housed by CSV excel files. The goal was to develop a python/jupyter scripts that manipulates the pandas and numpy libraries to evaluate the data and offer a high level analysis.

### Heroes of Pymoli Code Functionality

Each section of code pulls from the raw data and creates dataframes to store the subsets of information and to avoid overwriting original raw data. The whole script is sectioned according to the type of analysis requested (gender demographics, age demographics, purchasing according to age, etc.). Generally, the script relies on merging the subsets of data around shared columns or indicies to create the final summary tables in each output. In the case of the age data, bins were manipulated to group the users by age bracket. Lastly, in general the output information was formatted according to the option request found in the instructions. 

The following high level analyses were completed: 

1. Player Count
2. Total Purchasing Analysis (no delimiting factors or demographics)
3. Gender Demographics
4. Purhcasing Analysis by Gender
5. Age Demographics 
6. Purchasing Analysis by Age
7. Top Spenders (by Screenname)
8. Most Popular Items 
9. Most Profitable Items

### Results 

No output file or images were requested. For the script, the output of each section can be viewed using the Jupyter Notebook interface directly after each section of code. The sections must be run sequentially since each later section often has dependencies from those prior. 

# Compare States for Optimal Customer Base


## Project Highlights
### Research Question:
Which state, California or Washington, would provide the most significant potential for business success based on the ideal customer demographic of above average income?

### Scope of Project:
This project's scope is to use Jupyter Notebooks, NumPy, Pandas, Matplotlib, and Seborn Libraries to compare Washington and California census data and determine which state has the highest proportion of client-determined ideal customer demographics of above-average income males. Additional examination of population demographic correlations will provide further insight into counties with more substantial customer potential. Using bar charts and scatter plots will provide a visual analysis of the additional factor correlations. The analysis result is a recommendation to the client of which state offers more business opportunities and which counties within that state are ideal for relocation. The project scope does not include an analysis of race, commute time, or other states besides the two states specified.
Project Overview:
Due to its iterative nature and adaptability, I used an agile project planning methodology for the project organization. The project was conducted iteratively with defined stages of gathering data, cleaning data, analyzing data, creating visuals, and presentation. Each stage was conducted in sprints which allowed for feedback from the client and evaluation of each step as it was completed.
I used a virtual environment within the coding platform VS Studio Code and various additional tool extensions. The project used a Jupyter Notebooks platform to easily compile code with outputs in an organized, accessible format. I used the programming language Python to create functions and interact with the dataset. I used Python libraries Pandas, NumPy, Matplotlib, and Seaborn to manipulate, conduct numeric analysis, and create visuals and graphs. Panopto was used to create a video presentation of the project and results to the client.

## Project Execution
### Methodology
Using an agile methodology to guide the planning process, allowed for the client to be involved the Meet and Plan, Design, Develop, Release, and Feedback phases guide precise project planning and defined expectations of each phase.
Meet and Plan: Client and I discussed expectations and determined project particulars such as scope, budget, timeline, and requirements.
Design: Using the client-agreed-upon census data, I gathered and reviewed the dataset to ensure it was suitable for the agreed-upon project plan and client requirements.
Develop: During development, data cleaning, processing, and analytical exploration was performed. Jupyter Notebooks and Pandas were used to create functions and additional libraries for statistical analysis.
Release: The results will be presented to the client with visuals and insight findings based on the guidelines determined during the meeting and plan phase. Based on the analyzed data results, I provided recommendations.
Feedback: This phase of the project will allow the client to provide feedback and make changes to the scope or any other requirements they may desire for the investigation

### Variance of methodology:
No changes to project planning or organization methods were made. The client appreciated the agile workflow presented and the flexibility it allowed.

### Project Plan
Much of the proposal plan remained in place for the project and the client approved the objectives and deliverables presented during the project planning phase.

### Objective 1:
Determine which state between Washington and California has more ideal customers based on county and state income averages.
Deliverable 1.1: This objective's deliverable is to create a function to calculate each state's average income separately and which counties have an average income above the state average and logs the results in a separate column of 1s for above state average and 0s for not above the state average.
Deliverable 1.2: The objective's deliverable is to conduct a statistical analysis comparing the proportion of above-average incomes in each state.

### Objective 2: Determine significant correlations between counties and ideal customer factors.
Deliverable 2.1: A deliverable of the objective is to create a bar graph depicting males per top counties with above-average incomes.
Deliverable 2.2: A deliverable of the objective is to create a scatterplot illustrating population t otals and income.

### Objective 3: Present analysis insights to client
Deliverable 3: Create a Panaopto video to present the project process, finding, and recommendations to the client.

### Variance in Plan:
The analysis results and recommendations were originally planned to be presented in a Tableau dashboard, but after considering the degree of information to be presented, a video presentation with explanations was decided to be more appropriate.
### Timeline, Milestones, Cost:
The client approved the milestones as presented in the project proposal but asked for adjustments to milestones and budget.
Milestone or deliverable Duration (hours or days) Projected start date Anticipated end date
Gather Dataset
1 hour
06/11/2024
06/11/2024
Clean Dataset 10 hours 6 hours
06/11/2024
06/12/2024
Analize Dataset
3 days
06/13/2024
06/16/2024
Create Visuals
8 hours
06/17/2024
06/17/2024 Create Dashboard 8 hours 06/18/2024 06/18/2024
Present to Client
1 hour
06/20/2024
06/20/2024
There was no change to price proposal and the client approved the proposed costs.
1. Hardware item: No cost
2. Software – VS Studio: No cost
4. 44 work hours: $880 (44 hours at $20 per hour)
Variance of milestones and cost:
The data required less time for cleaning, so I decided to reduce the predicted time. The dashboard milestone is no longer part of the plan since deciding on a video presentation; thus, it has been removed from the timeline and milestones. The project proposal included a $1000 fee for hardware, but upon review, it was determined that since no new hardware was needed for the project, the fee would be removed.

## Data Collection Process

### Data selection/collection:
I used the 2017 US census data suggested during the project proposal and finalized it with the client during planning. The dataset contains demographic and economic data for each county. The 2017 US
census data is appropriate for analyzing California and Washington for the highest opportunity for the client's business to succeed. The client wants to know where to relocate that will offer a population that matches its ideal client demographics of primarily males and above-average income.
Variance of selection/collection:
The collection and selection of the dataset did not change from the project proposal; the client is interested in regions to move, and the dataset fulfills that requirement.
Data handling/processing:
I encountered no obstacles or variances from the planned data collection outlined in Task 2.
Data governance, privacy, security, ethical, legal, and regulatory compliance:
Kaggle.com is a public data source containing datasets for free public exploration. The US census dataset obtained from Kaggle.com does not contain any personally identifiable information or licenses that would present privacy, security, ethical, governance, or legal compliance concerns that would jeopardize the integrity of any individual or institution or the integrity of this project.
Variance of data governance, privacy, security, ethical, legal, and regulatory compliance:
No obstacles or variances occurred while evaluating the data and its governance integrity.

### Advantages and Limitations of Data Set
Advantage of dataset:
The census data has averages of multiple socio and economic demographics for each county in all 50 states. It provides excellent regional data for exploring and analyzing how the client's ideal customer is represented in each State and county to narrow down where they should consider relocating and opening a storefront.
Disadvantage of dataset:
The dataset does not provide census information for the ideal customer demographics of men with over-average incomes. Instead, it has income averages by county and count of men in the county. It was impossible to know precisely how many men per State or county had individual incomes above average, which limited the specificity of the analysis.

### Data Extraction and Preparation
Data Extraction:
I downloaded the 2017 US census data, acs2017_county_data.csv, from Kaggle.com and read the CSV file into a Jupyter Notebook using Pandas, just as proposed, with no variances.
Data Preparation:
The dataset for this project has already been adequately cleaned and is complete. Still, I needed to filter the data to remove unneeded data, such as data for states other than California and Washington and data outside the scope of the project goals. I determined the average income of each state, used a boolean function to decide which counties per state have above-state average incomes, and stored the results in a new column called ‘Target_Income.’ I also created a column to isolate the counties with more men than women and called it ‘Target_Demo.’
Variance of data preparation:
The original plan did not include a column for ideal customer demographic of which counties had majority men. This addition to the data processing, allowed the analysis to compare regions of high ideal customers easily.

## Data Analysis Process

### Data Analysis Methods
This project aimed to identify which state, California or Washington, provides the most significant potential for business success based on the ideal customer demographic of above-average income.
For the statistical analysis of the two different population proportions, I used a two-sample z-test with a type 1 error rate of 5% to determine which of the two states, if any, has the higher proportion of ideal customer populations based on income. This method worked well for the project because the population mean comparison is based on proportion rather than population size, resulting in a more accurate representation of state demographics compared to each other. To narrow the investigation even further, additional analysis was conducted on qualitative data of males in the counties of the dominant state. The evaluation is in a series of bar graphs. The correlation analysis of male populations refined the analysis of ideal customer characteristics across the state.

### Advantages and Limitations of Tools and Techniques
Tool advantages:
1. VS Studio Code: Code editor environment tailored with needed platforms and languages creating a streamlined space with the project requirements, files, programs, and languages in one easy to navigate space.
2. Python: programming code language used to create functions and interact with the dataset and user friendly to review outputs in real-time and easy troubleshooting.
3. Jupyter Notebooks: platform used to compile code with outputs together in an organized, easy format.
4. Pandas Library: used for reading csv files into a workable dataset. Has tailored functions for data analysis and manipulation of dataset for cleaning and removing unneeded data.
5. NumPy Library: numerical analysis and support for calculations that compare statistical insights without having to manually write each equation.
6. Matplotlib Library: Allowed for quick visuals and analysis by creating graphs.
7. Seaborn Library: Along with Matplotlib, this library allowed for more detailed statistical data visuals.
8.Stasmodel.api: Used for ease of statistical modeling and
9. Panopto: Used to make video presentation of project and recommendations for client’s review

Tool disadvantages:
1. VS Studio Code: It is important that correct programming interpreter is selected, or the environment will not run correctly.
2. Python: If desired libraries and modules must be downloaded, Python will not function to its full capabilities.
3. Jupyter Notebooks: The block format of the platform can lead to lengthy and repetitive displays.
4. Pandas Library: Is not compatible with massive and unstructured datasets.
5. NumPy Library: Uses Nan for null values and may cause issues when comparing values across platforms.
6. Matplotlib Library: Visuals and graphs are less appealing than other libraries.
7. Seaborn Library: Can be slow to run and use a lot of memory
8.Statsmodel.api: Can be confusing if user does not understand the stats tests to use
9. Panopto: Recording only, no option to include video calls for real-time feedback and questions from stakeholders

### Application of Analytical Methods
Step-by-step of analytical methods applied and requirements for verification:
Gather/explore data:
a.
Import dataset into Jupyter Notebook with Pandas read_csv() function
b.
Review data frame structure and observe for obvious issues:
a.
View data table first 5 rows using head() function
a.
Visually observe and confirm data formation and note values
b.
Identify the columns required are present: State, County, Income, Men, Women, TotalPop
a.
Men- count
b.
Income- average
c.
Use info() for overview of datatypes, shape, null values

Clean data:
a.
Create a new data frame, using copy(),that only obtains data related to California and Washington
b.
Use nunique() to view number of unique values per feature and confirm only two are in the State column
c.
Look for completeness of data using info()
d.
Check for any duplicated rows with duplicated()
e.
Remove columns not needed for the analysis using the .drop() function
a.
Confirm dataset has been created as desired using info()
b.
View number of unique values per column to see if any counties might be represented more than once.
f.
Create two new columns called Target_Income and Target_Demo containing values for counties matching the ideal customer demographics.

Statistical analysis of the two different population proportions:
a.
Establish hypotheses and metrics
a.
Null- California and Washington are equal in proportion of above average incomes
b.
Alternative- California and Washington are not equal in proportion of above average incomes
c.
Metrics to establish p-value (probability)- two-sample z-test
d.
Alpha value used to determine statistical significance - 5%= 0.5
b.
Conduct test
a.
Isolate counties with above average incomes per state into separate variables called cal_income_above and wash_income_above
b.
Create values for the count of total counties per state called n_cal and n_wash
c.
Use proportions_ztest() from sm.stats to obtain z_score and p_value
d.
Observe results compared with the alpha to determine results- p>a = reject the null and p<a= accept the null

Qualitative analysist of males in the counties of the dominant state:
a.
Create a dataset with only ideal customer demographics
b.
Use matplotlib to create bar graph to analyze the correlation of majority male populations and above average incomes of top 5 counties with highest total population.
c.
Use matplotlib to visually inspect the correlations on counties that meet customer demographics and income.

## Data Analysis Results
### Statistical Significance
To assess which state the client's small business would succeed in, I needed to determine which of the two states has more regions with above-average income. Since California and Washington differ in size and county count, statistical testing provided a more accurate comparison of the two states. I used a two-proportion z-test to compare the proportion of counties with above-state average incomes in both states. I used a null hypothesis of no significant difference in the proportion of incomes above the average between California and Washington and an alternative hypothesis of a difference existing.
I found the two proportions of regions with above-average income in each state and then found the overall proportion.
#num of CA counties with above state average income cal_income_above = len(df[(df['State'] =='California') & (df['Target_Income'] == True)]) #num of WA counties with above state average income wash_income_above = len(df[(df['State'] =='Washington') & (df['Target_Income'] == True)]) #num of counties in CA n_cal = len(df[df['State'] == 'California'] == True) #num of counties in WA n_wash = len(df[df['State'] == 'Washington'] == True)
I then calculated a z-score and p-score using proportions_ztest() function from statsmodel.api z_score, p_value = sm.stats.proportions_ztest(count=[cal_income_above, wash_income_above],nobs=[n_cal, n_wash], alternative = 'larger')
z-score = 0.03111771794122532
p-value = 0.48758782981894583

The z-score represents the standard deviation of the population means, and the p-value is the probability of that z-score under the null hypothesis. I compared the z-score and the p-value with the alpha value of 0.05 to determine if the null should be rejected or accepted. The p-value is 0.48 and significantly above the 0.05 threshold, indicating significant evidence to accept the null hypothesis. The z-score is 0.03 and supports the p-value observed because its value is below zero, meaning the difference in means is equal. The evidence validates the null hypothesis that there is no difference in the proportion of counties with above-state average incomes between California and Washington.
### Practical Significance
This project gave the client practical insight into which region offers the most opportunity for their small business based on the ideal customer demographics of males with above-average income. Relocating a business is a precarious decision with many factors that may impact its success, and particular analysis is critical to the future and stability of the company. The z-test conducted showed the client that both states are regionally equal in the proportion of ideal customers based on incomes above the state average, and both provide positive business potential.
Once it was established that California and Washington held substantial opportunities equally for relocation, focusing on gender trends pointed the client to twelve counties that matched the ideal customer demographics of males in above state average income areas. provide the least risk and best opportunity for relocation and business success. Using graphs to explore the ideal customer counties they clearly show that the two states remain relatively even in counties that meet the client criteria. A side-by-side barh chart comparing county incomes and populations shows three strong candidates for the client to consider for relocation: Snohomish Washington, Santa Clara, California, and San Francisco, California.

### Overall Success
The analysis is successful and effective in its goal of providing a small tailoring business with state and county analysis to determine which states and counties offer the most opportunity for business success based on ideal customer characteristics of males with above-average incomes.
Since California and Washington differ in size and county count, statistical testing provided a more accurate comparison of the two states. The z-test successfully confirms no difference in the proportion of counties with above-state average incomes between California and Washington, and both provide positive business potential. Focusing on gender trends, I successfully identified twelve counties that matched the ideal customer demographics of males in above-state average income areas. The project has met the criteria outlined and effectively provides the client with the perfect customers for their business and relocation options.

## Conclusion

### Summary of Conclusions
I used a two-proportion z-test to compare the proportion of counties with above-state average incomes in both states. The analysis results were thorough in their proportional comparison done through statistical testing of state incomes to find both provided ideal options for the client to consider. The exploratory analysis through graphs narrowed the search down to twelve counties with above-average incomes and majority male populations. The project identifies twelve regions with the ideal customers, providing the best opportunity for their business to flourish.

### Effective Storytelling
The visualizations used in this project were created using Python libraries and MatPlotlib. The pie chart shows the distribution of ideal customers between California and Washington, with California having seven counties with ideal customers and Washington with. Next, I used a side-by-side bar chart to compare the populations and average incomes of the target counties and observed which counties stood out, providing a solid visual of how the counties differ. Another barh chart shows the income of the counties only producing different stand out counties than when comparing income and population. These charts tell a story of which counties have the most ideal customer demographics and which are more economically advanced. These observations create a narrative pointing to top options for clients to relocate their business.

### Recommended Courses of Action
This project asked which state, California or Washington, would provide the most significant potential for business success based on the ideal customer demographic of above-average income. The client is considering relocating to either California or Washington. The perfect customer demographic is male, with an above-average annual income. The client is interested in obtaining and maintaining a customer base of return customers. The analysis informs the client that there is no significant proportional difference in ideal customers based on average income between California and Washington. And investigate which counties may provide more opportunities for the new store to be a success through statistical and qualitative analysis. I have narrowed down the optimal regions for the customer to consider to twelve counties, all with above-the-state average incomes and majority male populations.
Based on population and income comparisons, I recommend Santa Clara, California, to the client for optimal business opportunities. This county has a high population of ideal customers and strong economy to support the new businesses and maintain a customer base for future growth.

Another option the client should consider is a Satna Barabra county. Since the client is interested in returning customers, a region with a smaller population but a high income could be ideal.
The analysis has provided two recommendations to the client. Both options identify high areas of ideal customer demographics that will give the best opportunity for their small tailoring businesses to thrive.


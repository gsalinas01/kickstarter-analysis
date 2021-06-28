# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
 * The purpose of this analysis is to uncover trends in kickstarter data in order to find out the best plan of action for starting a campaign. 
    

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
 * Data from the Outcomes category ("successful", "failed", and "canceled") was compared against the Year category (launch date) of all campaigns.
 * The data in the Parent Category was then filtered for the "theater" subcategory, which provided insight to determine during which months this category had the most success or failures.  

### Analysis of Outcomes Based on Goals
  * Data from the Outcomes category was plotted against the Goal category to determine the relationship between the goal-amount ranges and the percentage successful, failed, or canceled projects.
  
### Challenges and Difficulties Encountered
  * A challenge encountered was determining the best way to present the data in a manner that was simple, yet insightful.
  * Research into github syntax for presentation and tutorials on various styles helped solve this issue.

## Results

- What are two conclusions you can draw about the Theater Outcomes based on Launch Date?
    * Based on the kickstarter data for the Theater category, there were more successful campaigns in May. 
    * On the other hand, it is important to note that May, June, July, and October also had similar amounts of failed campaigns.
<img src="https://user-images.githubusercontent.com/60943801/123563288-835f2f00-d779-11eb-8e4d-7226501bcebe.png" width="700" height="500">

- What can you conclude about the Outcomes based on Goals?
    * Based on Goals, the "plays" subcategory displayed the most success with campaign goals less that $5,000. 
    * Failed campaigns projected a peak 100% fail rate with campaign goals of $45,000 - $50,000.
    * This seems to indicate that campaigns with lower goals had a greater success rate than campaigns with higher goals.
 <img src="https://user-images.githubusercontent.com/60943801/123563323-aee21980-d779-11eb-8904-0e4b8be7cb37.png" width="700" height="500">


- What are some limitations of this dataset?
    * Outliers  
      * Data that is deviant from the rest can distort our statiscical analysis and interrupt the assumptions we make.
      * Example: The goal category for all kickstarter data presents a median of $5,000, while the mean jumps to $71,939. This drastic change between mean and median suggests outliers in the data and is confirmed by goal amounts such as $10,000,000 for the campaign "Project: eXelcius - Next Generation Movie".
    * Errors
      * While some errors may be more simple in nature, such as a typo, others require deeper analysis.
      * Example: Certain formulas require data to have values greater than 0. This means that we either need to switch up formulas to achieve more concrete results, or clean up the data to exclude values that are not consistent with our assumptions. 

- What are some other possible tables and/or graphs that we could create?
-   * Scatter plots. For example, in order to visualize the trend between launch dates and subcategory success, this would be a great tool because we could see if there is a positive or negative correlation.
-   * Pie charts. Pie charts are simple enough to provide a good picture of what the data consists of. This would be a great tool to display, for example, the total amount of successful, canceled, and failed campaigns in the data before diving into deeper analysis.
    
    [~$Kickstarter_Challenge.xlsx](https://github.com/gsalinas01/kickstarter-analysis/files/6722491/Kickstarter_Challenge.xlsx)

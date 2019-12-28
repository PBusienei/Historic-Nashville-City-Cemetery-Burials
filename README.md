# Historic-Nashville-City-Cemetery-Burials

The city of Nashville provides a dataset of known burials in city cemeteries from 1846 through 1979. This dataset holds factual information, but it also offers a fascinating glimpse into historical trends in medicine, literacy, racial equality, and more.

The Nashville City Cemetery Association has asked you to explore the dataset to create charts that can be used in marketing materials. The following exercises are a starting point for exploring the data and creating visualizations. Once you have completed the exercises below, create additional visualizations to accompany storytelling points. An example of this is shown below for the first exercise.

![top 10 causes](/assets/top_10_death_causes.png)

1.	Used a pivot table to find the 10 most common (known) recorded causes of death, and evaluate the counts of each type. Once the metrics had been established, plotted in a **bar chart**. In the analysis of the top 10 causes of death, there was  spelling mistakes that are affecting the counts. For example, assume Cholera and Cholrea are the same cause of death. Created a new column in the original dataset to update spelling errors to make the count of the top 10 causes more accurate. There was a need to **refresh the pivot table** to see changes applied.

2.	Created a line chart showing number of burials per year. Determined what years were there the most burials? Dig to find ideas as to why?

3. Examined deaths for each decade beginning with the 1850s. Looked at the total number of deaths and the proportion of male deaths to female deaths. Use a **pivot table** with a **slicer** to do this, and created a clustered bar chart to show how male and female deaths have changed over time.

4. Next looked at how age at time of death has changed over time. Added a column to the original dataset to classify each row to one of the following categories (0-18, 19-25, 26-40, 41-64, and 65+). Was keen about a strategy to deal with missing values. Made a series of pie charts or donut charts to show the breakdown of each age group for these four periods: before 1880, 1881-1900, 1900-1920, after 1920.

5. Examined burials by month. Determined the months with higher burials? Determine the top five causes of death for each month? Chose a visualisation that conveys the differences well.

6. Created a new column titled Last Name. Extracted the last name from the Name column by subsetting to all characters to the left of the comma. This will result in many errors for rows missing commas.   
    a. 	Drilled down to those rows without a comma – what do you notice?  
    b.	Looked at the most common last names of people buried in this cemetery?  
    c.	Determine the famous person buried in this cemetery. 
    
7. Determined any interesting patterns regarding where (`Section/Lot`) people were buried?


#### Created a new sheet for each pivot table or analysis work done to create a visualization and gave each sheet a descriptive/meaningful name. Put all final charts (along with the related story) on their own worksheet. 

# Project Title
# Insights into content trends to inform strategic decisions

## Problem Statement

Social Buzz is a fast growing business unicorn that need to adapt quickly to its global scale. Accenture has begun a 3 month POC focussing on these tasks:
- An audit of their big data practice 
- Recommendations for a successful IPO 
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity


### Steps followed 

- Step 1 : Load data into Microsoft Excel, dataset is a csv file.
- Step 2 : The client has sent through:
    - 7 data sets - each data set contains different columns  and values.
   - A data model - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.
   ![Web capture_22-1-2024_202053_cdn theforage com](https://github.com/devika-santhosh/Power-BI-Project/assets/125188753/4d6d347b-7150-4c59-bb37-45e13e76ff15)
- Step 3 : Identified the datasets for the analysis which are 'Reaction', 'Content', and 'Reaction Types'
- Step 4 :To clarify why I made this selection:
  - The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
  - As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
  - We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
  - So, to figure out popularity, we’ll have to add up which content categories have the largest score.
- Step 5 : Clean the data by:
  - removing rows that have values which are missing,
  - changing the data type of some values within a column, and
  - removing columns which are not relevant to this task.
    - Think about how each column might be relevant to the business question we’re investigating. If we can’t think of why a column may be useful, it may not be worth including it.
- Step 6 : Cleaned the data by removing null values and unnecessary columns. 
- Step 7 : Data Modelling: To completed data modelling, following these steps:
  - Create a final data set by merging your three tables together. [Hint: You can use a “VLookUp” formula]
  - Figure out the Top 5 performing categories

- Step 9 : Build your presentation Structure
           
- Step 10 : Presenting the conclusion before the client. 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.
![Web capture_22-1-2024_20452_cdn theforage com](https://github.com/devika-santhosh/Power-BI-Project/assets/125188753/280e26ea-61d9-4288-b6fb-26049d2ace98)
![Web capture_22-1-2024_204517_cdn theforage com](https://github.com/devika-santhosh/Power-BI-Project/assets/125188753/e3a65170-f1c9-40a7-9268-272c89f1968b)

Finally tackled this task and found the top 5 most popular categories as asked, but I also went one step further.
- Found that animals and science are the two most popular categories, suggesting that users like "real-life" and "factual" content
- Also found that food was a common theme amongst popular content and the most popular food category was healthy eating
- This could be a signal to show the types of people that are using your platform, and you could use this insight to boost engagement even further. For example, we could run a campaign with content focused on this category or work with healthy eating brands to promote content.
- As much as this analysis was insightful, I would love to help you with similar analysis.

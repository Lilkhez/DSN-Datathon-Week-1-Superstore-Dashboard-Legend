# DSN-Datathon-Week-1-Superstore-Dashboard-Legend

##Project Title: #RE-VIZ-IT Challenge
###1. Introduction
This project is part of the #RE-VIZ-IT challenge for week 28 of 2023. The challenge aims to revisit a classic Tableau visualization exercise originally presented in the summer of 2018. The goal is to recreate a visualization that previously required complex techniques, such as additional sheets, custom charts, and sheet swapping. Participants are encouraged to attempt the challenge, comparing it to the original, and share their solutions. The full details can be found here https://workout-wednesday.com/2023w28tab/

###2. Requirements
1.	KPIs: Create Key Performance Indicators (KPIs) for Sales and Profit.
2.	State Map: Create a map displaying data by state.
3.	Bar Chart: Create a bar chart showing data by subcategory.
4.	Dimension Selection: Allow users to select between two dimensions.
5.	Measure Selection: Allow users to select between two measures.
6.	Colour Legend: Only display the colour legend when the map is selected.

###3. Dataset
This project utilizes the Superstore dataset, which can be accessed here [Superstore.xls](https://data.world/stanke/superstore-20214)

###4. Solution Steps
**Data Preparation**
•	Load the Superstore dataset into Tableau.
•	No data cleaning was performed as it was already cleaned. However, it underwent a second verification (data validation) to ensure that it has been thoroughly cleaned.
**Building KPIs**
•	Created two KPIs for Sales and Profit using calculated fields.
•	Display these KPIs prominently on the dashboard.
**Creating a State Map**
•	Utilize geographical data to create a state map.
•	Allow users to select between the two dimensions (e.g., Sales or Profit) for colouring the map.
•	Implement interactivity to enable users to click on states for additional details.
**Developing a Bar Chart**
•	Created a bar chart to represent data by subcategory.
•	Allow users to switch between the two dimensions (e.g., Sales or Profit) and see the corresponding bar chart.
**Implementing User Controls**
•	Set up parameter controls for dimension and measure selection.
•	Configure the dashboard to respond dynamically to user selections.
**Conditional Display of Colour Legend**
•	Apply conditional formatting to display the colour legend only when the map is selected.
•	Provide clear visual cues to guide users on when the colour legend is visible.

###5. Result
The Tableau project successfully recreates the challenge from 2018, offering an efficient and interactive visualization of Sales and Profit data. Users can explore the data by switching between dimensions and measures, and the colour legend is displayed only when the map is selected, enhancing user experience.

###6. Feedback
Feedback on this Tableau project is highly encouraged. Please feel free to provide comments, suggestions, or improvements to the project. Your input will be valuable for enhancing the quality of the visualization and making it more informative and user-friendly.



![coverPic](https://github.com/Lilkhez/DSN-Datathon-Week-1-Superstore-Dashboard-Legend/assets/89860250/b42589c6-5fd4-43f8-b45f-eae547854c04)

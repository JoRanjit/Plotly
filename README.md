# Belly Button bio diversity project using Plotly
### For this project, people wiped cotton swabs in or on their belly buttons. Each participant’s belly button hosted about 67 different species of microbes. Yet not one was common to every person, and only eight were found on at least 70 percent of participants.
#### This Plotly project helps to dive into the research using charts and figures.

##### We created a drop down option where the user could choose from the many samples listed. Based on the selection - charts will be updated with the results of the research like:
    * details of the subject from whom the sample was taken
    * a Plotly horizontal bar chart with the IDs of the microbes found in his belly button and their counts.
        -- IDs of the microbes(otu-id) on y-axis
        -- count of microbes(sample values) on x-axis
        -- the microbe names(otu-labels) on hover-over

![bar chart]( https://github.com/JoRanjit/Plotly/blob/main/Images/Deliverable%20%231%20-%20bar%20chart%20with%20hover.PNG)

##### A bubble chart is generated which also gives a different view of the IDs and counts and types of microbes found on the subject's belly button.
    * we used Plotly's 'scatter' chart option to create this graph,
        -- otu-ids on x-axis
        -- sample values as y-axis
        -- sample values as size of the bubbles
        -- otu-ids as marker colors(using the 'Earth' color-scale)     
        -- otu-lables as hover text

![bubble chart]( https://github.com/JoRanjit/Plotly/blob/main/Images/Deliverable%20%232%20-%20Bubble%20chart.PNG)

#### A gauge chart which showed the wash frequency of the subject per week is also provided
    * we used Plotly's 'gauge' chart option to create this chart
        -- used 'indicator' chart type with the wash frequency as value  
        -- mode is 'gauge+number'
        -- used five steps from 0-2 up-to 8-10 with 10 as max. with 5 different colors.
        -- bar color of gauge is set to black      

![gauge chart]( https://github.com/JoRanjit/Plotly/blob/main/Images/Deliverable%20%233%20-%20Gauge%20chart.PNG)

#### Finally we created a github webpage to host this website - https://joranjit.github.io/Plotly/
    * formatted the sheet using style.css stylesheet
        -- added an image to the jumbotron title bar
        -- added more information about the project as a paragraph
        -- added different back-ground colors to different sections
        -- re-organized the charts and sections to create a better look.

![Final github website]( https://github.com/JoRanjit/Plotly/blob/main/Images/Deliverable%20%234%20-%20Final%20formatted%20version.PNG)

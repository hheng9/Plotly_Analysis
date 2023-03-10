# Plotly_Analysis

## Overview of Analysis
In this analysis we learn the skills needed to create interactive data visualizations with Plotly and JavaScript. We then use the basics of Plotly and create various types of charts as well as manipulate data using JavaScript. Learning how to use event listeners helps us create interactivity within the visualizations. Creating a dynamic chart with a dropdown menu is a key skill that will be helpful in creating a dashboard for the volunteers to view. Plotly and JavaScript gives us the ability to create more advanced and customized visualizations to display more information to our audience effectively.

## Results 

### The program uses Plotly.js to create three types of charts for the selected sample. 
  * Horizontal bar chart of the top 10 bacteria cultures found in the sample.
 ![hBar](https://user-images.githubusercontent.com/118647523/224199993-32907906-c2d7-4126-8d47-5828ce2d11bd.png)
 
  * Bubble chart showing the distribution of bacteria cultures across all samples. 
![bubble](https://user-images.githubusercontent.com/118647523/224200032-f919d882-0f28-4aa2-a8d9-81c9a9745d26.png)

  * Gauge chart displaying the washing frequency for the selected sample.

![wFreq](https://user-images.githubusercontent.com/118647523/224200054-cdb64dd8-b1a5-4ffe-9ead-b8ce3e79ac1d.png)



### The code is a JavaScript program that initializes a dashboard with a dropdown menu to select a sample, and then uses D3.js to load and display data from a JSON file containing samples and metadata.
![drop](https://user-images.githubusercontent.com/118647523/224199793-96752561-209a-4a24-b5cf-40784c7a5f53.png)

### The program updates the charts and metadata panel in real-time whenever a new sample is selected from the dropdown menu, allowing the user to explore and compare the data for different samples.

### The program defines two functions: buildMetadata() and buildCharts(), which respectively create a panel displaying the demographic information for a selected sample and generate interactive plots displaying information about the bacteria cultures found in that sample.







View my site is live at https://hheng9.github.io/Plotly_Analysis/

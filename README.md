# belly-button-challenge

## Link to the visuzalization demo
https://malumisa.github.io/bellybutton_demo.github.io/

In this project, the task to build an interactive dashboard to explore the Belly Button Biodiversity dataset, which gathers the microbes that colonize human navels.
This dataset reveals that a small handful of microbial species (also known as  operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Procedure and steps:
1.	Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
2.	Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  	Use sample_values as the values for the bar chart.
  	Use otu_ids as the labels for the bar chart.
  	Use otu_labels as the hovertext for the chart.
    
    ![image](https://user-images.githubusercontent.com/111699427/216680595-8ae0d09b-46e6-4e60-bd8a-7fb184849e4f.png)
3.	Create a bubble chart that displays each sample.
  	Use otu_ids for the x values.
  	Use sample_values for the y values.
    Use sample_values for the marker size.
  	Use otu_ids for the marker colors.
    Use otu_labels for the text values.
    ![image](https://user-images.githubusercontent.com/111699427/216680777-acb9f143-25b5-49cc-be8c-02cb38a0ce8c.png)
    
4.	Display the sample metadata, i.e., an individual's demographic information.
5.	Display each key-value pair from the metadata JSON object somewhere on the page.
![image](https://user-images.githubusercontent.com/111699427/216680883-2b1dc2e9-ab66-4e5b-a804-66cb26421020.png)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
![image](https://user-images.githubusercontent.com/111699427/216681016-7f1173d7-fe43-444e-8255-786612638f3f.png)

7. dapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ Links to an external site.to plot the weekly washing frequency of the individual.
    You will need to modify the example gauge code to account for values ranging from 0 through 9.
    Update the chart whenever a new sample is selected.
<img width="619" alt="image" src="https://user-images.githubusercontent.com/111699427/216681545-a6c3903e-aca2-4247-b5f0-30f57ddc1301.png">








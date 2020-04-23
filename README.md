# power_bi
<i>This repository is where I am storing any of my work that I'm doing with using Power BI as a analysis tool.</i>

<h3>In this repository:</h3>

<h5>edmonton_weather_project</h5>
<p>I lived in Edmonton, AB for 2 years. Being the most northerly major city in North America, it is a place with what most people would 
consider an extreme weather pattern. So let's dig into the data and see what the weather really is like there!</p>

<p>Currently, the dashboard I developed using Power BI was developed from data downloaded based on the time period for which I lived 
in Edmonton [courtesy of weatherstats.ca in collaberation with Environment and Climate Change Canada]. The raw data was downloaded as a CSV 
file. I then cleaned the data which involved:</p>
<ul><li>Removing columns that were not relevent to the story I wished to tell with this data</li> 
    <li>Removing columns that did not have enough values to display a relevant or significant trend or point of interest</li>
    <li>Removing rows that represented dates outside of the time period I was interested in for this project</li>
    <li>Replacing any value that was listed as empty in a column that I was interested in using with the value "0". It is possible that 
        this was a result of data not being recorded but after investigating the data trends using the value of "0" and then
        as NULL, it makes sense that "0" was what was intended by the data provider.</li>
</ul>

<p>The dashboard itself is fairly rudimentary in design but was still valuable as a project. I learned about how to import data into Power
BI from a CSV file and how to transform the data. I then managed to create a few basic visuals to display a few key findings.</p>

<p>To expand with this project in the future, I am going to write a program in Python that can scrape the website at regular intervals 
to create a live dashboard.</p>

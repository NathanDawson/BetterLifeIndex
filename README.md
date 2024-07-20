# OECD Better Life Index Data Analysis

#### <a href="https://nbviewer.org/github/NathanDawson/BetterLifeIndex/blob/main/NB_betterLifeIndex.ipynb">Jupyter Notebook</a>

### Project Overview
This project aims to showcase my ability to transform datasets using both Excel and 
Python, and to create clear, user-friendly visualisations that allow for actionable 
insights. The dataset used in this project is from the OECD Better Life Index, which
measures well-being across several areas in OECD countries. More information about 
the OECD Better Life Index can be found <a href="https://www.oecdbetterlifeindex.org/">here.
</a>

### Data Description
The dataset contains measures for 38 OECD countries and 3 non-OECD countries, across
24 indicators that are categorised into 11 topic areas: Housing, Income, Jobs, 
Community, Education, Environment, Civic Engagement, Health, Life Satisfaction, 
Safety, and Work-Life Balance.

### Technologies Utilised
<ul>
  <li>Excel</li>
  <li>Python</li>
  <li>Jupyter</li>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>Vega-Altair</li>
</ul>

### Project Workflow

<b>Excel Pre-processing</b>
<ul>
  <li><b>Column Restructuring: </b>Merged nested columns to create single, coherent columns. For example, combined ‘Housing’, ‘Rooms per Person’, and ‘Units (Ratio)’ into ‘Housing – Rooms per Person as rat’.</li>
  <li><b>Column Eliminated: </b>Removed unnecessary columns, such as those used for 
  spacing.</li>
  <li><b>Missing Data Handling: </b>Converted all blank and placeholder cells to ‘NaN’ for better consistency and visibility.</li>
</ul>

<b>Python Pre-processing</b>
<ul>
  <li><b>Missing Data Imputation: </b>For columns with less than 20% missing data, imputed using the median of the column. For columns with over 20% missing data, used K-Nearest Neighbour (KNN) imputation.</li>
  <li><b>Data Cleaning: </b> Ensured all data was formatted correctly for analysis and visualisation.</li>
</ul>

<b>Data Analysis and Visualisation</b>
<ul>
  <li><b>Visualisations Created</b>
    <ul>
      <li>Work-Life Balance</li>
      <li>Income</li>
      <li>Life Satisfaction</li>
      <li>Health</li>
      <li>Safety</li>
    </ul>
    <p>These visualisations were designed to support the exploration and comparison         of well-being across different countries by highlighting essential aspects of        quality of life.</p>
  </li>
</ul>

<b>Ensuring Visualisation Suitability</b>
<ul>
  <li><b>Engaging Design: </b> Utilised a variety of graph types to make the                  visualisations more engaging.</li>
  <li><b>Simplified Metrics: </b>Used familiar metrics like percentage and average,           avoiding complex statistical terms.</li>
  <li><b>Interactive Elements: </b>Included hover features to provide additional              information on data points.</li>
  <li><b>Printability: </b>Added legends and consistent colour scales to ensure the           visualisations are understandable even when printed.</li>
</ul>

<b>Application of Design Principles</b>
<ul>
  <li><b>Gestalt Theory</b>
    <ul>
      <li><b>Law of Proximity: </b>Ordered bar charts in descending order for easy                comparison.</li>
      <li><b>Law of Continuity: </b>Used layered datasets in choropleth graphs for                complex relationship interpretation.</li>
    </ul>
  </li>
  <li><b>PARC Design Principles</b>
    <ul>
      <li><b>Repetition: </b>Consistent colour scale across all visualisations to                 unify the presentation.</li>
    </ul>
  </li>  
</ul>

<b>Use of Colour and Interactive Elements</b>
<ul>
  <li><b>Colour: </b>Utilised the same colour scheme with varying shades to represent different data values, creating a cohesive look.</li>
  <li><b>Interactive Features: </b>Enabled users to hover over data points to reveal additional information, enhancing the exploration experience.</li>
</ul>

<b>Coordinated Views Design</b>
<ul>
  <li><b>Layout: </b>Arranged visualisations in a 2x2 grid for easy side-by-side comparison, with a larger choropleth graph accessible by scrolling.</li>
</ul>

<b>Considerations for Language and Text</b>
<ul>
  <li><b>User Accessibility: </b> Ensured all language and text used were understandable by a wide audience, avoiding complex statistical jargon.</li>
</ul>


### Conclusion
<p>This project demonstrates my capability to:</p>
<ul>
  <li>Transform and preprocess datasets in Excel and Python.</li>
  <li>Handle missing data effectively.</li>
  <li>Create insightful and user-friendly visualisations.</li>
  <li>Apply design principles to enhance data presentation.</li>
  <li>Communicate findings in an accessible manner.</li>
</ul>
<p>By showcasing this project, I aim to highlight my data analysis skills and my ability to create actionable insights through effective data visualisation.</p>

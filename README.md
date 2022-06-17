# README File

Make sure that all libraries are installed, such as plotly, Dash, and pandas. Once all libraries are installed and all packages are imported, simply run the file called "main_KTQ.py". This will generate 6 different plots and will promptly pop up in a web browser. If at any point, the user does not want to see a particular plot, the "fig.show" in the respective function or the function in the main method can be commented out in the "main_KTQ.py" file to view all other plots. 

In the user interfeace, plotly allows the user to hover over the names of the given data points to obtain specific values. If the user does not want to see a specific scatter line or part of the part, the value can be simply unchecked in the legend. Some plots are interactive in question 1 and 3, containing a slider which will allow the user to change the year specified.

The data is merged in separate files for the research questions 2 and 3. The file "merged_foot_print.py" merges the food-footprints csv based on the Entity and an inner join. A new file file
"foot_footprints_total.csv" is the complete file of the merged csv files. This file is primarily used for research question 2. The file titled "merged_CO2_life.csv" is merging "emissions.csv", "life_expectancy.csv" and "supply_life_expectancy.csv" to have a complete picture of how emissions from various countries has changed with respect to life expectancy over the time period. This 
file "merged_env_life.csv" is produced and is analyzed in research question 3. All the csv and py files are present in the folder that is submitted to the project.

Lastly, for the drop down menu with a line plot, navigate to the file named "question_3_dash.py". Make sure pandas, numpy, and Dash libraries are installed. This can be done by entering "pip install [insert library name]". Once all packages are imported and libraries installed, run the file. In the terminal, a website will appear to view the line plot, namely
http://127.0.0.1:8050/. Open this link to view it by pasting this URL in a web browser or using Cmd (or Ctrl) + Click. If an error occurs, Port8050 may be in use by another program and the other application will have to be terminated. Once the application is open, the page will allow the user to choose a country. Select a country and the data will update. Use Cmd (or Ctrl) + C
to quit the program in the terminal.

# RecruitingShiny
Welcome to the **RecruitingShiny** repository! This project contains the code for an R shiny app that visualizes NCAA Division 1 football recruiting data from 2000 to 2024. The app maps the hometowns of recruits, providing insights into geographic recruiting patterns and trends across years and schools. 

**Overview**

The **RecruitingShiny** app leverages college football recruiting data from the `cfbfastR` package to plot player hometowns on an interactive map using the `leaflet` package within R. With filtering options, users can explore where recruits for varius schools and years are coming from, enabling deeper analysis of recruitment trends. 

**Example Use Case**

In the example below, we filter for recruits in the year **2024** who committed to **Penn State**. This setup allows users to view the hometowns of 2024 Penn State recruits on the map. 
1. Use the **Year** filter to select **2024**
2. Use the **School** filter to select **Penn State**
3. The map updates to only display recruits from this selection

<img width="959" alt="recruitingshinysc" src="https://github.com/user-attachments/assets/86ead021-c2b1-4d8e-95af-df3af03fb7ee">

**Repository Structure**

- **app.R**: Main file containing the shiny app code.
- **.Renviron**: Environment file that contains API key for college football database.
- **README.md**: Documentation for understanding the project setup, features, and usage.

**Future Improvements**
- Include more summary statistics on each team (e.g., positions breakdown)
- Plot the actual latitude and longitude of the players high school instead of hometown to get a better understanding of where the best high school football teams in each state are located.

**Contributing**
If you're interested in contributing, please submit a pull request or open an issue with ideas for improving the app. 

**License**
This project is licensed under the MIT license. See the `LICENSE` file for details.

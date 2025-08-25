# CS340 Project Two

### Functionalities/Requirements Overview

-   Interactive filter options (Radio Inputs)

    -   Water Rescue

    -   Mountain Rescue

    -   Disaster Rescue

    -   No filters

-   Geolocation for selected animals

-   A pie chart that dynamically changes to applied filters

### Tools Used

-   MongoDB (crud_module.py)

    -   For querying various filter options

-   Pandas

    -   Converting JSON dictionary format into a table format

-   Dash (Plotly)

    -   Displaying database contents using

    -   Create a user-friendly interface using HTML style syntax

    -   Dynamically update upon filter selection

    -   Dynamic map for the selected animal

    -   Dynamic pie chart displaying the percentage of breeds

### Tests

Main dashboard (Default view)

<https://youtu.be/-Tpj3f1qAS8>

Selecting an animal

<https://youtu.be/R3JpffKy4jg>

Scrolling through filter options

<https://youtu.be/DB8P1aHkx5o>

### Challenges

Initially, I had trouble understanding how callbacks worked for data
filtration; however, after looking at the documentation for Dash, I
could understand how they worked. I also had some trouble in deciding
which input to use for the project. Otherwise, I did not have had too
much trouble with the rest of the project.

### Resources

[RadioItems](https://dash.plotly.com/dash-core-components/radioitems)

[Callbacks](https://dash.plotly.com/basic-callbacks)
# CS-340

A Dash web application that interacts with an Animal Shelter database and displays information using data tables, charts, and a geolocation map. This is a comprehensive code, and it seems to be well-structured. Here's a brief overview of what the code does:

The code imports necessary libraries and modules such as Dash components, Plotly, Pandas, and the AnimalShelter module.

It initializes the AnimalShelter object with your credentials and retrieves data from the database, which is stored in a Pandas DataFrame.

The layout of the Dash app is defined using HTML and Dash components. The layout consists of a title, radio buttons for filtering options, a data table, and two sections for charts.

Callback functions are defined using the @app.callback decorator. These functions handle interactions between components and update the content of the app dynamically based on user actions.

The update_dashboard callback updates the data table based on the selected filter type.

The update_styles callback updates the style of the selected columns in the data table.

The update_graphs callback generates a pie chart based on the selected data in the data table.

The update_map callback generates a geolocation map with markers based on the selected data in the data table.

The app object is created using the JupyterDash class.


A Python class named AnimalShelter that encapsulates CRUD (Create, Read, Update, Delete) operations for interacting with an "Animal" collection in a MongoDB database. The class uses the pymongo library to communicate with the MongoDB server. 

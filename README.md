# CS340
Grazioso Salvare Rescue Dashboard
Project Overview
This project is designed to support Grazioso Salvare, an innovative international rescue-animal training company, in identifying dogs that are potential candidates for various types of rescue operations. By utilizing data from animal shelters around Austin, Texas, this dashboard allows Grazioso Salvare to filter and visualize data effectively, helping them make informed decisions about which dogs to train for specific rescue scenarios.

Functionalities
Dashboard Features
Interactive Data Table: Displays the unfiltered view of the Austin Animal Center Outcomes data set, allowing users to filter based on specific criteria such as type of rescue.
![image](https://github.com/jmdonnell423/CS340/assets/91856296/94221fe8-1d96-4307-961f-b3c554c30143)
 

Geolocation Chart: Maps the location of selected animals, providing a visual representation of their last known location.
 ![image](https://github.com/jmdonnell423/CS340/assets/91856296/f46dd687-79cc-44c7-b3fe-b06abea22cfc)

Age Distribution Chart: Visualizes the age distribution of selected animal types to aid in identifying suitable candidates for rescue training.
 ![image](https://github.com/jmdonnell423/CS340/assets/91856296/48a3750b-a2be-4c09-9358-4fd720219ac3)

Dynamic Filtering: Users can apply filters based on the type of rescue—such as water, mountain, or disaster rescue—to view relevant animal data.
 ![image](https://github.com/jmdonnell423/CS340/assets/91856296/1b1120a7-db9f-4830-9ad8-8c42e1260293)

User Interaction
Filter Selection: Through radio buttons, users can select the type of rescue to filter animals accordingly.
Data Selection: Clicking on a row in the data table updates the charts to reflect detailed information about the selected animal.
Technologies Used
MongoDB: Chosen for its flexibility with unstructured data and scalability, which is crucial for handling varying formats of data from animal shelters.
Python: Utilized for backend development, interfacing with the database using a custom CRUD module to manage MongoDB operations.
Dash by Plotly: Provides the frontend framework, facilitating the creation of interactive, web-based dashboards with Python.
Plotly: Used for creating the interactive charts that dynamically update based on user interaction with the data table.
Setup and Installation

Clone the repository:
bash
Copy code
git clone https://github.com/jmdonnell423/CS340.git

Navigate to the project directory:
bash
Copy code
cd grazioso-salvare-dashboard

Install required packages:
Copy code
pip install -r requirements.txt

Run the application:
Copy code
python app.py
Screenshots
Dashboard Initial State: Shows the dashboard upon loading with default settings.
Filtered by Water Rescue: Displays the dashboard after applying the Water Rescue filter.
Filtered by Mountain Rescue: Shows the results after selecting Mountain Rescue.
Reset State: The dashboard after hitting the 'Reset' filter to show all data.
(Include actual screenshots in your Word document as specified in the project submission requirements.)

Challenges Encountered
Data Integration: Ensuring that data from various sources conformed to a unified format suitable for analysis proved challenging and required extensive preprocessing.
Dynamic Chart Updates: Implementing the logic to update charts based on table selection involved complex state management and callback functions.
Conclusion
The Grazioso Salvare Rescue Dashboard serves as a comprehensive tool to aid in the selection process of rescue animals, tailored to specific rescue needs identified by Grazioso Salvare. Its development from concept to deployment demonstrates effective application of modern web technologies and database management practices.

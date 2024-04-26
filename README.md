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

Writing Maintainable, Readable, and Adaptable Programs
In software development, particularly when working on projects like the CRUD Python module from Project One, several best practices ensure that the code remains maintainable, readable, and adaptable:

Modularity: Building the application in modular components, as demonstrated in the CRUD module, allows each part to be developed, tested, and debugged independently. This modularity also supports adaptability, making it easier to update or replace components without affecting the rest of the system.
Documentation and Comments: Proper documentation and inline comments in the code are crucial. They help other developers (and future you) understand why certain decisions were made, what each part of the code does, and how the components interact.
Consistent Coding Standards: Following consistent naming conventions and coding standards improves readability and helps maintain consistency throughout the project, reducing the cognitive load required to understand the code.
Version Control: Using version control systems like Git allows you to track changes, revert to previous states, and collaborate efficiently with others.
Testing: Implementing tests (unit tests, integration tests) ensures that each part functions correctly and continues to do so as the project evolves.
Advantages of Working with a CRUD Module:

Reusability: The CRUD module created for Project One can be imported and utilized in any other project that requires database operations, reducing redundancy and ensuring consistency.
Separation of Concerns: By isolating the database operations in a separate module, the codebase becomes cleaner and easier to manage. The separation also enhances security as changes to the database structure or credentials can be managed in one location.
Scalability: It's easier to scale and optimize a module focused on database interactions than to rework embedded database calls spread across an application.
Future Use of CRUD Module:

Different Projects: The same CRUD module can be adapted with minimal changes to fit different projects that require similar database operations.
Microservices Architecture: In a microservices architecture, having a dedicated service handling all data interactions (like a CRUD module) can simplify the development and maintenance of other services.
Teaching Tool: It can be used as an educational resource to teach database connectivity and manipulation using Python.
Approach to Problem Solving as a Computer Scientist
Approach:

Analytical Thinking: Start by understanding the problem thoroughly, including all requirements and constraints. Break the problem down into smaller, manageable components.
Research and Planning: Investigate existing solutions, technologies, and tools that can be leveraged. Plan the solution architecture by considering factors like scalability, performance, and maintainability.
Iterative Development: Develop the solution incrementally, testing each part as it's built. This approach helps in catching issues early and integrating feedback effectively.
Review and Refactor: Continuously review the code for potential improvements and refactor it for better performance and readability.
Differences from Other Assignments:

Scope and Integration: This project required integrating multiple technologies (Python, Dash, MongoDB) and applying them in a coherent system, which might be broader in scope compared to assignments focused on single technologies or theories.
Real-World Application: The project was directly linked to real-world applications, making it essential to consider aspects like user experience and data integrity more deeply.
Future Techniques for Database Creation:

Data Modeling: Focus on robust data modeling to ensure the database is optimized for the queries it will need to support.
Security Measures: Implement strong security measures from the start, including data encryption and secure access controls.
Scalability Planning: Design the database with scalability in mind, considering potential future growth in data volume and access frequency.
Importance of Computer Scientists
Computer scientists develop solutions and technologies that have a profound impact on various aspects of business and society. By creating efficient and effective software and systems, they enable organizations to operate more effectively. In the case of Grazioso Salvare, the project helps the organization streamline the process of identifying suitable animals for rescue training, thereby enhancing their operational efficiency and effectiveness in rescue operations.

Impact:

Innovation: Drive innovations that can transform industries, making processes smarter and more efficient.
Problem Solving: Address and solve complex problems using computational approaches, significantly impacting business outcomes and societal issues.
Enhancement of Capabilities: Improve existing systems and processes, allowing organizations to do more with less and to leverage data in decision-making processes effectively.
By mastering these skills and approaches, you not only contribute to specific projects like those for Grazioso Salvare but also build a foundation for addressing future challenges in various domains.

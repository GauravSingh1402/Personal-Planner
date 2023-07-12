
<h1 align="center" id="title">Personal Planner</h1>

<p align="center">
    <a href="https://personal-planner.onrender.com/">View Live Project</a>
  </p>

<p id="description">
Personal Planner is a task management tool built using Flask, HTML, and CSS with Jinja Templating and an SQLite database. It provides a project-based task management solution to help users efficiently categorize and manage their tasks. With features like project creation, task management, and profile editing, Personal Planner offers an intuitive and personalized task management experience.</p>

<h2>📃 Table of Contents</h2>

* [Features](#features)
* [Installation Steps](#installation-steps)
* [Built With](#built-with)
* [Usage](#usage)

<h2 id="features">💡 Features</h2>

Here're some of the project's best features:

-   User Authentication:
    
    -   Sign up and log in to the application to access personalized task management features.
-   Dashboard:
    
    -   Upon logging in, users are presented with a dashboard displaying their existing projects and an option to create a new project.
-   Project Management:
    
    -   Create multiple projects to categorize and organize tasks effectively.
    -   Access each project individually to view and manage its associated tasks.
-   Task Management:
    
    -   Create, update, and delete tasks within each project.
    -   Mark tasks as completed, which moves them to a separate section called Completed Tasks.
-   Profile Editing:
    
    -   Users can edit their profile details such as name, email address, and password through the My Profile section.
   
<h2 id="installation-steps">⚙️ Installation Steps</h2>
To run SummaSense locally, follow these steps:

1.  Clone the frontend repository:
```
git clone https://github.com/GauravSingh1402/Personal-Planner.git
```

2. Navigate to the project directory:
```
cd Personal-planner
```

3. Set up a virtual environment (optional but recommended):
```
virtualenv venv
source venv/bin/activate
```

4. Install the dependencies:
```
pip install -r requirements.txt

```
5. Export Flask environment variables:

-   For Linux/Mac:
	```
	export FLASK_APP=app.py
	export FLASK_ENV=development
	```
-	For Windows:
	```
	set FLASK_APP=app.py
	set FLASK_ENV=development
	```
6. Start the server:
```
flask run
```

<h2 id="built-with">💻 Built With</h2>

-   Flask
-   HTML
-   CSS
-   Jinja Templating
-   SQLite

<h2 id="usage">🖱️ Usage</h2>

1.  Sign up or log in to access the Personal Planner application.
2.  On the dashboard, create new projects to organize your tasks.
3.  Access individual projects to create, update, and delete tasks.
4.  Mark tasks as completed, moving them to the Completed Tasks section.
5.  Edit your profile details, such as name, email address, and password, in the My Profile section.

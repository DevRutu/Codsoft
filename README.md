<div align="center">
<h1>Task Manager</h1>
A Python-Django Task Manager Project with REST API 
<br>
<br>
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue">
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green">
<h3>Project's Short Demo</h3>


</div>


## Technology Used

-   **Frontend:** HTML5, CSS3, Bootstrap5, JavaScript
-   **Backend:** Python=3.11.4, Django=4.2.5
-   **Database:** PostgreSQL, (Hosted on Render for Production)
-   **Static and Media Upload:** AWS S3 Bucket using Cloudflare R2
-   **API:** Django-REST-Framework
-   **Version Control:** Git, GitHub
-   **Editor:** VS Code
-   **Operating System:** Windows
-   **Browser(Tested On):** Google Chrome, Microsoft Edge, Mozilla Firefox




## API Details

-   **Endpoint:** http://127.0.0.1:8000/tasks/api/v1/tasks
-   **Method:** GET
-   **Description:**
    -   Returns all the tasks
-   **Endpoint:** http://127.0.0.1:8000/tasks/api/v1/tasks/1
-   **Method:** GET, PUT, PATCH, DELETE
-   **Description:**
    -   Returns a single task
    -   Updates a single task
    -   Partially updates a single task
    -   Deletes a single task

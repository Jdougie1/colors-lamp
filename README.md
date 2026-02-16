\# COLORS (LAMP Stack)



\## Description

COLORS is a LAMP-stack web app with a PHP API and a browser frontend that supports user login and color operations (add/search) through API endpoints.



\## Technologies Used

\- Linux / Apache / MySQL / PHP

\- HTML, CSS, JavaScript



\## Project Structure

\- `api/` - PHP API endpoints

\- `public/` - frontend files (HTML/CSS/JS)



\## Setup (High Level)

1\. Deploy the project under an Apache web root.

2\. Create a MySQL database and tables expected by the API (`Users`, `Colors`).

3\. Update the database credentials in the PHP files (placeholders in this repo).

4\. Open the frontend in a browser.



\## How to Run / Access

\- `http://localhost/<project-folder>/public/`  

or  

\- `http://<server-host>/<project-folder>/public/`



\## Assumptions / Limitations

\- Requires a working Apache + PHP + MySQL environment.

\- DB schema must match what the endpoints expect.



\## AI Usage

\- Used AI to help format documentation and remove sensitive credentials from source files.


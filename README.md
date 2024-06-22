# Backend-Server-Windows-App The Project File is in the zip form

 https://github.com/SmithaSV/Windows-App.git
The above link is for frontend of Windows App.

 Building the backend application using TypeScript and Express.js, start by setting up development environment. Ensure having Node.js and npm (Node Package Manager) installed.
Create a new Express App project using TypeScript in Visual Studio Code
Install the required packages:

express: npm install express

body-parser: npm install body-parser

typescript: npm install typescript

Create the three endpoints:

/ping: a GET request that returns true

/submit: a POST request that saves the submission to the database

/read: a GET request that retrieves a submission from the database based on the index query parameter

Use a JSON file (db.json) as the database to store submissions

After the Instllations of the packages, type npm start in the terminal to start the server in the port 3000.

Now the Backend Server is established.

The Screenshots attached below are testing in Postman API.


![read](https://github.com/SmithaSV/Backend-Server-Windows-App/assets/84849699/25838b77-f852-4d85-a376-474d3b858f44)
![submit](https://github.com/SmithaSV/Backend-Server-Windows-App/assets/84849699/42de60af-c4f6-4015-9d1f-9df216677d24)
![Search](https://github.com/SmithaSV/Backend-Server-Windows-App/assets/84849699/f06feb7c-62e8-4f69-aea9-8fb078b67f3c)
![ping](https://github.com/SmithaSV/Backend-Server-Windows-App/assets/84849699/63603dae-fadf-4ed4-89f8-c9d1e719d621)

![db json](https://github.com/SmithaSV/Backend-Server-Windows-App/assets/84849699/398451e9-e17f-481b-8994-566443d3c776)
This is the db.json where the data is stored.

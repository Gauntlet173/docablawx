# Docablawx

This is a demonstration created for DocaCon 2023, showing the deployment of a Blawx
server and a Docassemble server.

## Installation

`docker compose up -d`

Go to `https://localhost:8000` and register as a Blawx user. Create a new Project from the
"Old Age Security Act" example.

Note that it may take up to 5 minutes for docassemble to launch.

Go to `http://localhost`, and once docassemble is ready, log in as admin/password, and go to the Playground.

Click the "Upload" button and upload `oasa.yml`.

Click "Save and Run". If you create a single individual named "jonathan" (note lower case)
and say "yes" to whether he was a pensioner, you will receive the following response:

![Example Response](docablawx_demo.png)
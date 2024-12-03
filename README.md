﻿# CD_project

### Setting up

Open 'src/main/resources/application.yml' and add your Github OAuth2 credentials:
client-id: <YOUR_CLIENT_ID>
client-secret: <YOUR_CLIENT_SECRET>

Make sure while creating OAuth2 app use 'http://localhost:8080' as homepage URL and 'http://localhost:8080/login/oauth2/code/github' as Authorization Callback URL

Run the project and visit 'http://localhost:8080/login` to start the login process.

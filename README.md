## How to use.

In the project directory, you can run:

### `docker-compose build`

You will have to make a docker-compose.yml file at the root of your project, which will describe the different
docker services used.
This file must include at least the Docker service server used to launch the application on port 8080 .

### `docker-compose up`

The validation of the integrity of your application will be done when launching the docker-compose up request.
The server service will run by exposing the port 8080

### `about.json`

The server service will respond to the request http://localhost:8080/about.json .
The json will explain the services, the widgets linked to them and even their parameters and parameters types.

**Note: this project is still on dev.**

![Login](https://raw.githubusercontent.com/GregoireDuhem/Dashboard-Epitech/main/Front/src/Assets/Screenshots/Capture%20d’écran%202022-04-05%20à%2018.57.12.png)

![MainPage](https://raw.githubusercontent.com/GregoireDuhem/Dashboard-Epitech/main/Front/src/Assets/Screenshots/Capture%20d’écran%202022-04-05%20à%2018.58.38.png)

![Profile](https://raw.githubusercontent.com/GregoireDuhem/Dashboard-Epitech/main/Front/src/Assets/Screenshots/Capture%20d’écran%202022-04-05%20à%2018.59.05.png)

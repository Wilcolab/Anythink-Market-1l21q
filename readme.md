# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/08/2022 @vanessa-cooper]:** So the first thing first.  We just need to install the Docker Application from the  https://docs.docker.com/get-docker/   as per your system (like: Mac, Windows , Linux ). 

Step 2 : We just need to create a virtualiation  setup . 
 <!-- For windows  https://docs.microsoft.com/en-us/windows/wsl/install-manual#step-6---install-your-linux-distribution-of-choice  -->
 Step 3: After you completed the installation of the WSL-2 setup .
 It's the right time to start and run the DOCKER Application. 

 Step 4: Just keep the DOCKER Application running in the background and open the terminal where your root folder is located and to check if the docker is working properly, just type the following command. 
 <!--
  C1 : docker -v
  C2: docker-compose -v
  -->

Step 5: type the command  'docker-compose up' from the project root directory to load Anythink's backend and frontend.

If Docker is working correctly, the backend should be running and able to connect to your local database.

Step 6 : Let's test this by pointing your browser to http://localhost:3000/api/ping

Step 7:Now, it’s time to check the frontend and make sure it’s connected to the backend.
Visit :  http://localhost:3001/register 


and that's all Ka'BOOM ! 

That's all we needed ! 

Phew! I think that's not too much for this setup 😁.
05/08/2022 - 0:42am




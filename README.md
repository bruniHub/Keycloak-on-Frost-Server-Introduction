# Keycloak on Frost Server Introduction
## Preface
All exmaples are run with a docker-compose file. You can find seperate files for Keycloak and Frost or use the file in the *shared* folder which runs both services at once. To get no conflicts with different programs running locally on your machine make sure to check **docker container ls** and stop those containers.
A detailed description about docker-compose and all relevant comands can be found on https://docs.docker.com/get-started/
## Set up Keycloak
Frist start the Keycloak server with said docker-compose files. Both files run the server on http://localhost:8080 . Now you can find the admin console of Keycloak in your webbrowser. To login use the user **admin** with the password **Pa55w0rd**. After you loged in you have to create a new client for the Frost server. To do this navigate to the realm **master** which should be already initialized and create a new client. ![Keycloak-Clients](https://user-images.githubusercontent.com/43475725/125331575-72511900-e348-11eb-958a-f22bd8c5b394.png)

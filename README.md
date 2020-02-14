# docker-compose


Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure
your application's services. Then, with a single command, you create and start all the services from your configuration. ... Run docker-compose up and Compose starts and runs your entire app.

![](https://solutionsanz.files.wordpress.com/2017/08/compose.png?w=633)

Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. To learn more about all the features of Compose, see the list of features.

Compose works in all environments: production, staging, development, testing, as well as CI workflows. You can learn more about each case in Common Use Cases.

Using Compose is basically a three-step process:

    Define your app’s environment with a Dockerfile so it can be reproduced anywhere.

    Define the services that make up your app in docker-compose.yml so they can be run together in an isolated environment.

    Run docker-compose up and Compose starts and runs your entire app.



#Docker Compose installation
#Check the current release and if necessary, update it in the command below:
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
#Next, set the permissions to make the binary executable:
sudo chmod +x /usr/local/bin/docker-compose
#Then, verify that the installation was successful by checking the version:
docker-compose --version

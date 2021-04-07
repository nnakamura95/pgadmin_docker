# pgadmin_docker

## Step 1 
Start docker-compose
> mkdir docker

> docker-compose up

## Step 2
Once the container is running you should be able to access http://localhost:5050/

Use email address as follow:
> admin@adming

Use password as follow:
> root

## Step 3
- Click Servers > Create > Server to create a new server.

- Select the General tab. For the name field, use any name. 

## Step 4

Run the following command.
> docker ps

Grab the CONTAINER ID of postgres and run the following comand
> docker inspect container_ID_number | grep IPAddress

※ Example command
>docker inspect fcc97e066cc8 | grep IPAddress

Copy the IP address that is display and past in the Host of the Connection tab of the pgadmin page.

For the Username:
> postgres

For the Password:
> postgres

Finally, click the "Save password?" and then click Save




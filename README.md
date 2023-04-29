# Upgrade-of-Odoo14-to-16
To do this, we must follow the officual docker-hub documentation https://hub.docker.com/_/odoo/

The script to run is in the repo above (Remove the mount lines in the volumes).

If you come across the error below:

![image](https://user-images.githubusercontent.com/99332618/235287915-9521b881-8012-4461-a676-8c9de264f881.png)

There is a solution:

![image](https://user-images.githubusercontent.com/99332618/235287937-4177e99e-1d53-453a-b117-15e7be637567.png)

And it will run:

![image](https://user-images.githubusercontent.com/99332618/235288006-e6ed87f7-7f96-4fc0-9218-e835484baab1.png)

If you have a orphan container error: To solve use the link https://stackoverflow.com/questions/50947938/docker-compose-orphan-containers-warning

![image](https://user-images.githubusercontent.com/99332618/235288117-8e49f2ff-af8f-4c79-831a-b350e66ccf4f.png)

The problem is that we have two docker-compose files in a project and in order to solve this, we must create a docker-compose file for each project.

![image](https://user-images.githubusercontent.com/99332618/235288179-826c6c58-048b-4a6a-a597-fb0b2b2ade2b.png)

![image](https://user-images.githubusercontent.com/99332618/235288234-4bc0e66a-8a28-4c7c-8aa6-8cf7f5d2e19f.png)




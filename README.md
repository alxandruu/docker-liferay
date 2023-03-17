# docker-liferay

All files inside the folders are going to be executed only once, to create the images. When the images are created the data inside this folders are not required.
- liferay: All files inside this folder are going to be deployed and override into the liferay container.
- sql: Folder containing all the .sql files to be executed in the mysql container. To verify that all files have been executed correctly, the SQL container must finish     accepting connections.
- Database root password is "root".

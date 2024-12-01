# MacOS-Database-Setup-Docker-Azure-Data-Studio-Guide
1. Download Azure Data Studio
2. Download Docker
3. Open Terminal and paste this command "docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=Justice1234" -p 1401:1433 --name sqlserver -d mcr.microsoft.com/mssql/server:2019-latest"
4. Open Docker and check if container is created, than run the container.
5. Now go to Azure Data Studio -> go to Connections -> New Connections -> <img width="497" alt="image" src="https://github.com/user-attachments/assets/27d4ca77-41b9-4c3f-9b06-ac63d8e91b12">
Password: Justice1234
6. Click on Connect and you are done

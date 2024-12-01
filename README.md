# MacOS-Database-Setup-Docker-Azure-Data-Studio-Guide
1. Download Azure Data Studio https://learn.microsoft.com/en-us/azure-data-studio/download-azure-data-studio?tabs=win-install%2Cwin-user-install%2Credhat-install%2Cwindows-uninstall%2Credhat-uninstall#download-azure-data-studio
2. Download Docker https://www.docker.com/products/docker-desktop/
3. Open Terminal and paste this command "docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=Justice1234" -p 1401:1433 --name sqlserver -d mcr.microsoft.com/mssql/server:2019-latest"
4. Open Docker and check if container is created, than run the container.
5. Now go to Azure Data Studio -> go to Connections -> New Connections ->
6. Password: Justice1234
<img width="497" alt="image" src="https://github.com/user-attachments/assets/27d4ca77-41b9-4c3f-9b06-ac63d8e91b12">

7. Click on Connect and you are done
8. Now you are able to see this
    <img width="1438" alt="image" src="https://github.com/user-attachments/assets/a7bb395a-1ace-45c9-bce4-b26de916bf6a">
9. You can Create Database by clicking the 'Databases'


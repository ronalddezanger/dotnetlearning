# Learning and experimenting with .NET subjects 

added webapp and blazor pwa

Make a elasticsearch view search

## Run a docker SQL SERVER

```Batchfile
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=SQLServer@Test01" -p 1433:1433 --name sql1 --hostname sql1  -d mcr.microsoft.com/mssql/server:2022-latest
```
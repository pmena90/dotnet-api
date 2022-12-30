# dotnet-api
Dotnet core api (Boilerplate).
- MySql 
- Azure storage (user avatars)
- Sendgrid
- JWT token custom auth

## Development
Create a mysql database and provide the connection-string in the appsettings.json. 

Restore your dependencies:
```console
dotnet restore
```

Run migrations (From APICore.Data project):
```console
dotnet ef database update -s ..\APICore.API
```
Run the API project:
```console
dotnet run
```

> Note: You can use windows azure storage emulator to enable uploading user's avatars.

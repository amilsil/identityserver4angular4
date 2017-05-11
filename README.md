# Running the setup

Startup both the server and the client as follows.

### Server 

In command line, navigate to src/QuickStartIdentityServer folder. 
Execute,

```text
dotnet restore
dotnet run
```

### Client

In command line, navigate to src/Angular2OidcClient folder. 
Execute,

```text
npm i
ng serve
```

# Testing

Load http://localhost:4200/ and click on *Start signin main window*. This should initiate the sign-in flow. 

Open the Browser Development Tools and watch the logs.
# Example deploying ARM template

- `deploy.ps1` - Powershell example
- `deploy.sh` - Bash example
- `deploymenthelper.cs` - C# example

Example deploying a template:

```powershell
# All on one line, though
.\Deploy.ps1 
    -subscriptionId '<your sub id>' 
    -resourceGroupName 'example-rg' 
    -resourceGroupLocation 'Central US' 
    -deploymentName 'azureciexample' 
    -parametersFilePath 'parameters-example1.json'
```

## Notes

- `template.json` - see for web app, app insights, ping test, and MySQL DB
- `parameters-example1.json` - all you need to do is generate a JSON file like this to pass into deployment function
- Make sure web app name is unique across Azure
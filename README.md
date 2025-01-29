# blazor-test

# Download the SDK
https://download.visualstudio.microsoft.com/download/pr/96489126-b9ba-414a-a2d0-d8c5b61a22be/fe047e117e9cc43738ba2222f4769da2/dotnet-sdk-9.0.102-osx-arm64.pkg
## Check if it's installed
dotnet --version

# Install C# extension on VS Code
Search for C# Dev Kit

# Create the app
CMD+SHIFT+P     type:  .net
## Select .NET: New Project...
### Select Blazor Web App
### Choose the folder and name the project as "BlazorApp" (idk if it's mandatory to have the name like this...)

## Open the SOLUTION EXPLORER tab in VSCode (could be already opened)
Program.cs: is the entry point for the app that starts the server and where you configure the app services and middleware.
Inside the Components directory:
    App.razor is the root component for the app:
    Routes.razor configures the Blazor router.
    The Pages directory contains some example web pages for the app.
BlazorApp.csproj: defines the app project and its dependencies and can be viewed by double-clicking the BlazorApp project node in the Solution Explorer.
The Properties/launchSettings.json: defines different profile settings for the local development environment. A port number is automatically assigned at project creation and saved on this file.

## Move to inside the app folder through the terminal

### Open the RUN AND DEBUG tab in VSCode
Click on the "Run and Debug" button
Type "C#" select for More options... and select the "C#: BlazorApp [Default Configuration]"
### OR just run "dotnet watch" in the terminal

# Working ✅
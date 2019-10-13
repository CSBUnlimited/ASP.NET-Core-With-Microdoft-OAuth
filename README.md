# ASP.NET-Core-With-Microsoft-OAuth
ASP.NET Core 2.2 MVC Application using Microsoft OAuth

<ul>
<li>First you need to install dotnet core SDK. You can download by using this link
https://dotnet.microsoft.com/download/dotnet-core/2.2

<br/></li>
<li>Run the following commands to securely store ClientId and ClientSecret using Secret Manager.

> dotnet user-secrets set Authentication:Microsoft:ClientId **ClientId** <br/>
> dotnet user-secrets set Authentication:Microsoft:ClientSecret **ClientSecret** <br/>

ClientId and ClientSecret is provided in the document that provided in submission. Please replace those values before run the application 
<br/></li>
<br/>
<li> After the installation to run the application, open a powershell and enter the command<br/>
> dotnet run
  
</li>
</ul>

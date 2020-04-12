# Simple Background Jobs With Hangfire and ASP.NET Core
Hangfire is an open source library to schedule and execute background jobs in .NET applications.<br/> 
We can create a simple background process inside the same application pool or thread with no need of creating another application.<br/> 
Hangfire creates background jobs in persistence storage. In this sample I am using MS SQL Server.

Note: first step after installing the Nuget packages is run the database script. We should have something like this:
![DB](https://github.com/sarahonorato/aspnet-core-hangfire/blob/master/ExpectedResultImages/HangFire.SQLServer.PNG)

## Nuget Packages
[Hangfire.NetCore](https://www.nuget.org/packages/Hangfire.NetCore/)<br/>
[HangFire.SqlServer](https://www.nuget.org/packages/HangFire.SqlServer/)

## Hangfire Dashboard
![Dashboard](https://github.com/sarahonorato/aspnet-core-hangfire/blob/master/ExpectedResultImages/Hangfire.Dashboard.PNG)
![Dashboard](https://github.com/sarahonorato/aspnet-core-hangfire/blob/master/ExpectedResultImages/Hangfire.Dashboard2.PNG)

## References
[Hangfire](https://www.hangfire.io/)
[Tutorial](https://docs.hangfire.io/en/latest/getting-started/aspnet-core-applications.html)

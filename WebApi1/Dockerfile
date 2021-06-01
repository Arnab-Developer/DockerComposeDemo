FROM mcr.microsoft.com/dotnet/aspnet:5.0
COPY WebApi1/bin/publish/ ./app
WORKDIR /app
ENTRYPOINT ["dotnet", "WebApi1.dll"]
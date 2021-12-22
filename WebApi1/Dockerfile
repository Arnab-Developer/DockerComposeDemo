FROM mcr.microsoft.com/dotnet/aspnet:6.0
COPY WebApi1/bin/publish/ ./app
WORKDIR /app
ENTRYPOINT ["dotnet", "WebApi1.dll"]
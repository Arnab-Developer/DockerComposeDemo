FROM mcr.microsoft.com/dotnet/aspnet:5.0
COPY WebApi2/bin/publish/ ./app
WORKDIR /app
ENTRYPOINT ["dotnet", "WebApi2.dll"]
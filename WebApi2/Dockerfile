FROM mcr.microsoft.com/dotnet/aspnet:6.0
COPY WebApi2/bin/publish/ ./app
WORKDIR /app
ENTRYPOINT ["dotnet", "WebApi2.dll"]
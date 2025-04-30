# Dockerfile
FROM mcr.microsoft.com/dotnet/aspnet:6.0 AS runtime
WORKDIR /app
COPY ./publish .
ENTRYPOINT ["dotnet", "UserOwnsData.dll"]

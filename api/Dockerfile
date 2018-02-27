FROM microsoft/aspnetcore:2.0

WORKDIR /app
COPY bin/Release/PublishOutput .

ENTRYPOINT ["dotnet", "api.dll"]

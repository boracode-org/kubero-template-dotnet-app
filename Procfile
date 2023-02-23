web: dotnet bin/Release/net7.0/DotNet.Docker.dll
worker: dotnet run --project Worker
build: dotnet restore && dotnet publish -c Release -o /app
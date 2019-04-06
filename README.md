#SonarQubeNetCore

#Setup SonarQube#
1. $ docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube

#Using VS Code, Coverlet, xUnit, plus these Visual Studio Code extensions

1. Coverage Gutters - Reads in the lcov.info file (name matters) and highlights lines with color
2. .NET Core Test Explorer - Discovers tests and gives you a nice explorer.
3. Coverlet - The start of .NET Core Code Coverage

# Installation
1. $ dotnet tool install --global coverlet.console
2. $ dotnet tool install --global dotnet-sonarscanner --version 4.3.1

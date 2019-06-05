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

#Story
https://medium.com/@boriphuth/%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99-code-%E0%B9%83%E0%B8%AB%E0%B9%89%E0%B8%A1%E0%B8%B5%E0%B8%84%E0%B8%B8%E0%B8%93%E0%B8%A0%E0%B8%B2%E0%B8%9E-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-sonarqube-%E0%B9%81%E0%B8%A5%E0%B8%B0-net-core-1556988ae269

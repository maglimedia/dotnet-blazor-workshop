dotnet run --project src/BlazingPizza.Server/BlazingPizza.Server.csproj
cp ./localhost.pfx /mnt/c/Users/damac/.aspnet/https
dotnet dev-certs https --clean --import /mnt/c/Users/damac/.azure/https.pfxopenssl verify --password 30314812


cp /mnt/c/Users/damac/.azure/https.pfx localhost.pfx 
FROM microsoft/dotnet:2.2-sdk AS build-env
WORKDIR /app

# Cópia do código e Build da aplicacao
COPY . ./
RUN dotnet publish -c Release -o out

# Build da imagem
FROM microsoft/dotnet:2.2-aspnetcore-runtime
WORKDIR /app
COPY --from=build-env /app/out .
ENTRYPOINT ["dotnet", "webapi-core.dll"]

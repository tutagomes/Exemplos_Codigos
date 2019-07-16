# Azure Pipelines

Primeiro, vamos executar um laboratório deveras interessante, através do link:

https://labondemand.com/AuthenticatedLaunch/54150?providerId=4



E depois, vamos ver como montar diferentes builds para diferentes tipos de código. Neste repositório, temos três pastas principais, cada uma representando um tipo de linguagem diferente.

- Laravel-example: Interpretada (PHP)
- quasar-exemplo: Transpilada (JS)
- webapi-core: Compilada (C#)

O objetivo é criar pipelines de build que geram um artefato .zip contendo então o resultado. Na parte do JS, devemos distribuir para todas as plataformas desktop, incluindo Linux, Mac e Windows (Utilizando o Electron).

Depois das builds, devemos baixar e verificar a correta execução das aplicações.





1. CD:

https://labondemand.com/AuthenticatedLaunch/38301?providerId=4



2. Package Management:

https://labondemand.com/AuthenticatedLaunch/38313?providerId=4



3. Aumentando Produtividade:

https://labondemand.com/AuthenticatedLaunch/38310?providerId=4



4. Na segunda parte, iremos então montar uma imagem Docker contendo cada aplicação auto-hospedada. Vamos também criar uma conta no Docker Hub para publicar nossas imagens.
   1. Criando uma conta no Docker Hub - https://hub.docker.com/signup
   2. Montando uma pipeline Docker - https://docs.microsoft.com/en-us/azure/devops/pipelines/languages/docker?view=azure-devops





Dê uma olhada em como criar uma pipeline de build para .NET Core utilizando YAML através do link:

https://docs.microsoft.com/pt-br/azure/devops/pipelines/languages/dotnet-core?view=azure-devops



Você também pode criar Pipelines através da interface de linha de comando da Azure: https://docs.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline-cli?view=azure-devops



Se você quiser conferir mais laboratórios como os acima, dê uma olhada no link https://www.microsoft.com/handsonlabs/selfpacedlabs


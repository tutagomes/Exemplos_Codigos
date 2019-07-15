# Azure Pipelines

Primeiro, vamos executar um laboratório deveras interessante, através do link:

https://labondemand.com/AuthenticatedLaunch/54150?providerId=4



E depois, vamos ver como montar diferentes builds para diferentes tipos de código. Neste repositório, temos três pastas principais, cada uma representando um tipo de linguagem diferente.

- Laravel-example: Interpretada (PHP)
- quasar-exemplo: Transpilada (JS)
- webapi-core: Compilada (C#)

O objetivo é criar pipelines de build que geram um artefato .zip contendo então o resultado. Na parte do JS, devemos distribuir para todas as plataformas desktop, incluindo Linux, Mac e Windows (Utilizando o Electron).

Depois das builds, devemos baixar e verificar a correta execução das aplicações.



Na segunda parte, iremos então montar uma imagem Docker contendo cada aplicação auto-hospedada. Vamos também criar uma conta no Docker Hub para publicar nossas imagens.

https://hub.docker.com/signup


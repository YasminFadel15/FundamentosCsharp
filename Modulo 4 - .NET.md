# .NET CLI
  - CLI: sigla para Command Line Interface.
  - Interface de linha de comando.
  - Comandos adicionados ao terminal, definido pelo comando 'dotnet'.
 
# Tipos de projetos
  - Class Library: o resultado final é uma DLL, não possui interface.
  - Console Apllication: o resultado final é uma aplicação que roda no terminal, pode receber inputs.
  - Projeto Web: ASP.NET Web, ASP.NET MVC, ASP.NET WebAPI.
  - Projeto de Testes: Microsoft Tests.

# Criar novo projeto
  - dotnet new console => Novo Console Application;
  - dotnet new classlib => Nova Class Library;
  - dotnet new web => Novo projeto ASP.NET Core;
  - dotnet new mvc => Novo projeto ASP.NET Core;
  - dotnet new webapi => Novo projeto ASP.NET Core;
  - dotnet new mstest => Novo projeto Microsoft Test.
  - Para especificar uma pasta usar '-o'.

# Fluxo de execução
  - dotnet restore: restaura todos os pacotes que a aplicação precisa para ser executada;
  - dotnet build: compila a aplicação;
  - dotnet clean: limpa as compilações anteriores;
  - dotnet run: compila e executa a aplicação.

# Variáveis de ambiente
  - Dizer ao .NET qual ambiente:
    * dotnet run --enviroment=$SEU_AMBIENTE
    * dotnet run --enviroment=development
    * dotnet run --enviroment=production
  - O run não executa depuração (debug).

# WEB API com .NET e SQL Server | CRUD + Repository Pattern 💻

Este projeto consiste em uma API desenvolvida com **.NET** e **SQL Server**, implementando operações CRUD (Create, Read, Update, Delete) e utilizando o padrão de repositório (Repository Pattern) para uma estrutura de código mais organizada e escalável.

## Requisitos

- **SQL Server**: Certifique-se de que o SQL Server esteja instalado e configurado corretamente em sua máquina ou servidor.
- **.NET 5.0 ou superior**: A aplicação foi desenvolvida utilizando a plataforma .NET 5.0 ou superior.

## Instruções para Rodar o Projeto

1. **Clone o repositório** para sua máquina local:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. **Configuração do Banco de Dados**:
    - Certifique-se de que o SQL Server esteja rodando e acessível.
    - Crie um banco de dados no SQL Server ou edite a string de conexão no arquivo `appsettings.json` para apontar para o seu banco de dados.
    
    Exemplo de configuração no `appsettings.json`:
    ```json
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Database=SeuBancoDeDados;Trusted_Connection=True;"
    }
    ```

3. **Executando as migrações do banco de dados**:
    Execute o comando para aplicar as migrações e criar o banco de dados:
    No terminal do Nuget.
    ```bash
    update-database
    ```

    Isso irá gerar o banco de dados e suas tabelas automaticamente.

## Funcionalidades

- **CRUD Completo**: O projeto implementa as operações básicas de CRUD para um recurso de exemplo.
- **Repository Pattern**: A lógica de acesso ao banco de dados é organizada através do padrão Repository, garantindo que o código seja modular e fácil de manter.

## Como Usar a API

Após a configuração do banco de dados e a execução do comando para atualizar as migrações, você pode rodar a aplicação localmente com o seguinte comando:

```bash
dotnet run




# Challenge

## Integrantes:
- **João Vitor Valaitis Paulo** - RM: 553972
- **Carlos Eduardo Ariza** - RM: 553461
- **Fernando Shinji Tanigushi** - RM: 553587

## Descrição do Projeto
O **Challenge** é um aplicativo desenvolvido para facilitar a logística empresarial e a checagem de sinistros na área de odontologia. O sistema permite que os funcionários da empresa e dentistas verifiquem a veracidade das informações, especialmente em notas fiscais, e identifiquem sinistros durante visitas de rotina. A aplicação tem o objetivo de melhorar a confiabilidade e transparência nos processos de gestão de sinistros e visitas.

## Objetivo do Projeto
O principal objetivo do projeto é fornecer uma plataforma eficiente para a verificação de informações e gestão de sinistros, otimizando a operação e garantindo que os dados sejam tratados de forma transparente e eficaz.

## Escopo
O projeto inclui as seguintes funcionalidades principais:
- **Registro e autenticação de usuários**: Funcionários da empresa e dentistas podem se cadastrar e autenticar no sistema.
- **Registro e gerenciamento de visitas**: As visitas realizadas durante a rotina de checagem de sinistros podem ser registradas e gerenciadas.
- **Registro e gerenciamento de sinistros**: Sinistros podem ser registrados, e suas informações podem ser consultadas e atualizadas.
- **Verificação de veracidade de informações**: O sistema permite verificar se as informações em notas fiscais são corretas.
- **API RESTful**: A aplicação fornece uma API para interação com o aplicativo frontend.

## Requisitos Funcionais
- O sistema deve permitir o **cadastro de usuários**, com dois tipos de perfis: funcionário da empresa e dentista.
- O sistema deve possibilitar o **registro de visitas e sinistros**, com funcionalidades de consulta e edição.
- A aplicação deve fornecer uma **API RESTful** que permita acessar e interagir com as funcionalidades do sistema.

## Requisitos Não Funcionais
- **Segurança**: O sistema deve garantir a proteção das informações sensíveis dos usuários.
- **Escalabilidade**: O sistema deve ser capaz de lidar com um número crescente de usuários e dados.
- **Performance**: O sistema deve garantir tempos de resposta rápidos para todas as requisições.

## Tecnologias Utilizadas
- **.NET 8**: Plataforma para desenvolvimento da aplicação.
- **Entity Framework Core**: Framework ORM utilizado para o acesso ao banco de dados.
- **SQL Server**: Banco de dados utilizado para armazenar as informações do sistema.
- **ASP.NET Core**: Framework utilizado para construir a API RESTful do projeto.

## Como Rodar o Projeto

### 1. Instalar as Dependências
Certifique-se de ter o **.NET 8** e o **SQL Server** instalados.

No diretório do projeto, execute o comando:

```bash
dotnet restore
### 2. Configuração do Banco de Dados
Configure o banco de dados no arquivo appsettings.json para se conectar ao seu servidor de banco de dados SQL Server.

Para aplicar as migrações e atualizar o banco de dados, use o comando:

bash
Copiar código
dotnet ef database update
### 3. Rodar o Projeto
Após configurar o banco e restaurar as dependências, execute o comando:

bash
Copiar código
dotnet run
### 4. Acessar a API
A API estará disponível na URL:

http://localhost:5000 ou
https://localhost:5001 (dependendo da configuração)
### 5. Swagger
A documentação da API pode ser acessada através do Swagger:

http://localhost:5000/swagger ou
https://localhost:5001/swagger


# Controle de Gastos — Flask + SQL Server

Aplicação web desenvolvida em Python com Flask e SQL Server para o gerenciamento de gastos pessoais. O sistema permite cadastrar, consultar, editar e excluir registros, além de apresentar um resumo estatístico dos valores cadastrados.

## Funcionalidades

* **Cadastro de gastos:** registro de gastos com descrição, valor e data.
* **Listagem de gastos:** visualização dos registros cadastrados.
* **Edição de gastos:** atualização das informações dos registros.
* **Exclusão de gastos:** remoção de registros cadastrados.
* **Resumo financeiro:** apresentação dos valores máximo, mínimo, total e média dos gastos.
* **Persistência de dados:** armazenamento das informações em banco de dados SQL Server.

## Tecnologias utilizadas

* Python
* Flask
* SQL Server
* PyODBC
* HTML
* CSS
* Git e GitHub

## Conceitos praticados

* Desenvolvimento de aplicações web com Flask.
* Criação e organização de rotas.
* Operações CRUD (Create, Read, Update e Delete).
* Integração entre Python e SQL Server.
* Execução de consultas SQL para obtenção de dados.
* Cálculo de estatísticas para apresentação de um resumo financeiro.

## Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/EduardoCosta71/Controle-de-Gastos-Versao-Banco-de-Dados.git
```

### 2. Entre na pasta do projeto

```bash
cd Controle-de-Gastos-Versao-Banco-de-Dados
```

### 3. Crie um ambiente virtual

```bash
python -m venv venv
```

Ative o ambiente virtual no Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

### 5. Configure o banco de dados

É necessário ter o SQL Server instalado e configurar a conexão com o banco de dados conforme as configurações utilizadas no projeto.

Certifique-se de que o banco de dados e a tabela necessária estejam criados antes de executar a aplicação.

### 6. Execute a aplicação

```bash
python app.py
```

Depois, acesse o endereço local exibido no terminal pelo Flask, geralmente:

```text
http://127.0.0.1:5000
```

## Objetivo do projeto

Este projeto foi desenvolvido para praticar o desenvolvimento Backend com Python e Flask, a integração com bancos de dados relacionais e a implementação de operações CRUD em uma aplicação web.

## Autor

**Eduardo Costa Borges**

* GitHub: [EduardoCosta71](https://github.com/EduardoCosta71)

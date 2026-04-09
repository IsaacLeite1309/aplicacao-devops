# Aplicação DevOps - Avaliação N1

Esta aplicação foi desenvolvida como parte da avaliação N1 da disciplina de **Ferramentas de Implantação Contínua**. O projeto consiste em um servidor web simples construído para demonstrar o domínio do fluxo de trabalho DevOps, focado em versionamento semântico, colaboração via branches e automação de processos.

## Tecnologias Utilizadas

* **Node.js**: Ambiente de execução Javascript server-side.
* **Express.js**: Framework minimalista para gerenciamento de rotas e servidores HTTP.
* **Git**: Sistema de controle de versão distribuído.
* **GitHub**: Plataforma de hospedagem e colaboração de código.

## Como Executar o Projeto

Siga os passos abaixo para rodar a aplicação localmente:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO-AQUI/aplicacao-devops.git](https://github.com/SEU-USUARIO-AQUI/aplicacao-devops.git)

2. **Instale as dependências:**
    Este comando irá baixar os pacotes necessários (como o Express.js) listados no arquivo package.json.
    npm install
3. **Inicie o servidor:**
    Execute o ponto de entrada da aplicação localizado na pasta src.
    node src/app.js

## Endpoints da API

A aplicação expõe os seguintes pontos de acesso para interação e verificação:

* **`GET /`**: Rota principal que serve o arquivo estático `index.html`. Esta é a porta de entrada visual da aplicação.
* **`GET /integrantes`**: Rota técnica que retorna um objeto JSON contendo a lista oficial de todos os integrantes do grupo.

**Exemplo de resposta da rota `/integrantes`:**
```json
{
  "integrantes": [
    {"nome": "Isaac da Silva Leite"},
    {"nome": "Klaudenilson Sampaio ALves"},
    {"nome": "Higor Pessoa da Silva"}
  ]
}

## Equipe de Desenvolvimento

Esta equipe trabalhou de forma colaborativa e paralela, seguindo os princípios de transparência e integração contínua do DevOps.

| Nome Completo | Função Principal no Projeto |
| **Isaac da Silva Leite** | Gestão de Repo e Documentação |
| **Klaudenilson Sampaio ALves** | Setup e Lógica de Dados |
| **NHigor Pessoa da Silva** | Frontend e Rotas de View |



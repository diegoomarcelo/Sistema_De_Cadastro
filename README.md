# Sistema de Cadastro de Alunos 🎓

Este é um projeto de sistema de cadastro desenvolvido para aplicar conceitos de **Programação Orientada a Objetos (POO)** e arquitetura de software.

## Tecnologias Utilizadas
* **Linguagem:** Java 
* **Arquitetura:** MVC (Model, View, Controller)
* **Banco de Dados:** MySQL
* **Padrão de Projeto:** DAO (Data Access Object) para persistência de dados.
* **Ferramenta:** NetBeans.

## Estrutura do Projeto (MVC)
O sistema foi organizado seguindo o padrão **CMV (Controle, Modelo e Visão)** para garantir a separação de responsabilidades:
* **Modelo (Model):** Representa as entidades e a lógica de dados. **DAO (Data Access Object)**, responsável por toda a integração e comandos SQL com o banco de dados MySQL.
* **Visão (View):** Interface de interação com o usuário.
* **Controle (Controller):** Gerencia o fluxo de dados entre a Visão e o Modelo, aplicando as regras de negócio.

## Funcionalidades
O sistema permite a gestão dos alunos através das seguintes operações:
- [x] **Cadastrar Aluno:** Adiciona novos alunos ao banco de dados.
- [x] **Excluir Aluno:** Remove registros existentes.
- [x] **Pesquisar por Matrícula:** Localização rápida de dados através do número identificador.
- [x] **Alterar Dados:** Atualização de informações de alunos já cadastrados.
- [x] **Sair:** Encerramento seguro da aplicação.

## 🏁 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/diegoomarcelo/Sistema_De_Cadastro.git
2. Conecte ao banco de dados MySQL com o DAO.
3. Execute a através da sua IDE de preferência.
   

# API de CRUD de Médicos - Curso Spring Boot 3 Alura 
Api de um CRUD de médicos desenvolvida em Java usando o framework Spring Boot 3 no curso "Spring Boot 3: desenvolva uma API Rest em Java"

Foram utilizadas dependecias como lombok, Spring MVC, Spring Data JPA, Spring Validation, Flyway para as migrações do banco de dados e MySql como banco de dados

Durante o curso, foi utilizado um TRELLO para simular o andamento das Sprints. cada cartão especificava como cada tarefa deveria ser feita

## Cadastro de Médicos

O sistema deve possuir uma funcionalidade de cadastro de médicos, na qual as seguintes informações deverão ser preenchidas:

* **Nome**

* **E-mail**

* **Telefone**

* **CRM**

* **Especialidade** (Ortopedia, Cardiologia, Ginecologia ou Dermatologia)

* **Endereço completo** (logradouro, número, complemento, bairro, cidade, UF e CEP)

Todas as informações são de preenchimento **obrigatório**, exceto o número e o complemento do endereço.

## Listagem de Médicos

O sistema deve possuir uma funcionalidade de listagem de médicos, na qual as seguintes informações, de cada um dos médicos cadastrados, deverão ser exibidas:

* **Nome**

* **E-mail**

* **CRM**

* **Especialidade**

A listagem deve ser **ordenada** pelo **nome** do médico, de maneira **crescente**, bem como ser **paginada**, trazendo **10 registros** por página.

## Atualização de Médicos 

O sistema deve possuir uma funcionalidade de atualização de dados cadastrais de médicos, na qual as seguintes informações poderão ser atualizadas:

* **Nome**
* **Telefone**
* **Endereço**

As seguintes regras de negócio devem ser validadas pelo sistema:

* **Não** permitir a alteração do **e-mail** do médico;
* **Não** permitir a alteração do **CRM** do médico;
* **Não** permitir a alteração da **Especialidade** do médico.

## Exclusão do Médico
O sistema deve possuir uma funcionalidade que permita a exclusão de médicos cadastrados.

As seguintes regras de negócio devem ser validadas pelo sistema:

* A exclusão **não** deve **apagar** os dados do médico, mas torná-lo como **"inativo"** no sistema.












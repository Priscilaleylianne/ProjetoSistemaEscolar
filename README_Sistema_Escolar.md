# 🏫 Sistema Escolar em C++ -- Programação Orientada a Objetos

Este repositório contém o desenvolvimento completo de um **Sistema
Escolar** implementado em **C++**, utilizando os princípios fundamentais
da **Programação Orientada a Objetos (POO)**.

## 📁 Estrutura do Projeto

    /src
       ├── Pessoa.hpp / Pessoa.cpp
       ├── Aluno.hpp / Aluno.cpp
       ├── Professor.hpp / Professor.cpp
       ├── Setor.hpp / Setor.cpp
       ├── Secretaria.hpp / Secretaria.cpp
       ├── Turma.hpp / Turma.cpp
       └── Sistema.hpp / Sistema.cpp
    /main.cpp
    /uml
    /docs

## 🎯 Objetivo do Sistema

-   Cadastro de alunos e professores\
-   Gerenciamento de setores e secretaria\
-   Organização de turmas\
-   Aplicação de encapsulamento, herança e polimorfismo\
-   Testes de integração e refatoração\
-   Programação em pares

## 📋 Levantamento de Requisitos

### Requisitos Funcionais

-   Cadastrar alunos\
-   Cadastrar professores\
-   Criar e gerenciar turmas\
-   Gerenciar setores\
-   Listar dados\
-   Aplicar polimorfismo

### Requisitos Não Funcionais

-   Código modular\
-   Uso obrigatório de POO\
-   UML estruturado\
-   Manutenção simples

## 🧩 Modelagem UML

A modelagem inclui as classes: Pessoa, Aluno, Professor, Turma, Setor,
Secretaria e Sistema.

## ⚙️ Componentes do Sistema

### Classe Pessoa

Classe base com atributos essenciais e métodos virtuais.

### Classe Aluno

Possui matrícula e vínculo com turma.

### Classe Professor

Possui disciplina e vínculo com setor.

### Classe Turma

Gerencia alunos.

### Classe Secretaria

Gerencia setores e professores.

### Classe Sistema

Centraliza todas as operações.

## 🛡️ Aplicação dos Conceitos de POO

### Encapsulamento

-   Atributos privados
-   Getters e setters

### Herança

-   Pessoa → Aluno\
-   Pessoa → Professor

### Polimorfismo

-   Métodos sobrescritos\
-   Ponteiros para superclasse

## 🤝 Trabalho Colaborativo

-   Programação em pares\
-   Revisão cruzada de código\
-   Refatorações contínuas

## 🧪 Testes de Integração

-   Integração entre classes\
-   Validação de polimorfismo\
-   Testes de listas e composição

## 🔧 Refatoração

-   Padronização\
-   Separação em .hpp e .cpp\
-   Redução de duplicidade

## 📝 Relato Reflexivo

Relatos individuais sobre o aprendizado e prática de POO.

## 📦 Como Executar

    g++ main.cpp src/*.cpp -o sistema_escolar
    ./sistema_escolar

## 📚 Referências

-   Deitel --- C++ Como Programar\
-   Stroustrup --- The C++ Programming Language\
-   Documentação oficial C++

## 📎 Anexos

-   Código-fonte\
-   UML\
-   Prints\
-   Relatos

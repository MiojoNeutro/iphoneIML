```mermaid
classDiagram
    class iPhone {
    }

    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet


# DIO - Desafio iPhone UML

📱 Projeto desenvolvido como parte de um desafio da Digital Innovation One (DIO).

## 🎯 Objetivo
O desafio consiste em criar um **diagrama UML** representando um iPhone e, em seguida, implementar as classes em Java com seus respectivos métodos, aplicando os conceitos de Programação Orientada a Objetos (POO).

## 🛠️ Estrutura
- **Diagrama UML** → Representação das funcionalidades do iPhone.
- **Classes implementadas** → Métodos de ligar, atender chamadas, reproduzir músicas e navegar na internet.

## 🚀 Tecnologias
- Java
- UML (Unified Modeling Language)

## 📚 O que foi praticado
- Modelagem de classes e interfaces
- Aplicação dos pilares da POO
- Implementação de métodos simulando funcionalidades do iPhone

---

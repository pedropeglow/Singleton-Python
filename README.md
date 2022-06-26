# Singleton Python

Atividade de Design Pattern

### 🎥 Link Video

Link: https://drive.google.com/drive/folders/1NGvflyIaOQhxTYlYG_knRIhAdvyS0VQM?usp=sharing

### 📄 Material Explicativo

Motivo:

O singleton permite garantir que uma classe tenha apenas uma instância, garantindo um acesso global a essa instância.

Problema sanados:
1) Controlar o acesso a algum recurso compartilhado, como um acesso a uma base de dados ou parametrização de configuração de uma aplicação.

2) O padrão Singleton permite o acesso global para a instância criada.

Exemplo de aplicabilidade no código:
No código criado, uma classe possui uma mensagem com erro de português. Com o singleton, ainda que os erros sejam corrigidos em outra instância, a instância global também acaba sendo corrigida.
É claro que se o objetivo é manter a instancia global imutável, podemos proteger a classe.

Pros:
Certeza de que só tem uma única classe.
Ponto de acesso global à classe.
Objeto inicializado somente quando for chamado pela primeira vez.

Contras:
Viola o princípio da responsabilidade única (SOLID).
Difícil realizar testes unitários em decorrência da violação da responsabilidade única.
O padrão Singleton pode mascarar um design ruim.
O padrão requer tratamento especial em um ambiente multithreaded para que múltiplas threads não possam criar um objeto singleton várias vezes.

### Features

- [x] Design Pattern Singleton

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python]

### Autor

---

<sub><b>Pedro Peglow</b></sub>🚀
<sub><b>Wagner Souza de Paula</b></sub>🚀

Feito por Pedro Peglow e Wagner Souza de Paula 👋🏽 Entre em contato!

<a href="https://github.com/wagnersouzadepaula"><img src="https://github.com/wagnersouzadepaula.png" width="45" height="45"></a> &nbsp;
<a href="https://github.com/pedropeglow"><img src="https://github.com/pedropeglow.png" width="45" height="45"></a> &nbsp;



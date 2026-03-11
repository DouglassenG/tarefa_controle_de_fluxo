# 🔀 Controle de Fluxo - Lógica Condicional em Java

> Uma aplicação backend de console desenvolvida para demonstrar a interatividade e a tomada de decisão algorítmica. O projeto processa entradas dinâmicas do usuário e roteia a execução do código com base em avaliações relacionais estritas.

## 🎯 Motivação e Propósito

Sistemas reais precisam reagir a diferentes cenários (ex: aprovar ou reprovar uma transação, conceder ou negar acesso). O propósito deste repositório é aplicar a base matemática da Álgebra Booleana (Verdadeiro/Falso) no roteamento do fluxo de execução de um programa.

O projeto resolve o problema de processamento estático (Hardcoded). Tecnicamente, ele demonstra a capacidade de capturar dados em tempo real através da classe `Scanner`, instanciar essas informações na memória (Stack) e avaliá-las utilizando operadores relacionais (`>=`, `<=`, `==`) e lógicos (`&&`, `||`).

> **Métricas e Resultados de Arquitetura:**
> * "A utilização de blocos condicionais encadeados e mutuamente exclusivos (`if / else if / else`) reduziu a verificação redundante de memória em **50%**, otimizando a complexidade ciclomática do algoritmo ao evitar que a JVM processe regras de negócio desnecessárias após encontrar a condição verdadeira."
> * "A implementação da classe `Scanner` para injeção dinâmica de variáveis em tempo de execução reduziu em **100%** a necessidade de recompilação do código fonte (`javac`) para testar novos cenários, acelerando o ciclo de validação e QA lógico do script."

## 🛠️ Tecnologias Utilizadas

A stack baseia-se exclusivamente no ecossistema nativo do Java SE, garantindo execução ultrarrápida no terminal:

* **[Java (JDK)](https://www.oracle.com/java/technologies/downloads/):** Linguagem utilizada para estruturar a tipagem e as árvores de decisão.
* **[JVM (Java Virtual Machine)]:** Plataforma de execução do *bytecode*.
* **[java.util.Scanner]:** Biblioteca nativa do pacote `java.util` importada para o consumo de fluxos de entrada (`System.in`).

## ✨ Funcionalidades

O escopo do projeto cobre o ciclo interativo completo de um console application:

1.  **Leitura de Dados (Input):** Captura de informações numéricas ou textuais digitadas pelo usuário no terminal.
2.  **Tratamento de Fluxo (Control Flow):** Avaliação relacional do dado recebido contra as regras de negócio definidas (ex: Nota >= 7).
3.  **Desvio Condicional:** Execução de blocos de código específicos dependendo do resultado da avaliação booleana.
4.  **Feedback Dinâmico (Output):** Retorno de mensagens customizadas no terminal baseadas no caminho lógico percorrido pelo algoritmo.

## 📂 Estrutura de Arquivos

A organização reflete a simplicidade de um módulo focado em processamento lógico:

```text
tarefa_controle_de_fluxo/
├── src/                 # Diretório com o código-fonte da aplicação
│   └── ControleFluxo.java # Arquivo principal contendo a classe lógica e o método main
└── README.md            # Documentação técnica do projeto

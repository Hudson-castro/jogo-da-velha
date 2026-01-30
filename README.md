# Jogo da Velha (Tic-Tac-Toe)

Este repositório contém uma implementação simples do **Jogo da Velha** em Java, desenvolvida com fins educacionais para praticar lógica de programação, orientação a objetos e uso básico do Git/GitHub.

---

## 📌 Sobre o projeto

O **Jogo da Velha** é um jogo clássico para dois jogadores, onde cada jogador alterna turnos marcando posições em uma matriz 3x3. O objetivo é alinhar **três símbolos iguais** (na horizontal, vertical ou diagonal) antes do adversário.

Neste projeto:

* Um jogador utiliza **X**
* O outro utiliza **O**
* O jogo informa vitória, derrota ou empate

---

## 🧠 Conceitos trabalhados

* Estruturas de decisão (`if`, `else`)
* Laços de repetição
* Matrizes (arrays bidimensionais)
* Métodos e organização de código
* Lógica de verificação de vitória
* Execução de programas Java pelo terminal

---

## 📂 Estrutura do projeto

```
📁 jogodavelha
 ├── JogoDaVelha.java   # Classe principal com a lógica do jogo
 ├── TesteJogo.java    # Classe de teste / execução do jogo
 └── README.md         # Documentação do projeto
```

---

## ▶️ Como executar o projeto

### Pré-requisitos

* Java JDK instalado (versão 8 ou superior)
* Terminal ou prompt de comando

### Passo a passo

1. Clone o repositório:

   ```bash
   git clone git@github.com:Hudson-castro/jogo-da-velha.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd jogo-da-velha
   ```

3. Compile os arquivos Java:

   ```bash
   javac JogoDaVelha.java TesteJogo.java
   ```

4. Execute o jogo:

   ```bash
   java TesteJogo
   ```

---

## 🎮 Como jogar

* O tabuleiro é exibido no terminal
* Cada jogador escolhe uma posição informando linha e coluna
* As jogadas se alternam automaticamente
* O jogo termina quando:

  * Um jogador vence
  * O tabuleiro é completamente preenchido (empate)

---

## 🚀 Possíveis melhorias futuras

* Interface gráfica (Swing ou JavaFX)
* Validação mais robusta de entradas
* Modo jogador vs computador
* Placar de vitórias
* Testes automatizados

---

## 👤 Autor

Desenvolvido por **Hudson Castro** 👨‍💻
Projeto com fins educacionais.

---

## 📜 Licença

Este projeto é livre para uso educacional e pessoal.

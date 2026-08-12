# Chess System - Java

[![Java Version](https://img.shields.io/badge/Java-25-orange)](https://www.oracle.com/java/)

Este projeto é um sistema de jogo de xadrez completo desenvolvido em **Java 25**, executado inteiramente via terminal. O objetivo principal foi aplicar conceitos avançados de **Programação Orientada a Objetos (POO)** e lógica de jogos.

---

## 🎮 O Jogo

O sistema permite uma partida completa entre dois jogadores, incluindo:
- Movimentação de todas as peças (Peão, Torre, Cavalo, Bispo, Rei e Rainha).
- Validação de movimentos possíveis.
- Sistema de captura de peças.
- Lógica de **Xeque** e **Xeque-mate**.
- Jogadas especiais: **Roque**, **En Passant** e **Promoção de Peão**.

## 🛠️ Conceitos Aplicados

Este projeto demonstra o domínio de fundamentos críticos de engenharia de software:
* **Encapsulamento**: Proteção de estados internos do tabuleiro e peças.
* **Herança e Polimorfismo**: Estrutura base de peças com comportamentos específicos.
* **Tratamento de Exceções**: Captura de movimentos inválidos e erros de sistema.
* **Matrizes**: Manipulação de posições em um grid 8x8.
* **Enumerações**: Definição de cores e status do jogo.

## 🏗️ Arquitetura do Sistema

O projeto é dividido em camadas de responsabilidade:
1.  **Board Layer (Camada de Tabuleiro)**: Gerencia as peças e posições.
2.  **Chess Layer (Camada de Xadrez)**: Contém as regras específicas do jogo de xadrez.
3.  **Application (Camada de Aplicação)**: Interface de usuário via terminal (UI) e entrada de dados.

---

## 🔧 Como Executar

### Pré-requisitos
- JDK 25 instalado.

### Passo a passo
1. Clone o repositório:
   ```bash
   git clone https://github.com/lucasgcunha/chess-sistem-java.git
2. Acesse a pasta do projeto:
   ```bash
   cd chess-sistem-java
3. Compile o projeto:
   ```bash
   javac application/Program.java
4. Execute o jogo:
   ```bash
   java application/Program

## 📸 Preview do Sistema

Ao executar o programa, o tabuleiro será exibido no terminal desta forma:

```text
  8 R N B Q K B N R
  7 P P P P P P P P
  6 . . . . . . . .
  5 . . . . . . . .
  4 . . . . . . . .
  3 . . . . . . . .
  2 P P P P P P P P
  1 R N B Q K B N R
    a b c d e f g h

Turn: 1
Waiting player: WHITE

Source: a2
Target: a4

  8 r n b q k b n r
  7 p p p p p p p p
  6 . . . . . . . .
  5 . . . . . . . .
  4 P . . . . . . .
  3 . . . . . . . .
  2 . P P P P P P P
  1 R N B Q K B N R
    a b c d e f g h
```
> **Nota:** Este programa utiliza cores ANSI. Logo, no terminal, as peças pretas estão coloridas de amarelo para diferenciá-las das brancas.

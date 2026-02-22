# 🧙 JOENEY RPG em Grafos — A Jornada do Cristal

Jogo de aventura em terminal desenvolvido em **C**, aplicando **Estrutura de Dados do tipo Grafo** para representar o mapa do mundo.
Cada local é um vértice e cada caminho é uma aresta (direcionada e/ou ponderada).

---

## 📌 Sobre o Projeto

O jogador inicia na **Vila Inicial** e recebe a missão de recuperar o **Cristal Roxinho**.
Durante a jornada, percorre diferentes cenários, toma decisões e enfrenta eventos que impactam suas vidas.

Conceitos aplicados:

* Grafos direcionados e não direcionados
* Grafos ponderados (custo em vidas)
* Lista de adjacência
* Alocação dinâmica de memória
* Modularização em C (`.h` e `.c`)

---

## 🎮 Modos de Jogo

| Modo     | Descrição                |
| -------- | ------------------------ |
| Fácil    | Mais vidas e menor custo |
| Normal   | Desafio equilibrado      |
| Difícil  | Grafo não direcionado    |
| Pacífico | Sem custo de vidas       |

---

## ❤️ Sistema de Vidas

* Eventos podem aumentar ou reduzir vidas.
* Caminhos podem ter custo.
* 0 vidas → derrota.
* Chegar ao Cristal Roxinho → vitória.

---

## 📂 Estrutura do Projeto

```bash
main.c      # Controle principal
Grafo.c     # Implementação do grafo e lógica do jogo
Grafo.h     # Definições e protótipos
```

---

## ⚙️ Compilação

### Linux / Mac

```bash
gcc main.c Grafo.c -o jogo
./jogo
```

### Windows (MinGW)

```bash
gcc main.c Grafo.c -o jogo.exe
jogo.exe
```

---

## 🎯 Objetivo

Projeto acadêmico desenvolvido na matéria de Estrutura de Dados 2, para aplicação prática da utilização de **Grafos**, integrando lógica, estruturas dinâmicas e interatividade em terminal.


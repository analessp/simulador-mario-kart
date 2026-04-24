# 🏎️ Simulador Mario Kart

Um simulador de corridas inspirado no universo do Mario Kart, desenvolvido com JavaScript e executado via Node.js no terminal.

---

## 📖 Sobre o Projeto

Este projeto simula uma corrida entre personagens clássicos, utilizando regras simples baseadas em atributos e sorte (dados).  
O objetivo é praticar lógica de programação de forma divertida e interativa.

---

## 🚀 Tecnologias Utilizadas

- JavaScript (ES6+)
- Node.js

---

## 🎮 Como Funciona

A corrida acontece em rodadas. Em cada rodada:

1. Um tipo de pista é sorteado:
   - 🛣️ Reta
   - 🌀 Curva
   - ⚔️ Confronto

2. Cada jogador rola um dado (1 a 6)

3. O valor do dado é somado a um atributo específico:

| Tipo de Pista | Atributo Utilizado |
|--------------|-------------------|
| Reta         | Velocidade        |
| Curva        | Manobrabilidade   |
| Confronto    | Poder             |

4. Quem tiver o maior valor ganha a rodada e soma pontos

---

## 🧩 Estrutura do Projeto


📁 src/
└── index.js


---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/analessp/simulador-mario-kart.git
2. Acesse a pasta do projeto
cd simulador-mario-kart
3. Execute o projeto
node src/index.js
📊 Exemplo de Execução
🏁 Corrida iniciada!

Rodada 1: RETA
Mario 🎲 4 + Velocidade (3) = 7
Luigi 🎲 5 + Velocidade (2) = 7

Empate!

Rodada 2: CURVA
...

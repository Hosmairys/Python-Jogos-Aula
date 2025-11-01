# 🕹️ Jogos em Python com Pygame

Este repositório contém dois jogos desenvolvidos em **Python 3.12** utilizando a biblioteca **Pygame**.  
São exemplos didáticos e divertidos de como criar jogos 2D simples, interativos e com pontuação dinâmica.

---

## 🎯 Jogo 1 — Acerte o Alvo!

### 📘 Descrição
O jogo **"Acerte o Alvo!"** é um mini game de reflexos onde o objetivo é clicar o mais rápido possível sobre o quadrado vermelho que muda de posição aleatoriamente a cada acerto.  
Cada clique correto soma **+1 ponto**. O jogo termina quando o jogador fecha a janela.

### 🧠 Conceitos abordados
- Manipulação de eventos de **mouse** (`MOUSEBUTTONDOWN`)
- Controle de FPS com `pygame.time.Clock()`
- Renderização de texto e formas geométricas (`pygame.draw.rect`)
- Sistema simples de pontuação

### ▶️ Como jogar
1. Execute o script:
   ```bash
   python acerte_o_alvo.py

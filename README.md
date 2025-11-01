```markdown
# 🕹️ Projetos em Python com Pygame  
### Repositório: [Hosmairys/Python-Jogos-Aula](https://github.com/Hosmairys/Python-Jogos-Aula)

Este repositório contém **dois jogos desenvolvidos em Python 3.12** utilizando a biblioteca **Pygame**.  
Eles fazem parte de um projeto educacional voltado para o aprendizado de lógica de programação e desenvolvimento de jogos 2D.

---

## 📂 Estrutura do Projeto

```

📁 Python-Jogos-Aula/
│
├── acerte_o_alvo.py       # Jogo 1: Acerte o Alvo
├── pong.py                # Jogo 2: Pong Clássico
└── README.md              # Documentação do projeto

````

---

## 🎯 Jogo 1 — Acerte o Alvo!

### 📘 Descrição
Um mini game de reflexos em que o objetivo é **clicar no quadrado vermelho** o mais rápido possível.  
Cada clique correto move o alvo para uma posição aleatória e soma **+1 ponto**.

### 🧠 Conceitos aplicados
- Eventos de mouse (`MOUSEBUTTONDOWN`)
- Detecção de colisão com `Rect.collidepoint()`
- Controle de FPS (`Clock.tick(60)`)
- Renderização de texto e cores no Pygame

### ▶️ Como jogar
1. Execute o jogo com o comando:
   ```bash
   python acerte_o_alvo.py
````

2. Clique sobre o **quadrado vermelho** sempre que ele aparecer.
3. Veja sua pontuação aumentar no canto superior esquerdo.

### 🖼️ Imagem do jogo

<img width="806" height="635" alt="Pong" src="https://github.com/user-attachments/assets/1704915a-558d-48f3-9d13-903f937e19ec" />

<img width="802" height="627" alt="AcerteAlvo" src="https://github.com/user-attachments/assets/649bb6c3-ff69-4ed8-824c-9ccbbd2e56c2" />


---

## 🏓 Jogo 2 — Pong (Clássico)

### 📘 Descrição

Uma recriação do clássico **Pong**, com dois jogadores e sistema de pontuação.
Cada jogador controla uma raquete e deve evitar que a bola ultrapasse sua linha.

### 🎮 Controles

| Jogador        | Subir | Descer |
| -------------- | ----- | ------ |
| 🧍‍♂️ Esquerda | W     | S      |
| 🧍‍♂️ Direita  | ↑     | ↓      |

O jogo termina quando um dos jogadores alcança **5 pontos**.

### 🧠 Conceitos aplicados

* Classes e objetos (`Raquete`, `Bola`)
* Movimento contínuo com `pygame.key.get_pressed()`
* Colisões com `colliderect()`
* Exibição de pontuação e mensagem de vitória

### ▶️ Como jogar

1. Execute o jogo com:

   ```bash
   python pong.py
   ```
2. Use as teclas para mover as raquetes.
3. Evite que a bola ultrapasse sua borda.
4. O primeiro a marcar 5 pontos vence!

### 🖼️ Imagem do jogo

> *(Adicione aqui uma captura de tela do jogo — ex: `img/pong.png`)*
> ![Pong Screenshot](img/pong.png)

---

## ⚙️ Pré-requisitos

Antes de rodar os jogos, instale o **Python 3.12** (ou superior) e a biblioteca **Pygame**:

```bash
pip install pygame
```

Verifique se a instalação foi concluída corretamente:

```bash
python -m pygame.examples.aliens
```

Se o jogo de exemplo abrir, o Pygame está funcionando!

---

## 🚀 Execução Rápida

```bash
# Clone o repositório
git clone https://github.com/Hosmairys/Python-Jogos-Aula.git

# Acesse o diretório
cd Python-Jogos-Aula

# Execute o jogo desejado
python acerte_o_alvo.py
# ou
python pong.py
```

---

## 💡 Possíveis melhorias futuras

### Para *Acerte o Alvo*:

* Adicionar cronômetro e ranking de tempo.
* Níveis de dificuldade com tamanhos variados de alvo.
* Sons e animações de acerto.

### Para *Pong*:

* Adicionar modo solo com IA.
* Implementar menu inicial e reinício.
* Efeitos sonoros e pontuação persistente.

---

## 👩‍💻 Autora

Desenvolvido por **Hosmairys Yuriannys Holder Rodriguez**
💻 Estudante e desenvolvedora entusiasta de Python e Pygame.
📍 São Paulo, Brasil

📫 [GitHub](https://github.com/Hosmairys)

---

## 🪪 Licença

Este projeto está licenciado sob a **MIT License**.
Você pode usar, modificar e distribuir o código livremente, desde que mantenha os devidos créditos à autora.

---

> ⭐ **Dê uma estrela no repositório** se este projeto te ajudou a aprender Pygame!

```

---

Deseja que eu adicione **um cabeçalho visual com banner estilo GitHub (com fundo escuro e texto “Python Games Project” em pixel art)** para deixar o README mais atrativo? Posso gerar o banner automaticamente.
```

# Jo-Ken-Po Game  

Um mini-jogo inspirado no clássico **Jo-Ken-Po (Pedra, Papel e Tesoura)**.  
O jogador escolhe cartas para duelar contra o computador, cada uma com atributos e interações únicas.  
Reprodução da trilha de javascript do bootcamp Front-End Santander 2025.

---

Link Deploy: https://trilha-javascript-jokenpo.vercel.app/

## Funcionalidades  

- 🎮 Sistema de **cartas clicáveis** com efeitos visuais.  
- 🖼️ Exibição de detalhes da carta selecionada (imagem, nome e atributo).  
- ⚔️ Duelos automáticos entre **jogador x computador**.  
- 📊 **Placar em tempo real** (Win/Lose).  
- 🔊 **Efeitos sonoros** e música de fundo.  
- 🎥 Vídeo de fundo temático para imersão.  
- 🔄 Botão para **resetar o duelo** e iniciar novamente.  

---

## 📂 Estrutura do Projeto  

```bash
    yu-gi-oh-jokenpo
    ┣ 📂 src
    ┃ ┣ 📂 assets
    ┃ ┃ ┣ 📂 audios # sons dos duelos
    ┃ ┃ ┣ 📂 cursor # cursores personalizados
    ┃ ┃ ┣ 📂 icons # imagens das cartas e ícones
    ┃ ┃ ┗ 📂 video # vídeo de fundo
    ┃ ┣ 📂 scripts
    ┃ ┃ ┗ engine.js # lógica principal do jogo
    ┃ ┣ 📂 styles
    ┃ ┃ ┣ buttons.css
    ┃ ┃ ┣ containers_and_frames.css
    ┃ ┃ ┣ main.css
    ┃ ┃ ┗ reset.css
    ┣ index.html
    ┗ README.md
```

## Como Jogar  

1. Abra o projeto em um navegador (`index.html`).  
2. Escolha uma carta clicando sobre ela.  
3. O computador selecionará uma carta aleatória.  
4. O resultado do duelo será exibido (**WIN / LOSE / DRAW**).  
5. Clique em **GANHOU (Next Duel)** para reiniciar a rodada.  

---

##  Regras do Jogo  

O sistema segue a lógica do **Pedra, Papel e Tesoura**, adaptado para cartas:  

- **Blue Eyes White Dragon (Paper)** 🐉 
  - ✅ Vence de: **Dark Magician**  
  - ❌ Perde para: **Exodia**  

- **Dark Magician (Rock)** 🧙‍♂️  
  - ✅ Vence de: **Exodia**  
  - ❌ Perde para: **Blue Eyes White Dragon**  

- **Exodia (Scissors)** 🗿  
  - ✅ Vence de: **Blue Eyes White Dragon**  
  - ❌ Perde para: **Dark Magician**  

---

##  Tecnologias Utilizadas  

- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**  
- 🎶 Áudio e 🎥 vídeo integrados para imersão  


(./src/assets/jokenpo-preview.PNG)



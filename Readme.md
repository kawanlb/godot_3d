# Projeto Final - Game Engine (2025)

## 🎮 Nome do Jogo
**Caipora**  

---

## 👥 Integrantes do Grupo

- Arthur Nogueira Silveira de Lima Santos - 01610363
- Eduardo Marinho Xavier Junior - 01625908
- Kawan Leandro Batista de Lima Santos - 01616317
- Leticia Pinheiro Paoleschi - 01651848-
- Marcus Trummer - 01650257
- Matheus Emanuel dos Santos Aguiar Paiva - 01615805

---

## 🕹️ Controles do Jogo

| Ação                      | Tecla         |
|---------------------------|---------------|
| Mover personagem          | W, A, S, D     |
| Mover câmera              | Mouse          |
| Interagir com objetos     | (CHEGAR PERTO) |
| Abrir inventário          | ESC         |
---

## 🧠 Conceitos Aplicados

- Ambiente 3D completo com colisões, iluminação e texturas.
- Personagem 3D controlável com física e sistema de animação.
- Sistema de câmera em terceira pessoa com seguimento suave.
- Objetos interativos no cenário com detecção de colisão.
- Sistema de inventário e coleta de itens.
- Inimigos com IA básica (patrulha e ataque).
- Estrutura modular com separação de lógica, UI e apresentação.
- Scripts organizados e comentados com uso de sinais.

---

## 🗺️ Estrutura do Projeto
Scenes/
├── Levels/
│ └── Level 1.tscn → Cena principal do ambiente
├── Player/
│ └── Player.tscn → Cena do personagem jogável
│ └── GUI/ → Interface do usuário
├── Monsters/ → Cenas de inimigos
└── Objects/ → Objetos interativos (Torch, Fireball etc)

Scripts/
├── Player/ → Lógica do jogador e estados
├── Monsters/AI */ → IA dos inimigos
├── Objects/ → Interações com itens e objetos
└── Global/Utils.gd → Scripts auxiliares e globais

---

## 🛠️ Recursos Utilizados

| Tipo        | Fonte                                       |
|-------------|---------------------------------------------|
| Assets 3D   |https://kaylousberg.itch.io/kaykit-adventurers 
  --          |https://kaylousberg.itch.io/kaykit-dungeon-remastered
  --          |https://kaylousberg.itch.io/kaykit-skeletons
            

---

## ▶️ Instruções de Execução
1. Abra o Godot Engine (versão 4.x ou a que você estiver usando).
2. Clique em **Importar Projeto** e selecione a pasta raiz do projeto.
3. Execute a cena principal (`Level 1.tscn`).
4. Use os controles listados acima para jogar.
   
---

## 💬 Créditos

Este projeto foi desenvolvido para a disciplina **Game Engine (2025)** do **Centro Universitário Maurício de Nassau**.

**Professor:** Dr. Diogo Francisco Borba Rodrigues

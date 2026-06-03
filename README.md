# 🐍 Snake Game

Uma versão moderna e responsiva do clássico **Snake Game**, desenvolvida utilizando apenas tecnologias nativas da web (**HTML, CSS e JavaScript puro**).

O projeto foi construído em um único arquivo HTML, sem dependências externas, oferecendo uma implementação simples, leve e totalmente compatível com navegadores modernos.

---

## 🎮 Demonstração

O jogador controla uma cobrinha que deve consumir alimentos espalhados aleatoriamente pelo cenário para aumentar sua pontuação e crescer de tamanho.

O desafio é sobreviver o maior tempo possível sem colidir com:

* As bordas do mapa
* O próprio corpo da cobrinha

---

## ✨ Funcionalidades

### Gameplay

* ✅ Controle pelas teclas de seta do teclado
* ✅ Controles touch para dispositivos móveis
* ✅ Geração aleatória de comida
* ✅ Crescimento da cobrinha ao consumir alimentos
* ✅ Sistema de pontuação em tempo real
* ✅ Sistema de recorde (High Score)
* ✅ Persistência do recorde via LocalStorage
* ✅ Detecção de colisão com paredes
* ✅ Detecção de colisão com o próprio corpo
* ✅ Tela de Game Over
* ✅ Reinício rápido da partida

### Interface

* ✅ Design moderno
* ✅ Layout responsivo
* ✅ Compatível com desktop e mobile
* ✅ Animações suaves
* ✅ HUD com pontuação e recorde
* ✅ Instruções visíveis ao usuário
* ✅ Visual inspirado em jogos modernos

### Desenvolvimento

* ✅ HTML semântico
* ✅ CSS organizado e escalável
* ✅ JavaScript modularizado
* ✅ Código comentado
* ✅ Fácil manutenção
* ✅ Nenhuma dependência externa

---

# 🚀 Tecnologias Utilizadas

| Tecnologia        | Finalidade                   |
| ----------------- | ---------------------------- |
| HTML5             | Estrutura da aplicação       |
| CSS3              | Estilização e responsividade |
| JavaScript (ES6+) | Lógica do jogo               |

---

# 📂 Estrutura do Projeto

```text
snake-game/
│
├── snake.html
└── README.md
```

Todo o projeto está contido em um único arquivo:

```text
snake.html
```

Dentro dele encontram-se:

```html
<!-- HTML -->
<!-- CSS -->
<!-- JavaScript -->
```

organizados em seções bem definidas.

---

# ▶️ Como Executar

## Método 1 (mais simples)

1. Faça o download do arquivo:

```text
snake.html
```

2. Abra o arquivo em qualquer navegador moderno:

* Google Chrome
* Microsoft Edge
* Firefox
* Opera
* Brave
* Safari

Pronto. O jogo estará funcionando imediatamente.

---

## Método 2 (GitHub Pages)

Caso publique o projeto no GitHub:

1. Faça push do repositório.
2. Acesse:

```text
Settings → Pages
```

3. Configure:

```text
Source → Deploy from Branch
```

4. Selecione:

```text
main / root
```

5. Salve.

O GitHub Pages disponibilizará uma URL pública para jogar online.

---

# 🎯 Controles

## Desktop

| Tecla | Ação                |
| ----- | ------------------- |
| ⬆️    | Mover para cima     |
| ⬇️    | Mover para baixo    |
| ⬅️    | Mover para esquerda |
| ➡️    | Mover para direita  |

---

## Mobile

Botões direcionais exibidos na interface:

```text
⬆️
⬅️ ⬇️ ➡️
```

---

# 🏆 Sistema de Pontuação

Cada alimento consumido adiciona pontos ao placar.

```text
+10 pontos por alimento
```

O melhor resultado é armazenado automaticamente no navegador através do:

```javascript
localStorage
```

Assim, o recorde permanece salvo mesmo após fechar a página.

---

# 📱 Responsividade

O jogo foi desenvolvido para funcionar adequadamente em diferentes tamanhos de tela:

* Desktop
* Notebook
* Tablet
* Smartphone

O canvas é redimensionado automaticamente para oferecer a melhor experiência possível.

---

# 🧠 Conceitos Aplicados

Durante o desenvolvimento foram utilizados conceitos importantes de programação de jogos:

* Loop principal de atualização
* Renderização em Canvas 2D
* Controle de estado do jogo
* Detecção de colisão
* Gerenciamento de eventos do teclado
* Gerenciamento de eventos touch
* Persistência local
* Responsividade
* Organização modular do código

---

# 📸 Recursos Visuais

O projeto inclui:

* Fundo moderno com gradientes
* Painéis com efeito glassmorphism
* Sombras suaves
* Elementos arredondados
* Comida com efeito glow
* Cabeça da cobrinha diferenciada visualmente
* Interface inspirada em aplicações modernas

---

# 🔧 Possíveis Melhorias Futuras

Algumas ideias para evolução do projeto:

* 🔊 Efeitos sonoros
* 🎵 Música de fundo
* ⚡ Sistema de níveis
* 🏅 Conquistas
* 🌎 Ranking online
* 🎨 Temas alternativos
* 👥 Modo multiplayer local
* ⏸ Sistema de pausa
* 🕹 Controle por swipe em dispositivos móveis

---

# 🤝 Contribuição

Contribuições são bem-vindas.

Caso encontre bugs ou tenha sugestões:

1. Faça um Fork
2. Crie uma Branch

```bash
git checkout -b feature/minha-feature
```

3. Commit suas alterações

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

4. Push para a branch

```bash
git push origin feature/minha-feature
```

5. Abra um Pull Request

---

# 📄 Licença

Este projeto está disponível sob a licença MIT.

Sinta-se livre para utilizar, modificar e distribuir.

---

# 👨‍💻 Autor

Desenvolvido com HTML, CSS e JavaScript puro como demonstração de desenvolvimento front-end e criação de jogos para navegador.

---

## ⭐ Se este projeto foi útil para você

Considere deixar uma estrela no repositório:

```text
⭐ Star this repository
```

Isso ajuda o projeto a alcançar mais pessoas.

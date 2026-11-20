# ♠️♥️ Sueca Portuguesa ♦️♣️

Uma versão web interativa e responsiva do clássico jogo de cartas português **Sueca**, desenvolvida num único ficheiro HTML para jogar a solo contra 3 bots com inteligência artificial.

---

## ✨ Funcionalidades

- **Regras Oficiais da Sueca:** Baralho de 40 cartas (sem 8, 9 e 10), sentido anti-horário, obrigatoriedade de assistir ao naipe puxado e corte com trunfo.
- **Bots com Raciocínio Tático:** Os bots memorizam cartas já jogadas na ronda (identificando cartas mestras como o 7 após sair o Ás), evitam abrir o 7 desprotegido, dão carga (pontos) ao parceiro quando a vaza está segura e cortam estrategicamente.
- **Interface Clara e Responsiva:**
  - Carta de trunfo sempre visível no topo da mesa.
  - Cartas jogadas posicionadas junto a cada jogador para leitura imediata da vaza.
  - Destaque visual nas cartas jogáveis apenas durante o teu turno.
  - Compatível com computador e telemóvel.
- **Contagem Completa de Partida:** Acompanhamento dos pontos da ronda (até 120) e dos **Jogos Ganhos** (vitória simples, dobrada e Bandeira).
- **Pronto para GitHub Pages:** Botão integrado para exportar o jogo limpo como `index.html`.

---

## 🃏 Regras e Pontuação

O jogo disputa-se entre duas equipas de dois jogadores frente a frente (**Tu + Parceiro [Norte]** contra **Este + Oeste**).

### Hierarquia e Valor das Cartas

| Carta | Nome / Observação | Pontos | Força |
| :---: | :--- | :---: | :---: |
| **A** | Ás | **11** | 10 (Mais forte) |
| **7** | Manilha / Bisca | **10** | 9 |
| **K** | Rei | **4** | 8 |
| **J** | Valete | **3** | 7 |
| **Q** | Dama | **2** | 6 |
| **6 a 2** | Cartas brancas / Lixo | **0** | 5 a 1 (Mais fraca) |

*Total de pontos por ronda: **120 pontos**.*

### Atribuição de Jogos

- **61 a 90 pontos:** +1 Jogo (Vitória simples)
- **91 a 119 pontos:** +2 Jogos (Vitória dobrada)
- **120 pontos:** +4 Jogos (**Bandeira**)
- **60 - 60 pontos:** Empate (0 jogos atribuídos)

---

## 🚀 Como Jogar Online (GitHub Pages)

1. Descarrega o ficheiro do jogo através do botão **Exportar / GitHub** dentro da aplicação (será guardado como `index.html`).
2. Cria um repositório público no teu [GitHub](https://github.com) (por exemplo, `sueca-portuguesa`).
3. Carrega os ficheiros `index.html` e `README.md` para a raiz do repositório.
4. No repositório, acede a **Settings** $\rightarrow$ **Pages**.
5. Em **Build and deployment / Branch**, seleciona `main` e a pasta `/ (root)`, e clica em **Save**.
6. Aguarda cerca de 1 minuto e acede ao link público gerado pelo GitHub Pages.

### Executar Localmente

Não requer instalação de dependências nem servidor. Basta abrir o ficheiro `index.html` (ou `sueca.html`) diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3** & [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- **JavaScript (ES6+)** puro (sem dependências externas)

---

## 📄 Licença

Este projeto está sob a licença MIT. Sente-te à vontade para jogar, modificar e partilhar.
# 🏎️ PITWALL - F1 Dashboard (GP de São Paulo)

Bem-vindo ao **PITWALL**, um dashboard temático inspirado na Formula 1 e na lendária Copa Pistão! Este projeto web exibe informações sobre o GP de São Paulo em Interlagos, apresentando cartões de pilotos interativos, tabela de classificação atualizada e um formulário para reserva de ingressos.

Projeto desenvolvido como parte da formação do **SENAI** focado no aprendizado prático de **HTML5** e **CSS3**.

---

##  Sumário

- [Visão Geral](#-visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura de Arquivos](#-estrutura-de-arquivos)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Autores e Créditos](#-autores-e-créditos)

---

##  Visão Geral

O projeto consiste em uma página *Landing Page / Dashboard* para um evento de corrida no Autódromo de Interlagos. Ele conta com uma estética *dark mode* inspirada nas transmissões e identidades visuais da F1 moderna, utilizando detalhes contrastantes em vermelho (`#E10600`) e cores personalizadas para cada equipe (Ferrari, McLaren, Mercedes, Audi).

---

##  Funcionalidades

- **Menu de Navegação Fixo (`Topbar`):** Navegação rápida com links diretos para as seções do site e atalho para compra de ingressos.
- **Hero Section:** Banner principal em formato diagonal com métricas do circuito (71 voltas, 4.309 km, 15 curvas) e chamada para ação (*CTA*).
- **Grid de Pilotos:** Exibição em cartões com design dinâmico por equipe (borda e fundo correspondentes às marcas da Ferrari, McLaren, Mercedes e Audi).
- **Tabela de Classificação do Campeonato:** Tabela estilizada com visualização de pontos, vitórias, saldo de diferença e campo preparativo para busca interativa.
- **Formulário de Ingressos:** Formulário para reserva com seleção de setores, quantidade de ingressos, envio de foto para o telão e mensagens de apoio aos pilotos.

---

##  Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página web.
- **CSS3:** 
  - Layout Responsivo (Flexbox e CSS Grid)
  - Efeitos modernos de design (`clip-path` para cortes diagonais)
  - Variáveis de cores e identidades visuais por equipe
  - Efeitos interativos em botões e links (`hover` e `active`)

---

##  Estrutura de Arquivos

```text
├── assets/
│   ├── Gemini_Generated_Image_kgyqwhkgyqwhkgyq.jpg  # Imagem de fundo do banner
│   ├── i.png                                          # Avatar Oscar Piastri
│   ├── i (1).png                                      # Avatar Charles Leclerc
│   ├── george-russell-f1-driver-profile-picture.webp  # Avatar George Russell
│   └── i (2).png                                      # Avatar Gabriel Bortoleto
├── copa_pistao.html                                   # Estrutura HTML principal
├── copa_pistao.css                                    # Estilização CSS do projeto
└── README.md                                          # Documentação do projeto
```

---

## Como Executar o Projeto

1. **Clonar ou Baixar o Repositório:**
   Baixe os arquivos para o seu computador.

2. **Organizar a Pasta:**
   Certifique-se de manter o arquivo `copa_pistao.html` e `copa_pistao.css` no mesmo diretório, junto com a pasta `assets/` contendo as imagens necessárias.

3. **Abrir no Navegador:**
   Dê um duplo clique no arquivo `copa_pistao.html` ou abra-o utilizando a extensão *Live Server* no VS Code.

---

##  Autores Erick Cardoso/rykedev

- **Desenvolvimento:** Erick
- **Instituição:** SENAI
- **Nota:** Os dados de pontos, números e estatísticas da tabela têm caráter meramente ilustrativo para fins didáticos de estudo de layout HTML/CSS.

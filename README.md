# 🌊 Festival Maré Cheia

**Trio:** Victor Moises, Julio Cesar e Miguel Alves
**Site publicado:** *https://site-com-ia-rust.vercel.app/*

Festival de MPB realizado no cais de Paraty (RJ), de **13 a 15 de novembro de 2026**, com apresentações distribuídas em três palcos: **Cais, Casarão e Mangue**.

---

## 🎵 Sobre o projeto

O **Festival Maré Cheia** é um festival fictício de MPB criado com uma proposta visual inspirada em festivais pequenos, cidades históricas e na atmosfera do litoral de Paraty.

A identidade do site busca transmitir uma sensação **marítima, artesanal e noturna**, utilizando cores sólidas, tipografia marcante e elementos inspirados no mar.

### Público-alvo

O site foi pensado para pessoas de **25 a 60 anos** que:

* Gostam de MPB e de ouvir álbuns completos;
* Viajam para festivais de pequeno porte;
* Gostam de cidades históricas;
* Preferem shows mais tranquilos e próximos do público;
* Valorizam boa qualidade de som e organização;
* Procuram um line-up selecionado e uma experiência mais intimista.

### Clima visual

**Marítimo · Artesanal · Noturno**

---

## 🎨 Identidade visual

### Paleta de cores

| Cor                  | Hexadecimal | Utilização                                               |
| -------------------- | ----------- | -------------------------------------------------------- |
| **Verde-maré**       | `#0E2B2B`   | Fundo de todas as páginas                                |
| **Areia**            | `#EFE3C2`   | Textos, ingressos e mapa                                 |
| **Coral**            | `#D9452F`   | Botões, letreiro rolante e nomes dos artistas principais |
| **Amarelo-maracujá** | `#F2B134`   | Sol do hero, links, números e página atual do menu       |
| **Azulejo**          | `#2E6FA7`   | Ondas animadas, mar do mapa e marcadores                 |

### Tipografia

* **Títulos:** Bricolage Grotesque
* **Textos:** Karla

A **Bricolage Grotesque** foi escolhida para os títulos por ter uma aparência marcante, semelhante à comunicação visual de cartazes de rua.

A **Karla** foi utilizada nos textos por ser uma fonte simples e confortável para leitura.

---

## 💡 Referências visuais

O projeto teve como referência alguns sites de festivais:

1. **Coala Festival** — inspiração para a apresentação do line-up em grade, com retrato, nome, dia e horário.
2. **Primavera Sound** — inspiração para a hierarquia do cartaz, destacando os principais artistas.
3. **MOFO** — inspiração para o uso de cores sólidas no fundo e para uma comunicação mais descontraída.

---

## 🤖 Prompts que mais contribuíram para o desenvolvimento

### 1. Estrutura inicial do site

> "Estou fazendo o site de um festival de MPB chamado Maré Cheia, no cais de Paraty, para um público adulto que gosta de festival pequeno. Fundo #0E2B2B, texto #EFE3C2, coral #D9452F, amarelo #F2B134 e azul #2E6FA7. Título em Bricolage Grotesque e texto em Karla. Escreva o arquivo index.html completo, com o header tendo o nome do festival à esquerda e o menu à direita usando display flex. O CSS vai no style.css. Sem gradiente, sem emoji e sem card arredondado com sombra."

### 2. Animação das ondas

> "No lugar de uma faixa colorida no topo, coloque um SVG de duas ondas no fim do hero e anime as ondas com translateX em loop infinito de 14s e 22s, uma em cada direção. Escreva só o trecho de CSS da classe .mare."

### 3. Design dos ingressos

> "Os ingressos estão parecendo card genérico. Deixe cada um com cara de canhoto de entrada: fundo areia, preço grande em coral, lista separada por linha tracejada e um recorte redondo nas duas laterais usando mask com radial-gradient. Escreva o style.css inteiro."

### 4. Animações e acessibilidade

> "Troque a animação de entrada que está em todas as seções por uma coisa só: o hero entra em sequência (linha de data, título, chamada, botões, com delay crescente) e o resto da página aparece com IntersectionObserver quando entra na tela. Adicione também um bloco prefers-reduced-motion desligando tudo."

---

## 📁 Estrutura do projeto

```text
festival-mare-cheia/
│
├── index.html
│   └── Página inicial: nome, datas, local, chamada e 3 atrações
│
├── lineup.html
│   └── 10 artistas com retrato, dia, horário e palco
│       + filtro por dia
│
├── ingressos.html
│   └── 4 tipos de ingresso com preço e informações
│
├── informacoes.html
│   └── Endereço, como chegar, mapa e regras
│
├── faq.html
│   └── 8 perguntas frequentes e formulário de contato
│
├── style.css
│   └── Folha de estilos compartilhada pelas 5 páginas
│
└── img/
    ├── retratos dos artistas
    ├── logo/favicon
    ├── antes.png
    ├── depois.png
    └── mapa.svg
```

---

## ✨ Funcionalidades e extras

O projeto conta com:

* Design responsivo para dispositivos móveis;
* Menu de navegação presente nas páginas;
* Página atual destacada em amarelo;
* Identidade visual própria com paleta e tipografia definidas;
* Logo próprio, utilizado também como favicon;
* Line-up com 10 artistas;
* Filtro do line-up por dia;
* Ingressos com visual inspirado em canhotos de entrada;
* FAQ com perguntas em formato de sanfona;
* Página de informações com endereço, como chegar e mapa;
* Formulário de contato;
* Ondas animadas em SVG;
* Animações de entrada utilizando IntersectionObserver;
* Suporte a `prefers-reduced-motion`, reduzindo ou desativando animações para usuários que preferem menos movimento.

---

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript
* SVG
* Google Fonts
* IntersectionObserver API
* CSS `mask` e `radial-gradient`
* Vercel

---

## 🚀 Publicação

O site foi desenvolvido como um projeto estático e publicado utilizando a **Vercel**.

**Site:** *[colar aqui o link da Vercel]*

---

## 👥 Integrantes

* Victor Moises
* Julio Cesar
* Miguel Alves

---

## 📅 Informações do festival

| Informação   | Detalhes                    |
| ------------ | --------------------------- |
| **Festival** | Maré Cheia                  |
| **Gênero**   | MPB                         |
| **Local**    | Cais de Paraty — Paraty, RJ |
| **Data**     | 13 a 15 de novembro de 2026 |
| **Palcos**   | Cais, Casarão e Mangue      |

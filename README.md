# Guia de Uso do Portfólio em Grupo

Este README descreve o funcionamento do Portfólio Web criado utilizando **HTML5**, **CSS3** e **Bootstrap 5**, baseado exatamente no código fornecido.

---

## Estrutura Geral do Projeto

O site é composto por três áreas principais:

* **Cabeçalho (Header)**
* **Conteúdo Principal (Main)**
* **Rodapé (Footer)**

Todo o layout utiliza classes do Bootstrap, complementado por um arquivo CSS personalizado (`style.css`).

---

## Cabeçalho e Navegação

O topo do site possui uma **navbar responsiva**, configurada da seguinte forma:

### Links de Navegação

* **Home** (com estado ativo destacado)
* **Adryan** – Link para o LinkedIn
* **Murilo** – Link para o LinkedIn
* **Erlon** – Link para o LinkedIn

### Menu Responsivo

Em telas menores, o menu se transforma em um ** botão hambúrguer**, utilizando o Collapse do Bootstrap.

---

## Carrossel (Hero)

A seção inicial do conteúdo principal contém um **carrossel Bootstrap** com três imagens:

* Cada imagem possui **títulos e subtítulos centralizados**, estilizados no CSS.
* Possui **setas de navegação** e **indicadores** para trocar as imagens.

As frases são estilizadas por meio da classe personalizada `.frase-carrosel`.

---

## Cards de Apresentação

Logo abaixo do carrossel há três grupos de cards:

### Cards Individuais (Apresentação)

Cada membro possui um card com:

* Nome
* Função (Front-End / Back-End)
* Instituição (Uninassau)
* Lista de conhecimentos técnicos
* Botão **"Ver Perfil"** levando ao GitHub

Os cards incluem efeitos de hover definidos no CSS (`transform` e `box-shadow`).

---

### Cards "Sobre Mim"

Cards com textos de apresentação pessoal.
Estilização especial aplicada através de `.about-me-text`.

---

### Cards de Redes Sociais

Incluem cartões com logos de:

* **LinkedIn** (um para cada membro)
* **GitHub** (um para cada membro)

Cada card contém botão que direciona para o perfil correspondente.

As imagens são estilizadas com o CSS personalizado `.linkedin-img` e `.github-img`.

---

## Rodapé

O rodapé apresenta:

### Tabela de Contatos

Tabela com Nome, Telefone e Email dos três membros.
Possui bordas arredondadas personalizadas (`tr-1`, `tr-2`, `tr-3`, `tr-4`).

### Direitos Autorais

Mensagem padrão:

> “© 2025 Portfólio em grupo. Todos os direitos reservados.”

---

## Como Executar e Editar

O projeto é **100% estático**, sem dependências externas além do Bootstrap CDN.

### Executar

1. Baixe ou clone os arquivos.
2. Abra o arquivo **index.html** diretamente no navegador.

### Editar

* **index.html** → Estrutura, textos, links e carrossel
* **style.css** → Estilização, cores, animações, responsividade personalizada

---

## Tecnologias Utilizadas

* HTML5
* CSS3 (personalizado)
* Bootstrap 5 (via CDN)
* Google Fonts (Open Sans, Alan Sans, Lato)

---

Se quiser que eu gere uma versão **mais completa**, com tabelas, imagens, instruções avançadas, ou até uma versão em inglês, é só pedir!

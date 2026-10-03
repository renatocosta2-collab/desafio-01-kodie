# Desafio 01 — KODIE Academy

## Portfólio Ash Ketchum — Treinador Pokémon

Landing Page desenvolvida como parte do **Desafio 01 da KODIE Academy**, com o objetivo de colocar em prática conceitos de HTML5, CSS3, responsividade, acessibilidade, Git, GitHub e publicação com GitHub Pages.

O projeto apresenta um portfólio fictício de **Ash Ketchum como treinador Pokémon**, mostrando sua jornada, experiência e alguns de seus Pokémon parceiros.

---

## Objetivo do projeto

Criar uma Landing Page simples, organizada, acessível e responsiva utilizando apenas:

- HTML5
- CSS3
- Git
- GitHub
- GitHub Pages

O projeto foi desenvolvido sem JavaScript, sem CSS inline e sem utilização da tag `<style>` no HTML.

---

## Estrutura da página

A Landing Page contém:

- Header com nome e menu de navegação;
- Hero com apresentação e chamada para ação;
- Seção Sobre;
- Seção Experiência;
- Seção Pokémon Parceiros;
- Cards com Pokémon;
- Galeria de imagens;
- Seção de Contato;
- Footer com informações e links internos.

---

## HTML semântico

Foram utilizados elementos semânticos do HTML5 para representar corretamente a estrutura da página, incluindo:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<footer>`

Também foi utilizada uma hierarquia organizada de títulos com `h1`, `h2` e `h3`.

As imagens possuem atributos `alt` descritivos para contribuir com a acessibilidade.

---

## CSS e responsividade

O CSS foi mantido em um arquivo externo chamado:

`style.css`

A estilização utiliza recursos como:

- Flexbox;
- CSS Grid;
- margin;
- padding;
- gap;
- unidades relativas;
- pseudo-classes;
- efeitos de hover e foco;
- Media Queries.

Foram criadas adaptações para diferentes tamanhos de tela, incluindo desktop, tablet e celular.

A página foi testada para manter organização visual e evitar rolagem horizontal indevida.

---

## Organização dos arquivos

```text
desafio-01-kodie/
│
├── index.html
├── style.css
└── README.md

'''

## Uso de Inteligência Artificial

A Inteligência Artificial foi utilizada como ferramenta de apoio durante o desenvolvimento deste projeto, conforme permitido pela proposta do desafio.

A IA auxiliou em:

- criação e organização da estrutura inicial;
- aplicação de HTML semântico;
- organização e estilização do CSS;
- utilização de Flexbox e Grid;
- responsividade para diferentes tamanhos de tela;
- revisão de boas práticas;
- explicação dos conceitos utilizados;
- apoio na identificação e correção de problemas.

O código foi analisado, testado e acompanhado durante o desenvolvimento, relacionando o uso da IA aos conhecimentos estudados em HTML e CSS.

---

## Prompts utilizados

### Prompt para HTML

> Estou criando uma Landing Page simples e responsiva utilizando apenas HTML5 e CSS3.
>
> O tema do projeto será um portfólio do Ash Ketchum, apresentado como um treinador Pokémon.
>
> Crie uma página com uma aparência moderna, simples e organizada, contendo:
>
> Header: nome "Ash Ketchum" e menu de navegação;
>
> Hero: título de apresentação, uma breve descrição e um botão de chamada para ação;
>
> Sobre: uma breve apresentação do Ash como treinador;
>
> Experiência: informações sobre sua jornada como treinador;
>
> Pokémon parceiros: pelo menos 3 cards apresentando Pokémon parceiros;
>
> Galeria: imagens relacionadas ao personagem e à jornada;
>
> Contato: uma seção simples com informações fictícias de contato;
>
> Footer: nome do projeto e uma pequena mensagem.
>
> Utilize HTML semântico com header, nav, main, section, article e footer.
>
> Utilize uma hierarquia correta de títulos (h1, h2, h3) e atributos alt descritivos nas imagens.

### Complemento do prompt para HTML

> Não utilize JavaScript, CSS inline ou a tag `<style>`. O CSS deve ficar em um arquivo externo chamado style.css.
>
> Para as imagens, sugira imagens relacionadas a cada seção e forneça URLs de imagens públicas que possam ser utilizadas no projeto, sempre que possível utilizando fontes apropriadas para uso educacional.
>
> O projeto deve ser responsivo para celular, tablet e desktop.
>
> Separe o resultado em:
>
> index.html
>
> style.css
>
> Antes do código, explique brevemente a estrutura criada.

### Prompt para CSS

> Crie um arquivo CSS externo para essa Landing Page.
>
> Utilize Flexbox e Grid quando apropriado, espaçamentos com margin, padding e gap, unidades relativas e uma Media Query para adaptar a página para celular.
>
> Não utilize CSS inline nem JavaScript.
>
> Explique brevemente as principais propriedades utilizadas.

### Prompt para revisão

> Analise meu código HTML e CSS abaixo como se você fosse um professor de desenvolvimento web.
>
> Meu projeto é um portfólio simples do Ash Ketchum.
>
> Verifique:
>
> HTML semântico;
>
> hierarquia dos títulos;
>
> acessibilidade das imagens;
>
> organização das classes;
>
> uso de Flexbox e Grid;
>
> espaçamentos;
>
> responsividade;
>
> possíveis problemas de rolagem horizontal.
>
> Não reescreva todo o projeto. Aponte os problemas encontrados, explique o motivo e sugira como posso corrigi-los.
>
> HTML:
>
> [código HTML]
>
> CSS:
>
> [código CSS]

---

## Versionamento com Git

O projeto foi versionado utilizando Git, registrando etapas diferentes do desenvolvimento por meio de commits significativos.

Commits realizados durante o desenvolvimento:

```bash
git commit -m "feat: cria estrutura semantica da landing page"
git commit -m "style: adiciona layout responsivo e organizacao visual"
git commit -m "docs: adiciona README e documentacao do projeto"
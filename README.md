# POC-Flexbox-TechMack
Prova de Conceito sobre Flexbox desenvolvida pelo grupo TechMack
# Projeto de Estilização CSS

Este projeto implementa uma página web simples com estilização utilizando CSS. O layout é centrado, com cores vibrantes e uma estrutura de conteúdo organizada em duas colunas.

## Estrutura do CSS

### 1. Estilização Global (`body`)

```css
body {
    background-color: #734885;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    font-family: Arial, Helvetica, sans-serif;
    color: #F28322;
}
```
- Background Color: A cor de fundo é um roxo escuro (#734885).
- Layout: O conteúdo do corpo da página é centralizado tanto horizontalmente quanto verticalmente usando flexbox.
- Tipografia: A fonte usada é uma combinação de Arial, Helvetica, e fontes sans-serif. A cor do texto principal é laranja vibrante (#F28322).
  
### 2. Estilização do Título (`h1`)

```css
h1 {
    display: flex;
    justify-content: center;
    font-size: 50px;
}
```
- Tamanho da Fonte: O título tem um tamanho de fonte grande, de 50px.
- Centralização: O título é centralizado horizontalmente.
  
### 3. Estilização dos Parágrafos (`p`)

```css
p {
    color: #F2F2F2;
    font-weight: bold;
    font-size: 18px;
    line-height: 1.5;
    text-align: justify;
    margin-bottom: 20px;
    text-indent: 30px;
}
```
- Cor do Texto: O texto dos parágrafos é branco (#F2F2F2).
- Estilo: O texto é em negrito, com um tamanho de 18px e espaçamento entre linhas de 1.5.
- Alinhamento: O texto é justificado, com indentação de 30px na primeira linha.

### 4. Estilização dos Itens de Lista (`li`)
```css
li {
    font-family: Arial, Helvetica, sans-serif;
    color: #F2F2F2;
    margin-bottom: 1%;
}
```
- Fonte: Consistente com o restante da página, utilizando Arial, Helvetica, sans-serif.
- Cor: Branco (#F2F2F2).
- Espaçamento: Há um pequeno espaço entre os itens de lista.

### 5. Estrutura da Página (`header e #pageContent`)
```css
header {
    width: 100%;
}

#pageContent {
    display: flex;
    justify-content: center;
    align-content: center;
    background-color: #734885;
    width: 80%;
    margin: 0;
}
```
- Header: O cabeçalho ocupa toda a largura da página.
- Conteúdo Principal: O conteúdo é organizado em um layout flexível, centralizado, e ocupa 80% da largura da página.

### 6. Conteúdo à Esquerda e à Direita (`#leftContent e #rightContent`)
```css
#leftContent {
    margin-right: 5px;
    text-align: justify;
    width: 50%;
    flex-direction: column;
    padding-right: 2%;
}

#rightContent {
    text-align: justify;
    border-left: 2px solid black;
    width: 50%;
    flex-direction: column;
    padding-left: 2%;
}
```
- Divisão do Conteúdo: A página é dividida em duas colunas iguais (50% de largura cada).
- Conteúdo Esquerdo: Tem um espaçamento à direita e é justificado.
- Conteúdo Direito: Também justificado, com uma borda preta à esquerda para separação.

### 7. Estilização das Imagens (`img`)
```css

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
}
```
- Centralização: As imagens são centralizadas horizontalmente.
- Tamanho: As imagens são redimensionadas para ocupar 50% da largura do contêiner.

## Como Utilizar
Para usar este CSS no seu projeto:

- Copie o código CSS para o seu arquivo .css.
- Aplique as classes e IDs correspondentes ao seu HTML.
- Garanta que o HTML siga a estrutura esperada para que o layout e a estilização sejam aplicados corretamente.
## Tecnologias Utilizadas
- HTML
- CSS (Flexbox para layout)
## Autores
Este projeto foi desenvolvido para entendermos, os diferentes tipos de uso da propriedade display:Flex.
Projetado por
- Arthur_Eduardo
- Guilherme_Sampaio
- Felipe_Melantonio 


 

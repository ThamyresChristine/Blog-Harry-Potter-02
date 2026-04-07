# Fandom Harry Potter

## O Projeto: [Fandom Harry Potter](https://thamyreschristine.github.io/Blog-Harry-Potter-02/)

## Foi feito com 

- HTML5 Semântico
- CSS Colors e Fonts(font-face)
- CSS Flexbox
- CSS Grid
- Design Responsivo(CSS Media Queries)

## O que foi aprendido

Foi aprendido o fundamental de HMTL e CSS para criação de um site. No HTML, destaca-se os acordeões feitos na página "A Saga" com as as tags _details_, _summary_ e _div_ para 
exibir a imagem e um resumo de cada livro da saga.

```html
<details>
  <summary>Harry Potter e o Enigma do Príncipe</summary>
    <div class="border">
      <div class="div">
        <img src="./assets/img/English_Harry_Potter_6.jpg" width="350px" alt="harry e dumbledore olhando para uma taça">
        <div class="p">
          <p></p>
        </div>
      </div>
      <div class="a-href"><a href="#">Compre o Livro Aqui</a></div>
    </div>
</details>
```

No CSS detalhe para a estilização do cabeçalho e menu principal do site, adicionando uma imagem de fundo ocupando todo o plano de fundo do titulo principal, aplicação das propriedades _flex_ _position relative com z-index_ no menu para uma visualização horizontal e que não sai da tela enquanto o usuário dá um scroll na página.

```css
header {
        background-image: url('../img/oqspeqq1a8ha1.png');
        background-position: center;
        background-size: cover;
        color: #e5ba40;
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: center;
        position: relative;
}
nav {
    font-size: 2rem;
    background-color: #001F3F;
    z-index: 1000;
}
```

## O uso da IA

Foi utilizado o ChatGPT para a criação das imagens e de parte dos textos. 
Nas imagens, solicitou-se a IA a criação das imagens no estilo do _studio Ghibli_. Os prompts foram específicos - pedindo como deveria ser o plano de funda da imagem, solicitando as características marcantes dos personagens e as feições de acordo com os livros.
Quanto aos textos, foi pedido apenas para a IA para produzir diferentes tipos de texto:
- fazer um resumo de cada um dos personagens citados, destacando suas características principais
- organizar as informações e curiosidades da história em listas

## Recursos Utilizados
A fonte do site foi retirada da biblioteca do Google: 
- [Example resource 1](https://www.example.com)

A paleta de cores foi de acordo com as cores apresentadas nos filmes e foi encontrada em dois sites:
- [Example resource 2](https://www.example.com)
- [Example resource 2](https://www.example.com)

## Aprendizado Contínuo

Foi o primeiro projeto de FrontEnd, utilizando o fundamental de HTML e CSS. Para os próximos projetos, desejo consolidar os conceitos de HTML e aprofundar em CSS intermediário (mais layouts e transições).

## Agradecimentos

Este projeto é resultado de uma série de aulas junto com o [Nicholas](). Agradeço pela oportunidade de aprender coisas novas e parceria na jornada da programação.

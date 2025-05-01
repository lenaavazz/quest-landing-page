# Frontend Mentor - Huddle landing page with single introductory section solution

Esta é uma solução para o [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação através de contrução de projetos realistas.

## Índice

- [Visão Geral](#visao-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
- [Meu processo](#meu-processo)
  - [Construindo com](#construindo-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Visão Geral

### O desafio

Os usuários devem ser capazes de:

- Ver o layout ideal da página dependendo do tamanho da tela do dipositivo
- Ver os estados de interação com os elementos que são interativos na página

### Screenshot

<img src="./src/images/tela-desktop.gif" alt="gi da tela do computador">

<img src="./src/images/tela-mobile.gif" alt="gi da tela do dispositivo móvel">

## Meu processo

### Construindo com

- Semântica HTML5
- Propriedades CSS
- Flexbox

### O que eu aprendi

Primeiro de tudo gostaria de dizer que aprendi que somente com persistência cheguei até aqui, e isso foi uma grande vitória.

Consegui ver, depois de apanhar muito que, montar um código HTML bem estruturado faz total diferença depois quando vamos fazer o CSS porque facilita muito mais.

No CSS tive bastante dificuldade, e eram coisas simples como posicionar imagens por exemplo, também em posicionar os ícones de redes sociais dentro dos círculos e fazer o hover em todos esses elementos. E depois posicionar eles sempre na base do projeto sem que eles ficassem subindo toda vez que a tela mudasse de tamanho.

E aqui eu mostro como ficou essa parte dos ícones:

```html
<div class="social">
  <div class="circulo">
    <a href="">
      <i class="fab fa-facebook-f"></i>
    </a>          
  </div>
```

```css
.container .social .circulo{
  display: flex;
  width: 35px;
  height: 35px;
  border: #fff solid 1px;
  border-radius: 50%;
  align-items: center;
  justify-content: center;
  margin-left: 16px;
  transition: 0.3s;
}
```

## Autor

- Frontend Mentor - [@lenaavazz](https://www.frontendmentor.io/profile/lenaavazz)
- Instagram - [@lenaavazz](https://www.instagram.com/lenaa_vazz/)

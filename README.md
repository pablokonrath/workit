# Solução da página inicial Workit

Esta é uma solução para o desafio da página inicial Workit no [Frontend Mentor](https://www.frontendmentor.io). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Índice

- [Visão geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Captura de tela](#captura-de-tela)
- [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
    - [Desenvolvimento contínuo](#desenvolvimento-contínuo)

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal para a interface, dependendo do tamanho da tela do dispositivo
- Ver os estados de foco e hover para todos os elementos interativos na página

### Captura de tela

![Captura de Tela](./assets/images/home.png)

## Links

- URL da solução: [https://github.com/pablokonrath/workit.github.io]()
- URL do site ao vivo: [https://pablokonrath.github.io/workit.github.io/]()

## Meu processo

### Construído com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Sass
- Metodologias BEM, ITCSS, NAMESPACES

# Resumo do Projeto

## O que eu aprendi

Ao trabalhar neste projeto, consegui aprimorar minhas habilidades em manipulação de posições usando `absolute` e `relative`. Esse projeto foi meu primeiro desafio prático, o que me permitiu reforçar meus conhecimentos nas tecnologias utilizadas, como HTML, CSS e React.

### Posicionamento absoluto e relativo

Entendi como utilizar `position: absolute` e `position: relative` para controlar melhor o layout dos elementos na página. Aprendi a importância de definir um elemento pai com `position: relative` para que o posicionamento absoluto de seus filhos seja calculado com base nesse elemento pai.

```css
.container {
  position: relative;
}

.elemento-absoluto {
  position: absolute;
  top: 10px;
  left: 20px;
}
```

No entanto, ainda encontrei desafios significativos ao lidar com o posicionamento de elementos e a nomenclatura de classes. Às vezes, tive dificuldade em determinar a melhor abordagem para organizar e nomear minhas classes CSS de forma clara e eficiente.

```css
/* Exemplo de nomenclatura de classe que ainda estou aperfeiçoando como BEM */
.header__container {
  /* Estilos para o container do cabeçalho */
}

.header__title {
  /* Estilos para o título do cabeçalho */
}
```

Esse projeto me ensinou a importância da prática contínua e do aprendizado iterativo, e estou ansioso para aplicar esses conhecimentos em projetos futuros e continuar aprimorando minhas habilidades.

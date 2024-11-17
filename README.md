# 24 CSS Projects

## Descrição
Este repositório contém uma coleção de 24 projetos desenvolvidos para aprimorar minhas habilidades em CSS. Cada projeto aborda diferentes técnicas e desafios que envolvem a criação de layouts modernos, animações e interações que são fundamentais para o desenvolvimento web responsivo e acessível.

## Objetivos
O principal objetivo deste repositório é explorar e aplicar novos conceitos em CSS, ao mesmo tempo em que reforço fundamentos essenciais. Ao longo destes 24 projetos, busco:

- Aprender e aplicar novas propriedades e métodos CSS.
- Melhorar a criação de layouts responsivos e flexíveis.
- Explorar animações e transições para melhorar a experiência do usuário.
- Trabalhar com técnicas de design acessível e amigável para diferentes dispositivos.

## Projetos
### Projeto 01 - Botão Colorido
Esse projeto se trata da construção de um botão com bordas coloridas que mudam de lado se o mouse estiver em cima do botão. Nesse projeto, aprendi sobre:
- Gradiente
Para completar esse desafio, precisei aprender sobre `linear-gradient`, onde apliquei-o dentro da `border-image` do botão.Precisamos usar o `border-image` pois o gradiente é tratado como uma imagem. Além disso, eu também tinha a opção de colocar o grandiente no background na div `button-border` e adicionar um padding, pois o efeito seria o mesmo da borda do botão.

### Projeto 02 - Pesquisa Expansiva
Nesse projeto eu crio uma barra de pesquisa que se expande quando o usuário clica nela. Nesse projeto, aprendi sobre:
- Esconder um `label` de forma visual, mas *não esconder dos leitores de tela*;
- `::placeholder`;
1. No segundo projeto, tive que *aprender mais sobre formulários*. Um dos maiores desafios foi encontrar uma forma de esconder o `label` visualmente dos usuários mas de um jeito que ele ficasse visível para os leitores de tela. Aprendi que tem uma forma de fazer isso com CSS. (Se quiser se aprofundar, clique [aqui](https://www.w3.org/WAI/tutorials/forms/labels/#hiding-label-text).e procure o tópico "Note on hiding elements".)
2. O meu segundo desafio foi encontrar uma forma de fazer o placeholder do forms sumir quando estivesse em focus. Para resolver isso eu encontrei o pseudo-elemento `::placeholder` e o usei junto com a pseudo-classe `focus`.
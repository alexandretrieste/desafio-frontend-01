# Desafio Frontend
Como parte do processo seletivo do [MaaS](https://github.com/ModalServices), utilizamos esse desafio técnico para avaliar seus conhecimento técnicos e habilidades com o requisito da vaga, lembrando apenas, que claro, o teste deve ser feito por você e apenas você, no conforto de seu castelo!

## Descrição do desafio

O desafio consiste em criar uma aplicação client-side escalável, utilizando a biblioteca React, que faça consultas e consuma uma API externa, nesse cenário, sendo da Marvel, seguindo as diretrizes mencionadas logo abaixo e o protótipo desenvolvido especialmente para esse desafio.

[Link para o protótipo e assets no Figma](https://figma.com/file/b7EzpqbYSCIjj2OFHPGCqY/Live-On-Challenge-Frontend-React)

## API

```https://developer.marvel.com```

## Diretrizes

A aplicação deve contemplar as seguintes diretrizes:

### Home

- Na **Home**, assim que o usuário acessá-la, **devemos trazer a lista de heróis da Marvel**, de acordo com a listagem da API, que provavelmente estarão em ordem alfabética.
  - O card de cada herói deve possuir sua **imagem**, seu **nome**, uma **breve descrição** e um **botão para adicioná-lo ao nosso time** (também conhecido como **Favoritar** em outras línguas 😂).
- Quando pensamos em fazer uma **aplicação performática** e na **quantidade de personagens que a Marvel possui**, **é de alta importância que a lista de heróis exibidas seja paginada**, seja através de um meio tradicional (com números e botões de "Próximo" e "Anterior") ou carregamento infinito baseado na rolagem da página pelo usuário.
- E claro, é de **extrema importância** que exista uma **barra de pesquisa para podermos buscar nossos heróis favoritos** no meio de tanta gente!

### Perfil do Herói

- No **Perfil do Herói**, temos um card de apresentação com a **imagem do personagem**, seu **nome** e uma **breve descrição**.
- Uma seção com **5 quadrinhos** do herói, sendo que cada um deve conter sua **imagem**, **nome**, **data de lançamento**, **quantidade de páginas**, o **preço praticado**, e uma **breve descrição**, **limitada em 200 caractéres** (visto que as descrições oscilam demais).

### Favoritos

- Nos **Favoritos**, a lista de cards dos herói que foram selecionados para a equipe deve ser exibido, assim como pode ser visto na **Home**, com a diferença de que o botão que servia para juntá-lo ao time, agora o remove.
- Novamente, pensando em uma aplicação performática, é interessante que exista uma paginação, seja ela tradicional (como explicado acima), ou de carregamento infinito.

## Diferenciais

- README.MD organizado;
- Responsividade da aplicação;
- [TypeScript](https://typescriptlang.org);
- Pré-processadores CSS [(Sass ou SCSS)](https://sass-lang.com);
- Utilização da [contextAPI](https://reactjs.org/docs/context.html) ou [Redux](https://redux.js.org);

## Como entregar o desafio?

1. Faça um fork desse projeto em sua conta pessoal no GitHub;
2. Desenvolva o desafio Frontend do [MaaS](https://github.com/ModalServices);
3. Adicione como membro do repositório o seguinte usuário do GitHub [@vagas-modalservices](https://github.com/vagas-modalservices);
4. Por fim, envie um email informando que concluiu o desafio p/ [vagas@liveonsolutions.com](mailto:vagas@liveonsolutions.com). (coloque no assunto o nome do desafio)

## Avaliação

Seu projeto será avaliado de acordo com a qualidade e organização de código, arquitetura, além de seus conhecimentos sobre a biblioteca React, JavaScript ou TypeScript, padronizações, portanto, esperamos que seus conhecimentos estejam afiados!

Dito isso, depois de nos dar acesso ao repositório do seu teste, pedimos que por favor nos avise através do email [vagas@liveonsolutions.com](mailto:vagas@liveonsolutions.com). Avaliaremos o mais rápido possível e também garantimos o feedback!

A equipe Frontend do MaaS te deseja boa sorte e esperamos que você se divirta com o desafio!

# Setta - Desafio Mobile

Esse desafio é parte do processo de seleção para desenvolvedores mobile que desejam trabalhar na [Setta](https://setta.co).

## Sobre o desafio

O objetivo é avaliar sua experiência em escrever código coeso, de fácil manutenção e baixo acoplamento. Não existem respostas certas ou erradas, portanto você será avaliado de acordo com alguns critérios de aceite, além dos itens abaixo.

## A Avaliação

- Atendimento aos critérios de aceite;
- Documentação (comente sobre decisões técnicas, escolhas, requisitos, etc);
- Código (modularização, nomenclaturas, padronização, reutilização, organização);
- Design da solução/arquitetura;
- Conhecimento de Git;
- Conhecimento de frameworks e outras tecnologias;
- Algoritmo, abstrações e acoplamento.

## O problema

Precisamos registrar o tempo que um usuário passa focado, e também quanto tempo ele tem de interrupções enquanto faz uma tarefa. Para isso, criamos um cronômetro que registra cada bloco de tempo, de pausa e de foco, e que nos mostra um relatório ao ser finalizado.

**Um exemplo de uso**:

- usuário pressiona `play` o cronômetro inicia a contagem;
- usuário pressiona `pause` quando o cronômetro registra `02:10`;
- usuário fica `01:25` em modo `pause`;
- usuário pressiona `play` novamente e o cronometro continua de `02:10`;
- uma nova pausa com cronômetro marcando `06:05`, portanto esse bloco de tempo durou `3:55`
- depois de `08:20`, novamente aperta o play;
- usuário pressiona `finalizar` com cronômetro marcando `18:39`, e vê a tela seguinte com as informações que estão na [imagem de timeblocks](./img/timeblocks.png);

> Você pode ver as 3 telas que precisam ser desenvolvidas no [Figma](https://www.figma.com/file/UnE9gL6XCrPsVXjHbrTc8d/Setta-Mobile-Challange?node-id=0%3A1), ou [aqui](./img/screens.png)

## Extras/Funcionalidades opcionais

Se quiser dar um passo além, listamos aqui algumas coisas que você pode incluir na sua entrega:

- Incluia testes automatizados utilizando o [Jest](https://jestjs.io/pt-BR/) e [@testing-library/react-native](https://github.com/callstack/react-native-testing-library);
- Adicione uma nova tela, para mostrar os cronômetros finalizados, onde seja possível acessá-los e ver os timeblocks de cada um;
- Pense em uma funcionalidade interessante e implemente ela no app, use a criatividade!

## Como submeter seu teste

Após finalizar o desafio, dê acesso ao [@brunobertolini](https://github.com/brunobertolini), e então envie um email para `bruno.bertolini@setta.co` com:

- Assunto: [Mobile Developer] Seu nome;
- Link do repositório do seu teste
- Informações sobre você: Github, Linkedin, e tudo o que considerar importante.

## Dúvidas

Se tiver qualquer dúvida, abra uma [issue](https://github.com/setta-labs/mobile-challenge/issues).

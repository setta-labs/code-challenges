# Setta - Desafio Backend

Esse desafio é parte do processo de seleção para desenvolvedores backend que desejam trabalhar na [Setta](https://setta.co).

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

> Seu código precisa estar coberto por testes automatizados.

## O problema

Precisamos registrar o tempo que um usuário passa focado, e também quanto tempo ele tem de interrupções enquanto faz uma tarefa. Para isso, criamos um cronômetro que registra cada bloco de tempo, de pausa e de foco, e que nos mostra um relatório ao ser finalizado.

Cada tarefa pode ter uma lista de tempos, onde teremos cada bloco de foco e cada bloco de pausa. Queremos guardar esses tempos para que consigamos futuramente analisar:

- Quanto tempo o usuário passou focado em cada tarefa;
- Quanto tempo o usuário teve de interrupção em cada tarefa;
- Qual tempo médio de foco de cada tarefa;
- Qual tempo médio de interrupção em cada tarefa.

Por enquanto, precisamos apenas guardar esses dados e retorná-los em um endpoint para atender às [telas](./img/screens.png) que serão desenvolvidas no app.

## Extras/Funcionalidades opcionais

Se quiser dar um passo além, listamos aqui algumas coisas que você pode incluir na sua entrega:

- Incluir % de cobertura nos testes;
- Adicionar funcionalidade de dados para análise (um novo endpoint, ou no mesmo, fica a seu critério);
- Adicionar suporte à GraphQL além do REST;
- Pense em uma funcionalidade interessante e implemente ela no app, use a criatividade!

## Como submeter seu teste

Após finalizar o desafio, dê acesso ao [@brunobertolini](https://github.com/brunobertolini), e então envie um email para `bruno.bertolini@setta.co` com:

- Assunto: [Backend Developer] Seu nome;
- Link do repositório do seu teste
- Informações sobre você: Github, Linkedin, e tudo o que considerar importante.

## Dúvidas

Se tiver qualquer dúvida, abra uma [issue](https://github.com/setta-labs/mobile-challenge/issues).
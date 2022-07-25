# Teste de Programação Elo7
Como parte do processo seletivo do Elo7, gostaríamos que você fizesse uma pequena tarefa. Conforme seu resultado convidaremos você para uma sessão de pair-programming.

O objetivo dessa tarefa é avaliar como você desenvolve código em termos de estilo, eficiência e qualidade.

Crie um repositório no seu Github com a resolução da tarefa descrita abaixo e veremos a sua progressão por meio dos commits.

## Feature
Estamos querendo divulgar algumas de nossas vagas disponíveis aqui no Elo7, e, para isso, gostariamos de desenvolver uma landing page.

Nesta landing page, fornecemos algumas informações e deixamos em exposição nossas vagas em aberto.

## O que deverá ser feito:
Propomos a criação da tela com as seguintes premissas:
- Tela principal contendo um resumo sobre o Elo7, como é trabalhar aqui, alguns depoimentos e nossa cultura, além de conter uma listagem das vagas em aberto;

### *Opcional*
- Em cada uma das vagas a ser visualizadas nesta landing page, seria interessante adicionar um icone `favoritar`, onde o candidato pode clicar neste icone e deixar esta vaga "salva" em uma sessão de favoritos (outra tela), para uma candidatura futura;
- Com a disponibilização deste icone favoritar, deverá ser feito uma tela secundária, onde o candidato poderá visualizar todas as suas vagas favoritadas, caso a tenha feito.

## Orientações
- Link do figma com o layout a ser seguido TODO FIGMA LAYOUT;
- Os dados das vagas devem ser obtitos desta [API](http://www.mocky.io/v2/5d6fb6b1310000f89166087b);
- Infelizmente, os dados obtidos pelo mock acima não não foram tratados e, por isso, devem ser seguidos as seguintes premissas para exibição das vagas ao candidato:
  - Remover as vagas inativas;
  - Para os casos em que não tem a localização, exibir  a palavra "Remoto" no lugar da localidade.
  - Todos os arquivos necessários para o teste podem ser baixados [aqui](https://s3.amazonaws.com/files.elo7.com.br/candidatos/front-end/teste.zip)
- *Item opcional*: Implemente algum mecanismo para salvar as vagas favoritadas pelo candidato, podende ser: localStorage, cookie, sessionStorage, arquivo .txt, etc. Fique a vontade para escolher;

## Premissas
| Abrangência                | O que esperamos      |
| :------------------------: | -------------------- |
| Linguagem                  | Javascript/Typescrit |
| Estilo                     | Css/SASS             |
| Requisição                 | Fetch/Axios          |
| *Armazenamento (opcional)* | *Livre Escolha*      |

## Dicas
- Mais importante do que o seu conhecimento em framework A ou B, iremos avaliar o seu conhecimento com Javascript / Typescript e CSS / SASS;
- Também vamos levar em conta a organização e estrutura do código desenvolvido;
- Tente reutilizar sempre que possível o código desenvolvido;
- Esperamos que o layout fique o mais próximo possível do layout fornecido, além de estar flexível (responsivo) conforme a largura da tela;
- Caso deseje aprimorar o template proposto, fique à vontade. Se algo não estiver óbvio, assuma o que for mais claro para você e documente suas suposições.

## Imagem base para a criação da landing page
![68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f66696c65732e656c6f372e636f6d2e62722f63616e64696461746f732f66726f6e742d656e642f76616761732e706e67](https://user-images.githubusercontent.com/7774041/180889357-426be8e3-9e24-4fe5-b88d-7caebc3ac352.png)

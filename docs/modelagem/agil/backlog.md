# Backlog do Produto + Histórias de Usuário

## 1. Introdução
<p align="justify">&emsp;&emsp; Em um cenário de desenvolvimentos ágeis, a geração de um artefato amplo que acorda as necessidades do produto como um todo se faz necessário. Assim, o Product Backlog (Backlog do Produto) entra em ação.</p>

<p align="justify">&emsp;&emsp; Um conceito que melhor define Product Backlog pode ser o seguinte: é uma lista contendo todas as funcionalidades desejadas para um produto. Ele é definido e gerenciado pelo PO - Product Owner (membro da equipe responsável pelo entendimento dos desejos do cliente e do produto a ser desenvolvido).</p>

<p align="justify">&emsp;&emsp; É interessante que todo Backlog siga a técnica DEEP:</p>

- **D**etailed: os itens devem estar detalhados (e visíveis) para entendimento de todos os envolvidos no processo.
- **E**stimated: é importante que o Backlog possa ser estimável, isto é, quanto tempo demoraria e quantos recursos serão usados para cada item do desenvolvimento.
- **E**mergent: o Backlog não é estático, ele muda e é acrescentado ao longo do ciclo de vida do produto.
- **P**rioritized: os itens devem ser priorizados, para que, assim, os itens mais valiosos e vitais possam ser mais visíveis e focados.

## 2. Metodologia

### 2.1 Especificação do Product Backlog
<p align="justify">&emsp;&emsp; Para o desenvolvimento do Product Backlog do projeto, a equipe vai utilizar de uma técnica de especificação dividida em 3 níveis de granularidade:</p>

- **Épico**: nível superior compostas por features que possuem um objetivo específico, mas comum.
- **Features**: podem ser entendidas como as funcionalidades em si do Software, mas de forma geral, sem muito detalhamento.
- **Histórias de Usuário**: é o nível em que o detalhamento do item em si acontece.

### 2.2 Histórias de Usuário
<p align="justify">&emsp;&emsp; As histórias de usuário podem ser usadas para expressar uma funcionalidade/requisito de um Software na visão e perspectiva de um cliente que realmente usará a aplicação. Sendo assim, é possível entender quais são as expectativas e necessidades daqueles que serão os verdadeiros utilizadores do sistema.</p>

<p align="justify">&emsp;&emsp; É essencial que todas as histórias de usuário possuam critérios de aceitação relacionadas a si, para que seja possível o levantamento da qualidade e do que seria uma história completa e bem-sucedida.</p>

### 2.3 Estrutura do Product Backlog com Histórias de Usuário
<p align="justify">&emsp;&emsp; Com o entedimento da especificação do Product Backlog e das Histórias de Usuário, a equipe montou o Product Backlog do aplicativo YouTube, seguindo o seguinte formato:</p>

#### Nome Épico

##### Nome Feature

<p align="justify">&emsp;&emsp; Lista de Histórias de Usuário ligadas a essa Feature e, consequentemente, Épico.</p>

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| USXX | Tipo Usuário | Funcionalidade | Objetivo          | - Critério 1<br/>- Critério 2 | Alta/Média/Baixa |

<p align="justify">&emsp;&emsp; As prioridades foram divididas entre Alta, Média ou Baixa levando em consideração uma análise na visão das técnicas de priorização já usadas no projeto (<a href="https://requisitos-de-software.github.io/2022.1-Youtube/elicitacao/priorizacao/moscow/" target="_blank">MoSCoW</a> e <a href="https://requisitos-de-software.github.io/2022.1-Youtube/elicitacao/priorizacao/100dol/" target="_blank">100 Dólares</a>). Sendo assim, itens de <b>Alta</b> prioridade são essenciais e mais recursos seriam destinados a eles, os de <b>Média</b> prioridade são importantes para o aplicativo, mas não vitais para seu funcionamento e os itens de <b>Baixa</b> prioridade são aperitivos sem foco inicial.</p>

## 3. Product Backlog

### Épico - Conta

#### Feature - Gerenciamento de conta

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Usuário   | Adicionar uma conta | ter uma (ou mais) conta cadastrada para realizar login | - O usuário deve adicionar sua conta Google no aplicativo<br/>- O usuário deve ser redirecionado para uma página de cadastro/conta do google | Alta |
| US0 | Usuário   | Remover uma conta | sair da minha conta adicionada no app | - Ter a opção de remover conta do dispositivo<br/>- O sistema deve pedir uma confirmação que a ação de logout realmente será executada | Alta |

#### Feature - Funcionalidades adicionais/externas (?) <-----------------------------------------------

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Usuário   | espelhar o aplicativo a outro dispositivo | ter acesso à plataforma em outra tela | - O usuário deve clicar no botão de espelhar<br/>- Deve ser mostrada os dispositivos possíveis de espelhamento para que o usuário selecione o desejado | Baixa |
| US0 | Usuário   | acessar o modo de navegação anônimo | ter um acesso mais restrito ao aplicativo | - O usuário deve clicar no botão "modo de navegação anônima" nas suas configurações<br/>- O aplicativo deve explicar as mudanças que o modo de navegação anônima tem para com o modo normal | Baixa |
| US0 | Usuário   | ativar o modo escuro | ter um aplicativo com design noturno | - O usuário deve clicar no botão "geral" nas suas configurações<br/>- O usuário pode escolher enter a aparência escura ou a clara | Baixa |

### Épico - Criação de Conteúdo

#### Gerenciamento de canal

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Criador de conteúdo | Criar um canal | Postar meus vídeos | - O usuário deve, inicialmente, escolher o nome do canal<br/>- O usuário deve selecionar uma foto de perfil para o canal | Alta |
| US0 | Criador de conteúdo | Editar o banner do meu canal | ter uma apresentação personalizada | - O usuário deverá escolher uma de suas fotos no dispositivo<br/> | Média |
| US0 | Criador de conteúdo | Excluir um canal | não ter mais acesso a ele | - Um botão de "excluir canal" deve estar disponível nas configurações do canal<br/>- O sistema deve pedir uma confirmação que a ação será executada | Baixa |
| US0 | Criador de conteúdo | Obter estatísticas do canal | ter noção dos meus números de performance | - Um ícone/botão de gráficos deve aparecer na tela inicial do canal<br/>- Ao clicar na tela, um dashboard com as estatísticas de inscritos e vídeos deve aparecer | Média |

#### Feature - Gerenciamento de vídeos

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Criador de conteúdo | Postar um vídeo | hospedar meu vídeo no meu canal | - O usuário deve adicionar sua conta Google no aplicativo<br/>- O usuário deve ser redirecionado para uma página de cadastro/conta do google | Alta |
| US0 | Criador de conteúdo | Excluir um vídeo | não ter mais acesso a ele | - Um botão de "excluir vídeo" deve estar disponível na tela de edição do vídeo<br/>- O sistema deve pedir uma confirmação que a ação será executada | Alta |
| US0 | Criador de conteúdo | Adicionar legendas ao vídeo | ter a opção de legenda para os espectadores | - <----------------------------------------------- | Alta |
| US0 | Criador de conteúdo | Obter estatísticas de um vídeo | ter noção dos meus números de performance | - Um botão de "estatísticas" deve aparecer no menu do vídeo<br/>- Ao clicar na tela, um dashboard com as estatísticas do vídeos (visualizações, curtidas, entre outros) deve aparecer | Média |
| US0 | Criador de conteúdo | Adicionar Thumbnail a um vídeo | ter uma imagem relacionada ao vídeo postado | - No menu do vídeo, deve ter um botão de alterar a imagem do vídeo<br/>- O aplicativo deve ter acesso às imagens no dispositivo para que o usuário selecione a Thumbnail desejada | Média |

### Épico - Consumir Conteúdo

#### Feature - Interação com vídeo

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Espectador | Assistir um vídeo | consumir um conteúdo do meu gosto | - O usuário deve poder clicar em um vídeo na sua tela para acessá-lo<br/>- A tela do vídeo deve estar em tamanho maximizado ao ser aberta pela primeira vez. | Alta |
| US0 | Espectador | Comentar em um vídeo | expressar o que desejar em forma de texto acerca do vídeo | - Deve haver uma área para os comentários de um vídeo<br/>- Deve ser clicado o botão de "enviar", para que o comentário seja publicado para o público | Média |
| US0 | Espectador | Avaliar um vídeo | expressar se gostei ou não do vídeo | - Devem haver dois botões: o de curtir e o de não curtir<br/>- Ao clicar o botão, ele deve mudar de cor para expressar que foi clicado | Média |
| US0 | Espectador | Compartilhar um vídeo | mandar ele para outras pessoas em outras redes sociais | - Deve haver o botão de "compartilhar" na tela do vídeo<br/>- Ao clicar na opção de compartilhar, o usuário pode copiar o link ou enviar o vídeo em outras redes sociais | Média |
| US0 | Espectador | Mudar a velocidade de um vídeo | acelerar ou desacelerar ele | - O vídeo que está sendo assistido deve possuir um botão no seu menu de "alterar velocidade de reprodução"<br/>- O usuário terá 5 opções de velocidade (2 mais lentas, a normal e 2 mais rápidas) | Baixa |
| US0 | Espectador | Mudar a qualidade de um vídeo | ver em uma maior ou menor qualidade | - O vídeo que está sendo assistido deve possuir um botão no seu menu de "alterar quadalide"<br/>- O usuário terá opções referentes às qualidades disponíveis (de 144p a 4k) | Baixa |
| US0 | Espectador | Avançar ou retroceder 10 segundos de um vídeo | ir para uma minutagem desejada mais rapidamente | - O vídeo não pode estar minimizado<br/>- Ao clicar da metade para a direita, o vídeo deve avançar<br/>- Ao clicar da metade para a esquerda, o vídeo deve retroceder | Baixa |

#### Feature - Interação com canal

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Espectador | Inscrever-se em um canal | ter acesso a mais funcionalidades relacionadas ao canal | - O botão de "inscrever-se" deve aparecer na tela de um vídeo do canal ou na própria tela do canal<br/>- O botão deve mudar para cinza ao ser clicado | Alta |
| US0 | Espectador | Ativar notificações de um canal | ser notificado toda vez o canal postar um vídeo | - Deve haver um botão em ícone de sino simbolizando as notificações<br/>- O botão deve mudar para preenchido de cinza ao ser clicado | Baixa |
| US0 | Espectador | Acessar os vídeos de um canal | ver todos os vídeos postados de um canal específico | - O usuário deve acessar a tela de um canal para encontrar o botão de "vídeos"<br/>- O usuário pode ordenar os vídeos por tempo de publicação ou relevância | Alta |

#### Feature - Playlists

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Usuário | Criar uma Playlist | salvar vídeos selecionados em uma área única | - Na área de biblioteca, deve ter o botão de criar uma playlist<br/>- O usuário deve, a princípio, selecionar o nome e alguns vídeos para a playlist | Média |
| US0 | Usuário | Excluir uma Playlist | não ter mais acesso a ela | - Um botão de "excluir playlist" deve estar disponível no menu da playlist selecionada<br/>- O sistema deve pedir uma confirmação que a ação será executada | Baixa |
| US0 | Usuário | Adicionar um vídeo a playlist | salvar esse vídeo nela | - Deve haver um botão de "salvar" na tela inicial do vídeo<br/>- Ao pressionar o botão, o usuário deve selecionar a playlist que ele deseja adicionar o vídeo | Média |
| US0 | Usuário | Excluir vídeo de uma playlist | não ter mais acesso a esse vídeo na playlist | - Deve haver um botão de "remover vídeo" na tela da playlist<br/>- O sistema deve pedir uma confirmação que a ação será executada | Baixa |

### Épico - Navegação

#### Feature - Página Inicial

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Espectador | ter vídeos recomendados na minha tela principal | encontrar vídeos de forma mais simples | - O sistema deve recomendar vídeos para o usuário na tela inicial<br/>- O vídeo na tela inicial pode ser reproduzido ao clicar nele. | Média |
| US0 | Espectador | Ver os vídeos postados pelos canais que sou inscritos | acessá-los de forma mais simples | - Na tela inicial, o usuário tem a opção de menu "Inscrições"<br/>- A tela, a princípio, ordena os vídeos por publicação mais recente. | Média |

#### Feature - Busca

| ID   | Eu, como     | Desejo         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US0 | Usuário | Buscar por assuntos | encontrar conteúdos a meu gosto | - Na página inicial deve haver um ícone de lupa no lado superior da tela<br/>- O usuário deve poder buscar por qualquer texto que desejar<br/>- A busca pode ser filtrada por tipo (vídeo, canal ou playlist) ou por quando foi publicada | Alta |
| US0 | Usuário | Ver meu histórico de busca | recuperar buscas feitas | - Na opção de busca, as últimas pesquisas feitas devem aparecer para o usuário<br/>- Na tela "biblioteca", deve haver um botão que direciona para uma tela com todas as buscas já feitas pelo usuário. | Média |

## 4. Referências

> - Milene Serrano, Requisitos - Aula 15. Acesso em: 06 de jul. de 2022. Disponível em: Aprender3.
> - LuizTools, Product Backlog - Introdução. Acesso em: 28 de jul. de 2022. Disponível em: https://www.youtube.com/watch?v=z4ubaBwjCsU&feature=youtu.be.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 28/07/2022 | Criação do esqueleto do documento e introdução inicial. | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
| 1.1    | 28/07/2022 | Reformulação da estrutura do Product Backlog. | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
| 1.2    | 28/07/2022 | Adição de histórias, features e épicos iniciais. | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
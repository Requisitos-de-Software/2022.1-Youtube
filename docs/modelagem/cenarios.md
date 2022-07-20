# Cenários

## 1. Introdução
Cenários são uma ferramenta utilizada para descrever as situações de uso de um sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros atores externos, auxiliando no entendimento e na descoberta de novos requisitos.

Em adição, segundo Carroll, o fato de um cenário projetar uma descrição concreta de uma atividade em que o usuário se engaja no momento em que está realizando uma tarefa específica é a propriedade que melhor define um cenário.(Cenários - Rastreamento de Cenários, página 47).

## 2. Metodologia
Após a listagem dos cenários identificados pela equipe, eles foram detalhados compondo os seguintes elementos:

- **Título**: breve identificação do cenário.
- **Objetivo**: o que se busca no cenário.
- **Contexto**: ambiente e pré-condição para o cenário acontecer.
- **Ator(es)**: sistemas ou usuários/pessoas que interagem no cenário.
- **Recursos**: o que é necessário para o cenário acontecer.
- **Episódios**: passo-a-passo do cenário.
- **Exceções**: impedimentos para a realização do cenário.

## 3. Cenários

### 3.1 Cenário 1 - Assistir a um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Assistir a um vídeo |
| Objetivo | Assistir a conteúdo (vídeo) postado na plataforma |
| Contexto | - Local: página inicial ou página de um canal<br/>- Pré-Condição: estar com o aplicativo aberto e conectado a internet |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário, caso o vídeo esteja pausado, clica no botão de play |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.2 Cenário 2 - Avaliar um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Avaliar um vídeo |
| Objetivo | Curtir ou não um vídeo que está sendo reproduzido |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta<br/>- Pré-Condição: estar logado em alguma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica no ícone de "curtir" ou "não curtir" do vídeo |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.3 Cenário 3 - Comentar em um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Comentar em um vídeo |
| Objetivo | Postar um comentário na sessão de comentários de um vídeo |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta<br/>- Pré-Condição: estar logado em alguma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário abre a aba de comentários de um vídeo<br/>3. O usuário escreve seu comentário na área designada<br/>4. O usuário clica em "enviar" para postar seu comentário|
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.4 Cenário 4 - Inscrever-se em um canal
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Inscrever-se em um canal |
| Objetivo | Se tornar inscrito em um canal na plataforma |
| Contexto | - Local: página de um vídeo ou página de um canal<br/>- Pré-Condição: estar com a página de um vídeo ou canal aberta<br/>- Pré-Condição: estar logado em alguma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica no botão "inscrever" ao lado do nome do canal<br/>1. O usuário clica em um canal<br/>2. O usuário clica no botão "inscrever" abaixo da foto do canal, na página incial do canal|
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.5 Cenário 5 - Compartilhar um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Compartilhar um vídeo |
| Objetivo | Compartilhar um vídeo postado nas redes sociais |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica no botão de "Compartilhar"<br/>3. O usuário seleciona a rede social que deseja compartilhar o vídeo |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.6 Cenário 6 - Criar uma Playlist
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Criar uma Playlist |
| Objetivo | Criar uma Playlist, isto é, uma "pasta" em que se pode salvar vídeos |
| Contexto | - Local: página "biblioteca"<br/>- Pré-Condição: estar logado em alguma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário abre a aba "biblioteca" na área inferior da tela<br/>2. O usuário clica no botão de "Nova Playlist"<br/>3. O usuário seleciona os vídeos que farão parte da playlist<br/>4. O usuário coloca o nome da playlist<br/>5. O usuário decide a privacidade de playlist<br/>6. O usuário cria a playlist |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.7 Cenário 7 - Adicionar vídeo a uma playlist
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Adicionar vídeo a uma playlist |
| Objetivo | Adicionar um vídeo que se está assistindo a uma playlist |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta<br/>- Pré-Condição: estar logado em alguma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário pressiona o botão de "Salvar"<br/>3. O usuário seleciona a playlist em que quer adicionar o vídeo |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.8 Cenário 8 - Alterar velocidade de reprodução de um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Alterar velocidade de reprodução de um vídeo |
| Objetivo | Acelerar ou desacelerar um vídeo que está sendo reproduzido |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica nas opções de um vídeo<br/>3. O usuário seleciona a opção "alterar velocidade de reprodução"<br/>4. O usuário seleciona a velocidade desejada |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.9 Cenário 9 - Controlar tempo de um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Controlar tempo de um vídeo |
| Objetivo | Avançar ou retroceder 10 segundos de um vídeo que está sendo reproduzido |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica duas vezes na tela na parte direita (ou esquerda) do vídeo |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.10 Cenário 10 - Criar um clipe de um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Criar um clipe de um vídeo |
| Objetivo | Fazer um corte de no máximo 60 segundos de um vídeo |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta<br/>- Pré-Condição: estar logado em alguma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica no botão "clipe"<br/>3. O usuário adiciona uma descrição ao clipe<br/>4. O usuário clica em "compartilhar clipe" e seleciona a rede social que irá compartilhar o clipe |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.11 Cenário 11 - Alterar qualidade de um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Alterar qualidade de um vídeo |
| Objetivo | Aumentar ou diminuir a qualidade visual de  um vídeo que está sendo reproduzido |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica nas opções de um vídeo<br/>3. O usuário seleciona a opção "alterar qualidade"<br/>4. O usuário seleciona a qualidade desejada |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.12 Cenário 12 - Visualizar vídeos postados dos canais inscritos
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Visualizar vídeos postados dos canais inscritos |
| Objetivo | Ver os vídeos mais recentes postados pelos canais em que o usuário é inscritos |
| Contexto | - Local: página de inscrições<br/>- Pré-Condição: estar logado em uma conta<br/>- Pré-Condição: estar inscrito em pelo menos um canal que já postou um vídeo, no mínimo |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica na aba "inscrições" na área inferior da interface inicial |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.13 Cenário 13 - Acionar notificações de um canal
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acionar notificações de um canal |
| Objetivo | Acionar a opção de receber notificações quando um canal lançar um vídeo |
| Contexto | - Local: página de um canal<br/>- Pré-Condição: estar logado em uma conta<br/>- Pré-Condição: estar na página de um canal<br/>- Pré-Condição: estar inscrito em um canal |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário abre a página inicial de um canal<br/>2. O usuário clica no ícone de "sino" presente ao lado do botão de inscrição  |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.14 Cenário 14 - Pesquisar por algum assunto
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Pesquisar por algum assunto |
| Objetivo | Pesquisar por um assunto, a fim de encontrar vídeos ou canais relacionados a ele |
| Contexto | - Local: página inicial<br/>- Pré-Condição: estar em alguma interface que permita a opção de busca |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica no ícone de "lupa" na área superior da tela<br/>2. O usuário escreve o assunto que deseja pesquisar<br/>3. O usuário clica no botão de enviar para que a busca seja efetuada |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.15 Cenário 15 - Acessar o histórico de vídeos exibidos
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acessar o histórico de vídeos exibidos |
| Objetivo | Visualizar os últimos vídeos acessados e reproduzidos|
| Contexto | - Local: página "biblioteca"<br/>- Pré-Condição: estar logado em alguma conta<br/>- Pré-Condicão: já ter acessado a algum vídeo |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário abre a aba "biblioteca" na área inferior da tela<br/>2. O usuário clica no botão de "Ver Tudo" na área de histórico |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.16 Cenário 16 - Denunciar um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Denunciar um vídeo |
| Objetivo | Reportar ao sistema que um vídeo pode estar violando alguma diretriz |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário abre as opções do vídeo<br/>3. O usuário seleciona a opção de "Denunciar"<br/>4. O usuário seleciona a razão da denúncia<br/>5. O usuário clica no botão "denunciar" para enviar a denúncia |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.17 Cenário 17 - Minimizar um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Minimizar um vídeo |
| Objetivo | Reduzir o tamanho de um vídeo em reprodução para continuar navegando na plataforma |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta<br/>- Pré-Condição: o vídeo não ser de conteúdo infantil |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário arrasta o vídeo para baixo |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.18 Cenário 18 - Realizar Login
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Realizar Login |
| Objetivo | Ter acesso a mais ferramentas e opções do sistema |
| Contexto | - Local: página de login<br/>- Pré-Condição: ter uma conta no google criada |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica no botão de "fazer login"<br/>2. O usuário preenche suas informações da conta do google |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.19 Cenário 19 - Realizar Logout
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Realizar Logout |
| Objetivo | Não ter mais acesso à conta antes logada |
| Contexto | - Local: página de informação da conta<br/>- Pré-Condição: estar logado em uma conta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica na sua foto de conta na área superior da interface para exibir suas informações<br/>2. O usuário clica no botão "Usar o YouTube sem fazer login" |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.20 Cenário 20 - Ativar legendas de um vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Ativar legendas de um vídeo |
| Objetivo | Assistir um vídeo com legendas |
| Contexto | - Local: página de um vídeo<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica no botão de "CC" (closed captions, inglês para legendas) |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.21 Cenário 21 - Acessar um canal
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acessar um canal |
| Objetivo | Acessar a página inicial de um canal, onde pode-se encontrar vídeos postados por ele |
| Contexto | - Local: página de um vídeo ou página inicial<br/>- Pré-Condição: estar com a página de um vídeo aberta |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica em um vídeo<br/>2. O usuário clica na foto ou nome do canal<br/>3. O usuário clica na foto de um canal de um vídeo na página inicial |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.22 Cenário 22 - Postar vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Postar vídeo |
| Objetivo | Mandar um vídeo disponivel na galeria do celular ao Youtube |
| Contexto | - Local: página inicial do youtube<br/>- Pré-Condição: estar com acesso a internet e com o video salvo na galeria do celular |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica no "+" circulado na pagina principal<br/>2. O usuário seleciona a opção "Enivar um vídeo"<br/>3. O usuário seleciona o vídeo da galeria que quer postar<br/>4. O usuário editar as informações do vídeo, titulo, tags, visibilidade, etc<br/>5. O usuário seleciona se o conteudo é ou não relacionado à crianças<br/>6. O usuário clica em "Enviar um vídeo" |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.23 Cenário 23 - Acessar o seu canal
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acessar o seu canal |
| Objetivo | Acessar o seu canal do Youtube |
| Contexto | - Local: página inicial do youtube<br/>- Pré-Condição: estar com acesso a internet |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário clica na sua foto de perfil na página inicial<br/>2. O usuário seleciona a opção "Seu canal" |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.24 Cenário 24 - Gerenciar vídeos
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Gerenciar vídeos |
| Objetivo | Ter acesso a todos os vídeos já postados |
| Contexto | - Local: página principal do seu canal<br/>- Pré-Condição: estar com acesso a internet |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário acessar o seu canal no Youtube<br/>2. Na página principal o usuário seleciona a opção "Gerenciar vídeos" |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

### 3.25 Cenário 25 - Editar vídeos
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Editar vídeos |
| Objetivo | Editar os vídeos já postados no canal |
| Contexto | - Local: página de gerenciamento de vídeos<br/>- Pré-Condição: estar com acesso a internet |
| Ator(es) | Usuário |
| Recursos | - Dispositivo celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O usuário acessa a página do seu canal<br/>2. O usuário entra na página de gerenciamento de vídeos<br/>3. O usuário seleciona o vídeo que quer editar e clica nos 3 pontinhos ao lado do nome do vídeo selecionado<br/>4. O usuário clica na opção "Editar"<br/>5. O usuário faz as alterações desejadas e clica na opção salvar |
| Exceções | 1. O dispositivo desconectar da internet<br/>2. Acabar a bateria do dispositivo |

## 4. Referências

> - Cenários - Rastreamento de Cenários.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução, metodologia e estrutura de cenários | @victorleaoo | @B3holder2 |
| 1.1    | 17/07/2022 | Adição de cenários relacionados ao usuário (espectador) | @victorleaoo | @B3holder2 |

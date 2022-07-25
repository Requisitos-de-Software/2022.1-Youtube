# Léxicos - Objeto

## 1. Introdução
Trata-se de uma técnica que procura descrever os símbolos de uma linguagem. Tem como principal objetivo a identificação de palavras ou frases peculiares ao meio social da aplicação.(Milene Serrano, Requisitos - Aula 10, página 13).

Os léxicos podem ser dividos em 3 tipos: Estado, Objeto e Verbo. Essa página é dedicada aos **objetos**.

## 2. Metodologia
Após a listagem dos léxicos do tipo objeto identificados pela equipe, eles foram detalhados compondo os seguintes elementos:

- **Nome**: nome do léxico em si.
- **Sinônimos**: palavras ou expressões com significado similar ao léxico.
- **Impacto**: ações que podem ser aplicadas ao objeto.
- **Noção**: definição do objeto e outros com os quais se relaciona.

## 3. Léxicos - Objeto

<div id="banner"></div>

### 3.1 - Banner
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Banner |
| Sinônimos| Capa |
| Impacto  | Um banner pode ser alterado para seguir a identidade visual do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) do usuário |
| Noção    | É a capa do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), onde geralmente fica as informações do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |

<div id="canal"></div>

### 3.2 - Canal
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Canal |
| Sinônimos| Perfil, Armazém de [Vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Impacto  | Um canal pode ser criado, pesquisado, compartilhado e, principalmente, é onde os [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) serão armazenados/postados<br/>Os outros usuários podem ser inscreverem em um canal |
| Noção    | É um tipo de conta visualmente editável em que se pode armazenar conteúdos para que outros usuários possam encontrá-los e consumí-los |

<div id="clipe"></div>

### 3.3 - Clipe
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Clipe |
| Sinônimos| Corte de [Vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Impacto  | Um clipe pode ser compartilhado para outras redes sociais |
| Noção    | Um clipe é um corte de até 60 segundos de uma parte de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |

<div id="comentario"></div>

### 3.4 - Comentário
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Comentário |
| Sinônimos| Opinião |
| Impacto  | Um comentário pode ser curtido por outros usuários ou fixado pelo dono do canal que fez o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Noção    | Uma opinião, análise ou ponderação sobre o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |

<div id="conteudo"></div>

### 3.5 - Conteúdo
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Conteúdo  |
| Sinônimos| Entretenimento, [Vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Impacto  | Todas as interações que são relacionadas a [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video), [Shorts](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#shorts), transmissões, [clipes](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe), entre outros, se referem a um tipo de conteúdo |
| Noção    | Conteúdo seria uma forma abrangente de todos os diferentes tipos de vídeos que podem ser postados ou feitos, englobando [Shorts](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#shorts), vídeos e transmissões ao vivo<br/>Quando se fala em conteúdo, é qualquer meio de entretenimento que pode ser criado |

<div id="criador-conteudo"></div>

### 3.6 - Criador de Conteúdo
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Criador de Conteúdo |
| Sinônimos| Youtuber, Produtor de conteúdo |
| Impacto  | O criador de conteúdo irá criar o [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) e poderá postar vídeos e shorts e também fazer lives  |
| Noção    | É um tipo de usuário que utiliza o aplicativo para postar vídeos e demais conteúdos |

<div id="dispositivo"></div>

### 3.7 - Dispositivo
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Dispositivo |
| Sinônimos| Aparelho |
| Impacto  | O dispositivo irá realizar todas as funcionalidades do aplicativo |
| Noção    | É o aparelho que irá acessar o youtube, e onde o usuário poderá [assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir), [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar), [comentar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#comentar) e avaliar vídeos |

<div id="espectador"></div>

### 3.8 - Espectador
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Espectador |
| Sinônimos| Audiência |
| Impacto  | Um espectador pode se inscrever nos [canais](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) e [assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) aos [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Noção    | É um tipo de usuário que utiliza o aplicativo para [assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |

<div id="fila"></div>

### 3.9 - Fila de Reprodução
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Fila de Reprodução |
| Sinônimos| Em espera |
| Impacto  | [Vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) podem ser adicionados à fila de reprodução para serem executados em ordem |
| Noção    | A fila de reprodução é um conjunto de [cídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que estão em uma ordem para serem reproduzidos |

<div id="historico"></div>

### 3.10 - Histórico
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Histórico |
| Sinônimos| Acessados, Biblioteca de Acessos |
| Impacto  | Um histórico pode ser de [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) assistidos pelo usuário ou de pesquisas realizadas por ele<br/>O histórico pode ser apagado quando desejado |
| Noção    | O histórico seria um tipo de armazenamento dos vídeos/pesquisas que um usuário já acessou |

<div id="interface"></div>

### 3.11 - Interface
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Interface, Página |
| Sinônimos| Tela |
| Impacto  | Uma interface pode interagir e ser interagida<br/>Cliques e botões são elementos que podem ser manipulados em uma interface |
| Noção    | A interface são os elementos que aparecem na tela e como estão distribuídos<br/>Podem ser as páginas de [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video), inicial, [canais](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) etc. |

<div id="legenda"></div>

### 3.12 - Legenda
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Legenda |
| Sinônimos| Descrição em tempo real |
| Impacto  | Uma legenda pode ser ativada ou desativada e também pode ser escolhida o idioma da legenda|
| Noção    | Texto escrito do áudio do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |

<div id="notificacao"></div>

### 3.13 - Notificação
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Notificação |
| Sinônimos| Notícia, Aviso |
| Impacto  | Uma notificação pode ser ativada ou desativada por um usuário em determinado [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Noção    | É um aviso ao usuário que um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) que ele é inscrito postou um conteúdo novo  |

<div id="plataforma"></div>

### 3.14 - Plataforma
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Plataforma |
| Sinônimos| Sistema, Aplicativo |
| Impacto  | Quando é dito funcionalidades da "plataforma", se diz ao o que o aplicativo pode fazer |
| Noção    | É uma forma de representar o aplicativo YouTube |

<div id="playlist"></div>

### 3.15 - Playlist
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Playlist |
| Sinônimos| Lista de reprodução |
| Impacto  | A playlist pode ser compartilhada, criada, e reproduzida na ordem definida ou em ordem aleatória |
| Noção    | Um conjunto de [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que pode ser tocado em uma ordem determinada ou em ordem aleatória |

<div id="privacidade"></div>

### 3.16 - Privacidade
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Privacidade |
| Sinônimos| Segurança |
| Impacto  | A privacidade pode ser pública (para todos), não-listado (restrito) ou privado (somente para o dono) |
| Noção    | É a noção de como os dados estão representados a terceiros |

<div id="qualidade"></div>

### 3.17 - Qualidade
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Qualidade |
| Sinônimos| Resolução |
| Impacto  | A qualidade de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) poderá ser ajustada de acordo com a vontade do usuário, podendo ter um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) com maior ou menor resolução |
| Noção    | A qualidade do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) é a resolução que ele será reproduzido no dispositivo do usuário |

<div id="shorts"></div>

### 3.18 - Shorts
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Shorts |
| Sinônimos| [Vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) Curtos |
| Impacto  | Os Shorts tem sua própria área no aplicativo e podem ser curtido, comentados e compartilhados<br/>Para ver Shorts, basta arrastá-los para baixo para passar para o próximo|
| Noção    | Shorts são um tipo de [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) como se fosse um curto [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) (no máximo 60 segundos) e no formato vertical |

<div id="superchat"></div>

### 3.19 - SuperChat
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | SuperChat |
| Sinônimos| Doação, Chat pago |
| Impacto  | Um superchat pode ser mandado em transmissões ao vivo e pode ser pago o valor que o usuário desejar |
| Noção    | É um tipo de comentário especial em lives em que o usuário pode pagar para ter sua mensagem destacada |

<div id="tag"></div>

### 3.20 - Tag
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Tag |
| Sinônimos| Etiqueta, Palavra-Chave |
| Impacto  | Tags podem ser adicionadas, editadas ou removidas quando desejadas pelo usuário |
| Noção    | São palavras que podem ser adicionadas a um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ou [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) para identificar temas relacionados a eles |

<div id="thumbnail"></div>

### 3.21 - Thumbnail
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Thumbnail |
| Sinônimos| Capa do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Impacto  | Um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) pode ter uma thumbnail personalizada por um usuário ou pode ser uma captura do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Noção    | É a imagem que um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) recebe como capa<br/>Quando o vídeo aparece para um usuário seja pela página inicial ou pesquisa, a thumbnail é a imagem de apresentação do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)|

<div id="usuario"></div>

### 3.22 - Usuário
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Usuário |
| Sinônimos| Cliente, Users |
| Impacto  | Um usuário pode [assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) aos conteúdos, se inscrever nos canais e também pode criar um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) e [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Noção    | Usuário é qualquer um que utiliza o aplicativo e pode ser um espectador ou criador de conteúdos |

<div id="velocidade"></div>

### 3.23 - Velocidade de Reprodução
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Velocidade de Reprodução |
| Sinônimos|           |
| Impacto  | A velocidade de reprodução pode ser ajustada de acordo com a vontade do usuário, podendo acelerar ou retardar o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Noção    | É uma forma do usuário aumentar o diminuir o tempo do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ajustando a velocidade em que ele é reproduzido |

<div id="video"></div>

### 3.24 - Vídeo
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Vídeo     |
| Sinônimos| Gravação |
| Impacto  | Pode ser assistido, avaliado, comentado, denunciado, pausado, resumido, alterado, compartilhado e postado por usuários. |
| Noção    | É um meio de entretenimento que pode tomar diferentes assuntos e formas de produção.<br/>É pertecente a um canal e feito por um [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo). |

## 4. Referências

> - Milene Serrano, Requisitos - Aula 07. Acesso em: 06 de jul. de 2022. Disponível em: Aprender3.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução, metodologia e estrutura de léxico - objetivo | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.1    | 17/07/2022 | Adição sem ordenação de léxicos de objetos e um exemplo de como deve ser feito | <a href="https://github.com/victorleaoo">@victorleaoo</a> <a href="https://github.com/Alef012">@Alef012</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.2    | 17/07/2022 | Léxicos de objetos ordenados | <a href="https://github.com/victorleaoo">@victorleaoo</a> <a href="https://github.com/Alef012">@Alef012</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.3    | 24/07/2022 | Adição de links dos githubs no histórico de versões | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.4    | 24/07/2022 | Correção de erro em que estava léxicos de "verbo" | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.5    | 24/07/2022 | Adição de ID para cada um dos léxicos para que possam ser referenciados em outras páginas | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.6    | 24/07/2022 | Referência de links dos léxicos encontrados na página | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
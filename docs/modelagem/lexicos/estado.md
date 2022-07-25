# Léxicos - Estado

## 1. Introdução
Trata-se de uma técnica que procura descrever os símbolos de uma linguagem. Tem como principal objetivo a identificação de palavras ou frases peculiares ao meio social da aplicação.(Milene Serrano, Requisitos - Aula 10, página 13).

Os léxicos podem ser dividos em 3 tipos: Estado, Objeto e Verbo. Essa página é dedicada aos **estados**.

## 2. Metodologia
Após a listagem dos léxicos do tipo estado identificados pela equipe, eles foram detalhados compondo os seguintes elementos:

- **Nome**: nome do léxico em si.
- **Sinônimos**: palavras ou expressões com significado similar ao léxico.
- **Impacto**: identificar outros estados e ações que podem ocorrer a partir do que se descreve.
- **Noção**: o que significa e quais ações levaram a esse estado.

## 3. Léxicos - Estado

<div id="em-estreia"></div>

### 3.1 - Em Estreia
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Em Estreia |
| Sinônimos| Programado, A ser lançado |
| Impacto  | Um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) em estreia pode ser acompanhado ao vivo durante seu lançamento pelo público<br/>O [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) só estará completamente disponível quando a estreia acabar |
| Noção    | É o estado de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que é programado para ser postado em uma determinada data e horário |

<div id="inscrito"></div>

### 3.2 - Inscrito
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Inscrito |
| Sinônimos| Assinante, Seguidor |
| Impacto  | Um [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) inscrito em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) pode ativar suas notificações<br/>Um [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) inscrito pode ver os [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s recentes postados por um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) na sua aba e "inscrições" |
| Noção    | É o estado em que o [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario), ao se [inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), se torna para o [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |

<div id="logado"></div>

### 3.3 - Logado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Logado |
| Sinônimos| Conectado, Autenticado |
| Impacto  | Um [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) logado pode utilizar de ferramentas e funcionalidades mais sofisticadas no app, como, por exemplo, se [inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), criar e manipular [playlists](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) etc. |
| Noção    | Um [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) que se autentica com os dados de sua conta Google (e-mail e senha) |

<div id="maximizado"></div>

### 3.4 - Maximizado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Maximizado |
| Sinônimos| Aumentado, Expandido |
| Impacto  | Um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video), quando maximizado, é exibido em uma maior parte da tela (podendo ser ela toda)<br/>O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) tem menos autonomia para mexer no aplicativo quando um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) está maximizado |
| Noção    | É quando uma página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) é a tela principal, tomando, assim, boa parte da tela para si|

<div id="minimizado"></div>

### 3.5 - Minimizado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Minimizado |
| Sinônimos| Reduzido, Diminuído |
| Impacto  | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) pode executar outras ações, como pesquisa, acessar [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), [playlists](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist), [históricos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico) etc.<br/>O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) recebe autonomia maior com o aplicativo enquanto ainda assiste a um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)|
| Noção    | É quando um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) está com seu tamanho original reduzido, dando espaço à tela para navegar em outras áreas do aplicativo|

<div id="nao-listado"></div>

### 3.6 - Não-Listado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Não-Listado |
| Sinônimos| Restrito |
| Impacto  | O [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) não pode ser encontrado em buscas<br/>Normalmente, é usado quando se quer hospedar um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo), mas somente para um público restrito conhecido |
| Noção    | Um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) em estado não-listado só pode ser acessado por [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario)s com seu link, uma vez que não é público para buscas |

<div id="pausado"></div>

### 3.7 - Pausado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Pausado |
| Sinônimos| Interrompido, Parado |
| Impacto  | A reprodução do [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) ([vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) e som) param |
| Noção    | É quando um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) em reprodução pode ser interrompido |

<div id="postado"></div>

### 3.8 - Postado
| Elemento | Descrição |
| :------: | :-------- |
| Nome     | Postado |
| Sinônimos| Publicado |
| Impacto  | O [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) postado pode ser assistido, curtido, comentado, compartilhado, salvo em uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist), entre outras funcionalidades |
| Noção    | É quando um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) ([vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ou Shorts) está hospedado na plataforma, podendo, assim, ser visto por outros [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario)s |

## 4. Referências

> - Milene Serrano, Requisitos - Aula 07. Acesso em: 17 de jul. de 2022. Disponível em: Aprender3.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução, metodologia e estrutura de léxico - estado | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.1    | 17/07/2022 | Adição sem ordenação de léxicos de estado e um exemplo de como deve ser feito | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.2    | 18/07/2022 | Descrição de todos os léxicos de estado e ordenação em ordem alfabética | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.3    | 24/07/2022 | Adição de links dos githubs no histórico de versões | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.4    | 24/07/2022 | Correção de erro em que estava léxicos de "verbo" | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.5    | 24/07/2022 | Adição de ID para cada um dos léxicos para que possam ser referenciados em outras páginas | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.6    | 24/07/2022 | Referência de links dos léxicos encontrados na página | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
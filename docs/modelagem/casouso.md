# Casos de Uso

## 1. Introdução
Caso de Uso é uma documentação acerca do comportamento do sistema em desenvolvimento, isto é, o que funcionalmente deve ser fornecido pelo sistema.(Andrey Pimentel, Projeto de Software Usando a UML, página 13).

A partir disso, podem ser criados modelos para ilustar/representar os casos de uso de um sistema.

## 2. Composição de um Diagrama de Casos de Uso
Um Diagrama de Casos de Uso compõe diversos elementos e relacionamentos. Dito isso, é importante entendê-los antes de criar ou até mesmo ver e analisar um diagrama desse tipo.

### 2.1 Elementos
Primeiramente, o diagrama tem 3 elementos gerais que o compõem: atores, casos de uso e sistema.

#### 2.1.1 Atores
Atores representam algo ou alguém que deve interagir com o sistema, sem fazer parte dele.

São representados por um homem palito, como representado na figura 1.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/stickman.png" width="128" height="128"/>

<figcaption>Figura 1: Homem Palito para representar Ator.</figcaption>

</center>

#### 2.1.2 Casos de Uso
Casos de Uso representam a funcionalidade fornecida pelo sistema. Basicamente, é um diálogo entre um ator e o sistema.

São representados por uma figura oval, como representado na figura 2.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/usecase.png" width="128" height="128"/>

<figcaption>Figura 2: Figura oval para representar Caso de Uso.</figcaption>

</center>

#### 2.1.3 Sistema
O sistema, ou limite de sistema, é a delimitação de atuação da aplicação em si.

É representado por uma figura retangular, como representado na figura 3.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/retangulo.png" width="128" height="128"/>

<figcaption>Figura 3: Figura retangular para representar Sistema.</figcaption>

</center>

### 2.2 Relacionamentos
Relacionamentos podem ser estabelecidos entre atores e casos de uso ou entre atores e, basicamente, representam as interações que eles podem ter.

#### 2.2.1 Include
Relacionamentos include são aqueles que ocorrem sempre que o caso de uso base a que se refere for executado.

É representado por uma seta pontilhada direcionada ao caso de uso a ser executado após o base, como representado na figura 4.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/include.png" width="256" height="256"/>

<figcaption>Figura 4: Representação de Relacionamento Include.</figcaption>

</center>

#### 2.2.2 Extend
Relacionamentos extend são aqueles que podem ocorrer quando o caso de uso base a que se refere for executado, não sendo obrigatoriamente sempre executado.

É representado por uma seta pontilhada direcionada para o caso de uso base executado, como representado na figura 5.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/extend.png" width="256" height="256"/>

<figcaption>Figura 5: Representação de Relacionamento Extend.</figcaption>

</center>

## 3. Metodologia
A partir da listagem dos diagramas de caso de uso identificados, o grupo modelou-os e fez suas especificações com as seguintes informações:

- **Descrição**: explicação da funcionalidade representada.
- **Ator**: quem performa a ação.
- **Pré-condições**: condições/requisitos necessários para a realização do caso de uso.
- **Fluxo Principal**: maneira que o ator acessará/utilizará a funcionalidade.
- **Pós-condição**: o que será resultado do caso de uso.

## 4. Diagramas de Caso de Uso

### 4.1 Diagrama 1 - Casos de Uso para o Criador de Conteúdo
A figura 1 apresenta o diagrama de casos de uso para um usuário criador de conteúdo

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/casouso-criador.png"/>

<figcaption>Figura 1: Diagrama de Casos de Uso - Criador de Conteúdo. Autor: Paulo Henrique Almeida.</figcaption>

</center>

#### Caso de Uso 1 - Criar Canal
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar Canal |
| Descrição      | O criador de conteúdo cria um canal, onde postará e armazenará seus vídeos/conteúdos |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Clica na sua foto de perfil<br/>- Entra em "meu canal"<br/>- Preenche foto e nome do canal|
| Pós-condição   | O usuário tem um canal criado|

#### Caso de Uso 2 - Autenticar Usuário
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Autenticar Usuário |
| Descrição      | O usuário autentica suas credenciais de login para poder ter acesso a mais ferramentas |
| Ator           | Usuário |
| Pré-condições  | Ter uma conta Google |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica em "Fazer Login"<br/>- Usuário se autentica com sua conta Google|
| Pós-condição   | O usuário está no estado logado e pode acessar ferramentas antes restritas|

#### Caso de Uso 3 - Postar Conteúdo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Postar Conteúdo |
| Descrição      | A funcionalidade de postar conteúdo, como, por exemplo, um vídeo |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado<br/>- Ter um vídeo armazenado no computador para postar |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica no ícone "+" na área inferior<br/>- Seleciona o envio de vídeo<br/>- Coloca as informações do conteúdo (título, descrição e visibilidade)<br/>- Clica em "postar" |
| Pós-condição   | O usuário terá um conteúdo postado em seu canal |

#### Caso de Uso 4 - Criar Playlists
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar Playlists |
| Descrição      | O usuário executa a ação de criar uma playlist |
| Ator           | Usuário |
| Pré-condições  | - Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre a tela de biblioteca<br/>- Seleciona a opção de "nova playlist"<br/>- Adiciona vídeos à playlist<br/>- Informa o nome e privacidade da playlist<br/>- Clica em "criar playlist" |
| Pós-condição   | O usuário terá uma playlist associada a sua conta criada |

#### Caso de Uso 5 - Excluir Conteúdo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Excluir Conteúdo |
| Descrição      | O usuário exclui um conteúdo postado |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado<br/>- Ter um conteúdo postado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre a aba de gerenciamento de vídeos<br/>- Abre o menu de um vídeo representado por um ícone de "3 pontos verticais"<br/>- Seleciona o botão de excluir<br/>- Confirma a remoção do vídeo |
| Pós-condição   | O usuário terá seu conteúdo antes postado, agora deletado |

#### Caso de Uso 6 - Ver estatísticas do conteúdo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Ver estatísticas do conteúdo |
| Descrição      | O usuário tem a funcionalidade de ver as estatísticas e dados de um conteúdo postsado |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado<br/>- Ter um conteúdo postado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre a tela de seu canal<br/>- Usuário abre a aba de estatísticas |
| Pós-condição   | O usuário terá acesso às estatísticas de seus conteúdos postados |

#### Caso de Uso 7 - Editar informações do conteúdo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Editar informações do conteúdo |
| Descrição      | O usuário executa a funcionalidade de alterar informações de um conteúdo já postado |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado<br/>- Ter um conteúdo postado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre a aba de gerenciamento de vídeos<br/>- Abre o menu de um vídeo representado por um ícone de "3 pontos verticais"<br/>- Seleciona o botão de editar<br/>- Faz as edições desejadas no conteúdo<br/>- Clica em "salvar" |
| Pós-condição   | O usuário terá as informações de um conteúdo já postado alteradas |

#### Caso de Uso 8 - Adicionar Thumbnail
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Adicionar Thumbnail |
| Descrição      | Um conteúdo pode ter uma thumbnail (imagem de apresentação do vídeo) adicionada a ele |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado<br/>- Ter um conteúdo postado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre a aba de gerenciamento de vídeos<br/>- Abre o menu de um vídeo representado por um ícone de "3 pontos verticais"<br/>- Seleciona o botão de editar<br/>- Clica no ícone de adicionar imagem ao vídeo<br/>- Clica em "salvar" |
| Pós-condição   | O usuário terá uma imagem inicial (thumbnail) relacionada a ele |

#### Caso de Uso 9 - Fazer transmissão ao vivo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Fazer transmissão ao vivo |
| Descrição      | O usuário pode fazer uma transmissão ao vivo na plataforma |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica no ícone "+" na área inferior<br/>- Seleciona a opção de "transmissão ao vivo"<br/>- Coloca as informações da transmissão<br/>- Clica em "iniciar transmissão" |
| Pós-condição   | O usuário estará realizando uma transmissão ao vivo no seu canal|

#### Caso de Uso 10 - Postar Shorts
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Postar Shorts |
| Descrição      | O usuário pode postar um tipo de vídeo de até 60 segundos e de forma vertical |
| Ator           | Usuário Criador de Conteúdo |
| Pré-condições  | - Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica no ícone "+" na área inferior<br/>- Seleciona a opção de "criar um short"<br/>- Seleciona um clipe<br/>- Clica em "concluído"<br/>- Adiciona as informações do shorts<br/>- Clica em "postar" |
| Pós-condição   | O usuário um Shorts postado no seu canal |

### 4.2 Diagrama 2 - Casos de Uso para o espectador
A figura 2 apresenta o diagrama de casos de uso para um espectador (usuário regular do sistema)

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/casouso-espectador.png"/>

<figcaption>Figura 2: Diagrama de Casos de Uso - Espectador. Autor: Paulo Henrique Almeida.</figcaption>

</center>

#### Caso de Uso 1 - Criar Canal
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar Canal |
| Descrição      | O espectador cria um canal, onde poderá postar e armazenar seus vídeos/conteúdos |
| Ator           | Usuário Espectador |
| Pré-condições  | Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Clica na sua foto de perfil<br/>- Entra em "meu canal"<br/>- Preenche foto e nome do canal |
| Pós-condição   | O usuário tem um canal criado |

#### Caso de Uso 2 - Inscrever em Canal
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Inscrever em Canal |
| Descrição      | O espectador se inscreve em um canal, por onde poderá acompanhar/consumir os conteúdo que estão sendo postados |
| Ator           | Usuário Espectador |
| Pré-condições  | Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Clica no ícone/nome do canal que deseja se inscrever <br/>- Clica em "inscrever-se"<br/>|
| Pós-condição   | O usuário está inscrito no canal |

#### Caso de Uso 3 - Autenticar Usuário
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Autenticar Usuário |
| Descrição      | O usuário autentica suas credenciais de login para poder ter acesso a mais ferramentas |
| Ator           | Usuário |
| Pré-condições  | Ter uma conta Google |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica em "Fazer Login"<br/>- Usuário se autentica com sua conta Google |
| Pós-condição   | O usuário está no estado logado e pode acessar ferramentas antes restritas |

#### Caso de Uso 4 - Consumir Conteúdo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Consumir Conteúdo |
| Descrição      | O usuário consome/assiste os conteúdos/vídeos que estão postados no sistema |
| Ator           | Usuário Espectador |
| Pré-condições  | Abrir o aplicativo |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica em um card de vídeo<br/>- Usuário consome o vídeo |
| Pós-condição   | O usuário consimiu/assistiu um conteúdo |

#### Caso de Uso 5 - Pesquisar Conteúdo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Pesquisar Conteúdo |
| Descrição      | O usuário pesquisa por um conteúdo/vídeo que foi postados no sistema |
| Ator           | Usuário Espectador |
| Pré-condições  | Abrir o aplicativo |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário clica na ferramenta de pesquisa<br/>- Usuário digita título de conteúdo/vídeo que deseja consumir<br/>- Usuário clica em buscar |
| Pós-condição   | O sistema disponibilzia ao usuário o conteúdo desejado/relacionado na pesquisa |

#### Caso de Uso 6 - Criar Playlists
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar Playlists |
| Descrição      | O usuário cria uma lista de conteúdos/vídeos que deseja consumir |
| Ator           | Usuário |
| Pré-condições  | - Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre a tela de biblioteca<br/>- Seleciona a opção de "nova playlist"<br/>- Adiciona vídeos à playlist<br/>- Informa o nome e privacidade da playlist<br/>- Clica em "criar playlist" |
| Pós-condição   | O usuário terá uma playlist associada a sua conta criada |

#### Caso de Uso 7 - Avaliar
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Avaliar |
| Descrição      | O usuário avalia (positivamente ou negativamente) conteúdos/vídeos consumidos |
| Ator           | Usuário Espectador |
| Pré-condições  | - Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre um vídeo<br/>- Usuário clica no joinha para avaliar positivamente ou no joinha invertido para avaliar negativamente <br/> |
| Pós-condição   | O usuário terá avaliado um vídeo |

#### Caso de Uso 8 - Comentar
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Comentar |
| Descrição      | O usuário comenta conteúdos/vídeos consumidos |
| Ator           | Usuário Espectador |
| Pré-condições  | - Estar logado/autenticado |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre um vídeo<br/>- Usuário clica em comentários<br/>- Usuário clica em "Adicione um comentário..."</br>- Usuário digita um comentário e clica na seta à direita para postar comentário |
| Pós-condição   | O usuário terá comentado um vídeo |

#### Caso de Uso 9 - Compartilhar
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Compartilhar |
| Descrição      | O usuário compartilha conteúdos/vídeos consumidos |
| Ator           | Usuário Espectador |
| Pré-condições  | - Estar com um vídeo aberto |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre um vídeo<br/>- Usuário clica em compartilhar<br/>- Usuário seleciona a forma que deseja compartilhar o vídeo</br>- Usuário possuirá o link do vídeo ou terá compartilhado o vídeo em alguma rede social |
| Pós-condição   | O usuário terá compartilhado um vídeo |

#### Caso de Uso 10 - Alterar velocidade e Qualidade do vídeo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Alterar velocidade e Qualidade do vídeo |
| Descrição      | O usuário poderá alterar a velocidade do vídeo, deixando-o mais lento ou mais rápido, e também poderá alterar a qualidade do vídeo deixando-o com menor ou maior resolução |
| Ator           | Usuário Espectador |
| Pré-condições  | - Estar com um vídeo aberto |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre um vídeo<br/>- Usuário clica nos três pontinhos no canto superior direito do vídeo<br/>- Usuário clica em "Velocidade de reprodução" ou "Qualidade"</br>- Usuário seleciona a velocidade de reprodução ou qualidade desejada |
| Pós-condição   | O vídeo aberto estará na Velocidade de reprodução ou qualidade desejada |

#### Caso de Uso 11 - Ver legendas
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Ver legendas |
| Descrição      | O usuário poderá consumir o conteúdo/vídeo com legendas |
| Ator           | Usuário Espectador |
| Pré-condições  | - Estar com um vídeo aberto |
| Fluxo Principal| - Usuário abre o aplicativo<br/>- Usuário abre um vídeo<br/>- Usuário clica nos três pontinhos no canto superior direito do vídeo<br/>- Usuário clica em "Legendas"</br>- Usuário seleciona o idioma de legenda desejado |
| Pós-condição   | O vídeo aberto estará legendado no idioma escolhido |

## 5. Referências

> - Andrey Pimentel, Projeto de Software Usando a UML. Julho de 2007.

## 6. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução e composição de um diagrama de caso de uso. | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.1    | 19/07/2022 | Adição do diagrama e das descrições dos casos de uso para um usuário criador de conteúdo. | <a href="https://github.com/victorleaoo">@victorleaoo</a>, <a href="https://github.com/owhenrique">@owhenrique</a> | <a href="https://github.com/B3holder2">@B3holder2</a> |
| 1.2    | 19/07/2022 | Adição do diagrama e das descrições dos casos de uso para um usuário espectador. | <a href="https://github.com/owhenrique">@owhenrique</a>, <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/Alef012">@Alef012</a> |
| 1.3    | 24/07/2022 | Adição de links dos githubs no histórico de versões | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
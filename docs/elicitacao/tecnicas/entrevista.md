# Entrevista

## 1. Introdução
A entrevista é uma das técnicas mais utilizadas de coleta de dados e levantamento de requisitos. Trata-se de uma conversa guiada por um roteiro de perguntas ou tópicos, na qual um entrevistador busca obter informação de um entrevistado (Seidman, 2019).

A entrevista tem como vantagens:

- Permitir coletar muitas informações dos [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario)s individualmente.
- Ser flexível: permite fazer perguntas de follow-up e se aprofundar mais do que questionários ou grupos de foco.
(Simone Diniz, Interação Humano-Computador. - Cáp. 7, páginas 143, 144)

## 2. Metodologia
A partir de um roteiro de perguntas, um participante do grupo entrevistou um [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) do aplicativo YouTube. O roteiro foi o seguinte:

- Para o que você usa o Youtube?
- O que você gosta no Youtube?
- Quando você usa o Youtube?
- Por que você usa o Youtube?
- Como você usa o Youtube?
- Você gosta do Youtube? O que você acha de bom nele?
- E o que acha de ruim ou que poderia melhorar?
- O que você espera de recurso no que convém ao utilizar o app como um espectador (assistir [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video))?
- O que você esperaria do app caso fosse um [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) ([postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video))?
- Caso você fosse o criador do youtube o que você adicionaria?
- Acerca do design do app, teria algo que mudaria? Alguma funcionalidade nova?

A partir das respostas do [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario), foram elicitados requisitos que já são implementados no aplicativo e alguns outros que podem vir a serem.

[Áudio da Entrevista](https://user-images.githubusercontent.com/33530818/178569542-d2e32903-021d-424a-bdd0-fb63df893b2f.mp4)

## 3. Participantes

- Carlos Daniel (@CDGodoy): Entrevistador
- João Gabriel: Entrevistado

## 4. Resultados
### 4.1 Requisitos Funcionais
| ID    | Requisito |
| :-:   | :-------- |
| RFE01 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de assistir [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| RFE02 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder ouvir músicas pelo aplicativo |
| RFE03 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder pesquisar por [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| RFE04 | O [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) deve ser capaz de [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| RFE05 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder seguir/[inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) a um [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| RFE06 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de ativar [notificações](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#notificacao) para os [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) a serem criados por um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| RFE07 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder criar uma conta para acessar seus [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) em diferentes plataformas |
| RFE08 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de pular propagandas que vem a aparecer em [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| RFE09 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder encontrar novos [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ao navegar pela interface |
| RFE10 | O sistema deve mostrar ao [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) todas as ferramentas disponíveis a ele |

### 4.2 Requisitos Não-Funcionais
| ID     | Requisito | 
| :-:    | :-------- |
| RNFE01 | O sistema deve recomendar [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) para o [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| RNFE02 | O sistema deve dar apoio para [criadores de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| RNFE03 | O sistema deve estar disponível para a maioria dos dispositivos móveis, como, por exemplo, os que são Android ou iOS |
| RNFE04 | O sistema deve proporcionar a integração entre plataformas |
| RNFE05 | O sistema deve ter um design direcionado aos [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) (praticidade) |
| RNFE06 | O sistema deve oferecer um modo escuro para o aplicativo |

## 5. Referências
> - Simone Diniz, Interação Humano-Computador. São Paulo, 1a Edição, Elsevier, 2010.

## 6. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 06/07/2002 | Criação do esqueleto do documento e introdução inicial. | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.1    | 12/07/2002 | Adição da entrevista + requisitos elicitados por ela. | <a href="https://github.com/victorleaoo">@victorleaoo</a>, <a href="https://github.com/CDGodoy">@CDGodoy</a> | <a href="https://github.com/owhenrique">@owhenrique</a>, <a href="https://github.com/lramon2001">@lramon2001</a> |
| 1.2    | 24/07/2022 | Adição de links dos githubs no histórico de versões | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
| 1.3    | 24/07/2022 | Referência de links dos léxicos encontrados na página | <a href="https://github.com/victorleaoo">@victorleaoo</a> | <a href="https://github.com/owhenrique">@owhenrique</a> |
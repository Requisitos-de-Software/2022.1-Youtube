# NFR Framework

## 1. Introdução
<p align="justify">&emsp;&emsp;"O framework NFR é um método de expressar e analisar requisitos não funcionais. Seu objetivo é ajudar os desenvolvedores a implementar soluções customizadas, levando em consideração as características do domínio e sistema. Essas características incluem requisitos não-funcionais, requisitos funcionais, prioridades e carga de trabalho. Esses fatores determinam a escolha de alternativas de desenvolvimento para um determinado sistema (CHUNG et al., 2000)."(SILVA, 2019, p. 30)</p>

<p align="justify">&emsp;&emsp;Eles estão relacionados ao comportamento do sistema e não à sua função, porque descrevem como o sistema funciona. Eles são geralmente representados por gráficos Softgoal Interdependency (SIG), que descrevem as dependências entre softgoals e como eles são esquadrinhados. Sendo um Softgoal uma unidade básica que representa o requisito não-funcional, visando saber se ele será cumprido (implementado) ou não.</p>

## 2. Metodologia 
<p align="justify">&emsp;&emsp; A partir da definição do NFR Framework, a equipe seguiu a representação usando SIGs para a implementação da ferramenta. A seguir, encontra-se a legenda dos elementos encontrados no desenvolvimento do documento:</p>

- **Softgoals**: eles podem ser representados de 3 formas diferentes dependendo de sua característica para uso. A figura 1 mostra os 3 tipos possíveis.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/nfr/tipos-soft.png" width="256" height="256"/>

<figcaption>Figura 1: Tipos de Softgoals.</figcaption>

</center>

- **Interdependências**: as relações entre os softgoals podem ser divididas em 4 tipos diferentes de decomposição. A figura 2 as explana.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/nfr/tipos-inter.png"/>

<figcaption>Figura 2: Tipos de Interdependências.</figcaption>

</center>

- **Contribuições**: a fim de descrever a satisfação de um softgoal descendente em relação a um ascendente, podem ser usadas algumas contribuições. No projeto serão usadas duas:

<p align="justify">&emsp;&emsp; AND: Os softgoals ascendentes só são satifeitos se os descendentes também forem.</p>
<p align="justify">&emsp;&emsp; OR: Se algum softgoal descendente for satisfeito, o ascendente também já será satisfeito.</p>

- **Procedimento de avaliação**: para determinar o grau de satisfação de um requisito não-funcional, algumas legendas podem ser usadas. A figura 3 mostra as usadas no projeto:

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/nfr/tipos-prod.png"/>

<figcaption>Figura 3: Tipos de Procedimentos de Avaliação.</figcaption>

</center>

## 3. NFR Framework

## 4. Referências
> - CHUNG, Lawrence; NIXON, Brian. Nixon, YU, Eric; MYLOPOULOS, John. "Non-Functional Requirements in Software Engineering". Springer US, 2000.
> - SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 28/07/2022 | Criação da primeira versão do documento com a introdução e referências | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.1    | 28/07/2022 | Adição da metodologia a ser utilizada no NFR Framework do projeto | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
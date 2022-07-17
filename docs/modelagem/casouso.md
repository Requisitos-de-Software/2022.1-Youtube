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

### 4.1 Diagrama 1 - Nome

Diagrama 1 - 

| Informação     |           |
| :--------:     | :-------  |
| Descrição      |           |
| Ator           |           |
| Pré-condições  |           |
| Fluxo Principal|           |
| Pós-condição   |           |

## 5. Referências

> - Andrey Pimentel, Projeto de Software Usando a UML. Julho de 2007.

## 6. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2002 | Criação da primeira versão do documento com a introdução e composição de um diagrama de caso de uso. | @victorleaoo | @owhenrique |
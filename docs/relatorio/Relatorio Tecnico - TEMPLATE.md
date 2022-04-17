# Informações do Projeto
`TÍTULO DO PROJETO`  

Negare

`CURSO` 

Ciência da Computação

## Participantes


> Inclua a lista dos membros da equipe com seus nomes completos.
>
> Os membros do grupo são: 
> - Diogo Henrique de Souza Costa
> - Iago Nathan Baruc Soares Silva
> - Lucca Cenisio Martins
> - Matheus Antônio de Lima Sinis
> - Vitória de Lourdes Carvalho Santos

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

“Negare” é uma plataforma para discussões a respeito das notícias lidas na internet através de um fórum, a fim de verificar sua veracidade, levando as notícias da forma mais leve possível. Além disso, o site ajuda os leitores a identificar notícias falsas através de elementos apresentados nas mesmas. 

## Problema

O compartilhamento de notícias falsas pode causar grandes problemas, pois leva um compartilhamento em massa de desinformação, levando as pessoas a acreditarem na notícia sem se preocuparem se é verdadeira ou não, ficando cada vez mais difícil repassar  à informação correta. Dessa forma, as pessoas se tornam facilmente manipuláveis por pessoas má intencionadas.




## Objetivos

Objetivo Geral :
Reduzir a propação de fake news.

Objetivo específico:
A ideia do projeto é desenvolver um site acessível a público aberto com suporte a postagem de notícias para análise dos próprios usuários. A postagem é feita a partir de um portal ao estilo fórum e, assim que estiver publicada, estará disponível para análise popular. Em uma sessão de comentários dedicados, os usuários poderão discutir sobre a veracidade da notícia e suas fontes, contribuindo com fontes que argumentam contra ou a favor da notícia em discussão.



## Justificativa

Devido ao impacto das fake news em diversas áreas sociais, como na política e no meio científico, muitas pessoas estão tendo acesso à notícias falsas que são produzidas por pessoas mal intencionadas que de alguma forma deseja manipular essa informação para o seu próprio bem, gerando desinformação em massa. Por isso, desenvolvemos um site que visa reduzir a propagação de fake news para todas as pessoas que têm acesso à informações e notícias no seu dia a dia em redes sociais.




## Público-Alvo

Homens e mulheres de todas as idades, que são brasileiros, estão sempre à procura de saber a verdade e que gostam de combater a fake news.
Não temos um público principal, é uma plataforma aberta e acessível para brasileiros de todas as idades comprometidos com a verdade e que gostam de combater as fake news.
Em especial, visamos também a parcela populacional como menos acesso à informação pois, percebe-se nela assim como nas pessoas idosas, uma maior suscetibilidade à notícias falsas. Um agravante no caso dos idosos é a comum barreira do conhecimento tecnológico, deixando-os desprotegidos enquanto navegam pela internet.



 
# Especificações do Projeto

O projeto utilizou técnicas para alinhar o problema dos usuários e mapear como o problema pode ser resolvido, com a criação de personas e mapa de empatia pra entender o problema do usuario. As outras técnicas utilizadas são apresentadas a seguir no resto da documentação.


## Personas e Mapas de Empatia

![PMGCC-M - T1-G6 - Fake News 2](https://user-images.githubusercontent.com/101272856/163691378-a9ec6546-deb1-45f5-8aba-bdc1cc8f0c3f.jpg)

![PMGCC-M - T1-G6 - Fake News 2 (1)](https://user-images.githubusercontent.com/101272856/163691388-4e69cf9f-e1a8-4a1e-9c68-1cb3213dd56f.jpg)

![PMGCC-M - T1-G6 - Fake News 2 (2)](https://user-images.githubusercontent.com/101272856/163691405-a685e548-1688-4bb3-b6d3-9fbff6b3cd82.jpg)

![PMGCC-M - T1-G6 - Fake News 2 (3)](https://user-images.githubusercontent.com/101272856/163691413-274b5afa-a8be-47f6-aa8e-8bb25eb82f53.jpg)

![PMGCC-M - T1-G6 - Fake News 2 (4)](https://user-images.githubusercontent.com/101272856/163691429-4efe9836-db42-4cd3-94d8-0ae41c10c70c.jpg)

![PMGCC-M - T1-G6 - Fake News 2 (5)](https://user-images.githubusercontent.com/101272856/163691438-47f1c925-ad3d-4013-b3b6-63248b66ddaf.jpg)



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Ler notícias verdadeiras                         | Me manter informado      |
|Usuário do sistema  | Descobrir se determinada noticia é verdadeira    | Ter certeza que estou me informando corretamente |
|Usuário do sistema  | Descobrir como identificar se uma notícia é falsa| Não acreditar em todas as notícias que eu vejo sem antes analisá-las|
|Usuário do sistema  | Debater sobre a veracidade de notícias           | Para aprender a entender como outras pessoas entendem que uma notícia é falsa|
|Usuário do sistema  | Diminuir a propagação de fake news               | Que haja menos pessoas desinformadas      |
|Usuário do sistema  | Fácil acesso a notícias                                  | Me manter informado      |



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Sistema de login e criação de contas | MÉDIA | 
|RF-002| Perfil do usuário   | MÉDIA |
|RF-003| Deve ser possível publicar novas notícias em um fórum.| ALTA |
|RF-004| Comentário em notícias publicadas do fórum| ALTA |
|RF-005| Avaliar comentários de outros usuários nos fóruns de notícia | BAIXA |
|RF-006| Feed de notícias | ALTA |
|RF-007| Aba com dicas sobre as características comuns de notícias falsas| ALTA |
|RF-008| Aba que indica sites com tendências mais ou menos confiáveis | ALTA |
|RF-009| Avaliar a veracidade de uma notícia com base nos comentários que ela recebeu | ALTA |
|RF-010| Sistema de reputação de conta dos usuários. | BAIXA |
|RF-011| Resumo sobre as discussões de uma notícia, para verificação rápida das informações mais relevantes. | BAIXA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Linguagem - Html/ CSS e Javascript | ALTA | 
|RNF-002| Banco de dados -  FireBase |  ALTA |
|RNF-003| Plataforma - Web | ALTA |



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| Falta de conhecimento de todas as funções da linguagem|
|02| Falta de recursos financeiros para contratação de softwares avançados|
|03| O prazo do projeto pode ser curto para a execução de todas as ideias e o custo do projeto pode ser caro por precisar de ferramentas pagas, por exemplo o FireBase que tem sua parte gratuita mas talvez não seja suficiente pelo tamanho do projeto|


# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

![Tela principal](https://user-images.githubusercontent.com/101272856/163691511-9854dd07-772c-4251-9977-088eace48184.png)
  Tela principal de quando o usuário abre o site sem fazer o login
  
![Cadastro](https://user-images.githubusercontent.com/101272856/163691535-5ca77d59-b5f6-4f64-9bad-24e20b304a9c.png)
  Tela de cadastro


![Tela principal logado](https://user-images.githubusercontent.com/101272856/163691522-cb2aef24-17ea-4257-88bb-112f62884251.png)
  Após fazer o login
  
![Tela principal logado-1](https://user-images.githubusercontent.com/101272856/163691527-ad90c61c-6aaa-4ef9-86e9-e31cb27fedc4.png)
  Tela principal com cadastro

![dicas](https://user-images.githubusercontent.com/101272856/163691537-289c1e75-b640-43b5-a45e-b7d45cefa7e8.png)
  Tela sobre dicas de como descobrir se uma notícia é falsa

![Nossas notícias](https://user-images.githubusercontent.com/101272856/163691539-5f4d50f0-bc37-4417-a5de-0e948880a159.png)
  Notícias postadas pelos administradores

![Postagem Usuario](https://user-images.githubusercontent.com/101272856/163691540-4f4fb805-b93c-40ff-b7ba-46651acd592e.png)
  

![Postagem](https://user-images.githubusercontent.com/101272856/163691541-f772c3c4-9951-43ab-8065-d28c2ce50266.png)

![Sites confiaveis](https://user-images.githubusercontent.com/101272856/163691542-48747cc7-b421-4eb9-b6bd-212c4bd0e5ca.png)
  Aba sobre sites confiáveis





# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis
A divisão dos papéis foi feita através do trello usando a metodologia scrum.
https://trello.com/invite/b/RPSIdZu9/37e07c28d40b155be6af5ba82588bfe1/fake-news



## Ferramentas

As ferramentas escolhidas estão listadas abaixo e o motivo da escolha de cada uma é principalmente a praticidade de cada uma delas e a possibilidade de realização do trabalho em conjunto.

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVOB6_Ecc=/ | 
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-tiaw-fake-news-2.git | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://www.figma.com/file/1eYS0inTR6MyvqIXkXx6FS/Untitled?node-id=0%3A1 | 
|Editor de código| Visual Studio Code | 
|Ferramentas de comunicação| Discord e Whatsapp |

>
>

## Controle de Versão

O controle de versão foi feito através do repositório do GITHUB

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)

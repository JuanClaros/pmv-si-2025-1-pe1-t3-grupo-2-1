# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto.

Caso deseje atribuir uma imagem a sua persona, utilize o site https://thispersondoesnotexist.com/

## Personas
### Persona 1: João, 8 anos - O Jovem Colecionador 
- **Idade**: 8 anos
- **Profissão**: Estudante
- **Interesses**: Coleciona bonecos de ação, figuras de heróis e personagens de filmes.
- **Desafios**: Tem dificuldade em lembrar quais bonecos já possui e quais ainda quer adquirir. Muitas vezes, acaba pedindo itens repetidos aos pais.
- **Necessidade**: Uma forma fácil e divertida de catalogar e visualizar sua coleção, com imagens e descrições.

### Persona 2: Dona Maria, 72 anos - A Idosa Organizada
- **Idade**: 72 anos
- **Profissão**: Aposentada
- **Interesses**: Leitura de livros, DVDs de filmes clássicos, cartas e fotos de família.
- **Desafios**: Esquece quais títulos já leu ou assistiu e tem dificuldade para organizar seus itens.
- **Necessidade**: Um sistema simples e intuitivo para registrar e consultar sua coleção, ajudando a evitar compras duplicadas e a acessar facilmente seus pertences.

### Persona 3: Lucas, 35 anos - O Pai Atento
- **Idade**: 35 anos
- **Profissão**: Executivo
- **Interesses**: Organizar a casa, coleções de cards esportivos e itens de quadrinhos.
- **Desafios**: Com a rotina agitada, não tem tempo de manter um registro detalhado de sua coleção e, por vezes, compra itens repetidos.
- **Necessidade**: Uma solução prática e eficiente para cadastrar e acessar rapidamente seu acervo pessoal, garantindo melhor gestão do espaço e do orçamento.

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|---------------------|------------------------------------|----------------------------------------|
|Usuário da aplicação | Registrar itens do meu acervo      | Me lembrar e gerenciar quais itens possuo
|Usuário da aplicação | Verificar a existência de um item dentro do meu acervo | Identificar se já possuo este item
|Usuário da aplicação | Registrar itens que ainda não possuo em uma lista de desejo | Me auxiliar em momentos em que tenho oportunidade de aumentar meu acervo
|Usuário da aplicação | Compartilhar/exportar a lista de meu acervo | Me auxiliar em momentos de troca ou venda
|Usuário da aplicação | Classificar meus itens de acordo com suas características(valor, estado de conservação, etc) | Me auxiliar a organizar minha coleção

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----| 
| RF-001 | Permitir que usuários criem suas próprias coleções | ALTO  |
| RF-002 | Permitir que usuários excluam suas próprias coleções | ALTO  |
| RF-003 | Permitir que usuários alterem suas próprias coleções | ALTO  |
| RF-004 | Categorizar suas próprias coleções | ALTO  |
| RF-005 | Adicionar itens desejados a sua coleção | MEDIO  |
| RF-006 | Emprestar itens da coleção para outro usuário	 | MEDIO  |
| RF-007 | Realizar cadastro no sistema | ALTO  |
| RF-008 | Realização de login no sistema | ALTO  |
| RF-009 | Realização de alteração de dados pessoais | ALTO  |
| RF-010 | Criação de subgrupos dentro de suas coleções | ALTO  |
| RF-011 | Histórico de empréstimos | MEDIO  |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

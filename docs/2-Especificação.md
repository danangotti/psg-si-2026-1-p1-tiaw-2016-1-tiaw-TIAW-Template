# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas

Persona 1 — Maria da Silva

Maria da Silva tem 45 anos, é costureira autônoma e mora em uma área de risco sujeita a enchentes. Passa a maior parte do tempo em casa, onde trabalha e cuida da família. É uma pessoa batalhadora, protetora e muito conectada com os vizinhos, porém fica ansiosa durante períodos de chuvas fortes.

Utiliza principalmente o celular (WhatsApp), além de televisão e rádio quando possível. Seu principal objetivo é receber alertas antecipados para saber o momento certo de agir, protegendo sua família e seus bens.

Maria tem dificuldade com termos técnicos e não confia em informações desencontradas ou fake news. Prefere orientações simples, diretas e confiáveis.

Persona 2 — João Carlos

João Carlos tem 38 anos, trabalha como motorista e também mora em uma região vulnerável a alagamentos. Passa grande parte do dia fora de casa, mas se preocupa constantemente com a segurança da família.

Utiliza o celular com frequência e busca informações rápidas e objetivas. Em situações de emergência, precisa tomar decisões rápidas, como escolher rotas seguras ou avisar familiares.

João valoriza praticidade e confiabilidade, e sente dificuldade quando as informações são confusas ou chegam tarde demais.

> Enumere e detalhe as personas da sua solução. Para
> tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e
> personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

 EU COMO...                      | QUERO/PRECISO ... (FUNCIONALIDADE)            | PARA ... (MOTIVO/VALOR)               |
| ------------------------------- | --------------------------------------------- | ------------------------------------- |
| Moradora de área de risco       | Receber alertas no celular antes de desastres | Ter tempo de proteger minha família   |
| Usuária do sistema              | Visualizar rotas de fuga seguras              | Saber para onde ir em emergências     |
| Moradora do bairro              | Receber informações simples e claras          | Não ficar confusa com termos técnicos |
| Mãe de família                  | Avisar meus familiares rapidamente            | Garantir que todos estejam seguros    |
| Usuária                         | Localizar abrigos próximos                    | Me proteger em caso de enchente       |
| Pessoa preocupada com segurança | Receber informações confiáveis                | Não cair em fake news                 |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais
>   (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais
>   (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

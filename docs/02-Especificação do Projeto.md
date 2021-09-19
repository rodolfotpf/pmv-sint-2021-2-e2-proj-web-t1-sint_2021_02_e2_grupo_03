# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

## Personas

Marcelo tem 42 anos, é formado em administração de empresas e é gerente de um supermercado. Está em busca de um sistema para gerenciar o controle de estacionamento. 

Paulo tem 33 anos, é empresário e trabalha terceirizando serviços de estacionamentos. E está em busca de um software que visa controle, praticidade e facilidade no dia a dia de um negocio de estacionamentos, tendo um controle maior irá auxiliar no momento em que fizer propostas comerciais. 



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`          |PARA ... `MOTIVO/VALOR`                      |
|--------------------|---------------------------------------------|---------------------------------------------|
|Eu como Marcelo     | Registrar a horas dos veículos estacionados | Para ter o controle diário                  |
|Eu como Marcelo     | Registrar o veículo                         | Para ter o controle diário                  |
|Eu como Paulo       | Preciso cadastrar o valor por hora          | Para fazer a cobrança                       |
|Eu como Paulo       | gerar relatórios ao fim do dia              | Para administrar contas                     |
|Eu como Marcelo     | Cadastrar o veículo                         | Para fazer a cobrança                       |
|Eu como Paulo       | Preciso de uma lista de todas as vagas      | Para ter controle de vagas ocupadas e vazias|



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                                          | Prioridade |
|------|-----------------------------------------------------------------|------------|
|RF-001| Permitir que o usuário cadastre veículo e a hora                | ALTA       | 
|RF-002| Permitir que o usuário faça consultas de vagas ocupadas e vazias| MÉDIA      |
|RF-003| Permitir que o usuário cadastre o valor hora                    | ALTA       |
|RF-004| Permitir que o usuário cadastre o total de vagas                | MÉDIA      |



### Requisitos não Funcionais

|ID     | Descrição do Requisito                                |Prioridade |
|-------|-------------------------------------------------------|-----------|
|RNF-001| O sistema deve Layout amigavél                        | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 5s |  BAIXA    | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                   |
|--|---------------------------------------------|
|01| Primeira versão será lançada apenas Web     |



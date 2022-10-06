# DOCUMENTO DE VISÃO - SIAGEN

## Sumário

- [DOCUMENTO DE VISÃO - SIAGEN](#documento-de-visão---siagen)
  - [Sumário](#sumário)
  - [Introdução](#introdução)
  - [Posicionamento](#posicionamento)
    - [Declaração do problema](#declaração-do-problema)
    - [Declaração da posição do produto](#declaração-da-posição-do-produto)
  - [Declaração das partes interessadas](#declaração-das-partes-interessadas)
    - [Resumo das partes interessadas](#resumo-das-partes-interessadas)
    - [Ambiente do usuário](#ambiente-do-usuário)
  - [Visão geral do produto](#visão-geral-do-produto)
    - [Necessidades e recursos](#necessidades-e-recursos)
  - [Outros requisitos do produto](#outros-requisitos-do-produto)
  - [Requisitos funcionais](#requisitos-funcionais)
    - [Especificação de casos de uso](#especificação-de-casos-de-uso)
      - [Caso de uso Manter Viagem – Emanuel Costa](#caso-de-uso-manter-voluntario--mateus-pereira)
  - [Tabela dos riscos](#tabela-dos-risco)
  - [Lista de regras de negócio](#lista-de-regras-de-negócio)

## Introdução

O Siagen é um sistema web que tem como objetivo, automatizar a organização dos transportes; controle de vagas por veículo; 
consultar disponibilidade de vagas, entre outros. Otimizando a organização de viagens diárias realizadas com os pacientes 
para fora do município.

## Posicionamento

### Declaração do problema

|                              |                                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------- |
| O problema de                | Processo manual, lento e dependente de várias etapas de organização                                 |
| Afeta                        | Paciente que utilizam os serviços da Secretaria Municipal de Saúde (SMS).                           |
| No qual o impacto é          | Lentidão na organização das viagens, disponibilidade de vagas e comunicação entre os setores da SMS.|
| Uma solução de sucesso seria | A implatação e adesão do sistema para organição das viagens.                                        |

### Declaração da posição do produto

|               |                                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------------- |
| Para          | Paciente que utilizam os serviços da Secretaria Municipal de Saúde (SMS)                                             |
| O (SIAGEN)    | É um sistema WEB.                                                                                                    |
| Que           | Busca otimizar um trabalho que é feito de forma manual.                                                              |
| O sistema     | Oferece a automatização do gerenciamento de viagens com os pacientes do município.                                   |

## Declaração das partes interessadas

### Resumo das partes interessadas

| Nome                                | Descrição                                                                                        |
| ----------------------------------- | ------------------------------------------------------------------------------------------------ |
| Coordenador do Setor de Transportes | Funcionario responsável pela organização das viagens.                                            |
| Funcionários do Setor de Regulação  | Responsáveis pelas marcações de exames e consultas.                                              |
| Pacientes                           | Utilizadores dos serviço gerenciado.                                                             |
| Motoristas                          | Responsável pelos pacientes durante o trajeto.                                                   |
| Desenvolvedor                       | Pessoa responsável por cuidar da codificação e desenvolvimento do software em si: Emanuel Costa. |
| Gestão municipal                    | Responsável por fornecer este serviço.                                                           |

### Ambiente do usuário

Atualmente, o cenário se descreve de maneira simples: Os pacientes por não terem toda a corbetura
de atendimento de saúde dentro do município, precisam se locomover para outros municípios com o 
objetivo de realizar exames ou consultas. Sendo oferecido pela gestão municipal, por meio da secretaria 
municipal de saúde, carros e vans que fazem o translado dos pacientes até os municípios de atendimento.

## Visão geral do produto

### Necessidades e recursos

| Necessidades                                                                                                                                                                                                                                                                | Funcionalidades correspondentes                                                                                             | Responsável                     |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------- |
| Manter o registro das viagens realizadas com os pacientes| <ul><li>Registrar viagem </li><li>Cancelar viagem </li><li>Listar viagens  </li></ul>                             | Emanuel Costa          |
| Manter o controle de todos os pacientes que utilizam os transportes. | <ul><li>Cadastrar paciente </li><li>Listar pacientes</li><li>Alterar paciente  </li><li>Deletar paciente. </li></ul> | Emanuel Costa |
| Manter o controle de motorista. | <ul><li>Cadastrar motorista </li><li>Listar motoristas</li><li>Alterar motorista</li><li>Remover motorista</li></ul>                | Emanuel Costa |
| Manter o controle de municiíos de destino. | <ul><li>Cadastrar município </li><li>Listar municípios</li><li>Alterar município</li><li>Remover município</li></ul>                | Emanuel Costa |
| Manter o controle de locais de atendimento. | <ul><li>Cadastrar local de atendimento </li><li>Listar locais de atendimento </li><li>Alterar local de atendimento </li><li>Remover local de atendimento </li></ul>                | Emanuel Costa |
| Manter o controle de exames e consultas. | <ul><li>Cadastrar exame/consulta </li><li>Listar exames/consultas</li><li>Alterar exame/consulta  </li><li>Deletar exame/consulta. </li></ul> | Emanuel Costa |
| Manter o controle de veículos| <ul><li>Cadastrar veículo</li><li>Listar veículos</li><li>Atualizar veículos</li><li>Remover veículo</li></ul>                | Emanuel Costa  |


## Outros requisitos do produto

| Requisitos não-funcionais                                                                                       |
| --------------------------------------------------------------------------------------------------------------- |
| RNF 1: O sistema necessitará de um dispositivo que possibilite o acesso a internet. |
| RNF 2: O sistema necessitará de um browser de internet para ser acessado.|
| RNF 3: O sistema possibilitará a verificação de duas etapas para maior segurança.                               |

## Requisitos funcionais

### Especificação de casos de uso

#### Caso de uso Manter Viagem – Emanuel Costa

  | Caso de Uso - 01 |
  | ------ |

  | Nome do caso de uso: | CADASTRAR VIAGEM                                       |
  | -------------------- | ---------------------------------------------------------- |
  | Ator Principal:      | Coordenador de transportes                                                 |
  | Atores Secundários:  |      Pacientes, motoristas, funcionários do setor de regulação |
  | Descrição:           | Este caso de uso permite cadastrar uma nova viagem. |
  | Pré-condições:       | Funcionário deve estar logado no sistema para cadastrar uma nova viagem.  |
  | Pós-condições:       | Viagem cadasatrada no sistema.                          |

  | Fluxo Básico - CADASTRAR VIAGEM |
  | ----------------------------------- |

  |     | Ações do Ator                                                                   | Principal: Usuário Ações do Sistema:                                 |
  | --- | ------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
  | 1   | O caso de uso tem inicio quando o ator clica em criar nova viagem, na pagina inicial. | O sistema apresenta um formulário.                                   |
  | 2   | O ator preenche os dados de data e destino. | O sistema valida e guarda os dados.                                  |
  | 3   |                                                                                 | O sistema apresenta um formulário para seleção de motorista e veículo. |
  | 4   |                                               | O sistema verifica a disponibilidade das entidades selecionadas |
  | 5   |  Se as entidades estiverem disponíveis |  O sistema segue para o passo 7.            |
  | 6   |  Se as entidades não estiverem disponíveis | O sistema apresenta um alerta de "Recurso não disponível", será necessário selecionar nova(s) entidades. |
  | 7   |   | O sistema exibe a lista de pacientes. 
  | 8   | O ator seleciona os pacientes com consultas marcadas com datas correspondentes a viagem clicando no caixa de seleção | O sistema exibe informações de consulta/exame, município e local de atendimento |
  | 9   | O ator clica em confirmar para criar a viagem  |O sistema apresenta a mensagem "Nova viagem criada com sucesso". |
  | 10   | | Fim do caso de uso. |


  | Caso de Uso - 02 |
  | ------ |

  | Nome do caso de uso: | VISUALIZAR VIAGEM                                                    |
  | -------------------- | ------------------------------------------------------------------------ |
  | Ator Principal:      | Coordenador de transportes |
  | Atores Secundários:  |  Pacientes, motoristas, funcionários do setor de regulação |
  | Descrição:           | Este caso de uso permite ao ator, consultar editar e cancelar uma viagem. |
  | Pré-condições:       | O voluntário deve estar autenticado no sistema.                          |
  | Pós-condições:       | Consulta, edição ou cancelamento da viagem .|

  | Fluxo Basíco - VISUALIZAR VIAGEM |
  | ------------------------------------ |

  |     | Ações do Ator                                                                                | Principal: Usuário Ações do Sistema:                  |
  | --- | -------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
  | 1   | O caso de uso tem inicio na pagina inicial do SISTEMA, quando o ator clica no calendário de datas com viagens a serem executadas. | O sistema recupera os dados das viagens.               |
  | 2   |                                                                                              | O sistema apresenta todas as viagens agendadas para aquela data. |
  | 3   | O ator clicar na viagem para qual quer a informação | O sistema apresenta os dados da viagem selecionada. |
  | 4   | | O caso de uso é encerrado. |

  | FLUXO ALTERNATIVO 1 – EDITAR VIAGEM |
  | --------------------------------------- |

  |     | Ações do Ator                                 | Principal: Usuário Ações do Sistema:                    |
  | --- | --------------------------------------------- | ------------------------------------------------------- |
  | 1   | O ator clica em editar viagem.            | O sistema recupera os dados.                            |
  | 2   |                                               | O sistema apresenta um formulário para edição de dados. |
  | 3   | O ator modifica os campos que deseja alterar. | O sistema valida e guarda os dados.                     |
  | 4   |                                               | O sistema apresenta a mensagem "Viagem alterada.    |


  | FLUXO ALTERNATIVO 2 – CANCELAR VIAGEM |
  | ---------------------------------------- |

  |     | Ações do Ator                                     | Principal: Usuário Ações do Sistema:                                                                            |
  | --- | ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
  | 1   | O ator clica em cacelar viagem.               | O sistema recupera os dados.                                                                                    |
  | 2   |                                                   | O sistema apresenta um POPUP,perguntando se deseja mesmo cancelar a viagem.                                      |
  | 3   | O ator clica em sim, desejo cancelar a viagem. | O sistema apresenta um CHECKBOX com os possíveis motivos, e caixa de texto, caso queira relatar outros motivos. |
  | 4   |                                                   | O sistema valida e guarda os motivos da exclusão.           |
  | 5   |                                                   | O sistema cancela a viagem. O sistema apresenta a mensagem Viagem cancelada”.                            |
  | 6   | | O caso de uso é encerrado. |

## Tabela dos riscos

| Descrição                                | Causa                                                                                        |
| ----------------------------------- | ------------------------------------------------------------------------------------------------ |
| Não adesão do sistema | Difilculdades do coordenar de utilizar o sistema devido ao processo atual parecer o mais adequado. |
| Indiponibilidade de recursos de hardware  | O setor de transportes não dispor de computador para utilização do sistema. |
 
  
## Lista de regras de negócio

| Regras de negócio                                                               |
| ------------------------------------------------------------------------------- |
| RN1: O coordenador do setor de transportes deve manter o cadastro atualizado.           |
| RN2: O sistema possibilitará a verificação de duas etapas para maior segurança. |
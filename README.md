# SIM Mobile

**Case de transformação digital aplicada à manutenção industrial**

O SIM Mobile foi uma iniciativa criada para disponibilizar, em dispositivos móveis, atividades relevantes do sistema corporativo de manutenção. O objetivo era reduzir a dependência de computadores fixos e aproximar o registro das informações do local onde o trabalho era executado.

## Documentação

- [Estudo de caso em português](CASE_STUDY_PT.md)
- [Case study in English](CASE_STUDY_EN.md)

## Contexto

Técnicos de manutenção executavam atividades no chão de fábrica, mas ainda precisavam se deslocar até salas de apoio para consultar estoque, abrir ou atualizar ordens de manutenção, registrar mão de obra e concluir serviços.

Quando o acesso a um computador não era imediato, parte dos registros era feita posteriormente. Isso aumentava a distância entre a execução do trabalho e a informação disponível no sistema.

## Problema de negócio

O processo anterior apresentava os seguintes pontos:

- dependência de computadores fixos;
- deslocamentos entre a área produtiva e as salas de apoio;
- espera por estações disponíveis;
- registros realizados depois da execução;
- ordens de manutenção abertas por mais tempo;
- apontamentos de mão de obra realizados posteriormente;
- menor aderência entre os dados do sistema e a realidade operacional.

A sequência observada era:

`registro atrasado → apontamentos ausentes → ordens abertas → dados menos confiáveis → capacidade analítica limitada`

## Solução

O SIM Mobile foi desenvolvido como uma extensão dos fluxos mais relevantes do sistema corporativo, sem reproduzir integralmente a versão desktop.

As funcionalidades disponibilizadas ao longo do projeto incluíram:

- manutenção corretiva;
- criação e atualização de ordens de manutenção;
- consulta de estoque;
- manutenção preventiva;
- consulta de apontamentos de mão de obra;
- requisição de materiais.

## Minha atuação

Conduzi a iniciativa pelo lado do negócio, em interface com a equipe de Tecnologia da Informação.

Minhas responsabilidades incluíram:

- identificação das necessidades operacionais;
- mapeamento da jornada dos usuários;
- levantamento e priorização de requisitos;
- definição de telas, fluxos e comportamentos esperados;
- alinhamento entre Manutenção e TI;
- acompanhamento do desenvolvimento;
- testes funcionais;
- registro de erros e acompanhamento de correções;
- condução do piloto;
- treinamento inicial da equipe de PCM;
- apoio à implantação e à liberação de acessos;
- acompanhamento da adoção inicial.

O desenvolvimento técnico do software ficou sob responsabilidade da equipe de TI.

## Escopo documentado

| Indicador | Resultado |
|---|---:|
| Início da implantação | 2021 |
| Fluxos mobile disponibilizados | 5+ |
| Usuários habilitados até outubro de 2022 | 148 |
| Unidades brasileiras acompanhadas | 3 |

Usuários habilitados não equivalem necessariamente a usuários ativos. Os dados históricos disponíveis comprovam a liberação dos acessos, mas não a frequência diária de uso.

## Evolução do projeto

| Período | Etapa | Entrega |
|---|---|---|
| Março de 2021 | Modelagem e desenvolvimento | Estruturação inicial da solução mobile |
| Junho de 2021 | Fase 1 | Manutenção corretiva, criação de ordens e consulta de estoque |
| Dezembro de 2021 | Expansão | Manutenção preventiva e consulta de apontamentos de mão de obra |
| Novembro de 2022 | Novo fluxo | Requisição de materiais |

## Piloto e implantação

O piloto começou com equipes de manutenção elétrica e um escopo funcional controlado.

O ciclo de validação adotado foi:

`desenvolvimento → teste → uso em campo → registro de problemas → correção → novo teste`

A implantação envolveu autorização dos usuários, treinamento, solicitação de acesso à rede Wi-Fi, liberação do sistema e início do uso mobile. A equipe de PCM foi treinada primeiro para apoiar as demais equipes durante a expansão.

## Impacto documentado

Os registros disponíveis permitem afirmar que o projeto:

- aproximou atividades do sistema do local de execução;
- permitiu registros mais próximos do momento da atividade;
- reduziu a dependência de computadores em salas de apoio;
- aproximou execução e registro;
- criou uma base mais favorável para dados operacionais atualizados;
- fortaleceu a colaboração entre manutenção e tecnologia.

Os dados disponíveis não permitem atribuir ao projeto, de forma isolada, ganho financeiro, redução exata de tempo ou aumento quantitativo de produtividade.

## Indicadores para uma próxima fase

Uma etapa posterior poderia conectar logs de acesso, eventos das ordens de manutenção e indicadores das equipes.

### Adoção

- usuários ativos mensais;
- conversão entre acesso habilitado e uso;
- frequência de uso;
- adoção por funcionalidade, equipe e unidade.

### Eficiência operacional

- tempo para encerramento das ordens;
- percentual de ordens encerradas no mesmo turno;
- tempo entre execução e registro;
- participação do mobile em relação ao desktop.

### Qualidade dos dados

- ordens sem apontamento de mão de obra;
- envelhecimento das ordens abertas;
- taxa de registros tardios;
- percentual de ordens incompletas.

### Desempenho do negócio

- tempo produtivo dos técnicos;
- backlog de manutenção;
- disponibilidade dos equipamentos;
- correlação entre uso da solução e MTTR.

## Competências aplicadas

`Business Analysis` · `Análise de Processos` · `Requisitos Funcionais` · `Transformação Digital` · `Testes Funcionais` · `Gestão da Mudança` · `Implantação` · `Indicadores Operacionais`

## Confidencialidade

O repositório apresenta o contexto, o processo, a solução e minha atuação sem expor código proprietário, documentos internos, nomes de usuários ou informações estratégicas da empresa.

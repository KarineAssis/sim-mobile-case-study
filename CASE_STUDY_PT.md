# SIM Mobile — Estudo de caso de Data Analytics e transformação digital

## Resumo executivo

O SIM Mobile foi uma iniciativa de transformação digital aplicada à manutenção industrial que evidencia um princípio central de Analytics: **a qualidade dos insights depende da qualidade e do momento da captura dos dados**.

O problema principal era a distância entre a execução do trabalho e o registro das informações. Técnicos que atuavam no chão de fábrica ainda precisavam se deslocar até computadores fixos para consultar estoque, abrir ou atualizar ordens de manutenção, registrar mão de obra e concluir serviços. Quando o registro era adiado, o sistema deixava de refletir a operação no momento adequado.

Atuei na condução do projeto pelo lado do negócio, traduzindo o problema operacional em requisitos funcionais, testes, piloto, implantação e oportunidades de mensuração.

## Contexto

Antes da solução, parte da rotina administrativa da manutenção dependia de computadores localizados em salas de apoio. Quando o acesso não era imediato, o registro podia ser realizado posteriormente.

Esse processo gerava:

- deslocamentos entre a área produtiva e as salas de apoio;
- espera por computadores disponíveis;
- registros realizados depois da execução;
- ordens de manutenção abertas por mais tempo;
- apontamentos de mão de obra feitos posteriormente;
- menor aderência entre o sistema e a realidade operacional;
- uma base menos confiável para indicadores e análises.

### Cadeia do problema de dados

`execução em campo → deslocamento e espera → registro tardio → ordens abertas ou incompletas → menor qualidade dos dados → insights limitados`

## Objetivo

Disponibilizar, em dispositivos móveis, os fluxos mais relevantes para a rotina dos técnicos de manutenção, aproximando o registro das informações do local e do momento de execução.

## Solução

O SIM Mobile foi desenvolvido como uma extensão dos fluxos do sistema corporativo, sem reproduzir integralmente a versão desktop.

As funcionalidades incluíram:

- manutenção corretiva;
- criação e atualização de ordens de manutenção;
- consulta de estoque;
- manutenção preventiva;
- consulta de apontamentos de mão de obra;
- requisição de materiais.

## Minha atuação

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
- acompanhamento da adoção inicial;
- definição de indicadores para avaliar adoção, eficiência e qualidade dos dados.

O desenvolvimento técnico do software ficou sob responsabilidade da equipe de TI.

## Evolução do projeto

| Período | Etapa | Entrega |
|---|---|---|
| Março de 2021 | Modelagem e desenvolvimento | Estruturação inicial da solução mobile |
| Junho de 2021 | Fase 1 | Manutenção corretiva, criação de ordens e consulta de estoque |
| Dezembro de 2021 | Expansão | Manutenção preventiva e consulta de apontamentos de mão de obra |
| Novembro de 2022 | Novo fluxo | Requisição de materiais |

## Piloto e implantação

O piloto começou com equipes de manutenção elétrica e um escopo funcional controlado.

O ciclo de validação foi:

`desenvolvimento → teste → uso em campo → registro de problemas → correção → novo teste`

A implantação envolveu:

1. autorização dos usuários;
2. preparação do treinamento;
3. solicitação de acesso à rede Wi-Fi;
4. liberação do acesso ao sistema;
5. início do uso mobile.

A equipe de PCM foi treinada primeiro para apoiar as demais equipes durante a expansão.

## Escopo documentado

| Indicador | Resultado |
|---|---:|
| Início da implantação | 2021 |
| Fluxos mobile disponibilizados | 5+ |
| Usuários habilitados até outubro de 2022 | 148 |
| Unidades brasileiras acompanhadas | 3 |

Usuários habilitados não equivalem necessariamente a usuários ativos. Os registros históricos disponíveis comprovam a liberação dos acessos, mas não a frequência diária de uso.

## Impacto documentado

Os dados disponíveis permitem afirmar que o projeto:

- aproximou atividades do sistema do local de execução;
- permitiu registros mais próximos do momento da atividade;
- reduziu a dependência de computadores em salas de apoio;
- aproximou execução e registro;
- criou uma base mais favorável para dados operacionais atualizados;
- fortaleceu a colaboração entre manutenção e tecnologia.

Os dados disponíveis não permitem atribuir ao projeto, de forma isolada, ganho financeiro, redução exata de tempo ou aumento quantitativo de produtividade.

## Oportunidade analítica

Uma próxima fase poderia integrar logs de acesso, eventos das ordens de manutenção e indicadores de desempenho para avaliar adoção, eficiência e impacto operacional.

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

## Competências demonstradas

`Data Capture` · `Data Quality` · `Operational Analytics` · `Business Analysis` · `Requisitos Funcionais` · `Indicadores` · `Testes Funcionais` · `Gestão da Mudança` · `Stakeholder Management`

## Confidencialidade

Este estudo de caso apresenta o contexto, o processo, a solução e minha atuação sem expor código proprietário, documentos internos, nomes de usuários ou informações estratégicas da empresa.
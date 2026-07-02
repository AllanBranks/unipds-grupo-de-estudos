# LAB 001 • Avaliador Inteligente de Atendimento

> Primeira iniciativa do Laboratório de IA Aplicada do Grupo de Estudos da Pós-Graduação UNIPDS.

---

# 📖 Contexto

Esta iniciativa surgiu durante um brainstorming realizado pelo grupo de estudos.

O objetivo do laboratório é aprender Engenharia de Software aplicada à Inteligência Artificial através da construção de soluções reais.

O primeiro desafio escolhido pelo grupo foi investigar como modelos de linguagem podem auxiliar na avaliação automática de atendimentos realizados via WhatsApp.

Este documento representa a consolidação das ideias discutidas durante os primeiros encontros e servirá como base para evolução do projeto.

---



# 🎯 Problema

Empresas realizam centenas de atendimentos diariamente por canais como WhatsApp.

Avaliar manualmente a qualidade desses atendimentos é um processo caro, demorado e pouco escalável.

Além disso, resumir toda uma conversa em uma nota de **0 a 5** nem sempre representa a qualidade real da interação, pois esse tipo de avaliação perde grande parte do contexto do atendimento.

A proposta desta iniciativa é investigar como modelos de linguagem podem produzir análises mais completas e contextualizadas dessas conversas.

---



# 💡 Objetivo

Construir um agente capaz de analisar automaticamente atendimentos encerrados e gerar informações que auxiliem gestores na avaliação da qualidade do atendimento.

O projeto também servirá como ambiente para estudo de arquiteturas de IA, agentes inteligentes e desenvolvimento guiado por Inteligência Artificial.

---



# 🔄 Fluxo Inicial

```text
Cliente

↓

WhatsApp

↓

Atendimento

↓

Atendimento encerrado

↓

Processo diário

↓

Agente de IA

↓

Resultado da análise via Whatsapp para o Operador

↓

Backoffice ( Futuro )
```

---



# 🔍 Informações analisadas

O agente deverá produzir informações como:

### Atendimento
- Qualidade do atendimento
- Educação
- Cordialidade
- Formalidade
- Clareza da comunicação

---

### Cliente

- Sentimento durante a conversa
- Indícios de satisfação

---

### Processo

- Tempo total do atendimento
- Tempo de resposta entre mensagens
- Categoria do atendimento
- Identificação de resolução do problema

---

### Resultado

- Resumo da conversa
- Avaliação geral
- Pontos positivos
- Oportunidades de melhoria

---



# 🛠 Stack Inicial

Como ponto de partida, o grupo pretende utilizar:

- Node.js
- LangGraph
- Evolution API
- OpenRouter

A escolha busca aproveitar os conhecimentos desenvolvidos durante a pós-graduação e explorar arquiteturas baseadas em agentes.

> ⚠️ Esse ponto está em aberto e será debatido no próximo encontro 

---



# 🎓 Objetivos de Aprendizagem

Além do desenvolvimento da solução, esta iniciativa servirá para estudar:

- Engenharia de Prompt
- Agentes de IA
- LangGraph
- MCP (Model Context Protocol)
- RAG
- Modelos Locais e via agregadores
- Avaliação de LLMs
- Arquitetura para aplicações com IA
- Desenvolvimento Guiado por IA (SDD)

---



# 💻 Forma de Desenvolvimento

O projeto será desenvolvido de forma colaborativa.

Pretendemos utilizar IA como apoio durante todas as etapas do desenvolvimento, incentivando experimentação, revisão de código, geração de testes e evolução contínua da solução.

Sempre que possível, a arquitetura deverá favorecer baixo acoplamento, permitindo futuras experimentações com outras linguagens e tecnologias.

---



# 🏢 Empresa Fictícia

Será criada uma empresa fictícia que servirá como contexto para o laboratório.

Ela será utilizada para definir:

- Cenários
- Regras de negócio
- Exemplos
- Conversas
- Casos de uso

> ⚠️ Esse ponto está em aberto e será debatido no próximo encontro 

---



# 🚀 Evoluções Futuras

As ideias abaixo fazem parte do backlog do laboratório e poderão ser desenvolvidas nas próximas iterações.

## Dashboard

Visualização das análises realizadas pela IA.

## SLA

Definição de diferentes tempos esperados para cada categoria de atendimento.

Exemplos:

- Vendas
- Financeiro
- Suporte
- Dúvidas
- Urgências



## Atendimento Híbrido

A IA inicia o atendimento e transfere para um atendente humano quando necessário.

## Atendimento com IA

A IA conduz todo o atendimento de forma autônoma.

## Agentes Especializados

Criar agentes específicos para diferentes áreas.

Exemplos:

- Comercial
- Suporte
- Financeiro
- Customer Success

---



# ❓ Pontos em Aberto

As seguintes decisões ainda serão discutidas pelo grupo.

- Como identificar que um atendimento foi encerrado.
- Como integrar com o WhatsApp.
- Como armazenar as conversas.
- Como representar os resultados das análises.
- Como definir os critérios de qualidade.
- Definição da empresa fictícia.

---



# 📅 Próximos Passos

- Consolidar o MVP.
- Definir arquitetura inicial.
- Criar backlog.
- Dividir responsabilidades.
- Iniciar o desenvolvimento.

---

> **Este documento representa o estado atual das discussões do grupo e será atualizado continuamente conforme a evolução do laboratório.**


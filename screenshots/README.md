# Evidências técnicas — MEU CONSULTOR AI

## 1. Sobre este diretório

Este diretório documenta evidências visuais do desenvolvimento do **MEU CONSULTOR AI**, um projeto autoral de assistente inteligente integrado ao WhatsApp.

A solução utiliza automações no n8n, componentes de inteligência artificial, integrações por APIs e webhooks e persistência de dados no Supabase.

**Objetivo da documentação:** apresentar decisões de implementação, fluxos automatizados, integrações e competências técnicas desenvolvidas durante a construção do produto.

As capturas representam momentos específicos do desenvolvimento e não comprovam, isoladamente, a estabilidade ou a disponibilidade das funcionalidades em produção.

## 2. Interface conversacional — WhatsApp

### 2.1 Apresentação do assistente

![Apresentação do MEU CONSULTOR](01-whatsapp-apresentacao.jpg)

**Descrição:** interface conversacional utilizada para apresentar as funcionalidades do MEU CONSULTOR.

**Competências relacionadas:**
- Desenvolvimento de experiências conversacionais.
- Integração de mensagens com processos automatizados.
- Organização da interação entre usuário e assistente.

### 2.2 Agendamento e consulta

![Agendamento pelo WhatsApp](02-whatsapp-agendamento-consulta.jpg)

**Descrição:** cenário de teste envolvendo solicitação de agendamento em linguagem natural, confirmação da operação e consulta de compromissos.

**Aspectos técnicos demonstrados:**
- Interpretação de solicitações em linguagem natural.
- Encaminhamento de intenções para fluxos específicos.
- Confirmação explícita antes de operações.
- Recuperação e apresentação de informações.

**Limitação:** a captura não substitui a verificação dos registros persistidos no banco de dados.

## 3. Orquestração de workflows — n8n

### 3.1 Execução 9402 — Workflow principal

![Execução 9402](03-n8n-execucao-9402.jpg)

Registro de execução concluída com sucesso pelo n8n, apresentando a orquestração de etapas automatizadas.

### 3.2 Execução 3877 — Processamento e ramificações

![Execução 3877](04-n8n-execucao-3877.jpg)

Evidência de caminhos relacionados ao processamento de mensagens, tarefas e documentos.

### 3.3 Execução 3801 — Operações com tarefas

![Execução 3801](05-n8n-execucao-3801.jpg)

Representação de operações de consulta, atualização e cancelamento de tarefas, incluindo etapas de preparação de respostas.

### 3.4 Execução 3795 — Roteamento de intenções

![Execução 3795](06-n8n-execucao-3795.jpg)

Demonstração da estrutura de roteamento de solicitações entre componentes de IA e operações de dados.

### 3.5 Execução 3749 — Integração de processos

![Execução 3749](07-n8n-execucao-3749.jpg)

Evidência da conexão entre processamento de tarefas, operações de dados e envio de respostas pelo WhatsApp.

**Competências relacionadas às execuções:**
- Modelagem e orquestração de workflows.
- Construção de ramificações condicionais.
- Integração entre serviços.
- Inspeção e diagnóstico de execuções.
- Tratamento e encaminhamento de informações.

## 4. Componentes e integrações

### 4.1 Webhooks e anexos

![Webhook e anexos](08-n8n-webhook-anexos.jpg)

Estrutura de recebimento de mensagens e identificação de anexos para processamento.

### 4.2 Agente de agenda

![Agente de agenda](09-n8n-agente-agenda.jpg)

Fluxo de interpretação de solicitações relacionadas à agenda e encaminhamento às operações correspondentes.

### 4.3 Tarefas e lembretes

![Tarefas e lembretes](10-n8n-tarefas-lembretes.jpg)

Estrutura de automação para operações relacionadas ao gerenciamento de tarefas e lembretes.

### 4.4 Roteamento de tarefas

![Roteamento de tarefas](11-n8n-roteamento-tarefas.jpg)

Distribuição de solicitações entre caminhos de execução conforme a intenção identificada.

## 5. Competências técnicas demonstradas

| Área | Competências evidenciadas |
|---|---|
| Automação | Modelagem, implementação e inspeção de workflows no n8n |
| Inteligência artificial | Integração de componentes de IA e roteamento de intenções |
| Integração de sistemas | Utilização de webhooks e APIs |
| Interfaces conversacionais | Construção de interações pelo WhatsApp |
| Operações de dados | Estruturação de fluxos de consulta, criação e atualização |
| Engenharia de processos | Condicionais, confirmações e encaminhamento de ações |
| Diagnóstico técnico | Análise de execuções e identificação de falhas |
| Documentação | Registro de arquitetura, componentes e evidências |

Essas competências são sustentadas pelos cenários documentados, respeitando as limitações das capturas disponíveis.

## 6. Limitações, validação e segurança

As evidências representam registros de implementação e testes em momentos específicos.

Uma execução marcada como bem-sucedida no n8n significa que o workflow terminou sem erro reportado naquela execução. Isso não comprova automaticamente a correção de todos os resultados, a segurança da solução ou sua estabilidade em produção.

A publicação de evidências deve seguir critérios de proteção de informações:

- Não divulgar credenciais, tokens ou chaves de API.
- Não expor URLs sensíveis ou webhooks de produção.
- Não publicar dados pessoais sem autorização.
- Utilizar informações fictícias ou anonimizadas nos exemplos.
- Verificar identificadores e informações de infraestrutura.
- Documentar separadamente funcionalidades testadas e funcionalidades planejadas.

**Status de auditoria:** revisão documental realizada; inspeção individual de segurança das imagens ainda pendente.

## 7. Documentação complementar

- [Arquitetura técnica](../docs/arquitetura.md)
- [Estudo de caso — Agendamentos pelo WhatsApp](../case-studies/agendamentos-whatsapp.md)

---

**MEU CONSULTOR AI**

Projeto autoral de inteligência artificial aplicada, automação de processos, integração de sistemas e desenvolvimento de soluções SaaS.

*Documentação técnica em evolução, com evidências de implementação e testes.*

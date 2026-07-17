# tmh-agent-skills

Skills para o **Claude Cowork** para criação e atualização de prompts de agentes de IA na plataforma **The Mind Hub (TMH)** no Bitrix24.

## Skills disponíveis

**tmh-prompt-create** — Cria prompts completos de agentes TMH: prompt principal + arquivos RAG. Descreve o caso de uso do cliente e a skill gera tudo pronto para upload.

**tmh-prompt-update** — Revisa, diagnostica e corrige prompts existentes de agentes TMH. Cola o prompt atual, descreve o problema e a skill entrega a versão corrigida.

## Como instalar

Baixe o ficheiro `.skill` pretendido: [tmh-prompt-create.skill](./tmh-prompt-create.skill) ou [tmh-prompt-update.skill](./tmh-prompt-update.skill)

No Claude Cowork, vá a **Settings > Skills > Upload skill** e selecione o ficheiro. A skill fica disponível imediatamente — escreva `/tmh-prompt-create` ou `/tmh-prompt-update` no chat para activá-la.

## O que é o The Mind Hub (TMH)?

O TMH é uma aplicação no Bitrix24 Market que integra agentes de IA com o CRM Bitrix24. Os agentes recebem um prompt principal e arquivos RAG de conhecimento, com acesso a ferramentas como `crm_lead_get`, `crm_deal_update`, `calendar_event_add`, `retriever_tool`, entre outras.

Estas skills encapsulam todo o conhecimento necessário para criar e manter esses agentes com qualidade de produção.

## Autor

Rômulo Guerra — [Arrecife Digital](https://arrecifedigital.pt)

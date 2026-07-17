# tmh-agent-skills

Skills para o **Claude Cowork** e comandos para o **Claude Code** para criação e atualização de prompts de agentes de IA na plataforma **The Mind Hub (TMH)** no Bitrix24.

## Skills disponíveis

**tmh-prompt-create** — Cria prompts completos de agentes TMH: prompt principal + arquivos RAG. Descreve o caso de uso do cliente e a skill gera tudo pronto para upload.

**tmh-prompt-update** — Revisa, diagnostica e corrige prompts existentes de agentes TMH. Cola o prompt atual, descreve o problema e a skill entrega a versão corrigida.

## Instalar no Claude Cowork

Baixe o ficheiro `.skill` pretendido: [tmh-prompt-create.skill](./tmh-prompt-create.skill) ou [tmh-prompt-update.skill](./tmh-prompt-update.skill)

No Claude Cowork, vá a **Settings > Skills > Upload skill** e selecione o ficheiro. A skill fica disponível imediatamente — escreva `/tmh-prompt-create` ou `/tmh-prompt-update` no chat para activá-la.

## Instalar no Claude Code

Cole este bloco no **PowerShell** para descarregar os comandos directamente do GitHub e instalar na pasta correcta:

```powershell
mkdir "$env:USERPROFILE\.claude\commands" -Force

Invoke-WebRequest -Uri "https://raw.githubusercontent.com/RomuloGuerra/tmh-agent-skills/main/tmh-prompt-create.md" -OutFile "$env:USERPROFILE\.claude\commands\tmh-prompt-create.md"

Invoke-WebRequest -Uri "https://raw.githubusercontent.com/RomuloGuerra/tmh-agent-skills/main/tmh-prompt-update.md" -OutFile "$env:USERPROFILE\.claude\commands\tmh-prompt-update.md"
```

Depois disso, `/tmh-prompt-create` e `/tmh-prompt-update` aparecem no autocomplete do Claude Code.

## O que é o The Mind Hub (TMH)?

O TMH é uma aplicação no Bitrix24 Market que integra agentes de IA com o CRM Bitrix24. Os agentes recebem um prompt principal e arquivos RAG de conhecimento, com acesso a ferramentas como `crm_lead_get`, `crm_deal_update`, `calendar_event_add`, `retriever_tool`, entre outras.

Estas skills encapsulam todo o conhecimento necessário para criar e manter esses agentes com qualidade de produção.

## Autor

Rômulo Guerra — [Arrecife Digital](https://arrecifedigital.pt)

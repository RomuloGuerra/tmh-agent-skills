# tmh-agent-skills

Skills para o **Claude Cowork** que auxiliam na criação e atualização de prompts de agentes de IA para a plataforma **The Mind Hub (TMH)** no Bitrix24.

## Skills disponíveis

### `tmh-prompt-create`
Cria prompts completos de agentes de IA para clientes TMH — prompt principal + arquivos RAG. Basta descrever o caso de uso do cliente e a skill gera tudo pronto para upload no TMH.

### `tmh-prompt-update`
Revisa, diagnostica e corrige prompts existentes de agentes TMH. Cola o prompt atual, descreve o problema e a skill entrega a versão corrigida com diagnóstico detalhado.

## Como instalar

1. Baixe o ficheiro `.skill` da skill desejada:
2.    - [`tmh-prompt-create.skill`](./tmh-prompt-create.skill)
      -    - [`tmh-prompt-update.skill`](./tmh-prompt-update.skill)
       
           - 2. No Claude Cowork, abra **Settings → Skills → Upload skill**
            
             3. 3. Selecione o ficheiro `.skill` — a skill ficará disponível imediatamente
               
                4. 4. Para usar, escreva `/tmh-prompt-create` ou `/tmh-prompt-update` no chat
                  
                   5. ## O que é o The Mind Hub (TMH)?
                  
                   6. O TMH é uma aplicação no Bitrix24 Market que integra agentes de IA com o CRM Bitrix24. Os agentes recebem um prompt principal (`.md`) e arquivos de conhecimento RAG (`.docx`) e têm acesso a ferramentas como `crm_lead_get`, `crm_deal_update`, `calendar_event_add`, `retriever_tool`, entre outras.
                  
                   7. Estas skills encapsulam todo o conhecimento necessário para criar e manter esses agentes com qualidade de produção.
                  
                   8. ## Autor
                  
                   9. Rômulo Guerra — [Arrecife Digital](https://arrecifedigital.pt)

# 📋 Automação de Intake de Solicitações — Google Forms + Sheets + Apps Script

> Parte 1 de 2 do projeto "Gestão de demandas do time de dados" na iRede.
> Parte 2 (dashboard): [link do outro repositório]

## Contexto

O time de dados da iRede recebia solicitações de forma dispersa (e-mail, mensagem, conversa informal), sem padronização nem rastreabilidade. Isso dificultava priorização, gerava retrabalho e não permitia medir volume ou tempo de atendimento.

## O que foi construído

Um fluxo de intake estruturado, do pedido até o registro auditável:

1. **Formulário padronizado (Google Forms)** — captura solicitante, tipo de demanda, prioridade e prazo desejado em campos fixos, eliminando ambiguidade na entrada.
2. **Registro automático (Google Sheets)** — cada resposta gera uma linha estruturada, servindo como fonte única de verdade para o time.
3. **Automação de fluxo (Google Apps Script)** — script dispara:
   - Notificação por e-mail ao time de dados a cada nova solicitação
   - Preenchimento automático de campos derivados (data de entrada, status inicial, ID sequencial)
   - Validações que impedem registros incompletos

## Stack

`Google Forms` · `Google Sheets` · `Google Apps Script` · `Automação de fluxo de trabalho`

## Resultado

- Eliminação de solicitações "perdidas" por canal informal
- Base estruturada que alimenta diretamente o [dashboard de acompanhamento](https://github.com/EstherLins/dashboard-acompanhamento-demandas) (Parte 2)
- Tempo de resposta a novas solicitações reduzido pela notificação automática

## Observação

Os dados demonstrados em capturas de tela/exemplos são fictícios, para preservar a confidencialidade das informações reais do time.

---

Projeto documentado também em: [portfólio completo](https://esther-lins.vercel.app)

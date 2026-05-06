# ⚖️ Painel Fórum — OAB Santana de Parnaíba

> Sistema operacional interno para gestão de demandas do Convênio DPESP/OAB-SP na 247ª Subseção de Santana de Parnaíba.

🔗 **[Acessar o painel ao vivo](https://cassiakelly995-lab.github.io/demandadoforum/)**

---

## O que é

Painel web de uso diário para processar as demandas enviadas pelo Fórum da Comarca à equipe de Assistência Judiciária Gratuita. Concentra em um único lugar os tutoriais do sistema DOL, checklists obrigatórios, gerador de respostas institucionais, histórico de mensagens e critérios legais de nomeação — tudo o que a equipe precisa para atender com segurança e agilidade.

Construído para eliminar erros operacionais em nomeações sensíveis: cada módulo reflete uma regra real do sistema DPESP, incluindo bloqueios legais e requisitos obrigatórios que, se ignorados, invalidam a nomeação.

---

## Funcionalidades

| Módulo | Descrição |
|---|---|
| 📋 Depoimento Especial | Tutorial DOL passo a passo para nomeação de vítimas (Lei 13.431/17) com checklist e presunção de vulnerabilidade |
| 📁 Inventário / Alvará | Procedimento obrigatório para nomeações de herdeiros — inclui inclusão do falecido no sistema (CAJ 017/2023) |
| 💬 Gerador de Respostas | Formulários inteligentes que geram mensagens institucionais prontas para 4 tipos de situação |
| 👤 Curador Especial | Orientações, checklist e respostas para demandas de curador — com regra de nomeação ativa |
| 🗂️ Avaliação Financeira | Regras de validade (1 ano), documentação exigida e resposta pronta para avaliação vencida |
| 🕐 Histórico | Registro local de mensagens salvas durante o turno |
| 📧 E-mails UPJ | Endereços institucionais da UPJ Cível para envios diretos |
| 📌 Critérios | Quem tem direito à nomeação com ou sem avaliação financeira, com fundamentação legal |

---

## Gerador de Respostas

O módulo central do painel. Preencha os campos e a mensagem é gerada automaticamente, formatada e pronta para copiar:

- **Resposta Padrão** — para prestação de informações gerais ao juízo
- **Confirmar Nomeação** — informa ao fórum que a indicação de advogado foi realizada (com nome, OAB e data)
- **Solicitar Dados** — pede documentos ou informações faltantes com campos selecionáveis
- **Acuse de Recebimento** — confirmação rápida de recebimento de ofício

---

## Base legal implementada

O painel codifica regras jurídicas reais que a equipe precisa aplicar corretamente:

- **Lei nº 13.431/2017** — sistema de garantia de direitos de criança/adolescente vítima de violência
- **CAJ nº 017/2023** — inclusão obrigatória do falecido em nomeações de Inventário/Alvará
- **Deliberação 89/08 CSDP (art. 2º, §20), com redação da Deliberação 409/23** — presunção de usuário da Defensoria para vítimas do depoimento especial

---

## Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Sem dependências externas. Histórico salvo via `localStorage`. Roda direto no navegador.

---

## Como usar

1. Acesse **[cassiakelly995-lab.github.io/demandadoforum](https://cassiakelly995-lab.github.io/demandadoforum/)**
2. Selecione o módulo correspondente ao tipo de demanda recebida do fórum
3. Siga o checklist antes de abrir o sistema DOL
4. Use o Gerador de Respostas para criar e copiar a mensagem institucional
5. Salve no Histórico para registro do turno

---

## Contexto

Desenvolvido por **Cássia Kelly Lins Reis** — Assistente Administrativa da 247ª Subseção OAB Santana de Parnaíba, equipe de Assistência Judiciária Gratuita. As regras, fluxos e bloqueios implementados refletem a operação real do Convênio DPESP/OAB-SP, construídos a partir de 10 anos de experiência na linha de frente do atendimento.

---

*Este repositório faz parte de um ecossistema de ferramentas internas desenvolvidas para a OAB Santana de Parnaíba.*

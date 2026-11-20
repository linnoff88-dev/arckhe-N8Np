# ðŸš€ N8Np - Biblioteca de Workflows n8n & AI Agents

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![MkDocs](https://img.shields.io/badge/docs-mkdocs-blue)](https://inematds.github.io/N8Np/)
[![Material for MkDocs](https://img.shields.io/badge/theme-material-00C7B7)](https://squidfunk.github.io/mkdocs-material/)
[![Workflows](https://img.shields.io/badge/workflows-532-success)](https://inematds.github.io/N8Np/workflows/)
[![License](https://img.shields.io/badge/license-Community-orange)](LICENSE)

> Biblioteca completa de workflows n8n, AI agents e automaÃ§Ãµes da comunidade N8Np

## ðŸ“Š EstatÃ­sticas

- **532 workflows** catalogados
- **198 AI Agents**
- **420 tÃ³picos** da comunidade
- **23 liÃ§Ãµes** do curso completo
- **1.1 GB** de conteÃºdo educacional

## ðŸŒ Acesse o Site

ðŸ‘‰ **[https://inematds.github.io/N8Np/](https://inematds.github.io/N8Np/)**

Site de documentaÃ§Ã£o completo com:
- ðŸ” Busca inteligente
- ðŸ“ CategorizaÃ§Ã£o automÃ¡tica
- ðŸŽ¨ Tema moderno Material Design
- ðŸŒ— Modo claro/escuro
- ðŸ“± Responsivo

## ðŸŽ¯ Categorias

### ðŸ¤– [AI Agents](https://inematds.github.io/N8Np/workflows/ai-agents/)
Agentes inteligentes com LLMs (GPT-4, Claude, etc), RAG pipelines, chatbots e sistemas HITL

**Destaques:**
- Agente de vendas com validaÃ§Ã£o humana
- First AI Agent com Google Sheets
- RAG Workflow vs RAG Agent
- Voice Email Agent

### ðŸ”„ [AutomaÃ§Ãµes](https://inematds.github.io/N8Np/workflows/automations/)
Workflows para automatizar processos empresariais

**Destaques:**
- Customer Support Workflow
- LinkedIn Automation
- Invoice Processing
- WhatsApp Agent

### ðŸ› ï¸ [IntegraÃ§Ãµes](https://inematds.github.io/N8Np/workflows/integrations/)
Conectores com serviÃ§os populares

**DisponÃ­veis:**
- Google Drive, Sheets, Gmail
- Supabase / Postgres
- OpenAI, Perplexity
- Airtable, Firecrawl, Apify

### ðŸ“š [Curso Completo](https://inematds.github.io/N8Np/curso/)
"The Ultimate n8n Course" com 23 liÃ§Ãµes progressivas

## ðŸš€ Como Usar

### Acessar Online
Visite: [https://inematds.github.io/N8Np/](https://inematds.github.io/N8Np/)

### Rodar Localmente
```bash
# Clonar repositÃ³rio
git clone https://github.com/inematds/N8Np.git
cd N8Np

# Instalar dependÃªncias
pip install mkdocs mkdocs-material

# Rodar site
cd n8np-docs
mkdocs serve
```

Acesse: http://127.0.0.1:8000

### Importar Workflows
1. Navegue pelo site e encontre o workflow desejado
2. Copie o caminho do arquivo (ex: `Ref/2494913847/8187/1) RAG Pipeline & Chatbot.json`)
3. Importe no seu n8n
4. Reconfigure as credenciais

## ðŸ“‚ Estrutura do RepositÃ³rio

```
N8Np/
â”œâ”€â”€ Ref/                          # 532 workflows organizados por tÃ³pico
â”‚   â””â”€â”€ 2494913847/              # Grupo do Telegram
â”‚       â”œâ”€â”€ [topic_id]/          # TÃ³pico individual
â”‚       â”‚   â”œâ”€â”€ *.json          # Workflows n8n
â”‚       â”‚   â”œâ”€â”€ content.txt     # Conversa da comunidade
â”‚       â”‚   â”œâ”€â”€ metadata.json   # Metadados
â”‚       â”‚   â””â”€â”€ *.pdf           # DocumentaÃ§Ã£o
â”‚       â””â”€â”€ ...
â”œâ”€â”€ n8np-docs/                   # Site de documentaÃ§Ã£o
â”‚   â”œâ”€â”€ mkdocs.yml              # ConfiguraÃ§Ã£o
â”‚   â”œâ”€â”€ docs/                   # ConteÃºdo markdown
â”‚   â””â”€â”€ site/                   # HTML gerado
â”œâ”€â”€ generate_docs.py             # Script de geraÃ§Ã£o
â”œâ”€â”€ CLAUDE.md                    # Guia para Claude Code
â”œâ”€â”€ RELATORIO_ANALISE.md        # AnÃ¡lise do repositÃ³rio
â””â”€â”€ README.md                   # Este arquivo
```

## ðŸ”„ Atualizar DocumentaÃ§Ã£o

Se novos workflows forem adicionados:

```bash
# Regenerar documentaÃ§Ã£o
python3 generate_docs.py

# Deploy
cd n8np-docs
mkdocs gh-deploy
```

## ðŸ¤ Contribuir

ContribuiÃ§Ãµes sÃ£o bem-vindas! Para adicionar workflows:

1. Adicione os arquivos `.json` em `Ref/2494913847/[novo_topico]/`
2. Execute `python3 generate_docs.py`
3. FaÃ§a um Pull Request

## ðŸ“– DocumentaÃ§Ã£o

- [CLAUDE.md](CLAUDE.md) - Guia para Claude Code trabalhar no repo
- [RELATORIO_ANALISE.md](RELATORIO_ANALISE.md) - AnÃ¡lise completa do conteÃºdo
- [IMPLEMENTACAO_COMPLETA.md](IMPLEMENTACAO_COMPLETA.md) - Detalhes da implementaÃ§Ã£o
- [n8np-docs/README.md](n8np-docs/README.md) - DocumentaÃ§Ã£o do site

## âš ï¸ Importante

- Todos os workflows precisam de **credenciais reconfiguradas** apÃ³s importaÃ§Ã£o
- Este Ã© um **repositÃ³rio de referÃªncia**, nÃ£o uma instalaÃ§Ã£o n8n ativa
- Sempre revise os workflows antes de usar em produÃ§Ã£o

## ðŸŒŸ Destaques da Comunidade

### Workflow Mais Popular
**Agente de Vendas com ValidaÃ§Ã£o Humana**

Sistema completo de sales automation com loop de feedback humano usando Gmail "Send and Wait" + Text Classifier.

### Caso de Uso Real
**GeraÃ§Ã£o de MÃºsicas AutomÃ¡tica**

Workflow que gera mÃºsicas com PiAPI e envia para Google Drive automaticamente.

## ðŸ“ž Comunidade

- ðŸ’¬ [Telegram](https://t.me/n8np) - Comunidade N8Np
- ðŸŒ [Site](https://inematds.github.io/N8Np/) - DocumentaÃ§Ã£o oficial
- ðŸ“§ Email: inematds@gmail.com

## ðŸ“„ License

ConteÃºdo compartilhado pela comunidade N8Np para uso educacional.

---

<p align="center">
  <strong>âœ¨ Criado pela comunidade N8Np</strong><br>
  <em>1.1 GB de conteÃºdo educacional | 532 workflows | 420 tÃ³picos</em>
</p>

<p align="center">
  <a href="https://inematds.github.io/N8Np/">ðŸŒ Visite o Site</a> â€¢
  <a href="https://inematds.github.io/N8Np/workflows/">ðŸ“ Ver Workflows</a> â€¢
  <a href="https://inematds.github.io/N8Np/curso/">ðŸ“š Fazer Curso</a>
</p>

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>
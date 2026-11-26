ï»¿# ê°Å¸Å¡â¬ N8Np - Biblioteca de Workflows n8n & AI Agents

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![MkDocs](https://img.shields.io/badge/docs-mkdocs-blue)](https://linnoff88-dev.github.io/arckhe-/)
[![Material for MkDocs](https://img.shields.io/badge/theme-material-00C7B7)](https://squidfunk.github.io/mkdocs-material/)
[![Workflows](https://img.shields.io/badge/workflows-532-success)](https://linnoff88-dev.github.io/arckhe-/workflows/)
[![License](https://img.shields.io/badge/license-Community-orange)](LICENSE)

> Biblioteca completa de workflows n8n, AI agents e automaêÂ§êÂµes da comunidade N8Np

## ê°Å¸âÅ  EstatêÂ­sticas

- **532 workflows** catalogados
- **198 AI Agents**
- **420 têÂ³picos** da comunidade
- **23 liêÂ§êÂµes** do curso completo
- **1.1 GB** de conteêÂºdo educacional

## ê°Å¸ÅÂ Acesse o Site

ê°Å¸ââ° **[https://linnoff88-dev.github.io/arckhe-/](https://linnoff88-dev.github.io/arckhe-/)**

Site de documentaêÂ§êÂ£o completo com:
- ê°Å¸âÂ Busca inteligente
- ê°Å¸âÂ CategorizaêÂ§êÂ£o automêÂ¡tica
- ê°Å¸Å½Â¨ Tema moderno Material Design
- ê°Å¸Åâ Modo claro/escuro
- ê°Å¸âÂ± Responsivo

## ê°Å¸Å½Â¯ Categorias

### ê°Å¸Â¤â [AI Agents](https://linnoff88-dev.github.io/arckhe-/workflows/ai-agents/)
Agentes inteligentes com LLMs (GPT-4, Claude, etc), RAG pipelines, chatbots e sistemas HITL

**Destaques:**
- Agente de vendas com validaêÂ§êÂ£o humana
- First AI Agent com Google Sheets
- RAG Workflow vs RAG Agent
- Voice Email Agent

### ê°Å¸ââ [AutomaêÂ§êÂµes](https://linnoff88-dev.github.io/arckhe-/workflows/automations/)
Workflows para automatizar processos empresariais

**Destaques:**
- Customer Support Workflow
- LinkedIn Automation
- Invoice Processing
- WhatsApp Agent

### ê°Å¸âºÂ ê¯Â¸Â [IntegraêÂ§êÂµes](https://linnoff88-dev.github.io/arckhe-/workflows/integrations/)
Conectores com serviêÂ§os populares

**DisponêÂ­veis:**
- Google Drive, Sheets, Gmail
- Supabase / Postgres
- OpenAI, Perplexity
- Airtable, Firecrawl, Apify

### ê°Å¸âÅ¡ [Curso Completo](https://linnoff88-dev.github.io/arckhe-/curso/)
"The Ultimate n8n Course" com 23 liêÂ§êÂµes progressivas

## ê°Å¸Å¡â¬ Como Usar

### Acessar Online
Visite: [https://linnoff88-dev.github.io/arckhe-/](https://linnoff88-dev.github.io/arckhe-/)

### Rodar Localmente
```bash
# Clonar repositêÂ³rio
git clone https://github.com/linnoff88-dev/N8Np.git
cd N8Np

# Instalar dependêÂªncias
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

## ê°Å¸ââ Estrutura do RepositêÂ³rio

```
N8Np/
ê¢âÅê¢ââ¬ê¢ââ¬ Ref/                          # 532 workflows organizados por têÂ³pico
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ 2494913847/              # Grupo do Telegram
ê¢ââ       ê¢âÅê¢ââ¬ê¢ââ¬ [topic_id]/          # TêÂ³pico individual
ê¢ââ       ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ *.json          # Workflows n8n
ê¢ââ       ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ content.txt     # Conversa da comunidade
ê¢ââ       ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ metadata.json   # Metadados
ê¢ââ       ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ *.pdf           # DocumentaêÂ§êÂ£o
ê¢ââ       ê¢ââê¢ââ¬ê¢ââ¬ ...
ê¢âÅê¢ââ¬ê¢ââ¬ n8np-docs/                   # Site de documentaêÂ§êÂ£o
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ mkdocs.yml              # ConfiguraêÂ§êÂ£o
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ docs/                   # ConteêÂºdo markdown
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ site/                   # HTML gerado
ê¢âÅê¢ââ¬ê¢ââ¬ generate_docs.py             # Script de geraêÂ§êÂ£o
ê¢âÅê¢ââ¬ê¢ââ¬ CLAUDE.md                    # Guia para Claude Code
ê¢âÅê¢ââ¬ê¢ââ¬ RELATORIO_ANALISE.md        # AnêÂ¡lise do repositêÂ³rio
ê¢ââê¢ââ¬ê¢ââ¬ README.md                   # Este arquivo
```

## ê°Å¸ââ Atualizar DocumentaêÂ§êÂ£o

Se novos workflows forem adicionados:

```bash
# Regenerar documentaêÂ§êÂ£o
python3 generate_docs.py

# Deploy
cd n8np-docs
mkdocs gh-deploy
```

## ê°Å¸Â¤Â Contribuir

ContribuiêÂ§êÂµes sêÂ£o bem-vindas! Para adicionar workflows:

1. Adicione os arquivos `.json` em `Ref/2494913847/[novo_topico]/`
2. Execute `python3 generate_docs.py`
3. FaêÂ§a um Pull Request

## ê°Å¸ââ DocumentaêÂ§êÂ£o

- [CLAUDE.md](CLAUDE.md) - Guia para Claude Code trabalhar no repo
- [RELATORIO_ANALISE.md](RELATORIO_ANALISE.md) - AnêÂ¡lise completa do conteêÂºdo
- [IMPLEMENTACAO_COMPLETA.md](IMPLEMENTACAO_COMPLETA.md) - Detalhes da implementaêÂ§êÂ£o
- [n8np-docs/README.md](n8np-docs/README.md) - DocumentaêÂ§êÂ£o do site

## ê¢Å¡Â ê¯Â¸Â Importante

- Todos os workflows precisam de **credenciais reconfiguradas** apêÂ³s importaêÂ§êÂ£o
- Este êÂ© um **repositêÂ³rio de referêÂªncia**, nêÂ£o uma instalaêÂ§êÂ£o n8n ativa
- Sempre revise os workflows antes de usar em produêÂ§êÂ£o

## ê°Å¸ÅÅ¸ Destaques da Comunidade

### Workflow Mais Popular
**Agente de Vendas com ValidaêÂ§êÂ£o Humana**

Sistema completo de sales automation com loop de feedback humano usando Gmail "Send and Wait" + Text Classifier.

### Caso de Uso Real
**GeraêÂ§êÂ£o de MêÂºsicas AutomêÂ¡tica**

Workflow que gera mêÂºsicas com PiAPI e envia para Google Drive automaticamente.

## ê°Å¸âÅ¾ Comunidade

- ê°Å¸âÂ¬ [Telegram](https://t.me/n8np) - Comunidade N8Np
- ê°Å¸ÅÂ [Site](https://linnoff88-dev.github.io/arckhe-/) - DocumentaêÂ§êÂ£o oficial
- ê°Å¸âÂ§ Email: linnoff88-dev@gmail.com

## ê°Å¸ââ License

ConteêÂºdo compartilhado pela comunidade N8Np para uso educacional.

---

<p align="center">
  <strong>ê¢ÅÂ¨ Criado pela comunidade N8Np</strong><br>
  <em>1.1 GB de conteêÂºdo educacional | 532 workflows | 420 têÂ³picos</em>
</p>

<p align="center">
  <a href="https://linnoff88-dev.github.io/arckhe-/">ê°Å¸ÅÂ Visite o Site</a> ê¢â¬Â¢
  <a href="https://linnoff88-dev.github.io/arckhe-/workflows/">ê°Å¸âÂ Ver Workflows</a> ê¢â¬Â¢
  <a href="https://linnoff88-dev.github.io/arckhe-/curso/">ê°Å¸âÅ¡ Fazer Curso</a>
</p>

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>
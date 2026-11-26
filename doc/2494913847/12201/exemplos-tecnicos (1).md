
# Exemplos Técnicos – Agentes e Pipelines IA

Este documento acompanha o pacote de automações e agentes enviados no arquivo `modelos-json.zip`.

---

## 1. agente-atendimento-estilo.json
**Descriçêo:** Agente com respostas personalizadas no estilo Ferran Tort. Aplica coaching direto, sem listas e com estilo provocativo.
**Ideal para:** Automaçêo de atendimento via WhatsApp ou Telegram.

---

## 2. agente-rag-interativo.json
**Descriçêo:** RAG com controle estruturado de upload, eliminaçêo e formataçêo segura de mensagens para Telegram.
**Ideal para:** Atendimento baseado em documentos com regras de formataçêo.

---

## 3. agente-rag-delete.json
**Descriçêo:** Pipeline que remove arquivos tanto do Supabase quanto do Google Drive com base no ID do documento.
**Ideal para:** Manutençêo de base vetorial RAG.

---

## 4. pipeline-rag-avancado.json
**Descriçêo:** Pipeline completo que extrai texto de PDF e Excel, resume, e insere no Supabase com tratamento de arquivos e chunks.
**Ideal para:** Processamento automático de grandes volumes de documentos.

---

## 5. agente-rag-semantico.json
**Descriçêo:** Pipeline RAG com chunking semântico, identificaçêo de hierarquias de seções e mapeamento por índice no texto.
**Ideal para:** Documentaçêo técnica, legal, livros ou regulamentos.

---

## 6. chatbot-multicanal-ftd.json
**Descriçêo:** Pipeline educacional com fluxo multicanal, embeddings com Pinecone e orientaçêo de aprendizado contínuo.
**Ideal para:** Chatbots educativos com base em conhecimento estruturado.

---

## 7. rag-multimidia-imagens.json
**Descriçêo:** OCR de arquivos com imagens, gráficos ou tabelas usando Mistral AI + descriçêo visual + indexaçêo multimodal.
**Ideal para:** PDFs com conteúdo visual complexo.

---

## 8. pipeline-rag-dinamico.json
**Descriçêo:** Watcher dinâmico que detecta novos arquivos no Google Drive e atualiza automaticamente a base Supabase com embeddings.
**Ideal para:** Atualizaçêo contínua de repositórios de conhecimento.

---

## 9. enxame-de-agentes.json
**Descriçêo:** Agente orquestrador multimodal que recebe entrada por voz ou texto e direciona para subagentes como e-mail, calendário, etc.
**Ideal para:** Atendimento completo via Telegram com entrada multimodal.

---

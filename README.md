# Sistema de Busca Inteligente com PDFs

## 💡 Objetivo
Criar um sistema de busca inteligente que:
- Carregue arquivos PDF
- Indexe os textos usando embeddings semânticos
- Permita busca por similaridade vetorial
- Gere respostas com IA baseadas nos documentos

## ⚙️ Tecnologias usadas
- Python
- PyMuPDF
- Sentence Transformers
- FAISS
- OpenAI GPT (ou outro LLM)
- Streamlit (opcional)

## 📷 Prints
(Adicione prints mostrando seu código, a busca funcionando, respostas do chatbot)

## ✨ Insights
- A busca semântica é muito mais poderosa que a busca por palavra-chave.
- Modelos como `MiniLM` oferecem bom custo-benefício em termos de performance.
- Organizar a base em chunks com metadados ajuda bastante a rastrear respostas.

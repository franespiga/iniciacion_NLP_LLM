# Curso de LLMs y Aplicaciones de IA

## Descripción

Este curso proporciona una introducción completa a los Modelos de Lenguaje Grande (LLMs) y sus aplicaciones prácticas. Los notebooks están diseñados para ser **standalone** (independientes), con explicaciones en **español** y código/comentarios en **inglés**.

## Estructura del Curso

| Notebook | Tema | Duración | Dificultad |
|----------|------|----------|------------|
| 01 | Introducción a NLP y Embeddings Básicos | 2-2.5h | Básico |
| 02 | Embeddings con Transformers | 2-2.5h | Básico |
| 03 | Ingeniería de Prompts | 2-2.5h | Básico |
| 04 | Chatbots Básicos | 1.5-2h | Básico |
| 05 | Vector Stores y Retrieval | 2-2.5h | Intermedio |
| 06 | Introducción a RAG | 2.5-3h | Intermedio |
| 07 | Reranking y Optimización | 2h | Intermedio |
| 08 | Introducción a Agentes | 2-2.5h | Intermedio |
| 09 | Agentes con LangChain | 2.5-3h | Avanzado |
| 10 | LangGraph y Flujos | 2.5-3h | Avanzado |
| 11 | RAG Avanzado Agentic | 2.5-3h | Avanzado |
| 12 | Modelos de Gran Contexto y Multimodales | 2h | Avanzado |

## Progresión recomendada

```
Fundamentos (01-04)
       ↓
Retrieval (05-07)
       ↓
Agentes (08-10)
       ↓
Avanzado (11-12)
```

## Requisitos

### APIs (Gratuitas)
- **Groq API** (gratis): https://console.groq.com/keys
  - Tier gratuito generoso para modelos Llama 3.3
- **HuggingFace** (gratis): Modelos de embeddings open source

### Librerías principales
```bash
pip install langchain langchain-groq langchain-community langchain-huggingface
pip install sentence-transformers faiss-cpu
pip install langgraph
```

## Características

- **Sin costos de API**: Usa Groq (gratis) y modelos HuggingFace
- **Standalone**: Cada notebook es independiente
- **Práctico**: Código ejecutable con ejemplos reales
- **Progresivo**: De conceptos básicos a sistemas avanzados
- **Bilingüe**: Explicaciones en español, código en inglés

## Contenido por notebook

### 01 - Introducción a NLP y Embeddings Básicos
- One-Hot Encoding (Scikit-Learn, Keras)
- Word2Vec (modelo propio y pre-entrenados)
- GloVe
- Visualización con PCA

### 02 - Embeddings con Transformers
- BERT y BETO (español)
- Sentence Transformers
- Búsqueda semántica
- Visualización 3D con UMAP

### 03 - Ingeniería de Prompts
- Zero-shot y Few-shot
- Prompts con rol
- Chain of Thought
- Formato de salida
- Temperatura y diversidad

### 04 - Chatbots Básicos
- Chatbot basado en reglas
- Chatbot con LLM
- Memoria conversacional
- Interfaces con Streamlit

### 05 - Vector Stores y Retrieval
- FAISS
- Document Loaders
- Text Splitters
- Similarity Search
- Persistencia

### 06 - Introducción a RAG
- Arquitectura RAG
- Implementación paso a paso
- RAG con LangChain
- Memoria conversacional

### 07 - Reranking y Optimización
- Cross-Encoder
- Bi-Encoder
- LLM como Reranker
- Estrategias combinadas

### 08 - Introducción a Agentes
- Componentes de un agente
- Chain of Thought y ReAct
- Herramientas personalizadas
- Primer agente simple

### 09 - Agentes con LangChain
- Tipos de agentes
- Herramientas integradas
- Agente con RAG
- Memoria en agentes
- Salidas estructuradas

### 10 - LangGraph y Flujos
- Estados y grafos
- Flujos condicionales
- RAG con LangGraph
- Auto-corrección
- Checkpoints

### 11 - RAG Avanzado Agentic
- Arquitectura completa
- Clasificación de preguntas
- Reformulación de queries
- Verificación de calidad
- Evaluación

### 12 - Modelos de Gran Contexto y Multimodales
- Ventana de contexto
- LCM vs RAG
- CLIP
- Búsqueda de imágenes por texto
- Futuro de los LLMs

## Autor

Curso creado por Francisco Espiga Fernández

## Licencia

Material educativo para uso no comercial.

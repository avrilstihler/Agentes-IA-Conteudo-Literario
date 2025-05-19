# 📚 Sistema de Agentes IA para Conteúdo Literário com Gemini ✒️

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/avrilstihler/Agentes-IA-Conteudo-Literario/blob/main/sistema_agentes_livros_gemini.ipynb)


Este projeto utiliza o poder do Google Gemini e do Google Agent Development Kit (ADK) para criar um sistema inteligente capaz de gerar conteúdo rico e detalhado sobre livros e autores. Seja para uma resenha aprofundada, uma análise de autor ou um ponto de partida para discussões literárias, este sistema de agentes colabora para produzir textos informativos e envolventes.

---

## 🎯 Objetivo Principal

Automatizar e auxiliar na criação de conteúdo literário de qualidade, como resenhas de livros e análises de autores, utilizando uma cadeia de agentes de Inteligência Artificial especializados, cada um com uma função específica no processo de pesquisa, planejamento, redação e revisão.

---

## ✨ Funcionalidades Chave

O sistema é composto por um pipeline de **quatro agentes IA especializados**:

1.  **Agente Bibliotecário/Pesquisador de Livros 🧑‍🏫📖:**
    *   **Pesquisa Detalhada:** Coleta informações abrangentes sobre um livro específico (sinopse, autor, temas, recepção crítica, gênero) ou um autor (biografia, obras principais, estilo, prêmios) utilizando a ferramenta `google_search`.
    *   **Compilação Organizada:** Apresenta os dados de forma estruturada para fácil consulta pelos próximos agentes.

2.  **Agente Crítico Literário/Planejador 🗺️✍️:**
    *   **Análise Estratégica:** Avalia as informações coletadas pelo Agente Bibliotecário.
    *   **Criação de Esqueleto:** Desenvolve um plano estruturado e detalhado para a resenha do livro ou análise do autor, definindo seções chave (introdução, enredo, análise de personagens, temas, estilo, conclusão, etc.).
    *   **Orientação para Redação:** Fornece um guia claro para o Agente Redator.

3.  **Agente Resenhista de Livros/Redator ✍️📚:**
    *   **Redação Criativa e Informativa:** Com base no plano fornecido, escreve a resenha ou análise completa, com foco em profundidade, clareza e engajamento.
    *   **Linguagem Apropriada:** Utiliza um tom adequado para amantes de livros, equilibrando análise crítica com paixão pela leitura.
    *   **Desenvolvimento de Conteúdo:** Expande cada ponto do plano, criando um texto coeso e rico em detalhes.

4.  **Agente Editor Literário/Revisor ✅🧐:**
    *   **Controle de Qualidade:** Revisa meticulosamente o rascunho produzido pelo Agente Redator.
    *   **Critérios de Avaliação:** Verifica clareza, coerência, profundidade da análise, correção gramatical, estilo, ausência de spoilers indevidos e adequação ao público.
    *   **Feedback Construtivo:** Aprova o texto se estiver excelente ou fornece sugestões específicas para melhoria, podendo até reescrever trechos.

---

## 🛠️ Tecnologias Utilizadas

*   Python 🐍
*   Google Gemini API (`google-genai`) - Modelo `gemini-2.0-flash` (ou outro de sua escolha)
*   Google Agent Development Kit (`google-adk`)
*   Google Search (como ferramenta dos agentes)
*   Google Colaboratory (ambiente de execução)

---

## ⚙️ Como Usar

1.  **API Key 🔑:** Obtenha sua API Key do Google Gemini no [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  **Abra no Colab:** Clique no botão "Open In Colab" no topo deste README.
3.  **Configure a API Key:** No Colab, vá em "Secrets" (ícone de chave 🔑) e adicione sua `GOOGLE_API_KEY`.
4.  **Execute o Notebook:** Rode as células do notebook em ordem.
5.  **Interaja:** Quando solicitado, digite o nome do livro ou autor sobre o qual deseja gerar conteúdo.
6.  **Acompanhe o Processo:** Observe a saída de cada agente, desde a coleta de informações até a revisão final do texto.

---

## 📄 Licença
Este projeto está licenciado sob a licença MIT.

Para mais detalhes, consulte o arquivo [LICENSE](./LICENSE).

---

Este sistema é um exemplo poderoso de como a IA pode ser uma ferramenta valiosa para criadores de conteúdo, pesquisadores e entusiastas da literatura! Sinta-se à vontade para experimentar e adaptar! 🎉

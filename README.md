# 🤖 Imersão Agentes de IA: Portfólio de Projetos  

Este repositório serve como um portfólio para os estudos e projetos desenvolvidos na área de **Agentes de IA**.  
Inclui o material do curso intensivo da **Alura**, bem como um projeto pessoal focado na aplicação e validação dos conhecimentos adquiridos.  


## ℹ️ Visão Geral da Imersão  

Este projeto é resultado da **Imersão de Agentes de IA da Alura**, um programa educacional intensivo de três aulas que abordou os seguintes conceitos fundamentais:  

- **Classificação de intenções com IA**  
  Interpretação e categorização da intenção do usuário a partir da análise das mensagens.  

- **Construção de base de conhecimento com RAG**  
  Utilização da arquitetura **RAG (Retrieval-Augmented Generation)** para fornecer contexto e dados externos ao modelo de IA.  

- **Orquestração de agente com LangGraph**  
  Criação de fluxos de trabalho complexos e encadeamento de diferentes ações e modelos de IA para tarefas mais elaboradas.  


## 🚀 Tecnologias Utilizadas  

- **Python** → Linguagem principal utilizada.  
- **Google Gemini API** → Modelo de linguagem de grande escala (LLM) empregado para processamento e geração de texto.  
- **LangChain** → Framework para facilitar o desenvolvimento e a orquestração de aplicações baseadas em LLMs.  
- **Pydantic** → Biblioteca para validação de dados e conversão das saídas da IA em classes tipadas.  
- **Google Colab** → Ambiente de desenvolvimento utilizado para a execução do código.  
- **Gradio** → Criação de uma interface web simples e interativa para interação com o agente.
- **Hugging Face Spaces** → Hospedagem do projeto em um ambiente acessível via navegador.

## 🌐 Versão Web  

Além do notebook, este projeto conta com uma versão **web interativa** criada com **Gradio**, onde é possível conversar diretamente com o agente e explorar os fluxos implementados.  

👉 Acesse aqui: [Imersão Agentes de IA - Web (Hugging Face Spaces)](https://huggingface.co/spaces/helosalgado/imersao-alura-ia)  

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/HeloSalgado/imersao-dev-agentes-IA.git
    ```
2. Abra no Google Colab: Aceda ao repositório clonado e abra o notebook desejado (por exemplo, Imersao-agentes-IA.ipynb) no Google Colab.

3. Configure a sua Chave de API: Para que o código funcione, é necessário adicionar a sua chave de API do Gemini no Google Colab.
    - No painel lateral esquerdo, selecione o ícone de chave (Secret Manager).
    - Adicione uma nova variável secreta com o nome GEMINI_API_KEY e cole o valor da sua chave.

4. Instale as dependências.

5. Execute o restante do código: Continue a execução das células para interagir com o modelo e explorar os exemplos.
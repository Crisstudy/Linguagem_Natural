# 🔤 Processamento de Linguagem Natural (PLN) - Análise de Legendas e Textos

Repositório dedicado ao estudo e desenvolvimento de rotinas de **Processamento de Linguagem Natural (PLN)** e **Mineração de Textos** em Python. O projeto abrange desde a ingestão de dados não estruturados até a tokenização e análise semântica utilizando a biblioteca **spaCy**.

---

## 📌 Escopo do Projeto

- **Ingestão e Extração de Dados:** Download programático e leitura de arquivos de texto (`.txt`) e bases estruturadas (`.csv`).
- **Limpeza e Normalização:** Tratamento de codificação (`utf-8`), remoção de ruídos e padronização de caracteres.
- **Processamento de Texto com PLN:** Tokenização, remoção de *stop words*, lematização e análise de frequência.
- **Análise Aplicada:** Aplicação prática em conjuntos de dados de avaliações de clientes (*e-commerce*) e transcrições/legendas.

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python 3.9
- **Ambiente de Desenvolvimento:** Visual Studio Code / Jupyter Notebooks
- **Processamento de Dados:** `pandas`
- **PLN & NLP:** `spaCy` (Modelo: `pt_core_news_sm`)
- **Utilitários:** `urllib`, `collections.Counter`
- **Controle de Versão:** Git / GitHub / GitHub Desktop

---

## 📂 Estrutura do Repositório

text
Linguagem_Natural/
├── venv/                       # Ambiente virtual (ignorado no versionamento)
├── processamento-LN.ipynb      # Notebook com pipeline de PLN
├── breaking-bad-s01e01.txt     # Dataset de texto extraído para análise
├── .gitignore                  # Arquivos e pastas excluídos do Git
└── README.md                   # Documentação do repositório


🚀 Como Executar o Projeto Localmente
1. Clonar o Repositório
   git clone [https://github.com/Crisstudy/Linguagem_Natural.git](https://github.com/Crisstudy/Linguagem_Natural.git)
   cd Linguagem_Natural

2. Criar e Ativar o Ambiente Virtual (venv)
macOS / Linux:
   python3 -m venv venv
   source venv/bin/activate

3. Instalar as Dependências e o Modelo de Linguagem
     pip install pandas spacy ipykernel
     pip install [https://github.com/explosion/spacy-models/releases/download/pt_core_news_sm-3.7.0/pt_core_news_sm-3.7.0-py3-none-any.whl](https://github.com/explosion/spacy-models/releases/download/pt_core_news_sm-3.7.0/pt_core_news_sm-3.7.0-py3-none-any.whl)

**4. Executar o Notebook
Abra o VS Code, selecione o Kernel da venv (Python 3.9) no canto superior direito do arquivo processamento-LN.ipynb e execute as células.**

Desenvolvido por Prof. Elvis de Souza

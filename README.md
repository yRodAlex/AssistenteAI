# AssistenteAI

Projeto: **Assistente AI**  
Descrição: implementação de um assistente baseado em IA para o “Caso 1 – Curso de Data Science”.  
Linguagem principal: Python  
Autor / Mantenedor: yRodAlex  

---

## Índice

- [Visão Geral](#visão-geral)  
- [Funcionalidades](#funcionalidades)  
- [Arquitetura / Estrutura do Projeto](#arquitetura--estrutura-do-projeto)  
- [Requisitos](#requisitos)  
- [Instalação](#instalação)  
- [Uso / Exemplos](#uso--exemplos)  
- [Configuração / Parâmetros](#configuração--parâmetros)  
- [Como Contribuir](#como-contribuir)  
- [Licença](#licença)  
- [Contato](#contato)  

---

## Visão Geral

O *AssistenteAI* é um projeto que propõe um agente inteligente de suporte para responder perguntas, auxiliar em análise de dados ou interagir com o usuário de forma dinâmica — parte de um estudo de caso para o curso de Data Science.  

O projeto utiliza **Python**, **Streamlit** e a **API do Groq** para criar uma interface web interativa que permite conversar com o modelo de linguagem.

---

## Funcionalidades

- Interface web simples via **Streamlit**  
- Integração com a API do **Groq**  
- Receber perguntas e comandos do usuário  
- Processamento de linguagem natural para gerar respostas  
- Estrutura flexível para novas funcionalidades  

---

## Arquitetura / Estrutura do Projeto
├── README.md
├── requirements.txt
├── dsa_assistente.py
└── recursos_adicionais/ (se houver)


- `dsa_assistente.py` — script principal com a lógica do assistente  
- `requirements.txt` — dependências do projeto  
- (Opcional) imagens, dados de exemplo, scripts auxiliares  

---

## Requisitos

- Python 3.8 ou superior  
- Dependências listadas em `requirements.txt`  

Principais bibliotecas:  
- `streamlit`  
- `groq`  
- `pandas` (se manipular dados)  
- `numpy` (se realizar cálculos numéricos)  

---

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/yRodAlex/AssistenteAI.git
   cd AssistenteAI

---

Crie e ative um ambiente virtual:
Linux 

python3 -m venv .venv
source .venv/bin/activate

---

Configuração / Parâmetros:
export GROQ_API_KEY="sua_chave_aqui"

---

Uso / Exemplos
streamlit run dsa_assistente.py

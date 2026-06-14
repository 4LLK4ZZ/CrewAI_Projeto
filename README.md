# 👥 CrewAI Multi-Agent Systems

Este repositório foi desenvolvido para organizar e estruturar meus estudos e projetos práticos utilizando o framework **CrewAI**. O objetivo é explorar a criação, orquestração e colaboração de múltiplos agentes de Inteligência Artificial trabalhando em equipe para resolver problemas complexos.

---

## 📂 Estrutura do Repositório

O projeto está dividido nas seguintes pastas e arquivos principais:

| Diretório / Arquivo | Descrição                                                                                                                                                                 |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📂 `create_crew/`   | Módulo dedicado à criação, configuração e definição das equipes (Crews), incluindo a atribuição de papéis (*Roles*), objetivos (*Goals*) e tarefas (*Tasks*) dos agentes. |
| 📂 `projeto_novo/`  | Ambiente para o desenvolvimento e teste de novas implementações, fluxos de trabalho isolados ou automações específicas.                                                   |
| `.gitignore`        | Arquivo de configuração para ignorar arquivos temporários e variáveis de ambiente confidenciais (como arquivos `.env`).                                                   |
| `requirements.txt`  | Arquivo contendo todas as dependências e bibliotecas Python necessárias para a execução do ecossistema.                                                                   |

---

## 🛠️ Tecnologias e Conceitos Utilizados

* Python 3.10+
* CrewAI Framework — Orquestração de agentes baseados em papéis.
* LangChain / Agno — Integrações, conectores e ferramentas personalizadas para os agentes.
* Modelos de Linguagem (LLMs) — Integração com APIs externas (OpenAI, Gemini, Claude) ou modelos locais (Ollama).

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/4LLK4ZZ/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO
```

### 2. Configure o ambiente virtual

```bash
python -m venv .venv
```

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

```bash
source .venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Configure as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto para armazenar suas credenciais.

> ⚠️ Nunca envie este arquivo para o GitHub.

```env
OPENAI_API_KEY=seu_token_aqui

# Ou, dependendo do provedor configurado:
GEMINI_API_KEY=seu_token_aqui
```

---

## 🧠 Fluxo de Trabalho Base do CrewAI

O desenvolvimento neste repositório segue a arquitetura padrão do CrewAI:

### Agents

Definição dos especialistas responsáveis pela execução das tarefas.

**Exemplos:**

* Pesquisador
* Escritor
* Analista Financeiro
* Desenvolvedor

### Tasks

Definição clara do que cada especialista precisa entregar, incluindo contexto, objetivos e resultado esperado.

### Crew

União dos agentes e tarefas em um fluxo coordenado, que pode ser executado de forma:

* Sequencial
* Hierárquica
* Personalizada conforme a necessidade do projeto

---

## 🎯 Objetivos do Repositório

* Aprender e aplicar conceitos de sistemas multiagentes.
* Desenvolver automações inteligentes utilizando CrewAI.
* Experimentar integrações com diferentes LLMs.
* Criar fluxos colaborativos entre agentes especializados.
* Consolidar boas práticas de engenharia de prompts e orquestração de agentes.

---

## 📌 Observações

* Utilize ambientes virtuais para manter as dependências isoladas.
* Armazene credenciais apenas em arquivos `.env`.
* Mantenha o arquivo `.gitignore` atualizado para evitar o envio de informações sensíveis ao repositório.

---

## 👨‍💻 Autor

Desenvolvido por **4LLK4ZZ**.

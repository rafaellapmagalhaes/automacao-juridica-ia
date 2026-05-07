# ⚖️ Automação Jurídica com IA

## 👋 Oii!

Meu nome é Rafaella Magalhães e esse projeto foi desenvolvido como uma forma de aprender mais sobre automação, APIs, Python e Inteligência Artificial aplicada a ambientes reais.

A ideia surgiu pensando em como escritórios de advocacia ainda gastam MUITO tempo organizando manualmente informações de clientes, preenchendo planilhas e separando processos. Então resolvi criar um sistema simples, mas extremamente funcional, usando IA para automatizar tudo isso.

Esse projeto utiliza Python + Claude API + Google Sheets para transformar textos desorganizados em dados estruturados automaticamente.

---

# 🚀 Sobre o Projeto

O sistema recebe textos contendo informações de clientes e utiliza a IA do Claude para:

- identificar nomes
- separar CPF
- identificar o tipo de processo
- gerar um resumo automático
- organizar tudo em JSON
- enviar automaticamente para uma planilha do Google Sheets

Na prática, isso significa que o usuário pode simplesmente colar vários textos de clientes e deixar a IA fazer todo o trabalho pesado!

---

# 🚀 Tecnologias Utilizadas

* Python
* Claude API
* Google Sheets API
* Google Drive API
* Google Cloud
* VS Code

---
# 💡 Por que esse projeto é útil?

Esse tipo de automação pode economizar MUITO tempo em ambientes jurídicos.

Em vez de:
- ler cliente por cliente
- preencher planilhas manualmente
- organizar informações sozinho

o sistema automatiza praticamente tudo.

Além disso, o projeto mostra como IA pode ser usada em aplicações reais e úteis, e não apenas como chatbot.

---

# 🛠️ Tecnologias Utilizadas

## 🐍 Python

Linguagem principal do projeto. Responsável por conectar tudo.

---

## 🤖 Claude API

IA utilizada para interpretar e organizar os textos automaticamente.

---

## 📊 Google Sheets API

Utilizada para enviar os dados diretamente para a planilha.

---

## ☁️ Google Cloud

Usado para:
- ativação das APIs
- autenticação
- geração das credenciais JSON

---

## 💻 VS Code

Editor utilizado para desenvolvimento do projeto.

---

# 📦 Funcionalidades

- ✔ Cadastro automático de clientes
- ✔ Processamento de múltiplos clientes de uma vez
- ✔ Integração com IA
- ✔ Organização automática de dados
- ✔ Conversão para JSON
- ✔ Integração com Google Sheets
- ✔ Automação jurídica
- ✔ Estrutura escalável

---

# ☁️ Configuração do Google Cloud

## 1. Criar Projeto

Acesse:

[https://console.cloud.google.com/](https://console.cloud.google.com/)

Crie um novo projeto.

---

## 2. Ativar APIs

Ative:

* Google Sheets API
* Google Drive API

---

## 3. Criar Conta de Serviço

* APIs e Serviços
* Credenciais
* Criar Credenciais
* Conta de Serviço

---

## 4. Gerar JSON

Na conta criada:

* Keys
* Add Key
* Create New Key
* JSON

Baixe o arquivo.

Renomeie para:

```bash
credenciais.json
```

---

## 5. Compartilhar Planilha

Compartilhe sua planilha do Google Sheets com o e-mail da conta de serviço.

Permissão:

```bash
Editor
```
---

# 🐍 Código Principal

Está no repositório codigopython.

---
# ⚙️ Instalação e Execução

Para executar este projeto, siga os passos abaixo:

1. Clone o repositório
git clone URL_DO_REPOSITORIO
2. Acesse a pasta do projeto
cd projeto
3. Instale as dependências

Todas as bibliotecas necessárias estão listadas no arquivo requirements.txt.

```bash
pip install -r requirements.txt
```
---
#📦 Dependências utilizadas

Este projeto utiliza as seguintes bibliotecas:

```bash
anthropic
gspread
oauth2client
```

---
#🔐 Configuração das credenciais

Para o funcionamento correto do projeto, é necessário configurar o arquivo credenciais.json, obtido através do Google Cloud (Google Sheets API e Google Drive API).

---

# ▶️ Como Executar

No terminal:

```bash
py -3.12 NomedoProjeto.py
```

---

# 🧪 Exemplo de Entrada

```text
João Silva CPF 11122233344 entrou com ação trabalhista por demissão sem direitos.

Maria Souza CPF 99988877766 quer solicitar pensão alimentícia.

Carlos Pereira CPF 55544433322 sofreu golpe bancário e quer processo contra o banco.

FIM
```

---

# 📊 Resultado Esperado

| Nome           | CPF         | Processo    | Resumo                |
| -------------- | ----------- | ----------- | --------------------- |
| João Silva     | 11122233344 | Trabalhista | Demissão sem direitos |
| Maria Souza    | 99988877766 | Família     | Pensão alimentícia    |
| Carlos Pereira | 55544433322 | Civil       | Golpe bancário        |

---

# 👩‍💻 Desenvolvido por

Rafaella Magalhães

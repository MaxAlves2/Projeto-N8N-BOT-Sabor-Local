# Projeto-N8N-BOT-Sabor-Local
# 🤖 Projeto Sabor Local - Automação N8N & Telegram

<p align="center">
  <img src="https://img.shields.io/badge/n8n-Automated-FF6F61?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/Telegram-Chatbot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge" alt="Status">
</p>

---

## 📝 Sobre o Projeto

O **Sabor Local** é um chatbot inteligente desenvolvido para a plataforma **Telegram**, totalmente integrado e automatizado utilizando o **n8n**. O objetivo principal deste projeto é otimizar o atendimento ao cliente, automatizando fluxos de conversas, processamento de pedidos e interações em tempo real de forma eficiente e escalável.

Este repositório contém o arquivo de exportação em formato `.json` com o workflow completo pronto para ser importado no n8n.

---

## 🚀 Funcionalidades

* 💬 **Atendimento Automatizado:** Respostas rápidas e fluxos de conversa inteligentes via Telegram.
* 🔄 **Integração Ponta a Ponta:** Workflow estruturado no n8n para gerenciar os gatilhos e respostas de forma assíncrona.
* 📦 **Pronto para Implantação:** Estrutura modular que permite fácil manutenção e expansão para novas ferramentas (como bancos de dados ou planilhas).

---

## 🛠️ Tecnologias Utilizadas

* [n8n](https://n8n.io/) – Ferramenta de automação de fluxo de trabalho baseada em nós.
* [Telegram Bot API](https://core.telegram.org/bots/api) – Interface para comunicação e recepção de mensagens do usuário.
* [JSON](https://www.json.org/) – Formato de estruturação de dados para exportação/importação do workflow.
* [Google AI Studio](https://aistudio.google.com/api-keys?project=gen-lang-client-0614371395) – Criar e resgatar uma chave de API 
---

## 🔧 Como Replicar este Projeto

Para rodar este chatbot na sua própria instância do n8n, siga os passos abaixo:

1.  **Criar um Bot no Telegram:**
    * Converse com o `@BotFather` no Telegram e crie um novo bot para obter o seu **API Token**.
2.  **Importar o Workflow no n8n:**
    * Baixe o arquivo `Sabor Local - Chatbot Completo.json` deste repositório.
    * No seu painel do n8n, crie um novo fluxo, clique no menu de opções (três pontos no canto superior direito) e selecione **Import do File**.
3.  **Configurar as Credenciais:**
    * Abra o nó do Telegram dentro do n8n e insira o seu **API Token** gerado no passo 1.
    * Abra um nó do Google Gemini e utilize a chave de API resgatada.
4.  **Ativar o Fluxo:**
    * Altere o status do workflow de `Inactive` para **Active**.

---

## 📁 Estrutura de Arquivos

```text
├── Sabor Local - Chatbot Completo.json  # Workflow completo exportado do n8n
└── README.md                            # Documentação do projeto

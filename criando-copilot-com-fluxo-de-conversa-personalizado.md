## 🚀 Desafio DIO – Bootcamp Suzano: Criando um Copilot com Fluxo de Conversa Personalizado

Este documento resume as etapas do desafio proposto pela DIO no Bootcamp **Suzano – Python Developer**, cujo objetivo é criar um agente com fluxo de conversa personalizado utilizando o **Microsoft Copilot Studio**.

---

### ✅ Requisitos

- Conta Microsoft 365 ativa
- Acesso a um computador com navegador

---

### 🧭 Etapas do Projeto

#### 1. Criando um Copilot em Branco

- Acesse: [copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)
- Crie um agente novo, preferencialmente com idioma em inglês.
- Informe:
  - Nome do agente
  - Descrição
  - Prompt com instruções
- (Opcional) Adicione uma base de conhecimento.
- Clique em **Create**.

---

#### 2. Customizando um Tópico

- Navegue até **Topics** → **Add topic** → escolha o template em branco.
- Defina frases de gatilho, como:
  - “buscar informações de AI Builder”
  - “o que é AI Builder”
- Clique no símbolo de ➕ para adicionar um **node**:
  - Escolha: **Advanced** → **Generative answers**
- Na aba **System**, mantenha as configurações padrão de **Data sources**.
- Adicione novo node ➕ e selecione **Send a message** com texto de encerramento como:
  > “Tópico de AI Builder encerrado!”
- Renomeie o tópico (ex: de “Untitled” para “AI Builder”) e clique em **Save**.

---

#### 3. Personalizando a Mensagem de Erro

- Acesse: **Conversational Boosting** dentro de **Topics**
- No fluxo **All other conditions**, clique em **Send a message**
- Escreva sua mensagem de erro personalizada, como:
  > “Desculpe, não entendi. Pode reformular sua pergunta?”

---

#### 4. Ajustando a Qualidade das Respostas com GenAI

- Em **Conversational Boosting** → **Create generative answers** → clique em **Edit** (em **Data Sources**)
- Na lateral direita:
  - **Knowledge sources**: adicione base de conhecimento
  - **Classic data**: permite uso do conhecimento geral da IA
  - **Content moderation level**: escolha entre `low`, `medium`, `high`
  - Use a variável `Activity.Text` como base para o prompt de pesquisa

✅ Alternativamente:
- Vá em **Settings** → **Generative AI**
- Ajuste configurações globais de uso de IA para todo o agente (não apenas para um único tópico)

---

### 🔗 Links Úteis

- [Microsoft Learn](https://learn.microsoft.com)
- [Digital Innovation One (DIO)](https://www.dio.me)
- [Romão’s Learn](https://romaos.com.br/learn)

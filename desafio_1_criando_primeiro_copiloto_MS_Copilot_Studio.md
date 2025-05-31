
# Desafio DIO – Bootcamp Suzano: Criando seu Primeiro Copiloto com Microsoft Copilot Studio

Este documento resume as etapas do desafio proposto pela DIO no Bootcamp **Suzano – Python Developer**, cujo objetivo é criar um primeiro copiloto utilizando o **Microsoft Copilot Studio**.

---

## ✅ Requisitos

- Conta no **Microsoft 365** (pode ser gratuita)
- Um computador com acesso à internet

---

## 🚀 Etapas do Desafio

### 🔹 Etapa 1 – Acesso à Plataforma

1. Acesse: [https://copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)
2. Faça login com sua conta Microsoft 365.
   - ⚠️ **Importante**: Contas do Outlook ou Hotmail **não funcionam** para esta finalidade.

---

### 🔹 Etapa 2 – Criar um Copilot com Base em Modelo

1. Na página inicial, escolha o modelo **"Safe Travels"**.
2. Preencha as seguintes informações:
   - **Nome** do agente
   - **Ícone** (opcional)
   - **Descrição** para facilitar manutenções futuras
   - **Instruções** de comportamento via prompts
     - Recomenda-se escrever as instruções em **inglês** para melhor eficiência.

     **Exemplo de prompt:**
     ```
     You are a travel expert specialized in international trips departing from Brazil. 
     You should respond politely and professionally. 
     You represent the company DIO and your name is DIO's travel agent.
     ```

3. Em **Knowledge**, selecione ou confirme a base de conhecimento padrão.
4. Ajuste a **língua principal** do bot em “Edit language”.
   - Futuramente será possível adicionar múltiplos idiomas.
5. Clique em **Create**. O agente será criado e você será redirecionado ao painel de controle.

---

### 🔹 Etapa 3 – Criar um Copilot com Base em Descrição

1. Na página inicial, em vez de escolher um modelo, digite uma descrição na caixa:  
   **"Describe your agent to create it"**.

   **Exemplo de descrição:**
   ```
   I would like to create an agent with Brazilian data from traveling across the world.
   ```

   - Instruções funcionam melhor em **inglês**.
   - Pode-se buscar **modelos de prompt** prontos na internet.

2. Clique em **Next** para prosseguir com a criação.
3. Edite os campos:
   - **Nome**
   - **Ícone**
   - **Descrição**
   - **Instruções**
   - **Knowledge**

   As configurações seguem os mesmos princípios da etapa anterior.

---

### 🔹 Etapa 4 – Criar um Copilot em Branco

1. Clique em **Create** no menu lateral e selecione **New agent**.
2. Configure as seguintes informações:
   - **Nome**
   - **Ícone**
   - **Descrição**
   - **Instruções**
   - **Knowledge**

   - 💡 **Recomendação**: não adicione nenhuma base de conhecimento neste momento, pois ainda estamos definindo a arquitetura do agente.

3. Clique no menu `...` para acessar configurações avançadas, como:
   - **Solution**
   - **Schema name**

4. Clique em **Create**.

   - ⏳ Aguarde alguns minutos após a criação para que o agente seja **treinado** antes de iniciar os testes.

---

## 📌 Observações Finais

- Sempre que possível, escreva prompts e instruções em **inglês**, pois isso melhora a interpretação pela IA.
- Teste e itere seu agente após a criação para garantir que ele está se comportando conforme esperado.

---

## 📎 Links Úteis

- [Microsoft Copilot Studio](https://copilotstudio.microsoft.com)
- [Bootcamp DIO – Suzano Python Developer](https://www.dio.me)

---

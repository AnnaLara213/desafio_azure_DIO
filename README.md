# desafio_azure_DIO
# 🎯 Análise de Sentimentos com o Language Studio — Azure AI

Este projeto demonstra como utilizar o **Language Studio**, uma ferramenta do Azure AI, para realizar **análise de sentimentos** em textos. A análise identifica emoções como **positiva**, **negativa**, **neutra** ou **mista**, com base no conteúdo fornecido.

---

## 🧠 O que é Análise de Sentimentos?

A **análise de sentimentos** é uma técnica de **Processamento de Linguagem Natural (PLN)** que detecta emoções e opiniões em textos. Ideal para entender o que usuários ou clientes estão dizendo sobre produtos, serviços ou marcas.

---

## 🚀 Como usar no Azure Language Studio

### 1. Acesse o Language Studio

- Acesse: [https://language.cognitive.azure.com](https://language.cognitive.azure.com)
- Faça login com sua conta Microsoft
- Caso necessário, crie um recurso **Azure AI Language** no [portal do Azure](https://portal.azure.com)

### 2. Inicie uma análise

- Clique em **"Analisar texto"** ou selecione **“Sentiment Analysis”**
- Digite ou cole o texto que deseja analisar (ex: "O atendimento foi ótimo, mas o produto estava danificado.")
- Clique em **“Run”**

### 3. Interprete os resultados

- O Language Studio exibirá o **sentimento geral** (positivo, negativo, neutro ou misto)
- Mostrará também a **análise por frase**
- Os resultados incluem **pontuações de confiança**

---

## 🧪 Exemplo de Entrada e Saída

**Texto de entrada**:
> "A entrega foi rápida, mas o produto veio com defeito."

**Saída esperada**:
- Sentimento geral: `Misto`
- Frase 1: Positiva → "A entrega foi rápida."
- Frase 2: Negativa → "O produto veio com defeito."

---

## 🛠️ Aplicações

- Análise de feedback de clientes
- Monitoramento de redes sociais
- Classificação automática de tickets de suporte
- Inteligência de mercado

---

## 💡 Requisitos

- Conta no Microsoft Azure
- Recurso **Azure AI Language** criado
- (Opcional) Chave de API e endpoint para uso via SDK ou REST API

---

## 📚 Recursos

- [Documentação Oficial — Azure AI Language](https://learn.microsoft.com/azure/cognitive-services/language-service/overview)
- [Azure Language Studio](https://language.cognitive.azure.com/)
- [Exemplos com SDKs (Python, C#, etc.)](https://learn.microsoft.com/azure/cognitive-services/language-service/sentiment-opinion-mining/quickstart)

---

## 📄 Licença

Este projeto é apenas demonstrativo e não possui licença comercial atribuída.

# Desafio de Proejto: Análise de Sentimentos com Language Studio no Azure AI

Este repositório tem como objetivo documentar a prática, os experimentos e os aprendizados adquiridos durante a exploração das ferramentas **Azure Speech Studio** e **Language Studio**, com foco na **análise de fala** e **processamento de linguagem natural (PLN)**.

## 🎯 Objetivo

Desenvolver habilidades práticas na criação de soluções de inteligência artificial com foco em **voz** e **linguagem**, utilizando os recursos disponibilizados pela Microsoft Azure. O conteúdo aqui apresentado serve como material de apoio para **estudos**, **prototipagem de soluções** e **futuras implementações em projetos reais**.

## 📁 Estrutura do Repositório

📂 azure-speech-language-practice/
├── 📁 speech-studio/
│   ├── notas-speech.md
│   ├── exemplos-transcricao/
│   └── insights-modelagem-voz.md
├── 📁 language-studio/
│   ├── notas-language.md
│   ├── exemplos-anotacoes-texto/
│   └── insights-classificacao-intencao.md
├── 📁 datasets/
│   └── samples/
├── 📄 README.md
└── 📄 LICENSE

## 🗣️ Exploração do Azure Speech Studio

O [Speech Studio](https://speech.microsoft.com/) é uma ferramenta para criação, teste e implantação de soluções de IA com voz. Nesta seção, exploramos:

### ✅ Funcionalidades Praticadas

- Transcrição de áudio em tempo real (Speech to Text)

- Conversão de texto em fala (Text to Speech)

- Criação de modelos personalizados de voz

- Análise de sentimentos e entidades em áudio

- Extração de palavras-chave de conversas gravadas

### 🧪 Experimentos Realizados

- 🎧 **Teste de transcrição com diferentes sotaques**

- 🗣️ **Criação de uma voz personalizada com samples**

- 📝 **Comparação entre modelos predefinidos e personalizados**

- 📊 **Análise da precisão na transcrição com ruído de fundo**

### 📓 Insights

- A personalização melhora significativamente a fidelidade da transcrição em domínios específicos.

- A qualidade do áudio de entrada impacta diretamente o desempenho do modelo.

- Modelos multilingues são eficazes, mas requerem treinamento contextual para maior acurácia.

## 🧾 Exploração do Azure Language Studio

O [Language Studio](https://language.azure.com/) permite aplicar análises avançadas em texto, como extração de entidades, análise de sentimentos e classificação.

### ✅ Funcionalidades Praticadas

- Análise de sentimentos (positivo, neutro, negativo)

- Extração de entidades nomeadas (NER)

- Classificação de intenção e tópicos

- Tradução e detecção de idioma

- Criação de projetos de linguagem personalizada

### 🧪 Experimentos Realizados

- 🗂️ **Classificação automática de e-mails por intenção**

- 📄 **Extração de entidades em textos jurídicos**

- 🌐 **Tradução multilíngue com análise de sentimento**

- 🧠 **Criação de um projeto de linguagem customizado com rótulos manuais**

### 📓 Insights

- A análise de sentimentos é sensível ao idioma e ao contexto cultural.

- A categorização manual com rótulos aumenta a precisão em domínios específicos.

- Entidades personalizadas podem ser treinadas para identificar termos técnicos ou específicos da empresa.

## 📚 Recursos de Apoio

- [Documentação oficial Speech Services](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/)

- [Documentação do Azure Language Studio](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/)

- [Exemplos de uso do Azure Cognitive Services](https://github.com/Azure-Samples)

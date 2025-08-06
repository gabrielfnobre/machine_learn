# 🗣️ Processamento de Linguagem Natural (PLN / NLP)

## 📖 O que é?
***Processamento de Linguagem Natural*** (do inglês, ***Natural Language Processing – NLP***) é uma subárea da Inteligência Artificial que permite que máquinas compreendam, interpretem, gerem e interajam com a linguagem humana, seja ela escrita ou falada.

Em outras palavras, o PLN é o que permite que computadores leiam, escrevam, escutem e até conversem com pessoas, tornando a comunicação entre humanos e máquinas mais natural.

## 🧾 Origem e histórico
O PLN começou a se desenvolver a partir da década de **1950**, com projetos iniciais de tradução automática entre línguas. Um marco foi o ***teste de Turing***, proposto por **Alan Turing**, que questionava se uma máquina poderia conversar de forma indistinguível de um humano.

Inicialmente baseado em regras linguísticas e gramáticas formais, o PLN evoluiu nas décadas seguintes com abordagens estatísticas (anos 1990) e, mais recentemente, com ***deep learning*** e ***modelos de linguagem pré-treinados***, como o **BERT**, **GPT** e **T5**.

## 💡 O que realmente significa?
PLN envolve uma série de tarefas relacionadas à linguagem, como:
* Análise sintática (parsing)
* Reconhecimento de entidade (NER)
* Classificação de texto
* Geração de texto
* Tradução automática
* Análise de sentimentos
* Chatbots e assistentes virtuais
* Transcrição de fala (ASR)
* Resposta automática a perguntas

O desafio central do PLN é lidar com a ambiguidade, contexto, ironia, gírias e variações linguísticas da linguagem humana.

## 🧰 Aplicações no ambiente de trabalho
### ✅ Exemplos práticos:
* Chatbots inteligentes para atendimento ao cliente
* Análise de sentimentos em redes sociais ou feedbacks
* Classificação automática de e-mails e documentos
* Extração de dados de contratos, notas fiscais, boletins
* Detecção de spam
* Reconhecimento de voz (speech-to-text)
* Tradução automática (Google Tradutor, DeepL)
* Assistentes virtuais (Alexa, Siri, Google Assistant)

### 🗣️ Como usar a terminologia com clareza:
* ***“Estamos usando PLN para classificar os chamados abertos por categoria.”***
* ***“Essa IA usa modelos de linguagem para gerar respostas automaticamente.”***
* ***“O PLN extrai as entidades-chave dos documentos, como nome, data e valor.”***
* ***“Essa ferramenta faz análise de sentimentos com base em comentários dos clientes.”***

## 🔧 Ferramentas e bibliotecas comuns

|**Finalidade**	          | **Ferramenta / Biblioteca**            |
|-------------------------|----------------------------------------|
| NLP tradicional         | NLTK, spaCy, TextBlob                  |
| Deep Learning em NLP    | Hugging Face Transformers, BERT, GPT   |
| Modelos em português    | BERTimbau, Portuguese-BERT, mBERT      |
| Speech-to-text          | Google Speech API, Whisper (OpenAI)    |
| Tradução                | MarianMT, Google Translate API         |
| Análise de sentimentos  | VADER, TextBlob, huggingface pipeline  |

## 🔄 Pipeline típico de PLN
1. Coleta de dados de texto
2. Limpeza e pré-processamento
3. Remoção de stopwords
4. Tokenização
5. Lematização/stemming
6. Representação de texto
7. Bag of Words / TF-IDF
8. Word Embeddings (Word2Vec, GloVe)
9. Embeddings de modelos como BERT
10. Treinamento de modelos / Inferência
11. Pós-processamento e entrega de valor

## 🤖 Modelos de linguagem (LLMs)
A nova geração de PLN é dominada por modelos de linguagem pré-treinados (LLMs) como:
* GPT (OpenAI)
* BERT (Google)
* T5, RoBERTa, LLaMA, Mistral, Claude

Esses modelos aprendem com bilhões de textos e são capazes de gerar, resumir, traduzir e entender textos complexos com alto grau de fluência e contexto.

## 🧭 Dica prática
Quando usar PLN no trabalho:
* Comece com tarefas simples: classificação de textos, extração de palavras-chave, agrupamento.
* Explore APIs prontas: Hugging Face, Azure Cognitive Services, Google NLP API.
* Se quiser resultados mais controlados e transparentes, use modelos tradicionais + regras linguísticas.
* Para projetos mais ambiciosos (como um assistente de IA), opte por LLMs finetunados ou sistemas híbridos.
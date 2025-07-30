# 🧠 Sistemas Especialistas

## 📖 O que são?
***Sistemas Especialistas*** são programas de computador que emulam a capacidade de decisão de um especialista humano em um domínio específico. Eles operam com base em uma ***base de conhecimento*** e um ***mecanismo de inferência***, permitindo que o sistema resolva problemas, dê diagnósticos ou tome decisões com base em regras lógicas.

São considerados uma das formas clássicas de Inteligência Artificial, muito antes da popularização do machine learning.

## 🧾 Origem e histórico
O conceito surgiu na década de ***1960*** e ganhou força nos anos ***1970 e 1980***. Um dos primeiros e mais famosos foi o ***Dendral (para análise química)*** e o ***MYCIN***, que ajudava médicos a diagnosticar infecções bacterianas e recomendar antibióticos.

Esses sistemas mostraram que, mesmo sem aprender com dados, uma IA baseada em conhecimento codificado podia ter desempenho comparável (ou até superior) a humanos em tarefas bem delimitadas.

## 🧠 Componentes principais
**1. Base de Conhecimento**
Regras do tipo SE...ENTÃO... escritas por especialistas humanos ou desenvolvedores, contendo fatos, heurísticas e experiências.

**2. Mecanismo de Inferência**
Motor lógico que manipula as regras para chegar a conclusões com base nos dados fornecidos.

**3. Interface do Usuário**
Meio pelo qual o usuário insere informações e obtém respostas do sistema.

**4. (Opcional) Módulo de Explicação**
Explica o porquê de determinada conclusão, útil para auditoria e transparência.

## 💡 Significado real e aplicação atual
Embora os sistemas especialistas tenham sido ofuscados pela ascensão do ***machine learning*** e ***deep learning***, eles ***ainda são valiosos*** em ambientes:
* Onde há pouco ou nenhum dado disponível
* Onde decisões precisam ser explicáveis (ex: compliance, medicina, direito)
* Onde regras e exceções são claras e bem definidas

Muitos sistemas de ***automação industrial***, ***diagnóstico técnico***, ***jurídico*** e ***tributário*** ainda usam essa abordagem.

## 🧰 Como usar no ambiente de trabalho
### ✅ Exemplos práticos:
* ***Diagnóstico de falhas técnicas*** com base em sintomas (Ex: “Se motor aquece e não gira, então problema pode ser no rolamento”)
* ***Sistema tributário:*** regras fiscais que mudam por estado, tipo de operação, etc.
* ***Regras de aprovação*** de crédito em sistemas legados
* ***Chatbots baseados em fluxos fixos de decisão***

### 🗣️ Como conversar com colegas ou stakeholders:
* *“Estamos implementando um sistema especialista para automatizar o processo de decisão com base nas regras do negócio.”*
* *“Esse não é um modelo preditivo, é um sistema especialista baseado em regras.”*
* *“Vamos extrair conhecimento dos especialistas e formalizar em uma base de conhecimento para o motor de inferência.”*

### 🔄 Comparando com IA moderna

| Aspecto                | Sistema Especialista               | IA moderna (ML/DL)         |
|------------------------|----------------------------------|----------------------------|
| Fonte de conhecimento  | Regras humanas explícitas         | Dados históricos           |
| Aprendizado            | Não aprende com dados             | Aprende automaticamente    |
| Explicabilidade        | Alta (regras claras)              | Pode ser difícil de explicar|
| Flexibilidade          | Baixa para mudanças e exceções   | Alta adaptabilidade        |

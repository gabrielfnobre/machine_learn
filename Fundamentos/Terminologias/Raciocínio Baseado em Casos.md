# Raciocínio Baseado em Casos (RBC)

## 🧠 O que é?

O **Raciocínio Baseado em Casos (RBC)** é uma abordagem de Inteligência Artificial onde a solução de novos problemas é baseada na **experiência passada** — ou seja, **em casos anteriores similares** já resolvidos.

Em vez de tentar resolver tudo do zero, o sistema **busca no seu histórico de casos** e **reaproveita soluções antigas**, adaptando-as à nova situação.

## 📜 Origem e História

- Começou a ganhar destaque nos anos **1980**
- Inspirado em como **seres humanos aprendem com a experiência**
- Muito usado em **sistemas especialistas** e **sistemas de apoio à decisão**
- Pioneiros: Roger Schank, Janet Kolodner e outros

## 🎯 O que realmente significa?

Imagine que você tem um banco de dados com **vários problemas resolvidos**. Quando surge um novo problema:

1. O sistema **procura casos parecidos** no seu acervo
2. **Seleciona** o mais similar
3. **Adapta** a solução antiga à nova situação
4. **Aplica** a solução adaptada
5. **Armazena** esse novo caso para futuras consultas

É uma forma de "memória computacional", baseada no princípio: **“problemas semelhantes têm soluções semelhantes”**.

## 🔧 Componentes de um Sistema RBC

1. **Aquisição de casos**: construção do banco de experiências
2. **Recuperação**: encontrar o(s) caso(s) mais parecido(s)
3. **Adaptação**: modificar a solução antiga para caber no novo problema
4. **Avaliação**: testar se a solução adaptada funciona
5. **Retenção**: guardar o novo caso e a solução aplicada

## 🧰 Como usar no ambiente de trabalho?

### Exemplos práticos:
- **Diagnóstico médico**: comparar sintomas com casos anteriores
- **Atendimento ao cliente**: sistemas que sugerem soluções com base em atendimentos antigos
- **Manutenção industrial**: identificar falhas com base em ocorrências anteriores
- **Direito**: análise de jurisprudências (decisões passadas)
- **Educação**: sistemas que recomendam conteúdos com base em desempenhos semelhantes

### Ferramentas e Tecnologias:
- **myCBR (open source para RBC)**
- **jCOLIBRI (Java)**
- **Python + bibliotecas personalizadas**
- **Sistemas especialistas customizados**
- **Bancos de dados bem estruturados com metadados para indexação dos casos**

## 💬 Como falar disso com a galera da área?

Frases comuns:
- “Esse sistema usa casos anteriores como base para a tomada de decisão.”
- “Estamos alimentando a base de conhecimento com falhas passadas para prever problemas futuros.”
- “A adaptação de soluções antigas é a chave para resolver problemas novos com agilidade.”
- “RBC é ótimo para ambientes onde o conhecimento explícito é difícil de formalizar, mas a experiência acumulada é rica.”

## 🧠 Resumo

| Aspecto                     | Descrição |
|----------------------------|-----------|
| **Definição**              | Resolver problemas com base em experiências anteriores |
| **Origem**                 | Inspirado na memória humana, anos 80 |
| **Etapas**                 | Recuperar, Adaptar, Avaliar, Aprender |
| **Aplicações**             | Medicina, suporte, manutenção, direito |
| **Ferramentas**            | myCBR, jCOLIBRI, sistemas próprios |


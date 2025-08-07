# Resolução de Problemas por Meio de Busca

## 🧠 O que é?

É uma das abordagens mais fundamentais da Inteligência Artificial (IA), usada quando um agente **não tem conhecimento direto da solução**, mas sabe quais ações pode tomar e quais estados do mundo elas geram. A ideia é **navegar por um espaço de estados possíveis** até encontrar o estado objetivo.

É como **um quebra-cabeça**: o agente parte de um estado inicial e precisa descobrir, por tentativas sistemáticas, o melhor caminho até a solução.

## 📜 Origem e História

A abordagem surgiu com os primeiros trabalhos da IA, na década de **1950**, com o desenvolvimento de programas para resolver problemas como jogos (xadrez, damas) e quebra-cabeças (como o problema das 8 peças).

Marcos históricos:
- **1957**: Algoritmo de busca em largura (BFS)
- **1961**: Algoritmo A* (A estrela), criado por Hart, Nilsson e Raphael

## 🎯 O que realmente significa?

Significa estruturar o problema como:

- **Estado inicial**
- **Ações possíveis**
- **Estados sucessores**
- **Teste de objetivo**
- **Custo de caminho**

E então aplicar um algoritmo que percorra esse **espaço de busca** até encontrar a solução desejada.

## 🔧 Tipos de Busca:

### 🔍 Busca Cega (não-informada)
Não utiliza informações adicionais sobre o estado.
- **Busca em Largura (BFS)**
- **Busca em Profundidade (DFS)**
- **Busca de Custo Uniforme**
  
### 💡 Busca Heurística (informada)
Usa estimativas para guiar a busca.
- **Algoritmo A\***
- **Best-First Search**
- **Hill Climbing**
- **Busca Gulosa**

## 🧰 Como usar no ambiente de trabalho?

### Exemplos práticos:
- **Planejamento logístico**: encontrar rotas ideais
- **Jogos de estratégia**: escolher a melhor jogada
- **IA em robótica**: planejar caminhos para robôs
- **Navegadores GPS**: calcular o melhor trajeto
- **Soluções de automação**: decidir sequência de ações para atingir um objetivo

### Ferramentas e Tecnologias:
- **Linguagens como Python, Java, Prolog**
- **Bibliotecas como NetworkX, AIMA, Graph-tool**
- **Motores de jogos com pathfinding (ex: Unity com A\*)**
- **Sistemas especialistas com motores de inferência baseados em busca**

## 💬 Como falar disso com a galera da área?

Frases comuns em projetos ou reuniões:
- “Esse problema pode ser representado como um grafo e resolvido com A*.”
- “Usamos busca em largura para garantir a menor quantidade de passos.”
- “A heurística foi crucial para otimizar o tempo de resposta do agente.”
- “Modelamos o problema como um espaço de estados com operadores definidos.”

## 🧠 Resumo

| Aspecto                     | Descrição |
|----------------------------|-----------|
| **Definição**              | Solução de problemas estruturados como busca em um espaço de estados |
| **Tipos**                  | Cega (sem heurística) ou Informada (com heurística) |
| **Aplicações**             | Planejamento, jogos, robótica, GPS, IA |
| **Técnicas famosas**       | BFS, DFS, A*, Hill Climbing |
| **Ferramentas**            | Python, AIMA, Unity, Prolog |


# 🧬 Algoritmos Genéticos (Genetic Algorithms - GA)
## 📖 O que são?
***Algoritmos Genéticos (AGs)*** são uma técnica de otimização e busca inspirada nos princípios da ***seleção natural*** e ***evolução biológica***. Eles pertencem ao campo da ***IA evolucionária***.

A ideia é simples, mas poderosa: evoluir soluções ao longo de gerações, aplicando operações análogas à genética:
* Seleção
* Crossover (cruzamento)
* Mutação

São especialmente úteis para resolver problemas complexos, com muitas variáveis, soluções combinatórias ou sem solução analítica direta.

## 🧾 Origem e histórico
Os Algoritmos Genéticos foram formalizados por **John Holland** em 1975, na Universidade de Michigan, com o livro ***“Adaptation in Natural and Artificial Systems”***.

O objetivo era modelar o processo de adaptação evolutiva como um algoritmo computacional, capaz de encontrar boas soluções mesmo em espaços de busca vastos e complexos.

## 💡 O que realmente significam?
Algoritmos Genéticos são baseados no conceito de populações de candidatos a soluções que evoluem iterativamente. A cada geração:
* As melhores soluções ("mais adaptadas") são selecionadas
* Novas soluções ("filhos") são geradas por crossover
* Algumas sofrem mutações aleatórias
* A população é atualizada, mantendo os melhores
* O processo se repete até:
    * Encontrar uma solução suficientemente boa
    * Ou atingir um número máximo de gerações

## 🔁 Etapas principais de um AG
1. Codificação das soluções (cromossomos)
2. Pode ser binária, numérica, vetores, strings, etc.
3. Inicialização da população
4. Geração aleatória de soluções iniciais
5. Avaliação (função de aptidão)
6. Mede a qualidade de cada solução
7. Seleção
8. Escolhe os indivíduos para reprodução (ex: torneio, roleta)
9. Crossover (cruzamento)
10. Combina genes de dois pais para gerar filhos
11. Mutação
12. Altera aleatoriamente partes dos cromossomos
13. Nova geração
14. Substitui parte ou toda a população antiga

## 🧰 Aplicações no ambiente de trabalho
### ✅ Exemplos práticos:
* Otimização de rotas logísticas (ex: entrega de mercadorias)
* Agendamento de tarefas ou turnos de trabalho
* Configuração ideal de parâmetros em máquinas ou sistemas
* Design de produtos com múltiplas restrições (engenharia)
* Treinamento de redes neurais (otimização de hiperparâmetros)
* Jogos: bots que aprendem estratégias baseadas em evolução

### 🗣️ Como usar essa terminologia:
* ***“Vamos usar um Algoritmo Genético para encontrar a melhor configuração possível com essas restrições.”***
* ***“Esse problema é de otimização combinatória, e AGs se encaixam muito bem.”***
* ***“Usamos seleção por torneio e mutação adaptativa nesse AG.”***

## 🔧 Ferramentas e bibliotecas comuns

| **Linguagem**	  | **Biblioteca**                 |
|-----------------|--------------------------------|
| Python          | DEAP, PyGAD, Genetic           |
| R               | GA                             | 
| Java            | JGAP                           |
| MATLAB          | ga() da toolbox de otimização  |

## 🧭 Dica prática
* Use AGs quando você tiver muitas variáveis ou um espaço de busca complexo, com múltiplas restrições ou objetivos conflitantes.
* Eles não garantem a melhor solução global, mas podem encontrar boas soluções rapidamente, especialmente quando outros métodos falham.
* Combine com conhecimento do domínio: escolha bons critérios de fitness, defina limites realistas e boas estratégias de mutação e seleção.

## 🧬 AG vs. outros métodos de IA

| **Característica** |	**Algoritmos Genéticos**        |	**Machine Learning tradicional**  |
|--------------------|----------------------------------|-------------------------------------|
| Inspiração         | Evolução biológica               | Estatística e aprendizado           |
| Entrada principal  | Função de aptidão                | Dados históricos rotulados          |
| Objetivo           | Otimização                       | Previsão / classificação            |
| Explicabilidade    | Alta (estrutura explícita)       | Pode ser opaca (deep learning)      |
| Dados necessários  | Nenhum (funciona só com regras)  | Muitos dados                        |
# Miniguia de Estudos: Introdução ao Machine Learning

## 📌 Contexto e Objetivos
Este repositório foi criado como parte do desafio NotebookLM da DIO.  
Tema escolhido: **Machine Learning**  
Objetivos:
- Compreender os conceitos fundamentais de aprendizado supervisionado e não supervisionado.
- Explorar aplicações práticas de algoritmos de ML.
- Utilizar IA como ferramenta de estudo ativo e curadoria de conhecimento.

---

## 📚 Curadoria de Fontes
1. [OpenML](https://www.openml.org) – Plataforma aberta com datasets e experimentos de ML.  
2. [Machine Learning Study Resources](https://github.com/rasbt/machine-learning-study-resources) – Repositório GitHub com materiais de estudo atualizados.  
3. [Machine Learning Systems Textbook](https://mlsysbook.org) – Livro-texto aberto cobrindo todo o ciclo de vida de ML.  
4. https://www.ime.unicamp.br/~valle/Teaching/MS571/Aula%2007%20-%20Medidas%20de%20Desempenho%0Aem%20Problemas%20de%20Classifica%C3%A7%C3%A3o.pdf
5. https://pt.wikipedia.org/wiki/Aprendizado_de_m%C3%A1quina
6. https://blog.dsacademy.com.br/desvendando-hiperparametros-o-guia-definitivo-para-otimizar-modelos-de-machine-learning/
7. https://uds.com.br/blog/machine-learning/
8. Machine Learning Systems: Educational Resources
9. https://www.ibm.com/br-pt/think/topics/gradient-descent
10. https://www.ibm.com/br-pt/think/topics/overfitting-vs-underfitting
11. https://aws.amazon.com/pt/compare/the-difference-between-machine-learning-supervised-and-unsupervised/
12. https://pt.wikipedia.org/wiki/Aprendizagem_de_%C3%A1rvore_de_decis%C3%A3o
13. https://pt.wikipedia.org/wiki/Aprendizagem_por_refor%C3%A7o
> Cada fonte foi escolhida por trazer uma perspectiva complementar: visão geral, prática aplicada e aprofundamento teórico.

---

## 🎯 Engenharia de Prompts
Arquivo: `prompts.md`  
Exemplos de perguntas utilizadas no NotebookLM:
- "Explique a diferença entre aprendizado supervisionado e não supervisionado em até 3 parágrafos."
- "Explique aprendizado supervisionado em linguagem simples para iniciantes, com um exemplo prático."
- "Como saber se um modelo de classificação é realmente bom?"
- "Qual a diferença entre erro de underfitting e overfitting?"

Dificuldades encontradas:
- Algumas respostas vieram muito genéricas, exigindo refinamento dos prompts.
- Necessidade de detalhar melhor o contexto para obter explicações mais aplicáveis.
- Ajuste de linguagem: perguntas mais específicas geraram respostas mais úteis.

---

## 📖 Miniguia de Estudo

### Resumos Estruturados
- **Aprendizado Supervisionado**: usa dados rotulados para treinar modelos; objetivo é prever saídas específicas. Exemplos: classificação (spam vs não spam) e regressão (preço de imóveis).  
- **Aprendizado Não Supervisionado**: trabalha com dados sem rótulos; busca padrões ocultos. Exemplos: clustering e redução de dimensionalidade.  
- **Avaliação de Modelos de Classificação**: métricas como acurácia, precisão, recall, F1-score e AUC são usadas para medir desempenho.  
- **Underfitting vs Overfitting**: underfitting = modelo simples demais, não aprende padrões; overfitting = modelo complexo demais, memoriza ruído. O ideal é o equilíbrio viés-variância.

---

### Glossário
- **Classificação**: atribuição de categorias a dados (ex.: spam vs não spam).  
- **Regressão**: previsão de valores contínuos (ex.: preço de casas).  
- **Clustering**: agrupamento de dados semelhantes sem rótulos.  
- **Overfitting**: modelo que memoriza dados de treino e falha em generalizar.  
- **Underfitting**: modelo simplista que não captura padrões relevantes.  
- **Validação Cruzada**: técnica para avaliar consistência do modelo em diferentes divisões de dados.  
- **Trade-off Viés-Variância**: equilíbrio entre simplicidade e complexidade do modelo para minimizar erro de generalização.

---

### Prompts Reutilizáveis
- "Explique [conceito] em linguagem simples para iniciantes, com exemplo prático."  
- "Compare [algoritmo A] e [algoritmo B] destacando vantagens e limitações."  
- "Quais métricas são usadas para avaliar [tipo de modelo]?"  
- "Crie um exemplo prático de aplicação de [algoritmo] com dados fictícios."  

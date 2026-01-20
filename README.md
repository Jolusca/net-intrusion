# net-intrusion
Criação de artigo para detecção de padrões de ataques em rede


## Checklist de Correções do Artigo

### Alberto - Introdução, Contexto e Trabalhos Relacionados

**Foco:** Embasamento teórico geral e referências

- [x] Adicionar referências para afirmações gerais da introdução:
  - Uso de aprendizado de máquina em sistemas de detecção de intrusões
  - Importância da seleção e remoção de atributos
- [x] Inserir estudos que:
  - Avaliem modelos de ML aplicados à detecção de anomalias em redes
  - Utilizem técnicas de seleção ou remoção de atributos

---

### João Lucas Mota — Fundamentação dos Modelos e Técnicas

**Foco:** Explicação conceitual dos métodos e técnicas citadas

- [x] Explicar as técnicas de pré-processamento citadas no texto:
  - [x] One-Hot Encoding
  - [x] Label Encoding
  - [x] Padronização / Normalização dos dados
  - [x] Amostragem estratificada
- [x] Esclarecer a diferença entre:
  - Redução de dimensionalidade (ex.: PCA)
  - Remoção manual de atributos
- [x] Justificar teoricamente a escolha pela remoção manual de features no estudo

---

### João Lucas Rodrigues -  Métricas, Avaliação e Clareza Textual

**Foco:** Métricas de desempenho, consistência e clareza científica

- [ ] Criar uma subseção explicando as métricas utilizadas:
  - [ ] Precision
  - [ ] Recall
  - [ ] F1-Score
  - [ ] Support
- [ ] Explicar por que a acurácia, isoladamente, não é suficiente para avaliação
- [ ] Garantir que todas as métricas presentes nas tabelas sejam citadas e explicadas no texto
- [x] Revisar ortografia e padronização da escrita:
  [x] - Corrigir termos como *directamente*, *correctamente*, *selecção*, etc.

---
### TODO 
- [x] reseach questions
- [x] slides de PoC 
- [x] Escolher modelos
- [x] Pesquisar sobre diferentes modelos
- [x] Começar a estrutura do artigo
- [x] Redes Neurais (MLP)
- [x] MLP reduzido sem o src bytes (correlação com o Random Forest)
- [x] Isolation Forest
- [x] KNN
- [x] Random Forest
- [x] Comparação entre os modelos
- [x] Introdução do dataset
- [x] Estruturar análises com retirada de colunas
- [x] Resultados MLP
- [x] Resultados Random Forest

https://www.canva.com/design/DAG3xUeqaa8/gn4ky1JF9uxutgEoXoED8w/edit


### Analise do ChatGPT sobre possíveis decisões do projeto

https://chatgpt.com/share/69035515-fbfc-8001-b794-d1da3a529152

### Datasets

https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection

### Research Questions:

- 1. A utilização de Machine Learning no processo de analise de ataques a redes de servidores se prova eficiente?
- 2. Como a escolha do modelo utilizado para analisar os ataques a redes de servidores pode afetar no resultado da analise? (Random Forest, MLP, KNN, Isolation Forest)
- [x] comparação MLP e Random Forest
- 3. Como os dados analisados alteram o resultado da analise de ataques a redes de servidores utilizando Machine Learning?
- 4. Quais os melhores modelos para serem utilizados com a presença dos dados selecionados?

### Site com as bibliotecas de python a serem utilizadas:

https://scikit-learn.org/stable/supervised_learning.html


## Referências de artigos semelhantes

https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://sol.sbc.org.br/index.php/sbrc/article/download/35134/34925/&ved=2ahUKEwjf1KDJiOqQAxXhBrkGHeaZNvwQFnoECBkQAQ&usg=AOvVaw1BjbKxYF_zPFljj5mRCFdz

https://sol.sbc.org.br/index.php/sbrc/article/view/35170/34961
### Livro 
https://0-lucas.github.io/digital-garden/99.-Books/Hands-on-Machine-Learning.pdf



 ## Sugestões:
 Ver research Rabbit 
 https://www.researchrabbit.ai/

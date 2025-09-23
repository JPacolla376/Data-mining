# Projeto de Mineração de Dados

## Tema
**Desafios no uso de nuvem pública, privada e de governo em ciências de dados**

Este projeto tem como objetivo aplicar técnicas de mineração de dados em um conjunto de dados real e, ao mesmo tempo, discutir os principais desafios enfrentados ao utilizar diferentes tipos de nuvem no contexto de ciência de dados.

---

## Dataset
- **Nome:** Bank Marketing Dataset  
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)  
- **Instâncias:** 41.188  
- **Atributos:** 20  
- **Classe Alvo:** `y` → Cliente aderiu (*yes*) ou não (*no*) a um depósito a prazo.  

---

## Estrutura do Projeto
### Etapa 1 — Pré-Processamento e Análise Exploratória
- Carregamento do dataset.  
- Verificação e tratamento de valores ausentes.  
- Codificação de variáveis categóricas.  
- Normalização de atributos numéricos.  
- Divisão em treino e teste (80% / 20%).  
- Resumo estatístico e visualização dos dados.

### Etapa 2 — Modelagem e Avaliação
- Algoritmos de Classificação:
  - Decision Tree Classifier
  - Random Forest Classifier
- Avaliação de desempenho por métricas:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Interpretação e discussão dos resultados obtidos.

---

## Discussão sobre Nuvem
O projeto também aborda os impactos do uso de nuvem no contexto de ciência de dados:

- **Nuvem Pública:** escalabilidade e acesso rápido a recursos, mas com desafios relacionados a custos variáveis, segurança e conformidade (LGPD/GDPR).  
- **Nuvem Privada:** maior controle e segurança dos dados, porém com alto custo de infraestrutura e equipe especializada.  
- **Nuvem de Governo:** conformidade regulatória e governança rígida, mas com burocracia e menor flexibilidade para inovação.  

---

## Tecnologias Utilizadas
- Python 3  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Google Colab  

---

## Autores

- **[João Augusto Selegatto Pacolla](https://github.com/JPacolla376)**
- **[Maikon Gino](https://github.com/MaikonGino)**
Disciplina: Mineração de Dados  
Fatec Araras — Centro Paula Souza

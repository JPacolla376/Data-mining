# Projeto de Mineração de Dados: Marketing Bancário em Nuvem

## 📒 Sobre o Projeto

Este repositório contém o Projeto da disciplina de **Mineração de Dados**, ministrada pela Prof.ª Ivone Piedade Terra na FATEC Araras.

O estudo aplica um ciclo completo de Descoberta de Conhecimento em Bancos de Dados (KDD) em um dataset de marketing bancário. O objetivo é duplo:
1.  **Análise Preditiva:** Desenvolver e avaliar modelos de classificação para prever a adesão de clientes a um produto financeiro.
2.  **Análise Descritiva:** Aplicar técnicas de agrupamento para segmentar a base de clientes e identificar perfis de consumo distintos (personas).

Além da análise técnica, o projeto discute as implicações estratégicas e os desafios de operacionalizar tais modelos em diferentes arquiteturas de **Nuvem Computacional (Pública, Privada e Híbrida)**, conectando a teoria da mineração de dados com a prática do mercado.

---

## Dataset Utilizado

- **Nome:** Bank Marketing Dataset
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Instâncias:** 41.188
- **Atributos:** 21
- **Variável Alvo:** `y` → Cliente aderiu ('yes') ou não ('no') a um depósito a prazo.

---

## 🚀 Estrutura do Projeto

O projeto foi dividido em duas etapas principais, seguindo as diretrizes da disciplina:

### **Etapa 1 — Análise Exploratória e Pré-processamento**

Nesta fase, o foco foi compreender e preparar os dados para a modelagem, garantindo a qualidade e a robustez da análise.

- **Análise Exploratória de Dados (AED):** Investigação estatística e visual para identificar padrões, correlações, outliers e o desbalanceamento da classe alvo.
- **Pipeline de Pré-processamento:** Construção de um pipeline robusto com `Scikit-learn` para:
    - Tratar *data leakage* (remoção da feature `duration`).
    - Realizar a divisão estratificada dos dados (80% treino, 20% teste).
    - Aplicar imputação de dados (mediana para numéricos, moda para categóricos).
    - Padronizar features numéricas (`StandardScaler`).
    - Codificar features categóricas (`OneHotEncoder`).

### **Etapa 2 — Modelagem, Avaliação e Análise**

Nesta etapa, foram aplicadas duas tarefas distintas de mineração de dados para extrair insights preditivos e descritivos.

#### **1. Tarefa de Classificação (Aprendizado Supervisionado)**

- **Objetivo:** Prever a adesão de clientes.
- **Técnica Adicional:** Balanceamento de classes com **SMOTE** no conjunto de treino.
- **Algoritmos Aplicados:**
    - `Regressão Logística` (como baseline)
    - `Random Forest Classifier`
- **Avaliação:** Análise de performance com base no **Recall** da classe positiva, Matriz de Confusão e Relatório de Classificação completo.

#### **2. Tarefa de Agrupamento (Aprendizado Não Supervisionado)**

- **Objetivo:** Segmentar clientes e criar personas.
- **Técnica Adicional:** **Método do Cotovelo (Elbow Method)** para determinar o número ideal de clusters.
- **Algoritmo Aplicado:**
    - `K-Means`
- **Avaliação:** Análise do **Coeficiente de Silhueta** e interpretação detalhada do perfil de cada cluster, transformando os grupos em segmentos de negócio acionáveis.

---

## 🛠️ Tecnologias Utilizadas

<table align="center">
  <tr>
    <td align="center" width="110">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" height="80">
      <br>Python 3
    </td>
    <td align="center" width="110">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" height="80">
      <br>Pandas
    </td>
    <td align="center" width="110">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" height="80">
      <br>NumPy
    </td>
    <td align="center" width="110">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" height="80">
      <br>Scikit-learn
    </td>
     <td align="center" width="110">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" height="80">
      <br>Matplotlib
    </td>
    <td align="center" width="110">
      <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" height="80">
      <br>Seaborn
    </td>
    <td align="center" width="110">
      <img src="https://colab.research.google.com/img/colab_favicon_256px.png" height="80">
      <br>Google Colab
    </td>
  </tr>
</table>

---

## 📂 Como Executar o Projeto

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/JPacolla376/Data-mining.git](https://github.com/JPacolla376/Data-mining.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd Data-mining
    ```
3.  O arquivo principal do projeto é um notebook do Google Colab:
    - **[Projeto_Mineracao_Final.ipynb](https://colab.research.google.com/drive/1KgEmXnJfYYe6ZY93N-yx2q9rVrkwPEr4)**
4.  Abra o notebook no Google Colab e execute as células sequencialmente. Todas as dependências já estão inclusas no ambiente do Colab.

---

## 👨‍💻 Autores

- **[João Augusto Selegatto Pacolla](https://github.com/JPacolla376)**
- **[Maikon F. Gino](https://github.com/MaikonGino)**

<br>

**Disciplina:** Mineração de Dados  
**Instituição:** FATEC Araras — Centro Paula Souza

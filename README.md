# 🔎✨ Projeto de Mineração de Dados
> "Transformando dados em conhecimento e desafios em oportunidades!"

---

## 📌 Tema
**Desafios no uso de nuvem pública, privada e de governo em ciências de dados**  
Este projeto busca unir **ciência de dados prática** com uma **reflexão crítica** sobre como diferentes modelos de nuvem impactam a mineração de dados em termos de custo, segurança, privacidade e governança.

---

## 📊 Dataset Utilizado
📂 **Bank Marketing Dataset** — UCI Machine Learning Repository  
- **Instâncias:** 41.188  
- **Atributos:** 20 (socioeconômicos, demográficos e de campanha)  
- **Classe Alvo:** `y` → Cliente aderiu (*yes*) ou não (*no*) a um depósito a prazo.  

🔗 Fonte: [UCI Bank Marketing](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

---

## ⚙️ Etapas do Projeto
### ✅ Etapa 1 — Pré-Processamento e Análise Exploratória
- Carregamento do dataset.  
- Tratamento de valores ausentes.  
- Codificação de variáveis categóricas.  
- Normalização de atributos numéricos.  
- Divisão em treino/teste (80%/20%).  
- Resumo estatístico e visualizações:
  - 📈 Histogramas
  - 📊 Gráficos de barras
  - 🔥 Matriz de correlação (heatmap)

### 🚀 Etapa 2 — Modelagem (Classificação)
- **Decision Tree Classifier** 🌳 → fácil de interpretar, bom para análise inicial.  
- **Random Forest Classifier** 🌲🌲🌲 → modelo ensemble robusto, reduz overfitting.  
- Avaliação com métricas:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Visualização dos resultados e interpretação crítica.

---

## ☁️ Desafios da Nuvem em Ciência de Dados
Este projeto também aborda os **impactos de diferentes modelos de nuvem** no contexto de mineração de dados:

- **🌐 Nuvem Pública:** escalável e acessível, mas exige atenção ao custo variável, segurança e compliance com LGPD/GDPR.  
- **🏢 Nuvem Privada:** maior controle e segurança, mas alto custo de infraestrutura e equipe especializada.  
- **🏛️ Nuvem de Governo:** garante conformidade e governança, mas pode limitar inovação e trazer burocracia.  

---

## 🛠️ Tecnologias e Bibliotecas
- **Python 3** 🐍  
- **Pandas & NumPy** (manipulação de dados)  
- **Matplotlib & Seaborn** (visualização)  
- **Scikit-learn** (pré-processamento e algoritmos de ML)  
- **Google Colab** (execução em nuvem acadêmica gratuita)  

---

## 🎯 Conclusão (Etapa 1)
Com o dataset limpo, explorado e documentado, estabelecemos uma base sólida para aplicar algoritmos de classificação.  
Além da prática técnica, reforçamos como **o ambiente em que a mineração de dados é executada (nuvem pública, privada ou governamental)** influencia diretamente fatores como **custo, segurança, privacidade e escalabilidade**.

Próximo passo 👉 **Etapa 2: Implementação dos modelos e avaliação de desempenho.**

---

## 👨‍💻 Autores
**João Augusto Selegatto Pacolla**  
**Maikon Fabricio Gino**  
Disciplina: *Mineração de Dados*  
Fatec Araras — Centro Paula Souza

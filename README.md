# selecao-features
Projeto que analiso a importancia de cada feature de um dataframe e então utilizou para treinar o ML



# Previsão de cancelamentos de agenda de um hotel

Projeto de Machine Learning desenvolvido com foco em seleção de features de um dataframe.

Variável alvo (booking_status): Indica se a reserva foi cancelada (1) ou mantida (0), com distribuição balanceada entre as classes no conjunto analisado.

Preparação dos dados: Variáveis categóricas já convertidas para formato numérico (incluindo codificação one-hot) e verificação de ausência de valores nulos.

Prevenção de data leakage: Divisão estratificada (stratify=y) entre conjuntos de treino e teste realizada antes da análise exploratória e da modelagem.

Modelo baseline: Treinamento de um RandomForestClassifier utilizando todas as 30 features disponíveis, alcançando acurácia inicial de aproximadamente 92,06% no conjunto de teste.


---

## 🚀 Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn


---

## 📊 Etapas do projeto


Análise exploratória (EDA): Inspeção de distribuições e comparações entre classes, como o comportamento de lead_time em reservas canceladas versus não canceladas.

Seleção de features:

Avaliar correlações com a variável alvo (booking_status).

Inspecionar a importância das variáveis (feature_importances_) no modelo de floresta aleatória.

Testar abordagens de seleção de atributos (como SelectKBest, SelectFromModel ou RFE) para verificar o impacto na performance e na simplicidade do modelo.


---

## 📈 Resultados obtidos

O modelo apresentou o seguinte desempenho:

```python
92% de acurácia 
```


---

## 🧠 Principais aprendizados

Neste projeto foram praticados conceitos importantes como:

- avaliação de modelos
- preparação de dados
- validação de resultados
- visualização de dados
- analise de importancia de features
- ferramentas de seleção de features

---

## 📂 Estrutura do projeto

```bash
📁 projeto
 ┣ 📄 notebook.ipynb
 ┣ 📄 README.md

```
---

## ▶️ Como executar

Clone o repositório:

```bash
git clone https://github.com/FernandoDevelo/selecao-features.git
```

---


## 👨‍💻 Autor

Projeto desenvolvido por Fernando Nascimento durante os estudos em Data Science e Machine Learning.
````


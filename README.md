# 📊 Microatividades com Pandas — Análise de Dados Sísmicos

Este projeto reúne uma série de microatividades realizadas com o objetivo de praticar manipulação, visualização e análise de dados utilizando a biblioteca **pandas** em Python. Os dados utilizados são referentes a terremotos registrados globalmente, incluindo informações como magnitude, localização, profundidade e ocorrência de tsunamis.

---

## 🧰 Material Necessário

- Interpretador Python ou ambiente de codificação:
  - JupyterLab
  - Jupyter Notebooks
  - Google Colab
- Biblioteca `pandas` instalada
- Editor ou IDE (VS Code, PyCharm, etc.)
- Arquivo de dados: `earthquake_data_tsunami.csv`

---

## 🧪 Microatividade 1 — Visualização Completa com `to_string()`

### 🔧 Procedimentos

- Importar a biblioteca pandas
- Configurar `display.max_rows` para 9999
- Carregar o conjunto de dados original
- Imprimir o DataFrame completo com `to_string()`

### ✅ Resultado Esperado

Exibir o DataFrame completo sem truncamento, demonstrando domínio das configurações de exibição do pandas.

---

## 🧪 Microatividade 2 — Visualização Parcial com `head()` e `tail()`

### 🔧 Procedimentos

- Carregar o conjunto de dados original
- Imprimir as **10 primeiras linhas** com `head(10)`
- Imprimir as **10 últimas linhas** com `tail(10)`

### ✅ Resultado Esperado

Visualizar rapidamente o início e o fim do conjunto de dados, utilizando métodos básicos de inspeção.

---

## 🧪 Microatividade 3 — Informações Gerais com `info()`, `shape`, `isnull()`, `dtypes`, `memory_usage()`

### 🔧 Procedimentos

- Carregar o conjunto de dados original
- Imprimir informações gerais com `info()`
- Obter:
  - Total de linhas e colunas com `shape`
  - Quantidade de dados nulos com `isnull().sum()`
  - Tipos de dados com `dtypes`
  - Memória utilizada com `memory_usage(deep=True).sum()`

### ✅ Resultado Esperado

Demonstrar capacidade de extrair metadados e estatísticas estruturais do DataFrame.

---

## 📁 Estrutura de Arquivos

📦 projeto-terremotos-pandas ├── earthquake_data_tsunami.csv ├── microatividade1_visualizacao_completa.ipynb ├── microatividade2_head_tail.ipynb ├── microatividade3_info_estrutura.ipynb └── README.md

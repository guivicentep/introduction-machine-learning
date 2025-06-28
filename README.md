# 📚 Projeto de Estudos em Machine Learning

Este repositório serve como um espaço dedicado ao meu aprendizado e prática de conceitos fundamentais em Machine Learning, utilizando a flexibilidade e interatividade dos Jupyter Notebooks. Aqui, exploro diversas bibliotecas e técnicas essenciais para a construção e análise de modelos de dados.

---

## 🎯 Objetivo

O principal objetivo deste projeto é consolidar meu conhecimento em Machine Learning através da aplicação prática de conceitos. Cada notebook representa um tópico ou uma etapa de aprendizado, permitindo-me:

* **Compreender** os fundamentos teóricos por trás de algoritmos e técnicas.
* **Desenvolver** habilidades em manipulação, visualização e pré-processamento de dados.
* **Implementar** e testar diferentes modelos de Machine Learning.
* **Analisar** e interpretar resultados, avaliando a performance dos modelos.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

Este projeto faz uso das seguintes ferramentas e bibliotecas Python:

* **Jupyter Notebook:** Para um ambiente de desenvolvimento interativo e documentado.
* **Pandas:** Para manipulação e análise de dados estruturados.
* **NumPy:** Para computação numérica eficiente, especialmente com arrays.
* **Matplotlib:** Para criação de visualizações estáticas, animadas e interativas em Python.
    * *(Opcional: Adicione aqui outras bibliotecas que você planeja usar ou já usou, como `Seaborn`, `Scikit-learn`, etc.)*

---

## 📂 Estrutura do Repositório

O repositório está organizado da seguinte forma:

.
├── .ipynb_checkpoints/ # (Ignorado pelo Git) Backups temporários do Jupyter.
├── data/
│   ├── car-sales-missing-data.csv
│   ├── car-sales-missing-dropped.csv
│   ├── car-sales.csv
│   ├── exported-car-sales.csv
│   └── heart-disease.csv
├── env/                # (Ignorado pelo Git) Ambiente virtual do Python.
├── images/             # Contém imagens ou gráficos gerados/utilizados nos notebooks.
├── notebooks/
│   ├── 1-example-notebook.ipynb
│   ├── 1-introduction-to-pandas.ipynb
│   ├── 1-pandas-practice.ipynb
│   ├── 2-introduction-to-numpy.ipynb
│   └── 3-matplotlib.ipynb
├── .gitignore
├── README.md
└── requirements.txt

* **`notebooks/`**: Contém todos os arquivos Jupyter Notebook (`.ipynb`), organizados por tópico ou ordem de aprendizado.
* **`data/`**: Armazena os conjuntos de dados utilizados nos notebooks.
* **`.gitignore`**: Define os arquivos e diretórios a serem ignorados pelo Git (como `env/` e `.ipynb_checkpoints/`).
* **`README.md`**: Este arquivo, fornecendo uma visão geral do projeto.
* **`requirements.txt`**: Lista todas as dependências Python necessárias para executar os notebooks.

---

## 🚀 Como Executar os Notebooks

Para explorar e executar os notebooks localmente, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**
    ```bash
    python -m venv env
    ```
    * No Windows:
        ```bash
        .\env\Scripts\activate
        ```
    * No macOS/Linux:
        ```bash
        source env/bin/activate
        ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Isso abrirá uma nova aba no seu navegador com a interface do Jupyter. Navegue até a pasta `notebooks/` e abra os arquivos `.ipynb` para começar a explorar.

---

## 📝 Conteúdo dos Notebooks (Exemplos)

Aqui estão alguns exemplos de tópicos abordados nos notebooks:

* **`1-introduction-to-pandas.ipynb`**: Manipulação básica de DataFrames, seleção, filtragem e operações.
* **`2-introduction-to-numpy.ipynb`**: Operações com arrays multidimensionais e funções matemáticas.
* **`3-matplotlib.ipynb`**: Criação de gráficos de dispersão, histogramas, box plots, etc.
    * *(Considere adicionar uma breve descrição para o `1-example-notebook.ipynb` também, se ele for um exemplo genérico ou introdutório.)*

---

## 🤝 Contribuição

Este projeto é um espaço pessoal de aprendizado, mas sinta-se à vontade para:

* Abrir `issues` para sugestões ou dúvidas.
* Fazer `fork` do repositório para experimentar por conta própria.

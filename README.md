# Projeto de Ciência de Dados II - Análise Vigitel 2024

Este repositório contém o projeto desenvolvido para a disciplina de Ciência de Dados II. O objetivo principal é realizar o processamento, análise exploratória e aplicação de técnicas de aprendizado de máquina na base de dados do Vigitel 2024.

[![Vídeo de demonstração](https://img.youtube.com/vi/TGhim9U_JBM?si=EV08coAmh_PHeSbH/0.jpg)](https://youtu.be/TGhim9U_JBM?si=EV08coAmh_PHeSbH)

## 📂 Estrutura do Repositório

* **data/**: Diretório com os dados brutos e documentação.
  * `dataset vitigel 2024.csv`: Base de dados principal.
  * `dicionario-vigitel-2006-2024.xlsx`: Dicionário explicativo das variáveis.
* **src/**: Diretório com os códigos-fonte.
  * `trabalho-cd2.ipynb`: Notebook principal contendo todo o pipeline de importação, limpeza, tratamento, análise exploratória e modelagem dos dados.
* **apresentacao_CDII.pptx.pdf**: Slides da apresentação do projeto.
* **relatorio_tecnico_CDII.pdf**: Relatório técnico detalhado com a metodologia e os resultados obtidos.
* **requirements.txt**: Lista de dependências e bibliotecas do Python necessárias para rodar o projeto.
* **.gitignore**: Arquivo de configuração do Git para ignorar pastas locais e arquivos desnecessários no versionamento (como a pasta `venv/`).

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python 3.x
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn
* **Machine Learning & Pré-processamento:** Scikit-Learn (StandardScaler, LabelEncoder, OneHotEncoder, SimpleImputer, PCA, t-SNE)

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar o ambiente e rodar o notebook na sua máquina:

### 1. Clonar o repositório

    git clone https://github.com/felipelemedias/trabalho-cd2
    cd trabalho-cd2
    code .

### 2. Criar e ativar um ambiente virtual

Para evitar conflitos de versão, é recomendado o uso de um ambiente virtual (venv).

No Windows:

    python -m venv venv
    .\venv\Scripts\activate

No Linux/macOS:

    python3 -m venv venv
    source venv/bin/activate

### 3. Instalar as dependências

Com o ambiente virtual ativado, instale as bibliotecas necessárias:

    pip install -r requirements.txt

### 4. Executar o Notebook

Abra a pasta do projeto em sua IDE preferida (como VS Code) ou inicie o Jupyter Notebook pelo terminal.

Via VS Code: Abra o arquivo `src/trabalho-cd2.ipynb` e certifique-se de selecionar o kernel do ambiente virtual (venv) no canto superior direito.

Via Terminal (Jupyter):

    jupyter notebook

Navegue até a pasta `src/` e abra o arquivo `trabalho-cd2.ipynb`.

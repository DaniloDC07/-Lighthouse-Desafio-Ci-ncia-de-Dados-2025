# [Lighthouse] Desafio Ciência de Dados-2025

Terceira etapa do processo seletivo do programa LIGHTHOUSE DA Indicium para a carreira de Ciência de Dados.

## Contexto do Projeto
Fui alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente no processo de criação de uma plataforma de aluguéis temporários na cidade de Nova York. Para o desenvolvimento de sua estratégia de precificação, pediu para que a Indicium fizesse uma análise exploratória dos dados de seu maior concorrente, assim como um teste de validação de um modelo preditivo.

O **objetivo** deste projeto é desenvolver um modelo preditivo de preços para uma plataforma de aluguéis temporários em Nova York, analisando dados do maior concorrente da empresa.

### Este desafio avalia:

- Conhecimento em estatística e modelos preditivos;
- Criatividade na resolução de problemas;
- Aplicação de modelos básicos de machine learning.


## Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido utilizando **Python 3.x** e as seguintes bibliotecas:
  - **Manipulação de dados:**
      - `numpy` - Manipulação de arrays e operações matemáticas
      - `pandas` - Análise e manipulação de dados
      
  - **Visualização:**
      - `cartopy` - Biblioteca para criação de mapas e visualizações geográficas
      - `matplotlib` - Criação de gráficos e visualizações
      - `geopandas` - Para manipulação de dados geoespaciais
      - `geodatasets` - Acesso a datasets geoespaciais para background de gráficos espaciais
      - `seaborn` - Biblioteca para visualização estatística
      - `wordcloud` - Geração de nuvens de palavras
        
  - **Modelagem Preditiva:**
      - `scikit-learn` - Modelos de machine learning
      - `torch`- Framework de machine learning para computação com GPU
  
  - **Processamento de Linguagem Natural (NLP):**
      - `nltk` - Natural Language Toolkit, para processamento de linguagem natural


## Instalação

1. **Clone o repositório:**

   Primeiro, clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/DaniloDC07/LH_CD_DANILO_DIAS_CRUZ.git
   cd LH_CD_DANILO_DIAS_CRUZ 
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado):**

   Criar um ambiente virtual para garantir que as dependências sejam isoladas:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use venv\Scripts\activate
    ```

3. **Instale as dependências:**
   
    O repositório contém um arquivo *requirements.txt* com todas as bibliotecas necessárias para o funcionamento do projeto.
    Para instalar as bibliotecas, use o seguinte comando:
    ```bash
    pip install -r requirements.txt
    ```

4. **Executando o Jupyter Notebook:**

   Para iniciar o Jupyter Notebook, execute o seguinte comando no terminal dentro do diretório do projeto
    ```bash
    jupyter notebook
    ```

## Como Utilizar o Projeto

1. **Exploração dos Dados:**
   
    Abra o Jupyter Notebook e execute as células para visualizar estatísticas e gráficos.
    A análise inicial ajudará a entender a distribuição dos preços e identificar padrões.

2. **Treinamento do Modelo:**

    Testamos diferentes abordagens para prever os preços com base nas características dos imóveis.

3. **Previsão de Preço:**

    Aplicamos o modelo para prever o preço de um apartamento específico.
  
4. **Exportação do Modelo:**

    O modelo treinado foi salvo no formato .pkl para reutilização e se encontra disponivel no repositório.

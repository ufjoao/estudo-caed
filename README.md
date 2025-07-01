# Análise de Sentimento e Predição de Gênero em Letras de Música

## Descrição do Projeto

Este projeto foi desenvolvido como parte do processo seletivo do CAEd e demonstra um pipeline completo de análise de dados textuais. A partir de uma base de dados de letras de música, foram realizadas duas tarefas principais:
1.  **Análise de Polaridade:** Para entender a evolução do sentimento nas obras de artistas e sua correlação com a popularidade.
2.  **Predição de Gênero:** Construção de um modelo de Machine Learning para classificar o gênero musical a partir da letra, incluindo um ciclo de otimização para lidar com dados desbalanceados.

## Estrutura do Repositório

- **/notebooks:** Contém o Jupyter Notebook `Modelo_Analise.ipynb` com todo o código e análise.
- **/reports:** Contém os gráficos gerados e o relatório técnico final em PDF.
- **/data:** Destinado a arquivos de dados. O dataset original não foi incluído devido ao seu tamanho. O cache da análise de sentimento (`.parquet`) também é ignorado por este repositório.

## Como Executar

1.  Clone este repositório:
    git clone https://github.com/ufjoao/estudo-caed

2.  Navegue até a pasta do projeto e crie um ambiente virtual:
    python -m venv .venv
    .\.venv\Scripts\activate
    
3.  Instale as dependências:
    pip install -r requirements.txt

4.  Abra o Jupyter Notebook na pasta `notebooks` para executar a análise.
    jupyter notebook


## Ferramentas Utilizadas
- Python 3
- Pandas e NumPy
- Scikit-learn
- NLTK
- Matplotlib e Seaborn
- Jupyter Notebook
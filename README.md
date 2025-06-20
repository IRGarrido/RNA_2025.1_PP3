# RNA_2025.1_PP3
Treinamento de modelos de classificação para projeto prático da disciplina Redes Neurais Artificiais.

# RNA_PP3
Repositório destinado à publicação das atividades do 23° Projeto Prático de Redes Neurais Artificiais 2025.1  
**Data de criação:** 24/05/2025
**Última atualização:** 10/06/2025 

Este projeto tem por objetivo a execução de um treinamento mediante Aprendizado Supervisionado de uma rede neural MLP para problemas de classificação. Nesse contexto, utiliza-se o dataset Stellar Classification Dataset - SDSS17, com dados disponíveis à comunidade científica pelo servidor Skyserver do levantamento astronômico Sloan Digital Sky Survey. A tarefa de classificação utiliza de valores ondas emitidas por um corpo celestes para definir se este é uma galáxia, quasar ou estrela.
Disponível em: https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17 

## Tecnologias Utilizadas
- **Anaconda:** Gerenciamento de ambientes virtuais;
- **Python:** Execução do algoritmo, utilizando as seguintes bibliotecas:
  - **Joblib:** Armazenamento do modelo em disco;
  - **Keras:** Métricas de treinamentos, modelos de redes neurais artificiais e busca em grade (usado em modelo inicial);
  - **Matplotlib:** Plotagem de gráficos;
  - **Numpy:** Processos matriciais otimizados;
  - **Pandas:** Manipulação de dados;
  - **Pretty-table:** Organização e plotagem de dados tabulares;
  - **Sci-kit learn:** Métricas de treinamentos e modelos de redes neurais artificiais;
  - **XGBoost:** Modelo classificador XGBoost (Extreme Gradient Boost).

## Estrutura do Projeto
```plaintext
RNA_2025.1_PP3/
├── holdout                                       # Armazenamento de datasets de treino e de teste divididos entre atributo alvo e features
├── tuner1_dir/star_classification                # Resultados da busca em grade do Keras
├── .gitignore                                    # Manipulação de git para evitar conflitos de output na branch master
├── analise_exploratoria.ipynb                    # Jupyter Notebook contendo a manipulaçao do dataset
├── grid_search.ipynb                             # Jupyter Notebook contendo tentativa inicial de busca em grade com hiperparâmetros selecionados
├── treinamento.ipynb                             # Jupyter Notebook contendo treinamento e busca em grade de redes neurais artificias por abordagens holdout 60/40 e downsampling
├── xgboost.ipynb                                 # Jupyter Notebook contendo treinamento do modelo XGBoost
├── analise_experimentos.ipynb                    # Jupyter Notebook contendo uma breve análise dos experimentos realizados comparado métricas 
├── star_classification.csv                       # Dataset utilizado para o problema de classificação
├── modified_star_classification.csv              # Dataset modificado através do Jupyter Notebook analise_exploratoria.ipnyb
├── mlp_model.joblib                              # Melhor modelo de rede neural artificial MLP encontrado
└── README.md                                     # Documentação do projeto
```

## Autores
- Professora orientadora: Elloa B. Guedes (ebgcosta@uea.edu.br)
- Adriana Raffaella Dos Santos Fonseca (ardsf.eng23@uea.edu.br)
- Ana Flavia De Castro Segadilha Da Silva (afdcsds.eng23@uea.edu.br)
- Davi Aguiar Moreira (dam.eng23@uea.edu.br)
- Guilherme Goncalves Moraes (ggm.eng23@uea.edu.br)
- Ian Garrido Reis (igr.eng23@uea.edu.br)
- Luiz Fernando Borges Brito (lfbb.eng23@uea.edu.br)
- Pedro Vitor Barros Maranhão (pvbm.eng23@uea.edu.br)
- Rita De Cassia Brasil Alves (rdcba.eng23@uea.edu.br)
- Yago De Oliveira Feitoza (ydof.eng21@uea.edu.br)

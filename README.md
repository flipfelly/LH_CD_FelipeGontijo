# LH_CD_FelipeGontijo

Case técnico do processo seletivo Indicium - Lighthouse Data & Analytics

## Sobre o Projeto

Este repositório contém a solução desenvolvida para o case técnico do processo seletivo da Indicium. O projeto apresenta uma análise completa de dados utilizando técnicas de machine learning, com foco na aplicação do algoritmo Random Forest para modelagem preditiva.

## Tecnologias Utilizadas

- Python 3.8+
- Pandas
- NumPy
- Matplotlib/Seaborn
- Jupyter Notebook
- Scikit-learn
- Random Forest Classifier/Regressor
- Pickle

## Estrutura do Projeto

```
LH_CD_FelipeGontijo/
├── data/                   # Dados utilizados no projeto
├── case_indicium-EDA.ipynb              # Análise Exploratória de Dados
├── Case_Indicium-Model      # Modelagem e análises complementares
├── requirements.txt        # Dependências do projeto
└── README.md              # Documentação do projeto
```

## Instalação e Configuração

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Procedimento de Instalação

1. **Clonar o repositório**
```bash
git clone https://github.com/flipfelly/LH_CD_FelipeGontijo.git
cd LH_CD_FelipeGontijo
```

2. **Instalar dependências**
```bash
pip install -r requirements.txt
```

3. **Executar a análise**
```bash
jupyter notebook
```

## Ordem de Execução

Recomendo seguir a sequência abaixo para compreensão completa da solução:

1. **case_indicium-EDA.ipynb** - Análise exploratória inicial dos dados
2. **Case_Indicium-Model.ipynb** - Modelo

## Metodologia

### Análise Exploratória de Dados (EDA)
- Caracterização do dataset
- Identificação de padrões e anomalias
- Análise de correlações e distribuições


### Modelagem
O modelo escolhido para este projeto foi o **Random Forest**.

#### Justificativa para Escolha do Random Forest

**Vantagens:**
- **Robustez**: Menor propensão ao overfitting comparado a árvores individuais
- **Interpretabilidade**: Fornece feature importance para análise de variáveis
- **Versatilidade**: Funciona bem com dados categóricos e numéricos
- **Tratamento de missing values**: Lida naturalmente com valores ausentes
- **Não-linearidade**: Captura relações complexas entre variáveis
- **Estabilidade**: Menos sensível a outliers

**Limitações:**
- **Complexidade computacional**: Maior tempo de treinamento e predição
- **Memória**: Requer mais recursos computacionais para armazenamento
- **Interpretabilidade limitada**: Menos interpretável que modelos lineares simples
- **Bias em dados desbalanceados**: Pode favorecer classes majoritárias
- **Overfitting em datasets pequenos**: Pode apresentar overfitting em amostras reduzidas


---

## Contexto do Desenvolvimento

Este projeto foi desenvolvido como parte do processo seletivo da Indicium, demonstrando competências técnicas em:
- Análise exploratória de dados
- Seleção e implementação de algoritmos de machine learning
- Avaliação crítica de modelos
- Comunicação técnica de resultados

## Documentação

Para iniciar a análise, execute o notebook case_indicium-EDA.ipynb, que contém o contexto completo e a fundamentação para as decisões técnicas subsequentes.

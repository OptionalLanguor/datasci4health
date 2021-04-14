# Influência da Descontinuação da Medicação de Parkinson nas Funções Cerebrais

## Influence of Parkinson's Medication Discontinuation on Brain Functions

## Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação Ciência e Visualização de Dados em Saúde, oferecida no primeiro semestre de 2021, na Unicamp.
 
Integrantes:

| Nome                               | RA     | Especialização                     |
|------------------------------------|--------|------------------------------------|
| Alessandro Welbi Domingues Junior  | 263535 | Ciências Farmacêuticas             |
| Alex de Castro Carvalho            | 134749 | Neurociências                      |
| Felipe Augusto Oliveira dos Santos | 233292 | Engenharia de Automação e Controle |
| Felipe Marinho Tavares             | 265680 | Engenharia da Computação           |
| Thiago Machado da Cunha            | 231357 | Engenharia Eletrônica              |

## Descrição Resumida do Projeto

Este projeto tem como objetivo mensurar os efeitos da descontinuação da medicação de Parkinson nas funções cerebrais.
Link para vídeo de apresentação da proposta do projeto: https://www.youtube.com/watch?v=MeClDQ8rOfA

## Pergunta de Pesquisa

"Há diferença significativa nas funções cerebrais de pacientes com doença de Parkinson após interrupção da farmacoterapia por 15 horas?"

## Bases de Dados

### EEG: Simon Conflict in Parkinson's
### Eletroencefalografia (EEG) em Parkinson

Tarefa de conflito de Simon com custo de manipulação com reforço. 28 pacientes com Parkinson e 28 controles pareados. A PD (Parkinson Disease) veio duas vezes com intervalo de uma semana, com ou sem medicação. O CTL (pessoa saudável) só entrou uma vez. Tarefa incluída na linguagem de programação Matlab. Dados coletados por volta de 2015 no Laboratório de Ritmos Cognitivos e Computação da Universidade do Novo México. Os participantes também tinham um acelerômetro colado na mão mais afetada por tremores. Dimensões X, Y, Z registradas por toda parte.
James F Cavanagh and Arun Singh and Kumar Narayanan (2021). EEG: Simon Conflict in Parkinson's. OpenNeuro. [Dataset] doi: 10.18112/openneuro.ds003509.v1.1.0
EEG: Simon Conflict in Parkinson's - Snapshot 1.1.0

## Metodologia

A metodologia seguirá como base o método KDD (Knowledge Discovery and Data Mining), processo de descobrimento de conhecimento a partir de dados. Neste projeto seguiremos os seguintes passos:

* Separação dos dados de interesse
* Pré-processamento dos dados, para a exclusão dos ruídos nas séries temporais.
* Transformar as séries temporais pré-processadas em matrizes de correlação.
* Utilizar as matrizes de correlação em aprendizado de máquina para classificar os pacientes medicados e não medicados.
 
## Ferramentas

As ferramentas que serão utilizadas durante o planejamento, execução e análise deste projeto seguem listados abaixo:
- GitHub
- Matlab
- Python
- Google Docs
- Google Drive
- Pandas
- Scikit Learn
- Keras
- PyTorch
- TensorFlow
- Scipy
- Google Colab
- Jupyter Notebook

## Cronograma

As atividades do projeto têm sua organização baseada no método KDD (Knowledge Discovery and Data Mining), com adaptações em suas etapas.

1. Estudo do domínio e revisão de literatura
2. Seleção de base de dados
3. Limpeza e pré-processamento de dados
  * Análise de exploração de dados (EDA, Exploratory Data Analysis)
  * Identificação e remoção de ruído e outliers
  * Seleção e separação de dados
  * Definição de estratégia para dados faltantes
4. Redução e projeção dos dados
  * Descobrimento de características úteis para representação dos dados
  * Diminuição de dimensionalidade e redução de variáveis para obtenção de representações invariantes
5. Estudo e comparação de algoritmos para mineração de dados
  * Comparar adequação para uso de métodos de mineração de dados com a natureza e representação do dado
  * Procura de parâmetros para algoritmos, objetivando melhoria no encontro de padrões de interesse nos dados
  * Interpretação de padrões encontrados
6. Consolidação do conhecimento descoberto em relatórios

| Atividades | Abril W1 | Abril W2 | Abril W3 | Abril W4 | Abril W5 | Maio W1 | Maio W2 | Maio W3 | Maio W4 |
|------------|----------|----------|----------|----------|----------|---------|---------|---------|---------|
| 1          | X        | X        | X        | X        |          |         |         |         |         |
| 2          | X        | X        |          |          |          |         |         |         |         |
| 3          |          | X        | X        | X        |          |         |         |         |         |
| 4          |          |          | X        | X        | X        | X       |         |         |         |
| 5          |          |          |          |          | X        | X       | X       | X       |         |
| 6          | X        |          |          |          |          | X       |         | X       | X       |

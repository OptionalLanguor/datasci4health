# Influência da Descontinuação da Medicação de Parkinson nas Funções Cerebrais

## Influence of Parkinson's Medication Discontinuation on Brain Functions

## Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health/home), oferecida no primeiro semestre de 2021, na Unicamp.
 
Integrantes:

| Nome                           	| RA 	| Especialização                 	|
|------------------------------------|--------|------------------------------------|
| Alessandro Welbi Domingues Junior  | 263535 | Ciências Farmacêuticas         	|
| Felipe Augusto Oliveira dos Santos | 233292 | Engenharia de Automação e Controle |
| Felipe Marinho Tavares         	| 265680 | Engenharia da Computação       	|
| Thiago Machado da Cunha        	| 231357 | Engenharia Eletrônica          	|

## Descrição Resumida do Projeto

Este projeto tem como objetivo mensurar os efeitos da descontinuação da medicação de Parkinson nas funções cerebrais.

# Vídeos do Projeto

## Vídeo da Proposta
Link para [vídeo de apresentação da proposta do projeto](https://youtu.be/YZS0005Awzs).

## Vídeo da Apresentação Final
Link para [vídeo de apresentação final do projeto](https://youtu.be/YZS0005Awzs).

# Slides do Projeto

## Slides da Apresentação Final
Link para [slides da apresentação final do projeto](EEG - Project Presentation.pdf).

# Introdução e Referenciais de Teóricos

A doença de Parkinson (DP) é uma doença neurodegenerativa que se caracteriza pela perda de neurônios dopaminérgicos na substância negra. A neurodegeneração na doença de Parkinson se manifesta em dificuldades de execução motora e cognitivas. A atividade exagerada dos gânglios basais é comumente encontrada em pacientes com  Parkinson e pode ser suprimida por tratamento com fármaco precursor dopaminérgico, com o grau de supressão sendo correlacionado com a melhora dos sintomas. (Güntekin B. et al; Cognitive Impairment in Parkinson’s Disease Is Reflected with Gradual Decrease of EEG Delta Responses during Auditory Discrimination; 2018) (Cavanagh J. F. et al; Cognitive states influence dopamine-driven aberrant learning in Parkinson’s disease; 2017).
Diferentes biomarcadores são estudados para avaliar os sintomas motores e o risco de demência em pacientes com a doença de Parkinson podendo realizar-se tanto uma análise quantitativa quanto qualitativa por eletroencefalografia (EEG).

A atividade beta exagerada dos gânglios basais (13-35 Hz) é comumente encontrada em pacientes com doença de Parkinson e pode ser suprimida por tratamento com fármaco precursor dopaminérgico (ex. levodopa), com o grau de supressão sendo correlacionado com a melhora dos sintomas motores. A atividade beta consiste fisiologicamente em explosões fásicas de curta duração nos circuitos motores corticais-gânglios basais, mas em pacientes com Parkinson apresenta tendência em consistir em rajadas fásicas de maior duração (Tinkhauser G. et al; Beta burst dynamics in Parkinson’s disease OFF and ON dopaminergic medication; 2017). 
A atividade teta médio-frontal (4 - 8 Hz) é particularmente prevalente após novos estímulos, instruções conflitantes ou após erros. A atividade teta é modulada após erros durante o tempo de reação correlacionados com ajustes pós-erro e relacionada com neurônios frontais únicos que controlam tais ajustes. Para avaliar tal atividade é possível utilizar metodologia como o conflito de Simon para gerar conflitos e decisões dos pacientes, avaliando assim a atividade na banda de 4 a 8Hz. (Singh A. et al; Mid-frontal theta activity is diminished during cognitive control in Parkinson’s disease; 2018).
Outro indicador que pode ser utilizado na avaliação da doença de Parkinson em paciente é a atividade delta (0,5 - 4 Hz) do eletroencefalograma (EEG). Esta é um dos indicadores eletrofisiológicos essenciais que podem mostrar o declínio cognitivo. Muitas pesquisas na literatura mostraram um aumento das respostas delta com o aumento da carga cognitiva. Além disso, as respostas delta foram diminuídas em comprometimento cognitivo leve e doença de Alzheimer em comparação com controles saudáveis durante paradigmas cognitivos, como o conflito de Simon. (Güntekin B. et al; Cognitive Impairment in Parkinson’s Disease Is Reflected with Gradual Decrease of EEG Delta Responses during Auditory Discrimination; 2018)

Neste estudo foram processados dados de 28 pacientes com Parkinson que visitaram o laboratório duas vezes com sete dias de intervalo: uma primeira com o protocolo de farmacoterapia sendo seguido e uma vez após 15 horas da última administração de levodopa. Tais condições são referidas como ON ou OFF. Os pacientes foram contrabalançados nas sessões com base em um modelo aleatório predefinido; havia um número igual de pacientes com Parkinson ON e OFF na primeira sessão. 
Os pacientes foram expostos a um conflito de Simon modificado e ocorrendo da seguinte forma: Em cada fase de treinamento, uma tarefa Simon modificada foi utilizada para eliciar o conflito de resposta durante a apresentação de quatro estímulos únicos. Cada estímulo foi apresentado no lado esquerdo ou direito da tela. Os participantes foram instruídos a pressionar o botão esquerdo do *gamepad* quando o estímulo era amarelo e o botão direito quando estava azul. Essas apresentações eram, portanto, espacialmente congruentes (lado da tela = mão de resposta) ou incongruentes (lado da tela ≠ mão de resposta) como em uma tarefa padrão do Simon. Os estímulos consistiam em quatro formas exclusivas atribuídas aleatoriamente. Seguindo uma resposta precisa, os participantes podem ganhar pontos (teste premiado; verde +1) ou não (teste de punição; vermelho 0) de acordo com um cronograma probabilístico.
Na tarefa de Simon, os participantes respondem a estímulos visuais ao realizar uma resposta, movendo-se à direita para um estímulo (por exemplo, ao ver um quadrado), ou movendo-se à esquerda para outro estímulo diferente (por exemplo, ao ver um círculo). Estímulos são apresentados às vezes no canto direito de um display e às vezes no canto esquerdo. Para uso deste banco de dados, não é relevante o desempenho dos pacientes em responder aos estímulos corretamente. O interesse está nos dados coletados de ondas cerebrais (EEG) e de acelerômetro.

# Pergunta de Pesquisa

"Há diferença significativa nas funções cerebrais de pacientes com doença de Parkinson após interrupção da farmacoterapia por 15 horas?"

# Objetivos do Projeto

Extrair informações do sinal de EEG de pacientes com Parkinson, e controle, para analisar se é possível identificar a existência ou não de diferença de funções cerebrais através de métodos estatísticos aplicados ao EEG.

## Bases de Dados

### EEG: Simon Conflict in Parkinson's
### Eletroencefalografia (EEG) em Parkinson

Tarefa de conflito de Simon com custo de manipulação com reforço. 28 pacientes com Parkinson e 28 controles pareados. A PD (Parkinson Disease) veio duas vezes com intervalo de uma semana, com ou sem medicação. O CTL (pessoa saudável) só entrou uma vez. Tarefa incluída na linguagem de programação Matlab. Dados coletados por volta de 2015 no Laboratório de Ritmos Cognitivos e Computação da Universidade do Novo México. Os participantes também tinham um acelerômetro colado na mão mais afetada por tremores. Dimensões X, Y, Z registradas por toda parte.
James F Cavanagh and Arun Singh and Kumar Narayanan (2021). EEG: Simon Conflict in Parkinson's. OpenNeuro. [Dataset] doi: 10.18112/openneuro.ds003509.v1.1.0
EEG: Simon Conflict in Parkinson's - Snapshot 1.1.0

### Análise exploratória no dataset:

* Análise de metadados: [notebooks/e2_metadata_analysis.ipynb](notebooks/e2_metadata_analysis.ipynb)
* Análise de sinais de EEG por recordings: [notebooks/e2_per_recording_analysis.ipynb](notebooks/e2_per_recording_analysis.ipynb)

## Metodologia

A metodologia seguirá como base o método KDD (Knowledge Discovery and Data Mining), processo de descobrimento de conhecimento a partir de dados. Neste projeto seguiremos os seguintes passos:

* Separação dos dados de interesse
* Pré-processamento dos dados, para a exclusão dos ruídos nas séries temporais.
* Transformar as séries temporais pré-processadas em matrizes de correlação.
* Utilizar as matrizes de correlação em aprendizado de máquina para classificar os pacientes medicados e não medicados.

### Integração entre Bases e Análise Exploratória

Com o intuito de realizar   exploratória a partir dos dados brutos obtidos, foi necessário a realização de um processamento adicional visando a criação de uma nova feature. Conforme as referências bibliográficas, esse processamento adicional se faz extremamente útil quando se trata de processamento de sinais de EEG.

Um dos métodos mais amplamente usados para analisar dados de EEG é decompor o sinal em bandas de frequência funcionalmente distintas, como delta (0,5-4 Hz), theta (4-8 Hz), alfa (8-12 Hz), beta (12-30 Hz) e gama (30-100 Hz). Isso implica na decomposição do sinal EEG em componentes de frequência, o que é comumente obtido através de transformadas de Fourier, que retorna, para cada categoria de frequência, um número complexo do qual se pode então facilmente extrair a amplitude e fase do sinal nessa frequência específica. Na análise espectral, é comum tomar o quadrado da magnitude do FFT para obter uma estimativa da densidade espectral de potência (ou espectro de potência, ou periodograma), expressa em (micro) -Volts2 por Hertz no caso de dados de EEG .

Embora uma miríade de análises possa ser realizada a partir da densidade espectral de potência, nos concentramos aqui em uma muito simples: a potência média da banda, que consiste em calcular um único número que resume a contribuição de determinada banda de frequência para o total potência do sinal. Isso pode ser particularmente útil em uma abordagem de aprendizado de máquina, quando geralmente você deseja extrair alguns recursos-chave ou features de seus dados.

Sendo assim, visando obter uma maior quantidade de features em nosso dataset, realizamos uma análise de bandpower para todos os canais dispostos no dataset, utilizando as 5 diferentes frequências de atividade além dos dados de todos os pacientes que realizaram o teste.

No *dataframe* obtido ficaram então dispostas as seguintes variáveis: o valor absoluto de potência de banda média, a potência de banda relativa, que é a expressão da potência em uma banda de frequência como uma porcentagem da potência total do sinal, o paciente, a sessão de teste, a frequência de atividade mensurada naquela banda e o canal estimado. Além dos canais comumente conhecidos no EEG, também foi realizado a mesma analise para 3 sinais de referência nos eixos X, Y e Z em um acelerômetro colocado na mão dos pacientes.

## Ferramentas

As ferramentas que foram utilizadas durante o planejamento, execução e análise deste projeto são listadas abaixo:

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

# Discussão

Modelando um problema como classificação binária para pacientes com Parkinson que tiveram a interrupção de farmacoterapia, foram configurados experimentos utilizando classificadores: Logistic Regression, SVM, KNN, Decision Tree, e Random Forest. Nas variações dos experimentos foi explorado o uso do sinais de acelerômetro, de todos os canais de EEG, e de apenas canais Fz, Pz e Oz que possuem relevância descrita na literatura para a doença de Parkinson. Os canais de EEG foram analisados também considerando cada uma das cinco bandas de frequência: delta (0.5–4 Hz), theta (4–8 Hz), alpha (8–12 Hz), beta (12–30 Hz), e gamma (30~100 Hz). Os experimentos de classificação foram conduzidos no notebook "[e3_classification.ipynb](notebooks /e3_classification.ipynb)" onde a implementação do código, definição de experimentos, e resultados podem ser acompanhados.

Foi obtida a matrix de correlação gerada pelas features obtidas a partir de estatísticas descritivas (média, desvio padrão, *quartiles*, para canais de EEG e ACC) e da feature bandpower (absoluto e relativo) para 5 bandas de frequência dos sinais: delta (0.5–4 Hz), theta (4–8 Hz), alpha (8–12 Hz), beta (12–30 Hz), gamma (30–100 Hz). O acelerômetro mostrou possuir forte contribuição para identificação de pacientes de Parkinson com interrupção de farmacoterapia devido a estar aferindo diretamente movimentos dos pacientes. Para os canais de EEG, os canais na linha central da cabeça (Fz, Pz e Oz) mostraram-se relevantes e dentro das features com maior correlação com a classe "Pacientes de Parkinson com interrupção de farmacoterapia".

O melhor experimento avaliado no conjunto de teste (30% do dataset) para classificação obtido foi o Logistic Regression com regularização L2, usando features de bandpower e considerando do EEG apenas canais Fz, Pz, e Oz, com métricas no teste de "Cohen Kappa 0.4620", "ROC AUC 0.7518", "Balanced Accuracy 0.7518".

# Conclusão

O trabalho mostrou que há diferença significativa nas funções cerebrais de pacientes com doença de Parkinson após interrupção da farmacoterapia através da avaliação dos efeitos da descontinuação da medicação de Parkinson nas funções cerebrais. Foram processados os sinais nos canais de EEG através de analise de bandpower e de estatísticas descritivas, foi realizado uma analise exploratória dos dados mostrando correlações entre as features selecionadas e por fim uma análise comparativa entre algoritmos de classificação visando um diagnóstico inteligente de pacientes que tenham ou não Parkinson.
Em trabalhos futuros poderia-se explorar a modelagem de classificadores estatísticos para identificação segmentos de tempo de pacientes com Parkinson com interrupção de farmacoterapia. Mudando do uso de todo *recording* de sinais para apenas a classificação de segmentos de tempo (i.e. períodos de 1 minuto, ou 5 minutos, de dados de entrada), podendo prover assim informação de qual segmento de tempo possui o comportamento que indica que um paciente de Parkinson possa não estar sobre efeito de farmacoterapia.

# Referências Bibliográficas

Cavanagh J. F. et al; Cognitive states influence dopamine-driven aberrant learning in Parkinson’s disease; 2017.
https://pubmed.ncbi.nlm.nih.gov/28384481/#:~:text=Individual%20differences%20in%20dopaminergic%20tone,as%20a%20function%20of%20medication.

Güntekin B. et al; Cognitive Impairment in Parkinson’s Disease Is Reflected with Gradual Decrease of EEG Delta Responses during Auditory Discrimination; 2018.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5826339/

Singh A., et al; Mid-frontal theta activity is diminished during cognitive control in Parkinson's disease, 2018.
https://pubmed.ncbi.nlm.nih.gov/29802866/

Tinkhauser G., et al; Beta burst dynamics in Parkinson’s disease OFF and ON dopaminergic medication 2017.
https://academic.oup.com/brain/article/140/11/2968/4430808

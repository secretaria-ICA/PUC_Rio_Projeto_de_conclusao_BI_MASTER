#### Aluno: [Cristóvão Augusto Pessanha de Souza Júnior](https://github.com/crisouzajr)
#### Orientadora: [Nome Sobrenome](https://github.com/link_do_github) e [Nome Sobrenome](https://github.com/link_do_github).
#### Co-orientador(/a/es/as): [Nome Sobrenome](https://github.com/link_do_github) e [Nome Sobrenome](https://github.com/link_do_github). 


---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina 
"Projetos de Sistemas Inteligentes de Apoio à Decisão".

<!-- para os links a seguir, caso os arquivos estejam no mesmo repositório que este README, não há necessidade de incluir o link completo: basta incluir 
o nome do arquivo, com extensão, que o GitHub completa o link corretamente -->

- [Link para o código_1 https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclus-o_BI_MASTER/blob/1)-An%C3%A1lise-Explort%C3%B3ria-e-S%C3%A9rie-Temporal/1)_Exploratory_analysis_and_graphs_development.ipynb]

- [Link para o código_2 https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclus-o_BI_MASTER/tree/2)-Presets-como-atributos-XGBoost-para-categoriza%C3%A7%C3%A3o]

- [Link para o código_3 https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclus-o_BI_MASTER/tree/3)-Vari%C3%A1veis-f%C3%ADsicas-operacionais-XGBoost-para-categoriza%C3%A7%C3%A3o]

- [Link para o código_4 https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclus-o_BI_MASTER/tree/4)-%C3%A1rvore-de-decis%C3%A3o-para-classifica%C3%A7%C3%A3o-no-conjunto-completo].

- [Link para a monografia](https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclus-o_BI_MASTER/blob/main/Relat%C3%B3rio.pdf).


---

### Resumo

A possibilidade de demarcar exatamente onde irá ocorrer as operações de perfuração, otimização das operações de perfuração, bem como manutenção preditivas 
e detecção de falhas, são algumas das possibilidades que o Machine Learning aplicado a indústria de O&G pode nos oferecer. Nesse projeto, vou demonstrar 
através de um modelo de Machine Learning como é possível, estruturar uma ferramenta preditiva, para evitar falhas em equipamentos, melhorando assim o seu desempenho. 

### Abstract 

The possibility of demarcating exactly where drilling operations will take place, optimization of drilling operations, as well as predictive maintenance 
and fault detection, are some of the possibilities that Machine Learning applied to the O&G industry can offer us. In this project, 
I will demonstrate through a Machine Learning model how it is possible to structure a predictive tool to avoid equipment failures, thus improving its performance.


### 1. Introdução

De acordo com a Sociedade Internacional de Automação, cerca de 647 Bilhões de dólares são perdidos anualmente devido a paradas de produção relacionadas com falhas 
em equipamentos. A partir dos dados gerados por sensores instalados nesses equipamentos, e utilizando de modelos de IA preditivos, empresas estão podendo detectar 
falhas em equipamentos antes que elas venham a ocorrer. XGBoost, LSTM e Autoencoders, são algumas das tecnologias de IA que podem estimar e diagnosticar as condições 
operacionais de equipamentos, prevendo e informando qual intervalo de tempo apropriado para que um serviço de manutenção seja realizado. Todos os modelos têm 
como base de apoio para sua construção, bibliotecas já conhecidas como TensorFlow e Keras.


### 2. Modelagem

Nesse projeto, utilizei um modelo que demonstra como classificar e outro para categorizar falhas em equipamentos. Através deste relatório, demonstro como ocorreu a 
criação de cada sequência de notebook, onde a proposta é responder algumas perguntas que servem como direcionamento a um objetivo específico, onde a criação das 
inferências foi feita a partir de um conjunto de dados brutos, ou seja, utilizando uma base de dados vinda de um banco específico, já pronta para que seja construído 
o modelo de Machine Learning a partir da mesma. Para criação dos notebooks, utilizei o Google Colab e algumas bibliotecas como: Pandas e Scikit-Learn, para criação 
dos Modelos de Machine Learning e os gráficos categorizadores, Plotly como meio de criar séries temporais, onde os ciclos de funcionamento do equipamento é a 
base para criação da time-line para inferência dos resultados.



### 3. Resultados

Após realizar uma análise exploratória minuciosa da base de dados original, entendi que era preciso utilizar um recurso estatístico de correlação entre os atributos 
gerentes  e as falhas, logo, após a inferência, foi entendido que os atributos, Preset_1 e Preset_2, mesmo quando utilizando o recurso one hot encoder, 
não houve uma correlação significativa que justificasse a permanência desses dois atributos, durante a criação dos modelos de Machine Learning, tanto para, 
Classificação e Categorização. 

Quando criados, os dois modelos desempenharam suas funções de acordo com a ideia desenvolvida para o projeto, onde o XGboost alcançou uma média absoluta entre 
os erros de 9,1%, categorizando as falhas em 3 classes, e onde através alguma função localizadora, é possível identificar e separar esses dados e entender 
o funcionamento do equipamento e planejar a melhor forma de evitar que novas falhas ocorram.
O modelo classificador com acurácia de 0,925, Kappa de 0,46 e F1 de 0,50, foi capaz de identificar as falhas com uma precisão de 95%.



### 4. Conclusões

Após a criação dos dois modelos de ML, é possível entender que cada um deles conseguiu cumprir de forma adequada com sua função de categorização das falhas, 
onde é possível observar uma escala com relação a um valor ideal baseado no erro médio, sendo esse modelo o Gradient Boosting Regressor.
Quando foi necessário desenvolver um modelo que fosse capaz de classificar as falhas dentro de um conjunto de dados, a Árvore de Decisão conseguiu inferir e 
classificar falhas através do modelo criado com uma acurácia superior a 94%.
Um outro recurso de extrema importância complementando o desenvolvimento do trabalho, é a possibilidade de extrair os atributos dos grupos de falhas, em conjuntos 
distinto de dados e utilizar fórmulas estatísticas ou outra tecnologia para que as falhas mais graves possam ser evitadas.

---

Matrícula: 202.190.134

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

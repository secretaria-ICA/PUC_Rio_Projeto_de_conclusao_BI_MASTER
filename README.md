#### Aluno: [Cristóvão Augusto Pessanha de Souza Júnior](https://github.com/crisouzajr)
#### Orientadora: [Nome Sobrenome](https://github.com/link_do_github) e [Nome Sobrenome](https://github.com/link_do_github).
#### Co-orientador(/a/es/as): [Nome Sobrenome](https://github.com/link_do_github) e [Nome Sobrenome](https://github.com/link_do_github). 


---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina 
"Projetos de Sistemas Inteligentes de Apoio à Decisão".

<!-- para os links a seguir, caso os arquivos estejam no mesmo repositório que este README, não há necessidade de incluir o link completo: basta incluir 
o nome do arquivo, com extensão, que o GitHub completa o link corretamente -->

- [Análise Exploratória e Desenvolvimento de Gráficos](https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclusao_BI_MASTER/blob/main/An%C3%A1lise_Explorat%C3%B3ria_e_Desenvolvimento_de_Gr%C3%A1ficos.ipynb) 

- [XGBOOST para Categorização](https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclusao_BI_MASTER/blob/main/XGBoost_para_Categoriza%C3%A7%C3%A3o.ipynb)
- [Produção GBT](https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclusao_BI_MASTER/blob/main/Produ%C3%A7%C3%A3o_Variaveis_GBT.ipynb)

- [Árvore de Decisão](https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclusao_BI_MASTER/blob/main/%C3%81rvore_de_Decis%C3%A3o_para_Classifica%C3%A7%C3%A3o.ipynb)
- [Produção DT](https://github.com/crisouzajr/PUC_Rio_Projeto_de_conclusao_BI_MASTER/blob/main/Produ%C3%A7%C3%A3o_DT.ipynb)

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

Quando aplicado à indústria, a Machine Learning é capaz de automatizar processos, otimizando operações e proporcionando um aumento de produtividade, qualidade e eficiência no desempenho das mais variadas funções.

Durante muitos anos essa nova vertente da tecnologia ainda passava por um processo de adaptação dentro das empresas e até um certo momento sofreu uma resistência quanto aos verdadeiros retornos com relação ao aprimoramento econômico com redução de custos operacionais e possibilidade de novos investimentos. 
Porém, assim como toda nova forma de se executar tarefas em uma corporação, essa inteligência teve que se adaptar e encontrar um ponto focal para que pudesse ser entendida e que os resultados encontrados pela IA, fosse mensurável e escalonado, foi então que houve a necessidade e criação do que é entendido como MLOps.

MLOps (uma combinação de Machine Learning e “operações de tecnologia da informação”) é uma nova disciplina / foco / prática para colaboração e comunicação entre Cientistas de Dados e profissionais de tecnologia da informação (TI), ao automatizar e produzir algoritmos de aprendizado de máquina. Por meio de práticas e ferramentas, o MLOps tem como objetivo estabelecer uma cultura e um ambiente em que as tecnologias de ML possam gerar benefícios comerciais, construindo, testando e liberando, de maneira rápida, frequente e confiável, a tecnologia de ML em produção.

#### O Machine Learning atualmente 

Já é sabido que a indústria como um todo está passando por diferentes transformações, advindas dos impactos da COVID-19 e foi nesse momento que a tecnologia mostrou sua real importância nesse momento em que já é entendido que o ML e IA nos auxiliou à realização de inúmeras tarefas cotidianas. 
O setor de pesquisa e desenvolvimento busca constantemente encontrar soluções que possam ser a aplicação direta do ML no tanto Downstream como no Upstream dessa indústria. 

De acordo com o relatório desenvolvido por [Mordor Intelligence](https://www.mordorintelligence.com/industry-reports/ai-market-in-oil-and-gas) , como os custos relacionados a aquisição de sensores IoT declinou, diversas outras empresas que ainda não conseguiam adquirir estes, que são peça fundamental na comunicação e distribuição de dados entre equipamentos e interfaces de execução de IA. E então existe uma expectativa bem positiva para o setor de um aumento de cerca de 10,81% nos lucros produzidos por essa indústria entre 2021-2027, graças aos advindos proporcionados pela ML e IA.

#### Machine Learning no setor de O&G

Como sou um profissional atuante do setor de O&G decidi direcionar o objetivo do projeto na área em questão, sendo que farei uma abordagem para carácter de ampliação de conhecimento de algumas das possibilidades onde acredito que o Machine Learning especificadamente possui uma funcionalidade bastante útil no sentido de redução de custos com manutenção corretiva ou erros de projetos que até o surgimento dessa inteligência se tornavam mais custosos a medida em que não era possível fazer um estudo mais aprofundado das perspectivas de produção. 

Nesse projeto, vou demonstrar através de um modelo de Machine Learning como é possível, estruturar uma ferramenta preditiva capaz de classificar e categorizar falhas em equipamentos, preservando o ativo da empresa e reduzindo custos com manutenção não programada ou desnecessária. 
A possibilidade de demarcar exatamente onde irá ocorrer as operações de perfuração, otimizar as operações de perfuração, bem como a manutenção preditivas e detecção de falhas, são algumas das possibilidades que o Machine Learning aplicado a indústria de O&G pode nos oferecer. Abaixo apresento algumas aplicabilidades reais dos conceitos mencionados acima, bem como a fonte de pesquisa onde as soluções apresentadas podem ser encontradas. 

- Previsão para Operações de Perfuração
RSI é um recurso disponibilizado em [pgs.com](https://www.pgs.com/data-library/north-and-south-america/south-atlantic-margin/campos--santos/santos-vision/) contendo os principais recursos tecnológicos de imagens, para auxiliar empresas a montar e atualizar a sua estrutura de pesquisa no campo de exploração e construir modelos de ML que possam prever pontos exatos de perfuração.

- Otimizando Operações de Perfuração
Outra vantagem proporcionada pela IA, é a otimização de operações de perfuração, uma vez que a partir de dados histórico de operações já realizadas, é possível aprimorar e aprender novas formas de execução e evitar erros passados. Um bom exemplo de aplicações realizadas com IA, é a redução no tempo e custos com operações de conexão em perfuração utilizando CNN para diagnósticos, tabulação de resultados na construção de interfaces gráficas para análises cognitivas. Mais detalhes dessa tecnologia foram apresentados na [Offshore Conference](https://onepetro.org/OTCONF/proceedings-abstract/18OTC/3-18OTC/D031S031R002/179764).

- Previsão de incidente com tubulações obstruídas de poços produtores
Recentemente, dois pesquisadores, Elahifar & Hosseini, criaram um modelo de ANN chamado [rede neural de otimização para enxame de partículas híbridas](https://link.springer.com/article/10.1007/s13202-021-01436-3#Tab17), ou em resumo (PSO-based ANN), uma tecnologia de IA capaz de prever através de utilização de algumas variáveis específicas, tais como: peso da lama, ponto de rendimento e viscosidade plástica por exemplo, onde o modelo prevê com uma acurácia de até 80%, quando uma tubulação relacionada as operações de perfuração pode vir a ser obstruída.
 
 - Manutenção Preditiva e Detecção de Falhas em equipamentos
 De acordo com a Sociedade Internacional de Automação, cerca de 647 Bilhões de dólares são perdidos anualmente devido a paradas de produção relacionadas com falhas em equipamentos. A partir dos dados gerados por sensores instalados nesses equipamentos, e utilizando de modelos de IA preditivos, empresas estão podendo detectar falhas em equipamentos antes que elas venham a ocorrer.
XGBoost, LSTM e Autoencoders, são algumas das tecnologias de IA que podem estimar e diagnosticar as condições operacionais de equipamentos, prevendo e informando qual intervalo de tempo apropriado para que um serviço de manutenção seja realizado. Todos os modelos têm como base de apoio para sua construção, bibliotecas já conhecidas como TensorFlow e Keras.



### 2. METODOLOGIA, DESENVOLVIMENTO E ESCOLHA DOS MODELOS DE MACHINE LEARNING

A metodologia que utilizei para iniciar a elaboração desse projeto consistiu em criar uma divisão do todo em 4 partes principais INTRODUÇÃO; DESENVOLVIMENTO; OBJETIVO E CONCLUSÃO.
Ao caracterizar essas 4 partes principais como partes Macro, e suas subdivisões como Micro partes, é possível assim criar um fluxo de informações que quando conectadas geram o conhecimento e proposta objetiva final.
Cada um dos pontos citados acima para construção do projeto, não necessariamente precisam possuir essa nomenclatura, porém, essa forma básica com as quatro palavras-chave, é meu guia para explicar como o tema escolhido é aplicado em um contexto social e já existente.
Na parte da Introdução eu conto como a indústria estava e vem sendo modificada, após o advindo do recurso de aprendizado de máquina, e utilizo de referências já existentes e aplicáveis para que o propósito por traz da tecnologia preditiva, possa ser entendida em diferentes ramos do setor de O&G, que é a área escolhida por mim para ser o ponto chave do projeto.

No Desenvolvimento contém a construção e união de ideias e referências, até chegar ao desenvolvimento dos primeiros códigos e busca de base de dados para inferência e demonstração do conhecimento.
Meu objetivo para projetos, é sempre baseado em conceitos de gestão de projetos onde ferramentas como 5W3H e suas extensões, são essenciais para nortear e criar um sentido geral.
E na parte de conclusão é quando através de resultados, todo o conceito de criação da solução é respondido, como também abrindo possibilidades para novas formas de pensar e otimizar até mesmo esta solução já criada.
Nesse projeto utilizei tanto um modelo que possa classificar, como também outro que possa categorizar as falhas em equipamentos.

Antes de iniciar o desenvolvimento dos códigos direcionados a classificação das falhas, realizei uma pesquisa teórica, na qual eu pudesse usar como referência na construção da ideia e até mesmo que fosse uma forma de escolher o melhor algoritmo que trouxesse respostas realmente coerentes quanto a categorização, principalmente. 
As fontes iniciais de pesquisa foram [fonte 1](https://towardsdatascience.com/machine-learning-part-18-boosting-algorithms-gradient-boosting-in-python-ef5ae6965be4) & [fonte 2](https://towardsdatascience.com/guide-to-confusion-matrices-classification-performance-metrics-a0ebfc08408e). Essas duas referências foram utilizadas como forma de guia para elaboração de toda a estrutura inicial e de escolha dos algoritmos.
Através deste relatório demonstro como acorreu a criação de cada sequência de notebook, onde a proposta é responder algumas perguntas que servem como direcionamento a um objetivo específico.

Para criação dos notebooks, utilizei o Google Colab e algumas bibliotecas como: Pandas e Scikit-Learn, para criação dos Modelos de Machine Learning e os gráficos categorizadores, Plotly como meio de criar séries temporais, onde os ciclos de funcionamento do equipamento é a base para criação da time-line para inferência e visualização.
Antes de escolher os algoritmos finais, utilizei de diferentes algoritmos, tais como: Randon Forest, KNN e SVM, comparei os resultados que cada um apresentou, e então foi quando escolhi aqueles que me trouxeram as métricas e respostas mais precisas para as inferências desenvolvidas, e que foram: XGBoost para categorização e Decision Tree para classificação. Mais detalhes sobre os dois algoritmos escolhidos, bem como cada um deles foi utilizado com a base de dados disponibilizada, são apresentados nos próximos capítulos.

Com relação ao desenvolvimento do projeto afim de se encontrar os objetivos determinados, esse projeto se dividiu em 4 etapas, onde existe primeiramente a exploração da base de dados, seguindo com a separação de alguns atributos mais específicos e realizando testes isolados com esses atributos, para saber se eles possuíam uma relevância bastante significativa quanto a produção de resultados tanto para classificação ou categorização. 
E após todos os testes e definição dos atributos essenciais a criação dos modelos, venho com a conclusão apresentando as métricas e avaliações de desempenho de cada modelo comprovando assim a eficácia de cada um deles.



### 3. DESENVOLVIMENTO

#### ANÁLISE EXPLORATÓRIA DA BASE DE DADOS

Após a realização da primeira análise exploratória, três principais aspetos foram observados na base de dados:
Shape da base de dados: 10 atributos e 800 linhas.
Missing Values: não existem dados faltantes na base.
Característica da base: Dados categóricos e dados numéricos na mesma base.

#### MODELOS DE MACHINE LEARNING

- XGBOOST

“XGBoost é uma abordagem poderosa para construir modelos de regressão supervisionada. A validade dessa afirmação pode ser inferida conhecendo sua função objetivo (XGBoost). 
A função objetivo contém uma função de perda e um termo de regularização. Ele informa sobre a diferença entre os valores reais e os valores previstos, ou seja, quão longe os resultados do modelo estão dos valores reais. 
A função de perda mais comum no XGBoost para problemas de regressão (categorização) é reg: linear, e para classificação binária é reg: logistics.

- DECISION TREE

A Árvore de Decisão é a ferramenta mais poderosa e popular para classificação e previsão. Uma árvore de decisão é uma estrutura de árvore semelhante a um fluxograma, onde cada nó interno denota um teste em um atributo, cada ramo representa um resultado do teste e cada nó folha (nó terminal) contém um rótulo de classe.
Construção da Árvore de Decisão: Uma árvore pode ser “aprendida” dividindo o conjunto de origem em subconjuntos, com base em um teste de valor de atributo. Esse processo é repetido em cada subconjunto derivado de uma maneira recursiva chamada particionamento recursivo. A recursão é concluída quando o subconjunto em um nó tem o mesmo valor da variável de destino ou quando a divisão não adiciona mais valor às previsões. A construção de um classificador de árvore de decisão não requer nenhum conhecimento de domínio ou configuração de parâmetros e, portanto, é apropriado para a descoberta de conhecimento exploratório. As árvores de decisão podem lidar com dados de alta dimensão. Em geral, o classificador de árvore de decisão tem boa precisão. A indução da árvore de decisão é uma abordagem indutiva típica para aprender o conhecimento sobre classificação.

Representação da Árvore de Decisão: As árvores de decisão classificam as instâncias através da raiz até algum nó folha, que fornece a classificação da instância. Uma instância é classificada iniciando-se no nó raiz da árvore, testando o atributo especificado por este nó e, em seguida, descendo a ramificação da árvore correspondente ao valor do atributo. Este processo é então repetido para a sub árvore enraizada no novo nó.

### OBJETIVO

#### Análise Exploratória da Base de Dados.

Antes de definir quais modelos de Machine Learning seriam os ideais para realizar o estudo, realizei os procedimentos básicos exploratório para entender a base como um todo, onde primeiramente fiz a contagem de quantas vezes dentro da base de dados houve a ocorrência de falhas.

![image](https://user-images.githubusercontent.com/73768941/194211173-d48f50d6-f853-47d4-b091-88968abadd02.png)

Outra análise exploratória e de extrema importância é entender a correlação existente entre cada um dos atributos da base, como forma até mesmo decidir a relevância de se manter determinado atributo, da mesma forma quando verificamos se algum atributo possui dados faltantes em uma quantidade grande o que faz com que sua permanência no conjunto seja desnecessária. 

![image](https://user-images.githubusercontent.com/73768941/194211036-c9a80421-b442-4e59-a683-a05d54cab413.png)

Para criação dos modelos futuros e outros tipos de análises, desenvolvi novos Dataset, onde um deles continha apenas os dados que apresentavam as falhas e outro sem as falhas, para que eu pudesse então, através de algumas análises estatísticas descritivas, entender a forma como cada uma das variáveis se apresentam durante a ocorrência e não das falhas, como mostrado na imagem abaixo.

![image](https://user-images.githubusercontent.com/73768941/194211856-3d9e4d3d-58b0-420e-8e94-1a724141bfe6.png)

Após avaliar essa parte mais descritiva do processo, entendi que era preciso realizar uma pesquisa mais aprofundada na base de dados para entender melhor o comportamento das variáveis e como seria possível fazer a categorização dos dados e não associar, já que eles possuíam uma label, sendo assim supervisionados, onde agrupamento e associação de dados com uma saída pré-definida não é uma tarefa comum para os algoritmos que eu conhecia. 
De qualquer forma realizei a criação de um modelo utilizando KNN, porém ele não teve muito sucesso dentro desse estudo, apresentando métricas de avaliação que não faziam sentido.
Foi então que retornei à minha pesquisa sobre referencial teórico e encontrei o Gradient Boost Regressor, que é um modelo capaz de categorizar conjunto de dados supervisionado utilizando regressão, ou seja, com uma saída já pré-determinada.

#### Categorizar as falhas do equipamento de acordo com os atributos.

Para que o modelo de Machine Learning fosse capaz de categorizar as falhas tivesse bons resultados, entendi que era necessário analisar a correção existente entre os atributos, e constatar a importância de alguns atributos dentro da base de dados. E de acordo com o grau de correção apresentado entre as falhas observadas dois dos atributos: Preset_1 e Preset_2, indicaram diretamente relacionado as falhas do equipamento valores mínimos, e em alguns momentos até negativos. 
Realizei a operação one – hot – encoder para verificar se dessa forma iria existir algum novo grau de proximidade entre esses dois atributos com a saída, porém após testes, não houve nenhuma diferença significativa nos resultados, que mostrassem a necessidade de se manter na base de dados os Preset_1 e Preset_2 para criação do modelo categorizador das falhas.

![image](https://user-images.githubusercontent.com/73768941/194211956-3132a56e-70b7-4338-b91d-868b3850667b.png)

Como é possível observar na imagem acima, após a criação do modelo a média absoluta entre erros foi de 9,2%.
O modelo então foi salvo utilizando e importando no notebook o recurso pickle para realizar teste de inferência com a base de dados. 
Fiz então a montagem de um outro notebook onde separei apenas os dados contendo as falhas e utilizando o modelo categorizador salvo, foi possível observar como o algoritmo separou e selecionou as categorias. 

![image](https://user-images.githubusercontent.com/73768941/194211980-f5617188-cc67-4628-afd6-6b31fa954873.png)

Somente demonstrar as categorias apresentadas pelo algoritmo não indica nenhum resultado de inteligência sustentável, pois o que algoritmo fez, foi apenas apresentar números e categorias.
Mas surgiu a questão, porque essas 3 categorias? E qual ou quais fatores e atributos que as separou dessa forma?
Foi então que realizei a separação do conjunto de dados em 3 diferentes Dataset como é visto nas, e apliquei para cada um deles uma análise estatística descritiva, para que dessa forma, eu pudesse verificar qual parâmetro o algoritmo utilizou para criar essas categorias.

 ![image](https://user-images.githubusercontent.com/73768941/194212023-0c9a4e8e-6fbc-42f4-b175-968dd2eaca26.png)

 ![image](https://user-images.githubusercontent.com/73768941/194212033-8f69718f-9d1a-4dae-b09e-6f50fe63b490.png)

 ![image](https://user-images.githubusercontent.com/73768941/194212048-b7b6ee40-aa5b-4da7-b79b-a893f6ada136.png)

E sim, realmente o GBR fez uma seleção baseada em atributos específicos e utilizou como base a relação principalmente com a medida de tendência central, que foi a média absoluta. 
Chamei df1 o conjunto de dados com 8 linhas e onde a categoria da falha possui valor de 1,012712. E então df2 será o que tem 30 linhas e categoria de falha 1,174242, e por fim df3 28 linhas com categoria de falha de 1,827586.

df1 = 1,012712
A partir dessa análise estatística descritiva, é possível observar que as variáveis relacionadas a vibração X & Z estão predominantes nessa categoria.

![image](https://user-images.githubusercontent.com/73768941/194212115-bb783ec1-23fc-4d06-85f0-ca774a00cbb6.png)

df2 = 1,174242
A partir dessa análise estatística descritiva, é possível observar que as variáveis relacionadas a temperatura e frequência estão predominantes nessa categoria. 

![image](https://user-images.githubusercontent.com/73768941/194212149-95cd99b7-3577-42b9-89a6-70523b65e596.png)

df3 = 1,827586
A partir dessa análise estatística descritiva, é possível observar que as variáveis relacionadas a pressão e vibração Y estão predominantes nessa categoria. 

![image](https://user-images.githubusercontent.com/73768941/194212196-d841b7ca-213f-4baa-a965-d088fac51108.png)

#### Aprendizado de Máquina Classificador e métrica de avaliação.

Para definir qual seria o modelo classificador a ser utilizado no projeto, desenvolvi três modelos diferentes utilizando os seguintes algoritmos: Support Vector Machine (SVM), Randon Forest (RF) e Decision Tree (DT). 
Foram utilizados todos os atributos em cada um dos modelos, e cada um deles apresentou métricas de avaliação distintas. Onde aquele que teve o melhor desempenho para classificar as falhas dentro do conjunto de dados, foi o Decision Tree / Árvore de Decisão, como é possível verificar nas imagens abaixo.

Randon Forest

![image](https://user-images.githubusercontent.com/73768941/194212273-59ee36c3-bce7-4957-b7ab-78c0142a3cbd.png)

Support Vector Machine

![image](https://user-images.githubusercontent.com/73768941/194212294-22c35c5d-708e-401b-b2e7-50886ff98555.png)

Decision Tree

![image](https://user-images.githubusercontent.com/73768941/194212318-eaeb404b-f724-4597-923a-c6e50659d077.png)

Selecionado o modelo de Árvore de Decisão para classificação das falhas, foi o momento de desenvolver um processo de produção que gerasse resultados com o modelo salvo, e que seja possível utilizar em qualquer nova base de dados apresentada.
Como é possível verificar na imagem abaixo, o modelo conseguiu classificar quase que totalmente as falhas dentro o conjunto de dados.

![image](https://user-images.githubusercontent.com/73768941/194212346-8ae800a9-4b51-4eb7-88f4-bdb6b09670c4.png)

#### Avaliando a importância das variáveis.

Durante as análises exploratórias da base de dados e consequentemente após o desenvolvimento dos modelos de Machine Learning que foram aplicados dentro desse estudo, e principalmente o modelo categorizador, foi possível verificar a importância de alguns atributos, e foi então a partir desse ponto que pensei em utilizar como base para demonstrar visualmente o comportamento das variáveis, as inferências que foram identificadas durante o processo de categorização. 

Vou demonstrar a importância das variáveis nos momentos em que as falhas ocorreram e através dos 3 Dataset que foram construídos durante a etapa de categorização fiz o desenvolvimento das séries temporais utilizando a biblioteca Plotly e como forma de criar um relatório gráfico que possa ser compartilhado utilizei o Datapane. 
Os três gráficos seguem a seguinte sequência:  df1 (vibração X & Z), df2 (temperatura e frequência) e df3 (pressão e vibração Y).

![image](https://user-images.githubusercontent.com/73768941/194212430-2e45ab6c-ac04-413e-970a-5fc01d163331.png)

![image](https://user-images.githubusercontent.com/73768941/194212437-a56f5b74-8534-4502-bf07-d244904c19f6.png)

![image](https://user-images.githubusercontent.com/73768941/194212442-4db9e036-68eb-481e-bc20-e03293fc7a9f.png)


### 4. Conclusões

Após a criação dos dois modelos de Machine Learning, foi possível entender que cada um deles conseguiu cumprir de forma adequada com sua função de categorização das falhas, onde é possível observar uma escala com relação a um valor ideal baseado no erro médio, sendo esse modelo o Gradient Boosting Regressor de 9,2%.
Já o modelo Árvore de Decisão conseguiu inferir e classificar falhas através do modelo criado com uma acurácia superior a 94%.

Um outro recurso de extrema importância complementando o desenvolvimento do trabalho, foi a possibilidade de extrair separar os grupos de falhas em conjuntos distinto de dados e utilizar fórmulas estatísticas descritivas para entender a categorização das falhas.

### REFERENCIAL TEÓRICO

[Ernest Ng, XGBoost for Multi-class Classification. Toward Data Science, 2020.](https://towardsdatascience.com/xgboost-for-multi-class-classification-799d96bcd368) 
[Destin Gong, Top 6 Machine Learning Algorithms for Classification. Toward Data Science, 2022.](https://towardsdatascience.com/top-machine-learning-algorithms-for-classification-2197870ff501) 
[North Sea Transition Authority, UKCS Production.](https://www.nstauthority.co.uk/data-centre/nsta-open-data/production/) 
[PGS, Santos Vision 3D.](https://www.pgs.com/data-library/north-and-south-america/south-atlantic-margin/campos--santos/santos-vision/) 
[Mordor Inteligence, GLOBAL AI IN OIL AND GAS MARKET - GROWTH, TRENDS, COVID-19 IMPACT, AND FORECAST (2022 - 2027).](https://www.mordorintelligence.com/industry-reports/ai-market-in-oil-and-gas) 
[OnePetro, Application of Real-time Video Streaming and Analytics to Breakdown Rig Connection Process.](https://onepetro.org/OTCONF/proceedings-abstract/18OTC/3-18OTC/D031S031R002/179764) 
[Springer, Machine learning algorithm for prediction of stuck pipe incidents using statistical data: case study in middle east oil Fields.](https://link.springer.com/article/10.1007/s13202-021-01436-3#Tab17) 
[Cory Maklin, Gradient Boosting Decision Tree Algorithm Explained. Toward Data Science, 2019.](https://towardsdatascience.com/machine-learning-part-18-boosting-algorithms-gradient-boosting-in-python-ef5ae6965be4) 
[Nima Beheshti, Guide to Confusion Matrices & Classification Performance Metrics. Toward Data Science, 2019.](https://towardsdatascience.com/guide-to-confusion-matrices-classification-performance-metrics-a0ebfc08408e)) 
[Anirbid Sircar, Kriti Yadav, Kamakshi Rayavarapu, Namrata Bist, Hemangi Oza, Application of machine learning and artificial intelligence in oil and gas industry. ScienceDirect, 2021.](https://www.sciencedirect.com/science/article/pii/S2096249521000429?via%3Dihub) 

---

Matrícula: 202.190.134

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

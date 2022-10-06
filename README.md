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

Quando aplicado à indústria, a Machine Learning é capaz de automatizar processos, otimizando operações e proporcionando um aumento de produtividade, qualidade e eficiência no desempenho das mais variadas funções.

Durante muitos anos essa nova vertente da tecnologia ainda passava por um processo de adaptação dentro das empresas e até um certo momento sofreu uma resistência quanto aos verdadeiros retornos com relação ao aprimoramento econômico com redução de custos operacionais e possibilidade de novos investimentos. 
Porém, assim como toda nova forma de se executar tarefas em uma corporação, essa inteligência teve que se adaptar e encontrar um ponto focal para que pudesse ser entendida e que os resultados encontrados pela IA, fosse mensurável e escalonado, foi então que houve a necessidade e criação do que é entendido como MLOps.

MLOps (uma combinação de Machine Learning e “operações de tecnologia da informação”) é uma nova disciplina / foco / prática para colaboração e comunicação entre Cientistas de Dados e profissionais de tecnologia da informação (TI), ao automatizar e produzir algoritmos de aprendizado de máquina. Por meio de práticas e ferramentas, o MLOps tem como objetivo estabelecer uma cultura e um ambiente em que as tecnologias de ML possam gerar benefícios comerciais, construindo, testando e liberando, de maneira rápida, frequente e confiável, a tecnologia de ML em produção.

#### O Machine Learning atualmente 

Já é sabido que a indústria como um todo está passando por diferentes transformações, advindas dos impactos da COVID-19 e foi nesse momento que a tecnologia mostrou sua real importância nesse momento em que já é entendido que o ML e IA nos auxiliou à realização de inúmeras tarefas cotidianas. 
O setor de pesquisa e desenvolvimento busca constantemente encontrar soluções que possam ser a aplicação direta do ML no tanto Downstream como no Upstream dessa indústria. 

De acordo com o relatório desenvolvido por Mordor Intelligence, como os custos relacionados a aquisição de sensores IoT declinou, diversas outras empresas que ainda não conseguiam adquirir estes, que são peça fundamental na comunicação e distribuição de dados entre equipamentos e interfaces de execução de IA. E então existe uma expectativa bem positiva para o setor de um aumento de cerca de 10,81% nos lucros produzidos por essa indústria entre 2021-2027, graças aos advindos proporcionados pela ML e IA.

#### Machine Learning no setor de O&G

Como sou um profissional atuante do setor de O&G decidi direcionar o objetivo do projeto na área em questão, sendo que farei uma abordagem para carácter de ampliação de conhecimento de algumas das possibilidades onde acredito que o Machine Learning especificadamente possui uma funcionalidade bastante útil no sentido de redução de custos com manutenção corretiva ou erros de projetos que até o surgimento dessa inteligência se tornavam mais custosos a medida em que não era possível fazer um estudo mais aprofundado das perspectivas de produção. 

Nesse projeto, vou demonstrar através de um modelo de Machine Learning como é possível, estruturar uma ferramenta preditiva capaz de classificar e categorizar falhas em equipamentos, preservando o ativo da empresa e reduzindo custos com manutenção não programada ou desnecessária. 
A possibilidade de demarcar exatamente onde irá ocorrer as operações de perfuração, otimizar as operações de perfuração, bem como a manutenção preditivas e detecção de falhas, são algumas das possibilidades que o Machine Learning aplicado a indústria de O&G pode nos oferecer. Abaixo apresento algumas aplicabilidades reais dos conceitos mencionados acima, bem como a fonte de pesquisa onde as soluções apresentadas podem ser encontradas. 

- Previsão para Operações de Perfuração
RSI é um recurso disponibilizado em pgs.com contendo os principais recursos tecnológicos de imagens, para auxiliar empresas a montar e atualizar a sua estrutura de pesquisa no campo de exploração e construir modelos de ML que possam prever pontos exatos de perfuração.

- Otimizando Operações de Perfuração
Outra vantagem proporcionada pela IA, é a otimização de operações de perfuração, uma vez que a partir de dados histórico de operações já realizadas, é possível aprimorar e aprender novas formas de execução e evitar erros passados. Um bom exemplo de aplicações realizadas com IA, é a redução no tempo e custos com operações de conexão em perfuração utilizando CNN para diagnósticos, tabulação de resultados na construção de interfaces gráficas para análises cognitivas. Mais detalhes dessa tecnologia foram apresentados na Offshore Conference.

- Previsão de incidente com tubulações obstruídas de poços produtores
Recentemente, dois pesquisadores, Elahifar & Hosseini, criaram um modelo de ANN chamado rede neural de otimização para enxame de partículas híbridas, ou em resumo (PSO-based ANN), uma tecnologia de IA capaz de prever através de utilização de algumas variáveis específicas, tais como: peso da lama, ponto de rendimento e viscosidade plástica por exemplo, onde o modelo prevê com uma acurácia de até 80%, quando uma tubulação relacionada as operações de perfuração pode vir a ser obstruída.
 
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
As fontes iniciais de pesquisa foram (https://towardsdatascience.com/machine-learning-part-18-boosting-algorithms-gradient-boosting-in-python-ef5ae6965be4) & (https://towardsdatascience.com/guide-to-confusion-matrices-classification-performance-metrics-a0ebfc08408e) . Essas duas referências foram utilizadas como forma de guia para elaboração de toda a estrutura inicial e de escolha dos algoritmos.
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

#### Análise Exploratória da Base de Dados

Antes de definir quais modelos de Machine Learning seriam os ideais para realizar o estudo, realizei os procedimentos básicos exploratório para entender a base como um todo, onde primeiramente fiz a contagem de quantas vezes dentro da base de dados houve a ocorrência de falhas 
Outra análise exploratória e de extrema importância é entender a correlação existente entre cada um dos atributos da base, como forma até mesmo decidir a relevância de se manter determinado atributo, da mesma forma quando verificamos se algum atributo possui dados faltantes em uma quantidade grande o que faz com que sua permanência no conjunto seja desnecessária. 

![image](https://user-images.githubusercontent.com/73768941/194211036-c9a80421-b442-4e59-a683-a05d54cab413.png)

Para criação dos modelos futuros e outros tipos de análises, desenvolvi novos Dataset, onde um deles continha apenas os dados que apresentavam as falhas e outro sem as falhas, para que eu pudesse então, através de algumas análises estatísticas descritivas, entender a forma como cada uma das variáveis se apresentam durante a ocorrência e não das falhas, como mostrado na imagem abaixo.


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

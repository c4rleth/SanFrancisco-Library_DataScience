[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
# SanFrancisco Library Analysis

O Sistema Integrado de Bibliotecas (ILS) de São Francisco é composto de registros bibliográficos, incluindo itens inventariados, registros de usuários e dados de circulação. Os dados são usados ​​na operação diária da biblioteca, incluindo circulação, catálogo público online, catalogação, aquisições, desenvolvimento de coleção, processamento e controle de periódicos. Este conjunto de dados representa o uso de itens inventariados por usuários (~ 420K registros) onde cada registro representa um usuário anônimo da biblioteca. As colunas individuais incluem estatísticas sobre o código de tipo e idade do usuário, o ano em que o usuário se registrou (somente desde 2003) e a intensidade com que o usuário tem utilizado o sistema de biblioteca (em termos de número de checkouts) desde o primeiro registro.

Os dados são fornecidos pela Biblioteca Pública SF através do Portal de Dados Abertos de São Francisco, sob o PDDL 1.0 ODC Public Domain Dedication and License (PDDL).

* Apresentação e descrição dos dados estudados.
* Limpeza dos dados, remoção dos valores sentinelas e valores duplicados.
* Usando os dados em grupos para entender nossa base de dados.
* Explorando os dados e criando graficos para visualização, como Histogramas e BoxPlots.
* Mapeando as variaveis qualitativas para dar inicio ao Machine Learning.
* Criando um classificador para descobrir os locais de maior movimento entre os usuarios.
* Testando nossa base de dados com RandomForestClassifier e DummyClassifier.
* Selecionando nossas melhores features usando SelectKBest, RFE e RFECV.
* Por fim, testando uma nova amostra no nosso algoritmo de treino. 


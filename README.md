# RESUMO

Em mamografia digital, apesar de ser considerado o método com maior sensibilidade e especificidade para o rastreamento do câncer de mama, detectar tumores em fase inicial ainda é uma tarefa difícil, dado ao fato das variações que o tecido mamário pode ter. Neste trabalho foi desenvolvida uma metodologia de padronização e planejamento de análises por radiômica em imagens mamográficas de equipamentos diferentes; esta metodologia de padronização desenvolvida apresentou resultados satisfatórios para os diferentes equipamentos utilizados, com coeficientes de variação dos valores obtidos menores que 15%.

## DESCRIÇÃO

A taxa de incidência do câncer de mama tem aumentado pelo mundo, tornando-se o tipo mais comum de câncer em mulheres. Em países desenvolvidos, ações de rastreamento da doença, de forma a detectá-la mais precocemente, tem proporcionado a diminuição na taxa de mortalidade pelo câncer de mama. Em contrapartida, países em desenvolvimen to como o Brasil, tanto a taxa de incidência como a de mortalidade têm aumentado, dado ao fato de que a maioria dos casos de câncer de mama tem o seu diagnóstico muito tardio.

O rastreamento do câncer de mama através da mamografia é uma prática considerada mundialmente como a de maior sensibilidade e especificidade. O objetivo do rastreamento por mamografia não é somente detectar a presença de câncer no tecido mamário, mas detectá-lo de forma precoce, e desta forma os tratamentos podem ser mais eficientes, diminuindo a taxa de mortalidade em decorrência da doença

A mamografia passou por várias modificações tecnológicas nos últimos anos, e esse constante aprimoramento que envolve a aquisição dessas imagens, é pelo fato do contraste entre os tecidos normal e patológico se apresentarem de formas muito semelhantes na imagem mamográfica.

Nos anos 90, os dispositivos de aquisição de imagens tiveram uma adaptação tecnológica, a radiografia digital ou DR (Digital Radiography), que consiste em um dispositivo acoplado de carga (DCC) diretamente ao equipamento de mamografia. Estes detetores podem converter o sinal recebido em imagem digital de forma indireta ou direta. 

Apesar do formato de imagem digital não alcançar a mesma resolução espacial entregue pelo formato analógico, pois nas imagens digitais a resolução espacial está diretamente associada ao tamanho do pixel, os recursos de pós-processamento disponíveis para a visualização da imagem, possibilidade de armazenamento por longo prazo, diminuir as reconvocações/repetições e desta forma a dose à qual a mama é exposta, são vantagens associadas a esta tecnologia.

Apesar da evolução pela qual a imagem mamográfica passou, sua análise requer tempo e habilidade técnica do médico, pois a interpretação de características benignas ou malignas na imagem não é simples. Com a introdução das imagens digitais, ferramentas de assistência para interpretação da imagem mamográfica foram desenvolvidas nas décadas de 90, como o CAD (Computer-Aided Diagnosis or Detection, do inglês diagnóstico ou detecção auxiliado por computador) software que a partir da análise das intensidades dos valores de pixel em regiões de interesse na imagem, apontam ao médico quais apresentam características com potencial patológico.

A busca pelo aperfeiçoamento de ferramentas como o CAD, levaram ao desenvolvimento de uma ferramenta que elevasse o nível do diagnóstico por imagem, como também a ter um papel central principalmente no diagnóstico de doenças oncológicas. Em crescente desenvolvimento há mais de uma década, Radiomics é uma ferramenta que tem o potencial de extrair dados quantitativos de imagens médicas. O termo Radiomics, onde o prefixo “radio” refere-se às modalidades radiológicas, e o sufixo “omics” que foi utilizado pela primeira vez quando foi realizado o mapeamento do genoma humano, a genômica, caracteriza a brangência do sistema como um todo, é o correspondente à análise global de um sistema biológico, identificando, quantificando e caracterizando a imagem.

Embora seja um desenvolvimento derivado dos sistemas CAD, a análise dos dados é realizada de forma independente. Os dados extraídos formam uma base de dados que auxiliam na identificação de patologias oncológicas, como por exemplo o estágio da doença ou resposta ao tratamento. A ideia central é que os dados extraídos estão diretamente relacionados com padrões genéticos e proteicos encontrados nas células, encorajando Radiomics a se tornar uma ferramenta de suporte a medicina de precisão.

Neste trabalho foi comparado o comportamento de características radiômicas após a aplicação de processamentos para a padronização de imagens médicas digitais de um simulador, que foram adquiridas em três equipamentos de mamografia diferentes, e quais dessas características que melhor representaram esse tipo de imagem. Foi verificada também a semelhança dos test object do simulador com imagens de humanos. Foram utilizados três equipamentos de mamografia digital, sendo dois com tecnologia de contador de fótons (Photon Counting) e um com tecnologia tomossíntese (Digital Breast Tomosynthesis), nomeados de PC1, PC2 e DBT, respectivamente.

Uma das etapas do desenvolvimento da metodologia foi a redução da dimensionalidade de características, o que poderá promover modelos mais eficientes de aprendizado de máquina, por gerar um menor custo computacional, quando comparado com o volume inicial de dados analisados neste trabalho. 

A estratégia sugerida que iniciou com um total de 108 características para cada test object, ao final selecionou 9 características para o test object Fibra e Microcalcificação e 10 para Massa, que poderão prosseguir como parte de analises mais robustas, que irão incluir um volume extraordinário de dados de imagens, históricos clínicos e resultados anatomopatológicos, para o desenvolvimento de soluções diagnósticas com aprendizado de máquina. Este passo finaliza a estratégia proposta neste trabalho para a padronização e desenvolvimento de análises por radiômica em imagens de mamografia digital.

Vale destacar que as características podem apresentar comportamentos diferentes, podendo uma característica melhor representar um tipo de patologia que outra, mesmo para imagens de uma mesma modalidade diagnóstica, sendo o tipo de tumor, hormônio ou a vascularização que a patologia apresenta as principais causas para essas variações de comportamento das características, pois interferem nas representações das intensidades de tons de cinza da imagem. Por esse motivo essas análises necessitam de um grande volume de imagens (dados) e de todas as informações disponíveis sobre a patologia a qual se quer criar um banco de dados  para análises por radiômica, como por exemplo: resultados do anatomopatológico, estadiamento, dentre outros.

A estratégia proposta neste trabalho apresentou resultados satisfatórios para a padronização de imagens mamográficas adquiridas em equipamentos de diferentes fabricantes, seguindo as diretrizes do IBSI.

Algumas características radiômicas calculadas com o simulador ACR apresentaram resultados dentro do limiar de valores publicados pelo IBSI. Os métodos utilizados para o cálculo e extração de características radiômicos do simulador e de imagens de humanos apresentaram valores dentro de um limiar de 15% de variação.

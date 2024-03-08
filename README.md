Este repositório contém um código Python que realiza análises de dados e gera gráficos interativos utilizando a biblioteca Plotly Express.
O código faz análises sobre um conjunto de dados de cancelamentos de serviços, identificando possíveis causas para os cancelamentos.
O processo começa com o carregamento dos dados de um arquivo CSV chamado "cancelamentos.csv".
Em seguida, o código remove informações desnecessárias do conjunto de dados, como a coluna "CustomerID", utilizando a biblioteca Pandas.
Após o pré-processamento dos dados, o código realiza análises exploratórias, criando histogramas para cada uma das variáveis do conjunto de dados.
Os histogramas são coloridos por uma variável categórica que indica se o cliente cancelou o serviço ou não.
Adicionando interatividade aos gráficos, é possível passar o mouse sobre as barras para ver informações detalhadas, como a contagem de cada grupo.
Por fim, os gráficos são salvos como arquivos HTML na pasta "charts_html", facilitando o compartilhamento e visualização em qualquer navegador da web.
Este código é útil para empresas que desejam entender melhor as causas dos cancelamentos de seus serviços e tomar medidas para reduzi-los.

# Modelo de Regressão para Marketing Digital

A análise a ser realizada refere-se a um empresa que solicitou a análise exploratória de dados de budgets de marketing digital em diferentes mídias em relação ao valor de vendas alcançado. Além disto foi requisitado um modelo preditivo de valores alcançados com os produtos dados os valores das variáveis.

A base de dados a ser utilizada está no formato ".csv" e foi fornecida pela empresa, contendo as seguintes colunas:

  - youtube: Investimento realizado na plataforma Youtube.
  - facebook: Investimento realizado na plataforma Facebook.
  - newspaper: Investimento realizado em newspaper
  - sales: Valor alcançado de vendas pelo produto.
    
Para alcançar este fim foram definidas algumas premissas:
  - Inicialmente será realizada a análise exploratória dos dados a fim de buscar inconsistência nos dados, como nulidades e tipificação dos dados.
  - No caso de serem encontradas estas inconsistências será avaliada a necessidade de realização de drop das linhas ou aplicação de valores de média ou mediana, conforme for julgado mais coerente.
  - Será adotado a priori o modelo de regressão linear para o treinamento do modelo de machine learning e devidamente documentado.
  - No final da análise será realizado o teste do modelo, a análise da aderência dos dados e por fim a predição do valor alcançado com uma campanha fixados alguns dados.
  - Para avaliar a aderência dos dados serão utilizados os parâmetros MSE e RMSE.
  - Após os testes do modelo será realizada a otimização do mesmo por meio de um otimizador de hiperparâmetros do Scikitlearn (GridSearchCV).
  - A função desta análise inicial é uma apresentação gráfica e de teste do produto, sendo somente liberada para deployment após a apresentação para a equipe técnica responsável.

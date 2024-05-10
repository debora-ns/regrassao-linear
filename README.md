Teremos uma espécie de formulário, em que preenchemos valores para cada característica de um imóvel, como área, banheiros, garagem e assim por diante. Uma vez que preenchermos os campos, teremos uma simulação do custo desse imóvel.

Estamos utilizando algumas bibliotecas para elaborar o simulador: IPython, widgets, Hbox e VBox. É criada uma caixa de texto para cada variável do simulador, em seguida há o botao, marcado pela entrada de texto Simular. Em seguida, teremos a parte de código que organiza as caixas de texto no espaço, em nosso caso, utilizamos duas colunas, cada uma com três variáveis.

Em seguida teremos uma função de que fato executa o simulador, que receberá a entrada, mas que os valores serão aqueles capturados pelos inputs de texto nos campos que criamos. Os dados serão recebidos como do tipo string e, posteriormente, transformados no tipo float. Depois desse processo, é realizado o print do resultado, de forma que o valor seja exibido na tela. É utilizado o método predict(), que recebe como parâmetro entrada. Por fim, é atribuído ao evento de clicar no botão, a chama da da função simulador.

Em outra célula, fazemos o display de todos esses elementos ao escrever display(inputs, botao).


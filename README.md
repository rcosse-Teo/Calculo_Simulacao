# Do-C-lculo-Simula-o-
Desenvolvido para o Curso sobre métodos numéricos

O código desenvolvido tem o propósito de ser a porta de entrada do autor para o uso de métodos numéricos para problemas de engenharia.
O presente trabalho é parte do trabalho final do curso do Cálculo à Simulação Computacional promovido pela empresa L2C Soluções e ministrado pelo professor Rafael Gontijo


O tópico abordado foi o de análise microestrutural de materiais compósitos, onde o modelo adotado para implememtação e análise é o Halpin-Tsai. 
Modelo semi-empírico derivado de aproximações de autoconsistência. 
O modelo de Halpin-Tsai foi escolhido por ter sido usado na minha tese de doutorado para comparação com outros modelos adotados e amplamente utilizados. 

Basicamente o código comparara os resultados de equacionamento utilizando tanto o métodos da bissecção, como o de Newton-Raphson , comparando-os.

Valores de entrada são inseridos e o modelo encontrará a quantidade de teor de reforço necessária para que se consiga alcançar o módulo de elasticidade requerido. 
Tudo isso baseado nas características dos módulos de elasticidade da matriz e da fibra. 
Lembrando que todo esse esforço é feito para determinação de caracterização de compósitos poliméricos reforçados com fibras contínuas. 

O cógigo é bem simplório, mas é um incentivo para que o autor migre do uso de software comerciais, cuja licença custa alguns milhares de dólares e o uso no setor acadêmico seja inviável. 

No final, a comparação dos métodos da bissecção e Newton-Raphson serve para se saber qual converge mais rápido para o resultado e assim exige menor poder computacional. 
Algo que é bastante almejado no mundo de previsão de propriedades mecânicas de compósitos reforçados com fibras curtas. 
Uma vez que ainda hoje softwares comarciais têm dificuldade de trabalhar com resultados mais precisos quando o teor de carga de carga curta seja disponibilizado de forma randômica. 

Os dois códigos aqui apresentados são os mesmos. Apenas aproveitei para testar as formas de transferência de informações do Collab para o GitHub.

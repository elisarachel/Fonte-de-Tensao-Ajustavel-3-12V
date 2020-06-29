
# Fonte de Tensão Ajustavel

Projeto desenvolvido para a disciplina Eletrônica para Computação (SSC0180), ministrada pelo professor Eduardo Valle Simões, do curso Ciência da Computação da USP - São Carlos  

## Objetivos
> Montar uma fonte de tensão ajustavel que receba 127V, de corrente alternada, na entrada, e que tenha na saida 3-12V, de corrente continua, fornecendo 100mA em sua voltagem maxima.


## Lista de componentes do circuito 

 Componente | Especificações     | Função | Valor    
:---------: | :-----------------:|:-----: |:----------:  
Transformador   | Entrada: 127V/220V / Saída: 12V + 12V 500mA | Modifica o potêncial elétrico fornecido.     |[R$21,90](https://www.filipeflop.com/produto/transformador-trafo-12v-12v-500ma-bivolt/?gclid=CjwKCAjwxLH3BRApEiwAqX9areP5FGhM8JJqK7Jvn082xlDDOCEa7RWokWT-8mK8e1Cb3rjjSbqzxxoCyewQAvD_BwE)
Ponte de diodos | 50-1000V/10A | Retifica uma corrente alternada para continua                                | [R$4,40](https://www.filipeflop.com/produto/modulo-ponte-h-kbu1010-retificadora/#tab-wc-simulador-parcelas) 
Capacitor       | 330µF/25V | Armazena carga elétrica num campo elétrico                                   | [R$0,89](https://www.filipeflop.com/produto/capacitor-eletrolitico-330%C2%B5f-25v-x5-unidades/)
Diodo Zener     | 13V/0,5W | Regula a tensão elétrica                                                        | [R$0,19]( https://www.filipeflop.com/produto/diodo-zener-2-a-39v/) 
Resistor        | 2.2KΩ |Diminui o consumo de energia, limitando a corrente que passa pelo Zener | [R$2,90](https://www.filipeflop.com/produto/resistor-2-2k-14w-x20-unidades/) 
Resistor        | 1KΩ | Limita a corrente elétrica que passará pelo LED                                      | [R$0,29](https://www.filipeflop.com/produto/resistor-1k%CF%89-14w-x20-unidades/)
Resistor        | 5.1KΩ | Impede que o potenciometro diminua a corrente abaixo de 3V                         | [R$0,29](https://www.filipeflop.com/produto/resistor-2-2k-14w-x20-unidades/)
Pôtenciometro   | 10K | Regula a corrente elétrica do circuito entre 12V-3V                       | [R$3,90](https://www.filipeflop.com/produto/potenciometro-linear-10k/)  
Transistor      | 40V/200mA  | Limitar a corrente elétrica                                        | [R$0,59](https://www.filipeflop.com/produto/transistor-a1015-pnp-x10-unidades/) 
LED     | 3.0-3.2V/20mA  | Muda a intensidade de seu brilho dependendo da corrente                                        | [R$0,29](https://www.filipeflop.com/produto/led-difuso-5mm-verde-x10-unidades/)
Total     |   |                                       | R$32,75



## Circuito do projeto

- ## Falstad 
![falstad](https://github.com/IgorGato/Fonte-de-Tensao-Ajustavel-3-12V/blob/master/Simulacao%20do%20circuito.png)
  A imagem acima foi obtida através da montagem do circuito no simulador falstad, e pode ser acessada atraves do link: 
  [Simulação Falstad](http://tinyurl.com/ychp2a6o)
  
  Uma explicação completa do circuito pode ser encontrada neste link no youtube.
  
- ## Eagle 

  Atraves do programa Eagle foi possivel desenhar a placa e todas as conexoes necessarias para possivel montagem da fonte, demonstrado nas imagens abaixo:
![Esquematico do Eagle](https://github.com/IgorGato/Fonte-de-Tensao-Ajustavel-3-12V/blob/master/esquematico%20eagle.jpeg)

- ## PCB
![PCB](https://github.com/IgorGato/Fonte-de-Tensao-Ajustavel-3-12V/blob/master/PCB.jpeg)


# Participantes

 - Elisa Rachel Beninca Martins. Número USP: XXXXXXX.
 - Igor Mateus Queiroz Gato. Número USP: 10261481.
 - Jonatas A Lopes. Número USP: XXXXXXX.
 - Mateus dos Santos Ribeiro. Número USP: XXXXXXX.

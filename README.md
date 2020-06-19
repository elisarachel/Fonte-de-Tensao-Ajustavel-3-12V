# Fonte de Tensao Ajustavel

Projeto desenvolvido para a disciplina Eletrônica para Computação (SSC0180), ministrada pelo professor Eduardo Valle Simões, do curso Ciência da Computação da USP - São Carlos  

## Objetivos
> Montar uma fonte de tensão ajustavel que receba 127V, de corrente alternada, na entrada, e que tenha na saida 3-12V, de corrente continua, fornecendo 100mA em sua voltagem maxima.


## Lista de componentes do circuito 

|Componente | Especificações/tipo | Função                                       | Valor |
| :---           |     :---            | :---                                         |:---   |
|Transformador (1 UN)   | Entrada: 127V/220V / Saída: 12V + 12V 500mA | Modifica o potêncial elétrico fornecido.     |R$ 21,90|
|Ponte de diodos (1 UN)| KBU1010 50-100V/10A | Retifica uma corrente alternada para continua|R$ 4,40|
|Capacitor       (1 UN)| 330µF 25V | Armazena cargas elétricas num campo elétrico |R$ 4,40 (5 UN)|
|Diodo Zener     (1 UN)| 13V 0,5W | Regula a tensão elétrica | R$ 1,90 (10 UN)|
|Resistor        (1 UN)| 2.2KΩ | Limita a corrente elétrica que passara pelo Zener, diminuindo o consumo de energia |R$ 2,90 (20 UN)|
|Resistor        (1 UN)| 1KΩ | Limita a corrente elétrica que passará pelo LED | R$ 2,90 (20 UN) |
|Resistor        (1 UN)| 5.1KΩ | Impede que o potenciometro diminua a corrente abaixo de 3V  |R$ 2,90 (20 UN)|
|Pôtenciometro   (1 UN)| 10K | Regula a corrente elétrica do circuito mantendo-a entre 12V - 3V |R$ 3,90|
|Transistor      (1 UN)| 40V/200mA  | Amplificar/Limitar a corrente elétrica |R$ 5,90 (10 UN)|

## Circuito do projeto

### Falstad 

  A imagem acima foi obtida através da montagem do circuito no simulador falstad, e pode ser acessada atraves do link:
  
  Uma explicação completa do circuito pode ser encontrada neste link. 

### Eagle 

  Atraves do programa Eagle foi possivel desenhar a placa e todas as conexoes necessarias para montagem da fonte, demonstrado nas imagens abaixo:



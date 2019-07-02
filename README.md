# FRANCELINO_Luximetro

# Conceito:
O projeto consiste em um programa que calcule a iluminosidade da luz de um ambiente, utilizando um pequeno LDR (Light Dependent Resistor) e do NI myRIO.

# Função:
Com o auxílio do Labview e do NI myRIO, o usuário poderá captar em tempo real os valores  da intensidade da luz de um certo ambiente na unidade Lux.

# Motivação:
A finalidade seria de virtualizar um equipamento chamado luxímetro, tal ferramenta está sendo cada vez mais utilizado pelos engenheiros para elaboração de projetos de iluminação, de forma personalizar a iluminação do local de acordo com a necessidade do tipo de atividade que será executada no local.
# Interface Gráfica:
Utilizando o LabView conseguimos desenvolver uma interface bem mais rápida, amistosa e intuitiva. A seguir, temos um esboço de como será visualizada pelo usuário:


![interface_04](https://user-images.githubusercontent.com/48970460/60512647-7bb04100-9cab-11e9-9404-b43cfa5cb8b3.jpg)

# Fluxograma:

![Fluxograma_LUXIMETRO](https://user-images.githubusercontent.com/48970460/60476767-2e07ea00-9c53-11e9-851c-f4a0a4b80b8c.jpeg)

# Código:

![codigo_luximetro](https://user-images.githubusercontent.com/48970460/60477984-6b6e7680-9c57-11e9-8c26-167b01e344b0.jpg)

LuximetroVI

![codigo_luximetro_myrio](https://user-images.githubusercontent.com/48970460/60478157-06675080-9c58-11e9-95a5-5f8baa847fbb.jpg)

# Circuito e funcionamento: 
![Aumentando Incidência da luz no LDR](https://user-images.githubusercontent.com/48970460/60478456-28150780-9c59-11e9-8aa9-9f9187e54dc4.jpeg)


Incidência da luz do ambiente no LDR


![Diminuindo  Incidência da luz no LDR](https://user-images.githubusercontent.com/48970460/60478474-3400c980-9c59-11e9-8561-5b322ebeec90.jpeg)


Diminuindo a incidência da luz do ambiente no LDR

# Itens utilizados no circuito: 
1) Um protoboard
2) Um LDR 10 mm 
3) Uma resistência de 3,3 kOhm
4) MyRio

# Calibração do equipamento:

De acordo com o Datasheet do LDR usado a calibragem foi feita para os seguintes parâmetros:
Mín 20 kOhm e Máx 100 kOhm - 10 lux
5kOhm - 100 lux




# Projeto Social Tecnologia E Sociedade de Irrigacao Comunitaria
Projeto social proposto na disciplina de Tecnologia e Sociedade para o curso de Bacharelado em Ciências da Computação pela instutuição Instituto Federal Catainense - Rio do Sul.

</br>

## Instruções
### Materiais
Para realização deste projeto foi utilizado um conjunto de sensores, sendo monitorados e controlados pelo Arduino, que com a combinação gerada dos dados gerados pelos sensores, ativa ou não um relé que controla o acionamento do maquinário responsável pela irrigação.

#### Sendor DHT22:
Usado para realizar a leitura da Temperatura e da Umidade do ar. É um sensor de umidade relativa e temperatura, com saída digital calibrada. Possui uma exclusiva tecnologia para medir a umidade, garantindo a confiabilidade e estabilidade. Possui internamente um microcontrolador de 8 Bits para tratar o sinal.  Possui tamanho compacto, baixo consumo, encapsulamento simples com apenas quatro terminais, podendo transmitir o sinal por até 20 metros. Todas essas características permitem utilizar esse sensor nas mais diversas aplicações.
##### Parâmetros Técnicos:
* 1 Tensão de Alimentação: +5V;
* 2 Range de temperatura: 0 a 50ºC com erro de +/- 2ºC;
* 3 Range de umidade: 20 a 90% RH com erro de +/- 5%;
* 4 Interface Digital.

#### Sensor Moisture Sample:
Usado para realizar a leitura  da Umidade do solo. Este sensor de pode ler a quantidade de umidade presente no solo ao seu redor. Este sensor utiliza as duas sondas para passar corrente através do solo, e, em seguida, a resistência faz uma leitura para obter o nível de umidade. O fator principal é a água, pois conduz eletricidade mais facilmente ( menor resistência), e sem água e com o solo seco a condutividade de energia é menor ( maior resistência).
##### Parâmetros Técnicos:
* 1 Tensão de Alimentação: 3,3V ou 5V;
* 2 Tensão do sinal de saída: 0 a 4,2V;
* 3 Corrente: 35mA.

#### Relay
Tem a capacidade de controlar diferentes tensões e potências sem o risco de danificar o micros-controlador.

#### Arduino Uno R3
É uma placa de microcontrolador, ele tem 14 pinos de entrada/saída digital (dos quais 6 podem ser usados como saídas PWM), 6 entradas analógicas, um cristal oscilador de 16MHz, uma conexão USB, uma entrada de alimentação uma conexão ICSP e um botão de reset.

### Como implementar cada um desses sensores

#### Implementação Sensor DHT-22

##### Cuidando da Biblioteca:
A biblioteca é formada por dois arquivos, um é o DHT11.h e outro é o DHT11.cpp, para baixá-los basta fazer o download do arquivo DHT22.zip a partir do seguinte link: http://www.seucurso.com.br/downloads/DHT22.zip.
Para o Windows basta criar uma pasta DHT22 dentro da pasta Libraries que está no local de instalação da IDE Arduino e colar os arquivos descompactados dentro dessa pasta criada.
</br>
Para o MAC OS, segure a tecla CONTROL e clique sobre o ícone da IDE Arduino, em seguida clique na opção Mostrar Conteúdo do Pacote. Encontre a pasta chamada libraries, ali crie uma pasta chamada DHT22 e cole os arquivos descompactados.

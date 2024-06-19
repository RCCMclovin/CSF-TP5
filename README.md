# CSF-TP5

Este trabalho utiliza os mesmos códigos para comunicação LoRa utilizados nas aulas anteriores.

### Medição do Ganho de uma Antena

Para este trabalho é necessário a presença de uma antena de ganho desconhecido, essa antena deverá ser conectada ao transmissor. O receptor deverá ser instalado a uma distância conhecida do transmissor (exemplo: 3 metros). Conhecendo a potência do transmissor, a perda no caminho (Path Loss) e o RSSI no receptor, calculem o ganho da antena desconhecida.

## Cantenna

![Cantenna](/imgs/OIP.jpeg)

Cantenna (junção das palavras em inglês "can" e "antenna") é uma antena composta por uma antena e uma lata, a qual age refletindo e direcionando o sinal emitido pela antena.

### Medição do ganho de uma cantenna

Foram contruidas duas cantennas para serem analizadas. Usando o mesmo processo de medição, calculem o ganho dessas cantennas e, em seguida, analizem o efeito da direção da cantenna e do posicionamento da antena dentro da lata na transmissão, comparem as 3 antenas testadas com a antena que campanha o ESP32 da Heltec.
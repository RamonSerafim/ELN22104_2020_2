# Atividade 3
Aluno: 
* Guilherme da Costa Franco

## Simulação de circuitos com Amplificadores operacionais AD8040 e AD8539.

### 1.Verifique no datasheet dos Ampops indicados os valores:

- Máxima e mínima tensão de alimentação
- Tensão de modo comum
- CMRR
- Máxima e mínima tensão de entrada
- Tensão de offset
- Corrente de polarização
- Consumo de corrente
- Ganho em malha aberta
- Impedância de entrada

### 1.1.Para o AD8040

- Máxima e mínima tensão de alimentação 

![image](https://user-images.githubusercontent.com/61738767/116282433-220ee580-a761-11eb-92b7-9028e2878fa0.png)

- Tensão de modo comum

![image](https://user-images.githubusercontent.com/61738767/116312985-8b9feb80-a783-11eb-8883-029833bd2314.png)

- CMRR

![image](https://user-images.githubusercontent.com/61738767/116313224-de79a300-a783-11eb-89e8-04b3d986198a.png)

- Máxima e mínima tensão de entrada

![image](https://user-images.githubusercontent.com/61738767/116313661-6790da00-a784-11eb-8ff1-f0f7aec19639.png)

- Tensão de offset

![image](https://user-images.githubusercontent.com/61738767/116313738-85f6d580-a784-11eb-8fa9-6ed26a5daf86.png)

- Corrente de polarização

![image](https://user-images.githubusercontent.com/61738767/116313824-a7f05800-a784-11eb-8cfe-82c8aa166e5f.png)

- Consumo de corrente

![image](https://user-images.githubusercontent.com/61738767/116313942-d2daac00-a784-11eb-851b-4c9a10e60f6d.png)

- Ganho em malha aberta

![image](https://user-images.githubusercontent.com/61738767/116314186-28af5400-a785-11eb-9903-b710742e47e2.png)

- Impedância de entrada

![image](https://user-images.githubusercontent.com/61738767/116314299-4da3c700-a785-11eb-86ae-f813eca99149.png)


*Referência:*https://www.analog.com/media/en/technical-documentation/data-sheets/AD8029_8030_8040.pdf

### 1.2.Para o AD8539

- Máxima e mínima tensão de alimentação

![image](https://user-images.githubusercontent.com/61738767/116314806-f8b48080-a785-11eb-8175-c0ee7ee0e845.png)


- Tensão de modo comum

![image](https://user-images.githubusercontent.com/61738767/116315000-43ce9380-a786-11eb-95f9-8f5d4f218ba7.png)

![image](https://user-images.githubusercontent.com/61738767/116315043-58ab2700-a786-11eb-9687-58837c5b382f.png)


- CMRR

![image](https://user-images.githubusercontent.com/61738767/116315221-9ad46880-a786-11eb-96b1-3070e61d7411.png)

![image](https://user-images.githubusercontent.com/61738767/116315290-b2abec80-a786-11eb-8f3b-cce41d2ce8f6.png)


- Máxima e mínima tensão de entrada

![image](https://user-images.githubusercontent.com/61738767/116315364-cbb49d80-a786-11eb-8bed-0c578a9b219d.png)


- Tensão de offset

![image](https://user-images.githubusercontent.com/61738767/116314837-0538d900-a786-11eb-91cb-77b296474539.png)


- Corrente de polarização

![image](https://user-images.githubusercontent.com/61738767/116315424-e1c25e00-a786-11eb-93cf-b8077b110690.png)


- Consumo de corrente

![image](https://user-images.githubusercontent.com/61738767/116315447-ea1a9900-a786-11eb-8eb3-0d4da153e2e5.png)


- Ganho em malha aberta

![image](https://user-images.githubusercontent.com/61738767/116315725-4c739980-a787-11eb-82c3-43273a931bad.png)


- Impedância de entrada


*Referência:*https://www.analog.com/media/en/technical-documentation/data-sheets/AD8538_8539.pdf

---

### 2.Simule um circuito seguidor de tensão com cada um dos ampops indicados e verifique os efeitos decorrentes da máxima e mínima tensão de entrada.

- Para o AD8040

![image](https://user-images.githubusercontent.com/61738767/116319004-20a6e280-a78c-11eb-84f2-2291c6efde84.png)

- Para o AD8539

![image](https://user-images.githubusercontent.com/61738767/116319351-c1959d80-a78c-11eb-9f6b-b6e7a602fa91.png)

*Considerações:* De acordo com os gráficos, o AD8040 saturou com ±5V e o AD8539 com ±2,5V.

---

### 3.Simule um circuito amplificador inversor com cada um dos ampops indicados e calcule os resistores para ter um ganho igual -100V/V.

- Para o AD8040

![image](https://user-images.githubusercontent.com/61738767/116321463-7e3d2e00-a790-11eb-8022-f2e209858f48.png)

- Para o AD8539

![image](https://user-images.githubusercontent.com/61738767/116320570-d96e2100-a78e-11eb-9df8-7cadfa8eb2a9.png)

- Para o AD8040 com 1kHz na entrada.

![image](https://user-images.githubusercontent.com/61738767/116321632-ce1bf500-a790-11eb-9a36-d9a03af1bab9.png)

- Para o AD8539 com 1kHz na entrada.

![image](https://user-images.githubusercontent.com/61738767/116320825-56999600-a78f-11eb-94ea-80716a789bce.png)


---

### 4.Simule um circuito amplificador não inversor com cada um dos ampops indicados e calcule os resistores para ter um ganho igual 10V/V.

- Aplicando 0 na entrada do AD8040

![image](https://user-images.githubusercontent.com/61738767/116322639-ce1cf480-a792-11eb-9329-01cf8c7fe47e.png)

- Aplicando 0 na entrada do AD8539

![image](https://user-images.githubusercontent.com/61738767/116324199-10940080-a796-11eb-9f7b-5506fa03278d.png)

- Aplicando um sinal continuo de 5mV, 50mV, 200mV e 500mV na entrada do AD8040.

![image](https://user-images.githubusercontent.com/61738767/116324083-cc086500-a795-11eb-8bd8-600a193d9112.png)

- Aplicando um sinal continuo de 5mV, 50mV, 200mV e 500mV na entrada do AD8539.

![image](https://user-images.githubusercontent.com/61738767/116324431-85ffd100-a796-11eb-8e4f-b3f431adb2e6.png)

*Considerações:* Devido as tensões de offset serem admitidas na simulação, percebeu-se que houve um aumento no erro percentual do AD8040 conforme diminuia-se a tensão de entrada (denotando que este amplificador não é recomendado para sinais de baixa tensão). Em contra partida, à medida que aumentava-se a tensão de entrada no AD8539, percebeu-se um aumento no erro percentual, principalmente devido à saturação do componente ser ±2,5V.

---

- Caso deseja-se projetar um amplificador subtrator com ganho de 100V/V, para sinais muito pequenos com variação de +/-10uV até +/-30mV de muito baixa frequência, qual desses ampops você utilizaria? Justifique a sua resposta.

*Resposta:* Como citado anteriormente, o AD8539 possui um desempenho melhor com sinais de entrada de baixa tensão que o AD8040. Portanto, o AD8539 seria a melhor opção.


- Escolha um terceiro ampop com características melhores que os ampops acima para uma aplicação
como subtrator.


## Código produzido e utilizado:

```
/* Configuração dos pinos */
void setup (){
pinMode(7, OUTPUT);
pinMode(8, OUTPUT);
pinMode(9, OUTPUT);
}

/* Loop principal com as luzes do semáforo */
void loop (){
digitalWrite(7, HIGH);
delay(6000);
digitalWrite(7, LOW);
digitalWrite(8, HIGH);
delay(4000);
digitalWrite(8, LOW);
digitalWrite(9, HIGH);
delay(2000);
digitalWrite(9, LOW);
```

## Tabela de componentes:

| Componentes | Especificações |
|--------------|----------------|
| 7 Jumpers    | Vermelho, Preto, Branco, Verde, Azul e Marrom |
| 1 Arduino    | UNO, 5V |
| 3 Resistores | 10 KΩ (Marrom, Preto, Laranja, Dourado) |
| 3 LEDs       | 2V |


## Tutorial em fotos:

![IMG_7375](https://github.com/user-attachments/assets/7f5c4114-e752-4503-93b2-ab1871ad1b70)

<br/>
Primeiramente realizei a ligação aos pinos ground e 5V do Arduino ONE com o jumper preto e vermelho respectivamente, trazendo a corrente para a protoboard e respeitando a divisão de cores. Posteriormente, trouxe as mesmas correntes para outra seção da protoboard a fim de criar um espaço separado para a construção da atividade, com um jumper vermelho (+) e branco (-).
<br/>
<br/>
<br/>

<img width="1020" height="517" alt="Screenshot 2025-10-28 09 14 42" src="https://github.com/user-attachments/assets/4fa9626d-b421-4042-892d-0d2cedaea5f4" />
<img width="1020" height="517" alt="Screenshot 2025-10-28 09 19 33" src="https://github.com/user-attachments/assets/100c11ac-3299-423f-98e5-b42197765b9e" />

<br/>
<br/>
<br/>
Entre os dois jumpers que traziam a corrente, posicionei primeiramente os jumpers ligados aos pinos 7, 8 e 9, que possibilitariam a temporização adequada conforme código dos leds vermelho, verde e amarelo, de forma a cada um estar conectado à uma "linha" para uma organização maior. Após isso, garanti que houvesse 1 resistor para cada linha, para proteção dos leds, com os últimos sendo posicionados entre cada "conjunto" (jumper de pino e resistor).
<br/>
<br/>


## Vídeo de demonstração:

https://drive.google.com/file/d/1qXG8YjNb3jRoF1ajZna2lPTUk8771uZG/view?usp=sharing 


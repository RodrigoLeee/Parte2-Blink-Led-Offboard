# Parte 2 Blink Led Offboard Arduino
Este repositório contém um projeto que simula um circuito e código no TinkerCAD para controlar dois LEDs externos (offboard) conectados a um Arduino. O circuito faz com que os LEDs pisquem a cada 500 milissegundos (0,5 segundo). Um dos LEDs possui um botão que permite ativar ou desativar o seu piscar, oferecendo controle manual sobre o funcionamento do LED. Este exemplo é ideal para aprender sobre o uso de botões e controle de múltiplos LEDs com o Arduino, explorando conceitos básicos de eletrônica e programação.

### Arduino no TinkerCad
Arduino e circuito montado no TinkerCAD. O circuito é composto pelo arduino, dois leds, dois resistores, um botão, e cabos jumper.
<div align="center">
    <img src="assets/ledoffboard1.png" alt="Imagem do Arduino 1" width="1000"/>
    <br>
    <sup>Imagem do Arduino 1 - Fonte: TinkerCAD</sup>
</div>

<div align="center">
    <img src="assets/ledoffboard2.jpg" alt="Imagem do Arduino 2" width="1000"/>
    <br>
    <sup>Imagem do Arduino 2 - Fonte: TinkerCAD</sup>
</div>

<div align="center">
    <img src="assets/ledoffboard3.jpg" alt="Imagem do Arduino 3" width="1000"/>
    <br>
    <sup>Imagem do Arduino 2 - Fonte: TinkerCAD</sup>
</div>

### Imagem do Código
Aqui está o código no TinkerCAD:
<div align="center">
    <img src="assets/codigo.jpg" alt="Imagem do Código" width="1000"/>
    <br>
    <sup>Imagem do Código - Fonte: TinkerCAD</sup>
</div>

### Código
Aqui está o código:
``` C
// C++ code
//
void setup()
{
  pinMode(10, OUTPUT);
}

void loop()
{
  digitalWrite(10, HIGH);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(500); // Wait for 1000 millisecond(s)
}
```

### Protótipo Um LED


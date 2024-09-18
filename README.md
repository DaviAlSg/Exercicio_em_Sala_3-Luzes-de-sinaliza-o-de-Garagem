# Exercicio_em_Sala_3-Luzes-de-sinaliza-o-de-Garagem
-
-
# Arduino feito no Tinkercard
![Editing Components (2)](https://github.com/user-attachments/assets/b25494d1-c90b-43ad-99ef-c5226afdf348)
-
-
# Materiais
-
Arduino Uno
3 LEDs
3 resistores de 220Ω
Fios de conexão
Protoboard
-
# Código

const int ledPin1 = 4;
const int ledPin2 = 5;
const int ledPin3 = 6;

void setup() {
pinMode(ledPin1, OUTPUT);
pinMode(ledPin2, OUTPUT);
pinMode(ledPin3, OUTPUT);
}

void loop() {
digitalWrite(ledPin1, HIGH);
delay(1000);
digitalWrite(ledPin1, LOW);

digitalWrite(ledPin2, HIGH);
delay(1000);
digitalWrite(ledPin2, LOW);

digitalWrite(ledPin3, HIGH);
delay(1000);
digitalWrite(ledPin3, LOW);
}

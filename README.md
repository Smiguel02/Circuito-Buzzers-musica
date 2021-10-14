# Circuito-Buzzers-musica
Circuito criado para banca do RAS, e testar Buzzers

void setup() {
  // put your setup code here, to run once:
  
pinMode(D0, OUTPUT);
pinMode(D1, OUTPUT);
pinMode(D2, OUTPUT);


}

void loop() {
  // put your main code here, to run repeatedly:
  // 261.63 329.63  392
  tone(D0, 261.63);
  tone(D1, 329.63);
  tone(D2, 392);
  delay(2000);
  noTone(D0);
  noTone(D1);
  noTone(D2);
  delay(10000);
  
  /*
  digitalWrite(D0, HIGH);
  delay(2000);
  digitalWrite(D0,LOW);
  delay(10);
  */
  
  /*
  digitalWrite(D5, HIGH);
  delay(2000);
  digitalWrite(D5,LOW);
  delay(10);

  digitalWrite(D6, HIGH);
  delay(2000);
  digitalWrite(D6,LOW);
  delay(10);
  
  */
}

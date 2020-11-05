# Aruino-Leds-potenciometro
int sensorValue = 0;

void setup() {
  pinMode(1, OUTPUT);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop() {
  digitalWrite(1, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(1, LOW);
  delay(15);
  
  digitalWrite(2, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(2, LOW);
  delay(15);
  
  digitalWrite(3, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(3, LOW);
  delay(15);
  
  digitalWrite(4, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(4, LOW);
  delay(15);
  
  digitalWrite(5, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(5, LOW);
  delay(15);
  
  digitalWrite(6, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(6, LOW);
  delay(15);
  
  digitalWrite(7, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(7, LOW);
  delay(15);
  
  digitalWrite(8, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(8, LOW);
  delay(15);

  digitalWrite(9, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(9, LOW);
  delay(15);

  digitalWrite(10, HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 25);
  digitalWrite(10, LOW);
  delay(15);
}

int roul_num = 0;
int speedrate = 0;
int roul_delay = 100;
int roul_random = random(5000,15000);
boolean val;

void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(2, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  val = analogRead(A0);
    if(val == false) {
      for (int roul_num = 0; roul_num <= 36; roul_num ++) {
        switch (roul_num) {
        case 1:
          digitalWrite(13, HIGH);
          break;
        case 2:
          digitalWrite(13, LOW);
          digitalWrite(12, HIGH);
          break;
        case 3:
          digitalWrite(11, HIGH);
          digitalWrite(12, LOW);
          break;
        case 4:
          digitalWrite(10, HIGH);
          digitalWrite(11, LOW);
          break;
        case 5:
          digitalWrite(9, HIGH);
          digitalWrite(10, LOW);
          break;
        case 6:
          digitalWrite(8, HIGH);
          digitalWrite(9, LOW);
          break;
        case 7:
          digitalWrite(8, LOW);
          break;
        case 8:
          digitalWrite(6, HIGH);
          break;
        case 9:
          digitalWrite(5, HIGH);
          digitalWrite(6, LOW);
          break;
        case 10:
          digitalWrite(4, HIGH);
          digitalWrite(5, LOW);
          break;
        case 11:
          digitalWrite(3, HIGH);
          digitalWrite(4, LOW);
          break;
        case 12:
          digitalWrite(2, HIGH);
          digitalWrite(3, LOW);
          break;
        case 13:
          digitalWrite(2, LOW);
          break;
        case 14:
          digitalWrite(12, HIGH);
          break;
        case 15:
          digitalWrite(11, HIGH);
          digitalWrite(12, LOW);
          break;
        case 16:
          digitalWrite(10, HIGH);
          digitalWrite(11, LOW);
          break;
        case 17:
          digitalWrite(9, HIGH);
          digitalWrite(10, LOW);
          break;
        case 18:
          digitalWrite(8, HIGH);
          digitalWrite(9, LOW);
          break;
        case 19:
          digitalWrite(8, LOW);
          break;
        case 20:
          digitalWrite(6, HIGH);
          break;
        case 21:
          digitalWrite(5, HIGH);
          digitalWrite(6, LOW);
          break;
        case 22:
          digitalWrite(4, HIGH);
          digitalWrite(5, LOW);
          break;
        case 23:
          digitalWrite(3, HIGH);
          digitalWrite(4, LOW);
          break;
        case 24:
          digitalWrite(2, HIGH);
          digitalWrite(3, LOW);
          break;
         case 25:
          digitalWrite(2, LOW);
          digitalWrite(13, HIGH);
          break;
         case 26:
           digitalWrite(13, LOW);
           digitalWrite(12, HIGH);
           break;
         case 27:
           digitalWrite(11, HIGH);
           digitalWrite(12, LOW);
           break;
         case 28:
           digitalWrite(10, HIGH);
           digitalWrite(11, LOW);
           break;
         case 29:
           digitalWrite(9, HIGH);
           digitalWrite(10, LOW);
           break;
         case 30:
           digitalWrite(8, HIGH);
           digitalWrite(9, LOW);
           break;
         case 31:
           digitalWrite(8, LOW);
           digitalWrite(7, HIGH);
           break;
         case 32:
           digitalWrite(6, HIGH);
           digitalWrite(7, LOW);
           break;
         case 33:
           digitalWrite(5, HIGH);
           digitalWrite(6, LOW);
           break;
         case 34:
           digitalWrite(4, HIGH);
           digitalWrite(5, LOW);
           break;
         case 35:
           digitalWrite(3, HIGH);
           digitalWrite(4, LOW);
           break;
         case 36:
           digitalWrite(2, HIGH);
           digitalWrite(3, LOW);
           break;
    }
    Serial.print("val = ");
    Serial.println(val);
    delay(10);
  }
  } else {
    int ran = random(2,13);

    
    Serial.print("val = ");
    Serial.print(val);
    Serial.print(",  ");
    Serial.print("ran = ");
    Serial.println(ran);
    
    for (int i=2; i<=13; i++) {
      digitalWrite(i,LOW);
    }    
    digitalWrite(ran, HIGH);
    delay(3000);
  }
}

//this is my first iot program

#define my_led 7

void setup() {

// put your setup code here, to run once:

pinMode (my led, OUTPUT);
}
void loop() {

// put your main code here, to run repeatedly:

digitalWrite(my_led, HIGH);
delay(1000);
digitalWrite(my_led, LOW);
delay(1000);
}
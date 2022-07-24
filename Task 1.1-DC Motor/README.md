# Arduino UNO- DC Motor (Set Up)
DC motors usually have only two leads, one positive and one negative. If you connect these two leads directly to a battery, the battery will provide power to the motor. If you swap the leads, the motor will rotate in the opposite direction. Here is a DC Motor running on the clock wise controlled by Arduino. 

## •	Here is the simulator link used in this project:

TinkerCad : tinkercad.com/circuits 

## •	Components List:
1.	Arduino Uno R3
2.	 DC Motor 
3.	9V Battery 
4.	H-bridge Motor Driver

## •	The code: 
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  
}

void loop()
{
  digitalWrite(13, HIGH);
  
  digitalWrite(12, LOW);
  
}

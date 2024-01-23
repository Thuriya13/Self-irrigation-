int water; //random variable
void setup ()
pinMode (3,0UTEUT) ; /loutput pin tor relay board, this will sent signal to the relay
pirMode (6, ZNPUT) ; /input pin ccming tron soil sensor
void loop ()
water
digitalRead (6) ; H resding the coming siqnal £rom the soil senso
iL (watez IGH) // if water level is full then cut the relay
digitalWrite (3, LOW) // low is to cut the relay
else
digitalWrite (3, IGI) : //high to continue proving signal and water supply
delay (400)



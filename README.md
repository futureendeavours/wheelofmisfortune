# wheelofmisfortune
Halloween Spin Wheel and Fog Machine Activator

This code was made for an Arduino Uno board and runs several main components:

1- A button pusher servo on a timer that activates a fog machine via remote button push. This quite literally is a servo glued to a remote control that every few minutes is activated and pushes the fog button. 
2- A continuous motion servo that is triggered by a sonic distance sensor. If someone puts their hand close to the sonic distance sensor, the wheel starts to spin until the hand is removed. The wheel will continue to spin for a few thousand ms after hand removal to make it seem more authentic. 

I saw quite a few questions online asking about each one of these functions individually. Hopefully someone finds this combined code useful in the future. 

-end-

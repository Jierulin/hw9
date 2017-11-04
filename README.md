# hw9
Why can you only use certain pins for analogWrite()?
  The frequency of the PWM signal on most pins is approximately 980 Hz. On the Uno boards, certain pins have different frequencies. In or der the analogWrite to work, it need to be connected to pins with similar frequences.
  

What is the range the map() function maps the value to? Why this range?
 A value of fromLow would get mapped to toLow, a value of fromHigh to toHigh
 Because the range need to be eaily controlled.

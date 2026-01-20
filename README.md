# RPi5-cooling-fan-control
Program works to cool my RPi5 with a 12v fan from an old Dell Desktop and it keeps my cpu below 35 C. I tried a proportional pwm based control on actual cpu
temperature but I did not like the up-down-up gradual canges, as it was distracting. So the speed is fixed until I 
choose to nano the manual speed setpoint.

<img width="640" height="712" alt="screenshot-2026-01-19-222848" src="https://github.com/user-attachments/assets/604ddb14-cff7-4248-ac12-3802047ba4b3" />

Note that Q1 is NPN small half-round signal transistor and Q2 is power transistor in metal tab config.    
Make sure you wire according to 1-2-3 = E-B-C on Q1 and 1-2-3 = B-C-E on Q2.

<img width="692" height="752" alt="screenshot-2026-01-19-223334" src="https://github.com/user-attachments/assets/f5af99f0-9a40-4976-83ac-8f5c9e933fd4" />

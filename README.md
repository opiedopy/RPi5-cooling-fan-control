# RPi5-cooling-fan-control
Program works to cool my RPi5 with a 12v fan from an old Dell Desktop and it keeps my cpu below 35 C. I tried a proportional pwm based control on actual cpu
temperature but I did not like the up-down-up gradual canges, as it was distracting. So the speed is fixed until I 
choose to nano the manual speed setpoint.

<img width="640" height="712" alt="screenshot-2026-01-19-222848" src="https://github.com/user-attachments/assets/8f68d896-755f-44ce-8f26-ee82e9006591" />

Note that Q1 is NPN small half-round signal transistor and Q2 is power transistor in metal tab config.    
Make sure you wire according to 1-2-3 = E-B-C on Q1 and 1-2-3 = B-C-E on Q2.



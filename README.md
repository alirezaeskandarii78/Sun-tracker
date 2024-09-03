# Sun-tracker
Sun Tracker + Solar Power Controller
this project contains 2 parts:
1: power control: this part controls battery charge and it works by estimating battery voltage + PV panel voltage and current. 
2: Sun tracker: 4 LDR sensors track the sun in the sky. 2 of them estimate the difference of light rays of the up and down part of the PV pannel and 2 estimates the light difference between the left and right parts. then the controller controls the angle of the panel toward the sun by 2 Servo-Motors -one in X, Y direction and one in Z direction-

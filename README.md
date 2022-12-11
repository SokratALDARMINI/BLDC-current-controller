# BLDC-current-controller
Current controller for a brushless DC motor using stm32f103c8t6
This project is meant to control BLDC motor of 350 W for a one wheel hoverboard using stm32f103c8t6 microcontroller. (see the hoverboard on youtube: https://www.youtube.com/watch?v=aa2UyJ1Kv6I
Implemenation with square wave currents: https://www.youtube.com/watch?v=D2rlX_WaPG8)

The project is done using the following components:
BTS 7960B High Current PN Half Bridge.
High Current PN Half Bridge. current sensor.

For current measurements, PA0, PA1, and  PA3 are used for the ADC.

For duty cycles for BTS 7860B elements, PB6, PB7, and PB8 are used.

For the hall sensors, PA8, PA9, PA10 are used.

To control the elements BTS 7860B for active mode, we used PB12, PB13, PB14.

This images shows the used microcontroller pins:
![image](https://user-images.githubusercontent.com/95107709/169672517-1aa80608-4244-402c-88bc-267f4cacccb8.png)

This photo shows the printed circuit for the controller:
![Capture](https://user-images.githubusercontent.com/95107709/169694170-3456d7fe-5029-4934-9448-173ea539337d.PNG)


This photo shows motor currents using the controller:
![20190730_223754](https://user-images.githubusercontent.com/95107709/169693395-5a980641-7b3d-426f-a092-c84afcddad1f.jpg)

The hoverboard:
![20190825_052734](https://user-images.githubusercontent.com/95107709/169694254-9d1e384e-2b48-4345-985c-15144d2dc49a.jpg)

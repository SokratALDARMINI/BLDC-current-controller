# BLDC-current-controller
Current controller for a brushless DC motor using stm32f103c8t6
This project is meant to control BLDC motor of 350 W for a one wheel hoverboard using stm32f103c8t6 microcontroller.

The project is done using the following components:
BTS 7960B High Current PN Half Bridge.
High Current PN Half Bridge. current sensor.

For current measurements, PA0, PA1, and  PA3 are used for the ADC.

For duty cycles for BTS 7860B elements, PB6, PB7, and PB8 are used.

For the hall sensors, PA8, PA9, PA10 are used.

To control the elements BTS 7860B for active mode, we used PB12, PB13, PB14.

![image](https://user-images.githubusercontent.com/95107709/169672517-1aa80608-4244-402c-88bc-267f4cacccb8.png)

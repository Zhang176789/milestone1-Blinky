MKEL 1123: BLINKY APP
Prepared by: Group 2
Hu Yanbing
Peng Yilin
Zhang Yanpeng


1.The code is based on the STM32 microcontroller series and the HAL library, and it configures system clocks, initializes GPIO and UART interfaces, and controls a GPIO pin to flash an LED in the main loop. 
2.Use STM32CubeIDE studio and create a new project. Choose the board ‘NUCLEO-F446RE’. 

3.Name the project: ‘Blinky’.

4.Generate setup code for the selected board.
5.The code mainly includes the following parts.
a.Including Header Files and Defining Global Variables.
b.Function Declarations.
c.Main Function.
d.System Clock Configuration (SystemClock_Config).
e.GPIO Initialization (MX_GPIO_Init).
f.USART2 UART Initialization (MX_USART2_UART_Init).
g.Error Handling (Error_Handler).
6.For LED blinking, using a while loop and set the LED to turn on for 600 milliseconds and off for 1000 milliseconds.

7.DEMO video link on YouTube: https://youtu.be/FlFFnVAFnRU?si=BJgSToomIFqOPglz.

NOTE: for the figures view the set up instructions word document.

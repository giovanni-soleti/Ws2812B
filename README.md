# Ws2812B LED STRIP CONTROL
In this repository there is the code developed to control an RGB Led Strip with STM32F446-RE. That code could be used in every Nucleo Board with a TIMER and DMA :) 
Led Strip color can be modified changing the input of get_color, a new color also can be declared as a uint8_t vector of 3 elements:
the first one control the RED component, the second one the GREEN component and the third one control the BLUE component.
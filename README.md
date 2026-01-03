# STM32-ADC-DMA-UART
TIM2 generates a 100 Hz update event (TRGO).
ADC1 is externally triggered by TIM2 TRGO.
DMA in circular mode transfers ADC data to memory.
ADC values are transmitted via USART2 at 115200 baud.
Project configured using STM32CubeMX.
Application code written in USER CODE sections.

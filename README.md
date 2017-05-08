# FPS_GT511C3_DUE_MEGA
FPS_GT511C3 Library of Biometric Shield for Arduino adapted to Arduino DUE and Arduino Mega.

The original FPS_GT511C3 lib was developed for Arduino Uno, it originally uses "SoftwareSerial.h" which is an emulation of an USART due Arduino Uno has only one on chip USART which is necessary for USB communication with programming IDE.

In case o Arduino DUE and MEGA, there are more than one on chip USART, so, it is not necessary any emulation. The emulation provided by "SoftwareSerial.h" lib is also limited to low clock frequencies (max 20 MHz) which is not compatible with DUE or MEGA that use to be faster.

By
Daniel Trevisan Tatsch
Cleber Jorge Amaral

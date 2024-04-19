This is a basic task scheduler. I like to call it a primitive version of an OS.
 It switches between tasks turning on different LEDs  with some programmable delay
  on the STM32 Discovery board. It makes use of context switching using inline assembly
 language code. It makes use of interrupt handlers like Systick Handler and the PendSV
  to perform the context switching.

# Reliable-Wireless-Communication-Based-on-LISA

This project is about creating reliable wireless communication based on Linear Invariant Synchronisation Algorithm (LISA), data scrambling and
LBC. LISA is used to extract sync field which helps in extracting start bit for payload. Scrambling is used to improve clock recovery and data reception capabilities by removing long sequences of zeros and ones. Error detection is done by LBC block. Two nodes which are based on LPC1769 are able to successfully communicate on noisy channel based on LISA, data scrambling and LBC block.

# Introduction
This project mains at establishing reliable wireless communication which should work even for slightly noisy wireless channel. Implementation is based on LPC1769 which is an ARM Cortex-M3 based microcontroller. LPC1769 operates at 120Mhz which gives sufficient speed for data processing.
Heart of reliable communication is based on LISA. It helps in extracting payload depending upon timing information retrieved from sync field. For maintaining signal integrity use scrambling/descrambling. For error detection and correction, LBC is used.

Please refer attached document for more information.

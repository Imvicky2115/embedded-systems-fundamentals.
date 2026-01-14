# embedded-systems-fundamentals.
Notes and concepts on embedded systems: MCU boot flow, memory, interrupts, timers, PWM, ADC, drivers, and communication protocols.

Initial commit: Embedded systems fundamentals overview
---

## MCU Boot Process
- Power is applied to MCU
- Reset occurs
- MCU reads reset vector from Flash
- Startup code initializes stack and memory
- main() function is called

---

## Flash vs RAM
- Flash stores firmware and constants
- RAM stores variables, stack, buffers
- Code executes from Flash
- MCU uses RAM as working memory

---

## Interrupts
- Interrupts are hardware events
- MCU pauses current execution
- Jumps to ISR using vector table
- ISR handles the event quickly

---

## Timers
- Timers are hardware counters
- Used for time measurement
- Generate interrupts
- Used for PWM and scheduling

---

## PWM
- MCU pins are digital
- PWM simulates analog control
- Generated using timers
- Used for motor speed, LED brightness

---

## ADC
- Converts analog voltage to digital value
- Implemented in hardware
- Software configures and reads ADC



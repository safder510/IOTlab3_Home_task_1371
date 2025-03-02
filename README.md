# IOTlab3_Home_task_1371


TASK 3

What is a Debounce Issue and Why Do We Need to Get Rid of It?
A debounce issue occurs when a mechanical switch or button is pressed, generating multiple unintended signals due to mechanical bouncing. Since switch contacts do not close instantly but oscillate before stabilizing, this can cause false multiple detections instead of a single input. Debouncing is necessary to ensure accurate input detection, prevent errors, and improve system reliability, especially in embedded systems and digital devices.

Where Can Debounce Issues Be Critical?
Debounce problems can be critical in keyboards, embedded systems, industrial automation, medical devices, and gaming consoles, where precise input detection is necessary. In medical equipment, incorrect input readings can be life-threatening, while in industrial automation, unintended signals can cause operational hazards. In gaming and user interfaces, debounce issues lead to poor user experience due to unintended multiple actions.

 Why Does Debounce Occur? Is It a Compiler Error, Logical Error, or a Cheap Microcontroller?
Debounce occurs due to the mechanical nature of switches, not because of a compiler error or a cheap microcontroller. The compiler only translates code, and even expensive microcontrollers need debounce handling. It is purely a logical issue caused by physical switch vibrations. Debounce can be resolved using hardware solutions (capacitors, Schmitt triggers) or software techniques (delays, state machines, and interrupts).


TASK 4

Why Do We Use Interrupts?
Interrupts are used in microcontrollers to handle time-sensitive events efficiently without continuously checking for them in the main program loop. Instead of constantly polling for input, an interrupt allows the microcontroller to pause its current task, execute a specific function, and then resume from where it left off. This makes the system more responsive and efficient, especially in applications like real-time systems, sensors, and embedded devices.

How Do Interrupts Lower the Processing Cost of the Microcontroller?
Interrupts reduce the processing cost by eliminating the need for continuous polling, which consumes CPU cycles even when no event occurs. Instead of wasting resources on checking inputs repeatedly, the microcontroller remains idle or focuses on other tasks until an interrupt signal is triggered. This improves overall performance, reduces power consumption, and optimizes resource utilization in embedded systems.
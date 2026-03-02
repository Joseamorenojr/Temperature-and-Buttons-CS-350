Emerging Systems Architectures and Technologies

This repository contains two embedded systems projects that demonstrate my ability to design interface software for hardware components, implement state machines, analyze hardware architectures, and apply maintainable software engineering practices.

Project 1: Smart Thermostat Prototype (Thermostat.py)

This project involved developing a working smart thermostat prototype for a company entering the IoT market. The system reads temperature data from an AHT20 sensor via I2C, manages heating and cooling states using PWM LEDs over GPIO, displays real-time information on a 16x2 LCD, and transmits status updates over UART to simulate cloud communication. A state machine controls three modes: off, heat, and cool, while buttons allow the user to cycle modes and adjust the temperature setpoint.

What I Did Well

I implemented a clean and reliable state machine with clear transitions and entry/exit logic. I successfully integrated multiple communication interfaces (GPIO, I2C, UART) within one application and used threading to manage the display without blocking system responsiveness. I also analyzed hardware architecture options (Raspberry Pi, Microchip, Freescale) and justified a solution based on memory, Wi-Fi capability, and peripheral support.

Areas for Improvement

I could improve error handling, logging, and hardware abstraction to make the system more production-ready and portable across platforms.

Transferable Skills

Designing finite state machines. 
Integrating hardware communication protocols
Managing concurrency in embedded systems
Evaluating hardware architectures based on business requirements

Maintainability

The project uses modular classes, consistent formatting, descriptive naming, and structured comments. Separating display management and state logic improves readability and adaptability.

Project 2: Morse Code State Machine (Milestone3.py)

This project required building a state machine that transmits Morse code messages using LEDs. The red LED represents dots (500 ms) and the blue LED represents dashes (1500 ms), with accurate timing between symbols, letters, and words. A button toggles between “SOS” and “OK” without interrupting the current transmission. A 16x2 LCD provides user feedback.

What I Did Well

I created a structured, timing-accurate state machine with clearly defined states for dots, dashes, and pauses. I implemented event-driven button handling and used threading to maintain smooth transmission while allowing message toggling.

Areas for Improvement

The transmit logic could be further refactored for simplicity, and timing values could be centralized for easier configuration.
Transferable Skills
Real-time state-driven system design
Event-based GPIO input handling
Timing coordination in embedded applications
Writing modular, scalable code

Maintainability

Clear state definitions, modular class design, and a Morse dictionary abstraction make the code easy to expand and adapt. 

Together, these projects demonstrate my ability to translate business requirements into functional embedded systems while applying structured design, hardware integration, and maintainable coding practices.

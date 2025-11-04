Automatic 3-Phase Generator Start System Under Phase Failure Condition

This project presents the design and implementation of an automatic three-phase generator start system that activates whenever a phase failure is detected in the utility grid. The system is built around a microcontroller-based control unit (Arduino Nano) that continuously monitors all three phases using ZMPT101B voltage sensors.

When a phase failure or total power outage occurs, the system automatically:

  Detects the faulty phase.
  
  Triggers the generator’s start sequence.
  
  Waits for voltage stabilization.
  
  Transfers the load seamlessly to the generator via automatic transfer relays.
  
  Returns to grid supply once normal power is restored.

Key Features:

  Real-time phase failure detection.
  
  Automatic generator start and stop.
  
  Safe transfer with electrical interlocking.
  
  Delay logic to prevent false starts.
  
  Compact and low-cost design for industrial and commercial use.

Technologies Used:

  Arduino Nano (microcontroller logic)
  
  ZMPT101B voltage sensors
  
  Relay and contactor interface circuits
  
  Embedded C / Arduino IDE

Performance:

  Phase failure detection: ~3 s
  
  Generator start and stabilization: ~10 s
  
  Total load transfer time: ~10 s


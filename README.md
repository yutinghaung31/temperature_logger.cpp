#Temperature Logger Simulator

A simple C++ multithreaded project that simulates a temperature sensor, logs readings to a file, and demonstrates embedded software development principles — inspired by real-world applications like Fluke handheld instruments.

#Project Overview

This application mimics how embedded devices gather and store sensor data in real time. It uses:
- Multithreading to simulate a background sensor and a logger
- File I/O to write the results to `temperature_log.txt`
- C++11 features like `std::thread`, `std::mutex`, and `std::chrono`
- Random number generation to simulate sensor readings

#Technologies Used

- C++
- C++11 standard library
- POSIX Threads (`-pthread`)
- Terminal-based input/output

#How to Run

1. Clone the repository:

   git clone https://github.com/YOUR_USERNAME/temperature-logger-simulator.git
   cd temperature-logger-simulator
#temperature_logger.cpp

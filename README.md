# AltRoutes Vehicle Simulator

A **Spring Boot-based vehicle simulation service** that models vehicles moving along predefined paths while avoiding collisions. Vehicles dynamically adjust their speed based on traffic ahead, with fractional progress tracking for smooth motion.

---

## 🚗 Features

- **Multiple Vehicles Simulation**: Supports multiple vehicles moving simultaneously on the same or different paths.  
- **Collision Avoidance**: Vehicles slow down when another vehicle is too close ahead.  
- **Adaptive Speed Control**: Vehicles accelerate when the path is clear and decelerate near traffic.  
- **Fractional Movement**: Smooth movement using fractional progress instead of discrete jumps.  
- **Configurable Parameters**:
  - `safeDistance`: Minimum nodes apart to avoid collision.
  - `minSpeed`: Minimum speed to prevent deadlocks.
  - `maxSpeed`: Maximum speed a vehicle can reach.
  - `acceleration`: Speed increase per tick.

---

## 📦 Technology Stack

- **Java 17**  
- **Spring Boot 3.x**  
- **Lombok** for reducing boilerplate code  
- **SLF4J** for logging  
- **Spring Scheduling** for periodic simulation updates  

---

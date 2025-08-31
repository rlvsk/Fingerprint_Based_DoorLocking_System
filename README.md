# Fingerprint_Based_DoorLocking_System
This project presents a biometric door security system designed to replace traditional keys with fingerprint authentication for enhanced security and convenience. Built around a fingerprint sensor and microcontroller, the system ensures that only authorized users are granted access.

**Overview :**

The fingerprint module allows storage of up to 1000 unique fingerprints, making it suitable for both personal and small-scale institutional use. Stored fingerprints can be easily added or deleted as required, giving the system flexibility for dynamic access management.

Upon successful authentication, the system activates a 12V solenoid lock via a relay module. The average response time for the lock to disengage after fingerprint recognition is approximately 1.5 seconds, ensuring both efficiency and reliability in day-to-day usage.

**Core Components :**

R307 Fingerprint Sensor: Captures, stores, and verifies biometric data with high accuracy.

Arduino Uno: Acts as the primary controller, handling data from the sensor and triggering the lock.

Relay Module: Provides the necessary switching to control the solenoid lock safely.

12V Solenoid Lock: Physically secures the door and unlocks when authentication succeeds.

Breadboard and Jumper Wires: Used for prototyping and modular connectivity during development.

**Functional Highlights :**

High Capacity: Supports up to 1000 fingerprint entries, suitable for multiple users.

Flexible Management: Fingerprints can be added or removed at any time, making access control seamless.

Efficient Response: Lock operation occurs within 1.5 seconds of recognition, ensuring minimal delay.

Secure and Reliable: Eliminates risks associated with lost or duplicated physical keys.

**Learning Impact :**

Through this project, practical experience was gained in working with embedded systems, biometric technology, and electronic security hardware. Additionally, the system was also experimented on an STM32 microcontroller to compare performance and adaptability beyond Arduino-based development.

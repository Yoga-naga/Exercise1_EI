# yogapriya
EI
# Hostel Management — Design Patterns Demo

Language: Java

Structure: Each design pattern example is in its own package. One-class-per-file.

How to run:
1. mvn/gradle project available. Or compile manually:
   javac -d out src/main/java/com/example/hostel/**/**/*.java
   java -cp out com.example.hostel.behavioral.Observer.ObserverDemo

2. Tests: run each Demo main for each package.

Design decisions:
- Used Observer for push notifications.
- Strategy for runtime payment selection.
- Factory separates creation of leave types for maintainability.
- Builder ensures safe creation of complex immutable StudentProfile.
- Decorator adds logging/validation orthogonally.
- Adapter wraps legacy provider to new interface.

Commit messages: use short imperative style, e.g., "Add Observer pattern for room notifications".


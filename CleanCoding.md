# Clean Code Principiles

## 1. Grad

### Don´t Repeat Yourself (DRY)

### Keep it simple, stupid (KISS)

### Vorsicht vor Optimierungen!

### Favour Composition over Inheritance (FCoI)

### Integration Operation Segregation Principle (IOSP)

- Entweder enthält eine Methode **nur Logik**, d.h. Transformationen, Kontrollstrukturen oder I/O- bzw. allgemeiner: API-Aufrufe. Dann wird sie **Operation** genannt.
- Oder eine Methode enthält **keinerlei Logik**, sondern nur Aufrufe von anderen Methoden derselben Codebasis. Dann wird sie **Integration** genannt.

### Die Pfadfinderregel beachten

**Hinterlasse einen Ort immer in einem besseren Zustand als du ihn vorgefunden hast.**

### Root Cause Analysis

### Ein Versionskontrollsystem einsetzen

### Einfache Refaktorisierungsmuster anwenden

- Methode extrahieren
- Umbenennen

### Täglich reflektieren

- Kleinschrittige Planung
- Reflexion nach jedem Schritt
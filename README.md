Updated the library to support ESP IDF platform

Made changes:

1. In a line in assembly.h 
Line 420: #elif defined(ARDUINO) || defined(ESP32) || defined(__XTENSA__) || defined(__APPLE__) || defined(__unix__)

2. Converted helix_memory.cpp to helix_memory.c for C compiler ease

I have only made these two changes, Rest of the software is the same, I do not claim the entire software.

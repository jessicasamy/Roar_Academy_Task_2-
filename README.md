# Academy Task 2 – STM32 LED Control

This project uses an **STM32F103C8T6** microcontroller to control an LED with a push button.  
A **debouncing technique** is implemented to avoid false triggers, and the system is simulated in **Proteus**.

---

## Requirements
- STM32CubeIDE  
- Proteus  
- STM32 HAL Drivers Documentation  

---

## How to Run
1. Open the STM32CubeIDE project and build it.  
2. Find the generated `.hex` file inside the **Debug** folder.  
3. Open the Proteus project and load the `.hex` file into the STM32 component.  
4. Run the simulation → press the button → LED toggles.  

---

## Debouncing
- Method: **Simple delay-based debouncing** (~50 ms).  
- Purpose: Prevents multiple toggles caused by switch noise.  

---

## Author
- Jessica Samy  

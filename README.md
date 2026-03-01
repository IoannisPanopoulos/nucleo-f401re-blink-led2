# NUCLEO-F401RE — Blinky (LD2)

Board: **NUCLEO-F401RE (STM32F401RE)**  
Project: Blink the on-board LED **LD2**.

## What it does
- Toggles LD2 every 2500 ms (blink).

## Hardware
- Board: NUCLEO-F401RE
- USB: connect the PC to the **ST-LINK USB** connector (powers + programs the board)

## Build & Flash (STM32CubeIDE)
1. Open **STM32CubeIDE**
2. **File → Open Projects from File System...** (or import the project)
3. Build (hammer icon)
4. Run/Debug (green play / bug icon)
5. LED LD2 should blink

## Code
The blink logic is inside `Core/Src/main.c`:
<img width="4096" height="3072" alt="image" src="https://github.com/user-attachments/assets/1989f267-3779-486d-a19d-a4b194058c10" />
<img width="3072" height="4096" alt="image" src="https://github.com/user-attachments/assets/efdd8752-7a7d-4c27-8ecb-fb6c371746b4" />

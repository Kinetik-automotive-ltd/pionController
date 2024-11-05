
# PionController
Repo for STM32 based PION rearlight controller

![Top view](https://gist.github.com/user-attachments/assets/3d3f550c-7c4f-41f8-b1af-7d7980b72fb8)

![Bottom view](https://gist.github.com/user-attachments/assets/cd886626-65e4-4a15-87b1-9d01fb4132ef)

**Overview**

The Pion backlight control board is engineered to manage a 7x109 pixel LED matrix backlight within automotive interiors. This board leverages the STM32H743VITx microcontroller for LED control, offering dynamic picture displaying.

### Key Components

-   **Main Processor**: The STM32H743VITx microcontroller drives the control and processing of the LED matrix.
-   **CAN Transceivers**:
    -   **CAN Common**: Handles standard communication for routine vehicle operations.
    -   **CAN Critical**: Dedicated line for critical or high-priority messages within the system.
-   **Power Regulation**:
    -   **12V to 5V Regulator**: Provides a 5V supply.
    -   **5V to 3.3V Regulator**: Additional power regulation for the STM32.
-   **ESD Protection Circuit**: Protects sensitive components from electrostatic discharge.
-   **GPIO Pins (4)**: Converted from 3.3V to 5V via a voltage regulator, ensuring compatibility with external systems operating at higher voltages.



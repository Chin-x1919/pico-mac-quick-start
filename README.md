# WelcomeToQuickStartForPico-mac


Original form this [Repo](https://github.com/evansm7/pico-mac)
![IMG_78582722-02B2-4325-B8D7-8D666354C072](https://github.com/user-attachments/assets/d6a27c38-c5c6-4b94-81d0-36a43addbc90)
![IMG_1818](https://github.com/user-attachments/assets/21b60843-6929-48ce-bb4b-9e6e0abf6365)


| **Raspberry Pi Pico Pin** | **GPIO** | **Resistor** | **Connect To (VGA Board)** | **Note**                                                           |
| ------------------------- | -------- | ------------ | -------------------------- | ------------------------------------------------------------------ |
| Pin 24                    | GP18     | 100 Ω (×3)   | R, G, B                    | use GP18 only |
| Pin 27                    | GP21     | 68 Ω         | HSYNC (UGAHS)              | Horizontal sync                                                    |
| Pin 25                    | GP19     | 68 Ω         | VSYNC (UGAVS)              | Vertical sync                                                      |
| Pin 38 / Pin 23           | GND      | –            | VGA GND                    | Connect GND                                                        |
| Pin 39 (VSYS)             | –        | –            | VCC (5V)                   | use power form external psu                                        |
| ------------------------- | -------- | ------------ | -------------------------- | ------------------------------------------------------------------ |


you can download demo uf2 form [here](https://picomac.bluescsi.com/) if you're lazy(like me)
Just drag & drop it onto your Pico’s USB drive after holding the BOOTSEL button while plugging in.
**Important Notes**
Do not connect USB and external PSU at the same time
Using a breadboard may cause some signal noise If you want stability, it is recommended to use a PCB or perfboard
The resistor must be 100Ω (not 100kΩ) and 68Ω
MIT License

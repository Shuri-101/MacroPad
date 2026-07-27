# Fracture Pad (A macro pad project) 
<img width="822" height="707" alt="image" src="https://github.com/user-attachments/assets/de8d373c-149d-4e0c-bff8-5b10820a8ddc" />
<img width="790" height="578" alt="image" src="https://github.com/user-attachments/assets/59cad784-7688-41ac-932d-40816a054748" />

## Description:
A macro Pad for use in CAD and general productivity + convenience, mainly for use in CAD... but up to you to decide what you want to use it for, I included an OLED screen to display things like animations or info like RAM usage.

## Features:
- 1.51 inch transparent oled screen
- 9 cherry MX switches
- Back lit RGB leds for each switch (SK6812 MINI-E)
- 3 EC11 rotary encoders
- 3D printed voronoi patterned **snap lock** case **NO SCREWS NEEDED for assembly of case** (only screws are needed for the mounting of the OLED driver board which are provided in the oled package bought from waveshare)
- **NO HEAT ISERTS REQUIRED** as the oled board can be mounted on 3D printed standoffs by just threading the screws on since not a high amount of strength is required for mounting of the driver board.
- 3D printed TPU feet to prevent the macro pad from sliding around.

## CAD model:

### Info:
The casing is made up of 3 main layers OLED cover --> Case Lid --> Case bottom. Things that should be 3D printed are Rotary encoder knobs, All casing layers and OLED driver board standoffs. The casing has a OLED cover so the OLED driver and screen can be removed from the PCB so it can be reused. YOU MUST solder the MX switches after putting the PCB into the case (bottom and lid) since the lid contains a key panel to support the MX switches.

"Note: Created in solidworks"

### OLED cover:
<img width="750" height="525" alt="image" src="https://github.com/user-attachments/assets/972625da-d876-4583-8000-3447585b5a6a" />

### Case Lid:
<img width="726" height="517" alt="image" src="https://github.com/user-attachments/assets/a7320156-96dd-4282-a8d3-9c8bee3285a3" />

### Case bottom:
<img width="655" height="512" alt="image" src="https://github.com/user-attachments/assets/58f7b6bb-c8c7-4409-b0cb-16c181e2a5f3" />

### View of PCB mounting:
<img width="1028" height="678" alt="image" src="https://github.com/user-attachments/assets/af558c1d-702e-44d7-8aae-0b8f91d6d4d5" />

### Exploded view:
<img width="633" height="697" alt="image" src="https://github.com/user-attachments/assets/1d6f99af-05c4-44fd-835f-e02b038619ef" />
<img width="592" height="685" alt="image" src="https://github.com/user-attachments/assets/118f1bd5-c803-4098-a33b-8bf47e916044" />
<img width="570" height="625" alt="image" src="https://github.com/user-attachments/assets/a52a62b5-ae21-4755-89a5-eb608af0ce36" />

## Schematic:
<img width="1081" height="745" alt="image" src="https://github.com/user-attachments/assets/32968214-80ff-44a4-b055-5866b7310732" />
<img width="1335" height="793" alt="image" src="https://github.com/user-attachments/assets/78ef014f-713a-467c-8a9f-dff25a2e30e8" />
<img width="1202" height="826" alt="image" src="https://github.com/user-attachments/assets/013ee33c-b5fd-46b6-bb5d-8c49de73e9bc" />
<img width="902" height="816" alt="image" src="https://github.com/user-attachments/assets/32ce0920-7ddf-4a41-a6ab-d4c884e2af21" />

### Info:
- GPIO expander used to host the keyboard matrix allowing me to have 3 rotary encoders.
- Decoupling capacitors added for RGB LEDs and GPIO expander.
- Thru hole pads added for oled wires that connect to the oled driver board. 


## PCB
<img width="925" height="703" alt="image" src="https://github.com/user-attachments/assets/3d0b6c4c-6598-497b-9b01-34d272348e62" />

### Info:
- 2 layer PCB with ground plane included.
- 113mm (width) x 86mm (height).
- M3 sized mounting holes for securing the PCB. (No screws are used for mounting of this PCB in the case)
- I recomend to get the manufacutre to assemble the PCB for you as i use SMD variants for diodes, capacitors and components to save space, unless you know how to do reflow soldering and have the equipment.

## Firmware overview:

- Work in progress...

## BOM
- 9x SK6812MINI-E RGB LEDS.
- 9X Cherry MX keycaps.
- 85g of 3D printing filament (optional 3 colours and TPU feet)
- x1 MLCC ceramic capacitor 0.1uF
- x9 Cherry MX Mechanical Switches
- x1 Seeeduino XIAO SAMD21 (MCU) 
- x1 MLCC ceramic 4.7uF
- x1 330Ω resistor 
- x1 47 µF Electrolytic Capacitor
- x1 EC11 Rotary encoders


## Ai usage declaration:
Since this was my first PCB project i used ai extensively for research and learning how to design PCBs and how to use ki-cad. e.g. "How wide should this trace be" or  "What is a decoupling capacitor when should I use it I'm circuit does the GPIO expander need a decoupling capacitor..." **I ONLY USE AI TO LEARN**  like now i understand why decoupling capacitors are used and how they are connected and now i understand power traces like 5v should be wide and ground traces if needed should be wider to allow low resistance path... ill be happy to answer any questions regarding this.





# Kiwi Board

<img width="1216" height="679" alt="Screenshot 2025-08-16 at 12-41-57 471098307-857b4444-1be0-49bc-9b43-69fed2567859 png (PNG Image 1916 × 1100 pixels)" src="https://github.com/user-attachments/assets/ec3e78be-8b4e-432c-91e6-80fe78da471a" />


The Kiwi Board is a 42-key split keyboard designed for stenographic input. It features a 3×6 column-staggered layout with 3 thumb keys per side.  
The design is based on the [Polyglot keyboard](https://stenokeyboards.com/products/polyglot-keyboard) and includes an integrated RP2040 microcontroller.

This project started after I discovered steno and wanted to build a keyboard tailored for learning and experimenting with chorded input.

---

## Specifications

- Layout: Split, 3×6 + 3 thumb keys per side
- Total keys: 42
- Switches: MX
- Microcontroller: RP2040 (integrated)
- Firmware: [RMK](https://rmk.rs/) — A feature-rich Rust keyboard firmware
- Intended use: Compatible with steno software (e.g. [Plover](https://www.openstenoproject.org/plover/))

---

## Images

### PCB
<img width="1795" height="533" alt="image" src="https://github.com/user-attachments/assets/3fe10ff4-71dc-4758-a3b4-366e7a594955" />
<img width="2083" height="638" alt="image" src="https://github.com/user-attachments/assets/21614ac0-9672-4e2c-bfd5-21e89522caf4" />
<img width="1227" height="379" alt="image" src="https://github.com/user-attachments/assets/cda3ae21-e4e4-4a53-9af9-7eb9dc810d3e" />

### Schematic
<img width="1521" height="597" alt="image" src="https://github.com/user-attachments/assets/fd9ab7bb-5464-4f16-b5e8-8181591fd2c4" />
<img width="1822" height="1032" alt="image" src="https://github.com/user-attachments/assets/deadeab7-da63-49ea-b195-a460a0106978" />

### Case
<img width="1920" height="1080" alt="kiwi-top" src="https://github.com/user-attachments/assets/2b4a51f6-2061-4b20-b024-4e4b7f415d74" />
<img width="1367" height="609" alt="kiwi-side" src="https://github.com/user-attachments/assets/ab3ba2bd-b824-49e7-8cc8-06e99b9d9a5b" />
<img width="1916" height="1100" alt="kiwi-closeup" src="https://github.com/user-attachments/assets/857b4444-1be0-49bc-9b43-69fed2567859" />
<img width="2160" height="1100" alt="kiwi-angled" src="https://github.com/user-attachments/assets/0adbfe59-6658-45a5-b97e-50094731140b" />

---

## Bill of Materials (BOM)

| Item         | Price   | Notes                                |
|--------------|---------|--------------------------------------|
| PCB          | $83.78  | Ordered from JLCPCB                  |
| Keycaps      | $9.90   | [AliExpress link](https://shorturl.at/fVK32) |
| Rubber Feet  | $3.84   | [AliExpress link](https://shorturl.at/bqHlW) |
| Switches     | $32.72  | [Deltakey Co.](https://deltakeyco.com/)     |
| diodes    |  |           i own them           |
| hotswap sockets    |  |           i have them               |
| **Total**    | **$130.24** |                              |

---

## Firmware

The Kiwi Board uses [RMK](https://rmk.rs/), A feature-rich Rust keyboard firmware!


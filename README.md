# The Gater 🕹️

A physical logic gate explorer built entirely with raw 74LS-series logic. No microcontrollers. No code. Just pure digital logic hardware.

![Front of PCB](https://github.com/MZatar/The-Gater/blob/main/Images/front.png) ![real](https://github.com/MZatar/The-Gater/blob/main/Images/20260309_160907.jpg)   

## What is it?
The Gater is an educational PCB that physically demonstrates all 8 standard logic gate configurations (BUF, INV, AND, NAND, OR, NOR, XOR, XNOR) using only one `74LS00` (Quad NAND) and one `74LS02` (Quad NOR). 

Three DPDT toggle switches physically reroute the logic paths to mimic the desired gate, while dual push buttons provide the inputs.

## Features
* **100% Hardware Logic:** Relies purely on combinational routing between NAND and NOR gates.
* **8 Gate Modes:** Configurable via a 3-switch binary input (000 to 111).
* **Modern Power:** USB-C compatible (with proper 5.1kΩ CC pull-down resistors for C-to-C cable support) alongside standard pin headers.
* **Built-in Cheat Sheet:** Silkscreen truth tables for all gates right on the back.
* **Transparent Case:** Designed for a 3D-printed transparent PETG cover.

## Hardware Configuration
| Config (Switches) | Gate Configured |
| :--- | :--- |
| `000` | Buffer |
| `001` | Inverter (NOT) |
| `010` | AND |
| `011` | NAND |
| `100` | OR |
| `101` | NOR |
| `110` | XOR |
| `111` | XNOR |

## How to Build It
1. **Fabrication:** Grab the `.zip` file and upload it to your favorite PCB manufacturer (JLCPCB, PCBWay, etc.).
2. **Components:** Check the `BOM.csv` folder for exact parts.
3. **Assembly:** Solder the SMDs first (Type-C port), then move to the through-hole components.
4. **Case:** (optional) Print the `Gater_Case.stl` using transparent filament.

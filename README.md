# Raspberry Pi 4B Ventilated Case for OctoPrint

A compact, 3D-printable case for the **Raspberry Pi 4B**, designed for **OctoPrint use with active airflow** and compatible with pi camera module 2.

This enclosure is optimized for:

* Thermal stability
* Easy access to I/O
* Optional active cooling (4010 fan)

---

![Raspberry Pi 4B Case Render](docs/pi_case.png)

---

## Parts List

| Part                                   | Qty | Notes                           |
| -------------------------------------- | --- | ------------------------------- |
| Raspberry Pi 4B                        | 1   | Tested with 4GB & 8GB models    |
| M3 x 6mm screws                        | 4   | For lid mounting                |
| M3 x 10–12mm screws                    | 4   | For Pi mounting                 |
| M3 hex nuts                            | 4   | Optional if using through holes |
| 4010 5V Fan *(optional)*               | 1   | Recommended for OctoPrint       |
| Raspberry Pi heatsink kit *(optional)* | 1   | CPU + RAM + USB controller      |
| MicroSD Card                           | 1   | Class 10 / U1 or better         |
| 5V Power Supply                        | 1   | Official recommended            |

---

## Assembly

1. Insert M3 screws through the Pi mounting holes in the base.
2. Seat the Raspberry Pi 4B onto the internal standoffs.
3. Secure with nuts or screw directly into printed holes.
4. (Optional) Install heatsinks on:

   * CPU
   * RAM
   * USB controller
5. (Optional) Mount a 4010 fan:

   * **Orientation:** blow air *into* the case across the heatsinks
6. Attach lid using M3 x 6mm screws.

---

## Cooling Notes

This case is designed with:

* Top ventilation grid
* Bottom intake gap
* Side exhaust clearance

For OctoPrint (especially with camera streaming), active cooling is strongly recommended to avoid thermal throttling during long prints.

---

## License

MIT License – free to modify and remix.

---

Pull requests welcome!

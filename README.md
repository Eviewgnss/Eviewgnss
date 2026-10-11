# Eview GNSS

**RTK and dual-antenna heading GNSS receivers powered by Septentrio modules.**

Eview GNSS Technology Ltd designs and manufactures high-precision GNSS receivers, smart antennas, OEM boards and GNSS antennas for drones and UAVs, robotics, precision agriculture, surveying and GIS, construction, mining and marine platforms. Founded in 2010.

[Website](https://gnss-solutions.com/) · [sales@gnss-solutions.com](mailto:sales@gnss-solutions.com) · [YouTube](https://www.youtube.com/@EviewGNSS) · [LinkedIn](https://www.linkedin.com/company/gnss-solutions1)

---

## Product range by Septentrio module

| Septentrio module  | Eview products                                                                                                                      | Highlights                                         |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| **mosaic-G5**      | HBEV322 / HBEV11 RTK smart antennas, HB50, HB51, HB52 receivers; dual-antenna heading on HB50H, HB51, HB52H; G5P3H evaluation board | Quad-band, ultra-compact, low power; Galileo OSNMA |
| **mosaic-X5**      | HB6, HB56, HB62 base receiver                                                                                                       | All bands, up to 100 Hz; Galileo OSNMA             |
| **mosaic-H**       | HB6 Pro, HB56H                                                                                                                      | Dual-antenna heading, 0.15° at 1 m baseline        |
| **AsteRx-m3 Pro+** | HB10 receiver, HB59 OEM board                                                                                                       | Up to 100 Hz, low latency, dual-antenna heading    |
| **GNSS antennas**  | EV108, EV210, EV220, EV226, EV288                                                                                                   | Multi-band survey and UAV antennas                 |

**RTK accuracy (Septentrio specification):** 0.6 cm + 0.5 ppm horizontal, 1 cm + 1 ppm vertical.
**Interference mitigation:** Septentrio AIM+ on all receivers.

Module overview: [gnss-solutions.com/technology](https://gnss-solutions.com/technology/)

---

## Integration

Eview receivers output **Septentrio SBF** and **NMEA** and work with the existing open-source Septentrio drivers:

- **ArduPilot** – `GPS1_TYPE = 10` (SBF) or `26` (SBF dual-antenna heading)
- **PX4** – Septentrio driver (`SEP_PORT1_CFG`)
- **ROS 2** – [`septentrio_gnss_driver`](https://github.com/septentrio-gnss/septentrio_gnss_driver)

Configuration examples: **[ardupilot-config-examples](https://github.com/Eviewgnss/ardupilot-config-examples)** (ArduPilot parameters for HB6, HB52, HBEV322, HB6 Pro and HB10). PX4 and ROS 2 examples coming next.

---

## Datasheets, manuals and quotes

Datasheets and manuals are sent by email, and all products are quoted on request:
**[sales@gnss-solutions.com](mailto:sales@gnss-solutions.com?subject=Datasheet%20request)**

---

<sub>Eview GNSS is an independent manufacturer. Septentrio, mosaic and AsteRx are trademarks of Septentrio NV.

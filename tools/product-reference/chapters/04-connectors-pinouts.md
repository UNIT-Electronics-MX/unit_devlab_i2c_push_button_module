## **4 Connectors & Pinouts**

The released V1.0 pinout for the UE0168 Push Button Module shows the top and
bottom board views. Check the view and connector orientation before wiring.

### **4.1 Released Pinout** {.section-page}

![UE0168 Push Button Module pinout, top and bottom views.](../../../hardware/resources/unit_pinout_v_1_0_ue0168_i2c_push_button_module_en.png){width=5.8in}

**Figure 4.1 — UE0168 pinout, English version.** The Spanish version is linked
in Section 8.

### **4.2 Connection Groups** {.page-break}

| Group | Labels in the released drawing | Purpose |
|---|---|---|
| Qwiic I2C connector | `GND`, `VCC`, `SDA`, `SCL` | Power and I2C bus connections |
| Direct contacts | `VCC`, `GND`, `SIG` | Power and direct signal access |
| Service pads | `TX`, `RX`, `RST` | Pads identified in the drawing; consult the hardware design before use |

The drawing also marks two optional 4-pin, 1 mm JST connector positions. Its
solder-link note says opening the marked pad disables the I2C `SIG` signal.
The pinout does not establish electrical limits or connector part numbers.

# HDMI Test Pattern Generator

This design creates an HDMI driver with 4 different selectable test patterns.
The design is implemented on the Zybo Z7-10, using only PL and the onboard 125MHz oscillator.

VHDL files are found in HDMI_TPG/src/

vunit files are found in HDMI_TPG/test/

Constraint files are found in HDMI_TPG/constr/

```bash
--HDMI_TPG
 |
 |--src/
 |--test/
 |--cnstr/
```


TODO:
-- Short description about 8b/10b. Not the same as IBM's standard! This is totally different.
-- Test pattern_gen
-- Implement Xilinx SPram
-- Remove commented out clk_wiz_wrapper

![alt text](https://github.com/LJO-S/HDMI_TPG/blob/main/diagram.png)

## Design Summary
-Circuit: adc5b
-VDD: 1.2V
-Process: Tsmc 65nm
 
---

## Design Hierarchy 
-SAR5LG: 5-bit SAR ADC logic
-CDAC4b: 4-bit CDAC (Capacitor Digital to Analog Converter)
-BTSW: Bootstrapped Switch
-VCMP: Voltage Comparator

---

## Example 

```shell
$ Xyce adc5b.cir
```

---

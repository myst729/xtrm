# Xtrm

Extremely borderless mechanical keyboard. 40% staggered layout with an encoder, runs [QMK firmware](https://github.com/myst729/qmk_firmware/tree/master/keyboards/dg/xtrm).

![](images/xtrm.gif)

[On homemade keyboards](https://myst729.github.io/posts/2020/xtrm-40-keyboard/) (written in Chinese).

## Wiring

```
      C0      C1    C2    C3    C4    C5      C6    C7    C8     C9     C10       C11
   ,-------------------------------------------------------------------------------------.
R0 |  Esc  |  Q  |  W  |  E  |  R  |   T   |  Y  |  U  |  I  |   O    |  P   | Backspace |
   |-------+-----+-----+-----+-----+-------+-----+-----+-----+--------+------+-----------|
R1 |  Tab  |  A  |  S  |  D  |  F  |   G   |  H  |  J  |  K  |   L    |      |   Enter   |
   |-------+-----+-----+-----+-----+-------+-----+-----+-----+--------+------+-----------|
R2 | Shift |     |  Z  |  X  |  C  |   V   |  B  |  N  |  M  | RShift |  Up  | Caps Lock |
   |-------+-----+-----+-----+-----+-------+-----+-----+-----+--------+------+-----------|
R3 | Ctrl  | GUI |     | Alt |     | Space |     | Fn  | Fn2 |  Left  | Down |   Right   |
   `-------+-----+-----+-----+-----+-------+-----+-----+-----+--------+------+-----------'
```


## Tools

| Tool                              | Picture                    |
| --------------------------------- | -------------------------- |
| Soldering Iron (936)              | ![](images/tools/iron.jpg) |
| Soldering Wire (Sn63/Pb37, 0.8mm) | ![](images/tools/wire.jpg) |
| Soldering Flux                    | ![](images/tools/flux.jpg) |


## Materials

| Material         | Label               | Quantity | Picture                                   |
| ---------------- | ------------------- | -------- | ----------------------------------------- |
| ATMEGA32U4-AU    | U1                  | 1        | ![](images/materials/atmega32u4-au.jpg)   |
| PRTR5V0U2X       | U2                  | 1        | ![](images/materials/tvs-diode.jpg)       |
| 16MHz Crystal    | X1                  | 1        | ![](images/materials/crystal-16mhz.jpg)   |
| Type-C Connector | CN1                 | 1        | ![](images/materials/type-c.jpg)          |
| 500mA Fuse       | F1                  | 1        | ![](images/materials/fuse-500ma.jpg)      |
| 3mm LED          | LED1                | 1        | ![](images/materials/led-3mm.jpg)         |
| 10KΩ Resistor    | R3, R4, R6, R7, R10 | 5        | ![](images/materials/resisitor-10k.jpg)   |
| 5.1KΩ Resistor   | R2, R5              | 2        | ![](images/materials/resisitor-5100.jpg)  |
| 1KΩ Resistor     | R1, R11             | 2        | ![](images/materials/resisitor-1k.jpg)    |
| 22Ω Resistor     | R8, R9              | 2        | ![](images/materials/resisitor-22.jpg)    |
| 1uF Capacitor    | C6                  | 1        | ![](images/materials/capacitor-1uf.jpg)   |
| 470nF Capacitor  | C1                  | 1        | ![](images/materials/capacitor-470nf.jpg) |
| 100nF Capacitor  | C2, C3, C4, C5      | 4        | ![](images/materials/capacitor-100nf.jpg) |
| 10nF Capacitor   | C7, C8              | 2        | ![](images/materials/capacitor-10nf.jpg)  |
| 22pF Capacitor   | C9, C10             | 2        | ![](images/materials/capacitor-22pf.jpg)  |
| 1N4148 Diode     | D1-D43              | 43       | ![](images/materials/diode-1n4148.jpg)    |
| EC11 Encoder     | SW24                | 1        | ![](images/materials/encoder-ec11.jpg)    |
| 3x6x2.5 Switch   | KEY1                | 1        | ![](images/materials/switch-3x6x2.5.jpg)  |


## Pictures

![](images/keyboard/preview.jpg)

![](images/keyboard/kit.jpg)

![](images/keyboard/pcb.jpg)

![](images/keyboard/knob.jpg)

![](images/keyboard/almost.jpg)

![](images/keyboard/finished.jpg)

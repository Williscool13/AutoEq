# JAYS u-JAYS
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -2.9; 23 -3.3; 25 -3.6; 28 -4.0; 31 -4.2; 34 -4.5; 37 -4.6; 41 -4.8; 45 -4.9; 49 -5.0; 54 -5.1; 60 -5.4; 66 -5.6; 72 -5.8; 79 -5.9; 87 -6.1; 96 -6.1; 106 -6.0; 116 -5.9; 128 -5.9; 141 -6.4; 155 -6.4; 170 -5.9; 187 -6.1; 206 -5.9; 227 -5.5; 249 -5.1; 274 -4.2; 302 -3.3; 332 -2.8; 365 -2.8; 402 -3.1; 442 -3.5; 486 -4.1; 535 -4.3; 588 -4.4; 647 -4.8; 712 -5.3; 783 -5.5; 861 -6.0; 947 -6.3; 1042 -6.5; 1146 -6.4; 1261 -6.4; 1387 -6.5; 1526 -6.7; 1678 -6.7; 1846 -6.0; 2031 -5.2; 2234 -4.3; 2457 -3.1; 2703 -2.4; 2973 -2.3; 3270 -2.8; 3597 -2.1; 3957 -0.5; 4353 -1.1; 4788 -0.8; 5267 -1.8; 5793 -3.7; 6373 -4.3; 7010 -5.5; 7711 -4.4; 8482 -4.5; 9330 -4.5; 10263 -4.5; 11289 -4.5; 12418 -4.5; 13660 -4.5; 15026 -4.5; 16529 -4.5; 18182 -4.5; 20000 -4.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`JAYS u-JAYS GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `JAYS u-JAYS ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.2dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 2.95 | 1.5 dB  |
| Peaking | 382 Hz  | 2.86 | 2.4 dB  |
| Peaking | 2392 Hz | 0.43 | -3.6 dB |
| Peaking | 2638 Hz | 1.91 | 4.3 dB  |
| Peaking | 4353 Hz | 1.74 | 6.0 dB  |
| Peaking | 79 Hz   | 1.7  | -0.8 dB |
| Peaking | 177 Hz  | 0.66 | -1.6 dB |
| Peaking | 308 Hz  | 3.52 | 1.8 dB  |
| Peaking | 569 Hz  | 2.59 | 0.9 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 0.8 dB  |
| Peaking | 62 Hz    | 1.41 | -0.9 dB |
| Peaking | 125 Hz   | 1.41 | -1.9 dB |
| Peaking | 250 Hz   | 1.41 | 0.0 dB  |
| Peaking | 500 Hz   | 1.41 | 1.6 dB  |
| Peaking | 1000 Hz  | 1.41 | -2.5 dB |
| Peaking | 2000 Hz  | 1.41 | -1.2 dB |
| Peaking | 4000 Hz  | 1.41 | 4.3 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.9 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/JAYS%20u-JAYS/JAYS%20u-JAYS.png)
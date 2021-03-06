# Shure SE846 Black sample 1
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -8.1; 23 -8.2; 25 -8.4; 28 -8.5; 31 -8.6; 34 -8.7; 37 -8.8; 41 -8.9; 45 -8.9; 49 -8.9; 54 -9.0; 60 -9.1; 66 -9.2; 72 -9.3; 79 -9.4; 87 -9.6; 96 -9.7; 106 -9.8; 116 -9.8; 128 -9.8; 141 -9.7; 155 -9.7; 170 -9.5; 187 -9.4; 206 -9.2; 227 -9.2; 249 -9.0; 274 -8.9; 302 -8.8; 332 -8.7; 365 -8.6; 402 -8.6; 442 -8.6; 486 -8.5; 535 -8.4; 588 -8.2; 647 -8.0; 712 -7.7; 783 -7.3; 861 -6.9; 947 -6.8; 1042 -7.0; 1146 -7.7; 1261 -8.3; 1387 -8.6; 1526 -8.3; 1678 -7.7; 1846 -7.0; 2031 -6.3; 2234 -5.5; 2457 -4.5; 2703 -3.5; 2973 -2.5; 3270 -2.5; 3597 -3.0; 3957 -3.3; 4353 -2.4; 4788 -0.7; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -7.1; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Shure SE846 Black sample 1 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SE846 Black sample 1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 31 Hz   | 0.2  | -1.5 dB |
| Peaking | 181 Hz  | 0.31 | -2.3 dB |
| Peaking | 1474 Hz | 2.56 | -2.2 dB |
| Peaking | 3065 Hz | 2.05 | 3.6 dB  |
| Peaking | 5452 Hz | 2.31 | 6.4 dB  |
| Peaking | 562 Hz  | 3    | -0.4 dB |
| Peaking | 915 Hz  | 4.68 | 0.7 dB  |
| Peaking | 6525 Hz | 7.02 | 2.4 dB  |
| Peaking | 7993 Hz | 2.25 | -1.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -1.9 dB |
| Peaking | 62 Hz    | 1.41 | -2.0 dB |
| Peaking | 125 Hz   | 1.41 | -2.8 dB |
| Peaking | 250 Hz   | 1.41 | -1.9 dB |
| Peaking | 500 Hz   | 1.41 | -1.4 dB |
| Peaking | 1000 Hz  | 1.41 | -0.8 dB |
| Peaking | 2000 Hz  | 1.41 | -1.1 dB |
| Peaking | 4000 Hz  | 1.41 | 6.0 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Shure%20SE846%20Black%20sample%201/Shure%20SE846%20Black%20sample%201.png)
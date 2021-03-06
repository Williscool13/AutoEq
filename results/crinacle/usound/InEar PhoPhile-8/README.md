# InEar PhoPhile-8
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.9; 25 -1.2; 28 -1.6; 31 -1.9; 34 -2.1; 37 -2.3; 41 -2.6; 45 -2.8; 49 -3.0; 54 -3.3; 60 -3.5; 66 -3.8; 72 -4.2; 79 -4.5; 87 -4.9; 96 -5.3; 106 -5.7; 116 -6.0; 128 -6.2; 141 -6.5; 155 -6.7; 170 -6.8; 187 -6.9; 206 -6.9; 227 -7.0; 249 -7.0; 274 -6.9; 302 -6.9; 332 -6.9; 365 -6.8; 402 -6.8; 442 -6.7; 486 -6.7; 535 -6.6; 588 -6.5; 647 -6.3; 712 -6.1; 783 -5.8; 861 -5.6; 947 -5.6; 1042 -5.9; 1146 -6.7; 1261 -7.4; 1387 -7.9; 1526 -7.7; 1678 -7.1; 1846 -6.4; 2031 -5.6; 2234 -4.8; 2457 -4.1; 2703 -3.5; 2973 -3.6; 3270 -4.0; 3597 -3.8; 3957 -3.3; 4353 -2.8; 4788 -3.1; 5267 -4.9; 5793 -6.6; 6373 -5.2; 7010 -5.8; 7711 -7.9; 8482 -6.4; 9330 -5.8; 10263 -5.8; 11289 -5.8; 12418 -5.8; 13660 -5.8; 15026 -5.8; 16529 -5.8; 18182 -9.6; 20000 -12.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`InEar PhoPhile-8 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `InEar PhoPhile-8 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 24 Hz   | 1.14 | 5.1 dB  |
| Peaking | 50 Hz   | 1.84 | 2.0 dB  |
| Peaking | 1470 Hz | 2.35 | -2.4 dB |
| Peaking | 2761 Hz | 2.19 | 2.5 dB  |
| Peaking | 4381 Hz | 4.14 | 3.1 dB  |
| Peaking | 55 Hz   | 2.96 | -0.6 dB |
| Peaking | 72 Hz   | 0.88 | 2.0 dB  |
| Peaking | 136 Hz  | 0.27 | -1.6 dB |
| Peaking | 899 Hz  | 2.76 | 1.0 dB  |
| Peaking | 7788 Hz | 7.62 | -2.4 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 4.6 dB  |
| Peaking | 62 Hz    | 1.41 | 1.6 dB  |
| Peaking | 125 Hz   | 1.41 | -0.6 dB |
| Peaking | 250 Hz   | 1.41 | -1.2 dB |
| Peaking | 500 Hz   | 1.41 | -0.4 dB |
| Peaking | 1000 Hz  | 1.41 | -0.5 dB |
| Peaking | 2000 Hz  | 1.41 | -0.6 dB |
| Peaking | 4000 Hz  | 1.41 | 3.3 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.3 dB |
| Peaking | 16000 Hz | 1.41 | -0.7 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/InEar%20PhoPhile-8/InEar%20PhoPhile-8.png)
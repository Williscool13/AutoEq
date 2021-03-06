# Stax SR-Gamma Pro
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -1.2; 66 -2.7; 72 -3.3; 79 -4.0; 87 -4.9; 96 -6.1; 106 -6.6; 116 -7.1; 128 -7.6; 141 -7.7; 155 -7.7; 170 -7.6; 187 -7.7; 206 -7.6; 227 -7.3; 249 -7.0; 274 -6.6; 302 -6.2; 332 -6.0; 365 -5.8; 402 -5.9; 442 -5.7; 486 -5.8; 535 -5.9; 588 -5.7; 647 -5.6; 712 -5.8; 783 -5.8; 861 -6.1; 947 -6.3; 1042 -6.6; 1146 -6.8; 1261 -7.4; 1387 -8.1; 1526 -8.7; 1678 -9.0; 1846 -8.9; 2031 -7.8; 2234 -6.5; 2457 -4.2; 2703 -3.0; 2973 -2.5; 3270 -2.6; 3597 -2.7; 3957 -2.3; 4353 -3.8; 4788 -4.7; 5267 -6.2; 5793 -7.7; 6373 -8.6; 7010 -7.3; 7711 -7.2; 8482 -10.0; 9330 -11.4; 10263 -7.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -7.0; 20000 -10.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Stax SR-Gamma Pro GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-Gamma Pro ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.2dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 35 Hz   | 0.89 | 7.1 dB  |
| Peaking | 1803 Hz | 1.23 | -8.8 dB |
| Peaking | 2643 Hz | 0.56 | 7.7 dB  |
| Peaking | 5993 Hz | 2.43 | -4.4 dB |
| Peaking | 9100 Hz | 4.24 | -6.2 dB |
| Peaking | 35 Hz   | 1.44 | -6.1 dB |
| Peaking | 41 Hz   | 0.43 | 5.6 dB  |
| Peaking | 124 Hz  | 0.66 | -4.0 dB |
| Peaking | 380 Hz  | 1.1  | 1.0 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.6 dB  |
| Peaking | 62 Hz    | 1.41 | 4.1 dB  |
| Peaking | 125 Hz   | 1.41 | -2.2 dB |
| Peaking | 250 Hz   | 1.41 | -0.5 dB |
| Peaking | 500 Hz   | 1.41 | 1.3 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.4 dB |
| Peaking | 2000 Hz  | 1.41 | -1.7 dB |
| Peaking | 4000 Hz  | 1.41 | 5.1 dB  |
| Peaking | 8000 Hz  | 1.41 | -3.9 dB |
| Peaking | 16000 Hz | 1.41 | 0.2 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-Gamma%20Pro/Stax%20SR-Gamma%20Pro.png)
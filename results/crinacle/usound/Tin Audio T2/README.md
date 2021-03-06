# Tin Audio T2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.7; 45 -1.1; 49 -1.5; 54 -2.1; 60 -2.6; 66 -3.1; 72 -3.6; 79 -4.2; 87 -4.7; 96 -5.3; 106 -6.0; 116 -6.5; 128 -7.0; 141 -7.4; 155 -7.8; 170 -8.2; 187 -8.5; 206 -8.7; 227 -8.9; 249 -9.0; 274 -9.1; 302 -9.2; 332 -9.2; 365 -9.1; 402 -9.0; 442 -8.9; 486 -8.7; 535 -8.5; 588 -8.2; 647 -7.8; 712 -7.3; 783 -6.7; 861 -6.2; 947 -5.6; 1042 -5.7; 1146 -6.2; 1261 -6.5; 1387 -6.6; 1526 -6.2; 1678 -5.6; 1846 -5.1; 2031 -5.0; 2234 -5.4; 2457 -6.3; 2703 -7.1; 2973 -6.3; 3270 -4.7; 3597 -3.9; 3957 -4.4; 4353 -4.3; 4788 -5.3; 5267 -4.5; 5793 -1.2; 6373 -1.0; 7010 -4.0; 7711 -8.0; 8482 -7.7; 9330 -6.5; 10263 -6.5; 11289 -7.8; 12418 -10.7; 13660 -11.3; 15026 -11.9; 16529 -10.3; 18182 -8.9; 20000 -11.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Tin Audio T2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Tin Audio T2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.5dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 30 Hz    | 0.5  | 6.5 dB  |
| Peaking | 259 Hz   | 0.67 | -3.2 dB |
| Peaking | 3752 Hz  | 2.62 | 2.4 dB  |
| Peaking | 6147 Hz  | 4.36 | 6.6 dB  |
| Peaking | 15180 Hz | 0.9  | -5.4 dB |
| Peaking | 973 Hz   | 5.03 | 1.6 dB  |
| Peaking | 1986 Hz  | 3.09 | 1.7 dB  |
| Peaking | 2723 Hz  | 5.9  | -1.6 dB |
| Peaking | 8002 Hz  | 9.59 | -2.8 dB |
| Peaking | 10237 Hz | 4.38 | 1.9 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.9 dB  |
| Peaking | 62 Hz    | 1.41 | 3.0 dB  |
| Peaking | 125 Hz   | 1.41 | -0.7 dB |
| Peaking | 250 Hz   | 1.41 | -2.6 dB |
| Peaking | 500 Hz   | 1.41 | -2.1 dB |
| Peaking | 1000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 4000 Hz  | 1.41 | 2.5 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.9 dB  |
| Peaking | 16000 Hz | 1.41 | -6.8 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Tin%20Audio%20T2/Tin%20Audio%20T2.png)
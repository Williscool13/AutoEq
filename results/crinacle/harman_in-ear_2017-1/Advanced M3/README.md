# Advanced M3
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -13.7; 23 -13.7; 25 -13.8; 28 -13.8; 31 -13.9; 34 -13.9; 37 -14.0; 41 -14.0; 45 -14.1; 49 -14.1; 54 -14.2; 60 -14.3; 66 -14.4; 72 -14.5; 79 -14.6; 87 -14.7; 96 -14.9; 106 -15.0; 116 -15.0; 128 -14.9; 141 -14.8; 155 -14.6; 170 -14.3; 187 -14.0; 206 -13.6; 227 -13.1; 249 -12.6; 274 -12.0; 302 -11.4; 332 -10.6; 365 -9.9; 402 -9.2; 442 -8.5; 486 -7.8; 535 -7.1; 588 -6.3; 647 -5.6; 712 -4.8; 783 -4.0; 861 -3.4; 947 -3.1; 1042 -3.3; 1146 -3.5; 1261 -3.9; 1387 -3.9; 1526 -3.6; 1678 -3.4; 1846 -3.2; 2031 -3.0; 2234 -3.0; 2457 -3.2; 2703 -3.2; 2973 -2.5; 3270 -1.8; 3597 -1.7; 3957 -2.6; 4353 -4.3; 4788 -4.3; 5267 -1.4; 5793 -0.5; 6373 -1.0; 7010 -3.9; 7711 -6.2; 8482 -6.6; 9330 -7.9; 10263 -6.7; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -14.0; 16529 -22.0; 18182 -24.0; 20000 -19.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Advanced M3 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Advanced M3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.1dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 10 Hz    | 1.47 | -6.7 dB  |
| Peaking | 33 Hz    | 0.25 | -6.1 dB  |
| Peaking | 204 Hz   | 0.44 | -6.9 dB  |
| Peaking | 3299 Hz  | 0.09 | 4.5 dB   |
| Peaking | 18174 Hz | 0.75 | -21.3 dB |
| Peaking | 865 Hz   | 4.77 | 1.1 dB   |
| Peaking | 6087 Hz  | 3.58 | 5.0 dB   |
| Peaking | 7872 Hz  | 2.62 | -1.0 dB  |
| Peaking | 13225 Hz | 0.44 | -4.3 dB  |
| Peaking | 13238 Hz | 1.76 | 8.5 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -7.5 dB  |
| Peaking | 62 Hz    | 1.41 | -5.6 dB  |
| Peaking | 125 Hz   | 1.41 | -7.1 dB  |
| Peaking | 250 Hz   | 1.41 | -5.3 dB  |
| Peaking | 500 Hz   | 1.41 | -0.4 dB  |
| Peaking | 1000 Hz  | 1.41 | 3.3 dB   |
| Peaking | 2000 Hz  | 1.41 | 2.2 dB   |
| Peaking | 4000 Hz  | 1.41 | 4.1 dB   |
| Peaking | 8000 Hz  | 1.41 | 2.7 dB   |
| Peaking | 16000 Hz | 1.41 | -15.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Advanced%20M3/Advanced%20M3.png)
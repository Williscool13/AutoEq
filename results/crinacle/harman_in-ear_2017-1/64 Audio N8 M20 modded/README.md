# 64 Audio N8 M20 modded
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -10.7; 23 -10.6; 25 -10.4; 28 -10.2; 31 -9.9; 34 -9.5; 37 -9.2; 41 -8.9; 45 -8.6; 49 -8.5; 54 -8.2; 60 -7.9; 66 -7.8; 72 -7.8; 79 -7.8; 87 -7.9; 96 -8.1; 106 -8.2; 116 -8.4; 128 -8.5; 141 -8.8; 155 -8.8; 170 -9.0; 187 -9.2; 206 -9.4; 227 -9.5; 249 -9.5; 274 -9.6; 302 -9.7; 332 -9.5; 365 -9.4; 402 -9.3; 442 -9.3; 486 -9.1; 535 -8.8; 588 -8.6; 647 -8.3; 712 -7.9; 783 -7.6; 861 -7.2; 947 -7.2; 1042 -7.4; 1146 -8.1; 1261 -8.8; 1387 -9.3; 1526 -9.4; 1678 -9.2; 1846 -8.8; 2031 -8.0; 2234 -6.7; 2457 -5.1; 2703 -3.5; 2973 -2.3; 3270 -1.5; 3597 -1.5; 3957 -2.2; 4353 -3.0; 4788 -3.9; 5267 -1.6; 5793 -0.5; 6373 -1.0; 7010 -3.9; 7711 -6.2; 8482 -6.4; 9330 -7.6; 10263 -7.4; 11289 -6.5; 12418 -7.5; 13660 -16.9; 15026 -24.9; 16529 -29.1; 18182 -30.6; 20000 -24.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`64 Audio N8 M20 modded GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `64 Audio N8 M20 modded ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.3dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 23 Hz    | 0.99 | -4.1 dB  |
| Peaking | 555 Hz   | 0.17 | -2.9 dB  |
| Peaking | 5744 Hz  | 0.57 | 13.9 dB  |
| Peaking | 11992 Hz | 1.97 | 12.9 dB  |
| Peaking | 17251 Hz | 0.28 | -26.9 dB |
| Peaking | 941 Hz   | 0.92 | 6.8 dB   |
| Peaking | 1389 Hz  | 0.49 | -6.5 dB  |
| Peaking | 3042 Hz  | 1.45 | 5.4 dB   |
| Peaking | 4827 Hz  | 3.83 | -3.6 dB  |
| Peaking | 5784 Hz  | 3.5  | 2.5 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -4.0 dB  |
| Peaking | 62 Hz    | 1.41 | -0.3 dB  |
| Peaking | 125 Hz   | 1.41 | -1.4 dB  |
| Peaking | 250 Hz   | 1.41 | -2.8 dB  |
| Peaking | 500 Hz   | 1.41 | -1.9 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.8 dB  |
| Peaking | 2000 Hz  | 1.41 | -2.3 dB  |
| Peaking | 4000 Hz  | 1.41 | 6.2 dB   |
| Peaking | 8000 Hz  | 1.41 | 6.4 dB   |
| Peaking | 16000 Hz | 1.41 | -29.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/64%20Audio%20N8%20M20%20modded/64%20Audio%20N8%20M20%20modded.png)
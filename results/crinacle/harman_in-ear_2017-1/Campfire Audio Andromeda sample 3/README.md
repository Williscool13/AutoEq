# Campfire Audio Andromeda sample 3
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.1; 23 -7.3; 25 -7.6; 28 -7.8; 31 -8.1; 34 -8.2; 37 -8.4; 41 -8.5; 45 -8.7; 49 -8.9; 54 -9.1; 60 -9.3; 66 -9.6; 72 -9.9; 79 -10.2; 87 -10.6; 96 -11.0; 106 -11.4; 116 -11.8; 128 -12.0; 141 -12.3; 155 -12.4; 170 -12.5; 187 -12.6; 206 -12.6; 227 -12.6; 249 -12.4; 274 -12.2; 302 -12.0; 332 -11.6; 365 -11.2; 402 -10.8; 442 -10.5; 486 -10.0; 535 -9.4; 588 -8.9; 647 -8.2; 712 -7.5; 783 -6.8; 861 -6.2; 947 -5.9; 1042 -5.9; 1146 -6.1; 1261 -6.4; 1387 -6.4; 1526 -6.0; 1678 -5.5; 1846 -4.8; 2031 -3.5; 2234 -1.6; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -1.0; 5267 -0.5; 5793 -0.5; 6373 -2.4; 7010 -4.3; 7711 -6.2; 8482 -6.5; 9330 -7.2; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -15.5; 15026 -26.4; 16529 -30.4; 18182 -26.8; 20000 -17.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Campfire Audio Andromeda sample 3 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Campfire Audio Andromeda sample 3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.8dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 62 Hz    | 0.29 | -0.8 dB  |
| Peaking | 212 Hz   | 0.41 | -5.8 dB  |
| Peaking | 8554 Hz  | 0.25 | 7.3 dB   |
| Peaking | 9074 Hz  | 0.25 | 8.9 dB   |
| Peaking | 16456 Hz | 0.52 | -36.1 dB |
| Peaking | 1610 Hz  | 1.58 | -5.5 dB  |
| Peaking | 1830 Hz  | 0.77 | 3.5 dB   |
| Peaking | 8095 Hz  | 2.55 | -3.7 dB  |
| Peaking | 12516 Hz | 2.72 | 6.7 dB   |
| Peaking | 14672 Hz | 3.49 | -5.7 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -1.1 dB  |
| Peaking | 62 Hz    | 1.41 | -2.0 dB  |
| Peaking | 125 Hz   | 1.41 | -4.6 dB  |
| Peaking | 250 Hz   | 1.41 | -5.3 dB  |
| Peaking | 500 Hz   | 1.41 | -2.4 dB  |
| Peaking | 1000 Hz  | 1.41 | 0.2 dB   |
| Peaking | 2000 Hz  | 1.41 | 2.1 dB   |
| Peaking | 4000 Hz  | 1.41 | 7.3 dB   |
| Peaking | 8000 Hz  | 1.41 | 5.3 dB   |
| Peaking | 16000 Hz | 1.41 | -27.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Campfire%20Audio%20Andromeda%20sample%203/Campfire%20Audio%20Andromeda%20sample%203.png)
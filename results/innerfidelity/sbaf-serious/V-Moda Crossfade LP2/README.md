# V-Moda Crossfade LP2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -9.6; 23 -9.9; 25 -10.2; 28 -10.4; 31 -10.7; 34 -10.9; 37 -11.0; 41 -11.2; 45 -11.4; 49 -11.5; 54 -11.6; 60 -11.6; 66 -11.5; 72 -11.6; 79 -12.0; 87 -12.6; 96 -13.3; 106 -13.7; 116 -14.1; 128 -14.3; 141 -14.5; 155 -14.4; 170 -14.1; 187 -13.9; 206 -13.4; 227 -12.3; 249 -11.5; 274 -10.3; 302 -9.0; 332 -7.6; 365 -6.2; 402 -5.1; 442 -4.2; 486 -4.0; 535 -4.1; 588 -4.4; 647 -5.5; 712 -7.0; 783 -7.8; 861 -8.5; 947 -8.7; 1042 -8.8; 1146 -8.8; 1261 -8.6; 1387 -9.2; 1526 -8.8; 1678 -7.9; 1846 -6.3; 2031 -3.3; 2234 -3.9; 2457 -3.8; 2703 -4.0; 2973 -7.3; 3270 -10.5; 3597 -8.5; 3957 -5.0; 4353 -3.2; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.7; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`V-Moda Crossfade LP2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `V-Moda Crossfade LP2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.3dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 43 Hz   | 0.52 | -4.5 dB |
| Peaking | 125 Hz  | 1.39 | -5.9 dB |
| Peaking | 203 Hz  | 2.37 | -4.7 dB |
| Peaking | 2252 Hz | 5.58 | 3.1 dB  |
| Peaking | 5510 Hz | 2.83 | 7.1 dB  |
| Peaking | 510 Hz  | 1.36 | 6.7 dB  |
| Peaking | 1237 Hz | 0.3  | -4.8 dB |
| Peaking | 2781 Hz | 1.01 | 6.5 dB  |
| Peaking | 3280 Hz | 4.41 | -7.9 dB |
| Peaking | 4614 Hz | 7.79 | 2.4 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -4.0 dB |
| Peaking | 62 Hz    | 1.41 | -3.1 dB |
| Peaking | 125 Hz   | 1.41 | -7.4 dB |
| Peaking | 250 Hz   | 1.41 | -4.7 dB |
| Peaking | 500 Hz   | 1.41 | 4.9 dB  |
| Peaking | 1000 Hz  | 1.41 | -4.1 dB |
| Peaking | 2000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 4000 Hz  | 1.41 | 2.0 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.9 dB  |
| Peaking | 16000 Hz | 1.41 | -0.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/V-Moda%20Crossfade%20LP2/V-Moda%20Crossfade%20LP2.png)
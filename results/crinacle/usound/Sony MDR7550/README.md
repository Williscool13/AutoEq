# Sony MDR7550
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.7; 23 -1.1; 25 -1.4; 28 -1.9; 31 -2.2; 34 -2.5; 37 -2.7; 41 -3.0; 45 -3.3; 49 -3.6; 54 -3.8; 60 -4.2; 66 -4.5; 72 -4.9; 79 -5.4; 87 -5.9; 96 -6.3; 106 -6.8; 116 -7.3; 128 -7.6; 141 -7.9; 155 -8.4; 170 -8.6; 187 -8.8; 206 -8.9; 227 -9.0; 249 -9.1; 274 -9.1; 302 -9.1; 332 -9.1; 365 -9.0; 402 -8.9; 442 -8.7; 486 -8.5; 535 -8.3; 588 -8.0; 647 -7.6; 712 -7.1; 783 -6.6; 861 -6.8; 947 -6.8; 1042 -6.7; 1146 -7.2; 1261 -7.7; 1387 -8.1; 1526 -8.4; 1678 -8.3; 1846 -7.8; 2031 -6.8; 2234 -5.5; 2457 -3.9; 2703 -2.3; 2973 -0.8; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.6; 4788 -3.1; 5267 -8.5; 5793 -8.9; 6373 -4.2; 7010 -4.0; 7711 -6.8; 8482 -7.4; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR7550 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR7550 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 18 Hz   | 0.59 | 5.9 dB  |
| Peaking | 56 Hz   | 1.02 | 1.5 dB  |
| Peaking | 254 Hz  | 0.58 | -2.9 dB |
| Peaking | 1667 Hz | 2.41 | -2.7 dB |
| Peaking | 3405 Hz | 1.79 | 7.1 dB  |
| Peaking | 470 Hz  | 4.77 | -0.4 dB |
| Peaking | 4510 Hz | 5.46 | 3.5 dB  |
| Peaking | 5527 Hz | 4.66 | -6.4 dB |
| Peaking | 6626 Hz | 4.67 | 4.1 dB  |
| Peaking | 8061 Hz | 5.39 | -2.1 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 5.1 dB  |
| Peaking | 62 Hz    | 1.41 | 1.6 dB  |
| Peaking | 125 Hz   | 1.41 | -1.1 dB |
| Peaking | 250 Hz   | 1.41 | -2.6 dB |
| Peaking | 500 Hz   | 1.41 | -1.4 dB |
| Peaking | 1000 Hz  | 1.41 | -0.3 dB |
| Peaking | 2000 Hz  | 1.41 | -1.1 dB |
| Peaking | 4000 Hz  | 1.41 | 6.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.5 dB |
| Peaking | 16000 Hz | 1.41 | 0.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Sony%20MDR7550/Sony%20MDR7550.png)
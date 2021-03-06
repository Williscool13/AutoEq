# Cypher Labs Astru IEM
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.9; 31 -1.3; 34 -1.8; 37 -2.2; 41 -2.7; 45 -3.1; 49 -3.5; 54 -4.0; 60 -4.5; 66 -5.0; 72 -5.5; 79 -6.0; 87 -6.5; 96 -7.0; 106 -7.3; 116 -7.6; 128 -8.0; 141 -8.2; 155 -8.5; 170 -8.6; 187 -8.6; 206 -8.6; 227 -8.5; 249 -8.4; 274 -8.2; 302 -8.0; 332 -7.7; 365 -7.4; 402 -7.1; 442 -6.6; 486 -6.3; 535 -6.0; 588 -5.2; 647 -4.9; 712 -4.7; 783 -4.3; 861 -4.4; 947 -4.6; 1042 -4.9; 1146 -5.2; 1261 -5.7; 1387 -6.5; 1526 -7.5; 1678 -8.5; 1846 -9.4; 2031 -10.0; 2234 -9.7; 2457 -7.8; 2703 -7.0; 2973 -5.4; 3270 -3.8; 3597 -4.1; 3957 -6.7; 4353 -8.8; 4788 -6.6; 5267 -5.8; 5793 -5.3; 6373 -2.6; 7010 -4.4; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Cypher Labs Astru IEM GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Cypher Labs Astru IEM ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 26 Hz   | 1.15 | 6.4 dB  |
| Peaking | 879 Hz  | 1.97 | 2.6 dB  |
| Peaking | 2024 Hz | 2.44 | -3.9 dB |
| Peaking | 3319 Hz | 5.96 | 3.7 dB  |
| Peaking | 6357 Hz | 6.46 | 4.3 dB  |
| Peaking | 55 Hz   | 1.57 | 1.5 dB  |
| Peaking | 188 Hz  | 0.68 | -2.4 dB |
| Peaking | 602 Hz  | 2.34 | 1.1 dB  |
| Peaking | 4097 Hz | 2.58 | 1.5 dB  |
| Peaking | 4264 Hz | 6.46 | -4.3 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.1 dB  |
| Peaking | 62 Hz    | 1.41 | 1.0 dB  |
| Peaking | 125 Hz   | 1.41 | -1.7 dB |
| Peaking | 250 Hz   | 1.41 | -2.2 dB |
| Peaking | 500 Hz   | 1.41 | 0.6 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.8 dB  |
| Peaking | 2000 Hz  | 1.41 | -3.6 dB |
| Peaking | 4000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.9 dB  |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Cypher%20Labs%20Astru%20IEM/Cypher%20Labs%20Astru%20IEM.png)
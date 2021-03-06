# Monster Beats Lady Gaga HeartBeats
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.6; 37 -1.0; 41 -1.5; 45 -2.0; 49 -2.5; 54 -2.9; 60 -3.3; 66 -3.5; 72 -3.7; 79 -3.8; 87 -3.9; 96 -4.2; 106 -4.2; 116 -4.1; 128 -3.9; 141 -4.2; 155 -4.6; 170 -4.8; 187 -4.9; 206 -5.1; 227 -5.2; 249 -5.3; 274 -5.5; 302 -5.5; 332 -5.6; 365 -5.9; 402 -5.7; 442 -5.5; 486 -5.5; 535 -5.5; 588 -5.5; 647 -5.5; 712 -5.5; 783 -5.5; 861 -5.5; 947 -5.5; 1042 -5.8; 1146 -5.8; 1261 -6.1; 1387 -6.7; 1526 -7.4; 1678 -8.3; 1846 -9.4; 2031 -10.8; 2234 -12.4; 2457 -14.3; 2703 -15.6; 2973 -15.0; 3270 -13.1; 3597 -11.3; 3957 -10.0; 4353 -8.9; 4788 -7.7; 5267 -6.2; 5793 -4.3; 6373 -2.3; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Monster Beats Lady Gaga HeartBeats GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Monster Beats Lady Gaga HeartBeats ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.3dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 26 Hz   | 0.58 | 6.2 dB  |
| Peaking | 137 Hz  | 0.88 | 1.5 dB  |
| Peaking | 1060 Hz | 0.57 | 1.6 dB  |
| Peaking | 2730 Hz | 1.52 | -9.9 dB |
| Peaking | 6351 Hz | 3.77 | 5.4 dB  |
| Peaking | 7783 Hz | 8.68 | -0.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.7 dB  |
| Peaking | 62 Hz    | 1.41 | 1.6 dB  |
| Peaking | 125 Hz   | 1.41 | 1.9 dB  |
| Peaking | 250 Hz   | 1.41 | 0.7 dB  |
| Peaking | 500 Hz   | 1.41 | 0.4 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.6 dB  |
| Peaking | 2000 Hz  | 1.41 | -5.6 dB |
| Peaking | 4000 Hz  | 1.41 | -3.8 dB |
| Peaking | 8000 Hz  | 1.41 | 2.8 dB  |
| Peaking | 16000 Hz | 1.41 | -0.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Monster%20Beats%20Lady%20Gaga%20HeartBeats/Monster%20Beats%20Lady%20Gaga%20HeartBeats.png)
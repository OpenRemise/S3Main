# S3Main

[![license](https://img.shields.io/github/license/OpenRemise/S3Main)](https://github.com/OpenRemise/S3Main/raw/master/LICENSE)

<a href="https://openremise.at">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/OpenRemise/.github/raw/master/data/icons/icon_dark.svg">
  <img src="https://github.com/OpenRemise/.github/raw/master/data/icons/icon_light.svg" width="20%" align="right">
</picture>
</a>

Minimum IC pad distance:
green, blue, purple and red -> 0.19mm
white and black -> 0.22mm

PCB Style Guide
https://www.pcblibraries.com/forum/metric-pcb-design-tips_topic3103.html

## TPS281C100x
| ILIM1 | ILIM0 | RILIM | ICL [A] |
| ----- | ----- | ----- | ------- |
| 0     | 0     | ∞     | 0.5     |
| 0     | 1     | 39000 | 1.27    |
| 1     | 0     | 18700 | 2.72    |
| 1     | 1     | 12640 | 4.11    |

| OL_ON | Load [A] | Sense ratio | ISNS [mA] | RSNS | VSNS [V] | % of 1V ADC |
| ----- | -------- | ----------- | --------- | ---- | -------- | ----------- |
| 0     | 4        | 800         | 5         | 180  | 0.9      | 90          |
| 1     | 0.004    | 24          | 0.167     | 180  | 0.03     | 3           |
---
layout: default
title: Tuning and Calibration Overview
has_children: true
nav_order: 8
---

# Tuning and Calibration Overview
{: .no_toc}

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## General Resources
- Minimal 3DP's Basic Klipper Configuration Checks Procedure
	- [Klipper Basic Configuration Checks - Google Sheets](https://docs.google.com/spreadsheets/d/1CwccwL21RJTX0NQu1DDUu3yGtK1RVByJQGIV45AjyNA/edit?gid=0#gid=0)
- Minimal 3DP's Klipper Calibrations Spreadsheet
	- [Klipper Calibrations - Google Sheets](https://docs.google.com/spreadsheets/d/1LlSHsa86RuT_btswmDsmQp0LrTJ9U0HJcRhorsqz1ug/edit?gid=1017893331#gid=1017893331)
	- This is extremely useful to dial in your hot end (e.g. if you're not using a Voron Revo, you're using something odd like the Bambu X1C Hotend, etc)
	- In particular:
		- Orca Slicer Flow Calibration
		- Orca Slicer Flow Calibration YOLO
		- Pressure Advance
		- PA & Orca Slicer
		- Max Volumetric Speed
		- Extrusion Rate Smoothing (ERS)
	- Nice to have:
		- Run Current
			- *particularly if using the BTT SKR Mini E3 V3.0 which can handle higher currents than the Einsey RAMbo...*
		- Skew Correction
- OrcaSlicer's Calibration Info: [Calibration · SoftFever/OrcaSlicer Wiki · GitHub](https://github.com/SoftFever/OrcaSlicer/wiki/Calibration)
- 

## Miscellaneous Notes
- Ella suggests that if using SKR Mini, motor currents can increase over the values provided for the slower Rambo board.  See Run Current above.
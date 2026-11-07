# Atomic Absorption Spectroscopy and the Standard Addition Method

An interactive learning module for students on atomic absorption spectroscopy (AAS).

**▶ Open the module: https://sunitathyagarajan.github.io/AAS-standard-addition/**

The module is a single static web page, so it needs no installation or build step. It works on phones as well as desktops, in light and dark mode.

## What the module covers

1. **Basic concepts:** the instrument, atomization, and the Beer–Lambert law.
2. **Applications:** examples from materials chemistry and medicine.
3. **AAS vs UV-Vis vs emission:** what kinds of species each technique detects.
4. **Effect of temperature:** Boltzmann populations, flame temperatures and graphite-furnace programs.
5. **Interferences:** spectral, chemical, ionization and physical interferences, and background correction.
6. **Line width:** natural, Doppler and pressure broadening, and why the lamp's line width matters.
7. **Standard addition:** a simulator and two solved examples from the literature (chromium and manganese).
8. **Quiz:** nine questions to check understanding.

Every chapter has interactive plots, calculators or simulators. Students can change values and see the results update.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The module. This is the page GitHub Pages serves. |
| `aas-module.html` | An earlier copy of the module, kept for reference. Make future changes in `index.html`. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are, without processing them with Jekyll. |

## Using it offline

Download or clone the repository and open `index.html` in any modern browser. Everything works offline. The only exception is the JetBrains Mono font, which loads from Google Fonts; without an internet connection the page uses a system monospace font instead.

## Publishing

GitHub Pages serves this repository from the `main` branch, root folder (**Settings → Pages**). Any change pushed to `index.html` on `main` appears on the live site within a minute or two.

## Sources

The two solved standard-addition examples are adapted from problems in D. Harvey, [*Analytical Chemistry 2.1*, Chapter 10 Problems](https://chem.libretexts.org/Bookshelves/Analytical_Chemistry/Analytical_Chemistry_2.1_(Harvey)/10%3A_Spectroscopic_Methods/10.09%3A_Problems) (LibreTexts). The full reference list is at the end of the module.

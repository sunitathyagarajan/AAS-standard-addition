# Atomic Absorption Spectroscopy and the Standard Addition Method

An interactive learning module for students on atomic absorption spectroscopy (AAS). It is a single static page (`index.html`) with no build step, so it runs directly on GitHub Pages.

## Contents

1. **Basic concepts:** the instrument, atomization, and the Beer–Lambert law.
2. **Applications:** materials chemistry and medicine.
3. **AAS vs UV-Vis vs emission:** what kinds of species each technique detects.
4. **Effect of temperature:** Boltzmann populations, flame and furnace programs.
5. **Interferences:** spectral, chemical, ionization, physical, and background correction.
6. **Line width:** natural, Doppler and pressure broadening.
7. **Standard addition:** a simulator and two solved examples from the literature (Cr and Mn).
8. **Quiz.**

Every chapter has interactive plots, calculators or simulators. The page works on phones as well as desktops, in light and dark mode.

## Publishing on GitHub Pages

1. Push this folder to a GitHub repository (`index.html` must be at the top level).
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and click **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

The empty `.nojekyll` file tells GitHub Pages to serve the files as they are, without running Jekyll.

## Running locally

Open `index.html` in any modern browser. No server or internet connection is needed, except for the JetBrains Mono font, which loads from Google Fonts and falls back to a system monospace font when offline.

## Sources

The solved examples are adapted from problems in D. Harvey, *Analytical Chemistry 2.1*, Chapter 10 (LibreTexts). The full reference list is at the end of the module.

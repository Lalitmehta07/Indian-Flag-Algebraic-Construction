# 🇮🇳 Indian National Flag: A 1:1 Scale Algebraic Reconstruction
### Author: Lalit Mehta 

This repository contains a rigorous mathematical reconstruction of the National Flag of India, built entirely using coordinate geometry and algebraic inequalities.

## 🎯 The Challenge
The goal of this project was to create a 100% mathematically accurate, 1:1 scale map of the Tiranga based on official [Wiktionary Construction Sheets](https://share.google/D3BIv8rEwy68VGjF5). 

**Constraint:** The project was built using strictly algebraic logic. The Desmos `polygon` function was avoided during the construction phase and was only introduced as a final presentation layer to resolve hardware rendering limitations.

## 🛠️ Technical Details
- **Scale:** 1:1 (900-unit global width, 3:2 aspect ratio).
- **Ashoka Chakra:** 24 spokes generated via nested lists.
- **Symmetry:** Used inverse trigonometric offsets ($\arcsin$) to ensure constant chord lengths for spokes at various radii.
- **The Rendering Paradox:** Specifically addressed the "Infinite Slope" issue at 90° and 270° where standard inequalities fail to render solid regions.

## 🔗 Live Project
- **Interactive Website:** [View the Report](https://Lalitmehta07.github.io/Try/)
- **Algebraic Workspace:** [Explore on Desmos](https://www.desmos.com/calculator/wa6z9xyvln)

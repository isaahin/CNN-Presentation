# Convolutional Neural Networks
### A Beamer Presentation

> *How Machines Learn to See*

---

## Authors

| Name | Student ID |
|------|-----------|
| Arjo Kar | 2205031 |
| Lamisa Zahin | 2205046 |
| Zannatun Nayeem Ohee | 2205059 |

**Institution:** Bangladesh University of Engineering and Technology  
**Date:** February 2026

---

## About This Presentation

A visual, story-driven introduction to **Convolutional Neural Networks (CNNs)** built entirely in LaTeX using the Beamer framework and TikZ graphics — no PowerPoint, no external design tools.

### Topics Covered

- The motivation behind CNNs (the X-ray story)
- How computers see images vs. how humans do
- Why normal neural networks fail on images
- CNN building blocks: Conv Layer, ReLU, Pooling, FC Layer
- Step-by-step convolution walkthrough (Sobel-X kernel)
- Max pooling step-by-step
- A full CNN forward pass demo on a handwritten digit
- Real-world impact and limitations of CNNs

---

## File Structure

```
cnn-presentation/
│
├── main.tex                  # Main LaTeX source file
│
├── images/
│   ├── 01_Input_Image/
│   │   ├── 01_input_clean.png
│   │   └── 01_input_values.png
│   ├── 02_Conv1_Filters_and_Outputs/
│   │   ├── 00_filter_horizontal_values.png
│   │   ├── 00_filter_vertical_values.png
│   │   ├── 00_filter_corner_values.png
│   │   ├── 02_conv_horizontal_out_values.png
│   │   ├── 02_conv_vertical_out_values.png
│   │   └── 02_conv_corner_out_values.png
│   ├── 03_ReLU1/
│   │   ├── 03_relu_horizontal_values.png
│   │   ├── 03_relu_vertical_values.png
│   │   └── 03_relu_corner_values.png
│   ├── 04_Merged_Features/
│   │   └── 04_merged_relu_features_values.png
│   ├── 05_MaxPooling/
│   │   └── 05_maxpool_values.png
│   └── 06_Flatten/
│       └── 06_flatten_values.png
│
├── cnn_presentation.pdf      # Compiled output (ready to present)
└── README.md                 # This file
```

---

## How to Compile

### Requirements

Make sure you have a full LaTeX distribution installed:

- **Windows:** [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/)
- **macOS:** [MacTeX](https://tug.org/mactex/)
- **Linux:** `sudo apt install texlive-full`

### Required LaTeX Packages

| Package | Purpose |
|---------|---------|
| `beamer` | Presentation framework |
| `tikz` | All diagrams and visuals |
| `pgfplots` | Charts and graphs |
| `fontawesome5` | Icons |
| `amsmath` | Math equations |
| `xcolor` | Custom color palette |
| `booktabs` | Tables |

### Compile Command

```bash
pdflatex main.tex
pdflatex main.tex
```

> Run **twice** — the second pass resolves cross-references and frame numbers correctly.

### Using Overleaf (Recommended — no installation needed)

1. Go to [overleaf.com](https://overleaf.com) and create a free account
2. Click **New Project** → **Upload Project**
3. Zip the entire folder and upload
4. Click **Recompile**

---

## Design Notes

- **Color palette:** custom navy (`#0D3B66`), sky blue (`#2D9CDB`), amber (`#F2A900`)
- All visuals are drawn in **pure TikZ** — no external diagram tools
- The presentation uses **Beamer overlays** (`\only<n>`) for step-by-step reveals
- Aspect ratio: **16:9**

---

## License

This project was created for academic/educational purposes at BUET.  
Feel free to use or adapt with attribution.

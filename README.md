# 🧠 Convolutional Neural Networks
### *How Machines Learn to See*

> A fully hand-crafted **LaTeX Beamer** presentation — every diagram, every animation, every visual built from scratch using pure TikZ. No PowerPoint. No Canva. Just code.

---

## 📋 Course Information

| | |
|---|---|
| **Course** | CSE 200 — Technical Writing and Presentation |
| **Level & Term** | L2-T2 |
| **Institution** | Bangladesh University of Engineering and Technology (BUET) |
| **Date** | February 2026 |

---

## 👥 Authors & Contributions

This presentation was split into three parts, each owned and built by one author:

### 🔷 Arjo Kar — `2205031`
**Part 1: The Story & The Problem**
- The CNN origin story (the X-ray analogy)
- Human vision vs. computer vision
- Why normal neural networks fail on images (3 core problems)
- How CNN solves all three problems
- Building blocks overview

### 🔶 Lamisa Zahin — `2205046`
**Part 2: The Convolution Layer (Deep Dive)**
- What is convolution? (1D math → 2D CNN)
- Kernels explained — Blur, Sobel-X, Identity
- Full 9-step convolution walkthrough
- The feature map result
- ReLU activation — definition, graph, applied example
- Pooling layer — concept, math, 4-step walkthrough
- Fully connected layer
- Putting it all together — the full CNN pipeline

### 🟢 Zannatun Nayeem Ohee — `2205059`
**Part 3: CNN In Action & Real World**
- Live CNN demo — forward pass on a handwritten digit
- Input image → Conv filters → ReLU → Merge → Pooling → Flatten → FC → Softmax
- Real-world impact (Healthcare, Autonomous Vehicles, Agriculture)
- CNN adoption growth over time (charts)
- Limitations of CNNs

---

## 📁 File Structure

```
CNN-Presentation/
│
├── main.tex                        # Full LaTeX source
├── CNN.pdf            # Compiled presentation (ready to present)
├── README.md                       # This file
│
└── images/
    ├── 01_Input_Image/
    │   ├── 01_input_clean.png
    │   └── 01_input_values.png
    ├── 02_Conv1_Filters_and_Outputs/
    │   ├── 00_filter_horizontal_values.png
    │   ├── 00_filter_vertical_values.png
    │   ├── 00_filter_corner_values.png
    │   ├── 02_conv_horizontal_out_values.png
    │   ├── 02_conv_vertical_out_values.png
    │   └── 02_conv_corner_out_values.png
    ├── 03_ReLU1/
    │   ├── 03_relu_horizontal_values.png
    │   ├── 03_relu_vertical_values.png
    │   └── 03_relu_corner_values.png
    ├── 04_Merged_Features/
    │   └── 04_merged_relu_features_values.png
    ├── 05_MaxPooling/
    │   └── 05_maxpool_values.png
    └── 06_Flatten/
        └── 06_flatten_values.png
```

---

## 🛠️ How to Compile

### Option A — Overleaf *(easiest, no installation)*
1. Go to [overleaf.com](https://overleaf.com) → **New Project** → **Upload Project**
2. Zip the entire folder and upload it
3. Click **Recompile** — done

### Option B — Local LaTeX

**Install a LaTeX distribution:**
| OS | Distribution |
|----|-------------|
| Windows | [MiKTeX](https://miktex.org/) |
| macOS | [MacTeX](https://tug.org/mactex/) |
| Linux | `sudo apt install texlive-full` |

**Compile:**
```bash
pdflatex main.tex
pdflatex main.tex
```
> Run **twice** — second pass fixes frame numbers and cross-references.

### Required Packages
`beamer` · `tikz` · `pgfplots` · `fontawesome5` · `amsmath` · `xcolor` · `booktabs`

---

## 🎨 Design

- **Color palette:** navy `#0D3B66` · sky blue `#2D9CDB` · amber `#F2A900` · ice `#F4F8FC`
- **Aspect ratio:** 16:9
- All visuals drawn in **pure TikZ** — no external tools
- Step-by-step **Beamer overlays** for animated reveals
- Custom header, footer, and bullet styles throughout

---

## 📄 License

Created for academic purposes at BUET — CSE 200, L2-T2.  
Free to use and adapt with attribution.
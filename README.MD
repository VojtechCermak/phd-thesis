# PhD Thesis

This repository contains the PDF of my dissertation thesis, which explores automated animal identification using computer vision and machine learning. 

## 📖 Abstract
Identifying individual animals is crucial for wildlife research and conservation, enabling
tracking, behavior analysis, and population monitoring. However, traditional animal
identification methods, such as tagging and manual inspection, are labor-intensive and
impractical for large-scale studies. Automating this process using machine learning has
become essential with the increasing availability of large datasets from camera traps and
citizen science. This thesis explores animal identification as a computer vision problem,
addressing key challenges such as reliance on fine-grained features, class imbalance, envi-
ronmental variability, and limited data availability. The goal of this work is to improve
automated identification methods, making them more accurate, scalable, and robust for
real-world applications.

A key contribution is the WildlifeDatasets library, an open-source toolkit for ac-
cessing animal identification datasets, alongside WildlifeTools, a suite of methods and
tools designed to enhance research replicability and transparency. We also introduce
the SeaTurtleID dataset, which includes timestamps and spans a long duration. Using
this dataset, we demonstrate the importance of realistic training and evaluation splits to
prevent data leakage and ensure unbiased evaluation. Additionally, we present MegaDe-
scriptor, a foundational deep learning model for animal identification that works across
multiple species and outperforms existing methods. Finally, we propose WildFusion, a
hybrid approach that integrates local feature matching with deep learning through cali-
brated similarity fusion, improving both accuracy and computational efficiency.

## Thesis PDF
You can find the full thesis here:  
[Download Thesis](./phd_thesis.pdf)

## Related Papers
The thesis is based on the following papers:
``` ```
- **[SeaTurtleID2022:
A long-span dataset for reliable sea turtle re-identification](https://arxiv.org/pdf/2211.10307)**
- **[WildlifeDatasets: An open-
source toolkit for animal re-identification](https://arxiv.org/pdf/2311.09118)**
- **[WildFusion: Individual
Animal Identification with Calibrated Similarity Fusion](https://arxiv.org/pdf/2408.12934)**


## Citation
If you find this work useful, please cite it as:

```
@phdthesis{Cermak2025,
  author      = {Vojtech Cermák},
  title       = {Fine-grained recognition of animals in the wild},
  school      = {Czech Technical University in Prague, Faculty of Electrical Engineering, Department of Cybernetics},
  year        = {2025},
  type        = {PhD thesis},
}
```


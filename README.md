## 🚀 Overview
This project leverages Unsupervised Representation Learning to model "normality" and detect deviations (anomalies).

## 🧠 Key Algorithms Used:
- PaDiM (Patch Distribution Modeling): A framework that models the distribution of patches to encapsulate both global and local semantic information.
- PatchCore: A state-of-the-art method that utilizes a memory bank of "mid-level" features to detect anomalies, offering superior robustness and inference speed.


## 🛠️ Technical Stack
- Framework: PyTorch / Anomalib
- Dataset: MVTec AD 
- Metrics: Image-level AUROC (Area Under ROC Curve) and F1-Score.

## 📋 Experimental Results
Below are the performance metrics (Image-level AUROC and F1-Score) across various industrial categories. These results highlight the effectiveness of PatchCore in handling complex textures (like Grid) and small structural defects (like Screw).

### Bottle
**Padim**
[{'image_AUROC': 0.8511903882026672, 'image_F1Score': 0.8536585569381714}]

### Grid
**Padim**
[{'image_AUROC': 0.6468532085418701, 'image_F1Score': 0.8395061492919922}]

**Patchcore**
[{'image_AUROC': 0.8449883460998535, 'image_F1Score': 0.8809523582458496}]

### Cable
**Padim**
[{'image_AUROC': 0.7765517234802246, 'image_F1Score': 0.8426966071128845}]

**Patchcore**
[{'image_AUROC': 0.8422988057136536, 'image_F1Score': 0.8426966071128845}]

### Capsule
**Padim**
[{'image_AUROC': 0.8541666269302368, 'image_F1Score': 0.9142857193946838}]

### Carpet
**Padim**
[{'image_AUROC': 0.8704600930213928, 'image_F1Score': 0.8709677457809448}]

### Leather
**Padim**
[{'image_AUROC': 0.8805443644523621, 'image_F1Score': 0.8676470518112183}]

### Metal Nut
**Padim**
[{'image_AUROC': 0.9192789793014526, 'image_F1Score': 0.913385808467865}]

### Pill
**Padim**
[{'image_AUROC': 0.692765935287476, 'image_F1Score': 0.9080459475517273}]

### Screw
**Padim**
[{'image_AUROC': 0.6702380776405334, 'image_F1Score': 0.8888888955116272}]

**Patchcore**
[{'image_AUROC': 0.8559523224830627, 'image_F1Score': 0.8639053106307983}]

### Tile
**Padim**
[{'image_AUROC': 0.7517447471618652, 'image_F1Score': 0.8479999899864197}]

**Patchcore**
[{'image_AUROC': 0.8025922179222107, 'image_F1Score': 0.7647058963775635}]

### ToothBrush
**Padim**
[{'image_AUROC': 0.8730158805847168, 'image_F1Score': 0.8936170339584351}]

### Wood
**Padim**
[{'image_AUROC': 0.8075000047683716, 'image_F1Score': 0.8461538553237915}]

### Zipper
**Padim**
[{'image_AUROC': 0.7808388471603394, 'image_F1Score': 0.89570552110672}]

**Patchcore**
[{'image_AUROC': 0.8787006139755249, 'image_F1Score': 0.910179615020752}]

### Hazelnut
**Padim**
[{'image_AUROC': 0.7622727155685425, 'image_F1Score': 0.8527131676673889}]

**Patchcore**
[{'image_AUROC': 0.846818208694458, 'image_F1Score': 0.8503937125205994}]

### Transistor
**Padim**
[{'image_AUROC': 0.6793332695960999, 'image_F1Score': 0.7519999742507935}]

**Patchcore**
[{'image_AUROC': 0.7833333015441895, 'image_F1Score': 0.7680000066757202}]

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

![bottle1](Result/bottle/bottle1.png)
![bottle2](Result/bottle/bottle2.png)
![bottle3](Result/bottle/bottle3.png)
![bottle4](Result/bottle/bottle4.png)
![bottle5](Result/bottle/bottle5.png)

### Grid
**Padim**
[{'image_AUROC': 0.6468532085418701, 'image_F1Score': 0.8395061492919922}]

**Patchcore**
[{'image_AUROC': 0.8449883460998535, 'image_F1Score': 0.8809523582458496}]

![grid1](Result/grid/grid1.png)
![grid2](Result/grid/grid2.png)
![grid3](Result/grid/grid3.png)
![grid4](Result/grid/grid4.png)
![grid5](Result/grid/grid5.png)

### Cable
**Padim**
[{'image_AUROC': 0.7765517234802246, 'image_F1Score': 0.8426966071128845}]

**Patchcore**
[{'image_AUROC': 0.8422988057136536, 'image_F1Score': 0.8426966071128845}]

![cable1](Result/cable/cable1.png)
![cable2](Result/cable/cable2.png)
![cable3](Result/cable/cable3.png)
![cable4](Result/cable/cable4.png)
![cable5](Result/cable/cable5.png)

### Capsule
**Padim**
[{'image_AUROC': 0.8541666269302368, 'image_F1Score': 0.9142857193946838}]

![capsule1](Result/capsule/capsule1.png)
![capsule2](Result/capsule/capsule2.png)
![capsule3](Result/capsule/capsule3.png)
![capsule4](Result/capsule/capsule4.png)
![capsule5](Result/capsule/capsule5.png)

### Carpet
**Padim**
[{'image_AUROC': 0.8704600930213928, 'image_F1Score': 0.8709677457809448}]

![carpet1](Result/carpet/carpet1.png)
![carpet2](Result/carpet/carpet2.png)
![carpet3](Result/carpet/carpet3.png)
![carpet4](Result/carpet/carpet4.png)
![carpet5](Result/carpet/carpet5.png)

### Leather
**Padim**
[{'image_AUROC': 0.8805443644523621, 'image_F1Score': 0.8676470518112183}]

![leather1](Result/leather/leather1.png)
![leather2](Result/leather/leather2.png)
![leather3](Result/leather/leather3.png)
![leather4](Result/leather/leather4.png)
![leather5](Result/leather/leather5.png)

### Metal Nut
**Padim**
[{'image_AUROC': 0.9192789793014526, 'image_F1Score': 0.913385808467865}]

![metal_nut1](Result/metal_nut/metal_nut1.png)
![metal_nut2](Result/metal_nut/metal_nut2.png)
![metal_nut3](Result/metal_nut/metal_nut3.png)
![metal_nut4](Result/metal_nut/metal_nut4.png)
![metal_nut5](Result/metal_nut/metal_nut5.png)

### Pill
**Padim**
[{'image_AUROC': 0.692765935287476, 'image_F1Score': 0.9080459475517273}]

![pill1](Result/pill/pill1.png)
![pill2](Result/pill/pill2.png)
![pill3](Result/pill/pill3.png)
![pill4](Result/pill/pill4.png)
![pill5](Result/pill/pill5.png)

### Screw
**Padim**
[{'image_AUROC': 0.6702380776405334, 'image_F1Score': 0.8888888955116272}]

**Patchcore**
[{'image_AUROC': 0.8559523224830627, 'image_F1Score': 0.8639053106307983}]

![screw1](Result/screw/screw1.png)
![screw2](Result/screw/screw2.png)
![screw3](Result/screw/screw3.png)
![screw4](Result/screw/screw4.png)
![screw5](Result/screw/screw5.png)

### Tile
**Padim**
[{'image_AUROC': 0.7517447471618652, 'image_F1Score': 0.8479999899864197}]

**Patchcore**
[{'image_AUROC': 0.8025922179222107, 'image_F1Score': 0.7647058963775635}]

![tile1](Result/tile/tile1.png)
![tile2](Result/tile/tile2.png)
![tile3](Result/tile/tile3.png)
![tile4](Result/tile/tile4.png)
![tile5](Result/tile/tile5.png)

### ToothBrush
**Padim**
[{'image_AUROC': 0.8730158805847168, 'image_F1Score': 0.8936170339584351}]

![toothbrush1](Result/toothbrush/toothbrush1.png)
![toothbrush2](Result/toothbrush/toothbrush2.png)
![toothbrush3](Result/toothbrush/toothbrush3.png)
![toothbrush4](Result/toothbrush/toothbrush4.png)
![toothbrush5](Result/toothbrush/toothbrush5.png)

### Wood
**Padim**
[{'image_AUROC': 0.8075000047683716, 'image_F1Score': 0.8461538553237915}]

![wood1](Result/wood/wood1.png)
![wood2](Result/wood/wood2.png)
![wood3](Result/wood/wood3.png)
![wood4](Result/wood/wood4.png)
![wood5](Result/wood/wood5.png)

### Zipper
**Padim**
[{'image_AUROC': 0.7808388471603394, 'image_F1Score': 0.89570552110672}]

**Patchcore**
[{'image_AUROC': 0.8787006139755249, 'image_F1Score': 0.910179615020752}]

![zipper1](Result/zipper/zipper1.png)
![zipper2](Result/zipper/zipper2.png)
![zipper3](Result/zipper/zipper3.png)
![zipper4](Result/zipper/zipper4.png)
![zipper5](Result/zipper/zipper5.png)

### Hazelnut
**Padim**
[{'image_AUROC': 0.7622727155685425, 'image_F1Score': 0.8527131676673889}]

**Patchcore**
[{'image_AUROC': 0.846818208694458, 'image_F1Score': 0.8503937125205994}]

![hazelnut1](Result/hazelnut/hazelnut1.png)
![hazelnut2](Result/hazelnut/hazelnut2.png)
![hazelnut3](Result/hazelnut/hazelnut3.png)
![hazelnut4](Result/hazelnut/hazelnut4.png)
![hazelnut5](Result/hazelnut/hazelnut5.png)

### Transistor
**Padim**
[{'image_AUROC': 0.6793332695960999, 'image_F1Score': 0.7519999742507935}]

**Patchcore**
[{'image_AUROC': 0.7833333015441895, 'image_F1Score': 0.7680000066757202}]

# Image_

### Bottle
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 52/52 0:00:18 • 0:00:00 2.94it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8511903882026672     │
│       image_F1Score       │    0.8536585569381714     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.8511903882026672, 'image_F1Score': 0.8536585569381714}]

### Grid
#### Padim
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 50/50 0:00:17 • 0:00:00 2.86it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.6468532085418701     │
│       image_F1Score       │    0.8395061492919922     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.6468532085418701, 'image_F1Score': 0.8395061492919922}]

#### Patchcore
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8449883460998535     │
│       image_F1Score       │    0.8809523582458496     │
└───────────────────────────┴───────────────────────────┘

[{'image_AUROC': 0.8449883460998535, 'image_F1Score': 0.8809523582458496}]

### Cable
#### Padim
INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 104/104 0:00:44 • 0:00:00 2.40it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.7765517234802246     │
│       image_F1Score       │    0.8426966071128845     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.7765517234802246, 'image_F1Score': 0.8426966071128845}]

#### Patchcore
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8422988057136536     │
│       image_F1Score       │    0.8426966071128845     │
└───────────────────────────┴───────────────────────────┘

[{'image_AUROC': 0.8422988057136536, 'image_F1Score': 0.8426966071128845}]

### Capsule
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78/78 0:00:34 • 0:00:00 2.29it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8541666269302368     │
│       image_F1Score       │    0.9142857193946838     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.8541666269302368, 'image_F1Score': 0.9142857193946838}]

### Carpet
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 73/73 0:00:28 • 0:00:00 2.63it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8704600930213928     │
│       image_F1Score       │    0.8709677457809448     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.8704600930213928, 'image_F1Score': 0.8709677457809448}]

### Leather
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78/78 0:00:30 • 0:00:00 2.55it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8805443644523621     │
│       image_F1Score       │    0.8676470518112183     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.8805443644523621, 'image_F1Score': 0.8676470518112183}]

### Metal Nut
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 69/69 0:00:25 • 0:00:00 2.75it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.9192789793014526     │
│       image_F1Score       │     0.913385808467865     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.9192789793014526, 'image_F1Score': 0.913385808467865}]

### Pills
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 97/97 0:00:38 • 0:00:00 2.59it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.6927655935287476     │
│       image_F1Score       │    0.9080459475517273     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.6927655935287476, 'image_F1Score': 0.9080459475517273}]

### Screw
#### Padim
INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 101/101 0:00:35 • 0:00:00 2.90it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.6702380776405334     │
│       image_F1Score       │    0.8888888955116272     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.6702380776405334, 'image_F1Score': 0.8888888955116272}]

#### Patchcore
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8559523224830627     │
│       image_F1Score       │    0.8639053106307983     │
└───────────────────────────┴───────────────────────────┘

[{'image_AUROC': 0.8559523224830627, 'image_F1Score': 0.8639053106307983}]

### Tile
#### Padim
 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
Testing ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 76/76 0:00:28 • 0:00:00 2.71it/s  

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric AUROC was called before the ``update`` method which may lead to errors, as metric states have not yet been 
updated.
  warnings.warn(*args, **kwargs)

/usr/local/lib/python3.12/dist-packages/torchmetrics/utilities/prints.py:43: UserWarning: The ``compute`` method of
metric F1Score was called before the ``update`` method which may lead to errors, as metric states have not yet been
updated.
  warnings.warn(*args, **kwargs)

┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.7517447471618652     │
│       image_F1Score       │    0.8479999899864197     │
└───────────────────────────┴───────────────────────────┘


[{'image_AUROC': 0.7517447471618652, 'image_F1Score': 0.8479999899864197}]


#### Patchcore

 INFO:lightning_fabric.utilities.rank_zero:The following callbacks returned in `LightningModule.configure_callbacks` will override existing callbacks passed to Trainer: Evaluator, ImageVisualizer, PostProcessor, PreProcessor
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃        Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│        image_AUROC        │    0.8025922179222107     │
│       image_F1Score       │    0.7647058963775635     │
└───────────────────────────┴───────────────────────────┘

[{'image_AUROC': 0.8025922179222107, 'image_F1Score': 0.7647058963775635}]


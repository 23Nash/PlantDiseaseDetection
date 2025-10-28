============================================================
TRAINING COMPLETE - SUMMARY
============================================================

Configuration:
Device: cuda
Testing Mode: True
Epochs: 2
Batch Size: 64

Dataset:
Total samples: 6148
Number of classes: 39
Train samples: 3657
Validation samples: 1568
Test samples: 923

Accuracy:
Train Accuracy: 0.9229 (92.29%)
Validation Accuracy: 0.8807 (88.07%)
Test Accuracy: 0.9003 (90.03%)

# Model saved to: plant_disease_model_1.pt

...

1. Set TESTING_MODE = False in the configuration cell
2. Re-run all cells for full training
3. # Full training will take 4-7 hours on CPU or 15-40 min on GPU

============================================================
TRAINING COMPLETE - SUMMARY
============================================================

Configuration:
Device: cuda
Testing Mode: False
Epochs: 5
Batch Size: 64

Dataset:
Total samples: 61486
Number of classes: 39
Train samples: 36584
Validation samples: 15679
Test samples: 9223

Accuracy:
Train Accuracy: 0.8977 (89.77%)
Validation Accuracy: 0.8646 (86.46%)
Test Accuracy: 0.8661 (86.61%)

# Model saved to: plant_disease_model_1.pt

...
✓ Full training complete!

1. Use the saved model for predictions
2. # Consider transfer learning with VGG16 for better accuracy

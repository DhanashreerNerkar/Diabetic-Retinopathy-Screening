metabolic health (a diabetes complication) using images.
3,662 retinal images, cleaned to 3,530. SHA-256 pixel hashing removed 124 duplicates and 8 images with conflicting labels.
The train/test split was checked for leakage.
5-fold cross-validation over 6 model setups, 30 training runs in all. MobileNetV2 transfer learning won with a mean AUC of 0.9879.
On the held-out test set: 0.988 ROC-AUC, 98% sensitivity, with 7 missed DR cases out of 347.

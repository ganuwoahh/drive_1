# Retinal Vessel Segmentation

This project explores retinal blood vessel segmentation using a UNet while preserving vessel continuity

-> Implemented a UNet for binary vessel segmentation (vessel vs background)

-> Trained on patches instead of full images to better learn thin vessel structures

-> Used a combined Dice + clDice loss to improve vessel connectivity

-> Applied test-time augmentation at inference for more stable predictions

Results:

Dice: 0.7822

IoU: 0.6425

Sensitivity: 0.7602

Specificity: 0.9826


<img width="950" height="315" alt="v5" src="https://github.com/user-attachments/assets/de2e6e34-8b53-464b-83a2-c551bdeb4a2a" />

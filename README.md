### transfer_learning.ipynb

Performs below:
- Model fine-tuning for region cuisine classification
- Code has been altered multiple times to accommodate different versions of the model including:
   - Different versions of EfficientNet
   - Varying hyperparameters
   - Freezing

### CS5787_DL_final_project_feature_identification.ipynb

Performs below:
- Grad-CAM to generate heatmaps to analyze the parts of the images the model’s paying attention to
- PCA -> UMAP pipeline for clustering to evaluate the cluster separation
- TCAV to analyze which concept (i.e., noodles, rice, steak, tomato, spice) contributes as the positive signal for either classes

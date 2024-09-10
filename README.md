# master_tfm_code

Este es el repositorio que contiene todos los notebooks de código empleados en el Trabajo de Fin de Máster *Modelos generativos de difusión aplicados al ámbito de imagen médica*.

El reposirtio lo estructramos de la siguiente manera:
1. Entrenamiento de los DDPMs: notebooks `ddpm2D_melanoma_isic.ipynb`, `ddpm2D_bingn_isic.ipynb` y `ddpm2D_hand_meednist.ipynb`, que contienen el código para el entrenamiento de los modelos de difusión generativos considerados.
2. Entrenamiento de los extractores de características del FID: `unet_segmentation_training_isic2016.ipynb`, `skinlesnet_classification_training_isic.ipynb` y `resnet50_classification_training_isic.ipynb`, que muestra el entrenamiento de las distintas redes que a posteriori se usarán como extractores de características par el cálculo del FID.
3. Métricas de evaluación de calidad de las imágenes generadas por el modelo de difusión: `ssim_fid_malignant_generated.ipynb`, `ssim_fid_benign_generated.ipynb` y `classification_accuracy_score.ipynb`, que muestran el cálculo de las distintas métricas de evaluación de la calidad de las imágenes generadas consideradas en este trabajo.

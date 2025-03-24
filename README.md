## Débruitage d'Images avec OpenCV

##  Description du projet
Ce projet explore différentes techniques de débruitage d’images en utilisant OpenCV et Python. L'objectif est d'améliorer la qualité d'une image bruitée en appliquant divers filtres et d'évaluer leur efficacité à l'aide des métriques PSNR et SSIM.

## 🛠️ Technologies utilisées
- Python
- OpenCV
- NumPy
- Matplotlib
- skimage

## Contenu du projet
1. **Chargement et prétraitement de l'image**
   - Lecture d'une image en niveaux de gris
   - Ajout de bruit Speckle simulé
2. **Application des filtres de débruitage**
   - Filtre bilatéral (`cv2.bilateralFilter`)
   - Filtre avancé (`cv2.fastNlMeansDenoising`)
   - Filtre médian (`cv2.medianBlur`)
3. **Comparaison des résultats**
   - Évaluation de la qualité de l’image débruitée avec **PSNR** et **SSIM**
   - Comparaison visuelle des images

##  Résultats et Analyse
- **PSNR (Peak Signal-to-Noise Ratio)** : Plus il est élevé, meilleure est la qualité de l’image débruitée.
- **SSIM (Structural Similarity Index)** : Plus il est proche de 1, plus l’image restaurée est fidèle à l’originale.

##  Exécution du projet
### Installation des dépendances
```bash
pip install opencv-python numpy matplotlib scikit-image
```
### Lancer le script
```bash
python main.py
```

## Aperçu
Avant / Après débruitage avec différents filtres.

## Licence
Ce projet est sous licence MIT 


# Image Background / Blur / Name Uniqueness Notebooks

This repository contains three Jupyter notebooks for image background classification, image sharpness/blur analysis, and name uniqueness scoring.

Files
- [blur_image.ipynb](blur_image.ipynb)
- [name_uniqueness.ipynb](name_uniqueness.ipynb)
- [uniform_background.ipynb](uniform_background.ipynb)

Quick overview
- blur_image.ipynb — feature extraction and classifiers for blur detection. Key symbol: [`blur_image.get_features`](blur_image.ipynb).
- uniform_background.ipynb — dataset loading, MobileNetV2-based classifier, inference pipeline. Key symbols: [`uniform_background.load_images_from_folder`](uniform_background.ipynb), [`uniform_background.display_samples`](uniform_background.ipynb), [`uniform_background.predict_image_label`](uniform_background.ipynb).
- name_uniqueness.ipynb — compute name frequency and uniqueness score; save results to CSV. Key symbols: [`name_uniqueness.preprocess_data`](name_uniqueness.ipynb), [`name_uniqueness.calculate_scores`](name_uniqueness.ipynb), [`name_uniqueness.save_scores`](name_uniqueness.ipynb).

Dependencies
Install the required Python packages before running:
```bash
pip install numpy pandas matplotlib scikit-learn opencv-python tensorflow tqdm
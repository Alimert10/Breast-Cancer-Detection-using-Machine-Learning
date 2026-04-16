# Breast Cancer Detection using Machine Learning

## Despre Proiect
Acest proiect foloseste tehnici de invatare automata pentru a clasifica tumorile mamare in doua categorii: benigne sau maligne. Proiectul a fost dezvoltat in **Python** si utilizeaza setul de date public **Breast Cancer Wisconsin (Diagnostic)**.

## Etapele Proiectului
* **Preprocesarea Datelor**: Curatarea setului de date, gestionarea valorilor lipsa si scalarea caracteristicilor (Feature Scaling) pentru a imbunatati performanta modelelor.
* **Analiza si Vizualizare**: Utilizarea tehnicii **PCA (Principal Component Analysis)** pentru reducerea dimensionalitatii si vizualizarea distributiei datelor in spatiu bidimensional.
* **Modelare**: Implementarea si antrenarea a trei algoritmi de clasificare diferiti:
    * **Logistic Regression**
    * **Gaussian Naive Bayes**
    * **Support Vector Machine (SVM)**
* **Evaluare**: Compararea modelelor folosind metrici standard de performanta: acuratete, matricea de confuzie si raportul de clasificare.

## Rezultate
Proiectul analizeaza eficienta fiecarui algoritm in detectia precoce a cancerului, evidentiind modelul cu cea mai mare precizie si cea mai mica rata de erori de tip "False Negative", esentiale in domeniul medical.

## Tehnologii Utilizate
* **Limbaj**: Python
* **Biblioteci**: 
    * **Pandas & NumPy**: Pentru manipularea datelor.
    * **Scikit-learn**: Pentru implementarea modelelor de ML si preprocesare.
    * **Matplotlib & Seaborn**: Pentru generarea graficelor si vizualizarea PCA.
* **Mediu de lucru**: Jupyter Notebook.

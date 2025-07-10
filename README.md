# 🤖 RPA Challenge - Automatisation du remplissage de formulaire

Projet d’automatisation du site [rpachallenge.com](https://rpachallenge.com/) !  (Input form)
Ce script Python utilise Selenium pour remplir automatiquement un formulaire web à partir d’un fichier Excel.  
---

## 🚀 Fonctionnalités

- 📄 Lecture des données depuis un fichier Excel
- 🌐 Remplissage automatique du formulaire web
- 🖱️ Simulation d’un comportement humain via un navigateur Chrome
- ✅ Suivi de l’état de chaque soumission dans le fichier Excel

---

## 🛠️ Prérequis

- Python 3.x
- Google Chrome installé
- [ChromeDriver](https://chromedriver.chromium.org/) compatible (géré automatiquement)
- Les packages Python suivants :
  - `selenium`
  - `openpyxl`
  - `webdriver-manager`
  - `pyautogui`

```
pip install -r requirements.txt
```

---

## ⚡ Utilisation

1. Placer le `challenge.xlsx` dans le dossier du script.
2. Lancer le script :
   ```
   python rpa_challenge.py
   ```
3. Laisser le script s'exécuter : il ouvre Chrome, remplit le formulaire et soumet chaque ligne.
---

## 📝 Remarques

- Le dossier `CFT driver` (Chrome portable) et `.venv` sont ignorés du dépôt.
- Le script fonctionne en mode “humain” : il ouvre un vrai navigateur et simule la saisie.

---

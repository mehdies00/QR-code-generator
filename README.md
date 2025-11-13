

# Générateur de QR Code en Python

Ce mini-projet est un outil en ligne de commande simple, écrit en Python, pour créer rapidement des codes QR.
Il prend en entrée une chaîne de caractères (comme une URL ou du texte) et génère une image de QR code correspondante.

## ✨ Fonctionnalités

* Générer un QR code à partir de n'importe quel texte ou URL.
* Sauvegarder le QR code généré en tant que fichier image (format PNG).
* Facile à utiliser et à modifier.

## ⚙️ Prérequis

Avant de commencer, assurez-vous d'avoir installé :

* [Python 3](https://www.python.org/downloads/) (version 3.6 ou supérieure)
* `pip` (généralement inclus avec Python)

## 🚀 Installation

1. Clonez ce dépôt sur votre machine locale (ou téléchargez les fichiers) :

   ```bash
   git clone https://github.com/VOTRE_NOM/NOM_DU_REPO.git
   cd NOM_DU_REPO
   ```

2. Installez les dépendances nécessaires avec `requirements.txt` :

   ```bash
   py -m pip install -r requirements.txt
   ```

   *(Si vous n'avez pas de fichier `requirements.txt`, créez-le et ajoutez-y la ligne `qrcode[pil]`)*

## 📌 Usage

Pour utiliser le script, exécutez-le depuis votre terminal en fournissant les données que vous souhaitez encoder.

### Syntaxe :

```bash
py main.py "Vos données ici" nom_du_fichier_sortie
```

* `"Vos données ici"` : Le texte ou l'URL à transformer en QR code.
* `nom_du_fichier_sortie` : Le nom que vous souhaitez donner à votre image (sans `.png`).

### Exemple :

Créer un QR code pour Google et le sauvegarder sous `google_qr.png` :

```bash
py main.py "https://www.google.com" "google_qr"
```

Un fichier nommé **google_qr.png** sera créé dans le même dossier.

## 📄 Licence

Ce projet est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus de détails.

---

### ✅ Conseil

Créez un fichier `requirements.txt` contenant cette ligne :

```
qrcode[pil]
```

---

Si tu veux, je peux aussi t’aider à générer le fichier **main.py** complet pour ton projet QR Code.


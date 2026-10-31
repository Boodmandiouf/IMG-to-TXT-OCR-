# 📄 ImageText — Extracteur de texte OCR

ImageText est une petite application web qui permet d'extraire le texte présent dans une ou plusieurs images et captures d'écran grâce à la reconnaissance optique de caractères (OCR).

L'application s'ouvre directement dans un navigateur : **aucune installation de Python ni de Tesseract sur l'ordinateur n'est nécessaire**.

## ✨ Fonctionnalités

- Importer une ou plusieurs images.
- Ajouter des images par glisser-déposer.
- Extraire le texte avec Tesseract.js.
- Choisir la langue de reconnaissance : français, anglais, allemand, espagnol ou italien.
- Afficher le résultat de chaque image.
- Copier les résultats ou les exporter dans un fichier `.txt`.

## 🚀 Utilisation

1. Téléchargez `ImageText_Windows_sans_terminal.html` depuis le dépôt.
2. Ouvrez le fichier avec un navigateur récent.
3. Ajoutez vos images ou faites-les glisser dans la zone prévue.
4. Choisissez la langue de reconnaissance.
5. Cliquez sur **Extraire le texte**.
6. Copiez le résultat ou téléchargez-le au format `.txt`.

Aucune installation de Python ou de Tesseract n'est requise.

## 🧰 Technologies

- HTML
- CSS
- JavaScript
- [Tesseract.js](https://github.com/naptha/tesseract.js), moteur OCR exécuté dans le navigateur

## 🔐 Confidentialité et connexion Internet

La reconnaissance est effectuée dans le navigateur : les images sélectionnées ne sont pas envoyées à un serveur applicatif par le code de l'application.

**Une connexion Internet est toutefois nécessaire** pour charger Tesseract.js et les données linguistiques depuis le CDN lors de l'utilisation. Le moteur et les fichiers de langue ne sont pas inclus dans le fichier HTML.

## 🖼️ Formats d'image

Les formats pris en charge dépendent du navigateur et de Tesseract.js. Les formats courants tels que PNG, JPG/JPEG, WEBP et BMP sont adaptés. La prise en charge de TIFF peut varier.

## ⚠️ Limites connues

La qualité de l'extraction dépend de la résolution, du contraste, de l'orientation et de la lisibilité de l'image.

Les icônes, logos et éléments graphiques peuvent être interprétés à tort comme des lettres ou des chiffres. Les résultats OCR peuvent donc nécessiter une relecture.

## 📁 Contenu du dépôt

```text
ImageText/
├── README.md
├── LICENSE
└── ImageText_Windows_sans_terminal.html
```

## 📜 Licence

Ce projet est distribué sous licence MIT. Consultez le fichier [LICENSE](LICENSE).

---

**ImageText — Extraire le texte d'une image simplement.**

# BotClick - Bot Dofus

Un bot automatisé pour Dofus utilisant la reconnaissance d'image, de texte pour la résolution automatique des chasses aux trésors.

## Prérequis

### Tesseract OCR

Téléchargez et installez Tesseract OCR depuis:
https://github.com/tesseract-ocr/tesseract/releases

> Par défaut: `C:\Program Files\Tesseract-OCR`

### Python 3.12+

Assurez-vous d'avoir Python 3.12 ou une version plus récente installée.(pas compatible python 3.13)

### Configuration de Dofus

1. Assurez-vous que Dofus est configuré avec :
   - Échelle d'interface : 100%
   - Taille des textes : Grand
   - Interface en français
   - Thème : Brakmar Red (recommandé pour la détection)
   - Module Chasse -> Opacité des bandes noir -> Fort
   - Sort pour 1 cible uniquement sur la position "3" des sorts
   - Ne rien mettre en position "3" dans les objets
   - Potion de rappel (au moin 10) en position "2" dans les objets
   - Hectaupe en compagnon, assurez vous d'avoir le sort "Vol'Hante" en position "3" (par defaut)
   - Chasse a gauche, en bas du nom d'alliance, ne pas dépasser des bandes noirs de la chasse
   - Map en bas a droite, ne pas dépasser des bandes noirs de la chasse
   - Zaap a mettre en favori : Sufokia
   - Module a désactiver -> QUETE/ALTERATIONS
   - Preferable -> Monture
   - Combat -> Adapter la taille de la timeline
   - Notification -> Notifications interne -> tout désactiver
   - Aller au Nord/Sud/Ouest/Est : F5/F6/F7/F8

### Configuration système

1. Résolution d'écran : 1920x1080
2. Windows 10/11 (testé sur)
3. Clavier en disposition française (AZERTY)

## Fonctionnalités

- Résolution automatique des chasses aux trésors
- Navigation automatique via les zaaps et /travel
- Gestion des erreurs et tentatives de récupération

## Utilisation

1. Lancez Dofus et connectez-vous à votre personnage
2. Exécutez le script principal:

```bash
nadrojbot.exe
```

## Notes importantes

- Le bot utilise des coordonnées absolues pour certaines actions, assurez-vous que votre interface Dofus est correctement positionnée
- La détection d'images et de texte peut nécessiter des ajustements selon votre configuration

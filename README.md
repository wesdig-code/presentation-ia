# L'IA, sans avoir peur

Présentation HTML autonome pour expliquer l'intelligence artificielle à de **grands débutants**, sur un ton chaleureux et rassurant. Pensée pour être commentée à l'oral, à côté du public, avec des exemples testables en direct.

## Aperçu

- **Format :** un seul fichier HTML autonome (`presentation-ia.html`), ouvrable dans n'importe quel navigateur.
- **Scène :** 16:9 (1920×1080), mise à l'échelle automatiquement.
- **Style :** « Daisy Days » — couleurs pastel, grosses polices ludiques (Fredoka One + Quicksand), ombres dures, peu de texte par slide.
- **Langue :** français.

## Utilisation

Ouvrez simplement le fichier dans un navigateur :

```bash
# Linux
xdg-open presentation-ia.html

# macOS
open presentation-ia.html
```

Passez en plein écran (`F11`) pour la projection.

### Raccourcis clavier

| Touche | Action |
|--------|--------|
| `→` `↓` `Espace` `PageDown` | Slide suivante |
| `←` `↑` `PageUp` | Slide précédente |
| `Home` | Première slide |
| `E` | Activer / désactiver le mode édition |
| `Ctrl/Cmd + S` | Sauvegarder les modifications |

## Structure du dépôt

```
.
├── presentation-ia.html   # La présentation (autonome)
├── docs/                   # Specs & notes de conception
└── README.md
```

## Personnalisation

Les couleurs, polices et l'animation sont centralisées dans les variables CSS `:root` en haut du fichier `presentation-ia.html` — modifiez-les pour changer tout le look.

---

Auteur : fmorin

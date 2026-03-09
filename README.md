# MALM Data — Données linguistiques mooré

> Datasets du projet **MALM** (Mooré Acquisition Language Model)  
> Langue : mooré (moore) · Burkina Faso

## Fichiers

| Fichier | Contenu | Entrées |
|---------|---------|---------|
| `lexicon.json` | Dictionnaire mooré ↔ français ↔ anglais | 10 258 |
| `medical.json` | Terminologie médicale mooré | 1 841 |
| `proverbs_COMPLETE_v1.json` | Proverbes mooré ↔ français | 676 |
| `grammar.json` | Grammaire : 33 règles, 71 classificateurs, paradigmes | — |

## Sources

- **SRC-17** — Dictionnaire Mooré ↔ Français ↔ Anglais (2020, 368 pages) — source principale
- **SRC-11** — NIKIEMA N., *Studies in African Linguistics* 18(2), 1987
- **SRC-13** — Peace Corps Burkina Faso, *Introduction to Moore Language*, 2006
- **SRC-04/SRC-19** — Dictionnaires médicaux mooré-français-anglais (2020)
- **SRC-07** — Manuel de santé communautaire *Kibarã Karensaamba* (ANTBA/SIL, 2007)
- **SRC-21** — KABORE F.O., *Morphological Analyzer for Mooré* (Uppsala University, 2025)

## Structure des entrées
```json
// lexicon.json
{
  "id": "LEX-00001",
  "mooré": "baaga",
  "français": "chien",
  "english": "dog",
  "source": "SRC-17"
}

// proverbs_COMPLETE_v1.json
{
  "id": "PRV-0001",
  "mooré": "Pãng sã n tũud sore...",
  "français": "Quand la force emprunte le chemin...",
  "thème": "la force et la justice",
  "source": "SRC-17"
}
```

## Projet MALM

Ce repo fait partie de l'écosystème **progressio-media** :

- 🎮 [quiz-moore](https://github.com/progressio-media/quiz-moore) — Application pédagogique interactive
- 📊 **malm-data** ← vous êtes ici
- 🌐 [progressio-media](https://github.com/progressio-media/progressio-media) — Média numérique

## Licence

MIT — voir `LICENSE`

## Contact

Tuwend Nooma Jean Damase Roamba · tuwend.nooma@gmail.com

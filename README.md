# 🎨 Beamer-metropolis-themes

Ce dépôt contient un thème personnalisé pour **Beamer** (LaTeX), basé sur le célèbre thème **Metropolis**, avec des ajustements stylistiques personnalisés. Il permet de générer des présentations modernes et élégantes pour vos exposés académiques, soutenances, ou conférences.

---

## 📄 Contenu du dépôt

```
.
├── beamercolorthemewolf.sty   # Fichier de style couleur personnalisé
├── doc.Rmd                    # Présentation source en RMarkdown (optionnel)
├── doc.pdf                    # Présentation générée (aperçu)
├── doc.log                    # Fichier log de compilation LaTeX
├── preamble.tex               # Préambule LaTeX utilisé pour les slides
├── template.Rproj             # Projet RStudio (facultatif)
├── README.md                  # Ce fichier
```

---

## 🧰 Fonctionnalités du thème

- Basé sur le thème Metropolis
- Palette de couleurs personnalisée via `beamercolorthemewolf.sty`
- Typographie élégante et moderne
- Compatible avec LaTeX et `RMarkdown` via `rmarkdown::beamer_presentation`

---

## 🚀 Utilisation

### 🔧 Méthode 1 : Compilation LaTeX classique

1. Assurez-vous d’avoir une distribution LaTeX installée (TeX Live ou MikTeX).
2. Compilez le fichier avec `pdflatex` ou `xelatex` :

```bash
xelatex doc.tex
```

### 📊 Méthode 2 : Via RMarkdown

1. Ouvrir `doc.Rmd` dans RStudio.
2. Cliquer sur `Knit -> Knit to PDF`.
3. Assurez-vous que `template.Rproj` est ouvert si vous utilisez RStudio.

---

## 📷 Aperçu du rendu

Le fichier `doc.pdf` donne un aperçu du rendu visuel final avec le thème appliqué.

---

## 👤 Auteur

**Teeg-wendé Inoussa Ouedraogo**  
Étudiant en Master 1 MAS — Université Rennes 2  
📧 [teeg-wende-inoussa.ouedraogo@etudiant.univ-rennes2.fr](mailto:teeg-wende-inoussa.ouedraogo@etudiant.univ-rennes2.fr)

---

## 📄 Licence
  
Il peut être utilisé ou redistribué sans l’accord explicite de l’auteur.

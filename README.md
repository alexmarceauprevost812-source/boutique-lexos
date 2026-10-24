# Boutique LexOS

Page de vente des applications **LexOS** par **Alex Marceau Prevost** — *Produit du Québec*.

Site statique (`index.html` + images). Paiement sécurisé par **Stripe**, en dollars canadiens.

---

## Produits

### ⌁ LexOS USB-C — 35,00 $
L'édition LexOS la plus complète, avec le moteur d'animation **lexos-moteur**.
Tout le contenu de LexOS PRO, plus les effets et les couleurs de l'édition avancée.

- Moteur d'animation : zoom sur l'icône, nom lettre par lettre, pluie Matrix
- Pluie Matrix au déverrouillage
- Orange par défaut + 8 couleurs au choix
- Recherche avec IA locale (Ollama)
- Tout le contenu de LexOS PRO inclus

**Plateforme :** Android · Samsung Galaxy A55 / S25 Ultra · APK signé
**Achat :** https://buy.stripe.com/14A14n3Fk9THdTk1ga53O0s

---

### &lt;/&gt; CodexLocal — 25,99 $
L'atelier qui signe et fabrique tes APK directement sur le téléphone — même sans ordi et sans internet, au chalet.

- Signe tes APK sur le téléphone, hors ligne
- Studio de fabrication intégré
- Importe ta propre clé de signature (.jks / .p12)
- IA intégrée pour t'aider
- Mises à jour entre tes versions sans désinstaller

**Plateforme :** Android · outil de développeur · APK signé
**Achat :** https://buy.stripe.com/dRm4gzcbQaXL6qS1ga53O0u

---

### LEXOS LexOS PRO — 5,23 $
Le lanceur Android LexOS complet : ton téléphone devient un vrai terminal orange néon.
L'entrée dans l'univers LexOS.

- Accueil terminal (neofetch, heure en caractères chinois)
- Clavier néon + 80 émojis LexOS
- Écran de verrouillage : météo, agenda, notifications
- Pages d'applis, panneau latéral, titres animés
- Page Santé de l'appareil et Paramètres

**Plateforme :** Android · lanceur / thème · APK signé
**Achat :** https://buy.stripe.com/aFa14n7VAc1P8z07Ey53O0v

---

## Déploiement

Site statique, aucun build requis. Pour le mettre en ligne :

1. Sur [vercel.com](https://vercel.com) → **Add New** → **Project**
2. **Import Git Repository** → `boutique-lexos`
3. Framework : aucun (site statique) → **Deploy**

Le fichier `index.html` est servi à la racine.

## Fichiers

- `index.html` — la boutique
- `img0.jpg` — bureau LexOS (carte USB-C)
- `img1.jpg` — accueil CodexLocal (carte CodexLocal)
- `img2.jpg` — icône LexOS PRO (carte PRO)

## À faire

- Protéger le téléchargement des APK (achat Stripe → lien de téléchargement caché) avant la vente réelle.

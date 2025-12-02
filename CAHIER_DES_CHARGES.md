# CAHIER DES CHARGES
## Site Web - Complexe Scolaire Privé Les Dauphins Bleus

---

## 1. INFORMATIONS GÉNÉRALES

### 1.1. Présentation du projet
**Client** : Complexe Scolaire Privé Les Dauphins Bleus  
**Localisation** : Niamey, Quartier Banifandou 2, Boulevard TANIMOUNE, Niger  
**Date de création** : 2025  
**Type de projet** : Site web vitrine institutionnel

### 1.2. Objectifs du projet
- Présenter l'établissement scolaire de manière professionnelle
- Informer les parents et futurs élèves sur les services proposés
- Faciliter la prise de contact avec l'établissement
- Mettre en valeur l'équipe pédagogique et les infrastructures
- Améliorer la visibilité en ligne de l'établissement

### 1.3. Public cible
- **Primaire** : Parents d'élèves actuels et futurs
- **Secondaire** : Élèves, partenaires éducatifs, autorités locales
- **Contexte** : Population de Niamey et environs

---

## 2. CONTEXTE ET BESOINS

### 2.1. Contexte
Le Complexe Scolaire Privé Les Dauphins Bleus, fondé en 2018, souhaite disposer d'un site web moderne pour :
- Communiquer efficacement avec les parents
- Présenter ses valeurs, sa mission et sa vision
- Mettre en avant ses atouts (équipe, infrastructures, activités)
- Faciliter les inscriptions et demandes d'information

### 2.2. Besoins identifiés
1. **Visibilité** : Présence en ligne professionnelle
2. **Communication** : Canal de contact facile et accessible
3. **Information** : Présentation complète de l'établissement
4. **Crédibilité** : Image moderne et professionnelle
5. **Accessibilité** : Site consultable sur tous les appareils

---

## 3. FONCTIONNALITÉS REQUISES

### 3.1. Pages du site

#### 3.1.1. Page d'accueil (`index.html`)
- **Objectif** : Première impression positive
- **Contenu** :
  - Bannière avec slogan accrocheur
  - Section "Qui sommes-nous ?"
  - Section "Nos points forts" avec 3 cartes :
    - Enseignants qualifiés
    - Infrastructures modernes
    - Activités extrascolaires
- **Fonctionnalités** :
  - Animations au survol des cartes
  - Images défilantes automatiques

#### 3.1.2. Page À propos (`apropos.html`)
- **Objectif** : Présenter l'établissement en détail
- **Contenu** :
  - Historique (fondé en 2018)
  - Mission
  - Vision
  - Valeurs (5 valeurs principales)
  - Présentation de l'équipe pédagogique (11 membres)
- **Fonctionnalités** :
  - Galerie photos de l'équipe
  - Bouton d'appel à l'action vers contact

#### 3.1.3. Page Galerie (`galerie.html`)
- **Objectif** : Montrer la vie de l'école
- **Contenu** :
  - Grille de photos (minimum 12 images)
  - Photos de l'école, des cours, des activités
- **Fonctionnalités** :
  - Lightbox pour visualisation agrandie
  - Navigation clavier (flèches gauche/droite)
  - Responsive (grille adaptative)

#### 3.1.4. Page Contact (`contact.html`)
- **Objectif** : Faciliter la prise de contact
- **Contenu** :
  - Formulaire de contact (nom, email, sujet, message)
  - Coordonnées complètes :
    - Adresse : Niamey, Quartier Banifandou 2, Boulevard TANIMOUNE
    - Téléphone : +227 94 55 94 30
    - Email : ecolelesdauphinsbleu@gmail.com
  - Carte Google Maps intégrée
- **Fonctionnalités** :
  - Formulaire fonctionnel (Formspree)
  - Validation des champs
  - Message de confirmation
  - Liens cliquables (téléphone, email, WhatsApp)

#### 3.1.5. Pages légales
- **Politique de confidentialité** (`politique.html`)
- **Conditions Générales d'Utilisation** (`cgu.html`)

### 3.2. Fonctionnalités transversales

#### 3.2.1. Navigation
- Menu principal présent sur toutes les pages
- Indication de la page active
- Logo cliquable (retour accueil)
- Footer avec liens utiles

#### 3.2.2. Responsive Design
- **Desktop** : Largeur > 768px
- **Tablette** : Largeur 480px - 768px
- **Mobile** : Largeur < 480px
- Adaptation automatique des éléments :
  - Menu en colonne sur mobile
  - Logos redimensionnés
  - Grilles adaptatives
  - Texte lisible sur tous les écrans

#### 3.2.3. Interactions utilisateur
- Bouton "Retour en haut" (apparaît après scroll)
- Animations au survol (hover)
- Transitions fluides
- Feedback visuel sur les actions

---

## 4. CONTRAINTES TECHNIQUES

### 4.1. Technologies imposées
- **HTML5** : Structure sémantique
- **CSS3** : Styles et mise en page
- **JavaScript** : Minimal (uniquement pour interactions essentielles)
- **Pas de framework** : Code pur HTML/CSS/JS

### 4.2. Compatibilité navigateurs
- Chrome (dernière version)
- Firefox (dernière version)
- Safari (dernière version)
- Edge (dernière version)
- Navigateurs mobiles (iOS Safari, Chrome Mobile)

### 4.3. Performance
- Temps de chargement < 3 secondes
- Images optimisées
- Code CSS/JS minifié (optionnel)
- Pas de dépendances lourdes

### 4.4. Accessibilité
- Structure HTML sémantique
- Attributs alt sur toutes les images
- Contraste de couleurs suffisant
- Navigation au clavier possible

---

## 5. DESIGN ET IDENTITÉ VISUELLE

### 5.1. Couleurs principales
- **Bleu foncé** : #004080 (header, footer, boutons principaux)
- **Blanc** : #FFFFFF (texte sur fond bleu, fonds)
- **Gris clair** : #f9f9f9 (fonds de sections)
- **Or/Jaune** : #ffd700 (accents, hover)

### 5.2. Typographie
- **Police principale** : Arial, sans-serif
- **Hiérarchie** :
  - Titres H1 : 2.5em (bannière)
  - Titres H2 : 1.8em - 2em
  - Titres H3 : 1.2em - 1.5em
  - Texte : 1em - 1.1em

### 5.3. Éléments graphiques
- **Logo** : Présent dans header et footer
- **Images** : Photos de qualité, optimisées
- **Icônes** : Font Awesome pour les icônes sociales/contact
- **Boutons** : Coins arrondis, effets hover

### 5.4. Mise en page
- **Largeur maximale** : 1200px pour le contenu principal
- **Espacement** : Padding et margins cohérents
- **Grilles** : Flexbox et CSS Grid
- **Sections** : Espacement vertical régulier

---

## 6. CONTENU

### 6.1. Textes
- **Tone of voice** : Professionnel, bienveillant, rassurant
- **Langue** : Français
- **Longueur** : Concis mais informatif

### 6.2. Images
- **Format** : JPG, PNG
- **Taille optimale** : Adaptée à l'usage (bannière, vignettes, etc.)
- **Alt text** : Descriptif pour chaque image

### 6.3. Informations à afficher

#### Équipe pédagogique (11 membres)
1. Sani Zafarou - Directeur
2. Émile Dieudonné - Directeur adjoint
3. Koffi Sena - Secrétaire général
4. Mme Aïcha Yahya - Enseignante CI
5. Fabrice Klossou - Enseignant CP
6. Assani Abdourahamane - Enseignant CE1
7. Mr Malik - Enseignant CE2
8. Mr Yaovi Amevo - Enseignant CM1
9. Nadège N'guessan - Enseignante CM2
10. Tanti Leila - Caissière
11. Tanti Richala - Caissière

#### Coordonnées
- **Adresse** : Niamey, Quartier Banifandou 2, Boulevard TANIMOUNE
- **Téléphone** : +227 94 55 94 30
- **Email** : ecolelesdauphinsbleu@gmail.com
- **WhatsApp** : +227 94 55 94 30

#### Valeurs
1. Excellence académique
2. Créativité et innovation
3. Discipline et rigueur
4. Bienveillance et respect
5. Esprit de communauté

---

## 7. FONCTIONNALITÉS SPÉCIFIQUES

### 7.1. Formulaire de contact
- **Service** : Formspree (https://formspree.io/f/xwpanezg)
- **Champs** :
  - Nom (obligatoire)
  - Email (obligatoire, validation)
  - Sujet (obligatoire)
  - Message (obligatoire)
- **Comportement** :
  - Validation côté client
  - Message de confirmation après envoi
  - Réinitialisation du formulaire après succès
  - Gestion des erreurs

### 7.2. Carte Google Maps
- **Intégration** : Iframe Google Maps
- **Localisation** : Complexe Scolaire Privé LES DAUPHINS BLEUS
- **Responsive** : Hauteur fixe 400px, largeur 100%

### 7.3. Galerie photos
- **Affichage** : Grille responsive (3 colonnes desktop, 2 tablette, 1 mobile)
- **Lightbox** :
  - Ouverture au clic
  - Navigation précédent/suivant
  - Fermeture (bouton X ou clic extérieur)
  - Navigation clavier (flèches, Escape)

### 7.4. Animations
- **Points forts** : Rotation automatique des images au survol
- **Cartes** : Effet de zoom au survol
- **Boutons** : Changement de couleur au survol
- **Transitions** : Fluides (0.3s - 0.5s)

---

## 8. STRUCTURE DES FICHIERS

```
franck/
├── css/
│   └── style.css          # Feuille de style unique
├── images/                # Toutes les images
│   ├── logo.png
│   ├── prof1.png à prof11.png
│   ├── gal1.jpg à gal6.jpg
│   ├── IMG-20251029-WA*.jpg
│   ├── activite*.jpg
│   ├── enseignant*.jpg
│   ├── infrastructure*.jpg
│   ├── equipe.jpg
│   ├── qui-sommes-nous.png
│   └── reussite-enfants.png
├── index.html             # Page d'accueil
├── apropos.html          # Page À propos
├── contact.html          # Page Contact
├── galerie.html          # Page Galerie
├── politique.html        # Politique de confidentialité
├── cgu.html              # Conditions Générales
├── README.md             # Documentation technique
└── CAHIER_DES_CHARGES.md # Ce document
```

---

## 9. CRITÈRES D'ACCEPTATION

### 9.1. Fonctionnalités
- [ ] Toutes les pages s'affichent correctement
- [ ] Navigation fonctionne sur toutes les pages
- [ ] Formulaire de contact envoie les messages
- [ ] Galerie avec lightbox fonctionnelle
- [ ] Carte Google Maps s'affiche correctement
- [ ] Bouton retour en haut fonctionne
- [ ] Animations au survol actives

### 9.2. Design
- [ ] Respect de la charte graphique (couleurs, typographie)
- [ ] Design cohérent sur toutes les pages
- [ ] Logo présent et bien positionné
- [ ] Images de qualité et bien dimensionnées
- [ ] Espacements harmonieux

### 9.3. Responsive
- [ ] Site consultable sur mobile (< 480px)
- [ ] Site consultable sur tablette (480px - 768px)
- [ ] Site consultable sur desktop (> 768px)
- [ ] Aucun débordement horizontal
- [ ] Texte lisible sur tous les écrans
- [ ] Menu adaptatif fonctionnel

### 9.4. Performance
- [ ] Temps de chargement acceptable (< 3s)
- [ ] Images optimisées
- [ ] Code propre et commenté

### 9.5. Accessibilité
- [ ] Structure HTML sémantique
- [ ] Attributs alt sur toutes les images
- [ ] Navigation au clavier possible
- [ ] Contraste de couleurs suffisant

---

## 10. MAINTENANCE ET ÉVOLUTIONS FUTURES

### 10.1. Maintenance
- Mise à jour du contenu (équipe, activités)
- Ajout de nouvelles photos dans la galerie
- Vérification des liens externes
- Mise à jour des informations de contact si nécessaire

### 10.2. Évolutions possibles
- Système de gestion de contenu (CMS)
- Blog/Actualités
- Espace parents (connexion sécurisée)
- Calendrier des événements
- Galerie vidéo
- Multilingue (français/anglais/hausa)

---

## 11. DÉLAIS ET LIVRABLES

### 11.1. Livrables
- [x] Structure HTML complète (6 pages)
- [x] Feuille de style CSS unique
- [x] JavaScript pour interactions
- [x] Toutes les images intégrées
- [x] Documentation (README.md)
- [x] Cahier des charges

### 11.2. Tests
- Tests sur différents navigateurs
- Tests responsive (mobile, tablette, desktop)
- Validation du formulaire de contact
- Vérification de tous les liens

---

## 12. CONTACTS ET RESSOURCES

### 12.1. Coordonnées établissement
- **Nom** : Complexe Scolaire Privé Les Dauphins Bleus
- **Adresse** : Niamey, Quartier Banifandou 2, Boulevard TANIMOUNE
- **Téléphone** : +227 94 55 94 30
- **Email** : ecolelesdauphinsbleu@gmail.com
- **Fondé en** : 2018

### 12.2. Services externes utilisés
- **Formspree** : Gestion des formulaires de contact
- **Google Maps** : Carte interactive
- **Font Awesome** : Bibliothèque d'icônes (CDN)

---

## 13. GLOSSAIRE

- **Responsive** : Design adaptatif qui s'ajuste à la taille de l'écran
- **Lightbox** : Fenêtre modale pour afficher des images en grand format
- **CDN** : Content Delivery Network (réseau de distribution de contenu)
- **Semantic HTML** : HTML sémantique utilisant les balises appropriées
- **Hover** : Effet au survol de la souris
- **Footer** : Pied de page
- **Header** : En-tête de page

---

**Document créé le** : 2025  
**Version** : 1.0  
**Statut** : Projet terminé


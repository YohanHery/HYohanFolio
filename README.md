# HYohanFolio 🚀

Portfolio web interactif conçu pour présenter mon parcours académique, mes compétences techniques, mes projets en cybersécurité et développement, ainsi que mes performances en compétitions CTF.

L'ensemble de l'application est développé en architecture **Single-Page Application (SPA)** sans framework externe (Vanilla HTML, CSS, JavaScript), optimisé pour un déploiement statique ultra-rapide sur **GitHub Pages**.

---

## 📑 Sommaire

- [Aperçu des Fonctionnalités](#-aperçu-des-fonctionnalités)
- [Architecture des Rubriques](#-architecture-des-rubriques)
- [Stack Technique](#-stack-technique)
- [Installation & Utilisation Locale](#-installation--utilisation-locale)
- [Personnalisation](#-personnalisation)
- [Auteur & Contact](#-auteur--contact)

---

## ✨ Aperçu des Fonctionnalités

- **Navigation fluide :** Changement dynamique d'onglets côté client sans rechargement de page.
- **Responsive & Mobile-First :** Menu tiroir latéral (*drawer*) avec arrière-plan flouté (*backdrop blur*) et bouton burger animé.
- **Filtre interactif de projets :** Filtrage instantané par domaine technologique (Sécurité, C/Système, OCaml, Web, Python/Java, Data).
- **Palmarès CTF interactif :** Cartes de classements cliquables sous forme d'accordéon pour consulter les détails de chaque épreuve.
- **Section Contact moderne :** 
  - Cartes 3D avec halo lumineux cyan.
  - Copie instantanée de l'adresse e-mail avec feedback via notification *toast*.
  - Modale interactive permettant de composer un message et d'ouvrir directement l'interface web de Gmail ou le client mail par défaut.

---

## 📂 Architecture des Rubriques

### 1. 💼 Expérience
- **Timeline verticale lumineuse :** Parcours chronologique avec nœuds interactifs.
- **Missions & Postes :**
  - Stage en développement d'applications chez **PROXIAD AXE SEINE** (Symfony, PHP, Vue.js, React, Angular, Doctrine).
  - Mandat de **Représentant étudiant** de Licence Informatique à l'Université de Rouen Normandie.
  - Expériences professionnelles opérationnelles (CERP Rouen, Natup, AJV Vernon).
- **Mise en avant des compétences :** Badges techniques et *soft skills* (autonomie, travail en équipe, rigueur, gestion du stress).

### 2. 💻 Projets
Grille dynamique de projets alimentée par les travaux de licence et les réalisations personnelles :
- **Sécurité & Réseaux :** Segmentation réseau, pare-feu pfSense, audit Nmap et détection Snort.
- **C & Programmation Système :** Serveur démon de filtrage d'images (threads, sémaphores, tubes), compteur de mots exclusif (`projet_occ`), distance de Jaccard.
- **OCaml & Logique Formelle :** Validateur de syllogismes (diagrammes de Venn), algorithme de réduction de Tseitin, calculs sur polynômes (Karatsuba).
- **Python & Java :** Recherche de cycles hamiltoniens sur des graphes, travaux pratiques Java avec interfaces graphiques (IHM).
- **Web & Applicatifs :** Plateforme *BiblioWeb*, clone de plateforme de streaming (Vue.js / Laravel / TMDB), site e-commerce C2C.
- **Data & Outils Métier :** *Aircraft Certification Tracker* (Power BI & DAX / norme CS-25), tutoriel interactif Excel VBA.

### 3. 🎯 CTF (Capture The Flag)
- **Palmarès compétitif :**
  - **PascalCTF 2026 :** 92ᵉ / 855
  - **Jeanned'Hack 2025 :** 11ᵉ / 55 (duo vs équipes de 3)
  - **Jeanned'Hack 2024 :** 6ᵉ / 20 (solo vs équipes de 3)
  - **Jeanned'Hack 2026 :** Participation solo vs équipes de 5
- **Profils d'entraînement :** Référence aux plateformes Root-Me, TryHackMe et Hack The Box (`YohanImHere`).
- **Write-ups :** Cartes de comptes-rendus techniques de challenges (ex. *MISSION:ASTER*) classés par niveau de difficulté.

### 4. 📬 Contact
- Cartes interactives vers **Email**, **LinkedIn** et **GitHub**.
- Modale de contact pré-remplie avec redirection vers Gmail (`https://mail.google.com/mail/?view=cm...`).

---

## 🛠️ Stack Technique

- **HTML5 :** Structure sémantique accessible (`nav`, `section`, `form`, SVG natifs).
- **CSS3 :**
  - Variables CSS (`--bg-color`, `--card-bg`, `--accent`, etc.) pour un thème sombre cohérent.
  - Flexbox et CSS Grid pour la mise en page adaptative.
  - Animations keyframes (`fadeIn`, `floatSlow`) et micro-interactions.
- **JavaScript (ES6+) :**
  - Gestion des onglets et bascule de classes actives.
  - Système de filtrage dynamique du DOM.
  - API Clipboard (`navigator.clipboard.writeText`) pour la copie rapide.

---

## 🚀 Installation & Utilisation Locale

Aucun gestionnaire de paquets (`npm`, `yarn`) ni étape de compilation n'est requis.

1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/YohanHery/HYohanFolio.git](https://github.com/YohanHery/HYohanFolio.git)
   cd HYohanFolio
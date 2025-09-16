# 🌿 Morada Lodge - Site Vitrine & Réservation en Ligne

Bienvenue dans le dépôt GitHub du site web **Morada Lodge**, un site vitrine moderne pour un lodge au Bénin, intégrant une page de réservation étape par étape avec options de paiement en ligne ou sur place.

---

## 📝 Description du projet

Le site Morada Lodge a été conçu pour :  
- Présenter les **chambres**, le **restaurant**, la **galerie** et les **contacts** du lodge.  
- Offrir une expérience utilisateur **simple et fluide**, adaptée aux ordinateurs et mobiles grâce à **Tailwind CSS**.  
- Proposer une **réservation en ligne incrémentale** : le client renseigne ses informations, choisit le type de paiement (en ligne ou sur place), et peut payer via **FedaPay, Cinet ou Kika**.  

---

## 🌐 Pages principales

1. **index.html** : Page d’accueil avec :  
   - Hero avec bouton "Réserver maintenant"  
   - Sections Chambres, Restaurant, Galerie et Contact  
   - Footer  

2. **reservation.html** : Page de réservation étape par étape :  
   - Étape 1 : Informations personnelles (Nom, Email, Téléphone)  
   - Étape 2 : Choix du mode de paiement (en ligne ou sur place)  
   - Étape 3 : Redirection vers la plateforme de paiement choisie (FedaPay / Cinet / Kika)  
   - Étape 4 : Confirmation de réservation si paiement sur place  

---

## 💻 Technologies utilisées

- **HTML5** et **CSS**  
- **Tailwind CSS** pour le style moderne et responsive  
- **JavaScript** pour la logique des étapes de réservation  
- (Optionnel) APIs de paiement pour intégration avancée  

---

## ⚡ Fonctionnalités principales

- Design **responsive** pour mobile et desktop  
- Navigation fluide et sticky header  
- Page de réservation **incrémentale**  
- Possibilité de choisir le mode de paiement  
- Redirection vers les plateformes de paiement locales ou internationales  

---

## 📂 Structure du projet
morada-lodge/
│
├─ index.html # Page d'accueil
├─ reservation.html # Page de réservation étape par étape
├─ README.md # Documentation du projet
└─ assets/ # Images et ressources (facultatif)


---

## 🚀 Installation et usage

1. Cloner le dépôt :  
```bash
git clone https://github.com/votre-utilisateur/morada-lodge.git


Ouvrir index.html dans votre navigateur pour tester le site.

Cliquer sur Réserver maintenant pour tester la page de réservation étape par étape.

Pour le paiement en ligne, remplacer les liens de redirection vers FedaPay, Cinet ou Kika par vos liens réels.

📌 Personnalisation

Modifier les images dans la section Chambres, Restaurant et Galerie selon vos besoins.

Mettre à jour les informations de contact dans la section Contact.

Adapter le style Tailwind CSS pour les couleurs et polices du lodge.

📫 Contact

Pour plus d’informations :

Email : contact@moradalodge.com

Téléphone : +229 90 00 00 00

🛡 License

Ce projet est sous MIT License. Libre d'utilisation, modification et distribution.

Morada Lodge - Un havre de paix au cœur de la nature.

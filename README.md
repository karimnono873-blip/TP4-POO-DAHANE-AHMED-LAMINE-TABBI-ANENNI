# 🌌 Système de Paie POO - TP N°04 (Deep Space Edition)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-OOP_Architecture-007396?style=for-the-badge&logo=java&logoColor=white)
![USTHB](https://img.shields.io/badge/USTHB-Space_Division-bc13fe?style=for-the-badge)

Ce dépôt contient l'implémentation complète pour le **TP N°4 : Application des concepts de la Programmation Orientée Objet (POO)**. 

Le projet modélise le système de calcul des salaires d'une entreprise nationale. Il intègre une architecture Java stricte et une interface utilisateur Web immersive (Thème Dashboard Spatial) permettant de simuler les flux financiers en temps réel.

---

## 🎓 Base de Lancement Académique
* **Centre de Commandement :** Université des Sciences et de la Technologie HOUARI BOUMEDIENE - USTHB
* **Secteur :** Faculté de Génie Electrique FGE - Département d'Automatique
* **Niveau & Flotte :** Master 1 AII (Automatique et Informatique Industrielle)
* **Superviseur :** M. MENANI

---

## 📐 Architecture Orientée Objet (UML)
Ce système a été conçu pour exploiter pleinement les paradigmes avancés de la POO :
* **Interfaces (`ICalculable`) :** Définition d'un contrat strict imposant la méthode `calculerSalaireNet()` à toutes les entités.
* **Classes Abstraites (`Employe`) :** Centralisation des attributs communs (Nom, Prénom, Salaire de Base) et des méthodes partagées (calcul des retenues, primes familiales).
* **Héritage (`Administratif` extends `Employe`) :** Spécialisation des profils pour traiter les spécificités des postes à responsabilités.
* **Polymorphisme & Redéfinition (`@Override`) :** Adaptation dynamique du calcul du salaire en fonction de la nature exacte de l'objet instancié.
* **Encapsulation :** Protection absolue des données sensibles via les modificateurs de visibilité `private` et `protected`.

---

## ⚙️ Logique Métier & Algorithmes
Le moteur de calcul prend en compte les variables suivantes pour générer le solde net :
* **Revenus :**
  * Salaire de base (fixe).
  * Prime familiale : +300 DA par enfant à charge (< 18 ans).
  * Prime de poste : Chef de service (+3% du salaire de base), Chef de bureau (+2%).
* **Retenues :**
  * Sécurité Sociale : -7% du salaire de base.
  * Pénalités d'absence : -0.5% du salaire de base par jour d'arrêt de travail.

---

## ✨ Fonctionnalités du Dashboard
* **Moteur Logique JS :** Transposition exacte de l'architecture Java en JavaScript pour une exécution fluide dans le navigateur.
* **Interface "Deep Space" :** Design holographique, typographie futuriste (`Orbitron`, `Fira Code`), et fond stellaire animé.
* **Télémétrie Financière Temps Réel :** Mise à jour dynamique de la décomposition du salaire (Primes vs Retenues) dès la modification d'un paramètre.
* **Animations Fluides :** Effets de compteurs numériques pour l'affichage du solde total brut calculé.

---

## 🚀 Déploiement
L'interface de simulation est prête à être déployée (compatible GitHub Pages) sans nécessité de configurer un environnement Java local (JRE/JDK) pour la visualisation :
1. Récupérez le fichier `index.html`.
2. Lancez-le dans n'importe quel navigateur web moderne.
3. Saisissez les données du personnel dans le panneau de commande de gauche.
4. Observez la décomposition holographique du salaire sur le panneau de droite.

---

## 👨‍💻 Officier de Bord & Architecte Logiciel
**Dahane Ahmed Lamine** *Spécialité Automatique et Informatique Industrielle - Ingénierie des Systèmes*

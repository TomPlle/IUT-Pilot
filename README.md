# IUT Companion 🎓📱

**IUT Companion** est une application mobile développée avec React Native et Expo, conçue pour centraliser l'ensemble des services numériques utiles aux étudiants de l'université (emploi du temps en direct, messagerie, plateforme pédagogique et portails ENT).

---

## 🚀 Fonctionnalités principales

* **Emploi du temps synchronisé (ADE) :**
  * Configuration instantanée via scan d'un QR code ADE (stockage local sécurisé avec `AsyncStorage`).
  * Navigation hebdomadaire et journalière avec mise en valeur du cours en cours.
  * Mise en cache locale des cours pour une consultation hors-ligne.
  * Bouton de réinitialisation rapide des données locales.

* **Services universitaires intégrés :**
  * **Messagerie :** Accès direct à Partage sans quitter l'application.
  * **E-Learning :** Plateforme Moodle intégrée en vue web native (`react-native-webview`).
  * **Portails & Services ENT :** Grille ergonomique de 20 accès directs vers les outils du campus (Izly, Crous & Go, Pix, Voltaire, Career Center, Catalogue BU, etc.).

---

## 🛠️ Stack technique

* **Framework :** [React Native](https://reactnative.dev/) avec [Expo](https://expo.dev/)
* **Navigation :** `@react-navigation/bottom-tabs` & `@react-navigation/native-stack`
* **Composants natifs :** `react-native-webview`, `react-native-safe-area-context`
* **Gestion du calendrier :** `ical.js`
* **Persistance des données :** `@react-native-async-storage/async-storage`
* **Compilation & Déploiement :** EAS Build (Android APK)

---

## 📲 Téléchargement sur Android (.APK)

Les versions compilées de l'application prêtes à l'installation sur Android sont disponibles directement dans l'onglet [Releases](https://www.google.com/search?q=https://github.com/TomPlle/IUT-Companion/releases).


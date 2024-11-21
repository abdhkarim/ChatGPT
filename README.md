# KHRAL - Outils de tests de vulnérabilités web

### Description du projet

**KHRAL** est un projet de sécurité destiné à tester et exploiter certaines vulnérabilités web courantes telles que l'**injection SQL**, les **attaques XSS** (Cross-Site Scripting), et d'autres vulnérabilités mentionnées dans le **Top 10 de l'OWASP**. Ce projet a pour but de créer des outils permettant de tester ces vulnérabilités de manière personnalisée, tout en comprenant le fonctionnement des tests de pénétration. Les outils créés seront utilisés dans des tests d'intrusion (pentesting) pour identifier des failles de sécurité dans les applications web.

Le projet regroupe plusieurs outils permettant d'identifier et d'exploiter des vulnérabilités communes dans les applications web, tout en permettant aux utilisateurs de mieux comprendre comment ces outils fonctionnent en coulisses.

### Objectifs

- Développer des outils de test pour les vulnérabilités OWASP telles que l'injection SQL, XSS, etc.
- Créer une interface utilisateur moderne pour naviguer entre les outils de test.
- Fournir une documentation pour permettre l'extension et la compréhension du fonctionnement des outils de pentesting.

### Fonctionnalités principales

- **Test d'injection SQL** : Teste la vulnérabilité d'un site aux injections SQL via des paramètres d'URL.
- **Test d'attaque XSS** : Vérifie la présence de vulnérabilités XSS dans une application web.
- **Interface graphique moderne** : Une interface graphique simple et moderne permettant de naviguer entre les outils de tests.

### Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants sur votre machine :

- **Python 3.x** : Ce projet utilise Python pour implémenter les outils de tests.
- **Bibliothèques Python** :
  - `requests` : pour effectuer des requêtes HTTP et tester les vulnérabilités.
  - `tkinter` : pour l'interface graphique.
  - `Pillow` : pour afficher des images dans l'interface.

Pour installer les dépendances Python, vous pouvez utiliser `pip` avec le fichier `requirements.txt` :

```bash
pip install -r requirements.txt

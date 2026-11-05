# AutoDNB4ème · Réviser les automatismes niveau 4ème

AutoDNB4ème : s'entraîner aux automatismes de 4ème sur le modèle de l'épreuve du DNB, en libre ou en épreuve chronométrée de 20 minutes, avec correction détaillée. Sans compte, rien ne quitte l'appareil.

🔗 **Utiliser en ligne :** https://auriaphilippe.forge.apps.education.fr/AutoDNB4eme/
📄 Licence [GNU GPL v3](LICENSE) · 📜 [Nouveautés](CHANGELOG.md) · 🛡️ [Sécurité](SECURITY.md) · ♿ [Accessibilité](accessibilite.html)

## Pour quoi faire ?

S'entraîner aux automatismes de 4ème sur le modèle de l'épreuve de mathématiques du DNB (DNB blancs de 4ème), librement par thème ou en épreuve de 20 minutes notée sur 6 points.

## Pour qui ?

Les élèves de 4ème, en autonomie ou en classe.

## Comment l'utiliser

1. Ouvrez la page en ligne (rien à installer, pas de compte).
2. Choisissez « Entraînement libre » (un thème, correction après chaque réponse) ou « Épreuve réelle » (20 minutes chrono, correction à la fin).
3. Répondez aux questions : réponse libre ou QCM.
4. Consultez la correction détaillée et les figures à la fin de la série.

Pour l'utiliser hors ligne, téléchargez le dépôt et ouvrez `index.html` dans un navigateur : aucune dépendance, aucune connexion nécessaire.

## Fonctionnalités

- 15 thèmes du programme de 4ème, avec Pythagore et Thalès traités séparément.
- Entraînement libre avec correction immédiate, ou épreuve de 20 minutes notée sur 6.
- Questions de réponse libre ou QCM, générées au hasard à chaque série.
- Questions identiques à celles de la console Professeur niveau 4ème.

## Données et vie privée

Aucun compte, aucun cookie, aucune mesure d'audience, aucun serveur. Le navigateur garde uniquement le thème clair ou sombre (clé `autodnb-theme`) sur l'appareil. Rien n'est envoyé sur le réseau. Aucune donnée personnelle d'élève n'est traitée. Pour tout effacer, supprimer les données du site dans le navigateur.

## Accessibilité

**Accessibilité : non conforme** (aucun audit réalisé). Les contenus connus comme non accessibles sont listés dans la [déclaration d'accessibilité](accessibilite.html), avec les pistes d'amélioration.

## Sécurité

Aucune bibliothèque ni police chargée depuis un site tiers, aucune requête réseau, pas d'`eval`, politique de sécurité du contenu (CSP) stricte et aucun gestionnaire `onclick` en ligne. Le détail, les limites de GitLab Pages et la façon de signaler une faille sont dans [SECURITY.md](SECURITY.md).

## Lancer en local / publier

- En local : ouvrir `index.html` dans un navigateur.
- Publication : GitLab Pages, via `.gitlab-ci.yml`, à chaque envoi sur la branche `main`. Aucune étape de construction.

## Architecture

```text
index.html             L'application (un seul fichier)
mentions-legales.html  Mentions légales
accessibilite.html     Déclaration d'accessibilité
assets/favicon.svg     Icône
assets/fonts/          Polices Syne et DM Sans (.woff2) et leur licence OFL
LICENSE                Licence GNU GPL v3
SECURITY.md            Sécurité
CHANGELOG.md           Historique des versions
.gitlab-ci.yml         Publication GitLab Pages
```

## Contribuer

- Signaler une erreur ou proposer une idée : [ouvrir un ticket](https://forge.apps.education.fr/auriaphilippe/AutoDNB4eme/-/issues).
- Proposer une modification : fourche du dépôt, puis demande de fusion.
- Règles : le français est la langue du projet (interface, commentaires, messages de commit) ; aucune dépendance externe ; tester l'application avant de proposer une modification.

## Crédits

- Les générateurs de questions sont écrits par l'auteur ; ils s'inspirent des programmes officiels, des ressources Éduscol « Les automatismes au collège » et des sujets du DNB publiés par le ministère.
- Polices **Syne** (© The Syne Project Authors) et **DM Sans** (© The DM Sans Project Authors), licence SIL Open Font License 1.1, voir `assets/fonts/`.
- Conçu par Philippe Auria, Collège Fernand Donatien, Fort-de-France.

## Licence

Logiciel libre sous licence [GNU GPL v3](LICENSE).

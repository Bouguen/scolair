# Scolair

Première intégration de la page publique de Scolair avec les corrections de navigation et d’accessibilité préparées le 5 novembre 2026.

## Fichiers

- `site.html` contient la page corrigée destinée à l’hébergement PHP existant.
- `apercu.html` permet de consulter la page localement. Les 22 illustrations publiques sont incluses dans le dossier img/ et chargées localement. Le formulaire utilise le repli vers un brouillon de courriel. Les contenus administrés et la liste des PDF ne sont pas chargés dans cet aperçu.

## Modifications

- Menu mobile avec état accessible, fermeture après navigation et touche Échap.
- Mise à jour des attributs HTML de langue et de direction en arabe et en anglais.
- Bandeau d’accueil plus compact et bouton principal harmonisé.
- Visites des modules et du parcours lancées manuellement.
- Précisions sur le périmètre du pilote et consigne de minimisation des données dans le formulaire.
- Liens vers la rubrique de protection des données et le contact dans le pied de page.

## Intégration à terminer

Le dépôt initial contenait uniquement un fichier `test` vide. La page a été récupérée depuis la version publique. Avant toute mise en production, récupérer les services `api/content.php`, `api/files.php`, `api/contact.php` et leur configuration auprès de l’hébergement actuel. Les services PHP, les données administrées et leurs configurations ne figurent pas dans cette copie publique. Ne pas ajouter de mots de passe ou de secrets au dépôt.

Confirmer auprès de l’équipe Scolair l’état actuel du pilote, les fonctionnalités disponibles, l’identité de l’entreprise et les pratiques de conservation des données avant de compléter les informations de confiance.

## Vérification

La syntaxe JavaScript des deux fichiers a été vérifiée. Les interactions de l’aperçu ont été testées avec un navigateur automatisé à 390 px et 1280 px, pour le menu mobile, la navigation vers une rubrique, le changement de langue et l’ouverture du formulaire. Aucun envoi de formulaire n’a été effectué. La livraison des messages et les services PHP restent à vérifier sur l’hébergement.

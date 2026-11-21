# Vietnam Love

Plateforme pédagogique mobile-first, inspirée de l’architecture fonctionnelle de Sawasdee-Love.

## État actuel
- Interface bilingue vietnamien / français.
- Trois modules pédagogiques, neuf leçons initiales et suivi de progression local.
- Présentation des trois niveaux d’offres.
- Paiement volontairement désactivé tant que les prix, les liens de paiement LIVE et la validation serveur ne sont pas confirmés.

## Lancer en local
Ouvrir `index.html` dans un navigateur. Le projet est volontairement sans dépendance ni abonnement logiciel pour cette première version.

## Sécurité — avant ouverture commerciale
La progression actuelle est enregistrée dans le navigateur et ne constitue pas un système d’authentification. Ne pas vendre l’accès sur cette seule base. La prochaine étape est un backend avec :
1. Stripe Checkout en mode LIVE et webhook signé côté serveur.
2. Attribution des droits à partir d’un paiement confirmé, jamais à partir d’un code public stocké dans le JavaScript.
3. Authentification et stockage serveur de la progression.
4. Espace d’administration protégé et journal des événements.

## Décisions à confirmer avant commercialisation
- Tarifs définitifs et devise (THB, EUR ou les deux).
- Contenu pédagogique vietnamien relu par une personne parfaitement bilingue vietnamien-français.
- Politique de confidentialité, conditions de vente et coordonnées de l’éditeur.
- Hébergement et domaine définitifs.

## Référence
Le parcours est structuré sur le modèle pédagogique existant de Sawasdee-Love, mais les contenus sont adaptés au contexte Vietnam–France et ne reprennent pas les codes d’accès ni les liens de paiement thaïlandais.

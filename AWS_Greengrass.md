AWS Greengrass est un service d'informatique en périphérie (edge computing) fourni par Amazon Web Services. 
Il permet d'exécuter du code, de collecter des données et de gérer des appareils connectés localement, 
même en l'absence de connectivité Internet. 
Voici une procédure générale pour commencer à utiliser AWS Greengrass :

- Créez un groupe Greengrass :
  - Connectez-vous à la console AWS et accédez au service Greengrass.
  - Cliquez sur "Create Group" (Créer un groupe).
  - Donnez un nom à votre groupe Greengrass et une description facultative.
  - Configurez les paramètres de sécurité et de mise à jour selon vos besoins.
  - Cliquez sur "Create Group" (Créer un groupe) pour terminer.
- Ajoutez des appareils au groupe Greengrass :
  - Dans la console Greengrass, sélectionnez votre groupe Greengrass nouvellement créé.
  - Cliquez sur "Add Device" (Ajouter un appareil).
  - Sélectionnez la méthode d'ajout d'appareil appropriée (par exemple, via l'ARN du certificat, via le certificat IOT Core, etc.).
  - Suivez les étapes spécifiques à la méthode choisie pour ajouter les appareils à votre groupe.
- Créez et configurez un Greengrass Core :
  - Dans la console Greengrass, sélectionnez votre groupe Greengrass.
  - Cliquez sur "Cores" dans le menu de gauche, puis sur "Add Core" (Ajouter un Core).
  - Configurez les détails du Core, tels que le nom, la description, les certificats, etc.
  - Sélectionnez les appareils associés au Core.
  - Cliquez sur "Add Core" (Ajouter un Core) pour terminer.
- Déployez des greengrass groups sur votre Core :
  - Dans la console Greengrass, sélectionnez votre groupe Greengrass.
  - Cliquez sur l'onglet "Deployments" (Déploiements).
  - Cliquez sur "Create a new deployment" (Créer un nouveau déploiement).
  - Configurez les détails du déploiement, tels que les groupes à déployer, les appareils cibles, etc.
  - Cliquez sur "Next" (Suivant) pour passer à l'étape suivante.
  - Sélectionnez les ressources à inclure dans le déploiement (lambda functions, machine learning models, etc.).
  - Cliquez sur "Review" (Vérifier) et vérifiez les détails du déploiement.
  - Cliquez sur "Deploy" (Déployer) pour lancer le déploiement.
  - Une fois que vous avez terminé ces étapes, votre groupe Greengrass et votre Core seront opérationnels,
  - prêts à exécuter du code et à interagir avec des appareils connectés localement.
  - Vous pouvez ajouter des lambdas functions,
  - configurer des règles et définir des abonnements pour répondre aux besoins spécifiques de votre application Greengrass.

N'oubliez pas de consulter la documentation officielle d'AWS Greengrass pour obtenir des informations plus détaillées 
sur chaque étape de la procédure et pour explorer les fonctionnalités avancées du service.

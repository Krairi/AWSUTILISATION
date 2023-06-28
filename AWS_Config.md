La configuration d'AWS Config implique plusieurs étapes pour permettre la gestion, la surveillance et l'évaluation continue de la conformité de vos ressources AWS. 
Voici une procédure générale pour configurer AWS Config :

- Créez un rôle IAM :
  - Commencez par créer un rôle IAM (Identity and Access Management) qui aura les autorisations nécessaires pour accéder aux ressources AWS et collecter les données de configuration.
  - Ce rôle doit disposer des autorisations appropriées pour accéder aux services AWS que vous souhaitez surveiller avec AWS Config.
- Activer AWS Config :
  - Accédez à la console AWS Management Console et recherchez le service AWS Config.
  - Activez AWS Config dans la région de votre choix. Lors de l'activation,
  - vous pouvez choisir les types de ressources que vous souhaitez surveiller et les détails de configuration que vous souhaitez collecter.
- Configurer les enregistrements :
  - Déterminez les ressources spécifiques que vous souhaitez surveiller avec AWS Config.
  - Vous pouvez configurer des enregistrements individuels pour chaque type de ressource
  - ou utiliser des règles de configuration pour sélectionner automatiquement les ressources en fonction de critères spécifiques.
- Configurer les évaluations :
  - Les évaluations dans AWS Config vous permettent de définir des règles de conformité pour vérifier si vos ressources respectent certaines politiques ou des bonnes pratiques spécifiques.
  - Configurez des règles d'évaluation pour les enregistrements AWS Config afin de détecter les non-conformités et de générer des rapports d'évaluation.
- Configurer les notifications :
  - Vous pouvez configurer des notifications pour être informé des changements de configuration et des non-conformités détectées par AWS Config.
  - Définissez les destinations des notifications, telles que les files d'attente Amazon SNS ou les flux Amazon Kinesis,
  - et spécifiez les types de notifications que vous souhaitez recevoir.
- Analyser les données de configuration :
  - Une fois AWS Config configuré, il commencera à collecter les données de configuration et à générer des rapports sur l'état de conformité de vos ressources.
  - Vous pouvez utiliser les API AWS Config pour accéder aux données de configuration et les analyser à l'aide d'outils tiers ou de vos propres scripts.
- Gérer les non-conformités :
  - En utilisant les informations fournies par AWS Config, identifiez les non-conformités et prenez les mesures nécessaires pour les résoudre.
  - Vous pouvez utiliser AWS Config Rules pour automatiser la vérification de conformité et prendre des mesures correctives en cas de non-conformité détectée.

Il convient de noter que cette procédure est une vue d'ensemble générale et qu'il peut y avoir des variations en fonction de vos besoins spécifiques et de votre environnement AWS. 
Vous pouvez consulter la documentation officielle d'AWS Config pour obtenir des instructions détaillées sur la configuration et l'utilisation du service.

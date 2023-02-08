Voici un exemple de configuration YAML pour déployer un simple serveur web "Hello World" dans Kubernetes :
- [Fichier config ici](./config.yml)

Cette configuration définit un déploiement hello-world-web-server qui comporte un seul réplica de conteneur Nginx exécutant un script shell qui écrit le message "Hello World" dans un fichier HTML. Le service Kubernetes associé expose ce conteneur sur un port 80 en utilisant un type de service ClusterIP.

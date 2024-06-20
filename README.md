# Application Dockerisée avec Docker Compose et nginx

Ce projet utilise Docker Compose pour orchestrer plusieurs services Docker, chacun défini par un Dockerfile spécifique. Un serveur nginx est configuré pour rediriger les services.

## Utilisation

### Prérequis

Assurez-vous d'avoir Docker installé sur votre machine.

### Démarrage de l'Application

1. Clonez ce dépôt sur votre machine :
   ```bash
   git clone <URL-du-repository>
   cd <nom-du-dossier>

2. Construisez les différents conteneurs pour accéder à l'application :
   ```bash
   docker compose up

3. Accédédez à l'application via ces URL : 
   ```bash
   localhost (frontend)
   localhost/api (backend)

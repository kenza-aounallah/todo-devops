# TodoList

This is the code for the React crash course on YouTube

## Quick Start

```bash
# Install dependencies
npm install

# Serve on localhost:3000
npm start

# Build for production
npm run build
```
## Configuration Jenkins

Pour configurer Jenkins avec les plugins nécessaires, suivez les étapes ci-dessous :

### Plugins Requis

1. **Gestion de Code Source**
   - **Git Plugin** : Permet à Jenkins de s'intégrer avec Git.

2. **Serveur d'Automatisation**
   - **Pipeline** : Permet de configurer des pipelines CI/CD.
   - **Blue Ocean** : Nouvelle interface utilisateur pour une meilleure gestion des pipelines.

3. **Installer Dépendances NPM**
   - **NodeJS Plugin** : Permet de configurer et d'utiliser Node.js et npm dans vos builds.

4. **OWASP Dependency**
   - **OWASP Dependency-Check Plugin** : Scanne les dépendances de votre projet pour les vulnérabilités.

5. **Docker**
   - **Docker Plugin** : Permet à Jenkins de gérer les conteneurs Docker.
   - **Docker Pipeline Plugin** : Ajoute des étapes spécifiques Docker pour les pipelines Jenkins.

6. **Docker Hub**
   - **Docker Hub Notification** : Permet de recevoir des notifications de Docker Hub dans Jenkins.

7. **Minikube**
   - **Kubernetes Plugin** : Permet l'intégration avec Kubernetes, utile pour déployer sur Minikube.

### Instructions d'Installation

1. Accédez à Jenkins via `http://localhost:8080`.
2. Allez dans "Manage Jenkins" -> "Manage Plugins".
3. Installez les plugins listés ci-dessus en utilisant l'onglet "Available".
4. Redémarrez Jenkins si nécessaire après l'installation des plugins.

Pour plus de détails, consultez la documentation officielle de Jenkins.

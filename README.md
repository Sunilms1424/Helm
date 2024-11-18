# Helm
## Helm Instalation(latest release)
```
https://github.com/helm/helm/releases
```
## Helm Commands
- Creates a new Helm chart with the specified name
```
helm create <chartname>
```
- to check ths Syntax error in helm chart
```
helm lint <chartname>
```
- Renders templates locally without installing the chart
```
helm template <chartname>
```
- Lists all the installed Helm releases in the current namespace
```
helm list
```
## Chart instalation
- Installs a Helm chart with the specified release name.
```
helm install <release-name> <chartname>
```
- Upgrades an existing release to a new version of the chart
```
helm update <release-name> <chartname>
```
- Uninstalls a Helm release and deletes all its resources
```
helm delete <release-name>
```
- Rolls back a release to a previous version (rev=revision)
```
helm rollback <release-name> <rev>
```
- 	Shows the status of a specific Helm release
```
helm status <release-name>
```
## Helm Repository
- Adds a Helm chart repository by name and URL.
```
helm repo add <repo name> <repo url>
```
- Lists all configured chart repositories.
```
helm repo list
```
- Updates the information of all chart repositories locally
```
helm repo update
```
- Searches for charts in all configured repositories using a keyword
```
helm search repo <repo name>
```

this is an example for:
app of apps with kustomize featuring 3 environments. 
Each environment deploys to a different cluster.
All are managed in one argocd instance in a separate cluster.
Each environment has it's own root app which deploys the apps in overlays/<environment> to a project.
projects must be created to accomodate.
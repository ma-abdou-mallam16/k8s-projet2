## Vérification du context

```bash
kubectl config current-context
```

## Création du déploiement

```bash
kubectl apply -f deploy.yaml
```

## Statut du POD

```bash
kubectl get pod
```

## Création du service

```bash
kubectl apply -f premier-service.yaml
```

## Récupérer l'IP du node

```bash
kubectl get nodes -o=wide
```

## Connexion au navigateur

```bash
http://134.122.48.27:30000/
```

## Vérification si les services du contrôlleur d'ingress ont été créés

```bash
kubectl get svc -n ingress-nginx
```

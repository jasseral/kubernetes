Con esta herramienta podemos ver si estamos siguiendo buenas prácticas en nuestro cluster

# Cómo instalarlo:

kubectl apply -f https://github.com/FairwindsOps/polaris/releases/latest/download/dashboard.yaml
kubectl expose deployment polaris-dashboard --type=NodePort --name=polaris-dashboard  --port=80 --target-port=8080


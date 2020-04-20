
kubectl apply -f secrets.yaml -f config.yaml -f development.yaml -f service.yaml -f ingress.yaml -f postgres.yaml -f migrate.yaml


http://arch.homework/otusapp/v1/user/



kubectl apply  -f postgres.yaml -f migrate.yaml
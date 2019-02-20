# linuxtips-giropops

# Instruções
Criação namespace com limitação de recursos:   
kubectl create -f linuxtips/config/namespace.yml  

Criação do service:   
kubectl create -f linuxtips/config/services.yaml  

Deploy versões v1
kubectl create -f linuxtips/config/deployment.yaml 

Deploy Canary 
kubectl create -f linuxtips/config/deployment.canary.yaml

Deploy versão v2
kubectl create -f linuxtips/config/deployment.1.yaml


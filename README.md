# linuxtips-giropops

# Instruções
Criação namespace com limitação de recursos:   
kubectl create -f linuxtips/config/namespace.yml  

Criação do service:   
kubectl create -f linuxtips/config/services.yaml  

Deploy das versões v1 e v2:  
kubectl create -f linuxtips/config/deployment.yaml  
kubectl create -f linuxtips/config/deployment.1.yaml  


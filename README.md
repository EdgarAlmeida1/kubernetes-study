# Descrição

Estudo sobre Kubernetes usando o Kind localmente.
Dentro da pasta app temos a aplicação Go com o respectivo Dockerfile usado para construção e push.

# Tópicos estudados

Foram estudados os conceitos básicos de Kubernetes, como a criação de nodes usando o Kind. Além disso, 
usando o kubectl nos arquivos .yaml, temos a criação de pods, replicasets, services, deployments usando configmaps nas váriaveis
de ambiente e em arquivos criados nos pods e secrets. Ademais, foram estudados a criação de persistent volumes, com seus claims
no deployment, metrics server para a escalação horizontal dos pods e a criação de stateful sets com o MySQL e um headless service.
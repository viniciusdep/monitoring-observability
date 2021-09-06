# monitoring-observability
Stacks de monitoramento e observabilidade prontas para deploy no cluster 

- AlertManager: Pronto para enviar notificações no Slack, é possível configurar o configMap e service de acordo com a necessidade;

- Grafana: Imagem base do Grafana com deployment e service type: LoadBalancer;

- K8s: Contém deploy do NGINX e service ingress;

- Prometheus: Imagem base do Prometheus, é possível configurar o configMap e service de acordo com a necessidade.

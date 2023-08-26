# Zabbix Grafana
## _Stack para Monitoramento em Zabbix junto com Grafana_

### Este documento serve para criar uma stack de monitoramento com os softwares atualizados, deploy rápido para sua infraestrutura de rede, os serviços que compõe a stack são:

- Zabbix-Server (Latest)
- MySQL 8.0
- Zabbix-Agent (Latest)
- Zabbix-frontend (Latest)
- Grafana (Latest)

## Tecnologia para Utilizar junto

- Docker (Obrigatório)
- Docker Compose (Obrigatório)
- Portainer (*_Opcional para gerenciar conteiners_*)

## Instalação

Para a instalação é necessário o docker e o docker compose. 

Para efetuar a instalação

```sh
Git clone https://github.com/VictorGomesSec/Zabbix-Grafana
cd Zabbix-Grafana
docker compose up -d
```



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)
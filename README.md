# GRAFANA STACK FOR DOCKER MONITORING

## Stack

Grafana:9.1.3

Influxdb:2.6

Telegraf:1.25

## Instruções para subir o ambiente

```bash
I.   Subir os serviços:

docker compose up

II.  Renomear e editar as variáveis do arquivo de referencia 'env-example' para '.env':

cp env-example .env

II.  Adicionar e configurar o InfluxDB no Grafana.

OBS. O nome da organização no Grafana deve ser igual ao configurado no InfluxDB.
```

# Projeto de Monitoramento com Prometheus e Blackbox Exporter

Este projeto foi desenvolvido para testar o funcionamento do Prometheus com o Blackbox Exporter, visando monitoramento sintético de endpoints.

## Estrutura do Projeto

O projeto utiliza o Docker Compose para facilitar a configuração e execução dos serviços. A estrutura do projeto é a seguinte:


- **blackbox**: Contém o arquivo de configuração do Blackbox Exporter, onde endpoints de teste para monitoramento são cadastrados.

- **docker-compose.yml**: Arquivo de configuração do Docker Compose para a orquestração dos serviços Prometheus, Blackbox Exporter e Grafana.

- **grafana**: Contém os arquivos de configuração do Grafana, incluindo dashboards e configurações de datasources.

- **prometheus.yml**: Arquivo de configuração do Prometheus.

## Endpoints de Teste

Foram cadastrados alguns endpoints de teste para monitoramento.

## Acesso

- **Prometheus**: Acesse o Prometheus pelo [localhost:9090](http://localhost:9090).

- **Grafana**: Acesse o Grafana pelo [localhost:3000](http://localhost:3000) utilizando as credenciais:
  - Usuário: admin
  - Senha: admin

![Preview do Projeto](https://i.ibb.co/2WWnvHK/graficos-blackbox.png)

## Observações

Certifique-se de que o Docker e o Docker Compose estão instalados em seu ambiente antes de iniciar o projeto.

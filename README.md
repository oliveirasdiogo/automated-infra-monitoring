# automated-infra-monitoring
Automated monitoring stack using Docker Compose, Prometheus, Grafana, and Node Exporter for real-time infrastructure metrics collection.

# 📊 Stack de Monitoramento de Infraestrutura (Prometheus + Grafana)

Este repositório contém a configuração completa para implantar uma stack de monitoramento de infraestrutura local ou em nuvem de forma totalmente automatizada utilizando **Docker** e **Docker Compose**.

A stack monitora métricas do sistema operacional (CPU, Memória, Disco, Rede) em tempo real.

## 🛠️ Tecnologias Utilizadas

*   **Docker & Docker Compose**: Para containerização e orquestração dos serviços.
*   **Prometheus**: Banco de dados de séries temporais utilizado para coletar e armazenar as métricas.
*   **Grafana**: Ferramenta de análise e visualização de dados (Dashboards).
*   **Node Exporter**: Coletor de métricas de hardware e do sistema operacional para kernels Linux.

## 🚀 Como Executar o Projeto

### Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina:
*   [Docker](https://docs.docker.com/get-docker/)
*   [Docker Compose](https://docs.docker.com/compose/install/)

### Passo a Passo

1. Clone este repositório para sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/automated-infra-monitoring.git](https://github.com/SEU_USUARIO/automated-infra-monitoring.git)
   cd automated-infra-monitoring

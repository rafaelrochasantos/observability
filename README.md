 # Grafana Stack

 Este projeto implementa um stack de observabilidade utilizando Grafana, Loki, Tempo e Prometheus.

 ## Visão Geral

 O Grafana Stack é uma solução completa para monitoramento e observabilidade de aplicações e infraestrutura. Ele inclui os seguintes componentes:

 *   **Grafana:** Plataforma de visualização e análise de dados.
 *   **Loki:** Sistema de agregação e armazenamento de logs.
 *   **Tempo:** Sistema de rastreamento distribuído.
 *   **Prometheus:** Sistema de monitoramento e alertas.
 *   **Mimir:** Sistema de monitoramento e alertas.

 ## Tecnologias Utilizadas

 *   **Linguagem de Programação:** N/A (configuração YAML)
 *   **Bibliotecas/Frameworks:**
     *   Grafana
     *   Loki
     *   Tempo
     *   Prometheus
     *   Mimir

 ## Setup

 1.  Clone este repositório.
 2.  Instale Docker e Docker Compose.
 3.  Execute `docker-compose up --build -d` na raiz do projeto.
 4.  Acesse o Grafana em `http://localhost:3000`.

 ## Configuração

 A configuração dos datasources (Loki, Tempo, Prometheus e Mimir) é realizada através do arquivo `config/grafana/datasources.yaml`.

 ## Padrões de Projeto

 *   Infraestrutura como código (IaC)

 ## Contribuição

 Pull requests são bem-vindos. Para mudanças maiores, por favor, abra uma issue primeiro para discutir o que você gostaria de mudar.

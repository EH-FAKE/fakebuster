# fakebuster

Nosso projeto tem como objetivo implementar um pipeline baseado em RAG (Retrieval-Augmented Generation) para identificar e combater desinformação de forma automática. Utilizando técnicas de busca e modelos de linguagem, visando avaliar a veracidade de afirmações com base em dados confiáveis.

## Tecnologias utilizadas 

- **[Docker](https://www.docker.com/)**  
  Plataforma de containers que simplifica o empacotamento, distribuição e execução de aplicações em ambientes isolados. Garante consistência do ambiente de desenvolvimento à produção. Versão recomendada: 26.0.0

- **[RAGFlow](https://github.com/infiniflow/ragflow)**  
  Framework de orquestração de fluxos RAG (Retrieval-Augmented Generation), facilitando a integração entre fontes de dados e modelos de linguagem. Versão mais recente: v0.18.0

- **[NGROK](https://ngrok.com/)**  
  Ferramenta que cria túneis seguros para expor servidores locais à internet, muito usada para testes de APIs, aplicações web e integração com webhooks. Versão recomendada: 3.x

## Requisitos

- CPU >= 4 cores
- RAM >= 16 GB
- Disk >= 50 GB
- Docker >= 24.0.0 & Docker Compose >= v2.26.1
- Ragflow >= v0.18.0

Se precisar de auxílio para instalar esses componentes, consulte a documentação oficial de cada ferramenta:

- [Instalação do Docker](https://docs.docker.com/get-docker/)
- [Instalação do Ragflow](https://github.com/infiniflow/ragflow/)
- [Instalação do Ngrok](https://github.com/NGROK/)

## Estrutura do Projeto

- `configs/`: Configurações
- `ragflow_pipeline/`: Implementação principal

## Contribuição

Para contribuir com o projeto, siga as instruções no [Guia de Contribuição](docs/guia-de-contribuicao)


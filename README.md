# Repositório de Estudos em Desenvolvimento Moderno de Software

## Introdução

Bem-vindo(a) a este repositório! O objetivo deste projeto é centralizar todo o código, documentação e aprendizados adquiridos durante o estudo de tecnologias e práticas essenciais no desenvolvimento moderno de software[cite: 1]. O conteúdo aqui presente segue o roteiro do "Plano de Estudo Abrangente para Desenvolvimento Moderno de Software"[cite: 1].

Este repositório utiliza uma estrutura de **monorepo** gerenciada com **NX** para organizar os diferentes projetos e áreas de estudo, abrangendo backend, frontend, infraestrutura, e mais.

## Estrutura do Monorepo (Gerenciado com NX)

A estrutura de pastas visa refletir as principais áreas do plano de estudo, facilitando a navegação e a organização:

/
├── apps/                  # Aplicações completas ou exemplos principais
│   ├── backend-api/
│   └── frontend-ui/
├── libs/                  # Bibliotecas compartilhadas e módulos de estudo
│   ├── 01-ai-ides/        # Exemplos e notas sobre IA em IDEs (Cursor)
│   ├── 02-devops-iac/     # Dockerfiles, manifests K8s, configs Terraform
│   │   ├── docker/
│   │   ├── kubernetes/
│   │   └── terraform/
│   ├── 03-architecture/   # Implementações de padrões (MVC, Hexagonal, Clean, Multi-Tenancy)
│   │   ├── mvc-example/
│   │   ├── hexagonal-example/
│   │   ├── clean-arch-example/
│   │   └── multi-tenancy-concepts/
│   ├── 04-api-design/     # Exemplos de APIs REST, gRPC e configurações de Gateway
│   │   ├── rest-api-example/
│   │   ├── grpc-service-example/
│   │   └── api-gateway-configs/
│   └── shared/            # Código compartilhado entre libs ou apps
├── tools/                 # Scripts e ferramentas auxiliares
└── docs/                  # Documentação adicional, incluindo este README
└── plano-de-estudo.md # (Opcional: Cópia ou resumo do plano original)

* **`/apps`**: Contém aplicações completas ou exemplos de ponta a ponta que integram vários conceitos estudados.
* **`/libs`**: O coração do estudo, onde cada subdiretório corresponde a uma seção principal do plano de estudo[cite: 4, 5, 6, 7]. Aqui você encontrará implementações de código, configurações, notas e exemplos específicos para cada tópico.
* **`/tools`**: Utilitários e scripts de apoio ao desenvolvimento ou execução dos exemplos.
* **`/docs`**: Documentação geral, diagramas, e este README.

## Conteúdo e Áreas de Estudo

Este repositório abrange as seguintes áreas principais, conforme o plano de estudo:

1. **Aproveitando a IA para Aprimorar o Fluxo de Trabalho com IDEs (Cursor)**[cite: 4]: Exploração e exemplos de como usar IDEs potencializadas por IA, como o Cursor, para acelerar o desenvolvimento, gerar código, depurar e refatorar[cite: 11, 13, 17, 18].
    * Localização: `libs/01-ai-ides/`
2. **Dominando Containers, Orquestração e Pipelines de IaC**[cite: 5]: Estudo prático de Docker para containerização, Kubernetes (K8s) para orquestração e Terraform para Infraestrutura como Código [IaC](cite: 38, 67, 98).
    * Docker: Criação de imagens, Dockerfiles, Docker Compose[cite: 44, 45, 64].
    * Kubernetes: Conceitos (Pods, Deployments, Services), kubectl, escalonamento[cite: 78, 81, 83, 89, 96].
    * Terraform: Provisionamento de infraestrutura, gerenciamento de estado, integração com K8s[cite: 99, 108, 111].
    * Localização: `libs/02-devops-iac/`
3. **Explorando Padrões Modernos de Arquitetura de Software**[cite: 6]: Análise e implementação de padrões arquiteturais para construir sistemas robustos, testáveis e manuteníveis.
    * MVC [Model-View-Controller](cite: 130, 131, 132).
    * Arquitetura Hexagonal [Ports and Adapters](cite: 135).
    * Clean Architecture[cite: 150].
    * Multi-Tenancy: Estratégias e desafios[cite: 178, 180].
    * Localização: `libs/03-architecture/`
4. **Design Avançado de APIs e Tecnologias**[cite: 7]: Cobertura de princípios de design de API, tecnologias e padrões.
    * Princípios de Design de API: Consistência, orientação a recursos, tratamento de erros, versionamento[cite: 211].
    * APIs RESTful: Restrições, melhores práticas, métodos HTTP[cite: 222, 232, 233, 234, 235, 236].
    * gRPC: Protocol Buffers, HTTP/2, streaming, comparação com REST[cite: 239, 240, 241, 247].
    * API Gateway: Papel, funcionalidades (roteamento, segurança, rate limiting), padrões[cite: 252, 255].
    * Localização: `libs/04-api-design/`

## Como Usar

* Clone o repositório.
* Certifique-se de ter o Node.js e o NX CLI instalados.
* Explore as pastas `libs/` para encontrar código e notas sobre cada tópico de estudo.
* Execute os exemplos ou aplicações encontrados em `apps/` seguindo as instruções específicas de cada projeto (geralmente em um README dentro da pasta do app/lib).
* Utilize os comandos NX para build, teste e execução (ex: `nx build backend-api`, `nx serve frontend-ui`, `nx test shared`).

## Aprendizado Contínuo

Este repositório é um trabalho em progresso e será atualizado conforme o aprendizado avança[cite: 300]. Sinta-se à vontade para explorar, aprender e contribuir!

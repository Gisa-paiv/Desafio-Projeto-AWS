# Projeto: Otimização de Custos e Infraestrutura em AWS

Este projeto documenta a implementação de uma estratégia de otimização de custos e infraestrutura em AWS, com foco na utilização de serviços de rede e segurança para reduzir despesas operacionais imediatas.

##Objetivo

Elencar e implementar 3 serviços AWS para redução de custos imediatos, sem comprometer a segurança, a performance ou a escalabilidade da infraestrutura.

## Ferramentas Implementadas

### 1. Amazon VPC (Virtual Private Cloud)
- Foco: Isolamento e segmentação lógica de rede na nuvem.
- Caso de uso: Substituição de infraestrutura física por VPCs com sub-redes públicas e privadas, reduzindo custos com hardware e melhorando o controle de tráfego entre recursos.

### 2. AWS Direct Connect
- Foco: Conexão dedicada entre datacenter corporativo e AWS.
- Caso de uso: Migração de tráfego de VPN para link dedicado, reduzindo custos com banda larga comercial e melhorando a latência e a segurança das comunicações híbridas.

### 3. Security Groups e Network ACLs
- Foco: Segurança granular em nível de instância e sub-rede.
- Caso de uso: Substituição de firewalls de terceiros por controles nativos da AWS, eliminando custos com licenças e simplificando a gestão de regras de segurança.

## Resultados Esperados

- Redução imediata de custos com hardware, licenças e links de comunicação.
- Melhoria na segurança com controles nativos e segmentação de rede.
- Maior performance e confiabilidade na conectividade híbrida.
- Simplificação operacional com serviços gerenciados pela AWS.

## Estrutura do Repositório

- `/docs` – Documentação complementar e referências técnicas.
- `/diagrams` – Diagramas de arquitetura e fluxos de rede.
- `/scripts` – Scripts de automação (Terraform, CloudFormation, CLI).
- `/reports` – Relatórios de custos e métricas de performance.

## Conceitos Aplicados

- VPC e Sub-redes: Isolamento e organização de recursos.
- Conectividade Híbrida: VPN, Direct Connect e Internet Gateway.
- Segurança em Camadas: Network ACLs (stateless) e Security Groups (stateful).

## Referências

- [Documentação Oficial da Amazon VPC](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/what-is-amazon-vpc.html)
- [AWS Direct Connect – Página Oficial](https://aws.amazon.com/directconnect/)
- [Segurança em VPC: Security Groups e NACLs](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_SecurityGroups.html)

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções ou novos casos de uso.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Projeto desenvolvido com foco em boas práticas de arquitetura cloud e eficiência operacional.

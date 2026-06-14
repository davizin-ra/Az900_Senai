# AZ-900 - Microsoft Azure Fundamentals

## Conceitos de Computação em Nuvem

### Modelos de Nuvem
- Pública: recursos fornecidos por provedores via internet
- Privada: infraestrutura dedicada
- Híbrida: integração entre on-premises e nuvem
- Multicloud: uso de múltiplos provedores

### Modelos de Serviço
- IaaS: controle sobre SO, aplicações e dados
- PaaS: foco no desenvolvimento de aplicações
- SaaS: uso direto de software

### Modelo de Responsabilidade Compartilhada
- Segurança física: provedor
- Infraestrutura: provedor
- Sistema operacional: cliente (IaaS), provedor (PaaS/SaaS)
- Aplicações e dados: cliente

### Benefícios da Nuvem
- Alta disponibilidade
- Escalabilidade vertical e horizontal
- Elasticidade
- Tolerância a falhas
- Recuperação de desastre
- Alcance global

### Tipos de Escala
- Escala vertical: aumento de recursos em uma máquina
- Escala horizontal: adição de novas instâncias

### CapEx vs OpEx
- CapEx: investimento inicial
- OpEx: pagamento sob demanda

---

## Arquitetura do Azure

### Estrutura de Recursos
- Resource Group: agrupamento lógico de recursos
- Subscription: unidade de cobrança
- Management Group: organização de múltiplas subscriptions

### Regiões e Disponibilidade
- Região: localização geográfica
- Zona de disponibilidade: isolamento físico dentro da região
- Region pairs: regiões emparelhadas para recuperação

---

## Serviços de Computação

- Virtual Machines: controle total (IaaS)
- Virtual Machine Scale Sets: escalabilidade automática
- App Service: hospedagem web (PaaS)
- Azure Functions: execução baseada em eventos
- Azure Container Instances: execução de containers sem orquestração
- Azure Kubernetes Service (AKS): orquestração de containers

---

## Serviços de Armazenamento

### Tipos
- Blob Storage: objetos
- File Storage: compartilhamento SMB
- Queue Storage: mensageria
- Table Storage: NoSQL

### Redundância
- LRS (Locally Redundant Storage)
- ZRS (Zone-Redundant Storage)
- GRS (Geo-Redundant Storage)
- RA-GRS (Read-Access Geo-Redundant)

### Camadas
- Hot
- Cool
- Archive

---

## Serviços de Rede

- Virtual Network (VNet)
- Subnets
- Network Security Groups (NSG)
- Azure Firewall
- Load Balancer (camada 4)
- Application Gateway (camada 7)
- VPN Gateway
- ExpressRoute (conexão privada)
- DNS

---

## Identidade, Segurança e Acesso

### Azure Active Directory (Entra ID)
- Gerenciamento de identidade
- SSO
- Integração com serviços

### Autenticação
- MFA
- Passwordless
- Conditional Access

### Autorização
- RBAC

### Segurança
- Defender for Cloud
- Azure Sentinel (SIEM)
- Key Vault (gerenciamento de segredos)

---

## Governança e Compliance

- Azure Policy: controle e conformidade
- Blueprints: implantação padronizada
- Resource Locks: proteção contra exclusão
- Tags: organização e controle de custos

---

## Monitoramento

- Azure Monitor
- Log Analytics
- Alerts
- Metrics

---

## Custos e Gerenciamento Financeiro

- Pay-as-you-go
- Reserved Instances
- Spot Instances
- Pricing Calculator
- Total Cost of Ownership (TCO)
- Cost Management + Billing

---

## SLA e Ciclo de Vida

- SLA define disponibilidade garantida
- Aumenta com redundância e múltiplas instâncias
- Serviços sem SLA: geralmente gratuitos

---

## Ferramentas de Gerenciamento

- Azure Portal
- Azure CLI
- Azure PowerShell
- ARM Templates (Infraestrutura como código)
- Bicep

---

## Conceitos Adicionais

### Alta Disponibilidade
- Uso de zonas
- Balanceamento de carga
- Replicação

### Recuperação de Desastre
- Backup
- Replicação geográfica
- Failover

### Migração
- Azure Migrate
- Estratégias: rehost, refactor, rearchitect

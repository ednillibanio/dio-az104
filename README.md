# DIO - Curso AZ-104

## Resumo para Certificação AZ-104 - Microsoft Azure Administrator

A certificação **AZ-104** é voltada para **administradores de Azure**, responsáveis por gerenciar serviços de nuvem como computação, armazenamento, redes e segurança dentro do Azure.

## 📚 Conteúdo por Domínio

### 1. Gerenciar Identidades e Governança no Azure (15-20%)

#### Azure Active Directory (Azure AD)
- **Definição:** Serviço de gerenciamento de identidades e acessos baseado em nuvem.
- **Principais funções:**
  - Gerenciar usuários e grupos.
  - Controlar autenticação.
  - Implementar SSO (Single Sign-On).

#### RBAC (Role-Based Access Control)
- **Definição:** Controle de permissões baseado em funções.
- **Exemplo:** Um usuário com papel de "Reader" só pode visualizar recursos.

#### Azure Policies
- **Definição:** Regras que controlam a criação e configuração de recursos no Azure.
- **Exemplo:** Bloquear criação de VMs em regiões fora do Brasil.

#### Azure Blueprints
- **Definição:** Conjunto de definições como RBAC, políticas, modelos ARM e recursos para padronizar a implantação.

#### Subscription e Management Groups
- **Subscription:** Contêiner para recursos.
- **Management Groups:** Agrupam múltiplas subscriptions para gestão centralizada.

---

### 2. Implementar e Gerenciar Armazenamento (15-20%)

#### Azure Storage Account
- **Tipos:** Blob, File Share, Table, Queue.
- **Performance:** Standard e Premium.
- **Redundância:** LRS, ZRS, GRS, RA-GRS.

#### Azure Blob Storage
- **Blobs:** Dados não estruturados (ex.: imagens, vídeos).
- **Tipos:** Block Blob, Append Blob, Page Blob.

#### Azure Files
- **File Share:** Compartilhamento de arquivos SMB para uso como file server.

#### Storage Access
- **SAS Token:** Acesso temporário e restrito a recursos.
- **Access Keys:** Chaves de acesso à conta de armazenamento.

#### Azure Storage Explorer
- **Ferramenta:** Interface gráfica para gerenciar contas de armazenamento.

---

### 3. Implantar e Gerenciar Recursos de Computação do Azure (20-25%)

#### Azure Virtual Machines (VMs)
- **Criação:** Via portal, CLI, PowerShell ou ARM Templates.
- **Tamanhos:** Exemplo: B, D, E, F series.

#### Availability Sets e Availability Zones
- **Availability Sets:** Alta disponibilidade dentro de um datacenter.
- **Availability Zones:** Alta disponibilidade entre diferentes zonas físicas.

#### Azure VM Scale Sets
- **Definição:** Escalonamento automático horizontal de VMs.

#### Azure App Services
- **Definição:** Serviço PaaS para hospedar aplicações web.

#### Azure Container Instances (ACI)
- **Definição:** Executar containers Docker sem provisionar VMs.

#### Azure Kubernetes Service (AKS)
- **Definição:** Orquestração de containers Kubernetes no Azure.

---

### 4. Configurar e Gerenciar Redes Virtuais (20-25%)

#### Virtual Network (VNet)
- **Definição:** Rede privada no Azure.
- **Componentes:** Subnets, NSG, Route Tables.

#### Network Security Groups (NSG)
- **Definição:** Firewall de nível de rede.
- **Funcionalidade:** Permitir ou negar tráfego.

#### Azure VPN Gateway
- **Definição:** Conexão entre Azure e local (on-premises) via VPN.

#### Azure ExpressRoute
- **Definição:** Conexão dedicada de alta performance entre local e Azure.

#### Azure Load Balancer
- **Definição:** Balanceador de carga L3/L4.

#### Azure Application Gateway
- **Definição:** Balanceador L7 com WAF integrado.

#### Azure DNS
- **Definição:** Gerenciamento de zonas e registros DNS na nuvem.

#### Private Endpoints
- **Definição:** Acesso privado a serviços PaaS via rede interna.

---

### 5. Monitorar e Fazer Backup de Recursos do Azure (10-15%)

#### Azure Monitor
- **Definição:** Monitoramento de desempenho e integridade.
- **Componentes:**
  - Metrics: Métricas numéricas.
  - Logs: Dados detalhados (ex.: Activity Log, Diagnostic Logs).

#### Azure Log Analytics
- **Definição:** Consulta e análise de logs.

#### Azure Alerts
- **Definição:** Alertas baseados em condições de métricas ou logs.

#### Azure Backup
- **Definição:** Solução de backup para VMs, bancos de dados e arquivos.

#### Azure Site Recovery (ASR)
- **Definição:** Solução de Disaster Recovery para replicar VMs para outra região.

---

### 6. Gerenciar Recursos do Azure com Ferramentas (10-15%)

#### Azure Resource Manager (ARM)
- **Definição:** Framework de gerenciamento de recursos.
- **Uso:** Implantação com Templates ARM.

#### Azure CLI
- **Definição:** Ferramenta de linha de comando multiplataforma.

#### Azure PowerShell
- **Definição:** Conjunto de cmdlets para administração de Azure via PowerShell.

#### Azure Cloud Shell
- **Definição:** Shell interativo disponível no portal Azure.

#### ARM Templates
- **Definição:** Infraestrutura como código (IaC) baseada em JSON.

#### Azure REST API
- **Definição:** API HTTP para operações administrativas.

---

### 7. Gerenciar Custo e Monitoramento de Recursos (10-15%)

#### Azure Cost Management
- **Definição:** Monitoramento, análise e otimização de custos do Azure.

#### Azure Budgets
- **Definição:** Definir orçamentos e receber alertas ao atingir limites.

#### Resource Tags
- **Definição:** Etiquetas para categorização de recursos.

#### Azure Advisor
- **Definição:** Recomendações sobre custo, segurança, performance e alta disponibilidade.

---

## ✅ Dicas Finais para Prova

- Conheça **bem o Portal Azure**, **CLI**, **PowerShell** e **ARM Templates**.
- Foque em **conceitos práticos**, especialmente cenários de administração.
- Entenda **modelos de disponibilidade**, **backup**, **segurança** e **gestão de custo**.

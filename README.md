# 💼 Laboratório de Ferramentas de Gerenciamento e Implantação no Azure

Neste laboratório, exploraremos as principais ferramentas de gerenciamento e implantação do Azure. Através dessas ferramentas, é possível implementar, monitorar e gerenciar seus recursos de maneira centralizada e organizada.

---

## 🔧 Visão Geral das Ferramentas de Gerenciamento e Implantação

### <span style="color:blue;">🛠️ Azure Resource Manager (ARM)</span> ![Badge](https://img.shields.io/badge/Azure%20Resource%20Manager-ARM-blue)
**Azure Resource Manager (ARM)** é a base de gerenciamento do Azure. Ele organiza os recursos em **Grupos de Recursos**, facilita a automação e permite o controle de acesso detalhado.

**Atividade**: Acesse o **Portal do Azure** e crie um novo **Grupo de Recursos**. Adicione alguns recursos como uma conta de armazenamento para organizar e agrupar seu ambiente.

---

### <span style="color:orange;">📜 Bicep</span> ![Badge](https://img.shields.io/badge/Bicep-Declarative%20Language-orange)
**Bicep** é uma linguagem declarativa que facilita a criação de templates para implantar e gerenciar recursos Azure de maneira simplificada e repetível.

**Atividade**: No **Azure Cloud Shell**, crie um arquivo `.bicep` e defina os parâmetros para criar uma máquina virtual. Após configurar o código, execute o template no grupo de recursos para provisionar a máquina virtual.

---

### <span style="color:yellowgreen;">💻 Azure CLI</span> ![Badge](https://img.shields.io/badge/Azure%20CLI-Command%20Line%20Tool-yellowgreen)
**Azure CLI** é uma interface de linha de comando que permite interagir com o Azure através de scripts e automação.

**Atividade**: No **Cloud Shell**, use comandos `az` para listar seus grupos de recursos e criar uma máquina virtual. Teste operações básicas como listar VMs e recursos.

---

### <span style="color:lightblue;">📑 Azure PowerShell</span> ![Badge](https://img.shields.io/badge/Azure%20PowerShell-Management%20Automation-lightblue)
**Azure PowerShell** é uma ferramenta em linha de comando, ideal para administradores que já estão familiarizados com PowerShell e preferem um ambiente integrado para gerenciar recursos Azure.

**Atividade**: Execute scripts de **Azure PowerShell** para criar e configurar recursos, como uma conta de armazenamento e uma máquina virtual.

---

### <span style="color:red;">🔒 Azure Policy</span> ![Badge](https://img.shields.io/badge/Azure%20Policy-Governance%20and%20Compliance-red)
**Azure Policy** é uma ferramenta para governança e conformidade, que permite implementar políticas em grupos de recursos, garantindo a consistência e a segurança da infraestrutura.

**Atividade**: Acesse o **Azure Policy** no portal e defina uma política, como restringir a criação de recursos fora de uma região específica. Aplique a política ao seu grupo de recursos.

---

### <span style="color:purple;">📐 Azure Blueprints</span> ![Badge](https://img.shields.io/badge/Azure%20Blueprints-Template%20Management-purple)
**Azure Blueprints** são modelos predefinidos que facilitam a criação e a configuração de ambientes Azure complexos e consistentes.

**Atividade**: Crie um blueprint que inclua políticas e permissões para um ambiente de desenvolvimento. Aplique o blueprint em um grupo de recursos específico.

---

## 📋 Conclusão do Laboratório

Este laboratório forneceu uma visão geral das ferramentas de gerenciamento e implantação no Azure, cobrindo desde a organização e criação de recursos até a configuração de políticas e governança. Essas ferramentas são essenciais para otimizar o uso e a segurança dos recursos do Azure.

> 🔗 **Recursos Adicionais**:
> - [Azure Resource Manager (ARM)](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/)
> - [Azure CLI](https://docs.microsoft.com/pt-br/cli/azure/)
> - [Azure PowerShell](https://docs.microsoft.com/pt-br/powershell/azure/)
> - [Azure Policy](https://docs.microsoft.com/pt-br/azure/governance/policy/)
> - [Azure Blueprints](https://docs.microsoft.com/pt-br/azure/governance/blueprints/)

Experimente cada ferramenta e encontre a melhor combinação para suas necessidades de gerenciamento e governança no Azure!

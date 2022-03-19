m04-SegGov
# IGTI - MBA Cloud: criação de ambiente no Azure com usuários, permissões, VNets, VMs e segurança

## Criação de usuários no Azure AD

![image](https://user-images.githubusercontent.com/101406714/159141366-bd176b6e-d219-474a-87df-adfb6d041abd.png)

## Definição de permissões para os usuário no Azure AD
**Grupo "Administradores" com permissão total no Azure AD "Global administrator"**

![image](https://user-images.githubusercontent.com/101406714/159141693-a37cdf1b-b96b-4ce1-8e41-c8770294888a.png)

![image](https://user-images.githubusercontent.com/101406714/159141945-f7c174b7-c904-4968-a811-caaaf1deb151.png)

**Grupo "Admin Redes" com permissão de apenas consulta aos recursos do Azure AD "Global reader"**

![image](https://user-images.githubusercontent.com/101406714/159141840-a9e76ed6-257e-43b5-8519-216f525be4bb.png)

![image](https://user-images.githubusercontent.com/101406714/159141890-24002586-bb36-4b70-8c58-75866aa6987a.png)

## Habilitação de MFA para usuários

## Definição de permissão total no Azure RBAC (Role Based Access Control)

## Definição de políticas (Azure Policy)
**Delimitação da criação de recursos em regiões específicas**

## Criação de Rede Virtual (VNet) e Sub-redes (Subnet)

## Provisionamento de Máquinas Virtuais (VMs)
**- Máquina 01**
  - Nome: VM-01-MODULO4
  - Tamanho: B1MS
  - LOCAL: Brasil-South
  - Sistema Operacional: Windows 10
  - Rede: SUBNET-01

**- Máquina 02**
  - Nome: VM-02-MODULO4
  - Tamanho: B1MS
  - LOCAL: Brasil-South
  - Sistema Operacional: Windows 10
  - Rede: SUBNET-02

## Definições de Segurança - NSG (Network Security Group)

## Criação de Key Vault para armazenar as senhas dos servidores em Secrets

## Criptografia dos discos das VMs utilizando DES (Disk Encryption Set) no padrão RSA 3072

##
**André Carlucci**

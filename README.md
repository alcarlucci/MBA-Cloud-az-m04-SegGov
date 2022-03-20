m04-SegGov
# IGTI - MBA Cloud: criação de ambiente no Azure com usuários, permissões, políticas, segurança e alguns recursos

## Criação de usuários no Azure AD

![image](https://user-images.githubusercontent.com/101406714/159141366-bd176b6e-d219-474a-87df-adfb6d041abd.png)

## Definição de permissões para os usuário no Azure AD
**Grupo "Administradores" com permissão total no Azure AD "Global administrator"**

![image](https://user-images.githubusercontent.com/101406714/159141693-a37cdf1b-b96b-4ce1-8e41-c8770294888a.png)

![image](https://user-images.githubusercontent.com/101406714/159141945-f7c174b7-c904-4968-a811-caaaf1deb151.png)

**Grupo "Admin Redes" com permissão de apenas consulta aos recursos do Azure AD "Global reader"**

![image](https://user-images.githubusercontent.com/101406714/159141840-a9e76ed6-257e-43b5-8519-216f525be4bb.png)

![image](https://user-images.githubusercontent.com/101406714/159141890-24002586-bb36-4b70-8c58-75866aa6987a.png)

## Habilitação de MFA para usuários administradores

**Ativação do MFA**
![image](https://user-images.githubusercontent.com/101406714/159166650-bef536c0-4e2b-4b21-b099-03b7d71bcdc6.png)

**Ativação do Alerta de Fraude e bloqueio de conta por reporte de fraude**
![image](https://user-images.githubusercontent.com/101406714/159171660-78b1da94-9405-4898-8cc6-3d67d71fe088.png)

## IAM: definição de permissões no Azure RBAC (Role Based Access Control)
**Atribuição de Funções (IAM - roles) a um determinado Grupo de Recursos:**
- User1 -> "Contributor": permissão total aos recursos, exceto atribuições no Azure RBAC
- User2 -> "Reader": apenas permissão de leitura aos recursos
- User3 -> "Owner": permissão total aos recursos, incluindo atribuições no Azure RBAC

![image](https://user-images.githubusercontent.com/101406714/159176444-f45c4a32-3a7a-4d3b-8bcf-70e25aca3f91.png)

## Definição de políticas (Azure Policy)
**Delimitação da criação de recursos em regiões específicas**
- Azure Policy delimitando criação de recursos apenas nas Regiões "Brasil-South" e "East-US"

![image](https://user-images.githubusercontent.com/101406714/159179692-ba8d522e-8596-4d8f-84fd-f59332a51153.png)

- Negação na criação de um recurso (VNet) fora da conformidade definida na política

![image](https://user-images.githubusercontent.com/101406714/159181705-cf310345-e504-41c0-8503-67d244e8f2b0.png)

## Criação de Rede Virtual (VNet) e Sub-redes (Subnet)
![image](https://user-images.githubusercontent.com/101406714/159183885-93c6c209-9084-4962-b27e-3cc4fa1773bb.png)
![image](https://user-images.githubusercontent.com/101406714/159184347-49c8b38a-f530-4b1c-a8d3-a06f85719214.png)

## Provisionamento de Máquinas Virtuais (VMs)
**- Máquina 01**
  - Nome: VM-01-MODULO4
  - Tamanho: B1S
  - LOCAL: East-US
  - Sistema Operacional: Windows 10
  - Rede: SUBNET-01

![image](https://user-images.githubusercontent.com/101406714/159185842-0f47141c-1101-42a1-8263-505662b59bb3.png)

**- Máquina 02**
  - Nome: VM-02-MODULO4
  - Tamanho: B1S
  - LOCAL: East-US
  - Sistema Operacional: Windows 10
  - Rede: SUBNET-02

![image](https://user-images.githubusercontent.com/101406714/159186117-8b255c2b-7801-4b29-b796-f1beec56b3c5.png)

## Definições de Segurança - NSG (Network Security Group)

## Criação de Key Vault para armazenar as senhas dos servidores em Secrets

## Criptografia dos discos das VMs utilizando DES (Disk Encryption Set) no padrão RSA 3072

##
**André Carlucci**

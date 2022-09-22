# Azure AD Domain Services
👉 

🔖 Alguns requisítos
* Máquina virtual para gerenciar o serviço ou uma máquina que acesse a rede do Azure para gereciamento
* Uma virtual network com uma Subnet específica para o serviço
* Configuração de DNS
* As VNETs precisam levar os endereços de IPs do Active directory Domins Servers para que todas as vms
  consigam chegar até o domínio.

👉 Virtual Network

![aadds03](images/aadds03.png)
![aadds04](images/aadds04.png)

👉 Virtual Machine
* Crie uma VM simples para realizar o gerenciamento do AADDS

👉 AADDS
 * Esse processo pode demorar até duas horas.
  
![aadds05](images/aadds05.png)
![aadds06](images/aadds06.png)
![aadds07](images/aadds07.png)
![aadds08](images/aadds08.png)
![aadds09](images/aadds09.png)

* Clique aqui para fazer a correção nos registros de DNS na VNET
![aadds10](images/aadds10.png)
![aadds11](images/aadds11.png)
![aadds12](images/aadds12.png)
![aadds13](images/aadds13.png)

* Valide a configuração na VNET

![aadds14](images/aadds14.png)

👉 Conforme dito, é preciso alterar as senhas dos usuários
* Altere a senha do usuário que foi cadastrado para administrar o AADDS

👉 Insira a VM no domínio com esse usuário ou qualquer usuário dentro do grupo abaixo:

![aadds15](images/aadds15.png)
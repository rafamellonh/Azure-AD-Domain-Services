# Azure AD Domain Services
👉 

🔖 Diferenças AAD X AADDS X ADDS

👉 Azure Active Directory (AAD)
* O Microsoft Azure Acitive Directory é uma solução de nuvem de gerenciamento de acesso e identidade abrangente que combina os
principais serviços de diretório, gerencimaneto do acesso de aplicativos e proteção de identidade avançada.
* Sincroniza usuários e grupos do ADDS utilisando o Azure AD Connect

👉 Azure Active Directory Domain Services (AADDS)
* O Azure Active Directory Domain Services é um serviço autônomo no Azure que habilita um serviço de diretório, sem necessidade de
  configurar um servidor controlador de domínio. Ele cria um controlador de domínio como um serviço, você não precisa se preocupar 
  com tempo de inatividade, patching ou outras coisas
* Sincroniza usuários e grupos automaticamente do AAD.

👉 Active Directory Domain Services (On-premises)
* O Active Directory Domain Services (ADDS) é o principal serviço de diretórios da Microsoft e base para as novas tecnologias de cloud.
  O ADDS usa um armazenamento de dados estruturado como base para uma organização lógica e hierárquica de informações de diretório.
* Pode sincronizar seus usuários e grupos com AAD utilizando o Azure AD Connect
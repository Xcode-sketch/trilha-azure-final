# trilha-azure-final

### Dominando uma Nuvem: Um Guia Básico sobre o Microsoft Azure
O Microsoft Azure é uma das maiores plataformas de computação em nuvem do mercado, oferecendo um portfólio de mais de 200 serviços que permitem que empresas e desenvolvedores criem, implementem e gerenciem aplicações em uma infraestrutura mundial. Este guia está cheio de resumos, anotações e dicas essenciais para quem quer começar ou aprofundar seus conhecimentos sobre o universo Azure.

### Resumos Essenciais: Os Pilares do Azure
Para que a gente entenda o Azure, é relevante ter noção dos seus serviços e conceitos básicos, que são distribuídos em vários modelos:

### Infraestrutura como Serviço (IaaS): Lá, o Azure offers the virtualized compute infrastructure, including servers (Virtual Machines), storage and networking. The system OS, applications, and data management are left to the user. It is the best choice for starting from existing workloads and transporting to the cloud with increased control.

### Platform as a Service (PaaS): The Azure sits on top of the infrastructure, including operating systems and development tools, so the developers only get to work on the design and managing of their applications. Examples of such a type of service include the Azure App Service and Azure SQL Database.

Software como Serviço (SaaS): Um Microsoft aloca e gerencia integralmente a aplicação, que é entregue aos usuários através da internet. Exemplos típicos são o Microsoft 365 e o Dynamics 365.

Principais Categorias de Serviços:

### Computação: Máquinas Virtuais (VMs), Azure Kubernetes Service (AKS) para orquestração de contêineres e Azure Functions para computação sem servidor.

### Armazenamento: Armazenamento de Blobs para não estruturados dados, Arquivos do Azure para arquivos compartilhamentos na nuvem e Armazenamento de Discos para VMs.

### Banco de Dados: Banco de Dados SQL do Azure (PaaS), Azure Cosmos DB (banco de dados NoSQL multimodelo) e serviços gerenciados para MySQL e PostgreSQL.

### Rede: Rede Virtual (VNet) para recursos isolamento, Balanceador de Carga para distribuir o tráfego e Gateway de Aplicativo como um aplicativo web firewall.

IA e Machine Learning: Serviços Cognitivos para adicionar inteligência de funcionalidade (visão, fala, linguagem) e Azure Machine Learning para criar e aprender modelos personalizados.

Anotações para Iniciantes: Conceitos-Chave a Dominar
Para embarcar nos primeiros passos no Azure, concentre-se em aprender a estrutura organizacional e os elementos fundamentais de segurança:

Grupos de Recursos (Resource Groups): São contêineres lógicos que compreendem recursos correlacionados do Azure, como VMs, contas de armazenamento e redes virtuais. Eles permitem gerenciamento, monitoramento e controle de acesso e são cruciais para o controle de custos. Lembre-se de que um recurso pode somente ser pertencente a um grupo de recursos único.

Redes Virtuais (VNet): O básico para segurança e isolamento, as VNets tornam possíveis que os recursos do Azure se comuniquem de forma segura entre si, com a internet e com redes locais. Possível segmentar uma VNet em sub-redes para organização maior e segurança maior.

Identidade e Acesso (Azure Active Directory - Azure AD): O Azure AD é a gestão de identidade e acesso na nuvem da Microsoft. Ele é fundamental para autenticar os utilizadores e controlar o acesso aos recursos.

Multifactor Autenticação (MFA): Uma camada de segurança essencial que apresenta um segundo tipo de autenticação de identidade, como um código de celular, ao lado da senha. A habilitação do MFA é uma das primeiras e mais importantes medidas de segurança a serem tomadas.

Microsoft Defender para Cloud: Uma solução para o gerenciamento de postura de segurança e defesa contra ameaças. Ele verifica continuamente seus recursos em busca de fraquezas e fornece sugestões para sua segurança aprimorada.

Dicas e Melhores Práticas para Uso Eficiente
Para obter o máximo de produção a partir do uso, siga as seguintes dicas e melhores práticas de segurança e gestão de custos:

## Segurança:
Treat an Identity as the Primary Perimeter: Security in a cloud environment is shifted from the network to identity. Leverage Azure AD to centralize identity management.

Utilize Role-Based Access Control (RBAC): Assign users only the rights they require to do their jobs (principle of least privilege). Refrain from assigning permissions directly to users; utilize Azure AD groups instead.

Enable o Acesso Condicional: Crie políticas que aproveitem condições específicas (por exemplo, localização do usuário, dispositivo) antes de permitir acesso às aplicações e dados.

Manter a Segurança da Rede: Utilize Grupos de Segurança de Rede (NSGs) para bloquear o tráfego de e para os recursos dentro de uma VNet. Ponderate o uso do Firewall do Azure por uma proteção mais robusta.

Utilize o Azure Key Vault: Armazene e gerencie segredos, chaves de criptografia e certificados de forma segura, em vez de mantê-los em seu código ou arquivos de configuração.

## Otimização de Custos:
Desligue Recursos Não Utilizados: Às vezes, pode parecer evidente, mas recursos como VMs de desenvolvimento e testes são muitas vezes mantidos ligados indevidamente. Automatice o desligamento desses recursos fora da jornada de trabalho.

Redimensione Subutilizados Recursos: Monitor ou uso de seus recursos, como VMs e banco de dados, e configure seu tamanho (SKUs) para alinhá-lo com o demanda real, sem provisionamento excessivo.

Aproveite avaliadas Reservas do Azure e Plano de Poupança: Para projetos de carga estáveis, comprometa-se com o uso de um ou três anos de serviços específicos para obter descontos significativos em relação ao preço do pagamento em um uso.

Use o Benefício Híbrido do Azure: Se você já possui licenças para Windows Server ou SQL Server com Software Assurance, pode usá-las no Azure para economizar com seus custos de licenciamento.

Guiie seus Gastos com o Microsoft Cost Management: Use as ferramentas do Azure para avaliar, gerenciar e otimizar seus custos na cloud. Crie orçamentos e alertas para ser notificado quando os gastos ultrapassarem certos níveis.

Ao dominar esses conceitos fundamentais e aplicar as dicas de segurança e otimização de custos, você estará bem posicionado para aproveitar todo o poder e a flexibilidade que a plataforma Microsoft Azure tem a oferecer.

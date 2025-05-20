# resumo-lab-CloudAzure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Conceitos de Nuvem
Durante o lab, aprendi que a Microsoft Azure é uma poderosa plataforma de computação em nuvem que oferece diversos serviços, como máquinas virtuais, bancos de dados, armazenamento, redes e inteligência artificial. Ela suporta diferentes modelos de serviço em nuvem:

- IaaS (Infraestrutura como Serviço): onde o usuário gerencia sistemas operacionais e aplicativos, enquanto a Azure fornece a infraestrutura.

- PaaS (Plataforma como Serviço): a Azure oferece um ambiente completo para desenvolver e hospedar aplicações sem se preocupar com a infraestrutura.

- SaaS (Software como Serviço): são soluções prontas que podem ser usadas diretamente pela internet, como o Microsoft 365.

Também entendi a diferença entre CapEx e OpEx:

- CapEx (Capital Expenditure) representa os gastos com compra de servidores e infraestrutura própria.

- OpEx (Operational Expenditure) são custos operacionais recorrentes, como pagar apenas pelo uso dos recursos na nuvem — o que traz mais flexibilidade, escalabilidade e economia.

Outro ponto importante foi entender o Modelo de Responsabilidade Compartilhada, que define quem é responsável por cada parte da segurança e operação na nuvem:

- A Azure cuida da segurança da nuvem (infraestrutura, data centers, redes).

- O cliente é responsável pelo que está na nuvem (dados, usuários, permissões, configurações e aplicações).

A responsabilidade do cliente varia de acordo com o modelo adotado:

- Em IaaS, ele gerencia mais componentes (como SO e apps).

- Em PaaS, a responsabilidade diminui e foca mais nos dados e código.

- Em SaaS, o provedor assume quase tudo, e o cliente cuida do uso e acessos.

Por fim, explorei os principais benefícios da nuvem Azure:

- Escalabilidade e Elasticidade: é possível ajustar os recursos conforme a demanda, garantindo desempenho e economia.

- Confiabilidade, Previsibilidade e Segurança: a nuvem da Azure oferece alta disponibilidade, proteção de dados e previsibilidade de custos.

- Governança e Gerenciabilidade: a plataforma permite controlar, monitorar e automatizar o ambiente com segurança e conformidade.

Esse conteúdo reforçou como a computação em nuvem transforma a forma como as empresas operam, tornando os ambientes mais ágeis, seguros e eficientes.

## Infraestrutura na Azure com VM e DB
Durante esse projeto, tive a oportunidade de criar e configurar meus primeiros recursos na Microsoft Azure, colocando em prática os conceitos aprendidos no lab da DIO.

O que foi realizado:

- Máquina Virtual (VM): Criei minha primeira VM na Azure, configurando sistema operacional, rede e regras de acesso.

- Banco de Dados: Implementei uma instância de banco de dados totalmente gerenciada, simulando um ambiente real de aplicação.

- Grupo de Recursos: Organizei todos os recursos criados dentro de um Resource Group, facilitando o gerenciamento, controle de custos e governança.

Esse processo me ajudou a entender na prática como provisionar recursos na nuvem, gerenciar infraestrutura como serviço (IaaS) e aplicar boas práticas de organização e segurança na Azure.

### VM Cloud Azure
![Detalhes da Virtual Machine](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/vm%20detalhes.png)

### Banco de Dados Cloud Azure
![Detalhes Database](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/db%20detalhes.png)

### Resource Group Cloud Azure
![Detalhes Resource Group](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/grupo%20de%20recursos%20com%20itens.png)

## Computação na Azure
A plataforma oferece diferentes formas de executar cargas de trabalho, como:

- Máquinas Virtuais (VMs): instâncias completas de sistema operacional, ideais para controle total do ambiente.

- Contêineres: leves, portáveis e rápidos, ideais para microsserviços e aplicações modernas.

- Azure Functions: modelo serverless, onde você paga apenas pelo tempo de execução do código.

Opções de hospedagem de aplicativos:

- Web Apps: hospedagem gerenciada para aplicações web com alta escalabilidade e integração contínua.

- Contêineres: usados com serviços como Azure Kubernetes Service (AKS).

- Máquinas Virtuais: opção mais flexível, mas exige mais gestão.

Redes e conectividade:

- Redes Virtuais (VNets): isolam e controlam a comunicação entre recursos.

- Sub-redes: divisão lógica dentro da VNet.

- Emparelhamento de rede (Peering): conecta redes virtuais diferentes.

- DNS e VPN Gateway: permitem personalizar nomes de rede e conectar ambientes locais com a nuvem.

- ExpressRoute: conexão privada e dedicada à Azure, com maior velocidade e segurança.

## Segurança Cloud Azure

Identidade, Acesso e Segurança: são pilares fundamentais para proteger os recursos na nuvem. A Azure permite gerenciar quem pode acessar o quê, como e em quais condições.

Microsoft Entra ID (antigo Azure AD): é o serviço de gerenciamento de identidades e diretórios da Microsoft. Permite criar e gerenciar usuários, grupos, permissões, logins únicos (SSO) e integrações com apps corporativos.

O Domain Services permite usar políticas de domínio do AD tradicional, sem a necessidade de servidores locais.

Autenticação e Autorização:

- Autenticação: processo de verificar a identidade do usuário (ex: login com senha ou MFA).

- Autorização: define o que o usuário pode fazer após ser autenticado (permissões e papéis).

- Acesso Condicional: mecanismo que aplica políticas de segurança com base em condições específicas (ex: bloquear login de locais não confiáveis, exigir autenticação multifator fora do horário comercial, etc.).

## IA Cloud Azure

Sobre a IA da Azure, explorei o uso de ferramenta, como o Speech Studio e o Language Studio, voltadas para o processamento de fala e linguagem natural. O objetivo foi desenvolver habilidades práticas na criação de soluções inteligentes que interpretam voz e texto, aplicando conceitos de reconhecimento de fala, análise de sentimentos, tradução e compreensão de linguagem.

## Recurso de Fala IA Azure
Realizei alguns testes no site da [Speech Studio da Microsoft](https://learn.microsoft.com/azure/cognitive-services/speech-service/). Tentei falar Teste Laboratório e deu esse resultado com o recurso de Transcrição em tempo real
![Detalhes Speech Studio](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/detalhes%20Fala%20ia.png)

## Recurso de Análise de Sentimento e Opiniões
Usei o seguinte texto no site [Language Studio da Microsoft](https://language.cognitive.azure.com/)
> **Tired hotel with poor service**  
> *The Royal Hotel, London, United Kingdom*  
> *5/6/2018*  
> This is an old hotel (has been around since the 1950s) and the room furnishings are average – becoming a bit old now and require changing.  
> The internet didn't work and I had to come to one of their office rooms to check in for my flight home.  
> The website says it's close to the British Museum, but it's too far to walk.

Sentence 1

![Sentence 1](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/resultado%20texto%20language%20studio.png)

Sentence 2

![Sentence 2](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/resultado%202%20.png)

Sentence 3

![Sentence 3](https://github.com/Phc01/resumo-lab-CloudAzure/blob/main/resultado%203.png)

Pela análise da IA sobre a opinião do usuário sobre o hotel, as 2 primeiras partes do texto deu negativo, e a parte 3 do texto ficou mais neutro mas mesmo assim deu negativo

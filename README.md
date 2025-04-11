# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

A computação em nuvem permite o acesso remoto a recursos de TI (por exemplo: servidores, armazenamento, banco de dados e de software). Esses recursos são fornecidos e hospedados por provedores como: AWS, Microsoft Azure e Google Cloud e o usuário é capaz de acessar tudo pela internet, já que a infraestrutura necessária, é gerenciada pelo próprio provedor, o usuário escolhe apenas o que precisa e tem tudo disponível em questão de minutos.

Esses servidores funcionam em grandes data centers distribuídos mundialmente. Em resumo, no lugar da empresa manter tudo localmente, elas adquirem esses recursos por demanda, pagando pelo que utilizam.

Existem 3 principais modelos:
- Infraestrutura como serviço: fornece os recursos de infraestrutura, como as máquinas virtuais e o armazenamento.
- Plataforma como serviço: fornece ambientes que já estão prontos para desenvolvimento de aplicativos.
- Software como serviço: fornece softwares acessíveis pelo navegador, como o office 365.

Temos alguns tipos de nuvens disponíveis, a escolha vai depender da necessidade, cada uma apresenta determinadas vantagens e desvantagens:

- Nuvem privada: é exclusivo para uma organização, costuma ser utilizado por empresas que precisam de maior controle de dados, como bancos, e geralmente é mantido internamente ou por um terceiro. As vantagens são a segurança, privacidade e maior controle dos dados. Um exemplo é uma empresa que tem o seu próprio datacenter com uma estrutura em nuvem.
- Nuvem pública: é a infraestrutura oferecida por provedores como a Azure, acessível pela internet, qualquer empresa ou pessoa pode contratar. Como vantagem, o custo é mais baixo pois o usuário paga apenas pelo que usar, a implantação é rápida e tem alta escalabilidade. 
- Nuvem Híbrida: ela combina a nuvem pública com a privada, assim os dados podem ser compartilhados entre elas. Usado por empresas que precisam equilibrar o controle de dados com escalabilidade. As vantagens são a flexibilidade e o melhor aproveitamento dos recursos.
- Multicloud: é a combinação de mais de um provedor de nuvem pública ao mesmo tempo, é utilizado por empresas que não querem depender de um só fornecedor ou querem alguma vantagem específica de cada provedor. Isso traz a vantagem de redução dos riscos e de otimização de custos.

Além disso, temos vários benefícios na computação em nuvem. Alguns que podemos citar:
- Escalabilidade:podemos ajustar os recursos de acordo com a necessidade.
- Segurança: os provedores investem em segurança avançada para a proteção de dados e podemos contar com as atualizações automáticas.
- Custo: o pagamento é baseado na demanda, ou seja, paga-se apenas aquilo que é utilizado, reduzindo ou eliminando os gastos com hardware.
- Disponibilidade: os serviços estão sempre online.

Na microsoft Azure, podemos criar uma máquina virtual, também chamada de VM (virtual machine). Para criar, é só acessar o site do portal Azure, escolher o serviço de máquinas virtuais, escolher o sistema operacional (se é Linux ou Windows), definir o tamanho desejado da VM (quanto é necessário de memória, de CPU), fazer a definição das regras de acesso a rede e em poucos minutos, ou até segundos, aa máquina vai estar pronta. Esse processo simula um computador dentro da nuvem, pode ser usado em testes, em treinamentos etc.


ATIVIDADE 2:

TIPOS DE SERVIÇO NA NUVEM AZURE

Temos 3 tipos de Serviço na Nuvem fornecidos pela Azure:
  - IaaS: Infraestrutura como serviço.
Nesse caso, a Microsoft oferece a infraestrutura bruta, que são os servidores, rede, armazenamento e máquinas virtuais. 
O usuário cuida do sistema operacional, aplicativos, das configurações e dos dados. É indicado para quem quer controle técnico.
Já a Azure cuida da manutenção da infraestrutura física e da conectividade. 

  - PaaS: Plataforma como serviço.
A Azure entrega um conjunto: infraestrutura + sistema operacional + banco de dados + ambiente de desenvolvimento. 
O usuário cuida apenas do aplicativo e dos dados. 
Nesse caso a Azure vai cuidar da manutenção da estrutura física, conectividade, sistema operacional etc

  - SaaS: Software como serviço.
Aqui usamos um software pronto na nuvem, sem ter que instalar nada pois é a Azure a responsável por tudo. Um exemplo é o Microsoft Teams.
A responsabilidade do usuário é apenas usar, já a da Azure é todo o suporte e manutenção, ou seja, infraestrutura física, plataforma, aplicativo.

Nos serviços de nuvem, o cliente e o provedor tem responsabilidades divididas, ou seja, compartilham a responsabilidade. Isso vai definir quem é responsável por cada ambiente da nuvem, dependendo do tipo de serviço escolhido. Em geral, a Azure cuida da segurança física, infraestrutura e plataforma, e o usuário cuida dos dados, senhas, acesso e configurações, mas isso pode variar de acordo com o tipo de nuvem escolhida. Quanto maior o serviço escolhido, maior é a responsabilidade da Azure. No modelo IaaS, o cliente tem um controle maior, mas também assume mais responsabilidades. 

A nuvem é segura, desde que o usuário também cumpra sua função e proteja seus dados, identidades de acesso e siga as conformidades regulatórias.

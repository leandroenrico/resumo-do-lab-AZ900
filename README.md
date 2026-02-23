# Resumo-do-lab-AZ900
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO - AZ 900

 Computação em nuvem: São serviços por meio da internet, possibilitando o uso de recursos e serviços de forma rápida, flexíveis e escalável;
O pagamento é realizado sobre os produtos ou serviços utilizados;

Existem nuvens públicas, privadas e híbrida, onde:

- Nuvem pública: 
Não existe Datacenter dedicado para cada conta;
Possui acesso a serviços e recursos que também podem ser usados por outras contas, não tendo hardwares dedicados por conta de usuário;
O acesso é seguro podendo ser realizado de diferentes formas;

-Nuvem privada:
Organizações criam nuvens de forma privado com acesso dedicado para somente a empresa e precisam comprar seu próprio hardware para conseguir escalonar e provisionar recursos;
O acesso é seguro podendo ser realizado de diferentes formas;

- Nuvem híbrida:
Combina as nuvens pública e privada para permitir que os aplicativos sejam executados no local mais apropriados, seja ele on-premise ou cloud, fornecendo maior segurança, disponibilidade e escalabilidade para o usuário;
O acesso é seguro podendo ser realizado de diferentes formas;

Características destas nuvens:

Nuvem pública:
Os aplicativos podem ser rapidamente provisionados e desprovisionados;
As organizações pagam apenas pelo que usam;
Nenhuma despesa de capital para escalar verticalmente;

Nuvem privada:
Os hardwares devem ser adquiridos para utilização dos serviços e recursos , com manutenção do hardware sendo realizada pelo próprio cliente;
As organizações têm controle total e são responsáveis pelos recursos e segurança do ambiente;
As organizações também são responsáveis pelas atualizações e manutenções dos hardwares, climatização do ambiente e fornecimento de energia;

Nuvem híbrida
Oferece a maior flexibilidade, de acordo com a necessidade e disponibilidade dos serviços e recursos;
As organizações determinam onde executar seus aplicativos, banco de dados e uso dos serviços;
As organizações controlam também os requisitos de segurança e conformidade;

Os benefícios da nuvem:

- Alta disponibilidade: Um SLA alto, mantendo a disponibilidade dos serviços e recursos, permitindo reembolso em caso de indisponibilidade de serviços;
- Tolerância a falhas: Associado a replicação de informações, onde o usuário não percebe falha ou indisponibilidade, a replicação de uma região ou entre região, permite continuação no negócio;
- Escalabilidade: Permite aumentar ou reduzir a quantidade de hardware ou serviço de acordo com as necessidades de momento para uso do serviço;
- Elasticidade: Exemplo black friday, onde é configurado scale set, quando configura para o hardware chegar a uma porcentagem, como 90% e o hardware poderá ser replicado ou reduzir gradativamente, de forma automatizada ou manual, adaptando os recursos a necessidades do negócio;
- Alcance global: Pode-se usar o recurso ou serviço em diversões localidades pelo mundo, podendo replicar ou consumi-los de acordo com as demandas;
- Capacidade de latência do cliente:  Latência entre localidades diferentes, que passam por back bonés, que permite velocidade;
- Agilidade: O self services permite usar de forma ágil os recursos e serviços;
- Considerações sobre custo preditivo: As despesas entre CAPEX e OPEX precisam ser avaliadas e consideradas;
- Recuperação de desastre: É quando se tem um problema e precisa recuperá-lo, subindo novamente na mesma região ou em região diferentes, dependendo da situação da região, usando uma replica ou backup;
- Segurança: Pode-se usar VPN (túnel dedicado) seja ela site-to-site, point-to-site, express Route, usando criptografia para o tráfego de dados, discos, tendo responsabilidades do provedor e do cliente;
- 
O que é CAPEX?

CAPEX é uma sigla para capital expenditure, termo em inglês que pode ser traduzido como “despesas de capital”. O CAPEX são compras de bens ou serviços que serão usados. As despesas de capital são ativos fixos, como aquisição de máquinas e equipamentos;
Uma das características definidoras de CAPEX é a longevidade, ou seja, as aquisições representam, em geral, os gastos da organização com ativos físicos.

Exemplos de CAPEX:
•	Construção de uma nova planta de fábrica;
•	Aquisição de um galpão;
•	Compra de equipamentos e máquinas;
•	Aquisição de frota de veículos e caminhões;
•	Melhorias na construção/espaço do escritório;
•	Registro de patentes.

O que é OPEX?

OPEX é uma sigla em inglês para despesas operacionais (operating expenses). O OPEX são os custos pagos por uma empresa de tempos em tempos após o uso dos recursos ou serviços, normalmente de forma mensal;

Exemplos de OPEX:
•	Aluguel de espaço da empresa;
•	Salários de colaboradores e pagamentos de prestadores de serviços;
•	Honorários contábeis e jurídicos;
•	Despesas administrativas;
•	Impostos;
•	Viagens de negócios;
•	Assinatura de softwares, hospedagem de sites e registros de domínios da web;
•	
- Azure IA: É uma plataforma de c nuvem que fornece um conjunto abrangente de serviços, para desenvolvedores e cientistas de dados, permitindo a criação, treinamento e implementação de soluções de inteligência artificial;

Serviços de nuvens:

IaaS: Infraestrutra como serviço, são as máquinas virtuais, armazenamento, redes e sistemas operacionas de um provedor. Remove a infraestrutura do seu on-premise e leva para nuvem;

PaaS: Plataforma como serviço, criação, teste e implantação de aplicativos de software, sem focar no gerenciamento de infraestrutura. Você cria os serviços e não se preocupa com a infraestrutura que hospeda o serviço;

SaaS: Software como serviços, serviços como Office 365 como exemplo, são software prontos, que permitem usar aplicações existentes, bastando usar, o que reduz a responsabilidade do cliente e aumenta para o provedor.

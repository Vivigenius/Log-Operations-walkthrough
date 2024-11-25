# Log-Operations-walkthrough
Tarefa 2 Configuração de Log

Opções de configuração de log

"Você tem coragem de configurar seus logs ou está feliz em se perder na loucura de milhares de linhas?" Em operações de log, há várias preocupações sobre abordagens de configuração, e identificar a abordagem de configuração adequada pode ser um ponto problemático. 
A configuração de log é uma operação multifacetada que aborda segurança, estabilidade operacional, conformidade regulatória e necessidades de depuração. Logs adequadamente configurados são cruciais em segurança cibernética, eficiência operacional, conformidade regulatória e desenvolvimento de software, fornecendo às organizações estatísticas abrangentes de gerenciamento de sistema, ativos e recursos. Vamos analisar e entender os escopos e diferenças de propósitos comuns da configuração de log.

SEGURANÇA
OPERACIONAL
JURÍDICO
DEPURAR


Fins de segurança

O registro e a configuração para fins de segurança são normalmente planejados para detectar e responder a anomalias e problemas de segurança. Por exemplo, configuração para verificar a autenticidade da atividade do usuário para garantir o controle de autorização e a detecção oportuna de acesso não autorizado. As principais áreas de foco dessa abordagem são:
•	Detecção de anomalias e ameaças
•	Registrando dados de autenticação do usuário
•	Garantir a integridade do sistema e a confidencialidade dos dados


Finalidades operacionais

O registro e a configuração para fins operacionais geralmente são planejados para detectar e responder a erros do sistema e identificar pontos de ação para aprimorar o desempenho, a continuidade e a confiabilidade do sistema. As principais áreas de foco dessa abordagem são:
•	Criação proativa de relatórios e notificações para status do sistema e do componente
•	Solução de problemas
•	Planejamento de capacidade
•	Faturamento de serviços


Fins legais

O registro e a configuração para fins legais são semelhantes aos fins de segurança; geralmente são planejados para permanecer em conformidade e aumentar o alinhamento com regulamentações e obrigações. Aqui, as leis, regulamentações e padrões de conformidade variam dependendo do escopo do trabalho, dos dados sendo processados e da área de serviço sendo fornecida. Portanto, cada inscrição virá com um conjunto de responsabilidades e diretrizes a serem seguidas. As principais áreas de foco dessa abordagem são:
•	Alinhamento com padrões, conformidade, regulamentos e leis
•	Por exemplo, ISO 27001, COBIT, GDPR, PCI DSS, HIPAA , FISMA
Exemplo de conformidade legal:  uma empresa deve ter um sistema de gerenciamento de log central ativo, configuração de log adequada, retenção de log de 12 meses para logs e logs de sistemas afiliados (os dados dos últimos três meses devem estar sempre prontos para pesquisa), verificações de segurança do sistema e dos componentes e verificações gerais de auditoria anuais para atender à conformidade de log PCI.


Finalidades de depuração

O registro e a configuração para fins de depuração geralmente são planejados para aumentar a confiabilidade do sistema e aprimorar os recursos fornecidos ao descobrir os bugs e as condições de falha em potencial. Esse escopo de configuração nem sempre é implementado no ambiente de produção e é usado principalmente para fins de teste e desenvolvimento. As principais áreas de foco dessa abordagem são:
•	Aumentando a visibilidade para a depuração do aplicativo
•	Aumentando a eficiência
•	Acelerando o processo de desenvolvimento

RESPOSTAS DA TAREFA 2
![image](https://github.com/user-attachments/assets/3ac50b4d-65d5-4afd-9a16-6b4395420ae4)
A finalidade operacional está diretamente relacionada ao monitoramento do desempenho e ao funcionamento dos sistemas, o que inclui aspectos como faturamento e uso de serviços. Esse tipo de log é utilizado para identificar métricas de utilização, como tempo de uso, consumo de recursos, e cálculo de custos associados a serviços. Portanto, é a escolha correta para medir o custo de uso de um serviço.


![image](https://github.com/user-attachments/assets/77a57617-c2b1-4e5f-89b8-186d6fe24cf9)
Logs de depuração (debug) são essenciais para investigar problemas em aplicativos, identificar bugs, e entender condições que possam causar falhas. Eles ajudam os desenvolvedores a melhorar a confiabilidade e a estabilidade do sistema, otimizando os recursos e garantindo que o aplicativo funcione corretamente. Essa finalidade é ideal para análises focadas em aprimoramento e estabilidade, principalmente durante o desenvolvimento ou manutenção do software.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Tarefa 3

Por onde começar e o que fazer depois de decidir a finalidade do log?
Se você já tem um objetivo e um plano de escopo, mas precisa de ajuda para saber como e onde começar, você pode usar os métodos de reunião e brainstorming com sua equipe. A reunião pode soar como uma ação passiva, mas ela dará início ao brainstorming, o que ajudará a considerar múltiplos aspectos e criar um rascunho do plano.
Lembre-se, cada propósito de configuração de log é planejado e implementado para cumprir uma meta diferente. Questionar é uma das maneiras mais comuns de identificar necessidades e facilitar o planejamento. Lembre-se, cada implementação é única, mas perguntas básicas comuns devem ser respondidas em quase todas as sessões de planejamento de configuração de log. Você pode usar as seguintes perguntas como ponto de partida e ampliar a lista de acordo com as respostas. Lembre-se, você precisará de etapas adicionais, como criar um plano detalhado, escolher ferramentas/tecnologias, estabelecer processos de monitoramento e revisão/análise após responder às perguntas iniciais.


Perguntas a serem feitas em uma reunião/sessão de planejamento:

•	O que você registrará e para quê (escopo do ativo e finalidade do registro)?

•	É necessário comprometimento ou esforço adicional para atingir o propósito (requisitos relacionados ao propósito)?

•	Quanto você vai registrar (detalhar escopo)?

•	Quanto você precisa registrar?

•	Como você vai registrar (a coleta)?

•	Como você vai armazenar os logs coletados?

•	Existe algum padrão, processo, legislação ou lei que você deve cumprir devido aos dados que você registra?

•	Como você vai proteger os logs?

•	Como você vai analisar os logs coletados?

•	Você tem recursos e força de trabalho suficientes para fazer o registro?

•	Você tem orçamento suficiente para planejar, implementar e manter o registro?


RESPOSTA DA TAREFA 3
![image](https://github.com/user-attachments/assets/ff7e337f-3662-4cc5-a805-7c3b97a62d18)

A pergunta "Quanto você precisa registrar?(How much do you need to log?)" está diretamente ligada à determinação do escopo e do nível de detalhes necessários para satisfazer essas demandas regulatórias, incluindo a menção específica dos requisitos do PCI DSS.


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Tarefa 4

Dilema de configuração: planejamento e implementação

Dilema de configuração: requisitos, aspirações, recursos e investimento
O dilema de configuração reflete os desafios da implementação. Conforme destacado na tarefa anterior, cada escopo de configuração de log vem com responsabilidades, diretrizes e desafios. Isso significa que a configuração de log e o registro são mais do que uma simples prática de habilitar o registro dos ativos e sobreviver entre milhares de linhas.

Cada plano de configuração de log resulta de uma análise única do escopo, ativos, objetivos, requisitos e expectativas a serem aplicados. Expectativas, requisitos e limites são determinados com o envolvimento de administradores de sistema, consultores jurídicos e financeiros e gerentes, se possível. Em resumo, a principal fonte do dilema é encontrar o equilíbrio entre requisitos, escopo, detalhes e preço (custos financeiros e trabalhistas, riscos e investimento). Durante a reunião, pode haver alguns pontos em que os participantes saem do assunto, mas é vital ter em mente que o objetivo principal da reunião é:

•	Atender a requisitos operacionais e de segurança específicos (não negociáveis), ao mesmo tempo em que considera a viabilidade de melhorar a capacidade por meio da implementação de dados e insights adicionais.

Por último, mas não menos importante, uma avaliação de risco abrangente, priorizando segurança, conformidade e necessidades legais, será útil para navegar neste dilema. Encontrar o equilíbrio em decisões de nível "operacional e de gerenciamento" e alcançar resultados seguros, eficientes, proativos, resilientes e sustentáveis no cenário de ameaças/TI em constante evolução e operações técnicas.

Traduzindo “Requisitos” e “Aspirações” para o Nível Operacional

Vamos analisar mais detalhadamente como exatamente o dilema surgiu.

![image](https://github.com/user-attachments/assets/3096ea39-7d84-485f-b4de-c4ede9d5f1b0)

Embora o foco principal seja o mesmo, dois conjuntos de perguntas representam duas dimensões distintas de registro e análise:
•	A parte base depende muito de uma mentalidade de detecção de incidentes. Ainda assim, ela fornece uma estrutura sólida para registro e análise, mas é reativa. Os requisitos são um bom lugar para começar, mas são úteis principalmente contra ameaças conhecidas.


•	A parte das aspirações é mais focada em uma mentalidade de caça a ameaças. Portanto, é proativa e requer mais recursos devido à necessidade de ir além. Portanto, esta parte é mais útil contra ameaças avançadas e sofisticadas. 
A parte de linha de base é necessária para uma base sólida de detecção de incidentes e escopo de resposta. No entanto, adotar aspirações proativas adicionando-as à visão operacional é fortemente recomendado, dado o cenário de ameaças em constante evolução. 

RESPOSTA DA TAREFA 4
![image](https://github.com/user-attachments/assets/f8b2fb65-e745-4cfe-9eed-14635317c1e0)


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Tarefa 5

Princípios e Dificuldades

Princípios de registro
O registro é um aspecto crítico das operações de segurança cibernética e TI. É um processo tão oneroso quanto funcional e requer utilização ativa de recursos. Portanto, é crucial implementar uma operação de registro adequada e garantir sua eficácia e eficiência. Existem vários princípios que ajudam a atingir o objetivo mencionado. A tabela abaixo destaca alguns dos fundamentos.
![image](https://github.com/user-attachments/assets/460a24fd-4796-4f84-88ed-a3d556fede21)


Desafios
Os desafios são parte do gerenciamento de logs tanto quanto os princípios. No entanto, a maioria deles pode ser abordada na seção de planejamento. A tabela abaixo destaca os principais desafios do log.
![image](https://github.com/user-attachments/assets/569422a6-f48d-413c-8b25-352d76adcaeb)


Para onde ir a partir daqui?

Os princípios e desafios mencionados são comuns e podem variar de acordo com o seu caso. No entanto, o ponto principal é aderir aos princípios de registro e abordar os desafios proativamente.


RESPOSTAS DA TAREFA 5
![image](https://github.com/user-attachments/assets/2803dcb8-d1f5-4301-a413-f62389ad930f)
O princípio de Arquivamento e Acessibilidade (Archiving and Accessibility) trata justamente de definir políticas de retenção de logs e garantir que os dados relevantes sejam armazenados de forma segura e acessível para futuras análises.
![image](https://github.com/user-attachments/assets/89a7497a-435c-4293-9e1d-2848024b211a)






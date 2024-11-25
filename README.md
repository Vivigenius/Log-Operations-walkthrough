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

PERGUNTAS DA TAREFA 2
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


PERGUNTA DA TAREFA 3
![image](https://github.com/user-attachments/assets/ff7e337f-3662-4cc5-a805-7c3b97a62d18)

A pergunta "Quanto você precisa registrar?(How much do you need to log?)" está diretamente ligada à determinação do escopo e do nível de detalhes necessários para satisfazer essas demandas regulatórias, incluindo a menção específica dos requisitos do PCI DSS.


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------




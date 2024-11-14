# DIO-CURSO-aws-step-functions

***Aula de AWS Step Functions:***

Assistindo as aulas sobre AWS Step Functions da DIO, aprendi mais sobre uma das soluções mais versáteis da AWS para automatizar a orquestração de fluxos de trabalho e processos. O AWS Step Functions permite que vários serviços da AWS sejam coordenados em um conjunto de etapas definidas, auxiliando na construção e monitoramento de aplicações resilientes e escaláveis, sem a necessidade de gerenciar a lógica de integração pessoalmente.

Por meio da lição, pesquisei sobre a Amazon States Language (ASL), uma linguagem JSON usada para criar a estrutura e o comportamento de máquinas de estados que representam nossos fluxos de trabalho. A ASL permite configurar diferentes aspectos operacionais, como decisões condicionais, processos paralelos e tratamento de erros, facilitando a modelagem de fluxos de trabalho, mesmo em situações complexas.

O design de máquinas de estados foi conhecimento importante aprendido. Os estados podem ser de vários tipos, incluindo Task, Choice, Wait, Parallel, Fail, e outros. O estado Task, por exemplo, permite que a máquina invoque funções Lambda, acesse outros serviços da AWS ou execute outras ações definidas. Já o estado Choice possibilita a criação de rotas condicionais, facilitando a personalização do fluxo de acordo com condições específicas.

Também explorei como o Step Functions facilita o controle de erros e a implementação de políticas de repetição automática. Isso garante que falhas temporárias ou de rede não interrompam o fluxo de trabalho, e que tarefas possam ser reexecutadas conforme necessário, contribuindo para a resiliência das aplicações.

O Step Functions ainda oferece integração nativa com outros serviços AWS, como Lambda, SNS, SQS, DynamoDB, entre outros, que permitem a automação de diversos processos sem a necessidade de desenvolvimento de código adicional.

Com essa aula, entendi como o AWS Step Functions ajuda a visualizar e monitorar o progresso dos fluxos de trabalho em tempo real, facilitando o rastreamento de problemas e o ajuste de processos de maneira rápida e eficaz.

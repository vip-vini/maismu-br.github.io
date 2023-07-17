# Central de Serviços

## Introdução

A `Central de Serviços` é um ponto centralizado de contato para esclarecimento de dúvidas, solicitação de serviços, entre outros processos relacionados. Ela é utilizada tanto por funcionários quanto por clientes da empresa. A Central de Serviços de TI, é uma estrutura completa para atender demandas dos colaboradores e parceiros do negócio, ela `centraliza as demandas e incidentes relacionados à T.I.` em um só lugar.

![Central de Serviços](https://portal.prodam.sp.gov.br/wp-content/uploads/2021/02/220221_Default-Site-Nova-Central-de-Servicos.jpg#center)

### O que é um Service Desk?
O **Service Desk** é uma unidade funcional composta por uma equipe dedicada, responsável por uma variedade de atividades relacionadas aos `serviços de TI` que são fornecidos aos colaboradores, empresas e parceiros da **Mais Mu**. O papel principal do Service Desk é centralizar demandas e incidentes relacionados à T.I. em um só lugar. Assim, registra e monitora essas atividades com o objetivo de solucioná-las e evitar que se repitam.

### O que é um incidente?
Um incidente é qualquer interrupção ou paralisação de um serviço de T.I. Também pode ser considerado um incidente a redução da qualidade de um serviço prestado.

No geral, um incidente pode afetar tanto o desempenho de um hardware como de seus programas e, desse modo, gerar uma série de problemas, como mau funcionamento do PC, falhas no servidor e indisponibilidade de acesso à Internet. 

Nesse cenário, é fundamental enfatizar que, muitas vezes, um incidente não ocorre por problemas estruturais físicos, visto que muitos deles acontecem por falhas nos testes e por decisões equivocadas.

__São exemplos de incidentes:__ falta de acesso à internet, servidor fora do ar, mau funcionamento de computadores etc. Eles podem ser identificados pela equipe de T.I., por sistemas de monitoramento ou, então, relatados pelos usuários e clientes.

Também é importante ter em mente que incidentes, problemas e eventos são conceitos diferentes. Eles podem se sobrepor, mas não são iguais. Segundo o ITIL, um evento é uma mudança de estado significativa para a gestão de um serviço de T.I. ou outro item de configuração. Já um problema é a causa raiz de um ou mais incidentes.

Resumindo:

- Um __evento__ é um alerta que alguma coisa aconteceu ou pode acontecer;
- Um __incidente__ é o efeito, isto é, aquilo que impacta o serviço;
- Um __problema__ é a causa raiz ou o porquê de o incidente ter acontecido;
- Todo incidente é um evento, mas nem todo evento é um incidente;
- Todo problema parte de um incidente e, consequentemente, de um evento. Mas o contrário não é verdadeiro.

Agora que já estamos alinhados quanto ao conceito de incidente, vamos entender o que é gerenciamento de incidentes:

### O que é Gerenciamento de Incidentes?
Gerenciamento de Incidentes é um processo que tem o objetivo de retomar um serviço o mais breve possível, causando o mínimo de danos ao negócio. Dessa forma, são mantidos os Acordos de Nível de Serviço firmados com as áreas de negócio. Isso pode ser feito através de um reparo rápido ou do fornecimento de uma solução alternativa ao cliente.

Conforme as boas práticas para gestão de T.I. do ITIL, o processo de gerenciamento de incidentes precisa ser composto de algumas etapas. Vamos conhecer mais detalhes sobre cada uma delas?

### Como fazer Gerenciamento de Incidentes segundo o ITIL
#### 1. Identificação de Incidentes
O primeiro passo para gerenciar incidentes é reconhece-los. Os incidentes podem ser identificados pela Central de Serviços, por sistemas de monitoramento e pelos próprios usuários e clientes. Dessa forma, os chamados chegam por diversos canais, como chat, e-mail e telefone.

#### 2. Registro de Incidentes
Todos os incidentes devem ser registrados conforme a ferramenta de controle adotada pela organização, que pode ser uma planilha ou um sistema de chamados, por exemplo. O registro é muito importante porque cria um histórico que possibilita a consolidação de uma `base de conhecimento`. Dessa forma, sempre que os analistas de suporte receberem um chamado eles poderão consultar a base e verificar se esse incidente já foi resolvido e qual foi a solução encontrada. O registro também facilita a comunicação na hora da “passagem de bastão”.

#### 3. Categorização de Incidentes
Nessa etapa do processo, a Central de Serviços irá classificar o chamado recebido. Qual é o tipo do chamado? É um incidente ou uma requisição? É um chamado de hardware ou software? Se não for um incidente, a Central de Serviços irá delegar o chamado para o processo adequado. Outra tarefa importante nesta etapa de categorização é definir a qual serviço do catálogo o incidente está relacionado.

#### 4. Priorização de Incidentes
É a etapa de definir se o incidente deve ser atendido agora ou pode esperar um pouco. Para isso, é preciso usar critérios relacionados à urgência e ao impacto. Um incidente urgente é aquele que precisa ser atendido imediatamente. Já um incidente impactante é aquele que pode gerar grandes riscos ao negócio. Os incidentes podem ser classificados de acordo com um dos seguintes graus de priorização: __“Muito Baixo”, “Baixo”, “Normal”, “Alto” e “Muito Alto”__.

#### 5. Diagnóstico Inicial de Incidentes
É a fase de entender, de fato, o incidente que foi reportado. Essa atividade compreende todo o processo de busca da Central de Serviços por uma solução que realmente resolva o chamado do usuário ou cliente. Normalmente, os atendentes do primeiro nível de suporte buscam respostas na Base de Conhecimento, em procedimentos técnicos da empresa, junto com os fornecedores ou com os próprios colegas. Também é importante ressaltar que, caso o atendente perceba que faltam informações para a resolução do chamado, ele deve solicitá-las ao usuário ou ao responsável.

#### 6. Escalada de Incidentes
Caso o atendente de primeiro nível de suporte não tenha o conhecimento técnico necessário para resolver o incidente, ele delegará a tarefa ao segundo nível de suporte. Essa situação é chamada de `escalada`. É muito interessante ter essa divisão dos atendimentos em níveis porque gera uma melhor distribuição de tarefas de acordo com as competências da equipe. Afinal, você não vai querer que o seu programador mais caro perca tempo lidando com pequenos incidentes que poderiam ter sido resolvidos por outras pessoas, não é mesmo?

#### 7. Resolução de Incidentes
É a fase em que os chamados são realmente solucionados, seja pelo primeiro nível de suporte ou posterior. Além de resolver o pedido do usuário ou cliente, o atendente também deve registrar todas as informações relevantes sobre o incidente e sua resolução. Outro ponto bem importante é garantir de verdade que o incidente foi resolvido, `comunicando o cliente`.

A resolução de um incidente pode apagar rastros e evidências que poderiam ser utilizados para resolver um problema (causa raiz). Por isso, é preciso cuidado nesse momento.

!!! note example "Exemplo:"
        Para resolver um incidente, como a queda de um servidor, o técnico aperta o botão de “Reset” da máquina. Isto vai apagar registros que poderiam ser utilizados para tentar investigar uma causa raiz para a queda do servidor.

#### 8. Fechamento de Incidentes
É o encerramento do chamado, que deve ser `documentado para eventuais consultas`. Também é preciso exportar as informações para a base de conhecimento, tornando-as acessíveis para outros atendentes. Caso essa base não seja constantemente reabastecida, corre-se o risco de perder tempo tentando encontrar a solução para um incidente que já foi resolvido anteriormente.

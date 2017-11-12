# Marcelo-Massruha
Projeto TS, BH e Indicadores - AutoEver

Cenário I - Criação de Rotina para controle de Projetos (Time-Sheet)
  1. Deverão existir as seguintes Tabelas (conforme estrutura atual do sistema - País, Cliente, Empresa, Filial) 
     a. Cadastro de Clientes
     b. Cadastro de Projetos
     c. Cadastro de Atividades
     d. Cadastro de Tarefas
     e. Tabela Time Sheet - Onde sejam gravados todos os dados da tarefa (colaborador, data início, hora início, data fim, hora fim, cliente, projeto, atividade, tarefa, observações, local do colaborador e do Cliente (geolocalização), duração total da tarefa (hora fim - hora início), quem planejou a tarefa (RH, Gestor, o próprio colaborador), Status da tarefa (Planejada, Em Execução, Finalizada) 
  2. Rotinas executadas pelo administrador, RH ou Gestor (definidas no perfil do usuário e permissões):
     a. Cadastrar Clientes
     a. Cadastrar Projetos
     b. Cadastrar Atividades
     c. Cadastrar tarefas
     d. Competências Colaborador
  3. No Portal o administrador, RH ou Gestor (definido no perfil do usuário e permissões): 
     a. Planeja um projeto, atividade e tarefa (Cliente, Local (geolocalização), data e hora) para os colaboradores sob sua gestão.
     b. Coloborador recebe ALERTA (Portal e APP) que possui uma tarefa para executar - Rotina de ALERTAS já existe, criar msg Alerta.
     c. Colaborador também pode planejar e iniciar uma Tarefa. Deverá selecionar o menu "Time Sheet - Iniciar Tarefa", clicar na opçõa "+" e selecionar o Cliente, Projeto, Atividade e Tarefa e fazer o CheckIn da Tarefa (confirmação com biometria a escolher - Facial ou Digital (funcionalidade já existente no Ponto Eletrônico). Fazer o registro da geolocalização (endereço, coordenadas, data e hora que foi feita a marcaçao, se por mobile, portal, tablet, toten, etc., carga do celular, mesmas opções existentes no Ponto.
     d. 
  4. Colaborador pode iniciar a tarefa pelo Portal ou APP. 
     a. Acessa Menu Time Sheet - Minhas Tarefas (verifica status e seleciona a tarefa que foi planejada para ele executar).
     b. Seleciona Iniciar Tarefa (Tela de checkin "mobile/portal")
     c. Seleciona Finalizar Tarefa (Tela de checkout "mobile/portal")
     d. O colaborador insere uma observação (campo texto) ao finalizar a tarefa. 
     e. Alertas serão gerados quando: Alguém planejar uma tarefa (quem gerou e quem planejou receber alertas); Colaborador planejar tarefa (colaborador e líder dele recebem os alertas); Colaborador Iniciar ou Finalizar uma Tarefa (Colaborador e Gestor). 
     f. O planejamento de tarefas poderão ter Workflow de aprovação configurado. O Workflow pode ser configurado quando planejada uma tarefa, quando inciada ou finalizada uma tarefa, quando cancelada uma tarefa. Mecanismo de Workflow já existe. 
     g. Cliente deverá receber um e-mail com o detalhamento da Tarefa (Cliente, Projeto, Atividade, Tarefa, Data, hora planejada, colaborador ou técnico que irá executar a tarefa (nome, foto, telefone, e-mail, CPF, RG, Placa do Carro). 
     h. 



Minhas tarefas
0
Exportar relatório das tarefas
0
Filtro na tela de minhas tarefas
0
Alertas do timesheet
0
Mostrar no balão do mapa, informações sobre tarefa iniciada do usuário
0
Correções em retorno de testes e erros (Orhganiza)

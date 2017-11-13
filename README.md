# Marcelo-Massruha
Projeto TS, BH e Indicadores - AutoEver

Cenário I - Criação de Rotina para controle de Projetos (Time-Sheet)

  1. Deverão existir as seguintes Tabelas (associadas a estrutura atual do sistema - País, Cliente, Empresa, Filial) 
     a. Cadastro de Clientes
     b. Cadastro de Projetos
     c. Cadastro de Atividades
     d. Cadastro de Tarefas
     e. Competências Colaboradores
     f. Tabela Time Sheet - Onde sejam gravados todos os dados da tarefa (colaborador, data início, hora início, data fim, hora fim, cliente, projeto, atividade, tarefa, observações, local do colaborador e do Cliente (geolocalização), duração total da tarefa (hora fim - hora início), quem planejou a tarefa (RH, Gestor, o próprio colaborador), Status da tarefa (Planejada, Em Execução, Finalizada), Anexos (foto ou arquivos). 

  2. Rotinas executadas pelo administrador, RH ou Gestor (definidas no perfil do usuário e permissões):
     a. Cadastrar Clientes
     b. Cadastrar Projetos
     c. Cadastrar Atividades
     d. Cadastrar Tarefas
     e. Cadastrar Competências 
     f. Associar Competências aos Colaboradores
     g. Gravar Históricos de todas as tarefas
     i. Deve funcionar para dispositivos móevis (Android e IOs) - Smartphone, Tablets, Portal Web, TVs Smart
     j. operar em modo On e Off-line
     k. Estrutura já preparada para multi-idioma
      
  3. No Portal o administrador, RH ou Gestor (definido no perfil do usuário e permissões): 
     a. Planeja um projeto, atividade e tarefa (Cliente, Local (geolocalização), data e hora) para os colaboradores sob sua gestão.
     b. Coloborador recebe ALERTA (Portal e APP) que possui uma tarefa para executar - Rotina de ALERTAS já existe, criar msg Alerta.
     c. Colaborador também pode planejar e iniciar uma Tarefa. Deverá selecionar o menu "Time Sheet - Iniciar Tarefa", clicar na opçõa "+" e selecionar o Cliente, Projeto, Atividade e Tarefa e fazer o CheckIn da Tarefa (confirmação com biometria a escolher - Facial ou Digital (funcionalidade já existente no Ponto Eletrônico). Fazer o registro da geolocalização (endereço, coordenadas, data e hora que foi feita a marcaçao, se por mobile, portal, tablet, toten, etc., carga do celular, (mesmas opções existentes no Ponto).
     d. 
  
  4. Colaborador pode iniciar a tarefa pelo Portal ou APP. 
     a. Acessa Menu Time Sheet - Minhas Tarefas (verifica status e seleciona a tarefa que foi planejada para ele executar).
     b. Seleciona Iniciar Tarefa (Tela de checkin "mobile/portal")
     c. Seleciona Finalizar Tarefa (Tela de checkout "mobile/portal")
     d. O colaborador insere uma observação (campo texto) e pode inserir um anexo (foto se for pelo celular, ou arquivo pelo portal) ao finalizar a tarefa.
     e. Alertas serão gerados quando: Alguém planejar uma tarefa (quem gerou e quem planejou receber alertas); Colaborador planejar tarefa (colaborador e líder dele recebem os alertas); Colaborador Iniciar ou Finalizar uma Tarefa (Colaborador e Gestor). Cliente Assinar tarefa. 
     f. O planejamento de tarefas poderão ter Workflow de aprovação configurado. O Workflow pode ser configurado quando planejada uma tarefa, quando inciada ou finalizada uma tarefa, quando cancelada uma tarefa. Mecanismo de Workflow já existe. 
     g. Permitir que sejam inserido Anexos (fotos ou arquivos) em cada uma das Tarefas.
     h. Campo assinatura do Colaborador
     i. Campo para Comentários do Cliente.
     j. Campo para Assinatura do Cliente.
     k. Cliente deverá receber um e-mail com o detalhamento da Tarefa (Cliente, Projeto, Atividade, Tarefa, Data, hora planejada, colaborador ou técnico que irá executar a tarefa (nome, foto, telefone, e-mail, CPF, RG, Placa do Carro).
     l. Visualizar no MAPA a posição geográfica do Colaborador/Técnico (no balão do mapa mostrar infos da tarefa) e do Cliente.
     m. Opção para disparar e-mail ao Cliente com Informações (campo Texto) e mostrar a posição geográfica onde o Colaborador/Técnico se encontra no MAPA em relação ao endereço do Cliente (anexar uma imagem do Mapa).
     n. Cliente recebe avaliação de satisfação (por e-mail link para respodner).
     o. Administrador, Colaborador, RH, Gestor recebe alerta que Cliente respondeu a pesquisa de satisfação.
     p. Histórico de tudo que ocorreu na tarefa (inclusive resultado da avaliação do cliente)
     q. Filtro na tela de minhas tarefas
     r. Parametros para CheckIn e CheckOut automáticos (horários gerados pelo sistema) ou Manual (colaborador ou técnico lançam hora início e hora término).
     s. Parametro para Colaborador poder ou não criar as suas próprias tarefas.

  5. Tela de Consulta (Portal e APP)
     a. Mostrar as tarefas planejadas (cliente, local, projeto, atividade, status, tarefa, hora início, hora fim, duração total, anexos, avaliação cliente, tempo de execução (para aquelas que estão em Execução no momento da consulta - Timer).
     b. Filtros (com todos os campos) de seleção para consulta e opção para exportar em formatos PDF, CSV/XLS ou Word   

  6. Ambiente esperado
     a. FRONT - Ionic 3 / Angular 4 
     b. BACK/API - MySQL 5.6 - Laravel 5.4 ou Lumen

  7. Anexos (imagens) armazenar em base64 / longblob ou mediumblob (como já é feito atualmente na fnção eSocial do aplicativo).

  8. Link das telas do APP no Marvel (faltam algumas telas a serem desenhadas para Portal e Mapa): https://marvelapp.com/57j32ch


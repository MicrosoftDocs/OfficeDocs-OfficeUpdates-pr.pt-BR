---
title: Notas de versão para as versões de canal mensalmente no 2015
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/11/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Fornece que aos profissionais de TI notas de versão do canal mensal libera do Office 365 ProPlus em 2015
ms.openlocfilehash: 0b235ba177dd2378cbb953315e2ead6b692ed52b
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/04/2018
ms.locfileid: "19555858"
---
# <a name="release-notes-for-monthly-channel-releases-in-2015"></a>Notas de versão para as versões de canal mensalmente no 2015

Essas notas de versão fornecem informações sobre novos recursos, atualizações de segurança e atualizações não relacionadas à segurança são incluídas nas atualizações de canal mensal para o Office 365 ProPlus em 2015.
 
> [!NOTE]
> - A seguir também fornece as informações sobre novos recursos, atualizações de segurança e não relacionadas à segurança atualizações para o Visio Pro para Office 365 e o cliente de Desktop do Project Online.
> - Essas informações também se aplicam ao Office 365 Business, que é a versão do Office que vem com alguns planos do Office 365, como Business Premium.
> - Mensalmente canal era chamado de canal atual antes da de 2017 setembro.

## <a name="version-1511-december-11"></a>Versão 1511: 11 de dezembro
*Versão 1511 (compilação 6366.2036)*

### <a name="excel-feature-updates"></a>Excel: Atualizações de recurso
-   **Modelos de BI:** Três novos modelos que se beneficiam de business intelligence recursos (BI) do Excel: [Ideias de calendário](https://support.office.com/article/7edbeb88-99ca-403f-a394-7e957d3d3f40), [Análise do estoque](https://support.office.com/article/f65e62ac-7af6-4cc6-98f3-f68b147ed65d), [Meu fluxo de caixa](https://support.office.com/article/215e9e2e-5813-41ad-a9ef-a0c0874841bb)

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema onde arrastando a alça de preenchimento de uma célula formatada com um número como uma data longa faz com que o Excel falha.
-   Para corrigir um problema onde a criação de uma tabela dinâmica ou gráfico dinâmico a partir de uma conexão de dados e colocada em uma nova planilha faz com que o Excel falha.
-   Corrigi um problema de onde os botões de filtro para um gráfico dinâmico não ficam visíveis quando não há nenhum filtrando os campos de tabela dinâmica subjacentes.
-   Corrigi um problema onde o modelo de dados é perdido ao fechar o Excel antes de salvar quando houver uma pasta de trabalho pessoal macro ocultas.
-   Corrigi um problema em que a edição de uma planilha com um gráfico de treemap em uma versão anterior do Excel 2016 que ele foi criado em faz o gráfico de treemap perder seus dados.

### <a name="onenote-feature-updates"></a>OneNote: Atualizações de recurso
-   **Inserir vídeos online:** Inserir vídeos do YouTube, OfficeMix ou Vimeo em uma página. [Obter mais informações](https://support.office.com/article/0a862f29-665c-43a5-9dd8-68009423cf7c)

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Corrigir um problema com o Office 365 Business, onde tentando usar o OneNote com SharePoint resulta em uma mensagem de erro que informa aos usuários que eles têm a atualização para uma versão diferente do Office.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recurso
-   **Calendário persa:** Adicione o calendário persa como um calendário principal ou alternativo.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema onde arrastar a barra de rolagem na lista de mensagem faz com que a lista para ir até o final da lista.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recurso
-   **Mudar transição:** Crie transições entre os slides e trazer movimento para apresentações para transmitir com mais eficiência os conceitos e informações. [Obter mais informações](https://support.office.com/article/8dd1c7b2-b935-44f5-a74c-741d8d9244ea)
-   **Designer do PowerPoint:** Um novo serviço que permite que você dê o seu conteúdo e gerar automaticamente uma variedade de ideias que você pode escolher para tornar os slides de suas aparência melhor. [Obter mais informações](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

    Esse serviço requer conectividade à Internet. Para desabilitar esse recurso, [use os arquivos de modelo administrativo de diretiva de grupo mais recentes](https://www.microsoft.com/download/details.aspx?id=49030) e habilitar a configuração de opções de Designer do PowerPoint. Você pode encontrar essa definição de diretiva em configuração do usuário\\modelos administrativos\\Microsoft Office 2016\\ferramentas | Opções | Geral | Opções de serviço … \\Designer do PowerPoint.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema onde SmartArt com animações não mostrada na sequência esperada no modo de exibição de apresentação de slides com o modo de exibição do apresentador.
-   Corrigi um problema onde a navegação de teclas numérica não funciona no modo de exibição de apresentação de slides.

### <a name="visio-non-security-updates"></a>Visio: Atualizações de não segurança
-   Corrigi um problema de onde os arquivos do AutoCAD exibidos no Visio aparecem indefinidos.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema de onde os documentos não podem ser salvos em uma biblioteca de documentos que possui uma coluna obrigatória.

### <a name="office-suite-feature-updates"></a>Pacote do Office: atualizações de recursos
-   **Enviar como opções**: enviar um documento como um anexo ou como um PDF do painel de compartilhar no Word ou PowerPoint.
-   **Inserir imagem API**: inserir imagens no Word, PowerPoint ou Excel usando o [método document.setSelectedDataAsync](https://msdn.microsoft.com/library/office/fp142145.aspx) na biblioteca do Office. js comuns. A API do JavaScript Word fornece métodos específicos do host chamados insertInlinePictureFromBase64() para definir imagens embutidas no [corpo](https://msdn.microsoft.com/library/office/mt598674.aspx), [ContentControl](https://msdn.microsoft.com/library/office/mt598675.aspx), [parágrafo](https://msdn.microsoft.com/library/office/mt598682.aspx)e objetos Range.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema onde as informações de data de modificação exibe quando seguindo um abrir ou salvar como serão truncadas.
-   Corrigi um problema onde clicar duas vezes no painel de texto para gráficos SmartArt faz com que o aplicativo falha.
-   Corrigi um problema onde o vídeo que reproduz durante a instalação permanece em uma tela preta depois de terminar de e até que a caixa de diálogo "A instalação foi concluída" seja fechada.
-   Corrigi um problema no qual o mouse sobre a notificação de "Modo de exibição protegido" em um documento protegido faz com que a notificação para ser obscurecida por um botão de rolagem muito grande.
-   Corrigi um problema onde a notificação de que uma atualização do Office está agendada será truncada em cazaque e húngaro.
-   Corrigi um problema onde atalhos fixados na barra de tarefas não são removidos de todos os usuários durante uma atualização manual.
-   Corrigi um problema onde falhas causadas por ações relacionadas licenciamento durante uma atualização automática deixa o usuário sem uma instalação do Office.
-   Corrigi um problema onde atualizando para o Office 2016 em um computador Windows 7 OEM que tiveram o Kit de pré-instalação do Office executar no modo de auditoria resultará em erro 0x80070005 durante a ativação.


## <a name="version-1509-december-8"></a>Versão 1509: 8 de dezembro
*Versão 1509 (compilação 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Corrigi um problema onde XPS ou impressões criados usando o cliente de desktop do Windows aparecem como um X vermelho nos clientes de área de trabalho não-Windows, porque os clientes não suportam XPS nativo renderização.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigir um problema onde um indicador é criado que abrange vários parágrafos, mas quando o email é recebido, o primeiro parágrafo do indicador é selecionado quando usando ir para.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-128](https://go.microsoft.com/fwlink/?LinkId=690559): atualização de segurança para o componente de gráficos do Microsoft a resolver a execução de código remoto (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Corrigi um problema em que as sessões de compartilhamento de aplicativo falharem, especialmente durante os períodos de tráfego intermitente.
-   Corrigi um problema que causa Skype para negócios panes se for o primeiro aplicativo a ser iniciado após a instalação do Office 2016.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-131](https://go.microsoft.com/fwlink/?LinkId=699410): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3116111)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema onde um hífen incondicional mostra como um quadrado ao usar algumas fontes.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Altere o transporte padrão para o download de atualizações em segundo plano de cache/BITS para HTTP.
-   Corrigi um problema onde falhas causadas por ações relacionadas licenciamento durante uma atualização automática deixa o usuário sem uma instalação do Office.
-   Corrigi um problema onde atualizando para o Office 2016 em um computador Windows 7 OEM que tiveram o Kit de pré-instalação do Office executar no modo de auditoria resultará em erro 0x80070005 durante a ativação.



## <a name="version-1509-november-10"></a>Versão 1509: 10 de novembro
*Versão 1509 (compilação 6001.1038)*

### <a name="access-security-updates"></a>Acesso: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema onde a gravação de uma macro para a criação de uma consulta resultará em um erro de compilação.
-   Corrigi um problema onde, depois que você excluir uma coluna no Editor de consulta, uma coluna em branco aparece no final da tabela após atualizar a consulta.
-   Corrigi um problema onde um erro inesperado ocorre ao escolher a guia minigráficos na análise rápida de uma tabela de consulta.
-   Corrigi um problema onde, após você realizar uma recortar e cola operação em uma tabela de consulta, você não pode atualizar a consulta usando o painel de consultas de pasta de trabalho.
-   A correção de um problema que, quando você atualizar uma consulta, o foco é movido para a folha da sua tabela de consulta associada.
-   Remova a referência a consulta de alimentação de mensagem de erro sobre as versões suportadas do OData.
-   Corrigi um problema onde os recursos de consulta de energia aparecem como disponível, mas não funcionam quando o produto ainda não foi ativado.
-   Atualizar a URL para Dotlesscss no arquivo \> conta \> sobre o Excel.

### <a name="onenote-security-updates"></a>OneNote: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema onde colar o texto para o Outlook não mostra o texto completo se a quantidade de texto colado for maior que a altura da janela.

### <a name="powerpoint-security-updates"></a>PowerPoint: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="project-security-updates"></a>Projeto: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="publisher-security-updates"></a>Publisher: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)
-   Boletim de segurança da Microsoft [MS15-123](https://technet.microsoft.com/library/security/ms15-123): atualização de segurança do Skype para Microsoft Lync e de negócios abordar a divulgação de informações (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Corrigi um problema com áudio ruído em dispositivos que têm dois microfones de entrada.
-   Corrigir um problema em que os usuários não podem entrar com êxito uma reunião após reiniciar um laptop do modo de suspensão e Skype antes do cliente entrou novamente.
-   Adicione suporte para mensagens contextuais ajudar a fornecer divulgação dos recursos aos usuários.
-   Atualize o texto na caixa de diálogo ingressar em áudio de reunião para direcionar os usuários para o local correto na interface de usuário para alterar configurações.
-   Corrigi um problema com notificações que os usuários ver quando experimentando ambos enviar e recebem problemas de rede.

### <a name="visio-security-updates"></a>Visio: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema onde a numeração de nota de rodapé não corresponde entre a exibição no Word e a impressão quando um documento que tenha definidas como "Reiniciar a numeração de cada página" de notas de rodapé é impresso em segundo plano.
-   Para corrigir um problema onde a coautoria em tempo real não funciona com arquivos armazenados no OneDrive, incluindo o usuário não que aparecem para outras pessoas, como a edição em tempo real e nenhuma informação de presença disponível.
-   Corrigi um problema onde Word Falha durante a coautoria em tempo real em um documento aberto a partir do SharePoint ou OneDrive.
-   Correção de e-mails de um problema de formatação que faz com que tabelas renderizar incorretamente quando colocados em HTML no Outlook e a janela é redimensionada.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): atualização de segurança para o Microsoft Office abordar a execução de código remoto (3104540)

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema onde o usuário repetidamente será solicitado a entrar durante a tentativa de abrir arquivos do SharePoint Online.
-   Corrigi um problema onde atalhos fixados na barra de tarefas não são removidos de todos os usuários durante uma atualização manual.
-   Adicione a capacidade do processo de atualização manual Click-to-Run detectar se o Outlook estiver conectado ao Exchange Server 2007 ou se o Business Contact Manager é instalado para avisar aos usuários de possíveis problemas com a atualização.
-   Verifique as caixas de diálogo para finalizar processos mais visíveis durante uma desinstalação ou atualizar porque essas caixas de diálogo podem obter oculto do usuário por trás de aplicativos abertos ou outra interface de usuário.
-   Corrigi um problema em que um usuário não obter conectado em um aplicativo do Office automaticamente ao usar um computador que é identificado como sendo associado a um domínio e um domínio de nuvem.



## <a name="version-1509-october-21"></a>Versão 1509: 21 de outubro
*Versão 1509 (compilação 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Para corrigir um problema que faz com que o OneNote falhe quando a mesma cor de uma borda está selecionada duas vezes no seletor de cores.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema onde um leitor de tela lê somente o primeiro parágrafo de uma assinatura de email de várias parágrafo ao editar a assinatura de email.
-   Corrigi um problema onde o cursor não está na posição correta ao escrever ou responder um email.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Corrigi um problema onde, em condições de baixa memória, tentando exibir uma área de trabalho compartilhada ou aplicativo resulta em conexão e desconexão repetidas tentativas para reingressar automaticamente e exibir a área de trabalho compartilhada ou aplicativo.
-   Corrigi um problema onde, como o aumento do número de participantes, a experiência de área de trabalho compartilhada vai piorando.
-   Corrigi um problema, quando a autenticação multifator é configurada, onde os prompts repetidas para autenticação de telefone são recebidas durante todo o dia.

### <a name="visio-non-security-updates"></a>Visio: Atualizações de não segurança
-   Corrigi um problema em que um objeto do Word inserido para ser exibida como um ícone esteja vazio após fechar e reabrir o Visio.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Para corrigir um problema onde a coautoria não está disponível e pode obter bloqueado documento quando o documento está no SharePoint Server 2013.
-   Corrigi um problema docx documentos onde a tabela é visível, mesmo que o conteúdo da tabela tem um estilo aplicado a ele, o que inclui a opção oculto.
-   Corrigi um problema de onde os documentos com hiperlinks relativos não podem ser salvos após realizar uma correção automática.
-   Corrigi um problema onde linhas navegue pelos slides durante a edição de um parágrafo em um documento com recuos de espelho.
-   Corrigi um problema onde exibição de linha é inconsistente durante a edição quando o posicionamento sub-pixel está desabilitado.
-   Corrigi um problema onde clicar em um pop-up de comentário com vários comentários onde primeiro está marcado como feito causa uma falha.
-   Corrigi um problema com a quebra de linha incorreta.
-   Para corrigir um problema onde a executar uma macro que utiliza a função TransformDocument em um documento com uma caixa de texto em um cabeçalho ou um rodapé causa uma falha.
-   Corrigi um problema com os documentos. docm, onde a remoção de todos os controles ActiveX causa erros quando o documento é aberto.
-   Corrigi um problema onde evento ContentControlOnExit não é acionado quando você clica em um cabeçalho.
-   Corrigi um problema onde controlar alterações mostra exclusões de revisores com o mesmo nome.
-   Correção de um problema com coautoria em tempo real de documentos configurado para remover informações pessoais onde exibem alterações como alterações controladas hora que o documento é salvo.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema onde na primeira vez em que a abertura de um aplicativo do Office após a atualização para 2016 resulta no aplicativo que está sendo no modo de funcionalidade reduzida e requer o aplicativo ser reiniciado para obter funcionalidade total.
-   Corrigi um problema onde executando o Office com compartilhado ativação do computador habilitada em um computador executando o Remote Desktop Services resultados em um erro, ao abrir um aplicativo, que informa ao usuário que eles precisam usar uma edição de licença de volume do Office.
-   Corrigi um problema onde instalação enfrenta em aproximadamente 90% concluída.
-   Corrigi um problema de onde os nomes de produto são localizados quando eles não devem ser.
-   Corrigi um problema em que a dica de ferramenta e KeyTip "Conte-me" não correspondem e estão em conflito com outras dicas de tecla na faixa de opções em várias versões localizadas.
-   Corrigi um problema onde Windows está mostrando Outlook como um novo aplicativo após uma atualização do Office 2013 para 2016 do Office.
-   Corrigi um problema em que a atualização para o Office 2016 do Office 2013 versão 15.0.4615.1002 (maio de 2014) resultará em um erro de 0x80041015.



## <a name="version-1509-october-5"></a>Versão 1509: 5 de outubro
*Versão 1509 (compilação 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Corrigir um problema com o Office 365 Business, onde tentando usar o OneNote com SharePoint resulta em uma mensagem de erro que informa aos usuários que eles têm a atualização para uma versão diferente do Office.
-   Corrigi um problema com 3 Surface Pro, onde visualização de gravação de vídeo não mostrar o que está sendo registrado.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Alterar o que um visualizador vê quando o participante do compartilhamento bloqueios tela no RDP. Visualizador agora é mostrada uma notificação, em vez da imagem de pausa RDP.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema de Click-to-Run onde o serviço do Office 2013 Click-to-Run não é restaurado se a atualização automática para Office 2016 não concluída devido a um erro ou cancelamento pelo usuário.
-   Corrigi problemas de um Click-to-Run onde uma falha durante a atualização automática para Office 2016 resulta em uma falha na atualização e não ser capaz de usar ou desinstalar os aplicativos do Office 2013.
-   Corrigir um problema de Click-to-Run onde tentar novamente a atualização automática 2016 Office após a reinicialização dos durante um anterior tenta atualizar leva a uma falha na atualização e incapacidade para serem desligados.
-   Corrigi um problema de Click-to-Run onde a tarefa de fluxo durante a instalação não é capaz de recuperar com êxito se o computador é reiniciado.
-   Corrigi um problema de Click-to-Run onde reinicializar durante uma atualização manual para Office 2016 deixa tarefas em um estado "em execução".
-   Corrigi um problema de Click-to-Run onde iniciar um aplicativo recém-instalada durante ao meio da instalação processar resulta em uma caixa de diálogo "conexão de Internet perdido" aparecer.
-   Para corrigir um problema de Click-to-Run onde os blocos de app mostrados durante a instalação não estiverem ativa e não iniciem o aplicativo quando os usuários clicado no lado a lado do aplicativo.
-   Corrigi um problema de Click-to-Run onde atualização automática de uma instalação sr-latn-cr para Office 2016 não converte a linguagem do cliente para sr-latn-rs.
-   Corrigi um problema de Click-to-Run onde a atualização automática falha enquanto a preparar a atualização quando há vários SKUs do Office instalado no computador.
-   Corrigi um problema de Click-to-Run onde as caixas de diálogo de erro aparecem se uma atualização manual é iniciada enquanto uma atualização automática estiver sendo executado.
-   Atualize as referências à "Suplementos" do produto da interface do usuário onde a capitalização do termo está incorreta.



## <a name="version-1509-september-22"></a>Versão 1509: 22 de setembro
*Versão 1509 (compilação 4229.1024)*

Esta é a versão inicial para este canal. Esta versão fornece a primeira disponibilidade dos aplicativos do Office 2016.

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-099](https://technet.microsoft.com/library/security/ms15-099): vulnerabilidades no Microsoft Office pode permitir a execução de código remoto (3089664)
-   Boletim de segurança da Microsoft [MS15-110](https://technet.microsoft.com/library/security/ms15-110): atualizações de segurança para o Microsoft Office remoto de lidar com a execução (3096440) de código

### <a name="visio-security-updates"></a>Visio: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades no Microsoft Office pode permitir a execução de código remoto (3080790)

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades no Microsoft Office pode permitir a execução de código remoto (3080790)

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   Boletim de segurança da Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades no Microsoft Office pode permitir a execução de código remoto (3080790)
-   Boletim de segurança da Microsoft [MS15-099](https://technet.microsoft.com/library/security/ms15-099): vulnerabilidades no Microsoft Office pode permitir a execução de código remoto (3089664)

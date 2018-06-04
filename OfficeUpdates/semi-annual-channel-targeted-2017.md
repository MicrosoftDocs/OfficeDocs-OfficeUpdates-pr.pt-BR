---
title: Notas de versão para as versões de canal delimitadas anual (multidifusão) no 2017
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Fornece os profissionais de TI com notas de versão para as versões de canal delimitadas anual (multidifusão) do Office 365 ProPlus em 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/04/2018
ms.locfileid: "19555862"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Notas de versão para as versões de canal delimitadas anual (multidifusão) no 2017

Essas notas de versão fornecem informações sobre novos recursos, atualizações de segurança e atualizações não relacionadas à segurança são incluídas nas atualizações de canal delimitadas anual (multidifusão) para o Office 365 ProPlus em 2017.
 
> [!NOTE]
> - A seguir também fornece as informações sobre novos recursos, atualizações de segurança e não relacionadas à segurança atualizações para o Visio Pro para Office 365 e o cliente de Desktop do Project Online.
> - Essas informações também se aplicam ao Office 365 Business, que é a versão do Office que vem com alguns planos do Office 365, como Business Premium.
> - Canal delimitadas anual (multidifusão) foi denominado primeiro lançamento para canal adiada antes de setembro de 2017.

## <a name="version-1708-december-12"></a>Versão 1708: 12 de dezembro
*Versão 1708 (compilação 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): vulnerabilidade de execução de código remoto do Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema onde o usuário incorretamente vê uma mensagem de erro "Falha catastrófica" ao abrir um Office 2007 ou a pasta de trabalho mais antiga (. xls ou. xla) com macros.
-   Corrigi um problema onde abrir uma pasta de trabalho da linha de comando pode resultar na perda de formatação rich text em uma célula.

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilidade de divulgação de informações do Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint: Atualizações de segurança
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilidade de divulgação de informações do Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança
-   Corrigi um problema com um problema onde o campo personalizado nível projeto dados podem obter perdidos em salva.
-   Para corrigir um problema onde uma falha save pode corromper um arquivo e fazer com que o projeto a apresentar falha ao abrir.
-   Corrigi um problema onde a abertura de um plano de projeto pode levar a uma falha.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   [170021 consultoria](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office defesa em profundidade de atualização



## <a name="version-1708-november-14"></a>Versão 1708: 14 de novembro
*Versão 1708 (compilação 8431.2110)*

### <a name="access-non-security-updates"></a>Acesso: Atualizações não relacionadas à segurança
-   Corrigi um problema em que tentar selecionar texto em uma caixa de texto ou caixa de combinação aparece selecionar todo o texto, ao invés de seleção indicação.

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): vulnerabilidade de desvio de recurso de segurança do Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilidade de corrupção de memória do Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o usuário não é possível fechar uma pasta de trabalho no modo de exibição protegido, quando o nome do arquivo contém colchetes.
-   Para corrigir um problema em que, quando o usuário tentar inserir um objeto em uma pasta de trabalho existente, Excel falha quando o usuário clica em Procurar.
-   Corrigi um problema onde selecionar "Redimensionar a forma para corrigir texto" (na parte caixa de opções/texto do texto do painel de ferramentas Formatar forma) resulta em nenhuma alteração à forma.
-   Para corrigir um problema em que, ao abrir uma pasta de trabalho clicando duas vezes nele, as fontes de texto de célula e os formatos não são carregados ou duas pastas de trabalho idênticas forem abertas para um único modelo.
-   Corrigi um problema onde não o feche a primeira pasta de trabalho criada quando o Excel é iniciado quando uma nova pasta de trabalho é aberta ou criada.
-   Para corrigir um problema onde o posicionamento da dica de ferramenta é fora de alinhamento ao arrastar ou arraste o preenchimento.
-   Para corrigir um problema em que, ao salvar uma pasta de trabalho usando o arquivo \> Salvar como, um nome de arquivo que contém os períodos aparece em branco ou truncado no arquivo de diálogo Salvar.
-   Corrigi um problema em que, ao salvar um arquivo de reserva sync, Office falha gravar em disco, mas mantém Office carregar o arquivo OneDrive. Com essa correção, o usuário agora verá uma mensagem de erro e o carregamento não prossiga.
-   Corrigi um problema com a renderização onde os cabeçalhos e linhas em preto aparecem devido a um driver de gráficos defeituoso.
-   Corrigi um problema em que o Excel cai ou é capaz de salvar a pasta de trabalho depois de um gráfico será inserido.
-   Corrigi um problema onde a linha de quebra de página na visualização de quebra de página incorretamente é posicionada.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema em que o usuário vê o foco na lista de mensagens saltar inesperadamente ao excluir mensagens.
-   Corrigi um problema que faz com que o usuário veja os prompts de autenticação durante a interação com anexos.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema em que, ao salvar um arquivo de reserva sync, Office falha gravar em disco, mas mantém Office carregar o arquivo OneDrive. Com essa correção, o usuário agora verá uma mensagem de erro e o carregamento não prossiga.
-   Corrigi um problema de qual edição e formatação de texto após Desfazer em uma tabela faz o PowerPoint panes.
-   Corrigir um problema onde referências ao Flash Player baseada YouTube incorporar resultado códigos em uma nova abertura de janela para reproduzir o vídeo. Códigos de incorporar antigo agora são atualizados para referência HTML5 baseada vídeos do YouTube para que eles reproduzirem corretamente no lugar.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   [170020 consultoria](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office defesa em profundidade de atualização

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema onde Word falha quando um usuário tentar salvar como para um documento existente no OneDrive for Business e, em seguida, cancela a salvar ou tenta Mesclar alterações existentes.
-   Corrigi um problema em que, ao salvar um arquivo de reserva sync, Office falha gravar em disco, mas mantém Office carregar o arquivo OneDrive. Com essa correção, o usuário agora verá uma mensagem de erro e o carregamento não prossiga.
-   Corrigi um problema onde o Word pode travar se o usuário navega até a guia Inserir logo depois de abrir o Word.
-   Corrigi um problema onde, após clicar na margem, os caracteres são exibidos no canto superior esquerdo da tela quando você digitar caracteres.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema com o zoom e dimensionamento em Add-ins do Office em um ambiente de DPI dinâmico.
-   Corrigi um problema onde o nó CurrentStatus do provedor de serviços de configuração do Office (CSP) retorna uma sequência vazia, mesmo se o Office 365 ProPlus está instalado atualmente.
-   Corrigi um problema que causa .box alterações de formato de arquivo, o que influencia a funcionalidade das versões mais antigas do Office instaladas no mesmo computador, pois .box arquivos são compartilhados entre todas as versões de um aplicativo do Office no mesmo computador.
-   Corrigi um problema onde, sob determinadas circunstâncias ao usar a ativação do computador compartilhado, uma mensagem de erro será exibida informando que o aplicativo foi executado em um erro dizendo que o está impedindo a partir funcionando corretamente e perguntando se o usuário deseja executar um reparo.



## <a name="version-1708-october-10"></a>Versão 1708: 10 de outubro
*Versão 1708 (compilação 8431.2107)*

### <a name="access-non-security-updates"></a>Acesso: Atualizações não relacionadas à segurança
-   Corrigi um problema onde uma consulta não irá executar se a consulta tem uma junção com uma chave primária de uma tabela vinculada do Microsoft Dynamics.
-   Corrigi um problema onde casas decimais não são exibidas para valores monetários em uma tabela do Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Para corrigir um problema em que o Excel Falha ao abrir um. Arquivo XLL.
-   Corrigi um problema onde o estilo do padrão de uma célula não seja processada corretamente após a adição de um cabeçalho ou rodapé no modo de exibição de Layout de página.
-   Corrigi um problema onde colando uma cópia de uma tabela dinâmica em outra pasta de trabalho pode resultar em uma falha.
-   Corrigi um problema onde, quando você escolhe o comando Substituir e abre a caixa de diálogo Localizar e substituir, o foco da caixa de diálogo está na guia Localizar, em vez de na guia Substituir.
-   Corrigi um problema em que o Excel falha quando abrir o painel de atividade para uma pasta de trabalho aberto a partir de um servidor do SharePoint mais antigo que o SharePoint Server 2016.
-   Corrigi um problema em que o Excel abre e exibe uma janela em branco quando um ou mais suplementos XLL estão habilitados.
-   Corrigi um problema onde o Excel cai após ter usado o botão de formulários em uma pasta de trabalho já está fechada.
-   Corrigi um problema em que, ao usar o evento SheetBeforeRightClick, inserir uma coluna que intercepta células mescladas não expanda as células mescladas.

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): vulnerabilidade de desvio de recurso de segurança do Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): vulnerabilidade de divulgação de informações do Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema onde o link "Saiba mais" em dicas de política não estiver visível ao usar o tema cinza escuro.
-   Corrigi um problema em que o Outlook falha quando o usuário está tentando configurar uma nova conta e eles fecharem a janela sem concluir a configuração da conta.
-   Corrigi um problema onde marcar como lida e marcar como não lida são exibidos como opções para mensagens na caixa de entrada compartilhada para um grupo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o PowerPoint cai ao abrir uma apresentação de um servidor do SharePoint mais antigo que o SharePoint Server 2016.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Word trava quando abrir o painel de atividade para um documento aberto a partir de um servidor do SharePoint mais antigo que o SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): vulnerabilidade de execução de código remoto do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema onde o andamento de reparo Online não será mostrado ao usuário.
-   Corrigi um problema onde as propriedades de arquivo do Office não são exibidas no Gerenciador de arquivos.
-   Corrigi um problema em que o Office desaparecem de suplemento botões na faixa de opções quando houver um segundo documento aberto.
-   Corrigi um problema onde alguns módulos VBA que têm nomes com caracteres de byte duplo não podem ser abertos.



## <a name="version-1708-september-12"></a>Versão 1708: 12 de setembro
*Versão 1708 (compilação 8431.2079)*

### <a name="access-feature-updates"></a>Access: Atualizações de recurso
-   **Propriedade de nome de rótulo:** Melhore a associar um rótulo um controle em um formulário de acessibilidade.
-   **a edição de um novo item é mais acessível:** Use um atalho de teclado rápida (Ctrl + E) para editar um novo item de uma caixa de combinação ou caixa de listagem.
-   **Dynamics connector:** Importar dados de ou vincular dados armazenados no Microsoft Dynamics. [Obter mais informações](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Conector da equipe de vendas:** Importar dados de ou vincular dados armazenados na equipe de vendas. [Obter mais informações](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: Atualizações de recurso
-   **Aprimoramentos "Adicionar colunas de exemplos":** Suporta mais transformações de data/hora, matemática e índice de coluna.
-   **Melhorias de desempenho:** Excel abre pastas de trabalho complexas com várias planilhas mais rapidamente, portanto você pode processa fórmulas com intervalos grandes, do que filtrar várias linhas, ou copie e cole mais rápidos.
-   **Inserir imagens online:** Nova página de aterrissagem do selecionando imagens e informações de atribuição é inserida automaticamente com a imagem.
-   **Conector do repositório do azure dados Lake:** Os usuários agora podem importar dados do Azure Lake do repositório de dados.
-   **Aprimoramentos "Adicionar a coluna de exemplos":** Oferece suporte a transformações adicionais, mais operações de data/hora e sugestões.
-   **Guia de dados**: botões da faixa de opções na guia dados tem foi reorganizados para dois novos grupos: Get & transformar dados e consultas & conexões.
-   **Compartilhar consultas**: exporte qualquer definição de consulta em um arquivo de Conexão de banco de dados do Office (ODC) e compartilhá-lo nas pastas de trabalho ou com outras pessoas.
-   **Carregar dados:** Carregar dados de uma consulta diretamente em tabelas dinâmicas ou gráficos dinâmicos, sem precisar salvar os dados no modelo de dados.
-   **Shared atividade do arquivo:** Escolha o botão de atividade no canto superior direito do arquivo para ver quando um arquivo compartilhado no OneDrive for Business ou SharePoint foi compartilhado, editado, renomeado ou restaurado.
-   **Links seguros:** Quando um usuário clica em um link, a proteção de ameaça avançadas (ATP) do Office 365 inspeciona no link para verificar se ele está mal-intencionado. Se o link é considerado mal-intencionado, o usuário é redirecionado para uma página de aviso, em vez da URL de destino original. [Obter mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **a funcionalidade de importação de dados aprimorada:** Importar facilmente e dados de várias fontes de forma. Gerenciar consultas de pasta de trabalho e as conexões com as consultas & Conexão lateral painel e compartilhar consultas com outros via arquivos ODC. [Obter mais informações](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Alterações nos arquivos compartilhados**: exibir quem fez as alterações nas pastas de trabalho compartilhadas e restauração de versões anteriores. [Obter mais informações](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Seleção de Laço com um botão de caneta:** Suporte para uso botões da caneta digital à seleção de Laço tinta sem visitar a faixa de opções.

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Excel trava temporariamente quando você expandir ou recolhe uma tabela dinâmica e os cabeçalhos de tabela dinâmica mover fora da tela.
-   Corrigi um problema onde guias são ignorados quando copiando e colando guia delimitada por texto do Word, resultando em texto não está sendo analisado em colunas.
-   Corrigi um problema em que o Excel Falha ao abrir a caixa de diálogo página da Web Publicar como.
-   Corrigi um problema em que a atualização de dados não for bem sucedida ou Excel Falha ao usar os dados de um servidor do SQL Server Analysis Services e diferem a localidade do Excel e a localidade do servidor SQL Server Analysis Services.
-   Corrigi um problema de onde os erros aparecem ao tentar salvar alterações em documentos sincronizados com o cliente do OneDrive.
-   Corrigi um problema onde as alterações não podem ser feitas em qualquer lugar em uma planilha quando houver uma tabela dinâmica com campos na área de filtro, mas nenhum outro lugar do campo.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recurso
-   **Aprimoramentos de acessibilidade:** Que fizemos facilitar a leitura e edição de texto, tabelas, listas e imagens em email quando você estiver usando um leitor de tela.
-   **Nova configuração de conta:** Configure novas contas com um novo assistente que requer menos etapas manuais.
-   **Caixa de diálogo Attach links:** Ao anexar um vínculo usando a anexação de arquivo na faixa de opções, você pode selecionar se deseja adicioná-lo como um link ou como um anexo. Se você não quiser ver essa caixa de diálogo de cada vez, vá para arquivo \> opções \> gerais e especifique como deseja que os links a ser anexado em "Opções de anexo".
-   **Suporte para anexos de local:** Arquivos do servidor do SharePoint no local são exibidos como arquivos recentes sob mensagem \> anexar arquivo local OneDrive para sites de equipe do SharePoint e de negócios são exibidas em Anexar arquivo \> procurar locais da Web e arquivos locais podem ser transferidos para OneDrive no local para sites corporativos.
-   **Classificações de negócios para grupos:**  Um nível de classificação de negócios definido pelo administrador de locatário, como confidencial, pode ser atribuído ao criar ou editar um grupo e essa classificação será exibida no cabeçalho de grupo.
-   **Acesso de convidado aos grupos do Office 365:** Colabore com pessoas fora da organização, concedendo a eles acesso a conversas do grupo, arquivos, convites de calendário e o bloco de anotações do grupo. [Obter mais informações](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Mensagens acionáveis:** Os desenvolvedores podem criar mensagens para tornar mais fácil para os usuários podem fazer ações simples ou rápidas diretamente no Outlook, sem precisar alternar para um site externo ou um aplicativo separado. [Obter mais informações](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidade de desvio de recurso de segurança do Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidade de divulgação de informações do Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidade de corrupção de memória do Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema em que você não conseguir configurar uma conta IMAP no Outlook.
-   Corrigi um problema que causa uma falha intermitente ao abrir o Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recurso
-   **Inserir imagens online:** Nova página de aterrissagem do selecionando imagens e informações de atribuição é inserida automaticamente com a imagem.
-   **Fechado legendas para vídeos:** Adicione legendas a um vídeo para tornar mais acessível. [Obter mais informações](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Narrar uma gravação:** Inclua vídeo de si próprio narração quando você faz uma gravação de uma apresentação. Gravações podem incluir animações, tinta, áudio e vídeo.
-   **Shared atividade do arquivo:** Escolha o botão de atividade no canto superior direito do arquivo para ver quando um arquivo compartilhado no OneDrive for Business ou SharePoint foi compartilhado, editado, renomeado ou restaurado.
-   **Criação de texto alt:** Um serviço baseado em nuvem gera automaticamente o texto alternativo para imagens em uma apresentação.
-   **Links seguros:** Quando um usuário clica em um link, a proteção de ameaça avançadas (ATP) do Office 365 inspeciona no link para verificar se ele está mal-intencionado. Se o link é considerado mal-intencionado, o usuário é redirecionado para uma página de aviso, em vez da URL de destino original. [Obter mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Aprimoramentos de designer:** Recomenda ideias de design profissional de listas e orientada a ação.
-   **Alterações nos arquivos compartilhados:** Exiba a quem fez as alterações nas apresentações compartilhadas e restauração de versões anteriores. [Obter mais informações](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: Atualizações de segurança
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): vulnerabilidade de execução de código remoto do PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): vulnerabilidade de execução de código remoto do PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema onde caracteres definido de usuário final (EUDCs) que são vinculados a fontes não são exibidos.

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança
-   Corrigi um problema onde abrir determinados arquivos do Project Online faz com que o Project pane.
-   Corrigi um problema onde início real pode ser erroneamente limpo quando você definir o trabalho restante.
-   Corrigi um problema onde a data de início real de atribuição podem mostrar dados diferentes que foi relatado pelo recurso por meio de status no Project Web App.
-   Corrigi um problema em que o trabalho real pode ser reagendado se a data de término da tarefa é alterada.
-   Corrigi um problema onde se você copiar e cola campos de custo, valores colados podem não corresponder exatamente os valores copiados devido a um problema de arredondamento.
-   Corrigi um problema onde dados divididos em fases para recursos do orçamento não são copiados quando você salva a partir de uma linha de base para outro.
-   Corrigi um problema onde o campo status não sempre calcula corretamente para tarefas de resumo.
-   Corrigi um problema onde trabalho real erroneamente obtém transferido para um recurso da empresa quando ele substitui um recurso local e trabalho protegido está ativado.
-   Corrigi um problema onde o projeto cai se você tiver uma tabela em que a primeira coluna é o nome da tarefa, a coluna está bloqueada e você clicar em uma tarefa.
-   Corrigi um problema de onde você pode atribuir o mesmo recurso várias vezes para a mesma tarefa por meio do modo de exibição Uso da tarefa.
-   Corrigi um problema de onde os valores dos campos personalizados de número podem ser perdidos ao abrir arquivos XML.
-   Corrigi um problema onde o recuo de tarefa de nível superior não sincronizar adequadamente do projeto para uma lista de tarefas do SharePoint.
-   Corrigi um problema onde se você importar informações de atribuição, recurso ou tarefa de uma pasta de trabalho do Excel, os valores no campo de trabalho podem ser ignorados.
-   Corrigi um problema onde valores de linha de base divididos em fases não coincidem com os valores iniciais quando você salva um projeto para o formato de arquivo XML.
-   Corrigi um problema em que o cliente do projeto não será aberto um projeto desde que ele considera que o projeto está com check-out quando ele realmente não está.
-   Corrigi um problema para que abrir arquivos do Project a partir de um servidor de arquivos com alta latência aberta mais rapidamente.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI+ vulnerabilidade divulgação de informações
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): vulnerabilidade de divulgação de informações de componente de elementos gráficos
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): execução de código remoto do componente de elementos gráficos da Microsoft

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Adicione diálogo que explica por que um usuário é capaz de ingressar em uma reunião quando determinadas portas sejam bloqueadas ou IPs não estão na lista branca.
-   Corrigi um problema onde as mensagens não lidas em salas de chat persistentes estiverem marcadas como lidos quando você clica em guias de conversa de mensagem Instantânea.
-   Corrigi um problema onde o IM em entrada brindes experiência um atraso de segundo várias.
-   Corrigi um problema onde um contato da AD é exibido como um número de telefone em vez do nome do contato quando a sincronização com o Exchange está desabilitada.
-   Corrigi um problema de onde os usuários de ingresso anônimo são bloqueados ingressem quando federação está desabilitada e o ingresso anônimo não está bloqueado explicitamente pelo organizador da reunião.
-   Corrigi um problema onde o número de convidados incorretamente é exibido para o organizador para reuniões que excedem o limite da reunião.
-   Corrigi um problema onde o número de telefone não é exibido na proposta em chamadas de entrada PSTN.
-   Corrigi um problema em que, ao usar a tecla Delete ao renomear um grupo da lista de contatos, todo o grupo é excluído.
-   Corrigi um problema onde a notificação de compartilhamento em uma conversa de mensagem Instantânea é liberada antes de compartilhamento for interrompido.
-   Corrigi um problema onde a tela de entrada estiver em branco para alguns idiomas diferentes do inglês.
-   Corrigi um problema de onde os caracteres do inglês no histórico de chat e bate-papo são truncados.
-   Exibe o número de telefone do chamador para uma chamada de entrada tratada pelo atendedor automático organizacional se o nome do usuário não é conhecido.
-   Adicionar uma configuração de inband permitindo a restrição de "Qualquer pessoa (sem restrições)" como uma opção para "essas pessoas não precisam aguardar no lobby."
-   Adicione a capacidade de ativar ou desativar o vídeo de autoatendimento para P2P vídeo chama no VDIv2.
-   Corrigi um problema onde números duplicados exibem contatos no menu suspenso de chamada.
-   Corrigi um problema de onde os representantes são removidos para usuários que mover entre Skype para negócios e Skype para básica de negócios.
-   Corrigi um problema onde invisível não está visível quando usando o habilitar aparecer Offline e políticas de cliente de URL de estado personalizados.
-   Amplie o botão de participação da reunião para corrigir truncamento de alguns idiomas localizados.
-   Aumente a importância de mensagens de alta prioridade no bate-papo.
-   Adicione o Office e Skype para tipos de extensão de arquivo de negócios para listas de bloqueio de transferência de arquivo permitidos.
-   Correções de localização em convites de reunião do Outlook para o texto do rodapé das reuniões é definida no não estão em inglês.
-   Corrigi um problema de onde os nomes do remetente podem ser alternados em conversas de vários usuários.
-   Corrigi um problema em que a janela de conversa em branco não aparecer até que uma reunião é incluída com êxito.
-   Corrigi um problema onde as informações do campo departamento em um cartão de visita estão vazias nos resultados da pesquisa se o campo título estiver vazio.
-   Corrigi falhas de entrada para os usuários migrados no local para online devido às regras de firewall.
-   Adicione uma nova chave de Registro DWORD para corrigir um problema em que, quando um usuário se conecta ao cliente em uma rede externa executando LyncAutoD, o cliente redefine a chave de registro OAuthUsed como false. Para corrigir o problema, defina o valor como 1 para EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket em HKEY\_atual\_usuário\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: Atualizações de recurso
-   **Criar diagramas dos dados do Excel:** Crie automaticamente um fluxograma básico ou um fluxograma multifuncional dos dados do Excel usando novos modelos de Visualizador de dados. [Obter mais informações](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Links seguros:** Quando um usuário clica em um link, a proteção de ameaça avançadas (ATP) do Office 365 inspeciona no link para verificar se ele está mal-intencionado. Se o link é considerado mal-intencionado, o usuário é redirecionado para uma página de aviso, em vez da URL de destino original. [Obter mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: Atualizações de não segurança
-   Corrigi um problema onde os suplementos de COM não recebem eventos de documento aberto quando um arquivo do Visio é aberto por um clique duas vezes em um arquivo de ícone ou nome de arquivo.

### <a name="word-feature-updates"></a>Word: Atualizações de recurso
-   **Inserir imagens online:** Nova página de aterrissagem do selecionando imagens e informações de atribuição é inserida automaticamente com a imagem.
-   **Criação de texto alt:** Um serviço baseado em nuvem gera automaticamente o texto alternativo (texto alt) para imagens em um documento.
-   **Shared atividade do arquivo:** Escolha o botão de atividade no canto superior direito do arquivo para ver quando um arquivo compartilhado no OneDrive for Business ou SharePoint foi compartilhado, editado, renomeado ou restaurado.
-   **Links seguros:** Quando um usuário clica em um link, a proteção de ameaça avançadas (ATP) do Office 365 inspeciona no link para verificar se ele está mal-intencionado. Se o link é considerado mal-intencionado, o usuário é redirecionado para uma página de aviso, em vez da URL de destino original. [Obter mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Alterações nos arquivos compartilhados:** Exiba a quem fez as alterações em documentos compartilhados e restauração de versões anteriores. [Obter mais informações](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Word fecha inesperadamente ao carregar o suplemento Grammarly.
-   Corrigi um problema onde, sob certas condições, Word trava ao tentar recuperar arquivos baseada na nuvem.
-   Corrigi um problema onde as formas dentro de tela de desenho não podem ser giradas.
-   Corrigi um problema em que, durante a digitação em coreano, consoantes e vogais são incorretamente separadas.
-   Salvar um documento como um PDF salva o documento como uma versão 1.7 PDF.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema que impeça o que é a caixa de diálogo nova exibição.
-   Corrigi um problema onde clicar na guia Draw faz com que o aplicativo falhe para alguns usuários.
-   Corrigi um problema onde passar o mouse sobre um controle comum que possui uma dica de ferramenta sobre ele faz com que o aplicativo falhe.
-   Corrigi um problema em que uma mensagem de erro de licenciamento aparece ao usar controles comuns.
-   Corrigi um problema com como alguns arquivos de programa são assinados, causando programas antivírus sinalizar esses arquivos, bem como problemas protegendo ou acessando dados em proteção de informações do Windows (WIP).
-   Adicionar support.to permitem que os usuários que trabalham em versões de 64 bits do Office para abrir os arquivos de macro que contêm controles Mscomctl.
-   Melhore a acessibilidade de controles usados no Mscomctl.
-   Corrigi um problema de onde os comandos estão faltando na faixa de opções ou as caixas de diálogo de personalização da barra de ferramentas de acesso rápido.



## <a name="version-1705-august-8"></a>Versão 1705: 8 de agosto
*Versão 1705 (compilação 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema com arrastar a barra de rolagem para mover-se por meio de uma lista de mensagens.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema com como alguns arquivos de programa são assinados, causando programas antivírus sinalizar esses arquivos, bem como problemas protegendo ou acessando dados em proteção de informações do Windows (WIP).
-   Corrigi um problema que impeça o que é a caixa de diálogo nova exibição.



## <a name="version-1705-july-27"></a>Versão 1705: 27 de julho
*Versão 1705 (compilação 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema de onde os erros aparecem ao tentar salvar alterações em documentos sincronizados com o cliente do OneDrive.
-   Corrigi um problema onde Excel Falha ao adicionar dados de planilha a um modelo de dados e o tema de alto contraste é definido como preto.

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidade de desvio de recurso de segurança do Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidade de divulgação de informações do Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidade de corrupção de memória do Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema onde adicionando uma forma, após o outro usuário altera o layout faz com que uma falha de mala direta.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema em que, durante a digitação em coreano, consoantes e vogais são incorretamente separadas.
-   Corrigi um problema no qual o endereço do destinatário em envelopes é impresso muito próximo até a borda esquerda.



## <a name="version-1705-july-13"></a>Versão 1705: 13 de julho
*Versão 1705 (compilação 8201.2136)*

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Excel falha para pastas de trabalho que contêm links externos.
-   Corrigi um problema onde colar as células do Excel para o Word mostra zeros nas células, mesmo que a configuração "Mostrar um zero nas células com valor zero" não está selecionada.

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança
-   Corrigi um problema de onde os valores que são selecionados para uma tabela/gráfico não estão visíveis no painel de tabela do gráfico.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Para corrigir um problema onde uma janela de conversa não mostrada no plano de fundo ao ingressar em uma reunião e a caixa de diálogo de ingresso de dispositivos de áudio é mostrada ao usuário.
-   Corrigi um problema onde o link da reunião do Outlook não sempre passa URI interno adequadamente.
-   Ampliado no botão de participação da reunião para corrigir truncamento de alguns idiomas localizados.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema onde tabelas não são exibidos corretamente após determinadas ações.
-   Corrigi um problema com qual várias edições para citações algum tempo aparece como uma única ação desfazer em vez de ações individuais consecutivas.
-   Corrigi um problema onde desfazer é desativado após determinadas ações.
-   Corrigi um problema para evitar a perda de dados possíveis depois de algumas ações de desfazer.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidade de execução de código remoto do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema que causa upgrades autônomos do Office 2013 para Office 2016 falhe quando usando o System Center Configuration Manager.
-   Corrigi um problema de onde os suplementos herdados implantados do repositório por meio do catálogo corporativo não carregam.



## <a name="version-1705-june-13"></a>Versão 1705: 13 de junho
*Versão 1705 (compilação 8201.2102)*

### <a name="access-feature-updates"></a>Access: Atualizações de recurso
-   **o que há de novo diálogo:** Uma caixa de diálogo que destaca os novos recursos de acesso é exibida quando o Access for aberto após o Access foi atualizado com os novos recursos. A caixa de diálogo também está disponível, indo para o arquivo \> conta \> What's New.
-   **Suporte número grande (bigint):** Use o tipo de dados grande número nas tabelas do Access para calcular grandes números, bem como vincular ou importar de bancos de dados externos que usam um tipo de dados equivalentes, como bigint no SQL Server. [Obter mais informações](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: Atualizações de recurso
-   **Suporte de proteção de informações do Windows (WIP):**   Excel agora é um aplicativo esclarecedora e pode diferenciar entre dados corporativos e pessoais, corretamente determinar qual proteger, com base em políticas configuradas.  [Obter mais informações](https://aka.ms/wiptechnet)
-   **Obter & transformar aperfeiçoamento:** No Editor de consulta, crie uma nova coluna, fornecendo valores de exemplo. Conforme você digita, o Excel detecta as transformações necessárias e mostra uma visualização da nova coluna.
-   **Inserir links recentes:** Facilmente com anexação de hiperlinks para sites ou de arquivos recentes baseado em nuvem e criar nomes de exibição significativo para pessoas que usam leitores de tela. [Obter mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personalizar o layout de tabela dinâmica padrão:** Configure uma tabela dinâmica da maneira desejada e iniciar com que o layout toda vez que você criar uma nova tabela de dinâmica. [Obter mais informações](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Obter & transformar aprimoramentos:** Os usuários podem criar novas colunas, por exemplo e dividir as colunas da tabela em linhas. Especificar parâmetros para HANA SAP e agrupando dados agora é mais fácil.
-   **Implantação centralizada de suplementos**: os administradores podem implantar e atualizar suplementos a usuários ou grupos do Centro de administração do Office 365. [Obter mais informações](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personalização da barra de ferramentas de acesso rápido:** Os ícones de subscrito e sobrescrito podem ser adicionados à barra de ferramentas de acesso rápido.
-   **Obter & transformar aprimoramentos:** Detecção automática de caractere delimitador quando divisão colunas usando o Editor de consulta, escolha o arquivo de amostra para usar com binários combinar e especificar a coleção de pacote para se conectar ao uso do conector DB2.
-   **Fonte Dubai:** Família de fontes que ofereça suporte a idiomas da Europa Ocidental, bem como os principais idiomas que usam o script árabe. [Obter mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de plano de fundo:** Remova um plano de fundo da imagem com uma ferramenta de desenho de forma livre.
-   **Obter & transformar aprimoramentos:** Use "Selecione tabelas relacionadas" na caixa de diálogo navegador com as conexões OLEDB e ODCB, combine vários arquivos diretamente a partir da caixa de diálogo de visualização de dados de pasta e usar uma nova opção de menu de contexto na janela Editor de consulta para inserir novas etapas em consultas existentes.
-   **Use uma caneta para selecionar e alterar objetos:** Pegar alças de objeto com uma caneta digital para redimensionar, girar, mover e muito mais.
-   **Mapear gráfico:** Comparar valores e Mostrar categorias entre as regiões geográficas. [Obter mais informações](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Imagens SVG:** Inserir e editar elementos gráficos vetoriais escaláveis (SVG) em pastas de trabalho. [Obter mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  Use os ícones de uma biblioteca padrão dos arquivos SVG (SVG) indo para inserir \> ilustrações \> ícones. [Obter mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salvar em pastas recentes:** Salvar uma pasta de trabalho em uma pasta de usados recentemente usando a guia recente quando você passar para o arquivo \> Salvar como.
-   **Aprimoramentos de acessibilidade:** Suporte aprimorado para usar o teclado, Narrator e outras tecnologias de assistência para ler e editar pastas de trabalho. [Obter mais informações](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): atualização de segurança para o Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Excel não define a senha de proteção da planilha quando aplicada por meio de programação para pastas de trabalho criadas no Excel 2010 ou anterior.
-   Corrigi um problema onde mesclar & Central não funcionam em planilhas agrupadas.
-   Corrigi um problema onde novas funções que foram introduzidas após o lançamento do Office 2016 - por exemplo, TEXTJOIN, CONCAT, IFS, MAXIFS e MINIFS - estão ausentes.
-   Corrigi um problema em que o Excel falha quando o usuário tenta aplicar permissões de nível de célula.
-   Para corrigir um problema onde salvar um arquivo de grande ao OneDrive for Business faz com que o arquivo a ser bloqueado e o usuário não pode editar o arquivo até que o usuário fecha e reabre o Excel.
-   Corrigi um problema em que uma nova janela será exibido em cinza quando uma pasta de trabalho. xls é aberta.
-   Corrigi um problema onde o Excel pode apresentar falha quando inserir hiperlinks.
-   Corrigi um problema em que o Excel pode falhar ao adicionar mapas XML.
-   Corrigi um problema em que o botão de comando para um suplemento não funciona depois que o suplemento for atualizado ou após remover e baixar o suplemento novamente da Office store.
-   Corrigi um problema em que o Excel pode apresentar falha quando manipulando folhas de DLL via VBA.
-   Corrigi um problema em que o Excel Falha ao selecionar uma caixa de combinação do controle de formulário em uma planilha de gráfico.

### <a name="onenote-feature-updates"></a>OneNote: Atualizações de recurso
-   **Suporte de proteção de informações do Windows (WIP):** OneNote agora é um aplicativo esclarecedora e pode diferenciar entre dados corporativos e pessoais, corretamente determinar qual proteger, com base em políticas configuradas. [Obter mais informações](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Corrigi um problema onde a tela de desenho do OneNote oculta conteúdo ou atualizações quando vários parágrafos estão no modo de exibição.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recurso
-   **Suporte de proteção de informações do Windows (WIP):**   Outlook agora é um aplicativo esclarecedora e pode diferenciar entre dados corporativos e pessoais, corretamente determinar qual proteger, com base em políticas configuradas.  [Obter mais informações](https://aka.ms/wiptechnet)
-   **Inserir links recentes:** Anexe os hiperlinks para sites ou de arquivos recentes baseado em nuvem e criar nomes de exibição significativo para pessoas que usam leitores de tela. [Obter mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Fonte Dubai:** Família de fontes que ofereça suporte a idiomas da Europa Ocidental, bem como os principais idiomas que usam o script árabe. [Obter mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de plano de fundo:** Remova um plano de fundo da imagem com uma ferramenta de desenho de forma livre.
-   **Verificar o acesso a arquivos compartilhados:** O Outlook informa ao usuário antes do tempo se destinatários podem não conseguir acessar um arquivo anexado do OneDrive ou do SharePoint e sugere como corrigir o problema.
-   **Definir permissões em anexos:** Anexos de OneDrive ou do SharePoint, o usuário pode definir se os receptores, na organização ou externamente, leram ou editar permissões para o anexo.
-   **Taskpane fixas:** Deixe o painel de tarefas do suplemento aberto ao mesmo tempo, alternando entre mensagens em uma caixa de correio. [Obter mais informações](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Imagens SVG:** Inserir e editar elementos gráficos vetoriais escaláveis (SVG) em emails. [Obter mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  Use os ícones de uma biblioteca padrão dos arquivos SVG (SVG) indo para inserir \> ilustrações \> ícones.  [Obter mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilidade de execução de código remoto do Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilidade de desvio de recurso de segurança do Microsoft Office
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): execução de código remoto do Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): vulnerabilidade de desvio de recurso de segurança do Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema onde o painel de navegação do Outlook interrompe o processamento quando o computador tiver pouco memória.
-   Larguras de anexo visualmente expandam para ajustar as informações de permissão e nome de arquivo.
-   Corrigi um problema no qual o usuário não pode pesquisar arquivos PST.
-   Corrigi um problema em que o usuário vê "Microsoft Exchange" novo armazenar tipo na caixa de diálogo "Novo arquivo de dados de Outlook" e selecionar esse novo tipo de dados faz com que o perfil do usuário inoperante.
-   Corrigi um problema onde uma imagem em uma mensagem é blacked check-out quando enviado de um computador usando DPI alta.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recurso
-   **Suporte de proteção de informações do Windows (WIP):**   PowerPoint agora é um aplicativo esclarecedora e pode diferenciar entre dados corporativos e pessoais, corretamente determinar qual proteger, com base em políticas configuradas.  [Obter mais informações](https://aka.ms/wiptechnet)
-   **Inserir links recentes:** Anexe os hiperlinks para sites ou de arquivos recentes baseado em nuvem e criar nomes de exibição significativo para pessoas que usam leitores de tela. [Obter mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implantação centralizada de suplementos**: os administradores podem implantar e atualizar suplementos a usuários ou grupos do Centro de administração do Office 365. [Obter mais informações](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fonte Dubai:** Família de fontes que ofereça suporte a idiomas da Europa Ocidental, bem como os principais idiomas que usam o script árabe. [Obter mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de plano de fundo:** Remova um plano de fundo da imagem com uma ferramenta de desenho de forma livre.
-   **Imagens SVG:** Inserir e editar elementos gráficos vetoriais escaláveis (SVG) nas apresentações. [Obter mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  Use os ícones de uma biblioteca padrão dos arquivos SVG (SVG) indo para inserir \> ilustrações \> ícones. [Obter mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Digitando em tempo real durante coautoria:** Consulte onde outras pessoas estão trabalhando na apresentação e modo de exibição é alterado enquanto eles digitam. [Obter mais informações](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Salvar em pastas recentes:** Salvar uma apresentação em uma pasta usada recentemente usando a guia recente quando você passar para o arquivo \> Salvar como.
-   **Criar formas de tinta precisas:** Arraste a borracha segmento para remover o bits em excesso de tinta, direita até a linha mais próxima.
-   **Selecione e manipular os objetos com uma caneta:** Usar uma caneta digital para mover, redimensionar ou girar objetos usando suas alças ou usar os botões de caneta com suporte à seleção de Laço tinta.
-   **Aprimoramentos de acessibilidade:** Suporte aprimorado para usar o teclado, Narrator e outras tecnologias de assistência para ler e editar apresentações. [Obter mais informações](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o PowerPoint cai quando o usuário estiver no painel de ideias de Design, se o arquivo mfplat.dll não estiver instalado no computador.
-   Corrigi um problema em que o botão de comando para um suplemento não funciona depois que o suplemento for atualizado ou após remover e baixar o suplemento novamente da Office store.

### <a name="project-feature-updates"></a>Projeto: Atualizações de recurso
-   **Rápida suspensa para a configuração predecessores:** Use o lista suspensa do gráfico de Gantt para escolher quais tarefas predecessoras ou sucessoras que você deseja vincular a uma tarefa.
-   **Nome de resumo da tarefa:**  Campo de tarefa somente leitura que mostra o nome da tarefa de resumo da tarefa.  

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança
-   Corrigi a caixa de diálogo Criar Site de projeto para mostrar o local correto para o site agora que no Project Online cada modelo de projeto da empresa (EPT) terá sua própria URL para sites de projeto.
-   Para corrigir um problema onde o evento BeforeClose VBA dispara antes do prompt de salvar e você não tiver uma forma programática para determinar a resposta do usuário para salvar prompt.
-   Corrigi um problema onde % física concluída não acumular corretamente para tarefas iniciando após a data de status do projeto.
-   Para corrigir um problema quando um recurso de custo e trabalho é atribuído à mesma tarefa, você não poderá alterar o gerente de status da tarefa.
-   Corrigi um problema onde para alguns projetos, todo o projeto de redistribuição podem deixá-lo em um loop infinito.
-   Um problema no qual a tarefa inicia e datas de término de correção não sincronizar a uma lista de tarefas do SharePoint corretamente se você tiver determinadas configurações regionais espanholas.
-   Corrigi um problema onde se você iniciar o processo de aprovações de status do cliente Project, ele talvez nunca terminar, deixando o projeto inutilizar.
-   Corrigi um problema onde visualização de impressão não nomes de tarefa de layout corretamente se você tiver palavras chinês e inglês.
-   Corrigi um problema de onde copiar a linha do tempo para PowerPoint como formas individuais não funciona.
-   Corrigir um problema em que a caixa de diálogo "Vínculos entre projetos" inesperadamente exibe o valor "Arquivo não encontrado".
-   Correção de um problema que você obtenha inconsistente resultados ao atribuir recursos com unidades máximas 0.
-   Corrigi um problema onde data de início da tarefa obtém redefinida para assim que possível quando a exclusão de data de início de uma atribuição, ignorando as coisas como predecessoras, que leva a líderes de divisões nas atribuições.
-   Para corrigir um problema onde se você abrir um arquivo do SharePoint por meio do menu recente, o projeto é automaticamente check-out para você mesmo se a configuração "Exigem documentos sejam verificados antes que eles podem ser editados?" está habilitado.
-   Corrigi um problema onde se você ir diretamente para o aplicativo de perfis do Project, Project cai.
-   Corrigi um problema onde tarefas agendadas manualmente não são atualizadas corretamente para os usuários a atualização do Project 2013.
-   Corrigi um problema onde quando abrir um projeto a partir de uma lista do SharePoint da lista de tarefas, Project pode travar enquanto o projeto é iniciado o processo de sincronização de tarefa.
-   Corrigi um problema onde o projeto falha em alguns casos, quando pretende criar equipe.
-   Corrigi um problema onde as informações de linha de base serão perdidas ao salvar um projeto.
-   Corrigi um problema onde impressões são difíceis de leitura para os planos de projeto grande.
-   Corrigi um problema onde projetos editados no Project Web App não mostram os valores corretos para os campos de fórmula.
-   Corrigi um problema onde as informações de campos personalizados da empresa do recurso não não salva corretamente para um plano de projeto.
-   Corrigi um problema onde a atualização % da tarefa trabalho concluído informações atualiza informações completas de % da tarefa.
-   Corrigi um problema onde a propriedade project altera quando o projeto é salvo.
-   Corrigi um problema onde a IDC incorretamente é calculado para uma tarefa de resumo.
-   Para corrigir um problema onde copiando e colando tarefas traz os dados de linha de base e os dados são salvos, mesmo que o usuário não é permitido para salvar os dados de linha de base protegida.
-   Corrigi um problema de onde a importação de dados do Excel resulta em informações de data incorreto para tarefas e atribuições.
-   Corrigi um problema onde, depois de abrir um relatório, Project cai ao fechar.
-   Corrigi um problema onde Project parar de funcionar ao salvar um projeto em que uma lista personalizada contém configurações de validação.
-   Para corrigir um problema onde inserir o "\>" caractere na coluna de teste na caixa de diálogo Definição de filtro não está corretamente interpretada como significado "é maior que."
-   Corrigir um problema com a exibição das linhas de andamento em relação à "Plano de linha de base".
-   Corrigi um problema onde a lista suspensa de nomes de campo não aparece ao personalizar filtros.
-   Corrigi um problema onde as visualizações de estilo de barra não aparecem na caixa de diálogo Estilos de barra.

### <a name="publisher-non-security-updates"></a>Publisher: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Publisher não exibe imagens CMYK TIF.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: recursos de atualizações
-   **Inserir link:** Adicione um link à mensagem Instantânea e chats de grupo e forneça o texto amigável para o link, em vez da URL completa.
-   **Notificação de compartilhamento de tela:** Uma notificação será exibida na janela de conversa quando estiver compartilhando uma tela em uma conversa de mensagens Instantâneas ou compartilhamento de tela continuará depois que você sair de uma reunião. A notificação lembra que você ainda estiver compartilhando sua tela e torna mais fácil interromper o compartilhamento usando o botão "Interromper compartilhamento".
-   **Suporte de proteção de informações do Windows (WIP):** Skype para negócios agora é suportado como um aplicativo somente do trabalho WIP.  Adicionando Skype à sua lista de aplicativos permitidos, ele indica Windows que ele não manipula dados pessoais.  Windows proteger os dados em nome do Skype para negócios.  [Obter mais informações](https://aka.ms/wiptechnet)
-   **Opção de redefinição de senha:** Um link de botão de redefinição é exibida na janela de entrada quando um usuário não consegue entrar em pelo menos uma vez.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   Boletim de segurança da Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): atualização de segurança para o componente de gráficos da Microsoft (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): vulnerabilidade de execução de código de cancelar inscrição remota do Windows
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): Skype para a vulnerabilidade de execução de código remoto de negócios

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Alterar a mensagem para chamadas tentadas para usuários com áudio desabilitado por diretiva de "Não é possível completar a chamada" para "não é possível chamar porque um administrador de TI tem restritas áudio. Tente usar mensagens instantâneas ou email em vez disso e pede para Verifique com seu administrador de TI".
-   Adicione que um hiperlink "Esqueceu o seu PIN de discagem" para reunião convida de usuários de conferência PSTN estiver habilitada para Skype para negócios Online.
-   Habilite a participação da reunião de equipes do Skype para Business Online.
-   Altere o volume de sessão de alto-falante do padrão de 40% para 75%.
-   Permitir o redimensionamento de lista de tabulação para uma largura mínima menor.
-   Atualize as teclas de atalho para corresponder a ordem das guias.
-   Corrigi incorreta direção do texto em hebraico durante o envio de um dispositivo móvel.
-   Corrigi um problema com as informações narrativa por um leitor de tela para o recurso de controle de área de trabalho/dar presente.
-   Mostrar aberto salas, além das salas visitadas em listas de salas selecione.
-   Adicione a capacidade de desativar o recurso de VoIP enquanto o aplicativo RCC personalizado estiver habilitado.
-   Alterar offline subtítulo de mensagens Instantâneas para "Testar o Skype para aplicativos de negócios móveis".
-   Para corrigir um problema que faz com que uma janela de conversação para uma conversa automaticamente aceita seja aberto como uma janela normal, em vez de minimizada e receba o foco para longe de outras janelas inesperadamente.
-   Corrigi um problema com usando um leitor de tela na caixa de diálogo Opções de reunião do Skype.
-   Corrigi um problema onde a primeira mensagem em um convite não é mostrada no email conversas perdidas.
-   Corrigi um problema de onde os números de discagem duplicados serão exibidos ao criar um convite de reunião do Outlook usando o botão Nova reunião do Skype.
-   Para corrigir um problema em que, quando uma barra de rolagem aparece, todas as conversas em um histórico de mensagens Instantâneas não forem selecionadas quando usando Ctrl + A para selecionar tudo.
-   Corrigi um problema onde o texto de saída não pode ser do mesmo formato exato ao usar o cmdlet Export-CsArchivingData.
-   Corrigi um problema em que o organizador da reunião é não é possível ver o vídeo dos participantes remotos quando usando reunir agora com 3 ou mais participantes.
-   Corrigi um problema em que a primeira linha da lista de participação da reunião estiver em branco quando um usuário clica com o botão direito no nome de outro usuário na lista de participantes.
-   Corrigi um problema de onde os usuários são não conseguir entrar quando você alterna entre interno e externas redes corporativas.
-   Corrigi um problema em que a área de bate-papo não fechará quando a transição de mensagens Instantâneas para áudio na transferência com consultoria.
-   Corrigi um problema de onde os nomes são truncados em notificações de proposta quando o toque simultâneo de dois pontos de extremidade é usado.
-   Corrigi um problema onde o nome de arquivo será truncado notificações de compartilhamento de arquivo.
-   Adicione dicas de ferramenta para Back para botões de chamada e de transferência.
-   Verifique o tempo gasto em espera na janela de transferência com consultoria disponível para leitores de tela, como o Narrator.
-   Adicione a capacidade de escolha de mensagens Instantâneas ou chamadas como a preferência de padrão para transferência com consultoria.
-   Adicione a capacidade, ao fazer uma transferência com consultoria, do mouse no botão "Transferência" para ver uma lista dos números de telefone do contato.
-   Melhorar a uma mensagem de erro geral para torná-la clear que o problema é que o usuário tem uma licença inválida ou não tiver sido atribuído uma licença.
-   Corrigi um problema onde não todos os contatos serão exibidos no título da janela de conversa quando um usuário inicia uma conversa com um contato e, em seguida, adiciona outro contato.
-   Corrigi um problema onde o Narrator não lê a linha 2ª de notificações.
-   Corrigi um problema onde as chamadas são transferidas para VOIP em vez do número consultado.
-   Corrigi um problema onde o Narrator comunica informações incorretas quando o usuário está navegando na janela de conteúdo.
-   Corrigir um problema onde os nomes de criador e o modificador não aparecem ao passar o mouse sobre uma anotação em um quadro de comunicações

### <a name="visio-feature-updates"></a>Visio: Atualizações de recurso
-   **Localizar os estênceis de terceiros:** Pesquise os estênceis de terceiros fornecidos por provedores de conteúdo selecionados.
-   **Slide trechos:** Dê trechos de um desenho do Visio e exportá-los como slides para o PowerPoint. [Obter mais informações](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: Atualizações de recurso
-   **Suporte de proteção de informações do Windows (WIP):**   Word agora é um aplicativo esclarecedora e pode diferenciar entre dados corporativos e pessoais, corretamente determinar qual proteger, com base em políticas configuradas.  [Obter mais informações](https://aka.ms/wiptechnet)
-   **Inserir links recentes:** Anexe os hiperlinks para sites ou de arquivos recentes baseado em nuvem e criar nomes de exibição significativo para pessoas que usam leitores de tela. [Obter mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implantação centralizada de suplementos**: os administradores podem implantar e atualizar suplementos a usuários ou grupos do Centro de administração do Office 365.  [Obter mais informações](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fonte Dubai:** Família de fontes que ofereça suporte a idiomas da Europa Ocidental, bem como os principais idiomas que usam o script árabe. [Obter mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de plano de fundo:** Remova um plano de fundo da imagem com uma ferramenta de desenho de forma livre.
-   **Lado a lado:** Navegue páginas no modo de exibição de Layout de impressão deslizando-as ao lado como uma pilha de papel. [Obter mais informações](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Use uma caneta para selecionar e alterar objetos:** Pegar alças de objeto com uma caneta digital para redimensionar, girar, mover e muito mais.
-   **Imagens SVG:** Inserir e editar elementos gráficos vetoriais escaláveis (SVG) em documentos. [Obter mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  Use os ícones de uma biblioteca padrão dos arquivos SVG (SVG) indo para inserir \> ilustrações \> ícones.  [Obter mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salvar em pastas recentes:** Salvar um documento em uma pasta usada recentemente usando a guia recente quando você passar para o arquivo \> Salvar como.
-   **Aprimorada leitura com ferramentas de aprendizagem:** Novos comandos no boost do modo de leitura habilidades de leitura, ajustando o espaçamento de texto, mostrando as quebras entre sílabas e realce cada palavra como o documento é lido em voz alta. [Obter mais informações](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **Reconhecimento de forma:** Transformar automaticamente seus desenhos em formas usando Draw \> converter a formas. [Obter mais informações](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): atualização de segurança para o Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): vulnerabilidade de execução de código remoto do Windows PDF 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): vulnerabilidade de execução de código remoto do Microsoft Office  

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema no qual o usuário não pode pesquisar arquivos PST.
-   Corrigi um problema em que o usuário vê "Microsoft Exchange" novo armazenar tipo na caixa de diálogo "Novo arquivo de dados de Outlook" e selecionar esse novo tipo de dados faz com que o perfil do usuário inoperante.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/WordPad código remoto execução vulnerabilidade w/Windows API
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): execução de código remoto do Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): vulnerabilidade de execução de código remoto do Microsoft Office



## <a name="version-1701-may-9"></a>Versão 1701: 9 de maio
*Versão 1701 (compilação 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema que faz com que os usuários vejam forma intermitente a seleção de mensagem na lista de mensagens saltar inesperadamente ao excluir mensagens.
-   Corrigi um problema que causa falhas intermitentes.
-   Adicionar o HKEY\_atual\_usuário\\Software\\Microsoft\\Office\\16.0\\Outlook\\opções\\geral\\DisableSupportBackstage a chave de registro para permitir que os administradores ocultar o suporte Escolha na guia arquivo.
-   Adicionar o HKEY\_atual\_usuário\\Software\\Microsoft\\Office\\16.0\\Outlook\\opções\\geral\\DisableOutlookFeedbackFeatures a chave de registro para permitir que os administradores desativar o Opções de "Outlook 2016 comentários" e "Blog do Outlook" em arquivo \> comentários.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidade de execução de código remoto do Microsoft Office

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Para corrigir um problema que faz com que uma janela de conversação para uma conversa automaticamente aceita seja aberto como uma janela normal, em vez de minimizada e receba o foco para longe de outras janelas inesperadamente.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidade de execução de código remoto do Microsoft Office

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): vulnerabilidade de execução de código remoto do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilidade de execução de código remoto do Microsoft Office



## <a name="version-1701-april-11"></a>Versão 1701: 11 de abril
*Versão 1701 (compilação 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema em que uma nova janela será exibido em cinza quando uma pasta de trabalho. xls é aberta.

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilidade de execução de código remoto do Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilidade de desvio de recurso de segurança do Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema em que o usuário vê "Microsoft Exchange" novo armazenar tipo na caixa de diálogo "Novo arquivo de dados de Outlook" e selecionar esse novo tipo de dados faz com que o perfil do usuário inoperante.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema onde uma imagem ausentes erro ocorre quando o usuário "Salvar como" para um local alternativo de um arquivo do PowerPoint que está armazenado em mídia removível, como uma unidade de thumb USB.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Corrigi um problema de onde os usuários são não conseguir entrar quando você alterna entre interno e externas redes corporativas.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/WordPad código remoto execução vulnerabilidade w/Windows API



## <a name="version-1701-march-14"></a>Versão 1701: 14 de março
*Versão 1701 (compilação 7766.2071)*

### <a name="access-non-security-updates"></a>Acesso: Atualizações não relacionadas à segurança
-   Corrigi um problema onde submenu menus não podem ser descartados.

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): atualização de segurança para o Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema onde o Excel pode apresentar falha quando inserir hiperlinks.
-   Corrigi um problema em que o Excel pode falhar ao adicionar mapas XML.
-   Corrigi um problema em que o botão de comando para um suplemento não funciona depois que o suplemento for atualizado ou após remover e baixar o suplemento novamente da Office store.
-   Corrigi um problema em que o Excel pode apresentar falha quando manipulando folhas de DLL via VBA.

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Corrigi um problema com qual tela de página do OneNote para de responder a cliques de mouse depois de autenticar usando um PIN em Windows 10 versão 1607 (também conhecido como atualização de aniversário no Windows).
-   Desabilite otimizada EDU específica printout comportamento quando um usuário insere um documento editável, como. docx ou. pptx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema onde conflitos de mesclagem aparecem de forma incorreta quando coautoria.
-   Corrigi um problema em que o botão de comando para um suplemento não funciona depois que o suplemento for atualizado ou após remover e baixar o suplemento novamente da Office store.
-   Corrigi um problema de onde os resultados de modelo em um erro em tempo de execução quando aplicado a formas em gráficos de objeto de chamadas para o VBA.

### <a name="publisher-non-security-updates"></a>Publisher: Atualizações não relacionadas à segurança
-   Corrigi um problema em que o Publisher não exibe imagens CMYK TIF.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   Boletim de segurança da Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): atualização de segurança para o componente de gráficos da Microsoft (4013075)

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): atualização de segurança para o Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema com consumos de memória ao usar determinadas configurações de monitor.
-   Corrigi um problema em que o botão de comando para um suplemento não funciona depois que o suplemento for atualizado ou após remover e baixar o suplemento novamente da Office store.



## <a name="version-1701-february-22"></a>Versão 1701: 22 de fevereiro
*Versão 1701 (compilação 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: Atualizações de recurso
-   **Aprimoramentos de transformação e conectividade de dados:** Expandir uma lista em uma nova coluna de texto com delimitador entre os valores e especifique uma opção de failover ao se conectar ao SQL.
-   **Aprimoramentos de transformação e conectividade de dados:** O tipo de dados de porcentagem agora é suportado e binário combinando função experiências criação foram melhoradas.
-   **Conector OLEDB:** Use o conector de banco de dados OLE em Get & Transform para criar uma consulta para importar dados, especificando uma cadeia de caracteres de Conexão e, opcionalmente, uma instrução SQL para executar.
-   **Repetição de tinta:** Vá para desenhar \> tinta repetição durante a repetição manuscrito frente e para trás para ocultar e revelar conteúdo, fornecem instruções passo a passo ou compreender melhor o fluxo de pensamentos dos outros. [Obter mais informações](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Suporte CSV (UTF-8):** Abrir e salvar arquivos CSV que usam a codificação de caracteres UTF-8.
-   **Transformações de dados e aprimoramentos de conectividade:** Selecione para importar tabelas relacionadas quando o carregamento de dados de fontes de OData, adicionar colunas personalizadas com valores provenientes de uma computação de função ou mostrar as dependências entre consultas usando um modo de exibição dedicado.
-   **Compartilhou comigo:** Ver os documentos que outras pessoas compartilharam com você indo para o arquivo \> Open \> compartilhadas com me. [Obter mais informações](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Alterar as cores:** Use conte-Me para definir a cor de fonte, realce, preenchimento da forma e muito mais. [Obter mais informações](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de segurança da Microsoft [MS16 148](https://technet.microsoft.com/library/security/ms16-148): atualização de segurança para o Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema em que, quando o tema do Office estiver definido como preto, uma mensagem de erro "Erro inesperado" aparece quando o botão direito do mouse em uma consulta no painel de consultas de pasta de trabalho.
-   Corrigi um problema em que o Excel falha quando o usuário tenta acessar opções da tabela dinâmica.
-   Corrigi um problema no qual os valores de células com texto e aspas duplas não são exportados corretamente ao salvar como CSV ou CSV UTF-8.
-   Corrigi um problema onde o Excel trava ou Falha ao fechar.
-   Corrigi um problema onde um hiperlink que contém uma fórmula concatenar ignora a parte do resultado concatenar.
-   Corrigi um problema onde colar uma tabela do Excel no formato rich text (RTF) para o Word não preserva o formato de tabela.
-   Corrigi um problema em que o usuário não puder executar Salvar como quando a pasta de trabalho contém uma planilha de Macro do MS Excel 4.0.
-   CTRL + ALT + 5 Verifique o atalho para mover uma seleção para a camada de objeto para coincidir com outros aplicativos.
-   A correção de um problema em que, quando digitando na barra de fórmulas e usar uma função com uma lista suspensa, como PROCV, pressionar Enter para concluir a fórmula seleciona o item superior na lista suspensa de AutoCompletar, em vez de leavingthe digitado no valor como-é.
-   Corrigi um problema onde abrir um Excel 97 - arquivo de formato (BIFF8) de arquivo binário do Excel 2003 que contém um hiperlink em uma planilha protegida faz com que o Excel achar que o arquivo está corrompido e Excel tentará reparar ou remover o conteúdo ilegível.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: atualizações não relacionadas à segurança
-   Para corrigir um problema onde, se o GrooveIntlResource.dll não pode ser carregado com êxito (que é improvável sob condições normais), um aplicativo do Office pode falhar se o usuário tentar abrir ou salvar um arquivo em uma pasta sincronizada, ou o Windows Explorer pode falhar se o usuário navega até um pasta sincronizada usando o Windows Explorer.
-   Corrigi um problema onde o OneDrive for Business não estiver desabilitada, mesmo que a chave do registro apropriada seja definida para desativar, quando o Office é configurado para receber atualizações de um local diferente de rede de entrega conteúdo do Office (CDN).

### <a name="onenote-feature-updates"></a>OneNote: Atualizações de recurso
-   **Controlar a sincronização de arquivo e imagem:** Vá para arquivo \> opções \> sincronizar com o controle se todos os arquivos e as imagens são baixadas automaticamente para todas as páginas em blocos de anotações.

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações de não segurança
-   Corrigi um problema onde o OneNote cai ao imprimir uma imagem maior que a página.
-   Corrigi um problema onde um usuário não pode excluir um modelo de página personalizado.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recurso
-   **Colaborar em anexos em tempo real:** Carrega anexos ao OneDrive for Business permitir que as pessoas a trabalhar na versão mais recente. Use o menu suspenso no anexo para carregar ou salvá-lo.
-   **Reservas e pacotes de viagens de cartões de resumo para:** Verifique e acompanhar reservas de viagens, bem como as entregas do pacote, usando cartões de resumo criados automaticamente na caixa de entrada e calendário. [Obter mais informações](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Editor:** Fornece avançadas, contextual revisores de texto para ajudar a melhorar a escrita de um. [Obter mais informações](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações de não segurança
-   Corrigi um problema no qual, quando o botão direito do mouse em um anexo na lista de anexos para uma conversa, todos os itens de menu de contexto são visíveis, em vez de apenas os itens de menu aplicável.
-   Corrigi um problema onde as mensagens de email de formato Rich Text (RTF) não podem ser abertas pelo destinatário se a mensagem foi enviada usando o gerenciamento de direitos de informação.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recurso
-   **Fechado legendas:** Se um slide contém um vídeo que fechou legendas, as legendas podem ser reproduzidas na apresentação de slides.
-   **Várias faixas de áudio:** Se um slide contém um vídeo que tem várias faixas de áudio, as trilhas podem ser reproduzidas na apresentação de slides.
-   **Seção copiando:** Copie e cole seções entre apresentações.
-   **Compartilhou comigo:** Ver os documentos que outras pessoas compartilharam com você indo para o arquivo \> Open \> compartilhadas com me. [Obter mais informações](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Repetição de tinta:** Repetição manuscrito frente e para trás para ocultar e revelar conteúdo, fornecem instruções passo a passo ou compreender melhor o fluxo de pensamentos dos outros. [Obter mais informações](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Melhores gravações:** Criar uma apresentação constituída de slides gravados, gravações de tela e o vídeo inserido e compartilhar conteúdo gravado sejam exibidas remotamente. Você também pode incorporar testes para ajudá-lo com o aprendizado remoto e tornar sua apresentação mais interativas, bem como alterar a cor de tinta e usar controles mais simples para registrar narrações e áudio.
-   **Aprimoramentos de designer:** Fornece sugestões de design usando SmartArt para listas com marcadores do processo.
-   **Guia faixa de opções de gravação:** Adicione uma guia gravação Personalizando a faixa de opções.
-   **Alterar as cores:** Use conte-Me para definir a cor de fonte, realce, preenchimento da forma e muito mais. [Obter mais informações](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Zoom:** Cria um resumo interativo da sua apresentação com links de navegação automática. [Obter mais informações](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Abrindo hiperlinks:** Use CTRL + clique para abrir hiperlinks durante a edição de uma apresentação.
-   **Texto realce:** Chame a atenção para texto importante usando o marca-texto do texto.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema em que, quando o corte de uma imagem, a parte cortada da imagem aparece escura.
-   Corrigi um problema onde, quando no modo de apresentação de slides e o Narrator está em execução, quando o usuário clica em um hiperlink e o site de falhas do PowerPoint é lentas para carregar.
-   Corrigi um problema onde a digitação em tempo real, quando coauthoring não funciona com tabelas.
-   Para corrigir um problema onde, ao abrir o PowerPoint em um computador que tem 3.0 Malwarebytes instalado, um erro de "Trabalho parado" aparece ou falha do PowerPoint.
-   Para corrigir um problema onde o modelo padrão não aparece em arquivo \> New.
-   Corrigi um problema onde o digitando o texto é interrompida e atrasada quando um arquivo que tem fontes incorporadas é gravado automaticamente.
-   Corrigi um problema com copiar imagens gráficas de (SVG) vetoriais escaláveis do Adobe Illustrator.

### <a name="project-feature-updates"></a>Projeto: Atualizações de recurso
-   **Campo Locked:** Defina o valor como Sim para impedir que os membros da equipe enviando atualizações em uma tarefa.
-   **Rótulos de linha do tempo:** Diferencie o cronograma de barras usando rótulos para fornecer-lhes nomes descritivos.
-   **Indicadores de progresso da linha do tempo:** Use marcas de seleção e colorido barras de progresso no modo de exibição linha do tempo para mostrar o quanto você estiver com cada tarefa.
-   **Aprimoramentos de acessibilidade:** Suporte aprimorado para usar o teclado, Narrator e outras tecnologias de assistência para ler e editar projetos.

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança
-   Corrigi um problema onde nenhuma linha de link é exibida ao criar um link entre projetos entre um projeto mestre e um subprojeto.
-   Para corrigir um problema onde valores de linha de base divididos em fases não são sempre salvos corretamente para o formato XML, especialmente trabalhar e valores que incluem durações parciais de custos.
-   Corrigi um problema onde, na aplicação de atualizações de status, trabalho real é adicionado à atribuição de um membro da equipe não relatar.
-   Corrigi um problema de onde os valores de linha de base são exibidos para um recurso, mesmo quando uma linha de base ainda não foi criada para o recurso.
-   Corrigi um problema onde visualização de impressão recorta o texto para que o texto não é visível.
-   Corrigir um problema em que, ao abrir um arquivo. mpp do SharePoint usando uma URL de atalho, o arquivo será aberto como check-out, embora a configuração "exigem documentos para fazer check-out para que eles possam ser editados?" está habilitado.
-   Corrigi um problema onde as atualizações do Project Web Apps a recursos materiais incorretamente altera dados divididos em fases.
-   Corrigi um problema onde abrindo um projeto que tenha uma tarefa de etapa pode adicionar uma data de início real a ela, embora ele não tinha uma data no momento quando ele foi salvo pela última vez.
-   Corrigi um problema com renumeração de estrutura (EDT) de divisão de trabalho.
-   Corrigi um problema onde quando você alterna fora de um modo de exibição baseados em grade de travamento Project e o Narrator é no.
-   Corrigi um problema em que uma mensagem de erro incorreta é mostrada sobre truncamento de dados divididos em fases ao abrir um arquivo XML.
-   Corrigi um problema onde a salvar uma linha de base não definidas corretamente valores divididos em fases.
-   Corrigi um problema onde o atraso da atribuição é ignorado quando a dados do projeto é lido a partir de um arquivo XML.
-   Corrigi um problema em que, ao abrir um arquivo do Project Online, mostra a data modificada último a hora de UTC em vez de no fuso horário ajustados tempo.
-   Corrigi um problema onde as faixas de cores de agrupamento não aparecem para as linhas não-agrupamento ao imprimir um modo de exibição de planilha.
-   Corrigi um problema onde uma opção de reparar incorretamente é mostrada quando o usuário inspeciona uma tarefa que tem uma atribuição além do problema de unidade máx.
-   Corrigi um problema em que o valor de um campo de código de estrutura não pode ser alterado depois que o projeto é publicado.
-   Corrigi um problema onde barras de Gantt não são dimensionadas corretamente em telas DPI altas em exibição de 175%.
-   Corrigi um problema onde se o usuário define o tempo de retardo através da caixa de diálogo informações sobre a tarefa, ela será incorretamente definida como uma duração decorrida.
-   Corrigi um problema onde quando abrir certos arquivos XML, a data de início da tarefa não está definido corretamente devido a um problema com a atribuição.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: recursos de atualizações
-   **Estilo de notificação do Windows:** Alterações na aparência de notificações de chamadas de entrada e conversas. [Obter mais informações](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Transferência com consultoria:** De dentro de uma chamada, consulte com outro usuário por meio de uma mensagem Instantânea ou chamada antes de transferir a chamada para o usuário. [Obter mais informações](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notificações de microfone:** Mostra uma notificação na janela de conversa, quando o microfone está sem som no sistema operacional ou se o microfone não está pegando qualquer áudio.
-   **Desabilitar "Meu número":** Use a entrada de registro DisableDisplayMyNumber para desabilitar "Meu número" sob o teclado de discagem.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Altere os botões de lobby usados para admitir ou recusar participantes do texto com imagens (um X ou uma marca de seleção).
-   Alterar a reunião texto de notificação de lembrete de "Aceitar" para "Join".
-   Atualize a mensagem mostrada ao remetente de uma mensagem Instantânea, quando o status do destinatário é definido como Não incomodar.
-   A mensagem mostrada ao remetente de uma mensagem Instantânea, quando o destinatário está offline e "Salvar histórico" estiver desabilitado, para deixar claro que o destinatário não receber a mensagem de atualização.
-   Adicione a capacidade de mover a barra de divisão vertical entre o histórico de chat e a lista de participação em um bate-papo de grupo.
-   Adicione o recurso para redimensionar a lista de guias nas janelas de mensagens Instantâneas ou sala de chat.
-   Adicione a capacidade de selecionar as salas de bate-papo pesquisadas quando estiver criando um tópico feed.
-   Corrigi um problema no qual a mensagem parar apareçam na conversa intermediário de histórico de chat.
-   Corrigi um problema onde as mensagens duplicadas aparecem na janela de conversa.
-   Corrigi um problema onde o ações de notificação de proposta (aceitar e ignorar) não são exibidas corretamente durante um alto volume de notificações.
-   Corrigi um problema em que o usuário não é possível digitar uma mensagem após usar o Alt + Tab para abrir uma janela de conversa minimizada.
-   Corrigi um problema onde no botão IM estiver esmaecido no cartão de visita para um usuário, apesar de mensagens Instantâneas está disponível.
-   Corrigi um problema onde várias janelas de conversa não abrem voltar ao seus tamanhos anteriores e locais após ser fechado e reaberto.
-   Corrigi um problema de onde os links personalizados não início quando selecionado.
-   Corrigi um problema onde o texto de reunião online no campo região não será exibido corretamente para caracteres do inglês.
-   Corrigi um problema no qual as informações de notificação, como duração da chamada, não são renderizadas corretamente em idiomas da direita para a esquerda.
-   Corrigi um problema em que, ao criar um tópico feed, desmarcar os resultados da pesquisa não redefine os resultados para uma lista de salas visitadas.
-   Corrigi um problema onde Skype para negócios trava quando várias janelas de conversa abertas ao mesmo tempo.
-   Corrigi um problema em que a última janela de conversa fica em branco e depois que todas as outras guias estão fechadas.
-   Corrigi um problema onde o foco padrão não estiver na área de entrada de bate-papo quando conversas com guias estão desabilitadas.
-   Para corrigir um problema onde "Link Esqueceu seu PIN de discagem?" link não é exibido no convite da reunião.
-   Corrigi um problema, onde parte do texto é cortado e truncado nas páginas do dispositivo geral e áudio com quando usar DPI alta telas a exibição de 175% ou mais.
-   Corrigi um problema onde Skype para negócios cai quando o computador é suspenso ou retomado quando não há nenhuma rede e o computador é um computador "sempre ativada sempre conectado (AOAC").
-   Corrigi um problema em que nenhum microfone for detectado em uma chamada ao usar um dispositivo Polycom CX100.
-   Para corrigir um problema onde escolhendo um link como \\ \\servername ou file:// em uma mensagem IM resulta em uma mensagem de erro, em vez de abrir o local.
-   Corrigi um problema, em um ambiente Virtual Desktop Infrastructure (VDI) que usa o local de roteamento, onde o usuário não possa fazer ou receber chamadas PSTN, pois o servidor pensa que o local do usuário não é válido para chamadas PSTN.
-   Alterar a linha de assunto de email enviado para uma mensagem perdida, quando o status do usuário estiver definido como Não incomodar ou apresentando, de "perdidas conversa com \<nome\>"para"\<nome\> enviaram uma mensagem no Skype for Business."
-   Inicia a captura o carimbo de hora para a entrar pela primeira vez no dispositivo como parte dos [dados census](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) para ajudar a identificar tendências de confiabilidade de entrada.
-   Corrigi um problema onde a opção para compartilhar um monitor secundário não aparece com determinadas configurações de monitor na janela 10 versão 1607 (também conhecida como a atualização de aniversário).
-   Corrigi um problema onde Skype para falhas de negócios quando o zoom no compartilhados conteúdo quando o participante do compartilhamento estiver usando um 3rd partes implementação de RDP.
-   Corrigi um problema onde o painel de controles de áudio não aparece quando um usuário clica no botão controles em uma chamada de áudio em um ambiente Virtual Desktop Infrastructure (VDI).
-   Corrigi um problema onde visualizadores ver uma tela preta quando um usuário está executando o Windows 7 e compartilha o monitor principal primeiro e, em seguida, alterna para compartilhar um segundo monitor.
-   Para corrigir um problema onde determinada especial caracteres, como o e comercial (&), não podem ser inserido na caixa de entrada de pesquisa ou o "que está acontecendo hoje?" caixa de seção.
-   Corrigir um problema onde a contagem não lida não é exibida quando há perdidas IMs offline.
-   Corrigi um problema de onde os modelos "Convidar por email" mencionado Lync em vez do Skype.
-   Corrigi um problema em que o número de linha está ausente da área de "Meu número" abaixo do teclado de discagem.
-   Corrigi um problema em que o ponteiro do mouse não é mostrado na área de entrada de mensagem Instantânea após enviar uma mensagem em um bate-papo.
-   Corrigir um problema onde Skype para negócios trava ao entrar e não há um problema ao carregar o pool de cache.
-   Corrigi um problema onde Skype para negócios cai quando entrando e restaurando conversas.
-   Corrigi um problema onde Skype para negócios trava ao entrar após reiniciar.
-   Corrigi um problema onde o link da reunião é desabilitado se os servidores do Exchange em ambas as organizações têm TNEF desabilitada.
-   Corrigi um problema em que uma chamada de vídeo não pode ser reiniciada se houver apenas uma conversa de mensagem Instantânea em andamento.
-   Corrigi um problema onde as anotações de texto em um quadro de comunicações são perdidas ao salvar o quadro de comunicações, como um arquivo PNG.
-   Corrigi um problema em que a primeira linha fica oculto Fernando em duas linhas em japonês na janela de mensagens Instantâneas.
-   Para corrigir um problema onde o caractere de e comercial (&) incorretamente é substituído por um caractere de sublinhado em nomes.
-   Corrigi um problema com a URL "Ingressar na reunião online" em uma reunião agendada.
-   Corrigi um problema onde posicionar o mouse sobre uma janela não ative a janela, mesmo que o sistema operacional está configurado para isso.
-   Corrigi um problema onde a itens do histórico de conversa de chamada de saída mostra o chamador, em vez da parte chamada.
-   Corrigi um problema onde o F12 localmente não salvar uma conversa.
-   Corrigi um problema onde um email de conversas perdidas não contém o IM inicial.
-   Corrigi um problema onde um emoji pode ser adicionada na área de texto de mensagens Instantâneas, mesmo se o apresentador tiver desabilitado a participação de mensagens Instantâneas.
-   Corrigi um problema com o layout da caixa de diálogo de opção toques e sons.
-   Corrigi um problema onde Skype para negócios cai ao fechar uma janela de conversa.
-   Corrigi um problema onde o DNS sem entrar falha quando o domínio está registrado como um domínio vanity.
-   Para corrigir um problema onde as configurações de notificação de chat persistente não estão sendo salvos ou carregados corretamente.
-   Corrigi um problema onde janelas de conversa ponto a ponto existentes ou salas de bate-papo não estão aparecendo depois de entrar, embora a configuração para reabrir conversas estiver definida.
-   Para corrigir um problema onde ativando mudo ou mudo a conversa ativa faz com que outras janelas de conversa apareça como se eles têm as mensagens não lidas.
-   Corrigi um problema de onde os usuários que estão configurados para bypass de mídia estão não é possível continuar uma chamada de um gateway PSTN depois que eles colocam a chamada em espera.
-   Corrigi um problema em que o usuário vê uma caixa azul em vez de vídeo ao ingressar em uma reunião por meio de uma URL quando usando um 3rd terceiros a implementação de RDP.
-   Corrigi um problema em que a parte de endereço SIP do usuário está mostrando em vez do nome de exibição no alerta proposta.
-   Para corrigir um problema onde, quando Skype para negócios se conecta a um servidor SIP na porta 443 e um servidor proxy estiver presente, há um atraso significativo no processo de entrada se o proxy não permitir dessas conexões. A correção será permitida, adicionando a entrada de registro EnableDetectProxyForAllConnections DWORD em HKEY\_atual\_usuário\\Software\\Microsoft\\UCCPlatform\\Lync e definindo o valor como 1.
-   Corrigi um problema em que, ao usar as conversas com guias, clicar duas vezes em uma guia e iniciando digitar às vezes podem causar o foco se mover para uma guia diferente e continuar a digitando naquela janela de conversa.
-   Corrigi um problema onde URLs incluídas em uma mensagem instantânea não podem ser selecionados na janela de histórico de chat usando o teclado.
-   Corrigi um problema em que um som de digitação deve ser ouvido se a caixa de seleção "Tocar um som quando exibindo uma conversa de mensagem Instantânea e uma pessoa está digitando" está selecionada em Opções de toques e sons.
-   Corrigi um problema onde as caixas de diálogo que aparecer não são anunciadas ao usar um leitor de tela, como o Narrator.
-   Corrigi um problema onde o primeiro tutorial execução não puder ser navegado com um teclado e não pode ser lido por um leitor de tela, como o Narrator.
-   Corrigi um problema no qual o ícone de presença da barra de tarefas não pode ser dimensionado nas configurações de DPI alta.
-   Corrigi um problema em que o botão de campo significativo na caixa de pesquisa não pode ser selecionado usando o teclado.
-   Corrigi um problema em que um usuário não é possível iniciar uma reunião se o convite for de um usuário em outro pool.
-   Corrigi um problema em que um usuário adicionando-se a uma reunião incorretamente é mostrado como um usuário diferente.
-   Corrigi um problema onde o ícone de presença de contato na notificação de alteração de status foi oculto para chamadas de entrada para o chefe.
-   Corrigi um problema onde a taxa de intermitência do cursor de texto na janela de mensagens Instantâneas não coincidem com as propriedades de teclado configurando no Windows.
-   Corrigi um problema onde um leitor de tela comunica um nome incorreto de contato para uma conversa de grupo.
-   Corrigi um problema em que o usuário não pode selecionar vários contatos usando o teclado.
-   Corrigi um problema onde as fotos dos usuários não podem ser recuperadas do Exchange.
-   Corrigi um problema onde o Skype para o cliente de negócios se conecta a um Skype para Business Server na rede interna, em vez de um em rede externa, quando o usuário se conecta usando acesso direto.
-   Corrigi um problema onde Skype para o cliente de negócios cai ao tentar resolver o nome do proprietário reunião.
-   Corrigi um problema onde a alteração de um Windows configuração enquanto Skype para negócios está sendo iniciado ou desligado faz com que Skype para negócios falhe.
-   Corrigi um problema onde Skype para negócios cai quando abrir a lista de participantes em uma sala de chat persistente e tentar mover o teclado foco para a lista de participantes.
-   Corrigi um problema onde Skype para negócios de travamento no resume quando nenhuma rede estiver disponível.

### <a name="visio-feature-updates"></a>Visio: Atualizações de recurso
-   **Modelagem de banco de dados suplemento:** Use o suplemento para criar um modelo de banco de dados de um banco de dados existente para ajudar a planejar um novo banco de dados ou entender um existente. [Obter mais informações](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [Baixe o suplemento](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Aprimoramentos de acessibilidade:** Suporte aprimorado para usar o teclado, Narrator e outras tecnologias de assistência para trabalhar com formas, edite com outras pessoas e muito mais.
-   **Modelos de terceiros e diagramas:** Navegar ou procurar por novos modelos e diagramas de exemplo disponíveis a partir de select provedores de conteúdo de terceiros. Nome do provedor de terceiros está listado na miniatura.
-   **Suporte de escrita à tinta:** Use caneta ou dedo para desenhar e anotar com as ferramentas na nova guia Draw.

### <a name="word-feature-updates"></a>Word: Atualizações de recurso
-   **Aprimoramentos de acessibilidade:** Suporte aprimorado para usar o teclado, Narrator e outras tecnologias de assistência para ler e editar documentos. [Obter mais informações](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Editor:** Fornece avançadas, contextual revisores de texto para ajudar a melhorar a escrita de um. [Obter mais informações](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Repetição de tinta:** Vá para desenhar \> tinta repetição durante a repetição manuscrito frente e para trás para ocultar e revelar conteúdo, fornecem instruções passo a passo ou compreender melhor o fluxo de pensamentos dos outros. [Obter mais informações](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Editar com gestos de caneta natural:** Fazer alterações em um documento, destacando para selecionar e Cruzando check-out para excluir. [Obter mais informações](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Compartilhou comigo:** Ver os documentos que outras pessoas compartilharam com você indo para o arquivo \> Open \> compartilhadas com me. [Obter mais informações](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Alterar as cores:** Use conte-Me para definir a cor de fonte, realce, preenchimento da forma e muito mais. [Obter mais informações](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema onde visualizar um documento no modo de leitura impede que a tecla TAB trabalhando em um segundo documento que está sendo exibido no Layout de impressão.
-   Corrigi um problema em que o Word trava quando mais de uma biblioteca de gramática é carregada.
-   Corrigi um problema onde pressionamentos coloridos desaparecem após dois ou três traços.
-   Corrigi um problema com aspas desaparecimento ao usar o Editor de método de entrada (IME) do Google.
-   Corrigi um problema em que um usuário não é possível usar a escrita à tinta com controles de conteúdo, ou quando não contíguas seleções são feitas.

### <a name="office-suite-feature-updates"></a>Pacote do Office: atualizações de recursos
-   **Comente:** Sugerir novos recursos ou informe à Microsoft o que você gosta ou que não está funcionando indo para o arquivo \> comentários

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   Boletim de segurança da Microsoft [MS16 148](https://technet.microsoft.com/library/security/ms16-148): atualização de segurança para o Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigi um problema quando usar CTRL + ALT + 7 ou CTRL + ALT + 8 em um teclado alemão abre a ferramenta de comentários do usuário, em vez de inserir o caractere apropriado.
-   Corrigi um problema onde TraceLogging causa uma falha no Windows 7 quando a instalação ou atualização do Office.
-   Corrigi um problema em que, quando desenho com tinta e usando um mouse, soltar o botão do mouse faz com que a tinta deslocar ligeiramente.
-   Corrigi um problema onde, depois de inserir uma imagem SVG em um documento do Office, a imagem SVG desaparece quando o documento é salvo e aberto novamente.
-   Para corrigir um problema onde o Office mostra a seguinte mensagem de erro durante a ativação para os usuários não estão em inglês: "o comprimento máximo da chave do produto é de 25 caracteres."
-   Corrigi um problema com os formulários VBA que podem causar a ordem z dos quadros para parar de funcionar ou exibidos incorretamente.
-   Corrigi um problema onde uma atualização trigged pelo System Center Configuration Manager altera a configuração de UpdateChannel no registro para algo que não é um canal de atualização válido.



## <a name="version-1609-january-10"></a>Versão 1609: 10 de janeiro
*Versão 1609 (compilação 7369.2102)*

Observação: As atualizações de segurança abordadas no boletim de segurança da Microsoft [MS17-002](https://technet.microsoft.com/library/security/ms17-002) não se aplicam à versão do Word nesta versão de canal.

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança
-   Corrigi um problema onde usando uma caixa de diálogo Editar medida faz com que o Excel falha.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
-   Corrigi um problema onde como trabalhar com formas às vezes, faz com que o PowerPoint falha.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Corrigi um problema onde a opção para compartilhar um monitor secundário não aparece com determinadas configurações de monitor na janela 10 versão 1607 (também conhecida como a atualização de aniversário).
-   Corrigi um problema onde Skype para falhas de negócios quando o zoom no compartilhados conteúdo quando o participante do compartilhamento estiver usando um 3rd partes implementação de RDP.
-   Para corrigir um problema onde, quando Skype para negócios se conecta a um servidor SIP na porta 443 e um servidor proxy estiver presente, há um atraso significativo no processo de entrada se o proxy não permitir dessas conexões. A correção será permitida, adicionando a entrada de registro EnableDetectProxyForAllConnections DWORD em HKEY\_atual\_usuário\\Software\\Microsoft\\UCCPlatform\\Lync e definindo o valor como 1.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
-   Corrigi um problema em que, ao usar o método InsertXML, um espaço reservado para um link desfeito imagem é mostrado em vez da imagem real.


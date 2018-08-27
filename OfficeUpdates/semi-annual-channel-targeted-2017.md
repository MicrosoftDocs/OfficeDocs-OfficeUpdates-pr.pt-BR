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
ms.sourcegitcommit: b230282c9b72374d46b6b262b450f6618b2205cc
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/27/2018
ms.locfileid: "19555862"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Notas de versão para as versões de canal delimitadas anual (multidifusão) no 2017

Essas notas de versão fornecem informações sobre novos recursos, atualizações de segurança e atualizações não relacionadas à segurança são incluídas nas atualizações de canal delimitadas anual (multidifusão) para o Office 365 ProPlus em 2017.
 
> [!NOTE]
> - A seguir, fornecemos informações sobre recursos, atualizações de segurança e outras atualizações não relacionadas à segurança para Visio Pro para Office 365 e Project Online Desktop Client.
> - Essas informações também se aplicam ao Office 365 Business, versão do Office que acompanha alguns planos do Office 365, como o Business Premium.
> - Canal delimitadas anual (multidifusão) foi denominado primeiro lançamento para canal adiada antes de setembro de 2017.

## <a name="version-1708-december-12"></a>Versão 1708: 12 de dezembro
*Versão 1708 (build 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema em que é exibida incorretamente ao usuário a mensagem de erro "Falha catastrófica" ao abrir uma pasta de trabalho com macros no Office 2007 ou versão anterior (.xls ou .xla).
-   Correção de um problema em que abrir uma pasta de trabalho na linha de comando pode causar perda de formatação em rich text na célula.

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilidade de divulgação não autorizada de informações do Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema em que os dados do campo personalizado de nível de projeto podem ser perdidos ao salvar.
-   Correção de um problema em que uma falha no salvamento pode corromper um arquivo e fazer o Project falhar ao abrir.
-   Correção de um problema em que abrir um plano de projeto pode causar uma falha.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office



## <a name="version-1708-november-14"></a>Versão 1708: 14 de novembro
*Versão 1708 (build 8431.2110)*

### <a name="access-non-security-updates"></a>Access: atualizações não relacionadas à segurança
-   Correção de um problema em que tentar selecionar o texto em uma caixa de texto ou caixa de combinação parecia selecionar todo o texto, em vez da seleção de indicação.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): vulnerabilidade de bypass do recurso de segurança do Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilidade de corrupção de memória do Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema em que o usuário não conseguia fechar uma pasta de trabalho no modo de exibição protegido quando o nome do arquivo continha colchetes.
-   Correção de um problema em que, quando o usuário tenta inserir um objeto em uma pasta de trabalho existente, o Excel falha quando o usuário clica em Navegar.
-   Correção de um problema em que selecionar "Redimensionar a forma para corrigir o texto" (na parte da Opções de Texto/Caixa de Texto do painel Formatar Forma) não resulta em uma mudança na forma.
-   Correção de um problema em que, ao abrir uma pasta de trabalho clicando duas vezes nela, as fontes e formatos das células de texto não são carregados ou duas pastas de trabalho idênticas são abertas para um único modelo.
-   Correção de um problema em que a primeira pasta de trabalho criada ao iniciar o Excel não fecha quando uma nova pasta de trabalho é aberta ou criada.
-   Corrigido um problema em que o posicionamento da dica de ferramenta é desalinhado ao arrastar ou preencher arrastando.
-   Corrigido um problema em que, ao salvar uma pasta de trabalho usando Arquivo \> Salvar Como, um nome de arquivo que contém pontos aparece em branco ou truncado na caixa de diálogo Salvar arquivo.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Correção um problema com a renderização onde linhas e cabeçalhos pretos aparecem devido a falhas no driver de gráfico.
-   Correção de um problema em que o Excel falha ou não consegue salvar a pasta de trabalho após a inserção de um gráfico.
-   Correção de um problema em que a linha de quebra de página na visualização de quebra de página está posicionada incorretamente.

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que o usuário vê o foco na lista de mensagens saltar inesperadamente ao excluir as mensagens.
-   Correção de um problema que faz com que o usuário veja solicitações de autenticação durante a interação com anexos.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Correção de um problema em que editar e formatar o texto após desfazer algo em uma tabela faz o PowerPoint falhar.
-   Correção de um problema em que as referências a códigos de inserção do YouTube com base no Flash Player resultam na abertura de uma nova janela para reproduzir o vídeo. Antigos códigos de inserção agora foram atualizados para fazer referência a vídeos do YouTube com base em HTML5 para que possam ser reproduzidos corretamente no lugar.

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [Supervisão 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): atualização de proteção abrangente do Microsoft Office

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Corrigido um problema em que o Word falha quando um usuário tenta Salvar Como para um documento existente no OneDrive for Business e cancela o salvamento ou tenta mesclar alterações existentes.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Correção de um problema em que o Word pode desligar se o usuário navegar para a guia Inserir logo após abrir o Word.
-   Correção de um problema em que, depois de clicar na margem, os caracteres são exibidos no canto superior esquerdo da tela ao inserir caracteres.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema com o zoom e dimensionamento em suplementos do Office em um ambiente de DPI dinâmico.
-   Correção de um problema em que o nó CurrentStatus do provedor de serviços de configuração (CSP) do Office retorna uma cadeia de caracteres vazia mesmo se o Office 365 ProPlus estiver instalado atualmente.
-   Correção de um problema que causa mudanças de formato no arquivo .box, o que afeta a funcionalidade de versões mais antigas do Office instaladas no mesmo computador, porque os arquivos .box são compartilhados entre todas as versões de um aplicativo do Office no mesmo computador.
-   Correção de um problema em que, em determinadas circunstâncias ao usar a ativação de computador compartilhado, uma mensagem de erro é exibida informando que o aplicativo encontrou um erro que o está impedindo de funcionar corretamente e perguntando se o usuário deseja executar um reparo.



## <a name="version-1708-october-10"></a>Versão 1708: 10 de outubro
*Versão 1708 (build 8431.2107)*

### <a name="access-non-security-updates"></a>Access: atualizações não relacionadas à segurança
-   Correção de um problema em que uma consulta não era executada se ela tivesse uma junção com uma chave primária de uma tabela vinculada do Microsoft Dynamics.
-   Correção de um problema em que as casas decimais não eram mostradas para valores monetários em uma tabela do Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema em que o Excel falha ao abrir um arquivo .XLL.
-   Correção de um problema em que o estilo de padrão de uma célula não renderiza corretamente depois de adicionar um cabeçalho ou rodapé no modo de exibição Layout de Página.
-   Correção de um problema em que colar uma cópia de uma Tabela Dinâmica em outra pasta de trabalho pode resultar em uma falha.
-   Correção de um problema em que, quando você seleciona o comando Substituir e a caixa de diálogo Localizar e Substituir se abre, o foco da caixa de diálogo fica na guia Localizar em vez de na guia Substituir.
-   Correção de um problema em que o Excel falha ao abrir o painel Atividade de uma pasta de trabalho aberta em um servidor do SharePoint mais antigo do que o SharePoint Server 2016.
-   Correção de um problema em que o Excel abre e exibe uma janela em branco quando um ou mais suplementos XLL são habilitados.
-   Correção de um problema em que o Excel falha depois de usar o botão Formulários em uma pasta de trabalho já fechada.
-   Correção de um problema em que, ao usar o evento SheetBeforeRightClick, inserir uma coluna que cruza células mescladas não expande as células mescladas.

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): vulnerabilidade de divulgação de informações do Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações que não são de segurança
-   Correção de um problema em que o link "Saiba mais" nas Dicas de Políticas não fica visível ao usar o tema Cinza Escuro.
-   Correção de um problema em que o Outlook falha quando o usuário está tentando configurar uma nova conta e fecha a janela sem concluir a configuração da conta.
-   Correção de um problema em que Marcar como Lido e Marcar como Não Lido são exibidos como opções para mensagens na caixa de entrada compartilhada de um grupo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema em que o PowerPoint falha ao abrir uma apresentação de um servidor do SharePoint mais antigo do que o SharePoint Server 2016.

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema em que o Word falha ao abrir o painel Atividade de um documento aberto em um servidor do SharePoint mais antigo do que o SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Vulnerabilidade de execução remota de código do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema em que o progresso de Reparo Online não é exibido ao usuário.
-   Correção de um problema em que as propriedades de arquivo do Office não são exibidas no Explorador de Arquivos.
-   Correção de um problema em que os botões de suplemento do Office desaparecem da faixa de opções quando há um segundo documento aberto.
-   Correção de um problema em que alguns módulos de VBA com nomes com caracteres de dois bytes não podem ser abertos.



## <a name="version-1708-september-12"></a>Versão 1708: 12 de setembro
*Versão 1708 (build 8431.2079)*

### <a name="access-feature-updates"></a>Access: atualizações de recursos
-   **Propriedade Label Name:** melhora a acessibilidade associando um rótulo a um controle ou formulário.
-   **A edição de itens novos ficou mais acessível:** use um atalho de teclado (Ctrl+E) rápido para editar um novo item em uma caixa de combinação ou em uma caixa de listagem.
-   **Dynamics Connector:** importar dados ou vincular a dados armazenados no Microsoft Dynamics. [Saiba mais](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Conector do Salesforce:** importar dados ou vincular a dados armazenados na Salesforce. [Saiba mais](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
-   **Melhorias do recurso "Adicionar Coluna de Exemplos":** com suporte para mais transformações de Data/Hora, Matemática e coluna de índice.
-   **Melhorias de desempenho:** O Excel abre pastas de trabalho complexas com várias planilhas mais rápido, para que você possa processar fórmulas com intervalos grandes, filtrar muitas linhas, ou copiar e colar mais rápido.
-   **Inserir imagens online:** a nova página de chegada para seleção de imagens e informações de atribuição são inseridas automaticamente com a imagem.
-   **Conector do Azure Data Lake Store:** os usuários já podem importar dados do Azure Data Lake Store.
-   **Melhorias "Adicionar coluna de Exemplos":** com suporte para sugestões, mais operações de Data/Hora e outras transformações.
-   **Guia Dados**: os botões da faixa de opções na guia Dados foram reorganizados em dois novos grupos: Obter e Transformar Dados e Consultas e Conexões.
-   **Compartilhar consultas**: exporte qualquer definição de consulta em um arquivo ODC (Conexão do banco de dados do Office) e compartilhe-o entre pastas de trabalho ou com outras pessoas.
-   **Carregar dados:** Carregue dados de uma consulta diretamente em tabelas dinâmicas ou gráficos dinâmicos sem precisar salvar os dados no modelo de dados.
-   **Atividade de arquivo compartilhado:** Escolha o botão Atividade, no canto superior direito do arquivo, para ver quando ele foi compartilhado, editado, renomeado ou restaurado no OneDrive for Business ou no SharePoint.
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Funcionalidade de importação de dados melhorada:** Importe facilmente e molde dados de várias fontes. Gerencie conexões e consultas de pastas de trabalho com o painel lateral Consultas e Conexões, e compartilhe as consultas com outras pessoas por meio dos arquivos ODC. [Mais informações](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Alterações em arquivos compartilhados**: veja quem fez alterações em pastas de trabalho compartilhadas e restaure versões anteriores. [Saiba mais](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Seleção de Laço com um botão de caneta:** use botões de caneta digital compatíveis para Seleção de Laço com tinta sem ter que acessar a Faixa de Opções.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema no qual o Excel trava temporariamente quando você expande ou recolhe uma Tabela Dinâmica, e os cabeçalhos dela se movem para fora da tela.
-   Correção de um problema em que as guias são ignoradas ao copiar e colar um texto delimitado por tabulação do Word, o que resulta na não análise do texto em colunas
-   Correção de um problema no qual o Excel trava ao abrir a caixa de diálogo Publicar como Página da Web.
-   Correção de um problema em que a atualização de dados não funciona ou o Excel falha durante o uso de dados de um servidor SQL Server Analysis Services, e as localidades do Excel e do servidor SQL Server Analysis Services são diferentes.
-   Correção de um problema em que o programa exibe erros ao tentar salvar alterações em documentos sincronizados com o cliente do OneDrive.
-   Correção de um problema em que não é possível fazer alterações na planilha quando há uma Tabela Dinâmica com campos na área do Filtro, mas nenhum campo em outros locais.

### <a name="outlook-feature-updates"></a>Outlook: atualizações de recursos
-   **Melhorias de acessibilidade:** facilitamos a leitura e a edição de textos, tabelas, listas e imagens no email durante o uso de um leitor de tela.
-   **Nova configuração de conta:** configure novas contas com um novo assistente que requer menos etapas manuais.
-   **Caixa de diálogo "Anexar" para links:** ao anexar um link usando o recurso "Anexar Arquivo" na Faixa de Opções, é possível escolher entre adicioná-lo como link ou como anexo. Caso prefira não exibir sempre esta caixa de diálogo, vá para Arquivo \> Opções \> Geral e especifique como deseja anexar os links em "Opções de Anexo".
-   **Suporte para anexos no local:** Os arquivos do SharePoint Server no local são exibidos como arquivos recentes em Mensagem \> Anexar Arquivo, os sites da equipe do OneDrive for Business e do SharePoint no local são exibidos em Anexar Arquivo \> Procurar Locais na Web e os arquivos locais podem ser carregados para os sites do OneDrive for Business no local.
-   **Setor de atividade para grupos:**  Um nível de setor de atividade definido pelo administrador do locatário, como Confidencial, pode ser atribuído ao criar ou ao editar um grupo e esse setor é exibido no cabeçalho do grupo.
-   **Acesso para convidado para Grupos do Office 365:** para colaborar com pessoas de fora da organização, conceda a elas acesso para conversas em grupo, arquivos, convites do calendário e Bloco de Anotações do Grupo. [Mais informações](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Mensagens acionáveis:** os desenvolvedores podem criar mensagens para tornar mais fácil para os usuários a realização de ações simples e rápidas no Outlook, sem ter que mudar para um site externo ou outro aplicativo. [Saiba mais](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidade de bypass do recurso de segurança do Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidade de corrupção de memória do Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações que não são de segurança
-   Correção de um problema em que não é possível configurar uma conta IMAP no Outlook.
-   Correção de um problema que causa falhas intermitentes ao abrir o Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: atualizações de recursos
-   **Inserir imagens online:** a nova página de chegada para seleção de imagens e informações de atribuição são inseridas automaticamente com a imagem.
-   **Legendas Codificadas:** adicione Legendas Codificadas a um vídeo para torná-lo mais acessível. [Saiba mais](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Narrar uma gravação:** Inclua vídeo de si mesmo narrando quando fizer uma gravação de uma apresentação. É possível incluir animações, link, áudio e vídeo nas gravações.
-   **Atividade de arquivo compartilhado:** Escolha o botão Atividade, no canto superior direito do arquivo, para ver quando ele foi compartilhado, editado, renomeado ou restaurado no OneDrive for Business ou no SharePoint.
-   **Criação de texto Alt:** um serviço baseado em nuvem gera automaticamente um texto alternativo para as imagens de uma apresentação.
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Melhorias do Designer:** recomenda ideias de design profissionais para listas orientadas para ações.
-   **Alterações em arquivos compartilhados:** veja quem fez alterações em apresentações compartilhadas e restaure versões anteriores. [Saiba mais](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): vulnerabilidade de execução remota de código do PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): vulnerabilidade de execução remota de código do PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema em que ocorre uma falha na exibição dos caracteres definidos pelo usuário final (EUDCs) que estão vinculados às fontes.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema no qual abrir determinados arquivos no Project Online faz com que o projeto falhe.
-   Correção de um problema em que o Início Real pode ser limpo por engano ao definir o trabalho restante.
-   Correção de um problema onde a Data de Início Real da Tarefa pode mostrar dados diferentes dos que foram relatados pelo recurso por meio de status no Project Web App.
-   Correção de um problema em que o trabalho real pode ser reprogramado se a data de término da tarefa for alterada.
-   Correção de um problema em que se você copiar e colar os campos de custo, os valores colados podem não corresponder exatamente aos valores copiados devido a um problema de arredondamento.
-   Correção de um problema em que os dados divididos ao longo do tempo para recursos de Orçamento não são copiados quando você salva de uma linha de base para outra.
-   Correção de um problema em que o campo de status nem sempre é calculado corretamente para tarefas de resumo.
-   Correção de um problema em que o trabalho real erroneamente é transferido para um recurso da empresa quando ela substitui um recurso local e o trabalho protegido está habilitado.
-   Correção de um problema em que o projeto trava se você tiver uma tabela cuja primeira coluna é o nome da tarefa, a coluna esteja bloqueada e você clicar em uma tarefa.
-   Correção de um problema em que você pode atribuir o mesmo recurso várias vezes à mesma tarefa por meio do modo de exibição de Uso da Tarefa.
-   Correção de um problema em que os valores contidos nos campos numéricos personalizados podem ser perdidos ao abrir arquivos XML.
-   Correção de um problema em que o recuo de tarefas de nível superior não sincroniza corretamente do Project para uma lista de tarefas do SharePoint.
-   Correção de um problema em que, se você importar tarefas, recursos ou informações sobre atribuição de uma pasta de trabalho no Excel, os valores no campo de trabalho podem ser ignorados.
-   Correção de um problema em que os valores de linha de base divididos em fases não correspondem aos valores iniciais ao salvar um projeto no formato de arquivo XML.
-   Correção de um problema em que o cliente do Project não abre um projeto por julgar que o respectivo check-out já foi feito, quando na verdade não foi.
-   Correção de um problema de modo que seja mais rápido abrir arquivos do Project em um servidor de arquivos com alta latência.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): vulnerabilidade de divulgação de informações confidenciais do Windows GDI+
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): vulnerabilidade de divulgação de informações de componente do Graphics
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): execução remota de código do componente do Microsoft Graphics

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Adição de uma caixa de diálogo explicando por que um usuário não consegue ingressar em uma reunião quando determinadas portas estão bloqueadas ou os IPs não estão na lista de permissões.
-   Correção de um problema em que as mensagens não lidas em salas de chat persistentes são marcadas como lidas ao clicar nas guias de conversas de mensagens instantâneas.
-   Correção de um problema em que as notificações do sistema de mensagens instantâneas são exibidas com atraso de vários segundos.
-   Correção de um problema em que o contato do AD é exibido como um número de telefone em vez de um nome de contato, quando a sincronização com o Exchange está desabilitada.
-   Correção de um problema em que usuários de ingresso anônimo são impedidos de ingressar quando a federação está desabilitada e o ingresso anônimo não foi bloqueado explicitamente pelo organizador da reunião.
-   Correção de um problema em que o número de convidados é exibido incorretamente para o organizador da reunião, no caso de reuniões que excedem o limite.
-   Correção de um problema em que o número de telefone não é exibido na notificação do sistema, em chamadas PSTN de entrada.
-   Correção de um problema em que, ao usar a tecla Delete para renomear um grupo da lista de contatos, o grupo inteiro é excluído.
-   Correção de um problema em que a notificação de compartilhamento na conversa de mensagem instantânea é ignorada antes da interrupção do compartilhamento.
-   Correção de um problema em que a tela de entrada fica em branco para alguns idiomas diferentes do inglês.
-   Correção de um problema em que os caracteres que não fazem parte da língua inglesa no chat e no histórico do chat apareciam ilegíveis.
-   Exibir o número de telefone do chamador em uma chamada de entrada manipulada pelo Atendedor Automático corporativo, se o nome do usuário for desconhecido.
-   Adição de uma configuração de inband liberando a restrição para "Qualquer pessoa (sem restrições)" como uma opção para "Essas pessoas não precisam aguardar no lobby".
-   Adição da capacidade de exibir ou ocultar a visualização do próprio vídeo para chamadas de vídeo P2P em VDIv2.
-   Correção de um problema em que os números dos contatos são exibidos em duplicado no menu suspenso Telefonar.
-   Correção de um problema em que representantes são removidos por usuários que alternam entre o Skype for Business e o Skype for Business Basic.
-   Correção de um problema em que o item Invisível não é exibido ao usar as políticas de cliente Habilitar Status para Invisível e URL de Estado Personalizado.
-   Ampliação do botão Ingressar na Reunião para corrigir o truncamento de alguns idiomas localizados.
-   Aumentar a importância das mensagens de Alta prioridade nos chats.
-   Adicionar tipos de extensão de arquivo do Office e do Skype for Business a listas de bloqueios de transferência de arquivos permitidos.
-   Correções de localização em convites para reunião do Outlook para Texto do Rodapé de reunião definido em idioma não inglês.
-   Correção de um problema em que é possível alterar os nomes dos remetentes em conversas de vários usuários.
-   Correção de um problema em que há uma falha na exibição da janela de conversa em branco, até que uma reunião seja incluída com êxito.
-   Correção de um problema em que as informações do campo Departamento de um Cartão de Visita aparecem em branco nos resultados de pesquisa, quando o campo Título está em branco.
-   Correção de falhas de entrada para usuários que migraram de ambientes locais para ambientes online devido a regras de firewall.
-   Adição de uma chave de registro DWORD para corrigir um problema em que, quando o usuário entra no cliente por meio de uma rede externa executando o serviço de Descoberta Automática do Lync, o cliente redefine a chave de registro OAuthUsed como falsa. Para corrigir o problema, defina o valor como 1 para EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket, em HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos
-   **Criar diagramas de dados do Excel:** Criar automaticamente um Fluxograma Básico ou um Fluxograma Multifuncional de dados do Excel usando novos modelos do Visualizador de Dados. [Mais informações](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: atualizações não relacionadas à segurança
-   Correção de um problema em que os suplementos de COM não recebem eventos de abertura do documento ao abrir um arquivo do Visio clicando duas vezes no respectivo ícone ou nome do arquivo.

### <a name="word-feature-updates"></a>Word: atualizações de recursos
-   **Inserir imagens online:** a nova página de chegada para seleção de imagens e informações de atribuição são inseridas automaticamente com a imagem.
-   **Criação de texto Alt:** um serviço baseado em nuvem gera automaticamente texto alternativo (texto alt) para imagens em um documento.
-   **Atividade de arquivo compartilhado:** Escolha o botão Atividade, no canto superior direito do arquivo, para ver quando ele foi compartilhado, editado, renomeado ou restaurado no OneDrive for Business ou no SharePoint.
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Alterações em arquivos compartilhados:** Veja quem fez alterações em documentos compartilhados e restaure versões anteriores. [Mais informações](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema em que o Word fecha inesperadamente ao carregar o suplemento Grammarly.
-   Correção de um problema em que, em determinadas condições, o Word falha ao tentar recuperar arquivos baseados na nuvem.
-   Correção de um problema em que não é possível girar formas dentro da tela de desenho.
-   Correção de um problema em que, ao digitar em coreano, as consoantes e vogais são separadas de forma incorreta.
-   Ao salvar um documento em PDF, ele é salvo na versão 1.7 do PDF.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema que impede que a caixa de diálogo Novidades seja exibida.
-   Correção de um problema em que o aplicativo falha para alguns usuários ao clicar na guia Desenhar.
-   Correção de um problema em que o aplicativo falha ao passar o cursor sobre um Controle Comum que contém uma dica de ferramenta.
-   Correção de um problema em que um Erro de Licenciamento é exibido ao usar Controles Comuns.
-   Correção de um problema relacionado à maneira pela qual alguns arquivos de programas são conectados fazendo com que programas antivírus sinalizem esses arquivos, além de problemas para proteger ou acessar dados no WIP (Proteção de Informações do Windows).
-   Adição de suporte para permitir que os usuários que trabalham em versões de 64 bits do Office abram arquivos de macro contendo controles mscomctl.ocx.
-   Melhoria de acessibilidade dos controles usados no mscomctl.ocx.
-   Correção de um problema em que os comandos estão ausentes das caixas de diálogo Personalizar Faixa de Opções ou Personalizar a Barra de Ferramentas de Acesso Rápido.



## <a name="version-1705-august-8"></a>Versão 1705: 8 de agosto
*Versão 1705 (build 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema ao arrastar a barra de rolagem para se movimentar por uma lista de mensagens.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema relacionado à maneira pela qual alguns arquivos de programas são conectados fazendo com que programas antivírus sinalizem esses arquivos, além de problemas para proteger ou acessar dados no WIP (Proteção de Informações do Windows).
-   Correção de um problema que impede que a caixa de diálogo Novidades seja exibida.



## <a name="version-1705-july-27"></a>Versão 1705: 27 de julho
*Versão 1705 (build 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que o programa exibe erros ao tentar salvar alterações em documentos sincronizados com o cliente do OneDrive.
-   Correção de um problema em que o Excel falha ao adicionar dados de uma planilha ao modelo de dados e o tema de alto contraste é definido como Preto.

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidade de bypass do recurso de segurança do Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidade de corrupção de memória do Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema em que ocorre uma falha de mesclagem ao adicionar uma forma, quando o usuário faz alterações no layout.

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema em que, ao digitar em coreano, as consoantes e vogais são separadas de forma incorreta.
-   Correção de um problema em que o endereço de entrega é impresso muito próximo à borda esquerda do envelope.



## <a name="version-1705-july-13"></a>Versão 1705: 13 de julho
*Versão 1705 (build 8201.2136)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Vulnerabilidade de corrupção de memória do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema em que o Excel trava em pastas de trabalho que contêm links externos.
-   Correção de um problema em que colar células do Excel no Word mostra zeros nas células, mesmo que a configuração "Mostrar um zero nas células cujo valor é zero" não esteja selecionada.

### <a name="project-non-security-updates"></a>Project: Atualizações que não são de segurança
-   Correção de um problema em que os valores que são selecionados para uma tabela/gráfico não estão visíveis no painel de tabela do gráfico.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Correção de um problema em que uma janela de conversa não aparece no plano de fundo ao ingressar em uma reunião e a caixa de diálogo de junção de dispositivos de áudio é mostrada para o usuário.
-   Correção de um problema em que o link da reunião do Outlook não passa sempre a URI interna corretamente.
-   Ampliado o botão Ingressar na Reunião para corrigir truncamento em alguns idiomas.

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema em que tabelas não são exibidas corretamente após determinadas ações.
-   Correção de um problema em que várias edições a citações por vezes aparecem como uma ação de desfazer em vez de ações individuais consecutivas.
-   Correção de um problema em que a ação de desfazer é desabilitada após determinadas ações.
-   Correção de um problema para evitar a possível perda de dados após determinadas ações de desfazer.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidade de execução remota de código do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema que causa falha em upgrades autônomos do Office 2013 para o Office 2016 ao usar o System Center Configuration Manager.
-   Correção de um problema em que suplementos herdados implantados do repositório por meio do catálogo corporativo não carregam.



## <a name="version-1705-june-13"></a>Versão 1705: 13 de junho
*Versão 1705 (build 8201.2102)*

### <a name="access-feature-updates"></a>Access: atualizações de recursos
-   **Caixa de diálogo Novidades:** Uma caixa de diálogo que destaca os novos recursos do Access é exibida ao abrir este programa, após a respectiva atualização com os novos recursos. A caixa de diálogo também está disponível em Arquivo \> Conta \> Novidades.
-   **Suporte para Número Grande (bigint):** Usar o tipo de dados Número Grande em tabelas do Access para calcular números grandes e para vincular a ou importar de bancos de dados externos que usam um tipo de dados equivalente, como bigint no SQL Server. [Mais informações](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
-   **Suporte à Proteção de Informações do Windows (WIP):**   O Excel agora é um aplicativo inteligente, e pode diferenciar dados pessoais de corporativos, determinando corretamente quais proteger com base em políticas configuradas.  [Mais informações](https://aka.ms/wiptechnet)
-   **Melhoria no recurso Obter e Transformar:** No Editor de Consultas, crie uma nova coluna fornecendo valores de exemplo. Conforme você digita, o Excel detecta as transformações necessárias e mostra uma visualização da nova coluna.
-   **Inserir links recentes:** Anexe facilmente hiperlinks aos sites ou arquivos recentes baseados em nuvem e crie nomes para exibição significativos para as pessoas que usam leitores de tela. [Mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personalizar o layout padrão da Tabela Dinâmica:** Configure uma Tabela Dinâmica da forma que desejar e comece com esse layout toda vez que você criar uma nova Tabela Dinâmica. [Mais informações](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Melhorias no recurso Obter e Transformar:** Os usuários podem criar novas colunas com um exemplo e dividir as colunas da tabela em linhas. Especificar parâmetros para dados de agrupamento e SAP HANA agora é mais fácil.
-   **Implantação centralizada de suplementos**: os administradores podem implantar e atualizar suplementos para os usuários ou grupos por meio do centro de administração do Office 365. [Mais informações](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personalização da Barra de Ferramentas de Acesso Rápido:** Os ícones Subscrito e Sobrescrito podem ser adicionados à Barra de Ferramentas de Acesso Rápido.
-   **Melhorias no recurso Obter e Transformar:** detecção automática de caractere delimitador ao dividir colunas usando o Editor de Consultas, escolher o arquivo de exemplo para usar com o recurso Combinar Binários e especificar a Coleção de Pacotes ao qual se conectar durante o uso do conector DB2.
-   **Fonte Dubai:** família de fontes compatível com idiomas da Europa Ocidental e com a maioria dos idiomas que usa escrita árabe. [Mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de segundo plano:** Remova o segundo plano da imagem com uma ferramenta de desenho de forma livre.
-   **Melhorias no recurso Obter e Transformar:** Use a opção "Selecionar Tabelas Relacionadas" na caixa de diálogo do Navegador com os conectores ODCB e OLEDB, combine vários arquivos diretamente na caixa de diálogo Visualização de Dados da pasta e use uma nova opção de menu de contexto na janela do Editor de Consultas para inserir novas etapas em consultas existentes.
-   **Use uma caneta para selecionar e alterar objetos:** Selecione alças de objeto com uma caneta digital para redimensionar, girar, mover e muito mais.
-   **Gráfico de mapa:** compare os valores e exiba as categorias nas regiões geográficas. [Mais informações](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Imagens SVG** insira e edite elementos gráficos vetoriais escaláveis (SVG) em pastas de trabalho. [Mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  utilize ícones de uma biblioteca padrão de arquivos de elementos gráficos vetoriais escaláveis (SVG) indo para Inserir \> Ilustrações \> Ícones. [Mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salvar em pastas recentes:** salve uma pasta de trabalho em uma pasta usada recentemente, por meio da guia Recente, indo para Arquivo \> Salvar como.
-   **Melhorias na acessibilidade:** suporte aprimorado no uso do teclado, do Narrator e de outras tecnologias adaptativas para ler e editar pastas de trabalho. [Mais informações](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Atualização de segurança do Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema em que o Excel não define a senha de proteção da planilha quando aplicada a pastas de trabalho criadas no Excel 2010 ou anterior.
-   Correção de um problema em que o botão Mesclar e Centralizar não funcionava em planilhas agrupadas.
-   Correção de um problema em que faltam novas funções que foram introduzidas após o lançamento do Office 2016, por exemplo, UNIRTEXTO, CONCAT, SES, MÁXIMOSES e MÍNIMOSES.
-   Correção de um problema em que o Excel trava quando o usuário tenta aplicar permissões a nível de célula.
-   Correção de um problema em que salvar um arquivo grande no OneDrive for Business faz com que o arquivo seja bloqueado, e o usuário só consiga editar o arquivo depois de fechar e abrir novamente o Excel.
-   Correção de um problema em que uma nova janela é exibida esmaecida quando uma pasta de trabalho .xls é aberta.
-   Correção de um problema em que o Excel pode falhar ao inserir hiperlinks.
-   Correção de um problema em que o Excel pode falhar ao adicionar Mapas XML.
-   Correção de um problema em que o botão de comando de um suplemento deixa de funcionar após atualizar ou remover e baixar novamente o suplemento da Office Store.
-   Correção de um problema em que o Excel pode falhar ao manipular planilhas DLL por meio do VBA.
-   Correção de um problema em que o Excel falha ao selecionar uma caixa de combinação de controle de formulário em uma planilha de gráfico.

### <a name="onenote-feature-updates"></a>OneNote: Atualizações de recursos
-   **Suporte à Proteção de Informações do Windows (WIP):** O OneNote agora é um aplicativo inteligente, e pode diferenciar dados pessoais de corporativos, determinando corretamente quais proteger com base em políticas configuradas. [Mais informações](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações que não são de segurança
-   Correção de um problema em que a tela do OneNote oculta conteúdo ou é atualizada quando muitos parágrafos estão no modo de exibição.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recursos
-   **Suporte à Proteção de Informações do Windows (WIP):**   O Outlook agora é um aplicativo inteligente, e pode diferenciar dados pessoais de corporativos, determinando corretamente quais proteger com base em políticas configuradas.  [Mais informações](https://aka.ms/wiptechnet)
-   **Inserir links recentes:** Anexe hiperlinks aos sites ou arquivos recentes baseados em nuvem e crie nomes para exibição significativos para as pessoas que usam leitores de tela. [Mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Fonte Dubai:** família de fontes compatível com idiomas da Europa Ocidental e com a maioria dos idiomas que usa escrita árabe. [Mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de segundo plano:** Remova o segundo plano da imagem com uma ferramenta de desenho de forma livre.
-   **Verifique o acesso aos arquivos compartilhados:** O Outlook informa ao usuário com antecedência que os destinatários talvez não consigam acessar um arquivo em anexo do OneDrive ou do SharePoint e sugere uma maneira de corrigir o problema.
-   **Defina permissões sobre anexos:** Em relação aos anexos do OneDrive ou do SharePoint, o usuário pode definir se os destinatários externos ou internos da organização têm permissões para ler ou editar o anexo.
-   **Painel de tarefas fixável:** Deixe o painel de tarefas do suplemento aberto enquanto alterna entre as mensagens em uma caixa de correio. [Mais informações](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Imagens SVG** insira e edite elementos gráficos vetoriais escaláveis (SVG) em emails. [Mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  utilize ícones de uma biblioteca padrão de arquivos de elementos gráficos vetoriais escaláveis (SVG) indo para Inserir \> Ilustrações \> Ícones. [Mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilidade de bypass de recurso de segurança do Microsoft Office
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): execução remota de código do Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): vulnerabilidade de bypass de recurso de segurança do Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações que não são de segurança
-   Correção de um problema em que o painel de navegação do Outlook para de renderizar quando a máquina está com pouca memória.
-   As larguras do anexo são expandidas visualmente para ajustar as informações de permissão e nome do arquivo.
-   Correção de um problema em que o usuário não consegue pesquisar arquivos PST.
-   Correção de um problema em que o usuário vê um novo tipo de armazenamento do "Microsoft Exchange" na caixa de diálogo "Novo Arquivo de Dados do Outlook" e a seleção desse novo tipo de dados faz com que o perfil do usuário se torne inutilizável.
-   Correção de um problema em que a imagem de uma mensagem é bloqueada quando é enviada de um computador com alto DPI.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recursos
-   **Suporte à Proteção de Informações do Windows (WIP):**   O PowerPoint agora é um aplicativo inteligente, e pode diferenciar dados pessoais de corporativos, determinando corretamente quais proteger com base em políticas configuradas. [Mais informações](https://aka.ms/wiptechnet)
-   **Inserir links recentes:** Anexe hiperlinks aos sites ou arquivos recentes baseados em nuvem e crie nomes para exibição significativos para as pessoas que usam leitores de tela. [Mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implantação centralizada de suplementos**: os administradores podem implantar e atualizar suplementos para os usuários ou grupos por meio do centro de administração do Office 365. [Mais informações](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fonte Dubai:** família de fontes compatível com idiomas da Europa Ocidental e com a maioria dos idiomas que usa escrita árabe. [Mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de segundo plano:** Remova o segundo plano da imagem com uma ferramenta de desenho de forma livre.
-   **Imagens SVG** insira e edite elementos gráficos vetoriais escaláveis (SVG) em apresentações. [Mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  utilize ícones de uma biblioteca padrão de arquivos de elementos gráficos vetoriais escaláveis (SVG) indo para Inserir \> Ilustrações \> Ícones. [Mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Digitando em tempo real durante coautoria:** Consulte onde outras pessoas estão trabalhando na apresentação e modo de exibição é alterado enquanto eles digitam. [Mais informações](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Salvar em pastas recentes:** salve uma apresentação em uma pasta usada recentemente, por meio da guia Recente, indo para Arquivo \> Salvar como.
-   **Criar formas de tinta precisas:** arraste a Borracha de Segmentos para remover o excesso de bits de tinta, até a linha mais próxima.
-   **Selecionar e manipular objetos com uma caneta:** use uma caneta digital para mover, redimensionar ou girar objetos por meio das alças ou use botões de caneta compatíveis para Seleção de Laço com tinta.
-   **Melhorias na acessibilidade:** suporte aprimorado do uso do teclado, do Narrator e de outras tecnologias adaptativas para ler e editar apresentações. [Mais informações](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que o PowerPoint falha quando o usuário está no painel Ideias de Design, se o arquivo mfplat.dll não estiver instalado no computador.
-   Correção de um problema em que o botão de comando de um suplemento deixa de funcionar após atualizar ou remover e baixar novamente o suplemento da Office Store.

### <a name="project-feature-updates"></a>Project: Atualizações de recursos
-   **Menu suspenso rápido para predecessores de configuração:** Use o menu suspenso do gráfico Gantt para escolher quais predecessores ou sucessores você deseja vincular a uma tarefa.
-   **Nome do Resumo da Tarefa:**  Campo de tarefa somente leitura que mostra o nome da tarefa resumo.  

### <a name="project-non-security-updates"></a>Project: Atualizações que não são de segurança
-   Correção da caixa de diálogo Criar Site do Projeto para mostrar o local correto do site, agora que no Project Online cada EPT (Modelo do Enterprise Project) terá a própria URL para sites de projetos.
-   Correção de um problema em que o evento VBA BeforeClose aciona antes do prompt Salvar, e você não tem uma forma programática de determinar a resposta do usuário para o prompt de salvamento.
-   Correção de um problema em que % Física Concluída não rola corretamente para as tarefas que começam após a data do status do projeto.
-   Correção de um problema em que ao atribuir um custo e um recurso de trabalho à mesma tarefa, você poderia não conseguir alterar o gerenciador de status da tarefa.
-   Correção de um problema em que, para alguns projetos, nivelar o projeto inteiro deixava você em um loop infinito.
-   Correção de um problema em que as datas de início e de término da tarefa não sincronizavam corretamente com uma lista de tarefas do SharePoint se você tivesse determinadas configurações regionais da Espanha.
-   Correção de um problema em que se você iniciasse o processo de aprovação de status do cliente do Project, poderia não terminar nunca, deixando o projeto em um estado inutilizável.
-   Correção de um problema em que a visualização da impressão não exibia os nomes da tarefa corretamente se você tivesse palavras em chinês e inglês.
-   Correção de um erro em que copiar a linha do tempo no PowerPoint como formas individuais não funciona.
-   Correção de um problema em que a caixa de diálogo "Links Entre Projetos" exibe de forma inesperada o valor "Arquivo Não Encontrado".
-   Correção de um problema em que você recebe resultados inconsistentes ao atribuir recursos com Unidades Máximas de 0.
-   Correção de um problema em que a data de início de uma tarefa é redefinida para O Quanto Antes ao excluir a data de início de uma atribuição, ignorando pontos como antecessores, o que leva a divisões de atribuições.
-   Correção de um problema em que se você abrir um arquivo do SharePoint por meio do menu Recentes, o check-out do projeto será feito automaticamente para você, mesmo que a configuração "Exigir o check-out dos documentos antes que eles possam ser editados?" esteja habilitada.
-   Correção de um problema em que se você for diretamente para o aplicativo de Perfis do Project, o Project falhará.
-   Correção de um problema em que tarefas agendadas manualmente não são atualizadas corretamente para usuários atualizando do Project 2013.
-   Correção de um problema em que ao abrir um projeto de uma lista de tarefas do SharePoint, o Project pode falhar ao iniciar o processo de sincronização das tarefas.
-   Correção de um problema em que o Project, às vezes, falha ao ir para Criar Equipe.
-   Correção de um problema em que ocorre a perda de informações da linha de base ao salvar um projeto.
-   Correção de um problema em que há dificuldade de leitura para Cópias Impressas de planos de projetos grandes.
-   Correção de um problema em que os projetos editados no Project Web App não mostram os valores corretos nos campos de fórmula.
-   Correção de um problema em que as informações dos campos personalizados de Recurso da Empresa não são salvas corretamente em um plano de projeto.
-   Correção de um problema em que a atualização da informação de porcentagem do trabalho concluída de uma tarefa atualiza a porcentagem concluída da tarefa.
-   Correção de um problema em que a propriedade do projeto é alterada após salvá-lo.
-   Correção de um problema em que a CPI é calculada de forma incorreta para uma tarefa resumo.
-   Correção de um problema em que as tarefas de cópia e colagem transferem os dados da linha de base e salvam os dados, mesmo que o usuário não tenha permissão para salvar os dados protegidos da linha de base.
-   Correção de um problema em que importar dados do Excel resulta em informações de data incorretas para tarefas e atribuições.
-   Correção de um problema em que o Project falha ao fechar, após a abertura de um relatório.
-   Correção de um problema em que o Project para de funcionar ao salvar um projeto cuja lista personalizada contém configurações de validação.
-   Correção de um problema em que a inserção do caractere "\>" na coluna de Teste da caixa de diálogo Definição de Filtro não é interpretada de forma correta como "maior que".
-   Correção de um problema com a exibição de linhas de andamento relacionadas ao "plano de linha de base".
-   Correção de um problema em que a lista suspensa de nomes de campo não é exibida ao personalizar filtros.
-   Correção de um problema em que as visualizações de Estilo da barra não são exibidas na caixa de diálogo Estilos de barra.

### <a name="publisher-non-security-updates"></a>Publisher: Atualizações que não são de segurança
-   Correção de um problema em que o Publisher não exibe imagens TIF em CMYK.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Atualizações de recursos
-   **Inserir link:** adicione um link aos chats de grupo e às mensagens instantâneas, e forneça texto amigável para o link em vez da URL inteira.
-   **Notificação de compartilhamento de tela:** Uma notificação será exibida na janela de conversa quando estiver compartilhando uma tela em uma conversa de mensagens Instantâneas ou compartilhamento de tela continuará depois que você sair de uma reunião. A notificação lembra que você ainda estiver compartilhando sua tela e torna mais fácil interromper o compartilhamento usando o botão "Interromper compartilhamento".
-   **Suporte à Proteção de Informações do Windows (WIP):** O Skype for Business agora tem suporte como um aplicativo Somente para Trabalhos de WIP.  Ao adicionar o Skype à sua lista de aplicativos permitidos, ele indica ao Windows que não processa dados pessoais. O Windows protegerá os dados em nome do Skype for Business. [Mais informações](https://aka.ms/wiptechnet)
-   **Opção para redefinir senha:** o link do botão Redefinir é exibido na janela de entrada, quando o usuário não consegue entrar pelo menos uma vez.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): atualização de segurança do componente Microsoft Graphics (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): vulnerabilidade de execução remota de código de Uniscribe do Windows
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): vulnerabilidade de execução remota de código do Skype for Business

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Alterar a mensagem para chamadas tentadas para usuários com áudio desabilitado por diretiva de "Não é possível completar a chamada" para "não é possível chamar porque um administrador de TI tem restritas áudio. Tente usar mensagens instantâneas ou email em vez disso e pede para Verifique com seu administrador de TI".
-   Adição de um hiperlink "Esqueceu seu PIN de discagem" para os convites da reunião de usuários habilitados para conferência PSTN do Skype for Business Online.
-   Ativação do ingresso das equipes à reunião do Skype for Business Online.
-   Alteração do volume padrão da sessão do alto-falante de 40% para 75%.
-   Permissão do redimensionamento da lista de guias para uma largura mínima ainda menor.
-   Atualização das teclas de atalho para corresponder a ordem de guias.
-   Correção da direção incorreta do texto em hebraico quando enviado de um dispositivo móvel.
-   Correção de um problema com a informação narrada por um leitor de tela para o recurso Apresentar Área de Trabalho/Conceder Controle.
-   Mostre salas abertas além das salas acompanhadas nas listas Selecionar Sala.
-   Adicione a possibilidade de desativar o recurso de VoIP enquanto o aplicativo RCC personalizado está habilitado.
-   Altere o slogan de mensagens instantâneas para "Experimente o aplicativo móvel do Skype for Business".
-   Correção de um problema que faz com que uma janela de conversa de uma conversa aceita automaticamente abra como uma janela normal em vez de minimizada, e inesperadamente tira o foco de outras janelas.
-   Correção de um problema com o uso de um leitor de tela na caixa de diálogo de Opções de Reunião do Skype.
-   Correção de um problema em que a primeira mensagem em um convite não é exibida no email de Conversas Perdidas.
-   Correção de um problema em que números de discagem duplicados são exibidos ao criar um convite de reunião a partir do Outlook usando o botão Nova Reunião do Skype.
-   Correção de um problema em que, quando uma barra de rolagem é exibida, todas as conversas no histórico de mensagens instantâneas não são selecionadas ao usar Ctrl+A para selecionar tudo.
-   Correção de um problema em que o texto de saída pode não ser do mesmo formato exato ao usar o cmdlet Export-CsArchivingData.
-   Correção de um problema em que o organizador da reunião não pode ver o vídeo dos participantes remotos ao usar Reunir Agora com três ou mais participantes.
-   Correção de um problema em que a primeira linha da lista de participação da reunião fica em branco quando um usuário clica com o botão direito no nome de outro usuário na lista de participantes.
-   Correção de um problema em que os usuários não conseguem entrar quando alternam entre redes corporativas internas e externas.
-   Correção de um problema em que a área do gráfico não é fechada ao fazer o escalonamento de IM para Áudio, na Transferência de consultoria.
-   Correção de um problema em que os nomes são truncados nas notificações do sistema, ao usar o toque de dois pontos de extremidade em simultâneo.
-   Correção de um problema em que o nome do arquivo é truncado, nas notificações de compartilhamento de arquivo.
-   Adicionar dicas de ferramenta para o recurso "Voltar à chamada" e para botões de transferência.
-   Disponibilizar o tempo gasto em espera na janela "Transferência de consultoria" para leitores de tela, como o Narrador.
-   Adicionar a capacidade de escolher IM ou chamadas como preferência padrão da Transferência de consultoria.
-   Adicionar a capacidade de clicar com o botão direito do mouse no botão "Transferência" a fim de exibir uma lista de números de telefone do contato, ao fazer uma transferência de consultoria.
-   Aprimorar uma mensagem de erro geral para informar com clareza que o problema está relacionado ao usuário que tem uma licença inválida ou que ainda não recebeu uma licença.
-   Correção de um problema em que nem todos os contatos são exibidos no título da janela da conversa quando um usuário inicia uma conversa com um contato e, em seguida, adiciona outro contato.
-   Correção de um problema em que o Narrador não lê a segunda linha das notificações.
-   Correção de um problema em que as chamadas são transferidas para o VoIP em lugar do número consultado.
-   Correção de um problema em que o Narrador pronuncia informações incorretas, quando o usuário navega na janela de Conteúdo.
-   Correção de um problema em que os nomes do criador e do modificador não são exibidos ao passar o cursor do mouse sobre as anotações em um quadro de comunicações

### <a name="visio-feature-updates"></a>Visio: Atualizações de recursos
-   **Localizar estênceis de terceiros:** Procure estênceis de terceiros fornecidos pelos provedores de conteúdo selecionados.
-   **Trechos de código:** Capture trechos de código de um desenho do Visio e exporte-os como slides para o PowerPoint. [Mais informações](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: atualizações de recursos
-   **Suporte à Proteção de Informações do Windows (WIP):**   O Word agora é um aplicativo inteligente, e pode diferenciar dados pessoais de corporativos, determinando corretamente quais proteger com base em políticas configuradas.   [Mais informações](https://aka.ms/wiptechnet)
-   **Inserir links recentes:** Anexe hiperlinks aos sites ou arquivos recentes baseados em nuvem e crie nomes para exibição significativos para as pessoas que usam leitores de tela. [Mais informações](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Implantação centralizada de suplementos**: os administradores podem implantar e atualizar suplementos para os usuários ou grupos por meio do centro de administração do Office 365. [Mais informações](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Fonte Dubai:** família de fontes compatível com idiomas da Europa Ocidental e com a maioria dos idiomas que usa escrita árabe. [Mais informações](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Remoção de segundo plano:** Remova o segundo plano da imagem com uma ferramenta de desenho de forma livre.
-   **Lado a Lado:** Navegue em páginas no modo de exibição Layout de Impressão ao deslizá-las lado a lado, como uma pilha de papéis. [Mais informações](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Use uma caneta para selecionar e alterar objetos:** Selecione alças de objeto com uma caneta digital para redimensionar, girar, mover e muito mais.
-   **Imagens SVG** insira e edite elementos gráficos vetoriais escaláveis (SVG) em documentos. [Mais informações](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserir ícones:**  utilize ícones de uma biblioteca padrão de arquivos de elementos gráficos vetoriais escaláveis (SVG) indo para Inserir \> Ilustrações \> Ícones. [Mais informações](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salvar em pastas recentes:** salve um documento em uma pasta usada recentemente, por meio da guia Recente, indo a Arquivo \> Salvar como.
-   **Leitura aprimorada com as ferramentas de aprendizagem:** os novos comandos no Modo Leitura melhoram as habilidades de leitura ajustando o espaçamento do texto, mostrando as quebras entre as sílabas e realçando cada palavra à medida que o documento é lido em voz alta. [Mais informações](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **Reconhecimento de formas:** para transformar os desenhos automaticamente em formas, use o recurso Desenhar \> Converter em Formas. [Mais informações](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Atualização de segurança do Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): vulnerabilidade de execução remota de código em PDFs no Windows 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Vulnerabilidade de execução remota de código do Microsoft Office  

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema em que o usuário não consegue pesquisar arquivos PST.
-   Correção de um problema em que o usuário vê um novo tipo de armazenamento do "Microsoft Exchange" na caixa de diálogo "Novo Arquivo de Dados do Outlook" e a seleção desse novo tipo de dados faz com que o perfil do usuário se torne inutilizável.

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): vulnerabilidade de execução remota de código do Microsoft Office/WordPad com API do Windows
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): execução remota de código do Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1701-may-9"></a>Versão 1701: 9 de maio
* Versão 1701 (build 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema que faz com que os usuários vejam intermitentemente a seleção de mensagem na lista de mensagens saltar de forma inesperada ao excluir mensagens.
-   Correção de um problema que causa falhas intermitentes.
-   A adição da chave do Registro HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage permite que os administradores ocultem a opção de Suporte na guia Arquivo.
-   Adicione a chave do registro HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures para que os administradores possam desativar as opções "Comentários sobre o Outlook 2016" e "Blog do Outlook" em Arquivo \> Comentários.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Atualizações de segurança
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidade de execução remota de código do Microsoft Office

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   correção de um problema que faz com que uma janela de conversa de uma conversa aceita automaticamente abra como uma janela normal em vez de minimizada, e inesperadamente tira o foco de outras janelas.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidade de execução remota de código do Microsoft Office

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1701-april-11"></a>Versão 1701: 11 de abril
*Versão 1701 (build 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que uma nova janela é exibida esmaecida quando uma pasta de trabalho .xls é aberta.

### <a name="outlook-security-updates"></a>Outlook: Atualizações de segurança
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilidade de bypass de recurso de segurança do Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações que não são de segurança
-   Correção de um problema em que o usuário vê um novo tipo de armazenamento do "Microsoft Exchange" na caixa de diálogo "Novo Arquivo de Dados do Outlook" e a seleção desse novo tipo de dados faz com que o perfil do usuário se torne inutilizável.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema em que ocorre um erro de imagem não encontrada quando o usuário executa "Salvar como" para um local alternativo de um arquivo do PowerPoint que está armazenado em mídia removível, como um pen drive USB.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Correção de um problema em que os usuários não conseguem entrar quando alternam entre redes corporativas internas e externas.

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): vulnerabilidade de execução remota de código do Microsoft Office/WordPad com API do Windows



## <a name="version-1701-march-14"></a>Versão 1701: 14 de março
*Versão 1701 (build 7766.2071)*

### <a name="access-non-security-updates"></a>Access: atualizações não relacionadas à segurança
-   Correção de um problema em que os menus suspensos não podem ser descartados.

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Atualização de segurança do Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Correção de um problema em que o Excel pode falhar ao inserir hiperlinks.
-   Correção de um problema em que o Excel pode falhar ao adicionar Mapas XML.
-   Correção de um problema em que o botão de comando de um suplemento deixa de funcionar após atualizar ou remover e baixar novamente o suplemento da Office Store.
-   Correção de um problema em que o Excel pode falhar ao manipular planilhas DLL por meio do VBA.

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações que não são de segurança
-   Correção de um problema em que a tela da página do OneNote deixa de responder a cliques do mouse após autenticar usando um PIN na versão 1607 do Windows 10 (também conhecida como Atualização de Aniversário do Windows).
-   Desabilite o comportamento otimizado da cópia impressa específico de EDU quando um usuário inserir um documento editável, como .docx ou .pptx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema em que conflitos de mesclagem aparecem incorretamente durante a coautoria.
-   Correção de um problema em que o botão de comando de um suplemento deixa de funcionar após atualizar ou remover e baixar novamente o suplemento da Office Store.
-   Correção de um problema em que chamadas para o modelo de objeto VBA resultam em um erro de tempo de execução quando formas são aplicadas a gráficos.

### <a name="publisher-non-security-updates"></a>Publisher: Atualizações que não são de segurança
-   Correção de um problema em que o Publisher não exibe imagens TIF em CMYK.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): atualização de segurança do componente Microsoft Graphics (4013075)

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Atualização de segurança do Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema de consumo de memória ao usar certas configurações de monitor.
-   Correção de um problema em que o botão de comando de um suplemento deixa de funcionar após atualizar ou remover e baixar novamente o suplemento da Office Store.



## <a name="version-1701-february-22"></a>Versão 1701: 22 de fevereiro
*Versão 1701 (build 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
-   **Melhorias na conectividade e na transformação de dados:** Expandir uma lista em uma nova coluna de texto com delimitador entre os valores e especificar uma opção de failover ao se conectar ao SQL.
-   **Melhorias na conectividade e na transformação de dados:** Agora há suporte para o tipo de dados Porcentagem, e experiências de autoria de função combinando binário foram aprimoradas.
-   **Conector OLEDB:** Use o conector OLEDB em Obter e Transformar para criar uma consulta para importar dados especificando uma Cadeia de Conexão e, opcionalmente, uma instrução SQL para executar.
-   **Reprodução de tinta:** vá para Desenhar \> Reprodução de tinta para reproduzir manuscritos para frente e para trás, a fim de ocultar e revelar conteúdo, fornecer instruções passo a passo ou entender melhor o fluxo de pensamento de outras pessoas.[Mais informações](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Suporte para CSV (UTF-8):** abrir e salvar arquivos CSV que usam a codificação de caracteres UTF-8.
-   **Melhorias de conectividade e transformação de dados:** escolha importar tabelas relacionadas quando carregar dados de fontes OData, adicionar colunas personalizadas com valores provenientes de cálculos de função ou mostrar as dependências entre consultas usando um modo de exibição dedicado.
-   **Compartilhado comigo:** Para ver os documentos que outras pessoas compartilharam com você, vá para Arquivo \> Abrir \> Compartilhado comigo. [Mais informações](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Alterar cores:** Use Diga-me para definir a cor para a fonte, realce, preenchimento de forma e muito mais. [Mais informações](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Atualização de segurança do Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel: Atualizações que não são de segurança
-   Foi corrigido um problema em que, quando o tema do Office é definido como Preto, uma mensagem de erro "Erro inesperado" aparece ao se clicar com o botão direito do mouse em uma consulta no painel Consultas da Pasta de Trabalho.
-   Foi corrigido um problema em que o Excel trava quando o usuário tenta acessar opções de Tabela Dinâmica.
-   Correção de um problema em que os valores das células com texto e aspas duplas não são exportados corretamente ao salvar como CSV ou CSV UTF-8.
-   Correção de um problema em que o Excel trava ou falha ao fechar.
-   Correção de um problema em que um hiperlink que contém uma fórmula concatenada ignora parte do resultado concatenado.
-   Correção de um problema em que o formato da tabela não é preservado ao colá-la do Excel, em formato RTF (rich text), no Word.
-   Correção de um problema em que o usuário não pode utilizar o Salvar como quando a pasta de trabalho contém uma planilha de Macro do MS Excel 4.0.
-   Tornar Ctrl+Alt+5 o atalho para mover uma seleção para a camada de objeto para corresponder a outros aplicativos.
-   Correção de um problema em que, ao digitar na barra de fórmulas e usar uma função com uma lista suspensa, como PROCV, pressionar Enter para calcular a fórmula faz com que o item superior da lista suspensa de Preenchimento Automático seja selecionado, em vez de deixar o valor digitado no estado em que se encontra.
-   Correção de um problema em que, ao abrir um formato de arquivo binário do Excel 97 ou Excel 2003 (BIFF8), que contém um hiperlink em uma planilha protegida, faz com que o programa considere o arquivo como corrompido e tente reparar ou remover o conteúdo ilegível.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: Atualizações que não são de segurança
-   Correção de um problema em que, se o GrooveIntlResource.dll não puder ser carregado com êxito (o que é improvável em circunstâncias normais), um aplicativo do Office poderá falhar se o usuário tentar abrir ou salvar um arquivo em uma pasta sincronizada ou o Windows Explorer poderá falhar se o usuário navegar para uma pasta sincronizada usando o Windows Explorer.
-   Foi corrigido um problema em que o OneDrive for Business não é desabilitado, mesmo que a chave do Registro apropriada seja definida para desabilitá-lo, quando o Office é configurado para receber atualizações de um local diferente da CDN (Rede de Distribuição de Conteúdo) do Office.

### <a name="onenote-feature-updates"></a>OneNote: Atualizações de recursos
-   **Controlar a sincronização de arquivos e imagens:** Vá para Arquivo \> Opções \> Sincronizar para controlar se todos os arquivos e imagens são baixados automaticamente para todas as páginas em blocos de anotações.

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações que não são de segurança
-   Foi corrigido um problema em que o OneNote trava ao imprimir uma imagem maior do que a página.
-   Correção de um problema em que um usuário não pode excluir um modelo de página personalizado.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recursos
-   **Colabore em anexos em tempo real:** Carregue anexos no OneDrive for Business para que todos possam trabalhar na versão mais recente. Use o menu suspenso no anexo para carregá-lo ou salvá-lo.
-   **Cartões de resumo para pacotes e reservas de viagem:** Verificar e controlar reservas de viagem, bem como entregas de pacote, usando cartões de resumo criados automaticamente na Caixa de Entrada e Calendário. [Mais informações](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Editor:** fornece um revisor de texto contextual avançado para ajudar a melhorar a escrita do usuário. [Mais informações](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Foi corrigido um problema em que, ao se clicar com o botão direito do mouse em um anexo na lista de anexos de uma conversa, todos os itens de menu de contexto são visíveis, em vez de apenas os itens de menu aplicáveis.
-   Correção de um problema em que o destinatário não consegue abrir as mensagens de email em RTF (Formato Rich Text), se as mensagens forem enviadas com Gerenciamento de Direitos de Informação.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recursos
-   **Legendas ocultas:** Se um slide contém um vídeo com legendas ocultas, as legendas podem ser reproduzidas na apresentação de slides.
-   **Várias faixas de áudio:** Se um slide contém um vídeo com várias faixas de áudio, as faixas podem ser reproduzidas na apresentação de slides.
-   **Cópia de seção:** copiar e colar seções entre apresentações.
-   **Compartilhado comigo:** Para ver os documentos que outras pessoas compartilharam com você, vá para Arquivo \> Abrir \> Compartilhado comigo. [Mais informações](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Reprodução de tinta:** Reproduza manuscritos para frente e para trás para ocultar e revelar conteúdo, fornecer instruções passo a passo ou entender melhor o fluxo de pensamento de outras pessoas. [Mais informações](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Melhores gravações:** Crie uma apresentação composta de slides gravados, gravações de tela e vídeo inserido e compartilhe o conteúdo gravado para ser visualizado remotamente. Você também pode inserir testes para auxiliar a aprendizagem remota e tornar a apresentação mais interativa, bem como alterar a cor da tinta e usar controles simples para gravar narrações e áudio.
-   **Melhorias do Designer:** Fornece sugestões de design usando SmartArt para listas de processos com marcadores.
-   **Guia de faixa de opções de gravação:** Adicione uma guia Gravação ao personalizar a faixa de opções.
-   **Alterar cores:** Use Diga-me para definir a cor para a fonte, realce, preenchimento de forma e muito mais. [Mais informações](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Zoom:** crie um resumo interativo da apresentação com links de navegação automática. [Mais informações](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Abrindo hiperlinks:** Use Ctrl+clique para abrir hiperlinks ao editar uma apresentação.
-   **Realce de texto:** Chame a atenção para um texto importante usando o marca-texto.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Corrigir um problema em que, ao recortar uma imagem, a parte recortada da imagem aparece escura.
-   Foi corrigido um problema em que, no modo de Apresentação de Slides e quando o Narrador está em execução, o PowerPoint falha quando o usuário clica em um hiperlink e o site tem carregamento lento.
-   Foi corrigido um problema em que a digitação em tempo real durante a coautoria não funciona com tabelas.
-   Correção de um problema em que, ao abrir o PowerPoint em um computador com o Malwarebytes 3.0 instalado, aparece um erro "Parou de funcionar" ou o PowerPoint trava.
-   Correção de um problema em que o modelo padrão não aparece na seção Arquivo \> Novo.
-   Correção de um problema em que a digitação do texto é interrompida e atrasada quando um arquivo com fontes inseridas é salvo automaticamente.
-   Correção de um problema com a cópia de imagens de elementos gráficos vetoriais escaláveis (SVG) do Adobe Illustrator.

### <a name="project-feature-updates"></a>Project: Atualizações de recursos
-   **Campo bloqueado:** Defina o valor como Sim para impedir que os membros da equipe enviem atualizações em uma tarefa.
-   **Rótulos de linha do tempo:** especifique as barras de linha do tempo usando rótulos para dar-lhes nomes descritivos.
-   **Indicadores de progresso de linha do tempo:** use as marcas de seleção e as barras de progresso coloridas no Modo de Exibição de Linha do Tempo para exibir em que ponto você está em cada tarefa.
-   **Melhorias na acessibilidade:** suporte aprimorado de uso do teclado, do Narrator e de outras tecnologias adaptativas para ler e editar projetos.

### <a name="project-non-security-updates"></a>Project: Atualizações que não são de segurança
-   Correção de um problema em que nenhuma linha de link é exibida ao criar um link entre projetos entre o projeto principal e um subprojeto.
-   Correção de um problema em que os valores de linha de base divididos ao longo do tempo não são sempre salvos corretamente no formato XML, especialmente os valores de custo e trabalho contendo durações parciais.
-   Correção de um problema em que, ao aplicar atualizações de status, o trabalho real é adicionado à atribuição que o membro da equipe não relatou.
-   Correção de um problema em que os valores da linha de base são exibidos para um recurso, mesmo quando uma linha de base ainda não foi criada para o recurso.
-   Correção de um problema em que a visualização de impressão corta o texto, de modo que ele não fica visível.
-   Correção de um problema em que, ao abrir um arquivo .mpp do SharePoint usando uma URL de atalho, o arquivo abre como selecionado, mesmo que a configuração "Exigir que os documentos sejam selecionados antes que eles possam ser editados?" esteja habilitada.
-   Correção de um problema em que as atualizações dos recursos materiais no Aplicativos Web do Project alteram incorretamente os dados divididos ao longo do tempo.
-   Correção de um problema em que abrir um projeto que tem uma tarefa importante pode adicionar uma Data de início real a ele mesmo que ele não tivesse uma data no momento em que ele foi salvo pela última vez.
-   Correção de um problema com a renumeração da estrutura de detalhamento de trabalho (EDT).
-   Foi corrigido um problema em que o Project trava quando você sai de uma exibição baseada em grade e o Narrador está ativado.
-   Foi corrigido um problema em que uma mensagem de erro incorreta é mostrada sobre truncamento de dados divididos em fases ao ser aberto um arquivo XML.
-   Foi corrigido um problema em que a gravação de uma linha de base não define corretamente valores divididos em fases.
-   Foi corrigido um problema em que o atraso da atribuição é ignorado quando os dados de projeto são lidos de um arquivo XML.
-   Foi corrigido um problema em que, ao ser aberto um arquivo do Project Online, a data de Última Modificação mostra a hora UTC em vez da hora ajustada para o fuso horário.
-   Foi corrigido um problema em que faixas coloridas de agrupamento não aparecem para linhas de agrupamento ao ser impresso um modo de exibição de planilha.
-   Foi corrigido um problema em que uma opção de reparo é mostrada incorretamente quando o usuário inspeciona uma tarefa que tem uma atribuição além do problema de unidade máxima.
-   Foi corrigido um problema em que o valor de um campo de Código de Estrutura de Tópicos não pode ser alterado depois que o projeto é publicado.
-   Correção de um problema em que as barras de Gantt não são dimensionadas corretamente em telas com alto DPI na exibição de 175%.
-   Correção de um problema em que se o usuário define o tempo de retardo por meio da caixa de diálogo Informações da Tarefa, ele é incorretamente definido com duração decorrida.
-   Correção de um problema em que ao abrir determinados arquivos XML, a data de início da tarefa não está definida corretamente devido a um problema com a atribuição.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Atualizações de recursos
-   **Estilo de notificação do Windows:** alterações na aparência das notificações de chamadas e conversas. [Mais informações](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Transferência com consultoria:** De dentro de uma chamada, consulte com outro usuário por meio de uma mensagem Instantânea ou chamada antes de transferir a chamada para o usuário. [Mais informações](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notificações de microfone:** mostre uma notificação na janela da conversa quando o microfone estiver mudo no sistema operacional ou se o microfone não estiver captando nenhum áudio.
-   **Desativação de "Meu número":** use a entrada de registro DisableDisplayMyNumber para desabilitar "Meu número" no teclado de discagem.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Alteração dos botões de lobby usados para admitir ou recusar os participantes do texto para imagens (um X ou uma marca de seleção).
-   Alteração do texto de notificação de lembrete da reunião de "Aceitar" para "Participar".
-   Atualização da mensagem mostrada ao remetente de uma Mensagem Instantânea quando o status do destinatário estiver definido como Não Incomodar.
-   Atualização da mensagem exibida ao remetente de uma Mensagem Instantânea, quando o destinatário estiver offline e "salvar no histórico" estiver desabilitado, para deixar claro que o destinatário não receberá a mensagem.
-   Adição da possibilidade de mover a barra divisória vertical entre o histórico do chat e a lista em um chat de grupo.
-   Adição da possibilidade de redimensionar a lista de guias nas janelas das salas de chat e de mensagens instantâneas.
-   Adição da possibilidade de selecionar as salas de chat pesquisadas ao criar um feed de tópico.
-   Correção de um problema em que as mensagens param de ser exibidas no histórico do meio da conversa do chat.
-   Correção de um problema em que mensagens duplicadas são exibidas na janela da conversa.
-   Correção de um problema em que as ações de notificação do sistema (Aceitar e Ignorar) não são exibidas corretamente durante um alto volume de notificações.
-   Correção de um problema em que o usuário não pode digitar uma mensagem após usar Alt+Tab para abrir uma janela de conversa minimizada.
-   Correção de um problema em que o botão de mensagem instantânea está esmaecido no cartão de visita de um usuário, muito embora as mensagens instantâneas estejam disponíveis.
-   Correção de um problema em que várias janelas de conversas não abrem novamente em seus tamanhos e locais anteriores após serem fechadas e reabertas.
-   Correção de um problema em que os links personalizados não iniciam quando selecionados.
-   Correção de um problema em que o texto da reunião online no campo Região não é exibido corretamente em caracteres que não sejam do inglês.
-   Correção de um problema em que as informações de notificação, como a duração da chamada, não são renderizadas corretamente nos idiomas da direita para a esquerda.
-   Correção de um problema em que, ao criar um feed de tópico, a limpeza dos resultados de pesquisa não redefine os resultados para uma lista de salas visitadas.
-   Correção de um problema em que o Skype for Business trava quando várias janelas de conversação estão abertas ao mesmo tempo.
-   Foi corrigido um problema em que a última janela de conversa fica em branco depois que todas as outras guias são fechadas.
-   Foi corrigido um problema em que o foco padrão não está na área de entrada de chat quando conversas em guias estão desabilitadas.
-   Foi corrigido um problema em que o link "Esqueceu seu PIN de discagem?" não aparece no convite da reunião.
-   Foi corrigido um problema em que texto é recortado e truncado nas páginas de dispositivo de Áudio e Gerais ao serem usados monitores de alto DPI com 175% de exibição ou mais.
-   Foi corrigido um problema em que o Skype for Business falha quando o computador é suspenso ou retomado quando há conexão de rede e o computador é AOAC ("sempre ativado, sempre conectado").
-   Foi corrigido um problema em que nenhum microfone é detectado em uma chamada ao ser usado um dispositivo Polycom CX100.
-   Foi corrigido um problema em que a escolha de um link como \\\\nomedoservidor ou arquivo:// em uma mensagem instantânea resulta em uma mensagem de erro em vez de abrir o local.
-   Foi corrigido um problema em que, em um ambiente VDI (Virtual Desktop Infrastructure) que usa o roteamento baseado em localização, o usuário não pode fazer ou receber chamadas PSTN porque o servidor acha que o local do usuário não é válido para chamadas PSTN.
-   Altere a linha de assunto do email enviado para uma mensagem perdida, quando o status do usuário estiver definido como Não Incomodar ou Apresentando, de "Conversa perdida com \<nome\>"para"\<Nome\> lhe enviou uma mensagem no Skype for Business".
-   Inicia a captura do carimbo de data/hora para a primeira entrada no dispositivo como parte dos [dados de censo](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) para ajudar a identificar tendências de confiabilidade de entrada.
-   Correção de um problema em que a opção de compartilhar um monitor secundário não aparece com determinadas configurações de monitor na versão 1607 do Windows 10 (também conhecida como a Atualização de Aniversário).
-   Correção de um problema em que ocorre uma falha no Skype for Business ao ampliar o conteúdo compartilhado quando o compartilhador está usando uma implementação de terceiros do RDP.
-   Correção de um problema em que o painel Controles de áudio não aparece quando o usuário clica no botão de controles durante uma chamada de áudio em um ambiente VDI (Virtual Desktop Infrastructure).
-   Correção de um problema em que as pessoas visualizam uma tela preta quando o usuário está executando o Windows 7 e compartilha o monitor principal primeiro e, em seguida, alterna para um segundo monitor.
-   Correção de um problema em que determinados caracteres especiais, como o E comercial (&), não podem ser inseridos na caixa de entrada de pesquisa ou na caixa de seção "O que está acontecendo hoje?".
-   Correção de um problema em que a contagem não lida não é mostrada quando há mensagens instantâneas offline perdidas.
-   Correção de um problema em que os modelos "Convidar por email" mencionavam Lync em vez de Skype.
-   Correção de um problema em que falta o número da linha na área "Meu número" abaixo do teclado de discagem.
-   Correção de um problema em que o ponteiro do mouse não é mostrado na área de entrada das mensagens instantâneas após enviar uma mensagem pelo chat.
-   Correção de um problema em que, ao entrar no Skype for Business, ele para e há um problema ao carregar o pool de cache.
-   Correção de um problema em que, ao entrar ou restaurar conversas no Skype for Business, ele falha.
-   Correção de um problema em que, ao entrar após reiniciar o Skype for Business, ele para.
-   Correção de um problema em que o link da reunião é desabilitado se os servidores Exchange em ambas as organizações tiverem o TNEF desabilitado.
-   Correção de um problema em que a chamada de vídeo não pode ser reiniciada se há apenas uma conversa por mensagem instantânea em andamento.
-   Correção de um problema em que as anotações de texto em um quadro de comunicações são perdidas ao salvar o quadro como um arquivo PNG.
-   Correção de um problema em que a primeira linha fica oculta ao inserir mais de duas linhas em japonês na janela de mensagens instantâneas.
-   Correção de um problema em que o caractere E comercial (&) é incorretamente substituído por um caractere sublinhado nos nomes.
-   Correção de um problema com a URL "Participar da reunião online" em uma reunião agendada.
-   Correção de um problema em que ao passar o mouse sobre uma janela não ativa essa janela mesmo que o sistema operacional esteja configurado para fazer isso.
-   Correção de um problema em que os itens do histórico da conversa da chamada de saída mostram quem fez a chamada em vez de mostrar quem a recebeu.
-   Correção de um problema em que o F12 não salva localmente uma conversa.
-   Correção de um problema em que o email da conversa perdida não contém a mensagem instantânea inicial.
-   Correção de um problema em que um emoji pode ser adicionado na área de texto da mensagem instantânea mesmo que o apresentador tenha desabilitado a participação por mensagem instantânea.
-   Correção de um problema com o layout da caixa de diálogo de opções de Toques e Sons.
-   Correção de um problema em que o Skype for Business falha ao fechar a janela de conversa.
-   Correção de um problema em que a entrada com menos DNS falha quando o domínio está registrado como um domínio personalizado.
-   Correção de um problema em que as configurações de notificação de chat persistente não estão sendo salvas ou carregadas corretamente.
-   Correção de um problema em que, após entrar, as janelas de conversa ponto a ponto existentes ou as salas de chat não aparecem, mesmo que a configuração para reabrir as conversas esteja definida.
-   Correção de um problema em que ao ativar ou desativar o mudo na conversa ativa faz com que outras janelas de conversa apareçam como se houvesse mensagens não lidas.
-   Correção de um problema em que os usuários que estão configurados para bypass de mídia não conseguem retomar a chamada de um gateway PSTN após colocarem-na em espera.
-   Correção de um problema em que o usuário vê uma caixa azul em vez do vídeo ao entrar em uma reunião por meio da URL, quando está usando uma implementação RDP de terceiros.
-   Correção de um problema em que é mostrada a parte do usuário do endereço SIP em vez do nome de exibição em um alerta de notificação do sistema.
-   Correção de um problema em que, quando o Skype for Business se conecta a um servidor SIP pela porta 443 e um servidor proxy está presente, há um atraso significativo no processo de entrada se o proxy não permitir tais conexões. A correção é habilitada adicionando a entrada de registro EnableDetectProxyForAllConnections DWORD em HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync e definindo o valor para 1.
-   Correção de um problema em que, ao usar conversas com guias, clicar duas vezes em uma guia e começar a digitar pode fazer com que o foco passe para uma guia diferente e continue a digitação na janela dessa conversa.
-   Correção de um problema em que URLs incluídas em uma mensagem instantânea não podem ser selecionadas na janela de histórico de chat usando o teclado.
-   Correção de um problema em que um som de digitação deve ser ouvido se a caixa de seleção "Reproduzir um som ao exibir uma conversa de mensagem Instantânea e alguém está digitando" é marcada em Opções de Toques e Sons.
-   Correção de um problema em que as caixas de diálogo que aparecem não são anunciadas usando um leitor de tela, como o Narrador.
-   Correção de um problema em que não era possível navegar no tutorial de primeira execução com um teclado e ele não podia ser lido por um leitor de tela, como o Narrador.
-   Correção de um problema em que o ícone de presença de barra de tarefas não é dimensionado nas configurações de DPI Alto.
-   Correção de um problema em que não é possível selecionar o botão limpar campo na caixa de pesquisa usando o teclado.
-   Correção de um problema em que um usuário não pode iniciar uma reunião se o convite é de um usuário em outro pool.
-   Correção de um problema em que um usuário que se adiciona a uma reunião é mostrado incorretamente como um usuário diferente.
-   Correção de um problema em que o ícone de presença do contato na notificação de alteração de status era ocultado para chamadas de entrada para o chefe.
-   Correção de um problema em que a taxa em que o cursor de texto pisca na janela de IM não coincide com as propriedades de teclado definidas no Windows.
-   Correção de um problema em que um leitor de tela anuncia um nome de contato incorreto para uma conversa em grupo.
-   Correção de um problema em que o usuário não pode selecionar vários contatos usando o teclado.
-   Correção de um problema em que as fotos dos usuários não podem ser recuperadas do Exchange.
-   Correção de um problema em que o cliente Skype for Business se conecta a um Servidor Skype for Business na rede interna, em vez de uma rede externa, quando o usuário se conecta usando Acesso Direto.
-   Correção de um problema em que o cliente Skype for Business trava ao tentar resolver o nome do proprietário reunião.
-   Correção de um problema em que a alteração de uma configuração do Windows enquanto o Skype for Business está sendo iniciado ou desligado faz com que o Skype for Business falhe.
-   Correção de um problema em que o Skype for Business trava ao abrir a lista de participantes em uma sala de chat persistente e tentar mover o foco do teclado para a lista de participantes.
-   Correção de um problema em que o Skype for Business falha no reinício, quando não há rede disponível.

### <a name="visio-feature-updates"></a>Visio: Atualizações de recursos
-   **Suplemento de Modelagem de Banco de Dados:** Use o suplemento para criar um modelo de banco de dados de um banco de dados existente para ajudar a planejar um novo banco de dados ou para entender um existente. [Mais informações](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614),[Baixar suplemento](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Melhorias na acessibilidade:** Suporte aprimorado para usar o teclado, o Narrador e outras tecnologias adaptativas para trabalhar com formas, editar com outras pessoas e muito mais.
-   **Diagramas e modelos de terceiros:** procure ou pesquise novos modelos e diagramas de exemplo disponíveis em provedores de conteúdo de terceiros selecionados. O nome do provedor de terceiros está listado na miniatura.
-   **Suporte para escrita à tinta:** Use seu dedo ou uma caneta para desenhar e fazer anotações com as ferramentas da nova guia Desenhar.

### <a name="word-feature-updates"></a>Word: Atualizações de recursos
-   **Melhorias na acessibilidade:** suporte aprimorado no uso do teclado, do Narrator e de outras tecnologias adaptativas para ler e editar documentos. [Mais informações](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Editor:** fornece um revisor de texto contextual avançado para ajudar a melhorar a escrita do usuário. [Mais informações](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Reprodução de tinta:** vá para Desenhar \> Reprodução de tinta para reproduzir manuscritos para frente e para trás, a fim de ocultar e revelar conteúdo, fornecer instruções passo a passo ou entender melhor o fluxo de pensamento de outras pessoas.[Mais informações](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Editar com gestos de caneta naturais:** faça alterações em um documento circulando para selecionar e cruzando para excluir. [Mais informações](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Compartilhado comigo:** Para ver os documentos que outras pessoas compartilharam com você, vá para Arquivo \> Abrir \> Compartilhado comigo. [Mais informações](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Alterar cores:** Use Diga-me para definir a cor para a fonte, realce, preenchimento de forma e muito mais. [Mais informações](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um erro em que a visualização de um documento no Modo de Leitura evita que a tecla Tab funcione em um segundo documento que esteja sendo visualizado no Layout de Impressão.
-   Foi corrigido um problema em que o Word trava quando mais de uma biblioteca de gramática é carregada.
-   Correção de um problema em que traços de tinta desaparecem após dois ou três traços.
-   Correção de um problema em que as aspas desaparecem ao usar o editor de método de entrada (IME) do Google.
-   Correção de um problema em que um usuário não pode usar tinta com controles de conteúdo ou quando são feitas seleções não contíguas.

### <a name="office-suite-feature-updates"></a>Pacote do Office: Atualizações de recursos
-   **Faça comentários:** Vá para Arquivo \> Comentários e faça sugestões de novos recursos ou fale com a Microsoft sobre os recursos que não funcionam ou os que agradam a você

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Atualização de segurança do Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema em que usar Ctrl+Alt+7 ou Ctrl+Alt+8 em um teclado alemão abre as ferramentas de feedback do usuário, em vez de inserir o caractere apropriado.
-   Correção de um problema em que TraceLogging causa uma falha no Windows 7 ao instalar ou atualizar o Office.
-   Foi corrigido um problema em que, ao se desenhar à tinta e usar um mouse, soltar o botão do mouse faz com que a tinta se desloque um pouco.
-   Foi corrigido um problema em que após a inserção de uma imagem SVG em um documento do Office, a imagem SVG desaparece quando o documento é salvo e aberto novamente.
-   Para corrigir um problema onde o Office mostra a seguinte mensagem de erro durante a ativação para os usuários não estão em inglês: "o comprimento máximo da chave do produto é de 25 caracteres."
-   Correção de um problema com formulários do VBA que podem fazer com que a ordem z de quadros pare de funcionar ou seja exibida incorretamente.
-   Correção de um problema em que uma atualização acionada pelo System Center Configuration Manager altera a configuração do UpdateChannel no registro para algo que não é um canal de atualização válido.



## <a name="version-1609-january-10"></a>Versão 1609: 10 de janeiro
*Versão 1609 (build 7369.2102)*

Observação: As atualizações de segurança abordadas no boletim de segurança da Microsoft [MS17-002](https://technet.microsoft.com/library/security/ms17-002) não se aplicam à versão do Word nesta versão de canal.

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que usar uma caixa de diálogo Editar Medida causa uma falha no Excel.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema em que trabalhar com formas, às vezes, causa uma falha no PowerPoint.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Correção de um problema em que a opção de compartilhar um monitor secundário não aparece com determinadas configurações de monitor na versão 1607 do Windows 10 (também conhecida como a Atualização de Aniversário).
-   Correção de um problema em que ocorre uma falha no Skype for Business ao ampliar o conteúdo compartilhado quando o compartilhador está usando uma implementação de terceiros do RDP.
-   Correção de um problema em que, quando o Skype for Business se conecta a um servidor SIP pela porta 443 e um servidor proxy está presente, há um atraso significativo no processo de entrada se o proxy não permitir tais conexões. A correção é habilitada adicionando a entrada de registro EnableDetectProxyForAllConnections DWORD em HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync e definindo o valor para 1.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao usar o método InsertXML, um espaço reservado para um link de imagem desfeito é exibido no lugar de uma imagem real.


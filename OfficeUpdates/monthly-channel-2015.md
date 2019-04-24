---
title: Notas de versão para lançamentos de canais mensais no 2015
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/11/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Fornece notas de versão aos profissionais de ti para lançamentos de canais mensais do Office 365 proPlus em 2015
ms.openlocfilehash: 0b235ba177dd2378cbb953315e2ead6b692ed52b
ms.sourcegitcommit: 358a0cbd1b722d309556c50d53abbe6c1a348f60
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32438799"
---
# <a name="release-notes-for-monthly-channel-releases-in-2015"></a>Notas de versão para lançamentos de canais mensais no 2015

Estas notas de versão fornecem informações sobre novos recursos, atualizações de segurança e atualizações que não são de segurança incluídas nas atualizações do canal mensal para o Office 365 proPlus em 2015.
 
> [!NOTE]
> - A seguir, fornecemos informações sobre recursos, atualizações de segurança e outras atualizações não relacionadas à segurança para Visio Pro para Office 365 e Project Online Desktop Client.
> - Essas informações também se aplicam ao Office 365 Business, versão do Office que acompanha alguns planos do Office 365, como o Business Premium.
> - O canal mensal era chamado de canal atual antes de setembro de 2017.

## <a name="version-1511-december-11"></a>Versão 1511:11 de dezembro
*Versão 1511 (build 6366.2036)*

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
-   **Modelos de BI:** Três novos modelos que aproveitam os recursos de BI (Business Intelligence) do Excel: insights de [calendário](https://support.office.com/article/7edbeb88-99ca-403f-a394-7e957d3d3f40), [análise de ações](https://support.office.com/article/f65e62ac-7af6-4cc6-98f3-f68b147ed65d), [meu](https://support.office.com/article/215e9e2e-5813-41ad-a9ef-a0c0874841bb) fluxo de trabalho

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que arrastar a alça de preenchimento de uma célula formatada com um número como data completa causa uma falha no Excel.
-   Correção de um problema em que criar uma Tabela Dinâmica ou um Gráfico Dinâmico a partir de uma conexão de dados e colocá-los em uma nova planilha causa uma falha no Excel.
-   Correção de um problema que faz com que os botões de filtro para um gráfico dinâmico não fiquem visíveis quando não houver nenhuma filtragem nos campos da tabela dinâmica subjacentes.
-   Correção de um problema que faz com que o Modelo de Dados seja perdido ao fechar o Excel antes de salvar quando há uma pasta de trabalho pessoal de macros oculta.
-   Correção de um problema em que editar uma planilha com um gráfico de mapa de árvore em uma versão do Excel 2016 anterior à versão em que a planilha foi criada faz com que o gráfico de mapa de árvore perca os seus dados.

### <a name="onenote-feature-updates"></a>OneNote: Atualizações de recursos
-   **Inserir vídeos online:** Inserir vídeos do YouTube, do OfficeMix ou do Vimeo em uma página. [Mais informações](https://support.office.com/article/0a862f29-665c-43a5-9dd8-68009423cf7c)

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações que não são de segurança
-   Correção de um problema no Office 365 Business no qual usar o OneNote com o SharePoint resulta em uma mensagem de erro que informa aos usuários que eles têm que atualizar para uma versão diferente do Office.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recursos
-   **Calendário persa:** Adicione o calendário persa como um calendário principal ou alternativo.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança
-   Correção de um problema em que arrastar a barra de rolagem na lista de mensagens faz avançar para o final da lista.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recursos
-   **Transição Transformar:** crie transições perfeitas entre slides e dê movimento às apresentações para transmitir conceitos e informações de maneira mais eficaz. [Mais informações](https://support.office.com/article/8dd1c7b2-b935-44f5-a74c-741d8d9244ea)
-   **Designer do PowerPoint:** um novo serviço que permite que você pegue o seu conteúdo e crie automaticamente várias ideias que podem ser escolhidas para melhorar a aparência de seus slides. [Mais informações](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

    Este serviço requer conectividade com a Internet. Para desabilitar esse recurso, [use os arquivos mais recentes do modelo administrativo da política de grupo](https://www.microsoft.com/download/details.aspx?id=49030) e habilite a configuração opções do designer do PowerPoint. Você pode encontrar esta configuração de política em Configurações do Usuário\\Modelos Administrativos\\Microsoft Office 2016\\Ferramentas | Opções | Geral | Opções de Serviço…\\Designer do PowerPoint.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações que não são de segurança
-   Correção de um problema que faz com que as animações SmartArt não sejam mostradas na sequência esperada no modo de exibição Apresentação de Slides com o modo de exibição do apresentador.
-   Correção de um problema que faz com que a navegação com as teclas numéricas não funcione no modo de exibição de Apresentação de Slides.

### <a name="visio-non-security-updates"></a>Visio: Atualizações que não são de segurança
-   Correção de um problema que faz com que os arquivos do AutoCAD visualizados no Visio apareçam desfocados.

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema em que os documentos não podem ser salvos em uma biblioteca de documentos que exige uma coluna.

### <a name="office-suite-feature-updates"></a>Pacote do Office: Atualizações de recursos
-   **Opções de enviar como**: Envie um documento como um anexo ou como um PDF no painel Compartilhar no Word ou no PowerPoint.
-   **Inserir API de Imagem**: insira imagens no Word, no Excel ou no PowerPoint usando o [método document.setSelectedDataAsync](https://msdn.microsoft.com/library/office/fp142145.aspx) na biblioteca comum do office.js. A API JavaScript do Word fornece métodos específicos de host chamados insertInlinePictureFromBase64 () para definir imagens embutidas nos objetos [Body](https://msdn.microsoft.com/library/office/mt598674.aspx), [ContentControl](https://msdn.microsoft.com/library/office/mt598675.aspx), [Paragraph](https://msdn.microsoft.com/library/office/mt598682.aspx)e Range.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Correção de um problema que faz com que as informações da Data de Modificação exibidas sejam truncadas ao executar a função Abrir ou Salvar como.
-   Correção de um problema que faz o aplicativo falhar quando alguém clica duas vezes no painel Texto dos elementos gráficos SmartArt.
-   Correção de um problema que faz o vídeo reproduzido durante a instalação permanecer em uma tela preta depois de terminar e até a caixa de diálogo "A instalação foi concluída" ser fechada.
-   Correção de um problema que faz com que uma notificação fique escondida por um botão de rolagem muito grande quando se passa o mouse sobre a notificação de "Modo de exibição protegido" em um documento protegido.
-   Correção de um problema em que uma notificação de atualização do Office agendada aparece truncada em cazaque e húngaro.
-   Correção de um problema em que os atalhos fixados na barra de tarefas não são removidos para todos os usuários durante uma atualização manual.
-   Correção de um problema em que as falhas causadas por ações relacionadas a licenciamento durante uma atualização automática deixam o usuário sem uma instalação do Office.
-   Correção de um problema em que atualizar o Office 2016 em um computador com o Windows 7 OEM que tenha executado o Kit de Pré-instalação em modo de auditoria resulta no erro 0x80070005 durante a ativação.


## <a name="version-1509-december-8"></a>Versão 1509:8 de dezembro
*Versão 1509 (build 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações não relacionadas à segurança
-   Correção de um problema que faz com que impressões ou XPS criados usando o cliente Windows de área de trabalho apareçam como um X vermelho para clientes Windows que não sejam de área de trabalho, pois esses clientes não dão suporte à renderização XPS nativa.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações que não são de segurança
-   Correção de um problema que faz com que um indicador que se estende por vários parágrafos seja criado, mas quando o email é recebido, somente o primeiro parágrafo do indicador é selecionado ao usar Ir Para.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-128](https://go.microsoft.com/fwlink/?LinkId=690559): atualização de segurança do componente do Microsoft Graphics para tratar da execução de código remoto (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Correção de um problema que causa falha nas sessões de compartilhamento de aplicativo, especialmente durante períodos de tráfego intermitente.
-   Correção de um problema que causa falha no Skype for Business se ele for o primeiro aplicativo iniciado depois de instalar o Office 2016.

### <a name="word-security-updates"></a>Word: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-131](https://go.microsoft.com/fwlink/?LinkId=699410): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3116111)

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema que mostra o hífen não separável como um quadrado ao usar algumas fontes.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Alteração do transporte padrão para baixar atualizações em segundo plano do Cache/BITS para HTTP.
-   Correção de um problema em que as falhas causadas por ações relacionadas a licenciamento durante uma atualização automática deixam o usuário sem uma instalação do Office.
-   Correção de um problema em que atualizar o Office 2016 em um computador com o Windows 7 OEM que tenha executado o Kit de Pré-instalação em modo de auditoria resulta no erro 0x80070005 durante a ativação.



## <a name="version-1509-november-10"></a>Versão 1509:10 de novembro
*Versão 1509 (build 6001.1038)*

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que gravar uma macro para criar uma consulta resulta em um erro de compilação.
-   Correção de um problema em que, após excluir uma coluna no Editor de Consultas, uma coluna em branco aparece no final da tabela depois de atualizar a consulta.
-   Correção de um problema em que um erro inesperado ocorre ao escolher a guia Minigráficos na Análise Rápida de uma tabela de consulta.
-   Correção de um problema em que, após realizar uma operação de cortar e colar em uma tabela de consulta, não é possível atualizar a consulta usando o painel Consultas da Pasta de Trabalho.
-   Correção de um problema em que, ao atualizar uma consulta, o foco é movido para a planilha da tabela de consulta associada.
-   Remoção da referência ao Power Query da mensagem de erro sobre versões do OData com suporte.
-   Correção de um problema em que os recursos do Power Query aparecem como disponíveis, mas não funcionam quando o produto não está ativado.
-   Atualização da URL para Dotlesscss em Arquivo \> Conta \> Sobre o Excel.

### <a name="onenote-security-updates"></a>OneNote: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança
-   Correção de um problema em que colar texto no Outlook não exibe o texto completo se a quantidade de texto colado for maior que a altura da janela.

### <a name="powerpoint-security-updates"></a>PowerPoint: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="project-security-updates"></a>Project: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="publisher-security-updates"></a>Publisher: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="skype-for-business-security-updates"></a>Skype for Business: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)
-   Boletim de Segurança da Microsoft [MS15-123](https://technet.microsoft.com/library/security/ms15-123): atualização de segurança do Skype for Business e Microsoft Lync para tratar da divulgação de informações (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Correção de um problema de ruído no áudio em dispositivos com dois microfones de entrada.
-   Correção de um problema em que os usuários não conseguem ingressar em uma reunião após retirar um laptop do modo de suspensão e antes de o cliente do Skype entrar novamente.
-   Adição de suporte para mensagens contextuais para ajudar a gerar conscientização sobre os recursos para os usuários.
-   Atualização do texto na caixa de diálogo Ingressar no Áudio da Reunião para direcionar os usuários para o local correto na IU para alterar as configurações.
-   Correção de um problema com as notificações que os usuários veem ao enfrentarem problemas de rede no envio e recebimento.

### <a name="visio-security-updates"></a>Visio: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema em que a numeração da nota de rodapé não corresponde entre a exibição no Word e a cópia impressa quando um documento que tem notas de rodapé definidas como "Reiniciar a numeração de cada página" for impresso em segundo plano.
-   Correção de um problema em que a coautoria em tempo real não funciona com arquivos armazenados no OneDrive, incluindo a não exibição do usuário para outros usuários ao editar em tempo real e a falta de informações disponíveis.
-   Correção de um problema em que o Word falha durante a coautoria em tempo real em um documento aberto a partir do SharePoint ou do OneDrive.
-   Correção de um problema de formatação que faz com que as tabelas renderizem incorretamente ao serem colocadas em emails HTML no Outlook e a janela for redimensionada.

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Atualização de Segurança do Microsoft Office para Tratar da Execução de Código Remoto (3104540)

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Correção de um problema em que o usuário é repetidamente solicitado a entrar ao tentar abrir arquivos a partir do SharePoint Online.
-   Correção de um problema em que os atalhos fixados na barra de tarefas não são removidos para todos os usuários durante uma atualização manual.
-   Adição ao processo de atualização manual do Clique para Executar da capacidade de detectar se o Outlook está conectado ao Exchange Server 2007 ou se o Business Contact Manager está instalado para avisar os usuários sobre possíveis problemas com a atualização.
-   Capacidade das caixas de diálogo encerrarem processos mais visíveis durante uma desinstalação ou atualização porque essas caixas de diálogo podem ficar ocultas atrás de aplicativos abertos ou uma outra IU.
-   Correção de um problema em que um usuário não entra automaticamente em um aplicativo do Office ao usar um computador identificado como sendo ingressado em um domínio e em um domínio na nuvem.



## <a name="version-1509-october-21"></a>Versão 1509:21 de outubro
*Versão 1509 (build 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações não relacionadas à segurança
-   Correção de um problema que faz o OneNote falhar quando a mesma cor é selecionada duas vezes para uma borda no seletor de cores.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações que não são de segurança
-   Correção de um problema em que um leitor de tela lê somente o primeiro parágrafo de uma assinatura de email com vários parágrafos ao editar a assinatura de email.
-   Correção de um problema em que o cursor não está na posição correta ao escrever ou responder a um email.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Correção de um problema em que, em condições de memória insuficiente, tentar visualizar um aplicativo ou área de trabalho compartilhada resulta em desconexão e em repetidas tentativas de reingressar automaticamente e visualizar o aplicativo ou área de trabalho compartilhada.
-   Correção de um problema que faz com que a experiência de área de trabalho compartilhada perca qualidade com o aumento no número de participantes.
-   Correção de um problema que faz com que avisos repetidos de autenticação de telefone sejam recebidos durante o dia quando a autenticação multifator está configurada.

### <a name="visio-non-security-updates"></a>Visio: Atualizações que não são de segurança
-   Correção de um problema em que um objeto do Word inserido para ser exibido como um ícone está vazio após fechar e reabrir o Visio.

### <a name="word-non-security-updates"></a>Word: Atualizações que não são de segurança
-   Correção de um problema em que a coautoria não está disponível e o documento pode ser bloqueado quando o documento está no SharePoint Server 2013.
-   Correção de um problema em documentos .docx nos quais a tabela é visível, embora o conteúdo da tabela tenha um estilo aplicado a ele que inclua a opção Oculto.
-   Correção de um problema em que os documentos com hiperlinks relativos não podem ser salvos após executar uma correção automática.
-   Correção de um problema que faz as linhas se moverem durante a edição de um parágrafo em um documento com recuos espelhados.
-   Correção de um problema que faz a linha ser exibida inconsistentemente durante a edição quando o posicionamento do subpixel é desabilitado.
-   Correção de um problema em que clicar em um pop-up de comentário com vários comentários quando o primeiro está marcado como Concluído causa uma falha.
-   Correção de um problema com quebra de linha incorreta.
-   Correção de um problema que causa uma falha ao executar uma macro que usa a função TransformDocument em um documento com uma caixa de texto em um cabeçalho ou rodapé.
-   Correção de um problema com documentos .docm que causa erros ao remover os controles ActiveX quando o documento é aberto.
-   Correção de um problema que faz o evento ContentControlOnExit não ser disparado ao clicar em um cabeçalho.
-   Correção de um problema que faz o recurso Controlar alterações mostrar exclusões de revisores com o mesmo nome.
-   Correção de um problema com a coautoria em tempo real de documentos configurados para removerem informações pessoais, que faz com que as alterações sejam exibidas como alterações controladas todas vezes que o documento é salvo.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Correção de um problema que faz com que, ao abrir um aplicativo do Office pela primeira vez depois de atualizar para o 2016, o aplicativo funcione no modo de funcionalidade reduzida e precise ser reiniciado para obter todas as funcionalidades.
-   Correção de um problema em que executar o Office com a ativação de computador compartilhado habilitada em um computador que execute os Serviços de Área de Trabalho Remota resulta em um erro, exibido ao abrir um aplicativo, que diz ao usuário que ele precisa usar uma edição de licenciamento por volume do Office.
-   Correção de um problema que faz a instalação parar quando aproximadamente 90% dela está concluída.
-   Correção de um problema em que os nomes dos produtos estão localizados, mas eles não deveriam estar.
-   Correção de um problema em que a dica de ferramenta e a dica de tecla do recurso "Diga-Me" não coincidem e entram em conflito com outras dicas de tecla na faixa de opções em várias versões localizadas.
-   Correção de um problema que faz o Windows mostrar o Outlook como um novo aplicativo após uma atualização do Office 2013 para Office 2016.
-   Correção de um problema que causa o erro 0x80041015 ao atualizar da versão 15.0.4615.1002 do Office 2013 (maio de 2014) para o Office 2016.



## <a name="version-1509-october-5"></a>Versão 1509:5 de outubro
*Versão 1509 (build 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações não relacionadas à segurança
-   Correção de um problema no Office 365 Business no qual usar o OneNote com o SharePoint resulta em uma mensagem de erro que informa aos usuários que eles têm que atualizar para uma versão diferente do Office.
-   Correção de um problema no Surface Pro 3 em que a visualização de gravação de vídeo não exibe o que está sendo gravado.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações que não são de segurança
-   Alteração daquilo que o visualizador vê quando o participante do compartilhamento bloqueia a tela no RDP. Agora o visualizador vê uma notificação em vez da imagem de pausa RDP.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações que não são de segurança
-   Correção de um problema do Clique para Executar em que o serviço Clique para Executar do Office 2013 não é restaurado se a atualização automática do Office 2016 não for concluída devido a um erro ou cancelamento pelo usuário.
-   Correção de problemas do Clique para Executar em que uma falha durante a atualização automática para o Office 2016 resulta em uma falha na atualização que não permite usar ou desinstalar os aplicativos do Office 2013.
-   Correção de um problema de Clique para Executar em que tentar novamente a atualização automática do Office 2016 após reiniciar durante uma tentativa anterior resulta em uma falha na atualização e na incapacidade de desligar.
-   Correção de um problema do Clique para Executar em que a tarefa Fluxo não consegue recuperar durante a instalação se o computador for reiniciado.
-   Correção de um problema do Clique para Executar em que reiniciar durante uma atualização manual do Office 2016 deixa tarefas no estado "em execução".
-   Correção de um problema do Clique para Executar em que iniciar um aplicativo recém-instalado no meio do processo de instalação resulta na exibição da caixa de diálogo "A conexão com a Internet foi perdida".
-   Correção de um problema do Clique para Executar em que os blocos de aplicativo exibidos durante a instalação não estão ativos e não iniciam o aplicativo quando os usuários clicam no bloco do aplicativo.
-   Correção de um problema do Clique para Executar em que a atualização automática de uma instalação sr-latn-cr do Office 2016 não converte o idioma do cliente para sr-latn-rs.
-   Correção de um problema do Clique para Executar em que a atualização automática falha ao preparar a atualização quando há vários SKUs do Office instalados no computador.
-   Correção de um problema do Clique para Executar em que as caixas de diálogo de erro são exibidas se uma atualização manual for iniciada enquanto uma atualização automática estiver em execução.
-   Atualização de referências para "Suplementos" na IU do produto onde o uso de maiúsculas do termo estiver incorreto.



## <a name="version-1509-september-22"></a>Versão 1509:22 de setembro
*Versão 1509 (build 4229.1024)*

Esta é a versão inicial para este canal. Esta versão oferece a primeira disponibilidade dos aplicativos do Office 2016.

### <a name="excel-security-updates"></a>Excel: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-099](https://technet.microsoft.com/library/security/ms15-099): vulnerabilidades do Microsoft Office poderão permitir a execução remota de código (3089664)
-   Boletim de Segurança da Microsoft [MS15-110](https://technet.microsoft.com/library/security/ms15-110): atualizações de segurança do Microsoft Office para tratar da execução de código remoto (3096440)

### <a name="visio-security-updates"></a>Visio: Atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades do Microsoft Office poderão permitir a execução remota de código (3080790)

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades do Microsoft Office poderão permitir a execução remota de código (3080790)

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   Boletim de Segurança da Microsoft [MS15-081](https://technet.microsoft.com/library/security/ms15-081): vulnerabilidades do Microsoft Office poderão permitir a execução remota de código (3080790)
-   Boletim de Segurança da Microsoft [MS15-099](https://technet.microsoft.com/library/security/ms15-099): vulnerabilidades do Microsoft Office poderão permitir a execução remota de código (3089664)

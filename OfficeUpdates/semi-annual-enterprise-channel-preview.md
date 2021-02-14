---
title: Notas de versão para lançamentos do Canal Empresarial Semestral em 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI notas de versão dos lançamentos do canal semestral (direcionado) do Microsoft 365 Apps em 2020
ms.openlocfilehash: bc3878099fa34b75437ce800250d711cb0f5bd0c
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173830"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="8fa33-103">Notas de versão para lançamentos do Canal Empresarial Semestral (Pré-visualização)</span><span class="sxs-lookup"><span data-stu-id="8fa33-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="8fa33-104">Estas notas de versão fornecem informações dos novos recursos e atualizações não relacionados à segurança que estão inclusos nas atualizações do Canal Empresarial Semestral (Pré-visualização) do Microsoft 365 Apps para Pequenos e Médios Negócios, Microsoft 365 Apps para Grandes Empresas e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="8fa33-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="8fa33-105">Estamos fazendo algumas alterações nos canais de atualização para o Microsoft 365 Apps, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="8fa33-106">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="8fa33-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-february-09"></a><span data-ttu-id="8fa33-107">Versão 2008: 09 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="8fa33-107">Version 2008: February 09</span></span>
<span data-ttu-id="8fa33-108">*Versão 2008 (Build 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-108">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="8fa33-109">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-111">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-112">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-112">Excel</span></span>

- <span data-ttu-id="8fa33-113">Corrigido um problema em que o Excel fechava inesperadamente ao abrir arquivos UNC com atributos de arquivo inválidos (data de criação, data de modificação, etc.)</span><span class="sxs-lookup"><span data-stu-id="8fa33-113">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="8fa33-114">Corrigido um problema em que as configurações decimais e de milhares de separadores não eram transferidas ao copiar um gráfico do Excel e colar no Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-114">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="8fa33-115">Corrigimos um problema onde o desempenho da execução de uma macro envolvendo a formatação de intervalo da Tabela Dinâmica se agravaria a cada vez que a macro fosse executada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-115">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="8fa33-116">Corrigimos um problema em que as regras de formatação condicional eram descartadas ao copiar ou mover planilhas para outra pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="8fa33-116">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="8fa33-117">Corrigimos um problema em que os usuários não podiam aplicar rótulos de confidencialidade aos arquivos do Excel quando a tela inicial da inicialização do aplicativo estava desabilitada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-117">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="8fa33-118">Corrigimos um problema ao abrir um arquivo na nuvem a partir da pasta de Sincronização do Microsoft OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-118">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-119">Outlook</span></span>

- <span data-ttu-id="8fa33-120">Corrigido um problema que fazia com que o Outlook parasse de funcionar esporadicamente ao adicionar ou salvar anexos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-120">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-121">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-121">PowerPoint</span></span>

- <span data-ttu-id="8fa33-122">Corrigimos um problema em que o comando de tamanho de fonte, adicionado ao QAT, completava automaticamente para o tamanho de fonte definido mais próximo ao atualizá-lo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-122">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="8fa33-123">Corrigido um problema onde copiar e colar um slide com a opção "manter a formatação da fonte" às vezes copiava inesperadamente sobre um novo slide mestre.</span><span class="sxs-lookup"><span data-stu-id="8fa33-123">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="8fa33-124">Palavra</span><span class="sxs-lookup"><span data-stu-id="8fa33-124">Word</span></span>

- <span data-ttu-id="8fa33-125">Corrigimos um problema no Controle de Alterações que às vezes a abertura de um documento do Word exibia uma caixa de diálogo de erro.</span><span class="sxs-lookup"><span data-stu-id="8fa33-125">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="8fa33-126">Corrigimos um problema ao abrir um arquivo na nuvem a partir da pasta de Sincronização do Microsoft OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-126">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8fa33-127">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-127">Office Suite</span></span>

- <span data-ttu-id="8fa33-128">Corrigido um problema que impedia a abertura bem-sucedida de um arquivo no Office.</span><span class="sxs-lookup"><span data-stu-id="8fa33-128">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="8fa33-129">Corrigido um problema onde documentos contendo contornos de esboços aplicados aos conectores por meio do Pincel de Formatação poderiam se corromper.</span><span class="sxs-lookup"><span data-stu-id="8fa33-129">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2008-january-12"></a><span data-ttu-id="8fa33-131">Versão 2008: 12 de janeiro</span><span class="sxs-lookup"><span data-stu-id="8fa33-131">Version 2008: January 12</span></span>
<span data-ttu-id="8fa33-132">*Versão 2008 (Build 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-132">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="8fa33-133">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-133">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-135">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-136">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-136">Excel</span></span>

- <span data-ttu-id="8fa33-137">Corrigido um problema em que os livros somente leitura não atualizavam mais os dados da tabela dinâmica quando abertos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-137">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="8fa33-138">Essa alteração fornece uma correção para o seguinte problema: Excel "Inserir Objeto" não mostra o ícone correto ao inserir um arquivo da pasta de sincronização local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-138">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="8fa33-139">Corrigido um problema em que os clientes eram notificados incorretamente sobre uma nova versão do arquivo durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="8fa33-139">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="8fa33-140">Corrigido um problema de edição em que o uso de IME com o modo Substituir avançava caracteres extras incorretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-140">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="8fa33-141">Corrigido um problema ao usar dados em tempo real em conjunto com a funcionalidade recalc multithread.</span><span class="sxs-lookup"><span data-stu-id="8fa33-141">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="8fa33-142">Corrige um problema em que o Excel falhava ao iniciar ou fechava inesperadamente se certas configurações de proteção contra exploits de Segurança do Windows (SimExec, CallerCheck) estivessem em uso</span><span class="sxs-lookup"><span data-stu-id="8fa33-142">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-143">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-143">Outlook</span></span>

- <span data-ttu-id="8fa33-144">Corrigimos um problema que fazia com que os SmartLinks perdessem a formatação quando salvos em rascunhos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-144">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="8fa33-145">Corrigimos um problema para fornecer a um usuário uma maneira de personalizar o texto de justificação ao substituir uma política.</span><span class="sxs-lookup"><span data-stu-id="8fa33-145">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="8fa33-146">Corrigimos um problema que fazia com que os caracteres chineses fossem alterados para pontos de interrogação ao salvar como um arquivo OFT.</span><span class="sxs-lookup"><span data-stu-id="8fa33-146">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-147">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-147">PowerPoint</span></span>

- <span data-ttu-id="8fa33-148">Corrigimos um problema de VBA em que Slide.Shapes.AddMediaObject2 fechava inesperadamente com formatos de vídeo legados (MPG-1, Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="8fa33-148">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="8fa33-149">Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-149">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="8fa33-150">Projeto</span><span class="sxs-lookup"><span data-stu-id="8fa33-150">Project</span></span>

- <span data-ttu-id="8fa33-151">Corrigido um problema em que o Microsoft Project podia ser encerrado inesperadamente ao abrir arquivos em que os contornos dos recursos foram especificados de uma determinada maneira.</span><span class="sxs-lookup"><span data-stu-id="8fa33-151">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="8fa33-152">Skype</span><span class="sxs-lookup"><span data-stu-id="8fa33-152">Skype</span></span>

- <span data-ttu-id="8fa33-153">Corrige um problema em que o certificado TLS-DSK de um usuário não era renovado no horário esperado, em vez de renovar apenas quando faltavam menos de 12 horas para sua validade.</span><span class="sxs-lookup"><span data-stu-id="8fa33-153">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="8fa33-154">Corrige um problema em que a interface do usuário do Skype for Business aparece em branco depois de entrar quando o Office ainda não está licenciado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-154">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8fa33-155">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-155">Office Suite</span></span>

- <span data-ttu-id="8fa33-156">Essa alteração aborda um problema relacionado à abertura de arquivos contendo diagramas legados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-156">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="8fa33-157">Essa alteração soluciona um problema com o proxy substituto SVG que resulta em violações de acesso.</span><span class="sxs-lookup"><span data-stu-id="8fa33-157">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-2008-december-08"></a><span data-ttu-id="8fa33-159">Versão 2008: 8 de setembro</span><span class="sxs-lookup"><span data-stu-id="8fa33-159">Version 2008: December 08</span></span>
<span data-ttu-id="8fa33-160">*Versão 2008 (Build 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-160">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="8fa33-161">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-161">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-163">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-163">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8fa33-164">Access</span><span class="sxs-lookup"><span data-stu-id="8fa33-164">Access</span></span>

- <span data-ttu-id="8fa33-165">Corrigimos um problema de erro ao tentar usar o construtor de DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="8fa33-165">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="8fa33-166">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-166">Excel</span></span>

- <span data-ttu-id="8fa33-167">Correção de um problema em que as tabelas dinâmicas não poderiam ser editadas e as pastas de trabalho não poderiam ser salvas se tivessem sido exportadas do plano de projeto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-167">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="8fa33-168">Corrigimos um problema onde, em alguns casos, várias barras de mensagens apareciam quando um arquivo fosse aberto no modo somente leitura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-168">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="8fa33-169">Corrigimos um problema em que os subtotais de tópicos poderiam parar de funcionar quando houvesse muitos valores de cabeçalho de coluna duplicados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-169">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="8fa33-170">Corrigimos um problema em que o Excel parava de funcionar quando houvesse uma atualização de objeto de política de grupo (por exemplo, através da atualização de política de grupo remoto) durante o recálculo de vários threads.</span><span class="sxs-lookup"><span data-stu-id="8fa33-170">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="8fa33-171">Corrigimos um problema em que o Excel parava de funcionar quando os usuários usassem a função de subtotal em mais de 255 colunas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-171">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="8fa33-172">Melhor kerning de texto no PowerPoint quando o conteúdo é copiado do Excel e colado no PowerPoint com a opção embed.</span><span class="sxs-lookup"><span data-stu-id="8fa33-172">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="8fa33-173">Correção de um problema que impedia a mudança da visualização da tabela e do editor de consulta no PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="8fa33-173">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="8fa33-174">Corrigimos um problema em que um usuário não poderia abrir diretamente um arquivo atomsvc (UTF8+BOM) do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8fa33-174">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="8fa33-175">Corrigimos um problema em que o PowerPivot agora reconhecerá com êxito o delimitador de tabulação.</span><span class="sxs-lookup"><span data-stu-id="8fa33-175">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-176">Outlook</span></span>

- <span data-ttu-id="8fa33-177">Corrigimos um problema que fazia com que o campo para: ficasse vazio ao enviar um relatório de status em uma Tarefa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-177">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="8fa33-178">Corrigimos um problema que causava a interrupção do evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="8fa33-178">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="8fa33-179">Corrigimos um problema que estava fazendo com que alguns usuários experimentassem o aplicativo para fechar inesperadamente ao enviar emails do Outlook de aplicativos diferentes do Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-179">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="8fa33-180">Corrigimos um problema que fazia com que os usuários experimentassem o desempenho reduzido ao mover vários itens de email entre pastas no modo online.</span><span class="sxs-lookup"><span data-stu-id="8fa33-180">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="8fa33-181">Adicionamos uma regkey que permite que os clientes desabilitem a inclusão de filetime para anexos nas operações do IDataObject (ou seja, arrastar e soltar, área de transferência).</span><span class="sxs-lookup"><span data-stu-id="8fa33-181">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="8fa33-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject 0 = filetimes são excluídos 1 = (padrão) os tempos de inclusos são incluídos</span><span class="sxs-lookup"><span data-stu-id="8fa33-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="8fa33-183">Corrigimos um problema que fazia com que as imagens embutidas desaparecessem ao responder a uma mensagem com um rótulo de proteção da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="8fa33-183">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="8fa33-184">Corrigimos um problema que fazia com que o nome de usuário fosse exibido como um número de telefone ao enviar uma caixa postal protegida do Azure, fazendo com que os usuários da área de trabalho do Outlook não consiguissem abrir a caixa postal de usuários externos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-184">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="8fa33-185">Corrigido um problema em que a configuração da configuração do OME estava adicionando anexos estranhos no item de email que forçava o Outlook a criptografar a mensagem, embora a opção DecryptAttachmentsForEncryptOnly tivesse sido configurada no lado do serviço.</span><span class="sxs-lookup"><span data-stu-id="8fa33-185">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-186">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-186">PowerPoint</span></span>

- <span data-ttu-id="8fa33-187">Consertamos um problema em que o gráfico vinculado do Excel se altera incorretamente para a planilha do Excel quando o usuário altera o caminho de origem para a pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-187">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="8fa33-188">Corrigimos um problema devido à qual o recurso 'Bem-vindo de volta!</span><span class="sxs-lookup"><span data-stu-id="8fa33-188">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="8fa33-189">Retome de onde você parou no Office' não estava funcionando no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-189">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="8fa33-190">Visio</span><span class="sxs-lookup"><span data-stu-id="8fa33-190">Visio</span></span>

- <span data-ttu-id="8fa33-191">Corrigimos um problema em que os usuários poderão criar linhas retas usando conectores no Visio para Office 365 para estênceis personalizados do Visio e modelos internos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-191">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="8fa33-192">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-192">Word</span></span>

- <span data-ttu-id="8fa33-193">Resolvemos um problema no qual os links longos não eram dispostos ao salvar um documento no formato HTML.</span><span class="sxs-lookup"><span data-stu-id="8fa33-193">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="8fa33-194">Corrigimos um problema em que, se você responder a um comentário pai que tenha extensões desconhecidas em uma lista de extensões, a resposta receberá essas mesmas extensões.</span><span class="sxs-lookup"><span data-stu-id="8fa33-194">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="8fa33-195">Corrigimos um problema no Outlook com a mensagem definida como Não encaminhar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-195">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8fa33-196">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-196">Office Suite</span></span>

- <span data-ttu-id="8fa33-197">Corrige um problema que impede que os usuários importem listas do SPO quando a ADAL estiver desabilitada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-197">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-november-10"></a><span data-ttu-id="8fa33-199">Versão 2008: 10 de novembro</span><span class="sxs-lookup"><span data-stu-id="8fa33-199">Version 2008: November 10</span></span>
<span data-ttu-id="8fa33-200">*Versão 2008 (Build 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-200">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="8fa33-201">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-201">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-203">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-203">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8fa33-204">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-204">Excel</span></span>

- <span data-ttu-id="8fa33-205">Corrigimos um problema em que certas funções apresentavam resultados incorretos após o carregamento de uma pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="8fa33-205">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="8fa33-206">Corrigimos um problema em que o aplicativo fechava inesperadamente, o que estava relacionado a referências do suplemento XLAM e intervalos nomeados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-206">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="8fa33-207">Corrigimos um problema onde usando um macro para definir a propriedade FormulaR1C1 para um intervalo, as referências de células estariam incorretas se uma planilha de gráfico fosse a planilha ativa. </span><span class="sxs-lookup"><span data-stu-id="8fa33-207">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="8fa33-208">Corrigido um problema que poderia causar um erro de que "Excel esgotou os recursos ao tentar calcular uma ou mais fórmulas".</span><span class="sxs-lookup"><span data-stu-id="8fa33-208">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="8fa33-209">Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.</span><span class="sxs-lookup"><span data-stu-id="8fa33-209">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="8fa33-210">Corrigimos um problema que poderia causar um travamento ao atualizar as tabelas dinâmicas OLAP.</span><span class="sxs-lookup"><span data-stu-id="8fa33-210">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-211">Outlook</span></span>

- <span data-ttu-id="8fa33-212">Corrigimos um problema onde os usuários podem agora desabilitar o IRM (Gerenciamento de Direitos de Informação) para o Outlook sem ter que desabilitá-lo para o resto das aplicações do Office.</span><span class="sxs-lookup"><span data-stu-id="8fa33-212">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="8fa33-213">Corrigimos um problema que impedia os usuários de conceder permissão de Editor a seus delegados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-213">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="8fa33-214">Corrigimos um problema que fazia com que os usuários experienciassem o aplicativo encerrar inesperadamente ao selecionar um resultado de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-214">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="8fa33-215">Corrigimos um problema que fazia com que as pesquisas nos calendários do Grupo não retornassem nenhum resultado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-215">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="8fa33-216">Resolvido um problema que fazia com que os delegados vissem falhas intermitentes ao abrir pastas compartilhadas em outra caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="8fa33-216">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="8fa33-217">Resolvido um problema que fazia com que alguns emails gerados automaticamente fossem enviados com um corpo em branco quando a linha de assunto estava em branco.</span><span class="sxs-lookup"><span data-stu-id="8fa33-217">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="8fa33-218">Corrigimos um problema que fazia com que os cabeçalhos das mensagens em Chinês ficassem distorcidos ao responder ou encaminhar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-218">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="8fa33-219">Corrigimos um problema em que experiências conectadas opcionais impediam o carregamento de suplementos da web.</span><span class="sxs-lookup"><span data-stu-id="8fa33-219">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="8fa33-220">Consulte os detalhes na [postagem do blog](https://developer.microsoft.com/pt-BR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-220">See details in [blog post](https://developer.microsoft.com/pt-BR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-221">PowerPoint</span></span>

- <span data-ttu-id="8fa33-222">Corrigimos um problema em que o suplemento de conteúdo do Microsoft Forms não processa após a inserção até que o usuário clique em outro slide para exibi-lo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-222">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8fa33-223">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-223">Office Suite</span></span>

- <span data-ttu-id="8fa33-224">Resolvido um problema para clientes comerciais que utilizam o Centro do Sistema de Gerenciador de Configurações ou outra ferramenta de gerenciamento para o Atualização do Office usando a prevenção contra perda de dados do Ponto de extremidade do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8fa33-224">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="8fa33-225">Corrigido um problema de que a API de Mensagens para suplementos do Office não está funcionando.</span><span class="sxs-lookup"><span data-stu-id="8fa33-225">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-2008-october-13"></a><span data-ttu-id="8fa33-227">Versão 2008: 13 de outubro</span><span class="sxs-lookup"><span data-stu-id="8fa33-227">Version 2008: October 13</span></span>
<span data-ttu-id="8fa33-228">*Versão 2008 (Compilação 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-228">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="8fa33-229">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-229">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-231">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-231">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-232">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-232">Excel</span></span>

- <span data-ttu-id="8fa33-233">Correção de um bug com APIs PivotDateFilter no qual as condições de filtragem 'Antes' e 'Depois' eram invertidas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-233">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="8fa33-234">Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="8fa33-234">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="8fa33-235">Correção de um problema em que o Excel pode falhar ao usar a Análise Rápida após congelar a linha superior da planilha.</span><span class="sxs-lookup"><span data-stu-id="8fa33-235">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="8fa33-236">Correção de um problema que pode causar um aviso sobre uma pasta de trabalho corrompida se contiver fórmulas usando SENÃODISP().</span><span class="sxs-lookup"><span data-stu-id="8fa33-236">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-237">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-237">Outlook</span></span>

- <span data-ttu-id="8fa33-238">Corrige um problema que fez com que os usuários não conseguissem fechar os calendários compartilhados, clicando no "X" no canto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-238">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="8fa33-239">Corrige um problema que fazia com que a configuração "Habilitar melhorias no calendário compartilhado", às vezes, falhasse ao ser aplicada a calendários compartilhados existentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-239">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="8fa33-240">Corrige um problema que fazia com que os usuários vissem um erro na página de links seguros, em vez de no documento que tentavam abrir, ao abrir um anexo na nuvem.</span><span class="sxs-lookup"><span data-stu-id="8fa33-240">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="8fa33-241">Corrige um problema de desempenho com o carregamento de anexos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-241">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-242">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-242">PowerPoint</span></span>

- <span data-ttu-id="8fa33-243">Essa alteração corrige um problema com o recurso Exportar para GIF Animado em que clicar no botão Exportar não exportava.</span><span class="sxs-lookup"><span data-stu-id="8fa33-243">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="8fa33-244">Correção de segurança para solucionar um problema que desativou a proteção de IRM ao abrir um arquivo do PowerPoint no Modo de Exibição Protegido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-244">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="8fa33-245">Resolvemos um problema no diálogo de Configurações de Ação que estava causando uma falha no aplicativo PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-245">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="8fa33-246">Visio</span><span class="sxs-lookup"><span data-stu-id="8fa33-246">Visio</span></span>

- <span data-ttu-id="8fa33-247">Resolvemos um problema que fez com que a visualização ao vivo falhasse no alinhamento do texto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-247">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="8fa33-248">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-248">Word</span></span>

- <span data-ttu-id="8fa33-249">Resolvemos um problema que fazia com que os usuários experimentassem um travamento ao abrir certos emails muito grandes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-249">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="8fa33-250">Corrigimos um problema em que o usuário pode experimentar uma falha ao abrir um documento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-250">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="8fa33-251">Resolveu um problema que pode ter causado uma falha durante a inicialização do Word.</span><span class="sxs-lookup"><span data-stu-id="8fa33-251">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="8fa33-252">Corrigimos um problema com a caixa de diálogo Galeria de Estilos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-252">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8fa33-253">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-253">Office Suite</span></span>

- <span data-ttu-id="8fa33-254">Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners.</span><span class="sxs-lookup"><span data-stu-id="8fa33-254">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="8fa33-255">Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".</span><span class="sxs-lookup"><span data-stu-id="8fa33-255">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="8fa33-256">Corrige o alto uso de CPUs em ociosidade com GIF/modelo em 3D animado</span><span class="sxs-lookup"><span data-stu-id="8fa33-256">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="8fa33-257">Essa alteração corrige uma falha ao iniciar os aplicativos do Office devido à falha no carregamento de d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="8fa33-257">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-september-08"></a><span data-ttu-id="8fa33-259">Versão 2008: 8 de setembro</span><span class="sxs-lookup"><span data-stu-id="8fa33-259">Version 2008: September 08</span></span>
<span data-ttu-id="8fa33-260">*Versão 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-260">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="8fa33-261">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-261">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="8fa33-263">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="8fa33-263">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8fa33-264">Access</span><span class="sxs-lookup"><span data-stu-id="8fa33-264">Access</span></span>

- <span data-ttu-id="8fa33-265">**Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la.</span><span class="sxs-lookup"><span data-stu-id="8fa33-265">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="8fa33-266">Pesquise e substitua o texto no SQL View.</span><span class="sxs-lookup"><span data-stu-id="8fa33-266">Search and replace text in SQL View.</span></span> <span data-ttu-id="8fa33-267">Selecione várias tabelas na janela Relações.</span><span class="sxs-lookup"><span data-stu-id="8fa33-267">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="8fa33-268">**Adicionar tabelas com menos cliques:** usar o painel de tarefas Adicionar Tabelas, que permanece aberto enquanto você trabalha, para adicionar tabelas a relações e consultas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-268">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="8fa33-269">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-269">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="8fa33-270">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-270">Excel</span></span>

- <span data-ttu-id="8fa33-271">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-271">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8fa33-272">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-272">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8fa33-273">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-273">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8fa33-274">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-274">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8fa33-275">**Crie Tabelas Dinâmicas a partir de conjuntos de dados no Power BI no Excel:** Você pode criar tabelas dinâmicas no Excel que estão conectadas a conjuntos de dados armazenados no Power BI com alguns cliques.</span><span class="sxs-lookup"><span data-stu-id="8fa33-275">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="8fa33-276"> Isso permite que você obtenha o melhor das Tabelas Dinâmicas e do Power BI.</span><span class="sxs-lookup"><span data-stu-id="8fa33-276">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="8fa33-277">Calcule, resuma e analise seus dados com Tabelas Dinâmicas a partir dos conjuntos de dados seguros do Power BI.</span><span class="sxs-lookup"><span data-stu-id="8fa33-277">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="8fa33-278">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-278">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="8fa33-279">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-279">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="8fa33-280">**Suas funções favoritas do Excel acabaram de ficar mais rápidas:** As funções SOMASES, MÉDIASES, CONT.SES, MÁXIMOSES e MÍNIMOSES estão muito mais rápidas do que nunca.</span><span class="sxs-lookup"><span data-stu-id="8fa33-280">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="8fa33-281">Chegue ao resultado final mais rapidamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-281">Get to the bottom line more quickly.</span></span> <span data-ttu-id="8fa33-282">Experimente agora.</span><span class="sxs-lookup"><span data-stu-id="8fa33-282">Try one now.</span></span>

- <span data-ttu-id="8fa33-283">**Aprimoramentos no Realtimedata (RTD):** No Office 365 canal mensal versão 2002 ou posterior, a função do Excel (RealTimeData) é muito mais rápida ao calcular os dados na planilha do que o Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="8fa33-283">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="8fa33-284">Removemos os gargalos na sua memória e estruturas de dados subjacentes, bem como o tornamos thread-safe para permitir o seu cálculo em todas as threads disponíveis de recálculo multithreaded (MTR).</span><span class="sxs-lookup"><span data-stu-id="8fa33-284">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-285">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-285">Outlook</span></span>

- <span data-ttu-id="8fa33-286">**As tualizações de calendário compartilhadas ficaram mais rápidas**: No caso de calendários compartilhados no Office 365, o Outlook pode atualizá-los usando a API REST.</span><span class="sxs-lookup"><span data-stu-id="8fa33-286">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="8fa33-287">Ative a visualização para atualizações mais rápidas e confiáveis de calendários compartilhados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-287">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="8fa33-288">**Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca.</span><span class="sxs-lookup"><span data-stu-id="8fa33-288">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="8fa33-289">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-289">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="8fa33-290">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-290">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8fa33-291">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-291">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8fa33-292">**Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-292">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="8fa33-293">As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-293">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="8fa33-294">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-294">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="8fa33-295">**O calendário recebe um novo formato:** ver atualizações visuais que facilitam a pesquisa do calendário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-295">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="8fa33-296">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-296">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="8fa33-297">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-297">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="8fa33-298">**Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online.</span><span class="sxs-lookup"><span data-stu-id="8fa33-298">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="8fa33-299">Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.</span><span class="sxs-lookup"><span data-stu-id="8fa33-299">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="8fa33-300">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-300">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="8fa33-301">**Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar?</span><span class="sxs-lookup"><span data-stu-id="8fa33-301">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="8fa33-302">O Outlook agora detecta isso e ajuda você a se conectar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-302">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="8fa33-303">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="8fa33-303">See details in [blog post](https://insider.office.com/pt-BR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="8fa33-304">**Obter sugestões de email ao procurar por alguém:** Quando você digitar o nome de uma pessoa na Caixa de pesquisa, os emails mais relevantes serão incluídos nas sugestões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-304">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="8fa33-305">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-305">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="8fa33-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-306">PowerPoint</span></span>

- <span data-ttu-id="8fa33-307">**Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles.</span><span class="sxs-lookup"><span data-stu-id="8fa33-307">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="8fa33-308">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-308">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="8fa33-309">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-309">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8fa33-310">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-310">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8fa33-311">**GIFs em instantes:** Um slide, um quadro.</span><span class="sxs-lookup"><span data-stu-id="8fa33-311">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="8fa33-312">Crie facilmente GIFs de loop no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-312">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="8fa33-313">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-313">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="8fa33-314">Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-314">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="8fa33-315">**Diagramas melhores:** Com conectores melhores e um processo de conversão de tinta mais suave, você pode usar a tinta em suas ideias de forma mais confiante.</span><span class="sxs-lookup"><span data-stu-id="8fa33-315">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="8fa33-316">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-316">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8fa33-317">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-317">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8fa33-318">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-318">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8fa33-319">**Comentários:** a nova experiência de comentários no PowerPoint permite que você descubra e adicione comentários de maneira rápida e fácil aos seus documentos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-319">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="8fa33-320">Modernize seus fluxos de trabalho de colaboração com novos recursos, como ancoragem de comentários, resolução, tarefas, notificações de menção aprimorada e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-320">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="8fa33-321">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-321">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="8fa33-322">**Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="8fa33-322">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="8fa33-323">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-323">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="8fa33-324">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-324">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="8fa33-325">**Vincular ao Slide:** Peça a um colega para contribuir com o conjunto de slides e inicie-o diretamente no slide para o qual você precisa de ajuda.</span><span class="sxs-lookup"><span data-stu-id="8fa33-325">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="8fa33-326">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-326">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="8fa33-327">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-327">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="8fa33-328">**Melhor desempenho de streaming de vídeo no PowerPoint:** fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável.</span><span class="sxs-lookup"><span data-stu-id="8fa33-328">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="8fa33-329">Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.</span><span class="sxs-lookup"><span data-stu-id="8fa33-329">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="8fa33-330">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-330">Word</span></span>

- <span data-ttu-id="8fa33-331">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-331">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8fa33-332">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-332">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8fa33-333">**Laço a tinta:** a ferramenta laço na guia desenhar ajuda a selecionar objetos desenhados à tinta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-333">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="8fa33-334">Selecione traços individuais ou palavras inteiras.</span><span class="sxs-lookup"><span data-stu-id="8fa33-334">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="8fa33-335">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-335">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="8fa33-336">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-336">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8fa33-337">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-337">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8fa33-338">**Confirmação de ação nos leitores de tela:** Confirmação de ação é um requisito de acessibilidade importante.</span><span class="sxs-lookup"><span data-stu-id="8fa33-338">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="8fa33-339">Com a introdução de uma nova API de Notificação do Windows, agora vamos alertar os usuários do leitor de tela sobre o sucesso de suas ações.</span><span class="sxs-lookup"><span data-stu-id="8fa33-339">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="8fa33-340">Recortar, copiar, colar, negrito, itálico, sublinhado, desfazer, refazer, correções automáticas e todas as maiúsculas agora são anunciadas para os usuários do Narrador no Word Win32.</span><span class="sxs-lookup"><span data-stu-id="8fa33-340">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="8fa33-341">Para habilitar esse recurso, ative o Narrador pressionando a tecla windows + ctrl + enter.</span><span class="sxs-lookup"><span data-stu-id="8fa33-341">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="8fa33-342">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="8fa33-342">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-343">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-343">Office Suite</span></span>

- <span data-ttu-id="8fa33-344">**Rótulos de confidencialidade:** agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-344">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-347">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-347">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8fa33-348">Acesso</span><span class="sxs-lookup"><span data-stu-id="8fa33-348">Access</span></span>

- <span data-ttu-id="8fa33-349">Resolveu um problema com a inserção de tabelas SQL vinculadas que incluem um campo identidade (por exemplo, numeração automática).</span><span class="sxs-lookup"><span data-stu-id="8fa33-349">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="8fa33-350">Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. </span><span class="sxs-lookup"><span data-stu-id="8fa33-350">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="8fa33-351">Corrige um problema para possibilitar o uso do tipo de dados de Data/Hora Estendida em seu código sem o aplicativo falhar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-351">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="8fa33-352">Corrige um problema para poder reverter para a versão mais atualizada do Access e usar o DAO/VBA para gerenciar e editar um tipo de dados decimais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-352">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="8fa33-353">Esta correção resolve o problema em que a tentativa de executar determinadas consultas tenha previamente produzido a mensagem de erro 'Consulta é muito complexa'.</span><span class="sxs-lookup"><span data-stu-id="8fa33-353">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="8fa33-354">O Access resolveu esse problema atual, mas estaremos analisando nossas interfaces adicionais para garantir que esse problema não persista.</span><span class="sxs-lookup"><span data-stu-id="8fa33-354">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="8fa33-355">A equipe vai informá-lo sobre atualizações futuras. Agradecemos sua paciência.</span><span class="sxs-lookup"><span data-stu-id="8fa33-355">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="8fa33-356">Este problema foi resolvido - agora você pode usar nosso driver ODBC fora das aplicações de Clicar para Executar do Office.</span><span class="sxs-lookup"><span data-stu-id="8fa33-356">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="8fa33-357">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-357">Excel</span></span>

- <span data-ttu-id="8fa33-358">A classificação automática de documentos pode ter ocorrido para as pastas de trabalho que estavam e modo somente leitura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-358">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="8fa33-359">Correção de uma falha que poderia ocorrer quando você tentasse criar uma conexão de dados se tivesse saído da sua conta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-359">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="8fa33-360">Solucionamos um problema em que o Excel poderia falhar ao tentar inserir Tabelas Dinâmicas em uma planilha de gráfico.</span><span class="sxs-lookup"><span data-stu-id="8fa33-360">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="8fa33-361">Poderia ocorrer um erro ao tentar salvar um arquivo que continha uma fórmula usando a função LET ().</span><span class="sxs-lookup"><span data-stu-id="8fa33-361">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="8fa33-362">Correção de um problema em que o Excel poderia falhar em determinadas circunstâncias ao usar o Pincel de Formatação.</span><span class="sxs-lookup"><span data-stu-id="8fa33-362">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="8fa33-363">Correção de um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-363">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8fa33-364">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="8fa33-364">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="8fa33-365">Corrigimos um problema que, em alguns casos, clicar em um hiperlink para um local na mesma pasta de trabalho fará com que a pasta de trabalho seja ocultada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-365">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="8fa33-366">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-366">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8fa33-367">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-367">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8fa33-368">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="8fa33-368">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8fa33-369">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="8fa33-369">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8fa33-370">Isso aborda um problema em que as conexões criadas pelo provedor de dados SQL nas versões anteriores do Office definem as propriedades da tabela interna de modo diferente do Office 365.</span><span class="sxs-lookup"><span data-stu-id="8fa33-370">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="8fa33-371">Isso fazia com que a lista suspensa da visualização de tabela / editor de consulta fosse desabilitada para arquivos com conexões criadas em versões mais antigas do Office quando elas fossem abertas usando o Office 365.</span><span class="sxs-lookup"><span data-stu-id="8fa33-371">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="8fa33-372">Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-372">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="8fa33-373">Resolvemos um problema em que a escrita à tinta poderia fazer com que o Excel não respondesse.</span><span class="sxs-lookup"><span data-stu-id="8fa33-373">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="8fa33-374">OneNote</span><span class="sxs-lookup"><span data-stu-id="8fa33-374">OneNote</span></span>

- <span data-ttu-id="8fa33-375">Informa os usuários, por meio da barra de informações, sobre ajustes temporários no Microsoft OneNote que ajudarão a melhorar a sincronização e o serviço durante o uso intenso pelo mundo inteiro.</span><span class="sxs-lookup"><span data-stu-id="8fa33-375">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="8fa33-376">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-376">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="8fa33-377">Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-377">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="8fa33-378">Melhoria da sincronização e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-378">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="8fa33-379">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="8fa33-379">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="8fa33-380">Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-380">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="8fa33-381">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="8fa33-381">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="8fa33-382">Melhoria na sincronização e estabilidade do serviço, alterando temporariamente a frequência com que os históricos de versão de página são criados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-382">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="8fa33-383">Melhoria na sincronização e estabilidade do servidor ao desabilitar, temporariamente, a transferências de páginas para a lixeira.</span><span class="sxs-lookup"><span data-stu-id="8fa33-383">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="8fa33-384">Os usuários que desejam excluir uma página, em vez disso, receberão uma caixa de diálogo perguntando se gostariam de excluir permanentemente a página.</span><span class="sxs-lookup"><span data-stu-id="8fa33-384">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-385">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-385">Outlook</span></span>

- <span data-ttu-id="8fa33-386">Corrige um problema que provocou os usuários que tentaram criar uma solicitação de reunião de uma conta secundária adicionada ao perfil, a não verem um campo em branco De: em vez de seus endereços de email.</span><span class="sxs-lookup"><span data-stu-id="8fa33-386">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="8fa33-387">Corrige um problema que fazia com que os usuários não conseguissem se conectar à pastas públicas após adicionar uma caixa de correio compartilhada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-387">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="8fa33-388">Resolveu um problema que fazia com que as reuniões não fossem retiradas do calendário de um gerente, quando recusadas por um representante em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="8fa33-388">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="8fa33-389">Resolveu um problema que impedia alguns usuários do recurso de Melhorias do Calendário Compartilhado de poderem visualizar um calendário compartilhado recém-adicionado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-389">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="8fa33-390">Corrige um problema que causava falhas ocasionais quando os usuários interagiam com anexos na nuvem.</span><span class="sxs-lookup"><span data-stu-id="8fa33-390">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="8fa33-391">Solucionamos um problema que fazia com que os usuários do CLP experimentassem uma falha ao mudar o endereço de um contexto de um contexto protegido para um não protegido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-391">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="8fa33-392">Solucionamos um problema em que o Outlook falhava ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="8fa33-392">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8fa33-393">Corrige um problema com o evento de auditoria CLP para o rótulo responder/encaminhar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-393">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="8fa33-394">Solucionamos um problema que provocava a alteração inesperada da largura do painel de pasta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-394">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8fa33-395">Aborda um problema que fazia com que os usuários vissem a data de criação de anexos que haviam copiado para seu sistema de arquivos por meio de arrastar e colar sendo definida como 1 de janeiro de 4501.</span><span class="sxs-lookup"><span data-stu-id="8fa33-395">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="8fa33-396">Tratamos de um problema que fazia com que os usuários de alguns conjuntos de caracteres vissem os nomes de arquivos exibidos incorretamente ao adicionar um Smart Link a um arquivo do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-396">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="8fa33-397">Soluciona um problema que exibia a mensagem “As regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-397">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="8fa33-398">Resolvido um problema que fazia com que o Outlook não recuperasse as sugestões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-398">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="8fa33-399">Corrige um problema que causava falhas no calendário em aperfeiçoamentos do Calendário Compartilhado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-399">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="8fa33-400">Soluciona um problema que causava falhas e travas intermitentes em algumas situações.</span><span class="sxs-lookup"><span data-stu-id="8fa33-400">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="8fa33-401">Tratamos de um problema que fazia com que os usuários experimentassem uma falha ao excluir 4 ou mais emails de uma conta POP com a opção "Baixar Apenas Cabeçalhos" selecionada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-401">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="8fa33-402">Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-402">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8fa33-403">Solucionado um problema que fazia com que representantes recebessem uma mensagem de erro ao editar um compromisso no calendário existente em um calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="8fa33-403">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="8fa33-404">Solucionamos um problema que fazia com que os usuários experimentassem falhas em aplicativos MAPI de terceiros.</span><span class="sxs-lookup"><span data-stu-id="8fa33-404">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="8fa33-405">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="8fa33-405">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8fa33-406">Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.</span><span class="sxs-lookup"><span data-stu-id="8fa33-406">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="8fa33-407">Corrige um problema que fazia com que os usuários do servidor do Windows 10 vissem o aviso “Status do antivírus: Inválido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-407">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="8fa33-408">Essa versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus foi encontrado” mesmo após a instalação correta do antivírus.</span><span class="sxs-lookup"><span data-stu-id="8fa33-408">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="8fa33-409">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="8fa33-409">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8fa33-410">Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.</span><span class="sxs-lookup"><span data-stu-id="8fa33-410">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="8fa33-411">Corrige um problema que fazia com que o Outlook solicitasse continuamente para os usuários executarem a Ferramenta Reparo da Caixa de Entrada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-411">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="8fa33-412">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="8fa33-412">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="8fa33-413">Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="8fa33-413">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="8fa33-414">Solucionamos um problema que provocou falha na exibição da página do assistente de agendamento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-414">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="8fa33-415">Resolvido um problema que provocava falha na exibição da página do Assistente de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-415">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="8fa33-416">Resolvido um problema que causava um ocasional travamento para os usuários ao recuperar informações pessoais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-416">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="8fa33-417">Corrige um problema que causava falhas ocasionais quando os usuários editavam destinatários.</span><span class="sxs-lookup"><span data-stu-id="8fa33-417">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8fa33-418">Corrige um problema que causava os usuários de ver anormalidades ao usar o modo de exibição compacto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-418">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="8fa33-419">Solucionamos um problema que fazia com que os usuários do Outlook vissem problemas com a navegação no modo de exibição compacto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-419">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="8fa33-420">Resolveu de um problema que fazia com que o menu de contexto do botão direito do mouse não fosse exibido nos controles de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-420">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="8fa33-421">Aborda um problema que fez com que os usuários recebessem o seguinte erro ao responder ou a redigir um novo email: “Alguns arquivos desta página da Web não estão no local esperado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-421">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="8fa33-422">Deseja baixá-los mesmo assim?</span><span class="sxs-lookup"><span data-stu-id="8fa33-422">Do you want to download them anyway?</span></span> <span data-ttu-id="8fa33-423">Se tiver certeza de que a página da Web é de uma fonte confiável, clique em Sim.”</span><span class="sxs-lookup"><span data-stu-id="8fa33-423">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="8fa33-424">Corrige um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-424">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="8fa33-425">Solucionamos um problema que fazia com que a pesquisa de um recurso sugerir um recurso não retornou nenhum resultado e deixe o usuário sem a opção de enviar uma nova ideia de recurso.</span><span class="sxs-lookup"><span data-stu-id="8fa33-425">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="8fa33-426">Corrige um problema que causava problemas de formatação em alertas de notificação de incidente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-426">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="8fa33-427">Corrige um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma Notificação de Administrador.</span><span class="sxs-lookup"><span data-stu-id="8fa33-427">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="8fa33-428">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="8fa33-428">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8fa33-429">Corrige um problema que causava falhas ocasionais quando os usuários editavam destinatários.</span><span class="sxs-lookup"><span data-stu-id="8fa33-429">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8fa33-430">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="8fa33-430">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-431">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-431">PowerPoint</span></span>

- <span data-ttu-id="8fa33-432">Isso corrige uma falha quando os usuários têm comentários modernos e antigos em um arquivo, disparando uma atualização nos comentários.</span><span class="sxs-lookup"><span data-stu-id="8fa33-432">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="8fa33-433">Solucionamos um problema de falha no aplicativo PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-433">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="8fa33-434">Solucionamos um problema de falha com o painel de sugestões.</span><span class="sxs-lookup"><span data-stu-id="8fa33-434">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="8fa33-435">Project</span><span class="sxs-lookup"><span data-stu-id="8fa33-435">Project</span></span>

- <span data-ttu-id="8fa33-436">Corrige um problema de quando os dados do predecessor/sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-436">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="8fa33-437">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="8fa33-437">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8fa33-438">Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-438">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="8fa33-439">Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.</span><span class="sxs-lookup"><span data-stu-id="8fa33-439">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="8fa33-440">Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="8fa33-440">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="8fa33-441">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-441">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8fa33-442">Solucionamos um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-442">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="8fa33-443">Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.</span><span class="sxs-lookup"><span data-stu-id="8fa33-443">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="8fa33-444">Corrige um problema no qual não era possível abrir projetos no cliente da área de trabalho do Project a partir do aplicativo web do Project caso a URL terminasse em .com.</span><span class="sxs-lookup"><span data-stu-id="8fa33-444">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="8fa33-445">Corrigimos um problema no qual, se você colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-445">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="8fa33-446">Corrigimos um problema no qual não era possível salvar um PDF/XPS do Project em uma biblioteca de documentos no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-446">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="8fa33-447">Correção de um problema em que uma tarefa marcada como 100% concluída mudava incorretamente para menos do que 100% concluída.</span><span class="sxs-lookup"><span data-stu-id="8fa33-447">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="8fa33-448">Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa resumo do projeto, o campo início/tarefa do projeto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-448">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="8fa33-449">Corrige um problema em que, se um recurso tivesse mais de uma tabela de taxas de custo definida, os custos restantes nem sempre eram calculados corretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-449">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="8fa33-450">Corrige um problema em que a data de término do projeto não está sendo atualizada para os projetos conectados à lista de tarefas do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-450">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="8fa33-451">Corrigimos um problema no qual a tarefa selecionada na caixa de diálogo para atribuir recursos não era a mesma que a tarefa selecionada no modo de exibição do quadro de tarefas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-451">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="8fa33-452">Corrigige um problema onde um projeto que estava em um estado ruim não podia ser aberto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-452">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="8fa33-453">Skype</span><span class="sxs-lookup"><span data-stu-id="8fa33-453">Skype</span></span>

- <span data-ttu-id="8fa33-454">Quando um usuário recebe uma política que os move para o modo Teams Only, ele ainda poderá usar o suplemento do Outlook do Skype for Business para agendar reuniões.</span><span class="sxs-lookup"><span data-stu-id="8fa33-454">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="8fa33-455">Após essa atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente ler a política, indicando que o usuário está no modo Teams Only, e entrar no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="8fa33-455">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="8fa33-456">Além disso, o suplemento Skype for Business no Outlook não será ativado durante a inicialização, caso veja que o cliente do Skype for Business está no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="8fa33-456">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="8fa33-457">Alterou o tom de pele do emoticon que dança para uma cor neutra.</span><span class="sxs-lookup"><span data-stu-id="8fa33-457">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-458">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-458">Word</span></span>

- <span data-ttu-id="8fa33-459">Resolvido um problema ao abrir documentos do Word a partir de uma entrega de documento personalizada (aspx) quando a URL contém um componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-459">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="8fa33-460">Essa alteração corrige um problema em que os aplicativos do Office poderiam ficar presos em um estado de falha silencioso de salvamento após uma sessão anterior de coautoria.</span><span class="sxs-lookup"><span data-stu-id="8fa33-460">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="8fa33-461">Soluciona um problema que fazia com que os usuários experimentassem uma falha ao responder ou redigir um novo email.</span><span class="sxs-lookup"><span data-stu-id="8fa33-461">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="8fa33-462">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="8fa33-462">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="8fa33-463">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="8fa33-463">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8fa33-464">Resolvemos um problema em que o usuário poderia perder conteúdo ao redimensionar uma forma.</span><span class="sxs-lookup"><span data-stu-id="8fa33-464">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="8fa33-465">Consertamos um problema em que os estilos básicos não eram atualizados com o estilo normal.</span><span class="sxs-lookup"><span data-stu-id="8fa33-465">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="8fa33-466">Resolvemos um problema em que a macro AutoOpen era executada antes do AutoExec.</span><span class="sxs-lookup"><span data-stu-id="8fa33-466">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="8fa33-467">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="8fa33-467">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8fa33-468">Soluciona um problema que pode ter causado uma falha ao arrastar conteúdo do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-468">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8fa33-469">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-469">Office Suite</span></span>

- <span data-ttu-id="8fa33-470">Para o antigo painel de Compartilhamento não baseado na Web, ao fechar o documento enquanto o painel de Compartilhamento abria, isso poderia causar uma falha.</span><span class="sxs-lookup"><span data-stu-id="8fa33-470">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="8fa33-471">Isto agora está corrigido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-471">This is now fixed.</span></span>

- <span data-ttu-id="8fa33-472">Corrige um problema de tempo que poderia causar uma falha ao fechar arquivos do Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-472">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="8fa33-473">Resolvemos o problema de taxa de falha do ValidateInstall configurando a validação de instalação do Bing Addon como verdadeira por padrão e considerando o sucesso do retorno MSI como um sucesso na instalação.</span><span class="sxs-lookup"><span data-stu-id="8fa33-473">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="8fa33-474">Portamos uma nova AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="8fa33-474">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8fa33-475">Corrige um problema com Clique para Executar, que resultava na falha de atualização durante a tentativa de vincular links simbólicos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-475">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="8fa33-476">Corrigido um problema que provocou uma mensagem do tempo de execução, mesmo que foi demonstrado que a transição para o produto completo tenha sido concluída.</span><span class="sxs-lookup"><span data-stu-id="8fa33-476">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="8fa33-477">A correção para esse problema foi garantir que o serviço computasse corretamente os produtos adicionados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-477">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="8fa33-478">Filtramos os produtos recém-adicionados (garantindo que também estejam presentes na nova configuração) e os adicionamos no final das IDs de lançamento dos produtos existentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-478">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="8fa33-479">Solucionamos um problema em que os usuários estavam vendo os elementos da interface do usuário ou o conteúdo que não estava sendo exibido em determinadas condições, em particular, no Modo de Exibição do Apresentador ou no uso de vários monitores.</span><span class="sxs-lookup"><span data-stu-id="8fa33-479">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="8fa33-480">Essa alteração soluciona as possíveis travas ao carregar e reproduzir conteúdo animado, como GIFs ou modelos 3D.</span><span class="sxs-lookup"><span data-stu-id="8fa33-480">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="8fa33-481">Essa alteração corrige um problema com a caixa de diálogos Compactar imagem que não mantém determinadas configurações do usuário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-481">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="8fa33-482">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="8fa33-482">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8fa33-483">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-483">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8fa33-484">Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-484">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="8fa33-485">Corrige um problema de falha com o host do Office no Windows quando um suplemento é ativado enquanto o valor TabProcGrowth do registro é tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="8fa33-485">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="8fa33-486">O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero.</span><span class="sxs-lookup"><span data-stu-id="8fa33-486">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="8fa33-487">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="8fa33-487">This change would fix this issue.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-august-11"></a><span data-ttu-id="8fa33-489">Versão 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="8fa33-489">Version 2002: August 11</span></span>
<span data-ttu-id="8fa33-490">*Versão 2002 (Compilação 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-490">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="8fa33-491">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-493">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-494">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-494">Excel</span></span>

- <span data-ttu-id="8fa33-495">Corrigido um problema que impedia a capacidade de mudar para editar arquivos que foram abertos como "leitura somente recomendado".</span><span class="sxs-lookup"><span data-stu-id="8fa33-495">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="8fa33-496">OneNote</span><span class="sxs-lookup"><span data-stu-id="8fa33-496">OneNote</span></span>

- <span data-ttu-id="8fa33-497">Removido as chamadas de identidade redundantes para reduzir a utilização de recursos</span><span class="sxs-lookup"><span data-stu-id="8fa33-497">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="8fa33-498">Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-498">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="8fa33-499">Melhoria na capacidade de detecção de erros e na experiência de sincronização com qualidade.</span><span class="sxs-lookup"><span data-stu-id="8fa33-499">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-500">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-500">Outlook</span></span>

- <span data-ttu-id="8fa33-501">Foi abordado um problema que causava um problema de desempenho significativo ao iniciar o Outlook para alguns locatários.</span><span class="sxs-lookup"><span data-stu-id="8fa33-501">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="8fa33-502">Skype</span><span class="sxs-lookup"><span data-stu-id="8fa33-502">Skype</span></span>

- <span data-ttu-id="8fa33-503">Corrigido um problema em que iniciar um compartilhamento de tela pode falhar em um cliente do Skype for Business de 32 bits após ele estiver sendo executado por vários dias.</span><span class="sxs-lookup"><span data-stu-id="8fa33-503">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-504">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-504">Office Suite</span></span>

- <span data-ttu-id="8fa33-505">Corrigido um problema em que, quando o salvamento automático estava desativado na política de grupo, alguns documentos não podiam mostrar o conteúdo mais recente do servidor na abertura até o usuário clicar em "Atualizações disponíveis".</span><span class="sxs-lookup"><span data-stu-id="8fa33-505">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-july-14"></a><span data-ttu-id="8fa33-507">Versão 2002: 14 de julho</span><span class="sxs-lookup"><span data-stu-id="8fa33-507">Version 2002: July 14</span></span>
<span data-ttu-id="8fa33-508">*Versão 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-508">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="8fa33-509">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-511">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-511">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-512">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-512">Excel</span></span>

- <span data-ttu-id="8fa33-513">Acelerar o carregamento de arquivos disponíveis na pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-513">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="8fa33-514">Correção de um problema que causava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8fa33-514">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8fa33-515">Correção de um problema em que a mensagem de erro "Esta pasta de trabalho está referenciada por outra pasta e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-515">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="8fa33-516">Correção de um problema em que uma pasta de trabalho poderia ficar oculta ao clicar em um hiperlink em uma pasta de trabalho já aberta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-516">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="8fa33-517">Correção de um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-517">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="8fa33-518">Desempenho aprimorado ao excluir colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-518">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="8fa33-519">Correção de um problema em que os nomes de impressora poderiam ser repetidos na lista de impressoras na caixa de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="8fa33-519">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="8fa33-520">Consertamos um problema em que as planilhas que continham várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-520">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-521">Outlook</span></span>

- <span data-ttu-id="8fa33-522">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-522">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="8fa33-523">Soluciona um problema em que compromissos ou reuniões recorrentes eram exibidos na hora errada ao alterar a definição de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-523">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="8fa33-524">Soluciona um problema que exibia a mensagem “As regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-524">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="8fa33-525">Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-525">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8fa33-526">Foi resolvido um problema que fazia com que as categorias desaparecessem ocasionalmente de mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="8fa33-526">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="8fa33-527">Foi resolvido um problema que fazia com que representantes vissem diferentes hierarquias de pastas em caixas de correio compartilhadas em computadores diferentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-527">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="8fa33-528">Solucionamos um problema que fazia com que representantes recebessem uma mensagem de erro ao editar um compromisso de calendário existente no calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="8fa33-528">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="8fa33-529">Correção de um problema que fazia com que o corpo de uma mensagem de Notificação de Falha na Entrega mudasse de Unicode para ASCII após editar o assunto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-529">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="8fa33-530">Correção de um problema que causava uma falha quando dois suplementos adicionam um botão ao mesmo grupo da faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="8fa33-530">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="8fa33-531">Correção de um problema que fazia com que os usuários não conseguissem endereçar emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="8fa33-531">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="8fa33-532">Correção de um problema que fazia com que os links não sejam adicionados aos emails com a permissão de locatário padrão correta quando a permissão de locatário padrão está configurada como "qualquer pessoa".</span><span class="sxs-lookup"><span data-stu-id="8fa33-532">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="8fa33-533">Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="8fa33-533">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-534">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-534">Word</span></span>

- <span data-ttu-id="8fa33-535">Correção de um problema na coautoria se habilitarmos a política FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="8fa33-535">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="8fa33-536">Correção de um problema em que partes rápidas no Word não funcionava ao adicionar um campo de pesquisa que foi renomeado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-536">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-537">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-537">Office Suite</span></span>

- <span data-ttu-id="8fa33-538">Correção de um problema em que poderia ocorrer uso excessivo da rede e da CPU durante a coautoria em arquivos grandes do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-538">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="8fa33-539">Fizemos uma nova AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="8fa33-539">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8fa33-540">Foi corrigido um problema de falha com o host do Office no Windows quando um suplemento é ativado enquanto o valor TabProcGrowth do registro é tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="8fa33-540">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-june-09"></a><span data-ttu-id="8fa33-542">Versão 2002: 09 de junho</span><span class="sxs-lookup"><span data-stu-id="8fa33-542">Version 2002: June 09</span></span>
<span data-ttu-id="8fa33-543">*Versão 2002 (Build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-543">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="8fa33-544">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-544">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-546">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-546">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-547">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-547">Excel</span></span>

- <span data-ttu-id="8fa33-548">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-548">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8fa33-549">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="8fa33-549">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="8fa33-550">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-550">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="8fa33-551">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="8fa33-551">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="8fa33-552">Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-552">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="8fa33-553">Correção de um problema em que um símbolo @ iniciando uma fórmula seria considerado um operador de interseção implícito.</span><span class="sxs-lookup"><span data-stu-id="8fa33-553">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-554">Outlook</span></span>

- <span data-ttu-id="8fa33-555">Permite que você ingresse em uma reunião do Teams diretamente por meio do cliente nativo do Teams.</span><span class="sxs-lookup"><span data-stu-id="8fa33-555">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="8fa33-556">Solucionamos um problema em que o Outlook falhava ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="8fa33-556">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8fa33-557">Solucionamos um problema que fazia com que os usuários com a configuração de emulação do navegador incorreta não conseguissem concluir o prompt de autenticação do Gmail.</span><span class="sxs-lookup"><span data-stu-id="8fa33-557">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="8fa33-558">Solucionamos um problema que fazia com que os usuários do Outlook nos sistemas operacionais de servidor vissem o erro "status do antivírus: inválido".</span><span class="sxs-lookup"><span data-stu-id="8fa33-558">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="8fa33-559">Esta versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus era encontrado, apesar do antivírus ter sido configurado adequadamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-559">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-560">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-560">Word</span></span>

- <span data-ttu-id="8fa33-561">Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.</span><span class="sxs-lookup"><span data-stu-id="8fa33-561">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-562">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-562">Office Suite</span></span>

- <span data-ttu-id="8fa33-563">Resolvemos esse problema atualizando os nomes dos canais no backstage para os nomes dos novos canais na bifurcação de Janeiro de 2020.</span><span class="sxs-lookup"><span data-stu-id="8fa33-563">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="8fa33-564">Corrigimos esse problema e no futuro, se um dispositivo for gerenciado por política, ele não chamará a API de audiência do DMS.</span><span class="sxs-lookup"><span data-stu-id="8fa33-564">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="8fa33-565">Resolvemos o problema em que há uma remoção incompleta ao adicionar e remover aplicativos em uma única transação.</span><span class="sxs-lookup"><span data-stu-id="8fa33-565">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="8fa33-566">O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero.</span><span class="sxs-lookup"><span data-stu-id="8fa33-566">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="8fa33-567">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="8fa33-567">This change would fix this issue.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-may-12"></a><span data-ttu-id="8fa33-569">Versão 2002: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="8fa33-569">Version 2002: May 12</span></span>
<span data-ttu-id="8fa33-570">*Versão 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-570">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="8fa33-571">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-571">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-573">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-573">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8fa33-574">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-574">Excel</span></span>

- <span data-ttu-id="8fa33-575">Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, especialmente com janelas ocultas, seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-575">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="8fa33-576">A abertura de arquivos CSV estava demorando mais do que o esperado em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="8fa33-576">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="8fa33-577">O Excel pode falhar em algumas circunstâncias ao alternar entre pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="8fa33-577">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="8fa33-578">Correção de um problema com o VBA no qual a escrita de valores em um intervalo seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-578">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="8fa33-579">Os dados copiados de uma coluna filtrada por cores às vezes não serão colados corretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-579">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="8fa33-580">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma Tabela Dinâmica.</span><span class="sxs-lookup"><span data-stu-id="8fa33-580">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8fa33-581">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="8fa33-581">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8fa33-582">Corrigido um problema em que a propriedade "O Valor Cruza Em" se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-582">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="8fa33-583">Usar um Intervalo.Valor e Intervalo.Valor2 (VBA) faria com que as fórmulas fossem inseridas como matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-583">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="8fa33-584">OneNote</span><span class="sxs-lookup"><span data-stu-id="8fa33-584">OneNote</span></span>

- <span data-ttu-id="8fa33-585">Localiza a notificação que permite que o usuário saiba mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="8fa33-585">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="8fa33-586">Exibe uma notificação que permite ao usuário saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade do serviço e de sincronia.</span><span class="sxs-lookup"><span data-stu-id="8fa33-586">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="8fa33-587">Melhoria da estabilidade do serviço e de sincronização, reduzindo temporariamente a frequência do número e da sincronia das páginas do histórico de versão no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-587">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="8fa33-588">Melhoria da sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-588">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="8fa33-589">Quando um usuário tenta excluir dados que normalmente seriam enviados para a lixeira, os usuários serão solicitados a optar por manter ou excluir permanentemente os dados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-589">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="8fa33-590">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-590">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="8fa33-591">Melhoria da estabilidade do serviço e da sincronia referindo-se temporariamente ao download de arquivos e imagens inseridas em blocos de anotações online até que o usuário navegue para a página no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-591">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="8fa33-592">Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-592">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="8fa33-593">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="8fa33-593">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="8fa33-594">Melhoria da sincronia e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="8fa33-594">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="8fa33-595">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="8fa33-595">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-596">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-596">Outlook</span></span>

- <span data-ttu-id="8fa33-597">Corrigido um problema que provocou a alteração inesperada da largura do painel de pasta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-597">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8fa33-598">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao tentar abrir arquivos .msg e .oft após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="8fa33-598">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="8fa33-599">Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-599">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="8fa33-600">Esta atualização corrige um problema com o Microsoft Outlook, que não exibe o rótulo de confidencialidade atual ao exibir ou redigir mensagens.</span><span class="sxs-lookup"><span data-stu-id="8fa33-600">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="8fa33-601">Solucionamos um problema que fazia com que os usuários não conseguissem lidar com emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="8fa33-601">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8fa33-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-602">PowerPoint</span></span>

- <span data-ttu-id="8fa33-603">Correção de um problema para retransmissão de mensagens corretas para os usuários que abrirem uma cópia de um arquivo que tenha comentários melhorados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-603">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-604">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-604">Word</span></span>

- <span data-ttu-id="8fa33-605">Resolvemos o problema em que o Access e o Publisher podem não inicializar corretamente dependendo de quais idiomas foram instalados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-605">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="8fa33-606">Corrigimos um problema com o recurso Comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="8fa33-606">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="8fa33-607">Corrigimos um problema ao mesclar dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-607">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-608">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-608">Office Suite</span></span>

- <span data-ttu-id="8fa33-609">Esta é uma correção para que o aplicativo do Project não bloqueie rede quando o arquivo estiver armazenado em cache no cliente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-609">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="8fa33-610">Resolvemos o problema em que uma operação interna estava gerando uma exceção na falha, em vez de fazer o logon e continuar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-610">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="8fa33-611">Os usuários afetados não serão mais impedidos de receber as atualizações.</span><span class="sxs-lookup"><span data-stu-id="8fa33-611">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="8fa33-612">Essa alteração garante que a estrutura de tópicos Esboçada funcione corretamente na faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="8fa33-612">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="8fa33-613">Corrigimos um problema ao abrir arquivos de locais no ambiente local com algumas configurações específicas de proxy.</span><span class="sxs-lookup"><span data-stu-id="8fa33-613">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="8fa33-614">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-614">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8fa33-615">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="8fa33-615">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8fa33-616">Esta atualização corrige um problema no Microsoft Word, em que textos com mais de 255 caracteres inseridos durante a aplicação de um rótulo de sensibilidade não poderiam ser subsequentemente identificados e removidos alterando ou removendo a etiqueta se a política de rótulo tiver aplicado um cabeçalho, rodapé ou marca-d ' água.</span><span class="sxs-lookup"><span data-stu-id="8fa33-616">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="8fa33-617">Correção de um problema que elimina panes durante as sessões de entrega do Office e maior confiabilidade na experiência do usuário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-617">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="8fa33-618">Esse bug atualiza o ponto de extremidade da URL do serviço de configuração avançada (ECS).</span><span class="sxs-lookup"><span data-stu-id="8fa33-618">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="8fa33-619">Chamar esse ponto de extremidade mais recente tem uma taxa de sucesso maior para buscar a partir de ECS.</span><span class="sxs-lookup"><span data-stu-id="8fa33-619">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-april-14"></a><span data-ttu-id="8fa33-621">Versão 2002: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="8fa33-621">Version 2002: April 14</span></span>
<span data-ttu-id="8fa33-622">*Versão 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-622">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="8fa33-623">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-623">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="8fa33-624">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="8fa33-624">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-625">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-625">Excel</span></span>

- <span data-ttu-id="8fa33-626">**Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão automaticamente enviados para as células vizinhas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-626">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="8fa33-627">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-627">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="8fa33-628">**Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE e RANDARRAY.</span><span class="sxs-lookup"><span data-stu-id="8fa33-628">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="8fa33-629">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-629">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="8fa33-630">**Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!:** Linha por linha, encontre tudo o que você precisa em uma tabela ou intervalo com o XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="8fa33-630">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="8fa33-631">
  [Saiba mais](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="8fa33-631">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-633">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-633">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-634">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-634">Excel</span></span>

- <span data-ttu-id="8fa33-635">O Excel falharia em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-635">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="8fa33-636">Ao salvar como um arquivo CSV, o Excel poderia mesclar todas as colunas em uma única coluna em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-636">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="8fa33-637">Usar Range.ClearContents em um intervalo de uma planilha protegida pode levar mais tempo do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-637">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="8fa33-638">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="8fa33-638">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="8fa33-639">As macros do VBA que interagem com a faixa de opções podem ser executadas com o conjunto de ScreenUpdating definido como Verdadeiro inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-639">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="8fa33-640">Foi solucionado um problema em que os links externos não eram atualizados durante o preenchimento (preencher abaixo, preencher entre, etc.) se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-640">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="8fa33-641">Em alguns casos, o uso do Application.Evaluate do VBA não funcionava para funções definidas pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-641">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8fa33-642">Solucionamos um problema de desempenho durante a criação de gráficos de modelos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-642">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-643">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-643">Outlook</span></span>

- <span data-ttu-id="8fa33-644">Foi solucionado um problema que fazia com que o Título do Grupo se expandisse inesperadamente em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="8fa33-644">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="8fa33-645">Foi resolvido um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-645">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="8fa33-646">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="8fa33-646">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="8fa33-647">Foi solucionado um problema que fazia com que o botão Salvar na nuvem estivesse ausente nas Ferramentas de anexo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-647">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8fa33-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-648">PowerPoint</span></span>

- <span data-ttu-id="8fa33-649">Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-lo em outro slide em um loop.</span><span class="sxs-lookup"><span data-stu-id="8fa33-649">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="8fa33-650">Project</span><span class="sxs-lookup"><span data-stu-id="8fa33-650">Project</span></span>

- <span data-ttu-id="8fa33-651">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="8fa33-651">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8fa33-652">Correção de um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-652">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-653">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-653">Word</span></span>

- <span data-ttu-id="8fa33-654">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="8fa33-654">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="8fa33-655">Corrigimos um problema com o ajuste de texto em uma tabela.</span><span class="sxs-lookup"><span data-stu-id="8fa33-655">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="8fa33-656">Corrigimos um problema em que não era possível inserir linhas horizontais e centralizar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-656">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="8fa33-658">Versão 2002: 10 de março</span><span class="sxs-lookup"><span data-stu-id="8fa33-658">Version 2002: March 10</span></span>
<span data-ttu-id="8fa33-659">*Versão 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-659">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="8fa33-660">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-660">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="8fa33-662">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="8fa33-662">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8fa33-663">Access</span><span class="sxs-lookup"><span data-stu-id="8fa33-663">Access</span></span>

- <span data-ttu-id="8fa33-664">**Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-664">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="8fa33-665">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-665">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="8fa33-666">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-666">Excel</span></span>

- <span data-ttu-id="8fa33-667">**Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles.</span><span class="sxs-lookup"><span data-stu-id="8fa33-667">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="8fa33-668">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-668">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="8fa33-669">**Encontre o que está procurando:** Pesquise comandos, pessoas, arquivos, fotos, artigos da Web e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-669">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="8fa33-670">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-670">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="8fa33-671">**Faça um Esboço:** Deixe as formas do Office da sua pasta de trabalho com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="8fa33-671">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="8fa33-672">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-672">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8fa33-673">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-673">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8fa33-674">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-674">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="8fa33-675">**Foco no que precisa ser feito:** Selecione Resolver para recolher comentários e dar destaque aos itens abertos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-675">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="8fa33-676">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-676">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="8fa33-677">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-677">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="8fa33-678">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-678">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8fa33-679">**Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel.</span><span class="sxs-lookup"><span data-stu-id="8fa33-679">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="8fa33-680">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-680">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="8fa33-681">**Leia e responda instantaneamente:** Responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="8fa33-681">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="8fa33-682">**Obtenha estatísticas em sua pasta de trabalho:** As Estatísticas da Pasta de Trabalho fornecem uma visão geral do conteúdo de uma pasta de trabalho, para ajudar você a descobrir o conteúdo com mais facilidade.</span><span class="sxs-lookup"><span data-stu-id="8fa33-682">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="8fa33-683">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-683">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8fa33-684">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-684">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8fa33-685">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-685">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="8fa33-686">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-686">Outlook</span></span>

- <span data-ttu-id="8fa33-687">**Conecte sua rede do LinkedIn ao Outlook:** Conecte sua conta do LinkedIn com segurança à sua conta da Microsoft para ver informações de perfis do LinkedIn diretamente no cartão de Pessoas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-687">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="8fa33-688">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-688">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="8fa33-p158">**Todas as opções de criptografia em um só lugar:** Basta ir para Opções > Criptografar para escolher como proteger sua mensagem de email. [Saiba mais](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="8fa33-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="8fa33-691">**O menu Inserir Link no Outlook inserirá um link com a permissão definida pelo administrador do locatário:** um link do Inserir Link MRU no Outlook insere um link que só funcionou para usuários que já tinham permissões.</span><span class="sxs-lookup"><span data-stu-id="8fa33-691">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="8fa33-692">Isso causou uma troca de emails frequente entre os usuários solicitando o acesso a um documento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-692">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="8fa33-693">Atualizamos essa experiência e agora o link é inserido com a permissão padrão definida pelo administrador do locatário. No MSIT, é "A organização pode editar", para que todos os usuários internos que recebem um link compartilhado dessa maneira possam acessá-lo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-693">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="8fa33-694">**Pesquisar com erros de ortografia ou digitação:** O Outlook encontrará o que você está procurando, mesmo quando a ortografia não corresponder.</span><span class="sxs-lookup"><span data-stu-id="8fa33-694">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="8fa33-695">**Emails de phishing fáceis de identificar:** As mensagens de spam e phishing têm uma aparência diferente, para que você possa identificá-las e eliminá-las facilmente na caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-695">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="8fa33-696">**Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.</span><span class="sxs-lookup"><span data-stu-id="8fa33-696">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="8fa33-697">**Deixe-me desenhar:** Rabisque em fotos ou adicione uma Tela de Desenho para enviar seus pensamentos com tinta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-697">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="8fa33-698">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-698">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="8fa33-699">**Veja as mensagens relevantes nos resultados de pesquisa:** o Outlook analisa os termos de pesquisa e mostra as mensagens de email mais relevantes na parte superior dos resultados da pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-699">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="8fa33-700">Você também verá todos os resultados classificados por data, na seção Resultados Principais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-700">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="8fa33-701">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-701">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="8fa33-702">**Obtenha sugestões de locais:** comece a digitar em Local ao agendar compromissos e reuniões, e o Outlook irá sugerir salas, endereços e outros locais recentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-702">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="8fa33-703">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-703">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="8fa33-704">**Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens.</span><span class="sxs-lookup"><span data-stu-id="8fa33-704">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="8fa33-705">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-705">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="8fa33-706">**Veja suas mensagens sob uma perspectiva diferente:** use o botão Sol/Lua para alternar entre planos de fundo claros e escuros no painel de leitura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-706">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="8fa33-707">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-707">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="8fa33-708">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-708">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8fa33-709">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-709">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8fa33-710">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-710">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="8fa33-711">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-711">PowerPoint</span></span>

- <span data-ttu-id="8fa33-712">**Colaboração rápida e em tempo real no PowerPoint:** Colaboração rápida e em tempo real no PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-712">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="8fa33-713">**Novas ferramentas de revisão:** não se preocupe com suas palavras.</span><span class="sxs-lookup"><span data-stu-id="8fa33-713">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="8fa33-714">Agora, o PowerPoint fornece sugestões de gramática e ortografia.</span><span class="sxs-lookup"><span data-stu-id="8fa33-714">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="8fa33-715">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-715">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="8fa33-716">**Legendas em tempo real:** As palavras do apresentador aparecem na tela automaticamente como legendas ou traduzidas para o idioma que escolher.</span><span class="sxs-lookup"><span data-stu-id="8fa33-716">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="8fa33-717">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-717">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="8fa33-p168">**Você calcula, nós formatamos:** Nós trocamos expressões matemáticas difíceis de desenhar por caracteres padrão. Basta escolher Tinta para Matemática e selecionar suas anotações manuscritas para começar.[Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="8fa33-p168">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="8fa33-721">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-721">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="8fa33-722">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-722">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="8fa33-723">**Localize e corrija títulos de slides ausentes:** Títulos de slides reforçam o seu discurso e tornam os seus slides acessíveis a usuários de todas as habilidades.</span><span class="sxs-lookup"><span data-stu-id="8fa33-723">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="8fa33-724">O Verificador de Acessibilidade mostra onde os títulos estão ausentes para que você possa adicioná-los imediatamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-724">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="8fa33-725">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-725">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="8fa33-726">**Faça um Esboço:** deixe as formas do Office da sua apresentação com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="8fa33-726">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="8fa33-727">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-727">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8fa33-728">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-728">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8fa33-729">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-729">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="8fa33-730">**Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem.</span><span class="sxs-lookup"><span data-stu-id="8fa33-730">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="8fa33-731">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-731">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="8fa33-732">**Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-732">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="8fa33-733">Deixá-los ou não ativados depende de você.</span><span class="sxs-lookup"><span data-stu-id="8fa33-733">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="8fa33-734">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-734">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="8fa33-735">**Repe-tinta-ção Instantânea:** Ao escrever à tinta nos slides, aplique uma animação de repetição para reproduzir o desenho real da sua tinta durante a apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="8fa33-735">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="8fa33-736">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-736">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="8fa33-737">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-737">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="8fa33-738">**Otimize sua apresentação para todos:** O Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.</span><span class="sxs-lookup"><span data-stu-id="8fa33-738">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="8fa33-739">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-739">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8fa33-740">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="8fa33-740">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="8fa33-741">**Por que reinventar quando você pode reutilizar?:** economize tempo reutilizando slides que você criou ou que outras pessoas compartilharam com você.</span><span class="sxs-lookup"><span data-stu-id="8fa33-741">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="8fa33-742">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-742">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="8fa33-743">**Transforme tinta manuscrita em formas, texto ou expressões matemáticas no PowerPoint para Office 365:** Vá de tinta de forma livre para formas, texto ou uma expressão matemática com apenas alguns traços.</span><span class="sxs-lookup"><span data-stu-id="8fa33-743">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="8fa33-744">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-744">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8fa33-745">**Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-745">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="8fa33-746">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-746">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="8fa33-747">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-747">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8fa33-748">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-748">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8fa33-749">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-749">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="8fa33-750">Visio</span><span class="sxs-lookup"><span data-stu-id="8fa33-750">Visio</span></span>

- <span data-ttu-id="8fa33-751">**Voltando para a cena do crime:** Use os novos estênceis de Evidência, Interno e Externo no modelo de Investigação de Cena de Crime para recriar cenas de crimes em detalhes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-751">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="8fa33-752">**Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha.</span><span class="sxs-lookup"><span data-stu-id="8fa33-752">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="8fa33-753">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-753">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="8fa33-754">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-754">Word</span></span>

- <span data-ttu-id="8fa33-755">**O Editor de Currículos se une ao Assistente de Currículos do LinkedIn:** O Editor de Currículos oferece uma seleção de verificações gramaticais e de estilo especialmente adaptadas para currículos, para tornar a sua escrita mais precisa e profissional.</span><span class="sxs-lookup"><span data-stu-id="8fa33-755">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="8fa33-756">**Corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D:** corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="8fa33-756">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="8fa33-757">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-757">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="8fa33-758">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-758">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="8fa33-759">**Colabore em cores:** Comentários e alterações são codificados por cores por colaborador, para que seja fácil ver quem está entre seus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="8fa33-759">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="8fa33-760">**Edite documentos habilitados para macro de maneira colaborativa:** Salve arquivos docm no OneDrive for Business e edite-os com seus colaboradores em tempo real.</span><span class="sxs-lookup"><span data-stu-id="8fa33-760">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="8fa33-761">**Aperfeiçoamentos de coautoria**: melhor desempenho do Word durante a coautoria em documentos com alterações controladas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-761">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="8fa33-762">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-762">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8fa33-763">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="8fa33-763">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8fa33-764">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-764">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="8fa33-765">**Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.</span><span class="sxs-lookup"><span data-stu-id="8fa33-765">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="8fa33-766">**Faça um Esboço:** deixe as formas do Office do seu documento com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="8fa33-766">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="8fa33-767">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-767">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8fa33-768">**Apagar com precisão:** Escolha entre dois tamanhos de borracha para corrigir pequenas imperfeições à tinta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-768">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="8fa33-769">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-769">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="8fa33-770">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-770">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8fa33-771">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-771">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="8fa33-772">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-772">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="8fa33-773">**Melhorias na coautoria** Confiabilidade aprimorada durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="8fa33-773">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="8fa33-774">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="8fa33-774">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="8fa33-775">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-775">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="8fa33-776">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-776">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8fa33-777">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="8fa33-777">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="8fa33-778">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="8fa33-778">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-781">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-781">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8fa33-782">Acessar</span><span class="sxs-lookup"><span data-stu-id="8fa33-782">Access</span></span>

- <span data-ttu-id="8fa33-783">Esta atualização corrige um problema no Microsoft Access que pode causar o erro “A consulta está corrompida” quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada no SQL.</span><span class="sxs-lookup"><span data-stu-id="8fa33-783">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="8fa33-784">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-784">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="8fa33-785">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="8fa33-785">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="8fa33-786">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="8fa33-786">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="8fa33-787">Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-787">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="8fa33-788">Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-788">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="8fa33-789">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-789">Excel</span></span>

- <span data-ttu-id="8fa33-790">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-790">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="8fa33-791">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="8fa33-791">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="8fa33-792">Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-792">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="8fa33-793">Esta atualização corrige um problema que fazia com que barra de fórmulas exibisse texto em uma fonte diferente da esperada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-793">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="8fa33-794">A funcionalidade Texto em Coluna pode falhar para algumas localidades.</span><span class="sxs-lookup"><span data-stu-id="8fa33-794">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="8fa33-795">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-795">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="8fa33-796">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="8fa33-796">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8fa33-797">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-797">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="8fa33-798">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="8fa33-798">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="8fa33-799">A funcionalidade Texto em Coluna pode falhar em algumas localizações.</span><span class="sxs-lookup"><span data-stu-id="8fa33-799">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="8fa33-800">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-800">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="8fa33-801">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="8fa33-801">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8fa33-802">Foi corrigido um problema que alguns usuários podem ter tido com objetos inseridos e vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="8fa33-802">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="8fa33-803">Corrigimos o menu do botão direito do mouse de Gráficos Dinâmicos para habilitar a opção Mostrar Detalhes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-803">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="8fa33-804">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-804">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="8fa33-805">Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="8fa33-805">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="8fa33-806">Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.</span><span class="sxs-lookup"><span data-stu-id="8fa33-806">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="8fa33-807">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="8fa33-807">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="8fa33-808">Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-808">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-809">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-809">Outlook</span></span>

- <span data-ttu-id="8fa33-810">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-810">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="8fa33-811">Solucionamos um problema que fazia com que os usuários experimentassem travamentos no Outlook ao recuperar as configurações da Nuvem.</span><span class="sxs-lookup"><span data-stu-id="8fa33-811">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="8fa33-812">Foi corrigido um problema que provocava um alinhamento inadequado da caixa de pesquisa no modo de DPI alto.</span><span class="sxs-lookup"><span data-stu-id="8fa33-812">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="8fa33-813">Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-813">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="8fa33-814">Solucionamos um problema que fazia com que os usuários vissem os e-mails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="8fa33-814">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="8fa33-815">Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.</span><span class="sxs-lookup"><span data-stu-id="8fa33-815">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="8fa33-816">Consertamos um problema que podia impedir que os arquivos fossem salvos em um local do WebDAV.</span><span class="sxs-lookup"><span data-stu-id="8fa33-816">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="8fa33-817">Corrigido um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="8fa33-817">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="8fa33-818">Solucionamos um problema que fazia com que aplicativos de terceiros não conseguissem enviar emails.</span><span class="sxs-lookup"><span data-stu-id="8fa33-818">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="8fa33-819">Resolvido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-819">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="8fa33-820">Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="8fa33-820">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="8fa33-821">Solucionamos um problema que fazia o Outlook sincronizar inesperadamente todos os emails, mesmo quando o controle deslizante de sincronização estivesse definido com uma configuração menor.</span><span class="sxs-lookup"><span data-stu-id="8fa33-821">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="8fa33-822">Solucionamos um problema que fez que usuários com tema escuro vissem o “De” suspenso mostrar texto branco sobre fundo branco.</span><span class="sxs-lookup"><span data-stu-id="8fa33-822">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="8fa33-823">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.</span><span class="sxs-lookup"><span data-stu-id="8fa33-823">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="8fa33-824">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-824">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="8fa33-825">Solucionado um problema que fazia com que a opção desativar o realce do item sinalizado deixasse de ser respeitada em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="8fa33-825">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="8fa33-826">Resolvido um problema que fazia com que usuários vissem um aviso “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo de Regras.</span><span class="sxs-lookup"><span data-stu-id="8fa33-826">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="8fa33-827">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-827">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="8fa33-828">Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-828">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="8fa33-829">Solucionamos um problema que podia resultar em uma falha ao exibir o mesmo item em várias janelas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-829">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="8fa33-830">Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-830">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="8fa33-831">Solucionamos um problema que fazia com que os usuários não conseguissem abrir algumas instâncias de itens de calendário recorrentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-831">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="8fa33-832">Solucionamos um problema que fazia com que os usuários com caixas de correio em servidores do Exchange 2010 tivessem problemas ao adicionar anexos a itens de calendário.</span><span class="sxs-lookup"><span data-stu-id="8fa33-832">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="8fa33-833">Solucionamos um problema que fazia com que os usuários tivessem problemas ao responder a mensagens assinadas digitalmente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-833">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="8fa33-834">Corrigimos um problema que fazia com que o campo Local nas reuniões fosse atualizado inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-834">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="8fa33-835">Solucionamos um problema que fazia com que as vírgulas no campo de local de uma reunião se transformassem em pontos-e-vírgulas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-835">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="8fa33-836">Solucionamos um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após a limpeza.</span><span class="sxs-lookup"><span data-stu-id="8fa33-836">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="8fa33-837">Solucionamos problemas relacionados a reuniões e compromissos no fuso horário de Brasília.</span><span class="sxs-lookup"><span data-stu-id="8fa33-837">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="8fa33-838">Foi corrigido um problema que fazia com que emails fossem enviados inesperadamente ao pressionar a tecla “S” após fechar o painel do verificador de acessibilidade.</span><span class="sxs-lookup"><span data-stu-id="8fa33-838">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="8fa33-839">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="8fa33-839">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="8fa33-840">Solucionamos um problema que fazia com que suplementos da Web acessassem mensagens com Gerenciamento de Direitos Digitais.</span><span class="sxs-lookup"><span data-stu-id="8fa33-840">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="8fa33-841">Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="8fa33-841">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="8fa33-842">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-842">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8fa33-843">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-843">PowerPoint</span></span>

- <span data-ttu-id="8fa33-844">Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-844">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="8fa33-845">Solucionamos um problema que pode ter causado uma falha ao usar o menu de contexto em comentários de PPT herdados.</span><span class="sxs-lookup"><span data-stu-id="8fa33-845">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="8fa33-846">Projeto</span><span class="sxs-lookup"><span data-stu-id="8fa33-846">Project</span></span>

- <span data-ttu-id="8fa33-847">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="8fa33-847">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="8fa33-848">Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="8fa33-848">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="8fa33-849">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="8fa33-849">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8fa33-850">Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="8fa33-850">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-851">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-851">Word</span></span>

- <span data-ttu-id="8fa33-852">Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-852">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="8fa33-853">O organizador de blocos de construção pode exibir um alerta inválido: “Você modificou estilos, blocos de construção”.</span><span class="sxs-lookup"><span data-stu-id="8fa33-853">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-854">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-854">Office Suite</span></span>

- <span data-ttu-id="8fa33-855">Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.</span><span class="sxs-lookup"><span data-stu-id="8fa33-855">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="8fa33-856">Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.</span><span class="sxs-lookup"><span data-stu-id="8fa33-856">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="8fa33-857">Correção de um bug na configuração de Data Limite de Atualização ODT e GPO, em que o prazo relativo só funcionava na primeira vez que era definido. A correção permite definir a data limite relativa nas atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="8fa33-857">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="8fa33-858">Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="8fa33-858">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="8fa33-859">Foi corrigido um problema em que, quando vários documentos da mesma biblioteca do SharePoint estivessem abertos no Word/Excel/PowerPoint, somente o primeiro documento aberto era verificado quanto à conformidade com Políticas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-859">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a><span data-ttu-id="8fa33-861">Versão 1908: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="8fa33-861">Version 1908: February 11</span></span>
<span data-ttu-id="8fa33-862">*Versão 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-862">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="8fa33-863">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-863">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-865">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-865">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-866">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-866">Excel</span></span>

- <span data-ttu-id="8fa33-867">Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.</span><span class="sxs-lookup"><span data-stu-id="8fa33-867">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="8fa33-868">Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.</span><span class="sxs-lookup"><span data-stu-id="8fa33-868">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="8fa33-869">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="8fa33-869">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8fa33-870">Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.</span><span class="sxs-lookup"><span data-stu-id="8fa33-870">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="8fa33-871">Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-871">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="8fa33-872">Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.</span><span class="sxs-lookup"><span data-stu-id="8fa33-872">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="8fa33-873">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-873">Outlook</span></span>

- <span data-ttu-id="8fa33-874">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-874">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="8fa33-875">Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.</span><span class="sxs-lookup"><span data-stu-id="8fa33-875">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="8fa33-876">Solucionado um problema que fazia com que os usuários experimentassem um travamento na tela Carregando perfil ao iniciar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fa33-876">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="8fa33-877">Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.</span><span class="sxs-lookup"><span data-stu-id="8fa33-877">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="8fa33-878">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="8fa33-878">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="8fa33-879">[Aqui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.</span><span class="sxs-lookup"><span data-stu-id="8fa33-879">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="8fa33-880">Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.</span><span class="sxs-lookup"><span data-stu-id="8fa33-880">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8fa33-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-881">PowerPoint</span></span>

- <span data-ttu-id="8fa33-882">Melhorou um cenário de copiar e colar Copiando a Forma no slide do powerpoint e colando em outro slide em um loop poderia falhar, com exceção.</span><span class="sxs-lookup"><span data-stu-id="8fa33-882">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="8fa33-883">Corrigido um problema que estava causando um desempenho mais lento entre os usuários da colaboração.</span><span class="sxs-lookup"><span data-stu-id="8fa33-883">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="8fa33-884">Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-884">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="8fa33-885">Corrigimos um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="8fa33-885">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="8fa33-886">Project</span><span class="sxs-lookup"><span data-stu-id="8fa33-886">Project</span></span>

- <span data-ttu-id="8fa33-887">Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-887">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="8fa33-888">Word</span><span class="sxs-lookup"><span data-stu-id="8fa33-888">Word</span></span>

- <span data-ttu-id="8fa33-889">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="8fa33-889">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-890">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-890">Office Suite</span></span>

- <span data-ttu-id="8fa33-891">Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.</span><span class="sxs-lookup"><span data-stu-id="8fa33-891">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a><span data-ttu-id="8fa33-893">Versão 1908:14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="8fa33-893">Version 1908: January 14</span></span>
<span data-ttu-id="8fa33-894">*Versão 1908 (Build 11929,20562)*</span><span class="sxs-lookup"><span data-stu-id="8fa33-894">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="8fa33-895">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8fa33-895">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="8fa33-897">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="8fa33-897">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8fa33-898">Excel</span><span class="sxs-lookup"><span data-stu-id="8fa33-898">Excel</span></span>

- <span data-ttu-id="8fa33-899">A dica de tecla holandesa para o título do documento foi alterada para Alt-G.</span><span class="sxs-lookup"><span data-stu-id="8fa33-899">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="8fa33-900">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="8fa33-900">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="8fa33-901">Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.</span><span class="sxs-lookup"><span data-stu-id="8fa33-901">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="8fa33-902">Outlook</span><span class="sxs-lookup"><span data-stu-id="8fa33-902">Outlook</span></span>

- <span data-ttu-id="8fa33-903">Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-903">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="8fa33-904">Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.</span><span class="sxs-lookup"><span data-stu-id="8fa33-904">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="8fa33-905">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="8fa33-905">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8fa33-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8fa33-906">PowerPoint</span></span>

- <span data-ttu-id="8fa33-907">Corrigimos um problema que poderia criar mestres ao copiar um slide de uma apresentação para outra.</span><span class="sxs-lookup"><span data-stu-id="8fa33-907">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="8fa33-908">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada</span><span class="sxs-lookup"><span data-stu-id="8fa33-908">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="8fa33-909">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="8fa33-909">Office Suite</span></span>

- <span data-ttu-id="8fa33-910">Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado.</span><span class="sxs-lookup"><span data-stu-id="8fa33-910">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="8fa33-911">Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.</span><span class="sxs-lookup"><span data-stu-id="8fa33-911">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="8fa33-912">Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.</span><span class="sxs-lookup"><span data-stu-id="8fa33-912">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="8fa33-914">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="8fa33-914">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-fevereiro-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

---
title: Notas de Versão para o Canal Beta
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece a lista mais recente de novos recursos, correções ou problemas conhecidos para o público-alvo do Insider − Modo Rápido.
ms.openlocfilehash: 12cfa4a285201c2d3839abfd93c5085fa5ea1d13
ms.sourcegitcommit: a58e0b1ff6d1170fabfd95ba7f25e2eb1e4fad0a
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/17/2020
ms.locfileid: "45166709"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="6b5b8-103">Notas de Versão para o Canal Beta</span><span class="sxs-lookup"><span data-stu-id="6b5b8-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="6b5b8-104">Este artigo contém notas de versão para compilações do Canal Beta para o Word, Excel, PowerPoint, Outlook, Access e Project para a área de trabalho do Windows.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="6b5b8-105">Toda semana, destacaremos novos recursos interessantes, correções importantes e quaisquer problemas significativos sobre os quais desejamos informá-lo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="6b5b8-106">Em geral, disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Beta ao longo do tempo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="6b5b8-107">Isso nos permite garantir que tudo esteja funcionando bem antes de liberarmos o recurso para um público maior.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="6b5b8-108">Portanto, caso você não veja algo descrito abaixo, não se preocupe.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="6b5b8-109">Estamos fazendo algumas alterações nos canais de atualização para os Aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="6b5b8-110">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="6b5b8-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="6b5b8-111">As notas de versão são publicadas semanalmente e podem ser uma compilação de várias compilações.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="6b5b8-112">A data de publicação das notas de versão pode não corresponder com a data de lançamento da compilação atual.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NÃO REMOVA)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

## <a name="version-2008-july-17"></a><span data-ttu-id="6b5b8-115">Versão 2008: 17 de julho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-115">Version 2008: July 17</span></span>
<span data-ttu-id="6b5b8-116">*Versão 2008 (Compilação 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-116">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-118">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-119">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-119">Excel</span></span>

- <span data-ttu-id="6b5b8-120">Consertamos um problema em que a qualquer momento em que um gráfico dinâmico com linhas de preenchimento ocultas era salvo e reaberto, as linhas de preenchimento se tornavam visíveis.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-120">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="6b5b8-121">Consertamos um problema em que os gráficos nem sempre eram atualizados conforme o esperado quando o ' ForceFullCalculation ' estava habilitado via VBA para a pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-121">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-122">Outlook</span></span>

- <span data-ttu-id="6b5b8-123">Resolvemos um problema em torno da criação de vários perfis no Outlook a partir do mesmo domínio de email.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-123">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="6b5b8-124">Resolve um problema que provocou a falha da exibição do ícone de bloqueio no cabeçalho de mensagens criptografadas S/MIME.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-124">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="6b5b8-125">Soluciona um problema que causou a remoção dos anexos de mensagens S/MIME quando enviadas sem criptografia.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-125">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="6b5b8-126">Corrige um problema que provocou mensagens de texto S/MIME sem formatação se tornarem truncadas ao enviar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-126">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="6b5b8-127">Resolve um problema que causa a corrupção de um arquivo ao enviar um email S/MIME não criptografado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-127">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="6b5b8-128">Soluciona um problema que fazia com que os usuários não conseguissem salvar anexos do OneDrive de fora de seu locatário em seu computador local ao selecionar a opção 'Salvar' na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-128">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="6b5b8-129">Resolve um problema que fazia com que os destinatários não conseguirem salvar mensagens protegidas por direitos, mesmo quando a permissão para salvar era concedida pelo remetente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-129">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="6b5b8-130">Corrige um problema que fazia com que as etiquetas de algumas opções de Pesquisa Avançada fossem truncadas em alguns idiomas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-130">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-131">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-131">Project</span></span>

- <span data-ttu-id="6b5b8-132">Resolvemos um problema em que as tarefas listadas no modo de exibição Quadro de Tarefas não estavam sincronizadas com as do diálogo Atribuir Recursos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-132">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="6b5b8-133">Corrigimos um problema no qual, se você copiasse e colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-133">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-134">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-134">Word</span></span>

- <span data-ttu-id="6b5b8-135">Consertamos um problema em que o comando 'Editor' era desabilitado quando o foco estava em uma caixa de texto de comentário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-135">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="6b5b8-136">Resolvemos um problema em que o comando 'Mostrar Marcação' era desabilitado quando o foco estava em uma caixa de texto de comentário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-136">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="6b5b8-137">Corrigimos um problema no XML personalizado no qual o estado dos comentários poderia ser perdido ao abrir o documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-137">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-138">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-138">Office Suite</span></span>

- <span data-ttu-id="6b5b8-139">Consertamos um problema em que, após o usuário abrir uma nova janela de aplicativo na barra de tarefas e criar um novo documento em branco, arquivos adicionais eram criados.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-139">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="6b5b8-140">Resolvemos um problema em que, se um usuário estava editando um documento mas teve permissões perdidas, não estávamos notificando sobre o usuário de que ele tinha que se autenticar novamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-140">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-10"></a><span data-ttu-id="6b5b8-142">Versão 2008: 10 de julho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-142">Version 2008: July 10</span></span>
<span data-ttu-id="6b5b8-143">*Versão 2008 (Build 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-143">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-145">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-145">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-146">Outlook</span></span>

- <span data-ttu-id="6b5b8-147">Consertamos um problema em que a opção Permitir Encaminhamento estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, caso a pasta compartilhada Download não tivesse sido verificada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-147">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="6b5b8-148">Consertamos um problema que exibia o botão imprimir em um estado desabilitado, mesmo que o usuário tivesse as permissões de impressão apropriadas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-148">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-149">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-149">Project</span></span>

- <span data-ttu-id="6b5b8-150">Consertamos um problema no qual quando você tentava salvar um PDF/XPS do Project em uma biblioteca de documentos do SharePoint, nada acontecia.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-150">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-151">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-151">Word</span></span>

- <span data-ttu-id="6b5b8-152">Consertamos um problema em que o Word deixava de responder depois de colar um texto e uma imagem na caixa de comentários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-152">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="6b5b8-153">Consertamos um problema em que o botão "Novo comentário" era desabilitado após a exclusão do último comentário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-153">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-july-03"></a><span data-ttu-id="6b5b8-155">Versão 2007: 03 de julho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-155">Version 2007: July 03</span></span>
<span data-ttu-id="6b5b8-156">*Versão 2007 (Build 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-156">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-158">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-158">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-159">Outlook</span></span>

- <span data-ttu-id="6b5b8-160">**Crie pesquisas no Outlook com a Pesquisa Rápida:** Crie facilmente uma pesquisa, colete votos e exiba os resultados em um email [Saiba mais](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-160">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="6b5b8-161">**Novo localizador de sala:** Pesquisar salas de conferência por diferentes recursos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-161">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-164">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-164">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-165">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-165">Excel</span></span>

- <span data-ttu-id="6b5b8-166">Consertamos um problema em que as tabelas do modelo de dados criadas em determinadas versões do Excel não podiam ser vistas na 'Visualização de Tabela', embora a consulta associada à tabela não tivesse sido editada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-166">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="6b5b8-167">Consertamos um problema em que a desabilitar "Ignorar referências Relativas/absolutas" na caixa de diálogo Definir Nome \ Aplicar Nomes fazia com que as fórmulas não funcionassem.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-167">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="6b5b8-168">Consertamos um problema em que a limpeza de um filtro de dados avançado podia ocasionar a perda da formatação da tabela.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-168">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="6b5b8-169">Consertamos um problema em que o caminho completo de um documento PDF inserido era mostrado na legenda do documento, em vez de apenas o nome do arquivo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-169">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="6b5b8-170">Consertamos um problema em que depois de desabilitar o conector em nuvem Wolfram e, depois, salvar e abrir novamente uma pasta de trabalho do Excel, podia resultar em uma falha.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-170">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="6b5b8-171">Consertamos um problema em que a inicialização do Excel com o suplemento Solver habilitado resultava em uma falha.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-171">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-172">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-172">Outlook</span></span>

- <span data-ttu-id="6b5b8-173">Consertamos um problema em que o Outlook travava se houvesse mais de 130 destinatários na linha "Para" e também melhoramos o desempenho da renderização do texto.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-173">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="6b5b8-174">Consertamos um problema na barra "Tarefas Pendentes", no qual os eventos que se estendiam por mais de dois dias exibiam a mesma hora de término para todos os dias subsequentes.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-174">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="6b5b8-175">Consertamos um problema que fazia com que os usuários do Outlook vissem a lista de mensagens parar de responder por vários minutos após o uso de calendários compartilhados.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-175">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-176">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-176">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-177">Consertamos um problema em que colar HTML em uma área de texto em um slide resultava que fosse colado em uma caixa de texto criada na parte superior do slide.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-177">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="6b5b8-178">Consertamos um problema em que selecionar todos os slides no Modo de Exibição do Apresentador e, em seguida, sair do modo de exibição do Apresentador usando Alt+Tab e retornar à apresentação de slides e clicar em "Finalizar Apresentação" poderia resultar em uma exceção não tratada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-178">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-179">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-179">Project</span></span>

- <span data-ttu-id="6b5b8-180">Consertamos um problema em que o Project pode falhar ao abrir determinados arquivos XML.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-180">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="6b5b8-181">Consertamos um problema em que você não conseguia abrir um arquivo do Project a partir de uma biblioteca de documentos do SharePoint se a biblioteca estivesse no modo moderno.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-181">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="6b5b8-182">Consertamos um problema em que os projetos não podiam ser abertos no cliente de área de trabalho do Project a partir do Project Web App, se a URL terminasse em '.com'.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-182">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-183">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-183">Word</span></span>

- <span data-ttu-id="6b5b8-184">Consertamos um problema durante o modo de coautoria quando há um conflito de mesclagem e o usuário já optou por descartar as alterações. Não mais exibimos a opção para salvar ou descartar alterações.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-184">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="6b5b8-185">Consertamos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, fazia com que o arquivo fosse salvo com a extensão .docx e com o nome de arquivo 'WRO0004.docx', independentemente do que o usuário inseriu, tornando o documento inutilizável.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-185">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-26"></a><span data-ttu-id="6b5b8-187">Versão 2007: 26 de junho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-187">Version 2007: June 26</span></span>
<span data-ttu-id="6b5b8-188">*Versão 2007 (Build 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-188">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-190">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-190">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6b5b8-191">Access</span><span class="sxs-lookup"><span data-stu-id="6b5b8-191">Access</span></span>

- <span data-ttu-id="6b5b8-192">Consertamos um problema em que o gerenciador de tabelas vinculadas solicitava uma chave primária se uma tabela SQL vinculada tivesse sido atualizada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-192">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="6b5b8-193">Consertamos um problema em que as consultas no Editor de Consultas rolavam para fora da área de visualização. </span><span class="sxs-lookup"><span data-stu-id="6b5b8-193">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="6b5b8-194">Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. </span><span class="sxs-lookup"><span data-stu-id="6b5b8-194">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-195">Outlook</span></span>

- <span data-ttu-id="6b5b8-196">Consertamos um problema em que os usuários não conseguiam 'Enviar Como' ou 'Enviar em nome' de uma lista de distribuição.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-196">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="6b5b8-197">Consertamos um problema em que inserir uma imagem embutida em uma mensagem e, em seguida, salvar a mensagem como um rascunho resultava em um redimensionamento da imagem.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-197">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="6b5b8-198">Consertamos um problema que fazia com que o corpo de uma mensagem de NDR mudasse de Unicode para ASCII após editar o assunto.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-198">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-199">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-199">Project</span></span>

- <span data-ttu-id="6b5b8-200">Consertamos um problema em que os links do Planner do Project na Nuvem da Comunidade Governamental haviam sido desabilitados.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-200">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-201">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-201">Office Suite</span></span>

- <span data-ttu-id="6b5b8-202">Consertamos um problema em que o texto inserido em um Elemento Gráfico Vetorial Escalonável (SVG) ficava ilegível após inseri-lo em um arquivo do Word, Excel ou PowerPoint, salvando e fechando o arquivo e reabrindo o arquivo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-202">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-19"></a><span data-ttu-id="6b5b8-204">Versão 2007: 19 de junho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-204">Version 2007: June 19</span></span>
<span data-ttu-id="6b5b8-205">*Versão 2007 (Build 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-205">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-207">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-207">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-208">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-208">Excel</span></span>

- <span data-ttu-id="6b5b8-209">Consertamos um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar uma pasta de trabalho no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-209">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="6b5b8-210">Consertamos um problema em que as pastas de trabalho eram somente leitura quando o arquivo só era recomendável como somente leitura.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-210">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-211">Outlook</span></span>

- <span data-ttu-id="6b5b8-212">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-212">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="6b5b8-213">Consertamos um problema que fazia com que os usuários vissem o seguinte erro ao fechar um compromisso que foi salvo anteriormente: "O item não pode ser salvo porque foi alterado por outro usuário ou em outra janela.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-213">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="6b5b8-214">Deseja fazer uma cópia na pasta padrão para o item?"</span><span class="sxs-lookup"><span data-stu-id="6b5b8-214">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="6b5b8-215">Consertamos um problema em que as datas no Minicalendário falhavam ao exibir em negrito para os usuários no Japão.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-215">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="6b5b8-216">Consertamos um problema que impedia que lembretes de calendário mostrassem os horários exatos para reuniões que aconteceriam em menos de uma semana.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-216">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-217">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-218">Consertamos um problema em que o indicador de cor de presença de um usuário não era atualizado na galeria de coautoria durante uma sessão de coautoria em tempo real.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-218">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-219">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-219">Project</span></span>

- <span data-ttu-id="6b5b8-220">Consertamos um problema em que, se as tarefas de duração fixa estiverem em 100% concluídas, mas o término real não for especificado, a % concluída da tarefa exibia menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-220">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-221">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-221">Word</span></span>

- <span data-ttu-id="6b5b8-222">Consertamos um problema em que a cor do hiperlink HTML não estava sendo processada corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-222">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-223">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-223">Office Suite</span></span>

- <span data-ttu-id="6b5b8-224">Consertamos um problema em que URLs que não eram baseadas em http ou https não eram exibidas na lista de Mais Usados Recentemente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-224">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-12"></a><span data-ttu-id="6b5b8-226">Versão 2007: 12 de junho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-226">Version 2007: June 12</span></span>
<span data-ttu-id="6b5b8-227">*Versão 2007 (Build 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-227">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-229">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-229">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-230">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-230">Excel</span></span>

- <span data-ttu-id="6b5b8-231">**Obtenha Dados da Organização com o Power BI usando Tipos de Dados:** Os tipos de dados do Excel no Power BI agora estão sendo disponibilizados para os participantes do programa Office Insider em organizações com o Office 365 E5/A5 ou o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-231">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="6b5b8-232">Obter as informações necessárias e atualizá-las facilmente é fundamental para muitos fluxos de trabalho diários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-232">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="6b5b8-233">Estamos oferecendo acesso às informações da sua empresa ou organização a partir do Power BI como tipo de dados no Excel, o amplia a capacidade de inserir informações vinculadas nas suas planilhas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-233">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="6b5b8-234">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-234">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="6b5b8-235">Ver detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-235">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-238">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-238">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6b5b8-239">Access</span><span class="sxs-lookup"><span data-stu-id="6b5b8-239">Access</span></span>

- <span data-ttu-id="6b5b8-240">Consertamos um problema que fazia com que o Microsoft Access não conseguisse identificar uma Coluna de Identidade em uma tabela do Servidor SQL vinculada, o que poderia fazer com que as linhas fossem relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-240">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-241">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-241">Excel</span></span>

- <span data-ttu-id="6b5b8-242">Consertamos um problema em que as linhas de grade principais de gráficos de radar não podiam ser formatadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-242">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-243">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-243">Project</span></span>

- <span data-ttu-id="6b5b8-244">Consertamos um problema em que o evento ProjectBeforeTaskChange não era acionado quando havia uma alteração na tarefa resumo do projeto ou no campo início/tarefa do projeto.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-244">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="6b5b8-245">Consertamos um problema em que uma redefinição de linha de base ou uma atualização poderia alterar os recursos de custo/trabalho e a linha de base poderia refletir valores de orçamento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-245">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-246">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-246">Word</span></span>

- <span data-ttu-id="6b5b8-247">Consertamos um problema em que a capacidade de limpar a formatação dentro do Painel comentários por meio do botão Limpar Formatação na Faixa de Opções do Office não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-247">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="6b5b8-248">Consertamos um problema em que alterar o tamanho de uma tabela quando a régua não é exibida fazia com que outros aplicativos executados em segundo plano começassem a piscar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-248">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="6b5b8-249">Consertamos um problema em que, em modo de coautoria, as respostas a comentários, às vezes, não apareciam no painel comentários, mas ficavam visíveis no painel revisões.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-249">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="6b5b8-250">Consertamos um problema em que o Word tinha uma lista com mais de 50 documentos abertos com frequência e, depois que você salvava e abria um documento, um histórico de revisão era exibido, ainda que nenhuma revisão tivesse sido realizada no documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-250">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-june-05"></a><span data-ttu-id="6b5b8-252">Versão 2006: 05 de junho</span><span class="sxs-lookup"><span data-stu-id="6b5b8-252">Version 2006: June 05</span></span>
<span data-ttu-id="6b5b8-253">*Versão 2006 (Build 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-253">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-255">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-255">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-256">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-256">Excel</span></span>

- <span data-ttu-id="6b5b8-257">**Classificar/filtrar enquanto estiver colaborando no Excel:** Agora você pode classificar e filtrar o arquivo do Excel e colaborar com outras pessoas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-257">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="6b5b8-258">Esse novo recurso impede que você seja afetado pelas classificações e filtros de outros usuários durante a coautoria do documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-258">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="6b5b8-259">**Crie Tabelas Dinâmicas a partir de Conjuntos de Dados no Power BI no Excel:** Você pode criar tabelas dinâmicas no Excel conectadas a conjuntos de dados armazenados no Power BI com alguns cliques.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-259">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="6b5b8-260"> Isso permite que você obtenha o melhor das Tabelas Dinâmicas e do Power BI.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-260"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="6b5b8-261">Calcule, resuma e analise seus dados com Tabelas Dinâmicas a partir dos conjuntos de dados seguros do Power BI.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-261">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="6b5b8-262">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-262">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="6b5b8-263">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-263">Outlook</span></span>

- <span data-ttu-id="6b5b8-264">**Reabra rapidamente os itens de uma sessão anterior:** Adicionamos a opção de reabrir rapidamente os itens de uma sessão anterior do Outlook.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-264">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="6b5b8-265">Se o Outlook falhar ou você fechá-lo, agora será possível reiniciar rapidamente os itens quando você reabrir o aplicativo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-265">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="6b5b8-266">Esse recurso não está habilitado por padrão.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-266">This feature is on by default.</span></span> <span data-ttu-id="6b5b8-267">Para desativá-lo, vá até Opções > Gerais > Opções de Inicialização.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-267">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-270">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-270">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-271">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-271">Excel</span></span>

- <span data-ttu-id="6b5b8-272">Consertamos um problema em que os valores personalizados no eixo do gráfico não eram aplicados corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-272">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="6b5b8-273">Consertamos um problema em que as planilhas que continham várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-273">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-274">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-274">Outlook</span></span>

- <span data-ttu-id="6b5b8-275">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-275">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="6b5b8-276">Consertamos um problema em que exibir um modelo ao redigir uma nova mensagem de email resultaria em uma falha.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-276">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="6b5b8-277">Resolvemos um problema em que os usuários não conseguiam acessar as pastas públicas do Exchange 2010 após a versão 1911 do Outlook.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-277">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="6b5b8-278">Consertamos um problema em que o botão Categorizar para calendários de grupo na Faixa de Opções do Office estava desabilitado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-278">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="6b5b8-279">Consertamos um problema que fazia com que os usuários com contatos conflitantes experimentassem falhas no Outlook.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-279">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="6b5b8-280">Consertamos um problema que resultava na falta do menu suspenso Arquivo Online em propriedades da pasta para usuários em monitores de DPI alto.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-280">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="6b5b8-281">Consertamos um problema que fazia com que os usuários experimentassem uma falha no Outlook ao trabalhar com hiperlinks em emails de Texto sem Formatação.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-281">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="6b5b8-282">Consertamos um problema que fazia com que o Outlook fosse incapaz de analisar os nomes de arquivo longos codificados com o RFC2231.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-282">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="6b5b8-283">Consertamos um problema que estava fazendo com que os usuários do Outlook experimentassem travamentos intermitentes ao usar leitores de tela.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-283">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-284">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-285">Consertamos um problema com a abertura de arquivos configurados pelo servidor com autenticação baseada em formulários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-285">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="6b5b8-286">Consertamos um problema em que os arquivos do PowerPoint com gráficos/pastas de trabalho inseridas poderiam resultar em falhas ao salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-286">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="6b5b8-287">Consertamos um problema em que um painel de Comentários fechado pelo usuário abria automaticamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-287">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="6b5b8-288">Consertamos um problema em que o editor de slide de um slide poderia se sobrepor ao próximo slide.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-288">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-289">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-289">Project</span></span>

- <span data-ttu-id="6b5b8-290">Consertamos um problema que impedia que tarefas órfãs fossem excluídas ou reatribuídas após o plano pai ser excluído.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-290">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-291">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-291">Word</span></span>

- <span data-ttu-id="6b5b8-292">Consertamos um problema em que os carimbos de data/hora nos painéis de Comentários não eram baseados no tempo de localidade do sistema.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-292">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="6b5b8-293">Consertamos um problema em que os comentários entre o aplicativo Web e o aplicativo da área de trabalho não estavam sincronizados.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-293">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version2006may29"></a><span data-ttu-id="6b5b8-295">Versão 2006: 29 de maio</span><span class="sxs-lookup"><span data-stu-id="6b5b8-295">Version 2006: May 29</span></span>
<span data-ttu-id="6b5b8-296">*Versão 2006 (Build 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-296">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="6b5b8-297">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-297">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-298">Outlook</span></span>

- <span data-ttu-id="6b5b8-299">**Botões adicionais adicionados às notificações do sistema do Outlook:** Os botões de Ação Rápida agora aparecem nas notificações do Outlook ao executar o Outlook no Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-299">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-300">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-300">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-301">**Melhor desempenho de Streaming de vídeo no PowerPoint:** Fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-301">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="6b5b8-302">Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-302">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolvedissues"></a><span data-ttu-id="6b5b8-305">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-305">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-306">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-306">Excel</span></span>

- <span data-ttu-id="6b5b8-307">Consertamos um problema em que o Excel era, ocasionalmente, encerrado ao iniciar o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-307">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="6b5b8-308">Consertamos um problema eu que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-308">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="6b5b8-309">Consertamos um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-309">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="6b5b8-310">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-310">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-311">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-312">Consertamos um problema em que os slides não eram centralizados após o zoom usando a roda do mouse.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-312">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-313">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-313">Word</span></span>

- <span data-ttu-id="6b5b8-314">Consertamos um problema em que não era possível copiar e colar o texto em um painel de comentários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-314">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="6b5b8-315">Consertamos um problema em que os balões de dicas de comentário apareciam borradas com zoom 100%.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-315">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="6b5b8-316">Resolvemos um problema em que a habilitação da política do Word 2007 e Documentos Binários e Templates posteriores causavam falha em alguns casos de coautoria.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-316">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="6b5b8-317">Consertamos um problema em que os arquivos com nomes de caminho longos (superiores a 32K) não abriam e uma mensagem de erro apropriada não estava sendo exibida.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-317">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="6b5b8-318">Versão 2006: 22 de maio</span><span class="sxs-lookup"><span data-stu-id="6b5b8-318">Version 2006: May 22</span></span>
<span data-ttu-id="6b5b8-319">*Versão 2006 (Build 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-319">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-321">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-321">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-322">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-322">Excel</span></span>

- <span data-ttu-id="6b5b8-323">**Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-323">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="6b5b8-324">Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-324">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="6b5b8-325">Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-325">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="6b5b8-326">Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-326">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="6b5b8-327">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-327">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-328">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-329">**Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-329">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="6b5b8-330">Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-330">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="6b5b8-331">Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-331">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="6b5b8-332">Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-332">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="6b5b8-333">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-333">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-334">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-334">Word</span></span>

- <span data-ttu-id="6b5b8-335">**Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-335">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="6b5b8-336">Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-336">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="6b5b8-337">Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-337">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="6b5b8-338">Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-338">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="6b5b8-339">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-339">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-342">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-342">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-343">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-343">Excel</span></span>

- <span data-ttu-id="6b5b8-344">Consertamos um problema em que a mensagem de erro "Esta pasta de trabalho está, atualmente, referenciada por outro e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-344">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="6b5b8-345">Consertamos um problema em que a memória estava sendo corrompida durante o gerenciamento de fontes entre o Excel e alguns aplicativos de tecnologia adaptativa de terceiros.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-345">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="6b5b8-346">Consertamos um problema em que o Excel falhava quando os Suplementos pedem Itens de Host em planilhas que contêm formas com bloqueios não selecionados.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-346">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-347">Outlook</span></span>

- <span data-ttu-id="6b5b8-348">Consertamos um problema em que o evento Folder.BeforeItemMove não era acionado corretamente quando um usuário movia itens entre pastas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-348">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="6b5b8-349">Consertamos um problema em que os usuários viam os itens de calendários que ultrapassavam o limite da meia-noite como Eventos de dia inteiro.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-349">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="6b5b8-350">Consertamos um problema em que o Outlook travava quando dois suplementos adicionavam um botão ao mesmo grupo na faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-350">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="6b5b8-351">Consertamos um problema em que os usuários não conseguiam compartilhar um calendário com um usuário convidado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-351">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-352">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-352">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-353">Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-353">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-354">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-354">Project</span></span>

- <span data-ttu-id="6b5b8-355">Consertamos um problema em que o Project falhava após clicar em Opções.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-355">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-356">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-356">Word</span></span>

- <span data-ttu-id="6b5b8-357">Consertamos um problema em que os hiperlinks nos comentários não estavam funcionando.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-357">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="6b5b8-358">Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-358">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="6b5b8-359">Consertamos um problema em que a colagem de HTML no WordMail para o Calendário não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-359">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="6b5b8-360">Consertamos um problema em que responder a um comentário em uma sessão de coautoria poderia fazer com que o Word congelasse.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-360">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-may-15"></a><span data-ttu-id="6b5b8-362">Versão 2006: 15 de maio</span><span class="sxs-lookup"><span data-stu-id="6b5b8-362">Version 2006: May 15</span></span>
<span data-ttu-id="6b5b8-363">*Versão 2006 (Build 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-363">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-365">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-365">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-366">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-366">Excel</span></span>

- <span data-ttu-id="6b5b8-367">**Fazer uma conexão em PDF:** Conectar, importar, atualizar dados de um PDF.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-367">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="6b5b8-368">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-368">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="6b5b8-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-369">Outlook</span></span>

- <span data-ttu-id="6b5b8-370">**Encontre o que você precisa:** Restrinja sua pesquisa com opções como pasta, remetente, data, informações do anexo e muito mais.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-370">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-371">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-372">**Não é preciso dar um clique: seus earbuds fazem isso por você** Use seu Surface Earbuds para controlar suas apresentações de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-372">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="6b5b8-373">Importante: Você deve parear seu Surface Earbuds com o aplicativo Surface Audio para Windows 10 para usar gestos para controlar as apresentações.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-373">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="6b5b8-374">As instruções sobre como começar a usar o aplicativo de áudio Surface no Windows 10 estão disponíveis aqui.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-374">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="6b5b8-375">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-375">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="6b5b8-376">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-376">Word</span></span>

- <span data-ttu-id="6b5b8-377">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-377">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-380">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-380">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-381">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-381">Excel</span></span>
- <span data-ttu-id="6b5b8-382">Consertamos um problema que resultou em um melhor tempo de desempenho para os usuários quando eles excluíam colunas mescladas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-382">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="6b5b8-383">Consertamos um problema que causava a duplicação de nomes de impressora na lista de impressoras disponíveis.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-383">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-384">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-384">PowerPoint</span></span>
- <span data-ttu-id="6b5b8-385">Consertamos um problema em que os atalhos de teclado e a verificação ortográfica não funcionavam conforme o esperado ao usar um teclado QWERTZ.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-385">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-386">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-386">Word</span></span>
- <span data-ttu-id="6b5b8-387">Resolvemos um problema em que a adição de um novo comentário em um documento em branco não faria nada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-387">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="6b5b8-388">Consertamos um problema em que inserir ou atualizar um índice em um documento que contém mais de cem entradas resultaria no travamento do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-388">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="6b5b8-389">Consertamos um problema em que os arquivos com valores XML personalizados abriam muito lentamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-389">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-390">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-390">Office Suite</span></span>
- <span data-ttu-id="6b5b8-391">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-391">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-may-08"></a><span data-ttu-id="6b5b8-394">Versão 2006: 08 de maio</span><span class="sxs-lookup"><span data-stu-id="6b5b8-394">Version 2006: May 08</span></span>
<span data-ttu-id="6b5b8-395">*Version 2006 (Build 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-395">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-397">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-397">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-398">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-398">Excel</span></span>

- <span data-ttu-id="6b5b8-399">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-399">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-400">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-400">Outlook</span></span>

- <span data-ttu-id="6b5b8-401">**Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-401">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="6b5b8-402">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-402">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="6b5b8-403">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-403">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-404">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-404">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-405">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-405">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="6b5b8-406">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-406">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="6b5b8-407">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-407">Word</span></span>

- <span data-ttu-id="6b5b8-408">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-408">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-411">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-411">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="6b5b8-412">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-412">Office Suite</span></span>

- <span data-ttu-id="6b5b8-413">Investigamos e resolvemos o problema em que uma implantação do Office 365 ProPlus via InTune era pausada após um desligamento do sistema operacional.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-413">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-01"></a><span data-ttu-id="6b5b8-415">Versão 2005: 1 de maio</span><span class="sxs-lookup"><span data-stu-id="6b5b8-415">Version 2005: May 01</span></span>
<span data-ttu-id="6b5b8-416">*Version 2005 (Build 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-416">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-418">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-418">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-419">Outlook</span></span>

- <span data-ttu-id="6b5b8-420">**Links aprimorados no email:** quando você incluir um link a um arquivo, o nome do arquivo substituirá a URL.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-420">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="6b5b8-421">Você pode alterar as permissões para que todos os destinatários tenham acesso.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-421">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="6b5b8-422">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-422">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-425">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-425">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-426">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-426">Excel</span></span>

- <span data-ttu-id="6b5b8-427">Corrigimos um problema em que a tabela de dados do gráfico poderia processar incorretamente valores em um eixo de datas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-427">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="6b5b8-428">Corrigimos um problema em que as quebras de página poderiam não ser desabilitadas após entrar no Layout da Página ou na Visualização da Quebra de Página.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-428">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="6b5b8-429">Corrigimos um problema em que os estilos de linha do gráfico poderiam ser perdidos após ocultar e reexibir colunas com dados de série.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-429">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="6b5b8-430">Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-430">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="6b5b8-431">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="6b5b8-431">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="6b5b8-432">Corrigimos um problema em que a formatação personalizada em gráficos dinâmicos pode não ser salva quando a opção "inverter se negativo" estiver habilitada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-432">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="6b5b8-433">Corrigimos um problema em que a formatação personalizada de um único ponto de dados em um Gráfico dinâmico não era salva se a opção "inverter se negativo" tivesse sido selecionada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-433">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="6b5b8-434">Essa alteração corrige um problema em que o caractere ' @ ' carregado em um arquivo CSV resultaria na conversão da cadeia de caracteres após o caractere ' @ ' em uma fórmula.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-434">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="6b5b8-435">Corrigimos um problema em que os valores decimais na função SEQUÊNCIA não eram arredondados corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-435">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-436">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-436">Outlook</span></span>

- <span data-ttu-id="6b5b8-437">Soluciona um problema que causava falhas nos safelinks muito longos, nos quais os usuários clicavam no cliente do Outlook Desktop devido ao truncamento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-437">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="6b5b8-438">Corrigimos um problema em que as pastas do Outlook com nomes que continham caracteres DBCS (conjunto de caracteres de dois bytes) poderiam desaparecer de forma intermitente ao sincronizar com o servidor.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-438">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="6b5b8-439">Para que isso aconteça, o Outlook tinha que ser configurado com uma conta IMAP e estar sendo executado em um sistema com a localidade definida como japonês.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-439">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-440">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-440">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-441">Corrigimos um problema em que, se um usuário criasse um comentário sem postá-lo, fechasse o painel Comentários, abrisse uma nova janela, navegasse por vários slides, fechasse a janela e, por fim, reabrisse o painel Comentários na apresentação original, os comentários de rascunho não estariam disponíveis.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-441">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-442">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-442">Project</span></span>

- <span data-ttu-id="6b5b8-443">Corrigimos um problema em que, se o Project estivesse conectado ao Project Web App e o separador decimal fosse uma vírgula, o método Adicionar TaskDependencies falharia quando o retardo fosse adicionado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-443">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-444">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-444">Word</span></span>

- <span data-ttu-id="6b5b8-445">Corrigimos um problema em que a inserção de comentários em um documento no modo de colaboração nem sempre funcionava.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-445">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="6b5b8-446">Essa alteração corrige um problema em que o cartão Pessoas piscava se o @ da menção estivesse selecionado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-446">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="6b5b8-447">Corrigimos um problema em que o fechamento de um documento com comentários de rascunho perguntaria para o usuário se eles gostaria de fechar o documento sem salvar os comentários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-447">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="6b5b8-448">Cancelar a solicitação fechava o documento, em vez de deixá-lo aberto.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-448">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="6b5b8-449">Corrigimos um problema em que a tradução de um comentário postado resultaria na mensagem de erro "ocorreu falha na inserção de texto traduzido".</span><span class="sxs-lookup"><span data-stu-id="6b5b8-449">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="6b5b8-450">No leitor Exibição da Web/Imersivo, clicar em uma dica rolaria a tela para cima, mesmo que ele já estivesse em exibição.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-450">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="6b5b8-451">Isso foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-451">This has been fixed.</span></span>
- <span data-ttu-id="6b5b8-452">Corrigimos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, o arquivo poderia ser salvo com a extensão. docx e com o nome de arquivo WRO0004.docx, independentemente de qual nome o usuário inseriu, tornando o documento inutilizável.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-452">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2005-april-24"></a><span data-ttu-id="6b5b8-454">Versão 2005: 24 de abril</span><span class="sxs-lookup"><span data-stu-id="6b5b8-454">Version 2005: April 24</span></span>
<span data-ttu-id="6b5b8-455">*Versão 2005 (Build 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-455">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-457">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-457">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-458">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-458">Excel</span></span>
- <span data-ttu-id="6b5b8-459">Essa alteração corrige um problema em que o valor do R-quadrado da linha de tendência do gráfico (no caso de interceptação em y forçado) estava incorreto, mesmo que a função PROJ.LIN retorne o valor correto.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-459">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="6b5b8-460">Essa alteração corrige um problema em que a formatação personalizada da linha de tendência do gráfico nem sempre estava sendo salva.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-460">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-461">Outlook</span></span>
- <span data-ttu-id="6b5b8-462">Corrigimos um problema em que o botão Categorizar de calendários de grupo na Faixa de Opções do Office estava desabilitado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-462">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="6b5b8-463">Corrigimos um problema em que os clientes corporativos com pastas de grupo não implementadas ou que não funcionavam resultaria na exibição da mensagem “não respondendo” no Outlook.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-463">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-464">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-464">PowerPoint</span></span>
- <span data-ttu-id="6b5b8-465">Corrigimos um problema em que passar o mouse sobre o símbolo de asterisco (\*) não exibia o nome de usuário e a data da última pessoa a atualizar o documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-465">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-466">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-466">Word</span></span>
- <span data-ttu-id="6b5b8-467">Habilitar a opção "Mostrar indicadores" não exibia os indicadores.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-467">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="6b5b8-468">Isso foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-468">This has been fixed.</span></span>
- <span data-ttu-id="6b5b8-469">Essa alteração corrige um problema em que o texto com hiperlinks pode não ser exibido se a opção "Mostrar códigos de campo em vez de seus valores" estiver habilitada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-469">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)


## <a name="version-2005-april-17"></a><span data-ttu-id="6b5b8-471">Versão 2005: 17 de abril</span><span class="sxs-lookup"><span data-stu-id="6b5b8-471">Version 2005: April 17</span></span>
<span data-ttu-id="6b5b8-472">*Versão 2005 (Build 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-472">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-474">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-474">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-475">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-475">Excel</span></span>
- <span data-ttu-id="6b5b8-476">Foi aumentado o tamanho dos controles de edição de referência de célula na caixa de diálogo Barras de Erros Personalizadas usada com gráficos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-476">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="6b5b8-477">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-477">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="6b5b8-478">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-478">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="6b5b8-479">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-479">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="6b5b8-480">Essa alteração corrige um problema em que as informações de formatação condicional (CF) não estavam sendo salvas nos arquivos XLSB corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-480">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="6b5b8-481">OneNote</span><span class="sxs-lookup"><span data-stu-id="6b5b8-481">OneNote</span></span>
- <span data-ttu-id="6b5b8-482">Foi corrigido um problema em que as quebras de linha estavam sendo armazenadas como guias verticais.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-482">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-483">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-483">Outlook</span></span>
- <span data-ttu-id="6b5b8-484">Resolve um problema que fazia com que os usuários não pudessem adicionar um Grupo de Contatos Pessoais como participante da reunião.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-484">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="6b5b8-485">Resolve um problema que fazia com que o assunto de reuniões a mais de 2 meses da data prevista não fosse exibido no Assistente de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-485">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="6b5b8-486">Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-486">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="6b5b8-487">Foi adicionada a capacidade de impor a configuração de assinatura padrão S/MIME pela política de grupo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-487">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="6b5b8-488">Resolve um problema que tornava inválidas as regras de exclusão criadas para caixas de correio diferentes da caixa de correio principal do usuário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-488">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="6b5b8-489">Resolve um problema que fazia com que os anexos fossem descartados ao encaminhar uma mensagem criptografada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-489">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-490">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-490">Project</span></span>
- <span data-ttu-id="6b5b8-491">Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-491">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="6b5b8-492">Corrigimos um problema em que o Project podia falhar ao alterar o campo de status do quadro em um projeto conectado a uma lista de tarefas do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-492">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="6b5b8-493">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-493">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2004-april-10"></a><span data-ttu-id="6b5b8-495">Versão 2004: 10 de abril</span><span class="sxs-lookup"><span data-stu-id="6b5b8-495">Version 2004: April 10</span></span>
<span data-ttu-id="6b5b8-496">*Versão 2004 (Build 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-496">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-498">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-498">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="6b5b8-499">Acessar</span><span class="sxs-lookup"><span data-stu-id="6b5b8-499">Access</span></span>

- <span data-ttu-id="6b5b8-500">**Ignore a caixa de diálogo Mostrar Tabela, vá diretamente para um painel de tarefas e simplifique a adição de tabelas a relacionamentos e consultas:** Adicione tabelas e consultas clicando em quatro guias, selecionando vários nomes, pesquisando por texto e arrastando de um painel de tarefas que permanece aberto enquanto você trabalha.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-500">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-501">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-501">Excel</span></span>

- <span data-ttu-id="6b5b8-502">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="6b5b8-502">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="6b5b8-503">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-503">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-504">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-504">Outlook</span></span>

- <span data-ttu-id="6b5b8-505">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="6b5b8-505">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="6b5b8-506">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-506">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="6b5b8-507">**Mantenha suas fotos em alta definição ao enviá-las como parte de um email:** Uma nova configuração do Outlook está disponível para limitar a compactação de imagem quando você envia fotos como parte do conteúdo de emails</span><span class="sxs-lookup"><span data-stu-id="6b5b8-507">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-508">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-508">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-509">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="6b5b8-509">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="6b5b8-510">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-510">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="6b5b8-511">**Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-511">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-512">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-512">Word</span></span>

- <span data-ttu-id="6b5b8-513">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="6b5b8-513">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="6b5b8-514">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-514">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="6b5b8-515">**Faça anotações na sua cópia particular:** crie anotações redigidas à mão para você mesmo, fazendo uma cópia privada de um documento compartilhado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-515">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="6b5b8-516">Vá para Exibir > Criar uma cópia privada para começar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-516">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-519">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-519">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6b5b8-520">Access</span><span class="sxs-lookup"><span data-stu-id="6b5b8-520">Access</span></span>

- <span data-ttu-id="6b5b8-521">Foram corrigidos problemas com o redimensionamento e a atualização de tabelas no painel de tarefas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-521">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-522">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-522">Excel</span></span>

- <span data-ttu-id="6b5b8-523">Foi corrigido um problema em que a seleção de um intervalo de células em uma planilha resultava na seleção de uma única célula.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-523">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="6b5b8-524">Foi corrigido um problema que podia fazer o Excel parar de responder quando se reduzia o tamanho de um gráfico com alguns intervalos de eixo x.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-524">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="6b5b8-525">Foi corrigido um problema em que a inserção de um modelo de gráfico definido pelo usuário poderia resultar no salvamento dele como um gráfico de colunas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-525">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="6b5b8-526">Foi corrigido um problema em que os rótulos de Dados de gráficos eram exibidos como em branco quando as células de dados subjacentes não possuíam uma legenda.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-526">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="6b5b8-527">Foi corrigido um problema em que, em uma planilha do Excel com referência de célula L1C1 habilitada que estivesse sendo criada em coautoria/compartilhada, passar o mouse sobre o ícone de presença do usuário não exibia a referência de célula ativa no modo L1C1.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-527">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-528">Outlook</span></span>

- <span data-ttu-id="6b5b8-529">Resolve um problema que fazia as categorias desaparecerem ocasionalmente das mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-529">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="6b5b8-530">Resolve um problema que fazia com que os representantes vissem diferentes hierarquias de pastas em computadores diferentes para caixas de correio compartilhadas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-530">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="6b5b8-531">Resolve um problema que fazia com que os usuários experimentassem uma falha ao tentar exibir as propriedades de um Formulário Organizacional.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-531">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="6b5b8-532">Resolve um problema que fazia com que alguns lembretes falhassem ao alterar o fuso horário em um computador.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-532">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-533">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-534">Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-534">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="6b5b8-535">Corrigimos um problema em que copiar texto do Excel para o PowerPoint poderia alterar a formatação.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-535">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="6b5b8-536">Essa alteração corrige um problema em que encontrar caracteres especiais usando "localizar somente palavras inteiras" nem sempre funcionava como esperado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-536">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-537">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-537">Project</span></span>

- <span data-ttu-id="6b5b8-538">Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-538">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-539">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-539">Word</span></span>

- <span data-ttu-id="6b5b8-540">Essa alteração corrige um problema em que passar o cursor do mouse sobre uma dica não realçava o seu cartão.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-540">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="6b5b8-541">Essa alteração corrige um problema que fazia com que o texto em formas agrupadas desaparecesse temporariamente ao usar a ferramenta Seleção de laço.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-541">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="6b5b8-542">Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-542">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="6b5b8-543">Essa alteração corrige um problema no modo de exibição de duas páginas em que, ao criar um comentário, a âncora de comentário nem sempre chegava a ser exibida.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-543">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="6b5b8-544">Corrigido um problema em que, para um parágrafo cujo estilo é um ancestral de um estilo vinculado a uma lista, a numeração dessa lista poderia ser perdida.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-544">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-27"></a><span data-ttu-id="6b5b8-546">Versão 2004: 27 de março</span><span class="sxs-lookup"><span data-stu-id="6b5b8-546">Version 2004: March 27</span></span>
<span data-ttu-id="6b5b8-547">*Versão 2004 (Build 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-547">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-549">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-549">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-550">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-550">Outlook</span></span>

- <span data-ttu-id="6b5b8-551">**Nova opção para desabilitar sugestões de @menções ao redigir emails:** você acha o seletor de @menções mais irritante do que útil?</span><span class="sxs-lookup"><span data-stu-id="6b5b8-551">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="6b5b8-552">Agora, você pode desativá-lo, se preferir.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-552">Now you can turn it off if you prefer.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-555">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-555">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-556">Outlook</span></span>
- <span data-ttu-id="6b5b8-557">Corrige um problema que fazia com que o botão “Salvar na nuvem” não aparecesse nas Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-557">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="6b5b8-558">Corrige um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não tem permissão de proprietário na mensagem que está sendo respondida.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-558">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="6b5b8-559">Corrige um problema que fazia com que os usuários não conseguissem adicionar anexos adicionais de um local da Web a uma reunião criada anteriormente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-559">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-560">PowerPoint</span></span>
- <span data-ttu-id="6b5b8-561">Essa alteração corrige um erro que poderia fazer com que arquivos do PowerPoint com emojis falhassem ao salvar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-561">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-562">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-562">Project</span></span>
- <span data-ttu-id="6b5b8-563">Correção de um problema em que, se ‘CustomFieldValueListGetItem’ fosse executado e uma tabela de pesquisa do campo personalizado não existisse, uma tabela de pesquisa vazia era criada, mesmo que não devesse ser.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-563">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-564">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-564">Word</span></span>
- <span data-ttu-id="6b5b8-565">Essa alteração corrige um problema em várias páginas selecionadas no menu Exibir, onde o painel de comentários poderia ser exibido em branco.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-565">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-20"></a><span data-ttu-id="6b5b8-567">Versão 2004: 20 de março</span><span class="sxs-lookup"><span data-stu-id="6b5b8-567">Version 2004: March 20</span></span>
<span data-ttu-id="6b5b8-568">*Versão 2004 (Build 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-568">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-570">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-570">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-571">Outlook</span></span>

- <span data-ttu-id="6b5b8-572">**Atualização visual de calendário:** ano passado, trouxemos uma experiência de email atualizada e, esse ano, é a vez do calendário ser transformado!</span><span class="sxs-lookup"><span data-stu-id="6b5b8-572">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="6b5b8-573">As atualizações são novas, mas familiarmente, como um usuário experiente do Outlook, você pode entrar e ser mais produtivo imediatamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-573">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="6b5b8-574">**Ajude a proteger os dados de seu grupo:** o rótulo de sensibilidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe</span><span class="sxs-lookup"><span data-stu-id="6b5b8-574">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-575">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-576">**Atualizar slides durante a apresentação de slides:** os slides de atualização alterados por outros autores durante a sua apresentação.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-576">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-579">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-579">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-580">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-580">Excel</span></span>

- <span data-ttu-id="6b5b8-581">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-581">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-582">Outlook</span></span>

- <span data-ttu-id="6b5b8-583">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-583">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="6b5b8-584">Essa alteração corrige um problema em que as últimas alterações em rascunhos de emails não foram atualizadas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-584">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="6b5b8-585">Correção de um problema em que clicar com o botão direito do mouse em um arquivo e usar ' enviar para ' não funcionará.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-585">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="6b5b8-586">Correção de um problema em que o usuário tinha um caminho de pesquisa personalizado para o catálogo de endereços, o escopo de resolução de nome do Outlook seria limitado ao caminho personalizado, em vez de incluir a lista de endereços global (GAL).</span><span class="sxs-lookup"><span data-stu-id="6b5b8-586">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="6b5b8-587">Correção de um problema em que, em um conjunto de resultados de pesquisa retornados, classificar os resultados por categorias, não exibiria as cores da categoria.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-587">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-588">Projeto</span><span class="sxs-lookup"><span data-stu-id="6b5b8-588">Project</span></span>

- <span data-ttu-id="6b5b8-589">Correção de um problema em que o evento de "ProjectBeforeTaskChange ' aplicativos Visual Basic (VBA) não foi disparado quando um usuário clica no botão" inativo "encontrado na faixa de opções tarefas no agrupamento de agendamento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-589">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="6b5b8-590">Se você definir os detalhes da predecessora ou da sucessora de dentro de um modo de exibição de tipo de formulário, o evento ProjectBeforeTaskChange Visual Basic Applications (VBA) não capturaria as alterações.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-590">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="6b5b8-591">Por exemplo, se você excluiu uma dependência e clicou em OK no formulário, o evento não foi acionado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-591">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="6b5b8-592">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-592">This behavior has been fixed.</span></span>

- <span data-ttu-id="6b5b8-593">Correção de um problema em que os valores mais recentes para o custo real do trabalho realizado (CRTR) não seriam exibidos depois de fazer uma alteração, como uma alteração de data.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-593">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="6b5b8-594">Correção de um problema em que abrir um projeto usando o menu mais recentemente utilizado (MRU) abriu o arquivo do projeto com acesso de leitura/gravação.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-594">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="6b5b8-595">Essa alteração corrige um problema em que, se você criou uma tarefa manual com uma data de início e uma hora (mas não duração), ela seria exibida com um horário incorreto na linha do tempo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-595">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="6b5b8-596">Correção de um problema em que imprimir uma linha do tempo usando o calendário islâmico resultaria em um mês sendo ignorado ou duplicado no modo de exibição de impressão.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-596">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="6b5b8-597">Essa alteração resolve um problema em que trabalhar no planejador de equipe com objetos GDI pode resultar na alocação total de objetos GDI e criar condições de pouca memória.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-597">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-598">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-598">Word</span></span>

- <span data-ttu-id="6b5b8-599">Correção de um problema em que a funcionalidade para postar comentários foi desabilitada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-599">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="6b5b8-600">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-600">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="6b5b8-601">Essa alteração resolve um problema em que o gerente de conta não despacha mensagens, resultando em um travamento com aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-601">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="6b5b8-602">Essa alteração corrige um problema em que o Sumário seria atualizado com estilos de título que não estão presentes no documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-602">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="6b5b8-603">Correção de um problema em que as assinaturas digitais salvas em documentos do Word seriam removidas durante a mala direta dos documentos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-603">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-13"></a><span data-ttu-id="6b5b8-605">Versão 2004: 13 de março</span><span class="sxs-lookup"><span data-stu-id="6b5b8-605">Version 2004: March 13</span></span>
<span data-ttu-id="6b5b8-606">*Versão 2004 (Build 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-606">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-608">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-608">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-609">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-609">Excel</span></span>
- <span data-ttu-id="6b5b8-610">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-610">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="6b5b8-611">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-611">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-612">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-612">PowerPoint</span></span>
- <span data-ttu-id="6b5b8-613">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-613">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="6b5b8-614">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-614">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="6b5b8-615">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-615">Word</span></span>
- <span data-ttu-id="6b5b8-616">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-616">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="6b5b8-617">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-617">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-620">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-620">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="6b5b8-621">Access</span><span class="sxs-lookup"><span data-stu-id="6b5b8-621">Access</span></span>
- <span data-ttu-id="6b5b8-622">Correção de um problema em que as versões internacionais do Access exibiam as cadeias de caracteres em inglês na interface do usuário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-622">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-623">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-623">Excel</span></span>
- <span data-ttu-id="6b5b8-624">Corrigido um problema de desempenho que os usuários podem ter experimentado ao editar por programação um intervalo grande de células.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-624">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="6b5b8-625">Corrigido um problema de desempenho que acontecia ao abrir arquivos csv em ambientes japoneses.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-625">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-626">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-626">Outlook</span></span>
- <span data-ttu-id="6b5b8-627">Soluciona um problema que fazia com que a data "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um e-mail ou salvá-lo, arrastando e soltando-o (ao contrário de um menu).</span><span class="sxs-lookup"><span data-stu-id="6b5b8-627">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="6b5b8-628">Resolve um problema que fez com que pressionar Enter no painel de localização expandido falhe ao iniciar uma pesquisa, exigindo que os usuários cliquem no botão de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-628">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="6b5b8-629">Correção de um problema em que a pesquisa não exibe informações sobre os usuários quando a opção "mostrar fotografias de usuário quando disponíveis" está desabilitada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-629">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="6b5b8-630">Project</span><span class="sxs-lookup"><span data-stu-id="6b5b8-630">Project</span></span>
- <span data-ttu-id="6b5b8-631">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-631">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="6b5b8-632">Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-632">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-633">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-633">Word</span></span>
- <span data-ttu-id="6b5b8-634">Corrigido um problema ao digitar ou editar um comentário e usar Ctrl + A resultaria na seleção de texto na tela, em vez de selecionar o texto apenas dentro do cartão de comentário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-634">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="6b5b8-635">Resolvemos um problema em que o alinhamento de palavras em um documento fica embaralhado quando você tenta editar após imprimir usando a impressão rápida.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-635">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="6b5b8-636">Consertamos um problema ao mesclar dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-636">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="6b5b8-637">Correção de um problema em que a marcação de revisões envolvendo equações podem resultar em uma falha ao salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-637">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-06"></a><span data-ttu-id="6b5b8-639">Versão 2003: 06 de março</span><span class="sxs-lookup"><span data-stu-id="6b5b8-639">Version 2003: March 06</span></span>
<span data-ttu-id="6b5b8-640">*Versão 2003 (Build 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-640">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-642">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-642">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-643">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-643">Outlook</span></span>

- <span data-ttu-id="6b5b8-644">Foi corrigido um problema em que a criação de uma regra com o Outlook Web Access não persistia no servidor Exchange e resultava em um conflito.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-644">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="6b5b8-645">Foi corrigido um problema em que o Outlook no modo escuro não exibia a lista suspensa do campo 'De:'.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-645">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="6b5b8-646">Resolve um problema que fazia com que os usuários não conseguissem anexar um arquivo à mensagem de email por meio do explorador de arquivos se esse arquivo estivesse aberto em outro aplicativo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-646">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-647">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-648">Foi corrigido um problema em que as miniaturas recomendadas acendiam e apagavam ao passar o mouse sobre elas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-648">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="6b5b8-649">Em alguns casos, isso pode causar uma falha no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-649">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-650">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-650">Word</span></span>

- <span data-ttu-id="6b5b8-651">Foi corrigido um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-651">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-652">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-652">Office Suite</span></span>

- <span data-ttu-id="6b5b8-653">Foi corrigido um problema com o Word/Excel/PowerPoint, em que o nome de usuário principal (UPN) não diferenciava maiúsculas de minúsculas, resultando em menos falhas ao trabalhar com arquivos no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-653">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="6b5b8-654">Foi corrigido um problema estético em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não era afetada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-654">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

## <a name="version-2003-february-28"></a><span data-ttu-id="6b5b8-657">Versão 2003: 28 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="6b5b8-657">Version 2003: February 28</span></span>
<span data-ttu-id="6b5b8-658">*Versão 2003 (Criação 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-658">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-660">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-660">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-661">Outlook</span></span>

- <span data-ttu-id="6b5b8-662">**Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-662">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="6b5b8-663">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-663">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-664">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-665">**Tinta aprimorada para moldar a experiência de diagramação:** Desenhe diagramas melhores e faça com que seja convertidos para que você possa manipular objetos do escritório [Saiba mais](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="6b5b8-665">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-668">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="6b5b8-669">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-669">Excel</span></span>

- <span data-ttu-id="6b5b8-670">Corrido um problema em que o texto em uma segmentação de dados não é dimensionado corretamente na visualização de impressão.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-670">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-671">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-671">Outlook</span></span>

- <span data-ttu-id="6b5b8-672">Soluciona um problema que fazia com que a data "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um e-mail ou salvá-lo, arrastando e soltando-o (ao contrário de um menu).</span><span class="sxs-lookup"><span data-stu-id="6b5b8-672">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-673">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-673">Word</span></span>

- <span data-ttu-id="6b5b8-674">Corrigido um problema que, ao percorrer um cartão de comentários, o foco na caixa de edição de comentários não ficava visível.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-674">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="6b5b8-675">Inserir um controle (como um Controle de Conteúdo de Texto) em uma equação e salvar e abrir o arquivo resulta em um erro de conteúdo não legível.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-675">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="6b5b8-676">Corrigido um problema em que o salvamento de um arquivo anteriormente protegido por senha em um armazenamento em nuvem não funcionava.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-676">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-677">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-677">Office Suite</span></span>

- <span data-ttu-id="6b5b8-678">Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-678">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-february-21"></a><span data-ttu-id="6b5b8-680">Versão 2003: 21 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="6b5b8-680">Version 2003: February 21</span></span>
<span data-ttu-id="6b5b8-681">*Versão 2003 (Build 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-681">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-683">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-683">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="6b5b8-684">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-684">Office Suite</span></span>

- <span data-ttu-id="6b5b8-685">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-685">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-688">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-688">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-689">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-689">Excel</span></span>
- <span data-ttu-id="6b5b8-690">Corrigido um problema que os usuários podem ter ao renomear medidas de tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-690">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="6b5b8-691">Corrigido um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-691">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="6b5b8-692">Corrigido um problema que fazia a interface do usuário piscar quando os usuários executavam uma macro que interagia com a faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-692">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="6b5b8-693">Corrigido um problema em que os arquivos CSV eram carregados incorretamente quando a primeira palavra no arquivo era TABLE.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-693">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="6b5b8-694">Corrigido um problema em que os usuários podem ter sofrido falhas ao alternar entre duas pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-694">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-695">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-695">Outlook</span></span>
- <span data-ttu-id="6b5b8-696">Corrigido um problema que fazia com que os usuários não conseguissem abrir mensagens de pasta pública quando o Outlook permanecia em execução durante a noite.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-696">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="6b5b8-697">Corrigida uma condição de corrida em que os botões 'Permitir' e 'Negar' na página de permissões são desativados durante o fluxo de trabalho de autenticação da adição de uma conta do Gmail.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-697">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="6b5b8-698">Resolvido um problema que fazia o Outlook gerar de forma inesperada a saída do log em alguns cenários, mesmo quando o log estava desativado.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-698">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-699">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-699">Word</span></span>
- <span data-ttu-id="6b5b8-700">Corrigido um problema em que os cartões de comentários nem sempre são destacados quando um ponteiro do mouse passa sobre o cartão de comentários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-700">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="6b5b8-701">Durante uma sessão ativa de coautoria de documentos, adicionar uma imagem diretamente a um cartão de comentários pode resultar na adição de uma marca.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-701">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="6b5b8-702">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-702">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-703">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-703">Office Suite</span></span>
- <span data-ttu-id="6b5b8-704">Ao usar as propriedades do MultiChoice/Lookup/Managed-metadata com documentos do Word/Excel/PowerPoint e salvá-los em uma biblioteca de documentos do SharePoint, essas propriedades anteriormente eram limitadas a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-704">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="6b5b8-705">Quando essas propriedades excederem 255 caracteres, esses documentos não puderam ser salvos.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-705">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="6b5b8-706">Com essa mudança, esse limite aumentou para 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-706">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-february-14"></a><span data-ttu-id="6b5b8-708">Versão 2003: 14 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="6b5b8-708">Version 2003: February 14</span></span>
<span data-ttu-id="6b5b8-709">*Versão 2003 (Build 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-709">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-711">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-711">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-712">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-712">Outlook</span></span>

- <span data-ttu-id="6b5b8-713">**Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar?</span><span class="sxs-lookup"><span data-stu-id="6b5b8-713">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="6b5b8-714">O Outlook agora detecta isso e ajuda você a se conectar.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-714">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-715">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-715">Word</span></span>

- <span data-ttu-id="6b5b8-716">**Encontre o Editor de Tinta na caixa de ferramentas de desenho:** Selecione Desenhar e, em seguida, escolha a caneta do Editor de Tinta para editar seu documento com o dedo ou uma caneta digital.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-716">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="6b5b8-717">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="6b5b8-717">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="6b5b8-718">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-718">Office Suite</span></span>

- <span data-ttu-id="6b5b8-719">**Ícones mais claros da barra de status:** Agora é mais fácil visualizar os ícones da barra de status.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-719">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-722">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-722">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="6b5b8-723">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-723">Outlook</span></span>

- <span data-ttu-id="6b5b8-724">Solucionamos um problema que fazia com que os usuários perdessem o acesso à caixa de diálogo de permissões de calendário "Opções de Disponibilidade".</span><span class="sxs-lookup"><span data-stu-id="6b5b8-724">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="6b5b8-725">Correção de um problema que pode resultar no alerta: "Infelizmente, estamos com problemas para abrir este item" ao abrir algumas instâncias de reunião recorrente enviadas de um fuso horário diferente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-725">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="6b5b8-726">Solucionamos um problema que pode fazer com que os usuários não consigam reabrir um arquivo. msg depois de arrastar e soltar um anexo da mensagem.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-726">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="6b5b8-727">Correção de um problema em que, após carregar um anexo de arquivo do Outlook para o OneDrive, poderia resultar no nome do arquivo sendo alterado se o nome do anexo contivesse parênteses.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-727">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-728">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-728">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-729">Correção de um problema que pode resultar em uma falha no salvamento de um documento no PowerPoint ou no Word com um gráfico do Excel.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-729">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-730">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-730">Word</span></span>

- <span data-ttu-id="6b5b8-731">Correção de um problema em que imagens em documentos perdem a transparência quando exportadas para PDF.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-731">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-february-07"></a><span data-ttu-id="6b5b8-733">Versão 2002: 7 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="6b5b8-733">Version 2002: February 07</span></span>
<span data-ttu-id="6b5b8-734">*Versão 2002 (Build 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="6b5b8-734">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a><span data-ttu-id="6b5b8-736">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-736">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="6b5b8-737">Access</span><span class="sxs-lookup"><span data-stu-id="6b5b8-737">Access</span></span>

- <span data-ttu-id="6b5b8-738">**Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-738">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="6b5b8-739">Pesquise e substitua o texto no SQL View.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-739">Search and replace text in SQL View.</span></span> <span data-ttu-id="6b5b8-740">Selecione várias tabelas na janela Relações.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-740">Select multiple tables in the Relationships window.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="6b5b8-743">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="6b5b8-743">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="6b5b8-744">Access</span><span class="sxs-lookup"><span data-stu-id="6b5b8-744">Access</span></span>

- <span data-ttu-id="6b5b8-745">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-745">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="6b5b8-746">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-746">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="6b5b8-747">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-747">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="6b5b8-748">Excel</span><span class="sxs-lookup"><span data-stu-id="6b5b8-748">Excel</span></span>

- <span data-ttu-id="6b5b8-749">Corrigido um problema em que o Excel falhava ao usar colunas de texto em com matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-749">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="6b5b8-750">Outlook</span><span class="sxs-lookup"><span data-stu-id="6b5b8-750">Outlook</span></span>

- <span data-ttu-id="6b5b8-751">Corrigido um problema em que a rolagem no calendário com a exibição do mês não mostrava eventos anteriores do calendário.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-751">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="6b5b8-752">Soluciona um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-752">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6b5b8-753">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6b5b8-753">PowerPoint</span></span>

- <span data-ttu-id="6b5b8-754">Corrigido um problema em que, após fechar um arquivo, o PowerPoint não o removia imediatamente da coleção Apresentações, se houvesse algum manipulador de eventos em execução.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-754">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="6b5b8-755">Portanto, o número de apresentações abertas relatadas pelo modelo de objeto ficava incorreto, e o desligamento do PowerPoint era impedido.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-755">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="6b5b8-756">Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-756">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="6b5b8-757">Word</span><span class="sxs-lookup"><span data-stu-id="6b5b8-757">Word</span></span>

- <span data-ttu-id="6b5b8-758">Às vezes, atualizar e rolar um índice pode exibir uma área cinza sobre o documento.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-758">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="6b5b8-759">Corrigido um problema em que, se um documento fosse usado em coautoria, a versão de rascunho de um comentário raiz poderia não ser preservada.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-759">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="6b5b8-760">Corrigido um problema em que alternar entre os cartões de comentários às vezes exibia o comentário selecionado inicialmente com um destaque de seleção.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-760">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="6b5b8-761">Corrigido um problema em que o uso de "Procurar" para salvar um arquivo não funcionava se um comentário fosse escrito, mas não postado, e o usuário tentasse salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-761">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="6b5b8-762">Com o SlideTrack habilitado e o painel de comentários fechado, Ctrl+Alt+M pode não abrir o painel de comentários.</span><span class="sxs-lookup"><span data-stu-id="6b5b8-762">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="6b5b8-763">Corrigido um problema ao adicionar @menção em uma tabela poderia gerar a mensagem de erro: "Uma tabela neste documento foi corrompida".</span><span class="sxs-lookup"><span data-stu-id="6b5b8-763">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="6b5b8-764">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="6b5b8-764">Office Suite</span></span>

- <span data-ttu-id="6b5b8-765">Resolve um problema que pode ter causado a instalação incorreta do pacote de ferramentas de revisão Nynorsk da Noruega (nn-no).</span><span class="sxs-lookup"><span data-stu-id="6b5b8-765">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|DevMain|Insiders| |16.0.13115.20000|version-2008-july-17|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13102.20002|versão-10-de-julho-2008|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

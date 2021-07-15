---
title: Notas de versão para os lançamentos do Canal Empresarial Mensal
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI as notas de versão para o Canal Empresarial Mensal dos Aplicativos do Microsoft 365 Apps
ms.openlocfilehash: 96a76ed1ed1849753422dae92626484a77cec2a4
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409557"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a><span data-ttu-id="ff067-103">Notas de versão para os lançamentos do Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="ff067-103">Release notes for Monthly Enterprise Channel</span></span>

<span data-ttu-id="ff067-104">Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionadas à segurança que estão inclusos em atualizações mensais do Canal Corporativo Mensal para Microsoft 365 Apps para Grandes Empresas, Microsoft 365 Apps para Pequenos e Médios negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="ff067-104">These release notes provide information about new features and non-security updates that are included in Monthly Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


[//]: # (NÃO REMOVA)



## <a name="version-2105-july-13"></a><span data-ttu-id="ff067-106">Versão 2105: 13 de julho</span><span class="sxs-lookup"><span data-stu-id="ff067-106">Version 2105: July 13</span></span>
<span data-ttu-id="ff067-107">*Versão 2105 (build 14026.20334)*</span><span class="sxs-lookup"><span data-stu-id="ff067-107">*Version 2105 (Build 14026.20334)*</span></span>

<span data-ttu-id="ff067-108">Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-108">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-110">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-110">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ff067-111">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-111">Outlook</span></span>

- <span data-ttu-id="ff067-112">**Obtenha sugestões de arquivos relevantes ao pesquisar:** ao digitar na caixa Pesquisar, os arquivos mais relevantes relacionados à sua pesquisa serão incluídos nas suas sugestões.</span><span class="sxs-lookup"><span data-stu-id="ff067-112">**Get relevant file suggestions when you search:** When you type in the Search box, the most relevant files related to your search will be included in your suggestions.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-115">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-116">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-116">Excel</span></span>

- <span data-ttu-id="ff067-117">Corrigido um problema para permitir que o Gerenciador de Nomes abra em livros com um grande número de nomes ocultos.</span><span class="sxs-lookup"><span data-stu-id="ff067-117">Fixed an issue to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="ff067-118">Corrigimos um problema em que as entradas extras apareciam na lista de suplementos do Excel para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-118">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="ff067-119">Corrigido um problema em que o suplemento Ferramentas de Análise não funcionava para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-119">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-120">Outlook</span></span>

- <span data-ttu-id="ff067-121">A alteração está sendo escura e sob um portão de alteração, portanto, se houver problemas, ela poderá ser desativada rapidamente.</span><span class="sxs-lookup"><span data-stu-id="ff067-121">Change is going in dark and under a change gate so if there are issues it can be turned off quickly.</span></span>


- <span data-ttu-id="ff067-122">Adicionamos uma chave do Registro que desabilitava a nova experiência do Localizador de Salas (a mesma experiência do Outlook para Web) e habilita o Localizador de Salas herdado com Horários Sugeridos.</span><span class="sxs-lookup"><span data-stu-id="ff067-122">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

   <span data-ttu-id="ff067-123">Chave do Registro:</span><span class="sxs-lookup"><span data-stu-id="ff067-123">Registry Key:</span></span>

    ><span data-ttu-id="ff067-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="ff067-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span></span>

    ><span data-ttu-id="ff067-125">0 (padrão) – O Outlook usa a nova plataforma OWA Powered eXperience de Localizador de Salas quando o usuário clica no botão "Localizador de Salas" para pesquisar salas disponíveis</span><span class="sxs-lookup"><span data-stu-id="ff067-125">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span></br>
    ><span data-ttu-id="ff067-126">1 - O Outlook usa a interface de usuário herdada do Localizador de Salas para procurar salas disponíveis</span><span class="sxs-lookup"><span data-stu-id="ff067-126">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span>


- <span data-ttu-id="ff067-127">Essa alteração permite que os usuários enviem comentários por meio de nosso novo sistema de comentários.</span><span class="sxs-lookup"><span data-stu-id="ff067-127">This change enables users to submit feedback through our new feedback system.</span></span>


- <span data-ttu-id="ff067-128">Corrigimos um problema que ocultava a opção de comentários para usuários da versão prévia do Office Permanente 2021.</span><span class="sxs-lookup"><span data-stu-id="ff067-128">We fixed an issue that caused the feedback option to be disabled for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="ff067-129">Corrigimos um problema que fazia com que os usuários receberam um erro ao selecionar "Abrir Propriedades do Outlook" no menu de contexto do clique com o botão direito do mouse para um destinatário em um email.</span><span class="sxs-lookup"><span data-stu-id="ff067-129">We fixed an issue that caused users to get an error when selecting "Open Outlook Properties" from the right click context menu for a recipient on an email.</span></span>


- <span data-ttu-id="ff067-130">Corrigimos um problema que causava um encerramento inesperado de aplicativo para alguns usuários ao carregar cartões de pessoas.</span><span class="sxs-lookup"><span data-stu-id="ff067-130">We fixed an issue that caused some users to experience unexpected app close when loading person cards.</span></span>


- <span data-ttu-id="ff067-131">Corrigimos um problema que causava um fechamento inesperado para os usuários ao remover pastas de um armazenamento de arquivo morto.</span><span class="sxs-lookup"><span data-stu-id="ff067-131">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="ff067-132">Corrigimos um problema que fez com que algumas instruções para o recurso "Encurtar reuniões" fossem desabilitadas através de tecnologias de leitor de tela.</span><span class="sxs-lookup"><span data-stu-id="ff067-132">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be disabled through screen reader technologies.</span></span>


- <span data-ttu-id="ff067-133">Corrigimos um problema que fazia com que os usuários experimentassem um prompt de alteração de propriedade inesperada ao fechar uma mensagem à qual responderam ou encaminharam.</span><span class="sxs-lookup"><span data-stu-id="ff067-133">We fixed an issue that caused users to experience an unexpected property change prompt when closing a message they had replied to or forwarded.</span></span>


- <span data-ttu-id="ff067-134">Resolvemos um problema que pode causar um fechamento inesperado ao interagir com o Outlook Mail ou o Calendar Views.</span><span class="sxs-lookup"><span data-stu-id="ff067-134">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-135">PowerPoint</span></span>

- <span data-ttu-id="ff067-136">Corrigido um problema em que a opção Reutilizar Slides não estava disponível para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-136">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="ff067-137">Project</span><span class="sxs-lookup"><span data-stu-id="ff067-137">Project</span></span>

- <span data-ttu-id="ff067-138">Corrigido um problema em que as tarefas programadas manualmente eram movidas para uma data incorreta.</span><span class="sxs-lookup"><span data-stu-id="ff067-138">Fixed an issue where assignments on manually scheduled tasks moved to an incorrect date.</span></span>


- <span data-ttu-id="ff067-139">Corrigido um problema em que se você criasse uma fórmula de campo personalizada que usasse as funções ProjectDate */ProjectDur*, e se o segundo parâmetro fosse as funções Date(), Now() ou Time() date e time, resultaria em um #ERROR.</span><span class="sxs-lookup"><span data-stu-id="ff067-139">Fixed an issue where if you create a custom field formula which uses the ProjectDate */ProjectDur* functions and if the second parameter is the Date(), Now() or Time() date and time functions, then a #ERROR results.</span></span>


### <a name="word"></a><span data-ttu-id="ff067-140">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-140">Word</span></span>

- <span data-ttu-id="ff067-141">Corrige um problema em que o Painel do Editor não abre.</span><span class="sxs-lookup"><span data-stu-id="ff067-141">Fixes an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="ff067-142">Corrigido um problema em que os cartões contextuais de tela para ortografia e gramática mostram botões de ícones, mas esses botões não têm dicas de ferramentas.</span><span class="sxs-lookup"><span data-stu-id="ff067-142">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-143">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ff067-143">Office Suite</span></span>

- <span data-ttu-id="ff067-144">Corrigido um problema de localização em que en-gb, fr-ca e es-mx agora correspondem às respectivas versões pai.</span><span class="sxs-lookup"><span data-stu-id="ff067-144">Fixed a localization issue where en-gb, fr-ca, and es-mx will now be matched with their respective parent versions.</span></span>


- <span data-ttu-id="ff067-145">Corrigido um fechamento inesperado ao reabrir determinados arquivos.</span><span class="sxs-lookup"><span data-stu-id="ff067-145">Fixed a unexpected close when reopening certain files.</span></span>


- <span data-ttu-id="ff067-146">Corrigido uma regressão de desempenho ao abrir arquivos SyncBacked.</span><span class="sxs-lookup"><span data-stu-id="ff067-146">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="ff067-147">Corrigido um problema em que o usuário não conseguia editar arquivos armazenados nos servidores OnPrem do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="ff067-147">Fixed an issue where user is unable to edit certain documents stored in OnPrem sharepoint servers.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2104-july-13"></a><span data-ttu-id="ff067-149">Versão 2104: 13 de julho</span><span class="sxs-lookup"><span data-stu-id="ff067-149">Version 2104: July 13</span></span>
<span data-ttu-id="ff067-150">*Versão 2104 (build 13929.20434)*</span><span class="sxs-lookup"><span data-stu-id="ff067-150">*Version 2104 (Build 13929.20434)*</span></span>

<span data-ttu-id="ff067-151">Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-151">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2104-june-08"></a><span data-ttu-id="ff067-152">Versão 2104: 08 de junho</span><span class="sxs-lookup"><span data-stu-id="ff067-152">Version 2104: June 08</span></span>
<span data-ttu-id="ff067-153">*Versão 2104 (Build 13929.20408)*</span><span class="sxs-lookup"><span data-stu-id="ff067-153">*Version 2104 (Build 13929.20408)*</span></span>

<span data-ttu-id="ff067-154">Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-154">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-156">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-156">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-157">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-157">Excel</span></span>

- <span data-ttu-id="ff067-158">**Salvamento automático e coautoria em documentos criptografados confidenciais:** Não troque produtividade por segurança.</span><span class="sxs-lookup"><span data-stu-id="ff067-158">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="ff067-159">Com a Proteção de Informações da Microsoft, os documentos criptografados com rótulos de sensibilidade agora podem ser salvos no AutoSave e em coautoria com outras pessoas em tempo real, assim como os documentos não criptografados.</span><span class="sxs-lookup"><span data-stu-id="ff067-159">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="ff067-160">Requer adesão do locatário (mais informações: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="ff067-160">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff067-161">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-161">PowerPoint</span></span>

- <span data-ttu-id="ff067-162">**Salvamento automático e coautoria em documentos criptografados confidenciais:** Não troque produtividade por segurança.</span><span class="sxs-lookup"><span data-stu-id="ff067-162">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="ff067-163">Com a Proteção de Informações da Microsoft, os documentos criptografados com rótulos de sensibilidade agora podem ser salvos no AutoSave e em coautoria com outras pessoas em tempo real, assim como os documentos não criptografados.</span><span class="sxs-lookup"><span data-stu-id="ff067-163">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="ff067-164">Requer adesão do locatário (mais informações: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="ff067-164">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="ff067-165">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-165">Word</span></span>

- <span data-ttu-id="ff067-166">**Salvamento automático e coautoria em documentos criptografados confidenciais:** Não troque produtividade por segurança.</span><span class="sxs-lookup"><span data-stu-id="ff067-166">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="ff067-167">Com a Proteção de Informações da Microsoft, os documentos criptografados com rótulos de sensibilidade agora podem ser salvos no AutoSave e em coautoria com outras pessoas em tempo real, assim como os documentos não criptografados.</span><span class="sxs-lookup"><span data-stu-id="ff067-167">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="ff067-168">Requer adesão do locatário (mais informações: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="ff067-168">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-171">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-171">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-172">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-172">Excel</span></span>

- <span data-ttu-id="ff067-173">Corrigimos um problema onde alguns os arquivos ocasionalmente não abriam no Modo de Exibição Protegido.</span><span class="sxs-lookup"><span data-stu-id="ff067-173">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="ff067-174">Corrigimos um problema que fazia com que a formatação de data fosse exibida incorretamente em alguns idiomas ao adicionar suplementos.</span><span class="sxs-lookup"><span data-stu-id="ff067-174">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="ff067-175">Corrigido um problema em que o suplemento Ferramentas de Análise não funcionava para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-175">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="ff067-176">Corrigimos um problema em que as entradas extras apareciam na lista de suplementos do Excel para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-176">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="ff067-177">Correção de um problema em que uma reversão da compilação da versão principal poderia resultar no fechamento do aplicativo ao abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="ff067-177">Fix for an issue where a major version build rollback could result in the application terminating on file open.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-178">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-178">Outlook</span></span>

- <span data-ttu-id="ff067-179">Corrigimos um problema que fazia com que alguns usuários do recurso de melhorias de compartilhamento do calendário tivessem problemas de interação com o calendário deles no painel de navegação.</span><span class="sxs-lookup"><span data-stu-id="ff067-179">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="ff067-180">Adicionamos uma chave do Registro que desabilitava a nova experiência do Localizador de Salas (a mesma experiência do Outlook para Web) e habilita o Localizador de Salas herdado com Horários Sugeridos.</span><span class="sxs-lookup"><span data-stu-id="ff067-180">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    
    <span data-ttu-id="ff067-181">Chave do Registro:</span><span class="sxs-lookup"><span data-stu-id="ff067-181">Registry Key:</span></span>

    ><span data-ttu-id="ff067-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="ff067-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    ><span data-ttu-id="ff067-183">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="ff067-183">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="ff067-184">0 (padrão) – O Outlook usa a nova plataforma OWA Powered eXperience de Localizador de Salas quando o usuário clica no botão "Localizador de Salas" para pesquisar salas disponíveis</span><span class="sxs-lookup"><span data-stu-id="ff067-184">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="ff067-185">1 - O Outlook usa a interface de usuário herdada do Localizador de Salas para procurar salas disponíveis</span><span class="sxs-lookup"><span data-stu-id="ff067-185">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="ff067-186">Corrigimos um problema que fez com que a resolução de nomes falhasse ao enviar em nome de outro usuário e resolver contra um catálogo de endereços que não é a Lista de Endereços Global.</span><span class="sxs-lookup"><span data-stu-id="ff067-186">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="ff067-187">Corrigimos um problema que fazia com que a opção de comentários não aparecesse para usuários da versão prévia do Office Permanente 2021.</span><span class="sxs-lookup"><span data-stu-id="ff067-187">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="ff067-188">Corrigimos um problema que poderia fazer com que os usuários vissem a mensagem que eles estão compondo perdendo o foco da IU.</span><span class="sxs-lookup"><span data-stu-id="ff067-188">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="ff067-189">Resolvemos um problema que fez com que o Outlook anulasse as preferências da Caixa de Entrada Destaques configurada no OWA.</span><span class="sxs-lookup"><span data-stu-id="ff067-189">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="ff067-190">Corrigimos um problema que fazia com que os usuários vissem as assinaturas desaparecerem inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="ff067-190">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="ff067-191">Corrigimos um problema que fazia com que os usuários com configurações móveis experimentassem falta de resposta.</span><span class="sxs-lookup"><span data-stu-id="ff067-191">We fixed an issue that caused users of roaming settings to experience unresponsiveness.</span></span>


- <span data-ttu-id="ff067-192">Corrigimos um problema que causava um fechamento inesperado do processo para os usuários ao pesquisar.</span><span class="sxs-lookup"><span data-stu-id="ff067-192">We fixed an issue that caused users to experience the process terminating unexpectedly when searching.</span></span>


- <span data-ttu-id="ff067-193">Corrigimos um fechamento inesperado relacionado à pesquisa.</span><span class="sxs-lookup"><span data-stu-id="ff067-193">We fixed a search-related unexpected close.</span></span>


- <span data-ttu-id="ff067-194">Corrigimos um problema que fazia com que o seletor de pessoas no Outlook expandisse para cima em vez de para baixo para usuários com uma licença permanente.</span><span class="sxs-lookup"><span data-stu-id="ff067-194">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-195">PowerPoint</span></span>

- <span data-ttu-id="ff067-196">Corrigimos um problema em que a opção Reutilizar Slides não estava disponível para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-196">Fixed an issue where Reuse Slides option was not available for a few users.</span></span>


- <span data-ttu-id="ff067-197">Corrigimos um problema relacionado a imagens vinculadas.</span><span class="sxs-lookup"><span data-stu-id="ff067-197">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="ff067-198">Corrigimos um problema em que uma reversão da compilação da versão principal poderia resultar em um fechamento inesperado ao abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="ff067-198">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="project"></a><span data-ttu-id="ff067-199">Project</span><span class="sxs-lookup"><span data-stu-id="ff067-199">Project</span></span>

- <span data-ttu-id="ff067-200">Corrigido um problema em que os usuários não conseguiam remover projetos do pool de recursos.</span><span class="sxs-lookup"><span data-stu-id="ff067-200">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="ff067-201">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-201">Word</span></span>

- <span data-ttu-id="ff067-202">Corrigimos um problema que exigia um alteração na edição do objeto OLE.</span><span class="sxs-lookup"><span data-stu-id="ff067-202">We fixed an issue which required a change on editing OLE object.</span></span>


- <span data-ttu-id="ff067-203">Corrigimos um problema em que alguns textos selecionados não ficavam visíveis ao usar o tema de modo escuro no modo de leitura.</span><span class="sxs-lookup"><span data-stu-id="ff067-203">We fixed an issue where some select text was not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="ff067-204">Corrigimos um problema que poderia fazer com que o Word fechasse inesperadamente quando o usuário fizesse logoff ou reiniciasse o computador.</span><span class="sxs-lookup"><span data-stu-id="ff067-204">Fixed an issue that may cause Word to unexpectedly close when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="ff067-205">Corrigimos um problema onde se atualizava o texto sobre a chamada automática para arquivos salvos localmente.</span><span class="sxs-lookup"><span data-stu-id="ff067-205">We fixed an issue that updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="ff067-206">Corrigimos um problema em que uma reversão da compilação da versão principal poderia resultar em um fechamento inesperado ao abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="ff067-206">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-207">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ff067-207">Office Suite</span></span>

- <span data-ttu-id="ff067-208">Corrigimos um problema que fazia com que o documento na nuvem não abrisse.</span><span class="sxs-lookup"><span data-stu-id="ff067-208">Fixed an issue that would cause cloud document to fail to open.</span></span>


- <span data-ttu-id="ff067-209">Essa mudança analisa o novo atributo TenantId enviado nas respostas do Cobalt e o armazena na Tabela Central.</span><span class="sxs-lookup"><span data-stu-id="ff067-209">This change parses the new TenantId attribute sent on Cobalt responses and stores it in the Central Table.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2103-june-08"></a><span data-ttu-id="ff067-211">Versão 2103: 08 de junho</span><span class="sxs-lookup"><span data-stu-id="ff067-211">Version 2103: June 08</span></span>
<span data-ttu-id="ff067-212">*Versão 2103 (Build 13901.20554)*</span><span class="sxs-lookup"><span data-stu-id="ff067-212">*Version 2103 (Build 13901.20554)*</span></span>

<span data-ttu-id="ff067-213">Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-213">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-215">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-215">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-216">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-216">Excel</span></span>

- <span data-ttu-id="ff067-217">Corrigido um problema em que as entradas extras apareciam na lista de suplementos do Excel para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-217">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-218">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ff067-218">Office Suite</span></span>

- <span data-ttu-id="ff067-219">Corrige um problema que fazia com que o Word, PowerPoint e Excel não abrisse um documento na nuvem se voltasse para uma versão anterior</span><span class="sxs-lookup"><span data-stu-id="ff067-219">Fix an issue Word, Powerpoint and Excel would fail to open cloud document if rolling back to a previous build</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2103-may-11"></a><span data-ttu-id="ff067-221">Versão 2103: 11 de maio</span><span class="sxs-lookup"><span data-stu-id="ff067-221">Version 2103: May 11</span></span>
<span data-ttu-id="ff067-222">*Versão 2103 (Build 13901.20516)*</span><span class="sxs-lookup"><span data-stu-id="ff067-222">*Version 2103 (Build 13901.20516)*</span></span>

<span data-ttu-id="ff067-223">Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-223">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-225">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-225">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-226">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-226">Excel</span></span>

- <span data-ttu-id="ff067-227">**Usar os novos tipos de dados automaticamente:** Ao digitar um valor de dados semelhante a um estoque ou uma localização geográfica, o Excel oferece a conversão para o tipo de dados conectado certo, ações ou geografia.</span><span class="sxs-lookup"><span data-stu-id="ff067-227">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="ff067-228">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-228">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="ff067-229">**Tipos de dados vinculados – dados reais para a vida real:** novos tipos de dados vinculados trazem fatos e dados sobre centenas de assuntos para ajudar você a alcançar seus objetivos diretamente no Excel.</span><span class="sxs-lookup"><span data-stu-id="ff067-229">**Linked data types: Real data for real life:** New linked data types bring you facts and data on hundreds of subjects to help you accomplish your goals right in Excel.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff067-230">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-230">Outlook</span></span>

- <span data-ttu-id="ff067-231">**Quebre a barreira do idioma com um tradutor interno:** Os suplementos para tradução não são mais necessários!</span><span class="sxs-lookup"><span data-stu-id="ff067-231">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="ff067-232">Agora você pode usar o Tradutor Inteligente no Outlook.</span><span class="sxs-lookup"><span data-stu-id="ff067-232">You can now use the Intelligent Translator in Outlook.</span></span> <span data-ttu-id="ff067-233">Quando você receber uma mensagem em outro idioma, um aviso aparecerá na parte superior da mensagem perguntando se você deseja que o Outlook a traduza para o seu idioma padrão.</span><span class="sxs-lookup"><span data-stu-id="ff067-233">When you receive a message in another language, a prompt will appear on top of the message asking if you’d like Outlook to translate it to your default language.</span></span>
<span data-ttu-id="ff067-234">Você também pode clicar com o botão direito para traduzir palavras, frases específicas ou a mensagem inteira.</span><span class="sxs-lookup"><span data-stu-id="ff067-234">You can also right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="ff067-235">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-235">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a><span data-ttu-id="ff067-236">Visio</span><span class="sxs-lookup"><span data-stu-id="ff067-236">Visio</span></span>

- <span data-ttu-id="ff067-237">**Gráficos prontos para seus diagramas:** escolha entre uma grande biblioteca de ícones, fotos de catálogo, pessoas removidas da imagem e figurinhas que você pode adicionar aos seus desenhos do Visio.</span><span class="sxs-lookup"><span data-stu-id="ff067-237">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="ff067-238">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-238">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br /><span data-ttu-id="ff067-239">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/access-illustrations-icons-in-visio)</span><span class="sxs-lookup"><span data-stu-id="ff067-239">See details in [blog post](https://insider.office.com/pt-BR/blog/access-illustrations-icons-in-visio)</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-242">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-242">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ff067-243">Access</span><span class="sxs-lookup"><span data-stu-id="ff067-243">Access</span></span>

- <span data-ttu-id="ff067-244">Corrigimos um problema quando um aplicativo externo solicita uma interface de acessibilidade. Isso nos impedirá de desligar até que eles liberem sua referência.</span><span class="sxs-lookup"><span data-stu-id="ff067-244">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


- <span data-ttu-id="ff067-245">Esta alteração corrige um problema em que, em alguns casos, executar uma consulta passagem do SQL Server poderia resultar em uma mensagem de erro indicando que havia um “estado do cursor inválido”.</span><span class="sxs-lookup"><span data-stu-id="ff067-245">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="ff067-246">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-246">Excel</span></span>

- <span data-ttu-id="ff067-247">Corrigimos um problema que fazia com que a formatação de data fosse exibida incorretamente em alguns idiomas ao adicionar suplementos.</span><span class="sxs-lookup"><span data-stu-id="ff067-247">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="ff067-248">Corrigido um problema em que o suplemento Ferramentas de Análise não funcionava para alguns usuários.</span><span class="sxs-lookup"><span data-stu-id="ff067-248">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="ff067-249">Corrigido um travamento potencial no Word ao desenhar uma imagem.</span><span class="sxs-lookup"><span data-stu-id="ff067-249">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-250">Outlook</span></span>

- <span data-ttu-id="ff067-251">Corrigimos um problema que fez com que a resolução de nomes falhasse ao enviar em nome de outro usuário e resolver contra um catálogo de endereços que não é a Lista de Endereços Global.</span><span class="sxs-lookup"><span data-stu-id="ff067-251">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="ff067-252">Corrigimos um problema que fez com que o Outlook anulasse as preferências da Caixa de Entrada Destaques configurada no OWA.</span><span class="sxs-lookup"><span data-stu-id="ff067-252">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="ff067-253">Corrigimos um problema que fazia com que algumas pessoas não conseguissem acessar as assinaturas associadas a contas de email secundárias.</span><span class="sxs-lookup"><span data-stu-id="ff067-253">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="ff067-254">Corrigimos um problema que fazia com que os usuários vissem mais assinaturas do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="ff067-254">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="ff067-255">Corrigimos um problema que fazia com que alguns usuários vissem suas agendas principal e secundária trocando de lugar no Painel de Navegação.</span><span class="sxs-lookup"><span data-stu-id="ff067-255">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>


- <span data-ttu-id="ff067-256">Corrigimos um problema que faz com que os usuários vejam incorretamente uma mensagem "Isso pode demorar um pouco" ao adicionar um calendário.</span><span class="sxs-lookup"><span data-stu-id="ff067-256">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="ff067-257">Corrigimos um problema que fazia com que os representantes aparecessem como o organizador de reuniões criadas em calendários recém-adicionados.</span><span class="sxs-lookup"><span data-stu-id="ff067-257">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="ff067-258">As reuniões neste estado não aparecem no calendário do diretor.</span><span class="sxs-lookup"><span data-stu-id="ff067-258">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="ff067-259">Corrigimos um problema em um componente do Outlook usado por aplicativos habilitados para MAPI em computadores com processadores ARM.</span><span class="sxs-lookup"><span data-stu-id="ff067-259">We fixed an issue in a component of Outlook that is used by MAPI-enabled applications on computers with ARM processors.</span></span> <span data-ttu-id="ff067-260">O problema pode fazer com que a pesquisa falhe ou causar uma carga extra no computador, pois os aplicativos em segundo plano são reiniciados repetidamente.</span><span class="sxs-lookup"><span data-stu-id="ff067-260">The issue could cause search to fail or cause extra load on the computer as background apps restarted repeatedly.</span></span>


- <span data-ttu-id="ff067-261">Corrigimos um problema que fazia com que alguns usuários experimentassem um fechamento inesperado do Outlook sincronizar alterações na hierarquia de pastas.</span><span class="sxs-lookup"><span data-stu-id="ff067-261">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="ff067-262">Corrigido um travamento potencial no Word ao desenhar uma imagem.</span><span class="sxs-lookup"><span data-stu-id="ff067-262">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-263">PowerPoint</span></span>

- <span data-ttu-id="ff067-264">Corrigimos um problema relacionado a imagens vinculadas.</span><span class="sxs-lookup"><span data-stu-id="ff067-264">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="ff067-265">Corrigido um travamento potencial no Word ao desenhar uma imagem.</span><span class="sxs-lookup"><span data-stu-id="ff067-265">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="project"></a><span data-ttu-id="ff067-266">Project</span><span class="sxs-lookup"><span data-stu-id="ff067-266">Project</span></span>

- <span data-ttu-id="ff067-267">Corrigido um problema em que o Visio podia parar de funcionar durante o fechamento.</span><span class="sxs-lookup"><span data-stu-id="ff067-267">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="ff067-268">Visio</span><span class="sxs-lookup"><span data-stu-id="ff067-268">Visio</span></span>

- <span data-ttu-id="ff067-269">Corrigido um problema em que o Visio podia parar de funcionar durante o fechamento.</span><span class="sxs-lookup"><span data-stu-id="ff067-269">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="word"></a><span data-ttu-id="ff067-270">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-270">Word</span></span>

- <span data-ttu-id="ff067-271">Corrigido um problema para otimizar as condições para as previsões de texto a serem oferecidas.</span><span class="sxs-lookup"><span data-stu-id="ff067-271">Fixed an issue to optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="ff067-272">Corrigido um problema onde se atualizava o texto sobre a chamada automática para arquivos salvos localmente.</span><span class="sxs-lookup"><span data-stu-id="ff067-272">Fixed an issue where updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="ff067-273">Corrigido um problema de coautoria de um documento, o rascunho ativo não era apagado quando a ordem do comentário era alterada.</span><span class="sxs-lookup"><span data-stu-id="ff067-273">Fixed an issue when coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="ff067-274">Corrige um problema onde Visualizar Impressão era fechado inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="ff067-274">Fixes an issue where Print preview closed unexpectedly.</span></span>


- <span data-ttu-id="ff067-275">Corrigido um travamento potencial no Word ao desenhar uma imagem.</span><span class="sxs-lookup"><span data-stu-id="ff067-275">Fixed a potential hang in Word when drawing an image.</span></span>



### <a name="office-suite"></a><span data-ttu-id="ff067-276">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ff067-276">Office Suite</span></span>

- <span data-ttu-id="ff067-277">Corrige um problema de confiabilidade relacionado ao suporte de aplicativos do Office em execução na sessão 0.</span><span class="sxs-lookup"><span data-stu-id="ff067-277">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="ff067-278">Corrigido um problema em que a renomeação não estava respondendo quando um arquivo SyncBacked era aberto offline e, em seguida, renomeava o arquivo no aplicativo antes de salvá-lo.</span><span class="sxs-lookup"><span data-stu-id="ff067-278">Fixed an issue which rename was unresponsive when opened a SyncBacked file offline then renamed the file in app before saving file.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2102-may-11"></a><span data-ttu-id="ff067-280">Versão 2102: 11 de maio</span><span class="sxs-lookup"><span data-stu-id="ff067-280">Version 2102: May 11</span></span>
<span data-ttu-id="ff067-281">*Versão 2102 (Build 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="ff067-281">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="ff067-282">Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-282">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-284">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-284">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-285">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-285">Excel</span></span>

- <span data-ttu-id="ff067-286">Corrigimos um problema que fazia com que a formatação da data fosse exibida incorretamente em alguns idiomas ao usar Suplementos.</span><span class="sxs-lookup"><span data-stu-id="ff067-286">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="ff067-287">Corrigimos um problema que impedia a capacidade de colar como fórmulas em uma página protegida.</span><span class="sxs-lookup"><span data-stu-id="ff067-287">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-288">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-288">Outlook</span></span>

- <span data-ttu-id="ff067-289">Isto permite aos usuários finais configurem o Outlook para adicionar uma reunião online a cada reunião que eles criarem.</span><span class="sxs-lookup"><span data-stu-id="ff067-289">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-290">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-290">PowerPoint</span></span>

- <span data-ttu-id="ff067-291">Corrigimos um problema relacionado a imagens vinculadas.</span><span class="sxs-lookup"><span data-stu-id="ff067-291">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="ff067-292">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-292">Word</span></span>

- <span data-ttu-id="ff067-293">Corrige um problema no Wordmail em que alguém não poderia enviar este item quando o 2084º caractere em um link fosse um caractere de escape.</span><span class="sxs-lookup"><span data-stu-id="ff067-293">Fixes an issue in Wordmail where someone cannot send this item' when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-294">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ff067-294">Office Suite</span></span>

- <span data-ttu-id="ff067-295">Corrigido um problema que fazia com que o Word fechasse inesperadamente durante a impressão de documentos longos.</span><span class="sxs-lookup"><span data-stu-id="ff067-295">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>


- <span data-ttu-id="ff067-296">Antes dessa alteração, os modelos do Office eram exibidos mesmo que o GPO estivesse ativada para desabilitá-los.</span><span class="sxs-lookup"><span data-stu-id="ff067-296">Before this change, Office templates were displaying even if GPO for disabling them was turned on.</span></span> <span data-ttu-id="ff067-297">Com essa alteração, os modelos agora respeitam corretamente o GPO e são exibidos/ocultados conforme solicitado.</span><span class="sxs-lookup"><span data-stu-id="ff067-297">With this change, templates now honor the GPO correctly and display/hide as requested.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2102-april-13"></a><span data-ttu-id="ff067-299">Versão 2102: 13 de abril</span><span class="sxs-lookup"><span data-stu-id="ff067-299">Version 2102: April 13</span></span>
<span data-ttu-id="ff067-300">*Versão 2102 (Build 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="ff067-300">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="ff067-301">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ff067-301">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-303">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-303">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-304">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-304">Excel</span></span>

- <span data-ttu-id="ff067-305">**Use a caixa de diálogo avançado para criar tipos de dados:** a caixa de diálogo avançada permite que você selecione manualmente as colunas que combinam o tipo de dados que você está criando.</span><span class="sxs-lookup"><span data-stu-id="ff067-305">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

- <span data-ttu-id="ff067-306">**Reexibir várias páginas ao mesmo tempo:** não há mais necessidade de exibir uma página por vez - exibir várias páginas ocultas de uma vez.</span><span class="sxs-lookup"><span data-stu-id="ff067-306">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="ff067-307">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-307">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a><span data-ttu-id="ff067-308">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-308">Outlook</span></span>

- <span data-ttu-id="ff067-309">**As configurações da Caixa de Entrada Destaques permanecem as mesmas em todos os dispositivos:** as suas preferências da Caixa de Entrada Destaques agora são armazenadas na nuvem.</span><span class="sxs-lookup"><span data-stu-id="ff067-309">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="ff067-310">Desfrute da mesma experiência ao usar o Outlook para Windows em qualquer computador e o Outlook na Web.</span><span class="sxs-lookup"><span data-stu-id="ff067-310">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="ff067-311">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-311">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="ff067-312">**As configurações do Outlook na nuvem:** escolha as configurações do Outlook para Windows, como Respostas Automáticas, Caixa de Entrada Destaques, Privacidade, e acesse-as em qualquer PC.</span><span class="sxs-lookup"><span data-stu-id="ff067-312">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

- <span data-ttu-id="ff067-313">**Escolha onde Pesquisar:** O novo escopo da pesquisa a lista suspensa permite que você modifique a pesquisa com mais facilidade e alterne entre as pastas atuais e a caixa de correio atual.</span><span class="sxs-lookup"><span data-stu-id="ff067-313">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="ff067-314">Agradecer a todas as pessoas no Em Breve, que forneceram comentários sobre a nova pesquisa na primeira experiência.</span><span class="sxs-lookup"><span data-stu-id="ff067-314">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="ff067-315">Esse design e essa atualização acabaram com esse comentário!</span><span class="sxs-lookup"><span data-stu-id="ff067-315">This design and update came out of that feedback!</span></span>

- <span data-ttu-id="ff067-316">**Rascunho de mensagens com sua voz:** Utilize a nova barra de ferramentas de ditado, comandos de voz, pontuação automática e muito mais para escrever mensagens.</span><span class="sxs-lookup"><span data-stu-id="ff067-316">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="ff067-317">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-317">Word</span></span>

- <span data-ttu-id="ff067-318">**Rascunho de documentos com sua voz:** Utilize a nova barra de ferramentas de ditado, comandos de voz e pontuação automática para rascunhar documentos.</span><span class="sxs-lookup"><span data-stu-id="ff067-318">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-321">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-321">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ff067-322">Access</span><span class="sxs-lookup"><span data-stu-id="ff067-322">Access</span></span>

- <span data-ttu-id="ff067-323">Esta alteração corrige um problema em que, em alguns casos, executar uma consulta passagem do SQL Server resultava em uma mensagem de erro indicando que havia um “estado do cursor inválido”.</span><span class="sxs-lookup"><span data-stu-id="ff067-323">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>



### <a name="excel"></a><span data-ttu-id="ff067-324">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-324">Excel</span></span>

- <span data-ttu-id="ff067-325">Corrigimos um problema no qual a validação de dados podia ser aplicada a células inesperadamente após adicionar linhas a uma tabela em outra planilha.</span><span class="sxs-lookup"><span data-stu-id="ff067-325">We fixed a bug in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="ff067-326">Corrigimos um problema em que a função para exibir DialogSheets não funcionava nas versões de 32 bits do Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-326">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


- <span data-ttu-id="ff067-327">Corrigimos um problema que fazia com que as imagens fossem menores do que o esperado ao usar a opção Colar Imagem Vinculada.</span><span class="sxs-lookup"><span data-stu-id="ff067-327">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="ff067-328">Corrigimos um problema que fazia com que a formatação de algumas tabelas dinâmicas corrompesse a pasta de trabalho ao salvar no formato .xls ou .xlt.</span><span class="sxs-lookup"><span data-stu-id="ff067-328">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="ff067-329">Corrigimos um problema que impedia que os usuários exportassem uma pasta de trabalho do Excel para PDF.</span><span class="sxs-lookup"><span data-stu-id="ff067-329">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="ff067-330">Foi corrigido um problema em que comandos desativados na Faixa de Opções do Office só teriam o ícone acinzentado, mas não o texto no Tema do Office Cinza Escuro.</span><span class="sxs-lookup"><span data-stu-id="ff067-330">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-331">Outlook</span></span>

- <span data-ttu-id="ff067-332">Corrigimos um problema que fazia com que os usuários de tradução embutida não pudessem enviar comentários.</span><span class="sxs-lookup"><span data-stu-id="ff067-332">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="ff067-333">Corrigimos um problema que fazia com que os usuários vissem as assinaturas com conteúdo Unicode danificadas.</span><span class="sxs-lookup"><span data-stu-id="ff067-333">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="ff067-334">Corrigimos um problema que fazia com que os usuários vissem mais assinaturas do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="ff067-334">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="ff067-335">Corrigimos um problema que fazia o Outlook travar quando estava ocioso.</span><span class="sxs-lookup"><span data-stu-id="ff067-335">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="ff067-336">Corrigimos um problema que fazia com que alguns usuários experimentassem o desligamento do aplicativo ao fechar as janelas de mensagens.</span><span class="sxs-lookup"><span data-stu-id="ff067-336">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="ff067-337">Corrigimos um problema que fazia com que os usuários do Calendário Compartilhado não conseguissem definir a cor de um calendário para amarelo ou marrom.</span><span class="sxs-lookup"><span data-stu-id="ff067-337">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="ff067-338">Corrigimos um problema que fazia com que os usuários vissem grupos de calendário duplicados aparecerem após a criação de um novo grupo.</span><span class="sxs-lookup"><span data-stu-id="ff067-338">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="ff067-339">Corrigimos um problema que fazia com que os usuários vissem os calendários recém-adicionados não aparecendo no painel de navegação até que o Outlook fosse reiniciado.</span><span class="sxs-lookup"><span data-stu-id="ff067-339">We fixed an issue that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-340">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-340">PowerPoint</span></span>

- <span data-ttu-id="ff067-341">Foi corrigido um problema em que comandos desativados na Faixa de Opções do Office só teriam o ícone acinzentado, mas não o texto no Tema do Office Cinza Escuro.</span><span class="sxs-lookup"><span data-stu-id="ff067-341">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="ff067-342">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-342">Word</span></span>

- <span data-ttu-id="ff067-343">Corrigimos um problema na resolução de conflitos durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="ff067-343">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="ff067-344">Corrigimos um problema com os controles de conteúdo de rich text.</span><span class="sxs-lookup"><span data-stu-id="ff067-344">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="ff067-345">Corrigimos um problema com a digitação no final de um parágrafo oculto que pode resultar no travamento do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="ff067-345">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="ff067-346">Corrigimos um problema em que o Narrador podia pular um parágrafo.</span><span class="sxs-lookup"><span data-stu-id="ff067-346">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="ff067-347">Corrigimos um problema relacionado a copiar e colar.</span><span class="sxs-lookup"><span data-stu-id="ff067-347">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="ff067-348">Corrige um problema com cores aplicadas a ícones e gráficos SVG com efeitos 3D.</span><span class="sxs-lookup"><span data-stu-id="ff067-348">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="ff067-349">Foi corrigido um problema em que comandos desativados na Faixa de Opções do Office só teriam o ícone acinzentado, mas não o texto no Tema do Office Cinza Escuro.</span><span class="sxs-lookup"><span data-stu-id="ff067-349">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-350">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ff067-350">Office Suite</span></span>

- <span data-ttu-id="ff067-351">Corrigimos um problema de confiabilidade relacionado ao suporte de aplicativos do Office em execução na sessão 0.</span><span class="sxs-lookup"><span data-stu-id="ff067-351">We fixed a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="ff067-352">Foi corrigido um erro que ocasionalmente fazia com que o texto no Outlook se tornasse transparente e, portanto, não legível.</span><span class="sxs-lookup"><span data-stu-id="ff067-352">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


- <span data-ttu-id="ff067-353">Corrigido um problema que poderia acontecer ao usar o narrador dentro de um texto que contém equações matemáticas.</span><span class="sxs-lookup"><span data-stu-id="ff067-353">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="ff067-354">Foi corrigido um problema em que o Ditado estava desabilitado para usuários da Nuvem da Comunidade Governamental</span><span class="sxs-lookup"><span data-stu-id="ff067-354">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="ff067-355">Corrigimos um problema em que os usuários não conseguiam salvar um arquivo ao abrir um arquivo aberto anteriormente com edições não salvas, mas agora o arquivo foi excluído.</span><span class="sxs-lookup"><span data-stu-id="ff067-355">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="ff067-356">Após a correção, os usuários receberão uma mensagem amigável para informá-los que o arquivo foi excluído, portanto, o usuário pode escolher descartar as alterações ou SalvarComo o arquivo.</span><span class="sxs-lookup"><span data-stu-id="ff067-356">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="ff067-357">Foi corrigido o problema de falha de renomeação ao abrir um arquivo SyncBacked offline e, em seguida, renomear o arquivo no aplicativo antes de salvá-lo.</span><span class="sxs-lookup"><span data-stu-id="ff067-357">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2101-april-13"></a><span data-ttu-id="ff067-359">Versão 2101: 13 de abril</span><span class="sxs-lookup"><span data-stu-id="ff067-359">Version 2101: April 13</span></span>
<span data-ttu-id="ff067-360">*Versão 2101 (Build 13628.20664)*</span><span class="sxs-lookup"><span data-stu-id="ff067-360">*Version 2101 (Build 13628.20664)*</span></span>

<span data-ttu-id="ff067-361">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ff067-361">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2101-march-09"></a><span data-ttu-id="ff067-362">Versão 2101: 09 de Março</span><span class="sxs-lookup"><span data-stu-id="ff067-362">Version 2101: March 09</span></span>
<span data-ttu-id="ff067-363">*Versão 2101 (Build 13628.20528)*</span><span class="sxs-lookup"><span data-stu-id="ff067-363">*Version 2101 (Build 13628.20528)*</span></span>

<span data-ttu-id="ff067-364">Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-364">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-366">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-366">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-367">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-367">Excel</span></span>

- <span data-ttu-id="ff067-368">Corrige um problema em que o Excel falhava ao iniciar ou fechava inesperadamente se certas configurações de proteção contra exploits de Segurança do Windows (SimExec, CallerCheck) estivessem em uso</span><span class="sxs-lookup"><span data-stu-id="ff067-368">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-369">Outlook</span></span>

- <span data-ttu-id="ff067-370">Corrigimos um problema que fazia com que o ícone de criptografia não fosse exibido para emails enviados usando a somente a opção de criptografia.</span><span class="sxs-lookup"><span data-stu-id="ff067-370">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="ff067-371">Corrigimos um problema que fazia com que os emails fossem enviados como assinados digitalmente depois que o usuário desmarcou essa opção.</span><span class="sxs-lookup"><span data-stu-id="ff067-371">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="ff067-372">Corrigimos um problema que causava problemas ao exibir a assinatura padrão correta no OWA.</span><span class="sxs-lookup"><span data-stu-id="ff067-372">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="ff067-373">Corrigimos um problema que causava um travamento dos usuários das Configurações de Nuvem ao atualizar as configurações.</span><span class="sxs-lookup"><span data-stu-id="ff067-373">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="ff067-374">Corrigimos um problema que algumas vezes fez com que o aplicativo fechasse inesperadamente quando os usuários estavam pesquisando no Outlook.</span><span class="sxs-lookup"><span data-stu-id="ff067-374">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="ff067-375">Corrigimos um problema que fazia com que usuários com Caixas de Correio Compartilhadas ou Delegadas com grandes hierarquias em seus perfis travassem.</span><span class="sxs-lookup"><span data-stu-id="ff067-375">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="ff067-376">Corrigimos um problema que fazia com que alguns usuários experimentassem o Outlook para fechar inesperadamente em determinados cenários de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="ff067-376">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


### <a name="project"></a><span data-ttu-id="ff067-377">Project</span><span class="sxs-lookup"><span data-stu-id="ff067-377">Project</span></span>

- <span data-ttu-id="ff067-378">Corrigimos um problema em que, quando um recurso de custo era atribuído a uma tarefa de marco, o custo da linha de base não era acumulado corretamente.</span><span class="sxs-lookup"><span data-stu-id="ff067-378">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


- <span data-ttu-id="ff067-379">Correção de um problema em que a bordas não apareciam para tarefas no modo de exibição Planejador de Equipe.</span><span class="sxs-lookup"><span data-stu-id="ff067-379">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="ff067-380">Correção de um problema em que arrastar e soltar não funcionava para tarefas no modo de exibição Planejador de Equipe.</span><span class="sxs-lookup"><span data-stu-id="ff067-380">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-381">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ff067-381">Office Suite</span></span>

- <span data-ttu-id="ff067-382">Corrige um problema relacionado às notificações de eventos do controlador de mídia.</span><span class="sxs-lookup"><span data-stu-id="ff067-382">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="ff067-383">Corrige um problema relacionado ao tempo do motor do media player.</span><span class="sxs-lookup"><span data-stu-id="ff067-383">Fixes an issue related to media player engine timing.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2012-march-09"></a><span data-ttu-id="ff067-385">Versão 2012: 09 de Março</span><span class="sxs-lookup"><span data-stu-id="ff067-385">Version 2012: March 09</span></span>
<span data-ttu-id="ff067-386">*Versão 2012 (Compilação 13530.20628)*</span><span class="sxs-lookup"><span data-stu-id="ff067-386">*Version 2012 (Build 13530.20628)*</span></span>

<span data-ttu-id="ff067-387">Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-387">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-389">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-389">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-390">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-390">Excel</span></span>

- <span data-ttu-id="ff067-391">**Requer que os usuários apliquem rótulos de confidencialidade:** Os usuários serão solicitados a aplicar um rótulo de confidencialidade se a política da sua organização exigir isso.</span><span class="sxs-lookup"><span data-stu-id="ff067-391">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff067-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-392">PowerPoint</span></span>

- <span data-ttu-id="ff067-393">**Requer que os usuários apliquem rótulos de confidencialidade:** Os usuários serão solicitados a aplicar um rótulo de confidencialidade se a política da sua organização exigir isso.</span><span class="sxs-lookup"><span data-stu-id="ff067-393">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="word"></a><span data-ttu-id="ff067-394">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-394">Word</span></span>

- <span data-ttu-id="ff067-395">**Requer que os usuários apliquem rótulos de confidencialidade:** Os usuários serão solicitados a aplicar um rótulo de confidencialidade se a política da sua organização exigir isso.</span><span class="sxs-lookup"><span data-stu-id="ff067-395">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>


## <a name="version-2012-february-09"></a><span data-ttu-id="ff067-396">Versão 2012: 09 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ff067-396">Version 2012: February 09</span></span>
<span data-ttu-id="ff067-397">*Versão 2012 (Build 13530.20528)*</span><span class="sxs-lookup"><span data-stu-id="ff067-397">*Version 2012 (Build 13530.20528)*</span></span>

<span data-ttu-id="ff067-398">Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-398">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-400">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-400">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-401">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-401">Excel</span></span>

- <span data-ttu-id="ff067-402">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="ff067-402">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="ff067-403">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-403">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="ff067-404">**Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="ff067-404">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="ff067-405">**Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H.</span><span class="sxs-lookup"><span data-stu-id="ff067-405">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="ff067-406">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-406">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="ff067-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-407">Outlook</span></span>

- <span data-ttu-id="ff067-408">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="ff067-408">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="ff067-409">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-409">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="ff067-410">**Aumente o tempo entre as reuniões consecutivas:** Dê aos participantes tempo para recuperar o fôlego ou viajar entre os locais, configurando as reuniões para começarem 5-10 minutos atrasado por padrão.</span><span class="sxs-lookup"><span data-stu-id="ff067-410">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="ff067-411">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-411">Learn more</span></span>](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- <span data-ttu-id="ff067-412">**Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="ff067-412">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="ff067-413">**Cada reunião online:** atualize suas configurações de calendário para tornar todas as reuniões que você criar uma Reunião de Equipe por padrão, para que você não precise mais se lembrar de clicar na opção Reunião de Equipes.</span><span class="sxs-lookup"><span data-stu-id="ff067-413">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="ff067-414">**Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H.</span><span class="sxs-lookup"><span data-stu-id="ff067-414">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="ff067-415">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-415">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

- <span data-ttu-id="ff067-416">**Cada reunião online:** atualize suas configurações de calendário para tornar todas as reuniões que você criar uma Reunião de Equipe por padrão, para que você não precise mais se lembrar de clicar na opção Reunião de Equipes.</span><span class="sxs-lookup"><span data-stu-id="ff067-416">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="ff067-417">**Novo localizador de sala:** Pesquisar salas de conferência por diferentes recursos.</span><span class="sxs-lookup"><span data-stu-id="ff067-417">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="ff067-418">**Nova experiência de reserva de sala de conferência e espaço de trabalho**: a experiência de reserva de sala de conferência foi atualizada e, com ela, adicionamos recursos que permitem que você agende também espaços de trabalho individuais</span><span class="sxs-lookup"><span data-stu-id="ff067-418">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-419">PowerPoint</span></span>

- <span data-ttu-id="ff067-420">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="ff067-420">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="ff067-421">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-421">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="ff067-422">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="ff067-422">See details in [blog post](https://insider.office.com/pt-BR/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="ff067-423">**Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="ff067-423">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="ff067-424">**Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H.</span><span class="sxs-lookup"><span data-stu-id="ff067-424">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="ff067-425">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-425">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a><span data-ttu-id="ff067-426">Visio</span><span class="sxs-lookup"><span data-stu-id="ff067-426">Visio</span></span>

- <span data-ttu-id="ff067-427">**Novos estênceis e formas do Azure:** Nós adicionamos muitos outros estênceis para ajudá-lo a criar diagramas do Azure atualizados.</span><span class="sxs-lookup"><span data-stu-id="ff067-427">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="ff067-428">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-428">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="ff067-429">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-429">Word</span></span>

- <span data-ttu-id="ff067-430">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="ff067-430">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="ff067-431">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-431">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="ff067-432">**Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="ff067-432">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="ff067-433">**Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H.</span><span class="sxs-lookup"><span data-stu-id="ff067-433">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="ff067-434">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-434">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-437">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-437">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-438">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-438">Excel</span></span>

- <span data-ttu-id="ff067-439">Esta alteração resolve um problema com a exibição adequada de fontes em equações.</span><span class="sxs-lookup"><span data-stu-id="ff067-439">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="ff067-440">Corrigido um problema em que alguns usuários veriam incorretamente uma barra de mensagens informando-os de uma nova versão de um arquivo durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="ff067-440">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="ff067-441">Corrigido um problema em que o Excel podia deixar as macros desabilitadas sem que fosse solicitado ao abrir um arquivo de suplemento do Excel contendo Macros do Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="ff067-441">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="ff067-442">Corrige um problema em que o Excel não pode ser iniciado ou encerrado inesperadamente se determinadas configurações de proteção do Windows Security Exploit (SimExec, CallerCheck) estiverem em uso.</span><span class="sxs-lookup"><span data-stu-id="ff067-442">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="ff067-443">Corrigido um problema em que o Excel poderia fechar inesperadamente ao usar o menu "Mostrar Valores Como" para uma Tabela Dinâmica.</span><span class="sxs-lookup"><span data-stu-id="ff067-443">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="ff067-444">Corrigimos um problema que quebrava algumas macros legadas do Excel 4.0 e Excel 5.0, bem como algumas chamadas VBA para dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="ff067-444">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-445">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-445">Outlook</span></span>

- <span data-ttu-id="ff067-446">Corrigimos um problema que fazia com que uma assinatura editada não salvasse depois de solicitar que o usuário o fizesse.</span><span class="sxs-lookup"><span data-stu-id="ff067-446">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="ff067-447">Corrigimos um problema que fazia com que alguns usuários experimentassem o fechamento inesperado do Outlook em determinados cenários de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="ff067-447">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="ff067-448">Corrigimos um problema que fazia com que alguns clientes se deparassem com um travamento durante o carregamento de seus calendários.</span><span class="sxs-lookup"><span data-stu-id="ff067-448">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="ff067-449">Corrigimos um problema que fazia com que usuários que têm Caixas de Correio Compartilhadas ou Delegadas com grandes hierarquias em seus perfis se deparassem com um travamento.</span><span class="sxs-lookup"><span data-stu-id="ff067-449">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-450">PowerPoint</span></span>

- <span data-ttu-id="ff067-451">Corrigimos um problema em que o comando de tamanho de fonte, adicionado ao QAT, completava automaticamente para o tamanho de fonte definido mais próximo ao atualizá-lo.</span><span class="sxs-lookup"><span data-stu-id="ff067-451">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="ff067-452">Esta alteração resolve um problema com a exibição adequada de fontes em equações.</span><span class="sxs-lookup"><span data-stu-id="ff067-452">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="ff067-453">Esta alteração resolve um problema com os preenchimentos de caminho ao aplicar operações de Mesclar Formas com determinadas geometrias.</span><span class="sxs-lookup"><span data-stu-id="ff067-453">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-454">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ff067-454">Office Suite</span></span>

- <span data-ttu-id="ff067-455">O Anaheim WebView ainda não oferece suporte ao Proteção de Informações do Windows (WIP).</span><span class="sxs-lookup"><span data-stu-id="ff067-455">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="ff067-456">Com essa correção, a plataforma de suplemento do Office volta ao nível inferior do WebView em um ambiente habilitado para WIP.</span><span class="sxs-lookup"><span data-stu-id="ff067-456">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="ff067-457">Pode ser Edge Spartan WebView ou Trident WebView, dependendo do ambiente do computador do cliente.</span><span class="sxs-lookup"><span data-stu-id="ff067-457">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="ff067-458">Ambos os WebViews de nível inferior suportam WIP.</span><span class="sxs-lookup"><span data-stu-id="ff067-458">Both down level WebViews support WIP.</span></span>


- <span data-ttu-id="ff067-459">Dimensionamento binário otimizado.</span><span class="sxs-lookup"><span data-stu-id="ff067-459">Optimized binary size.</span></span>


- <span data-ttu-id="ff067-460">Corrigida a sequência de fechamento do arquivo para que todos os componentes interdependentes sejam fechados normalmente.</span><span class="sxs-lookup"><span data-stu-id="ff067-460">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2011-february-09"></a><span data-ttu-id="ff067-462">Versão 2011: 09 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ff067-462">Version 2011: February 09</span></span>
<span data-ttu-id="ff067-463">*Versão 2011 (Build 13426.20658)*</span><span class="sxs-lookup"><span data-stu-id="ff067-463">*Version 2011 (Build 13426.20658)*</span></span>

<span data-ttu-id="ff067-464">Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-464">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2011-january-12"></a><span data-ttu-id="ff067-465">Versão 2011: 12 de janeiro</span><span class="sxs-lookup"><span data-stu-id="ff067-465">Version 2011: January 12</span></span>
<span data-ttu-id="ff067-466">*Versão 2011 (Build 13426.20526)*</span><span class="sxs-lookup"><span data-stu-id="ff067-466">*Version 2011 (Build 13426.20526)*</span></span>

<span data-ttu-id="ff067-467">Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-467">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ff067-469">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ff067-469">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ff067-470">Access</span><span class="sxs-lookup"><span data-stu-id="ff067-470">Access</span></span>

- <span data-ttu-id="ff067-471">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-471">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-472">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-472">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-473">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-473">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="ff067-474">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-474">Excel</span></span>

- <span data-ttu-id="ff067-475">**Criar variáveis para usar em fórmulas:** Melhorar o desempenho, a legibilidade e a capacidade de composição com a função LET.</span><span class="sxs-lookup"><span data-stu-id="ff067-475">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="ff067-476">Esta função permite que você crie variáveis nomeadas em fórmulas novas ou pré-existentes.</span><span class="sxs-lookup"><span data-stu-id="ff067-476">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="ff067-477">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-477">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="ff067-478">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="ff067-478">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="ff067-479">**Criar um tipo de dados personalizado no Power Query:** use uma fonte de dados para criar um tipo de dados personalizado que permite que você carregue várias informações relacionadas em uma coluna.</span><span class="sxs-lookup"><span data-stu-id="ff067-479">**Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column.</span></span> [<span data-ttu-id="ff067-480">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-480">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="ff067-481">Consulte os detalhes na [postagem do blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="ff067-481">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="ff067-482">**Nomeie a nova planilha após a consulta fonte:** quando os dados são carregados na nova planilha, a planilha será nomeada baseada no nome da consulta de origem.</span><span class="sxs-lookup"><span data-stu-id="ff067-482">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="ff067-483">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-483">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-484">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-484">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-485">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-485">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="ff067-486">OneNote</span><span class="sxs-lookup"><span data-stu-id="ff067-486">OneNote</span></span>

- <span data-ttu-id="ff067-487">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-487">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-488">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-488">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-489">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-489">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="ff067-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-490">Outlook</span></span>

- <span data-ttu-id="ff067-491">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-491">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-492">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-492">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-493">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-493">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a><span data-ttu-id="ff067-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-494">PowerPoint</span></span>

- <span data-ttu-id="ff067-495">**Biblioteca de Vídeo:** eleve seus documentos com uma biblioteca de vídeo de royalties livres e gratuitas selecionadas disponíveis no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="ff067-495">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app.</span></span>

- <span data-ttu-id="ff067-496">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-496">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-497">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-497">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-498">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-498">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="ff067-499">Project</span><span class="sxs-lookup"><span data-stu-id="ff067-499">Project</span></span>

- <span data-ttu-id="ff067-500">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-500">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-501">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-501">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-502">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-502">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="ff067-503">Publisher</span><span class="sxs-lookup"><span data-stu-id="ff067-503">Publisher</span></span>

- <span data-ttu-id="ff067-504">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-504">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-505">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-505">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-506">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-506">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="ff067-507">Visio</span><span class="sxs-lookup"><span data-stu-id="ff067-507">Visio</span></span>

- <span data-ttu-id="ff067-508">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-508">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-509">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-509">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-510">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-510">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="ff067-511">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-511">Word</span></span>

- <span data-ttu-id="ff067-512">**Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ff067-512">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="ff067-513">Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office.</span><span class="sxs-lookup"><span data-stu-id="ff067-513">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="ff067-514">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ff067-514">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ff067-517">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ff067-517">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff067-518">Excel</span><span class="sxs-lookup"><span data-stu-id="ff067-518">Excel</span></span>

- <span data-ttu-id="ff067-519">Corrigido um problema em que o Excel mostrava incorretamente uma barra de mensagens de que uma nova versão do arquivo está disponível e forçava o usuário a salvar suas alterações em uma cópia da pasta de trabalho ou descartar suas alterações.</span><span class="sxs-lookup"><span data-stu-id="ff067-519">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="ff067-520">Corrigido um problema em que o Excel pode deixar macros desativadas sem avisar ao abrir um arquivo de Suplemento do Excel contendo Macros do Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="ff067-520">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="outlook"></a><span data-ttu-id="ff067-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff067-521">Outlook</span></span>

- <span data-ttu-id="ff067-522">Corrigimos um problema que fazia com que alguns usuários não vissem assinaturas no menu suspenso de assinaturas, apesar de terem uma ou mais assinaturas configuradas.</span><span class="sxs-lookup"><span data-stu-id="ff067-522">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="ff067-523">Adicionamos uma regkey que permite que os clientes desabilitem a inclusão de filetime para anexos nas operações do IDataObject (ou seja, arrastar e soltar, área de transferência).</span><span class="sxs-lookup"><span data-stu-id="ff067-523">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="ff067-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="ff067-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="ff067-525">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="ff067-525">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="ff067-526">0 = filetimes são excluídos.</span><span class="sxs-lookup"><span data-stu-id="ff067-526">0 = filetimes are excluded.</span></span> <span data-ttu-id="ff067-527">1 = (padrão) filetimes são incluídos.</span><span class="sxs-lookup"><span data-stu-id="ff067-527">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="ff067-528">Corrigimos um problema que fazia com que as imagens embutidas desaparecessem ao responder a uma mensagem com um rótulo de proteção da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="ff067-528">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="ff067-529">Corrigimos um problema que causava a interrupção do evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="ff067-529">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="ff067-530">Corrigimos um problema que fazia com que o campo Para ficasse em branco ao enviar um relatório de status em uma tarefa.</span><span class="sxs-lookup"><span data-stu-id="ff067-530">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="ff067-531">Corrigimos um problema que fazia com que os participantes originais de algumas reuniões recebessem um cancelamento quando outro participante encaminhava a reunião.</span><span class="sxs-lookup"><span data-stu-id="ff067-531">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff067-532">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff067-532">PowerPoint</span></span>

- <span data-ttu-id="ff067-533">Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.</span><span class="sxs-lookup"><span data-stu-id="ff067-533">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="ff067-534">Corrigimos um problema que causava um erro ao salvar o arquivo após duplicar um slide que continha um áudio recém-gravado.</span><span class="sxs-lookup"><span data-stu-id="ff067-534">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="ff067-535">Resolvemos um problema de VBA em que Slide.Shapes.AddMediaObject2 travava com formatos de vídeo herdados (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="ff067-535">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="ff067-536">Essa alteração resolve um problema com a manipulação de erros que podem ocorrer durante o carregamento do vídeo.</span><span class="sxs-lookup"><span data-stu-id="ff067-536">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="ff067-537">Corrigido um problema com copiar/colar uma equação do Word para o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ff067-537">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="project"></a><span data-ttu-id="ff067-538">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="ff067-538">Project</span></span>

- <span data-ttu-id="ff067-539">Corrigido um problema em que projetos específicos podiam ser abertos se houvesse um problema com o arquivo de projeto em uma parte específica da carga.</span><span class="sxs-lookup"><span data-stu-id="ff067-539">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="ff067-540">Word</span><span class="sxs-lookup"><span data-stu-id="ff067-540">Word</span></span>

- <span data-ttu-id="ff067-541">Corrigido um bug de declaração exposto por portas otimizadas que afetavam o Word.</span><span class="sxs-lookup"><span data-stu-id="ff067-541">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


- <span data-ttu-id="ff067-542">Corrigimos um problema no qual os estilos de documento são substituídos por outros estilos do modelo.</span><span class="sxs-lookup"><span data-stu-id="ff067-542">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="ff067-543">Essa alteração resolve um problema com o cursor ao editar um documento.</span><span class="sxs-lookup"><span data-stu-id="ff067-543">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="ff067-544">Corrigido um problema com copiar/colar uma equação do Word para o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ff067-544">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff067-545">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ff067-545">Office Suite</span></span>

- <span data-ttu-id="ff067-546">Corrigido um problema em que a instalação de uma versão mais recente do Office em relação a certas versões mais antigas pode resultar em funcionalidade prejudicada (como a impossibilidade de usar o Power Query) devido à falta de entradas de registro.</span><span class="sxs-lookup"><span data-stu-id="ff067-546">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="ff067-547">Corrigido um problema de arquivo que seria aberto como NOT SyncBacked quando o URL do cache e o URL do OneDrive NÃO correspondessem.</span><span class="sxs-lookup"><span data-stu-id="ff067-547">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="ff067-548">Corrigimos um problema em que o SaveRequestManagerCam estava fazendo com que o aplicativo fosse fechado em vez de retornar um erro.</span><span class="sxs-lookup"><span data-stu-id="ff067-548">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2010-january-12"></a><span data-ttu-id="ff067-550">Versão 2010: 12 de janeiro</span><span class="sxs-lookup"><span data-stu-id="ff067-550">Version 2010: January 12</span></span>
<span data-ttu-id="ff067-551">*Versão 2010 (Build 13328.20550)*</span><span class="sxs-lookup"><span data-stu-id="ff067-551">*Version 2010 (Build 13328.20550)*</span></span>

<span data-ttu-id="ff067-552">Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ff067-552">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER FIM)

> [!NOTE]
> <span data-ttu-id="ff067-556">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="ff067-556">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|MEC|Production|Feature|16.0.14026.20334|version-2105-july-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13929.20408|version-2104-june-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

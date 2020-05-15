---
title: Notas de versão para lançamentos do Canal Semestral em 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI as notas de versão para as versões do Canal mensal do Microsoft 365 Apps em 2020
ms.openlocfilehash: 6619411170491543c4853e6db56fa845a7adc6e3
ms.sourcegitcommit: fb97680a81c7d96b0f0f539dc3e3c8c28ad654e9
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/13/2020
ms.locfileid: "44222074"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="1a837-103">Notas de versão para lançamentos do Canal Semestral em 2020</span><span class="sxs-lookup"><span data-stu-id="1a837-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="1a837-104">Estas notas de versão fornecem informações dos novos recursos e atualizações não relacionadas à segurança que estão inclusas nas atualizações de 2020 do Canal mensal do Microsoft 365 Apps para empresas, Microsoft 365 Apps para negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="1a837-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="1a837-105">Estamos fazendo algumas alterações nos canais de atualização para os Aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="1a837-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="1a837-106">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="1a837-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="1a837-107">O OneNote 2016 já está incluído por padrão quando um usuário no Canal semestral baixar e instalar o Microsoft 365 no Windows 10 do Portal do Office.</span><span class="sxs-lookup"><span data-stu-id="1a837-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-may-12"></a><span data-ttu-id="1a837-109">Versão 1908: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="1a837-109">Version 1908: May 12</span></span>
<span data-ttu-id="1a837-110">*Versão 1908 (Build 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="1a837-110">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="1a837-111">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-113">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-113">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="1a837-114">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-114">Excel</span></span>

- <span data-ttu-id="1a837-115">Ao copiar dados filtrados por cor para uma coluna com uma largura diferente, os valores não seriam colados.</span><span class="sxs-lookup"><span data-stu-id="1a837-115">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="1a837-116">Corrigimos um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="1a837-116">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="1a837-117">Corrigimos um problema com o VBA no qual a escrita de valores em um intervalo seria menor do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="1a837-117">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="1a837-118">Corrigimos um problema em que a propriedade "O Valor Cruza Em" se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="1a837-118">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="1a837-119">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="1a837-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

### <a name="onenote"></a><span data-ttu-id="1a837-120">OneNote</span><span class="sxs-lookup"><span data-stu-id="1a837-120">OneNote</span></span>

- <span data-ttu-id="1a837-121">Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="1a837-121">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="1a837-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-122">Outlook</span></span>

- <span data-ttu-id="1a837-123">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao abrir arquivos. msg e. oft após aplicar uma atualização recente do Windows.</span><span class="sxs-lookup"><span data-stu-id="1a837-123">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="1a837-124">Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="1a837-124">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="1a837-125">Foi solucionado um problema que fazia com que o botão "Salvar na nuvem" não estivesse presente nas Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="1a837-125">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="1a837-126">Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses.</span><span class="sxs-lookup"><span data-stu-id="1a837-126">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="1a837-127">Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido.</span><span class="sxs-lookup"><span data-stu-id="1a837-127">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="1a837-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="1a837-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="1a837-129">0 = Padrão.</span><span class="sxs-lookup"><span data-stu-id="1a837-129">0 = Default.</span></span>  <span data-ttu-id="1a837-130">1 = mostraremos apenas a política de texto de política de retenção.</span><span class="sxs-lookup"><span data-stu-id="1a837-130">1 = we will only show the PolicyName for Retention policy text.</span></span>


### <a name="word"></a><span data-ttu-id="1a837-131">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-131">Word</span></span>

- <span data-ttu-id="1a837-132">Corrigimos um problema ao unir dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="1a837-132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="1a837-133">Corrigimos um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="1a837-133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-may-12"></a><span data-ttu-id="1a837-135">Versão 1902: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="1a837-135">Version 1902: May 12</span></span>
<span data-ttu-id="1a837-136">*Versão 1902 (Build 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="1a837-136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="1a837-137">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-139">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="1a837-140">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-140">Outlook</span></span>

- <span data-ttu-id="1a837-141">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao abrir arquivos. msg e. oft após aplicar uma atualização recente do Windows.</span><span class="sxs-lookup"><span data-stu-id="1a837-141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="1a837-142">Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses.</span><span class="sxs-lookup"><span data-stu-id="1a837-142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="1a837-143">Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido.</span><span class="sxs-lookup"><span data-stu-id="1a837-143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="1a837-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="1a837-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="1a837-145">0 = Padrão.</span><span class="sxs-lookup"><span data-stu-id="1a837-145">0 = Default.</span></span>  <span data-ttu-id="1a837-146">1 = mostraremos apenas a política de texto de política de retenção.</span><span class="sxs-lookup"><span data-stu-id="1a837-146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-may-04"></a><span data-ttu-id="1a837-148">Versão 1908: 04 de maio</span><span class="sxs-lookup"><span data-stu-id="1a837-148">Version 1908: May 04</span></span>
<span data-ttu-id="1a837-149">*Versão 1908 (Build 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="1a837-149">*Version 1908 (Build 11929.20752)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="1a837-150">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-150">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1a837-151">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="1a837-151">Office Suite</span></span>

- <span data-ttu-id="1a837-152">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="1a837-152">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="1a837-153">Versão 1902: 04 de maio</span><span class="sxs-lookup"><span data-stu-id="1a837-153">Version 1902: May 04</span></span>
<span data-ttu-id="1a837-154">*Versão 1902 (Build 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="1a837-154">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="1a837-155">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-155">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1a837-156">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="1a837-156">Office Suite</span></span>

- <span data-ttu-id="1a837-157">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="1a837-157">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-14"></a><span data-ttu-id="1a837-158">Versão 1908: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="1a837-158">Version 1908: April 14</span></span>
<span data-ttu-id="1a837-159">*Versão 1908 (Build 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="1a837-159">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="1a837-160">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-162">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-162">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1a837-163">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-163">Excel</span></span>

- <span data-ttu-id="1a837-164">Foi corrigido um problema que levava à lentidão no desempenho ao excluir colunas contendo células mescladas.</span><span class="sxs-lookup"><span data-stu-id="1a837-164">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="1a837-165">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="1a837-165">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="1a837-166">Skype</span><span class="sxs-lookup"><span data-stu-id="1a837-166">Skype</span></span>

- <span data-ttu-id="1a837-167">Nome do título fixo da conversa com guias enquanto mais de uma conversa está em andamento.</span><span class="sxs-lookup"><span data-stu-id="1a837-167">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="1a837-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-168">Outlook</span></span>

- <span data-ttu-id="1a837-169">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao desligar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-169">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="1a837-170">Solucionamos um problema que fazia com que uma lista de salas vazia fosse exibida para os clientes em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="1a837-170">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1a837-171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1a837-171">PowerPoint</span></span>

- <span data-ttu-id="1a837-172">Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.</span><span class="sxs-lookup"><span data-stu-id="1a837-172">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="1a837-173">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-173">Word</span></span>

- <span data-ttu-id="1a837-174">Foi corrigido um problema no ajuste de texto de tabela.</span><span class="sxs-lookup"><span data-stu-id="1a837-174">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="1a837-175">Versão 1902: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="1a837-175">Version 1902: April 14</span></span>
<span data-ttu-id="1a837-176">*Versão 1902 (Build 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="1a837-176">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="1a837-177">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-march-10"></a><span data-ttu-id="1a837-179">Versão 1908: 10 de março</span><span class="sxs-lookup"><span data-stu-id="1a837-179">Version 1908: March 10</span></span>
<span data-ttu-id="1a837-180">*Versão 1908 (Build 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="1a837-180">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="1a837-181">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-181">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-183">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-183">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1a837-184">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-184">Excel</span></span>

- <span data-ttu-id="1a837-185">Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="1a837-185">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="1a837-186">A funcionalidade Texto em Coluna pode falhar para algumas localidades.</span><span class="sxs-lookup"><span data-stu-id="1a837-186">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="1a837-187">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="1a837-187">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1a837-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1a837-188">PowerPoint</span></span>

- <span data-ttu-id="1a837-189">Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.</span><span class="sxs-lookup"><span data-stu-id="1a837-189">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="1a837-190">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-190">Word</span></span>

- <span data-ttu-id="1a837-191">Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.</span><span class="sxs-lookup"><span data-stu-id="1a837-191">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1a837-192">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="1a837-192">Office Suite</span></span>

- <span data-ttu-id="1a837-193">Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.</span><span class="sxs-lookup"><span data-stu-id="1a837-193">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="1a837-194">Versão 1902: 10 de março</span><span class="sxs-lookup"><span data-stu-id="1a837-194">Version 1902: March 10</span></span>
<span data-ttu-id="1a837-195">*Versão 1902 (Build 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="1a837-195">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="1a837-196">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a><span data-ttu-id="1a837-198">Versão 1908: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="1a837-198">Version 1908: February 11</span></span>
<span data-ttu-id="1a837-199">*Versão 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="1a837-199">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="1a837-200">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-202">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1a837-203">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-203">Excel</span></span>

- <span data-ttu-id="1a837-204">Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.</span><span class="sxs-lookup"><span data-stu-id="1a837-204">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="1a837-205">Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.</span><span class="sxs-lookup"><span data-stu-id="1a837-205">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="1a837-206">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="1a837-206">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="1a837-207">Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.</span><span class="sxs-lookup"><span data-stu-id="1a837-207">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="1a837-208">Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.</span><span class="sxs-lookup"><span data-stu-id="1a837-208">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="1a837-209">Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.</span><span class="sxs-lookup"><span data-stu-id="1a837-209">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="1a837-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-210">Outlook</span></span>

- <span data-ttu-id="1a837-211">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="1a837-211">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="1a837-212">Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.</span><span class="sxs-lookup"><span data-stu-id="1a837-212">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="1a837-213">Solucionado um problema que fazia com que os usuários experimentassem um travamento na tela Carregando perfil ao iniciar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-213">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="1a837-214">Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.</span><span class="sxs-lookup"><span data-stu-id="1a837-214">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="1a837-215">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="1a837-215">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="1a837-216">[Aqui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.</span><span class="sxs-lookup"><span data-stu-id="1a837-216">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="1a837-217">Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.</span><span class="sxs-lookup"><span data-stu-id="1a837-217">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1a837-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1a837-218">PowerPoint</span></span>

- <span data-ttu-id="1a837-219">Melhorou um cenário de copiar e colar Copiando a Forma no slide do powerpoint e colando em outro slide em um loop poderia falhar, com exceção.</span><span class="sxs-lookup"><span data-stu-id="1a837-219">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="1a837-220">Corrigido um problema que estava causando um desempenho mais lento entre os usuários da colaboração.</span><span class="sxs-lookup"><span data-stu-id="1a837-220">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="1a837-221">Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.</span><span class="sxs-lookup"><span data-stu-id="1a837-221">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="1a837-222">Corrigimos um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-222">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="1a837-223">Project</span><span class="sxs-lookup"><span data-stu-id="1a837-223">Project</span></span>

- <span data-ttu-id="1a837-224">Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.</span><span class="sxs-lookup"><span data-stu-id="1a837-224">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="1a837-225">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-225">Word</span></span>

- <span data-ttu-id="1a837-226">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="1a837-226">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1a837-227">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="1a837-227">Office Suite</span></span>

- <span data-ttu-id="1a837-228">Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.</span><span class="sxs-lookup"><span data-stu-id="1a837-228">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-february-11"></a><span data-ttu-id="1a837-230">Versão 1902: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="1a837-230">Version 1902: February 11</span></span>
<span data-ttu-id="1a837-231">*Versão 1902 (Build 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="1a837-231">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="1a837-232">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-232">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-234">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="1a837-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-235">Outlook</span></span>

- <span data-ttu-id="1a837-236">Solucionado um problema que fazia com que os usuários encontrassem erros no algoritmo de criptografia ao enviar um email criptografado.</span><span class="sxs-lookup"><span data-stu-id="1a837-236">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="1a837-237">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-237">Word</span></span>

- <span data-ttu-id="1a837-238">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="1a837-238">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

## <a name="version-1808-february-11"></a><span data-ttu-id="1a837-241">Versão 1808: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="1a837-241">Version 1808: February 11</span></span>
<span data-ttu-id="1a837-242">*Versão 1808 (Build 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="1a837-242">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="1a837-243">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-243">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a><span data-ttu-id="1a837-245">Versão 1908:14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="1a837-245">Version 1908: January 14</span></span>
<span data-ttu-id="1a837-246">*Versão 1908 (Build 11929,20562)*</span><span class="sxs-lookup"><span data-stu-id="1a837-246">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="1a837-247">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-247">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="1a837-249">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="1a837-249">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="1a837-250">Access</span><span class="sxs-lookup"><span data-stu-id="1a837-250">Access</span></span>

- <span data-ttu-id="1a837-251">**Manter as guias dos objetos de banco de dados:** Veja as guias ativas, arraste as guias facilmente para reorganizá-las, e feche os objetos de banco de dados com apenas um clique.</span><span class="sxs-lookup"><span data-stu-id="1a837-251">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="1a837-252">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="1a837-252">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1a837-253">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="1a837-253">Switching between them has never been easier.</span></span> [<span data-ttu-id="1a837-254">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-254">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1a837-255">**Aplicar zoom com mais espaço:** aumente a caixa Zoom, altere a fonte e o Zoom lembrará de tudo.</span><span class="sxs-lookup"><span data-stu-id="1a837-255">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="1a837-256">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-256">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="1a837-257">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-257">Excel</span></span>

- <span data-ttu-id="1a837-258">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="1a837-258">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1a837-259">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="1a837-259">Switching between them has never been easier.</span></span> [<span data-ttu-id="1a837-260">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-260">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1a837-261">**Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis?</span><span class="sxs-lookup"><span data-stu-id="1a837-261">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="1a837-262">Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho.</span><span class="sxs-lookup"><span data-stu-id="1a837-262">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="1a837-263">Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.</span><span class="sxs-lookup"><span data-stu-id="1a837-263">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="1a837-264">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="1a837-264">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1a837-265">Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.</span><span class="sxs-lookup"><span data-stu-id="1a837-265">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="1a837-266">**Dê vida às suas planilhas:** insira gráficos animados em 3D para ver corações pulsando, planetas orbitando e a fúria do T-Rex na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="1a837-266">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="1a837-267">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-267">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="1a837-p111">**Saiba mais sobre seus dados:** O novo botão Ideias procura padrões em seus dados e os usa para criar sugestões inteligentes e personalizadas. [Saiba mais](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="1a837-p111">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="1a837-270">**A colaboração ficou mais fácil** : Os aperfeiçoamentos de coautoria significam que, ao trabalhar com acesso condicional, estilos de célula e muito mais, suas alterações são mescladas perfeitamente com as de seus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="1a837-270">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="1a837-271">**Una tabelas em colunas similares:** Obter e Transformar (Power Query) agora apresenta lógica de texto correspondente aproximado (também chamada de correspondência difusa) ao comparar colunas para mesclar tabelas.</span><span class="sxs-lookup"><span data-stu-id="1a837-271">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="1a837-272">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-272">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="1a837-273">**Codifique rapidamente com as melhorias do Power Query:** chegue rapidamente à conclusão de código com as cores de sintaxe e o preenchimento automático.</span><span class="sxs-lookup"><span data-stu-id="1a837-273">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="1a837-274">Também descubra facilmente funções, colunas e parâmetros.</span><span class="sxs-lookup"><span data-stu-id="1a837-274">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="1a837-275">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="1a837-275">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1a837-276">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="1a837-276">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1a837-277">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="1a837-277">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="1a837-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-278">Outlook</span></span>

- <span data-ttu-id="1a837-279">**Atualizamos a experiência de usuário do Outlook para você:** uma experiência simplificada, previamente disponível para visualização com Em Breve, projetada para ajudar você a se concentrar no que é mais importante.</span><span class="sxs-lookup"><span data-stu-id="1a837-279">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="1a837-280">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-280">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="1a837-281">**Uma faixa de opções simplificada também personalizável:** desfrute de uma única linha simplificada com os botões usados com mais frequência.</span><span class="sxs-lookup"><span data-stu-id="1a837-281">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="1a837-282">Alterne facilmente entre visualizações clássicas e simplificadas e comandos para fixar/desafixar.</span><span class="sxs-lookup"><span data-stu-id="1a837-282">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="1a837-283">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-283">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="1a837-284">**Continue trabalhando enquanto move mensagens:** Agora, o Outlook move mensagens em segundo plano para que você pode continuar trabalhando enquanto move uma grande quantidade de mensagens entre pastas.</span><span class="sxs-lookup"><span data-stu-id="1a837-284">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="1a837-285">**Crie intervalos entre reuniões consecutivas:** dê um tempo para os participantes descansarem ou se deslocarem entre os locais definindo o término antecipado das reuniões para entre cinco a dez minutos por padrão.</span><span class="sxs-lookup"><span data-stu-id="1a837-285">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="1a837-286">**Escolha a sua ação favorita:** não use Sinalizar e Excluir?</span><span class="sxs-lookup"><span data-stu-id="1a837-286">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="1a837-287">E quanto a Arquivar ou Marcar como Lida?</span><span class="sxs-lookup"><span data-stu-id="1a837-287">How about Archive or Mark as Read?</span></span> <span data-ttu-id="1a837-288">Personalize o menu de ação rápida com os comandos que você mais usa.</span><span class="sxs-lookup"><span data-stu-id="1a837-288">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="1a837-p118">**As pessoas verão o Meme que você usou:** se o texto ou as imagens estáticas não forem suficientes, use GIFs animados para convencer. [Saiba mais](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b).</span><span class="sxs-lookup"><span data-stu-id="1a837-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="1a837-291">**Uma maneira mais rápida de adicionar contas:** graças às melhorias de configuração de conta, ficou mais fácil adicionar contas do Outlook.com e do Gmail que usam a autenticação de dois fatores no Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-291">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="1a837-292">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-292">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="1a837-293">**Diga adeus aos limites de sincronização:** melhorias do Outlook acabou com o limite de pastas, então vá em frente e sincronize suas caixas de correio compartilhadas.</span><span class="sxs-lookup"><span data-stu-id="1a837-293">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="1a837-294">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="1a837-294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1a837-295">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="1a837-295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1a837-296">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="1a837-296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="1a837-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1a837-297">PowerPoint</span></span>

- <span data-ttu-id="1a837-298">**Melhoria na mudança de formas:** nomeie suas formas para ter mais controle sobre como elas são transformadas.</span><span class="sxs-lookup"><span data-stu-id="1a837-298">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="1a837-299">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-299">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="1a837-300">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="1a837-300">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1a837-301">Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.</span><span class="sxs-lookup"><span data-stu-id="1a837-301">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="1a837-302">**Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis?</span><span class="sxs-lookup"><span data-stu-id="1a837-302">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="1a837-303">Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho.</span><span class="sxs-lookup"><span data-stu-id="1a837-303">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="1a837-304">Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.</span><span class="sxs-lookup"><span data-stu-id="1a837-304">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="1a837-305">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="1a837-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1a837-306">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="1a837-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="1a837-307">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1a837-308">**Os vídeos online têm um novo lar:** salve um vídeo no Microsoft Stream para que qualquer pessoa em sua organização possa vê-lo.</span><span class="sxs-lookup"><span data-stu-id="1a837-308">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="1a837-309">Insira o link de vídeo e desfrute de uma apresentação multimídia com uma fração do tamanho do arquivo.</span><span class="sxs-lookup"><span data-stu-id="1a837-309">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="1a837-310">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-310">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="1a837-311">**Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="1a837-311">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="1a837-p126">**Saiba a opinião de seu público através de um questionário ou pesquisa:** coloque um questionário ou uma pesquisa em um slide. O Office coleta e armazena as respostas para você. [Saiba mais](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="1a837-p126">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="1a837-p127">**Inserir um vídeo online está mais fácil do que nunca:** Deseja colocar um vídeo do Vimeo ou YouTube no slide? O link da página de vídeo é tudo o que você precisa. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="1a837-p127">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="1a837-318">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="1a837-318">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1a837-319">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="1a837-319">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1a837-320">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-320">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="1a837-321">Project</span><span class="sxs-lookup"><span data-stu-id="1a837-321">Project</span></span>

- <span data-ttu-id="1a837-322">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="1a837-322">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1a837-323">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="1a837-323">Switching between them has never been easier.</span></span> [<span data-ttu-id="1a837-324">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-324">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="1a837-325">Visio</span><span class="sxs-lookup"><span data-stu-id="1a837-325">Visio</span></span>

- <span data-ttu-id="1a837-326">**Exporte diagramas de processo para o Word:** Adicione automaticamente conteúdo de diagrama, como formas e metadados, a um documento do Word.</span><span class="sxs-lookup"><span data-stu-id="1a837-326">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="1a837-327">Personalize o documento para criar as diretrizes de processo e os manuais de operação.</span><span class="sxs-lookup"><span data-stu-id="1a837-327">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="1a837-328">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-328">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="1a837-329">**Captura dupla em fluxogramas de dados:** os novos e deslumbrantes layouts para os fluxogramas do Visualizador de Dados são limpos, nítidos e fáceis de entender.</span><span class="sxs-lookup"><span data-stu-id="1a837-329">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="1a837-330">Clique na guia Design para ver as opções.</span><span class="sxs-lookup"><span data-stu-id="1a837-330">Click the Design tab for options.</span></span>

- <span data-ttu-id="1a837-331">**Estênceis criados diretamente no Azure:** crie um aplicativo de nuvem ou planeje uma arquitetura usando dezenas de estênceis do Azure.</span><span class="sxs-lookup"><span data-stu-id="1a837-331">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="1a837-332">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-332">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="1a837-p133">**Diga adeus aos links desfeitos do Excel:** não consegue encontrar a pasta de trabalho do Excel vinculada ao seu diagrama do Visualizador de Dados? Vincule-o novamente para que tudo volte ao normal. [Saiba mais](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="1a837-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="1a837-336">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="1a837-336">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1a837-337">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="1a837-337">Switching between them has never been easier.</span></span> [<span data-ttu-id="1a837-338">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-338">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1a837-339">**Exporte elementos visuais do Visio a partir do Power BI:** os elementos visuais do Visio para o Power BI agora estão sendo exibidos corretamente ao exportar relatórios do Power BI como PDFs, arquivos do PowerPoint e muito mais.</span><span class="sxs-lookup"><span data-stu-id="1a837-339">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="1a837-340">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-340">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="1a837-341">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-341">Word</span></span>

- <span data-ttu-id="1a837-342">**O modo Ferramentas de Aprendizagem tem suporte adicional para mais cores de página:** as Ferramentas de Aprendizagem no Word adicionam suporte para mais cores de tema de página, o que permite a alteração da cor da tela de fundo da página.</span><span class="sxs-lookup"><span data-stu-id="1a837-342">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="1a837-343">Várias pessoas têm desafios de leitura com um plano de fundo todo branco ou preto, então ampliamos as opções de cores no Word para PC e para Mac.</span><span class="sxs-lookup"><span data-stu-id="1a837-343">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="1a837-p137">**A edição ocorre naturalmente com o Editor por Tinta:** com um único traçado, divida ou una palavras, adicione uma nova linha ou insira palavras usando uma caneta. [Saiba mais](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="1a837-p137">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="1a837-p138">\*\*Transforme seu documento de estático para incrível: \*\* transforme seu documento em uma página da web interativa e fácil de compartilhar, com uma aparência ótima em qualquer dispositivo. [Saiba mais](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="1a837-p138">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="1a837-348">**Aumente o alcance do seu conteúdo:** precisa tornar seus documentos acessíveis?</span><span class="sxs-lookup"><span data-stu-id="1a837-348">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="1a837-349">Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho.</span><span class="sxs-lookup"><span data-stu-id="1a837-349">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="1a837-350">Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.</span><span class="sxs-lookup"><span data-stu-id="1a837-350">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="1a837-351">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="1a837-351">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1a837-352">Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.</span><span class="sxs-lookup"><span data-stu-id="1a837-352">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="1a837-353">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="1a837-353">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1a837-354">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="1a837-354">Switching between them has never been easier.</span></span> [<span data-ttu-id="1a837-355">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-355">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1a837-p142">**Melhore a compreensão com Line Focus:** percorra a linha de um documento sem distrações. Ajuste o foco para colocar uma, três ou cinco linhas na visualização de cada vez. [Saiba mais](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="1a837-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="1a837-359">**Salve suas alterações assim que forem realizadas:** Carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="1a837-359">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="1a837-360">**Chame a atenção com \@@Menções:** Use @menções nos comentários para informar a seus colegas de trabalho quando precisar deles.</span><span class="sxs-lookup"><span data-stu-id="1a837-360">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="1a837-361">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-361">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="1a837-362">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="1a837-362">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1a837-363">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="1a837-363">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1a837-364">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="1a837-364">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="1a837-365">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="1a837-365">Office Suite</span></span>

- <span data-ttu-id="1a837-366">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="1a837-366">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1a837-367">Basta digitar na caixa Pesquisar na guia Arquivo > Abrir para encontrar o arquivo que você está procurando.</span><span class="sxs-lookup"><span data-stu-id="1a837-367">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="1a837-368">**Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="1a837-368">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="1a837-369">**Controles de privacidade:** controles novos, atualizados e melhorados para dados de diagnóstico e experiências conectadas.</span><span class="sxs-lookup"><span data-stu-id="1a837-369">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="1a837-370">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-370">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="1a837-371">**Os produtos do Ofiice estão com um novo visual**Os ícones de produtos foram recriados para refletir as experiências simples, poderosas e inteligentes do Office.</span><span class="sxs-lookup"><span data-stu-id="1a837-371">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="1a837-372">**Instalação do Microsoft Teams:** o Microsoft Teams vem instalado por padrão nas instalações existentes do Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="1a837-372">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="1a837-373">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="1a837-373">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-376">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-376">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1a837-377">Access</span><span class="sxs-lookup"><span data-stu-id="1a837-377">Access</span></span>

- <span data-ttu-id="1a837-378">Essa atualização corrige um problema em que agregados como Soma podem truncar o resultado para um valor inteiro.</span><span class="sxs-lookup"><span data-stu-id="1a837-378">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="1a837-379">Essa atualização corrige um problema em que uma consulta da União que inclui referências a tabelas remotas (por exemplo, tabelas do SQL Server) pode fazer o Access fechar e reiniciar.</span><span class="sxs-lookup"><span data-stu-id="1a837-379">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="1a837-380">Esta atualização corrige um problema no Microsoft Access que pode causar o erro &quot;A consulta está corrompida&quot; quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada em SQL.</span><span class="sxs-lookup"><span data-stu-id="1a837-380">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="1a837-381">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-381">Excel</span></span>

- <span data-ttu-id="1a837-382">A dica de tecla holandesa para o título do documento foi alterada para Alt-G.</span><span class="sxs-lookup"><span data-stu-id="1a837-382">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="1a837-383">Correção de um problema no Excel em que as macros atribuídas a formas ou controles de formulário podem exibir mensagem de erro incorreta ou podem funcionar em intervalos de destino incorretos.</span><span class="sxs-lookup"><span data-stu-id="1a837-383">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="1a837-384">Resolvemos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item.</span><span class="sxs-lookup"><span data-stu-id="1a837-384">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="1a837-385">Isso corrige um problema em que é possível alterar a forma como uma Tabela Dinâmica é classificada e atualizá-la durante uma sessão de coautoria com outros usuários poderia causar uma falha.</span><span class="sxs-lookup"><span data-stu-id="1a837-385">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="1a837-386">Corrigido um problema onde o filtro de uma Tabela Dinâmica OLAP era definido como um valor que havia sido removido do cubo.</span><span class="sxs-lookup"><span data-stu-id="1a837-386">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="1a837-387">Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico.</span><span class="sxs-lookup"><span data-stu-id="1a837-387">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="1a837-388">Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.</span><span class="sxs-lookup"><span data-stu-id="1a837-388">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="1a837-389">Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.</span><span class="sxs-lookup"><span data-stu-id="1a837-389">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="1a837-390">Correção de um problema de conflito de mesclagem no Excel, que resultaria na reabertura de uma pasta de trabalho para os usuários.</span><span class="sxs-lookup"><span data-stu-id="1a837-390">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="1a837-391">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="1a837-391">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="1a837-392">Resolvido um problema que causava um erro no tempo de execução da macro ao ativar janelas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="1a837-392">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="1a837-393">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="1a837-393">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="1a837-394">Resolveu um problema que fazia com que as operações de recortar e colar próximas de uma tabela falhassem durante coautoria com outras pessoas.</span><span class="sxs-lookup"><span data-stu-id="1a837-394">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="1a837-395">Resolvemos um problema que causou interrupções na coautoria ao alterar propriedades personalizadas com a execução de macros.</span><span class="sxs-lookup"><span data-stu-id="1a837-395">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="1a837-396">Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.</span><span class="sxs-lookup"><span data-stu-id="1a837-396">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="1a837-397">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="1a837-397">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="1a837-398">Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.</span><span class="sxs-lookup"><span data-stu-id="1a837-398">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="1a837-399">Melhorias significativas no desempenho da exclusão de colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="1a837-399">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="1a837-400">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="1a837-400">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="1a837-401">Resolvido um problema em que a função Proc poderia retornar um erro.</span><span class="sxs-lookup"><span data-stu-id="1a837-401">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="1a837-402">Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.</span><span class="sxs-lookup"><span data-stu-id="1a837-402">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="1a837-403">Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.</span><span class="sxs-lookup"><span data-stu-id="1a837-403">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="1a837-404">Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta.</span><span class="sxs-lookup"><span data-stu-id="1a837-404">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="1a837-405">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="1a837-405">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="1a837-406">Melhoramos significativamente o desempenho da filtragem por cor.</span><span class="sxs-lookup"><span data-stu-id="1a837-406">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="1a837-407">Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.</span><span class="sxs-lookup"><span data-stu-id="1a837-407">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="1a837-408">Habilitamos mais de 16 suplementos para serem exibidos ao navegar no gerenciador de suplementos.</span><span class="sxs-lookup"><span data-stu-id="1a837-408">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="1a837-409">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="1a837-409">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="1a837-410">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="1a837-410">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1a837-411">Esta atualização corrige um erro em que os documentos do Office podem falhar ao carregar no OneDrive for Business com a mensagem "Falha no Carregamento".</span><span class="sxs-lookup"><span data-stu-id="1a837-411">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="1a837-412">Corrigimos um problema no recurso Ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="1a837-412">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="1a837-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-413">Outlook</span></span>

- <span data-ttu-id="1a837-414">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="1a837-414">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1a837-415">Correção de um problema em que os usuários que atualizavam a caixa de correio de uma autenticação básica para a moderna acabavam com a conta errada associada ao perfil do Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-415">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="1a837-416">Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais quando não deveriam.</span><span class="sxs-lookup"><span data-stu-id="1a837-416">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="1a837-417">Resolvido um problema que provocou falha na exibição de URLs de foco simples para alguns safelinks.</span><span class="sxs-lookup"><span data-stu-id="1a837-417">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="1a837-418">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="1a837-418">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="1a837-419">Resolvido um problema que fazia com que um subconjunto de usuários POP3 visualizasse todos os seus e-mails formatados em texto sem formatação, independentemente das configurações.</span><span class="sxs-lookup"><span data-stu-id="1a837-419">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="1a837-420">Essa correção restaurará o modo de exibição das mensagens formatadas como HTML.</span><span class="sxs-lookup"><span data-stu-id="1a837-420">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="1a837-421">Resolvido um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.</span><span class="sxs-lookup"><span data-stu-id="1a837-421">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="1a837-422">Resolvido um problema que fazia com que os usuários não conseguissem acessar sugestões de localização por meio de um leitor de tela.</span><span class="sxs-lookup"><span data-stu-id="1a837-422">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="1a837-423">Resolvido um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="1a837-423">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="1a837-424">Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-424">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="1a837-425">Resolvido um problema que fazia com que usuários vissem um aviso “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo de Regras.</span><span class="sxs-lookup"><span data-stu-id="1a837-425">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="1a837-426">Resolvido um problema que faria com que os usuários experimentassem uma falha no Outlook ao interagir com determinados safelinks.</span><span class="sxs-lookup"><span data-stu-id="1a837-426">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="1a837-427">Resolvido um problema que causava ambiguidade para os gerentes sobre se um representante já havia ou não respondido a uma determinada solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="1a837-427">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="1a837-428">Resolvido um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.</span><span class="sxs-lookup"><span data-stu-id="1a837-428">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="1a837-429">Resolvido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="1a837-429">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="1a837-430">Essa alteração permite que os administradores habilitem uma política para preferir o email da conta fornecida nos prompts de autenticação da Descoberta Automática no UPN.</span><span class="sxs-lookup"><span data-stu-id="1a837-430">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="1a837-431">Por padrão, a Descoberta Automática prefere o UPN da conta, quando disponível.</span><span class="sxs-lookup"><span data-stu-id="1a837-431">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="1a837-432">Solucionamos um problema que fazia com que os usuários ver falhas de pesquisa em Grupos Modernos.</span><span class="sxs-lookup"><span data-stu-id="1a837-432">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="1a837-433">Resolvido um problema que fazia com que os usuários do Outlook travassem no estado "Senha Necessária" em determinados cenários.</span><span class="sxs-lookup"><span data-stu-id="1a837-433">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="1a837-434">Resolvido um problema que fazia com que os usuários vissem sugestões de salas para reuniões que ocorriam fora do horário de disponibilidade dessa sala.</span><span class="sxs-lookup"><span data-stu-id="1a837-434">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="1a837-435">Corrigido um problema que fazia com que os usuários encontrassem erros de "Não há suporte para algoritmo de criptografia" ao enviar um email criptografado.</span><span class="sxs-lookup"><span data-stu-id="1a837-435">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="1a837-436">Corrigido um problema para usuários não falantes de inglês, onde a linha de assunto em um e-mail seria incrivelmente pequena.</span><span class="sxs-lookup"><span data-stu-id="1a837-436">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="1a837-437">Resolvido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1a837-437">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="1a837-438">Resolvido um problema que fazia com que os usuários experimentassem uma falha ao tentar criar uma regra a partir de uma mensagem de “Conversa Perdida”.</span><span class="sxs-lookup"><span data-stu-id="1a837-438">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="1a837-439">Corrigido um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="1a837-439">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="1a837-440">Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.</span><span class="sxs-lookup"><span data-stu-id="1a837-440">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="1a837-441">Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-441">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="1a837-442">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="1a837-442">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="1a837-443">Corrigido um problema que fazia com que a pesquisa de pasta atual falhasse intermitentemente.</span><span class="sxs-lookup"><span data-stu-id="1a837-443">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="1a837-444">Corrigido um problema que fazia com que alguns usuários encontrassem erros de autenticação ao tentar recuperar as configurações de nuvem do Outlook.</span><span class="sxs-lookup"><span data-stu-id="1a837-444">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="1a837-445">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="1a837-445">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="1a837-446">Resolvido um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.</span><span class="sxs-lookup"><span data-stu-id="1a837-446">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="1a837-447">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="1a837-447">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1a837-448">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1a837-448">PowerPoint</span></span>

- <span data-ttu-id="1a837-449">Correção de um problema em que alguns suplementos lançavam erros inesperados relacionados às formas nos gráficos.</span><span class="sxs-lookup"><span data-stu-id="1a837-449">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="1a837-450">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="1a837-450">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1a837-451">Essa alteração restaura o nome acessível para os controles de vídeo do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-451">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="1a837-452">Corrigimos um problema que poderia impedir a inicialização de algumas animações.</span><span class="sxs-lookup"><span data-stu-id="1a837-452">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="1a837-453">Corrigimos um problema ao copiar um slide de uma apresentação para outra, criando mestres duplicados.</span><span class="sxs-lookup"><span data-stu-id="1a837-453">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="1a837-454">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada</span><span class="sxs-lookup"><span data-stu-id="1a837-454">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="1a837-455">Correção de confiabilidade: Corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-455">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="1a837-456">Corrigido um problema em que os caracteres katakana de meia largura não giravam corretamente nas caixas de texto verticais no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-456">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="1a837-457">Project</span><span class="sxs-lookup"><span data-stu-id="1a837-457">Project</span></span>

- <span data-ttu-id="1a837-458">Correção de um problema para que os usuários do Windows 7 possam abrir projetos do Project Web App e sites do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-458">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="1a837-459">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="1a837-459">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="1a837-460">O comando Nivelar Tudo não resolve adequadamente uma superalocação de recursos.</span><span class="sxs-lookup"><span data-stu-id="1a837-460">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="1a837-461">Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.</span><span class="sxs-lookup"><span data-stu-id="1a837-461">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="1a837-462">Visio</span><span class="sxs-lookup"><span data-stu-id="1a837-462">Visio</span></span>

- <span data-ttu-id="1a837-463">A exportação como SVG do Visio falhou em várias formas.</span><span class="sxs-lookup"><span data-stu-id="1a837-463">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="1a837-464">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-464">Word</span></span>

- <span data-ttu-id="1a837-465">Essa alteração levará a melhorias de desempenho na abertura de documentos usando o Word.</span><span class="sxs-lookup"><span data-stu-id="1a837-465">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="1a837-466">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="1a837-466">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1a837-467">Corrigimos um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet.</span><span class="sxs-lookup"><span data-stu-id="1a837-467">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="1a837-468">Corrigimos um problema no controle de alterações que, às vezes, entravam em loop infinito.</span><span class="sxs-lookup"><span data-stu-id="1a837-468">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="1a837-469">Corrigidos vários problemas em que o aplicativo pode travar no desligamento.</span><span class="sxs-lookup"><span data-stu-id="1a837-469">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="1a837-470">E também corrige determinadas falhas relacionadas aos suplementos.</span><span class="sxs-lookup"><span data-stu-id="1a837-470">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1a837-471">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="1a837-471">Office Suite</span></span>

- <span data-ttu-id="1a837-472">Corrigido de um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.</span><span class="sxs-lookup"><span data-stu-id="1a837-472">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="1a837-473">Corrigido um problema que fazia com que os usuários recebessem a mensagem "Algo está nos impedindo de compartilhar isso" ao tentar compartilhar arquivos armazenados no SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="1a837-473">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="1a837-474">Corrigido um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-474">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="1a837-475">Esta é uma correção para uma falha que os usuários podem encontrar ao abrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="1a837-475">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="1a837-476">Impede que os usuários do PowerPoint se deparem com erro ao tentar Apresentar Online.</span><span class="sxs-lookup"><span data-stu-id="1a837-476">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="1a837-477">Em alguns casos, um arquivo do mecanismo de sincronização do SharePoint poderia exibir "Salvo", mas não ter salvado alterações, o que resulta em perda de dados.</span><span class="sxs-lookup"><span data-stu-id="1a837-477">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="1a837-478">Resolvemos um problema em que os usuários poderiam não conseguir salvar documentos do Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1a837-478">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="1a837-479">Esse problema afeta os usuários que criam um novo arquivo e escolhem a opção "caixa de diálogo Salvar como" depois de clicar no ícone Salvar ou pressionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="1a837-479">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="1a837-480">Corrigido um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.</span><span class="sxs-lookup"><span data-stu-id="1a837-480">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="1a837-481">Corrigido um bug em que as informações de acessibilidade não estavam sendo exibidas na laje Info Place dos bastidores.</span><span class="sxs-lookup"><span data-stu-id="1a837-481">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="1a837-482">Melhora a confiabilidade do processo de atualização do Office referente à integridade do registro.</span><span class="sxs-lookup"><span data-stu-id="1a837-482">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="1a837-483">Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="1a837-483">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="1a837-484">Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado.</span><span class="sxs-lookup"><span data-stu-id="1a837-484">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="1a837-485">Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.</span><span class="sxs-lookup"><span data-stu-id="1a837-485">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="1a837-486">Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.</span><span class="sxs-lookup"><span data-stu-id="1a837-486">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="1a837-487">Em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização.</span><span class="sxs-lookup"><span data-stu-id="1a837-487">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="1a837-488">Essa atualização melhora a confiabilidade ao publicar os atalhos do Office.</span><span class="sxs-lookup"><span data-stu-id="1a837-488">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="1a837-489">Corrigimos um problema em que as atualizações poderiam ser bloqueadas inesperadamente em redes limitadas.</span><span class="sxs-lookup"><span data-stu-id="1a837-489">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="1a837-490">Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="1a837-490">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="1a837-491">Maior confiabilidade ao baixar as atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.</span><span class="sxs-lookup"><span data-stu-id="1a837-491">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="1a837-492">Corrigido problemas relacionados à propriedade AutoAjuste da Caixa de texto/ Forma em plug-ins de terceiros.</span><span class="sxs-lookup"><span data-stu-id="1a837-492">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="1a837-493">Corrigimos um problema em que grandes modos de exibição em árvore poderiam resultar em falha.</span><span class="sxs-lookup"><span data-stu-id="1a837-493">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="1a837-494">Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.</span><span class="sxs-lookup"><span data-stu-id="1a837-494">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-january-14"></a><span data-ttu-id="1a837-496">Versão 1902: 14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="1a837-496">Version 1902: January 14</span></span>
<span data-ttu-id="1a837-497">*Versão 1902 (Build 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="1a837-497">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="1a837-498">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-498">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="1a837-500">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="1a837-500">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1a837-501">Excel</span><span class="sxs-lookup"><span data-stu-id="1a837-501">Excel</span></span>

- <span data-ttu-id="1a837-502">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="1a837-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="1a837-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="1a837-503">Outlook</span></span>

- <span data-ttu-id="1a837-504">Corrigido um problema que fazia com que os usuários encontrassem erros de "algoritmo de criptografia não é suportado" ao enviar um email criptografado.</span><span class="sxs-lookup"><span data-stu-id="1a837-504">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1a837-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1a837-505">PowerPoint</span></span>

- <span data-ttu-id="1a837-506">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada.</span><span class="sxs-lookup"><span data-stu-id="1a837-506">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="1a837-507">Word</span><span class="sxs-lookup"><span data-stu-id="1a837-507">Word</span></span>

- <span data-ttu-id="1a837-508">Essa alteração levará a melhorias de desempenho na abertura de documentos usando o Word.</span><span class="sxs-lookup"><span data-stu-id="1a837-508">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-january-14"></a><span data-ttu-id="1a837-510">Versão 1808: 14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="1a837-510">Version 1808: January 14</span></span>
<span data-ttu-id="1a837-511">*Versão 1808 (Build 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="1a837-511">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="1a837-512">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1a837-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="1a837-514">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="1a837-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

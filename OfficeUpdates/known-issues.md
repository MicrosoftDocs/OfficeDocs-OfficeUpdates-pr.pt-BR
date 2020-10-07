---
title: Problemas conhecidos do Office 365 ProPlus
ms.author: anankani
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Fornece informações sobre problemas conhecidos do Office 365 ProPlus
ms.openlocfilehash: eb771e0584a76f4ab4d506987a6b2379cc7087ee
ms.sourcegitcommit: db492a4c51ec771ab97c67e4b1d43ee36d8794b8
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/07/2020
ms.locfileid: "48369939"
---
# <a name="microsoft-365-apps-known-issues"></a><span data-ttu-id="419cd-103">Problemas conhecidos do Microsoft 365 Apps</span><span class="sxs-lookup"><span data-stu-id="419cd-103">Microsoft 365 Apps Known Issues</span></span>

<span data-ttu-id="419cd-104">Esses problemas conhecidos fornecem informações sobre as atualizações que não são de segurança incluídas no Canal Mensal, Canal Semestral (Direcionado) e atualizações de Canal Semestral em 2019 para Aplicativos do Microsoft 365 para empresas, Aplicativos do Microsoft 365 para pequenas empresas e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="419cd-104">These known issues provide information about non-security updates that are included in Monthly Channel, Semi-Annual Channel (Targeted), and Semi-Annual Channel  updates in 2019 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!NOTE]
>- <span data-ttu-id="419cd-105">Esta lista não é abrangente.</span><span class="sxs-lookup"><span data-stu-id="419cd-105">This list is not comprehensive.</span></span>
>- <span data-ttu-id="419cd-106">Se você tiver um problema em um canal diferente do canal mostrado como resolvido, poderá esperar a resolução em breve.</span><span class="sxs-lookup"><span data-stu-id="419cd-106">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="419cd-107">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="419cd-107">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="419cd-108">Os problemas resolvidos também estão documentados em suas respectivas páginas de canal.</span><span class="sxs-lookup"><span data-stu-id="419cd-108">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="419cd-109">Última Atualização: 12 de novembro de 2019</span><span class="sxs-lookup"><span data-stu-id="419cd-109">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="419cd-110">Excel</span><span class="sxs-lookup"><span data-stu-id="419cd-110">Excel</span></span>

- <span data-ttu-id="419cd-111">Controles da caixa de seleção podiam diminuir ao usar o AutoAjuste para ajustar a altura da linha</span><span class="sxs-lookup"><span data-stu-id="419cd-111">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="419cd-112">**Investigando**: Mensal, SACT</span><span class="sxs-lookup"><span data-stu-id="419cd-112">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="419cd-113">Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.</span><span class="sxs-lookup"><span data-stu-id="419cd-113">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="419cd-114">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-114">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="419cd-115">Os usuários poderiam ser impedidos de salvar no Office 365 formato de Pasta de Trabalho do Excel</span><span class="sxs-lookup"><span data-stu-id="419cd-115">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="419cd-116">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="419cd-117">Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.</span><span class="sxs-lookup"><span data-stu-id="419cd-117">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="419cd-118">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="419cd-119">Melhorias significativas no desempenho da exclusão de colunas com células mescladas</span><span class="sxs-lookup"><span data-stu-id="419cd-119">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="419cd-120">**Investigando**: SACT</span><span class="sxs-lookup"><span data-stu-id="419cd-120">**Investigating**: SACT</span></span><br><span data-ttu-id="419cd-121">**Resolvido**:  Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-121">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-122">Resultados incorretos ao converter filtros de relatórios com o restante da tabela dinâmica para consultas a servidores de tabela SQL.</span><span class="sxs-lookup"><span data-stu-id="419cd-122">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="419cd-123">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="419cd-123">**Investigating**: Monthly</span></span>

- <span data-ttu-id="419cd-124">Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico</span><span class="sxs-lookup"><span data-stu-id="419cd-124">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="419cd-125">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-125">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="419cd-126">Identificado um problema ao inserir arquivos como objeto no OneDrive.</span><span class="sxs-lookup"><span data-stu-id="419cd-126">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="419cd-127">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-127">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-128">Identificado um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam travar o Excel quando abertas nas versões atuais do Office.</span><span class="sxs-lookup"><span data-stu-id="419cd-128">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="419cd-129">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436), Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="419cd-129">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="419cd-130">Identificado um problema que estava causando atrasos na exibição de valores digitados após a exclusão de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="419cd-130">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="419cd-131">**Resolvido**: Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="419cd-131">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="419cd-132">Identificado um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="419cd-132">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="419cd-133">**Investigando**: SACT</span><span class="sxs-lookup"><span data-stu-id="419cd-133">**Investigating**: SACT</span></span> <br><span data-ttu-id="419cd-134">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-135">Identificado um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.</span><span class="sxs-lookup"><span data-stu-id="419cd-135">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="419cd-136">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="419cd-136">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="419cd-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="419cd-137">Outlook</span></span>

- <span data-ttu-id="419cd-138">Identificado um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="419cd-138">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="419cd-139">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-139">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="419cd-140">Identificado um problema que poderia resultar em um vazamento de memória.</span><span class="sxs-lookup"><span data-stu-id="419cd-140">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="419cd-141">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20388), Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="419cd-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="419cd-142">Corrigido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="419cd-142">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="419cd-143">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="419cd-144">Identificado um problema que às vezes poderia resultar em falha quando um usuário recebia uma mensagem de 'Conversa Perdida' do Skype.</span><span class="sxs-lookup"><span data-stu-id="419cd-144">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="419cd-145">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-145">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-146">Identificado um problema que fazia com que os Usuários recebessem um erro genérico “falha na operação” ao abrir um anexo em um computador em que o DisableBGSave estivesse habilitado.</span><span class="sxs-lookup"><span data-stu-id="419cd-146">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="419cd-147">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-148">Identificado um problema com os links do CID: as imagens (imagens baseadas em email do Outlook) não podiam ser desfeitas.</span><span class="sxs-lookup"><span data-stu-id="419cd-148">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="419cd-149">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-149">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="419cd-150">Corrigido um problema que poderia ter causado uma mensagem de erro incorreta ao tentar enviar email criptografado s/MIME.</span><span class="sxs-lookup"><span data-stu-id="419cd-150">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="419cd-151">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="419cd-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="419cd-152">PowerPoint</span></span>

- <span data-ttu-id="419cd-153">Alguns caracteres katakana podem ser exibidos incorretamente em uma caixa de texto vertical.</span><span class="sxs-lookup"><span data-stu-id="419cd-153">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="419cd-154">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="419cd-154">**Investigating**: Monthly</span></span>

- <span data-ttu-id="419cd-155">Corrigido um problema que impedia a criação de hiperlink ao colar texto com hiperlink.</span><span class="sxs-lookup"><span data-stu-id="419cd-155">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="419cd-156">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-156">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-157">Corrigido um problema que poderia causar a quebra de TextRanges após colar o texto nos espaços reservados de cabeçalho/rodapé/número de slide no slide mestre e no layout do slide.</span><span class="sxs-lookup"><span data-stu-id="419cd-157">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="419cd-158">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="419cd-159">Identificado um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.</span><span class="sxs-lookup"><span data-stu-id="419cd-159">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="419cd-160">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20396), Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="419cd-160">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="419cd-161">Project</span><span class="sxs-lookup"><span data-stu-id="419cd-161">Project</span></span>

- <span data-ttu-id="419cd-162">Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.</span><span class="sxs-lookup"><span data-stu-id="419cd-162">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="419cd-163">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="419cd-163">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="419cd-164">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-164">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="419cd-165">As superalocações não são resolvidas por nivelamento</span><span class="sxs-lookup"><span data-stu-id="419cd-165">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="419cd-166">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="419cd-166">**Investigating**: Monthly</span></span>

- <span data-ttu-id="419cd-167">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="419cd-167">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="419cd-168">**Resolvido**: Versão Mensal 1910 (12130.20344), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="419cd-168">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="419cd-169">Word</span><span class="sxs-lookup"><span data-stu-id="419cd-169">Word</span></span>

- <span data-ttu-id="419cd-170">A pesquisa no painel Navegação pode falhar</span><span class="sxs-lookup"><span data-stu-id="419cd-170">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="419cd-171">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="419cd-171">**Investigating**: Monthly</span></span>

- <span data-ttu-id="419cd-172">Identificado um problema ao inserir arquivos como objeto no OneDrive.</span><span class="sxs-lookup"><span data-stu-id="419cd-172">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="419cd-173">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="419cd-173">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="419cd-174">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="419cd-174">Office Suite</span></span>
- <span data-ttu-id="419cd-175">Tentar salvar um arquivo em um compartilhamento de rede desconectado podem ocasionar uma falha **Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="419cd-175">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="419cd-176">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="419cd-176">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

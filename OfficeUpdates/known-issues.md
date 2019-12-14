---
title: Problemas conhecidos do Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Fornece informações sobre problemas conhecidos do Office 365 ProPlus
ms.openlocfilehash: 73cd91d43e09900d81418427dab1da01d89f227b
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023546"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="ad63d-103">Problemas conhecidos do Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="ad63d-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="ad63d-104">Esses problemas conhecidos fornecem informações sobre atualizações não relacionadas à segurança incluídas nas atualizações do Canal Mensal, SACT e SAC para o Office 365 ProPlus 2019, Visio Pro para Office 365, Cliente de Área de Trabalho do Microsoft Project Online e Office 365 Business.</span><span class="sxs-lookup"><span data-stu-id="ad63d-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="ad63d-105">Esta tabela oferece um resumo dos problemas ativos atuais e dos que foram resolvidos.</span><span class="sxs-lookup"><span data-stu-id="ad63d-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="ad63d-106">Atualizaremos a tabela abaixo com problemas significativos que estamos investigando.</span><span class="sxs-lookup"><span data-stu-id="ad63d-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="ad63d-107">Esta lista não é abrangente.</span><span class="sxs-lookup"><span data-stu-id="ad63d-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="ad63d-108">Se você tiver um problema em um canal diferente do canal mostrado como resolvido, poderá esperar a resolução em breve.</span><span class="sxs-lookup"><span data-stu-id="ad63d-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="ad63d-109">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ad63d-109">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="ad63d-110">Os problemas resolvidos também estão documentados em suas respectivas páginas de canal.</span><span class="sxs-lookup"><span data-stu-id="ad63d-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="ad63d-111">Última Atualização: 12 de novembro de 2019</span><span class="sxs-lookup"><span data-stu-id="ad63d-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="ad63d-112">Excel</span><span class="sxs-lookup"><span data-stu-id="ad63d-112">Excel</span></span>

- <span data-ttu-id="ad63d-113">Controles da caixa de seleção podiam diminuir ao usar o AutoAjuste para ajustar a altura da linha</span><span class="sxs-lookup"><span data-stu-id="ad63d-113">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="ad63d-114">**Investigando**: Mensal, SACT</span><span class="sxs-lookup"><span data-stu-id="ad63d-114">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="ad63d-115">Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.</span><span class="sxs-lookup"><span data-stu-id="ad63d-115">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="ad63d-116">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="ad63d-117">Os usuários poderiam ser impedidos de salvar no Office 365 formato de Pasta de Trabalho do Excel</span><span class="sxs-lookup"><span data-stu-id="ad63d-117">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="ad63d-118">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="ad63d-119">Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.</span><span class="sxs-lookup"><span data-stu-id="ad63d-119">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="ad63d-120">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-120">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="ad63d-121">Melhorias significativas no desempenho da exclusão de colunas com células mescladas</span><span class="sxs-lookup"><span data-stu-id="ad63d-121">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="ad63d-122">**Investigando**: SACT</span><span class="sxs-lookup"><span data-stu-id="ad63d-122">**Investigating**: SACT</span></span><br><span data-ttu-id="ad63d-123">**Resolvido**:  Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-123">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-124">Resultados incorretos ao converter filtros de relatórios com o restante da tabela dinâmica para consultas a servidores de tabela SQL.</span><span class="sxs-lookup"><span data-stu-id="ad63d-124">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="ad63d-125">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="ad63d-125">**Investigating**: Monthly</span></span>

- <span data-ttu-id="ad63d-126">Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico</span><span class="sxs-lookup"><span data-stu-id="ad63d-126">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="ad63d-127">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-127">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="ad63d-128">Identificado um problema ao inserir arquivos como objeto no OneDrive.</span><span class="sxs-lookup"><span data-stu-id="ad63d-128">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="ad63d-129">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-129">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-130">Identificado um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam travar o Excel quando abertas nas versões atuais do Office.</span><span class="sxs-lookup"><span data-stu-id="ad63d-130">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="ad63d-131">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436), Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="ad63d-131">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="ad63d-132">Identificado um problema que estava causando atrasos na exibição de valores digitados após a exclusão de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="ad63d-132">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="ad63d-133">**Resolvido**: Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="ad63d-133">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="ad63d-134">Identificado um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="ad63d-134">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="ad63d-135">**Investigando**: SACT</span><span class="sxs-lookup"><span data-stu-id="ad63d-135">**Investigating**: SACT</span></span> <br><span data-ttu-id="ad63d-136">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-136">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-137">Identificado um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.</span><span class="sxs-lookup"><span data-stu-id="ad63d-137">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="ad63d-138">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="ad63d-138">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="ad63d-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="ad63d-139">Outlook</span></span>

- <span data-ttu-id="ad63d-140">Identificado um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ad63d-140">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="ad63d-141">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="ad63d-142">Identificado um problema que poderia resultar em um vazamento de memória.</span><span class="sxs-lookup"><span data-stu-id="ad63d-142">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="ad63d-143">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20388), Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="ad63d-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="ad63d-144">Corrigido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ad63d-144">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="ad63d-145">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="ad63d-146">Identificado um problema que às vezes poderia resultar em falha quando um usuário recebia uma mensagem de 'Conversa Perdida' do Skype.</span><span class="sxs-lookup"><span data-stu-id="ad63d-146">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="ad63d-147">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-148">Identificado um problema que fazia com que os Usuários recebessem um erro genérico “falha na operação” ao abrir um anexo em um computador em que o DisableBGSave estivesse habilitado.</span><span class="sxs-lookup"><span data-stu-id="ad63d-148">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="ad63d-149">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-149">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-150">Identificado um problema com os links do CID: as imagens (imagens baseadas em email do Outlook) não podiam ser desfeitas.</span><span class="sxs-lookup"><span data-stu-id="ad63d-150">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="ad63d-151">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-151">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="ad63d-152">Corrigido um problema que poderia ter causado uma mensagem de erro incorreta ao tentar enviar email criptografado s/MIME.</span><span class="sxs-lookup"><span data-stu-id="ad63d-152">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="ad63d-153">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-153">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ad63d-154">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ad63d-154">PowerPoint</span></span>

- <span data-ttu-id="ad63d-155">Alguns caracteres katakana podem ser exibidos incorretamente em uma caixa de texto vertical.</span><span class="sxs-lookup"><span data-stu-id="ad63d-155">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="ad63d-156">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="ad63d-156">**Investigating**: Monthly</span></span>

- <span data-ttu-id="ad63d-157">Corrigido um problema que impedia a criação de hiperlink ao colar texto com hiperlink.</span><span class="sxs-lookup"><span data-stu-id="ad63d-157">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="ad63d-158">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-159">Corrigido um problema que poderia causar a quebra de TextRanges após colar o texto nos espaços reservados de cabeçalho/rodapé/número de slide no slide mestre e no layout do slide.</span><span class="sxs-lookup"><span data-stu-id="ad63d-159">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="ad63d-160">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-160">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="ad63d-161">Identificado um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.</span><span class="sxs-lookup"><span data-stu-id="ad63d-161">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="ad63d-162">**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20396), Versão SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="ad63d-162">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="ad63d-163">Project</span><span class="sxs-lookup"><span data-stu-id="ad63d-163">Project</span></span>

- <span data-ttu-id="ad63d-164">Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.</span><span class="sxs-lookup"><span data-stu-id="ad63d-164">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="ad63d-165">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="ad63d-165">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="ad63d-166">**Resolvido**: Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-166">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="ad63d-167">As superalocações não são resolvidas por nivelamento</span><span class="sxs-lookup"><span data-stu-id="ad63d-167">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="ad63d-168">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="ad63d-168">**Investigating**: Monthly</span></span>

- <span data-ttu-id="ad63d-169">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="ad63d-169">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="ad63d-170">**Resolvido**: Versão Mensal 1910 (12130.20344), Versão SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ad63d-170">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="ad63d-171">Word</span><span class="sxs-lookup"><span data-stu-id="ad63d-171">Word</span></span>

- <span data-ttu-id="ad63d-172">A pesquisa no painel Navegação pode falhar</span><span class="sxs-lookup"><span data-stu-id="ad63d-172">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="ad63d-173">**Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="ad63d-173">**Investigating**: Monthly</span></span>

- <span data-ttu-id="ad63d-174">Identificado um problema ao inserir arquivos como objeto no OneDrive.</span><span class="sxs-lookup"><span data-stu-id="ad63d-174">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="ad63d-175">**Resolvido**: Versão Mensal 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="ad63d-175">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="ad63d-176">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ad63d-176">Office Suite</span></span>
- <span data-ttu-id="ad63d-177">Tentar salvar um arquivo em um compartilhamento de rede desconectado podem ocasionar uma falha **Investigando**: Mensalmente </span><span class="sxs-lookup"><span data-stu-id="ad63d-177">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="ad63d-178">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="ad63d-178">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

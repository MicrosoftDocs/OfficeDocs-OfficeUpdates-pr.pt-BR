---
title: Notas de Versão do Canal Mensal (Direcionado
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece a lista mais recente de novos recursos, correções ou problemas conhecidos para o público do Insider
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563671"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="ca93e-103">Notas de Versão do Canal Mensal do Office (Direcionado)</span><span class="sxs-lookup"><span data-stu-id="ca93e-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="ca93e-104">Este artigo contém notas de versão para builds de Canal Mensal (Direcionado) do Word, Excel, PowerPoint, Outlook, Access e Project para área de trabalho do Windows.</span><span class="sxs-lookup"><span data-stu-id="ca93e-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="ca93e-105">Toda semana, vamos destacar novos e interessantes recursos, correções importantes e quaisquer problemas significativos que você queira conhecer.</span><span class="sxs-lookup"><span data-stu-id="ca93e-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="ca93e-106">Observe que muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Mensal (Direcionado) durante um período de tempo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="ca93e-107">Isso nos permite garantir que tudo esteja funcionando bem antes de liberarmos o recurso para um público maior.</span><span class="sxs-lookup"><span data-stu-id="ca93e-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="ca93e-108">Portanto, se você não vir algo descrito abaixo, não se preocupe, você receberá eventualmente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="ca93e-109">Estamos fazendo algumas alterações nos canais de atualização do Microsoft 365 Apps, incluindo a adição de um novo canal de atualização (Canal corporativo mensal) e a alteração dos nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="ca93e-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="ca93e-110">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="ca93e-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="ca93e-111">A data de publicação das notas de versão pode não corresponder com a data de lançamento da compilação atual.</span><span class="sxs-lookup"><span data-stu-id="ca93e-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (NÃO REMOVA)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

## <a name="version-2005-june-04"></a><span data-ttu-id="ca93e-115">Versão 2005:04 de junho</span><span class="sxs-lookup"><span data-stu-id="ca93e-115">Version 2005: June 04</span></span>
<span data-ttu-id="ca93e-116">*Versão 2005 (Build 12827,20320)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ca93e-118">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ca93e-119">Access</span><span class="sxs-lookup"><span data-stu-id="ca93e-119">Access</span></span>

- <span data-ttu-id="ca93e-120">**Mantenha-se atualizado com os tempos! O tipo de dados estendidos de data/hora tem uma precisão melhor.:** apresentando um novo e aprimorado tipo de dados.</span><span class="sxs-lookup"><span data-stu-id="ca93e-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="ca93e-121">Para aprimorar a compatibilidade de sintaxe com o SQL e para aumentar a precisão e o nível de detalhes nos registros que incluem datas e horas, estamos implementando o tipo de dados DateTime2 no Access.</span><span class="sxs-lookup"><span data-stu-id="ca93e-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="ca93e-122">Essa data adicional & o tipo de dados de hora incluirá um intervalo de datas maior (0001-01-01 a 9999-12-31), com precisão de tempo mais elevada (nanossegundos, em vez de segundos) que você poderá fornecer e realizar cálculos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="ca93e-123">Para habilitar, selecione novo campo > data & tempo estendido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="ca93e-124">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="ca93e-125">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-125">Excel</span></span>

- <span data-ttu-id="ca93e-126">**Criar tabelas dinâmicas a partir de conjuntos de no Power bi no Excel:** Você pode criar tabelas dinâmicas no Excel que estão conectadas a conjuntos de os DataSets armazenados no Power BI com alguns cliques.</span><span class="sxs-lookup"><span data-stu-id="ca93e-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="ca93e-127">Isso permite obter o melhor das tabelas dinâmicas e do Power BI.</span><span class="sxs-lookup"><span data-stu-id="ca93e-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="ca93e-128">Calcule, resuma e analise os dados com tabelas dinâmicas de seus conjuntos de dados do Power BI seguro.</span><span class="sxs-lookup"><span data-stu-id="ca93e-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-129">Outlook</span></span>

- <span data-ttu-id="ca93e-130">**Opção para reabrir rapidamente os itens da sessão anterior do Outlook:** Adicionamos uma opção para reabrir rapidamente os itens de uma sessão anterior do Outlook.</span><span class="sxs-lookup"><span data-stu-id="ca93e-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-133">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="ca93e-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-134">PowerPoint</span></span>

- <span data-ttu-id="ca93e-135">Isso corrige uma falha quando os usuários têm comentários modernos e antigos em um arquivo, disparando uma atualização nos comentários.</span><span class="sxs-lookup"><span data-stu-id="ca93e-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ca93e-136">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-136">Office Suite</span></span>

- <span data-ttu-id="ca93e-137">Resolvemos o problema de taxa de falha do ValidateInstall Configurando a validação de instalação de Complementos do Bing como true por padrão e considerando o MSI Return Success como uma instalação bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="ca93e-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-29"></a><span data-ttu-id="ca93e-139">Versão 2005:29 de maio</span><span class="sxs-lookup"><span data-stu-id="ca93e-139">Version 2005: May 29</span></span>
<span data-ttu-id="ca93e-140">*Versão 2005 (Build 12827,20268)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-140">*Version 2005 (Build 12827.20268)*</span></span>

<span data-ttu-id="ca93e-141"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-141">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-142">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="ca93e-143">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-143">Excel</span></span>

- <span data-ttu-id="ca93e-144">**Modo de exibição de planilha:** Classificar/filtrar ao colaborar com outras pessoas na área de trabalho do Excel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-145">Outlook</span></span>

- <span data-ttu-id="ca93e-146">**Botões adicionais adicionados às notificações de notificação do Outlook:** Agora, os botões de ação rápida aparecem nas notificações do Outlook em caso de execução do Outlook no Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ca93e-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-149">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="ca93e-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-150">Outlook</span></span>

- <span data-ttu-id="ca93e-151">Foi corrigido um problema que fazia com que os usuários das versões do Windows 10 Server vejam o status de aviso de antivírus: inválido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="ca93e-152">Esta versão do Windows oferece suporte à detecção de antivírus, mas nenhum antivírus foi encontrado, apesar de ter o antivírus instalado corretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ca93e-153">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-153">Office Suite</span></span>

- <span data-ttu-id="ca93e-154">O host do Office estava falhando no Windows, quando um suplemento é ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth é definida como zero.</span><span class="sxs-lookup"><span data-stu-id="ca93e-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="ca93e-155">Essa alteração resolveria esse problema.</span><span class="sxs-lookup"><span data-stu-id="ca93e-155">This change would fix this issue.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-21"></a><span data-ttu-id="ca93e-157">Versão 2005:21 de maio</span><span class="sxs-lookup"><span data-stu-id="ca93e-157">Version 2005: May 21</span></span>
<span data-ttu-id="ca93e-158">*Versão 2005 (Build 12827,20210)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-158">*Version 2005 (Build 12827.20210)*</span></span>

<span data-ttu-id="ca93e-159"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-159">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-160">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-161">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-161">Excel</span></span>

- <span data-ttu-id="ca93e-162">**Obter dados de organização do Power bi usando os tipos de dados do Excel:** Você pode inserir dados da sua organização usando tipos de dados do Excel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="ca93e-163">Converta uma célula na sua pasta de trabalho e obtenha informações adicionais e atualize os dados sempre que precisar!</span><span class="sxs-lookup"><span data-stu-id="ca93e-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-166">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-167">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-167">Excel</span></span>

- <span data-ttu-id="ca93e-168">Correção de um problema em que o Excel pode parar de responder após usar Ctrl + Shift + teclas de direção para rolar quando a janela do Excel é compartilhada por meio do teams.</span><span class="sxs-lookup"><span data-stu-id="ca93e-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="ca93e-169">Em alguns casos, clicar em um hiperlink para um local dentro da mesma pasta de trabalho fará com que a pasta de trabalho fique oculta.</span><span class="sxs-lookup"><span data-stu-id="ca93e-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="ca93e-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-170">Outlook</span></span>

- <span data-ttu-id="ca93e-171">Foi corrigido um problema com o evento CLP de auditoria para o rótulo de resposta/encaminhamento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="ca93e-172">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma notificação de administrador.</span><span class="sxs-lookup"><span data-stu-id="ca93e-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-14"></a><span data-ttu-id="ca93e-174">Versão 2005:14 de maio</span><span class="sxs-lookup"><span data-stu-id="ca93e-174">Version 2005: May 14</span></span>
<span data-ttu-id="ca93e-175">*Versão 2005 (Build 12827,20160)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-175">*Version 2005 (Build 12827.20160)*</span></span>

<span data-ttu-id="ca93e-176"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-176">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-177">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-178">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-178">Excel</span></span>

- <span data-ttu-id="ca93e-179">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-180">PowerPoint</span></span>

- <span data-ttu-id="ca93e-181">**Não é preciso dar um clique: seus earbuds fazem isso por você** Use seu Surface Earbuds para controlar suas apresentações de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ca93e-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="ca93e-182">Importante: Você deve parear seu Surface Earbuds com o aplicativo Surface Audio para Windows 10 para usar gestos para controlar as apresentações.</span><span class="sxs-lookup"><span data-stu-id="ca93e-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="ca93e-183">As instruções sobre como começar a usar o aplicativo de áudio Surface no Windows 10 estão disponíveis aqui.</span><span class="sxs-lookup"><span data-stu-id="ca93e-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="ca93e-184">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="ca93e-185">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-186">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-186">Word</span></span>

- <span data-ttu-id="ca93e-187">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-190">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="ca93e-191">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-191">Excel</span></span>

- <span data-ttu-id="ca93e-192">Foi aumentado o tamanho dos controles de edição de referência de célula na caixa de diálogo Barras de Erros Personalizadas usada com gráficos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="ca93e-193">Corrigimos um problema em que a tabela de dados do gráfico poderia processar incorretamente valores em um eixo de datas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="ca93e-194">Corrigimos um problema em que as quebras de página poderiam não ser desabilitadas após entrar no Layout da Página ou na Visualização da Quebra de Página.</span><span class="sxs-lookup"><span data-stu-id="ca93e-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="ca93e-195">Corrigimos um problema em que os estilos de linha do gráfico poderiam ser perdidos após ocultar e reexibir colunas com dados de série.</span><span class="sxs-lookup"><span data-stu-id="ca93e-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="ca93e-196">Correção de um problema em que a inserção de uma coluna em uma lista filtrada levaria mais tempo do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="ca93e-197">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="ca93e-198">Correção de um problema em que o link externo para de funcionar depois que o arquivo for reaberto se o caminho do arquivo for muito longo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="ca93e-199">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ca93e-200">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="ca93e-201">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ca93e-202">Essa alteração corrige um problema em que as informações de formatação condicional (CF) não estavam sendo salvas nos arquivos XLSB corretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="ca93e-203">Essa alteração corrige um problema em que o valor do R-quadrado da linha de tendência do gráfico (no caso de interceptação em y forçado) estava incorreto, mesmo que a função PROJ.LIN retorne o valor correto.</span><span class="sxs-lookup"><span data-stu-id="ca93e-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="ca93e-204">Essa alteração corrige um problema em que a formatação personalizada da linha de tendência do gráfico nem sempre estava sendo salva.</span><span class="sxs-lookup"><span data-stu-id="ca93e-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="ca93e-205">Uma falha pode ocorrer ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "pasta de trabalho compartilhada" herdado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="ca93e-206">Corrigimos um problema em que a formatação personalizada em gráficos dinâmicos pode não ser salva quando a opção "inverter se negativo" estiver habilitada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="ca93e-207">Corrigimos um problema em que a formatação personalizada de um único ponto de dados em um Gráfico dinâmico não era salva se a opção "inverter se negativo" tivesse sido selecionada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="ca93e-208">Essa alteração corrige um problema em que o caractere ' @ ' carregado em um arquivo CSV resultaria na conversão da cadeia de caracteres após o caractere ' @ ' em uma fórmula.</span><span class="sxs-lookup"><span data-stu-id="ca93e-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="ca93e-209">Corrigimos um problema em que os valores decimais na função SEQUÊNCIA não eram arredondados corretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="ca93e-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="ca93e-210">OneNote</span></span>

- <span data-ttu-id="ca93e-211">Foi corrigido um problema em que as quebras de linha estavam sendo armazenadas como guias verticais.</span><span class="sxs-lookup"><span data-stu-id="ca93e-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-212">Outlook</span></span>

- <span data-ttu-id="ca93e-213">Resolve um problema que fazia com que os usuários não pudessem adicionar um Grupo de Contatos Pessoais como participante da reunião.</span><span class="sxs-lookup"><span data-stu-id="ca93e-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="ca93e-214">Correção de um problema em que o botão categorizar para calendários de grupo na faixa de opções do Office foi desabilitado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="ca93e-215">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="ca93e-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="ca93e-216">Corrigimos um problema em que os clientes corporativos com pastas de grupo não implementadas ou que não funcionavam resultaria na exibição da mensagem “não respondendo” no Outlook.</span><span class="sxs-lookup"><span data-stu-id="ca93e-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="ca93e-217">Solucionamos um problema que causaria um safelinks muito longo que os usuários clicaram no cliente da área de trabalho do Outlook para falha ao carregar devido ao truncamento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="ca93e-218">Corrigimos um problema em que as pastas do Outlook com nomes que continham caracteres DBCS (conjunto de caracteres de dois bytes) poderiam desaparecer de forma intermitente ao sincronizar com o servidor.</span><span class="sxs-lookup"><span data-stu-id="ca93e-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="ca93e-219">Para que isso aconteça, o Outlook tinha que ser configurado com uma conta IMAP e estar sendo executado em um sistema com a localidade definida como japonês.</span><span class="sxs-lookup"><span data-stu-id="ca93e-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="ca93e-220">Foi corrigido um problema que provocou as regras de exclusão criadas para caixas de correio diferentes da caixa de correio principal do usuário para se tornarem inválidas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="ca93e-221">Solucionamos um problema que fazia com que os anexos sejam descartados ao encaminhar uma mensagem criptografada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="ca93e-222">Solucionamos um problema que causaria reuniões com mais de dois meses de falha para exibir um assunto de reunião no assistente de agendamento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="ca93e-223">Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="ca93e-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="ca93e-224">Foi adicionada a capacidade de impor a configuração de assinatura padrão S/MIME pela política de grupo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-225">PowerPoint</span></span>

- <span data-ttu-id="ca93e-226">Corrigimos um problema em que, se um usuário criasse um comentário sem postá-lo, fechasse o painel Comentários, abrisse uma nova janela, navegasse por vários slides, fechasse a janela e, por fim, reabrisse o painel Comentários na apresentação original, os comentários de rascunho não estariam disponíveis.</span><span class="sxs-lookup"><span data-stu-id="ca93e-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="ca93e-227">Corrigimos um problema em que passar o mouse sobre o símbolo de asterisco (\*) não exibia o nome de usuário e a data da última pessoa a atualizar o documento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="ca93e-228">Project</span><span class="sxs-lookup"><span data-stu-id="ca93e-228">Project</span></span>

- <span data-ttu-id="ca93e-229">Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="ca93e-230">Corrigimos um problema em que o Project podia falhar ao alterar o campo de status do quadro em um projeto conectado a uma lista de tarefas do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="ca93e-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="ca93e-231">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="ca93e-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="ca93e-232">Correção de um problema em que, se o projeto estiver conectado ao Project Web App e o separador decimal for uma vírgula, o método TaskDependencies Add falhará quando o retardo for adicionado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="ca93e-233">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-233">Word</span></span>

- <span data-ttu-id="ca93e-234">Corrigimos um problema em que a inserção de comentários em um documento no modo de colaboração nem sempre funcionava.</span><span class="sxs-lookup"><span data-stu-id="ca93e-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="ca93e-235">Essa alteração corrige um problema em que o cartão Pessoas piscava se o @ da menção estivesse selecionado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="ca93e-236">Habilitar a opção "Mostrar indicadores" não exibia os indicadores.</span><span class="sxs-lookup"><span data-stu-id="ca93e-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="ca93e-237">Isso foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-237">This has been fixed.</span></span>

- <span data-ttu-id="ca93e-238">Corrigimos um problema em que o fechamento de um documento com comentários de rascunho perguntaria para o usuário se eles gostaria de fechar o documento sem salvar os comentários.</span><span class="sxs-lookup"><span data-stu-id="ca93e-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="ca93e-239">Cancelar a solicitação fechava o documento, em vez de deixá-lo aberto.</span><span class="sxs-lookup"><span data-stu-id="ca93e-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="ca93e-240">Corrigimos um problema na cópia e na colagem de cabeçalhos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="ca93e-241">Correção de um problema em que a conversão de um comentário Postado resultaria no erro "falha ao inserir texto traduzido".</span><span class="sxs-lookup"><span data-stu-id="ca93e-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="ca93e-242">Essa alteração corrige um problema em que o texto com hiperlinks pode não ser exibido se a opção: "mostrar códigos de campo em vez de seus valores" estiver habilitada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="ca93e-243">No leitor Exibição da Web/Imersivo, clicar em uma dica rolaria a tela para cima, mesmo que ele já estivesse em exibição.</span><span class="sxs-lookup"><span data-stu-id="ca93e-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="ca93e-244">Isso foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-244">This has been fixed.</span></span>

- <span data-ttu-id="ca93e-245">Corrigimos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, o arquivo poderia ser salvo com a extensão. docx e com o nome de arquivo WRO0004.docx, independentemente de qual nome o usuário inseriu, tornando o documento inutilizável.</span><span class="sxs-lookup"><span data-stu-id="ca93e-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ca93e-246">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-246">Office Suite</span></span>

- <span data-ttu-id="ca93e-247">Quando um usuário recebe uma política que as transfere apenas para o Microsoft Teams, ainda era possível usar o suplemento do Outlook para o Skype for Business para agendar reuniões.</span><span class="sxs-lookup"><span data-stu-id="ca93e-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="ca93e-248">Após esta atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente lê a política que indica que o usuário é apenas o Microsoft Teams e insere o modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="ca93e-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="ca93e-249">Além disso, o suplemento do Outlook para o Skype for Business não se ativará enquanto é iniciado se ele estiver no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="ca93e-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="ca93e-250">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="ca93e-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="ca93e-251">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-11"></a><span data-ttu-id="ca93e-253">Versão 2004: 11 de maio</span><span class="sxs-lookup"><span data-stu-id="ca93e-253">Version 2004: May 11</span></span>
<span data-ttu-id="ca93e-254">*Versão 2004 (Criação 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ca93e-256">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-257">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-257">Excel</span></span>

- <span data-ttu-id="ca93e-258">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-259">Outlook</span></span>

- <span data-ttu-id="ca93e-260">**Links aprimorados no email:** quando você incluir um link a um arquivo, o nome do arquivo substituirá a URL.</span><span class="sxs-lookup"><span data-stu-id="ca93e-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="ca93e-261">Você pode alterar as permissões para que todos os destinatários tenham acesso.</span><span class="sxs-lookup"><span data-stu-id="ca93e-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="ca93e-262">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="ca93e-263">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="ca93e-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="ca93e-264">**Conte suas histórias com GIFs animados:** Os GIFs animados já possuem suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-265">PowerPoint</span></span>

- <span data-ttu-id="ca93e-266">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="ca93e-267">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="ca93e-268">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-268">Word</span></span>

- <span data-ttu-id="ca93e-269">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-272">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-273">Outlook</span></span>

- <span data-ttu-id="ca93e-274">Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir notificações do sistema.</span><span class="sxs-lookup"><span data-stu-id="ca93e-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-04"></a><span data-ttu-id="ca93e-276">Versão 2004: 04 de maio</span><span class="sxs-lookup"><span data-stu-id="ca93e-276">Version 2004: May 04</span></span>
<span data-ttu-id="ca93e-277">*Versão 2004 (Build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-277">*Version 2004 (Build 12730.20250)*</span></span>

<span data-ttu-id="ca93e-278"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-278">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-279">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-280">Outlook</span></span>

- <span data-ttu-id="ca93e-281">**Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca.</span><span class="sxs-lookup"><span data-stu-id="ca93e-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="ca93e-282">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="ca93e-283">**Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="ca93e-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-286">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ca93e-287">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-287">Office Suite</span></span>

- <span data-ttu-id="ca93e-288">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2004-april-29"></a><span data-ttu-id="ca93e-290">Versão 2004: 29 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-290">Version 2004: April 29</span></span>
<span data-ttu-id="ca93e-291">*Versão 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-291">*Version 2004 (Build 12730.20236)*</span></span>

<span data-ttu-id="ca93e-292"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-292">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-293">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-294">Outlook</span></span>

- <span data-ttu-id="ca93e-295">**Ajude a proteger os dados de seu grupo:** o rótulo de Confidencialidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe.</span><span class="sxs-lookup"><span data-stu-id="ca93e-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-298">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-299">Outlook</span></span>

- <span data-ttu-id="ca93e-300">Aborda um problema que causa falha no Outlook em algumas versões do Windows.</span><span class="sxs-lookup"><span data-stu-id="ca93e-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-april-25"></a><span data-ttu-id="ca93e-302">Versão 2004: 25 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-302">Version 2004: April 25</span></span>
<span data-ttu-id="ca93e-303">*Versão 2004 (Build 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-305">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-306">Outlook</span></span>

- <span data-ttu-id="ca93e-307">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="ca93e-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="ca93e-308">Project</span><span class="sxs-lookup"><span data-stu-id="ca93e-308">Project</span></span>

- <span data-ttu-id="ca93e-309">Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.</span><span class="sxs-lookup"><span data-stu-id="ca93e-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ca93e-310">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-310">Office Suite</span></span>

- <span data-ttu-id="ca93e-311">Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2004-april-21"></a><span data-ttu-id="ca93e-313">Versão 2004: 21 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-313">Version 2004: April 21</span></span>
<span data-ttu-id="ca93e-314">*Versão 2004 (Build 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-316">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-317">Outlook</span></span>

- <span data-ttu-id="ca93e-318">Corrige um problema que fazia com que a largura do painel de pastas fosse alterada inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="ca93e-319">Corrige um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.</span><span class="sxs-lookup"><span data-stu-id="ca93e-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-april-15"></a><span data-ttu-id="ca93e-321">Versão 2004: 15 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-321">Version 2004: April 15</span></span>
<span data-ttu-id="ca93e-322">*Versão 2004 (Build 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-322">*Version 2004 (Build 12730.20150)*</span></span>

<span data-ttu-id="ca93e-323"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-323">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-324">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-325">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-325">Excel</span></span>

- <span data-ttu-id="ca93e-326">**O suporte ao conector do Facebook terminou:** a partir de abril de 2020, o Excel não dará mais suporte a conexões de dados externos que usam o conector do Facebook.</span><span class="sxs-lookup"><span data-stu-id="ca93e-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-327">Outlook</span></span>

- <span data-ttu-id="ca93e-328">**Nova opção para desabilitar sugestões de @menções ao redigir emails no Outlook:** você considera o seletor @mencionar mais irritante que útil?</span><span class="sxs-lookup"><span data-stu-id="ca93e-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="ca93e-329">Agora você pode desativá-lo, se preferir.</span><span class="sxs-lookup"><span data-stu-id="ca93e-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-330">PowerPoint</span></span>

- <span data-ttu-id="ca93e-331">**Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="ca93e-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-332">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-332">Word</span></span>

- <span data-ttu-id="ca93e-333">**Faça anotações na sua cópia particular:** crie anotações redigidas à mão para você mesmo, fazendo uma cópia privada de um documento compartilhado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="ca93e-334">Vá para Exibir > Criar uma cópia privada para começar.</span><span class="sxs-lookup"><span data-stu-id="ca93e-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-337">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ca93e-338">Access</span><span class="sxs-lookup"><span data-stu-id="ca93e-338">Access</span></span>

- <span data-ttu-id="ca93e-339">Foram corrigidos problemas com o redimensionamento e a atualização de tabelas no painel de tarefas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="ca93e-340">Correção de um problema em que as versões internacionais do Access exibiam as cadeias de caracteres em inglês na interface do usuário.</span><span class="sxs-lookup"><span data-stu-id="ca93e-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="ca93e-341">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-341">Excel</span></span>

- <span data-ttu-id="ca93e-342">Foi corrigido um problema em que a seleção de um intervalo de células em uma planilha resultava na seleção de uma única célula.</span><span class="sxs-lookup"><span data-stu-id="ca93e-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="ca93e-343">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ca93e-344">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="ca93e-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="ca93e-345">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="ca93e-346">Corrigido um problema de desempenho que os usuários podem ter experimentado ao editar por programação um intervalo grande de células.</span><span class="sxs-lookup"><span data-stu-id="ca93e-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="ca93e-347">Corrigido um problema de desempenho que acontecia ao abrir arquivos csv em ambientes japoneses.</span><span class="sxs-lookup"><span data-stu-id="ca93e-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="ca93e-348">Foi corrigido um problema em que a inserção de um modelo de gráfico definido pelo usuário poderia resultar no salvamento dele como um gráfico de colunas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="ca93e-349">Foi corrigido um problema em que os rótulos de Dados de gráficos eram exibidos como em branco quando as células de dados subjacentes não possuíam uma legenda.</span><span class="sxs-lookup"><span data-stu-id="ca93e-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="ca93e-350">Foi corrigido um problema que podia fazer o Excel parar de responder quando se reduzia o tamanho de um gráfico com alguns intervalos de eixo x.</span><span class="sxs-lookup"><span data-stu-id="ca93e-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="ca93e-351">Foi corrigido um problema em que, em uma planilha do Excel com referência de célula L1C1 habilitada que estivesse sendo criada em coautoria/compartilhada, passar o mouse sobre o ícone de presença do usuário não exibia a referência de célula ativa no modo L1C1.</span><span class="sxs-lookup"><span data-stu-id="ca93e-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="ca93e-352">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-353">Outlook</span></span>

- <span data-ttu-id="ca93e-354">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="ca93e-355">Essa alteração corrige um problema em que as últimas alterações em rascunhos de emails não foram atualizadas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="ca93e-356">Correção de um problema em que clicar com o botão direito do mouse em um arquivo e usar ' enviar para ' não funcionará.</span><span class="sxs-lookup"><span data-stu-id="ca93e-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="ca93e-357">Foi resolvido um problema que fazia os delegados verem diferentes hierarquias de pastas em computadores diferentes para caixas de correio compartilhadas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="ca93e-358">Foi resolvido um problema que fazia com que as categorias desaparecessem ocasionalmente de mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="ca93e-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="ca93e-359">Foi solucionado um problema que fazia com que alguns lembretes não fossem exibidos ao alterar o fuso horário em um computador.</span><span class="sxs-lookup"><span data-stu-id="ca93e-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="ca93e-360">Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao tentar exibir as propriedades de um formulário organizacional.</span><span class="sxs-lookup"><span data-stu-id="ca93e-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="ca93e-361">Correção de um problema em que o usuário tinha um caminho de pesquisa personalizado para o catálogo de endereços, o escopo de resolução de nome do Outlook seria limitado ao caminho personalizado, em vez de incluir a lista de endereços global (GAL).</span><span class="sxs-lookup"><span data-stu-id="ca93e-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="ca93e-362">Foi solucionado um problema que fazia com que o botão "Salvar na nuvem" não tivesse as Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="ca93e-363">Foi solucionado um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não tivesse permissão de proprietário na mensagem que estivesse sendo respondida.</span><span class="sxs-lookup"><span data-stu-id="ca93e-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="ca93e-364">Foi solucionado um problema que fazia com que os usuários não consiguissem adicionar outros anexos de um local da Web a uma reunião criada anteriormente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="ca93e-365">Foi solucionado um problema que fazia com que a data da "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um email ou salvar um anexo de um email arrastando e soltando (em vez de por meio de um menu).</span><span class="sxs-lookup"><span data-stu-id="ca93e-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="ca93e-366">Foi solucionado um problema que fazia com que pressionar Enter no painel de localização expandido falhasse em iniciar uma pesquisa, exigindo que os usuários clicassem no botão de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="ca93e-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="ca93e-367">Correção de um problema em que, em um conjunto de resultados de pesquisa retornados, classificar os resultados por categorias, não exibiria as cores da categoria.</span><span class="sxs-lookup"><span data-stu-id="ca93e-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="ca93e-368">Correção de um problema em que a pesquisa não exibe informações sobre os usuários quando a opção "mostrar fotografias de usuário quando disponíveis" está desabilitada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ca93e-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-369">PowerPoint</span></span>

- <span data-ttu-id="ca93e-370">Essa alteração corrige um erro que poderia fazer com que arquivos do PowerPoint com emojis falhassem ao salvar.</span><span class="sxs-lookup"><span data-stu-id="ca93e-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="ca93e-371">Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.</span><span class="sxs-lookup"><span data-stu-id="ca93e-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="ca93e-372">Corrigimos um problema em que copiar texto do Excel para o PowerPoint poderia alterar a formatação.</span><span class="sxs-lookup"><span data-stu-id="ca93e-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="ca93e-373">Essa alteração corrige um problema em que encontrar caracteres especiais usando "localizar somente palavras inteiras" nem sempre funcionava como esperado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="ca93e-374">Project</span><span class="sxs-lookup"><span data-stu-id="ca93e-374">Project</span></span>

- <span data-ttu-id="ca93e-375">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="ca93e-376">Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="ca93e-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ca93e-377">Foi corrigido um problema em que o evento 'ProjectBeforeTaskChange' do Visual Basic Applications (VBA) não era acionado quando um usuário clicava no botão "Inativar" encontrado na Faixa de Opções de Tarefas no agrupamento de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="ca93e-378">Se você definir os detalhes da predecessora ou da sucessora de dentro de um modo de exibição de tipo de formulário, o evento ProjectBeforeTaskChange Visual Basic Applications (VBA) não capturaria as alterações.</span><span class="sxs-lookup"><span data-stu-id="ca93e-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="ca93e-379">Por exemplo, se você excluiu uma dependência e clicou em OK no formulário, o evento não foi acionado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="ca93e-380">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="ca93e-381">Correção de um problema em que os valores mais recentes para o custo real do trabalho realizado (CRTR) não seriam exibidos depois de fazer uma alteração, como uma alteração de data.</span><span class="sxs-lookup"><span data-stu-id="ca93e-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="ca93e-382">Correção de um problema em que abrir um projeto usando o menu mais recentemente utilizado (MRU) abriu o arquivo do projeto com acesso de leitura/gravação.</span><span class="sxs-lookup"><span data-stu-id="ca93e-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="ca93e-383">Essa alteração corrige um problema em que, se você criou uma tarefa manual com uma data de início e uma hora (mas não duração), ela seria exibida com um horário incorreto na linha do tempo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="ca93e-384">Foi corrigido um problema em que imprimir uma linha do tempo usando um calendário islâmico resultava em um mês sendo ignorado ou duplicado no modo de exibição de impressão.</span><span class="sxs-lookup"><span data-stu-id="ca93e-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="ca93e-385">Essa alteração resolve um problema em que trabalhar no planejador de equipe com objetos GDI pode resultar na alocação total de objetos GDI e criar condições de pouca memória.</span><span class="sxs-lookup"><span data-stu-id="ca93e-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="ca93e-386">Foi corrigido um problema em que, se CustomFieldValueListGetItem fosse executado e uma tabela de pesquisa para o campo personalizado não existisse, uma tabela de pesquisa vazia era criada, mesmo que não devesse ser.</span><span class="sxs-lookup"><span data-stu-id="ca93e-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="ca93e-387">Quando os dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado</span><span class="sxs-lookup"><span data-stu-id="ca93e-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="ca93e-388">Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-389">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-389">Word</span></span>

- <span data-ttu-id="ca93e-390">Essa alteração corrige um problema em que passar o cursor do mouse sobre uma dica não realçava o seu cartão.</span><span class="sxs-lookup"><span data-stu-id="ca93e-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="ca93e-391">Essa alteração corrige um problema em várias páginas selecionadas no menu Exibir, onde o painel de comentários poderia ser exibido em branco.</span><span class="sxs-lookup"><span data-stu-id="ca93e-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="ca93e-392">Correção de um problema em que a funcionalidade para postar comentários foi desabilitada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="ca93e-393">Essa alteração corrige um problema que fazia com que o texto em formas agrupadas desaparecesse temporariamente ao usar a ferramenta Seleção de Laço.</span><span class="sxs-lookup"><span data-stu-id="ca93e-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="ca93e-394">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="ca93e-395">Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.</span><span class="sxs-lookup"><span data-stu-id="ca93e-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="ca93e-396">Essa alteração resolve um problema em que o gerente de conta não despacha mensagens, resultando em um travamento com aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="ca93e-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="ca93e-397">Essa alteração corrige um problema no modo de exibição de duas páginas em que, ao criar um comentário, a âncora de comentário nem sempre chegava a ser exibida.</span><span class="sxs-lookup"><span data-stu-id="ca93e-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="ca93e-398">Corrigido um problema ao digitar ou editar um comentário e usar Ctrl + A resultaria na seleção de texto na tela, em vez de selecionar o texto apenas dentro do cartão de comentário.</span><span class="sxs-lookup"><span data-stu-id="ca93e-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="ca93e-399">Corrigido um problema em que, para um parágrafo cujo estilo é um ancestral de um estilo vinculado a uma lista, a numeração dessa lista poderia ser perdida.</span><span class="sxs-lookup"><span data-stu-id="ca93e-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="ca93e-400">Essa alteração corrige um problema em que o Sumário seria atualizado com estilos de título que não estão presentes no documento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="ca93e-401">Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.</span><span class="sxs-lookup"><span data-stu-id="ca93e-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="ca93e-402">Corrigimos um problema ao mesclar 2 documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="ca93e-403">Correção de um problema em que as assinaturas digitais salvas em documentos do Word seriam removidas durante a mala direta dos documentos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="ca93e-404">Correção de um problema em que a marcação de revisões envolvendo equações podem resultar em uma falha ao salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-april-14"></a><span data-ttu-id="ca93e-406">Versão 2003: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-406">Version 2003: April 14</span></span>
<span data-ttu-id="ca93e-407">*Versão 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="ca93e-408">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ca93e-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

- <span data-ttu-id="ca93e-410">Várias correções de bugs e desempenho.</span><span class="sxs-lookup"><span data-stu-id="ca93e-410">Various bugs and performance fixes.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

## <a name="version-2003-april-09"></a><span data-ttu-id="ca93e-412">Versão 2003: 09 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-412">Version 2003: April 09</span></span>
<span data-ttu-id="ca93e-413">*Versão 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-413">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="ca93e-414"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-414">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-415">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-416">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-416">Excel</span></span>

- <span data-ttu-id="ca93e-417">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="ca93e-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ca93e-418">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ca93e-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-419">Outlook</span></span>

- <span data-ttu-id="ca93e-420">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="ca93e-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ca93e-421">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ca93e-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-422">PowerPoint</span></span>

- <span data-ttu-id="ca93e-423">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="ca93e-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ca93e-424">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ca93e-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-425">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-425">Word</span></span>

- <span data-ttu-id="ca93e-426">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="ca93e-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ca93e-427">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ca93e-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)




[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-april-03"></a><span data-ttu-id="ca93e-431">Versão 2003: 03 de abril</span><span class="sxs-lookup"><span data-stu-id="ca93e-431">Version 2003: April 03</span></span>
<span data-ttu-id="ca93e-432">*Versão 2003 (Criação 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (NÃO REMOVA O INÍCIO DO CONTEÚDO DO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-434">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-435">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-435">Excel</span></span>

- <span data-ttu-id="ca93e-436">Em alguns casos, o uso do Application.Evaluate do VBA não funcionava para funções definidas pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="ca93e-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-437">Outlook</span></span>

- <span data-ttu-id="ca93e-438">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="ca93e-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="ca93e-439">Projeto</span><span class="sxs-lookup"><span data-stu-id="ca93e-439">Project</span></span>

- <span data-ttu-id="ca93e-440">Quando os dados do Predecessor/Sucessor são editados em uma exibição de Formulário, um evento adicional do ProjectBeforeTaskChange é acionado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-441">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-441">Word</span></span>

- <span data-ttu-id="ca93e-442">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="ca93e-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DO BUGDETAILS)

## <a name="version-2003-march-31"></a><span data-ttu-id="ca93e-444">Versão 2003: 31 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-444">Version 2003: March 31</span></span>
<span data-ttu-id="ca93e-445">*Versão 2003 (Build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ca93e-447">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ca93e-448">Access</span><span class="sxs-lookup"><span data-stu-id="ca93e-448">Access</span></span>

- <span data-ttu-id="ca93e-449">\*\*Painel de Tarefas "Adicionar Tabelas": \*\* O novo Painel de Tarefas "Adicionar Tabelas" do Access finalmente chegou!</span><span class="sxs-lookup"><span data-stu-id="ca93e-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="ca93e-450">Esse recurso permite que você selecione/multi-selecione com facilidade quais tabelas gostaria de adicionar/remover à uma janela de consulta, sem navegar para a caixa de diálogo "Mostrar Tabelas" para consultas e para o modo de exibição de relação.</span><span class="sxs-lookup"><span data-stu-id="ca93e-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="ca93e-451">Isso também inclui uma nova guia "links" para exibir tabelas vinculadas, uma caixa de pesquisa para filtrar a lista atual, comportamento "arrastar e soltar" e muito mais!</span><span class="sxs-lookup"><span data-stu-id="ca93e-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-454">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="ca93e-455">Project</span><span class="sxs-lookup"><span data-stu-id="ca93e-455">Project</span></span>

- <div><span data-ttu-id="ca93e-456"><span style="display:inline !important;">Correção de um problema em que o usuário não conseguiu entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span></span><span class="sxs-lookup"><span data-stu-id="ca93e-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-25"></a><span data-ttu-id="ca93e-458">Versão 2003: 25 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-458">Version 2003: March 25</span></span>
<span data-ttu-id="ca93e-459">*Versão 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="ca93e-460">Várias correções de bugs e de desempenho.</span><span class="sxs-lookup"><span data-stu-id="ca93e-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="ca93e-461">Versão 2003: 23 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-461">Version 2003: March 23</span></span>
<span data-ttu-id="ca93e-462">*Versão 2003 (Build 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="ca93e-463">Várias correções de bugs e de desempenho.</span><span class="sxs-lookup"><span data-stu-id="ca93e-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="ca93e-464">Versão 2003: 21 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-464">Version 2003: March 21</span></span>
<span data-ttu-id="ca93e-465">*Versão 2003 (Build 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-465">*Version 2003 (Build 12624.20276)*</span></span>

<span data-ttu-id="ca93e-466"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-466">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-467">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-468">Outlook</span></span>

- <span data-ttu-id="ca93e-469">**Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online.</span><span class="sxs-lookup"><span data-stu-id="ca93e-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="ca93e-470">Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.</span><span class="sxs-lookup"><span data-stu-id="ca93e-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="ca93e-471">**Atualização visual de calendário:** ano passado, trouxemos uma experiência de email atualizada e, este ano, é a vez do calendário ser transformado!</span><span class="sxs-lookup"><span data-stu-id="ca93e-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="ca93e-472">As atualizações são novas, mas usuais e, como um usuário experiente do Outlook, você pode entrar e ser mais produtivo imediatamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-473">PowerPoint</span></span>

- <span data-ttu-id="ca93e-474">**Atualizar slides durante a apresentação de slides:** os slides de atualização alterados por outros autores durante a sua apresentação.</span><span class="sxs-lookup"><span data-stu-id="ca93e-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

## <a name="version-2003-march-16"></a><span data-ttu-id="ca93e-476">Versão 2003: 16 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-476">Version 2003: March 16</span></span>
<span data-ttu-id="ca93e-477">*Versão 2003 (Build 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-477">*Version 2003 (Build 12624.20224)*</span></span>


<span data-ttu-id="ca93e-478"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-478">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-479">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-480">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-480">Excel</span></span>

- <span data-ttu-id="ca93e-481">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="ca93e-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-482">Outlook</span></span>

- <span data-ttu-id="ca93e-483">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="ca93e-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-484">PowerPoint</span></span>

- <span data-ttu-id="ca93e-485">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="ca93e-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-486">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-486">Word</span></span>

- <span data-ttu-id="ca93e-487">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="ca93e-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ca93e-488">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-488">Office Suite</span></span>

- <span data-ttu-id="ca93e-489">**Painéis com Guias:** Agora, você pode alterar entre vários painéis usando uma interface de usuário de guia à direita do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="ca93e-490">A interface de usuário ficará visível apenas quando você tiver dois painéis ou mais abertos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-493">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-494">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-494">Excel</span></span>

- <span data-ttu-id="ca93e-495">Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-496">Outlook</span></span>

- <span data-ttu-id="ca93e-497">Solucionamos um problema que fazia com que os usuários vissem o processo do Outlook persistir no gerenciador de tarefas após sair.</span><span class="sxs-lookup"><span data-stu-id="ca93e-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-10"></a><span data-ttu-id="ca93e-499">Versão 2003: 10 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-499">Version 2003: March 10</span></span>
<span data-ttu-id="ca93e-500">*Versão 2003 (Build 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="ca93e-501">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ca93e-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)
### <a name="feature-updates"></a><span data-ttu-id="ca93e-503">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-504">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-504">Excel</span></span>
- <span data-ttu-id="ca93e-505">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ca93e-506">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="ca93e-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-507">PowerPoint</span></span>
- <span data-ttu-id="ca93e-508">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ca93e-509">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="ca93e-510">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-510">Word</span></span>
- <span data-ttu-id="ca93e-511">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ca93e-512">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="ca93e-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-513">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-514">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-514">Excel</span></span>

- <span data-ttu-id="ca93e-515">Correção de um problema superficial em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não foi afetada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ca93e-516">Corrigido um problema que os usuários podem ter ao renomear medidas de tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="ca93e-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="ca93e-517">Correção de um problema em que o texto em uma segmentação de dados não é dimensionado corretamente na visualização de impressão.</span><span class="sxs-lookup"><span data-stu-id="ca93e-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="ca93e-518">Corrigido um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="ca93e-519">Corrigido um problema que fazia a interface do usuário piscar quando os usuários executavam uma macro que interagia com a faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="ca93e-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="ca93e-520">Corrigido um problema em que os arquivos CSV eram carregados incorretamente quando a primeira palavra no arquivo era TABLE.</span><span class="sxs-lookup"><span data-stu-id="ca93e-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="ca93e-521">Corrigido um problema em que os usuários podem ter sofrido falhas ao alternar entre duas pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="ca93e-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="ca93e-522">Correção de um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.</span><span class="sxs-lookup"><span data-stu-id="ca93e-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="ca93e-523">Essa alteração corrige um erro em tempo de execução no modelo de objeto e a possível falha do aplicativo (Excel, Word) quando os suplementos pedem itens de host em documentos ou planilhas que contêm formas com bloqueios não selecionados.</span><span class="sxs-lookup"><span data-stu-id="ca93e-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="ca93e-524">Aborda um problema que causou a falha dos usuários do Outlook durante a sincronização das configurações.</span><span class="sxs-lookup"><span data-stu-id="ca93e-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="ca93e-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-525">Outlook</span></span>

- <span data-ttu-id="ca93e-526">Foi corrigido um problema em que a criação de uma regra com o Outlook Web Access não persistia no servidor Exchange e resultava em um conflito.</span><span class="sxs-lookup"><span data-stu-id="ca93e-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="ca93e-527">Aborda um problema que causou a falha dos usuários do Outlook durante a sincronização das configurações.</span><span class="sxs-lookup"><span data-stu-id="ca93e-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="ca93e-528">Correção de um problema em que o Outlook no modo escuro não exibia a lista suspensa do campo 'De:'.</span><span class="sxs-lookup"><span data-stu-id="ca93e-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="ca93e-529">Aborda um problema que fazia o Outlook gerar de forma inesperada a saída do log em alguns cenários, mesmo quando o log estava desativado.</span><span class="sxs-lookup"><span data-stu-id="ca93e-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="ca93e-530">Corrigido um problema que fazia com que os usuários não conseguissem abrir mensagens de pasta pública quando o Outlook permanecia em execução durante a noite.</span><span class="sxs-lookup"><span data-stu-id="ca93e-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="ca93e-531">Corrigida uma condição de corrida em que os botões 'Permitir' e 'Negar' na página de permissões são desativados durante o fluxo de trabalho de autenticação da adição de uma conta do Gmail.</span><span class="sxs-lookup"><span data-stu-id="ca93e-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="ca93e-532">Solucionamos um problema que fazia com que os usuários perdessem o acesso à caixa de diálogo&quot;opções de disponibilidade&quot; de permissões de calendário.</span><span class="sxs-lookup"><span data-stu-id="ca93e-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="ca93e-533">Correção de um problema que pode resultar no alerta: &quot;Infelizmente, estamos com problemas para abrir este item&quot; ao abrir algumas instâncias de reunião recorrente enviadas de um fuso horário diferente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="ca93e-534">Solucionamos um problema que pode fazer com que os usuários não consigam reabrir um arquivo. msg depois de arrastar e soltar um anexo da mensagem.</span><span class="sxs-lookup"><span data-stu-id="ca93e-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="ca93e-535">Correção de um problema em que, após carregar um anexo de arquivo do Outlook para o OneDrive, poderia resultar no nome do arquivo sendo alterado se o nome do anexo contivesse parênteses.</span><span class="sxs-lookup"><span data-stu-id="ca93e-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="ca93e-536">Solucionamos um problema que fazia com que os usuários não conseguissem anexar um arquivo à mensagem de email por meio do explorador de arquivos se esse arquivo estivesse aberto em outro aplicativo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="ca93e-537">Aborda um problema que causou a falha dos usuários do Outlook durante a sincronização das configurações.</span><span class="sxs-lookup"><span data-stu-id="ca93e-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ca93e-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-538">PowerPoint</span></span>

- <span data-ttu-id="ca93e-539">Foi corrigido um problema em que as miniaturas recomendadas acendiam e apagavam ao passar o mouse sobre elas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="ca93e-540">Em alguns casos, isso pode causar uma falha no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ca93e-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="ca93e-541">Correção de um problema superficial em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não foi afetada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ca93e-542">Correção de um problema que pode resultar em uma falha no salvamento de um documento no PowerPoint ou no Word com um gráfico do Excel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="ca93e-543">Projeto</span><span class="sxs-lookup"><span data-stu-id="ca93e-543">Project</span></span>

- <span data-ttu-id="ca93e-544">Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.</span><span class="sxs-lookup"><span data-stu-id="ca93e-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="ca93e-545">Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="ca93e-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ca93e-546">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="ca93e-547">Visio</span><span class="sxs-lookup"><span data-stu-id="ca93e-547">Visio</span></span>

- <span data-ttu-id="ca93e-548">O painel de informações de forma estava mostrando detalhes inconsistentes na seção dados da forma, com relação ao arquivo quando aberto na área de trabalho do Visio.</span><span class="sxs-lookup"><span data-stu-id="ca93e-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="ca93e-549">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-549">It has now been fixed.</span></span>

- <span data-ttu-id="ca93e-550">Bitmaps importados em versões anteriores a 2016 não estavam sendo renderizados devido a algumas verificações de segurança.</span><span class="sxs-lookup"><span data-stu-id="ca93e-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="ca93e-551">Corrigimos esse problema na assinatura do Visio.</span><span class="sxs-lookup"><span data-stu-id="ca93e-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-552">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-552">Word</span></span>

- <span data-ttu-id="ca93e-553">Corrigido um problema em que os cartões de comentários nem sempre são destacados quando um ponteiro do mouse passa sobre o cartão de comentários.</span><span class="sxs-lookup"><span data-stu-id="ca93e-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="ca93e-554">Correção de um problema que, ao usar o cartão de comentários, o foco na caixa de edição de comentários não ficava visível.</span><span class="sxs-lookup"><span data-stu-id="ca93e-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="ca93e-555">Correção de um problema superficial em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não foi afetada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ca93e-556">Durante uma sessão ativa de coautoria de documentos, adicionar uma imagem diretamente a um cartão de comentários pode resultar na adição de uma marca.</span><span class="sxs-lookup"><span data-stu-id="ca93e-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="ca93e-557">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-557">This issue has been fixed.</span></span>

- <span data-ttu-id="ca93e-558">Inserir um controle (como um Controle de Conteúdo de Texto) em uma equação e salvar e abrir o arquivo resulta em um erro de conteúdo não legível.</span><span class="sxs-lookup"><span data-stu-id="ca93e-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="ca93e-559">Corrigido um problema em que o salvamento de um arquivo anteriormente protegido por senha em um armazenamento em nuvem não funcionava.</span><span class="sxs-lookup"><span data-stu-id="ca93e-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="ca93e-560">Correção de um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="ca93e-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="ca93e-561">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-561">Office Suite</span></span>

- <span data-ttu-id="ca93e-562">Ao usar as propriedades do MultiChoice/Lookup/Managed-metadata com documentos do Word/Excel/PowerPoint e salvá-los em uma biblioteca de documentos do SharePoint, essas propriedades anteriormente eram limitadas a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="ca93e-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="ca93e-563">Quando essas propriedades excederem 255 caracteres, esses documentos não puderam ser salvos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="ca93e-564">Com essa mudança, esse limite aumentou para 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="ca93e-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="ca93e-565">Foi corrigido um problema com o Word/Excel/PowerPoint, em que o nome de usuário principal (UPN) não diferenciava maiúsculas de minúsculas, resultando em menos falhas ao trabalhar com arquivos no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="ca93e-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="ca93e-566">Correção de um problema em que, quando vários documentos da mesma biblioteca do SharePoint estivessem abertos no Word/Excel/PowerPoint, somente o primeiro documento aberto era verificado quanto à conformidade com Políticas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-05"></a><span data-ttu-id="ca93e-568">Versão 2002: março de 2005</span><span class="sxs-lookup"><span data-stu-id="ca93e-568">Version 2002: March 05</span></span>
<span data-ttu-id="ca93e-569">*Versão 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="ca93e-570">Várias correções de bugs e de desempenho.</span><span class="sxs-lookup"><span data-stu-id="ca93e-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="ca93e-571">Versão 2002: 04 de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-571">Version 2002: March 04</span></span>
<span data-ttu-id="ca93e-572">*Versão 2002 (Build 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-574">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="ca93e-575">Project</span><span class="sxs-lookup"><span data-stu-id="ca93e-575">Project</span></span>
- <div><span data-ttu-id="ca93e-576">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="ca93e-577">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-577">Office Suite</span></span>
- <div><span data-ttu-id="ca93e-578">Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.</span><span class="sxs-lookup"><span data-stu-id="ca93e-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-march-01"></a><span data-ttu-id="ca93e-580">Versão 2002: 01º de março</span><span class="sxs-lookup"><span data-stu-id="ca93e-580">Version 2002: March 01</span></span>
<span data-ttu-id="ca93e-581">*Versão 2002 (Criação 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-582">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-583">Outlook</span></span>

- <div><span data-ttu-id="ca93e-584">Resolve um problema que fazia com que aplicativos de terceiros não pudessem enviar e-mails.</span><span class="sxs-lookup"><span data-stu-id="ca93e-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-february-24"></a><span data-ttu-id="ca93e-586">Versão 2002: 24 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ca93e-586">Version 2002: February 24</span></span>
<span data-ttu-id="ca93e-587">*Versão 2002 (Criação 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="ca93e-588">Várias correções de bugs e de desempenho.</span><span class="sxs-lookup"><span data-stu-id="ca93e-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="ca93e-589">Versão 2002: 22 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ca93e-589">Version 2002: February 22</span></span>
<span data-ttu-id="ca93e-590">*Versão 2002 (Criação 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="ca93e-591">Várias correções de bugs e de desempenho.</span><span class="sxs-lookup"><span data-stu-id="ca93e-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="ca93e-592">Versão 2002: 21 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ca93e-592">Version 2002: February 21</span></span>
<span data-ttu-id="ca93e-593">Versão 2002 (Build 12527.20174)</span><span class="sxs-lookup"><span data-stu-id="ca93e-593">*Version 2002 (Build 12527.20174)*</span></span>


<span data-ttu-id="ca93e-594"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="ca93e-594">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ca93e-595">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ca93e-596">Access</span><span class="sxs-lookup"><span data-stu-id="ca93e-596">Access</span></span>

- <span data-ttu-id="ca93e-597">**Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la.</span><span class="sxs-lookup"><span data-stu-id="ca93e-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="ca93e-598">Pesquise e substitua o texto no SQL View.</span><span class="sxs-lookup"><span data-stu-id="ca93e-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="ca93e-599">Selecione várias tabelas na janela Relações.</span><span class="sxs-lookup"><span data-stu-id="ca93e-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-600">Outlook</span></span>

- <span data-ttu-id="ca93e-601">**Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar?</span><span class="sxs-lookup"><span data-stu-id="ca93e-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="ca93e-602">O Outlook agora detecta isso e ajuda você a se conectar.</span><span class="sxs-lookup"><span data-stu-id="ca93e-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-605">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ca93e-606">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="ca93e-607">Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="ca93e-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="ca93e-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-608">Outlook</span></span>

- <div><span data-ttu-id="ca93e-609">Corrige um problema que fazia com que as vírgulas no campo local de uma reunião se transformassem em ponto e vírgula.</span><span class="sxs-lookup"><span data-stu-id="ca93e-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="ca93e-610">Resolve um problema que pode resultar em uma falha ao exibir o mesmo item em várias janelas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="ca93e-611">Resolve um problema que fez com que o Outlook sincronize inesperadamente todos os e-mails, mesmo quando o controle deslizante de sincronização estiver definido como uma configuração menor.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="ca93e-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="ca93e-612">Resolve um problema que fez com que os usuários com o Tema Preto consultem o &quot;De&quot; da lista suspensa mostrem um texto branco sobre um fundo branco..</span><span class="sxs-lookup"><span data-stu-id="ca93e-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="ca93e-613"><span style="display:inline !important;">Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.</span></span><span class="sxs-lookup"><span data-stu-id="ca93e-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-february-18"></a><span data-ttu-id="ca93e-615">Versão 2002: 18 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ca93e-615">Version 2002: February 18</span></span>
<span data-ttu-id="ca93e-616">*Versão 2002 (Build 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="ca93e-617">Versão 2002: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="ca93e-617">Version 2002: February 11</span></span>
<span data-ttu-id="ca93e-618">*Versão 2002 (Build 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="ca93e-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="ca93e-619">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ca93e-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ca93e-621">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="ca93e-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ca93e-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-622">Outlook</span></span>

- <span data-ttu-id="ca93e-623">**Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="ca93e-624">As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="ca93e-625">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-625">Word</span></span>

- <span data-ttu-id="ca93e-626">**Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.</span><span class="sxs-lookup"><span data-stu-id="ca93e-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ca93e-627">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-627">Office Suite</span></span>

- <span data-ttu-id="ca93e-628">**Ícones mais claros da barra de status:** Agora é mais fácil visualizar os ícones da barra de status.</span><span class="sxs-lookup"><span data-stu-id="ca93e-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ca93e-631">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="ca93e-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ca93e-632">Access</span><span class="sxs-lookup"><span data-stu-id="ca93e-632">Access</span></span>

- <span data-ttu-id="ca93e-633">Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados.</span><span class="sxs-lookup"><span data-stu-id="ca93e-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="ca93e-634">Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.</span><span class="sxs-lookup"><span data-stu-id="ca93e-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="ca93e-635">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="ca93e-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="ca93e-636">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="ca93e-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="ca93e-637">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="ca93e-638">Excel</span><span class="sxs-lookup"><span data-stu-id="ca93e-638">Excel</span></span>

- <span data-ttu-id="ca93e-639">Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="ca93e-640">Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="ca93e-641">Corrigido um problema em que o Excel falhava ao usar colunas de texto em com matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="ca93e-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="ca93e-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="ca93e-642">Outlook</span></span>

- <span data-ttu-id="ca93e-643">Corrigido um problema em que a rolagem no calendário com a exibição do mês não mostrava eventos anteriores do calendário.</span><span class="sxs-lookup"><span data-stu-id="ca93e-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="ca93e-644">As pastas salvas em ‘Favoritos’ no painel de navegação à esquerda podem desaparecer continuamente.</span><span class="sxs-lookup"><span data-stu-id="ca93e-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="ca93e-645">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="ca93e-646">Solucionado um problema que fazia com que a opção desativar o realce do item sinalizado deixasse de ser respeitada em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="ca93e-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="ca93e-647">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.</span><span class="sxs-lookup"><span data-stu-id="ca93e-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="ca93e-648">Correção de um problema em que os emails que expiravam com base em uma política de retenção exibiam dois rótulos.</span><span class="sxs-lookup"><span data-stu-id="ca93e-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="ca93e-649">Um que mostrava que o email expiraria em um dia e outro exibindo a expiração em dois dias.</span><span class="sxs-lookup"><span data-stu-id="ca93e-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="ca93e-650">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="ca93e-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ca93e-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ca93e-651">PowerPoint</span></span>

- <span data-ttu-id="ca93e-652">Correção de um problema em que a Tinta não era processada completamente ou era pulado ao ser usada em uma animação de tinta do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ca93e-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="ca93e-653">Corrigido um problema em que, após fechar um arquivo, o PowerPoint não o removia imediatamente da coleção Apresentações, se houvesse algum manipulador de eventos em execução.</span><span class="sxs-lookup"><span data-stu-id="ca93e-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="ca93e-654">Portanto, o número de apresentações abertas relatadas pelo modelo de objeto ficava incorreto, e o desligamento do PowerPoint era impedido.</span><span class="sxs-lookup"><span data-stu-id="ca93e-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="ca93e-655">Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.</span><span class="sxs-lookup"><span data-stu-id="ca93e-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="ca93e-656">Project</span><span class="sxs-lookup"><span data-stu-id="ca93e-656">Project</span></span>

- <span data-ttu-id="ca93e-657">Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="ca93e-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="ca93e-658">Word</span><span class="sxs-lookup"><span data-stu-id="ca93e-658">Word</span></span>

- <span data-ttu-id="ca93e-659">Às vezes, atualizar e rolar um índice pode exibir uma área cinza sobre o documento.</span><span class="sxs-lookup"><span data-stu-id="ca93e-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="ca93e-660">Corrigido um problema em que o uso de "Procurar" para salvar um arquivo não funcionava se um comentário fosse escrito, mas não postado, e o usuário tentasse salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="ca93e-661">Corrigido um problema em que alternar entre os cartões de comentários às vezes exibia o comentário selecionado inicialmente com um destaque de seleção.</span><span class="sxs-lookup"><span data-stu-id="ca93e-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="ca93e-662">Correção de um problema em que a formatação em itálico era perdida após a edição de um comentário, pondo o texto em itálico e, em seguida, fazendo a postagem do mesmo.</span><span class="sxs-lookup"><span data-stu-id="ca93e-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="ca93e-663">Correção de um problema em que a dica de comentário não estava visível no modo de leitura com a cor da página Invertida.</span><span class="sxs-lookup"><span data-stu-id="ca93e-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="ca93e-664">Corrigido um problema em que, se um documento fosse usado em coautoria, a versão de rascunho de um comentário raiz poderia não ser preservada.</span><span class="sxs-lookup"><span data-stu-id="ca93e-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="ca93e-665">Com o SlideTrack habilitado e o painel de comentários fechado, Ctrl+Alt+M pode não abrir o painel de comentários.</span><span class="sxs-lookup"><span data-stu-id="ca93e-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="ca93e-666">Corrigido um problema ao adicionar @menção em uma tabela poderia gerar a mensagem de erro: "Uma tabela neste documento foi corrompida".</span><span class="sxs-lookup"><span data-stu-id="ca93e-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="ca93e-667">Correção de um problema em que os comandos de comentário (Editar comentário, Responder ao comentário, Excluir comentário, Resolver comentário) não estavam sendo exibidos no menu de contexto comentários.</span><span class="sxs-lookup"><span data-stu-id="ca93e-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ca93e-668">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="ca93e-668">Office Suite</span></span>

- <span data-ttu-id="ca93e-669">Resolve um problema que pode ter causado a instalação incorreta do pacote de ferramentas de revisão Nynorsk da Noruega (nn-no).</span><span class="sxs-lookup"><span data-stu-id="ca93e-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="ca93e-670">Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.</span><span class="sxs-lookup"><span data-stu-id="ca93e-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


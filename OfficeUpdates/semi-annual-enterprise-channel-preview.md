---
title: Notas de versão para lançamentos do Canal Empresarial Semestral em 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI notas de versão dos lançamentos do canal semestral (direcionado) do Microsoft 365 Apps em 2020
ms.openlocfilehash: 838721b3bd587a03ddce1bc68bd13c06ae2fdc37
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138737"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="67b85-103">Notas de versão para lançamentos do Canal Empresarial Semestral em 2020</span><span class="sxs-lookup"><span data-stu-id="67b85-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="67b85-104">Estas notas de versão fornecem informações dos novos recursos e atualizações não relacionadas à segurança que estão inclusas nas atualizações de 2020 do Canal Empresarial Semestral do Microsoft 365 Apps para Pequenos e Médios Negócios, Microsoft 365 Apps para Grandes Empresas e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="67b85-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="67b85-105">Estamos fazendo algumas alterações nos canais de atualização para o Microsoft 365 Apps, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="67b85-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="67b85-106">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="67b85-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-july-14"></a><span data-ttu-id="67b85-107">Versão 2002: 14 de julho</span><span class="sxs-lookup"><span data-stu-id="67b85-107">Version 2002: July 14</span></span>
<span data-ttu-id="67b85-108">*Versão 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="67b85-108">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="67b85-109">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-111">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="67b85-112">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-112">Excel</span></span>

- <span data-ttu-id="67b85-113">Acelerar o carregamento de arquivos disponíveis na pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="67b85-113">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="67b85-114">Correção de um problema que causava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="67b85-114">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="67b85-115">Correção de um problema em que a mensagem de erro "Esta pasta de trabalho está referenciada por outra pasta e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="67b85-115">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="67b85-116">Correção de um problema em que uma pasta de trabalho poderia ficar oculta ao clicar em um hiperlink em uma pasta de trabalho já aberta.</span><span class="sxs-lookup"><span data-stu-id="67b85-116">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="67b85-117">Correção de um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.</span><span class="sxs-lookup"><span data-stu-id="67b85-117">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="67b85-118">Desempenho aprimorado ao excluir colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="67b85-118">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="67b85-119">Correção de um problema em que os nomes de impressora poderiam ser repetidos na lista de impressoras na caixa de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="67b85-119">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="67b85-120">Consertamos um problema em que as planilhas que continham várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.</span><span class="sxs-lookup"><span data-stu-id="67b85-120">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="67b85-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-121">Outlook</span></span>

- <span data-ttu-id="67b85-122">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="67b85-122">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="67b85-123">Soluciona um problema em que compromissos ou reuniões recorrentes eram exibidos na hora errada ao alterar a definição de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="67b85-123">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="67b85-124">Soluciona um problema que exibia a mensagem “As regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="67b85-124">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="67b85-125">Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.</span><span class="sxs-lookup"><span data-stu-id="67b85-125">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="67b85-126">Foi resolvido um problema que fazia com que as categorias desaparecessem ocasionalmente de mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="67b85-126">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="67b85-127">Foi resolvido um problema que fazia com que representantes vissem diferentes hierarquias de pastas em caixas de correio compartilhadas em computadores diferentes.</span><span class="sxs-lookup"><span data-stu-id="67b85-127">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="67b85-128">Solucionamos um problema que fazia com que representantes recebessem uma mensagem de erro ao editar um compromisso de calendário existente no calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="67b85-128">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="67b85-129">Correção de um problema que fazia com que o corpo de uma mensagem de Notificação de Falha na Entrega mudasse de Unicode para ASCII após editar o assunto.</span><span class="sxs-lookup"><span data-stu-id="67b85-129">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="67b85-130">Correção de um problema que causava uma falha quando dois suplementos adicionam um botão ao mesmo grupo da faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="67b85-130">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="67b85-131">Correção de um problema que fazia com que os usuários não conseguissem endereçar emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="67b85-131">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="67b85-132">Correção de um problema que fazia com que os links não sejam adicionados aos emails com a permissão de locatário padrão correta quando a permissão de locatário padrão está configurada como "qualquer pessoa".</span><span class="sxs-lookup"><span data-stu-id="67b85-132">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="67b85-133">Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="67b85-133">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="67b85-134">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-134">Word</span></span>

- <span data-ttu-id="67b85-135">Correção de um problema na coautoria se habilitarmos a política FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="67b85-135">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="67b85-136">Correção de um problema em que partes rápidas no Word não funcionava ao adicionar um campo de pesquisa que foi renomeado.</span><span class="sxs-lookup"><span data-stu-id="67b85-136">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="67b85-137">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="67b85-137">Office Suite</span></span>

- <span data-ttu-id="67b85-138">Correção de um problema em que poderia ocorrer uso excessivo da rede e da CPU durante a coautoria em arquivos grandes do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="67b85-138">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="67b85-139">Fizemos um novo AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="67b85-139">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="67b85-140">Soluciona um problema que causava falha no host do Office no Windows, quando um suplemento é ativado enquanto o valor TabProcGrowth do registro é do tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="67b85-140">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-june-09"></a><span data-ttu-id="67b85-142">Versão 2002: 09 de junho</span><span class="sxs-lookup"><span data-stu-id="67b85-142">Version 2002: June 09</span></span>
<span data-ttu-id="67b85-143">*Versão 2002 (Build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="67b85-143">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="67b85-144">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-144">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-146">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-146">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="67b85-147">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-147">Excel</span></span>

- <span data-ttu-id="67b85-148">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="67b85-148">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="67b85-149">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="67b85-149">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="67b85-150">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="67b85-150">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="67b85-151">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="67b85-151">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="67b85-152">Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="67b85-152">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="67b85-153">Correção de um problema em que um símbolo @ iniciando uma fórmula seria considerado um operador de interseção implícito.</span><span class="sxs-lookup"><span data-stu-id="67b85-153">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="67b85-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-154">Outlook</span></span>

- <span data-ttu-id="67b85-155">Permite que você ingresse em uma reunião do Teams diretamente por meio do cliente nativo do Teams.</span><span class="sxs-lookup"><span data-stu-id="67b85-155">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="67b85-156">Solucionamos um problema em que o Outlook falhava ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="67b85-156">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="67b85-157">Solucionamos um problema que fazia com que os usuários com a configuração de emulação do navegador incorreta não conseguissem concluir o prompt de autenticação do Gmail.</span><span class="sxs-lookup"><span data-stu-id="67b85-157">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="67b85-158">Solucionamos um problema que fazia com que os usuários do Outlook nos sistemas operacionais de servidor vissem o erro "status do antivírus: inválido".</span><span class="sxs-lookup"><span data-stu-id="67b85-158">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="67b85-159">Esta versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus era encontrado, apesar do antivírus ter sido configurado adequadamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-159">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="67b85-160">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-160">Word</span></span>

- <span data-ttu-id="67b85-161">Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.</span><span class="sxs-lookup"><span data-stu-id="67b85-161">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="67b85-162">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="67b85-162">Office Suite</span></span>

- <span data-ttu-id="67b85-163">Resolvemos esse problema atualizando os nomes dos canais no backstage para os nomes dos novos canais na bifurcação de Janeiro de 2020.</span><span class="sxs-lookup"><span data-stu-id="67b85-163">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="67b85-164">Corrigimos esse problema e no futuro, se um dispositivo for gerenciado por política, ele não chamará a API de audiência do DMS.</span><span class="sxs-lookup"><span data-stu-id="67b85-164">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="67b85-165">Resolvemos o problema em que há uma remoção incompleta ao adicionar e remover aplicativos em uma única transação.</span><span class="sxs-lookup"><span data-stu-id="67b85-165">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="67b85-166">O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero.</span><span class="sxs-lookup"><span data-stu-id="67b85-166">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="67b85-167">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="67b85-167">This change would fix this issue.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-may-12"></a><span data-ttu-id="67b85-169">Versão 2002: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="67b85-169">Version 2002: May 12</span></span>
<span data-ttu-id="67b85-170">*Versão 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="67b85-170">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="67b85-171">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-171">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-173">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-173">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="67b85-174">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-174">Excel</span></span>

- <span data-ttu-id="67b85-175">Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, especialmente com janelas ocultas, seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="67b85-175">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="67b85-176">A abertura de arquivos CSV estava demorando mais do que o esperado em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="67b85-176">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="67b85-177">O Excel pode falhar em algumas circunstâncias ao alternar entre pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="67b85-177">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="67b85-178">Correção de um problema com o VBA no qual a escrita de valores em um intervalo seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="67b85-178">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="67b85-179">Os dados copiados de uma coluna filtrada por cores às vezes não serão colados corretamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-179">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="67b85-180">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma Tabela Dinâmica.</span><span class="sxs-lookup"><span data-stu-id="67b85-180">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="67b85-181">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="67b85-181">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="67b85-182">Corrigido um problema em que a propriedade "O Valor Cruza Em" se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="67b85-182">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="67b85-183">Usar um Intervalo.Valor e Intervalo.Valor2 (VBA) faria com que as fórmulas fossem inseridas como matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="67b85-183">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="67b85-184">OneNote</span><span class="sxs-lookup"><span data-stu-id="67b85-184">OneNote</span></span>

- <span data-ttu-id="67b85-185">Localiza a notificação que permite que o usuário saiba mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="67b85-185">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="67b85-186">Exibe uma notificação que permite ao usuário saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade do serviço e de sincronia.</span><span class="sxs-lookup"><span data-stu-id="67b85-186">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="67b85-187">Melhoria da estabilidade do serviço e de sincronização, reduzindo temporariamente a frequência do número e da sincronia das páginas do histórico de versão no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="67b85-187">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="67b85-188">Melhoria da sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="67b85-188">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="67b85-189">Quando um usuário tenta excluir dados que normalmente seriam enviados para a lixeira, os usuários serão solicitados a optar por manter ou excluir permanentemente os dados.</span><span class="sxs-lookup"><span data-stu-id="67b85-189">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="67b85-190">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="67b85-190">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="67b85-191">Melhoria da estabilidade do serviço e da sincronia referindo-se temporariamente ao download de arquivos e imagens inseridas em blocos de anotações online até que o usuário navegue para a página no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="67b85-191">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="67b85-192">Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="67b85-192">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="67b85-193">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="67b85-193">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="67b85-194">Melhoria da sincronia e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="67b85-194">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="67b85-195">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="67b85-195">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="67b85-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-196">Outlook</span></span>

- <span data-ttu-id="67b85-197">Corrigido um problema que provocou a alteração inesperada da largura do painel de pasta.</span><span class="sxs-lookup"><span data-stu-id="67b85-197">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="67b85-198">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao tentar abrir arquivos .msg e .oft após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="67b85-198">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="67b85-199">Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="67b85-199">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="67b85-200">Esta atualização corrige um problema com o Microsoft Outlook, que não exibe o rótulo de confidencialidade atual ao exibir ou redigir mensagens.</span><span class="sxs-lookup"><span data-stu-id="67b85-200">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="67b85-201">Solucionamos um problema que fazia com que os usuários não conseguissem lidar com emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="67b85-201">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="67b85-202">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-202">PowerPoint</span></span>

- <span data-ttu-id="67b85-203">Correção de um problema para retransmissão de mensagens corretas para os usuários que abrirem uma cópia de um arquivo que tenha comentários melhorados.</span><span class="sxs-lookup"><span data-stu-id="67b85-203">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="67b85-204">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-204">Word</span></span>

- <span data-ttu-id="67b85-205">Resolvemos o problema em que o Access e o Publisher podem não inicializar corretamente dependendo de quais idiomas foram instalados.</span><span class="sxs-lookup"><span data-stu-id="67b85-205">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="67b85-206">Corrigimos um problema com o recurso Comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="67b85-206">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="67b85-207">Corrigimos um problema ao mesclar dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="67b85-207">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="67b85-208">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="67b85-208">Office Suite</span></span>

- <span data-ttu-id="67b85-209">Esta é uma correção para que o aplicativo do Project não bloqueie rede quando o arquivo estiver armazenado em cache no cliente.</span><span class="sxs-lookup"><span data-stu-id="67b85-209">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="67b85-210">Resolvemos o problema em que uma operação interna estava gerando uma exceção na falha, em vez de fazer o logon e continuar.</span><span class="sxs-lookup"><span data-stu-id="67b85-210">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="67b85-211">Os usuários afetados não serão mais impedidos de receber as atualizações.</span><span class="sxs-lookup"><span data-stu-id="67b85-211">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="67b85-212">Essa alteração garante que a estrutura de tópicos Esboçada funcione corretamente na faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="67b85-212">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="67b85-213">Corrigimos um problema ao abrir arquivos de locais no ambiente local com algumas configurações específicas de proxy.</span><span class="sxs-lookup"><span data-stu-id="67b85-213">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="67b85-214">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="67b85-214">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="67b85-215">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="67b85-215">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="67b85-216">Esta atualização corrige um problema no Microsoft Word, em que textos com mais de 255 caracteres inseridos durante a aplicação de um rótulo de sensibilidade não poderiam ser subsequentemente identificados e removidos alterando ou removendo a etiqueta se a política de rótulo tiver aplicado um cabeçalho, rodapé ou marca-d ' água.</span><span class="sxs-lookup"><span data-stu-id="67b85-216">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="67b85-217">Correção de um problema que elimina panes durante as sessões de entrega do Office e maior confiabilidade na experiência do usuário.</span><span class="sxs-lookup"><span data-stu-id="67b85-217">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="67b85-218">Esse bug atualiza o ponto de extremidade da URL do serviço de configuração avançada (ECS).</span><span class="sxs-lookup"><span data-stu-id="67b85-218">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="67b85-219">Chamar esse ponto de extremidade mais recente tem uma taxa de sucesso maior para buscar a partir de ECS.</span><span class="sxs-lookup"><span data-stu-id="67b85-219">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-april-14"></a><span data-ttu-id="67b85-221">Versão 2002: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="67b85-221">Version 2002: April 14</span></span>
<span data-ttu-id="67b85-222">*Versão 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="67b85-222">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="67b85-223">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-223">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="67b85-224">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="67b85-224">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="67b85-225">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-225">Excel</span></span>

- <span data-ttu-id="67b85-226">**Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão enviados para as células vizinhas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-226">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="67b85-227">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-227">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="67b85-228">**Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span><span class="sxs-lookup"><span data-stu-id="67b85-228">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="67b85-229">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-229">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="67b85-230">**Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!** Linha por linha, encontre tudo o que precisa em uma tabela ou intervalo com XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="67b85-230">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="67b85-231">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-231">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-233">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-233">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="67b85-234">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-234">Excel</span></span>

- <span data-ttu-id="67b85-235">O Excel falharia em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="67b85-235">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="67b85-236">Ao salvar como um arquivo CSV, o Excel poderia mesclar todas as colunas em uma única coluna em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="67b85-236">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="67b85-237">Usar Range.ClearContents em um intervalo de uma planilha protegida pode levar mais tempo do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="67b85-237">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="67b85-238">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="67b85-238">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="67b85-239">As macros do VBA que interagem com a faixa de opções podem ser executadas com o conjunto de ScreenUpdating definido como Verdadeiro inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-239">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="67b85-240">Foi solucionado um problema em que os links externos não eram atualizados durante o preenchimento (preencher abaixo, preencher entre, etc.) se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="67b85-240">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="67b85-241">Em alguns casos, o uso do Application.Evaluate do VBA não funcionava para funções definidas pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="67b85-241">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="67b85-242">Solucionamos um problema de desempenho durante a criação de gráficos de modelos.</span><span class="sxs-lookup"><span data-stu-id="67b85-242">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="67b85-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-243">Outlook</span></span>

- <span data-ttu-id="67b85-244">Foi solucionado um problema que fazia com que o Título do Grupo se expandisse inesperadamente em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="67b85-244">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="67b85-245">Foi resolvido um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="67b85-245">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="67b85-246">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="67b85-246">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="67b85-247">Foi solucionado um problema que fazia com que o botão Salvar na nuvem estivesse ausente nas Ferramentas de anexo.</span><span class="sxs-lookup"><span data-stu-id="67b85-247">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="67b85-248">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-248">PowerPoint</span></span>

- <span data-ttu-id="67b85-249">Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-lo em outro slide em um loop.</span><span class="sxs-lookup"><span data-stu-id="67b85-249">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="67b85-250">Project</span><span class="sxs-lookup"><span data-stu-id="67b85-250">Project</span></span>

- <span data-ttu-id="67b85-251">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="67b85-251">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="67b85-252">Correção de um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="67b85-252">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="67b85-253">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-253">Word</span></span>

- <span data-ttu-id="67b85-254">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="67b85-254">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="67b85-255">Corrigimos um problema com o ajuste de texto em uma tabela.</span><span class="sxs-lookup"><span data-stu-id="67b85-255">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="67b85-256">Corrigimos um problema em que não era possível inserir linhas horizontais e centralizar.</span><span class="sxs-lookup"><span data-stu-id="67b85-256">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="67b85-258">Versão 2002: 10 de março</span><span class="sxs-lookup"><span data-stu-id="67b85-258">Version 2002: March 10</span></span>
<span data-ttu-id="67b85-259">*Versão 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="67b85-259">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="67b85-260">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-260">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="67b85-262">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="67b85-262">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="67b85-263">Access</span><span class="sxs-lookup"><span data-stu-id="67b85-263">Access</span></span>

- <span data-ttu-id="67b85-264">**Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas.</span><span class="sxs-lookup"><span data-stu-id="67b85-264">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="67b85-265">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-265">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="67b85-266">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-266">Excel</span></span>

- <span data-ttu-id="67b85-267">**Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles.</span><span class="sxs-lookup"><span data-stu-id="67b85-267">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="67b85-268">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-268">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="67b85-269">**Encontre o que está procurando:** Pesquise comandos, pessoas, arquivos, fotos, artigos da Web e muito mais.</span><span class="sxs-lookup"><span data-stu-id="67b85-269">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="67b85-270">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-270">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="67b85-271">**Faça um Esboço:** Deixe as formas do Office da sua pasta de trabalho com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="67b85-271">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="67b85-272">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-272">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="67b85-273">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="67b85-273">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="67b85-274">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="67b85-274">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="67b85-275">**Foco no que precisa ser feito:** Selecione Resolver para recolher comentários e dar destaque aos itens abertos.</span><span class="sxs-lookup"><span data-stu-id="67b85-275">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="67b85-276">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="67b85-276">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="67b85-277">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-277">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="67b85-278">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="67b85-278">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="67b85-279">**Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel.</span><span class="sxs-lookup"><span data-stu-id="67b85-279">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="67b85-280">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-280">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="67b85-281">**Leia e responda instantaneamente:** Responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="67b85-281">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="67b85-282">**Obtenha estatísticas em sua pasta de trabalho:** As Estatísticas da Pasta de Trabalho fornecem uma visão geral do conteúdo de uma pasta de trabalho, para ajudar você a descobrir o conteúdo com mais facilidade.</span><span class="sxs-lookup"><span data-stu-id="67b85-282">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="67b85-283">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-283">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="67b85-284">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-284">Find them at Insert > Icons.</span></span> [<span data-ttu-id="67b85-285">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-285">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="67b85-286">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-286">Outlook</span></span>

- <span data-ttu-id="67b85-287">**Conecte sua rede do LinkedIn ao Outlook:** Conecte sua conta do LinkedIn com segurança à sua conta da Microsoft para ver informações de perfis do LinkedIn diretamente no cartão de Pessoas.</span><span class="sxs-lookup"><span data-stu-id="67b85-287">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="67b85-288">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-288">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="67b85-p120">**Todas as opções de criptografia em um só lugar:** Basta ir para Opções > Criptografar para escolher como proteger sua mensagem de email. [Saiba mais](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="67b85-p120">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="67b85-291">**O menu Inserir Link no Outlook inserirá um link com a permissão definida pelo administrador do locatário:** um link do Inserir Link MRU no Outlook insere um link que só funcionou para usuários que já tinham permissões.</span><span class="sxs-lookup"><span data-stu-id="67b85-291">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="67b85-292">Isso causou uma troca de emails frequente entre os usuários solicitando o acesso a um documento.</span><span class="sxs-lookup"><span data-stu-id="67b85-292">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="67b85-293">Atualizamos essa experiência e agora o link é inserido com a permissão padrão definida pelo administrador do locatário. No MSIT, é "A organização pode editar", para que todos os usuários internos que recebem um link compartilhado dessa maneira possam acessá-lo.</span><span class="sxs-lookup"><span data-stu-id="67b85-293">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="67b85-294">**Pesquisar com erros de ortografia ou digitação:** O Outlook encontrará o que você está procurando, mesmo quando a ortografia não corresponder.</span><span class="sxs-lookup"><span data-stu-id="67b85-294">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="67b85-295">**Emails de phishing fáceis de identificar:** As mensagens de spam e phishing têm uma aparência diferente, para que você possa identificá-las e eliminá-las facilmente na caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="67b85-295">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="67b85-296">**Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.</span><span class="sxs-lookup"><span data-stu-id="67b85-296">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="67b85-297">**Deixe-me desenhar:** Rabisque em fotos ou adicione uma Tela de Desenho para enviar seus pensamentos com tinta.</span><span class="sxs-lookup"><span data-stu-id="67b85-297">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="67b85-298">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-298">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="67b85-299">**Veja as mensagens relevantes nos resultados de pesquisa:** o Outlook analisa os termos de pesquisa e mostra as mensagens de email mais relevantes na parte superior dos resultados da pesquisa.</span><span class="sxs-lookup"><span data-stu-id="67b85-299">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="67b85-300">Você também verá todos os resultados classificados por data, na seção Resultados Principais.</span><span class="sxs-lookup"><span data-stu-id="67b85-300">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="67b85-301">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-301">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="67b85-302">**Obtenha sugestões de locais:** comece a digitar em Local ao agendar compromissos e reuniões, e o Outlook irá sugerir salas, endereços e outros locais recentes.</span><span class="sxs-lookup"><span data-stu-id="67b85-302">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="67b85-303">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-303">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="67b85-304">**Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens.</span><span class="sxs-lookup"><span data-stu-id="67b85-304">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="67b85-305">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-305">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="67b85-306">**Veja suas mensagens sob uma perspectiva diferente:** use o botão Sol/Lua para alternar entre planos de fundo claros e escuros no painel de leitura.</span><span class="sxs-lookup"><span data-stu-id="67b85-306">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="67b85-307">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-307">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="67b85-308">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-308">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="67b85-309">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-309">Find them at Insert > Icons.</span></span> [<span data-ttu-id="67b85-310">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-310">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="67b85-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-311">PowerPoint</span></span>

- <span data-ttu-id="67b85-312">**Colaboração rápida e em tempo real no PowerPoint:** Colaboração rápida e em tempo real no PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-312">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="67b85-313">**Novas ferramentas de revisão:** não se preocupe com suas palavras.</span><span class="sxs-lookup"><span data-stu-id="67b85-313">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="67b85-314">Agora, o PowerPoint fornece sugestões de gramática e ortografia.</span><span class="sxs-lookup"><span data-stu-id="67b85-314">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="67b85-315">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-315">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="67b85-316">**Legendas em tempo real:** As palavras do apresentador aparecem na tela automaticamente como legendas ou traduzidas para o idioma que escolher.</span><span class="sxs-lookup"><span data-stu-id="67b85-316">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="67b85-317">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-317">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="67b85-p130">**Você calcula, nós formatamos:** Nós trocamos expressões matemáticas difíceis de desenhar por caracteres padrão. Basta escolher Tinta para Matemática e selecionar suas anotações manuscritas para começar.[Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="67b85-p130">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="67b85-321">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="67b85-321">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="67b85-322">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-322">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="67b85-323">**Localize e corrija títulos de slides ausentes:** Títulos de slides reforçam o seu discurso e tornam os seus slides acessíveis a usuários de todas as habilidades.</span><span class="sxs-lookup"><span data-stu-id="67b85-323">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="67b85-324">O Verificador de Acessibilidade mostra onde os títulos estão ausentes para que você possa adicioná-los imediatamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-324">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="67b85-325">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-325">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="67b85-326">**Faça um Esboço:** deixe as formas do Office da sua apresentação com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="67b85-326">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="67b85-327">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-327">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="67b85-328">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="67b85-328">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="67b85-329">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="67b85-329">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="67b85-330">**Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem.</span><span class="sxs-lookup"><span data-stu-id="67b85-330">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="67b85-331">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-331">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="67b85-332">**Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos.</span><span class="sxs-lookup"><span data-stu-id="67b85-332">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="67b85-333">Deixá-los ou não ativados depende de você.</span><span class="sxs-lookup"><span data-stu-id="67b85-333">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="67b85-334">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-334">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="67b85-335">**Repe-tinta-ção Instantânea:** Ao escrever à tinta nos slides, aplique uma animação de repetição para reproduzir o desenho real da sua tinta durante a apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="67b85-335">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="67b85-336">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-336">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="67b85-337">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="67b85-337">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="67b85-338">**Otimize sua apresentação para todos:** O Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.</span><span class="sxs-lookup"><span data-stu-id="67b85-338">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="67b85-339">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="67b85-339">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="67b85-340">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="67b85-340">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="67b85-341">**Por que reinventa quando você pode reutilizar?:** poupar tempo usando novamente slides que você criou ou que outras pessoas compartilharam com você.</span><span class="sxs-lookup"><span data-stu-id="67b85-341">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="67b85-342">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-342">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="67b85-343">**Transforme tinta manuscrita em formas, texto ou expressões matemáticas no PowerPoint para Office 365:** Vá de tinta de forma livre para formas, texto ou uma expressão matemática com apenas alguns traços.</span><span class="sxs-lookup"><span data-stu-id="67b85-343">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="67b85-344">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-344">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="67b85-345">**Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="67b85-345">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="67b85-346">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-346">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="67b85-347">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-347">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="67b85-348">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-348">Find them at Insert > Icons.</span></span> [<span data-ttu-id="67b85-349">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-349">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="67b85-350">Visio</span><span class="sxs-lookup"><span data-stu-id="67b85-350">Visio</span></span>

- <span data-ttu-id="67b85-351">**Voltando para a cena do crime:** Use os novos estênceis de Evidência, Interno e Externo no modelo de Investigação de Cena de Crime para recriar cenas de crimes em detalhes.</span><span class="sxs-lookup"><span data-stu-id="67b85-351">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="67b85-352">**Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha.</span><span class="sxs-lookup"><span data-stu-id="67b85-352">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="67b85-353">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-353">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="67b85-354">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-354">Word</span></span>

- <span data-ttu-id="67b85-355">**O Editor de Currículos se une ao Assistente de Currículos do LinkedIn:** O Editor de Currículos oferece uma seleção de verificações gramaticais e de estilo especialmente adaptadas para currículos, para tornar a sua escrita mais precisa e profissional.</span><span class="sxs-lookup"><span data-stu-id="67b85-355">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="67b85-356">**Corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D:** corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="67b85-356">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="67b85-357">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="67b85-357">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="67b85-358">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-358">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="67b85-359">**Colabore em cores:** Comentários e alterações são codificados por cores por colaborador, para que seja fácil ver quem está entre seus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="67b85-359">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="67b85-360">**Edite documentos habilitados para macro de maneira colaborativa:** Salve arquivos docm no OneDrive for Business e edite-os com seus colaboradores em tempo real.</span><span class="sxs-lookup"><span data-stu-id="67b85-360">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="67b85-361">**Aperfeiçoamentos de coautoria**: melhor desempenho do Word durante a coautoria em documentos com alterações controladas.</span><span class="sxs-lookup"><span data-stu-id="67b85-361">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="67b85-362">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-362">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="67b85-363">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="67b85-363">Find them at Insert > Icons.</span></span> [<span data-ttu-id="67b85-364">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-364">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="67b85-365">**Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.</span><span class="sxs-lookup"><span data-stu-id="67b85-365">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="67b85-366">**Faça um Esboço:** deixe as formas do Office do seu documento com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="67b85-366">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="67b85-367">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-367">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="67b85-368">**Apagar com precisão:** Escolha entre dois tamanhos de borracha para corrigir pequenas imperfeições à tinta.</span><span class="sxs-lookup"><span data-stu-id="67b85-368">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="67b85-369">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="67b85-369">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="67b85-370">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="67b85-370">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="67b85-371">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="67b85-371">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="67b85-372">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-372">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="67b85-373">**Melhorias na coautoria** Confiabilidade aprimorada durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="67b85-373">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="67b85-374">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="67b85-374">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="67b85-375">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-375">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="67b85-376">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="67b85-376">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="67b85-377">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="67b85-377">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="67b85-378">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-378">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="67b85-379">**Salvar formas como imagens:** em apenas alguns cliques, salve uma forma, ícone ou outro objeto como arquivo de imagem para reutilizá-lo em outro lugar.</span><span class="sxs-lookup"><span data-stu-id="67b85-379">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="67b85-380">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="67b85-380">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-383">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-383">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="67b85-384">Access</span><span class="sxs-lookup"><span data-stu-id="67b85-384">Access</span></span>

- <span data-ttu-id="67b85-385">Esta atualização corrige um problema no Microsoft Access que pode causar o erro &quot;A consulta está corrompida&quot; quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada em SQL.</span><span class="sxs-lookup"><span data-stu-id="67b85-385">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="67b85-386">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-386">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="67b85-387">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="67b85-387">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="67b85-388">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="67b85-388">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="67b85-389">Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados.</span><span class="sxs-lookup"><span data-stu-id="67b85-389">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="67b85-390">Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.</span><span class="sxs-lookup"><span data-stu-id="67b85-390">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="67b85-391">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-391">Excel</span></span>

- <span data-ttu-id="67b85-392">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="67b85-392">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="67b85-393">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="67b85-393">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="67b85-394">Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="67b85-394">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="67b85-395">Esta atualização corrige um problema que fazia com que barra de fórmulas exibisse texto em uma fonte diferente da esperada.</span><span class="sxs-lookup"><span data-stu-id="67b85-395">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="67b85-396">A funcionalidade Texto em Coluna pode falhar para algumas localidades.</span><span class="sxs-lookup"><span data-stu-id="67b85-396">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="67b85-397">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="67b85-397">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="67b85-398">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="67b85-398">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="67b85-399">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="67b85-399">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="67b85-400">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="67b85-400">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="67b85-401">A funcionalidade Texto em Coluna pode falhar em algumas localizações.</span><span class="sxs-lookup"><span data-stu-id="67b85-401">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="67b85-402">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="67b85-402">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="67b85-403">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="67b85-403">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="67b85-404">Foi corrigido um problema que alguns usuários podem ter tido com objetos inseridos e vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="67b85-404">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="67b85-405">Corrigimos o menu do botão direito do mouse de Gráficos Dinâmicos para habilitar a opção Mostrar Detalhes.</span><span class="sxs-lookup"><span data-stu-id="67b85-405">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="67b85-406">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="67b85-406">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="67b85-407">Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="67b85-407">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="67b85-408">Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.</span><span class="sxs-lookup"><span data-stu-id="67b85-408">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="67b85-409">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="67b85-409">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="67b85-410">Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.</span><span class="sxs-lookup"><span data-stu-id="67b85-410">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="67b85-411">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-411">Outlook</span></span>

- <span data-ttu-id="67b85-412">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="67b85-412">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="67b85-413">Solucionamos um problema que fazia com que os usuários experimentassem travamentos no Outlook ao recuperar as configurações da Nuvem.</span><span class="sxs-lookup"><span data-stu-id="67b85-413">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="67b85-414">Foi corrigido um problema que provocava um alinhamento inadequado da caixa de pesquisa no modo de DPI alto.</span><span class="sxs-lookup"><span data-stu-id="67b85-414">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="67b85-415">Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="67b85-415">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="67b85-416">Solucionamos um problema que fazia com que os usuários vissem os e-mails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="67b85-416">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="67b85-417">Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.</span><span class="sxs-lookup"><span data-stu-id="67b85-417">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="67b85-418">Consertamos um problema que podia impedir que os arquivos fossem salvos em um local do WebDAV.</span><span class="sxs-lookup"><span data-stu-id="67b85-418">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="67b85-419">Corrigido um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="67b85-419">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="67b85-420">Solucionamos um problema que fazia com que aplicativos de terceiros não conseguissem enviar emails.</span><span class="sxs-lookup"><span data-stu-id="67b85-420">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="67b85-421">Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão &quot;OK&quot; ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="67b85-421">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="67b85-422">Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="67b85-422">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="67b85-423">Solucionamos um problema que fazia o Outlook sincronizar inesperadamente todos os emails, mesmo quando o controle deslizante de sincronização estivesse definido com uma configuração menor.</span><span class="sxs-lookup"><span data-stu-id="67b85-423">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="67b85-424">Solucionamos um problema que fazia com que a suspensa &quot;De&quot; mostrasse texto branco em um fundo branco para usuários com o Tema Preto.</span><span class="sxs-lookup"><span data-stu-id="67b85-424">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="67b85-425">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.</span><span class="sxs-lookup"><span data-stu-id="67b85-425">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="67b85-426">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="67b85-426">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="67b85-427">Solucionado um problema que fazia com que a opção desativar o realce do item sinalizado deixasse de ser respeitada em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="67b85-427">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="67b85-428">Solucionamos um problema que fazia com que usuários vissem um prompt &quot;As regras neste computador não correspondem às regras no Microsoft Exchange&quot; ao abrir a caixa de diálogo de Regras.</span><span class="sxs-lookup"><span data-stu-id="67b85-428">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="67b85-429">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="67b85-429">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="67b85-430">Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="67b85-430">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="67b85-431">Solucionamos um problema que podia resultar em uma falha ao exibir o mesmo item em várias janelas.</span><span class="sxs-lookup"><span data-stu-id="67b85-431">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="67b85-432">Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="67b85-432">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="67b85-433">Solucionamos um problema que fazia com que os usuários não conseguissem abrir algumas instâncias de itens de calendário recorrentes.</span><span class="sxs-lookup"><span data-stu-id="67b85-433">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="67b85-434">Solucionamos um problema que fazia com que os usuários com caixas de correio em servidores do Exchange 2010 tivessem problemas ao adicionar anexos a itens de calendário.</span><span class="sxs-lookup"><span data-stu-id="67b85-434">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="67b85-435">Solucionamos um problema que fazia com que os usuários tivessem problemas ao responder a mensagens assinadas digitalmente.</span><span class="sxs-lookup"><span data-stu-id="67b85-435">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="67b85-436">Corrigimos um problema que fazia com que o campo Local nas reuniões fosse atualizado inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-436">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="67b85-437">Solucionamos um problema que fazia com que as vírgulas no campo de local de uma reunião se transformassem em pontos-e-vírgulas.</span><span class="sxs-lookup"><span data-stu-id="67b85-437">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="67b85-438">Solucionamos um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após a limpeza.</span><span class="sxs-lookup"><span data-stu-id="67b85-438">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="67b85-439">Solucionamos problemas relacionados a reuniões e compromissos no fuso horário de Brasília.</span><span class="sxs-lookup"><span data-stu-id="67b85-439">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="67b85-440">Foi corrigido um problema que fazia com que emails fossem enviados inesperadamente ao pressionar a tecla &quot;S&quot; após fechar o painel do verificador de acessibilidade.</span><span class="sxs-lookup"><span data-stu-id="67b85-440">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="67b85-441">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="67b85-441">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="67b85-442">Solucionamos um problema que fazia com que suplementos da Web acessassem mensagens com Gerenciamento de Direitos Digitais.</span><span class="sxs-lookup"><span data-stu-id="67b85-442">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="67b85-443">Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="67b85-443">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="67b85-444">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="67b85-444">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="67b85-445">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-445">PowerPoint</span></span>

- <span data-ttu-id="67b85-446">Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.</span><span class="sxs-lookup"><span data-stu-id="67b85-446">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="67b85-447">Solucionamos um problema que pode ter causado uma falha ao usar o menu de contexto em comentários de PPT herdados.</span><span class="sxs-lookup"><span data-stu-id="67b85-447">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="67b85-448">Projeto</span><span class="sxs-lookup"><span data-stu-id="67b85-448">Project</span></span>

- <span data-ttu-id="67b85-449">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="67b85-449">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="67b85-450">Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="67b85-450">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="67b85-451">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="67b85-451">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="67b85-452">Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="67b85-452">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="67b85-453">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-453">Word</span></span>

- <span data-ttu-id="67b85-454">Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.</span><span class="sxs-lookup"><span data-stu-id="67b85-454">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="67b85-455">O organizador de blocos de construção pode exibir um alerta inválido: &quot;Você modificou estilos, blocos de construção&quot;.</span><span class="sxs-lookup"><span data-stu-id="67b85-455">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="67b85-456">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="67b85-456">Office Suite</span></span>

- <span data-ttu-id="67b85-457">Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.</span><span class="sxs-lookup"><span data-stu-id="67b85-457">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="67b85-458">Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.</span><span class="sxs-lookup"><span data-stu-id="67b85-458">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="67b85-459">Correção de um bug na configuração de Data Limite de Atualização ODT e GPO, em que o prazo relativo só funcionava na primeira vez que era definido. A correção permite definir a data limite relativa nas atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="67b85-459">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="67b85-460">Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="67b85-460">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="67b85-461">Foi corrigido um problema em que, quando vários documentos da mesma biblioteca do SharePoint estivessem abertos no Word/Excel/PowerPoint, somente o primeiro documento aberto era verificado quanto à conformidade com Políticas.</span><span class="sxs-lookup"><span data-stu-id="67b85-461">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a><span data-ttu-id="67b85-463">Versão 1908: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="67b85-463">Version 1908: February 11</span></span>
<span data-ttu-id="67b85-464">*Versão 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="67b85-464">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="67b85-465">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-467">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-467">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="67b85-468">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-468">Excel</span></span>

- <span data-ttu-id="67b85-469">Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.</span><span class="sxs-lookup"><span data-stu-id="67b85-469">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="67b85-470">Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.</span><span class="sxs-lookup"><span data-stu-id="67b85-470">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="67b85-471">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="67b85-471">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="67b85-472">Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.</span><span class="sxs-lookup"><span data-stu-id="67b85-472">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="67b85-473">Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.</span><span class="sxs-lookup"><span data-stu-id="67b85-473">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="67b85-474">Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.</span><span class="sxs-lookup"><span data-stu-id="67b85-474">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="67b85-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-475">Outlook</span></span>

- <span data-ttu-id="67b85-476">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="67b85-476">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="67b85-477">Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.</span><span class="sxs-lookup"><span data-stu-id="67b85-477">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="67b85-478">Solucionado um problema que fazia com que os usuários experimentassem um travamento na tela Carregando perfil ao iniciar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="67b85-478">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="67b85-479">Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.</span><span class="sxs-lookup"><span data-stu-id="67b85-479">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="67b85-480">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="67b85-480">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="67b85-481">[Aqui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.</span><span class="sxs-lookup"><span data-stu-id="67b85-481">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="67b85-482">Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.</span><span class="sxs-lookup"><span data-stu-id="67b85-482">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="67b85-483">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-483">PowerPoint</span></span>

- <span data-ttu-id="67b85-484">Melhorou um cenário de copiar e colar Copiando a Forma no slide do powerpoint e colando em outro slide em um loop poderia falhar, com exceção.</span><span class="sxs-lookup"><span data-stu-id="67b85-484">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="67b85-485">Corrigido um problema que estava causando um desempenho mais lento entre os usuários da colaboração.</span><span class="sxs-lookup"><span data-stu-id="67b85-485">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="67b85-486">Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.</span><span class="sxs-lookup"><span data-stu-id="67b85-486">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="67b85-487">Corrigimos um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="67b85-487">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="67b85-488">Project</span><span class="sxs-lookup"><span data-stu-id="67b85-488">Project</span></span>

- <span data-ttu-id="67b85-489">Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.</span><span class="sxs-lookup"><span data-stu-id="67b85-489">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="67b85-490">Word</span><span class="sxs-lookup"><span data-stu-id="67b85-490">Word</span></span>

- <span data-ttu-id="67b85-491">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="67b85-491">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="67b85-492">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="67b85-492">Office Suite</span></span>

- <span data-ttu-id="67b85-493">Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.</span><span class="sxs-lookup"><span data-stu-id="67b85-493">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a><span data-ttu-id="67b85-495">Versão 1908:14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="67b85-495">Version 1908: January 14</span></span>
<span data-ttu-id="67b85-496">*Versão 1908 (Build 11929,20562)*</span><span class="sxs-lookup"><span data-stu-id="67b85-496">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="67b85-497">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="67b85-497">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="67b85-499">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="67b85-499">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="67b85-500">Excel</span><span class="sxs-lookup"><span data-stu-id="67b85-500">Excel</span></span>

- <span data-ttu-id="67b85-501">A dica de tecla holandesa para o título do documento foi alterada para Alt-G.</span><span class="sxs-lookup"><span data-stu-id="67b85-501">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="67b85-502">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="67b85-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="67b85-503">Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.</span><span class="sxs-lookup"><span data-stu-id="67b85-503">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="67b85-504">Outlook</span><span class="sxs-lookup"><span data-stu-id="67b85-504">Outlook</span></span>

- <span data-ttu-id="67b85-505">Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="67b85-505">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="67b85-506">Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.</span><span class="sxs-lookup"><span data-stu-id="67b85-506">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="67b85-507">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="67b85-507">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="67b85-508">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="67b85-508">PowerPoint</span></span>

- <span data-ttu-id="67b85-509">Corrigimos um problema que poderia criar mestres ao copiar um slide de uma apresentação para outra.</span><span class="sxs-lookup"><span data-stu-id="67b85-509">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="67b85-510">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada</span><span class="sxs-lookup"><span data-stu-id="67b85-510">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="67b85-511">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="67b85-511">Office Suite</span></span>

- <span data-ttu-id="67b85-512">Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado.</span><span class="sxs-lookup"><span data-stu-id="67b85-512">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="67b85-513">Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.</span><span class="sxs-lookup"><span data-stu-id="67b85-513">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="67b85-514">Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.</span><span class="sxs-lookup"><span data-stu-id="67b85-514">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="67b85-516">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="67b85-516">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

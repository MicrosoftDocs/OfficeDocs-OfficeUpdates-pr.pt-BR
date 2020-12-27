---
title: Notas de Versão para o Canal Beta
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece a lista mais recente de novos recursos, correções ou problemas conhecidos para o público-alvo do Programa Windows Insider − Modo Rápido.
ms.openlocfilehash: 6b42dcee02fa315647a1176bda1d581833ca5211
ms.sourcegitcommit: 9a0952ac6d6c19231b3f4148a69d3260300ae78a
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/25/2020
ms.locfileid: "49733204"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="51b68-103">Notas de Versão para o Canal Beta</span><span class="sxs-lookup"><span data-stu-id="51b68-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="51b68-104">Este artigo contém notas de versão para compilações do Canal Beta para o Word, Excel, PowerPoint, Outlook, Access e Project para a área de trabalho do Windows.</span><span class="sxs-lookup"><span data-stu-id="51b68-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="51b68-105">Toda semana, destacaremos novos recursos interessantes, correções importantes e quaisquer problemas significativos sobre os quais desejamos informá-lo.</span><span class="sxs-lookup"><span data-stu-id="51b68-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="51b68-106">Em geral, disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Beta ao longo do tempo.</span><span class="sxs-lookup"><span data-stu-id="51b68-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="51b68-107">Isso nos permite garantir que tudo esteja funcionando bem antes de liberarmos o recurso para um público maior.</span><span class="sxs-lookup"><span data-stu-id="51b68-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="51b68-108">Portanto, caso você não veja algo descrito abaixo, não se preocupe.</span><span class="sxs-lookup"><span data-stu-id="51b68-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="51b68-109">Estamos fazendo algumas alterações nos canais de atualização para os Aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="51b68-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="51b68-110">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="51b68-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="51b68-111">As notas de versão são publicadas semanalmente e podem ser uma compilação de várias compilações.</span><span class="sxs-lookup"><span data-stu-id="51b68-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="51b68-112">A data de publicação das notas de versão pode não corresponder com a data de lançamento da compilação atual.</span><span class="sxs-lookup"><span data-stu-id="51b68-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NÃO REMOVA)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

## <a name="version-2101-december-25"></a><span data-ttu-id="51b68-115">Versão 2101: 25 de dezembro</span><span class="sxs-lookup"><span data-stu-id="51b68-115">Version 2101: December 25</span></span>
<span data-ttu-id="51b68-116">*Versão 2101 (Build 13617.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-116">*Version 2101 (Build 13617.20002)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-118">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-119">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-119">Excel</span></span>

- <span data-ttu-id="51b68-120">Atualize para que as configurações dos separadores decimais e de milhares sejam carregadas ao copiar um gráfico do Excel e colá-lo no Word</span><span class="sxs-lookup"><span data-stu-id="51b68-120">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="51b68-121">Correção de um problema em que o Excel fechava inesperadamente ao abrir arquivos UNC com atributos de arquivo inválidos (hora de criação, tempo de modificação, etc.)</span><span class="sxs-lookup"><span data-stu-id="51b68-121">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="51b68-122">Essa alteração corrige um problema relacionado à alteração de cores de contorno das imagens SVG.</span><span class="sxs-lookup"><span data-stu-id="51b68-122">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-123">Outlook</span></span>

- <span data-ttu-id="51b68-124">Consertamos um problema que fazia com que os usuários não conseguissem saber quanto tempo queriam permitir o acesso ao iniciar uma mala direta no Word, o que resultava em um excesso de solicitações.</span><span class="sxs-lookup"><span data-stu-id="51b68-124">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="51b68-125">Consertamos um problema que provocava um fechamento inesperado do Outlook para usuários de suplementos baseados em resgate.</span><span class="sxs-lookup"><span data-stu-id="51b68-125">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-126">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-126">PowerPoint</span></span>

- <span data-ttu-id="51b68-127">Essa alteração corrige um problema relacionado à alteração de cores de contorno das imagens SVG.</span><span class="sxs-lookup"><span data-stu-id="51b68-127">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-128">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-128">Word</span></span>

- <span data-ttu-id="51b68-129">Essa alteração corrige um problema relacionado à alteração de cores de contorno das imagens SVG.</span><span class="sxs-lookup"><span data-stu-id="51b68-129">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="51b68-130">Corrige um problema em que a caixa de resposta de um cartão de comentário está fora da tela.</span><span class="sxs-lookup"><span data-stu-id="51b68-130">Fixes an issue where the reply box on a comment card is off the screen.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2101-december-18"></a><span data-ttu-id="51b68-132">Versão 2101: 18 de dezembro</span><span class="sxs-lookup"><span data-stu-id="51b68-132">Version 2101: December 18</span></span>
<span data-ttu-id="51b68-133">*Versão 2101 (Compilação 13610.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-133">*Version 2101 (Build 13610.20002)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-135">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-135">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-136">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-136">Excel</span></span>

- <span data-ttu-id="51b68-137">**Enviar dados de auditoria sobre rotulagem de confidencialidade para administradores M365:** Quando os usuários aplicarem, alterarem ou removerem as etiquetas de confidencialidade em seus documentos e emails, o Office enviará os dados de auditoria para o back-end de auditoria M365 para que os administradores possam ver.</span><span class="sxs-lookup"><span data-stu-id="51b68-137">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="51b68-138">Esta é uma funcionalidade silenciosa (sem IU) para benefício do administrador.</span><span class="sxs-lookup"><span data-stu-id="51b68-138">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-139">Outlook</span></span>

- <span data-ttu-id="51b68-140">**Enviar dados de auditoria sobre rotulagem de confidencialidade para administradores M365:** Quando os usuários aplicarem, alterarem ou removerem as etiquetas de confidencialidade em seus documentos e emails, o Office enviará os dados de auditoria para o back-end de auditoria M365 para que os administradores possam ver.</span><span class="sxs-lookup"><span data-stu-id="51b68-140">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="51b68-141">Esta é uma funcionalidade silenciosa (sem IU) para benefício do administrador.</span><span class="sxs-lookup"><span data-stu-id="51b68-141">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-142">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-142">PowerPoint</span></span>

- <span data-ttu-id="51b68-143">**Enviar dados de auditoria sobre rotulagem de confidencialidade para administradores M365:** Quando os usuários aplicarem, alterarem ou removerem as etiquetas de confidencialidade em seus documentos e emails, o Office enviará os dados de auditoria para o back-end de auditoria M365 para que os administradores possam ver.</span><span class="sxs-lookup"><span data-stu-id="51b68-143">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="51b68-144">Esta é uma funcionalidade silenciosa (sem IU) para benefício do administrador.</span><span class="sxs-lookup"><span data-stu-id="51b68-144">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-145">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-145">Word</span></span>

- <span data-ttu-id="51b68-146">**Enviar dados de auditoria sobre rotulagem de confidencialidade para administradores M365:** Quando os usuários aplicarem, alterarem ou removerem as etiquetas de confidencialidade em seus documentos e emails, o Office enviará os dados de auditoria para o back-end de auditoria M365 para que os administradores possam ver.</span><span class="sxs-lookup"><span data-stu-id="51b68-146">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="51b68-147">Esta é uma funcionalidade silenciosa (sem IU) para benefício do administrador.</span><span class="sxs-lookup"><span data-stu-id="51b68-147">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-150">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-150">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-151">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-151">Excel</span></span>

- <span data-ttu-id="51b68-152">Melhorou o desempenho ao aplicar estilos de formatação a tabelas dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="51b68-152">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-153">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-153">Outlook</span></span>

- <span data-ttu-id="51b68-154">Corrigimos um problema que fazia com que os usuários não conseguissem selecionar mais de uma categoria para pesquisar.</span><span class="sxs-lookup"><span data-stu-id="51b68-154">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="51b68-155">Corrigimos um problema que fazia com que a hora de início de alguns itens do calendário mudassem inesperadamente quando o evento era copiado de outro compromisso.</span><span class="sxs-lookup"><span data-stu-id="51b68-155">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


### <a name="project"></a><span data-ttu-id="51b68-156">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="51b68-156">Project</span></span>

- <span data-ttu-id="51b68-157">Resolvemos um problema em que os usuários abrem projetos que supostamente foram salvos com informações atualizadas, mas descobrem que as atualizações estão em falta.</span><span class="sxs-lookup"><span data-stu-id="51b68-157">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-158">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-158">Word</span></span>

- <span data-ttu-id="51b68-159">Corrija a animação ao digitar na parte inferior de um cartão de comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-159">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="51b68-160">Corrigimos um problema em que o Word trava ao salvar o documento em PDF com texto oculto.</span><span class="sxs-lookup"><span data-stu-id="51b68-160">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2101-december-11"></a><span data-ttu-id="51b68-162">Versão 2101: 11 de dezembro</span><span class="sxs-lookup"><span data-stu-id="51b68-162">Version 2101: December 11</span></span>
<span data-ttu-id="51b68-163">*Versão 2101 (Build 13604.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-163">*Version 2101 (Build 13604.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-165">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-165">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-166">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-166">Outlook</span></span>

- <span data-ttu-id="51b68-167">**As configurações do Outlook na nuvem:** escolha as configurações do Outlook para Windows, como Respostas Automáticas, Caixa de Entrada Destaques, Privacidade, e acesse-as em qualquer PC.</span><span class="sxs-lookup"><span data-stu-id="51b68-167">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-168">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-168">Word</span></span>

- <span data-ttu-id="51b68-169">**Melhor colaboração com comentários modernos:** Adicionar comentários a objetos, @menção colegas e resolver encadeamentos de comentários para obter uma melhor experiência de colaboração.</span><span class="sxs-lookup"><span data-stu-id="51b68-169">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="51b68-170">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-170">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br /><span data-ttu-id="51b68-171">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/modern-commenting-in-word)</span><span class="sxs-lookup"><span data-stu-id="51b68-171">See details in [blog post](https://insider.office.com/pt-BR/blog/modern-commenting-in-word)</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-174">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-174">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-175">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-175">Excel</span></span>

- <span data-ttu-id="51b68-176">Corrigido um problema em que o Excel mostrava incorretamente uma barra de mensagens de que uma nova versão do arquivo está disponível e forçava o usuário a salvar suas alterações em uma cópia da pasta de trabalho ou descartar suas alterações.</span><span class="sxs-lookup"><span data-stu-id="51b68-176">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="51b68-177">Corrigido um problema com a troca de separadores após uma chamada Selection.Parent.Copy.</span><span class="sxs-lookup"><span data-stu-id="51b68-177">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-178">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-178">Outlook</span></span>

- <span data-ttu-id="51b68-179">Solucionado um problema que provocou mensagens de texto S/MIME sem formatação se tornarem truncadas ao enviar.</span><span class="sxs-lookup"><span data-stu-id="51b68-179">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-180">PowerPoint</span></span>

- <span data-ttu-id="51b68-181">Esta alteração soluciona um problema com a repetição da reprodução de vídeos de fundo na apresentação de Slides.</span><span class="sxs-lookup"><span data-stu-id="51b68-181">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="51b68-182">Corrigimos um problema em que o comando de tamanho de fonte, adicionado ao QAT, completava automaticamente para o tamanho de fonte definido mais próximo ao atualizá-lo.</span><span class="sxs-lookup"><span data-stu-id="51b68-182">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-183">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-183">Word</span></span>

- <span data-ttu-id="51b68-184">Corrigimos um problema de exclusão de comentários modernos em um controle de conteúdo marcado como não editável.</span><span class="sxs-lookup"><span data-stu-id="51b68-184">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DE ERRO)

## <a name="version-2012-december-04"></a><span data-ttu-id="51b68-186">Versão 2012: 04 de dezembro</span><span class="sxs-lookup"><span data-stu-id="51b68-186">Version 2012: December 04</span></span>
<span data-ttu-id="51b68-187">*Versão 2012 (Build 13530.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-187">*Version 2012 (Build 13530.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-189">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-189">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-190">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-190">Outlook</span></span>

- <span data-ttu-id="51b68-191">**Aumente o tempo entre as reuniões consecutivas:** Dê aos participantes tempo para recuperar o fôlego ou viajar entre os locais, configurando as reuniões para começarem 5-10 minutos atrasado por padrão.</span><span class="sxs-lookup"><span data-stu-id="51b68-191">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="51b68-192">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-192">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a><span data-ttu-id="51b68-193">Visio</span><span class="sxs-lookup"><span data-stu-id="51b68-193">Visio</span></span>

- <span data-ttu-id="51b68-194">**Novos estênceis e formas do Azure:** Nós adicionamos muitos outros estênceis para ajudá-lo a criar diagramas do Azure atualizados.</span><span class="sxs-lookup"><span data-stu-id="51b68-194">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="51b68-195">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-195">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-198">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-199">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-199">Excel</span></span>

- <span data-ttu-id="51b68-200">Corrigido um problema em que a edição em idiomas que exigem o uso de IME se comportava mal durante a edição no modo de substituição.</span><span class="sxs-lookup"><span data-stu-id="51b68-200">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="51b68-201">Corrigido um hiperlink quebrado para um artigo de ajuda em um alerta caso o Salvamento automático fosse desabilitado.</span><span class="sxs-lookup"><span data-stu-id="51b68-201">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="51b68-202">Corrigido um problema em que o Excel fechava inesperadamente ao copiar e colar dados na exibição de fórmula.</span><span class="sxs-lookup"><span data-stu-id="51b68-202">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-203">Outlook</span></span>

- <span data-ttu-id="51b68-204">Corrigimos um problema que fazia com que os SmartLinks perdessem a formatação quando salvos em rascunhos.</span><span class="sxs-lookup"><span data-stu-id="51b68-204">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


### <a name="project"></a><span data-ttu-id="51b68-205">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="51b68-205">Project</span></span>

- <span data-ttu-id="51b68-206">Corrigido um problema em que abrir um projeto com muitos recursos demorava muito.</span><span class="sxs-lookup"><span data-stu-id="51b68-206">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="51b68-207">Corrigido um problema em que projetos específicos podiam ser abertos se houvesse um problema com o arquivo de projeto em uma parte específica da carga.</span><span class="sxs-lookup"><span data-stu-id="51b68-207">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-208">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-208">Word</span></span>

- <span data-ttu-id="51b68-209">Colar como texto sem formatação é geralmente preferível comparado a colar como rich text.</span><span class="sxs-lookup"><span data-stu-id="51b68-209">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="51b68-210">Este correção de menu de contexto permite que o usuário cole como texto sem formatação.</span><span class="sxs-lookup"><span data-stu-id="51b68-210">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="51b68-211">Caso contrário, o usuário teria que copiar para um editor de texto simples como o Bloco de notas e, em seguida, copiar do Bloco de notas para o aplicativo de destino desejado</span><span class="sxs-lookup"><span data-stu-id="51b68-211">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2012-november-27"></a><span data-ttu-id="51b68-213">Versão 2012: 27 de novembro</span><span class="sxs-lookup"><span data-stu-id="51b68-213">Version 2012: November 27</span></span>
<span data-ttu-id="51b68-214">*Versão 2012 (Build 13519.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-214">*Version 2012 (Build 13519.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-216">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-216">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-217">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-217">Excel</span></span>

- <span data-ttu-id="51b68-218">Isso corrige um problema em que o Power Pivot não conseguia importar corretamente um arquivo de texto delimitado por tabulação.</span><span class="sxs-lookup"><span data-stu-id="51b68-218">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-219">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-219">Outlook</span></span>

- <span data-ttu-id="51b68-220">Corrigimos um problema que fazia com que os usuários tivessem alguns problemas ao enviar email do Outlook de outros aplicativos além do Outlook.</span><span class="sxs-lookup"><span data-stu-id="51b68-220">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-221">PowerPoint</span></span>

- <span data-ttu-id="51b68-222">Essa alteração resolve um problema relacionado a tempos-limite durante a análise de tinta.</span><span class="sxs-lookup"><span data-stu-id="51b68-222">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="51b68-223">Essa alteração corrige um erro gramatical na interface de usuário Criar um GIF animado.</span><span class="sxs-lookup"><span data-stu-id="51b68-223">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="51b68-224">Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-224">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="51b68-225">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="51b68-225">Project</span></span>

- <span data-ttu-id="51b68-226">Corrigido um problema em que os usuários podem ver várias atribuições não atribuídas associadas a uma tarefa.</span><span class="sxs-lookup"><span data-stu-id="51b68-226">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="51b68-227">Corrigido um problema em que em grandes projetos pode ser muito lento inserir um nome de tarefa.</span><span class="sxs-lookup"><span data-stu-id="51b68-227">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2012-november-20"></a><span data-ttu-id="51b68-229">Versão 2012: 20 de novembro</span><span class="sxs-lookup"><span data-stu-id="51b68-229">Version 2012: November 20</span></span>
<span data-ttu-id="51b68-230">*Versão 2012 (Build 13512.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-230">*Version 2012 (Build 13512.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-232">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-232">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-233">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-233">Outlook</span></span>

- <span data-ttu-id="51b68-234">**Todas as reuniões online:** facilite o agendamento de reuniões online com uma nova configuração para tornar todas as reuniões online por padrão.</span><span class="sxs-lookup"><span data-stu-id="51b68-234">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-235">PowerPoint</span></span>

- <span data-ttu-id="51b68-236">**Biblioteca de vídeo:** Eleve seus documentos com uma biblioteca de vídeo de royalties livres e gratuitas selecionadas disponíveis no aplicativo</span><span class="sxs-lookup"><span data-stu-id="51b68-236">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-239">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-239">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="51b68-240">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-240">PowerPoint</span></span>

- <span data-ttu-id="51b68-241">Corrigido um problema em que o indicador de presença de um coautoria desconhecido não é totalmente atualizado, uma vez que mais informações sobre o coautoria estão disponíveis.</span><span class="sxs-lookup"><span data-stu-id="51b68-241">Fixed an issue where the presence indicator for an unknown coauthor does not get completely refreshed, once more information about the coauthor is available.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-242">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-242">Word</span></span>

- <span data-ttu-id="51b68-243">Corrigimos um problema em que o Word trava ao salvar o documento em PDF com texto oculto.</span><span class="sxs-lookup"><span data-stu-id="51b68-243">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DE ERRO)

## <a name="version-2012-november-13"></a><span data-ttu-id="51b68-245">Versão 2012: 13 de novembro</span><span class="sxs-lookup"><span data-stu-id="51b68-245">Version 2012: November 13</span></span>
<span data-ttu-id="51b68-246">*Versão 2012 (Criação 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="51b68-246">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-248">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-248">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-249">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-249">Excel</span></span>

- <span data-ttu-id="51b68-250">Corrigimos um problema em que o comando Inserir Objeto não mostra o ícone correto ao inserir um arquivo na pasta de sincronização local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="51b68-250">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-251">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-251">Outlook</span></span>

- <span data-ttu-id="51b68-252">Resolvemos um problema que fez com que o campo Para: ficasse em branco nos relatórios de status da tarefa.</span><span class="sxs-lookup"><span data-stu-id="51b68-252">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-253">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-253">PowerPoint</span></span>

- <span data-ttu-id="51b68-254">Resolvemos um problema de VBA em que Slide.Shapes.AddMediaObject2 travava com formatos de vídeo antigos (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="51b68-254">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="51b68-255">Projeto</span><span class="sxs-lookup"><span data-stu-id="51b68-255">Project</span></span>

- <span data-ttu-id="51b68-256">Resolvemos um problema em que não foi possível eliminar as dependências dos produtos entregues se o site do SharePoint ao qual o produto entregue estava associado não existisse mais.</span><span class="sxs-lookup"><span data-stu-id="51b68-256">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="51b68-257">Resolvemos um problema em que os usuários abrem projetos que supostamente foram salvos com informações atualizadas, mas descobrem que as atualizações estão em falta.</span><span class="sxs-lookup"><span data-stu-id="51b68-257">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-258">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-258">Word</span></span>

- <span data-ttu-id="51b68-259">Resolvemos um problema relacionado a imagens que ficavam borradas ao fazer zoom.</span><span class="sxs-lookup"><span data-stu-id="51b68-259">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="51b68-260">Consertamos um problema em que os hiperlinks longos estavam truncados.</span><span class="sxs-lookup"><span data-stu-id="51b68-260">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DE ERRO)

## <a name="version-2012-november-06"></a><span data-ttu-id="51b68-262">Versão 2012: 06 de novembro</span><span class="sxs-lookup"><span data-stu-id="51b68-262">Version 2012: November 06</span></span>
<span data-ttu-id="51b68-263">*Versão 2012 (Build 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-263">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-265">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-265">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-266">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-266">Excel</span></span>

- <span data-ttu-id="51b68-267">**Reexibir várias páginas ao mesmo tempo:** não há mais necessidade de exibir uma página por vez - exibir várias páginas ocultas de uma vez.</span><span class="sxs-lookup"><span data-stu-id="51b68-267">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="51b68-268">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-268">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="51b68-269">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-269">Outlook</span></span>

- <span data-ttu-id="51b68-270">**Mesma assinatura, todos os dispositivos:** sua assinatura é armazenada na nuvem.</span><span class="sxs-lookup"><span data-stu-id="51b68-270">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="51b68-271">Crie-o uma vez e use-o em todos os lugares onde usar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="51b68-271">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-274">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-274">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-275">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-275">Excel</span></span>

- <span data-ttu-id="51b68-276">Corrigimos um problema em que alguns elementos da faixa de opções não eram localizados em Chinês Simplificado.</span><span class="sxs-lookup"><span data-stu-id="51b68-276">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="51b68-277">Corrigimos um problema em que o Excel fechava inesperadamente durante a atualização.</span><span class="sxs-lookup"><span data-stu-id="51b68-277">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-278">Outlook</span></span>

- <span data-ttu-id="51b68-279">Corrigimos um problema de falha na adição de um anexo a uma mensagem aberta a partir de um arquivo zip.</span><span class="sxs-lookup"><span data-stu-id="51b68-279">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-2011-october-30"></a><span data-ttu-id="51b68-281">Versão 2011: 30 de outubro</span><span class="sxs-lookup"><span data-stu-id="51b68-281">Version 2011: October 30</span></span>
<span data-ttu-id="51b68-282">*Versão 2011 (Build 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="51b68-282">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-284">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-284">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-285">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-285">Excel</span></span>

- <span data-ttu-id="51b68-286">**Diálogos de Formatação Condicional aprimorados:** os diálogos de Formatação Condicional agora são redimensionáveis ​​e agora podem duplicar a regra com um único clique.</span><span class="sxs-lookup"><span data-stu-id="51b68-286">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="51b68-287">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-287">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-290">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-290">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-291">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-291">Access</span></span>

- <span data-ttu-id="51b68-292">Corrigimos um problema em que ao usar o DAO em aplicativos não pertencentes ao Office fazia com que o aplicativo fechasse inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-292">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="51b68-293">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-293">Excel</span></span>

- <span data-ttu-id="51b68-294">Corrigido um problema com o Power Pivot ao usar uma conexão com um banco de dados do Oracle.</span><span class="sxs-lookup"><span data-stu-id="51b68-294">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="51b68-295">Corrigimos um problema em que o Excel fechava inesperadamente quando o processo de cálculo MTR e atualização do Objeto de Política de Grupo (por exemplo, por meio da Atualização remota da Política de Grupo) era acionado.</span><span class="sxs-lookup"><span data-stu-id="51b68-295">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="51b68-296">Essa alteração corrige um bug, que causa uma falha no Excel ao tentar carregar um arquivo atomsvc.</span><span class="sxs-lookup"><span data-stu-id="51b68-296">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="51b68-297">Corrigimos um problema em que o Word parecia travar ao inserir a pasta de trabalho do Excel em um documento do Word.</span><span class="sxs-lookup"><span data-stu-id="51b68-297">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-298">Outlook</span></span>

- <span data-ttu-id="51b68-299">Corrigimos um problema em que o proprietário da caixa de correio não conseguia gerenciar a permissão Compartilhada para seu próprio Calendário porque a opção estava esmaecida.</span><span class="sxs-lookup"><span data-stu-id="51b68-299">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="51b68-300">Corrigimos um problema em que salvar modelos de email como .OFT alterava os caracteres Chineses para pontos de interrogação.</span><span class="sxs-lookup"><span data-stu-id="51b68-300">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="51b68-301">Corrigimos um problema em que o Outlook não conseguia criar uma mensagem com permissão restrita.</span><span class="sxs-lookup"><span data-stu-id="51b68-301">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="51b68-302">Resolvido um problema que fazia com que o Outlook parasse de funcionar esporadicamente ao adicionar ou salvar anexos.</span><span class="sxs-lookup"><span data-stu-id="51b68-302">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-303">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-303">PowerPoint</span></span>

- <span data-ttu-id="51b68-304">Corrigimos um problema em que as linhas de grade eram deslocadas dos slides ao fechar o painel de design.</span><span class="sxs-lookup"><span data-stu-id="51b68-304">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="51b68-305">Corrigimos um problema em que a barra de rolagem no slide começava a se ajustar depois de parar a gravação da tela com o painel de seleção aberto.</span><span class="sxs-lookup"><span data-stu-id="51b68-305">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="51b68-306">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="51b68-306">Project</span></span>

- <span data-ttu-id="51b68-307">Corrigido um problema em que, ao salvar um projeto do PWA em um arquivo mpp local, o ProjectBeforeTaskChangeEvent disparava para dados que não foram realmente alterados pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="51b68-307">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="51b68-308">Corrigido um problema em que os compromissos de recursos procuravam um recurso por nome em vez de GUID, o que causaria problemas se houvesse vários recursos com o mesmo nome.</span><span class="sxs-lookup"><span data-stu-id="51b68-308">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-309">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-309">Word</span></span>

- <span data-ttu-id="51b68-310">Corrigimos um problema em que clicar na dica de comentário não reduzia o zoom para mostrar o cartão de comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-310">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="51b68-311">Corrigimos um problema de layout que poderia ter mudado a linha entre as colunas.</span><span class="sxs-lookup"><span data-stu-id="51b68-311">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="51b68-312">Corrigimos um problema em que o Word parecia travar ao inserir a pasta de trabalho do Excel em um documento do Word.</span><span class="sxs-lookup"><span data-stu-id="51b68-312">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="51b68-313">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-313">Office Suite</span></span>

- <span data-ttu-id="51b68-314">Corrigimos um problema na Ferramenta de Implantação do Office, em que a configuração estava falhando ao usar o recurso RemoveMSI com o produto do Office 2007 "Relatório de Erros do Aplicativo da Microsoft".</span><span class="sxs-lookup"><span data-stu-id="51b68-314">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-2011-october-23"></a><span data-ttu-id="51b68-316">Versão 2011: 23 de outubro</span><span class="sxs-lookup"><span data-stu-id="51b68-316">Version 2011: October 23</span></span>
<span data-ttu-id="51b68-317">*Versão 2011 (Compilação 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-317">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-319">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-319">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="51b68-320">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-320">PowerPoint</span></span>

- <span data-ttu-id="51b68-321">**Ensaie a apresentação com o Pré-visualizador do PowerPoint:** Obtenha feedback sobre coisas que ajudam a manter o público envolvido - como ritmo, argumento de venda, palavras de preenchimento, frases confidenciais e muito mais.</span><span class="sxs-lookup"><span data-stu-id="51b68-321">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="51b68-322">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-322">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-325">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-325">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-326">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-326">Access</span></span>

- <span data-ttu-id="51b68-327">Corrigimos um problema em que alguns usuários viam o erro "recurso do sistema excedido" quando tentavam exportar uma consulta de sua pasta OneDrive sincronizada.</span><span class="sxs-lookup"><span data-stu-id="51b68-327">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="51b68-328">Corrigimos um problema em que a troca 'automática' entre janelas de formulário estava mudando para outro formulário.</span><span class="sxs-lookup"><span data-stu-id="51b68-328">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-329">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-329">Outlook</span></span>

- <span data-ttu-id="51b68-330">Corrigimos um problema ao colar um URL copiado do local da reunião para outro lugar (como um navegador), o URL contém um ponto e vírgula no final.</span><span class="sxs-lookup"><span data-stu-id="51b68-330">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-331">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-331">PowerPoint</span></span>

- <span data-ttu-id="51b68-332">Corrigimos um problema ao duplicar a apresentação de slides para o monitor secundário. A apresentação de slides pode se esconder atrás de outra janela.</span><span class="sxs-lookup"><span data-stu-id="51b68-332">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-333">Projeto</span><span class="sxs-lookup"><span data-stu-id="51b68-333">Project</span></span>

- <span data-ttu-id="51b68-334">Corrigido um problema em que o Microsoft Project podia ser encerrado inesperadamente ao abrir arquivos em que os contornos dos recursos foram especificados de uma determinada maneira.</span><span class="sxs-lookup"><span data-stu-id="51b68-334">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-335">Palavra</span><span class="sxs-lookup"><span data-stu-id="51b68-335">Word</span></span>

- <span data-ttu-id="51b68-336">Corrigimos um problema no Controle de Alterações que às vezes a abertura de um documento do Word exibia uma caixa de diálogo de erro.</span><span class="sxs-lookup"><span data-stu-id="51b68-336">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="51b68-337">Corrigimos um problema de impressão quando rótulo de confidencialidade com marcas d'água são aplicadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-337">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-2011-october-16"></a><span data-ttu-id="51b68-339">Versão 2011: 16 de outubro</span><span class="sxs-lookup"><span data-stu-id="51b68-339">Version 2011: October 16</span></span>
<span data-ttu-id="51b68-340">*Versão 2011 (Build 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-340">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-342">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-342">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-343">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-343">Excel</span></span>

- <span data-ttu-id="51b68-344">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-344">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="51b68-345">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-345">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="51b68-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-346">Outlook</span></span>

- <span data-ttu-id="51b68-347">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-347">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="51b68-348">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-348">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="51b68-349">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-349">PowerPoint</span></span>

- <span data-ttu-id="51b68-350">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-350">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="51b68-351">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-351">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="51b68-352">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-352">Word</span></span>

- <span data-ttu-id="51b68-353">**Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-353">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="51b68-354">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-354">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-357">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-357">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-358">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-358">Outlook</span></span>

- <span data-ttu-id="51b68-359">Consertamos um problema em que os usuários não conseguiram excluir os compromissos no Calendário dos grupos do Microsoft 365 na autenticação básica.</span><span class="sxs-lookup"><span data-stu-id="51b68-359">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="51b68-360">Consertamos um problema em que o Outlook falhou ao carregar o cache de apelidos.</span><span class="sxs-lookup"><span data-stu-id="51b68-360">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-361">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-361">PowerPoint</span></span>

- <span data-ttu-id="51b68-362">Consertamos um problema em que o ícone do espaço reservado para conteúdo ao lado de imagens não tinha dica de ferramenta.</span><span class="sxs-lookup"><span data-stu-id="51b68-362">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="51b68-363">Consertamos um problema em que o modo de exibição de apresentação de slides, mostrado pelo arquivo pptsx, permite a captura de tela do documento protegido por IRM.</span><span class="sxs-lookup"><span data-stu-id="51b68-363">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2011-october-09"></a><span data-ttu-id="51b68-365">Versão 2011: 09 de outubro</span><span class="sxs-lookup"><span data-stu-id="51b68-365">Version 2011: October 09</span></span>
<span data-ttu-id="51b68-366">*Versão 2011 (Build 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-366">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-368">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-368">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-369">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-369">Excel</span></span>

- <span data-ttu-id="51b68-370">**Criar fluxos de dados do Power Platform a partir de consultas:** Agora você pode exportar suas consultas para modelos do Power Query que podem ser usados para criar novos fluxos de dados do Power Platform</span><span class="sxs-lookup"><span data-stu-id="51b68-370">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-371">PowerPoint</span></span>

- <span data-ttu-id="51b68-372">**Exportar GIF animado em um intervalo:** selecione um intervalo de slides ao exportar para GIF animado</span><span class="sxs-lookup"><span data-stu-id="51b68-372">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="51b68-373">**Crie GIFs com Telas de Fundo Transparentes:** Ao exportar para um GIF animado, uma nova opção permitirá que você torne a tela de fundo transparente.</span><span class="sxs-lookup"><span data-stu-id="51b68-373">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-376">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-376">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-377">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-377">Excel</span></span>

- <span data-ttu-id="51b68-378">Consertamos um problema em que o nome do arquivo não era alterado após uma operação Salvar Como com suplementos COM habilitados.</span><span class="sxs-lookup"><span data-stu-id="51b68-378">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="51b68-379">Corrigimos um problema em que quando o Salvamento Automático falhava com uma mensagem de erro incorreta/enganosa quando havia uma definição de medida incorreta no modelo de dados do Excel.</span><span class="sxs-lookup"><span data-stu-id="51b68-379">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="51b68-380">Consertamos um problema em que o zoom e a área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="51b68-380">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-381">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-381">Outlook</span></span>

- <span data-ttu-id="51b68-382">Corrigimos um problema em que a impressão rápida de anexos de imagem resultava no erro, "O Windows não consegue encontrar esta imagem.</span><span class="sxs-lookup"><span data-stu-id="51b68-382">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="51b68-383">Verifique a localização e tente novamente ".</span><span class="sxs-lookup"><span data-stu-id="51b68-383">Check the location, and then try again".</span></span>


- <span data-ttu-id="51b68-384">Corrigimos um problema que fazia com que alguns usuários vissem o Outlook iniciar em um estado offline até que eles optassem por trabalhar manualmente online.</span><span class="sxs-lookup"><span data-stu-id="51b68-384">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-385">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-385">PowerPoint</span></span>

- <span data-ttu-id="51b68-386">Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="51b68-386">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="51b68-387">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-387">Project</span></span>

- <span data-ttu-id="51b68-388">Corrigido um problema em que o NewVal no evento ProjectBeforeTaskChagne não tinha o valor correto se um atraso fosse alterado em uma visualização do tipo Formulário de Tarefa.</span><span class="sxs-lookup"><span data-stu-id="51b68-388">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="51b68-389">Corrigido um problema em que, se você tiver uma lista de tarefas em um site de projeto e agrupar a lista de tarefas, não será capaz de editar rapidamente a lista de tarefas.</span><span class="sxs-lookup"><span data-stu-id="51b68-389">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="51b68-390">Corrigido um problema em que, se você atualizar um recurso empresarial por meio do CSOM, as unidades máximas de recursos poderiam ser perdidas.</span><span class="sxs-lookup"><span data-stu-id="51b68-390">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-391">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-391">Word</span></span>

- <span data-ttu-id="51b68-392">Consertamos um problema em que o zoom e a área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="51b68-392">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="51b68-393">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-393">Office Suite</span></span>

- <span data-ttu-id="51b68-394">Corrigimos um problema em que o Login interativo da API SSO retornava um código de erro.</span><span class="sxs-lookup"><span data-stu-id="51b68-394">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2010-october-02"></a><span data-ttu-id="51b68-396">Versão 2010: 2 de outubro</span><span class="sxs-lookup"><span data-stu-id="51b68-396">Version 2010: October 02</span></span>
<span data-ttu-id="51b68-397">*Versão 2010 (Build 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-397">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-399">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-399">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-400">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-400">Excel</span></span>

- <span data-ttu-id="51b68-401">**Use a caixa de diálogo avançado para criar tipos de dados:** a caixa de diálogo avançada permite que você selecione manualmente as colunas que combinam o tipo de dados que você está criando.</span><span class="sxs-lookup"><span data-stu-id="51b68-401">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-404">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-404">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="51b68-405">OneNote</span><span class="sxs-lookup"><span data-stu-id="51b68-405">OneNote</span></span>

- <span data-ttu-id="51b68-406">Consertamos um problema em que um usuário não conseguia selecionar e copiar o URL do bloco de texto no Arquivo OutSpace > Informações.</span><span class="sxs-lookup"><span data-stu-id="51b68-406">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-407">Outlook</span></span>

- <span data-ttu-id="51b68-408">Corrige um problema que provocava o envio de emails gerados automaticamente com um corpo em branco quando o assunto estava em branco.</span><span class="sxs-lookup"><span data-stu-id="51b68-408">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="51b68-409">Resolvemos um problema em que o GUID da pasta incorreto estava armazenado em cache para as pastas.</span><span class="sxs-lookup"><span data-stu-id="51b68-409">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="51b68-410">Quando um usuário copiava e colava um endereço de email no campo do destinatário com o nome de exibição, o endereço de email nem sempre era analisado corretamente e fazia aparecer um aviso informando que um endereço de email era inválido.</span><span class="sxs-lookup"><span data-stu-id="51b68-410">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="51b68-411">Foi corrigido para que o nome e o endereço de email sejam analisados ​​corretamente, de forma que o aviso não seja mais mostrado.</span><span class="sxs-lookup"><span data-stu-id="51b68-411">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="51b68-412">Corrigimos um problema em que as pastas compartilhadas online não retornavam o nome da pasta pai.</span><span class="sxs-lookup"><span data-stu-id="51b68-412">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="51b68-413">Em vez de uma falha, ele retornava um caminho vazio que saia incorretamente para a conta primária.</span><span class="sxs-lookup"><span data-stu-id="51b68-413">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="51b68-414">Consertamos um problema em que as mudanças de acompanhamento se ativavam depois de reabrir um rascunho no painel de visualização somente leitura.</span><span class="sxs-lookup"><span data-stu-id="51b68-414">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="51b68-415">Consertamos um problema em que a opção Salvar como não estava disponível para anexos clássicos.</span><span class="sxs-lookup"><span data-stu-id="51b68-415">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="51b68-416">Corrigimos um problema para fornecer a um usuário uma maneira de personalizar o texto de justificação ao substituir uma política.</span><span class="sxs-lookup"><span data-stu-id="51b68-416">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-417">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-417">PowerPoint</span></span>

- <span data-ttu-id="51b68-418">Solucionamos um problema em que o PowerPoint não exportava os pontos de marcadores de retângulo durante a exportação para PDF.</span><span class="sxs-lookup"><span data-stu-id="51b68-418">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="51b68-419">Consertamos um problema em que se você estivesse no último slide e passasse o dedo para o próximo slide depois de pressionar 'encerrar sessão' e antes do resumo ser exibido, a caixa de diálogo de sessão final também ficava visível na página de resumo.</span><span class="sxs-lookup"><span data-stu-id="51b68-419">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="51b68-420">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-420">Project</span></span>

- <span data-ttu-id="51b68-421">Correção de um problema em que o Project poderia falhar se você aplicasse um grupo ao modo de exibição de uso do recurso ou de planilha e, em seguida, inserisse uma coluna.</span><span class="sxs-lookup"><span data-stu-id="51b68-421">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="51b68-422">Correção de um problema em que, se você tivesse campos personalizados com fórmulas e estivesse usando o valor agregado, você poderia experienciar atrasos na mudança nos modos de exibição e ao abrir detalhes do projeto/tarefa.</span><span class="sxs-lookup"><span data-stu-id="51b68-422">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="51b68-423">Correção de um problema em que o método VBA ConsolidateProjects poderia ser arquivado se você tentasse adicionar o mesmo projeto várias vezes e tivesse AttachToSources definido como falso.</span><span class="sxs-lookup"><span data-stu-id="51b68-423">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="51b68-424">Correção de um problema em que, se você tiver um código de eventos em execução e tentar fazer alterações por meio de um modo de exibição Formulário de Tarefas, clicar no botão OK pode não confirmar as alterações.</span><span class="sxs-lookup"><span data-stu-id="51b68-424">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2010-september-25"></a><span data-ttu-id="51b68-426">Versão 2010: 25 de setembro</span><span class="sxs-lookup"><span data-stu-id="51b68-426">Version 2010: September 25</span></span>
<span data-ttu-id="51b68-427">*Versão 2010 (Build 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-427">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-429">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-429">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-430">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-430">Excel</span></span>

- <span data-ttu-id="51b68-431">**Criar tipos de dados com o Power Query:** criar tipos de dados valiosos com o Power Query por meio de qualquer fonte de dados</span><span class="sxs-lookup"><span data-stu-id="51b68-431">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-432">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-432">Outlook</span></span>

- <span data-ttu-id="51b68-433">**Atualizações da Experiência do Usuário para Tasks:** Uma atualização visual dos itens de tarefa</span><span class="sxs-lookup"><span data-stu-id="51b68-433">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="51b68-434">**Economizar tempo ao redigir mensagens:** Outlook mostra uma sugestão de escrita que ajuda você a redigir mensagens rapidamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-434">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="51b68-435">Para aceitar a sugestão, basta usar a tecla Tab.</span><span class="sxs-lookup"><span data-stu-id="51b68-435">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-436">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-436">Word</span></span>

- <span data-ttu-id="51b68-437">**O painel do Editor Microsoft obtém uma atualização no Word para a área de trabalho:** Atualizamos a experiência atual com o painel do editor no Word para clientes de área de trabalho.</span><span class="sxs-lookup"><span data-stu-id="51b68-437">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-440">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-440">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-441">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-441">Access</span></span>

- <span data-ttu-id="51b68-442">Consertamos um problema em que a posição da barra de rolagem não foi definida corretamente durante o carregamento da janela de consulta/relação salva enquanto é rolado.</span><span class="sxs-lookup"><span data-stu-id="51b68-442">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="51b68-443">Consertamos um problema em que o painel de tarefas adicionar tabela não estava exibindo nomes contendo '&' corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-443">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="51b68-444">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-444">Excel</span></span>

- <span data-ttu-id="51b68-445">Consertamos um problema em que o intervalo de várias categorias de vários níveis não estava funcionando em gráficos.</span><span class="sxs-lookup"><span data-stu-id="51b68-445">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="51b68-446">Consertamos um problema que pode causar uma falha ao atualizar tabelas dinâmicas OLAP.</span><span class="sxs-lookup"><span data-stu-id="51b68-446">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="51b68-447">Consertamos um problema em que a adição a uma tabela usada para a validação de dados não atualizou as opções de todas as planilhas na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="51b68-447">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="51b68-448">OneNote</span><span class="sxs-lookup"><span data-stu-id="51b68-448">OneNote</span></span>

- <span data-ttu-id="51b68-449">Consertamos um problema em que o OneNote não encontrou cores de alto contraste na tela para temas personalizados.</span><span class="sxs-lookup"><span data-stu-id="51b68-449">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="51b68-450">Consertamos um problema ao passar o mouse sobre a cor verde no seletor de cores do bloco de anotações, os pop-ups lêem "giz vermelho".</span><span class="sxs-lookup"><span data-stu-id="51b68-450">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="51b68-451">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-451">PowerPoint</span></span>

- <span data-ttu-id="51b68-452">Consertamos um problema em que o gráfico vinculado do Excel se altera incorretamente para a planilha do Excel quando o usuário altera o caminho de origem para a pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="51b68-452">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-453">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-453">Word</span></span>

- <span data-ttu-id="51b68-454">Consertamos um problema em que os links para os arquivos habilitados para fluxo de trabalho não foram abertos conforme o esperado.</span><span class="sxs-lookup"><span data-stu-id="51b68-454">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2010-september-18"></a><span data-ttu-id="51b68-456">Versão 2010: 18 de setembro</span><span class="sxs-lookup"><span data-stu-id="51b68-456">Version 2010: September 18</span></span>
<span data-ttu-id="51b68-457">*Versão 2010 (Build 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="51b68-457">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-459">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-459">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-460">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-460">Outlook</span></span>

- <span data-ttu-id="51b68-461">**Revise suas mensagens com o Editor:** Agora, você pode obter sugestões de gramática e de outros estilos em seus emails para usuários do Outlook de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="51b68-461">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="51b68-462">Procure palavras sublinhadas para ver as sugestões do Editor para aprimorar sua redação.</span><span class="sxs-lookup"><span data-stu-id="51b68-462">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="51b68-463">**Quebre a barreira do idioma com um tradutor interno:** Os suplementos para tradução não são mais necessários!</span><span class="sxs-lookup"><span data-stu-id="51b68-463">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="51b68-464">Em uma mensagem, clique com o botão direito para traduzir palavras, frases específicas ou a mensagem inteira.</span><span class="sxs-lookup"><span data-stu-id="51b68-464">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-467">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-467">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-468">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-468">Excel</span></span>

- <span data-ttu-id="51b68-469">Corrigido um problema com os Gráficos de Mapa 2D que não funcionavam ao usar o VBA para definir as cores dos valores como máximos, médios e mínimos de uma série.</span><span class="sxs-lookup"><span data-stu-id="51b68-469">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="51b68-470">Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.</span><span class="sxs-lookup"><span data-stu-id="51b68-470">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="51b68-471">Corrigido um problema que poderia causar um erro informando que o "Excel esgotou os recursos ao tentar calcular uma ou mais fórmulas".</span><span class="sxs-lookup"><span data-stu-id="51b68-471">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="51b68-472">Corrigido um problema em que o ChartSheet falhava em alguns casos quando uma fórmula era inserida por meio da barra de fórmula.</span><span class="sxs-lookup"><span data-stu-id="51b68-472">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="51b68-473">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-473">Outlook</span></span>

- <span data-ttu-id="51b68-474">Quando um usuário copiava e colava um endereço de email no campo do destinatário com o nome de exibição, o endereço de email nem sempre era analisado corretamente e fazia aparecer um aviso informando que um endereço de email era inválido.</span><span class="sxs-lookup"><span data-stu-id="51b68-474">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="51b68-475">Foi corrigido para que o nome e o endereço de email sejam analisados ​​corretamente, de forma que o aviso não seja mais mostrado.</span><span class="sxs-lookup"><span data-stu-id="51b68-475">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="51b68-476">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-476">Word</span></span>

- <span data-ttu-id="51b68-477">Corrigido um problema em que mostrava um pop-out de comentário quando um usuário tocava em uma alteração controlada (inserção/exclusão).</span><span class="sxs-lookup"><span data-stu-id="51b68-477">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="51b68-478">Corrigimos um problema com a exclusão de textos explicativos de comentários no Word.</span><span class="sxs-lookup"><span data-stu-id="51b68-478">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="51b68-479">Corrigimos um problema no Outlook com a mensagem definida como Não encaminhar.</span><span class="sxs-lookup"><span data-stu-id="51b68-479">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="51b68-480">Corrigimos um problema que ocorria ao salvar um documento do Word que continha citação e equação.</span><span class="sxs-lookup"><span data-stu-id="51b68-480">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DE BUGDETAILS)

## <a name="version-2010-september-11"></a><span data-ttu-id="51b68-482">Versão 2010: 11 de setembro</span><span class="sxs-lookup"><span data-stu-id="51b68-482">Version 2010: September 11</span></span>
<span data-ttu-id="51b68-483">*Versão 2010 (Build 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-483">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-485">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-485">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="51b68-486">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-486">Access</span></span>

- <span data-ttu-id="51b68-487">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-487">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-488">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-488">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-489">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-489">Excel</span></span>

- <span data-ttu-id="51b68-490">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-490">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-491">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-491">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="51b68-492">OneNote</span><span class="sxs-lookup"><span data-stu-id="51b68-492">OneNote</span></span>

- <span data-ttu-id="51b68-493">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-493">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-494">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-494">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-495">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-495">Outlook</span></span>

- <span data-ttu-id="51b68-496">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-496">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-497">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-497">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-498">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-498">PowerPoint</span></span>

- <span data-ttu-id="51b68-499">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-499">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-500">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-500">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-501">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-501">Project</span></span>

- <span data-ttu-id="51b68-502">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-502">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-503">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-503">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="51b68-504">Publisher</span><span class="sxs-lookup"><span data-stu-id="51b68-504">Publisher</span></span>

- <span data-ttu-id="51b68-505">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-505">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-506">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-506">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="51b68-507">Visio</span><span class="sxs-lookup"><span data-stu-id="51b68-507">Visio</span></span>

- <span data-ttu-id="51b68-508">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-508">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-509">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-509">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-510">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-510">Word</span></span>

- <span data-ttu-id="51b68-511">**O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro?</span><span class="sxs-lookup"><span data-stu-id="51b68-511">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="51b68-512">Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-512">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-515">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-515">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-516">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-516">Excel</span></span>

- <span data-ttu-id="51b68-517">Correção de um problema em que podia haver um atraso perceptível ao alternar entre planilhas com grandes quantidades de dados quando 'Visualização de quebra de página ' estava habilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-517">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-518">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-518">Outlook</span></span>

- <span data-ttu-id="51b68-519">Consertamos um problema com emails sendo ocultados após a desativação da Caixa de Entrada Destaques e a realização de uma classificação.</span><span class="sxs-lookup"><span data-stu-id="51b68-519">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-520">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-520">PowerPoint</span></span>

- <span data-ttu-id="51b68-521">Solucionamos um problema em que o GIF animava apenas uma vez no editor e nas apresentações de slides.</span><span class="sxs-lookup"><span data-stu-id="51b68-521">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2010-september-04"></a><span data-ttu-id="51b68-523">Versão 2010: 04 de setembro</span><span class="sxs-lookup"><span data-stu-id="51b68-523">Version 2010: September 04</span></span>
<span data-ttu-id="51b68-524">*Versão 2010 (Criação 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="51b68-524">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-526">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-526">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-527">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-527">Outlook</span></span>

- <span data-ttu-id="51b68-528">**E-mail de fixação:** Esse recurso ajuda os usuários a rastrearem os e-mails que precisam reenviar para você ou terem como um lembrete, mantendo-os no topo da lista de mensagens.</span><span class="sxs-lookup"><span data-stu-id="51b68-528">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="51b68-529">**Receba sugestões por e-mail ao pesquisar por pessoa:** ao digitar os termos de pesquisa no Outlook, você receberá os e-mails mais relevantes apresentados nas sugestões.</span><span class="sxs-lookup"><span data-stu-id="51b68-529">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="51b68-530">**Receba sugestões por e-mail ao pesquisar por pessoa:** ao digitar os termos de pesquisa no Outlook, você receberá os e-mails mais relevantes apresentados nas sugestões.</span><span class="sxs-lookup"><span data-stu-id="51b68-530">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="51b68-531">**O Microsoft Editor recebe uma atualização dos clientes da área de trabalho do Word e do Outlook:** estamos introduzindo um novo modelo de clique para revisar das sugestões de ortografia, gramática e estilo avançado do Editor.</span><span class="sxs-lookup"><span data-stu-id="51b68-531">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="51b68-532">Essa alteração também inclui uma nova superfície de cartão dedicado para revisar as sugestões.</span><span class="sxs-lookup"><span data-stu-id="51b68-532">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-533">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-533">Word</span></span>

- <span data-ttu-id="51b68-534">**O Microsoft Editor recebe uma atualização dos clientes da área de trabalho do Word e do Outlook:** estamos introduzindo um novo modelo de clique para revisar das sugestões de ortografia, gramática e estilo avançado do Editor.</span><span class="sxs-lookup"><span data-stu-id="51b68-534">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="51b68-535">Essa alteração também inclui uma nova superfície de cartão dedicado para revisar as sugestões.</span><span class="sxs-lookup"><span data-stu-id="51b68-535">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-538">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-538">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-539">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-539">Excel</span></span>

- <span data-ttu-id="51b68-540">Resolvemos um problema no qual, se você abrisse um arquivo contendo a função LET, ele exibiria o alerta: "Encontramos um problema de conteúdo no "seu arquivo.xlsx".</span><span class="sxs-lookup"><span data-stu-id="51b68-540">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="51b68-541">Você quer que tentemos recuperar o máximo possível?</span><span class="sxs-lookup"><span data-stu-id="51b68-541">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="51b68-542">Se você confiar na origem dessa pasta de trabalho, clique em Sim".</span><span class="sxs-lookup"><span data-stu-id="51b68-542">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="51b68-543">Corrigimos um erro relacionado às referências de suplemento XLAM e intervalos nomeados.</span><span class="sxs-lookup"><span data-stu-id="51b68-543">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="51b68-544">Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="51b68-544">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="51b68-545">Resolvemos um problema no qual, se um usuário aplicou um estilo personalizado a uma matriz dinâmica, ele receberá o erro: "Não é possível alterar partes de uma matriz".</span><span class="sxs-lookup"><span data-stu-id="51b68-545">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="51b68-546">Essa era uma restrição herdada que foi removida.</span><span class="sxs-lookup"><span data-stu-id="51b68-546">This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="51b68-547">Resolvemos um problema no qual a barra de fórmulas do Excel não será processada completamente depois que a conexão com um dispositivo for perdida, como uma sessão remota conectar/desconectar ou uma alteração de monitor.</span><span class="sxs-lookup"><span data-stu-id="51b68-547">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-548">Outlook</span></span>

- <span data-ttu-id="51b68-549">Resolvemos um problema que fornece mais flexibilidade para habilitar/desabilitar as opções de log padrão através da política de grupo.</span><span class="sxs-lookup"><span data-stu-id="51b68-549">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="51b68-550">Resolvemos um problema no qual o Nome de domínio herdado de um remetente de e-mail foi preservado e exibido depois que um rascunho de e-mail foi movido entre as caixas de correio com permissões de assistente e permissões de gerente.</span><span class="sxs-lookup"><span data-stu-id="51b68-550">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="51b68-551">Resolvemos um problema que fazia com que alguns usuários vissem o Outlook iniciar em um estado off-line até que eles optassem por trabalhar manualmente on-line.</span><span class="sxs-lookup"><span data-stu-id="51b68-551">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="51b68-552">Resolvemos um problema em que a execução do código VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage"), depois de habilitar a Fita de Linha Única (SLR), resultaria em um erro de tempo de execução.</span><span class="sxs-lookup"><span data-stu-id="51b68-552">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="51b68-553">Resolvemos um problema no qual as teclas "OK" e "Cancelar" no diálogo Respostas automáticas não seriam visíveis em um sistema com alta resolução (como 1750 x 1920) combinado com um grande tamanho de texto (como 175%).</span><span class="sxs-lookup"><span data-stu-id="51b68-553">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="51b68-554">Resolvemos uma condição na qual enviar um pedido de reunião de um grupo de contato vazio para outro grupo de contato resultaria em um acidente.</span><span class="sxs-lookup"><span data-stu-id="51b68-554">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="51b68-555">Resolvemos um problema que fazia com que os usuários experimentassem um erro ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="51b68-555">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="51b68-556">Resolvemos um problema no qual, se a política de grupo exigir um suplemento para ser sempre habilitada, o monitoramento do suplemento ficará indisponível para impedir que os usuários desabilitem o suplemento.</span><span class="sxs-lookup"><span data-stu-id="51b68-556">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-557">PowerPoint</span></span>

- <span data-ttu-id="51b68-558">Resolvemos um problema em que os vídeos não eram automaticamente reproduzidos nas apresentações de slides.</span><span class="sxs-lookup"><span data-stu-id="51b68-558">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="51b68-559">Resolvemos um problema no qual, depois de iniciar o PowerPoint, inserindo um slide e abrindo e fechando o painel de comentários, os slides no painel de miniaturas eram exibidos como sendo sobrepostos.</span><span class="sxs-lookup"><span data-stu-id="51b68-559">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-560">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-560">Project</span></span>

- <span data-ttu-id="51b68-561">Resolvemos um problema no qual, se um recurso tiver várias tabelas de taxas de custo, talvez o custo restante não seja calculado corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-561">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="51b68-562">Resolvemos um problema no qual a Data de término do projeto não era atualizada nos projetos conectados à lista de tarefas do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-562">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-563">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-563">Word</span></span>

- <span data-ttu-id="51b68-564">Resolvemos um problema no qual o Cartão de comentários exibia uma borda ao redor do texto do comentário se o usuário clicava no mesmo.</span><span class="sxs-lookup"><span data-stu-id="51b68-564">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="51b68-565">Resolvemos um problema no qual o foco não ia para o painel de comentários se o documento fosse ampliado para 160% ou mais e o painel de comentários não fosse visível.</span><span class="sxs-lookup"><span data-stu-id="51b68-565">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="51b68-566">Resolvemos um problema no qual os comentários em um documento eram exibidos em outros documentos abertos depois da alteração entre os vários documentos abertos.</span><span class="sxs-lookup"><span data-stu-id="51b68-566">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="51b68-567">Resolvemos um problema no qual, se um usuário criasse um rascunho de comentário ancorado em uma linha que já contivesse comentários confirmados, o rascunho era organizado na ordem errada em relação ao comentário comprometido no SideTrack.</span><span class="sxs-lookup"><span data-stu-id="51b68-567">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="51b68-568">Resolvemos um problema no qual os links longos não eram dispostos ao salvar um documento no formato HTML.</span><span class="sxs-lookup"><span data-stu-id="51b68-568">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="51b68-569">Resolvemos um problema no qual a macro AutoOpen era executada antes do AutoExec.</span><span class="sxs-lookup"><span data-stu-id="51b68-569">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2009-august-28"></a><span data-ttu-id="51b68-571">Versão 2009: 28 de agosto</span><span class="sxs-lookup"><span data-stu-id="51b68-571">Version 2009: August 28</span></span>
<span data-ttu-id="51b68-572">*Versão 2009 (Build 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="51b68-572">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-574">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-574">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-575">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-575">Outlook</span></span>

- <span data-ttu-id="51b68-576">Aborda um problema que provocou os usuários a enviarem conteúdo de email que tinha uma política "Não Encaminhar" aplicada ao OneNote ao selecionar mais de uma mensagem.</span><span class="sxs-lookup"><span data-stu-id="51b68-576">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-577">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-577">PowerPoint</span></span>

- <span data-ttu-id="51b68-578">Corrigimos um problema em que a funcionalidade para inserir um vídeo foi desabilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-578">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-579">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-579">Word</span></span>

- <span data-ttu-id="51b68-580">Corrigimos um problema em que o usuário não conseguisse sair do cabeçalho/rodapé ao selecionar um comentário.</span><span class="sxs-lookup"><span data-stu-id="51b68-580">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="51b68-581">Corrigimos um problema que impedia que os usuários vissem os threads de comentário que excediam o limite sidetrack porque a rolagem por meio do sidetrack não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="51b68-581">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="51b68-582">Corrigimos um problema em que a pesquisa por comentários resolvidos no painel sidetrack não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="51b68-582">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-583">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-583">Office Suite</span></span>

- <span data-ttu-id="51b68-584">Corrigimos um problema na Ferramenta de Implantação do Office, em que a configuração estava falhando ao usar o recurso RemoveMSI com o produto do Office 2007 "Relatório de Erros do Aplicativo da Microsoft".</span><span class="sxs-lookup"><span data-stu-id="51b68-584">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="51b68-585">Corrigimos um problema na caixa de diálogo Compactar imagem, onde algumas configurações DPI selecionadas pelo usuário não eram mantidas.</span><span class="sxs-lookup"><span data-stu-id="51b68-585">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2009-august-21"></a><span data-ttu-id="51b68-587">Versão 2009: 21 de agosto</span><span class="sxs-lookup"><span data-stu-id="51b68-587">Version 2009: August 21</span></span>
<span data-ttu-id="51b68-588">*Versão 2009 (Compilação 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-588">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-590">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-590">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-591">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-591">Excel</span></span>

- <span data-ttu-id="51b68-592">**Caneta de Ação no Excel:** Ferramenta de caneta para ajudá-lo a escrever à mão e fazer edições rápidas em seus dados</span><span class="sxs-lookup"><span data-stu-id="51b68-592">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-593">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-593">Outlook</span></span>

- <span data-ttu-id="51b68-594">**Excluir conversa pelo proprietário da mensagem:** Este recurso permite excluir uma conversa pelo proprietário da mensagem.</span><span class="sxs-lookup"><span data-stu-id="51b68-594">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-597">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-597">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-598">Acesso</span><span class="sxs-lookup"><span data-stu-id="51b68-598">Access</span></span>

- <span data-ttu-id="51b68-599">Corrigimos um problema onde as conexões a um banco de dados ODBC não estavam funcionando com aplicações de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-599">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-600">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-600">Excel</span></span>

- <span data-ttu-id="51b68-601">Corrigimos um problema onde usando um macro para definir a propriedade FormulaR1C1 para um intervalo, as referências de células estariam incorretas se uma planilha de gráfico fosse a planilha ativa. </span><span class="sxs-lookup"><span data-stu-id="51b68-601">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="51b68-602">Corrigimos um problema em que a escrita à tinta poderia fazer com que o Excel não respondesse.</span><span class="sxs-lookup"><span data-stu-id="51b68-602">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-603">Outlook</span></span>

- <span data-ttu-id="51b68-604">Corrigimos um problema onde os usuários podem agora desabilitar o IRM (Gerenciamento de Direitos de Informação) para o Outlook sem ter que desabilitá-lo para o resto das aplicações do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-604">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-605">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-605">Word</span></span>

- <span data-ttu-id="51b68-606">Corrigimos um problema em que o Word podia falhar depois que os comentários fossem excluídos.</span><span class="sxs-lookup"><span data-stu-id="51b68-606">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="51b68-607">Corrigimos um problema onde, em alguns casos, os marcadores não são exibidos corretamente no email.</span><span class="sxs-lookup"><span data-stu-id="51b68-607">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2009-august-14"></a><span data-ttu-id="51b68-609">Versão 2009: 14 de agosto</span><span class="sxs-lookup"><span data-stu-id="51b68-609">Version 2009: August 14</span></span>
<span data-ttu-id="51b68-610">*Versão 2009 (Compilação 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-610">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-612">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-613">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-613">Excel</span></span>

- <span data-ttu-id="51b68-614">Corrigimos um problema onde se um usuário digitasse um nome de fórmula, incluindo o parêntese e invocasse ajuda via F1, o tópico da ajuda específico a essa fórmula não seria exibido.</span><span class="sxs-lookup"><span data-stu-id="51b68-614">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="51b68-615">Corrigido um problema onde os macros atribuídos a botões eram quebrados após restaurar uma versão mais antiga do arquivo.</span><span class="sxs-lookup"><span data-stu-id="51b68-615">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-616">Outlook</span></span>

- <span data-ttu-id="51b68-617">Esta alteração corrige um problema onde a página da Reunião continuaria a ser exibida depois que o usuário trocasse as guias da página de Reunião para a página do Assistente de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="51b68-617">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-618">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-618">Word</span></span>

- <span data-ttu-id="51b68-619">Corrigimos um problema onde o ícone da imagem com marcadores não era exibido corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-619">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2009-august-07"></a><span data-ttu-id="51b68-621">Versão 2009: 07 de Agosto</span><span class="sxs-lookup"><span data-stu-id="51b68-621">Version 2009: August 07</span></span>
<span data-ttu-id="51b68-622">*Versão 2009 (Build 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-622">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-624">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-624">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-625">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-625">Outlook</span></span>

- <span data-ttu-id="51b68-626">Consertamos um problema em que os atributos da conta do usuário do Active Directory para "otherTelephone" e "otherHomePhone" não estavam mapeados para os atributos LDAP do Outlook correspondente.</span><span class="sxs-lookup"><span data-stu-id="51b68-626">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-627">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-627">PowerPoint</span></span>

- <span data-ttu-id="51b68-628">Consertamos um problema em que os usuários estavam vendo a barra da faixa de opções/ título sendo exibida em determinadas condições.</span><span class="sxs-lookup"><span data-stu-id="51b68-628">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-31"></a><span data-ttu-id="51b68-630">Versão 2008: 31 de Julho</span><span class="sxs-lookup"><span data-stu-id="51b68-630">Version 2008: July 31</span></span>
<span data-ttu-id="51b68-631">*Versão 2008 (Build 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-631">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-633">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-633">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-634">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-634">Excel</span></span>

- <span data-ttu-id="51b68-635">**Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-635">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="51b68-636">Não é necessário converter.</span><span class="sxs-lookup"><span data-stu-id="51b68-636">No conversion required.</span></span><br /><span data-ttu-id="51b68-637">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="51b68-637">See details in [blog post](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-638">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-638">Outlook</span></span>

- <span data-ttu-id="51b68-639">**Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-639">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="51b68-640">Não é necessário converter.</span><span class="sxs-lookup"><span data-stu-id="51b68-640">No conversion required.</span></span><br /><span data-ttu-id="51b68-641">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="51b68-641">See details in [blog post](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-642">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-642">PowerPoint</span></span>

- <span data-ttu-id="51b68-643">**Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-643">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="51b68-644">Não é necessário converter.</span><span class="sxs-lookup"><span data-stu-id="51b68-644">No conversion required.</span></span><br /><span data-ttu-id="51b68-645">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="51b68-645">See details in [blog post](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="51b68-646">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-646">Word</span></span>

- <span data-ttu-id="51b68-647">**Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-647">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="51b68-648">Não é necessário converter.</span><span class="sxs-lookup"><span data-stu-id="51b68-648">No conversion required.</span></span><br /><span data-ttu-id="51b68-649">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="51b68-649">See details in [blog post](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-652">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-652">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-653">Acessar</span><span class="sxs-lookup"><span data-stu-id="51b68-653">Access</span></span>

- <span data-ttu-id="51b68-654">Esta correção resolve o problema de quando na tentativa de executar determinadas consultas tenha previamente produzido a mensagem de erro 'Consulta é muito complexa'.</span><span class="sxs-lookup"><span data-stu-id="51b68-654">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-655">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-655">Excel</span></span>

- <span data-ttu-id="51b68-656">Corrigimos um problema em que, se a ordem de uma série de gráficos tiver sido alterada, a caixa de seleção correspondente alinhada com a série não foi reordenada juntamente com a série.</span><span class="sxs-lookup"><span data-stu-id="51b68-656">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="51b68-657">Corrigimos um problema em que uma cópia de uma imagem com um preenchimento de gradiente radial não correspondeu ao original.</span><span class="sxs-lookup"><span data-stu-id="51b68-657">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-658">Outlook</span></span>

- <span data-ttu-id="51b68-659">Isto corrige um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não teve permissões de proprietário na mensagem que está sendo respondida.</span><span class="sxs-lookup"><span data-stu-id="51b68-659">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="51b68-660">Esta correção resolve um problema que estava causando falha no Outlook ao exibir quebras de linha corretamente em conteúdo de markdown.</span><span class="sxs-lookup"><span data-stu-id="51b68-660">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-661">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-661">PowerPoint</span></span>

- <span data-ttu-id="51b68-662">Corrigimos um problema em que uma cópia de uma imagem com um preenchimento de gradiente radial não correspondeu ao original.</span><span class="sxs-lookup"><span data-stu-id="51b68-662">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="51b68-663">Corrigimos um problema em que o botão Formulários no PowerPoint não permitia a criação de Formulários quando o acesso ao Office Store não era permitido.</span><span class="sxs-lookup"><span data-stu-id="51b68-663">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-664">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-664">Project</span></span>

- <span data-ttu-id="51b68-665">Corrigimos um problema em que, para uma lista de tarefas do SharePoint, os botões da faixa de opções na segunda guia podem ficar desabilitados.</span><span class="sxs-lookup"><span data-stu-id="51b68-665">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-666">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-666">Word</span></span>

- <span data-ttu-id="51b68-667">Corrigimos um problema em que uma cópia de uma imagem com um preenchimento de gradiente radial não correspondeu ao original.</span><span class="sxs-lookup"><span data-stu-id="51b68-667">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="51b68-668">Corrigimos um problema em que, se um comentário foi adicionado para acompanhar uma alteração, o painel revisões seria aberto inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-668">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="51b68-669">Corrigimos um problema em que os links para documentos não estavam sendo inseridos na caixa de comentários por meio de Inserir -> Link suspenso.</span><span class="sxs-lookup"><span data-stu-id="51b68-669">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="51b68-670">Corrigimos um problema em que a contagem de hiperlinks na coleção de hyperlinks do VBA não foi iterada corretamente após a adição de uma imagem contendo um hiperlink.</span><span class="sxs-lookup"><span data-stu-id="51b68-670">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-24"></a><span data-ttu-id="51b68-672">Versão 2008: 24 de Julho</span><span class="sxs-lookup"><span data-stu-id="51b68-672">Version 2008: July 24</span></span>
<span data-ttu-id="51b68-673">*Versão 2008 (Compilação 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-673">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-675">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-675">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-676">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-676">Excel</span></span>

- <span data-ttu-id="51b68-677">**Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha.</span><span class="sxs-lookup"><span data-stu-id="51b68-677">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="51b68-678">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="51b68-678">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-681">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-681">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="51b68-682">OneNote</span><span class="sxs-lookup"><span data-stu-id="51b68-682">OneNote</span></span>

- <span data-ttu-id="51b68-683">Consertamos um problema em que o texto no espaço reservado da caixa de edição Pesquisar transbordaria se a janela do aplicativo fosse redimensionada a uma menor dimensão.</span><span class="sxs-lookup"><span data-stu-id="51b68-683">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-684">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-684">Word</span></span>

- <span data-ttu-id="51b68-685">Consertamos um problema em que o texto no espaço reservado da caixa de edição Pesquisar transbordaria se a janela do aplicativo fosse redimensionada a uma menor dimensão.</span><span class="sxs-lookup"><span data-stu-id="51b68-685">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="51b68-686">Consertamos um problema em que a opção 'Pessoas Específicas' para o Controlar Alterações era desabilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-686">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="51b68-687">Consertamos um travamento ocasional ao abrir arquivos HTML.</span><span class="sxs-lookup"><span data-stu-id="51b68-687">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-17"></a><span data-ttu-id="51b68-689">Versão 2008: 17 de julho</span><span class="sxs-lookup"><span data-stu-id="51b68-689">Version 2008: July 17</span></span>
<span data-ttu-id="51b68-690">*Versão 2008 (Compilação 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-690">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-692">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-692">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-693">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-693">Excel</span></span>

- <span data-ttu-id="51b68-694">Consertamos um problema em que a qualquer momento em que um gráfico dinâmico com linhas de preenchimento ocultas era salvo e reaberto, as linhas de preenchimento se tornavam visíveis.</span><span class="sxs-lookup"><span data-stu-id="51b68-694">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="51b68-695">Consertamos um problema em que os gráficos nem sempre eram atualizados conforme o esperado quando o ' ForceFullCalculation ' estava habilitado via VBA para a pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="51b68-695">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-696">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-696">Outlook</span></span>

- <span data-ttu-id="51b68-697">Resolvemos um problema em torno da criação de vários perfis no Outlook a partir do mesmo domínio de email.</span><span class="sxs-lookup"><span data-stu-id="51b68-697">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="51b68-698">Resolve um problema que provocou a falha da exibição do ícone de bloqueio no cabeçalho de mensagens criptografadas S/MIME.</span><span class="sxs-lookup"><span data-stu-id="51b68-698">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="51b68-699">Soluciona um problema que causou a remoção dos anexos de mensagens S/MIME quando enviadas sem criptografia.</span><span class="sxs-lookup"><span data-stu-id="51b68-699">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="51b68-700">Corrige um problema que provocou mensagens de texto S/MIME sem formatação se tornarem truncadas ao enviar.</span><span class="sxs-lookup"><span data-stu-id="51b68-700">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="51b68-701">Resolve um problema que causa a corrupção de um arquivo ao enviar um email S/MIME não criptografado.</span><span class="sxs-lookup"><span data-stu-id="51b68-701">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="51b68-702">Soluciona um problema que fazia com que os usuários não conseguissem salvar anexos do OneDrive de fora de seu locatário em seu computador local ao selecionar a opção 'Salvar' na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="51b68-702">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="51b68-703">Resolve um problema que fazia com que os destinatários não conseguirem salvar mensagens protegidas por direitos, mesmo quando a permissão para salvar era concedida pelo remetente.</span><span class="sxs-lookup"><span data-stu-id="51b68-703">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="51b68-704">Corrige um problema que fazia com que as etiquetas de algumas opções de Pesquisa Avançada fossem truncadas em alguns idiomas.</span><span class="sxs-lookup"><span data-stu-id="51b68-704">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-705">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-705">Project</span></span>

- <span data-ttu-id="51b68-706">Resolvemos um problema em que as tarefas listadas no modo de exibição Quadro de Tarefas não estavam sincronizadas com as do diálogo Atribuir Recursos.</span><span class="sxs-lookup"><span data-stu-id="51b68-706">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="51b68-707">Corrigimos um problema no qual, se você copiasse e colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-707">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-708">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-708">Word</span></span>

- <span data-ttu-id="51b68-709">Consertamos um problema em que o comando 'Editor' era desabilitado quando o foco estava em uma caixa de texto de comentário.</span><span class="sxs-lookup"><span data-stu-id="51b68-709">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="51b68-710">Resolvemos um problema em que o comando 'Mostrar Marcação' era desabilitado quando o foco estava em uma caixa de texto de comentário.</span><span class="sxs-lookup"><span data-stu-id="51b68-710">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="51b68-711">Corrigimos um problema no XML personalizado no qual o estado dos comentários poderia ser perdido ao abrir o documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-711">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-712">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-712">Office Suite</span></span>

- <span data-ttu-id="51b68-713">Consertamos um problema em que, após o usuário abrir uma nova janela de aplicativo na barra de tarefas e criar um novo documento em branco, arquivos adicionais eram criados.</span><span class="sxs-lookup"><span data-stu-id="51b68-713">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="51b68-714">Resolvemos um problema em que, se um usuário estava editando um documento mas teve permissões perdidas, não estávamos notificando sobre o usuário de que ele tinha que se autenticar novamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-714">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-10"></a><span data-ttu-id="51b68-716">Versão 2008: 10 de julho</span><span class="sxs-lookup"><span data-stu-id="51b68-716">Version 2008: July 10</span></span>
<span data-ttu-id="51b68-717">*Versão 2008 (Build 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-717">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-719">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-719">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-720">Outlook</span></span>

- <span data-ttu-id="51b68-721">Consertamos um problema em que a opção Permitir Encaminhamento estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, caso a pasta compartilhada Download não tivesse sido verificada.</span><span class="sxs-lookup"><span data-stu-id="51b68-721">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="51b68-722">Consertamos um problema que exibia o botão imprimir em um estado desabilitado, mesmo que o usuário tivesse as permissões de impressão apropriadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-722">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-723">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-723">Project</span></span>

- <span data-ttu-id="51b68-724">Consertamos um problema no qual quando você tentava salvar um PDF/XPS do Project em uma biblioteca de documentos do SharePoint, nada acontecia.</span><span class="sxs-lookup"><span data-stu-id="51b68-724">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-725">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-725">Word</span></span>

- <span data-ttu-id="51b68-726">Consertamos um problema em que o Word deixava de responder depois de colar um texto e uma imagem na caixa de comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-726">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="51b68-727">Consertamos um problema em que o botão "Novo comentário" era desabilitado após a exclusão do último comentário.</span><span class="sxs-lookup"><span data-stu-id="51b68-727">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-july-03"></a><span data-ttu-id="51b68-729">Versão 2007: 03 de julho</span><span class="sxs-lookup"><span data-stu-id="51b68-729">Version 2007: July 03</span></span>
<span data-ttu-id="51b68-730">*Versão 2007 (Build 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="51b68-730">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-732">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-732">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-733">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-733">Outlook</span></span>

- <span data-ttu-id="51b68-734">**Crie pesquisas no Outlook com a Pesquisa Rápida:** Crie facilmente uma pesquisa, colete votos e exiba os resultados em um email [Saiba mais](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="51b68-734">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="51b68-735">**Novo localizador de sala:** Pesquisar salas de conferência por diferentes recursos.</span><span class="sxs-lookup"><span data-stu-id="51b68-735">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-738">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-739">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-739">Excel</span></span>

- <span data-ttu-id="51b68-740">Consertamos um problema em que as tabelas do modelo de dados criadas em determinadas versões do Excel não podiam ser vistas na 'Visualização de Tabela', embora a consulta associada à tabela não tivesse sido editada.</span><span class="sxs-lookup"><span data-stu-id="51b68-740">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="51b68-741">Consertamos um problema em que a desabilitar "Ignorar referências Relativas/absolutas" na caixa de diálogo Definir Nome \ Aplicar Nomes fazia com que as fórmulas não funcionassem.</span><span class="sxs-lookup"><span data-stu-id="51b68-741">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="51b68-742">Consertamos um problema em que a limpeza de um filtro de dados avançado podia ocasionar a perda da formatação da tabela.</span><span class="sxs-lookup"><span data-stu-id="51b68-742">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="51b68-743">Consertamos um problema em que o caminho completo de um documento PDF inserido era mostrado na legenda do documento, em vez de apenas o nome do arquivo.</span><span class="sxs-lookup"><span data-stu-id="51b68-743">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="51b68-744">Consertamos um problema em que depois de desabilitar o conector em nuvem Wolfram e, depois, salvar e abrir novamente uma pasta de trabalho do Excel, podia resultar em uma falha.</span><span class="sxs-lookup"><span data-stu-id="51b68-744">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="51b68-745">Consertamos um problema em que a inicialização do Excel com o suplemento Solver habilitado resultava em uma falha.</span><span class="sxs-lookup"><span data-stu-id="51b68-745">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-746">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-746">Outlook</span></span>

- <span data-ttu-id="51b68-747">Consertamos um problema em que o Outlook travava se houvesse mais de 130 destinatários na linha "Para" e também melhoramos o desempenho da renderização do texto.</span><span class="sxs-lookup"><span data-stu-id="51b68-747">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="51b68-748">Consertamos um problema na barra "Tarefas Pendentes", no qual os eventos que se estendiam por mais de dois dias exibiam a mesma hora de término para todos os dias subsequentes.</span><span class="sxs-lookup"><span data-stu-id="51b68-748">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="51b68-749">Consertamos um problema que fazia com que os usuários do Outlook vissem a lista de mensagens parar de responder por vários minutos após o uso de calendários compartilhados.</span><span class="sxs-lookup"><span data-stu-id="51b68-749">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-750">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-750">PowerPoint</span></span>

- <span data-ttu-id="51b68-751">Consertamos um problema em que colar HTML em uma área de texto em um slide resultava que fosse colado em uma caixa de texto criada na parte superior do slide.</span><span class="sxs-lookup"><span data-stu-id="51b68-751">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="51b68-752">Consertamos um problema em que selecionar todos os slides no Modo de Exibição do Apresentador e, em seguida, sair do modo de exibição do Apresentador usando Alt+Tab e retornar à apresentação de slides e clicar em "Finalizar Apresentação" poderia resultar em uma exceção não tratada.</span><span class="sxs-lookup"><span data-stu-id="51b68-752">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-753">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-753">Project</span></span>

- <span data-ttu-id="51b68-754">Consertamos um problema em que o Project pode falhar ao abrir determinados arquivos XML.</span><span class="sxs-lookup"><span data-stu-id="51b68-754">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="51b68-755">Consertamos um problema em que você não conseguia abrir um arquivo do Project a partir de uma biblioteca de documentos do SharePoint se a biblioteca estivesse no modo moderno.</span><span class="sxs-lookup"><span data-stu-id="51b68-755">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="51b68-756">Consertamos um problema em que os projetos não podiam ser abertos no cliente de área de trabalho do Project a partir do Project Web App, se a URL terminasse em '.com'.</span><span class="sxs-lookup"><span data-stu-id="51b68-756">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-757">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-757">Word</span></span>

- <span data-ttu-id="51b68-758">Consertamos um problema durante o modo de coautoria quando há um conflito de mesclagem e o usuário já optou por descartar as alterações. Não mais exibimos a opção para salvar ou descartar alterações.</span><span class="sxs-lookup"><span data-stu-id="51b68-758">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="51b68-759">Consertamos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, fazia com que o arquivo fosse salvo com a extensão .docx e com o nome de arquivo 'WRO0004.docx', independentemente do que o usuário inseriu, tornando o documento inutilizável.</span><span class="sxs-lookup"><span data-stu-id="51b68-759">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-26"></a><span data-ttu-id="51b68-761">Versão 2007: 26 de junho</span><span class="sxs-lookup"><span data-stu-id="51b68-761">Version 2007: June 26</span></span>
<span data-ttu-id="51b68-762">*Versão 2007 (Build 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="51b68-762">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-764">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-764">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-765">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-765">Access</span></span>

- <span data-ttu-id="51b68-766">Consertamos um problema em que o gerenciador de tabelas vinculadas solicitava uma chave primária se uma tabela SQL vinculada tivesse sido atualizada.</span><span class="sxs-lookup"><span data-stu-id="51b68-766">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="51b68-767">Consertamos um problema em que as consultas no Editor de Consultas rolavam para fora da área de visualização. </span><span class="sxs-lookup"><span data-stu-id="51b68-767">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="51b68-768">Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. </span><span class="sxs-lookup"><span data-stu-id="51b68-768">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-769">Outlook</span></span>

- <span data-ttu-id="51b68-770">Consertamos um problema em que os usuários não conseguiam 'Enviar Como' ou 'Enviar em nome' de uma lista de distribuição.</span><span class="sxs-lookup"><span data-stu-id="51b68-770">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="51b68-771">Consertamos um problema em que inserir uma imagem embutida em uma mensagem e, em seguida, salvar a mensagem como um rascunho resultava em um redimensionamento da imagem.</span><span class="sxs-lookup"><span data-stu-id="51b68-771">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="51b68-772">Consertamos um problema que fazia com que o corpo de uma mensagem de NDR mudasse de Unicode para ASCII após editar o assunto.</span><span class="sxs-lookup"><span data-stu-id="51b68-772">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-773">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-773">Project</span></span>

- <span data-ttu-id="51b68-774">Consertamos um problema em que os links do Planner do Project na Nuvem da Comunidade Governamental haviam sido desabilitados.</span><span class="sxs-lookup"><span data-stu-id="51b68-774">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-775">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-775">Office Suite</span></span>

- <span data-ttu-id="51b68-776">Consertamos um problema em que o texto inserido em um Elemento Gráfico Vetorial Escalonável (SVG) ficava ilegível após inseri-lo em um arquivo do Word, Excel ou PowerPoint, salvando e fechando o arquivo e reabrindo o arquivo.</span><span class="sxs-lookup"><span data-stu-id="51b68-776">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-19"></a><span data-ttu-id="51b68-778">Versão 2007: 19 de junho</span><span class="sxs-lookup"><span data-stu-id="51b68-778">Version 2007: June 19</span></span>
<span data-ttu-id="51b68-779">*Versão 2007 (Build 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-779">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-781">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-781">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-782">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-782">Excel</span></span>

- <span data-ttu-id="51b68-783">Consertamos um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar uma pasta de trabalho no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="51b68-783">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="51b68-784">Consertamos um problema em que as pastas de trabalho eram somente leitura quando o arquivo só era recomendável como somente leitura.</span><span class="sxs-lookup"><span data-stu-id="51b68-784">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-785">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-785">Outlook</span></span>

- <span data-ttu-id="51b68-786">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="51b68-786">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="51b68-787">Consertamos um problema que fazia com que os usuários vissem o seguinte erro ao fechar um compromisso que foi salvo anteriormente: "O item não pode ser salvo porque foi alterado por outro usuário ou em outra janela.</span><span class="sxs-lookup"><span data-stu-id="51b68-787">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="51b68-788">Deseja fazer uma cópia na pasta padrão para o item?"</span><span class="sxs-lookup"><span data-stu-id="51b68-788">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="51b68-789">Consertamos um problema em que as datas no Minicalendário falhavam ao exibir em negrito para os usuários no Japão.</span><span class="sxs-lookup"><span data-stu-id="51b68-789">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="51b68-790">Consertamos um problema que impedia que lembretes de calendário mostrassem os horários exatos para reuniões que aconteceriam em menos de uma semana.</span><span class="sxs-lookup"><span data-stu-id="51b68-790">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-791">PowerPoint</span></span>

- <span data-ttu-id="51b68-792">Consertamos um problema em que o indicador de cor de presença de um usuário não era atualizado na galeria de coautoria durante uma sessão de coautoria em tempo real.</span><span class="sxs-lookup"><span data-stu-id="51b68-792">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-793">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-793">Project</span></span>

- <span data-ttu-id="51b68-794">Consertamos um problema em que, se as tarefas de duração fixa estiverem em 100% concluídas, mas o término real não for especificado, a % concluída da tarefa exibia menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="51b68-794">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-795">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-795">Word</span></span>

- <span data-ttu-id="51b68-796">Consertamos um problema em que a cor do hiperlink HTML não estava sendo processada corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-796">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-797">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-797">Office Suite</span></span>

- <span data-ttu-id="51b68-798">Consertamos um problema em que URLs que não eram baseadas em http ou https não eram exibidas na lista de Mais Usados Recentemente.</span><span class="sxs-lookup"><span data-stu-id="51b68-798">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-12"></a><span data-ttu-id="51b68-800">Versão 2007: 12 de junho</span><span class="sxs-lookup"><span data-stu-id="51b68-800">Version 2007: June 12</span></span>
<span data-ttu-id="51b68-801">*Versão 2007 (Build 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-801">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-803">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-803">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-804">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-804">Excel</span></span>

- <span data-ttu-id="51b68-805">**Obtenha Dados da Organização com o Power BI usando Tipos de Dados:** Os tipos de dados do Excel no Power BI agora estão sendo disponibilizados para os participantes do programa Office Insider em organizações com o Office 365 E5/A5 ou o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="51b68-805">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="51b68-806">Obter as informações necessárias e atualizá-las facilmente é fundamental para muitos fluxos de trabalho diários.</span><span class="sxs-lookup"><span data-stu-id="51b68-806">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="51b68-807">Estamos oferecendo acesso às informações da sua empresa ou organização a partir do Power BI como tipo de dados no Excel, o amplia a capacidade de inserir informações vinculadas nas suas planilhas.</span><span class="sxs-lookup"><span data-stu-id="51b68-807">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="51b68-808">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-808">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="51b68-809">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="51b68-809">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-812">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-812">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-813">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-813">Access</span></span>

- <span data-ttu-id="51b68-814">Consertamos um problema que fazia com que o Microsoft Access não conseguisse identificar uma Coluna de Identidade em uma tabela do Servidor SQL vinculada, o que poderia fazer com que as linhas fossem relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-814">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-815">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-815">Excel</span></span>

- <span data-ttu-id="51b68-816">Consertamos um problema em que as linhas de grade principais de gráficos de radar não podiam ser formatadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-816">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-817">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-817">Project</span></span>

- <span data-ttu-id="51b68-818">Consertamos um problema em que o evento ProjectBeforeTaskChange não era acionado quando havia uma alteração na tarefa resumo do projeto ou no campo início/tarefa do projeto.</span><span class="sxs-lookup"><span data-stu-id="51b68-818">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="51b68-819">Consertamos um problema em que uma redefinição de linha de base ou uma atualização poderia alterar os recursos de custo/trabalho e a linha de base poderia refletir valores de orçamento.</span><span class="sxs-lookup"><span data-stu-id="51b68-819">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-820">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-820">Word</span></span>

- <span data-ttu-id="51b68-821">Consertamos um problema em que a capacidade de limpar a formatação dentro do Painel comentários por meio do botão Limpar Formatação na Faixa de Opções do Office não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="51b68-821">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="51b68-822">Consertamos um problema em que alterar o tamanho de uma tabela quando a régua não é exibida fazia com que outros aplicativos executados em segundo plano começassem a piscar.</span><span class="sxs-lookup"><span data-stu-id="51b68-822">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="51b68-823">Consertamos um problema em que, em modo de coautoria, as respostas a comentários, às vezes, não apareciam no painel comentários, mas ficavam visíveis no painel revisões.</span><span class="sxs-lookup"><span data-stu-id="51b68-823">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="51b68-824">Consertamos um problema em que o Word tinha uma lista com mais de 50 documentos abertos com frequência e, depois que você salvava e abria um documento, um histórico de revisão era exibido, ainda que nenhuma revisão tivesse sido realizada no documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-824">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-june-05"></a><span data-ttu-id="51b68-826">Versão 2006: 05 de junho</span><span class="sxs-lookup"><span data-stu-id="51b68-826">Version 2006: June 05</span></span>
<span data-ttu-id="51b68-827">*Versão 2006 (Build 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-827">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-829">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-829">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-830">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-830">Excel</span></span>

- <span data-ttu-id="51b68-831">**Classificar/filtrar enquanto estiver colaborando no Excel:** Agora você pode classificar e filtrar o arquivo do Excel e colaborar com outras pessoas.</span><span class="sxs-lookup"><span data-stu-id="51b68-831">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="51b68-832">Esse novo recurso impede que você seja afetado pelas classificações e filtros de outros usuários durante a coautoria do documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-832">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="51b68-833">**Crie Tabelas Dinâmicas a partir de Conjuntos de Dados no Power BI no Excel:** Você pode criar tabelas dinâmicas no Excel conectadas a conjuntos de dados armazenados no Power BI com alguns cliques.</span><span class="sxs-lookup"><span data-stu-id="51b68-833">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="51b68-834"> Isso permite que você obtenha o melhor das Tabelas Dinâmicas e do Power BI.</span><span class="sxs-lookup"><span data-stu-id="51b68-834">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="51b68-835">Calcule, resuma e analise seus dados com Tabelas Dinâmicas a partir dos conjuntos de dados seguros do Power BI.</span><span class="sxs-lookup"><span data-stu-id="51b68-835">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="51b68-836">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-836">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="51b68-837">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-837">Outlook</span></span>

- <span data-ttu-id="51b68-838">**Reabra rapidamente os itens de uma sessão anterior:** Adicionamos a opção de reabrir rapidamente os itens de uma sessão anterior do Outlook.</span><span class="sxs-lookup"><span data-stu-id="51b68-838">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="51b68-839">Se o Outlook falhar ou você fechá-lo, agora será possível reiniciar rapidamente os itens quando você reabrir o aplicativo.</span><span class="sxs-lookup"><span data-stu-id="51b68-839">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="51b68-840">Esse recurso não está habilitado por padrão.</span><span class="sxs-lookup"><span data-stu-id="51b68-840">This feature is on by default.</span></span> <span data-ttu-id="51b68-841">Para desativá-lo, vá até Opções > Gerais > Opções de Inicialização.</span><span class="sxs-lookup"><span data-stu-id="51b68-841">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-844">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-844">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-845">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-845">Excel</span></span>

- <span data-ttu-id="51b68-846">Consertamos um problema em que os valores personalizados no eixo do gráfico não eram aplicados corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-846">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="51b68-847">Consertamos um problema em que as planilhas que continham várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.</span><span class="sxs-lookup"><span data-stu-id="51b68-847">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-848">Outlook</span></span>

- <span data-ttu-id="51b68-849">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="51b68-849">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="51b68-850">Consertamos um problema em que exibir um modelo ao redigir uma nova mensagem de email resultaria em uma falha.</span><span class="sxs-lookup"><span data-stu-id="51b68-850">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="51b68-851">Resolvemos um problema em que os usuários não conseguiam acessar as pastas públicas do Exchange 2010 após a versão 1911 do Outlook.</span><span class="sxs-lookup"><span data-stu-id="51b68-851">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="51b68-852">Consertamos um problema em que o botão Categorizar para calendários de grupo na Faixa de Opções do Office estava desabilitado.</span><span class="sxs-lookup"><span data-stu-id="51b68-852">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="51b68-853">Consertamos um problema que fazia com que os usuários com contatos conflitantes experimentassem falhas no Outlook.</span><span class="sxs-lookup"><span data-stu-id="51b68-853">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="51b68-854">Consertamos um problema que resultava na falta do menu suspenso Arquivo Online em propriedades da pasta para usuários em monitores de DPI alto.</span><span class="sxs-lookup"><span data-stu-id="51b68-854">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="51b68-855">Consertamos um problema que fazia com que os usuários experimentassem uma falha no Outlook ao trabalhar com hiperlinks em emails de Texto sem Formatação.</span><span class="sxs-lookup"><span data-stu-id="51b68-855">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="51b68-856">Consertamos um problema que fazia com que o Outlook fosse incapaz de analisar os nomes de arquivo longos codificados com o RFC2231.</span><span class="sxs-lookup"><span data-stu-id="51b68-856">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="51b68-857">Consertamos um problema que estava fazendo com que os usuários do Outlook experimentassem travamentos intermitentes ao usar leitores de tela.</span><span class="sxs-lookup"><span data-stu-id="51b68-857">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-858">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-858">PowerPoint</span></span>

- <span data-ttu-id="51b68-859">Consertamos um problema com a abertura de arquivos configurados pelo servidor com autenticação baseada em formulários.</span><span class="sxs-lookup"><span data-stu-id="51b68-859">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="51b68-860">Consertamos um problema em que os arquivos do PowerPoint com gráficos/pastas de trabalho inseridas poderiam resultar em falhas ao salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="51b68-860">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="51b68-861">Consertamos um problema em que um painel de Comentários fechado pelo usuário abria automaticamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-861">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="51b68-862">Consertamos um problema em que o editor de slide de um slide poderia se sobrepor ao próximo slide.</span><span class="sxs-lookup"><span data-stu-id="51b68-862">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-863">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-863">Project</span></span>

- <span data-ttu-id="51b68-864">Consertamos um problema que impedia que tarefas órfãs fossem excluídas ou reatribuídas após o plano pai ser excluído.</span><span class="sxs-lookup"><span data-stu-id="51b68-864">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-865">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-865">Word</span></span>

- <span data-ttu-id="51b68-866">Consertamos um problema em que os carimbos de data/hora nos painéis de Comentários não eram baseados no tempo de localidade do sistema.</span><span class="sxs-lookup"><span data-stu-id="51b68-866">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="51b68-867">Consertamos um problema em que os comentários entre o aplicativo Web e o aplicativo da área de trabalho não estavam sincronizados.</span><span class="sxs-lookup"><span data-stu-id="51b68-867">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2006-may-29"></a><span data-ttu-id="51b68-869">Versão 2006: 29 de maio</span><span class="sxs-lookup"><span data-stu-id="51b68-869">Version 2006: May 29</span></span>
<span data-ttu-id="51b68-870">*Versão 2006 (Compilação 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-870">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="51b68-871">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-871">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-872">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-872">Outlook</span></span>

- <span data-ttu-id="51b68-873">**Botões adicionais adicionados às notificações do sistema do Outlook:** os botões de Ação Rápida agora aparecem nas notificações do Outlook ao executar o Outlook no Windows 10.</span><span class="sxs-lookup"><span data-stu-id="51b68-873">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-874">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-874">PowerPoint</span></span>

- <span data-ttu-id="51b68-875">**Melhor desempenho de Streaming de vídeo no PowerPoint:** Fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável.</span><span class="sxs-lookup"><span data-stu-id="51b68-875">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="51b68-876">Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.</span><span class="sxs-lookup"><span data-stu-id="51b68-876">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-879">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-879">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-880">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-880">Excel</span></span>

- <span data-ttu-id="51b68-881">Consertamos um problema em que o Excel ocasionalmente seria encerrado ao iniciar o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="51b68-881">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="51b68-882">Consertamos um problema eu que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.</span><span class="sxs-lookup"><span data-stu-id="51b68-882">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="51b68-883">Consertamos um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.</span><span class="sxs-lookup"><span data-stu-id="51b68-883">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="51b68-884">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="51b68-884">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-885">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-885">PowerPoint</span></span>

- <span data-ttu-id="51b68-886">Consertamos um problema em que os slides não eram centralizados após o zoom usando a roda do mouse.</span><span class="sxs-lookup"><span data-stu-id="51b68-886">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-887">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-887">Word</span></span>

- <span data-ttu-id="51b68-888">Consertamos um problema em que não era possível copiar e colar o texto em um painel de comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-888">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="51b68-889">Consertamos um problema em que os balões de dicas de comentário apareciam borradas com zoom 100%.</span><span class="sxs-lookup"><span data-stu-id="51b68-889">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="51b68-890">Resolvemos um problema em que a habilitação da política do Word 2007 e Documentos Binários e Templates posteriores causavam falha em alguns casos de coautoria.</span><span class="sxs-lookup"><span data-stu-id="51b68-890">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="51b68-891">Consertamos um problema em que os arquivos com nomes de caminho longos (superiores a 32K) não abriam e uma mensagem de erro apropriada não estava sendo exibida.</span><span class="sxs-lookup"><span data-stu-id="51b68-891">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)


## <a name="version-2006-may-22"></a><span data-ttu-id="51b68-893">Versão 2006: 22 de maio</span><span class="sxs-lookup"><span data-stu-id="51b68-893">Version 2006: May 22</span></span>
<span data-ttu-id="51b68-894">*Versão 2006 (Build 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-894">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-896">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-896">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-897">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-897">Excel</span></span>

- <span data-ttu-id="51b68-898">**Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-898">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="51b68-899">Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo.</span><span class="sxs-lookup"><span data-stu-id="51b68-899">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="51b68-900">Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar.</span><span class="sxs-lookup"><span data-stu-id="51b68-900">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="51b68-901">Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-901">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="51b68-902">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="51b68-902">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-903">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-903">PowerPoint</span></span>

- <span data-ttu-id="51b68-904">**Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-904">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="51b68-905">Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo.</span><span class="sxs-lookup"><span data-stu-id="51b68-905">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="51b68-906">Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar.</span><span class="sxs-lookup"><span data-stu-id="51b68-906">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="51b68-907">Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-907">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="51b68-908">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="51b68-908">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="51b68-909">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-909">Word</span></span>

- <span data-ttu-id="51b68-910">**Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="51b68-910">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="51b68-911">Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo.</span><span class="sxs-lookup"><span data-stu-id="51b68-911">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="51b68-912">Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar.</span><span class="sxs-lookup"><span data-stu-id="51b68-912">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="51b68-913">Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-913">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="51b68-914">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="51b68-914">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-917">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-917">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-918">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-918">Excel</span></span>

- <span data-ttu-id="51b68-919">Consertamos um problema em que a mensagem de erro "Esta pasta de trabalho está, atualmente, referenciada por outro e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="51b68-919">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="51b68-920">Consertamos um problema em que a memória estava sendo corrompida durante o gerenciamento de fontes entre o Excel e alguns aplicativos de tecnologia adaptativa de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-920">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="51b68-921">Consertamos um problema em que o Excel falhava quando os Suplementos pedem Itens de Host em planilhas que contêm formas com bloqueios não selecionados.</span><span class="sxs-lookup"><span data-stu-id="51b68-921">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-922">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-922">Outlook</span></span>

- <span data-ttu-id="51b68-923">Consertamos um problema em que o evento Folder.BeforeItemMove não era acionado corretamente quando um usuário movia itens entre pastas.</span><span class="sxs-lookup"><span data-stu-id="51b68-923">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="51b68-924">Consertamos um problema em que os usuários viam os itens de calendários que ultrapassavam o limite da meia-noite como Eventos de dia inteiro.</span><span class="sxs-lookup"><span data-stu-id="51b68-924">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="51b68-925">Consertamos um problema em que o Outlook travava quando dois suplementos adicionavam um botão ao mesmo grupo na faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="51b68-925">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="51b68-926">Consertamos um problema em que os usuários não conseguiam compartilhar um calendário com um usuário convidado.</span><span class="sxs-lookup"><span data-stu-id="51b68-926">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-927">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-927">PowerPoint</span></span>

- <span data-ttu-id="51b68-928">Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="51b68-928">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-929">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-929">Project</span></span>

- <span data-ttu-id="51b68-930">Consertamos um problema em que o Project falhava após clicar em Opções.</span><span class="sxs-lookup"><span data-stu-id="51b68-930">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-931">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-931">Word</span></span>

- <span data-ttu-id="51b68-932">Consertamos um problema em que os hiperlinks nos comentários não estavam funcionando.</span><span class="sxs-lookup"><span data-stu-id="51b68-932">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="51b68-933">Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.</span><span class="sxs-lookup"><span data-stu-id="51b68-933">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="51b68-934">Consertamos um problema em que a colagem de HTML no WordMail para o Calendário não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="51b68-934">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="51b68-935">Consertamos um problema em que responder a um comentário em uma sessão de coautoria poderia fazer com que o Word congelasse.</span><span class="sxs-lookup"><span data-stu-id="51b68-935">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-may-15"></a><span data-ttu-id="51b68-937">Versão 2006: 15 de maio</span><span class="sxs-lookup"><span data-stu-id="51b68-937">Version 2006: May 15</span></span>
<span data-ttu-id="51b68-938">*Versão 2006 (Build 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-938">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-940">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-940">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-941">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-941">Excel</span></span>

- <span data-ttu-id="51b68-942">**Fazer uma conexão em PDF:** Conectar, importar, atualizar dados de um PDF.</span><span class="sxs-lookup"><span data-stu-id="51b68-942">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="51b68-943">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-943">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- <span data-ttu-id="51b68-944">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="51b68-944">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-945">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-945">Outlook</span></span>

- <span data-ttu-id="51b68-946">**Encontre o que você precisa:** Restrinja sua pesquisa com opções como pasta, remetente, data, informações do anexo e muito mais.</span><span class="sxs-lookup"><span data-stu-id="51b68-946">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-947">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-947">PowerPoint</span></span>

- <span data-ttu-id="51b68-948">**Não é preciso dar um clique: seus earbuds fazem isso por você** Use seu Surface Earbuds para controlar suas apresentações de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-948">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="51b68-949">Importante: Você deve parear seu Surface Earbuds com o aplicativo Surface Audio para Windows 10 para usar gestos para controlar as apresentações.</span><span class="sxs-lookup"><span data-stu-id="51b68-949">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="51b68-950">As instruções sobre como começar a usar o aplicativo de áudio Surface no Windows 10 estão disponíveis aqui.</span><span class="sxs-lookup"><span data-stu-id="51b68-950">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="51b68-951">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-951">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="51b68-952">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="51b68-952">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-953">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-953">Word</span></span>

- <span data-ttu-id="51b68-954">**Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.</span><span class="sxs-lookup"><span data-stu-id="51b68-954">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-957">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-957">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-958">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-958">Excel</span></span>
- <span data-ttu-id="51b68-959">Consertamos um problema que resultou em um melhor tempo de desempenho para os usuários quando eles excluíam colunas mescladas.</span><span class="sxs-lookup"><span data-stu-id="51b68-959">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="51b68-960">Consertamos um problema que causava a duplicação de nomes de impressora na lista de impressoras disponíveis.</span><span class="sxs-lookup"><span data-stu-id="51b68-960">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="51b68-961">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-961">PowerPoint</span></span>
- <span data-ttu-id="51b68-962">Consertamos um problema em que os atalhos de teclado e a verificação ortográfica não funcionavam conforme o esperado ao usar um teclado QWERTZ.</span><span class="sxs-lookup"><span data-stu-id="51b68-962">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-963">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-963">Word</span></span>
- <span data-ttu-id="51b68-964">Resolvemos um problema em que a adição de um novo comentário em um documento em branco não faria nada.</span><span class="sxs-lookup"><span data-stu-id="51b68-964">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="51b68-965">Consertamos um problema em que inserir ou atualizar um índice em um documento que contém mais de cem entradas resultaria no travamento do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="51b68-965">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="51b68-966">Consertamos um problema em que os arquivos com valores XML personalizados abriam muito lentamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-966">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-967">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-967">Office Suite</span></span>
- <span data-ttu-id="51b68-968">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="51b68-968">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-may-08"></a><span data-ttu-id="51b68-971">Versão 2006: 08 de maio</span><span class="sxs-lookup"><span data-stu-id="51b68-971">Version 2006: May 08</span></span>
<span data-ttu-id="51b68-972">*Version 2006 (Build 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-972">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-974">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-974">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-975">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-975">Excel</span></span>

- <span data-ttu-id="51b68-976">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="51b68-976">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-977">Outlook</span></span>

- <span data-ttu-id="51b68-978">**Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca.</span><span class="sxs-lookup"><span data-stu-id="51b68-978">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="51b68-979">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-979">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="51b68-980">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="51b68-980">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-981">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-981">PowerPoint</span></span>

- <span data-ttu-id="51b68-982">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="51b68-982">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="51b68-983">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-983">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="51b68-984">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-984">Word</span></span>

- <span data-ttu-id="51b68-985">**Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.</span><span class="sxs-lookup"><span data-stu-id="51b68-985">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-988">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-988">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="51b68-989">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="51b68-989">Office Suite</span></span>

- <span data-ttu-id="51b68-990">Investigamos e resolvemos o problema em que uma implantação do Office 365 ProPlus via InTune era pausada após um desligamento do sistema operacional.</span><span class="sxs-lookup"><span data-stu-id="51b68-990">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-01"></a><span data-ttu-id="51b68-992">Versão 2005: 1 de maio</span><span class="sxs-lookup"><span data-stu-id="51b68-992">Version 2005: May 01</span></span>
<span data-ttu-id="51b68-993">*Version 2005 (Build 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="51b68-993">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-995">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-995">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-996">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-996">Outlook</span></span>

- <span data-ttu-id="51b68-997">**Links aprimorados no email:** quando você incluir um link a um arquivo, o nome do arquivo substituirá a URL.</span><span class="sxs-lookup"><span data-stu-id="51b68-997">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="51b68-998">Você pode alterar as permissões para que todos os destinatários tenham acesso.</span><span class="sxs-lookup"><span data-stu-id="51b68-998">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="51b68-999">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-999">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1002">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1002">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-1003">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1003">Excel</span></span>

- <span data-ttu-id="51b68-1004">Corrigimos um problema em que a tabela de dados do gráfico poderia processar incorretamente valores em um eixo de datas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1004">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="51b68-1005">Corrigimos um problema em que as quebras de página poderiam não ser desabilitadas após entrar no Layout da Página ou na Visualização da Quebra de Página.</span><span class="sxs-lookup"><span data-stu-id="51b68-1005">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="51b68-1006">Corrigimos um problema em que os estilos de linha do gráfico poderiam ser perdidos após ocultar e reexibir colunas com dados de série.</span><span class="sxs-lookup"><span data-stu-id="51b68-1006">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="51b68-1007">Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1007">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="51b68-1008">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="51b68-1008">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="51b68-1009">Corrigimos um problema em que a formatação personalizada em gráficos dinâmicos pode não ser salva quando a opção "inverter se negativo" estiver habilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1009">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="51b68-1010">Corrigimos um problema em que a formatação personalizada de um único ponto de dados em um Gráfico dinâmico não era salva se a opção "inverter se negativo" tivesse sido selecionada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1010">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="51b68-1011">Essa alteração corrige um problema em que o caractere ' @ ' carregado em um arquivo CSV resultaria na conversão da cadeia de caracteres após o caractere ' @ ' em uma fórmula.</span><span class="sxs-lookup"><span data-stu-id="51b68-1011">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="51b68-1012">Corrigimos um problema em que os valores decimais na função SEQUÊNCIA não eram arredondados corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1012">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1013">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1013">Outlook</span></span>

- <span data-ttu-id="51b68-1014">Soluciona um problema que causava falhas nos safelinks muito longos, nos quais os usuários clicavam no cliente do Outlook Desktop devido ao truncamento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1014">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="51b68-1015">Corrigimos um problema em que as pastas do Outlook com nomes que continham caracteres DBCS (conjunto de caracteres de dois bytes) poderiam desaparecer de forma intermitente ao sincronizar com o servidor.</span><span class="sxs-lookup"><span data-stu-id="51b68-1015">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="51b68-1016">Para que isso aconteça, o Outlook tinha que ser configurado com uma conta IMAP e estar sendo executado em um sistema com a localidade definida como japonês.</span><span class="sxs-lookup"><span data-stu-id="51b68-1016">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1017">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1017">PowerPoint</span></span>

- <span data-ttu-id="51b68-1018">Corrigimos um problema em que, se um usuário criasse um comentário sem postá-lo, fechasse o painel Comentários, abrisse uma nova janela, navegasse por vários slides, fechasse a janela e, por fim, reabrisse o painel Comentários na apresentação original, os comentários de rascunho não estariam disponíveis.</span><span class="sxs-lookup"><span data-stu-id="51b68-1018">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-1019">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-1019">Project</span></span>

- <span data-ttu-id="51b68-1020">Corrigimos um problema em que, se o Project estivesse conectado ao Project Web App e o separador decimal fosse uma vírgula, o método Adicionar TaskDependencies falharia quando o retardo fosse adicionado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1020">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1021">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1021">Word</span></span>

- <span data-ttu-id="51b68-1022">Corrigimos um problema em que a inserção de comentários em um documento no modo de colaboração nem sempre funcionava.</span><span class="sxs-lookup"><span data-stu-id="51b68-1022">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="51b68-1023">Essa alteração corrige um problema em que o cartão Pessoas piscava se o @ da menção estivesse selecionado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1023">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="51b68-1024">Corrigimos um problema em que o fechamento de um documento com comentários de rascunho perguntaria para o usuário se eles gostaria de fechar o documento sem salvar os comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-1024">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="51b68-1025">Cancelar a solicitação fechava o documento, em vez de deixá-lo aberto.</span><span class="sxs-lookup"><span data-stu-id="51b68-1025">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="51b68-1026">Corrigimos um problema em que a tradução de um comentário postado resultaria na mensagem de erro "ocorreu falha na inserção de texto traduzido".</span><span class="sxs-lookup"><span data-stu-id="51b68-1026">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="51b68-1027">No leitor Exibição da Web/Imersivo, clicar em uma dica rolaria a tela para cima, mesmo que ele já estivesse em exibição.</span><span class="sxs-lookup"><span data-stu-id="51b68-1027">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="51b68-1028">Isso foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="51b68-1028">This has been fixed.</span></span>
- <span data-ttu-id="51b68-1029">Corrigimos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, o arquivo poderia ser salvo com a extensão. docx e com o nome de arquivo WRO0004.docx, independentemente de qual nome o usuário inseriu, tornando o documento inutilizável.</span><span class="sxs-lookup"><span data-stu-id="51b68-1029">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2005-april-24"></a><span data-ttu-id="51b68-1031">Versão 2005: 24 de abril</span><span class="sxs-lookup"><span data-stu-id="51b68-1031">Version 2005: April 24</span></span>
<span data-ttu-id="51b68-1032">*Versão 2005 (Build 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1032">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1034">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1034">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-1035">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1035">Excel</span></span>
- <span data-ttu-id="51b68-1036">Essa alteração corrige um problema em que o valor do R-quadrado da linha de tendência do gráfico (no caso de interceptação em y forçado) estava incorreto, mesmo que a função PROJ.LIN retorne o valor correto.</span><span class="sxs-lookup"><span data-stu-id="51b68-1036">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="51b68-1037">Essa alteração corrige um problema em que a formatação personalizada da linha de tendência do gráfico nem sempre estava sendo salva.</span><span class="sxs-lookup"><span data-stu-id="51b68-1037">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1038">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1038">Outlook</span></span>
- <span data-ttu-id="51b68-1039">Corrigimos um problema em que o botão Categorizar de calendários de grupo na Faixa de Opções do Office estava desabilitado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1039">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="51b68-1040">Corrigimos um problema em que os clientes corporativos com pastas de grupo não implementadas ou que não funcionavam resultaria na exibição da mensagem “não respondendo” no Outlook.</span><span class="sxs-lookup"><span data-stu-id="51b68-1040">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1041">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1041">PowerPoint</span></span>
- <span data-ttu-id="51b68-1042">Corrigimos um problema em que passar o mouse sobre o símbolo de asterisco (\*) não exibia o nome de usuário e a data da última pessoa a atualizar o documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1042">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1043">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1043">Word</span></span>
- <span data-ttu-id="51b68-1044">Habilitar a opção "Mostrar indicadores" não exibia os indicadores.</span><span class="sxs-lookup"><span data-stu-id="51b68-1044">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="51b68-1045">Isso foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="51b68-1045">This has been fixed.</span></span>
- <span data-ttu-id="51b68-1046">Essa alteração corrige um problema em que o texto com hiperlinks pode não ser exibido se a opção "Mostrar códigos de campo em vez de seus valores" estiver habilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1046">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)


## <a name="version-2005-april-17"></a><span data-ttu-id="51b68-1048">Versão 2005: 17 de abril</span><span class="sxs-lookup"><span data-stu-id="51b68-1048">Version 2005: April 17</span></span>
<span data-ttu-id="51b68-1049">*Versão 2005 (Build 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1049">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1051">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1051">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-1052">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1052">Excel</span></span>
- <span data-ttu-id="51b68-1053">Foi aumentado o tamanho dos controles de edição de referência de célula na caixa de diálogo Barras de Erros Personalizadas usada com gráficos.</span><span class="sxs-lookup"><span data-stu-id="51b68-1053">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="51b68-1054">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="51b68-1054">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="51b68-1055">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="51b68-1055">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="51b68-1056">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="51b68-1056">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="51b68-1057">Essa alteração corrige um problema em que as informações de formatação condicional (CF) não estavam sendo salvas nos arquivos XLSB corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1057">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="51b68-1058">OneNote</span><span class="sxs-lookup"><span data-stu-id="51b68-1058">OneNote</span></span>
- <span data-ttu-id="51b68-1059">Foi corrigido um problema em que as quebras de linha estavam sendo armazenadas como guias verticais.</span><span class="sxs-lookup"><span data-stu-id="51b68-1059">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1060">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1060">Outlook</span></span>
- <span data-ttu-id="51b68-1061">Resolve um problema que fazia com que os usuários não pudessem adicionar um Grupo de Contatos Pessoais como participante da reunião.</span><span class="sxs-lookup"><span data-stu-id="51b68-1061">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="51b68-1062">Resolve um problema que fazia com que o assunto de reuniões a mais de 2 meses da data prevista não fosse exibido no Assistente de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1062">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="51b68-1063">Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="51b68-1063">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="51b68-1064">Foi adicionada a capacidade de impor a configuração de assinatura padrão S/MIME pela política de grupo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1064">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="51b68-1065">Resolve um problema que tornava inválidas as regras de exclusão criadas para caixas de correio diferentes da caixa de correio principal do usuário.</span><span class="sxs-lookup"><span data-stu-id="51b68-1065">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="51b68-1066">Resolve um problema que fazia com que os anexos fossem descartados ao encaminhar uma mensagem criptografada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1066">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-1067">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-1067">Project</span></span>
- <span data-ttu-id="51b68-1068">Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1068">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="51b68-1069">Corrigimos um problema em que o Project podia falhar ao alterar o campo de status do quadro em um projeto conectado a uma lista de tarefas do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="51b68-1069">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="51b68-1070">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="51b68-1070">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2004-april-10"></a><span data-ttu-id="51b68-1072">Versão 2004: 10 de abril</span><span class="sxs-lookup"><span data-stu-id="51b68-1072">Version 2004: April 10</span></span>
<span data-ttu-id="51b68-1073">*Versão 2004 (Build 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1073">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-1075">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1075">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="51b68-1076">Acessar</span><span class="sxs-lookup"><span data-stu-id="51b68-1076">Access</span></span>

- <span data-ttu-id="51b68-1077">**Ignore a caixa de diálogo Mostrar Tabela, vá diretamente para um painel de tarefas e simplifique a adição de tabelas a relacionamentos e consultas:** Adicione tabelas e consultas clicando em quatro guias, selecionando vários nomes, pesquisando por texto e arrastando de um painel de tarefas que permanece aberto enquanto você trabalha.</span><span class="sxs-lookup"><span data-stu-id="51b68-1077">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-1078">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1078">Excel</span></span>

- <span data-ttu-id="51b68-1079">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="51b68-1079">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="51b68-1080">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="51b68-1080">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1081">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1081">Outlook</span></span>

- <span data-ttu-id="51b68-1082">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="51b68-1082">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="51b68-1083">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="51b68-1083">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="51b68-1084">**Mantenha suas fotos em alta definição ao enviá-las como parte de um email:** Uma nova configuração do Outlook está disponível para limitar a compactação de imagem quando você envia fotos como parte do conteúdo de emails</span><span class="sxs-lookup"><span data-stu-id="51b68-1084">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1085">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1085">PowerPoint</span></span>

- <span data-ttu-id="51b68-1086">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="51b68-1086">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="51b68-1087">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="51b68-1087">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="51b68-1088">**Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="51b68-1088">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1089">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1089">Word</span></span>

- <span data-ttu-id="51b68-1090">**Seletor de conteúdo M365 Premium:** dê vida aos seus documentos!</span><span class="sxs-lookup"><span data-stu-id="51b68-1090">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="51b68-1091">Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="51b68-1091">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="51b68-1092">**Faça anotações na sua cópia particular:** crie anotações redigidas à mão para você mesmo, fazendo uma cópia privada de um documento compartilhado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1092">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="51b68-1093">Vá para Exibir > Criar uma cópia privada para começar.</span><span class="sxs-lookup"><span data-stu-id="51b68-1093">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1096">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1096">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-1097">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-1097">Access</span></span>

- <span data-ttu-id="51b68-1098">Foram corrigidos problemas com o redimensionamento e a atualização de tabelas no painel de tarefas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1098">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-1099">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1099">Excel</span></span>

- <span data-ttu-id="51b68-1100">Foi corrigido um problema em que a seleção de um intervalo de células em uma planilha resultava na seleção de uma única célula.</span><span class="sxs-lookup"><span data-stu-id="51b68-1100">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="51b68-1101">Foi corrigido um problema que podia fazer o Excel parar de responder quando se reduzia o tamanho de um gráfico com alguns intervalos de eixo x.</span><span class="sxs-lookup"><span data-stu-id="51b68-1101">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="51b68-1102">Foi corrigido um problema em que a inserção de um modelo de gráfico definido pelo usuário poderia resultar no salvamento dele como um gráfico de colunas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1102">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="51b68-1103">Foi corrigido um problema em que os rótulos de Dados de gráficos eram exibidos como em branco quando as células de dados subjacentes não possuíam uma legenda.</span><span class="sxs-lookup"><span data-stu-id="51b68-1103">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="51b68-1104">Foi corrigido um problema em que, em uma planilha do Excel com referência de célula L1C1 habilitada que estivesse sendo criada em coautoria/compartilhada, passar o mouse sobre o ícone de presença do usuário não exibia a referência de célula ativa no modo L1C1.</span><span class="sxs-lookup"><span data-stu-id="51b68-1104">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1105">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1105">Outlook</span></span>

- <span data-ttu-id="51b68-1106">Resolve um problema que fazia as categorias desaparecerem ocasionalmente das mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="51b68-1106">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="51b68-1107">Resolve um problema que fazia com que os representantes vissem diferentes hierarquias de pastas em computadores diferentes para caixas de correio compartilhadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1107">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="51b68-1108">Resolve um problema que fazia com que os usuários experimentassem uma falha ao tentar exibir as propriedades de um Formulário Organizacional.</span><span class="sxs-lookup"><span data-stu-id="51b68-1108">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="51b68-1109">Resolve um problema que fazia com que alguns lembretes falhassem ao alterar o fuso horário em um computador.</span><span class="sxs-lookup"><span data-stu-id="51b68-1109">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1110">PowerPoint</span></span>

- <span data-ttu-id="51b68-1111">Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.</span><span class="sxs-lookup"><span data-stu-id="51b68-1111">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="51b68-1112">Corrigimos um problema em que copiar texto do Excel para o PowerPoint poderia alterar a formatação.</span><span class="sxs-lookup"><span data-stu-id="51b68-1112">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="51b68-1113">Essa alteração corrige um problema em que encontrar caracteres especiais usando "localizar somente palavras inteiras" nem sempre funcionava como esperado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1113">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-1114">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-1114">Project</span></span>

- <span data-ttu-id="51b68-1115">Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1115">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1116">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1116">Word</span></span>

- <span data-ttu-id="51b68-1117">Essa alteração corrige um problema em que passar o cursor do mouse sobre uma dica não realçava o seu cartão.</span><span class="sxs-lookup"><span data-stu-id="51b68-1117">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="51b68-1118">Essa alteração corrige um problema que fazia com que o texto em formas agrupadas desaparecesse temporariamente ao usar a ferramenta Seleção de laço.</span><span class="sxs-lookup"><span data-stu-id="51b68-1118">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="51b68-1119">Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.</span><span class="sxs-lookup"><span data-stu-id="51b68-1119">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="51b68-1120">Essa alteração corrige um problema no modo de exibição de duas páginas em que, ao criar um comentário, a âncora de comentário nem sempre chegava a ser exibida.</span><span class="sxs-lookup"><span data-stu-id="51b68-1120">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="51b68-1121">Corrigido um problema em que, para um parágrafo cujo estilo é um ancestral de um estilo vinculado a uma lista, a numeração dessa lista poderia ser perdida.</span><span class="sxs-lookup"><span data-stu-id="51b68-1121">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-27"></a><span data-ttu-id="51b68-1123">Versão 2004: 27 de março</span><span class="sxs-lookup"><span data-stu-id="51b68-1123">Version 2004: March 27</span></span>
<span data-ttu-id="51b68-1124">*Versão 2004 (Build 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1124">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-1126">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1126">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1127">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1127">Outlook</span></span>

- <span data-ttu-id="51b68-1128">**Nova opção para desabilitar sugestões de @menções ao redigir emails:** você acha o seletor de @menções mais irritante do que útil?</span><span class="sxs-lookup"><span data-stu-id="51b68-1128">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="51b68-1129">Agora, você pode desativá-lo, se preferir.</span><span class="sxs-lookup"><span data-stu-id="51b68-1129">Now you can turn it off if you prefer.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1132">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1132">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1133">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1133">Outlook</span></span>
- <span data-ttu-id="51b68-1134">Corrige um problema que fazia com que o botão “Salvar na nuvem” não aparecesse nas Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1134">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="51b68-1135">Corrige um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não tem permissão de proprietário na mensagem que está sendo respondida.</span><span class="sxs-lookup"><span data-stu-id="51b68-1135">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="51b68-1136">Corrige um problema que fazia com que os usuários não conseguissem adicionar anexos adicionais de um local da Web a uma reunião criada anteriormente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1136">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1137">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1137">PowerPoint</span></span>
- <span data-ttu-id="51b68-1138">Essa alteração corrige um erro que poderia fazer com que arquivos do PowerPoint com emojis falhassem ao salvar.</span><span class="sxs-lookup"><span data-stu-id="51b68-1138">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-1139">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-1139">Project</span></span>
- <span data-ttu-id="51b68-1140">Correção de um problema em que, se ‘CustomFieldValueListGetItem’ fosse executado e uma tabela de pesquisa do campo personalizado não existisse, uma tabela de pesquisa vazia era criada, mesmo que não devesse ser.</span><span class="sxs-lookup"><span data-stu-id="51b68-1140">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1141">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1141">Word</span></span>
- <span data-ttu-id="51b68-1142">Essa alteração corrige um problema em várias páginas selecionadas no menu Exibir, onde o painel de comentários poderia ser exibido em branco.</span><span class="sxs-lookup"><span data-stu-id="51b68-1142">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-20"></a><span data-ttu-id="51b68-1144">Versão 2004: 20 de março</span><span class="sxs-lookup"><span data-stu-id="51b68-1144">Version 2004: March 20</span></span>
<span data-ttu-id="51b68-1145">*Versão 2004 (Build 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1145">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-1147">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1147">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1148">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1148">Outlook</span></span>

- <span data-ttu-id="51b68-1149">**Atualização visual de calendário:** ano passado, trouxemos uma experiência de email atualizada e, esse ano, é a vez do calendário ser transformado!</span><span class="sxs-lookup"><span data-stu-id="51b68-1149">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="51b68-1150">As atualizações são novas, mas familiarmente, como um usuário experiente do Outlook, você pode entrar e ser mais produtivo imediatamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1150">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="51b68-1151">**Ajude a proteger os dados de seu grupo:** o rótulo de sensibilidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe</span><span class="sxs-lookup"><span data-stu-id="51b68-1151">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1152">PowerPoint</span></span>

- <span data-ttu-id="51b68-1153">**Atualizar slides durante a apresentação de slides:** os slides de atualização alterados por outros autores durante a sua apresentação.</span><span class="sxs-lookup"><span data-stu-id="51b68-1153">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1156">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1156">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-1157">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1157">Excel</span></span>

- <span data-ttu-id="51b68-1158">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1158">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1159">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1159">Outlook</span></span>

- <span data-ttu-id="51b68-1160">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1160">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="51b68-1161">Essa alteração corrige um problema em que as últimas alterações em rascunhos de emails não foram atualizadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1161">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="51b68-1162">Correção de um problema em que clicar com o botão direito do mouse em um arquivo e usar ' enviar para ' não funcionará.</span><span class="sxs-lookup"><span data-stu-id="51b68-1162">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="51b68-1163">Correção de um problema em que o usuário tinha um caminho de pesquisa personalizado para o catálogo de endereços, o escopo de resolução de nome do Outlook seria limitado ao caminho personalizado, em vez de incluir a lista de endereços global (GAL).</span><span class="sxs-lookup"><span data-stu-id="51b68-1163">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="51b68-1164">Correção de um problema em que, em um conjunto de resultados de pesquisa retornados, classificar os resultados por categorias, não exibiria as cores da categoria.</span><span class="sxs-lookup"><span data-stu-id="51b68-1164">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-1165">Projeto</span><span class="sxs-lookup"><span data-stu-id="51b68-1165">Project</span></span>

- <span data-ttu-id="51b68-1166">Correção de um problema em que o evento de "ProjectBeforeTaskChange ' aplicativos Visual Basic (VBA) não foi disparado quando um usuário clica no botão" inativo "encontrado na faixa de opções tarefas no agrupamento de agendamento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1166">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="51b68-1167">Se você definir os detalhes da predecessora ou da sucessora de dentro de um modo de exibição de tipo de formulário, o evento ProjectBeforeTaskChange Visual Basic Applications (VBA) não capturaria as alterações.</span><span class="sxs-lookup"><span data-stu-id="51b68-1167">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="51b68-1168">Por exemplo, se você excluiu uma dependência e clicou em OK no formulário, o evento não foi acionado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1168">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="51b68-1169">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="51b68-1169">This behavior has been fixed.</span></span>

- <span data-ttu-id="51b68-1170">Correção de um problema em que os valores mais recentes para o custo real do trabalho realizado (CRTR) não seriam exibidos depois de fazer uma alteração, como uma alteração de data.</span><span class="sxs-lookup"><span data-stu-id="51b68-1170">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="51b68-1171">Correção de um problema em que abrir um projeto usando o menu mais recentemente utilizado (MRU) abriu o arquivo do projeto com acesso de leitura/gravação.</span><span class="sxs-lookup"><span data-stu-id="51b68-1171">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="51b68-1172">Essa alteração corrige um problema em que, se você criou uma tarefa manual com uma data de início e uma hora (mas não duração), ela seria exibida com um horário incorreto na linha do tempo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1172">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="51b68-1173">Correção de um problema em que imprimir uma linha do tempo usando o calendário islâmico resultaria em um mês sendo ignorado ou duplicado no modo de exibição de impressão.</span><span class="sxs-lookup"><span data-stu-id="51b68-1173">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="51b68-1174">Essa alteração resolve um problema em que trabalhar no planejador de equipe com objetos GDI pode resultar na alocação total de objetos GDI e criar condições de pouca memória.</span><span class="sxs-lookup"><span data-stu-id="51b68-1174">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1175">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1175">Word</span></span>

- <span data-ttu-id="51b68-1176">Correção de um problema em que a funcionalidade para postar comentários foi desabilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1176">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="51b68-1177">Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1177">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="51b68-1178">Essa alteração resolve um problema em que o gerente de conta não despacha mensagens, resultando em um travamento com aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="51b68-1178">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="51b68-1179">Essa alteração corrige um problema em que o Sumário seria atualizado com estilos de título que não estão presentes no documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1179">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="51b68-1180">Correção de um problema em que as assinaturas digitais salvas em documentos do Word seriam removidas durante a mala direta dos documentos.</span><span class="sxs-lookup"><span data-stu-id="51b68-1180">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-13"></a><span data-ttu-id="51b68-1182">Versão 2004: 13 de março</span><span class="sxs-lookup"><span data-stu-id="51b68-1182">Version 2004: March 13</span></span>
<span data-ttu-id="51b68-1183">*Versão 2004 (Build 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1183">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="51b68-1185">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1185">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1186">Excel</span></span>
- <span data-ttu-id="51b68-1187">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1187">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="51b68-1188">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="51b68-1188">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="51b68-1189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1189">PowerPoint</span></span>
- <span data-ttu-id="51b68-1190">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1190">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="51b68-1191">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="51b68-1191">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="51b68-1192">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1192">Word</span></span>
- <span data-ttu-id="51b68-1193">**Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1193">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="51b68-1194">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="51b68-1194">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1197">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1197">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="51b68-1198">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-1198">Access</span></span>
- <span data-ttu-id="51b68-1199">Correção de um problema em que as versões internacionais do Access exibiam as cadeias de caracteres em inglês na interface do usuário.</span><span class="sxs-lookup"><span data-stu-id="51b68-1199">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-1200">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1200">Excel</span></span>
- <span data-ttu-id="51b68-1201">Corrigido um problema de desempenho que os usuários podem ter experimentado ao editar por programação um intervalo grande de células.</span><span class="sxs-lookup"><span data-stu-id="51b68-1201">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="51b68-1202">Corrigido um problema de desempenho que acontecia ao abrir arquivos csv em ambientes japoneses.</span><span class="sxs-lookup"><span data-stu-id="51b68-1202">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1203">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1203">Outlook</span></span>
- <span data-ttu-id="51b68-1204">Soluciona um problema que fazia com que a data "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um e-mail ou salvá-lo, arrastando e soltando-o (ao contrário de um menu).</span><span class="sxs-lookup"><span data-stu-id="51b68-1204">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="51b68-1205">Resolve um problema que fez com que pressionar Enter no painel de localização expandido falhe ao iniciar uma pesquisa, exigindo que os usuários cliquem no botão de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="51b68-1205">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="51b68-1206">Correção de um problema em que a pesquisa não exibe informações sobre os usuários quando a opção "mostrar fotografias de usuário quando disponíveis" está desabilitada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1206">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="51b68-1207">Project</span><span class="sxs-lookup"><span data-stu-id="51b68-1207">Project</span></span>
- <span data-ttu-id="51b68-1208">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1208">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="51b68-1209">Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="51b68-1209">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1210">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1210">Word</span></span>
- <span data-ttu-id="51b68-1211">Corrigido um problema ao digitar ou editar um comentário e usar Ctrl + A resultaria na seleção de texto na tela, em vez de selecionar o texto apenas dentro do cartão de comentário.</span><span class="sxs-lookup"><span data-stu-id="51b68-1211">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="51b68-1212">Resolvemos um problema em que o alinhamento de palavras em um documento fica embaralhado quando você tenta editar após imprimir usando a impressão rápida.</span><span class="sxs-lookup"><span data-stu-id="51b68-1212">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="51b68-1213">Consertamos um problema ao mesclar dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1213">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="51b68-1214">Correção de um problema em que a marcação de revisões envolvendo equações podem resultar em uma falha ao salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1214">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-06"></a><span data-ttu-id="51b68-1216">Versão 2003: 06 de março</span><span class="sxs-lookup"><span data-stu-id="51b68-1216">Version 2003: March 06</span></span>
<span data-ttu-id="51b68-1217">*Versão 2003 (Build 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1217">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1219">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1219">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1220">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1220">Outlook</span></span>

- <span data-ttu-id="51b68-1221">Foi corrigido um problema em que a criação de uma regra com o Outlook Web Access não persistia no servidor Exchange e resultava em um conflito.</span><span class="sxs-lookup"><span data-stu-id="51b68-1221">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="51b68-1222">Foi corrigido um problema em que o Outlook no modo escuro não exibia a lista suspensa do campo 'De:'.</span><span class="sxs-lookup"><span data-stu-id="51b68-1222">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="51b68-1223">Resolve um problema que fazia com que os usuários não conseguissem anexar um arquivo à mensagem de email por meio do explorador de arquivos se esse arquivo estivesse aberto em outro aplicativo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1223">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1224">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1224">PowerPoint</span></span>

- <span data-ttu-id="51b68-1225">Foi corrigido um problema em que as miniaturas recomendadas acendiam e apagavam ao passar o mouse sobre elas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1225">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="51b68-1226">Em alguns casos, isso pode causar uma falha no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-1226">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1227">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1227">Word</span></span>

- <span data-ttu-id="51b68-1228">Foi corrigido um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="51b68-1228">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-1229">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="51b68-1229">Office Suite</span></span>

- <span data-ttu-id="51b68-1230">Foi corrigido um problema com o Word/Excel/PowerPoint, em que o nome de usuário principal (UPN) não diferenciava maiúsculas de minúsculas, resultando em menos falhas ao trabalhar com arquivos no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="51b68-1230">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="51b68-1231">Foi corrigido um problema estético em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não era afetada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1231">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

## <a name="version-2003-february-28"></a><span data-ttu-id="51b68-1234">Versão 2003: 28 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="51b68-1234">Version 2003: February 28</span></span>
<span data-ttu-id="51b68-1235">*Versão 2003 (Criação 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1235">*Version 2003 (Build 12619.20002)*</span></span>

<span data-ttu-id="51b68-1236"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="51b68-1236">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="51b68-1237">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1237">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1238">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1238">Outlook</span></span>

- <span data-ttu-id="51b68-1239">**Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows.</span><span class="sxs-lookup"><span data-stu-id="51b68-1239">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="51b68-1240">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="51b68-1240">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="51b68-1241">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1241">PowerPoint</span></span>

- <span data-ttu-id="51b68-1242">**Tinta aprimorada para moldar a experiência de diagramação:** Desenhe diagramas melhores e faça com que seja convertidos para que você possa manipular objetos do escritório [Saiba mais](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="51b68-1242">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1245">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1245">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="51b68-1246">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1246">Excel</span></span>

- <span data-ttu-id="51b68-1247">Corrido um problema em que o texto em uma segmentação de dados não é dimensionado corretamente na visualização de impressão.</span><span class="sxs-lookup"><span data-stu-id="51b68-1247">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1248">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1248">Outlook</span></span>

- <span data-ttu-id="51b68-1249">Soluciona um problema que fazia com que a data "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um e-mail ou salvá-lo, arrastando e soltando-o (ao contrário de um menu).</span><span class="sxs-lookup"><span data-stu-id="51b68-1249">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1250">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1250">Word</span></span>

- <span data-ttu-id="51b68-1251">Corrigido um problema que, ao percorrer um cartão de comentários, o foco na caixa de edição de comentários não ficava visível.</span><span class="sxs-lookup"><span data-stu-id="51b68-1251">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="51b68-1252">Inserir um controle (como um Controle de Conteúdo de Texto) em uma equação e salvar e abrir o arquivo resulta em um erro de conteúdo não legível.</span><span class="sxs-lookup"><span data-stu-id="51b68-1252">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="51b68-1253">Corrigido um problema em que o salvamento de um arquivo anteriormente protegido por senha em um armazenamento em nuvem não funcionava.</span><span class="sxs-lookup"><span data-stu-id="51b68-1253">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-1254">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="51b68-1254">Office Suite</span></span>

- <span data-ttu-id="51b68-1255">Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.</span><span class="sxs-lookup"><span data-stu-id="51b68-1255">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-february-21"></a><span data-ttu-id="51b68-1257">Versão 2003: 21 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="51b68-1257">Version 2003: February 21</span></span>
<span data-ttu-id="51b68-1258">*Versão 2003 (Build 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1258">*Version 2003 (Build 12615.20000)*</span></span>

<span data-ttu-id="51b68-1259"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="51b68-1259">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="51b68-1260">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1260">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="51b68-1261">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="51b68-1261">Office Suite</span></span>

- <span data-ttu-id="51b68-1262">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="51b68-1262">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1265">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1265">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-1266">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1266">Excel</span></span>
- <span data-ttu-id="51b68-1267">Corrigido um problema que os usuários podem ter ao renomear medidas de tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="51b68-1267">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="51b68-1268">Corrigido um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1268">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="51b68-1269">Corrigido um problema que fazia a interface do usuário piscar quando os usuários executavam uma macro que interagia com a faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="51b68-1269">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="51b68-1270">Corrigido um problema em que os arquivos CSV eram carregados incorretamente quando a primeira palavra no arquivo era TABLE.</span><span class="sxs-lookup"><span data-stu-id="51b68-1270">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="51b68-1271">Corrigido um problema em que os usuários podem ter sofrido falhas ao alternar entre duas pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="51b68-1271">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1272">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1272">Outlook</span></span>
- <span data-ttu-id="51b68-1273">Corrigido um problema que fazia com que os usuários não conseguissem abrir mensagens de pasta pública quando o Outlook permanecia em execução durante a noite.</span><span class="sxs-lookup"><span data-stu-id="51b68-1273">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="51b68-1274">Corrigida uma condição de corrida em que os botões 'Permitir' e 'Negar' na página de permissões são desativados durante o fluxo de trabalho de autenticação da adição de uma conta do Gmail.</span><span class="sxs-lookup"><span data-stu-id="51b68-1274">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="51b68-1275">Resolvido um problema que fazia o Outlook gerar de forma inesperada a saída do log em alguns cenários, mesmo quando o log estava desativado.</span><span class="sxs-lookup"><span data-stu-id="51b68-1275">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1276">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1276">Word</span></span>
- <span data-ttu-id="51b68-1277">Corrigido um problema em que os cartões de comentários nem sempre são destacados quando um ponteiro do mouse passa sobre o cartão de comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-1277">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="51b68-1278">Durante uma sessão ativa de coautoria de documentos, adicionar uma imagem diretamente a um cartão de comentários pode resultar na adição de uma marca.</span><span class="sxs-lookup"><span data-stu-id="51b68-1278">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="51b68-1279">Esse problema foi corrigido.</span><span class="sxs-lookup"><span data-stu-id="51b68-1279">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-1280">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="51b68-1280">Office Suite</span></span>
- <span data-ttu-id="51b68-1281">Ao usar as propriedades do MultiChoice/Lookup/Managed-metadata com documentos do Word/Excel/PowerPoint e salvá-los em uma biblioteca de documentos do SharePoint, essas propriedades anteriormente eram limitadas a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="51b68-1281">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="51b68-1282">Quando essas propriedades excederem 255 caracteres, esses documentos não puderam ser salvos.</span><span class="sxs-lookup"><span data-stu-id="51b68-1282">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="51b68-1283">Com essa mudança, esse limite aumentou para 2048 caracteres.</span><span class="sxs-lookup"><span data-stu-id="51b68-1283">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-february-14"></a><span data-ttu-id="51b68-1285">Versão 2003: 14 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="51b68-1285">Version 2003: February 14</span></span>
<span data-ttu-id="51b68-1286">*Versão 2003 (Build 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1286">*Version 2003 (Build 12607.20000)*</span></span>

<span data-ttu-id="51b68-1287"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="51b68-1287">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="51b68-1288">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1288">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1289">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1289">Outlook</span></span>

- <span data-ttu-id="51b68-1290">**Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar?</span><span class="sxs-lookup"><span data-stu-id="51b68-1290">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="51b68-1291">O Outlook agora detecta isso e ajuda você a se conectar.</span><span class="sxs-lookup"><span data-stu-id="51b68-1291">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1292">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1292">Word</span></span>

- <span data-ttu-id="51b68-1293">**Encontre o Editor de Tinta na caixa de ferramentas de desenho:** Selecione Desenhar e, em seguida, escolha a caneta do Editor de Tinta para editar seu documento com o dedo ou uma caneta digital.</span><span class="sxs-lookup"><span data-stu-id="51b68-1293">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="51b68-1294">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="51b68-1294">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="51b68-1295">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="51b68-1295">Office Suite</span></span>

- <span data-ttu-id="51b68-1296">**Ícones mais claros da barra de status:** Agora é mais fácil visualizar os ícones da barra de status.</span><span class="sxs-lookup"><span data-stu-id="51b68-1296">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1299">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1299">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="51b68-1300">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1300">Outlook</span></span>

- <span data-ttu-id="51b68-1301">Solucionamos um problema que fazia com que os usuários perdessem o acesso à caixa de diálogo de permissões de calendário "Opções de Disponibilidade".</span><span class="sxs-lookup"><span data-stu-id="51b68-1301">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="51b68-1302">Correção de um problema que pode resultar no alerta: "Infelizmente, estamos com problemas para abrir este item" ao abrir algumas instâncias de reunião recorrente enviadas de um fuso horário diferente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1302">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="51b68-1303">Solucionamos um problema que pode fazer com que os usuários não consigam reabrir um arquivo. msg depois de arrastar e soltar um anexo da mensagem.</span><span class="sxs-lookup"><span data-stu-id="51b68-1303">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="51b68-1304">Correção de um problema em que, após carregar um anexo de arquivo do Outlook para o OneDrive, poderia resultar no nome do arquivo sendo alterado se o nome do anexo contivesse parênteses.</span><span class="sxs-lookup"><span data-stu-id="51b68-1304">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1305">PowerPoint</span></span>

- <span data-ttu-id="51b68-1306">Correção de um problema que pode resultar em uma falha no salvamento de um documento no PowerPoint ou no Word com um gráfico do Excel.</span><span class="sxs-lookup"><span data-stu-id="51b68-1306">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1307">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1307">Word</span></span>

- <span data-ttu-id="51b68-1308">Correção de um problema em que imagens em documentos perdem a transparência quando exportadas para PDF.</span><span class="sxs-lookup"><span data-stu-id="51b68-1308">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-february-07"></a><span data-ttu-id="51b68-1310">Versão 2002: 7 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="51b68-1310">Version 2002: February 07</span></span>
<span data-ttu-id="51b68-1311">*Versão 2002 (Build 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="51b68-1311">*Version 2002 (Build 12527.20040)*</span></span>

<span data-ttu-id="51b68-1312"> (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS</span><span class="sxs-lookup"><span data-stu-id="51b68-1312">[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="51b68-1313">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="51b68-1313">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="51b68-1314">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-1314">Access</span></span>

- <span data-ttu-id="51b68-1315">**Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la.</span><span class="sxs-lookup"><span data-stu-id="51b68-1315">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="51b68-1316">Pesquise e substitua o texto no SQL View.</span><span class="sxs-lookup"><span data-stu-id="51b68-1316">Search and replace text in SQL View.</span></span> <span data-ttu-id="51b68-1317">Selecione várias tabelas na janela Relações.</span><span class="sxs-lookup"><span data-stu-id="51b68-1317">Select multiple tables in the Relationships window.</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="51b68-1320">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="51b68-1320">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="51b68-1321">Access</span><span class="sxs-lookup"><span data-stu-id="51b68-1321">Access</span></span>

- <span data-ttu-id="51b68-1322">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="51b68-1322">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="51b68-1323">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="51b68-1323">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="51b68-1324">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="51b68-1324">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="51b68-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="51b68-1325">Excel</span></span>

- <span data-ttu-id="51b68-1326">Corrigido um problema em que o Excel falhava ao usar colunas de texto em com matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="51b68-1326">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="51b68-1327">Outlook</span><span class="sxs-lookup"><span data-stu-id="51b68-1327">Outlook</span></span>

- <span data-ttu-id="51b68-1328">Corrigido um problema em que a rolagem no calendário com a exibição do mês não mostrava eventos anteriores do calendário.</span><span class="sxs-lookup"><span data-stu-id="51b68-1328">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="51b68-1329">Soluciona um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="51b68-1329">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="51b68-1330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="51b68-1330">PowerPoint</span></span>

- <span data-ttu-id="51b68-1331">Corrigido um problema em que, após fechar um arquivo, o PowerPoint não o removia imediatamente da coleção Apresentações, se houvesse algum manipulador de eventos em execução.</span><span class="sxs-lookup"><span data-stu-id="51b68-1331">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="51b68-1332">Portanto, o número de apresentações abertas relatadas pelo modelo de objeto ficava incorreto, e o desligamento do PowerPoint era impedido.</span><span class="sxs-lookup"><span data-stu-id="51b68-1332">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="51b68-1333">Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.</span><span class="sxs-lookup"><span data-stu-id="51b68-1333">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="51b68-1334">Word</span><span class="sxs-lookup"><span data-stu-id="51b68-1334">Word</span></span>

- <span data-ttu-id="51b68-1335">Às vezes, atualizar e rolar um índice pode exibir uma área cinza sobre o documento.</span><span class="sxs-lookup"><span data-stu-id="51b68-1335">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="51b68-1336">Corrigido um problema em que, se um documento fosse usado em coautoria, a versão de rascunho de um comentário raiz poderia não ser preservada.</span><span class="sxs-lookup"><span data-stu-id="51b68-1336">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="51b68-1337">Corrigido um problema em que alternar entre os cartões de comentários às vezes exibia o comentário selecionado inicialmente com um destaque de seleção.</span><span class="sxs-lookup"><span data-stu-id="51b68-1337">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="51b68-1338">Corrigido um problema em que o uso de "Procurar" para salvar um arquivo não funcionava se um comentário fosse escrito, mas não postado, e o usuário tentasse salvar o arquivo.</span><span class="sxs-lookup"><span data-stu-id="51b68-1338">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="51b68-1339">Com o SlideTrack habilitado e o painel de comentários fechado, Ctrl+Alt+M pode não abrir o painel de comentários.</span><span class="sxs-lookup"><span data-stu-id="51b68-1339">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="51b68-1340">Corrigido um problema ao adicionar @menção em uma tabela poderia gerar a mensagem de erro: "Uma tabela neste documento foi corrompida".</span><span class="sxs-lookup"><span data-stu-id="51b68-1340">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="51b68-1341">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="51b68-1341">Office Suite</span></span>

- <span data-ttu-id="51b68-1342">Resolve um problema que pode ter causado a instalação incorreta do pacote de ferramentas de revisão Nynorsk da Noruega (nn-no).</span><span class="sxs-lookup"><span data-stu-id="51b68-1342">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|DevMain|Insiders| |16.0.13617.20002|version-2101-december-25|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13610.20002|version-2101-december-18|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13604.20000|version-2101-august-11|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13530.20000|version-2012-december-04|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13519.20000|version-2012-november-27|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13512.20000|version-2012-november-20|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13510.20004|version-2012-november-13|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13430.20000|version-2012-november-06|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13426.20004|version-2011-october-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13415.20002|version-2011-october-23|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

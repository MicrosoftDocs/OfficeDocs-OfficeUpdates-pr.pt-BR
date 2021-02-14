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
description: Fornece aos profissionais de TI as notas de versão para as versões do Canal Semestral do Microsoft 365 Apps em 2020
ms.openlocfilehash: 6b50195e2e84292b0b4b1e259254592f2c4a591b
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173650"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="3f30e-103">Notas de versão para lançamentos do Canal Empresarial Semestral</span><span class="sxs-lookup"><span data-stu-id="3f30e-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="3f30e-104">Estas notas de versão fornecem informações dos novos recursos e atualizações não relacionados à segurança que estão inclusos nas atualizações do Canal Empresarial Semestral do Microsoft 365 Apps para Grandes Empresas, Microsoft 365 Apps para Pequenos e Médios Negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="3f30e-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="3f30e-105">Estamos fazendo algumas alterações nos canais de atualização para o Microsoft 365 Apps, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="3f30e-106">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="3f30e-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="3f30e-107">O OneNote 2016 já está incluído por padrão quando um usuário no Canal Empresarial Semestral baixar e instalar o Microsoft 365 Apps no Windows 10 do Portal do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2008-february-09"></a><span data-ttu-id="3f30e-109">Versão 2008: 09 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-109">Version 2008: February 09</span></span>
<span data-ttu-id="3f30e-110">*Versão 2008 (Build 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-110">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="3f30e-111">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-113">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-114">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-114">Excel</span></span>

- <span data-ttu-id="3f30e-115">Corrigido um problema em que o Excel fechava inesperadamente ao abrir arquivos UNC com atributos de arquivo inválidos (data de criação, data de modificação, etc.)</span><span class="sxs-lookup"><span data-stu-id="3f30e-115">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="3f30e-116">Corrigido um problema em que as configurações decimais e de milhares de separadores não eram transferidas ao copiar um gráfico do Excel e colar no Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-116">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="3f30e-117">Corrigimos um problema onde o desempenho da execução de uma macro envolvendo a formatação de intervalo da Tabela Dinâmica se agravaria a cada vez que a macro fosse executada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-117">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="3f30e-118">Corrigimos um problema em que as regras de formatação condicional eram descartadas ao copiar ou mover planilhas para outra pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-118">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="3f30e-119">Corrigimos um problema em que os usuários não podiam aplicar rótulos de confidencialidade aos arquivos do Excel quando a tela inicial da inicialização do aplicativo estava desabilitada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-119">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="3f30e-120">Corrigimos um problema ao abrir um arquivo na nuvem a partir da pasta de Sincronização do Microsoft OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-120">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f30e-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-121">Outlook</span></span>

- <span data-ttu-id="3f30e-122">Corrigido um problema que fazia com que o Outlook parasse de funcionar esporadicamente ao adicionar ou salvar anexos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-122">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f30e-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-123">PowerPoint</span></span>

- <span data-ttu-id="3f30e-124">Corrigimos um problema em que o comando de tamanho de fonte, adicionado ao QAT, completava automaticamente para o tamanho de fonte definido mais próximo ao atualizá-lo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-124">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="3f30e-125">Corrigido um problema onde copiar e colar um slide com a opção "manter a formatação da fonte" às vezes copiava inesperadamente sobre um novo slide mestre.</span><span class="sxs-lookup"><span data-stu-id="3f30e-125">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="3f30e-126">Palavra</span><span class="sxs-lookup"><span data-stu-id="3f30e-126">Word</span></span>

- <span data-ttu-id="3f30e-127">Corrigimos um problema no Controle de Alterações que às vezes a abertura de um documento do Word exibia uma caixa de diálogo de erro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-127">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="3f30e-128">Corrigimos um problema ao abrir um arquivo na nuvem a partir da pasta de Sincronização do Microsoft OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-128">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f30e-129">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-129">Office Suite</span></span>

- <span data-ttu-id="3f30e-130">Corrigido um problema que impedia a abertura bem-sucedida de um arquivo no Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-130">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="3f30e-131">Corrigido um problema onde documentos contendo contornos de esboços aplicados aos conectores por meio do Pincel de Formatação poderiam se corromper.</span><span class="sxs-lookup"><span data-stu-id="3f30e-131">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-february-09"></a><span data-ttu-id="3f30e-133">Versão 2002: 09 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-133">Version 2002: February 09</span></span>
<span data-ttu-id="3f30e-134">*Versão 2002 (Build 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-134">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="3f30e-135">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-135">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-137">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-137">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="3f30e-138">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-138">Office Suite</span></span>

- <span data-ttu-id="3f30e-139">Corrigido um problema onde documentos contendo contornos de esboços aplicados aos conectores por meio do Pincel de Formatação poderiam se corromper.</span><span class="sxs-lookup"><span data-stu-id="3f30e-139">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-february-09"></a><span data-ttu-id="3f30e-141">Versão 1908: 09 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-141">Version 1908: February 09</span></span>
<span data-ttu-id="3f30e-142">*Versão 1908 (Build 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-142">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="3f30e-143">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-143">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="3f30e-144">Versão 2008: 12 de janeiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-144">Version 2008: January 12</span></span>
<span data-ttu-id="3f30e-145">*Versão 2008 (Build 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-145">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="3f30e-146">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="3f30e-148">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="3f30e-148">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-149">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-149">Access</span></span>

- <span data-ttu-id="3f30e-150">**Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la.</span><span class="sxs-lookup"><span data-stu-id="3f30e-150">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="3f30e-151">Pesquise e substitua o texto no SQL View.</span><span class="sxs-lookup"><span data-stu-id="3f30e-151">Search and replace text in SQL View.</span></span> <span data-ttu-id="3f30e-152">Selecione várias tabelas na janela Relações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-152">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="3f30e-153">**Adicionar tabelas com menos cliques:** usar o painel de tarefas Adicionar Tabelas, que permanece aberto enquanto você trabalha, para adicionar tabelas a relações e consultas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-153">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="3f30e-154">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-154">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="3f30e-155">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-155">Excel</span></span>

- <span data-ttu-id="3f30e-156">**Suas funções favoritas do Excel acabaram de ficar mais rápidas:** As funções SOMASES, MÉDIASES, CONT.SES, MÁXIMOSES e MÍNIMOSES estão muito mais rápidas do que nunca.</span><span class="sxs-lookup"><span data-stu-id="3f30e-156">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="3f30e-157">Chegue ao resultado final mais rapidamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-157">Get to the bottom line more quickly.</span></span> <span data-ttu-id="3f30e-158">Experimente agora.</span><span class="sxs-lookup"><span data-stu-id="3f30e-158">Try one now.</span></span>

- <span data-ttu-id="3f30e-159">**Aprimoramentos no Realtimedata (RTD):** No Office 365 canal mensal versão 2002 ou posterior, a função do Excel (RealTimeData) é muito mais rápida ao calcular os dados na planilha do que o Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="3f30e-159">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="3f30e-160">Removemos os gargalos na sua memória e estruturas de dados subjacentes, bem como o tornamos thread-safe para permitir o seu cálculo em todas as threads disponíveis de recálculo multithreaded (MTR).</span><span class="sxs-lookup"><span data-stu-id="3f30e-160">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="3f30e-161">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-161">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="3f30e-162">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-162">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="3f30e-163">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-163">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f30e-164">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-164">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f30e-165">**Crie Tabelas Dinâmicas a partir de conjuntos de dados no Power BI no Excel:** Você pode criar tabelas dinâmicas no Excel que estão conectadas a conjuntos de dados armazenados no Power BI com alguns cliques.</span><span class="sxs-lookup"><span data-stu-id="3f30e-165">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="3f30e-166"> Isso permite que você obtenha o melhor das Tabelas Dinâmicas e do Power BI.</span><span class="sxs-lookup"><span data-stu-id="3f30e-166">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="3f30e-167">Calcule, resuma e analise seus dados com Tabelas Dinâmicas a partir dos conjuntos de dados seguros do Power BI.</span><span class="sxs-lookup"><span data-stu-id="3f30e-167">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="3f30e-168">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-168">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="3f30e-169">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-169">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-170">Outlook</span></span>

- <span data-ttu-id="3f30e-171">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-171">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f30e-172">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-172">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f30e-173">**O calendário recebe um novo formato:** ver atualizações visuais que facilitam a pesquisa do calendário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-173">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="3f30e-174">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-174">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="3f30e-175">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-175">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="3f30e-176">**As tualizações de calendário compartilhadas ficaram mais rápidas**: No caso de calendários compartilhados no Office 365, o Outlook pode atualizá-los usando a API REST.</span><span class="sxs-lookup"><span data-stu-id="3f30e-176">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="3f30e-177">Ative a visualização para atualizações mais rápidas e confiáveis de calendários compartilhados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-177">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="3f30e-178">**Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-178">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="3f30e-179">As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-179">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="3f30e-180">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-180">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="3f30e-181">**Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online.</span><span class="sxs-lookup"><span data-stu-id="3f30e-181">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="3f30e-182">Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.</span><span class="sxs-lookup"><span data-stu-id="3f30e-182">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="3f30e-183">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-183">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="3f30e-184">**Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar?</span><span class="sxs-lookup"><span data-stu-id="3f30e-184">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="3f30e-185">O Outlook agora detecta isso e ajuda você a se conectar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-185">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="3f30e-186">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="3f30e-186">See details in [blog post](https://insider.office.com/pt-BR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="3f30e-187">**Obter sugestões de email ao procurar por alguém:** Quando você digitar o nome de uma pessoa na Caixa de pesquisa, os emails mais relevantes serão incluídos nas sugestões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-187">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="3f30e-188">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-188">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="3f30e-189">**Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca.</span><span class="sxs-lookup"><span data-stu-id="3f30e-189">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="3f30e-190">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-190">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="3f30e-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-191">PowerPoint</span></span>

- <span data-ttu-id="3f30e-192">**GIFs em uma piscar olhos:** um slide, um quadro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-192">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="3f30e-193">Crie facilmente GIFs de loop no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-193">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="3f30e-194">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-194">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="3f30e-195">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-195">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="3f30e-196">**Vincular ao Slide:** Peça a um colega para contribuir com o conjunto de slides e inicie-o diretamente no slide para o qual você precisa de ajuda.</span><span class="sxs-lookup"><span data-stu-id="3f30e-196">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="3f30e-197">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-197">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="3f30e-198">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-198">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="3f30e-199">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-199">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f30e-200">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-200">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f30e-201">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-201">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="3f30e-202">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-202">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="3f30e-203">**Diagramas melhores:** Com conectores melhores e um processo de conversão de tinta mais suave, você pode usar a tinta em suas ideias de forma mais confiante.</span><span class="sxs-lookup"><span data-stu-id="3f30e-203">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="3f30e-204">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-204">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="3f30e-205">**Melhor desempenho de streaming de vídeo no PowerPoint:** fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável.</span><span class="sxs-lookup"><span data-stu-id="3f30e-205">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="3f30e-206">Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-206">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="3f30e-207">**Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles.</span><span class="sxs-lookup"><span data-stu-id="3f30e-207">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="3f30e-208">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-208">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="3f30e-209">**Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="3f30e-209">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="3f30e-210">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-210">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="3f30e-211">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-211">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="3f30e-212">**Comentários:** a nova experiência de comentários no PowerPoint permite que você descubra e adicione comentários de maneira rápida e fácil aos seus documentos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-212">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="3f30e-213">Modernize seus fluxos de trabalho de colaboração com novos recursos, como ancoragem de comentários, resolução, tarefas, notificações de menção aprimorada e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-213">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="3f30e-214">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-214">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="3f30e-215">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-215">Word</span></span>

- <span data-ttu-id="3f30e-216">**Laço a tinta:** a ferramenta laço na guia desenhar ajuda a selecionar objetos desenhados à tinta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-216">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="3f30e-217">Selecione traços individuais ou palavras inteiras.</span><span class="sxs-lookup"><span data-stu-id="3f30e-217">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="3f30e-218">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-218">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="3f30e-219">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-219">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f30e-220">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-220">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f30e-221">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-221">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="3f30e-222">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-222">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="3f30e-223">**Confirmação de ação nos leitores de tela:** Confirmação de ação é um requisito de acessibilidade importante.</span><span class="sxs-lookup"><span data-stu-id="3f30e-223">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="3f30e-224">Com a introdução de uma nova API de Notificação do Windows, agora vamos alertar os usuários do leitor de tela sobre o sucesso de suas ações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-224">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="3f30e-225">Recortar, copiar, colar, negrito, itálico, sublinhado, desfazer, refazer, correções automáticas e todas as maiúsculas agora são anunciadas para os usuários do Narrador no Word Win32.</span><span class="sxs-lookup"><span data-stu-id="3f30e-225">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="3f30e-226">Para habilitar esse recurso, ative o Narrador pressionando a tecla windows + ctrl + enter.</span><span class="sxs-lookup"><span data-stu-id="3f30e-226">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="3f30e-227">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-227">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-228">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-228">Office Suite</span></span>

- <span data-ttu-id="3f30e-229">**Rótulos de confidencialidade:** agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-229">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-232">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-233">Acesso</span><span class="sxs-lookup"><span data-stu-id="3f30e-233">Access</span></span>

- <span data-ttu-id="3f30e-234">Correção de um problema em que o aplicativo fecharia inesperadamente ao usar a janela do Zoom.</span><span class="sxs-lookup"><span data-stu-id="3f30e-234">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="3f30e-235">Esta correção resolve o problema de onde a tentativa executar determinadas consultas tenha previamente produzido a mensagem de erro 'Consulta é muito complexa'.</span><span class="sxs-lookup"><span data-stu-id="3f30e-235">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="3f30e-236">Essa alteração corrige um problema que poderia fazer com que o Access falhasse ao iniciar a caixa Zoom (Shift + F2) para editar texto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-236">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="3f30e-237">Resolveu um problema com a inserção de tabelas SQL vinculadas que incluem um campo identidade (por exemplo, numeração automática).</span><span class="sxs-lookup"><span data-stu-id="3f30e-237">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="3f30e-238">Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. </span><span class="sxs-lookup"><span data-stu-id="3f30e-238">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="3f30e-239">Corrige um problema para possibilitar o uso do tipo de dados de Data/Hora Estendida em seu código sem o aplicativo falhar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-239">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="3f30e-240">Corrige um problema para poder reverter para a versão mais atualizada do Access e usar o DAO/VBA para gerenciar e editar um tipo de dados decimais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-240">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="3f30e-241">Corrigimos um problema de erro ao tentar usar o construtor de ODBC DSN</span><span class="sxs-lookup"><span data-stu-id="3f30e-241">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="3f30e-242">Este problema foi resolvido - agora você pode usar nosso driver ODBC fora das aplicações de Clicar para Executar do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-242">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="3f30e-243">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-243">Excel</span></span>

- <span data-ttu-id="3f30e-244">A classificação automática de documentos pode ter ocorrido para as pastas de trabalho que estavam e modo somente leitura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-244">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="3f30e-245">Correção de uma falha que poderia ocorrer quando você tentasse criar uma conexão de dados se tivesse saído da sua conta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-245">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="3f30e-246">Correção de um bug com APIs PivotDateFilter no qual as condições de filtragem 'Antes' e 'Depois' eram invertidas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-246">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="3f30e-247">Solucionamos um problema em que o Excel poderia falhar ao tentar inserir Tabelas Dinâmicas em uma planilha de gráfico.</span><span class="sxs-lookup"><span data-stu-id="3f30e-247">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="3f30e-248">Correção de um problema em que as tabelas dinâmicas não poderiam ser editadas e as pastas de trabalho não poderiam ser salvas se tivessem sido exportadas do plano do Project.</span><span class="sxs-lookup"><span data-stu-id="3f30e-248">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="3f30e-249">Pode ocorrer um erro ao tentar salvar um arquivo que contenha uma fórmula usando a função LET ().</span><span class="sxs-lookup"><span data-stu-id="3f30e-249">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="3f30e-250">Corrigimos um problema onde, em alguns casos, várias barras de mensagens apareciam quando um arquivo fosse aberto no modo somente leitura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-250">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="3f30e-251">Corrigimos um problema em que os subtotais de tópicos poderiam parar de funcionar quando houvesse muitos valores de cabeçalho de coluna duplicados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-251">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="3f30e-252">Corrigido um problema em que os livros somente leitura não atualizavam mais os dados da tabela dinâmica quando abertos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-252">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="3f30e-253">Essa alteração fornece uma correção para o seguinte problema: Excel "Inserir Objeto" não mostra o ícone correto ao inserir um arquivo da pasta de sincronização local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-253">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="3f30e-254">Corrigimos um problema em que o Excel parava de funcionar quando houvesse uma atualização de objeto de política de grupo (por exemplo, através da atualização de política de grupo remoto) durante o recálculo de vários threads.</span><span class="sxs-lookup"><span data-stu-id="3f30e-254">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="3f30e-255">Corrigimos um problema em que o Excel parava de funcionar quando os usuários usassem a função de subtotal em mais de 255 colunas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-255">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="3f30e-256">Melhor kerning de texto no PowerPoint quando o conteúdo é copiado do Excel e colado no PowerPoint com a opção embed.</span><span class="sxs-lookup"><span data-stu-id="3f30e-256">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="3f30e-257">Correção de um problema que impedia a mudança da visualização da tabela e do editor de consulta no PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="3f30e-257">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="3f30e-258">Corrigimos um problema em que um usuário não poderia abrir diretamente um arquivo atomsvc (UTF8+BOM) do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="3f30e-258">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="3f30e-259">Corrigido um problema em que os clientes eram notificados incorretamente sobre uma nova versão do arquivo durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="3f30e-259">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="3f30e-260">Corrigido um problema de edição em que o uso de IME com o modo Substituir avançava caracteres extras incorretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-260">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="3f30e-261">Corrigido um problema ao usar dados em tempo real em conjunto com a funcionalidade multithreaded recalc.</span><span class="sxs-lookup"><span data-stu-id="3f30e-261">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="3f30e-262">Corrige um problema em que o Excel falhava ao iniciar ou fechava inesperadamente se certas configurações de proteção contra exploração de Segurança do Windows (SimExec, CallerCheck) estivessem em uso</span><span class="sxs-lookup"><span data-stu-id="3f30e-262">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="3f30e-263">Correção de um problema em que o Excel poderia falhar em determinadas circunstâncias ao usar o Pincel de Formatação.</span><span class="sxs-lookup"><span data-stu-id="3f30e-263">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="3f30e-264">Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="3f30e-264">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="3f30e-265">Correção de um problema em que o Excel pode falhar ao usar a Análise Rápida após congelar a linha superior da planilha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-265">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="3f30e-266">Corrigimos um problema em que certas funções apresentavam resultados incorretos após o carregamento de uma pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-266">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="3f30e-267">Corrigimos um problema em que o aplicativo fechava inesperadamente, o que estava relacionado a referências do suplemento XLAM e intervalos nomeados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-267">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="3f30e-268">Corrigimos um problema onde usando um macro para definir a propriedade FormulaR1C1 para um intervalo, as referências de células estariam incorretas se uma planilha de gráfico fosse a planilha ativa. </span><span class="sxs-lookup"><span data-stu-id="3f30e-268">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="3f30e-269">Corrigido um problema que poderia causar um erro de que "Excel esgotou os recursos ao tentar calcular uma ou mais fórmulas".</span><span class="sxs-lookup"><span data-stu-id="3f30e-269">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="3f30e-270">Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.</span><span class="sxs-lookup"><span data-stu-id="3f30e-270">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="3f30e-271">Corrigimos um problema que poderia causar um travamento ao atualizar as tabelas dinâmicas OLAP.</span><span class="sxs-lookup"><span data-stu-id="3f30e-271">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="3f30e-272">Correção de um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-272">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="3f30e-273">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="3f30e-273">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="3f30e-274">Corrigimos um problema que, em alguns casos, clicar em um hiperlink para um local na mesma pasta de trabalho fará com que a pasta de trabalho seja ocultada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-274">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="3f30e-275">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-275">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="3f30e-276">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="3f30e-276">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="3f30e-277">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="3f30e-277">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="3f30e-278">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-278">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="3f30e-279">Corrigido um problema ao usar dados em tempo real em conjunto com a funcionalidade multithreaded recalc poderia fazer o aplicativo fechar inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-279">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="3f30e-280">Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-280">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="3f30e-281">Resolvemos um problema que poderia causar um aviso sobre uma pasta de trabalho corrompida se contivesse fórmulas usando IFNA().</span><span class="sxs-lookup"><span data-stu-id="3f30e-281">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="3f30e-282">Corrigimos um problema em que o Power Pivot agora reconhecerá com êxito o delimitador de tabulação.</span><span class="sxs-lookup"><span data-stu-id="3f30e-282">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="3f30e-283">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f30e-283">OneNote</span></span>

- <span data-ttu-id="3f30e-284">Informa os usuários, por meio da barra de informações, sobre ajustes temporários no Microsoft OneNote que ajudarão a melhorar a sincronização e o serviço durante o uso intenso pelo mundo inteiro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-284">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="3f30e-285">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-285">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="3f30e-286">Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-286">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="3f30e-287">Melhoria na sincronização e estabilidade do serviço, alterando temporariamente a frequência com que os históricos de versão de página são criados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-287">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="3f30e-288">Melhoria da sincronização e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-288">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="3f30e-289">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="3f30e-289">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="3f30e-290">Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-290">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="3f30e-291">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-291">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="3f30e-292">Melhoria na sincronização e estabilidade do servidor ao desabilitar, temporariamente, a transferências de páginas para a lixeira.</span><span class="sxs-lookup"><span data-stu-id="3f30e-292">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="3f30e-293">Os usuários que desejam excluir uma página, em vez disso, receberão uma caixa de diálogo perguntando se gostariam de excluir permanentemente a página.</span><span class="sxs-lookup"><span data-stu-id="3f30e-293">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="3f30e-294">Consertamos um problema em que o menu ortografia não foi carregado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-294">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f30e-295">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-295">Outlook</span></span>

- <span data-ttu-id="3f30e-296">Corrigimos um problema em que experiências conectadas opcionais impediam o carregamento de suplementos da web.</span><span class="sxs-lookup"><span data-stu-id="3f30e-296">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="3f30e-297">Veja mais detalhes aqui:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="3f30e-297">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="3f30e-298">Corrigimos um problema onde os usuários podem agora desabilitar o IRM (Gerenciamento de Direitos de Informação) para o Outlook sem ter que desabilitá-lo para o resto das aplicações do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-298">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="3f30e-299">Corrigimos um problema que impedia os usuários de conceder permissão de Editor a seus delegados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-299">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="3f30e-300">Corrigimos um problema que fazia com que os usuários ao experimentarem o aplicativo e ele encerrasse inesperadamente ao selecionar um resultado de pesquisa. </span><span class="sxs-lookup"><span data-stu-id="3f30e-300">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="3f30e-301">Corrige um problema que provocou os usuários que tentaram criar uma solicitação de reunião de uma conta secundária adicionada ao perfil, a não verem um campo em branco De: em vez de seus endereços de email.</span><span class="sxs-lookup"><span data-stu-id="3f30e-301">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="3f30e-302">Corrige um problema que fazia com que os usuários não conseguissem se conectar à pastas públicas após adicionar uma caixa de correio compartilhada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-302">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="3f30e-303">Resolveu um problema que fazia com que as reuniões não fossem retiradas do calendário de um gerente, quando recusadas por um representante em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="3f30e-303">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="3f30e-304">Resolveu um problema que impedia alguns usuários do recurso de Melhorias do Calendário Compartilhado de poderem visualizar um calendário compartilhado recém-adicionado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-304">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="3f30e-305">Corrige um problema que fez com que os usuários não conseguissem fechar os calendários compartilhados, clicando no "X" no canto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-305">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="3f30e-306">Corrige um problema que fazia com que a configuração "Habilitar melhorias no calendário compartilhado", às vezes, falhasse ao ser aplicada a calendários compartilhados existentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-306">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="3f30e-307">Corrigimos um problema que fazia com que as pesquisas nos calendários do Grupo não retornassem nenhum resultado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-307">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="3f30e-308">Corrige um problema que causava falhas ocasionais quando os usuários interagiam com anexos na nuvem.</span><span class="sxs-lookup"><span data-stu-id="3f30e-308">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="3f30e-309">Solucionamos um problema que fazia com que os usuários do CLP experimentassem uma falha ao mudar o endereço de um contexto de um contexto protegido para um não protegido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-309">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="3f30e-310">Corrige um problema que fazia com que os usuários vissem um erro na página de links seguros, em vez de no documento que tentavam abrir ao abrir um anexo na nuvem.</span><span class="sxs-lookup"><span data-stu-id="3f30e-310">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="3f30e-311">Solucionamos um problema em que o Outlook falhava ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="3f30e-311">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="3f30e-312">Corrige um problema com o evento de auditoria CLP para o rótulo responder/encaminhar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-312">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="3f30e-313">Solucionamos um problema que provocava a alteração inesperada da largura do painel de pasta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-313">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="3f30e-314">Corrigimos um problema que fazia com que o campo para: ficasse vazio ao enviar um relatório de status em uma Tarefa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-314">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="3f30e-315">Corrigimos um problema que causava a interrupção do evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="3f30e-315">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="3f30e-316">Aborda um problema que fazia com que os usuários vissem a data de criação de anexos que haviam copiado para seu sistema de arquivos por meio de arrastar e colar sendo definida como 1 de janeiro de 4501.</span><span class="sxs-lookup"><span data-stu-id="3f30e-316">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="3f30e-317">Tratamos de um problema que fazia com que os usuários de alguns conjuntos de caracteres vissem os nomes de arquivos exibidos incorretamente ao adicionar um Smart Link a um arquivo do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-317">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="3f30e-318">Soluciona um problema que exibia a mensagem “As regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-318">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="3f30e-319">Resolvido um problema que fazia com que o Outlook não recuperasse as sugestões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-319">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="3f30e-320">Corrige um problema que causava falhas no calendário em aperfeiçoamentos do Calendário Compartilhado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-320">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="3f30e-321">Solucionamos um problema que fazia com que os usuários experimentassem travamentos intermitentes e fechamentos em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-321">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="3f30e-322">Tratamos de um problema que fazia com que os usuários experimentassem uma falha ao excluir 4 ou mais emails de uma conta POP com a opção "Baixar Apenas Cabeçalhos" selecionada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-322">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="3f30e-323">Resolvido um problema que fazia com que os delegados vissem falhas intermitentes ao abrir pastas compartilhadas em outra caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="3f30e-323">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="3f30e-324">Resolvido um problema que fazia com que alguns emails gerados automaticamente fossem enviados com um corpo em branco quando a linha de assunto estava em branco.</span><span class="sxs-lookup"><span data-stu-id="3f30e-324">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="3f30e-325">Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-325">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="3f30e-326">Solucionado um problema que fazia com que representantes recebessem uma mensagem de erro ao editar um compromisso no calendário existente em um calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="3f30e-326">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="3f30e-327">Solucionamos um problema que fazia com que os usuários experimentassem falhas em aplicativos MAPI de terceiros.</span><span class="sxs-lookup"><span data-stu-id="3f30e-327">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="3f30e-328">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-328">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="3f30e-329">Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-329">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="3f30e-330">Corrige um problema que fazia com que os usuários do servidor do Windows 10 vissem o aviso “Status do antivírus: Inválido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-330">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="3f30e-331">Essa versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus foi encontrado” mesmo após a instalação correta do antivírus.</span><span class="sxs-lookup"><span data-stu-id="3f30e-331">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="3f30e-332">Corrigimos um problema que estava fazendo com que alguns usuários experimentassem o aplicativo para fechar inesperadamente ao enviar emails do Outlook de aplicativos diferentes do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-332">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="3f30e-333">Corrige um problema de desempenho com o carregamento de anexos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-333">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="3f30e-334">Corrige um problema que fazia com que o Outlook solicitasse continuamente para os usuários executarem a Ferramenta Reparo da Caixa de Entrada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-334">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="3f30e-335">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="3f30e-335">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="3f30e-336">Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="3f30e-336">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="3f30e-337">Corrigimos um problema que fazia com que os cabeçalhos das mensagens em Chinês ficassem distorcidos ao responder ou encaminhar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-337">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="3f30e-338">Solucionamos um problema que provocou falha na exibição da página do assistente de agendamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-338">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="3f30e-339">Resolvido um problema que provocava falha na exibição da página do Assistente de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="3f30e-340">Corrigimos um problema que fazia com que os usuários experimentassem o desempenho reduzido ao mover vários itens de email entre pastas no modo online.</span><span class="sxs-lookup"><span data-stu-id="3f30e-340">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="3f30e-341">Adicionamos uma regkey que permite que os clientes desabilitem a inclusão de filetime para anexos nas operações do IDataObject (ou seja, arrastar e soltar, área de transferência).</span><span class="sxs-lookup"><span data-stu-id="3f30e-341">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="3f30e-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject 0 = filetimes são excluídos 1 = (padrão) os tempos de inclusos são incluídos</span><span class="sxs-lookup"><span data-stu-id="3f30e-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="3f30e-343">Corrigimos um problema que fazia com que as imagens embutidas desaparecessem ao responder a uma mensagem com um rótulo de proteção da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="3f30e-343">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="3f30e-344">Corrigimos um problema que fazia com que o nome de usuário fosse exibido como um número de telefone ao enviar uma caixa postal protegida do Azure, fazendo com que os usuários da área de trabalho do Outlook não consiguissem abrir a caixa postal de usuários externos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-344">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="3f30e-345">Corrigido um problema em que a configuração da configuração do OME estava adicionando anexos estranhos no item de email que forçava o Outlook a criptografar a mensagem, embora a opção DecryptAttachmentsForEncryptOnly tivesse sido configurada no lado do serviço.</span><span class="sxs-lookup"><span data-stu-id="3f30e-345">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="3f30e-346">Consertamos um problema que fazia com que as opções Somente Criptografar e Não Encaminhar permanecessem habilitadas em alguns cenários, apesar de ser desabilitada pela política.</span><span class="sxs-lookup"><span data-stu-id="3f30e-346">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="3f30e-347">Corrigimos um problema que fazia com que o SmartLinks perca sua formatação quando salvo em rascunhos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-347">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="3f30e-348">Corrigimos um problema para fornecer a um usuário uma maneira de personalizar o texto de justificação ao substituir uma política.</span><span class="sxs-lookup"><span data-stu-id="3f30e-348">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="3f30e-349">Corrigimos um problema que fazia com que os caracteres Chineses fossem alterados para pontos de interrogação ao salvar como um arquivo OFT.</span><span class="sxs-lookup"><span data-stu-id="3f30e-349">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="3f30e-350">Resolvido um problema que causava falhas ocasionais quando os usuários recuperassem informações pessoais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-350">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="3f30e-351">Corrige um problema que causava falhas ocasionais quando os usuários editavam destinatários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-351">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="3f30e-352">Corrige um problema que causava os usuários de ver anormalidades ao usar o modo de exibição compacto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-352">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="3f30e-353">Solucionamos um problema que fazia com que os usuários do Outlook vissem problemas com a navegação no modo de exibição compacto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-353">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="3f30e-354">Resolveu de um problema que fazia com que o menu de contexto do botão direito do mouse não fosse exibido nos controles de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-354">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="3f30e-355">Aborda um problema que fez com que os usuários recebessem o seguinte erro ao responder ou a redigir um novo email: “Alguns arquivos desta página da Web não estão no local esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-355">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="3f30e-356">Deseja baixá-los mesmo assim?</span><span class="sxs-lookup"><span data-stu-id="3f30e-356">Do you want to download them anyway?</span></span> <span data-ttu-id="3f30e-357">Se tiver certeza de que a página da Web é de uma fonte confiável, clique em Sim.”</span><span class="sxs-lookup"><span data-stu-id="3f30e-357">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="3f30e-358">Corrige um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-358">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="3f30e-359">Solucionamos um problema que fazia com que a pesquisa de um recurso sugerir um recurso não retornou nenhum resultado e deixe o usuário sem a opção de enviar uma nova ideia de recurso.</span><span class="sxs-lookup"><span data-stu-id="3f30e-359">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="3f30e-360">Corrige um problema que causava problemas de formatação em alertas de notificação de incidente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-360">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="3f30e-361">Corrige um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma Notificação de Administrador.</span><span class="sxs-lookup"><span data-stu-id="3f30e-361">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="3f30e-362">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="3f30e-362">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f30e-363">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-363">PowerPoint</span></span>

- <span data-ttu-id="3f30e-364">Essa alteração corrige um problema com o recurso Exportar para GIF Animado em que clicar no botão Exportar não exportava.</span><span class="sxs-lookup"><span data-stu-id="3f30e-364">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="3f30e-365">Corrigimos um problema onde o suplemento de conteúdo do Microsoft Forms não processa após a inserção até que o usuário clique em outro slide para exibi-lo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-365">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="3f30e-366">Correção de segurança para solucionar um problema que desativou a proteção de IRM ao abrir um arquivo do PowerPoint no Modo de Exibição Protegido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-366">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="3f30e-367">Resolvemos um problema de VBA em que Slide.Shapes.AddMediaObject2 travava com formatos de vídeo herdados (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="3f30e-367">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="3f30e-368">Consertamos um problema em que o gráfico vinculado do Excel se altera incorretamente para a planilha do Excel quando o usuário altera o caminho de origem para a pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-368">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="3f30e-369">Isso corrige uma falha quando os usuários tenham tanto os comentários modernos quanto antigos em um arquivo, disparando uma atualização nos comentários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-369">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="3f30e-370">Consertamos um problema com o painel de sugestões que pode fazer o aplicativo fechar inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-370">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="3f30e-371">Resolvemos um problema no diálogo de Configurações de Ação que estava causando uma falha no aplicativo PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-371">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="3f30e-372">Consertamos um problema com o aplicativo do PowerPoint que pode fazer com que ele feche inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-372">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="3f30e-373">Corrigimos um problema devido à qual o recurso 'Bem-vindo de volta!</span><span class="sxs-lookup"><span data-stu-id="3f30e-373">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="3f30e-374">Retome de onde você parou no Office' não estava funcionando no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-374">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="3f30e-375">Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-375">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="3f30e-376">Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-376">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="3f30e-377">Resolvemos um problema em que a apresentação de slides no modo de exibição protegido não estava funcionando.</span><span class="sxs-lookup"><span data-stu-id="3f30e-377">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="3f30e-378">Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-378">Project</span></span>

- <span data-ttu-id="3f30e-379">Corrigimos um problema no qual a tarefa selecionada na caixa de diálogo para atribuir recursos não era a mesma que a tarefa selecionada no modo de exibição do quadro de tarefas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-379">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="3f30e-380">Corrige um problema em que, se um recurso tivesse mais de uma tabela de taxas de custo definida, os custos restantes nem sempre eram calculados corretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-380">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="3f30e-381">Corrige um problema em que a data de término do projeto não está sendo atualizada para os projetos conectados à lista de tarefas do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-381">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="3f30e-382">Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.</span><span class="sxs-lookup"><span data-stu-id="3f30e-382">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="3f30e-383">Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.</span><span class="sxs-lookup"><span data-stu-id="3f30e-383">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="3f30e-384">Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="3f30e-384">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="3f30e-385">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-385">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="3f30e-386">Solucionamos um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-386">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="3f30e-387">Corrige um problema onde um evento ProjectBeforeTaskChange adicional é acionado, quando os dados do predecessor/sucessor são editados em um modo de exibição de Formulário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-387">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="3f30e-388">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="3f30e-388">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="3f30e-389">Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-389">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="3f30e-390">Corrigimos um problema no qual não era possível salvar um PDF/XPS do Project em uma biblioteca de documentos no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-390">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="3f30e-391">Corrigimos um problema no qual, se você colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-391">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="3f30e-392">Corrigimos um problema no qual não era possível abrir projetos no cliente da área de trabalho do Project a partir do aplicativo web do Project caso o URL terminasse em .com.</span><span class="sxs-lookup"><span data-stu-id="3f30e-392">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="3f30e-393">Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa resumo do projeto, o campo início/tarefa do projeto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-393">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="3f30e-394">Correção de um problema em que uma tarefa marcada como 100% concluída mudava incorretamente para menos do que 100% concluída.</span><span class="sxs-lookup"><span data-stu-id="3f30e-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="3f30e-395">Corrigido um problema em que o Microsoft Project podia ser encerrado inesperadamente ao abrir arquivos em que os contornos dos recursos foram especificados de uma determinada maneira.</span><span class="sxs-lookup"><span data-stu-id="3f30e-395">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="3f30e-396">Skype</span><span class="sxs-lookup"><span data-stu-id="3f30e-396">Skype</span></span>

- <span data-ttu-id="3f30e-397">Alterou o tom de pele do emoticon que dança para uma cor neutra.</span><span class="sxs-lookup"><span data-stu-id="3f30e-397">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="3f30e-398">Quando um usuário recebe uma política que os move para o modo Teams Only, ele ainda poderá usar o suplemento do Outlook do Skype for Business para agendar reuniões.</span><span class="sxs-lookup"><span data-stu-id="3f30e-398">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="3f30e-399">Após essa atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente ler a política, indicando que o usuário está no modo Teams Only, e entrar no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="3f30e-399">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="3f30e-400">Além disso, o suplemento Skype for Business no Outlook não será ativado durante a inicialização, caso veja que o cliente do Skype for Business está no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="3f30e-400">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="3f30e-401">Corrige um problema em que o certificado TLS-DSK de um usuário não era renovado no horário esperado, em vez de renovar apenas quando faltavam menos de 12 horas para sua validade.</span><span class="sxs-lookup"><span data-stu-id="3f30e-401">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="3f30e-402">Corrige um problema em que a interface do usuário do Skype for Business aparece em branco depois de entrar quando o Office ainda não está licenciado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-402">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="3f30e-403">Visio</span><span class="sxs-lookup"><span data-stu-id="3f30e-403">Visio</span></span>

- <span data-ttu-id="3f30e-404">Resolvemos um problema que fez com que a visualização ao vivo falhasse no alinhamento do texto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-404">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="3f30e-405">Corrigimos um problema em que os usuários poderão criar linhas retas usando conectores no Visio para Office 365 para estênceis personalizados do Visio e modelos internos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-405">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="3f30e-406">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-406">Word</span></span>

- <span data-ttu-id="3f30e-407">Resolvido um problema ao abrir documentos do Word a partir de uma entrega de documento personalizada (aspx) quando a URL contém um componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-407">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="3f30e-408">Essa alteração corrige um problema em que os aplicativos do Office poderiam ficar presos em um estado de falha silencioso de salvamento após uma sessão anterior de coautoria.</span><span class="sxs-lookup"><span data-stu-id="3f30e-408">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="3f30e-409">Soluciona um problema que fazia com que os usuários experimentassem uma falha ao responder ou redigir um novo email.</span><span class="sxs-lookup"><span data-stu-id="3f30e-409">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="3f30e-410">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="3f30e-410">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="3f30e-411">Resolvemos um problema que fazia com que os usuários experimentassem um travamento ao abrir certos emails muito grandes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-411">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="3f30e-412">Consertamos um problema em que os títulos de numeração coladas mostraram um recuo adicional.</span><span class="sxs-lookup"><span data-stu-id="3f30e-412">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="3f30e-413">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="3f30e-413">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="3f30e-414">Resolvemos um problema em que o usuário poderia perder conteúdo ao redimensionar uma forma.</span><span class="sxs-lookup"><span data-stu-id="3f30e-414">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="3f30e-415">Corrigimos um problema em que o usuário pode experimentar uma falha ao abrir um documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-415">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="3f30e-416">Resolvemos um problema no qual os links longos não eram dispostos ao salvar um documento no formato HTML.</span><span class="sxs-lookup"><span data-stu-id="3f30e-416">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="3f30e-417">Resolvemos um problema em que os estilos básicos não eram atualizados com o estilo Normal.</span><span class="sxs-lookup"><span data-stu-id="3f30e-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="3f30e-418">Corrige um bug com extensões de comentário em que a resposta de comentário teria a mesma extensão que o comentário pai.</span><span class="sxs-lookup"><span data-stu-id="3f30e-418">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="3f30e-419">Corrigimos um problema em que, se você responder a um comentário pai que tenha extensões desconhecidas em uma lista de extensões, a resposta receberá essas mesmas extensões.</span><span class="sxs-lookup"><span data-stu-id="3f30e-419">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="3f30e-420">Resolveu um problema que pode ter feito o aplicativo fechar inesperadamente durante a inicialização.</span><span class="sxs-lookup"><span data-stu-id="3f30e-420">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="3f30e-421">Corrigimos um problema no Outlook com a mensagem definida como Não encaminhar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-421">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="3f30e-422">Corrigimos um problema com a caixa de diálogo Galeria de Estilos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-422">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="3f30e-423">Resolvemos um problema em que a macro AutoOpen era executada antes do AutoExec</span><span class="sxs-lookup"><span data-stu-id="3f30e-423">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f30e-424">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-424">Office Suite</span></span>

- <span data-ttu-id="3f30e-425">Para o antigo painel de Compartilhamento não baseado na Web, ao fechar o documento enquanto o painel de Compartilhamento abria, isso poderia causar uma falha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-425">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="3f30e-426">Correção de um problema de tempo que pode fazer o aplicativo fechar inesperadamente ao fechar os arquivos do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-426">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="3f30e-427">Corrige um problema que impede que os usuários importem listas do SPO quando a ADAL estiver desabilitada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-427">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="3f30e-428">Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners.</span><span class="sxs-lookup"><span data-stu-id="3f30e-428">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="3f30e-429">Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".</span><span class="sxs-lookup"><span data-stu-id="3f30e-429">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="3f30e-430">Resolvemos o problema de taxa de falha do ValidateInstall configurando a validação de instalação do Bing Addon como verdadeira por padrão e considerando o sucesso do retorno MSI como um sucesso na instalação.</span><span class="sxs-lookup"><span data-stu-id="3f30e-430">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="3f30e-431">Portamos uma nova AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="3f30e-431">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="3f30e-432">Corrige um problema com Clique para Executar, que resultava na falha de atualização durante a tentativa de vincular links simbólicos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-432">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="3f30e-433">Resolvido um problema para clientes comerciais que utilizam o Centro do Sistema de Gerenciador de Configurações ou outra ferramenta de gerenciamento para o Atualização do Office usando a prevenção contra perda de dados do Ponto de extremidade do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="3f30e-433">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="3f30e-434">Corrigido um problema que provocou uma mensagem do tempo de execução, mesmo que foi demonstrado que a transição para o produto completo tenha sido concluída.</span><span class="sxs-lookup"><span data-stu-id="3f30e-434">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="3f30e-435">A correção para esse problema foi garantir que o serviço computasse corretamente os produtos adicionados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-435">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="3f30e-436">Filtramos os produtos recém-adicionados (garantindo que também estejam presentes na nova configuração) e os adicionamos no final das IDs de lançamento dos produtos existentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-436">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="3f30e-437">Solucionamos um problema em que os usuários estavam vendo os elementos da interface do usuário ou o conteúdo que não estava sendo exibido em determinadas condições, em particular, no Modo de Exibição do Apresentador ou no uso de vários monitores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-437">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="3f30e-438">Essa alteração aborda um problema relacionado à abertura de arquivos contendo diagramas legados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-438">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="3f30e-439">Essa alteração soluciona um problema com o proxy substituto SVG que resulta em violações de acesso.</span><span class="sxs-lookup"><span data-stu-id="3f30e-439">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="3f30e-440">Corrige o alto uso de CPUs em ociosidade com GIF/modelo em 3D animado</span><span class="sxs-lookup"><span data-stu-id="3f30e-440">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="3f30e-441">Essa alteração soluciona as possíveis travas ao carregar e reproduzir conteúdo animado, como GIFs ou modelos 3D.</span><span class="sxs-lookup"><span data-stu-id="3f30e-441">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="3f30e-442">Essa alteração corrige uma falha ao iniciar os aplicativos do Office devido à falha no carregamento de d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="3f30e-442">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="3f30e-443">O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero.</span><span class="sxs-lookup"><span data-stu-id="3f30e-443">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="3f30e-444">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="3f30e-444">This change would fix this issue.</span></span>


- <span data-ttu-id="3f30e-445">Corrigido um problema de que a API de Mensagens para suplementos do Office não está funcionando.</span><span class="sxs-lookup"><span data-stu-id="3f30e-445">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="3f30e-446">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-446">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="3f30e-447">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="3f30e-447">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="3f30e-448">Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-448">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="3f30e-449">Soluciona um problema que pode ter causado uma falha ao arrastar conteúdo do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-449">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DE BUGDETAILS)

## <a name="version-2002-january-12"></a><span data-ttu-id="3f30e-451">Versão 2002: 12 de janeiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-451">Version 2002: January 12</span></span>
<span data-ttu-id="3f30e-452">*Versão 2002 (Build 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-452">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="3f30e-453">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-453">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-455">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-455">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-456">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-456">Excel</span></span>

- <span data-ttu-id="3f30e-457">Corrigido um problema ao usar dados em tempo real em conjunto com a funcionalidade multithreaded recalc poderia fazer o aplicativo fechar inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-457">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f30e-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-458">PowerPoint</span></span>

- <span data-ttu-id="3f30e-459">Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-459">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="3f30e-460">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-460">Word</span></span>

- <span data-ttu-id="3f30e-461">Corrige um bug com extensões de comentário em que a resposta de comentário tem a mesma extensão que o comentário pai.</span><span class="sxs-lookup"><span data-stu-id="3f30e-461">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (NÃO REMOVA O CONTEÚDO FINAL DE BUGDETAILS)

## <a name="version-1908-january-12"></a><span data-ttu-id="3f30e-463">Versão 1908: 12 de janeiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-463">Version 1908: January 12</span></span>
<span data-ttu-id="3f30e-464">*Versão 1908 (Build 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-464">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="3f30e-465">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-467">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-467">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="3f30e-468">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-468">Office Suite</span></span>

- <span data-ttu-id="3f30e-469">Essa alteração aborda um problema relacionado à abertura de arquivos contendo diagramas legados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-469">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2002-december-08"></a><span data-ttu-id="3f30e-471">Versão 2002: 8 de setembro</span><span class="sxs-lookup"><span data-stu-id="3f30e-471">Version 2002: December 08</span></span>
<span data-ttu-id="3f30e-472">*Versão 2002 (Build 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-472">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="3f30e-473">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-473">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-475">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-475">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-476">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-476">Excel</span></span>

- <span data-ttu-id="3f30e-477">Melhor kerning de texto no PowerPoint quando o conteúdo é copiado do Excel e colado no PowerPoint com a opção embed.</span><span class="sxs-lookup"><span data-stu-id="3f30e-477">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="3f30e-478">Corrigimos um problema em que o Excel para de funcionar durante o recálculo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-478">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="3f30e-479">Corrigimos um problema em que um usuário não podia abrir diretamente um arquivo atomsvc (UTF8+BOM) do Microsoft Office SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="3f30e-479">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="3f30e-480">Correção de um problema que impedia a mudança da visualização da tabela e do editor de consulta no PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="3f30e-480">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="3f30e-481">Desempenho aprimorado para arquivos que estão usando muitas das funções liberadas recentemente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-481">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f30e-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-482">Outlook</span></span>

- <span data-ttu-id="3f30e-483">Corrigido um problema em que a configuração da configuração do OME estava adicionando anexos estranhos no item de email que estava forçando o Outlook a criptografar a mensagem, mesmo que a opção DecryptAttachmentsForEncryptOnly fosse configurada no lado do serviço.</span><span class="sxs-lookup"><span data-stu-id="3f30e-483">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f30e-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-484">PowerPoint</span></span>

- <span data-ttu-id="3f30e-485">Consertamos um problema em que o gráfico vinculado do Excel se altera incorretamente para a planilha do Excel quando o usuário altera o caminho de origem para a pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-485">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="3f30e-486">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-486">Project</span></span>

- <span data-ttu-id="3f30e-487">Consertamos um problema em que os projetos não podiam ser abertos no cliente de área de trabalho do Project a partir do Project Web App, se a URL terminasse em '.com'.</span><span class="sxs-lookup"><span data-stu-id="3f30e-487">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-december-08"></a><span data-ttu-id="3f30e-489">Versão 1908: 8 de dezembro</span><span class="sxs-lookup"><span data-stu-id="3f30e-489">Version 1908: December 08</span></span>
<span data-ttu-id="3f30e-490">*Versão 1908 (Build 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-490">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="3f30e-491">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="3f30e-492">Versão 2002: 10 de novembro</span><span class="sxs-lookup"><span data-stu-id="3f30e-492">Version 2002: November 10</span></span>
<span data-ttu-id="3f30e-493">*Versão 2002 (Build 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-493">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="3f30e-494">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-494">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-496">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-496">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-497">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-497">Excel</span></span>

- <span data-ttu-id="3f30e-498">Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.</span><span class="sxs-lookup"><span data-stu-id="3f30e-498">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="3f30e-499">Corrigimos um problema que poderia causar um travamento ao atualizar as tabelas dinâmicas OLAP.</span><span class="sxs-lookup"><span data-stu-id="3f30e-499">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="3f30e-500">Corrigido um bug em que certas funções teriam um resultado incorreto após carregar uma pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-500">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="3f30e-501">Corrigimos um problema em que o aplicativo fechava inesperadamente, o que estava relacionado a referências do suplemento XLAM e intervalos nomeados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-501">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="3f30e-502">Corrigido um problema em que a execução da macro de filtro avançado relatava erros incorretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-502">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f30e-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-503">Outlook</span></span>

- <span data-ttu-id="3f30e-504">Corrigimos um problema que fazia com que os suplementos internos fossem inesperadamente desabilitados quando as experiências conectadas opcionais eram desabilitadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-504">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="3f30e-505">Corrigimos um problema que impedia os usuários de enviar como ou em nome de uma Lista de Distribuição que estava oculta na Lista de Endereços Global.</span><span class="sxs-lookup"><span data-stu-id="3f30e-505">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-1908-november-10"></a><span data-ttu-id="3f30e-507">Version 1908: 10 de novembro</span><span class="sxs-lookup"><span data-stu-id="3f30e-507">Version 1908: November 10</span></span>
<span data-ttu-id="3f30e-508">*Versão 1908 (Build 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-508">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="3f30e-509">Atualizações de segurança listadas[ aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="3f30e-510">Version 2002: 13 de outubro</span><span class="sxs-lookup"><span data-stu-id="3f30e-510">Version 2002: October 13</span></span>
<span data-ttu-id="3f30e-511">*Versão 2002 (Compilação 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-511">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="3f30e-512">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-514">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-514">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-515">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-515">Access</span></span>

- <span data-ttu-id="3f30e-516">Você não deve mais receber a menagem "A consulta é muito complexa" ou "um recurso do sistema excedeu o erro" na versão de 64 bits do Access", desde que você esteja obedecendo as diretrizes e requisitos de banco de dados do Access.</span><span class="sxs-lookup"><span data-stu-id="3f30e-516">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="3f30e-517">Depois de usar nosso recurso de filtro após nosso designer de consulta, seu banco de dados não deve mais falhar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-517">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="3f30e-518">Verifique se.</span><span class="sxs-lookup"><span data-stu-id="3f30e-518">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="3f30e-519">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-519">Excel</span></span>

- <span data-ttu-id="3f30e-520">Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="3f30e-520">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f30e-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-521">PowerPoint</span></span>

- <span data-ttu-id="3f30e-522">As novas apresentações criadas a partir de um modelo podem herdar uma configuração que impedia uma boa experiência de coautoria.</span><span class="sxs-lookup"><span data-stu-id="3f30e-522">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="3f30e-523">Essa correção garante que a configuração esteja limpa neste caso.</span><span class="sxs-lookup"><span data-stu-id="3f30e-523">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="3f30e-524">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-524">Word</span></span>

- <span data-ttu-id="3f30e-525">Consertamos um problema no qual ao abrir documentos com quebras de página e colunas, o usuário pode encontrar uma mensagem de erro "você ultrapassou o número máximo de páginas permitidas pelo Microsoft Word ou o documento pode estar danificado"</span><span class="sxs-lookup"><span data-stu-id="3f30e-525">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f30e-526">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-526">Office Suite</span></span>

- <span data-ttu-id="3f30e-527">Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners.</span><span class="sxs-lookup"><span data-stu-id="3f30e-527">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="3f30e-528">Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".</span><span class="sxs-lookup"><span data-stu-id="3f30e-528">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-october-13"></a><span data-ttu-id="3f30e-530">Versão 1908: 13 de outubro</span><span class="sxs-lookup"><span data-stu-id="3f30e-530">Version 1908: October 13</span></span>
<span data-ttu-id="3f30e-531">*Versão 1908 (Compilação 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-531">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="3f30e-532">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-534">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="3f30e-535">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-535">Office Suite</span></span>

- <span data-ttu-id="3f30e-536">Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners.</span><span class="sxs-lookup"><span data-stu-id="3f30e-536">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="3f30e-537">Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".</span><span class="sxs-lookup"><span data-stu-id="3f30e-537">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-september-08"></a><span data-ttu-id="3f30e-539">Versão 2002: 8 de setembro</span><span class="sxs-lookup"><span data-stu-id="3f30e-539">Version 2002: September 08</span></span>
<span data-ttu-id="3f30e-540">*Versão 2002 (Build 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-540">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="3f30e-541">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-541">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-543">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-543">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-544">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-544">Excel</span></span>

- <span data-ttu-id="3f30e-545">Isso aborda um problema em que as conexões criadas pelo provedor de dados SQL nas versões anteriores do Office definem as propriedades da tabela interna de modo diferente do Office 365.</span><span class="sxs-lookup"><span data-stu-id="3f30e-545">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="3f30e-546">Isso fazia com que a lista suspensa da Visualização de tabela / Editor de consulta fosse desabilitada para arquivos com conexões criadas em versões mais antigas do Office quando eram abertas usando o Office 365.</span><span class="sxs-lookup"><span data-stu-id="3f30e-546">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="3f30e-547">Resolvemos um problema em que a escrita à tinta poderia fazer com que o Excel não respondesse.</span><span class="sxs-lookup"><span data-stu-id="3f30e-547">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f30e-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-548">Outlook</span></span>

- <span data-ttu-id="3f30e-549">Corrige um problema que fazia com que os usuários não conseguissem se conectar às Pastas Públicas após adicionar uma caixa de correio compartilhada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-549">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f30e-550">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-550">Office Suite</span></span>

- <span data-ttu-id="3f30e-551">Essa alteração corrige um problema com a caixa de diálogos Compactar imagem que não mantém determinadas configurações do usuário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-551">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-1908-september-08"></a><span data-ttu-id="3f30e-553">Versão 1908: 8 de setembro</span><span class="sxs-lookup"><span data-stu-id="3f30e-553">Version 1908: September 08</span></span>
<span data-ttu-id="3f30e-554">*Versão 1908 (Build 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-554">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="3f30e-555">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-555">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="3f30e-556">Versão 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="3f30e-556">Version 2002: August 11</span></span>
<span data-ttu-id="3f30e-557">*Versão 2002 (Compilação 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-557">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="3f30e-558">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-558">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-560">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-560">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-561">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-561">Excel</span></span>

- <span data-ttu-id="3f30e-562">Corrigido um problema que impedia a capacidade de mudar para editar arquivos que foram abertos como "leitura somente recomendado".</span><span class="sxs-lookup"><span data-stu-id="3f30e-562">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="3f30e-563">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f30e-563">OneNote</span></span>

- <span data-ttu-id="3f30e-564">Removido as chamadas de identidade redundantes para reduzir a utilização de recursos</span><span class="sxs-lookup"><span data-stu-id="3f30e-564">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="3f30e-565">Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-565">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="3f30e-566">Melhoria na capacidade de detecção de erros e na experiência de sincronização com qualidade.</span><span class="sxs-lookup"><span data-stu-id="3f30e-566">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-567">Outlook</span></span>

- <span data-ttu-id="3f30e-568">Foi abordado um problema que causava um problema de desempenho significativo ao iniciar o Outlook para alguns locatários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-568">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="3f30e-569">Skype</span><span class="sxs-lookup"><span data-stu-id="3f30e-569">Skype</span></span>

- <span data-ttu-id="3f30e-570">Corrigido um problema em que iniciar um compartilhamento de tela pode falhar em um cliente do Skype for Business de 32 bits após ele estiver sendo executado por vários dias.</span><span class="sxs-lookup"><span data-stu-id="3f30e-570">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-571">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-571">Office Suite</span></span>

- <span data-ttu-id="3f30e-572">Corrigido um problema em que, quando o salvamento automático estava desativado na política de grupo, alguns documentos não podiam mostrar o conteúdo mais recente do servidor na abertura até o usuário clicar em "Atualizações disponíveis".</span><span class="sxs-lookup"><span data-stu-id="3f30e-572">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-august-11"></a><span data-ttu-id="3f30e-574">Versão 1908: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="3f30e-574">Version 1908: August 11</span></span>
<span data-ttu-id="3f30e-575">*Versão 1908 (Compilação 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-575">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="3f30e-576">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-576">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="3f30e-577">Versão 1902: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="3f30e-577">Version 1902: August 11</span></span>
<span data-ttu-id="3f30e-578">*Versão 1902 (Compilação 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-578">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="3f30e-579">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-july-14"></a><span data-ttu-id="3f30e-582">Versão 2002: 14 de julho</span><span class="sxs-lookup"><span data-stu-id="3f30e-582">Version 2002: July 14</span></span>
<span data-ttu-id="3f30e-583">*Versão 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-583">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="3f30e-584">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-584">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="3f30e-586">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="3f30e-586">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-587">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-587">Access</span></span>

- <span data-ttu-id="3f30e-588">**Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-588">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="3f30e-589">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-589">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="3f30e-590">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-590">Excel</span></span>

- <span data-ttu-id="3f30e-591">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-591">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="3f30e-592">**Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel.</span><span class="sxs-lookup"><span data-stu-id="3f30e-592">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="3f30e-593">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-593">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="3f30e-594">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-594">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="3f30e-595">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-595">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="3f30e-596">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-596">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="3f30e-597">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-597">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f30e-598">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-598">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f30e-599">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-599">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="3f30e-600">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-600">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="3f30e-601">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-601">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="3f30e-602">**Foco no que precisa ser feito:** selecione Resolver para recolher comentários e destacar os itens abertos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-602">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="3f30e-603">**Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão automaticamente enviados para as células vizinhas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-603">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="3f30e-604">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-604">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="3f30e-605">Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-605">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="3f30e-606">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-606">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="3f30e-607">**Faça um Esboço:** Deixe as formas do Office da sua pasta de trabalho com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-607">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="3f30e-608">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-608">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="3f30e-609">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-609">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="3f30e-610">**Encontre o que está procurando:** Pesquise comandos, pessoas, arquivos, fotos, artigos da Web e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-610">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="3f30e-611">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-611">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="3f30e-612">**Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE e RANDARRAY.</span><span class="sxs-lookup"><span data-stu-id="3f30e-612">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="3f30e-613">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-613">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="3f30e-614">**Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!:** Linha por linha, encontre tudo o que você precisa em uma tabela ou intervalo com o XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="3f30e-614">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="3f30e-615">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-615">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="3f30e-616">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-616">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="3f30e-617">**Controle sua pasta de trabalho grande:** células, fórmulas, gráficos, tabelas. Obtenha um instantâneo da sua pasta de trabalho com Estatísticas de Pasta de Trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-617">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="3f30e-618">**Leia e responda instantaneamente:** responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-618">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="3f30e-619">**Chame a atenção com \@@Menções:** Use @menções nos comentários para informar a seus colegas de trabalho quando precisar deles.</span><span class="sxs-lookup"><span data-stu-id="3f30e-619">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="3f30e-620">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-620">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="3f30e-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-621">Outlook</span></span>

- <span data-ttu-id="3f30e-622">**Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens.</span><span class="sxs-lookup"><span data-stu-id="3f30e-622">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="3f30e-623">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-623">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="3f30e-624">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-624">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f30e-625">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-625">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f30e-626">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-626">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="3f30e-627">**Deixe-me desenhar:** Rabisque em fotos ou adicione uma Tela de Desenho para enviar seus pensamentos com tinta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-627">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="3f30e-628">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-628">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="3f30e-629">**Obtenha sugestões de locais:** comece a digitar em Local ao agendar compromissos e reuniões, e o Outlook irá sugerir salas, endereços e outros locais recentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-629">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="3f30e-630">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-630">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="3f30e-631">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-631">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="3f30e-632">**Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.</span><span class="sxs-lookup"><span data-stu-id="3f30e-632">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="3f30e-633">**O menu Inserir Link no Outlook inserirá um link com a permissão definida pelo administrador do locatário:** um link do Inserir Link MRU no Outlook insere um link que só funcionou para usuários que já tinham permissões.</span><span class="sxs-lookup"><span data-stu-id="3f30e-633">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="3f30e-634">Isso causou uma troca de emails frequente entre os usuários solicitando o acesso a um documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-634">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="3f30e-635">Atualizamos essa experiência e agora o link é inserido com a permissão padrão definida pelo administrador do locatário. No MSIT, é "A organização pode editar", para que todos os usuários internos que recebem um link compartilhado dessa maneira possam acessá-lo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-635">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="3f30e-636">**Veja suas mensagens sob uma perspectiva diferente:** use o botão Sol/Lua para alternar entre planos de fundo claros e escuros no painel de leitura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-636">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="3f30e-637">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-637">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="3f30e-638">**Emails de phishing fáceis de identificar:** As mensagens de spam e phishing têm uma aparência diferente, para que você possa identificá-las e eliminá-las facilmente na caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-638">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="3f30e-p159">**Todas as opções de criptografia em um só lugar:** Basta ir para Opções > Criptografar para escolher como proteger sua mensagem de email. [Saiba mais](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p159">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="3f30e-641">**Pesquisar com erros de ortografia ou digitação:** o Outlook encontrará o que você está procurando, mesmo quando a ortografia não corresponder.</span><span class="sxs-lookup"><span data-stu-id="3f30e-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="3f30e-642">**Conecte sua rede do LinkedIn ao Outlook:** Conecte sua conta do LinkedIn com segurança à sua conta da Microsoft para ver informações de perfis do LinkedIn diretamente no cartão de Pessoas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-642">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="3f30e-643">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-643">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="3f30e-644">**Veja as mensagens relevantes nos resultados de pesquisa:** o Outlook analisa os termos de pesquisa e mostra as mensagens de email mais relevantes na parte superior dos resultados da pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-644">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="3f30e-645">Você também verá todos os resultados classificados por data, na seção Resultados Principais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-645">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="3f30e-646">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-646">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="3f30e-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-647">PowerPoint</span></span>

- <span data-ttu-id="3f30e-p162">**Você calcula, nós formatamos:** Nós trocamos expressões matemáticas difíceis de desenhar por caracteres padrão. Basta escolher Tinta para Matemática e selecionar suas anotações manuscritas para começar.[Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p162">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="3f30e-651">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-651">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="3f30e-652">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-652">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="3f30e-653">**Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-653">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="3f30e-654">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-654">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="3f30e-655">**Faça um Esboço:** deixe as formas do Office da sua apresentação com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-655">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="3f30e-656">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-656">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="3f30e-657">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-657">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="3f30e-658">**Repe-tinta-ção Instantânea:** Ao escrever à tinta nos slides, aplique uma animação de repetição para reproduzir o desenho real da sua tinta durante a apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="3f30e-658">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="3f30e-659">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-659">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="3f30e-660">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-660">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="3f30e-661">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="3f30e-661">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="3f30e-662">**Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem.</span><span class="sxs-lookup"><span data-stu-id="3f30e-662">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="3f30e-663">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-663">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="3f30e-664">**Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-664">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="3f30e-665">Deixá-los ou não ativados depende de você.</span><span class="sxs-lookup"><span data-stu-id="3f30e-665">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="3f30e-666">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-666">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="3f30e-667">**Localize e corrija títulos de slides ausentes:** Títulos de slides reforçam o seu discurso e tornam os seus slides acessíveis a usuários de todas as habilidades.</span><span class="sxs-lookup"><span data-stu-id="3f30e-667">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="3f30e-668">O Verificador de Acessibilidade mostra onde os títulos estão ausentes para que você possa adicioná-los imediatamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-668">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="3f30e-669">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-669">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="3f30e-670">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-670">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="3f30e-671">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-671">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="3f30e-672">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-672">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="3f30e-673">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-673">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f30e-674">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-674">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="3f30e-675">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-675">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="3f30e-676">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-676">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="3f30e-677">**Compartilhamento rápido de arquivo**: compartilhe seus documentos diretamente da lista usada recentemente sem precisar abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="3f30e-678">**Colaboração rápida e em tempo real no PowerPoint:** colaboração rápida e em tempo real no PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-678">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="3f30e-679">**Não é mais necessário voltar ao navegador:** você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-679">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="3f30e-680">**Novas ferramentas de revisão:** não se preocupe com suas palavras.</span><span class="sxs-lookup"><span data-stu-id="3f30e-680">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="3f30e-681">Agora, o PowerPoint fornece sugestões de gramática e ortografia.</span><span class="sxs-lookup"><span data-stu-id="3f30e-681">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="3f30e-682">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-682">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="3f30e-683">**Legendas em tempo real:** As palavras do apresentador aparecem na tela automaticamente como legendas ou traduzidas para o idioma que escolher.</span><span class="sxs-lookup"><span data-stu-id="3f30e-683">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="3f30e-684">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-684">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="3f30e-685">**Otimize sua apresentação para todos:** o Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.</span><span class="sxs-lookup"><span data-stu-id="3f30e-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="3f30e-686">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-686">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="3f30e-687">**Por que reinventar quando você pode reutilizar?:** economize tempo reutilizando slides que você criou ou que outras pessoas compartilharam com você.</span><span class="sxs-lookup"><span data-stu-id="3f30e-687">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="3f30e-688">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-688">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="3f30e-689">Visio</span><span class="sxs-lookup"><span data-stu-id="3f30e-689">Visio</span></span>

- <span data-ttu-id="3f30e-690">**Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-690">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="3f30e-691">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="3f30e-692">**Voltando para a cena do crime:** Use os novos estênceis de Evidência, Interno e Externo no modelo de Investigação de Cena de Crime para recriar cenas de crimes em detalhes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-692">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-693">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-693">Word</span></span>

- <span data-ttu-id="3f30e-694">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="3f30e-694">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="3f30e-695">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-695">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="3f30e-696">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-696">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="3f30e-697">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-697">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="3f30e-698">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-698">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="3f30e-699">**Compartilhamento rápido de arquivo**: compartilhe seus documentos diretamente da lista usada recentemente sem precisar abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-699">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="3f30e-700">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-700">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f30e-701">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="3f30e-701">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f30e-702">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-702">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="3f30e-703">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-703">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="3f30e-704">**Apagar com precisão:** Escolha entre dois tamanhos de borracha para corrigir pequenas imperfeições à tinta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-704">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="3f30e-705">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-705">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="3f30e-706">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-706">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="3f30e-707">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-707">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="3f30e-708">**Faça um Esboço:** deixe as formas do Office do seu documento com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-708">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="3f30e-709">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-709">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="3f30e-710">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="3f30e-710">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="3f30e-711">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-711">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="3f30e-712">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-712">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="3f30e-713">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-713">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="3f30e-714">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-714">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="3f30e-715">**O Editor de Currículos se une ao Assistente de Currículos do LinkedIn:** O Editor de Currículos oferece uma seleção de verificações gramaticais e de estilo especialmente adaptadas para currículos, para tornar a sua escrita mais precisa e profissional.</span><span class="sxs-lookup"><span data-stu-id="3f30e-715">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="3f30e-716">**Outras pessoas veem suas alterações rapidamente:** os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas alterações mais rápido do que nunca.</span><span class="sxs-lookup"><span data-stu-id="3f30e-716">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="3f30e-717">**Corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D:** corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="3f30e-717">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="3f30e-718">**Aperfeiçoamentos de coautoria**: desempenho aperfeiçoado do Word durante a coautoria em documentos com alterações controladas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-718">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="3f30e-719">**Melhorias na coautoria** confiabilidade aprimorada durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="3f30e-719">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="3f30e-720">**Colabore em cores:** Comentários e alterações são codificados por cores por colaborador, para que seja fácil ver quem está entre seus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-720">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="3f30e-721">**Edite documentos habilitados para macro de maneira colaborativa:** Salve arquivos docm no OneDrive for Business e edite-os com seus colaboradores em tempo real.</span><span class="sxs-lookup"><span data-stu-id="3f30e-721">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-722">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-722">Office Suite</span></span>

- <span data-ttu-id="3f30e-723">**Transforme tinta manuscrita em formas, texto ou expressões matemáticas no PowerPoint para Office 365:** Vá de tinta de forma livre para formas, texto ou uma expressão matemática com apenas alguns traços.</span><span class="sxs-lookup"><span data-stu-id="3f30e-723">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="3f30e-724">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-724">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-727">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-727">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-728">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-728">Access</span></span>

- <span data-ttu-id="3f30e-729">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="3f30e-729">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="3f30e-730">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-730">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="3f30e-731">Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-731">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="3f30e-732">Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-732">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="3f30e-733">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="3f30e-734">Esta atualização corrige um problema no Microsoft Access que pode causar o erro “A consulta está corrompida” quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada no SQL.</span><span class="sxs-lookup"><span data-stu-id="3f30e-734">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="3f30e-735">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-735">Excel</span></span>

- <span data-ttu-id="3f30e-736">Acelerar o carregamento de arquivos disponíveis na pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-736">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="3f30e-737">Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-737">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="3f30e-738">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-738">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3f30e-739">O Excel falhava em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-739">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="3f30e-740">Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-740">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="3f30e-741">Corrigimos o menu do botão direito do mouse de Gráficos Dinâmicos para habilitar a opção Mostrar Detalhes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-741">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="3f30e-742">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-742">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="3f30e-743">Corrigido um problema em que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-743">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="3f30e-744">Ao salvar como um arquivo CSV, o Excel poderia mesclar todas as colunas em uma única coluna em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-744">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="3f30e-745">Usar Range.ClearContents em um intervalo de uma planilha protegida pode levar mais tempo do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-745">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="3f30e-746">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-746">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="3f30e-747">As macros do VBA que interagem com a faixa de opções podem ser executadas com o conjunto de ScreenUpdating definido como Verdadeiro inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-747">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="3f30e-748">Corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos após copiar uma planilha contendo uma Tabela Dinâmica.</span><span class="sxs-lookup"><span data-stu-id="3f30e-748">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="3f30e-749">A abertura de arquivos CSV estava demorando mais do que o esperado em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="3f30e-749">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="3f30e-750">O Excel pode falhar em algumas circunstâncias ao alternar entre pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="3f30e-750">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="3f30e-751">Correção de um problema com o VBA no qual a escrita de valores em um intervalo seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-751">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="3f30e-752">Os dados copiados de uma coluna filtrada por cores às vezes não serão colados corretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-752">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="3f30e-753">Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, principalmente com janelas ocultas, era mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-753">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="3f30e-754">Solucionado um problema em que os links externos não eram atualizados durante o preenchimento (preencher abaixo, preencher entre, etc.) se o livro de origem estivesse& fechado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-754">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="3f30e-755">Corrigido um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="3f30e-755">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="3f30e-756">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="3f30e-756">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="3f30e-757">Corrigido um problema em que a propriedade "O Valor Cruza Em" no eixo do gráfico se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-757">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="3f30e-758">Correção de um problema que causava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="3f30e-758">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="3f30e-759">Desempenho aprimorado ao excluir colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-759">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="3f30e-760">Correção de um problema em que os nomes de impressora poderiam ser repetidos na lista de impressoras na caixa de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="3f30e-760">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="3f30e-761">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-761">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="3f30e-762">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-762">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="3f30e-763">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="3f30e-763">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="3f30e-764">Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-764">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="3f30e-765">Corrigido um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-765">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="3f30e-766">Correção de um problema em que a mensagem de erro "Esta pasta de trabalho está referenciada por outra pasta e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-766">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="3f30e-767">Correção de um problema em que uma pasta de trabalho poderia ficar oculta ao clicar em um hiperlink em uma pasta de trabalho já aberta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-767">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="3f30e-768">Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, principalmente com janelas ocultas, era mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-768">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="3f30e-769">Em alguns casos, o uso do Application.Evaluate do VBA não funcionava em funções definidas pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-769">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="3f30e-770">Corrigido um problema que alguns usuários podem ter tido com objetos inseridos e vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="3f30e-770">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="3f30e-771">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="3f30e-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f30e-772">Esta atualização corrige um problema que fazia com que a barra de fórmulas exibisse texto em uma fonte diferente da esperada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-772">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="3f30e-773">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="3f30e-773">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f30e-774">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-774">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="3f30e-775">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="3f30e-776">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="3f30e-776">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="3f30e-777">A funcionalidade Texto em Coluna pode falhar em algumas localizações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-777">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="3f30e-778">Solucionado um problema de desempenho durante a criação de gráficos de modelos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-778">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="3f30e-779">Corrigido um problema que fazia com que alguns usuários encontrassem falhas ao converter texto em colunas com células com uma matriz despejada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-779">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="3f30e-780">Usar um Range.Value e Range.Value2 (VBA) faria com que as fórmulas fossem inseridas como matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-780">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="3f30e-781">Correção de um problema em que um símbolo @ iniciando uma fórmula seria considerado um operador de interseção implícito.</span><span class="sxs-lookup"><span data-stu-id="3f30e-781">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="3f30e-782">Correção de um problema em que as planilhas com várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-782">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="3f30e-783">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="3f30e-783">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="3f30e-784">Soluciona um problema que fazia com que os usuários encontrassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-784">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="3f30e-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f30e-785">OneNote</span></span>

- <span data-ttu-id="3f30e-786">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-786">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="3f30e-787">Melhoria da estabilidade do serviço e da sincronia referindo-se temporariamente ao download de arquivos e imagens inseridas em blocos de anotações online até o usuário navegar para a página no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-787">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="3f30e-788">Melhoria da sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-788">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="3f30e-789">Quando um usuário tenta excluir dados que normalmente seriam enviados para a lixeira, os usuários serão solicitados a optar por manter ou excluir permanentemente os dados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-789">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="3f30e-790">Melhoria da estabilidade do serviço e de sincronização, reduzindo temporariamente a frequência do número e da sincronia das páginas do histórico de versão no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-790">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="3f30e-791">Exibe uma notificação que permite ao usuário saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade do serviço e de sincronia.</span><span class="sxs-lookup"><span data-stu-id="3f30e-791">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="3f30e-792">Melhoria da sincronização e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-792">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="3f30e-793">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="3f30e-793">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="3f30e-794">Melhoria da sincronização e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-794">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="3f30e-795">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-795">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="3f30e-796">Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="3f30e-796">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-797">Outlook</span></span>

- <span data-ttu-id="3f30e-798">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-798">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="3f30e-799">Corrige um problema que provocava falhas ocasionais no Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-799">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="3f30e-800">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="3f30e-800">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="3f30e-801">Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-801">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="3f30e-802">Soluciona um problema em que compromissos ou reuniões recorrentes eram exibidos na hora errada ao alterar a definição de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-802">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="3f30e-803">Ao usar o fuso horário de Brasília no ano de 2019, reuniões e compromissos recorrentes são exibidos no timeslot incorreto para o ano 2020.</span><span class="sxs-lookup"><span data-stu-id="3f30e-803">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="3f30e-804">Essa alteração é revelante para clientes no fuso horário de Brasília ou para reuniões e compromissos nesse fuso horário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-804">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="3f30e-805">Essa alteração permite que o Outlook substitua determinadas configurações de fuso horário do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-805">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="3f30e-806">Para invocar uma substituição de fuso horário, você deve configurar uma chave do registro para o usuário atual.</span><span class="sxs-lookup"><span data-stu-id="3f30e-806">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="3f30e-807">O nome da chave do registro deve corresponder ao nome interno do fuso horário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-807">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="3f30e-808">O valor indica o ano da regra de fuso horário a ser usado no lugar do ano vigente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-808">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="3f30e-809">Por exemplo, o valor de substituição da chave do registro a seguir usará a regra de fuso horário brasileiro para o ano de 2020 como regra efetiva.</span><span class="sxs-lookup"><span data-stu-id="3f30e-809">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="3f30e-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="3f30e-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="3f30e-811">Hora Oficial do Brasil"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="3f30e-811">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="3f30e-812">Corrigido um problema que fazia com que os usuários vissem o campo local nas reuniões mudar inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-812">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="3f30e-813">Corrigimos um problema que fazia com que o campo Local nas reuniões fosse atualizado inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-813">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="3f30e-814">Corrige um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após esvaziá-lo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-814">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="3f30e-815">Corrige um problema que fazia com que as vírgulas no campo local de uma reunião se transformassem em ponto e vírgula.</span><span class="sxs-lookup"><span data-stu-id="3f30e-815">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="3f30e-816">Permite ingressar em uma reunião do Teams diretamente por meio do cliente nativo do Teams.</span><span class="sxs-lookup"><span data-stu-id="3f30e-816">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="3f30e-817">Solucionado um problema que fazia com que os usuários com caixas de correio no Exchange 2010 Server tivessem problemas ao adicionar anexos a itens de calendário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-817">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="3f30e-818">Solucionado um problema que fazia com que os usuários tivessem problemas ao responder a mensagens assinadas digitalmente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-818">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="3f30e-819">Solucionado um problema que fazia com que os usuários não conseguissem abrir algumas instâncias de itens de calendário recorrentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-819">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="3f30e-820">Solucionado um problema que fazia com que o Título do Grupo se expandisse inesperadamente em algumas situações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-820">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="3f30e-821">Corrige um problema que fazia com que a largura do painel de pastas fosse alterada inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-821">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="3f30e-822">Soluciona um problema que causava falha no Outlook ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="3f30e-822">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="3f30e-823">Solucionado um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-823">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="3f30e-824">Resolve um problema que pode resultar em uma falha ao exibir o mesmo item em várias janelas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-824">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="3f30e-825">Soluciona um problema que exibia a mensagem “A regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-825">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="3f30e-826">Resolvido um problema que causou perda de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-826">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="3f30e-827">Solucionado um problema que fazia com que os usuários encontrassem um falha ao especificar um Endereço do Remetendo inválido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-827">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="3f30e-828">Solucionado um problema que fazia com que usuários vissem um prompt “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo Regras.</span><span class="sxs-lookup"><span data-stu-id="3f30e-828">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="3f30e-829">Corrige um problema que causava falha na opção para desabilitar o realce de item sinalizado, não sendo respeitado em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-829">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="3f30e-830">Corrigido um problema que fazia com que emails fossem enviados inesperadamente ao pressionar a tecla “S” após fechar o painel do verificador de acessibilidade.</span><span class="sxs-lookup"><span data-stu-id="3f30e-830">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="3f30e-831">Soluciona um problema que fazia com que os usuários encontrassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-831">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="3f30e-832">Soluciona um problema que fazia com que os usuários encontrassem uma falha ao cancelar a configuração da conta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-832">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="3f30e-833">Corrige um problema que fazia com que o Outlook sincronizasse inesperadamente todos os e-mails, mesmo quando o controle deslizante de sincronização estivesse definido como uma configuração menor.</span><span class="sxs-lookup"><span data-stu-id="3f30e-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="3f30e-834">Resolve um problema que fazia com que os usuários com o Tema Preto vissem a lista suspensa “De” como um texto branco sobre um fundo branco.</span><span class="sxs-lookup"><span data-stu-id="3f30e-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="3f30e-835">Soluciona um problema que fazia com que os usuários encontrassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="3f30e-835">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="3f30e-836">Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-836">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="3f30e-837">Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-837">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="3f30e-838">Resolve um problema que fazia com que aplicativos de terceiros não pudessem enviar e-mails.</span><span class="sxs-lookup"><span data-stu-id="3f30e-838">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="3f30e-839">Resolve um problema que fazia as categorias desaparecerem ocasionalmente das mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="3f30e-839">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="3f30e-840">Solucionamos um problema que fazia com que os usuários do Outlook nos sistemas operacionais de servidor vissem o erro "Status do antivírus: inválido".</span><span class="sxs-lookup"><span data-stu-id="3f30e-840">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="3f30e-841">Esta versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus foi encontrado” mesmo após a configuração correta do antivírus.</span><span class="sxs-lookup"><span data-stu-id="3f30e-841">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="3f30e-842">Resolve um problema que fazia com que representantes vissem diferentes hierarquias de pastas em caixas de correio compartilhadas em computadores diferentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-842">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="3f30e-843">Aborda um problema que fazia com que os representantes recebessem uma mensagem de erro ao editar um compromisso existente no calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="3f30e-843">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="3f30e-844">Solucionamos um problema que fazia com que os usuários com a configuração de emulação do navegador incorreta não conseguissem concluir o prompt de autenticação do Gmail.</span><span class="sxs-lookup"><span data-stu-id="3f30e-844">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="3f30e-845">Consertamos um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, caso a pasta compartilhada Download não fosse verificada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-845">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="3f30e-846">Soluciona um problema que fazia com que os usuários encontrassem uma falha ao tentar abrir arquivos .msg e .oft após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-846">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="3f30e-847">Soluciona um problema que fazia com que os usuários encontrassem uma falha ao pressionar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="3f30e-847">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="3f30e-848">Solucionado um problema que fazia com que os usuários encontrassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-848">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="3f30e-849">Corrige um problema que fazia com que o botão Salvar na nuvem não aparecesse nas Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-849">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="3f30e-850">Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.</span><span class="sxs-lookup"><span data-stu-id="3f30e-850">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="3f30e-851">Correção de um problema que causava uma falha quando dois suplementos adicionam um botão ao mesmo grupo da faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="3f30e-851">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="3f30e-852">Correção de um problema que fazia com que os links não fossem adicionados aos emails com a permissão de locatário padrão correta quando a permissão de locatário padrão está configurada como "qualquer pessoa".</span><span class="sxs-lookup"><span data-stu-id="3f30e-852">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="3f30e-853">Solucionamos um problema que fazia com que os usuários não conseguissem endereçar os emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="3f30e-853">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="3f30e-854">Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-854">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="3f30e-855">Corrige um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="3f30e-855">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="3f30e-856">Consertamos um problema que podia impedir que os arquivos fossem salvos em um local do WebDAV.</span><span class="sxs-lookup"><span data-stu-id="3f30e-856">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="3f30e-857">Aborda um problema que fazia com que os usuários não conseguissem salvar anexos do OneDrive de fora de seu locatário em seu computador local ao selecionar a opção “Salvar” na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="3f30e-857">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="3f30e-858">Correção de um problema que fazia com que o corpo de uma mensagem de Notificação de Falha na Entrega mudasse de Unicode para ASCII após editar o assunto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-858">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="3f30e-859">Corrigido um problema que fazia com que usuários observassem uma perda de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-859">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="3f30e-860">Solucionamos um problema que fazia com que os usuários vissem os emails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="3f30e-860">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="3f30e-861">Corrigido um problema que provocava um alinhamento inadequado da caixa de pesquisa no modo de DPI alto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-861">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="3f30e-862">Soluciona um problema que fazia com que os usuários encontrassem travamentos no Outlook ao recuperar as configurações da nuvem.</span><span class="sxs-lookup"><span data-stu-id="3f30e-862">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="3f30e-863">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-863">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="3f30e-864">Corrige um problema que provocava falhas ocasionais no Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-864">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="3f30e-865">Soluciona um problema que fazia com que os usuários encontrassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-865">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="3f30e-866">Soluciona um problema que fazia com que os usuários encontrassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="3f30e-866">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="3f30e-867">Corrige um problema que provocava falhas ocasionais no Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-867">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f30e-868">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-868">PowerPoint</span></span>

- <span data-ttu-id="3f30e-869">Soluciona um problema que pode ter causado uma falha ao usar o menu de contexto em comentários de PPT herdados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-869">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="3f30e-870">Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-la em outro slide em um loop.</span><span class="sxs-lookup"><span data-stu-id="3f30e-870">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="3f30e-871">Corrige de um problema de retransmissão de mensagens corretas para os usuários que abrirem uma cópia de um arquivo que tenha comentários melhorados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-871">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="3f30e-872">Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-872">Project</span></span>

- <span data-ttu-id="3f30e-873">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-873">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="3f30e-874">Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="3f30e-874">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="3f30e-875">Solucionamos um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-875">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="3f30e-876">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="3f30e-876">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="3f30e-877">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura</span><span class="sxs-lookup"><span data-stu-id="3f30e-877">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="3f30e-878">Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="3f30e-878">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-879">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-879">Word</span></span>

- <span data-ttu-id="3f30e-880">Soluciona um problema que fazia com que os usuários encontrassem uma falha ao pressionar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="3f30e-880">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="3f30e-881">Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-881">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="3f30e-882">Corrigimos um problema com o ajuste de texto em uma tabela.</span><span class="sxs-lookup"><span data-stu-id="3f30e-882">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="3f30e-883">Corrigimos um problema em que não era possível inserir linhas horizontais e centralizar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-883">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="3f30e-884">O organizador de blocos de construção pode exibir um alerta inválido: “Você modificou estilos, blocos de construção”.</span><span class="sxs-lookup"><span data-stu-id="3f30e-884">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="3f30e-885">Correção de um problema na coautoria se habilitarmos a política FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="3f30e-885">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="3f30e-886">Correção de um problema em que partes rápidas no Word não funcionava ao adicionar um campo de pesquisa que foi renomeado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-886">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="3f30e-887">Corrigimos um problema ao unir dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-887">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="3f30e-888">Corrigimos um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="3f30e-888">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="3f30e-889">Esta atualização corrige um problema no Microsoft Word, em que textos com mais de 255 caracteres inseridos durante a aplicação de um rótulo de sensibilidade não poderiam ser subsequentemente identificados e removidos alterando ou removendo a etiqueta se a política de rótulo tiver aplicado um cabeçalho, rodapé ou marca-d ' água.</span><span class="sxs-lookup"><span data-stu-id="3f30e-889">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-890">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-890">Office Suite</span></span>

- <span data-ttu-id="3f30e-891">Correção de um problema em que poderia ocorrer uso excessivo da rede e da CPU durante a coautoria em arquivos grandes do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-891">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="3f30e-892">Esta é uma correção para que o aplicativo do Project não bloqueie rede quando o arquivo estiver armazenado em cache no cliente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-892">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="3f30e-893">Resolvemos esse problema atualizando os nomes dos canais no backstage para os nomes dos novos canais na bifurcação de Janeiro de 2020.</span><span class="sxs-lookup"><span data-stu-id="3f30e-893">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="3f30e-894">Corrigimos esse problema e no futuro, se um dispositivo for gerenciado por política, ele não chamará a API de audiência do DMS.</span><span class="sxs-lookup"><span data-stu-id="3f30e-894">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="3f30e-895">Resolvido o problema em que há uma remoção incompleta ao adicionar e remover aplicativos em uma única transação.</span><span class="sxs-lookup"><span data-stu-id="3f30e-895">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="3f30e-896">Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-896">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="3f30e-897">Corrige um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Gerenciador de Configurações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-897">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="3f30e-898">Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-898">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="3f30e-899">Fizemos um novo AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="3f30e-899">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="3f30e-900">Resolvemos o problema em que uma operação interna estava gerando uma exceção na falha, em vez de fazer o logon e continuar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-900">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="3f30e-901">Os usuários afetados não serão mais impedidos de receber as atualizações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-901">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="3f30e-902">A nossa equipe adicionou o suporte ao cliente para informar os domínios CDN do Office na Visualização Semestral Anual.</span><span class="sxs-lookup"><span data-stu-id="3f30e-902">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="3f30e-903">Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.</span><span class="sxs-lookup"><span data-stu-id="3f30e-903">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="3f30e-904">Essa alteração garante que a estrutura de tópicos Esboçada funcione corretamente na faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="3f30e-904">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="3f30e-905">Corrigimos um problema ao abrir arquivos de locais no ambiente local com algumas configurações específicas de proxy.</span><span class="sxs-lookup"><span data-stu-id="3f30e-905">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="3f30e-906">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="3f30e-907">Correção de um problema que elimina panes durante as sessões de entrega do Office e maior confiabilidade na experiência do usuário.</span><span class="sxs-lookup"><span data-stu-id="3f30e-907">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="3f30e-908">Esse bug atualiza o ponto de extremidade da URL do serviço de configuração avançada (ECS).</span><span class="sxs-lookup"><span data-stu-id="3f30e-908">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="3f30e-909">Chamar esse ponto de extremidade mais recente tem uma taxa de sucesso maior para buscar a partir de ECS.</span><span class="sxs-lookup"><span data-stu-id="3f30e-909">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="3f30e-910">Esta atualização corrige um problema com o Microsoft Outlook, que não exibia o rótulo de confidencialidade atual ao exibir ou redigir mensagens.</span><span class="sxs-lookup"><span data-stu-id="3f30e-910">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="3f30e-911">Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.</span><span class="sxs-lookup"><span data-stu-id="3f30e-911">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="3f30e-912">Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-912">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="3f30e-913">O host do Office estava falhando no Windows quando um suplemento era ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era definida como zero.</span><span class="sxs-lookup"><span data-stu-id="3f30e-913">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="3f30e-914">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="3f30e-914">This change would fix this issue.</span></span>

- <span data-ttu-id="3f30e-915">Resolvemos o problema em que o Access e o Publisher podiam não inicializar corretamente dependendo de quais idiomas foram instalados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-915">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)





[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-july-14"></a><span data-ttu-id="3f30e-918">Versão 1908: 14 de julho</span><span class="sxs-lookup"><span data-stu-id="3f30e-918">Version 1908: July 14</span></span>
<span data-ttu-id="3f30e-919">*Versão 1908 (Build 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-919">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="3f30e-920">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-920">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-922">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-923">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-923">Access</span></span>

- <span data-ttu-id="3f30e-924">Essa atualização corrige um problema em que agregados como Soma podem truncar o resultado para um valor inteiro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-924">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="3f30e-925">Essa atualização corrige um problema em que uma consulta da União que inclui referências a tabelas remotas (por exemplo, tabelas do SQL Server) pode fazer o Access fechar e reiniciar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-925">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="3f30e-926">Esta atualização corrige um problema no Microsoft Access que pode causar o erro “A consulta está corrompida” quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada no SQL.</span><span class="sxs-lookup"><span data-stu-id="3f30e-926">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="3f30e-927">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-927">Excel</span></span>

- <span data-ttu-id="3f30e-928">A dica de tecla holandesa para o título do documento foi alterada para Alt-G.</span><span class="sxs-lookup"><span data-stu-id="3f30e-928">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="3f30e-929">Correção de um problema no Excel em que as macros atribuídas a formas ou controles de formulário podem exibir mensagem de erro incorreta ou podem funcionar em intervalos de destino incorretos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-929">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="3f30e-930">Resolvemos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item.</span><span class="sxs-lookup"><span data-stu-id="3f30e-930">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="3f30e-931">Isso corrige um problema em que é possível alterar a forma como uma Tabela Dinâmica é classificada e atualizá-la durante uma sessão de coautoria com outros usuários poderia causar uma falha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-931">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="3f30e-932">Corrigido um problema onde o filtro de uma Tabela Dinâmica OLAP era definido como um valor que havia sido removido do cubo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-932">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="3f30e-933">Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.</span><span class="sxs-lookup"><span data-stu-id="3f30e-933">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="3f30e-934">Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série</span><span class="sxs-lookup"><span data-stu-id="3f30e-934">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="3f30e-935">Correção relacionada às cores utilizadas nas visualizações ao inserir gráficos usando modelos de gráfico.</span><span class="sxs-lookup"><span data-stu-id="3f30e-935">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="3f30e-936">Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-936">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="3f30e-937">Correção de um problema de conflito de mesclagem no Excel, que resultaria na reabertura de uma pasta de trabalho para os usuários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-937">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="3f30e-938">Resolvido um problema que causava um erro no tempo de execução da macro ao ativar janelas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-938">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="3f30e-939">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-939">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3f30e-940">Resolveu um problema que fazia com que as operações de recortar e colar próximas de uma tabela falhassem durante coautoria com outras pessoas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-940">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="3f30e-941">Resolvemos um problema que causou interrupções na coautoria ao alterar propriedades personalizadas com a execução de macros.</span><span class="sxs-lookup"><span data-stu-id="3f30e-941">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="3f30e-942">Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-942">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="3f30e-943">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-943">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="3f30e-944">Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-944">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="3f30e-945">Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-945">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="3f30e-946">Corrigimos um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-946">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="3f30e-947">Corrigimos um problema com o VBA no qual a escrita de valores em um intervalo seria menor do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-947">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="3f30e-948">Corrigido um problema em que a propriedade "O Valor Cruza Em" no eixo do gráfico se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-948">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="3f30e-949">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="3f30e-949">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="3f30e-950">Foi corrigido um problema que levava à lentidão no desempenho ao excluir colunas contendo células mescladas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-950">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="3f30e-951">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-951">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="3f30e-952">Ao copiar dados filtrados por cor para uma coluna com uma largura diferente, os valores não seriam colados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-952">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="3f30e-953">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="3f30e-953">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="3f30e-954">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-954">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="3f30e-955">Corrigido um problema em que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-955">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="3f30e-956">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="3f30e-956">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="3f30e-957">A funcionalidade Texto em Coluna pode falhar para algumas localidades.</span><span class="sxs-lookup"><span data-stu-id="3f30e-957">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="3f30e-958">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-958">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="3f30e-959">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="3f30e-959">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f30e-960">Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.</span><span class="sxs-lookup"><span data-stu-id="3f30e-960">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="3f30e-961">Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.</span><span class="sxs-lookup"><span data-stu-id="3f30e-961">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="3f30e-962">Melhorias significativas no desempenho da exclusão de colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-962">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="3f30e-963">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-963">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="3f30e-964">Resolvido um problema em que a função Proc poderia retornar um erro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-964">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="3f30e-965">Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-965">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="3f30e-966">Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-966">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="3f30e-967">Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-967">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="3f30e-968">Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-968">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="3f30e-969">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="3f30e-969">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="3f30e-970">Melhoramos significativamente o desempenho da filtragem por cor.</span><span class="sxs-lookup"><span data-stu-id="3f30e-970">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="3f30e-971">Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-971">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="3f30e-972">Habilitamos mais de 16 suplementos para serem exibidos ao navegar no gerenciador de suplementos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-972">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="3f30e-973">Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-973">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="3f30e-974">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="3f30e-974">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="3f30e-975">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-975">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-976">Esta atualização corrige um erro em que os documentos do Office podem falhar ao carregar no OneDrive for Business com a mensagem "Falha no Carregamento".</span><span class="sxs-lookup"><span data-stu-id="3f30e-976">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="3f30e-977">Corrigimos um problema no recurso Ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="3f30e-977">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="3f30e-978">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f30e-978">OneNote</span></span>

- <span data-ttu-id="3f30e-979">Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="3f30e-979">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-980">Outlook</span></span>

- <span data-ttu-id="3f30e-981">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-981">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-982">Correção de um problema em que os usuários que atualizavam a caixa de correio de uma autenticação básica para a moderna acabavam com a conta errada associada ao perfil do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-982">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="3f30e-983">Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais quando não deveriam.</span><span class="sxs-lookup"><span data-stu-id="3f30e-983">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="3f30e-984">Resolvido um problema que provocou falha na exibição de URLs de foco simples em alguns safelinks.</span><span class="sxs-lookup"><span data-stu-id="3f30e-984">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="3f30e-985">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="3f30e-985">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="3f30e-986">Corrige um problema que fazia com que um subconjunto de usuários POP3 visualizasse todos os seus e-mails formatados em texto simples, independentemente das configurações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-986">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="3f30e-987">Essa correção restaurará o modo de exibição das mensagens formatadas como HTML.</span><span class="sxs-lookup"><span data-stu-id="3f30e-987">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="3f30e-988">Resolvido um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-988">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="3f30e-989">Resolvido um problema que fazia com que os usuários não conseguissem acessar sugestões de localização por meio de um leitor de tela.</span><span class="sxs-lookup"><span data-stu-id="3f30e-989">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="3f30e-990">Solucionado um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-990">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="3f30e-991">Resolvido um problema que causou perda de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-991">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="3f30e-992">Solucionado um problema que fazia com que os usuários encontrassem um falha ao especificar um Endereço do Remetendo inválido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-992">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="3f30e-993">Solucionado um problema que fazia com que usuários vissem um prompt “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo Regras.</span><span class="sxs-lookup"><span data-stu-id="3f30e-993">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="3f30e-994">Resolvido um problema que faria com que os usuários encontrassem uma falha no Outlook ao interagir com determinados safelinks.</span><span class="sxs-lookup"><span data-stu-id="3f30e-994">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="3f30e-995">Corrige um problema que causava ambiguidade para os gerentes em que um representante já havia ou não respondido a uma determinada solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="3f30e-995">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="3f30e-996">Resolvido um problema que fazia com que os usuários encontrassem uma falha ao processar algumas respostas de Descoberta Automática.</span><span class="sxs-lookup"><span data-stu-id="3f30e-996">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="3f30e-997">Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-997">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="3f30e-998">Essa alteração permite que os administradores habilitem uma política para preferir o email da conta fornecida nos prompts de autenticação da Descoberta Automática no UPN.</span><span class="sxs-lookup"><span data-stu-id="3f30e-998">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="3f30e-999">Por padrão, a Descoberta Automática prefere o UPN da conta, quando disponível.</span><span class="sxs-lookup"><span data-stu-id="3f30e-999">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="3f30e-1000">Soluciona um problema que fazia com que os usuários vissem falhas de pesquisa em Grupos Modernos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1000">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="3f30e-1001">Resolvido um problema que fazia com que os usuários do Outlook não saíssem do estado "Senha Necessária" em determinadas situações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1001">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="3f30e-1002">Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1002">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="3f30e-1003">Solucionado um problema que fazia com que os usuários encontrassem uma falha ao abrir arquivos msg e .oft após aplicar uma atualização recente do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1003">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="3f30e-1004">Solucionado um problema que fazia com que os usuários encontrassem um travamento na tela Carregando perfil ao iniciar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1004">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="3f30e-1005">Solucionado um problema que fazia com que os usuários encontrassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1005">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="3f30e-1006">Corrige um problema que fazia com que o botão “Salvar na nuvem” não aparecesse nas Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1006">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="3f30e-1007">Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1007">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="3f30e-1008">Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1008">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="3f30e-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = exibirá apenas o PolicyName no texto da Política de retenção.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="3f30e-1010">Solucionado um problema que fazia com que os usuários encontrassem uma falha ao desligar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1010">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="3f30e-1011">Solucionado um problema que fazia com que uma lista de salas vazia fosse exibida para os clientes em algumas situações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1011">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="3f30e-1012">Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1012">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="3f30e-1013">Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1013">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="3f30e-1014">Soluciona um problema que fazia com que os usuários encontrassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1014">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="3f30e-1015">Aqui está o [KB individual em que isso foi documentado para versões anteriores](https://support.microsoft.com/pt-BR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1015">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/pt-BR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="3f30e-1016">Corrigido um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1016">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="3f30e-1017">Corrige um problema que fazia com que as Dicas de política deixassem de ser exibidas ao usar um remetente alternativo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1017">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="3f30e-1018">Resolvido um problema que fazia com que os usuários vissem sugestões de salas para reuniões que ocorriam fora do horário de disponibilidade dessa sala.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1018">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="3f30e-1019">Corrigido um problema para usuários não falantes de inglês, onde a linha de assunto em um email seria muito pequena.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1019">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="3f30e-1020">Resolvido um problema que fazia com que os usuários encontrassem uma falha ao tentar criar uma regra a partir de uma mensagem de “Conversa Perdida”.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1020">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="3f30e-1021">Corrigido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1021">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="3f30e-1022">Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1022">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="3f30e-1023">Corrigido um problema que fazia com que usuários observassem uma perda de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1023">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="3f30e-1024">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1024">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="3f30e-1025">Aborda um problema que causou falha intermitente na pesquisa da pasta atual.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1025">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="3f30e-1026">Corrigido um problema que fazia com que alguns usuários encontrassem erros de autenticação ao tentar recuperar as configurações de nuvem do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1026">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="3f30e-1027">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1027">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="3f30e-1028">Resolvido um problema que fazia com que os usuários encontrassem uma falha ao processar algumas respostas de Descoberta Automática.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1028">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="3f30e-1029">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1029">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f30e-1030">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1030">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1031">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1031">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-1032">Essa alteração restaura o nome acessível para os controles de vídeo do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1032">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="3f30e-1033">Corrigido um problema que poderia impedir a inicialização de algumas animações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1033">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="3f30e-1034">Corrigido um problema que poderia criar mestres ao copiar um slide de uma apresentação para outra.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1034">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="3f30e-1035">Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-la em outro slide em um loop.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1035">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="3f30e-1036">Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1036">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="3f30e-1037">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1037">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="3f30e-1038">Corrigido um problema que causava lentidão no desempenho entre os usuários da colaboração.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1038">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="3f30e-1039">Correção de confiabilidade: corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1039">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="3f30e-1040">Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1040">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="3f30e-1041">Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1041">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="3f30e-1042">Corrigido um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1042">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="3f30e-1043">Correção de um problema em que alguns suplementos lançavam erros inesperados relacionados às formas nos gráficos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1043">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="3f30e-1044">Impede que os usuários do PowerPoint se deparem com erro ao tentar Apresentar Online.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1044">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="3f30e-1045">Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-1045">Project</span></span>

- <span data-ttu-id="3f30e-1046">Correção de um problema para que os usuários do Windows 7 possam abrir projetos do Project Web App e sites do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1046">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="3f30e-1047">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1047">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="3f30e-1048">O comando Nivelar Tudo não resolve adequadamente uma superalocação de recursos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1048">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="3f30e-1049">Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1049">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="3f30e-1050">Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1050">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="3f30e-1051">Skype</span><span class="sxs-lookup"><span data-stu-id="3f30e-1051">Skype</span></span>

- <span data-ttu-id="3f30e-1052">Nome do título fixo da conversa com guias enquanto mais de uma conversa está em andamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1052">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="3f30e-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1053">Visio</span></span>

- <span data-ttu-id="3f30e-1054">A exportação como SVG do Visio falhou em várias formas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-1055">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1055">Word</span></span>

- <span data-ttu-id="3f30e-1056">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1056">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-1057">Corrigido um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet</span><span class="sxs-lookup"><span data-stu-id="3f30e-1057">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="3f30e-1058">Corrigido um problema no ajuste de texto de tabela.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1058">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="3f30e-1059">Corrigido um problema no controle de alterações que, às vezes, entravam em loop infinito.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="3f30e-1060">Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1060">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="3f30e-1061">Corrigimos um problema ao unir dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1061">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="3f30e-1062">Corrigimos um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1062">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="3f30e-1063">Correção de vários problemas em que o aplicativo pode travar no desligamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1063">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="3f30e-1064">E também corrige determinadas falhas relacionadas aos suplementos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1064">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-1065">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1065">Office Suite</span></span>

- <span data-ttu-id="3f30e-1066">Corrigido de um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1066">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="3f30e-1067">Corrigido um problema que fazia com que os usuários recebessem a mensagem "Algo está nos impedindo de compartilhar isso" ao tentar compartilhar arquivos armazenados no SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1067">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="3f30e-1068">Corrigido um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1068">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="3f30e-1069">Esta é uma correção para uma falha que os usuários podem encontrar ao abrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1069">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="3f30e-1070">Em alguns casos, um arquivo do mecanismo de sincronização do SharePoint poderia exibir "Salvo", mas não ter salvado alterações, o que resulta em perda de dados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1070">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="3f30e-1071">Resolvemos um problema em que os usuários poderiam não conseguir salvar documentos do Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1071">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="3f30e-1072">Esse problema afeta os usuários que criam um novo arquivo e escolhem a opção "caixa de diálogo Salvar como" depois de clicar no ícone Salvar ou pressionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1072">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="3f30e-1073">Corrigida uma falha no Word afastando-se de uma API preterida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1073">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="3f30e-1074">Corrigido um problema em que os caracteres katakana de meia largura não giravam corretamente nas caixas de texto verticais no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1074">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="3f30e-1075">Corrigido um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1075">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="3f30e-1076">Corrigido um bug em que as informações de acessibilidade não estavam sendo exibidas na laje Info Place dos bastidores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1076">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="3f30e-1077">Melhora a confiabilidade do processo de atualização do Office referente à integridade do registro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1077">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="3f30e-1078">Atualizamos os nomes dos canais das bifurcações de janeiro e julho de 2019 para os novos nomes de canal.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1078">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="3f30e-1079">Corrigido um problema em que as atualizações poderiam ser bloqueadas inesperadamente em redes limitadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1079">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="3f30e-1080">Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1080">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="3f30e-1081">Em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1081">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="3f30e-1082">Essa atualização melhora a confiabilidade ao publicar os atalhos do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1082">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="3f30e-1083">Corrige um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Gerenciador de Configurações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1083">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="3f30e-1084">Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a conta do sistema não tinha conectividade de rede.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1084">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="3f30e-1085">Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1085">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="3f30e-1086">Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1086">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="3f30e-1087">Maior confiabilidade ao baixar as atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1087">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="3f30e-1088">Correção de problemas relacionados à propriedade AutoAjuste da Caixa de Texto/Forma em plug-ins de terceiros.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1088">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="3f30e-1089">Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1089">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="3f30e-1090">Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1090">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="3f30e-1091">Correção de um problema que grandes modos de exibição em árvore poderiam resultar em falha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1091">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="3f30e-1092">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1092">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="3f30e-1093">Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1093">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="3f30e-1094">Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1094">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-july-14"></a><span data-ttu-id="3f30e-1096">Versão 1902: 14 de julho</span><span class="sxs-lookup"><span data-stu-id="3f30e-1096">Version 1902: July 14</span></span>
<span data-ttu-id="3f30e-1097">*Versão 1902 (Build 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1097">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="3f30e-1098">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1098">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="3f30e-1099">Versão 1908: 09 de junho</span><span class="sxs-lookup"><span data-stu-id="3f30e-1099">Version 1908: June 09</span></span>
<span data-ttu-id="3f30e-1100">*Versão 1908 (Build 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1100">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="3f30e-1101">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1101">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1103">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1103">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1104">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1104">Excel</span></span>

- <span data-ttu-id="3f30e-1105">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1105">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="3f30e-1106">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1106">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="3f30e-1107">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="3f30e-1107">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-1108">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1108">Outlook</span></span>

- <span data-ttu-id="3f30e-1109">Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1109">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-1110">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1110">Office Suite</span></span>

- <span data-ttu-id="3f30e-1111">Atualizamos os nomes dos canais para as bifurcações de janeiro e julho de 2019 para os novos nomes de canal.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1111">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-june-09"></a><span data-ttu-id="3f30e-1113">Versão 1902: 09 de junho</span><span class="sxs-lookup"><span data-stu-id="3f30e-1113">Version 1902: June 09</span></span>
<span data-ttu-id="3f30e-1114">*Versão 1902 (Build 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1114">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="3f30e-1115">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1117">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1117">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="3f30e-1118">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1118">Office Suite</span></span>

- <span data-ttu-id="3f30e-1119">Atualizamos os nomes dos canais para as bifurcações de janeiro e julho de 2019 para os novos nomes de canal.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1119">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="3f30e-1120">Removemos referências obsoletas dos arquivos de linha de base que estavam dividindo a compilação C2R.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1120">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-may-12"></a><span data-ttu-id="3f30e-1122">Versão 1908: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1122">Version 1908: May 12</span></span>
<span data-ttu-id="3f30e-1123">*Versão 1908 (Build 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1123">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="3f30e-1124">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1124">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1126">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1126">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1127">Excel</span></span>

- <span data-ttu-id="3f30e-1128">Ao copiar dados filtrados por cor para uma coluna com uma largura diferente, os valores não seriam colados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1128">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1129">Outlook</span></span>

- <span data-ttu-id="3f30e-1130">Resolvido um problema que fazia com que os usuários travassem ao abrir arquivos msg e oft após a aplicação de uma atualização recente do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1130">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-1131">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1131">Word</span></span>

- <span data-ttu-id="3f30e-1132">Corrigimos um problema ao unir dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="3f30e-1133">Corrigimos um problema com o recurso comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-may-12"></a><span data-ttu-id="3f30e-1135">Versão 1902: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1135">Version 1902: May 12</span></span>
<span data-ttu-id="3f30e-1136">*Versão 1902 (Build 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="3f30e-1137">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1139">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="3f30e-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1140">Outlook</span></span>

- <span data-ttu-id="3f30e-1141">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao abrir arquivos. msg e. oft após aplicar uma atualização recente do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="3f30e-1142">Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="3f30e-1143">Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="3f30e-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="3f30e-1145">0 = Padrão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1145">0 = Default.</span></span>  <span data-ttu-id="3f30e-1146">1 = mostraremos apenas a política de texto de política de retenção.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-may-04"></a><span data-ttu-id="3f30e-1148">Versão 1908: 04 de maio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1148">Version 1908: May 04</span></span>
<span data-ttu-id="3f30e-1149">*Versão 1908 (Criação 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1149">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="3f30e-1150">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1151">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1151">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="3f30e-1152">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1152">Outlook</span></span>

- <span data-ttu-id="3f30e-1153">Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1153">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="3f30e-1154">Foi solucionado um problema que fazia com que o botão "Salvar na nuvem" não estivesse presente nas Ferramentas de Anexo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1154">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="3f30e-1155">Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1155">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="3f30e-1156">Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1156">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="3f30e-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="3f30e-1158">0 = Padrão 1 = mostraremos apenas o PolicyName para o texto da política de Retenção.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1158">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-1159">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1159">Office Suite</span></span>

- <span data-ttu-id="3f30e-1160">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1160">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="3f30e-1161">Versão 1902: 04 de maio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1161">Version 1902: May 04</span></span>
<span data-ttu-id="3f30e-1162">*Versão 1902 (Build 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1162">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1163">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1163">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="3f30e-1164">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1164">Office Suite</span></span>

- <span data-ttu-id="3f30e-1165">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1165">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="3f30e-1166">Versão 1908: 26 de abril</span><span class="sxs-lookup"><span data-stu-id="3f30e-1166">Version 1908: April 26</span></span>
<span data-ttu-id="3f30e-1167">*Versão 1908 (Build 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1167">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="3f30e-1168">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1168">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1169">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1170">Excel</span></span>

- <span data-ttu-id="3f30e-1171">Corrigimos um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1171">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="3f30e-1172">Corrigimos um problema com o VBA no qual a escrita de valores em um intervalo seria menor do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1172">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="3f30e-1173">Corrigimos um problema em que a propriedade "O Valor Cruza Em" se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1173">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="3f30e-1174">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1174">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="3f30e-1175">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f30e-1175">OneNote</span></span>

- <span data-ttu-id="3f30e-1176">Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1176">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="3f30e-1177">Versão 1908: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="3f30e-1177">Version 1908: April 14</span></span>
<span data-ttu-id="3f30e-1178">*Versão 1908 (Build 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1178">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="3f30e-1179">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1181">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1182">Excel</span></span>

- <span data-ttu-id="3f30e-1183">Foi corrigido um problema que levava à lentidão no desempenho ao excluir colunas contendo células mescladas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1183">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="3f30e-1184">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1184">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="3f30e-1185">Skype</span><span class="sxs-lookup"><span data-stu-id="3f30e-1185">Skype</span></span>

- <span data-ttu-id="3f30e-1186">Nome do título fixo da conversa com guias enquanto mais de uma conversa está em andamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1186">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1187">Outlook</span></span>

- <span data-ttu-id="3f30e-1188">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao desligar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1188">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="3f30e-1189">Solucionamos um problema que fazia com que uma lista de salas vazia fosse exibida para os clientes em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1189">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f30e-1190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1190">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1191">Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1191">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-1192">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1192">Word</span></span>

- <span data-ttu-id="3f30e-1193">Foi corrigido um problema no ajuste de texto de tabela.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1193">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="3f30e-1194">Versão 1902: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="3f30e-1194">Version 1902: April 14</span></span>
<span data-ttu-id="3f30e-1195">*Versão 1902 (Build 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1195">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="3f30e-1196">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-march-10"></a><span data-ttu-id="3f30e-1198">Versão 1908: 10 de março</span><span class="sxs-lookup"><span data-stu-id="3f30e-1198">Version 1908: March 10</span></span>
<span data-ttu-id="3f30e-1199">*Versão 1908 (Build 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1199">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="3f30e-1200">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1202">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1203">Excel</span></span>

- <span data-ttu-id="3f30e-1204">Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1204">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="3f30e-1205">A funcionalidade Texto em Coluna pode falhar para algumas localidades.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1205">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="3f30e-1206">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1206">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f30e-1207">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1207">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1208">Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1208">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="3f30e-1209">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1209">Word</span></span>

- <span data-ttu-id="3f30e-1210">Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1210">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f30e-1211">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1211">Office Suite</span></span>

- <span data-ttu-id="3f30e-1212">Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1212">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="3f30e-1213">Versão 1902: 10 de março</span><span class="sxs-lookup"><span data-stu-id="3f30e-1213">Version 1902: March 10</span></span>
<span data-ttu-id="3f30e-1214">*Versão 1902 (Build 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1214">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="3f30e-1215">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1215">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a><span data-ttu-id="3f30e-1217">Versão 1908: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-1217">Version 1908: February 11</span></span>
<span data-ttu-id="3f30e-1218">*Versão 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1218">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="3f30e-1219">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1219">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1221">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1222">Excel</span></span>

- <span data-ttu-id="3f30e-1223">Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1223">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="3f30e-1224">Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1224">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="3f30e-1225">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1225">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f30e-1226">Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1226">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="3f30e-1227">Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1227">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="3f30e-1228">Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1228">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f30e-1229">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1229">Outlook</span></span>

- <span data-ttu-id="3f30e-1230">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1230">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="3f30e-1231">Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1231">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="3f30e-1232">Solucionado um problema que fazia com que os usuários experimentassem um travamento na tela Carregando perfil ao iniciar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1232">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="3f30e-1233">Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1233">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="3f30e-1234">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1234">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="3f30e-1235">[Aqui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1235">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="3f30e-1236">Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1236">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f30e-1237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1237">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1238">Melhorou um cenário de copiar e colar Copiando a Forma no slide do powerpoint e colando em outro slide em um loop poderia falhar, com exceção.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1238">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="3f30e-1239">Corrigido um problema que estava causando um desempenho mais lento entre os usuários da colaboração.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1239">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="3f30e-1240">Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1240">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="3f30e-1241">Corrigimos um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1241">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="3f30e-1242">Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-1242">Project</span></span>

- <span data-ttu-id="3f30e-1243">Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1243">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-1244">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1244">Word</span></span>

- <span data-ttu-id="3f30e-1245">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1245">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-1246">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1246">Office Suite</span></span>

- <span data-ttu-id="3f30e-1247">Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1247">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-february-11"></a><span data-ttu-id="3f30e-1249">Versão 1902: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-1249">Version 1902: February 11</span></span>
<span data-ttu-id="3f30e-1250">*Versão 1902 (Build 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1250">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="3f30e-1251">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1251">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1253">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1253">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="3f30e-1254">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1254">Outlook</span></span>

- <span data-ttu-id="3f30e-1255">Solucionado um problema que fazia com que os usuários encontrassem erros no algoritmo de criptografia ao enviar um email criptografado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1255">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="3f30e-1256">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1256">Word</span></span>

- <span data-ttu-id="3f30e-1257">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1257">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

## <a name="version-1808-february-11"></a><span data-ttu-id="3f30e-1260">Versão 1808: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-1260">Version 1808: February 11</span></span>
<span data-ttu-id="3f30e-1261">*Versão 1808 (Build 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1261">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="3f30e-1262">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1262">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a><span data-ttu-id="3f30e-1264">Versão 1908:14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-1264">Version 1908: January 14</span></span>
<span data-ttu-id="3f30e-1265">*Versão 1908 (Build 11929,20562)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1265">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="3f30e-1266">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1266">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="3f30e-1268">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1268">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-1269">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-1269">Access</span></span>

- <span data-ttu-id="3f30e-1270">**Manter as guias dos objetos de banco de dados:** Veja as guias ativas, arraste as guias facilmente para reorganizá-las, e feche os objetos de banco de dados com apenas um clique.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1270">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="3f30e-1271">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1271">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="3f30e-1272">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1272">Switching between them has never been easier.</span></span> [<span data-ttu-id="3f30e-1273">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1273">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="3f30e-1274">**Aplicar zoom com mais espaço:** aumente a caixa Zoom, altere a fonte e o Zoom lembrará de tudo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1274">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="3f30e-1275">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1275">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="3f30e-1276">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1276">Excel</span></span>

- <span data-ttu-id="3f30e-1277">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1277">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="3f30e-1278">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1278">Switching between them has never been easier.</span></span> [<span data-ttu-id="3f30e-1279">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1279">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="3f30e-1280">**Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1280">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="3f30e-1281">Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1281">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="3f30e-1282">Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1282">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="3f30e-1283">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1283">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="3f30e-1284">Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1284">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="3f30e-1285">**Dê vida às suas planilhas:** insira gráficos animados em 3D para ver corações pulsando, planetas orbitando e a fúria do T-Rex na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1285">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="3f30e-1286">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1286">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="3f30e-p211">**Saiba mais sobre seus dados:** O novo botão Ideias procura padrões em seus dados e os usa para criar sugestões inteligentes e personalizadas. [Saiba mais](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p211">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="3f30e-1289">**A colaboração ficou mais fácil** : Os aperfeiçoamentos de coautoria significam que, ao trabalhar com acesso condicional, estilos de célula e muito mais, suas alterações são mescladas perfeitamente com as de seus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1289">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="3f30e-1290">**Una tabelas em colunas similares:** Obter e Transformar (Power Query) agora apresenta lógica de texto correspondente aproximado (também chamada de correspondência difusa) ao comparar colunas para mesclar tabelas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1290">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="3f30e-1291">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1291">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="3f30e-1292">**Codifique rapidamente com as melhorias do Power Query:** chegue rapidamente à conclusão de código com as cores de sintaxe e o preenchimento automático.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1292">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="3f30e-1293">Também descubra facilmente funções, colunas e parâmetros.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1293">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="3f30e-1294">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="3f30e-1295">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="3f30e-1296">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="3f30e-1297">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1297">Outlook</span></span>

- <span data-ttu-id="3f30e-1298">**Atualizamos a experiência de usuário do Outlook para você:** uma experiência simplificada, previamente disponível para visualização com Em Breve, projetada para ajudar você a se concentrar no que é mais importante.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1298">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="3f30e-1299">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1299">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="3f30e-1300">**Uma faixa de opções simplificada também personalizável:** desfrute de uma única linha simplificada com os botões usados com mais frequência.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1300">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="3f30e-1301">Alterne facilmente entre visualizações clássicas e simplificadas e comandos para fixar/desafixar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1301">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="3f30e-1302">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1302">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="3f30e-1303">**Continue trabalhando enquanto move mensagens:** Agora, o Outlook move mensagens em segundo plano para que você pode continuar trabalhando enquanto move uma grande quantidade de mensagens entre pastas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1303">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="3f30e-1304">**Crie intervalos entre reuniões consecutivas:** dê um tempo para os participantes descansarem ou se deslocarem entre os locais definindo o término antecipado das reuniões para entre cinco a dez minutos por padrão.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1304">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="3f30e-1305">**Escolha a sua ação favorita:** não use Sinalizar e Excluir?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1305">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="3f30e-1306">E quanto a Arquivar ou Marcar como Lida?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1306">How about Archive or Mark as Read?</span></span> <span data-ttu-id="3f30e-1307">Personalize o menu de ação rápida com os comandos que você mais usa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1307">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="3f30e-p218">**As pessoas verão o Meme que você usou:** se o texto ou as imagens estáticas não forem suficientes, use GIFs animados para convencer. [Saiba mais](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b).</span><span class="sxs-lookup"><span data-stu-id="3f30e-p218">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="3f30e-1310">**Uma maneira mais rápida de adicionar contas:** graças às melhorias de configuração de conta, ficou mais fácil adicionar contas do Outlook.com e do Gmail que usam a autenticação de dois fatores no Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1310">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="3f30e-1311">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1311">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="3f30e-1312">**Diga adeus aos limites de sincronização:** melhorias do Outlook acabou com o limite de pastas, então vá em frente e sincronize suas caixas de correio compartilhadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1312">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="3f30e-1313">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1313">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="3f30e-1314">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1314">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="3f30e-1315">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1315">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="3f30e-1316">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1316">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1317">**Melhoria na mudança de formas:** nomeie suas formas para ter mais controle sobre como elas são transformadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1317">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="3f30e-1318">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1318">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="3f30e-1319">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1319">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="3f30e-1320">Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1320">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="3f30e-1321">**Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1321">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="3f30e-1322">Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1322">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="3f30e-1323">Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1323">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="3f30e-1324">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1324">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="3f30e-1325">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1325">Switching between them has never been easier.</span></span> [<span data-ttu-id="3f30e-1326">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1326">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="3f30e-1327">**Os vídeos online têm um novo lar:** salve um vídeo no Microsoft Stream para que qualquer pessoa em sua organização possa vê-lo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1327">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="3f30e-1328">Insira o link de vídeo e desfrute de uma apresentação multimídia com uma fração do tamanho do arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1328">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="3f30e-1329">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1329">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="3f30e-1330">**Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1330">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="3f30e-p226">**Saiba a opinião de seu público através de um questionário ou pesquisa:** coloque um questionário ou uma pesquisa em um slide. O Office coleta e armazena as respostas para você. [Saiba mais](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p226">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="3f30e-p227">**Inserir um vídeo online está mais fácil do que nunca:** Deseja colocar um vídeo do Vimeo ou YouTube no slide? O link da página de vídeo é tudo o que você precisa. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p227">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="3f30e-1337">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1337">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="3f30e-1338">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1338">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="3f30e-1339">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1339">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="3f30e-1340">Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-1340">Project</span></span>

- <span data-ttu-id="3f30e-1341">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1341">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="3f30e-1342">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1342">Switching between them has never been easier.</span></span> [<span data-ttu-id="3f30e-1343">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1343">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="3f30e-1344">Visio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1344">Visio</span></span>

- <span data-ttu-id="3f30e-1345">**Exporte diagramas de processo para o Word:** Adicione automaticamente conteúdo de diagrama, como formas e metadados, a um documento do Word.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1345">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="3f30e-1346">Personalize o documento para criar as diretrizes de processo e os manuais de operação.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1346">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="3f30e-1347">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1347">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="3f30e-1348">**Captura dupla em fluxogramas de dados:** os novos e deslumbrantes layouts para os fluxogramas do Visualizador de Dados são limpos, nítidos e fáceis de entender.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1348">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="3f30e-1349">Clique na guia Design para ver as opções.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1349">Click the Design tab for options.</span></span>

- <span data-ttu-id="3f30e-1350">**Estênceis criados diretamente no Azure:** crie um aplicativo de nuvem ou planeje uma arquitetura usando dezenas de estênceis do Azure.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1350">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="3f30e-1351">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1351">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="3f30e-p233">**Diga adeus aos links desfeitos do Excel:** não consegue encontrar a pasta de trabalho do Excel vinculada ao seu diagrama do Visualizador de Dados? Vincule-o novamente para que tudo volte ao normal. [Saiba mais](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p233">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="3f30e-1355">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1355">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="3f30e-1356">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1356">Switching between them has never been easier.</span></span> [<span data-ttu-id="3f30e-1357">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1357">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="3f30e-1358">**Exporte elementos visuais do Visio a partir do Power BI:** os elementos visuais do Visio para o Power BI agora estão sendo exibidos corretamente ao exportar relatórios do Power BI como PDFs, arquivos do PowerPoint e muito mais.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1358">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="3f30e-1359">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1359">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="3f30e-1360">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1360">Word</span></span>

- <span data-ttu-id="3f30e-1361">**O modo Ferramentas de Aprendizagem tem suporte adicional para mais cores de página:** as Ferramentas de Aprendizagem no Word adicionam suporte para mais cores de tema de página, o que permite a alteração da cor da tela de fundo da página.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1361">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="3f30e-1362">Várias pessoas têm desafios de leitura com um plano de fundo todo branco ou preto, então ampliamos as opções de cores no Word para PC e para Mac.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1362">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="3f30e-p237">**A edição ocorre naturalmente com o Editor por Tinta:** com um único traçado, divida ou una palavras, adicione uma nova linha ou insira palavras usando uma caneta. [Saiba mais](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p237">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="3f30e-p238">**Transforme seu documento de estático para incrível:** transforme seu documento em uma página da web interativa e fácil de compartilhar, com uma aparência ótima em qualquer dispositivo. [Saiba mais](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p238">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="3f30e-1367">**Aumente o alcance do seu conteúdo:** precisa tornar seus documentos acessíveis?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1367">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="3f30e-1368">Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1368">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="3f30e-1369">Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1369">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="3f30e-1370">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1370">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="3f30e-1371">Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1371">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="3f30e-1372">**Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="3f30e-1373">Nunca foi tão fácil alternar entre elas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1373">Switching between them has never been easier.</span></span> [<span data-ttu-id="3f30e-1374">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="3f30e-p242">**Melhore a compreensão com Line Focus:** percorra a linha de um documento sem distrações. Ajuste o foco para colocar uma, três ou cinco linhas na visualização de cada vez. [Saiba mais](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="3f30e-p242">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="3f30e-1378">**Salve suas alterações assim que forem realizadas:** Carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1378">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="3f30e-1379">**Chame a atenção com \@@Menções:** Use @menções nos comentários para informar a seus colegas de trabalho quando precisar deles.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1379">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="3f30e-1380">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1380">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="3f30e-1381">**Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1381">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="3f30e-1382">Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1382">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="3f30e-1383">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1383">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="3f30e-1384">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1384">Office Suite</span></span>

- <span data-ttu-id="3f30e-1385">**Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente?</span><span class="sxs-lookup"><span data-stu-id="3f30e-1385">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="3f30e-1386">Basta digitar na caixa Pesquisar na guia Arquivo > Abrir para encontrar o arquivo que você está procurando.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1386">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="3f30e-1387">**Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1387">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="3f30e-1388">**Controles de privacidade:** controles novos, atualizados e melhorados para dados de diagnóstico e experiências conectadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1388">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="3f30e-1389">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1389">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="3f30e-1390">**Os produtos do Ofiice estão com um novo visual** Os ícones de produtos foram recriados para refletir as experiências simples, poderosas e inteligentes do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1390">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="3f30e-1391">**Instalação do Microsoft Teams:** o Microsoft Teams vem instalado por padrão nas instalações existentes do Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1391">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="3f30e-1392">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="3f30e-1392">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1395">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1395">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f30e-1396">Access</span><span class="sxs-lookup"><span data-stu-id="3f30e-1396">Access</span></span>

- <span data-ttu-id="3f30e-1397">Essa atualização corrige um problema em que agregados como Soma podem truncar o resultado para um valor inteiro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1397">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="3f30e-1398">Essa atualização corrige um problema em que uma consulta da União que inclui referências a tabelas remotas (por exemplo, tabelas do SQL Server) pode fazer o Access fechar e reiniciar.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1398">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="3f30e-1399">Esta atualização corrige um problema no Microsoft Access que pode causar o erro &quot;A consulta está corrompida&quot; quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada em SQL.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1399">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="3f30e-1400">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1400">Excel</span></span>

- <span data-ttu-id="3f30e-1401">A dica de tecla holandesa para o título do documento foi alterada para Alt-G.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1401">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="3f30e-1402">Correção de um problema no Excel em que as macros atribuídas a formas ou controles de formulário podem exibir mensagem de erro incorreta ou podem funcionar em intervalos de destino incorretos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1402">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="3f30e-1403">Resolvemos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1403">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="3f30e-1404">Isso corrige um problema em que é possível alterar a forma como uma Tabela Dinâmica é classificada e atualizá-la durante uma sessão de coautoria com outros usuários poderia causar uma falha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1404">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="3f30e-1405">Corrigido um problema onde o filtro de uma Tabela Dinâmica OLAP era definido como um valor que havia sido removido do cubo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1405">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="3f30e-1406">Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1406">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="3f30e-1407">Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1407">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="3f30e-1408">Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1408">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="3f30e-1409">Correção de um problema de conflito de mesclagem no Excel, que resultaria na reabertura de uma pasta de trabalho para os usuários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1409">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="3f30e-1410">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1410">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3f30e-1411">Resolvido um problema que causava um erro no tempo de execução da macro ao ativar janelas minimizadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1411">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="3f30e-1412">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1412">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3f30e-1413">Resolveu um problema que fazia com que as operações de recortar e colar próximas de uma tabela falhassem durante coautoria com outras pessoas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1413">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="3f30e-1414">Resolvemos um problema que causou interrupções na coautoria ao alterar propriedades personalizadas com a execução de macros.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1414">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="3f30e-1415">Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1415">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="3f30e-1416">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1416">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="3f30e-1417">Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1417">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="3f30e-1418">Melhorias significativas no desempenho da exclusão de colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1418">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="3f30e-1419">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1419">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="3f30e-1420">Resolvido um problema em que a função Proc poderia retornar um erro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1420">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="3f30e-1421">Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1421">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="3f30e-1422">Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1422">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="3f30e-1423">Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1423">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="3f30e-1424">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1424">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="3f30e-1425">Melhoramos significativamente o desempenho da filtragem por cor.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1425">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="3f30e-1426">Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1426">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="3f30e-1427">Habilitamos mais de 16 suplementos para serem exibidos ao navegar no gerenciador de suplementos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1427">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="3f30e-1428">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1428">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="3f30e-1429">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1429">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-1430">Esta atualização corrige um erro em que os documentos do Office podem falhar ao carregar no OneDrive for Business com a mensagem "Falha no Carregamento".</span><span class="sxs-lookup"><span data-stu-id="3f30e-1430">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="3f30e-1431">Corrigimos um problema no recurso Ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1431">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-1432">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1432">Outlook</span></span>

- <span data-ttu-id="3f30e-1433">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1433">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-1434">Correção de um problema em que os usuários que atualizavam a caixa de correio de uma autenticação básica para a moderna acabavam com a conta errada associada ao perfil do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1434">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="3f30e-1435">Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais quando não deveriam.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1435">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="3f30e-1436">Resolvido um problema que provocou falha na exibição de URLs de foco simples para alguns safelinks.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1436">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="3f30e-1437">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1437">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="3f30e-1438">Resolvido um problema que fazia com que um subconjunto de usuários POP3 visualizasse todos os seus e-mails formatados em texto sem formatação, independentemente das configurações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1438">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="3f30e-1439">Essa correção restaurará o modo de exibição das mensagens formatadas como HTML.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1439">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="3f30e-1440">Resolvido um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1440">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="3f30e-1441">Resolvido um problema que fazia com que os usuários não conseguissem acessar sugestões de localização por meio de um leitor de tela.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1441">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="3f30e-1442">Resolvido um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1442">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="3f30e-1443">Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1443">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="3f30e-1444">Resolvido um problema que fazia com que usuários vissem um aviso “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo de Regras.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1444">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="3f30e-1445">Resolvido um problema que faria com que os usuários experimentassem uma falha no Outlook ao interagir com determinados safelinks.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1445">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="3f30e-1446">Resolvido um problema que causava ambiguidade para os gerentes sobre se um representante já havia ou não respondido a uma determinada solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1446">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="3f30e-1447">Resolvido um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1447">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="3f30e-1448">Resolvido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1448">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="3f30e-1449">Essa alteração permite que os administradores habilitem uma política para preferir o email da conta fornecida nos prompts de autenticação da Descoberta Automática no UPN.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1449">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="3f30e-1450">Por padrão, a Descoberta Automática prefere o UPN da conta, quando disponível.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1450">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="3f30e-1451">Solucionamos um problema que fazia com que os usuários ver falhas de pesquisa em Grupos Modernos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1451">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="3f30e-1452">Resolvido um problema que fazia com que os usuários do Outlook travassem no estado "Senha Necessária" em determinados cenários.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1452">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="3f30e-1453">Resolvido um problema que fazia com que os usuários vissem sugestões de salas para reuniões que ocorriam fora do horário de disponibilidade dessa sala.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1453">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="3f30e-1454">Corrigido um problema que fazia com que os usuários encontrassem erros de "Não há suporte para algoritmo de criptografia" ao enviar um email criptografado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1454">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="3f30e-1455">Corrigido um problema para usuários não falantes de inglês, onde a linha de assunto em um e-mail seria incrivelmente pequena.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1455">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="3f30e-1456">Resolvido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1456">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="3f30e-1457">Resolvido um problema que fazia com que os usuários experimentassem uma falha ao tentar criar uma regra a partir de uma mensagem de “Conversa Perdida”.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1457">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="3f30e-1458">Corrigido um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1458">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="3f30e-1459">Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1459">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="3f30e-1460">Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1460">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="3f30e-1461">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1461">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="3f30e-1462">Corrigido um problema que fazia com que a pesquisa de pasta atual falhasse intermitentemente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1462">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="3f30e-1463">Corrigido um problema que fazia com que alguns usuários encontrassem erros de autenticação ao tentar recuperar as configurações de nuvem do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1463">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="3f30e-1464">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1464">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="3f30e-1465">Resolvido um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1465">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="3f30e-1466">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1466">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f30e-1467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1467">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1468">Correção de um problema em que alguns suplementos lançavam erros inesperados relacionados às formas nos gráficos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1468">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="3f30e-1469">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1469">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-1470">Essa alteração restaura o nome acessível para os controles de vídeo do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1470">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="3f30e-1471">Corrigimos um problema que poderia impedir a inicialização de algumas animações.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1471">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="3f30e-1472">Corrigimos um problema ao copiar um slide de uma apresentação para outra, criando mestres duplicados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1472">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="3f30e-1473">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada</span><span class="sxs-lookup"><span data-stu-id="3f30e-1473">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="3f30e-1474">Correção de confiabilidade: Corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1474">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="3f30e-1475">Corrigido um problema em que os caracteres katakana de meia largura não giravam corretamente nas caixas de texto verticais no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1475">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="3f30e-1476">Project</span><span class="sxs-lookup"><span data-stu-id="3f30e-1476">Project</span></span>

- <span data-ttu-id="3f30e-1477">Correção de um problema para que os usuários do Windows 7 possam abrir projetos do Project Web App e sites do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1477">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="3f30e-1478">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1478">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="3f30e-1479">O comando Nivelar Tudo não resolve adequadamente uma superalocação de recursos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1479">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="3f30e-1480">Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1480">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="3f30e-1481">Visio</span><span class="sxs-lookup"><span data-stu-id="3f30e-1481">Visio</span></span>

- <span data-ttu-id="3f30e-1482">A exportação como SVG do Visio falhou em várias formas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1482">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-1483">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1483">Word</span></span>

- <span data-ttu-id="3f30e-1484">Essa alteração levará a melhorias de desempenho na abertura de documentos usando o Word.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1484">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="3f30e-1485">Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1485">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="3f30e-1486">Corrigimos um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1486">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="3f30e-1487">Corrigimos um problema no controle de alterações que, às vezes, entravam em loop infinito.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1487">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="3f30e-1488">Corrigidos vários problemas em que o aplicativo pode travar no desligamento.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1488">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="3f30e-1489">E também corrige determinadas falhas relacionadas aos suplementos.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1489">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f30e-1490">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="3f30e-1490">Office Suite</span></span>

- <span data-ttu-id="3f30e-1491">Corrigido de um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1491">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="3f30e-1492">Corrigido um problema que fazia com que os usuários recebessem a mensagem "Algo está nos impedindo de compartilhar isso" ao tentar compartilhar arquivos armazenados no SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1492">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="3f30e-1493">Corrigido um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1493">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="3f30e-1494">Esta é uma correção para uma falha que os usuários podem encontrar ao abrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1494">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="3f30e-1495">Impede que os usuários do PowerPoint se deparem com erro ao tentar Apresentar Online.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1495">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="3f30e-1496">Em alguns casos, um arquivo do mecanismo de sincronização do SharePoint poderia exibir "Salvo", mas não ter salvado alterações, o que resulta em perda de dados.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1496">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="3f30e-1497">Resolvemos um problema em que os usuários poderiam não conseguir salvar documentos do Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1497">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="3f30e-1498">Esse problema afeta os usuários que criam um novo arquivo e escolhem a opção "caixa de diálogo Salvar como" depois de clicar no ícone Salvar ou pressionar Ctrl + S.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1498">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="3f30e-1499">Corrigido um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1499">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="3f30e-1500">Corrigido um bug em que as informações de acessibilidade não estavam sendo exibidas na laje Info Place dos bastidores.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1500">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="3f30e-1501">Melhora a confiabilidade do processo de atualização do Office referente à integridade do registro.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1501">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="3f30e-1502">Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1502">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="3f30e-1503">Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1503">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="3f30e-1504">Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1504">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="3f30e-1505">Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1505">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="3f30e-1506">Em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1506">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="3f30e-1507">Essa atualização melhora a confiabilidade ao publicar os atalhos do Office.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1507">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="3f30e-1508">Corrigimos um problema em que as atualizações poderiam ser bloqueadas inesperadamente em redes limitadas.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1508">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="3f30e-1509">Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1509">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="3f30e-1510">Maior confiabilidade ao baixar as atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1510">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="3f30e-1511">Corrigido problemas relacionados à propriedade AutoAjuste da Caixa de texto/ Forma em plug-ins de terceiros.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1511">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="3f30e-1512">Corrigimos um problema em que grandes modos de exibição em árvore poderiam resultar em falha.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1512">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="3f30e-1513">Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1513">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-january-14"></a><span data-ttu-id="3f30e-1515">Versão 1902: 14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-1515">Version 1902: January 14</span></span>
<span data-ttu-id="3f30e-1516">*Versão 1902 (Build 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1516">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="3f30e-1517">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="3f30e-1519">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="3f30e-1519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f30e-1520">Excel</span><span class="sxs-lookup"><span data-stu-id="3f30e-1520">Excel</span></span>

- <span data-ttu-id="3f30e-1521">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1521">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f30e-1522">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f30e-1522">Outlook</span></span>

- <span data-ttu-id="3f30e-1523">Corrigido um problema que fazia com que os usuários encontrassem erros de "algoritmo de criptografia não é suportado" ao enviar um email criptografado.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1523">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f30e-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f30e-1524">PowerPoint</span></span>

- <span data-ttu-id="3f30e-1525">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1525">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="3f30e-1526">Word</span><span class="sxs-lookup"><span data-stu-id="3f30e-1526">Word</span></span>

- <span data-ttu-id="3f30e-1527">Essa alteração levará a melhorias de desempenho na abertura de documentos usando o Word.</span><span class="sxs-lookup"><span data-stu-id="3f30e-1527">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-january-14"></a><span data-ttu-id="3f30e-1529">Versão 1808: 14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="3f30e-1529">Version 1808: January 14</span></span>
<span data-ttu-id="3f30e-1530">*Versão 1808 (Build 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="3f30e-1530">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="3f30e-1531">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f30e-1531">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="3f30e-1533">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="3f30e-1533">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|DC|Production| |16.0.12527.21416|version-2002-december-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

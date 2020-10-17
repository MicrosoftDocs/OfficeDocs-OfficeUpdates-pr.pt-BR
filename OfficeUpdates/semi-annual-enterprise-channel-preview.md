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
ms.openlocfilehash: 18637bac9ff51237a2afe97136febbd20cb46512
ms.sourcegitcommit: f906906efeaa6b3d35d324a70303ed4c79771552
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/14/2020
ms.locfileid: "48466109"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="838a4-103">Notas de versão para lançamentos do Canal Empresarial Semestral em 2020</span><span class="sxs-lookup"><span data-stu-id="838a4-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="838a4-104">Estas notas de versão fornecem informações dos novos recursos e atualizações não relacionadas à segurança que estão inclusas nas atualizações de 2020 do Canal Empresarial Semestral do Microsoft 365 Apps para Pequenos e Médios Negócios, Microsoft 365 Apps para Grandes Empresas e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.</span><span class="sxs-lookup"><span data-stu-id="838a4-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="838a4-105">Estamos fazendo algumas alterações nos canais de atualização para o Microsoft 365 Apps, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="838a4-106">Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="838a4-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-october-13"></a><span data-ttu-id="838a4-107">Versão 2008: 13 de outubro</span><span class="sxs-lookup"><span data-stu-id="838a4-107">Version 2008: October 13</span></span>
<span data-ttu-id="838a4-108">*Versão 2008 (Compilação 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="838a4-108">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="838a4-109">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-111">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-112">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-112">Excel</span></span>

- <span data-ttu-id="838a4-113">Correção de um bug com APIs PivotDateFilter no qual as condições de filtragem 'Antes' e 'Depois' eram invertidas.</span><span class="sxs-lookup"><span data-stu-id="838a4-113">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="838a4-114">Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="838a4-114">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="838a4-115">Correção de um problema em que o Excel pode falhar ao usar a Análise Rápida após congelar a linha superior da planilha.</span><span class="sxs-lookup"><span data-stu-id="838a4-115">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="838a4-116">Correção de um problema que pode causar um aviso sobre uma pasta de trabalho corrompida se contiver fórmulas usando SENÃODISP().</span><span class="sxs-lookup"><span data-stu-id="838a4-116">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="838a4-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-117">Outlook</span></span>

- <span data-ttu-id="838a4-118">Corrige um problema que fez com que os usuários não conseguissem fechar os calendários compartilhados, clicando no "X" no canto.</span><span class="sxs-lookup"><span data-stu-id="838a4-118">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="838a4-119">Corrige um problema que fazia com que a configuração "Habilitar melhorias no calendário compartilhado", às vezes, falhasse ao ser aplicada a calendários compartilhados existentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-119">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="838a4-120">Corrige um problema que fazia com que os usuários vissem um erro na página de links seguros, em vez de no documento que tentavam abrir, ao abrir um anexo na nuvem.</span><span class="sxs-lookup"><span data-stu-id="838a4-120">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="838a4-121">Corrige um problema de desempenho com o carregamento de anexos.</span><span class="sxs-lookup"><span data-stu-id="838a4-121">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="838a4-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-122">PowerPoint</span></span>

- <span data-ttu-id="838a4-123">Essa alteração corrige um problema com o recurso Exportar para GIF Animado em que clicar no botão Exportar não exportava.</span><span class="sxs-lookup"><span data-stu-id="838a4-123">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="838a4-124">Correção de segurança para solucionar um problema que desativou a proteção de IRM ao abrir um arquivo do PowerPoint no Modo de Exibição Protegido.</span><span class="sxs-lookup"><span data-stu-id="838a4-124">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="838a4-125">Resolvemos um problema no diálogo de Configurações de Ação que estava causando uma falha no aplicativo PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-125">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="838a4-126">Visio</span><span class="sxs-lookup"><span data-stu-id="838a4-126">Visio</span></span>

- <span data-ttu-id="838a4-127">Resolvemos um problema que fez com que a visualização ao vivo falhasse no alinhamento do texto.</span><span class="sxs-lookup"><span data-stu-id="838a4-127">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="838a4-128">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-128">Word</span></span>

- <span data-ttu-id="838a4-129">Resolvemos um problema que fazia com que os usuários experimentassem um travamento ao abrir certos emails muito grandes.</span><span class="sxs-lookup"><span data-stu-id="838a4-129">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="838a4-130">Corrigimos um problema em que o usuário pode experimentar uma falha ao abrir um documento.</span><span class="sxs-lookup"><span data-stu-id="838a4-130">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="838a4-131">Resolveu um problema que pode ter causado uma falha durante a inicialização do Word.</span><span class="sxs-lookup"><span data-stu-id="838a4-131">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="838a4-132">Corrigimos um problema com a caixa de diálogo Galeria de Estilos.</span><span class="sxs-lookup"><span data-stu-id="838a4-132">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="838a4-133">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-133">Office Suite</span></span>

- <span data-ttu-id="838a4-134">Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners.</span><span class="sxs-lookup"><span data-stu-id="838a4-134">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="838a4-135">Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".</span><span class="sxs-lookup"><span data-stu-id="838a4-135">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="838a4-136">Corrige o alto uso de CPUs em ociosidade com GIF/modelo em 3D animado</span><span class="sxs-lookup"><span data-stu-id="838a4-136">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="838a4-137">Essa alteração corrige uma falha ao iniciar os aplicativos do Office devido à falha no carregamento de d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="838a4-137">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-september-08"></a><span data-ttu-id="838a4-139">Versão 2008: 8 de setembro</span><span class="sxs-lookup"><span data-stu-id="838a4-139">Version 2008: September 08</span></span>
<span data-ttu-id="838a4-140">*Versão 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="838a4-140">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="838a4-141">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-141">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="838a4-143">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="838a4-143">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="838a4-144">Access</span><span class="sxs-lookup"><span data-stu-id="838a4-144">Access</span></span>

- <span data-ttu-id="838a4-145">**Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la.</span><span class="sxs-lookup"><span data-stu-id="838a4-145">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="838a4-146">Pesquise e substitua o texto no SQL View.</span><span class="sxs-lookup"><span data-stu-id="838a4-146">Search and replace text in SQL View.</span></span> <span data-ttu-id="838a4-147">Selecione várias tabelas na janela Relações.</span><span class="sxs-lookup"><span data-stu-id="838a4-147">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="838a4-148">**Adicionar tabelas com menos cliques:** usar o painel de tarefas Adicionar Tabelas, que permanece aberto enquanto você trabalha, para adicionar tabelas a relações e consultas.</span><span class="sxs-lookup"><span data-stu-id="838a4-148">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="838a4-149">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-149">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="838a4-150">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-150">Excel</span></span>

- <span data-ttu-id="838a4-151">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="838a4-151">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="838a4-152">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-152">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="838a4-153">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-153">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="838a4-154">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="838a4-154">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="838a4-155">**Crie Tabelas Dinâmicas a partir de conjuntos de dados no Power BI no Excel:** Você pode criar tabelas dinâmicas no Excel que estão conectadas a conjuntos de dados armazenados no Power BI com alguns cliques.</span><span class="sxs-lookup"><span data-stu-id="838a4-155">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="838a4-156"> Isso permite que você obtenha o melhor das Tabelas Dinâmicas e do Power BI.</span><span class="sxs-lookup"><span data-stu-id="838a4-156"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="838a4-157">Calcule, resuma e analise seus dados com Tabelas Dinâmicas a partir dos conjuntos de dados seguros do Power BI.</span><span class="sxs-lookup"><span data-stu-id="838a4-157">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="838a4-158">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-158">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="838a4-159">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="838a4-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="838a4-160">**Suas funções favoritas do Excel acabaram de ficar mais rápidas:** As funções SOMASES, MÉDIASES, CONT.SES, MÁXIMOSES e MÍNIMOSES estão muito mais rápidas do que nunca.</span><span class="sxs-lookup"><span data-stu-id="838a4-160">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="838a4-161">Chegue ao resultado final mais rapidamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-161">Get to the bottom line more quickly.</span></span> <span data-ttu-id="838a4-162">Experimente agora.</span><span class="sxs-lookup"><span data-stu-id="838a4-162">Try one now.</span></span>

- <span data-ttu-id="838a4-163">**Aprimoramentos no Realtimedata (RTD):** No Office 365 canal mensal versão 2002 ou posterior, a função do Excel (RealTimeData) é muito mais rápida ao calcular os dados na planilha do que o Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="838a4-163">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="838a4-164">Removemos os gargalos na sua memória e estruturas de dados subjacentes, bem como o tornamos thread-safe para permitir o seu cálculo em todas as threads disponíveis de recálculo multithreaded (MTR).</span><span class="sxs-lookup"><span data-stu-id="838a4-164">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-165">Outlook</span></span>

- <span data-ttu-id="838a4-166">**As tualizações de calendário compartilhadas ficaram mais rápidas**: No caso de calendários compartilhados no Office 365, o Outlook pode atualizá-los usando a API REST.</span><span class="sxs-lookup"><span data-stu-id="838a4-166">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="838a4-167">Ative a visualização para atualizações mais rápidas e confiáveis de calendários compartilhados.</span><span class="sxs-lookup"><span data-stu-id="838a4-167">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="838a4-168">**Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca.</span><span class="sxs-lookup"><span data-stu-id="838a4-168">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="838a4-169">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-169">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="838a4-170">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-170">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="838a4-171">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="838a4-171">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="838a4-172">**Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="838a4-172">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="838a4-173">As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.</span><span class="sxs-lookup"><span data-stu-id="838a4-173">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="838a4-174">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="838a4-174">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="838a4-175">**O calendário recebe um novo formato:** ver atualizações visuais que facilitam a pesquisa do calendário.</span><span class="sxs-lookup"><span data-stu-id="838a4-175">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="838a4-176">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-176">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="838a4-177">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="838a4-177">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="838a4-178">**Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online.</span><span class="sxs-lookup"><span data-stu-id="838a4-178">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="838a4-179">Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.</span><span class="sxs-lookup"><span data-stu-id="838a4-179">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="838a4-180">**Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar?</span><span class="sxs-lookup"><span data-stu-id="838a4-180">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="838a4-181">O Outlook agora detecta isso e ajuda você a se conectar.</span><span class="sxs-lookup"><span data-stu-id="838a4-181">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="838a4-182">Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="838a4-182">See details in [blog post](https://insider.office.com/pt-BR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="838a4-183">**Obter sugestões de email ao procurar por alguém:** Quando você digitar o nome de uma pessoa na Caixa de pesquisa, os emails mais relevantes serão incluídos nas sugestões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="838a4-183">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="838a4-184">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-184">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="838a4-185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-185">PowerPoint</span></span>

- <span data-ttu-id="838a4-186">**Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles.</span><span class="sxs-lookup"><span data-stu-id="838a4-186">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="838a4-187">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-187">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="838a4-188">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="838a4-188">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="838a4-189">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-189">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="838a4-190">**GIFs em instantes:** Um slide, um quadro.</span><span class="sxs-lookup"><span data-stu-id="838a4-190">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="838a4-191">Crie facilmente GIFs de loop no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-191">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="838a4-192">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-192">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="838a4-193">Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="838a4-193">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="838a4-194">**Diagramas melhores:** Com conectores melhores e um processo de conversão de tinta mais suave, você pode usar a tinta em suas ideias de forma mais confiante.</span><span class="sxs-lookup"><span data-stu-id="838a4-194">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="838a4-195">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-195">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="838a4-196">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-196">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="838a4-197">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="838a4-197">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="838a4-198">**Comentários:** a nova experiência de comentários no PowerPoint permite que você descubra e adicione comentários de maneira rápida e fácil aos seus documentos.</span><span class="sxs-lookup"><span data-stu-id="838a4-198">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="838a4-199">Modernize seus fluxos de trabalho de colaboração com novos recursos, como ancoragem de comentários, resolução, tarefas, notificações de menção aprimorada e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-199">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="838a4-200">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-200">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="838a4-201">**Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="838a4-201">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="838a4-202">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-202">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="838a4-203">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="838a4-203">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="838a4-204">**Vincular ao Slide:** Peça a um colega para contribuir com o conjunto de slides e inicie-o diretamente no slide para o qual você precisa de ajuda.</span><span class="sxs-lookup"><span data-stu-id="838a4-204">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="838a4-205">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-205">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="838a4-206">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="838a4-206">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="838a4-207">**Melhor desempenho de streaming de vídeo no PowerPoint:** fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável.</span><span class="sxs-lookup"><span data-stu-id="838a4-207">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="838a4-208">Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.</span><span class="sxs-lookup"><span data-stu-id="838a4-208">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="838a4-209">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-209">Word</span></span>

- <span data-ttu-id="838a4-210">**Gráficos de mapa aprimorados:** Melhoramos os gráficos de mapa, integrando-os com os Tipos de Dados Geográficos do Excel, que podem revelar informações detalhadas sobre seus locais mapeados.</span><span class="sxs-lookup"><span data-stu-id="838a4-210">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="838a4-211">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-211">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="838a4-212">**Laço a tinta:** a ferramenta laço na guia desenhar ajuda a selecionar objetos desenhados à tinta.</span><span class="sxs-lookup"><span data-stu-id="838a4-212">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="838a4-213">Selecione traços individuais ou palavras inteiras.</span><span class="sxs-lookup"><span data-stu-id="838a4-213">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="838a4-214">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-214">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="838a4-215">**Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-215">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="838a4-216">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="838a4-216">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="838a4-217">**Confirmação de ação nos leitores de tela:** Confirmação de ação é um requisito de acessibilidade importante.</span><span class="sxs-lookup"><span data-stu-id="838a4-217">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="838a4-218">Com a introdução de uma nova API de Notificação do Windows, agora vamos alertar os usuários do leitor de tela sobre o sucesso de suas ações.</span><span class="sxs-lookup"><span data-stu-id="838a4-218">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="838a4-219">Recortar, copiar, colar, negrito, itálico, sublinhado, desfazer, refazer, correções automáticas e todas as maiúsculas agora são anunciadas para os usuários do Narrador no Word Win32.</span><span class="sxs-lookup"><span data-stu-id="838a4-219">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="838a4-220">Para habilitar esse recurso, ative o Narrador pressionando a tecla windows + ctrl + enter.</span><span class="sxs-lookup"><span data-stu-id="838a4-220">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="838a4-221">Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="838a4-221">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-222">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-222">Office Suite</span></span>

- <span data-ttu-id="838a4-223">**Rótulos de confidencialidade:** agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.</span><span class="sxs-lookup"><span data-stu-id="838a4-223">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-226">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-226">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="838a4-227">Acesso</span><span class="sxs-lookup"><span data-stu-id="838a4-227">Access</span></span>

- <span data-ttu-id="838a4-228">Resolveu um problema com a inserção de tabelas SQL vinculadas que incluem um campo identidade (por exemplo, numeração automática).</span><span class="sxs-lookup"><span data-stu-id="838a4-228">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="838a4-229">Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. </span><span class="sxs-lookup"><span data-stu-id="838a4-229">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="838a4-230">Corrige um problema para possibilitar o uso do tipo de dados de Data/Hora Estendida em seu código sem o aplicativo falhar.</span><span class="sxs-lookup"><span data-stu-id="838a4-230">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="838a4-231">Corrige um problema para poder reverter para a versão mais atualizada do Access e usar o DAO/VBA para gerenciar e editar um tipo de dados decimais.</span><span class="sxs-lookup"><span data-stu-id="838a4-231">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="838a4-232">Esta correção resolve o problema em que a tentativa de executar determinadas consultas tenha previamente produzido a mensagem de erro 'Consulta é muito complexa'.</span><span class="sxs-lookup"><span data-stu-id="838a4-232">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="838a4-233">O Access resolveu esse problema atual, mas estaremos analisando nossas interfaces adicionais para garantir que esse problema não persista.</span><span class="sxs-lookup"><span data-stu-id="838a4-233">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="838a4-234">A equipe vai informá-lo sobre atualizações futuras. Agradecemos sua paciência.</span><span class="sxs-lookup"><span data-stu-id="838a4-234">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="838a4-235">Este problema foi resolvido - agora você pode usar nosso driver ODBC fora das aplicações de Clicar para Executar do Office.</span><span class="sxs-lookup"><span data-stu-id="838a4-235">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="838a4-236">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-236">Excel</span></span>

- <span data-ttu-id="838a4-237">A classificação automática de documentos pode ter ocorrido para as pastas de trabalho que estavam e modo somente leitura.</span><span class="sxs-lookup"><span data-stu-id="838a4-237">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="838a4-238">Correção de uma falha que poderia ocorrer quando você tentasse criar uma conexão de dados se tivesse saído da sua conta.</span><span class="sxs-lookup"><span data-stu-id="838a4-238">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="838a4-239">Solucionamos um problema em que o Excel poderia falhar ao tentar inserir Tabelas Dinâmicas em uma planilha de gráfico.</span><span class="sxs-lookup"><span data-stu-id="838a4-239">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="838a4-240">Poderia ocorrer um erro ao tentar salvar um arquivo que continha uma fórmula usando a função LET ().</span><span class="sxs-lookup"><span data-stu-id="838a4-240">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="838a4-241">Correção de um problema em que o Excel poderia falhar em determinadas circunstâncias ao usar o Pincel de Formatação.</span><span class="sxs-lookup"><span data-stu-id="838a4-241">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="838a4-242">Correção de um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="838a4-242">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="838a4-243">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="838a4-243">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="838a4-244">Corrigimos um problema que, em alguns casos, clicar em um hiperlink para um local na mesma pasta de trabalho fará com que a pasta de trabalho seja ocultada.</span><span class="sxs-lookup"><span data-stu-id="838a4-244">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="838a4-245">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="838a4-245">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="838a4-246">O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="838a4-246">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="838a4-247">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="838a4-247">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="838a4-248">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma tabela dinâmica.</span><span class="sxs-lookup"><span data-stu-id="838a4-248">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="838a4-249">Isso aborda um problema em que as conexões criadas pelo provedor de dados SQL nas versões anteriores do Office definem as propriedades da tabela interna de modo diferente do Office 365.</span><span class="sxs-lookup"><span data-stu-id="838a4-249">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="838a4-250">Isso fazia com que a lista suspensa da visualização de tabela / editor de consulta fosse desabilitada para arquivos com conexões criadas em versões mais antigas do Office quando elas fossem abertas usando o Office 365.</span><span class="sxs-lookup"><span data-stu-id="838a4-250">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="838a4-251">Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="838a4-251">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="838a4-252">Resolvemos um problema em que a escrita à tinta poderia fazer com que o Excel não respondesse.</span><span class="sxs-lookup"><span data-stu-id="838a4-252">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="838a4-253">OneNote</span><span class="sxs-lookup"><span data-stu-id="838a4-253">OneNote</span></span>

- <span data-ttu-id="838a4-254">Informa os usuários, por meio da barra de informações, sobre ajustes temporários no Microsoft OneNote que ajudarão a melhorar a sincronização e o serviço durante o uso intenso pelo mundo inteiro.</span><span class="sxs-lookup"><span data-stu-id="838a4-254">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="838a4-255">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-255">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="838a4-256">Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.</span><span class="sxs-lookup"><span data-stu-id="838a4-256">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="838a4-257">Melhoria da sincronização e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-257">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="838a4-258">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="838a4-258">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="838a4-259">Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-259">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="838a4-260">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="838a4-260">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="838a4-261">Melhoria na sincronização e estabilidade do serviço, alterando temporariamente a frequência com que os históricos de versão de página são criados.</span><span class="sxs-lookup"><span data-stu-id="838a4-261">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="838a4-262">Melhoria na sincronização e estabilidade do servidor ao desabilitar, temporariamente, a transferências de páginas para a lixeira.</span><span class="sxs-lookup"><span data-stu-id="838a4-262">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="838a4-263">Os usuários que desejam excluir uma página, em vez disso, receberão uma caixa de diálogo perguntando se gostariam de excluir permanentemente a página.</span><span class="sxs-lookup"><span data-stu-id="838a4-263">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-264">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-264">Outlook</span></span>

- <span data-ttu-id="838a4-265">Corrige um problema que provocou os usuários que tentaram criar uma solicitação de reunião de uma conta secundária adicionada ao perfil, a não verem um campo em branco De: em vez de seus endereços de email.</span><span class="sxs-lookup"><span data-stu-id="838a4-265">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="838a4-266">Corrige um problema que fazia com que os usuários não conseguissem se conectar à pastas públicas após adicionar uma caixa de correio compartilhada.</span><span class="sxs-lookup"><span data-stu-id="838a4-266">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="838a4-267">Resolveu um problema que fazia com que as reuniões não fossem retiradas do calendário de um gerente, quando recusadas por um representante em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="838a4-267">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="838a4-268">Resolveu um problema que impedia alguns usuários do recurso de Melhorias do Calendário Compartilhado de poderem visualizar um calendário compartilhado recém-adicionado.</span><span class="sxs-lookup"><span data-stu-id="838a4-268">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="838a4-269">Corrige um problema que causava falhas ocasionais quando os usuários interagiam com anexos na nuvem.</span><span class="sxs-lookup"><span data-stu-id="838a4-269">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="838a4-270">Solucionamos um problema que fazia com que os usuários do CLP experimentassem uma falha ao mudar o endereço de um contexto de um contexto protegido para um não protegido.</span><span class="sxs-lookup"><span data-stu-id="838a4-270">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="838a4-271">Solucionamos um problema em que o Outlook falhava ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="838a4-271">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="838a4-272">Corrige um problema com o evento de auditoria CLP para o rótulo responder/encaminhar.</span><span class="sxs-lookup"><span data-stu-id="838a4-272">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="838a4-273">Solucionamos um problema que provocava a alteração inesperada da largura do painel de pasta.</span><span class="sxs-lookup"><span data-stu-id="838a4-273">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="838a4-274">Aborda um problema que fazia com que os usuários vissem a data de criação de anexos que haviam copiado para seu sistema de arquivos por meio de arrastar e colar sendo definida como 1 de janeiro de 4501.</span><span class="sxs-lookup"><span data-stu-id="838a4-274">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="838a4-275">Tratamos de um problema que fazia com que os usuários de alguns conjuntos de caracteres vissem os nomes de arquivos exibidos incorretamente ao adicionar um Smart Link a um arquivo do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-275">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="838a4-276">Soluciona um problema que exibia a mensagem “As regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="838a4-276">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="838a4-277">Resolvido um problema que fazia com que o Outlook não recuperasse as sugestões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="838a4-277">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="838a4-278">Corrige um problema que causava falhas no calendário em aperfeiçoamentos do Calendário Compartilhado.</span><span class="sxs-lookup"><span data-stu-id="838a4-278">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="838a4-279">Soluciona um problema que causava falhas e travas intermitentes em algumas situações.</span><span class="sxs-lookup"><span data-stu-id="838a4-279">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="838a4-280">Tratamos de um problema que fazia com que os usuários experimentassem uma falha ao excluir 4 ou mais emails de uma conta POP com a opção "Baixar Apenas Cabeçalhos" selecionada.</span><span class="sxs-lookup"><span data-stu-id="838a4-280">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="838a4-281">Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.</span><span class="sxs-lookup"><span data-stu-id="838a4-281">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="838a4-282">Solucionado um problema que fazia com que representantes recebessem uma mensagem de erro ao editar um compromisso no calendário existente em um calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="838a4-282">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="838a4-283">Solucionamos um problema que fazia com que os usuários experimentassem falhas em aplicativos MAPI de terceiros.</span><span class="sxs-lookup"><span data-stu-id="838a4-283">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="838a4-284">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="838a4-284">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="838a4-285">Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.</span><span class="sxs-lookup"><span data-stu-id="838a4-285">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="838a4-286">Corrige um problema que fazia com que os usuários do servidor do Windows 10 vissem o aviso “Status do antivírus: Inválido.</span><span class="sxs-lookup"><span data-stu-id="838a4-286">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="838a4-287">Essa versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus foi encontrado” mesmo após a instalação correta do antivírus.</span><span class="sxs-lookup"><span data-stu-id="838a4-287">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="838a4-288">Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="838a4-288">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="838a4-289">Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.</span><span class="sxs-lookup"><span data-stu-id="838a4-289">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="838a4-290">Corrige um problema que fazia com que o Outlook solicitasse continuamente para os usuários executarem a Ferramenta Reparo da Caixa de Entrada.</span><span class="sxs-lookup"><span data-stu-id="838a4-290">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="838a4-291">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="838a4-291">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="838a4-292">Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="838a4-292">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="838a4-293">Solucionamos um problema que provocou falha na exibição da página do assistente de agendamento.</span><span class="sxs-lookup"><span data-stu-id="838a4-293">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="838a4-294">Resolvido um problema que provocava falha na exibição da página do Assistente de Agendamento.</span><span class="sxs-lookup"><span data-stu-id="838a4-294">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="838a4-295">Resolvido um problema que causava um ocasional travamento para os usuários ao recuperar informações pessoais.</span><span class="sxs-lookup"><span data-stu-id="838a4-295">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="838a4-296">Corrige um problema que causava falhas ocasionais quando os usuários editavam destinatários.</span><span class="sxs-lookup"><span data-stu-id="838a4-296">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="838a4-297">Corrige um problema que causava os usuários de ver anormalidades ao usar o modo de exibição compacto.</span><span class="sxs-lookup"><span data-stu-id="838a4-297">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="838a4-298">Solucionamos um problema que fazia com que os usuários do Outlook vissem problemas com a navegação no modo de exibição compacto.</span><span class="sxs-lookup"><span data-stu-id="838a4-298">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="838a4-299">Resolveu de um problema que fazia com que o menu de contexto do botão direito do mouse não fosse exibido nos controles de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="838a4-299">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="838a4-300">Aborda um problema que fez com que os usuários recebessem o seguinte erro ao responder ou a redigir um novo email: “Alguns arquivos desta página da Web não estão no local esperado.</span><span class="sxs-lookup"><span data-stu-id="838a4-300">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="838a4-301">Deseja baixá-los mesmo assim?</span><span class="sxs-lookup"><span data-stu-id="838a4-301">Do you want to download them anyway?</span></span> <span data-ttu-id="838a4-302">Se tiver certeza de que a página da Web é de uma fonte confiável, clique em Sim.”</span><span class="sxs-lookup"><span data-stu-id="838a4-302">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="838a4-303">Corrige um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.</span><span class="sxs-lookup"><span data-stu-id="838a4-303">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="838a4-304">Solucionamos um problema que fazia com que a pesquisa de um recurso sugerir um recurso não retornou nenhum resultado e deixe o usuário sem a opção de enviar uma nova ideia de recurso.</span><span class="sxs-lookup"><span data-stu-id="838a4-304">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="838a4-305">Corrige um problema que causava problemas de formatação em alertas de notificação de incidente.</span><span class="sxs-lookup"><span data-stu-id="838a4-305">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="838a4-306">Corrige um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma Notificação de Administrador.</span><span class="sxs-lookup"><span data-stu-id="838a4-306">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="838a4-307">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="838a4-307">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="838a4-308">Corrige um problema que causava falhas ocasionais quando os usuários editavam destinatários.</span><span class="sxs-lookup"><span data-stu-id="838a4-308">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="838a4-309">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="838a4-309">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="838a4-310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-310">PowerPoint</span></span>

- <span data-ttu-id="838a4-311">Isso corrige uma falha quando os usuários têm comentários modernos e antigos em um arquivo, disparando uma atualização nos comentários.</span><span class="sxs-lookup"><span data-stu-id="838a4-311">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="838a4-312">Solucionamos um problema de falha no aplicativo PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-312">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="838a4-313">Solucionamos um problema de falha com o painel de sugestões.</span><span class="sxs-lookup"><span data-stu-id="838a4-313">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="838a4-314">Project</span><span class="sxs-lookup"><span data-stu-id="838a4-314">Project</span></span>

- <span data-ttu-id="838a4-315">Corrige um problema de quando os dados do predecessor/sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.</span><span class="sxs-lookup"><span data-stu-id="838a4-315">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="838a4-316">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="838a4-316">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="838a4-317">Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><span class="sxs-lookup"><span data-stu-id="838a4-317">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="838a4-318">Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.</span><span class="sxs-lookup"><span data-stu-id="838a4-318">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="838a4-319">Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="838a4-319">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="838a4-320">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-320">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="838a4-321">Solucionamos um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="838a4-321">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="838a4-322">Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.</span><span class="sxs-lookup"><span data-stu-id="838a4-322">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="838a4-323">Corrige um problema no qual não era possível abrir projetos no cliente da área de trabalho do Project a partir do aplicativo web do Project caso a URL terminasse em .com.</span><span class="sxs-lookup"><span data-stu-id="838a4-323">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="838a4-324">Corrigimos um problema no qual, se você colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-324">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="838a4-325">Corrigimos um problema no qual não era possível salvar um PDF/XPS do Project em uma biblioteca de documentos no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-325">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="838a4-326">Correção de um problema em que uma tarefa marcada como 100% concluída mudava incorretamente para menos do que 100% concluída.</span><span class="sxs-lookup"><span data-stu-id="838a4-326">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="838a4-327">Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa resumo do projeto, o campo início/tarefa do projeto.</span><span class="sxs-lookup"><span data-stu-id="838a4-327">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="838a4-328">Corrige um problema em que, se um recurso tivesse mais de uma tabela de taxas de custo definida, os custos restantes nem sempre eram calculados corretamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-328">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="838a4-329">Corrige um problema em que a data de término do projeto não está sendo atualizada para os projetos conectados à lista de tarefas do SharePoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-329">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="838a4-330">Corrigimos um problema no qual a tarefa selecionada na caixa de diálogo para atribuir recursos não era a mesma que a tarefa selecionada no modo de exibição do quadro de tarefas.</span><span class="sxs-lookup"><span data-stu-id="838a4-330">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="838a4-331">Corrigige um problema onde um projeto que estava em um estado ruim não podia ser aberto.</span><span class="sxs-lookup"><span data-stu-id="838a4-331">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="838a4-332">Skype</span><span class="sxs-lookup"><span data-stu-id="838a4-332">Skype</span></span>

- <span data-ttu-id="838a4-333">Quando um usuário recebe uma política que os move para o modo Teams Only, ele ainda poderá usar o suplemento do Outlook do Skype for Business para agendar reuniões.</span><span class="sxs-lookup"><span data-stu-id="838a4-333">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="838a4-334">Após essa atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente ler a política, indicando que o usuário está no modo Teams Only, e entrar no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="838a4-334">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="838a4-335">Além disso, o suplemento Skype for Business no Outlook não será ativado durante a inicialização, caso veja que o cliente do Skype for Business está no modo somente ingresso na reunião.</span><span class="sxs-lookup"><span data-stu-id="838a4-335">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="838a4-336">Alterou o tom de pele do emoticon que dança para uma cor neutra.</span><span class="sxs-lookup"><span data-stu-id="838a4-336">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-337">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-337">Word</span></span>

- <span data-ttu-id="838a4-338">Resolvido um problema ao abrir documentos do Word a partir de uma entrega de documento personalizada (aspx) quando a URL contém um componente de consulta.</span><span class="sxs-lookup"><span data-stu-id="838a4-338">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="838a4-339">Essa alteração corrige um problema em que os aplicativos do Office poderiam ficar presos em um estado de falha silencioso de salvamento após uma sessão anterior de coautoria.</span><span class="sxs-lookup"><span data-stu-id="838a4-339">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="838a4-340">Soluciona um problema que fazia com que os usuários experimentassem uma falha ao responder ou redigir um novo email.</span><span class="sxs-lookup"><span data-stu-id="838a4-340">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="838a4-341">Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.</span><span class="sxs-lookup"><span data-stu-id="838a4-341">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="838a4-342">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="838a4-342">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="838a4-343">Resolvemos um problema em que o usuário poderia perder conteúdo ao redimensionar uma forma.</span><span class="sxs-lookup"><span data-stu-id="838a4-343">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="838a4-344">Consertamos um problema em que os estilos básicos não eram atualizados com o estilo normal.</span><span class="sxs-lookup"><span data-stu-id="838a4-344">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="838a4-345">Resolvemos um problema em que a macro AutoOpen era executada antes do AutoExec.</span><span class="sxs-lookup"><span data-stu-id="838a4-345">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="838a4-346">Corrige um problema ao copiar e colar uma imagem SVG.</span><span class="sxs-lookup"><span data-stu-id="838a4-346">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="838a4-347">Soluciona um problema que pode ter causado uma falha ao arrastar conteúdo do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="838a4-347">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="838a4-348">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-348">Office Suite</span></span>

- <span data-ttu-id="838a4-349">Para o antigo painel de Compartilhamento não baseado na Web, ao fechar o documento enquanto o painel de Compartilhamento abria, isso poderia causar uma falha.</span><span class="sxs-lookup"><span data-stu-id="838a4-349">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="838a4-350">Isto agora está corrigido.</span><span class="sxs-lookup"><span data-stu-id="838a4-350">This is now fixed.</span></span>

- <span data-ttu-id="838a4-351">Corrige um problema de tempo que poderia causar uma falha ao fechar arquivos do Office</span><span class="sxs-lookup"><span data-stu-id="838a4-351">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="838a4-352">Resolvemos o problema de taxa de falha do ValidateInstall configurando a validação de instalação do Bing Addon como verdadeira por padrão e considerando o sucesso do retorno MSI como um sucesso na instalação.</span><span class="sxs-lookup"><span data-stu-id="838a4-352">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="838a4-353">Portamos uma nova AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="838a4-353">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="838a4-354">Corrige um problema com Clique para Executar, que resultava na falha de atualização durante a tentativa de vincular links simbólicos.</span><span class="sxs-lookup"><span data-stu-id="838a4-354">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="838a4-355">Corrigido um problema que provocou uma mensagem do tempo de execução, mesmo que foi demonstrado que a transição para o produto completo tenha sido concluída.</span><span class="sxs-lookup"><span data-stu-id="838a4-355">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="838a4-356">A correção para esse problema foi garantir que o serviço computasse corretamente os produtos adicionados.</span><span class="sxs-lookup"><span data-stu-id="838a4-356">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="838a4-357">Filtramos os produtos recém-adicionados (garantindo que também estejam presentes na nova configuração) e os adicionamos no final das IDs de lançamento dos produtos existentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-357">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="838a4-358">Solucionamos um problema em que os usuários estavam vendo os elementos da interface do usuário ou o conteúdo que não estava sendo exibido em determinadas condições, em particular, no Modo de Exibição do Apresentador ou no uso de vários monitores.</span><span class="sxs-lookup"><span data-stu-id="838a4-358">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="838a4-359">Essa alteração soluciona as possíveis travas ao carregar e reproduzir conteúdo animado, como GIFs ou modelos 3D.</span><span class="sxs-lookup"><span data-stu-id="838a4-359">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="838a4-360">Essa alteração corrige um problema com a caixa de diálogos Compactar imagem que não mantém determinadas configurações do usuário.</span><span class="sxs-lookup"><span data-stu-id="838a4-360">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="838a4-361">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="838a4-361">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="838a4-362">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="838a4-362">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="838a4-363">Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-363">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="838a4-364">Corrige um problema de falha com o host do Office no Windows quando um suplemento é ativado enquanto o valor TabProcGrowth do registro é tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="838a4-364">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="838a4-365">O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero.</span><span class="sxs-lookup"><span data-stu-id="838a4-365">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="838a4-366">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="838a4-366">This change would fix this issue.</span></span>



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2002-august-11"></a><span data-ttu-id="838a4-368">Versão 2002: 11 de agosto</span><span class="sxs-lookup"><span data-stu-id="838a4-368">Version 2002: August 11</span></span>
<span data-ttu-id="838a4-369">*Versão 2002 (Compilação 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="838a4-369">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="838a4-370">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-370">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-372">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-372">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-373">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-373">Excel</span></span>

- <span data-ttu-id="838a4-374">Corrigido um problema que impedia a capacidade de mudar para editar arquivos que foram abertos como "leitura somente recomendado".</span><span class="sxs-lookup"><span data-stu-id="838a4-374">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="838a4-375">OneNote</span><span class="sxs-lookup"><span data-stu-id="838a4-375">OneNote</span></span>

- <span data-ttu-id="838a4-376">Removido as chamadas de identidade redundantes para reduzir a utilização de recursos</span><span class="sxs-lookup"><span data-stu-id="838a4-376">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="838a4-377">Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.</span><span class="sxs-lookup"><span data-stu-id="838a4-377">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="838a4-378">Melhoria na capacidade de detecção de erros e na experiência de sincronização com qualidade.</span><span class="sxs-lookup"><span data-stu-id="838a4-378">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-379">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-379">Outlook</span></span>

- <span data-ttu-id="838a4-380">Foi abordado um problema que causava um problema de desempenho significativo ao iniciar o Outlook para alguns locatários.</span><span class="sxs-lookup"><span data-stu-id="838a4-380">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="838a4-381">Skype</span><span class="sxs-lookup"><span data-stu-id="838a4-381">Skype</span></span>

- <span data-ttu-id="838a4-382">Corrigido um problema em que iniciar um compartilhamento de tela pode falhar em um cliente do Skype for Business de 32 bits após ele estiver sendo executado por vários dias.</span><span class="sxs-lookup"><span data-stu-id="838a4-382">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-383">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="838a4-383">Office Suite</span></span>

- <span data-ttu-id="838a4-384">Corrigido um problema em que, quando o salvamento automático estava desativado na política de grupo, alguns documentos não podiam mostrar o conteúdo mais recente do servidor na abertura até o usuário clicar em "Atualizações disponíveis".</span><span class="sxs-lookup"><span data-stu-id="838a4-384">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-july-14"></a><span data-ttu-id="838a4-386">Versão 2002: 14 de julho</span><span class="sxs-lookup"><span data-stu-id="838a4-386">Version 2002: July 14</span></span>
<span data-ttu-id="838a4-387">*Versão 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="838a4-387">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="838a4-388">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-388">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-390">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-390">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-391">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-391">Excel</span></span>

- <span data-ttu-id="838a4-392">Acelerar o carregamento de arquivos disponíveis na pasta local do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="838a4-392">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="838a4-393">Correção de um problema que causava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="838a4-393">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="838a4-394">Correção de um problema em que a mensagem de erro "Esta pasta de trabalho está referenciada por outra pasta e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="838a4-394">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="838a4-395">Correção de um problema em que uma pasta de trabalho poderia ficar oculta ao clicar em um hiperlink em uma pasta de trabalho já aberta.</span><span class="sxs-lookup"><span data-stu-id="838a4-395">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="838a4-396">Correção de um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.</span><span class="sxs-lookup"><span data-stu-id="838a4-396">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="838a4-397">Desempenho aprimorado ao excluir colunas com células mescladas.</span><span class="sxs-lookup"><span data-stu-id="838a4-397">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="838a4-398">Correção de um problema em que os nomes de impressora poderiam ser repetidos na lista de impressoras na caixa de diálogo Imprimir.</span><span class="sxs-lookup"><span data-stu-id="838a4-398">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="838a4-399">Consertamos um problema em que as planilhas que continham várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.</span><span class="sxs-lookup"><span data-stu-id="838a4-399">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="838a4-400">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-400">Outlook</span></span>

- <span data-ttu-id="838a4-401">Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-401">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="838a4-402">Soluciona um problema em que compromissos ou reuniões recorrentes eram exibidos na hora errada ao alterar a definição de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="838a4-402">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="838a4-403">Soluciona um problema que exibia a mensagem “As regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.</span><span class="sxs-lookup"><span data-stu-id="838a4-403">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="838a4-404">Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.</span><span class="sxs-lookup"><span data-stu-id="838a4-404">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="838a4-405">Foi resolvido um problema que fazia com que as categorias desaparecessem ocasionalmente de mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="838a4-405">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="838a4-406">Foi resolvido um problema que fazia com que representantes vissem diferentes hierarquias de pastas em caixas de correio compartilhadas em computadores diferentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-406">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="838a4-407">Solucionamos um problema que fazia com que representantes recebessem uma mensagem de erro ao editar um compromisso de calendário existente no calendário de um gerenciador.</span><span class="sxs-lookup"><span data-stu-id="838a4-407">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="838a4-408">Correção de um problema que fazia com que o corpo de uma mensagem de Notificação de Falha na Entrega mudasse de Unicode para ASCII após editar o assunto.</span><span class="sxs-lookup"><span data-stu-id="838a4-408">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="838a4-409">Correção de um problema que causava uma falha quando dois suplementos adicionam um botão ao mesmo grupo da faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="838a4-409">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="838a4-410">Correção de um problema que fazia com que os usuários não conseguissem endereçar emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="838a4-410">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="838a4-411">Correção de um problema que fazia com que os links não sejam adicionados aos emails com a permissão de locatário padrão correta quando a permissão de locatário padrão está configurada como "qualquer pessoa".</span><span class="sxs-lookup"><span data-stu-id="838a4-411">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="838a4-412">Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.</span><span class="sxs-lookup"><span data-stu-id="838a4-412">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-413">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-413">Word</span></span>

- <span data-ttu-id="838a4-414">Correção de um problema na coautoria se habilitarmos a política FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="838a4-414">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="838a4-415">Correção de um problema em que partes rápidas no Word não funcionava ao adicionar um campo de pesquisa que foi renomeado.</span><span class="sxs-lookup"><span data-stu-id="838a4-415">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-416">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-416">Office Suite</span></span>

- <span data-ttu-id="838a4-417">Correção de um problema em que poderia ocorrer uso excessivo da rede e da CPU durante a coautoria em arquivos grandes do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-417">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="838a4-418">Fizemos um novo AppV51 para corrigir uma regressão no AppV51 anterior.</span><span class="sxs-lookup"><span data-stu-id="838a4-418">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="838a4-419">Soluciona um problema que causava falha no host do Office no Windows, quando um suplemento é ativado enquanto o valor TabProcGrowth do registro é do tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="838a4-419">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-june-09"></a><span data-ttu-id="838a4-421">Versão 2002: 09 de junho</span><span class="sxs-lookup"><span data-stu-id="838a4-421">Version 2002: June 09</span></span>
<span data-ttu-id="838a4-422">*Versão 2002 (Build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="838a4-422">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="838a4-423">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-423">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-425">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-425">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-426">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-426">Excel</span></span>

- <span data-ttu-id="838a4-427">Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.</span><span class="sxs-lookup"><span data-stu-id="838a4-427">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="838a4-428">Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.</span><span class="sxs-lookup"><span data-stu-id="838a4-428">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="838a4-429">Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.</span><span class="sxs-lookup"><span data-stu-id="838a4-429">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="838a4-430">Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".</span><span class="sxs-lookup"><span data-stu-id="838a4-430">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="838a4-431">Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="838a4-431">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="838a4-432">Correção de um problema em que um símbolo @ iniciando uma fórmula seria considerado um operador de interseção implícito.</span><span class="sxs-lookup"><span data-stu-id="838a4-432">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-433">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-433">Outlook</span></span>

- <span data-ttu-id="838a4-434">Permite que você ingresse em uma reunião do Teams diretamente por meio do cliente nativo do Teams.</span><span class="sxs-lookup"><span data-stu-id="838a4-434">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="838a4-435">Solucionamos um problema em que o Outlook falhava ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="838a4-435">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="838a4-436">Solucionamos um problema que fazia com que os usuários com a configuração de emulação do navegador incorreta não conseguissem concluir o prompt de autenticação do Gmail.</span><span class="sxs-lookup"><span data-stu-id="838a4-436">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="838a4-437">Solucionamos um problema que fazia com que os usuários do Outlook nos sistemas operacionais de servidor vissem o erro "status do antivírus: inválido".</span><span class="sxs-lookup"><span data-stu-id="838a4-437">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="838a4-438">Esta versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus era encontrado, apesar do antivírus ter sido configurado adequadamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-438">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-439">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-439">Word</span></span>

- <span data-ttu-id="838a4-440">Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.</span><span class="sxs-lookup"><span data-stu-id="838a4-440">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-441">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-441">Office Suite</span></span>

- <span data-ttu-id="838a4-442">Resolvemos esse problema atualizando os nomes dos canais no backstage para os nomes dos novos canais na bifurcação de Janeiro de 2020.</span><span class="sxs-lookup"><span data-stu-id="838a4-442">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="838a4-443">Corrigimos esse problema e no futuro, se um dispositivo for gerenciado por política, ele não chamará a API de audiência do DMS.</span><span class="sxs-lookup"><span data-stu-id="838a4-443">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="838a4-444">Resolvemos o problema em que há uma remoção incompleta ao adicionar e remover aplicativos em uma única transação.</span><span class="sxs-lookup"><span data-stu-id="838a4-444">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="838a4-445">O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero.</span><span class="sxs-lookup"><span data-stu-id="838a4-445">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="838a4-446">Essa alteração corrigiria esse problema.</span><span class="sxs-lookup"><span data-stu-id="838a4-446">This change would fix this issue.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-may-12"></a><span data-ttu-id="838a4-448">Versão 2002: 12 de maio</span><span class="sxs-lookup"><span data-stu-id="838a4-448">Version 2002: May 12</span></span>
<span data-ttu-id="838a4-449">*Versão 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="838a4-449">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="838a4-450">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-450">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-452">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-452">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="838a4-453">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-453">Excel</span></span>

- <span data-ttu-id="838a4-454">Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, especialmente com janelas ocultas, seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="838a4-454">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="838a4-455">A abertura de arquivos CSV estava demorando mais do que o esperado em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="838a4-455">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="838a4-456">O Excel pode falhar em algumas circunstâncias ao alternar entre pastas de trabalho com diferentes níveis de zoom.</span><span class="sxs-lookup"><span data-stu-id="838a4-456">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="838a4-457">Correção de um problema com o VBA no qual a escrita de valores em um intervalo seria mais lento do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="838a4-457">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="838a4-458">Os dados copiados de uma coluna filtrada por cores às vezes não serão colados corretamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-458">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="838a4-459">Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma Tabela Dinâmica.</span><span class="sxs-lookup"><span data-stu-id="838a4-459">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="838a4-460">As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.</span><span class="sxs-lookup"><span data-stu-id="838a4-460">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="838a4-461">Corrigido um problema em que a propriedade "O Valor Cruza Em" se altera inesperadamente ao salvar e reabrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="838a4-461">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="838a4-462">Usar um Intervalo.Valor e Intervalo.Valor2 (VBA) faria com que as fórmulas fossem inseridas como matrizes dinâmicas.</span><span class="sxs-lookup"><span data-stu-id="838a4-462">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="838a4-463">OneNote</span><span class="sxs-lookup"><span data-stu-id="838a4-463">OneNote</span></span>

- <span data-ttu-id="838a4-464">Localiza a notificação que permite que o usuário saiba mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.</span><span class="sxs-lookup"><span data-stu-id="838a4-464">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="838a4-465">Exibe uma notificação que permite ao usuário saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade do serviço e de sincronia.</span><span class="sxs-lookup"><span data-stu-id="838a4-465">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="838a4-466">Melhoria da estabilidade do serviço e de sincronização, reduzindo temporariamente a frequência do número e da sincronia das páginas do histórico de versão no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-466">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="838a4-467">Melhoria da sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-467">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="838a4-468">Quando um usuário tenta excluir dados que normalmente seriam enviados para a lixeira, os usuários serão solicitados a optar por manter ou excluir permanentemente os dados.</span><span class="sxs-lookup"><span data-stu-id="838a4-468">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="838a4-469">Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-469">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="838a4-470">Melhoria da estabilidade do serviço e da sincronia referindo-se temporariamente ao download de arquivos e imagens inseridas em blocos de anotações online até que o usuário navegue para a página no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-470">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="838a4-471">Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-471">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="838a4-472">Os blocos de anotações locais não são afetados por essa medida.</span><span class="sxs-lookup"><span data-stu-id="838a4-472">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="838a4-473">Melhoria da sincronia e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="838a4-473">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="838a4-474">Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.</span><span class="sxs-lookup"><span data-stu-id="838a4-474">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-475">Outlook</span></span>

- <span data-ttu-id="838a4-476">Corrigido um problema que provocou a alteração inesperada da largura do painel de pasta.</span><span class="sxs-lookup"><span data-stu-id="838a4-476">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="838a4-477">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao tentar abrir arquivos .msg e .oft após uma atualização do Windows.</span><span class="sxs-lookup"><span data-stu-id="838a4-477">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="838a4-478">Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.</span><span class="sxs-lookup"><span data-stu-id="838a4-478">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="838a4-479">Esta atualização corrige um problema com o Microsoft Outlook, que não exibe o rótulo de confidencialidade atual ao exibir ou redigir mensagens.</span><span class="sxs-lookup"><span data-stu-id="838a4-479">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="838a4-480">Solucionamos um problema que fazia com que os usuários não conseguissem lidar com emails em uma lista de distribuição pessoal.</span><span class="sxs-lookup"><span data-stu-id="838a4-480">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="838a4-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-481">PowerPoint</span></span>

- <span data-ttu-id="838a4-482">Correção de um problema para retransmissão de mensagens corretas para os usuários que abrirem uma cópia de um arquivo que tenha comentários melhorados.</span><span class="sxs-lookup"><span data-stu-id="838a4-482">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-483">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-483">Word</span></span>

- <span data-ttu-id="838a4-484">Resolvemos o problema em que o Access e o Publisher podem não inicializar corretamente dependendo de quais idiomas foram instalados.</span><span class="sxs-lookup"><span data-stu-id="838a4-484">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="838a4-485">Corrigimos um problema com o recurso Comparar em documentos protegidos para edição.</span><span class="sxs-lookup"><span data-stu-id="838a4-485">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="838a4-486">Corrigimos um problema ao mesclar dois documentos em um único documento.</span><span class="sxs-lookup"><span data-stu-id="838a4-486">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-487">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-487">Office Suite</span></span>

- <span data-ttu-id="838a4-488">Esta é uma correção para que o aplicativo do Project não bloqueie rede quando o arquivo estiver armazenado em cache no cliente.</span><span class="sxs-lookup"><span data-stu-id="838a4-488">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="838a4-489">Resolvemos o problema em que uma operação interna estava gerando uma exceção na falha, em vez de fazer o logon e continuar.</span><span class="sxs-lookup"><span data-stu-id="838a4-489">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="838a4-490">Os usuários afetados não serão mais impedidos de receber as atualizações.</span><span class="sxs-lookup"><span data-stu-id="838a4-490">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="838a4-491">Essa alteração garante que a estrutura de tópicos Esboçada funcione corretamente na faixa de opções.</span><span class="sxs-lookup"><span data-stu-id="838a4-491">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="838a4-492">Corrigimos um problema ao abrir arquivos de locais no ambiente local com algumas configurações específicas de proxy.</span><span class="sxs-lookup"><span data-stu-id="838a4-492">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="838a4-493">Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.</span><span class="sxs-lookup"><span data-stu-id="838a4-493">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="838a4-494">Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.</span><span class="sxs-lookup"><span data-stu-id="838a4-494">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="838a4-495">Esta atualização corrige um problema no Microsoft Word, em que textos com mais de 255 caracteres inseridos durante a aplicação de um rótulo de sensibilidade não poderiam ser subsequentemente identificados e removidos alterando ou removendo a etiqueta se a política de rótulo tiver aplicado um cabeçalho, rodapé ou marca-d ' água.</span><span class="sxs-lookup"><span data-stu-id="838a4-495">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="838a4-496">Correção de um problema que elimina panes durante as sessões de entrega do Office e maior confiabilidade na experiência do usuário.</span><span class="sxs-lookup"><span data-stu-id="838a4-496">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="838a4-497">Esse bug atualiza o ponto de extremidade da URL do serviço de configuração avançada (ECS).</span><span class="sxs-lookup"><span data-stu-id="838a4-497">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="838a4-498">Chamar esse ponto de extremidade mais recente tem uma taxa de sucesso maior para buscar a partir de ECS.</span><span class="sxs-lookup"><span data-stu-id="838a4-498">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-april-14"></a><span data-ttu-id="838a4-500">Versão 2002: 14 de abril</span><span class="sxs-lookup"><span data-stu-id="838a4-500">Version 2002: April 14</span></span>
<span data-ttu-id="838a4-501">*Versão 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="838a4-501">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="838a4-502">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-502">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="838a4-503">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="838a4-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-504">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-504">Excel</span></span>

- <span data-ttu-id="838a4-505">**Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão enviados para as células vizinhas automaticamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-505">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="838a4-506">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-506">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="838a4-507">**Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span><span class="sxs-lookup"><span data-stu-id="838a4-507">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="838a4-508">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-508">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="838a4-509">**Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!** Linha por linha, encontre tudo o que precisa em uma tabela ou intervalo com XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="838a4-509">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="838a4-510">
  [Saiba mais](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="838a4-510">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-512">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-512">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-513">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-513">Excel</span></span>

- <span data-ttu-id="838a4-514">O Excel falharia em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-514">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="838a4-515">Ao salvar como um arquivo CSV, o Excel poderia mesclar todas as colunas em uma única coluna em alguns casos.</span><span class="sxs-lookup"><span data-stu-id="838a4-515">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="838a4-516">Usar Range.ClearContents em um intervalo de uma planilha protegida pode levar mais tempo do que o esperado.</span><span class="sxs-lookup"><span data-stu-id="838a4-516">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="838a4-517">Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.</span><span class="sxs-lookup"><span data-stu-id="838a4-517">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="838a4-518">As macros do VBA que interagem com a faixa de opções podem ser executadas com o conjunto de ScreenUpdating definido como Verdadeiro inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-518">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="838a4-519">Foi solucionado um problema em que os links externos não eram atualizados durante o preenchimento (preencher abaixo, preencher entre, etc.) se o livro de origem estivesse fechado.</span><span class="sxs-lookup"><span data-stu-id="838a4-519">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="838a4-520">Em alguns casos, o uso do Application.Evaluate do VBA não funcionava para funções definidas pelo usuário.</span><span class="sxs-lookup"><span data-stu-id="838a4-520">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="838a4-521">Solucionamos um problema de desempenho durante a criação de gráficos de modelos.</span><span class="sxs-lookup"><span data-stu-id="838a4-521">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="838a4-522">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-522">Outlook</span></span>

- <span data-ttu-id="838a4-523">Foi solucionado um problema que fazia com que o Título do Grupo se expandisse inesperadamente em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="838a4-523">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="838a4-524">Foi resolvido um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="838a4-524">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="838a4-525">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="838a4-525">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="838a4-526">Foi solucionado um problema que fazia com que o botão Salvar na nuvem estivesse ausente nas Ferramentas de anexo.</span><span class="sxs-lookup"><span data-stu-id="838a4-526">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="838a4-527">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-527">PowerPoint</span></span>

- <span data-ttu-id="838a4-528">Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-lo em outro slide em um loop.</span><span class="sxs-lookup"><span data-stu-id="838a4-528">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="838a4-529">Project</span><span class="sxs-lookup"><span data-stu-id="838a4-529">Project</span></span>

- <span data-ttu-id="838a4-530">Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.</span><span class="sxs-lookup"><span data-stu-id="838a4-530">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="838a4-531">Correção de um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.</span><span class="sxs-lookup"><span data-stu-id="838a4-531">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-532">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-532">Word</span></span>

- <span data-ttu-id="838a4-533">Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.</span><span class="sxs-lookup"><span data-stu-id="838a4-533">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="838a4-534">Corrigimos um problema com o ajuste de texto em uma tabela.</span><span class="sxs-lookup"><span data-stu-id="838a4-534">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="838a4-535">Corrigimos um problema em que não era possível inserir linhas horizontais e centralizar.</span><span class="sxs-lookup"><span data-stu-id="838a4-535">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="838a4-537">Versão 2002: 10 de março</span><span class="sxs-lookup"><span data-stu-id="838a4-537">Version 2002: March 10</span></span>
<span data-ttu-id="838a4-538">*Versão 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="838a4-538">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="838a4-539">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-539">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="838a4-541">Atualizações de recursos</span><span class="sxs-lookup"><span data-stu-id="838a4-541">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="838a4-542">Access</span><span class="sxs-lookup"><span data-stu-id="838a4-542">Access</span></span>

- <span data-ttu-id="838a4-543">**Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas.</span><span class="sxs-lookup"><span data-stu-id="838a4-543">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="838a4-544">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-544">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="838a4-545">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-545">Excel</span></span>

- <span data-ttu-id="838a4-546">**Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles.</span><span class="sxs-lookup"><span data-stu-id="838a4-546">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="838a4-547">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-547">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="838a4-548">**Encontre o que está procurando:** Pesquise comandos, pessoas, arquivos, fotos, artigos da Web e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-548">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="838a4-549">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-549">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="838a4-550">**Faça um Esboço:** Deixe as formas do Office da sua pasta de trabalho com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="838a4-550">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="838a4-551">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-551">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="838a4-552">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="838a4-552">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="838a4-553">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="838a4-553">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="838a4-554">**Foco no que precisa ser feito:** Selecione Resolver para recolher comentários e dar destaque aos itens abertos.</span><span class="sxs-lookup"><span data-stu-id="838a4-554">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="838a4-555">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="838a4-555">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="838a4-556">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-556">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="838a4-557">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="838a4-557">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="838a4-558">**Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel.</span><span class="sxs-lookup"><span data-stu-id="838a4-558">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="838a4-559">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-559">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="838a4-560">**Leia e responda instantaneamente:** Responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="838a4-560">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="838a4-561">**Obtenha estatísticas em sua pasta de trabalho:** As Estatísticas da Pasta de Trabalho fornecem uma visão geral do conteúdo de uma pasta de trabalho, para ajudar você a descobrir o conteúdo com mais facilidade.</span><span class="sxs-lookup"><span data-stu-id="838a4-561">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="838a4-562">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-562">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="838a4-563">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-563">Find them at Insert > Icons.</span></span> [<span data-ttu-id="838a4-564">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-564">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="838a4-565">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-565">Outlook</span></span>

- <span data-ttu-id="838a4-566">**Conecte sua rede do LinkedIn ao Outlook:** Conecte sua conta do LinkedIn com segurança à sua conta da Microsoft para ver informações de perfis do LinkedIn diretamente no cartão de Pessoas.</span><span class="sxs-lookup"><span data-stu-id="838a4-566">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="838a4-567">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-567">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="838a4-p156">**Todas as opções de criptografia em um só lugar:** Basta ir para Opções > Criptografar para escolher como proteger sua mensagem de email. [Saiba mais](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="838a4-p156">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="838a4-570">**O menu Inserir Link no Outlook inserirá um link com a permissão definida pelo administrador do locatário:** um link do Inserir Link MRU no Outlook insere um link que só funcionou para usuários que já tinham permissões.</span><span class="sxs-lookup"><span data-stu-id="838a4-570">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="838a4-571">Isso causou uma troca de emails frequente entre os usuários solicitando o acesso a um documento.</span><span class="sxs-lookup"><span data-stu-id="838a4-571">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="838a4-572">Atualizamos essa experiência e agora o link é inserido com a permissão padrão definida pelo administrador do locatário. No MSIT, é "A organização pode editar", para que todos os usuários internos que recebem um link compartilhado dessa maneira possam acessá-lo.</span><span class="sxs-lookup"><span data-stu-id="838a4-572">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="838a4-573">**Pesquisar com erros de ortografia ou digitação:** O Outlook encontrará o que você está procurando, mesmo quando a ortografia não corresponder.</span><span class="sxs-lookup"><span data-stu-id="838a4-573">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="838a4-574">**Emails de phishing fáceis de identificar:** As mensagens de spam e phishing têm uma aparência diferente, para que você possa identificá-las e eliminá-las facilmente na caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="838a4-574">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="838a4-575">**Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.</span><span class="sxs-lookup"><span data-stu-id="838a4-575">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="838a4-576">**Deixe-me desenhar:** Rabisque em fotos ou adicione uma Tela de Desenho para enviar seus pensamentos com tinta.</span><span class="sxs-lookup"><span data-stu-id="838a4-576">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="838a4-577">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-577">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="838a4-578">**Veja as mensagens relevantes nos resultados de pesquisa:** o Outlook analisa os termos de pesquisa e mostra as mensagens de email mais relevantes na parte superior dos resultados da pesquisa.</span><span class="sxs-lookup"><span data-stu-id="838a4-578">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="838a4-579">Você também verá todos os resultados classificados por data, na seção Resultados Principais.</span><span class="sxs-lookup"><span data-stu-id="838a4-579">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="838a4-580">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-580">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="838a4-581">**Obtenha sugestões de locais:** comece a digitar em Local ao agendar compromissos e reuniões, e o Outlook irá sugerir salas, endereços e outros locais recentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-581">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="838a4-582">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-582">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="838a4-583">**Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens.</span><span class="sxs-lookup"><span data-stu-id="838a4-583">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="838a4-584">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-584">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="838a4-585">**Veja suas mensagens sob uma perspectiva diferente:** use o botão Sol/Lua para alternar entre planos de fundo claros e escuros no painel de leitura.</span><span class="sxs-lookup"><span data-stu-id="838a4-585">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="838a4-586">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-586">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="838a4-587">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-587">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="838a4-588">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-588">Find them at Insert > Icons.</span></span> [<span data-ttu-id="838a4-589">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-589">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="838a4-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-590">PowerPoint</span></span>

- <span data-ttu-id="838a4-591">**Colaboração rápida e em tempo real no PowerPoint:** Colaboração rápida e em tempo real no PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-591">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="838a4-592">**Novas ferramentas de revisão:** não se preocupe com suas palavras.</span><span class="sxs-lookup"><span data-stu-id="838a4-592">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="838a4-593">Agora, o PowerPoint fornece sugestões de gramática e ortografia.</span><span class="sxs-lookup"><span data-stu-id="838a4-593">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="838a4-594">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-594">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="838a4-595">**Legendas em tempo real:** As palavras do apresentador aparecem na tela automaticamente como legendas ou traduzidas para o idioma que escolher.</span><span class="sxs-lookup"><span data-stu-id="838a4-595">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="838a4-596">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-596">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="838a4-p166">**Você calcula, nós formatamos:** Nós trocamos expressões matemáticas difíceis de desenhar por caracteres padrão. Basta escolher Tinta para Matemática e selecionar suas anotações manuscritas para começar.[Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="838a4-p166">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="838a4-600">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-600">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="838a4-601">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-601">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="838a4-602">**Localize e corrija títulos de slides ausentes:** Títulos de slides reforçam o seu discurso e tornam os seus slides acessíveis a usuários de todas as habilidades.</span><span class="sxs-lookup"><span data-stu-id="838a4-602">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="838a4-603">O Verificador de Acessibilidade mostra onde os títulos estão ausentes para que você possa adicioná-los imediatamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-603">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="838a4-604">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-604">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="838a4-605">**Faça um Esboço:** deixe as formas do Office da sua apresentação com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="838a4-605">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="838a4-606">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-606">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="838a4-607">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="838a4-607">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="838a4-608">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="838a4-608">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="838a4-609">**Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem.</span><span class="sxs-lookup"><span data-stu-id="838a4-609">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="838a4-610">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-610">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="838a4-611">**Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos.</span><span class="sxs-lookup"><span data-stu-id="838a4-611">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="838a4-612">Deixá-los ou não ativados depende de você.</span><span class="sxs-lookup"><span data-stu-id="838a4-612">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="838a4-613">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-613">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="838a4-614">**Repe-tinta-ção Instantânea:** Ao escrever à tinta nos slides, aplique uma animação de repetição para reproduzir o desenho real da sua tinta durante a apresentação de slides.</span><span class="sxs-lookup"><span data-stu-id="838a4-614">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="838a4-615">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-615">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="838a4-616">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="838a4-616">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="838a4-617">**Otimize sua apresentação para todos:** O Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.</span><span class="sxs-lookup"><span data-stu-id="838a4-617">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="838a4-618">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="838a4-618">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="838a4-619">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="838a4-619">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="838a4-620">**Por que reinventa quando você pode reutilizar?:** poupar tempo usando novamente slides que você criou ou que outras pessoas compartilharam com você.</span><span class="sxs-lookup"><span data-stu-id="838a4-620">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="838a4-621">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-621">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="838a4-622">**Transforme tinta manuscrita em formas, texto ou expressões matemáticas no PowerPoint para Office 365:** Vá de tinta de forma livre para formas, texto ou uma expressão matemática com apenas alguns traços.</span><span class="sxs-lookup"><span data-stu-id="838a4-622">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="838a4-623">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-623">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="838a4-624">**Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-624">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="838a4-625">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-625">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="838a4-626">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-626">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="838a4-627">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-627">Find them at Insert > Icons.</span></span> [<span data-ttu-id="838a4-628">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-628">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="838a4-629">Visio</span><span class="sxs-lookup"><span data-stu-id="838a4-629">Visio</span></span>

- <span data-ttu-id="838a4-630">**Voltando para a cena do crime:** Use os novos estênceis de Evidência, Interno e Externo no modelo de Investigação de Cena de Crime para recriar cenas de crimes em detalhes.</span><span class="sxs-lookup"><span data-stu-id="838a4-630">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="838a4-631">**Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha.</span><span class="sxs-lookup"><span data-stu-id="838a4-631">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="838a4-632">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-632">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="838a4-633">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-633">Word</span></span>

- <span data-ttu-id="838a4-634">**O Editor de Currículos se une ao Assistente de Currículos do LinkedIn:** O Editor de Currículos oferece uma seleção de verificações gramaticais e de estilo especialmente adaptadas para currículos, para tornar a sua escrita mais precisa e profissional.</span><span class="sxs-lookup"><span data-stu-id="838a4-634">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="838a4-635">**Corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D:** corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D.</span><span class="sxs-lookup"><span data-stu-id="838a4-635">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="838a4-636">**Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais.</span><span class="sxs-lookup"><span data-stu-id="838a4-636">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="838a4-637">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-637">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="838a4-638">**Colabore em cores:** Comentários e alterações são codificados por cores por colaborador, para que seja fácil ver quem está entre seus colaboradores.</span><span class="sxs-lookup"><span data-stu-id="838a4-638">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="838a4-639">**Edite documentos habilitados para macro de maneira colaborativa:** Salve arquivos docm no OneDrive for Business e edite-os com seus colaboradores em tempo real.</span><span class="sxs-lookup"><span data-stu-id="838a4-639">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="838a4-640">**Aperfeiçoamentos de coautoria**: melhor desempenho do Word durante a coautoria em documentos com alterações controladas.</span><span class="sxs-lookup"><span data-stu-id="838a4-640">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="838a4-641">**Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-641">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="838a4-642">Encontre-os em Inserir > Ícones.</span><span class="sxs-lookup"><span data-stu-id="838a4-642">Find them at Insert > Icons.</span></span> [<span data-ttu-id="838a4-643">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-643">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="838a4-644">**Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.</span><span class="sxs-lookup"><span data-stu-id="838a4-644">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="838a4-645">**Faça um Esboço:** deixe as formas do Office do seu documento com uma aparência casual de desenhado à mão.</span><span class="sxs-lookup"><span data-stu-id="838a4-645">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="838a4-646">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-646">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="838a4-647">**Apagar com precisão:** Escolha entre dois tamanhos de borracha para corrigir pequenas imperfeições à tinta.</span><span class="sxs-lookup"><span data-stu-id="838a4-647">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="838a4-648">Saiba Mais</span><span class="sxs-lookup"><span data-stu-id="838a4-648">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="838a4-649">**Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.</span><span class="sxs-lookup"><span data-stu-id="838a4-649">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="838a4-650">**Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.</span><span class="sxs-lookup"><span data-stu-id="838a4-650">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="838a4-651">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-651">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="838a4-652">**Melhorias na coautoria** Confiabilidade aprimorada durante a coautoria.</span><span class="sxs-lookup"><span data-stu-id="838a4-652">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="838a4-653">**Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.</span><span class="sxs-lookup"><span data-stu-id="838a4-653">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="838a4-654">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-654">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="838a4-655">**Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.</span><span class="sxs-lookup"><span data-stu-id="838a4-655">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="838a4-656">**Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.</span><span class="sxs-lookup"><span data-stu-id="838a4-656">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="838a4-657">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="838a4-657">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-660">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-660">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="838a4-661">Acessar</span><span class="sxs-lookup"><span data-stu-id="838a4-661">Access</span></span>

- <span data-ttu-id="838a4-662">Esta atualização corrige um problema no Microsoft Access que pode causar o erro “A consulta está corrompida” quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada no SQL.</span><span class="sxs-lookup"><span data-stu-id="838a4-662">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="838a4-663">Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-663">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="838a4-664">Esta atualização corrige um problema no uso de um ADODB.</span><span class="sxs-lookup"><span data-stu-id="838a4-664">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="838a4-665">O objeto gravador no código VB pode incorretamente relatar um erro.</span><span class="sxs-lookup"><span data-stu-id="838a4-665">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="838a4-666">Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados.</span><span class="sxs-lookup"><span data-stu-id="838a4-666">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="838a4-667">Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.</span><span class="sxs-lookup"><span data-stu-id="838a4-667">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="838a4-668">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-668">Excel</span></span>

- <span data-ttu-id="838a4-669">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="838a4-669">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="838a4-670">Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.</span><span class="sxs-lookup"><span data-stu-id="838a4-670">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="838a4-671">Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.</span><span class="sxs-lookup"><span data-stu-id="838a4-671">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="838a4-672">Esta atualização corrige um problema que fazia com que barra de fórmulas exibisse texto em uma fonte diferente da esperada.</span><span class="sxs-lookup"><span data-stu-id="838a4-672">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="838a4-673">A funcionalidade Texto em Coluna pode falhar para algumas localidades.</span><span class="sxs-lookup"><span data-stu-id="838a4-673">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="838a4-674">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="838a4-674">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="838a4-675">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="838a4-675">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="838a4-676">Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.</span><span class="sxs-lookup"><span data-stu-id="838a4-676">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="838a4-677">O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.</span><span class="sxs-lookup"><span data-stu-id="838a4-677">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="838a4-678">A funcionalidade Texto em Coluna pode falhar em algumas localizações.</span><span class="sxs-lookup"><span data-stu-id="838a4-678">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="838a4-679">Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.</span><span class="sxs-lookup"><span data-stu-id="838a4-679">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="838a4-680">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="838a4-680">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="838a4-681">Foi corrigido um problema que alguns usuários podem ter tido com objetos inseridos e vinculados (OLE).</span><span class="sxs-lookup"><span data-stu-id="838a4-681">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="838a4-682">Corrigimos o menu do botão direito do mouse de Gráficos Dinâmicos para habilitar a opção Mostrar Detalhes.</span><span class="sxs-lookup"><span data-stu-id="838a4-682">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="838a4-683">Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.</span><span class="sxs-lookup"><span data-stu-id="838a4-683">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="838a4-684">Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.</span><span class="sxs-lookup"><span data-stu-id="838a4-684">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="838a4-685">Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.</span><span class="sxs-lookup"><span data-stu-id="838a4-685">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="838a4-686">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="838a4-686">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="838a4-687">Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.</span><span class="sxs-lookup"><span data-stu-id="838a4-687">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-688">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-688">Outlook</span></span>

- <span data-ttu-id="838a4-689">Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.</span><span class="sxs-lookup"><span data-stu-id="838a4-689">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="838a4-690">Solucionamos um problema que fazia com que os usuários experimentassem travamentos no Outlook ao recuperar as configurações da Nuvem.</span><span class="sxs-lookup"><span data-stu-id="838a4-690">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="838a4-691">Foi corrigido um problema que provocava um alinhamento inadequado da caixa de pesquisa no modo de DPI alto.</span><span class="sxs-lookup"><span data-stu-id="838a4-691">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="838a4-692">Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.</span><span class="sxs-lookup"><span data-stu-id="838a4-692">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="838a4-693">Solucionamos um problema que fazia com que os usuários vissem os e-mails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.</span><span class="sxs-lookup"><span data-stu-id="838a4-693">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="838a4-694">Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.</span><span class="sxs-lookup"><span data-stu-id="838a4-694">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="838a4-695">Consertamos um problema que podia impedir que os arquivos fossem salvos em um local do WebDAV.</span><span class="sxs-lookup"><span data-stu-id="838a4-695">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="838a4-696">Corrigido um problema com a seleção de algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="838a4-696">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="838a4-697">Solucionamos um problema que fazia com que aplicativos de terceiros não conseguissem enviar emails.</span><span class="sxs-lookup"><span data-stu-id="838a4-697">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="838a4-698">Resolvido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.</span><span class="sxs-lookup"><span data-stu-id="838a4-698">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="838a4-699">Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="838a4-699">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="838a4-700">Solucionamos um problema que fazia o Outlook sincronizar inesperadamente todos os emails, mesmo quando o controle deslizante de sincronização estivesse definido com uma configuração menor.</span><span class="sxs-lookup"><span data-stu-id="838a4-700">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="838a4-701">Solucionamos um problema que fez que usuários com tema escuro vissem o “De” suspenso mostrar texto branco sobre fundo branco.</span><span class="sxs-lookup"><span data-stu-id="838a4-701">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="838a4-702">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.</span><span class="sxs-lookup"><span data-stu-id="838a4-702">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="838a4-703">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="838a4-703">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="838a4-704">Solucionado um problema que fazia com que a opção desativar o realce do item sinalizado deixasse de ser respeitada em alguns cenários.</span><span class="sxs-lookup"><span data-stu-id="838a4-704">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="838a4-705">Resolvido um problema que fazia com que usuários vissem um aviso “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo de Regras.</span><span class="sxs-lookup"><span data-stu-id="838a4-705">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="838a4-706">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="838a4-706">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="838a4-707">Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.</span><span class="sxs-lookup"><span data-stu-id="838a4-707">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="838a4-708">Solucionamos um problema que podia resultar em uma falha ao exibir o mesmo item em várias janelas.</span><span class="sxs-lookup"><span data-stu-id="838a4-708">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="838a4-709">Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="838a4-709">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="838a4-710">Solucionamos um problema que fazia com que os usuários não conseguissem abrir algumas instâncias de itens de calendário recorrentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-710">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="838a4-711">Solucionamos um problema que fazia com que os usuários com caixas de correio em servidores do Exchange 2010 tivessem problemas ao adicionar anexos a itens de calendário.</span><span class="sxs-lookup"><span data-stu-id="838a4-711">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="838a4-712">Solucionamos um problema que fazia com que os usuários tivessem problemas ao responder a mensagens assinadas digitalmente.</span><span class="sxs-lookup"><span data-stu-id="838a4-712">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="838a4-713">Corrigimos um problema que fazia com que o campo Local nas reuniões fosse atualizado inesperadamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-713">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="838a4-714">Solucionamos um problema que fazia com que as vírgulas no campo de local de uma reunião se transformassem em pontos-e-vírgulas.</span><span class="sxs-lookup"><span data-stu-id="838a4-714">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="838a4-715">Solucionamos um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após a limpeza.</span><span class="sxs-lookup"><span data-stu-id="838a4-715">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="838a4-716">Solucionamos problemas relacionados a reuniões e compromissos no fuso horário de Brasília.</span><span class="sxs-lookup"><span data-stu-id="838a4-716">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="838a4-717">Foi corrigido um problema que fazia com que emails fossem enviados inesperadamente ao pressionar a tecla “S” após fechar o painel do verificador de acessibilidade.</span><span class="sxs-lookup"><span data-stu-id="838a4-717">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="838a4-718">Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.</span><span class="sxs-lookup"><span data-stu-id="838a4-718">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="838a4-719">Solucionamos um problema que fazia com que suplementos da Web acessassem mensagens com Gerenciamento de Direitos Digitais.</span><span class="sxs-lookup"><span data-stu-id="838a4-719">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="838a4-720">Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.</span><span class="sxs-lookup"><span data-stu-id="838a4-720">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="838a4-721">Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="838a4-721">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="838a4-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-722">PowerPoint</span></span>

- <span data-ttu-id="838a4-723">Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.</span><span class="sxs-lookup"><span data-stu-id="838a4-723">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="838a4-724">Solucionamos um problema que pode ter causado uma falha ao usar o menu de contexto em comentários de PPT herdados.</span><span class="sxs-lookup"><span data-stu-id="838a4-724">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="838a4-725">Projeto</span><span class="sxs-lookup"><span data-stu-id="838a4-725">Project</span></span>

- <span data-ttu-id="838a4-726">Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.</span><span class="sxs-lookup"><span data-stu-id="838a4-726">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="838a4-727">Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.</span><span class="sxs-lookup"><span data-stu-id="838a4-727">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="838a4-728">Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</span><span class="sxs-lookup"><span data-stu-id="838a4-728">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="838a4-729">Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="838a4-729">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-730">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-730">Word</span></span>

- <span data-ttu-id="838a4-731">Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.</span><span class="sxs-lookup"><span data-stu-id="838a4-731">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="838a4-732">O organizador de blocos de construção pode exibir um alerta inválido: “Você modificou estilos, blocos de construção”.</span><span class="sxs-lookup"><span data-stu-id="838a4-732">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-733">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="838a4-733">Office Suite</span></span>

- <span data-ttu-id="838a4-734">Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.</span><span class="sxs-lookup"><span data-stu-id="838a4-734">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="838a4-735">Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.</span><span class="sxs-lookup"><span data-stu-id="838a4-735">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="838a4-736">Correção de um bug na configuração de Data Limite de Atualização ODT e GPO, em que o prazo relativo só funcionava na primeira vez que era definido. A correção permite definir a data limite relativa nas atualizações subsequentes.</span><span class="sxs-lookup"><span data-stu-id="838a4-736">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="838a4-737">Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="838a4-737">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="838a4-738">Foi corrigido um problema em que, quando vários documentos da mesma biblioteca do SharePoint estivessem abertos no Word/Excel/PowerPoint, somente o primeiro documento aberto era verificado quanto à conformidade com Políticas.</span><span class="sxs-lookup"><span data-stu-id="838a4-738">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a><span data-ttu-id="838a4-740">Versão 1908: 11 de fevereiro</span><span class="sxs-lookup"><span data-stu-id="838a4-740">Version 1908: February 11</span></span>
<span data-ttu-id="838a4-741">*Versão 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="838a4-741">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="838a4-742">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-742">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-744">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-744">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-745">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-745">Excel</span></span>

- <span data-ttu-id="838a4-746">Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.</span><span class="sxs-lookup"><span data-stu-id="838a4-746">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="838a4-747">Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.</span><span class="sxs-lookup"><span data-stu-id="838a4-747">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="838a4-748">Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.</span><span class="sxs-lookup"><span data-stu-id="838a4-748">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="838a4-749">Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.</span><span class="sxs-lookup"><span data-stu-id="838a4-749">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="838a4-750">Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.</span><span class="sxs-lookup"><span data-stu-id="838a4-750">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="838a4-751">Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.</span><span class="sxs-lookup"><span data-stu-id="838a4-751">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="838a4-752">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-752">Outlook</span></span>

- <span data-ttu-id="838a4-753">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.</span><span class="sxs-lookup"><span data-stu-id="838a4-753">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="838a4-754">Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.</span><span class="sxs-lookup"><span data-stu-id="838a4-754">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="838a4-755">Solucionado um problema que fazia com que os usuários experimentassem um travamento na tela Carregando perfil ao iniciar o Outlook.</span><span class="sxs-lookup"><span data-stu-id="838a4-755">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="838a4-756">Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.</span><span class="sxs-lookup"><span data-stu-id="838a4-756">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="838a4-757">Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="838a4-757">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="838a4-758">[Aqui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.</span><span class="sxs-lookup"><span data-stu-id="838a4-758">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="838a4-759">Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.</span><span class="sxs-lookup"><span data-stu-id="838a4-759">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="838a4-760">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-760">PowerPoint</span></span>

- <span data-ttu-id="838a4-761">Melhorou um cenário de copiar e colar Copiando a Forma no slide do powerpoint e colando em outro slide em um loop poderia falhar, com exceção.</span><span class="sxs-lookup"><span data-stu-id="838a4-761">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="838a4-762">Corrigido um problema que estava causando um desempenho mais lento entre os usuários da colaboração.</span><span class="sxs-lookup"><span data-stu-id="838a4-762">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="838a4-763">Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.</span><span class="sxs-lookup"><span data-stu-id="838a4-763">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="838a4-764">Corrigimos um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="838a4-764">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="838a4-765">Project</span><span class="sxs-lookup"><span data-stu-id="838a4-765">Project</span></span>

- <span data-ttu-id="838a4-766">Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.</span><span class="sxs-lookup"><span data-stu-id="838a4-766">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="838a4-767">Word</span><span class="sxs-lookup"><span data-stu-id="838a4-767">Word</span></span>

- <span data-ttu-id="838a4-768">Corrigida uma falha no Word afastando-se de uma API reprovada.</span><span class="sxs-lookup"><span data-stu-id="838a4-768">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-769">Pacote do Office</span><span class="sxs-lookup"><span data-stu-id="838a4-769">Office Suite</span></span>

- <span data-ttu-id="838a4-770">Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.</span><span class="sxs-lookup"><span data-stu-id="838a4-770">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a><span data-ttu-id="838a4-772">Versão 1908:14 de janeiro</span><span class="sxs-lookup"><span data-stu-id="838a4-772">Version 1908: January 14</span></span>
<span data-ttu-id="838a4-773">*Versão 1908 (Build 11929,20562)*</span><span class="sxs-lookup"><span data-stu-id="838a4-773">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="838a4-774">Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="838a4-774">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="838a4-776">Problemas resolvidos</span><span class="sxs-lookup"><span data-stu-id="838a4-776">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="838a4-777">Excel</span><span class="sxs-lookup"><span data-stu-id="838a4-777">Excel</span></span>

- <span data-ttu-id="838a4-778">A dica de tecla holandesa para o título do documento foi alterada para Alt-G.</span><span class="sxs-lookup"><span data-stu-id="838a4-778">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="838a4-779">Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.</span><span class="sxs-lookup"><span data-stu-id="838a4-779">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="838a4-780">Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.</span><span class="sxs-lookup"><span data-stu-id="838a4-780">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="838a4-781">Outlook</span><span class="sxs-lookup"><span data-stu-id="838a4-781">Outlook</span></span>

- <span data-ttu-id="838a4-782">Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.</span><span class="sxs-lookup"><span data-stu-id="838a4-782">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="838a4-783">Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.</span><span class="sxs-lookup"><span data-stu-id="838a4-783">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="838a4-784">Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.</span><span class="sxs-lookup"><span data-stu-id="838a4-784">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="838a4-785">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="838a4-785">PowerPoint</span></span>

- <span data-ttu-id="838a4-786">Corrigimos um problema que poderia criar mestres ao copiar um slide de uma apresentação para outra.</span><span class="sxs-lookup"><span data-stu-id="838a4-786">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="838a4-787">Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada</span><span class="sxs-lookup"><span data-stu-id="838a4-787">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="838a4-788">Pacote Office</span><span class="sxs-lookup"><span data-stu-id="838a4-788">Office Suite</span></span>

- <span data-ttu-id="838a4-789">Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado.</span><span class="sxs-lookup"><span data-stu-id="838a4-789">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="838a4-790">Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.</span><span class="sxs-lookup"><span data-stu-id="838a4-790">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="838a4-791">Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.</span><span class="sxs-lookup"><span data-stu-id="838a4-791">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="838a4-793">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="838a4-793">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-august-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

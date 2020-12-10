---
title: Histórico da versão da Ferramenta de Implantação do Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fornece aos Profissionais de TI um histórico da versão da Ferramenta de Implantação do Office (ODT)
ms.openlocfilehash: 125f37f1fb4b21d2d63784e51703c1297d928f49
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601406"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="57eaa-103">Histórico do lançamento da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="57eaa-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="57eaa-104">A ODT (ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões clique para executar do Office, como os Aplicativos do Microsoft 365, para os computadores cliente.</span><span class="sxs-lookup"><span data-stu-id="57eaa-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="57eaa-105">A ODT dá mais controle sobre uma instalação do Office.</span><span class="sxs-lookup"><span data-stu-id="57eaa-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="57eaa-106">É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários.</span><span class="sxs-lookup"><span data-stu-id="57eaa-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="57eaa-107">Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="57eaa-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="57eaa-108">O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="57eaa-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="57eaa-109">**Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="57eaa-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="57eaa-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="57eaa-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="december-8-2020"></a><span data-ttu-id="57eaa-111">8 de dezembro de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-111">December 8, 2020</span></span>
<span data-ttu-id="57eaa-112">Versão 16.0.13426.20308 (setup.exe versão 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="57eaa-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="57eaa-113">Correção de um problema em que o modo de download estava bloqueando os downloads de canal de 2019 permanentes se o dispositivo tivesse um produto do Office instalado de um canal 2019 não-permanente.</span><span class="sxs-lookup"><span data-stu-id="57eaa-113">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="57eaa-114">Correção de um problema em que uma migração de arquitetura falharia em uma origem local criada por meio do modo de download que tenha especificado uma versão explícita no XML de configuração.</span><span class="sxs-lookup"><span data-stu-id="57eaa-114">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="57eaa-115">23 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-115">November 23, 2020</span></span>
<span data-ttu-id="57eaa-116">Versão 16.0.13328.20420 (setup.exe versão 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="57eaa-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="57eaa-117">Corrigido um problema em que os revisores de texto não estavam sendo baixados pelo modo /download</span><span class="sxs-lookup"><span data-stu-id="57eaa-117">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="57eaa-118">Corrigido um problema em que o modo /download falhava ao ser executado em um contexto de usuário não elevado</span><span class="sxs-lookup"><span data-stu-id="57eaa-118">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="57eaa-119">Corrigido um problema em que a especificação de um atributo de Versão no XML de configuração resultava em um download incompleto no modo /download</span><span class="sxs-lookup"><span data-stu-id="57eaa-119">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="57eaa-120">Corrigido um problema em que a Ferramenta de Implantação do Office não era chamada de “setup.exe” quando extraída</span><span class="sxs-lookup"><span data-stu-id="57eaa-120">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="57eaa-121">Corrigido um problema de priorização da fonte de instalação quando um atributo de canal é fornecido no XML de configuração</span><span class="sxs-lookup"><span data-stu-id="57eaa-121">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="57eaa-122">10 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-122">November 10, 2020</span></span>
<span data-ttu-id="57eaa-123">Versão 16.0.13328.20356 (setupODT.exe versão 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="57eaa-123">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="57eaa-124">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="57eaa-124">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="57eaa-125">Para evitar confusão e diagnosticar problemas de configuração com mais facilidade, a ODT agora é chamada de setupODT.exe por padrão</span><span class="sxs-lookup"><span data-stu-id="57eaa-125">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="57eaa-126">29 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-126">October 29, 2020</span></span>
<span data-ttu-id="57eaa-127">Versão 16.0.13328.20292 (Instalação.exe versão 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="57eaa-127">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="57eaa-128">Resolve um problema em que certos produtos do Office 2007 podem bloquear inesperadamente a instalação ao usar o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="57eaa-128">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="57eaa-129">14 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-129">October 14, 2020</span></span>
<span data-ttu-id="57eaa-130">Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="57eaa-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="57eaa-131">Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado</span><span class="sxs-lookup"><span data-stu-id="57eaa-131">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="57eaa-132">Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's</span><span class="sxs-lookup"><span data-stu-id="57eaa-132">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="57eaa-133">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="57eaa-133">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="57eaa-134">9 de junho de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-134">June 9, 2020</span></span>

<span data-ttu-id="57eaa-135">Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="57eaa-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="57eaa-136">O canal atual agora é o canal padrão quando um canal não é especificado</span><span class="sxs-lookup"><span data-stu-id="57eaa-136">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="57eaa-137">Suporte adicional ao Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="57eaa-137">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="57eaa-138">Suporte adicional para novos nomes de canal</span><span class="sxs-lookup"><span data-stu-id="57eaa-138">Added support for new channel names</span></span>
- <span data-ttu-id="57eaa-139">Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis</span><span class="sxs-lookup"><span data-stu-id="57eaa-139">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="57eaa-140">Recursos expandidos do MSIRemove para remover produtos do Office 2007</span><span class="sxs-lookup"><span data-stu-id="57eaa-140">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="57eaa-141">Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access</span><span class="sxs-lookup"><span data-stu-id="57eaa-141">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="57eaa-142">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-142">April 15, 2020</span></span>

<span data-ttu-id="57eaa-143">Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="57eaa-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="57eaa-144">Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7</span><span class="sxs-lookup"><span data-stu-id="57eaa-144">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="57eaa-145">Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado</span><span class="sxs-lookup"><span data-stu-id="57eaa-145">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="57eaa-146">Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente</span><span class="sxs-lookup"><span data-stu-id="57eaa-146">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="57eaa-147">16 de janeiro de 2020</span><span class="sxs-lookup"><span data-stu-id="57eaa-147">January 16, 2020</span></span>

<span data-ttu-id="57eaa-148">Versão 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="57eaa-148">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="57eaa-149">Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados</span><span class="sxs-lookup"><span data-stu-id="57eaa-149">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="57eaa-150">Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados</span><span class="sxs-lookup"><span data-stu-id="57eaa-150">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="57eaa-151">Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="57eaa-151">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="57eaa-152">31 de outubro de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-152">October 31, 2019</span></span>

<span data-ttu-id="57eaa-153">Versão 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="57eaa-153">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="57eaa-154">Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-154">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="57eaa-155">Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado</span><span class="sxs-lookup"><span data-stu-id="57eaa-155">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="57eaa-156">Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80</span><span class="sxs-lookup"><span data-stu-id="57eaa-156">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="57eaa-157">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-157">July 10, 2019</span></span>

<span data-ttu-id="57eaa-158">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="57eaa-158">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="57eaa-159">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="57eaa-159">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="57eaa-160">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="57eaa-160">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="57eaa-161">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-161">April 23, 2019</span></span>

<span data-ttu-id="57eaa-162">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="57eaa-162">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="57eaa-163">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="57eaa-163">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="57eaa-164">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="57eaa-164">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="57eaa-165">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-165">April 16 2019</span></span>

<span data-ttu-id="57eaa-166">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="57eaa-166">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="57eaa-167">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="57eaa-167">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="57eaa-168">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="57eaa-168">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="57eaa-169">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="57eaa-169">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="57eaa-170">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-170">March 13, 2019</span></span>

<span data-ttu-id="57eaa-171">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="57eaa-171">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="57eaa-172">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="57eaa-172">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="57eaa-173">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="57eaa-173">January 14, 2019</span></span>

<span data-ttu-id="57eaa-174">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="57eaa-174">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="57eaa-175">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="57eaa-175">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="57eaa-176">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="57eaa-176">Related links</span></span>

[<span data-ttu-id="57eaa-177">Centro de download da ODT</span><span class="sxs-lookup"><span data-stu-id="57eaa-177">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
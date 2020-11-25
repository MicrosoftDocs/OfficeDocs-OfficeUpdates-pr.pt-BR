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
ms.openlocfilehash: a1553a3f08a254c9c177fec88073073c34a3427c
ms.sourcegitcommit: 413694d561d367e93ad51c9be41495ad09a24af3
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/23/2020
ms.locfileid: "49385477"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="59bc9-103">Histórico do lançamento da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="59bc9-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="59bc9-104">A ODT (Ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões Clique para executar do Office, como o Microsoft 365 Apps, para os computadores cliente.</span><span class="sxs-lookup"><span data-stu-id="59bc9-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="59bc9-p101">A ODT dá mais controle sobre uma instalação do Office. Você pode definir quais produtos e idiomas são instalados, como esses produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários. Para saber mais sobre como usar a ODT, confira a [Visão geral da ferramenta de implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="59bc9-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="59bc9-108">O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="59bc9-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="59bc9-109">**Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="59bc9-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="59bc9-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="59bc9-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="november-23-2020"></a><span data-ttu-id="59bc9-111">23 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-111">November 23, 2020</span></span>
<span data-ttu-id="59bc9-112">Versão 16.0.13328.20420 (setup.exe versão 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="59bc9-112">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="59bc9-113">Corrigido um problema em que os revisores de texto não estavam sendo baixados pelo modo /download</span><span class="sxs-lookup"><span data-stu-id="59bc9-113">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="59bc9-114">Corrigido um problema em que o modo /download falhava ao ser executado em um contexto de usuário não elevado</span><span class="sxs-lookup"><span data-stu-id="59bc9-114">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="59bc9-115">Corrigido um problema em que a especificação de um atributo de Versão no XML de configuração resultava em um download incompleto no modo /download</span><span class="sxs-lookup"><span data-stu-id="59bc9-115">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="59bc9-116">Corrigido um problema em que a Ferramenta de Implantação do Office não era chamada de “setup.exe” quando extraída</span><span class="sxs-lookup"><span data-stu-id="59bc9-116">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="59bc9-117">Corrigido um problema de priorização da fonte de instalação quando um atributo de Canal é fornecido no XML de configuração</span><span class="sxs-lookup"><span data-stu-id="59bc9-117">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="59bc9-118">10 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-118">November 10, 2020</span></span>
<span data-ttu-id="59bc9-119">Versão 16.0.13328.20356 (setupODT.exe versão 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="59bc9-119">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="59bc9-120">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="59bc9-120">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="59bc9-121">Para evitar confusão e diagnosticar problemas de configuração com mais facilidade, a ODT agora é chamada de setupODT.exe por padrão</span><span class="sxs-lookup"><span data-stu-id="59bc9-121">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="59bc9-122">29 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-122">October 29, 2020</span></span>
<span data-ttu-id="59bc9-123">Versão 16.0.13328.20292 (Instalação.exe versão 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="59bc9-123">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="59bc9-124">Resolve um problema em que certos produtos do Office 2007 podem bloquear inesperadamente a instalação ao usar o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="59bc9-124">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="59bc9-125">14 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-125">October 14, 2020</span></span>
<span data-ttu-id="59bc9-126">Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="59bc9-126">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="59bc9-127">Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado</span><span class="sxs-lookup"><span data-stu-id="59bc9-127">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="59bc9-128">Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's</span><span class="sxs-lookup"><span data-stu-id="59bc9-128">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="59bc9-129">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="59bc9-129">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="59bc9-130">9 de junho de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-130">June 9, 2020</span></span>

<span data-ttu-id="59bc9-131">Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="59bc9-131">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="59bc9-132">O canal atual agora é o canal padrão quando um canal não é especificado</span><span class="sxs-lookup"><span data-stu-id="59bc9-132">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="59bc9-133">Suporte adicional ao Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="59bc9-133">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="59bc9-134">Suporte adicional para novos nomes de canal</span><span class="sxs-lookup"><span data-stu-id="59bc9-134">Added support for new channel names</span></span>
- <span data-ttu-id="59bc9-135">Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis</span><span class="sxs-lookup"><span data-stu-id="59bc9-135">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="59bc9-136">Recursos expandidos do MSIRemove para remover produtos do Office 2007</span><span class="sxs-lookup"><span data-stu-id="59bc9-136">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="59bc9-137">Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access</span><span class="sxs-lookup"><span data-stu-id="59bc9-137">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="59bc9-138">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-138">April 15, 2020</span></span>

<span data-ttu-id="59bc9-139">Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="59bc9-139">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="59bc9-140">Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7</span><span class="sxs-lookup"><span data-stu-id="59bc9-140">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="59bc9-141">Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado</span><span class="sxs-lookup"><span data-stu-id="59bc9-141">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="59bc9-142">Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente</span><span class="sxs-lookup"><span data-stu-id="59bc9-142">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="59bc9-143">16 de janeiro de 2020</span><span class="sxs-lookup"><span data-stu-id="59bc9-143">January 16, 2020</span></span>

<span data-ttu-id="59bc9-144">Versão 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="59bc9-144">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="59bc9-145">Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados</span><span class="sxs-lookup"><span data-stu-id="59bc9-145">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="59bc9-146">Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados</span><span class="sxs-lookup"><span data-stu-id="59bc9-146">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="59bc9-147">Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="59bc9-147">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="59bc9-148">31 de outubro de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-148">October 31, 2019</span></span>

<span data-ttu-id="59bc9-149">Versão 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="59bc9-149">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="59bc9-150">Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-150">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="59bc9-151">Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado</span><span class="sxs-lookup"><span data-stu-id="59bc9-151">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="59bc9-152">Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80</span><span class="sxs-lookup"><span data-stu-id="59bc9-152">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="59bc9-153">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-153">July 10, 2019</span></span>

<span data-ttu-id="59bc9-154">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="59bc9-154">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="59bc9-155">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="59bc9-155">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="59bc9-156">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="59bc9-156">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="59bc9-157">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-157">April 23, 2019</span></span>

<span data-ttu-id="59bc9-158">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="59bc9-158">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="59bc9-159">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="59bc9-159">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="59bc9-160">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="59bc9-160">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="59bc9-161">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-161">April 16 2019</span></span>

<span data-ttu-id="59bc9-162">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="59bc9-162">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="59bc9-163">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="59bc9-163">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="59bc9-164">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="59bc9-164">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="59bc9-165">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="59bc9-165">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="59bc9-166">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-166">March 13, 2019</span></span>

<span data-ttu-id="59bc9-167">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="59bc9-167">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="59bc9-168">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="59bc9-168">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="59bc9-169">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="59bc9-169">January 14, 2019</span></span>

<span data-ttu-id="59bc9-170">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="59bc9-170">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="59bc9-171">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="59bc9-171">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="59bc9-172">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="59bc9-172">Related links</span></span>

[<span data-ttu-id="59bc9-173">Centro de download da ODT</span><span class="sxs-lookup"><span data-stu-id="59bc9-173">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
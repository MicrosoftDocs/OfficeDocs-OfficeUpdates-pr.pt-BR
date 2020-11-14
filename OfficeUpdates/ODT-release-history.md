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
ms.openlocfilehash: acc7e37ae203c824c0759eab641491d377073a7f
ms.sourcegitcommit: 0cba381a1439abdc7044a81772609c91998d65f0
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/12/2020
ms.locfileid: "48999536"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="bb9c9-103">Histórico do lançamento da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="bb9c9-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="bb9c9-104">A ODT (Ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões Clique para executar do Office, como o Microsoft 365 Apps, para os computadores cliente.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="bb9c9-p101">A ODT dá mais controle sobre uma instalação do Office. Você pode definir quais produtos e idiomas são instalados, como esses produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários. Para saber mais sobre como usar a ODT, confira a [Visão geral da ferramenta de implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="bb9c9-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="bb9c9-108">O **Sistema Operacional com Suporte** : Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="bb9c9-109">**Instruções de Instalação** : Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setupodt.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="bb9c9-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setupodt.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="bb9c9-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="bb9c9-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="bb9c9-111">10 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="bb9c9-111">November 10, 2020</span></span>
<span data-ttu-id="bb9c9-112">Versão 16.0.13328.20356 (setupODT.exe versão 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="bb9c9-112">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="bb9c9-113">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="bb9c9-113">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="bb9c9-114">Para evitar confusão e diagnosticar problemas de configuração com mais facilidade, a ODT agora é chamada de setupODT.exe por padrão</span><span class="sxs-lookup"><span data-stu-id="bb9c9-114">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="bb9c9-115">29 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="bb9c9-115">October 29, 2020</span></span>
<span data-ttu-id="bb9c9-116">Versão 16.0.13328.20292 (Instalação.exe versão 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="bb9c9-116">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="bb9c9-117">Resolve um problema em que certos produtos do Office 2007 podem bloquear inesperadamente a instalação ao usar o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="bb9c9-117">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="bb9c9-118">14 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="bb9c9-118">October 14, 2020</span></span>
<span data-ttu-id="bb9c9-119">Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="bb9c9-119">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="bb9c9-120">Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado</span><span class="sxs-lookup"><span data-stu-id="bb9c9-120">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="bb9c9-121">Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's</span><span class="sxs-lookup"><span data-stu-id="bb9c9-121">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="bb9c9-122">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="bb9c9-122">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="bb9c9-123">9 de junho de 2020</span><span class="sxs-lookup"><span data-stu-id="bb9c9-123">June 9, 2020</span></span>

<span data-ttu-id="bb9c9-124">Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="bb9c9-124">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="bb9c9-125">O canal atual agora é o canal padrão quando um canal não é especificado</span><span class="sxs-lookup"><span data-stu-id="bb9c9-125">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="bb9c9-126">Suporte adicional ao Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="bb9c9-126">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="bb9c9-127">Suporte adicional para novos nomes de canal</span><span class="sxs-lookup"><span data-stu-id="bb9c9-127">Added support for new channel names</span></span>
- <span data-ttu-id="bb9c9-128">Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis</span><span class="sxs-lookup"><span data-stu-id="bb9c9-128">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="bb9c9-129">Recursos expandidos do MSIRemove para remover produtos do Office 2007</span><span class="sxs-lookup"><span data-stu-id="bb9c9-129">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="bb9c9-130">Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access</span><span class="sxs-lookup"><span data-stu-id="bb9c9-130">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="bb9c9-131">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="bb9c9-131">April 15, 2020</span></span>

<span data-ttu-id="bb9c9-132">Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="bb9c9-132">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="bb9c9-133">Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7</span><span class="sxs-lookup"><span data-stu-id="bb9c9-133">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="bb9c9-134">Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado</span><span class="sxs-lookup"><span data-stu-id="bb9c9-134">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="bb9c9-135">Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente</span><span class="sxs-lookup"><span data-stu-id="bb9c9-135">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="bb9c9-136">16 de janeiro de 2020</span><span class="sxs-lookup"><span data-stu-id="bb9c9-136">January 16, 2020</span></span>

<span data-ttu-id="bb9c9-137">Versão 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="bb9c9-137">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="bb9c9-138">Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados</span><span class="sxs-lookup"><span data-stu-id="bb9c9-138">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="bb9c9-139">Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados</span><span class="sxs-lookup"><span data-stu-id="bb9c9-139">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="bb9c9-140">Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="bb9c9-140">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="bb9c9-141">31 de outubro de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-141">October 31, 2019</span></span>

<span data-ttu-id="bb9c9-142">Versão 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="bb9c9-142">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="bb9c9-143">Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-143">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="bb9c9-144">Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado</span><span class="sxs-lookup"><span data-stu-id="bb9c9-144">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="bb9c9-145">Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80</span><span class="sxs-lookup"><span data-stu-id="bb9c9-145">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="bb9c9-146">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-146">July 10, 2019</span></span>

<span data-ttu-id="bb9c9-147">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="bb9c9-147">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="bb9c9-148">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-148">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="bb9c9-149">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-149">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="bb9c9-150">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-150">April 23, 2019</span></span>

<span data-ttu-id="bb9c9-151">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="bb9c9-151">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="bb9c9-152">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-152">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="bb9c9-153">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="bb9c9-153">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="bb9c9-154">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-154">April 16 2019</span></span>

<span data-ttu-id="bb9c9-155">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="bb9c9-155">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="bb9c9-156">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-156">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="bb9c9-157">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="bb9c9-157">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="bb9c9-158">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-158">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="bb9c9-159">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-159">March 13, 2019</span></span>

<span data-ttu-id="bb9c9-160">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="bb9c9-160">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="bb9c9-161">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-161">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="bb9c9-162">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="bb9c9-162">January 14, 2019</span></span>

<span data-ttu-id="bb9c9-163">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="bb9c9-163">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="bb9c9-164">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="bb9c9-164">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="bb9c9-165">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="bb9c9-165">Related links</span></span>

[<span data-ttu-id="bb9c9-166">Centro de download da ODT</span><span class="sxs-lookup"><span data-stu-id="bb9c9-166">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
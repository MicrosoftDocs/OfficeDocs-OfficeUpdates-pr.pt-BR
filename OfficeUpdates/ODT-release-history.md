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
ms.openlocfilehash: 4f65d41bfa18321a951fb18abcf919056bec7c5d
ms.sourcegitcommit: 57e715a8a3c0565b902cb3e6ca45d18a26f8ec45
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/15/2020
ms.locfileid: "48469990"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="abc86-103">Histórico do lançamento da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="abc86-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="abc86-104">A ODT (ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões clique para executar do Office, como os Aplicativos do Microsoft 365, para os computadores cliente.</span><span class="sxs-lookup"><span data-stu-id="abc86-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="abc86-105">A ODT dá mais controle sobre uma instalação do Office.</span><span class="sxs-lookup"><span data-stu-id="abc86-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="abc86-106">É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários.</span><span class="sxs-lookup"><span data-stu-id="abc86-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="abc86-107">Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="abc86-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="abc86-108">O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="abc86-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="abc86-109">**Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="abc86-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="abc86-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="abc86-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="abc86-111">14 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="abc86-111">October 14, 2020</span></span>
<span data-ttu-id="abc86-112">Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="abc86-112">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="abc86-113">Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado</span><span class="sxs-lookup"><span data-stu-id="abc86-113">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="abc86-114">Resolve um problema onde alguns produtos do Office 2007 podem bloquear inesperadamente a instalação ao utilizar o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="abc86-114">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>
- <span data-ttu-id="abc86-115">Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's</span><span class="sxs-lookup"><span data-stu-id="abc86-115">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="abc86-116">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="abc86-116">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="abc86-117">9 de junho de 2020</span><span class="sxs-lookup"><span data-stu-id="abc86-117">June 9, 2020</span></span>

<span data-ttu-id="abc86-118">Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="abc86-118">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="abc86-119">O canal atual agora é o canal padrão quando um canal não é especificado</span><span class="sxs-lookup"><span data-stu-id="abc86-119">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="abc86-120">Suporte adicional ao Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="abc86-120">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="abc86-121">Suporte adicional para novos nomes de canal</span><span class="sxs-lookup"><span data-stu-id="abc86-121">Added support for new channel names</span></span>
- <span data-ttu-id="abc86-122">Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis</span><span class="sxs-lookup"><span data-stu-id="abc86-122">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="abc86-123">Recursos expandidos do MSIRemove para remover produtos do Office 2007</span><span class="sxs-lookup"><span data-stu-id="abc86-123">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="abc86-124">Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access</span><span class="sxs-lookup"><span data-stu-id="abc86-124">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="abc86-125">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="abc86-125">April 15, 2020</span></span>

<span data-ttu-id="abc86-126">Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="abc86-126">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="abc86-127">Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7</span><span class="sxs-lookup"><span data-stu-id="abc86-127">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="abc86-128">Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado</span><span class="sxs-lookup"><span data-stu-id="abc86-128">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="abc86-129">Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente</span><span class="sxs-lookup"><span data-stu-id="abc86-129">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="abc86-130">16 de janeiro de 2020</span><span class="sxs-lookup"><span data-stu-id="abc86-130">January 16, 2020</span></span>

<span data-ttu-id="abc86-131">Versão 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="abc86-131">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="abc86-132">Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados</span><span class="sxs-lookup"><span data-stu-id="abc86-132">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="abc86-133">Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados</span><span class="sxs-lookup"><span data-stu-id="abc86-133">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="abc86-134">Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="abc86-134">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="abc86-135">31 de outubro de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-135">October 31, 2019</span></span>

<span data-ttu-id="abc86-136">Versão 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="abc86-136">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="abc86-137">Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-137">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="abc86-138">Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado</span><span class="sxs-lookup"><span data-stu-id="abc86-138">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="abc86-139">Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80</span><span class="sxs-lookup"><span data-stu-id="abc86-139">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="abc86-140">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-140">July 10, 2019</span></span>

<span data-ttu-id="abc86-141">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="abc86-141">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="abc86-142">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="abc86-142">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="abc86-143">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="abc86-143">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="abc86-144">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-144">April 23, 2019</span></span>

<span data-ttu-id="abc86-145">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="abc86-145">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="abc86-146">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="abc86-146">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="abc86-147">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="abc86-147">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="abc86-148">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-148">April 16 2019</span></span>

<span data-ttu-id="abc86-149">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="abc86-149">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="abc86-150">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="abc86-150">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="abc86-151">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="abc86-151">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="abc86-152">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="abc86-152">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="abc86-153">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-153">March 13, 2019</span></span>

<span data-ttu-id="abc86-154">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="abc86-154">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="abc86-155">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="abc86-155">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="abc86-156">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="abc86-156">January 14, 2019</span></span>

<span data-ttu-id="abc86-157">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="abc86-157">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="abc86-158">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="abc86-158">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="abc86-159">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="abc86-159">Related links</span></span>

[<span data-ttu-id="abc86-160">Centro de download da ODT</span><span class="sxs-lookup"><span data-stu-id="abc86-160">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
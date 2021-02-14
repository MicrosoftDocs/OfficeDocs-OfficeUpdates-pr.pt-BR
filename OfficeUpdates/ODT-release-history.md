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
ms.openlocfilehash: 1046a62a8440402e64bb25cb5ccf3dfbd84c894d
ms.sourcegitcommit: b015407aa6693d879f11025b40a7b45424753f99
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/10/2021
ms.locfileid: "50177943"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="b5637-103">Histórico do lançamento da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="b5637-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="b5637-104">A ODT (ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões clique para executar do Office, como os Aplicativos do Microsoft 365, para os computadores cliente.</span><span class="sxs-lookup"><span data-stu-id="b5637-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="b5637-105">A ODT dá mais controle sobre uma instalação do Office.</span><span class="sxs-lookup"><span data-stu-id="b5637-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="b5637-106">É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários.</span><span class="sxs-lookup"><span data-stu-id="b5637-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="b5637-107">Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="b5637-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="b5637-108">O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="b5637-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="b5637-109">**Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="b5637-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="b5637-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="b5637-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="february-9-2021"></a><span data-ttu-id="b5637-111">9 de fevereiro de 2021</span><span class="sxs-lookup"><span data-stu-id="b5637-111">February 9, 2021</span></span>
<span data-ttu-id="b5637-112">Versão 16.0.13628.20274 (setup.exe versão 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="b5637-112">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="b5637-113">Adicionada validação para avisar e impedir instalações sem suporte no Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="b5637-113">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="b5637-114">Correções de confiabilidade para dispositivos ARM64</span><span class="sxs-lookup"><span data-stu-id="b5637-114">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="b5637-115">12 de janeiro de 2021</span><span class="sxs-lookup"><span data-stu-id="b5637-115">January 12, 2021</span></span>
<span data-ttu-id="b5637-116">Versão 16.0.13530.20376 (configuração.exe versão 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="b5637-116">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="b5637-117">Corrigido um problema em que o registro do produto corrompido ou fora do padrão poderia causar falhas nas operações RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="b5637-117">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="b5637-118">21 de dezembro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-118">December 21, 2020</span></span>
<span data-ttu-id="b5637-119">Versão 16.0.13426.20370 (setup.exe versão 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="b5637-119">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="b5637-120">Corrigido um problema em que as instalações de origem local dos Revisores de Texto do canal PerpetualVL2019 estavam falhando</span><span class="sxs-lookup"><span data-stu-id="b5637-120">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="b5637-121">Corrigido um problema para garantir que o cliente Clique para Executar tente uma atualização automática ao adicionar produtos adicionais em idiomas que não estejam completos em uma instalação existente.</span><span class="sxs-lookup"><span data-stu-id="b5637-121">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="b5637-122">8 de dezembro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-122">December 8, 2020</span></span>
<span data-ttu-id="b5637-123">Versão 16.0.13426.20308 (setup.exe versão 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="b5637-123">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="b5637-124">Correção de um problema em que o modo de download estava bloqueando os downloads de canal de 2019 permanentes se o dispositivo tivesse um produto do Office instalado de um canal 2019 não-permanente.</span><span class="sxs-lookup"><span data-stu-id="b5637-124">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="b5637-125">Correção de um problema em que uma migração de arquitetura falharia em uma origem local criada por meio do modo de download que tenha especificado uma versão explícita no XML de configuração.</span><span class="sxs-lookup"><span data-stu-id="b5637-125">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="b5637-126">23 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-126">November 23, 2020</span></span>
<span data-ttu-id="b5637-127">Versão 16.0.13328.20420 (setup.exe versão 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="b5637-127">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="b5637-128">Corrigido um problema em que os revisores de texto não estavam sendo baixados pelo modo /download</span><span class="sxs-lookup"><span data-stu-id="b5637-128">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="b5637-129">Corrigido um problema em que o modo /download falhava ao ser executado em um contexto de usuário não elevado</span><span class="sxs-lookup"><span data-stu-id="b5637-129">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="b5637-130">Corrigido um problema em que a especificação de um atributo de Versão no XML de configuração resultava em um download incompleto no modo /download</span><span class="sxs-lookup"><span data-stu-id="b5637-130">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="b5637-131">Corrigido um problema em que a Ferramenta de Implantação do Office não era chamada de “setup.exe” quando extraída</span><span class="sxs-lookup"><span data-stu-id="b5637-131">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="b5637-132">Corrigido um problema de priorização da fonte de instalação quando um atributo de canal é fornecido no XML de configuração</span><span class="sxs-lookup"><span data-stu-id="b5637-132">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="b5637-133">10 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-133">November 10, 2020</span></span>
<span data-ttu-id="b5637-134">Versão 16.0.13328.20356 (setupODT.exe versão 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="b5637-134">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="b5637-135">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="b5637-135">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="b5637-136">Para evitar confusão e diagnosticar problemas de configuração com mais facilidade, a ODT agora é chamada de setupODT.exe por padrão</span><span class="sxs-lookup"><span data-stu-id="b5637-136">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="b5637-137">29 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-137">October 29, 2020</span></span>
<span data-ttu-id="b5637-138">Versão 16.0.13328.20292 (Instalação.exe versão 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="b5637-138">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="b5637-139">Resolve um problema em que certos produtos do Office 2007 podem bloquear inesperadamente a instalação ao usar o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="b5637-139">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="b5637-140">14 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-140">October 14, 2020</span></span>
<span data-ttu-id="b5637-141">Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="b5637-141">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="b5637-142">Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado</span><span class="sxs-lookup"><span data-stu-id="b5637-142">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="b5637-143">Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's</span><span class="sxs-lookup"><span data-stu-id="b5637-143">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="b5637-144">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="b5637-144">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="b5637-145">9 de junho de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-145">June 9, 2020</span></span>

<span data-ttu-id="b5637-146">Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="b5637-146">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="b5637-147">O canal atual agora é o canal padrão quando um canal não é especificado</span><span class="sxs-lookup"><span data-stu-id="b5637-147">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="b5637-148">Suporte adicional ao Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="b5637-148">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="b5637-149">Suporte adicional para novos nomes de canal</span><span class="sxs-lookup"><span data-stu-id="b5637-149">Added support for new channel names</span></span>
- <span data-ttu-id="b5637-150">Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis</span><span class="sxs-lookup"><span data-stu-id="b5637-150">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="b5637-151">Recursos expandidos do MSIRemove para remover produtos do Office 2007</span><span class="sxs-lookup"><span data-stu-id="b5637-151">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="b5637-152">Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access</span><span class="sxs-lookup"><span data-stu-id="b5637-152">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="b5637-153">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-153">April 15, 2020</span></span>

<span data-ttu-id="b5637-154">Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="b5637-154">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="b5637-155">Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7</span><span class="sxs-lookup"><span data-stu-id="b5637-155">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="b5637-156">Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado</span><span class="sxs-lookup"><span data-stu-id="b5637-156">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="b5637-157">Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente</span><span class="sxs-lookup"><span data-stu-id="b5637-157">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="b5637-158">16 de janeiro de 2020</span><span class="sxs-lookup"><span data-stu-id="b5637-158">January 16, 2020</span></span>

<span data-ttu-id="b5637-159">Versão 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="b5637-159">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="b5637-160">Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados</span><span class="sxs-lookup"><span data-stu-id="b5637-160">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="b5637-161">Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados</span><span class="sxs-lookup"><span data-stu-id="b5637-161">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="b5637-162">Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="b5637-162">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="b5637-163">31 de outubro de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-163">October 31, 2019</span></span>

<span data-ttu-id="b5637-164">Versão 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="b5637-164">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="b5637-165">Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-165">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="b5637-166">Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado</span><span class="sxs-lookup"><span data-stu-id="b5637-166">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="b5637-167">Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80</span><span class="sxs-lookup"><span data-stu-id="b5637-167">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="b5637-168">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-168">July 10, 2019</span></span>

<span data-ttu-id="b5637-169">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="b5637-169">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="b5637-170">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="b5637-170">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="b5637-171">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="b5637-171">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="b5637-172">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-172">April 23, 2019</span></span>

<span data-ttu-id="b5637-173">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="b5637-173">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="b5637-174">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="b5637-174">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="b5637-175">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="b5637-175">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="b5637-176">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-176">April 16 2019</span></span>

<span data-ttu-id="b5637-177">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="b5637-177">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="b5637-178">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="b5637-178">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="b5637-179">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="b5637-179">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="b5637-180">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="b5637-180">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="b5637-181">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-181">March 13, 2019</span></span>

<span data-ttu-id="b5637-182">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="b5637-182">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="b5637-183">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="b5637-183">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="b5637-184">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="b5637-184">January 14, 2019</span></span>

<span data-ttu-id="b5637-185">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="b5637-185">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="b5637-186">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="b5637-186">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="b5637-187">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="b5637-187">Related links</span></span>

[<span data-ttu-id="b5637-188">Centro de download da ODT</span><span class="sxs-lookup"><span data-stu-id="b5637-188">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
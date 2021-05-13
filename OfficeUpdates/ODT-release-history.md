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
ms.openlocfilehash: 16814bd8ef3b67f3ff4bab2f60627fbb65a37e03
ms.sourcegitcommit: 8841de32b2d66cec6c0b07e7bc87faab0248c019
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/11/2021
ms.locfileid: "52322461"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="0fa48-103">Histórico do lançamento da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="0fa48-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="0fa48-104">A ODT (ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões clique para executar do Office, como os Aplicativos do Microsoft 365, para os computadores cliente.</span><span class="sxs-lookup"><span data-stu-id="0fa48-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="0fa48-p101">A ODT dá mais controle sobre uma instalação do Office. Você pode definir quais produtos e idiomas são instalados, como esses produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários. Para saber mais sobre como usar a ODT, confira a [Visão geral da ferramenta de implantação do Office](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="0fa48-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="0fa48-108">O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="0fa48-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="0fa48-109">**Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="0fa48-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="0fa48-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="0fa48-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="may-10-2021"></a><span data-ttu-id="0fa48-111">10 de maio de 2021</span><span class="sxs-lookup"><span data-stu-id="0fa48-111">May 10, 2021</span></span>
<span data-ttu-id="0fa48-112">Versão 16.0.13929.20296 (setup.exe versão 16.0.13929.20238)</span><span class="sxs-lookup"><span data-stu-id="0fa48-112">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="0fa48-113">Corrigido um problema em que o /modo de configuração poderia falhar se um arquivo de configuração incluir o MigrateArch e o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="0fa48-113">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="0fa48-114">Melhorias adicionais de confiabilidade</span><span class="sxs-lookup"><span data-stu-id="0fa48-114">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="0fa48-115">13 de abril de 2021</span><span class="sxs-lookup"><span data-stu-id="0fa48-115">April 13, 2021</span></span>
<span data-ttu-id="0fa48-116">Versão 16.0.13901.20336 (setup.exe versão 16.0.13901.20328)</span><span class="sxs-lookup"><span data-stu-id="0fa48-116">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="0fa48-117">Correções de confiabilidade para configurar operações que são executadas em dispositivos com o Office já instalado</span><span class="sxs-lookup"><span data-stu-id="0fa48-117">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="0fa48-118">Correções para evitar a exibição da interface do usuário de andamento duplicado em alguns cenários</span><span class="sxs-lookup"><span data-stu-id="0fa48-118">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="0fa48-119">Aprimoramentos na precisão do código de erro mostrada na interface do usuário</span><span class="sxs-lookup"><span data-stu-id="0fa48-119">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="0fa48-120">Correções de confiabilidade para plataformas ARM</span><span class="sxs-lookup"><span data-stu-id="0fa48-120">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="0fa48-121">23 de março de 2021</span><span class="sxs-lookup"><span data-stu-id="0fa48-121">March 23, 2021</span></span>
<span data-ttu-id="0fa48-122">Versão 16.0.13801.20360 (setup.exe versão 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="0fa48-122">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="0fa48-123">Mudanças para oferecer suporte aos próximos lançamentos de produtos do Office</span><span class="sxs-lookup"><span data-stu-id="0fa48-123">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="0fa48-124">Correções de confiabilidade para plataformas ARM</span><span class="sxs-lookup"><span data-stu-id="0fa48-124">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="0fa48-125">25 de fevereiro de 2021</span><span class="sxs-lookup"><span data-stu-id="0fa48-125">February 25, 2021</span></span>
<span data-ttu-id="0fa48-126">Versão 16.0.13628.20476 (setup.exe versão 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="0fa48-126">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="0fa48-127">Corrigido um problema em que os arquivos configuration.xml que especificam vários idiomas não eram validados</span><span class="sxs-lookup"><span data-stu-id="0fa48-127">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="0fa48-128">Corrigido um problema em que a propriedade FORCEAPPSHUTDOWN não era respeitada em cenários MigrateArch</span><span class="sxs-lookup"><span data-stu-id="0fa48-128">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="0fa48-129">Corrigido um problema em que a especificação de dois ou mais atributos PIDKEY em configuration.xml falhou ao instalar os PIDKeys</span><span class="sxs-lookup"><span data-stu-id="0fa48-129">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="0fa48-130">9 de fevereiro de 2021</span><span class="sxs-lookup"><span data-stu-id="0fa48-130">February 9, 2021</span></span>
<span data-ttu-id="0fa48-131">Versão 16.0.13628.20274 (setup.exe versão 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="0fa48-131">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="0fa48-132">Adicionada validação para avisar e impedir instalações sem suporte no Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="0fa48-132">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="0fa48-133">Correções de confiabilidade para dispositivos ARM64</span><span class="sxs-lookup"><span data-stu-id="0fa48-133">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="0fa48-134">12 de janeiro de 2021</span><span class="sxs-lookup"><span data-stu-id="0fa48-134">January 12, 2021</span></span>
<span data-ttu-id="0fa48-135">Versão 16.0.13530.20376 (configuração.exe versão 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="0fa48-135">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="0fa48-136">Corrigido um problema em que o registro do produto corrompido ou fora do padrão poderia causar falhas nas operações RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="0fa48-136">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="0fa48-137">21 de dezembro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-137">December 21, 2020</span></span>
<span data-ttu-id="0fa48-138">Versão 16.0.13426.20370 (setup.exe versão 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="0fa48-138">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="0fa48-139">Corrigido um problema em que as instalações de origem local dos Revisores de Texto do canal PerpetualVL2019 estavam falhando</span><span class="sxs-lookup"><span data-stu-id="0fa48-139">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="0fa48-140">Corrigido um problema para garantir que o cliente Clique para Executar tente uma atualização automática ao adicionar produtos adicionais em idiomas que não estejam completos em uma instalação existente.</span><span class="sxs-lookup"><span data-stu-id="0fa48-140">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="0fa48-141">8 de dezembro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-141">December 8, 2020</span></span>
<span data-ttu-id="0fa48-142">Versão 16.0.13426.20308 (setup.exe versão 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="0fa48-142">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="0fa48-143">Correção de um problema em que o modo de download estava bloqueando os downloads de canal de 2019 permanentes se o dispositivo tivesse um produto do Office instalado de um canal 2019 não-permanente.</span><span class="sxs-lookup"><span data-stu-id="0fa48-143">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="0fa48-144">Correção de um problema em que uma migração de arquitetura falharia em uma origem local criada por meio do modo de download que tenha especificado uma versão explícita no XML de configuração.</span><span class="sxs-lookup"><span data-stu-id="0fa48-144">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="0fa48-145">23 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-145">November 23, 2020</span></span>
<span data-ttu-id="0fa48-146">Versão 16.0.13328.20420 (setup.exe versão 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="0fa48-146">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="0fa48-147">Corrigido um problema em que os revisores de texto não estavam sendo baixados pelo modo /download</span><span class="sxs-lookup"><span data-stu-id="0fa48-147">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="0fa48-148">Corrigido um problema em que o modo /download falhava ao ser executado em um contexto de usuário não elevado</span><span class="sxs-lookup"><span data-stu-id="0fa48-148">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="0fa48-149">Corrigido um problema em que a especificação de um atributo de Versão no XML de configuração resultava em um download incompleto no modo /download</span><span class="sxs-lookup"><span data-stu-id="0fa48-149">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="0fa48-150">Corrigido um problema em que a Ferramenta de Implantação do Office não era chamada de “setup.exe” quando extraída</span><span class="sxs-lookup"><span data-stu-id="0fa48-150">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="0fa48-151">Corrigido um problema de priorização da fonte de instalação quando um atributo de canal é fornecido no XML de configuração</span><span class="sxs-lookup"><span data-stu-id="0fa48-151">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="0fa48-152">10 de novembro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-152">November 10, 2020</span></span>
<span data-ttu-id="0fa48-153">Versão 16.0.13328.20356 (setupODT.exe versão 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="0fa48-153">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="0fa48-154">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="0fa48-154">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="0fa48-155">Para evitar confusão e diagnosticar problemas de configuração com mais facilidade, a ODT agora é chamada de setupODT.exe por padrão</span><span class="sxs-lookup"><span data-stu-id="0fa48-155">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="0fa48-156">29 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-156">October 29, 2020</span></span>
<span data-ttu-id="0fa48-157">Versão 16.0.13328.20292 (Instalação.exe versão 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="0fa48-157">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="0fa48-158">Resolve um problema em que certos produtos do Office 2007 podem bloquear inesperadamente a instalação ao usar o RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="0fa48-158">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="0fa48-159">14 de outubro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-159">October 14, 2020</span></span>
<span data-ttu-id="0fa48-160">Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="0fa48-160">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="0fa48-161">Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado</span><span class="sxs-lookup"><span data-stu-id="0fa48-161">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="0fa48-162">Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's</span><span class="sxs-lookup"><span data-stu-id="0fa48-162">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="0fa48-163">Melhoria da confiabilidade e da resiliência</span><span class="sxs-lookup"><span data-stu-id="0fa48-163">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="0fa48-164">9 de junho de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-164">June 9, 2020</span></span>

<span data-ttu-id="0fa48-165">Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="0fa48-165">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="0fa48-166">O canal atual agora é o canal padrão quando um canal não é especificado</span><span class="sxs-lookup"><span data-stu-id="0fa48-166">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="0fa48-167">Suporte adicional ao Canal Empresarial Mensal</span><span class="sxs-lookup"><span data-stu-id="0fa48-167">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="0fa48-168">Suporte adicional para novos nomes de canal</span><span class="sxs-lookup"><span data-stu-id="0fa48-168">Added support for new channel names</span></span>
- <span data-ttu-id="0fa48-169">Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis</span><span class="sxs-lookup"><span data-stu-id="0fa48-169">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="0fa48-170">Recursos expandidos do MSIRemove para remover produtos do Office 2007</span><span class="sxs-lookup"><span data-stu-id="0fa48-170">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="0fa48-171">Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access</span><span class="sxs-lookup"><span data-stu-id="0fa48-171">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="0fa48-172">15 de abril de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-172">April 15, 2020</span></span>

<span data-ttu-id="0fa48-173">Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="0fa48-173">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="0fa48-174">Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7</span><span class="sxs-lookup"><span data-stu-id="0fa48-174">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="0fa48-175">Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado</span><span class="sxs-lookup"><span data-stu-id="0fa48-175">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="0fa48-176">Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente</span><span class="sxs-lookup"><span data-stu-id="0fa48-176">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="0fa48-177">16 de janeiro de 2020</span><span class="sxs-lookup"><span data-stu-id="0fa48-177">January 16, 2020</span></span>

<span data-ttu-id="0fa48-178">Versão 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="0fa48-178">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="0fa48-179">Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados</span><span class="sxs-lookup"><span data-stu-id="0fa48-179">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="0fa48-180">Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados</span><span class="sxs-lookup"><span data-stu-id="0fa48-180">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="0fa48-181">Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](/deployoffice/microsoft-search-bing)</span><span class="sxs-lookup"><span data-stu-id="0fa48-181">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="0fa48-182">31 de outubro de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-182">October 31, 2019</span></span>

<span data-ttu-id="0fa48-183">Versão 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="0fa48-183">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="0fa48-184">Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-184">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="0fa48-185">Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado</span><span class="sxs-lookup"><span data-stu-id="0fa48-185">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="0fa48-186">Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80</span><span class="sxs-lookup"><span data-stu-id="0fa48-186">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="0fa48-187">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-187">July 10, 2019</span></span>

<span data-ttu-id="0fa48-188">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="0fa48-188">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="0fa48-189">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="0fa48-189">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="0fa48-190">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="0fa48-190">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="0fa48-191">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-191">April 23, 2019</span></span>

<span data-ttu-id="0fa48-192">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="0fa48-192">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="0fa48-193">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="0fa48-193">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="0fa48-194">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="0fa48-194">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="0fa48-195">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-195">April 16 2019</span></span>

<span data-ttu-id="0fa48-196">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="0fa48-196">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="0fa48-197">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="0fa48-197">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="0fa48-198">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="0fa48-198">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="0fa48-199">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="0fa48-199">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="0fa48-200">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-200">March 13, 2019</span></span>

<span data-ttu-id="0fa48-201">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="0fa48-201">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="0fa48-202">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="0fa48-202">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="0fa48-203">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="0fa48-203">January 14, 2019</span></span>

<span data-ttu-id="0fa48-204">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="0fa48-204">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="0fa48-205">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="0fa48-205">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="0fa48-206">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="0fa48-206">Related links</span></span>

[<span data-ttu-id="0fa48-207">Centro de download da ODT</span><span class="sxs-lookup"><span data-stu-id="0fa48-207">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
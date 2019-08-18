---
title: Histórico da versão da Ferramenta de Implantação do Office (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fornece aos Profissionais de TI um histórico da versão da Ferramenta de Implantação do Office (ODT)
ms.openlocfilehash: b0f53ad140880f7ef173efc544892d56f0658bb1
ms.sourcegitcommit: 917d87752cde322a74251b6d23b12815587d1e51
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/16/2019
ms.locfileid: "36444937"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="f1886-103">Histórico da versão da Ferramenta de Implantação do Office</span><span class="sxs-lookup"><span data-stu-id="f1886-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="f1886-104">A Ferramenta de Implantação do Office (ODT) é uma ferramenta de linha de comando que pode ser usada para baixar e implantar versões Clique para Executar do Office, como o Office 365 ProPlus, para os computadores clientes.</span><span class="sxs-lookup"><span data-stu-id="f1886-104">The Office 2016 Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Office 365 ProPlus to your client computers.</span></span> 


<span data-ttu-id="f1886-105">A ODT dá mais controle sobre uma instalação do Office.</span><span class="sxs-lookup"><span data-stu-id="f1886-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="f1886-106">É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários.</span><span class="sxs-lookup"><span data-stu-id="f1886-106">The ODT gives you more control over an Office installation: you can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="f1886-107">Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/pt-BR/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="f1886-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/en-us/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="f1886-108">\*\* Sistema Operacional com Suporte\*\*: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="f1886-108">The tool runs on Windows 10 , Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, and Windows Server 2012 R2.</span></span> 
 
 <span data-ttu-id="f1886-109">**Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="f1886-109">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="f1886-110">[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="f1886-110">Download the [Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="f1886-111">10 de julho de 2019</span><span class="sxs-lookup"><span data-stu-id="f1886-111">July 10, 2019</span></span>

<span data-ttu-id="f1886-112">Versão 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="f1886-112">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="f1886-113">Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="f1886-113">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="f1886-114">Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.</span><span class="sxs-lookup"><span data-stu-id="f1886-114">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="f1886-115">23 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="f1886-115">April 23, 2019</span></span>

<span data-ttu-id="f1886-116">Versão 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="f1886-116">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="f1886-117">Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.</span><span class="sxs-lookup"><span data-stu-id="f1886-117">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="f1886-118">Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="f1886-118">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="f1886-119">16 de abril de 2019</span><span class="sxs-lookup"><span data-stu-id="f1886-119">April 16, 2019</span></span>

<span data-ttu-id="f1886-120">Versão 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="f1886-120">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="f1886-121">Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="f1886-121">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="f1886-122">Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="f1886-122">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="f1886-123">MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.</span><span class="sxs-lookup"><span data-stu-id="f1886-123">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="f1886-124">13 de março de 2019</span><span class="sxs-lookup"><span data-stu-id="f1886-124">March 13, 2019</span></span>

<span data-ttu-id="f1886-125">Versão 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="f1886-125">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="f1886-126">Aperfeiçoamentos nos cenários de atualização e migração.</span><span class="sxs-lookup"><span data-stu-id="f1886-126">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="f1886-127">14 de janeiro de 2019</span><span class="sxs-lookup"><span data-stu-id="f1886-127">January 14, 2019</span></span>

<span data-ttu-id="f1886-128">Versão 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="f1886-128">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="f1886-129">Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.</span><span class="sxs-lookup"><span data-stu-id="f1886-129">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="f1886-130">Links relacionados</span><span class="sxs-lookup"><span data-stu-id="f1886-130">Related links</span></span>

[<span data-ttu-id="f1886-131">Notas de Versão da ODT</span><span class="sxs-lookup"><span data-stu-id="f1886-131">ODT Release notes</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
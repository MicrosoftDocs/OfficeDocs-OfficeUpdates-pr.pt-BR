---
title: Problemas conhecidos do Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Fornece informações sobre problemas conhecidos do Office 365 ProPlus
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068046"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="6857d-103">Problemas conhecidos do Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="6857d-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="6857d-104">Esses problemas conhecidos fornecem informações sobre atualizações não relacionadas à segurança incluídas nas atualizações do Canal Mensal, SACT e SAC para o Office 365 ProPlus 2019, Visio Pro para Office 365, Cliente de Área de Trabalho do Microsoft Project Online e Office 365 Business.</span><span class="sxs-lookup"><span data-stu-id="6857d-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="6857d-105">Esta tabela oferece um resumo dos problemas ativos atuais e dos que foram resolvidos.</span><span class="sxs-lookup"><span data-stu-id="6857d-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="6857d-106">Atualizaremos a tabela abaixo com problemas significativos que estamos investigando.</span><span class="sxs-lookup"><span data-stu-id="6857d-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="6857d-107">Esta lista não é abrangente.</span><span class="sxs-lookup"><span data-stu-id="6857d-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="6857d-108">Setembro de 2019</span><span class="sxs-lookup"><span data-stu-id="6857d-108">September 10, 2019</span></span>

|<span data-ttu-id="6857d-109">Resumo</span><span class="sxs-lookup"><span data-stu-id="6857d-109">Summary</span></span>|<span data-ttu-id="6857d-110">Investigando</span><span class="sxs-lookup"><span data-stu-id="6857d-110">Investigating</span></span>|<span data-ttu-id="6857d-111">Resolvido</span><span class="sxs-lookup"><span data-stu-id="6857d-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="6857d-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="6857d-112">**Outlook**</span></span>
<span data-ttu-id="6857d-113">Encontramos um problema que poderia impedir que os arquivos fossem salvos em um local WebDAV.</span><span class="sxs-lookup"><span data-stu-id="6857d-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="6857d-114">Versão mensal 1909</span><span class="sxs-lookup"><span data-stu-id="6857d-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="6857d-115">**Project**</span><span class="sxs-lookup"><span data-stu-id="6857d-115">**Project**</span></span>
<span data-ttu-id="6857d-116">Considere o seguinte cenário.</span><span class="sxs-lookup"><span data-stu-id="6857d-116">Consider the following scenario.</span></span> <span data-ttu-id="6857d-117">Você abre um projeto.</span><span class="sxs-lookup"><span data-stu-id="6857d-117">You open a project.</span></span> <span data-ttu-id="6857d-118">Você clica no menu Arquivo, clica em Exportar e clica no botão Criar PDF/XPS.</span><span class="sxs-lookup"><span data-stu-id="6857d-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="6857d-119">Na caixa de diálogo Procurar, digite um nome de arquivo e clique em OK.</span><span class="sxs-lookup"><span data-stu-id="6857d-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="6857d-120">Nesta situação, você descobre que o arquivo PDF do XPS não é criado.</span><span class="sxs-lookup"><span data-stu-id="6857d-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="6857d-121">Versão 1902 do SAC</span><span class="sxs-lookup"><span data-stu-id="6857d-121">SAC Version 1902</span></span>||
|<span data-ttu-id="6857d-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="6857d-122">**Word**</span></span>
<span data-ttu-id="6857d-123">Encontramos um problema que os usuários poderiam encontrar ao abrir um arquivo.</span><span class="sxs-lookup"><span data-stu-id="6857d-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="6857d-124">Versão mensal 1908</span><span class="sxs-lookup"><span data-stu-id="6857d-124">Monthly Version 1908</span></span>||
<span data-ttu-id="6857d-125">Para arquivos do Office sincronizados pelo Mecanismo de Sincronização do OneDrive, os metadados do documento, como Propriedades Necessárias e requisitos de Tipo de Conteúdo, não são mais validados ao Salvar e Salvar como.</span><span class="sxs-lookup"><span data-stu-id="6857d-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="6857d-126">Versão 1902 do SAC</span><span class="sxs-lookup"><span data-stu-id="6857d-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="6857d-127">Maio 2019 - EXEMPLO</span><span class="sxs-lookup"><span data-stu-id="6857d-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="6857d-128">Resumo</span><span class="sxs-lookup"><span data-stu-id="6857d-128">Summary</span></span>|<span data-ttu-id="6857d-129">Investigando</span><span class="sxs-lookup"><span data-stu-id="6857d-129">Investigating</span></span>|<span data-ttu-id="6857d-130">Resolvido</span><span class="sxs-lookup"><span data-stu-id="6857d-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="6857d-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="6857d-131">**Excel**</span></span>
<span data-ttu-id="6857d-132">Exemplo resolvido em várias compilações -- encontramos um problema que fazia com que os gráficos em cascata e em funil ficassem fora de sincronia com as tabelas quando as células eram inseridas ou excluídas.</span><span class="sxs-lookup"><span data-stu-id="6857d-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="6857d-133">Versão 1902 do SAC</span><span class="sxs-lookup"><span data-stu-id="6857d-133">SAC Version 1902</span></span> <br> <span data-ttu-id="6857d-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="6857d-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="6857d-135">Versão mensal 1905</span><span class="sxs-lookup"><span data-stu-id="6857d-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="6857d-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="6857d-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="6857d-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="6857d-137">**Word**</span></span>
<span data-ttu-id="6857d-138">Exemplo resolvido em alguns builds, não em todos -- Encontramos um problema de desempenho ao ativar as Partes Rápidas para as propriedades do documento.</span><span class="sxs-lookup"><span data-stu-id="6857d-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="6857d-139">Versão SAC 1808</span><span class="sxs-lookup"><span data-stu-id="6857d-139">SAC Version 1808</span></span>|<span data-ttu-id="6857d-140">Versão 1902 do SAC</span><span class="sxs-lookup"><span data-stu-id="6857d-140">SAC Version 1902</span></span> <br> <span data-ttu-id="6857d-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="6857d-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="6857d-142">Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="6857d-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

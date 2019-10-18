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
ms.openlocfilehash: 60706952efab5ec1379cbe260442b5865f599f28
ms.sourcegitcommit: 34571aa50b48a2111dee315f0ebf2e5f90cdf434
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/17/2019
ms.locfileid: "37574369"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conhecidos do Office 365 ProPlus

Esses problemas conhecidos fornecem informações sobre atualizações não relacionadas à segurança incluídas nas atualizações do Canal Mensal, SACT e SAC para o Office 365 ProPlus 2019, Visio Pro para Office 365, Cliente de Área de Trabalho do Microsoft Project Online e Office 365 Business.

Esta tabela oferece um resumo dos problemas ativos atuais e dos que foram resolvidos.  Atualizaremos a tabela abaixo com problemas significativos que estamos investigando.

> [!NOTE]
>- Esta lista não é abrangente.
>- Os problemas resolvidos também estão documentos em suas respectivas páginas de canal.

<br>

## <a name="october-2019"></a>Outubro de 2019

|Resumo|Aplicativos afetados|
|:-------------------------------------------------------------------------------------|:---------------------|
|Identificamos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item. <br><br> **Versão Resolvida**: <br> SACT Versão 1908  (16.0.11929.20396)|Excel<br><br>
|Identificado um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.<br><br> **Status**: Em investigação|Outlook<br><br>
|Identificado um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.<br><br> **Versão Resolvida**: <br>Versão Mensal 1909 (16.0.12026.20264) <br> SACT Versão 1908 (16.0.11929.20396)|PowerPoint<br><br>
|Identificamos um problema em que, em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização.  <br><br> **Status**: Em investigação|Pacote do Office<br><br>
|Foi identificado um problema em que os usuários podem não conseguir salvar documentos do Word, Excel e PowerPoint.  Esse problema afeta os usuários que criam um novo arquivo e exibe a opção “Salvar como Modelo de Caixa de Diálogo” depois de clicar no ícone Salvar ou pressionar Ctrl + S.<br><br> **Versão resolvida**: <br>Versão mensal 1909 (16.0.12026.20334) <br> Versão SACT 1908 (16.0.11929.20396)|Pacote do Office<br><br>
|

<br>
<br>

## <a name="september-2019"></a>Setembro de 2019

|Resumo|Aplicativos afetados|
|:-------------------------------------------------------------------------------------|:---------------------|
|Identificamos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas. <br><br> **Versão resolvida**: <br>Versão mensal 1909 (16.0.12026.20052) <br> SACT Versão 1908 (16.0.11929.20344) <br> SAC Versão 1902 (16.0.11328.20434)|Excel<br><br>
|Identificamos um problema no recurso ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32. <br><br> **Versão resolvida**: <br>SACT Versão 1908 (16.0.11929.20352) <br>|Excel<br><br>
|Identificamos um problema em que são exibidos somente 16 suplementos ao navegar no gerenciador de suplementos. <br><br>**Versão resolvida**: <br>Versão mensal 1909 (16.0.12026.20264) <br> SACT Versão 1908 (16.0.11929.20352) <br>|Excel<br><br>
|Identificamos um problema que poderia impedir que os arquivos fossem salvos em um local do WebDAV.<br><br>**Versão resolvida**: <br>Versão mensal 1909 16.0.12026.20264)|Outlook<br><br>
|Identificamos um problema que provocou falha na exibição de URLs de foco simples para alguns safelinks.<br><br>**Versão resolvida**: <br> SACT Versão 1908 (16.0.11929.20370)|Outlook<br><br>
|Identificamos um problema em que atualizações no anexo bloqueavam a lógica no Outlook para bloquear anexos python também.<br><br>**Versão resolvida**: <br>SACT Versão 1908 (16.0.11929.20370)|Outlook<br><br>
|Identificamos um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.<br><br>**Versão resolvida**: <br>SACT Versão 1908 (16.0.11929.20370)|Outlook<br><br>
|Identificamos um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.<br><br>**Versão resolvida**: <br>Versão mensal 1909 (16.0.12026.20264)<br>SACT Versão 1908 (16.0.11929.20370) |PowerPoint<br><br>
|Identificamos um problema durante a criação de um PDF/XPS no menu arquivo, o arquivo não foi criado.  <br><br>**Versão resolvida**: <br>SAC Versão 1908 (16.0.11328.20428)|Project<br><br>
|Identificamos um problema que os usuários poderiam encontrar ao abrir um arquivo.<br><br>**Versão resolvida**: <br>Versão mensal 1909 (16.0.12026.20264) <br> SACT Versão 1908 (16.0.11929.20340)|Word<br><br>
|Identificado um problema com arquivos do Office sincronizados pelo Mecanismo de Sincronização do OneDrive, os metadados do documento, como Propriedades Necessárias e requisitos de Tipo de Conteúdo, não são mais validados ao Salvar e Salvar como.<br><br>**Versão resolvida**: <br> Versão mensal 1906 (16.0.11727.20210)<br>SAC Versão 1902 (16.0.11328.20438)|Word<br><br>
|Identificamos um problema em que as versões atuais do JAWS no Windows não anunciam palavras ao usar Caps + Seta para a direita.<br><br>**Versão resolvida**: <br>Versão mensal 1904 (16.0.11601.20144)<br>SAC Versão 1902 (16.0.11328.20438)|Word<br><br>
|Identificamos um problema com o download de atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.<br><br>**Versão resolvida**: <br> SACT Versão 1908 (16.0.11929.20380)|Pacote do Office<br><br>
|Identificamos um problema em que a notificação “Corrigir minha conta” não desaparecia após o logon com êxito.<br><br>**Versão resolvida**: <br>SAC Versão 1902 (16.0.11328.20438)|Pacote do Office<br><br>
|


<br>
<br>

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).

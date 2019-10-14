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
ms.openlocfilehash: 6bfbf0f50b70334a09729177efbd3cd1c15f1e7b
ms.sourcegitcommit: f0366356e2da83813c99a59e9ce3e60338d11dcc
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/11/2019
ms.locfileid: "37453561"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conhecidos do Office 365 ProPlus

Esses problemas conhecidos fornecem informações sobre atualizações não relacionadas à segurança incluídas nas atualizações do Canal Mensal, SACT e SAC para o Office 365 ProPlus 2019, Visio Pro para Office 365, Cliente de Área de Trabalho do Microsoft Project Online e Office 365 Business.

Esta tabela oferece um resumo dos problemas ativos atuais e dos que foram resolvidos.  Atualizaremos a tabela abaixo com problemas significativos que estamos investigando.

 > [!NOTE]
 >- Esta lista não é abrangente.
 >- Os problemas resolvidos também estão documentos em suas respectivas páginas de canal.

<br>

## <a name="october-2019"></a>Outubro de 2019

|Resumo|Aplicativos afetados|Investigando|Resolvido|
|:-------------------------------------------------------------------------------------|:------------|:---------------------|:---------------------|
|
Encontramos um problema em Localizar e Substituir que alterou o local em que o foco estava no diálogo após encontrar o primeiro item.|Excel|SACT Versão 1908||
|
Encontramos um problema em que, em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização.|Pacote do Office|SACT Versão 1908||

<br>

## <a name="september-2019"></a>Setembro de 2019

|Resumo|Investigando|Solução esperada|Resolvido|
|:-------------------------------------------------------------------------------------|:------------|:---------------------|:---------------------|
|**Excel**
Descobrimos um problema que impede que os hiperlinks sejam colados em algumas planilhas protegidas.|||Versão mensal 1909 <br> (16.0.12026.20264) <br> SACT Versão 1908 <br> (16.0.11929.20344) <br> SAC Versão 1902 <br> (16.0.11328.20434)|
Encontramos um problema no recurso ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32.|||Versão Mensal 1909 <br> 16.0.12026.20264) <br> SACT Versão 1908<br>(16.0.11929.20352) <br> SAC Verions 1902 <br>(16.0.11328.20434)|
Encontramos um problema em que são exibidos somente 16 suplementos ao navegar no gerenciador de suplementos.||SAC Versão ?|Versão Mensal 1909 <br> (16.0.12026.20264) <br> SACT Versão 1908<br>(16.0.11929.20352)|
|**Outlook**
Encontramos um problema que poderia impedir que os arquivos fossem salvos em um local WebDAV.|||Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema que fazia com que as URLs de passagem simples não fossem exibidas para alguns links de segurança.|||Versão Mensal 1909 <br> (16.0.12026.20264)<br> SACT Versão 1908<br>(16.0.11929.20370)|
Encontramos um problema em que atualizações no anexo bloqueavam a lógica no Outlook para também bloquear anexos python.|||Versão mensal 1909 <br> (16.0.12026.20264)<br> SACT Versão 1908<br>(16.0.11929.20370)||
Corrigido um problema que fazia com que os usuários observassem um vazamento de memória no processo do Outlook.|||Versão mensal 1909 <br> (16.0.12026.20264)<br> SACT Versão 1908<br>(16.0.11929.20370)||
|**PowerPoint**
Encontramos um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.|||Versão mensal 1909 <br> (16.0.12026.20264) <br> SACT Versão 1908<br>(16.0.11929.20370)||
|**Project**
Encontramos um problema durante a criação de um PDF/XPS no menu arquivo. o arquivo não foi criado. |||SAC Versão 1908<br>(16.0.11328.20428)|
|**Word**
Encontramos um problema que os usuários poderiam encontrar ao abrir um arquivo.|||Versão mensal 1909 <br> (16.0.12026.20264) <br> SACT Versão 1908 <br> (16.0.11929.20340)||
Encontramos um problema com arquivos do Office sincronizados pelo Mecanismo de Sincronização do OneDrive, os metadados do documento, como Propriedades Necessárias e requisitos de Tipo de Conteúdo, não são mais validados ao Salvar e Salvar como.|||SAC Versão 1902 <br> (16.0.11328.20426)|
Encontramos um problema em que o JAWS em builds atuais do Windows não anuncia palavras ao usar Caps Lock + Seta para a direita.|||SAC Versão 1902 <br> (16.0.11328.20438)|
|**Pacote Office**
Encontramos um problema com o download de atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente. ||| Versão mensal 1909 <br> (16.0.12026.20264) <br> SACT Versão 1908<br> (16.0.11929.20380)|
Encontramos um problema em que a notificação "Corrigir minha conta" não desaparece após o login com êxito.|||SAC Versão 1902 (16.0.11328.20438)|

<br>
<br>

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).

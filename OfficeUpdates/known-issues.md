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
ms.openlocfilehash: 18082351f0ed6df9b50e5c1193adb2d85a2da40a
ms.sourcegitcommit: 01ac73d10be11b830776836c70d0a0efe4e7aafc
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/04/2019
ms.locfileid: "37391305"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conhecidos do Office 365 ProPlus

Esses problemas conhecidos fornecem informações sobre atualizações não relacionadas à segurança incluídas nas atualizações do Canal Mensal, SACT e SAC para o Office 365 ProPlus 2019, Visio Pro para Office 365, Cliente de Área de Trabalho do Microsoft Project Online e Office 365 Business.

Esta tabela oferece um resumo dos problemas ativos atuais e dos que foram resolvidos.  Atualizaremos a tabela abaixo com problemas significativos que estamos investigando.

 > [!NOTE]
 >- Esta lista não é abrangente.

<br>

## <a name="september-2019"></a>Setembro de 2019

|Resumo|Investigando|Resolvido|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
Descobrimos um problema que impede que os hiperlinks sejam colados em algumas planilhas protegidas.|SACT Versão 1908 <br> Versão 1902 do SAC|Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema no recurso ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32.||Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema em que são exibidos somente 16 suplementos ao navegar no Gerenciador de suplementos.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
|**Outlook**
Encontramos um problema que poderia impedir que os arquivos fossem salvos em um local WebDAV.||Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema que fazia com que as URLs de passagem simples não fossem exibidas para alguns links de segurança.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema em que atualizações no anexo bloqueavam a lógica no Outlook para também bloquear anexos python.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
Corrigido um problema que fazia com que os usuários observassem um vazamento de memória no processo do Outlook.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
|**PowerPoint**
Encontramos um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
|**Project**
Encontramos um problema durante a criação de um PDF/XPS no menu arquivo. o arquivo não foi criado. |Versão 1902 do SAC||
|**Word**
Encontramos um problema que os usuários poderiam encontrar ao abrir um arquivo.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema com arquivos do Office sincronizados pelo Mecanismo de Sincronização do OneDrive, os metadados do documento, como Propriedades Necessárias e requisitos de Tipo de Conteúdo, não são mais validados ao Salvar e Salvar como.|Versão 1902 do SAC||
Encontramos um problema em que o JAWS em builds do Windows 19H1 não anuncia palavras ao usar Caps + Seta para a direita.|Versão 1902 do SAC||
|**Pacote Office**
Substituição do SHA-1: para proteger a segurança do cliente do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)|
Encontramos um problema com o download de atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.|SACT Versão 1908|Versão mensal 1909 <br> (16.0.12026.20264)||
Encontramos um problema em que a notificação "Corrigir minha conta" não desaparece após o login com êxito.|Versão 1902 do SAC||



## <a name="may-2019---sample"></a>Maio 2019 - EXEMPLO

|Resumo|Investigando|Resolvido|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
Exemplo resolvido em várias compilações -- encontramos um problema que fazia com que os gráficos em cascata e em funil ficassem fora de sincronia com as tabelas quando as células eram inseridas ou excluídas.||Versão 1902 do SAC <br> (16.0.11328.20306) <br> Versão mensal 1905 <br> (16.0.11629.20210)|
|**Word**
Exemplo resolvido em alguns builds, não em todos -- Encontramos um problema de desempenho ao ativar as Partes Rápidas para as propriedades do documento.|Versão SAC 1808|SACT Versão 1902 <br> (16.0.11328.20340)|

<br>
<br>

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).

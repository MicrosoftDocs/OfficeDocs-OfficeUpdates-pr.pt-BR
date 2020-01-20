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
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230059"
---
# <a name="release-history-for-office-deployment-tool"></a>Histórico da versão da Ferramenta de Implantação do Office

A Ferramenta de Implantação do Office (ODT) é uma ferramenta de linha de comando que pode ser usada para baixar e implantar versões Clique para Executar do Office, como o Office 365 ProPlus, para os computadores clientes. 


A ODT dá mais controle sobre uma instalação do Office. É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários. Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).

 ** Sistema Operacional com Suporte**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2 
 
 **Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml). 

[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).


## <a name="january-16-2020"></a>16 de janeiro de 2020

Versão 16.0.12325.20288
- Corrige um problema em que a interface de usuário da instalação do Office pode ser exibida em um idioma incorreto quando vários idiomas são instalados
- Corrige um problema em que a instalação do Office pode falhar inesperadamente quando determinados pacotes de revisores de texto são instalados
- Adiciona suporte para controlar opcionalmente a implantação inicial do [recurso Pesquisa da Microsoft no Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)


## <a name="october-31-2019"></a>31 de outubro de 2019

Versão 16.0.12130.20272
- Correção de um problema para permitir a instalação do Skype for Business Basic 2019 com produtos com licenças perpétuas por volume empresarial de 2019
- Correção de um problema que pode causar falhas inesperadas no modo de download da ODT em determinadas circunstâncias quando um proxy é usado
- Novo recurso que permite que o modo de download da ODT seja baixado via HTTP usando uma porta diferente da porta 80


## <a name="july-10-2019"></a>10 de julho de 2019

Versão 16.0.11901.20022
- Adicionado suporte para produtos adicionais quando instalados com o Office 2019: Access Runtime, Skype for Business Basic.
- Adicionado suporte para a instalação condicional de produtos autônomos quando atualizados do MSI.

## <a name="april-23-2019"></a>23 de abril de 2019

Versão 16.0.11617.33601
- Corrigido um bug com RemoveMSI=True para limpar as configurações de registro relacionadas.
- Códigos de erro atualizados para fornecer detalhes adicionais para falhas inesperadas (E_UNEXPECTED).

## <a name="april-16-2019"></a>16 de abril de 2019

Versão 16.0.11615.33602
- Suporte para atualização de 32 bits C2R para 64 bits C2R com o novo atributo MigrateArch.
- Lógica atualizada para/configurar que permite acesso a arquivos XML de configuração armazenados em locais da Web (http e https).
- MatchInstalled adicionou como um novo atributo que permite que a ODT corresponda à versão existente ao adicionar outros produtos ou idiomas.

## <a name="march-13-2019"></a>13 de março de 2019

Versão 16.0.11509.33604
- Aperfeiçoamentos nos cenários de atualização e migração.

## <a name="january-14-2019"></a>14 de janeiro de 2019

Versão 16.0.11306.33602
- Aperfeiçoamentos de registro de log e telemetria para a configuração da implantação.


## <a name="related-links"></a>Links relacionados

[Centro de download da ODT](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
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
# <a name="release-history-for-office-deployment-tool"></a>Histórico do lançamento da Ferramenta de Implantação do Office

A ODT (ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões clique para executar do Office, como os Aplicativos do Microsoft 365, para os computadores cliente. 


A ODT dá mais controle sobre uma instalação do Office. É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários. Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).

 O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016. 
 
 **Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml). 

[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).

## <a name="october-14-2020"></a>14 de outubro de 2020
Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)
- Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado
- Resolve um problema onde alguns produtos do Office 2007 podem bloquear inesperadamente a instalação ao utilizar o RemoveMSI
- Maior segurança ao executar a ODT a partir de um diretório que contém outras DLL's
- Melhoria da confiabilidade e da resiliência

## <a name="june-9-2020"></a>9 de junho de 2020

Versão 16.0.12827.20268 (setup.exe versão 16.0.12827.20258)
- O canal atual agora é o canal padrão quando um canal não é especificado
- Suporte adicional ao Canal Empresarial Mensal
- Suporte adicional para novos nomes de canal
- Recursos adicionais de resiliência para continuar a instalar, se possível, mesmo quando alguns recursos de idioma estão indisponíveis
- Recursos expandidos do MSIRemove para remover produtos do Office 2007
- Recursos expandidos do MSIRemove para remover Mecanismo do Banco de Dados do Access 

## <a name="april-15-2020"></a>15 de abril de 2020

Versão 16.0.12624.20320 (setup.exe versão 16.0.12624.20290)
- Adiciona suporte para as versões do Office específicas para o fim da vida útil do Windows 7
- Corrige um problema em que as configurações de personalização poderiam não ser aplicadas conforme esperado
- Corrige um problema em que arquivos .cat incorretos poderiam ser baixados inesperadamente

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
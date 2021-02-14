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
# <a name="release-history-for-office-deployment-tool"></a>Histórico do lançamento da Ferramenta de Implantação do Office

A ODT (ferramenta de implantação do Office) é uma ferramenta de linha de comando que você pode usar para baixar e implantar versões clique para executar do Office, como os Aplicativos do Microsoft 365, para os computadores cliente. 


A ODT dá mais controle sobre uma instalação do Office. É possível definir quais produtos e idiomas são instalados, como os produtos devem ser atualizados e se deseja ou não exibir a experiência de instalação para os usuários. Para saber mais sobre como usar a ODT, confira [Visão geral da Ferramenta de Implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).

 O **Sistema Operacional com Suporte**: Windows 10, Windows 8.1, Windows Server 2019 ou Windows Server 2016. 
 
 **Instruções de Instalação**: Baixe e execute o arquivo executável de extração automática, que contém o executável da Ferramenta de Implantação do Office (setup.exe) e um arquivo de configuração de exemplo (configuration.xml). 

[Baixar a Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).

## <a name="february-9-2021"></a>9 de fevereiro de 2021
Versão 16.0.13628.20274 (setup.exe versão 16.0.13628.20246)
- Adicionada validação para avisar e impedir instalações sem suporte no Windows 8.0
- Correções de confiabilidade para dispositivos ARM64


## <a name="january-12-2021"></a>12 de janeiro de 2021
Versão 16.0.13530.20376 (configuração.exe versão 16.0.13530.20334)
- Corrigido um problema em que o registro do produto corrompido ou fora do padrão poderia causar falhas nas operações RemoveMSI

## <a name="december-21-2020"></a>21 de dezembro de 2020
Versão 16.0.13426.20370 (setup.exe versão 16.0.13426.20352)
- Corrigido um problema em que as instalações de origem local dos Revisores de Texto do canal PerpetualVL2019 estavam falhando
- Corrigido um problema para garantir que o cliente Clique para Executar tente uma atualização automática ao adicionar produtos adicionais em idiomas que não estejam completos em uma instalação existente.


## <a name="december-8-2020"></a>8 de dezembro de 2020
Versão 16.0.13426.20308 (setup.exe versão 16.0.13426.20308)
- Correção de um problema em que o modo de download estava bloqueando os downloads de canal de 2019 permanentes se o dispositivo tivesse um produto do Office instalado de um canal 2019 não-permanente.
- Correção de um problema em que uma migração de arquitetura falharia em uma origem local criada por meio do modo de download que tenha especificado uma versão explícita no XML de configuração.


## <a name="november-23-2020"></a>23 de novembro de 2020
Versão 16.0.13328.20420 (setup.exe versão 16.0.13328.20420)
- Corrigido um problema em que os revisores de texto não estavam sendo baixados pelo modo /download
- Corrigido um problema em que o modo /download falhava ao ser executado em um contexto de usuário não elevado
- Corrigido um problema em que a especificação de um atributo de Versão no XML de configuração resultava em um download incompleto no modo /download
- Corrigido um problema em que a Ferramenta de Implantação do Office não era chamada de “setup.exe” quando extraída
- Corrigido um problema de priorização da fonte de instalação quando um atributo de canal é fornecido no XML de configuração

## <a name="november-10-2020"></a>10 de novembro de 2020
Versão 16.0.13328.20356 (setupODT.exe versão 16.0.13328.20336)
- Melhoria da confiabilidade e da resiliência
- Para evitar confusão e diagnosticar problemas de configuração com mais facilidade, a ODT agora é chamada de setupODT.exe por padrão

## <a name="october-29-2020"></a>29 de outubro de 2020
Versão 16.0.13328.20292 (Instalação.exe versão 16.0.13328.20290)
- Resolve um problema em que certos produtos do Office 2007 podem bloquear inesperadamente a instalação ao usar o RemoveMSI

## <a name="october-14-2020"></a>14 de outubro de 2020
Versão 16.0.13231.20368 (setup.exe versão 16.0.13231.20350)
- Todos os produtos agora usarão o Canal Mensal por padrão quando nenhum canal for especificado
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
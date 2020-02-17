---
title: Notas de versão para lançamentos do Canal Semestral (Direcionado) em 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece notas de versão ao profissionais de TI para lançamentos do Canal Semestral (Direcionado) do Office 365 ProPlus em 2020
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978709"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>Notas de versão para lançamentos do Canal Semestral (Direcionado) em 2020

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionados à segurança incluídos nas atualizações do Canal Semestral (Direcionado) do Office 365 ProPlus em 2020, Visio Pro para Office 365, o cliente da Área de Trabalho do Project Online e o Office 365 Business. 

> [!NOTE]
>
> - Muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Semestral (direcionado) durante um período de tempo. Se você não encontrar imediatamente algo descrito abaixo, aguarde que muito em breve estará disponível. [Saiba mais](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - O Microsoft Teams está incluído nas novas instalações do Canal Semestral (Direcionado), começando com a Versão 1902. As equipes serão adicionadas às instalações existentes do Canal Semestral (Direcionado) quando elas forem atualizadas para a Versão 1908 ou posterior. Para obter mais informações, confira [Implantar o Microsoft Teams com Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

## <a name="version-1908-february-11"></a>Versão 1908: 11 de fevereiro
*Versão 1908 (Build 11929.20606)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/pt-BR/officeupdates/office365-proplus-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.

- Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.

- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.

- Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.


- Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.

- Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.


### <a name="outlook"></a>Outlook

- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.

- Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.

- Solucionado um problema que fazia com que os usuários experimentassem um travamento na tela Carregando perfil ao iniciar o Outlook.

- Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.


- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix. [Aqui](https://support.microsoft.com/pt-BR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.

- Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.


### <a name="powerpoint"></a>PowerPoint

- Melhorou um cenário de copiar e colar Copiando a Forma no slide do powerpoint e colando em outro slide em um loop poderia falhar, com exceção.


- Corrigido um problema que estava causando um desempenho mais lento entre os usuários da colaboração.

- Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.

- Corrigimos um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.

### <a name="project"></a>Project

- Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.

### <a name="word"></a>Word

- Corrigida uma falha no Word afastando-se de uma API reprovada.

### <a name="office-suite"></a>Pacote do Office

- Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a>Versão 1908:14 de janeiro
*Versão 1908 (Build 11929,20562)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- A dica de tecla holandesa para o título do documento foi alterada para Alt-G.

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

- Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.

### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.

- Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.

- Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.

### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema que poderia criar mestres ao copiar um slide de uma apresentação para outra.
- Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada

### <a name="office-suite"></a>Pacote Office

- Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado. Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.

- Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).
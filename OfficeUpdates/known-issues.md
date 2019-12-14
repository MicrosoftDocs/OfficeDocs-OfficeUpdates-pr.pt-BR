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
ms.openlocfilehash: 73cd91d43e09900d81418427dab1da01d89f227b
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023546"
---
# <a name="office-365-proplus-known-issues"></a>Problemas conhecidos do Office 365 ProPlus

Esses problemas conhecidos fornecem informações sobre atualizações não relacionadas à segurança incluídas nas atualizações do Canal Mensal, SACT e SAC para o Office 365 ProPlus 2019, Visio Pro para Office 365, Cliente de Área de Trabalho do Microsoft Project Online e Office 365 Business.

Esta tabela oferece um resumo dos problemas ativos atuais e dos que foram resolvidos.  Atualizaremos a tabela abaixo com problemas significativos que estamos investigando.

> [!NOTE]
>- Esta lista não é abrangente.
>- Se você tiver um problema em um canal diferente do canal mostrado como resolvido, poderá esperar a resolução em breve. [Saiba mais](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- Os problemas resolvidos também estão documentados em suas respectivas páginas de canal.

<br>

### <a name="last-updated-november-12-2019"></a>Última Atualização: 12 de novembro de 2019

### <a name="excel"></a>Excel

- Controles da caixa de seleção podiam diminuir ao usar o AutoAjuste para ajustar a altura da linha<br><br>**Investigando**: Mensal, SACT

- Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.<br><br>**Resolvido**: Versão SACT 1908 (11929.20436) 

- Os usuários poderiam ser impedidos de salvar no Office 365 formato de Pasta de Trabalho do Excel<br><br>**Resolvido**: Versão SACT 1908 (11929.20436)


- Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.<br><br>**Resolvido**: Versão SACT 1908 (11929.20436)

- Melhorias significativas no desempenho da exclusão de colunas com células mescladas<br><br>**Investigando**: SACT<br>**Resolvido**:  Versão Mensal 1910 (12130.20272)

- Resultados incorretos ao converter filtros de relatórios com o restante da tabela dinâmica para consultas a servidores de tabela SQL.<br><br>**Investigando**: Mensalmente 

- Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico<br><br>**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)


- Identificado um problema ao inserir arquivos como objeto no OneDrive.<br><br> **Resolvido**: Versão Mensal 1910 (12130.20272)

- Identificado um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam travar o Excel quando abertas nas versões atuais do Office.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436), Versão SAC 1902 (11328.20468)

- Identificado um problema que estava causando atrasos na exibição de valores digitados após a exclusão de um intervalo.<br><br>
**Resolvido**: Versão SAC 1902 (11328.20468)

- Identificado um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.<br><br>
**Investigando**: SACT <br>**Resolvido**: Versão Mensal 1910 (12130.20272)

- Identificado um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20300)

### <a name="outlook"></a>Outlook

- Identificado um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)

- Identificado um problema que poderia resultar em um vazamento de memória. <br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20388), Versão SAC 1902 (11328.20468)

- Corrigido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20436)

- Identificado um problema que às vezes poderia resultar em falha quando um usuário recebia uma mensagem de 'Conversa Perdida' do Skype.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272)

- Identificado um problema que fazia com que os Usuários recebessem um erro genérico “falha na operação” ao abrir um anexo em um computador em que o DisableBGSave estivesse habilitado.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20272)

- Identificado um problema com os links do CID: as imagens (imagens baseadas em email do Outlook) não podiam ser desfeitas.<br><br>
**Resolvido**: Versão SACT 1908 (11929.20436)

- Corrigido um problema que poderia ter causado uma mensagem de erro incorreta ao tentar enviar email criptografado s/MIME.<br><br>**Resolvido**: Versão Mensal 1910 (12130.20272)

### <a name="powerpoint"></a>PowerPoint

- Alguns caracteres katakana podem ser exibidos incorretamente em uma caixa de texto vertical.<br><br>
**Investigando**: Mensalmente 

- Corrigido um problema que impedia a criação de hiperlink ao colar texto com hiperlink. <br><br>**Resolvido**: Versão Mensal 1910 (12130.20272)

- Corrigido um problema que poderia causar a quebra de TextRanges após colar o texto nos espaços reservados de cabeçalho/rodapé/número de slide no slide mestre e no layout do slide. <br><br>**Resolvido**: Versão Mensal 1910 (12130.20272)

- Identificado um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.<br>
<br>**Resolvido**: Versão Mensal 1910 (12130.20272), Versão SACT 1908 (11929.20396), Versão SAC 1902 (11328.20468)

### <a name="project"></a>Project

- Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.<br><br>
**Investigando**: Mensalmente <br>
**Resolvido**: Versão SACT 1908 (11929.20436)

- As superalocações não são resolvidas por nivelamento<br><br>
**Investigando**: Mensalmente 

- Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.<br><br>
**Resolvido**: Versão Mensal 1910 (12130.20344), Versão SACT 1908 (11929.20436)

### <a name="word"></a>Word

- A pesquisa no painel Navegação pode falhar<br><br>
**Investigando**: Mensalmente 

- Identificado um problema ao inserir arquivos como objeto no OneDrive.<br><br> **Resolvido**: Versão Mensal 1910 (12130.20272)

### <a name="office-suite"></a>Pacote Office
- Tentar salvar um arquivo em um compartilhamento de rede desconectado podem ocasionar uma falha **Investigando**: Mensalmente 



<br>
<br>

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).

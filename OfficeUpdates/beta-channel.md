---
title: Notas de Versão para o Canal Beta
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece a lista mais recente de novos recursos, correções ou problemas conhecidos para o público-alvo do Insider − Modo Rápido.
ms.openlocfilehash: b28f6a4ec822d90c0b00ae1743d0f3a3dc84e7f4
ms.sourcegitcommit: 7970c58850bdb43dbfd159b661467afad6ebca7e
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/25/2020
ms.locfileid: "48276437"
---
# <a name="release-notes-for-beta-channel"></a>Notas de Versão para o Canal Beta

Este artigo contém notas de versão para compilações do Canal Beta para o Word, Excel, PowerPoint, Outlook, Access e Project para a área de trabalho do Windows. Toda semana, destacaremos novos recursos interessantes, correções importantes e quaisquer problemas significativos sobre os quais desejamos informá-lo. Em geral, disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Beta ao longo do tempo. Isso nos permite garantir que tudo esteja funcionando bem antes de liberarmos o recurso para um público maior. Portanto, caso você não veja algo descrito abaixo, não se preocupe.  

> [!IMPORTANT]
> Estamos fazendo algumas alterações nos canais de atualização para os Aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes. Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - As notas de versão são publicadas semanalmente e podem ser uma compilação de várias compilações.
> - A data de publicação das notas de versão pode não corresponder com a data de lançamento da compilação atual.

[//]: # (NÃO REMOVA)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

## <a name="version-2010-september-25"></a>Versão 2010: 25 de setembro
*Versão 2010 (Build 13318.20000)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Criar tipos de dados com o Power Query:** criar tipos de dados valiosos com o Power Query por meio de qualquer fonte de dados

### <a name="outlook"></a>Outlook

- **Atualizações da Experiência do Usuário para Tasks: ** Uma atualização visual dos itens de tarefa

- **Economizar tempo ao redigir mensagens:** Outlook mostra uma sugestão de escrita que ajuda você a redigir mensagens rapidamente. Para aceitar a sugestão, basta usar a tecla Tab.

### <a name="word"></a>Word

- **O painel do Editor Microsoft obtém uma atualização no Word para a área de trabalho:** Atualizamos a experiência atual com o painel do editor no Word para clientes de área de trabalho.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Consertamos um problema em que a posição da barra de rolagem não foi definida corretamente durante o carregamento da janela de consulta/relação salva enquanto é rolado.


- Consertamos um problema em que o painel de tarefas adicionar tabela não estava exibindo nomes contendo '&' corretamente.


### <a name="excel"></a>Excel

- Consertamos um problema em que o intervalo de várias categorias de vários níveis não estava funcionando em gráficos.


- Consertamos um problema que pode causar uma falha ao atualizar tabelas dinâmicas OLAP.


- Consertamos um problema em que a adição a uma tabela usada para a validação de dados não atualizou as opções de todas as planilhas na pasta de trabalho.


### <a name="onenote"></a>OneNote

- Consertamos um problema em que o OneNote não encontrou cores de alto contraste na tela para temas personalizados.


- Consertamos um problema ao passar o mouse sobre a cor verde no seletor de cores do bloco de anotações, os pop-ups lêem "giz vermelho".


### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que o gráfico vinculado do Excel se altera incorretamente para a planilha do Excel quando o usuário altera o caminho de origem para a pasta local do OneDrive.


### <a name="word"></a>Word

- Consertamos um problema em que os links para os arquivos habilitados para fluxo de trabalho não foram abertos conforme o esperado.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2010-september-18"></a>Versão 2010: 18 de setembro
*Versão 2010 (Build 13312.20006)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Revise suas mensagens com o Editor:** Agora, você pode obter sugestões de gramática e de outros estilos em seus emails para usuários do Outlook de 64 bits. Procure palavras sublinhadas para ver as sugestões do Editor para aprimorar sua redação.

- **Quebre a barreira do idioma com um tradutor interno:** Os suplementos para tradução não são mais necessários! Em uma mensagem, clique com o botão direito para traduzir palavras, frases específicas ou a mensagem inteira.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema com os Gráficos de Mapa 2D que não funcionavam ao usar o VBA para definir as cores dos valores como máximos, médios e mínimos de uma série.


- Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.


- Corrigido um problema que poderia causar um erro informando que o "Excel esgotou os recursos ao tentar calcular uma ou mais fórmulas".


- Corrigido um problema em que o ChartSheet falhava em alguns casos quando uma fórmula era inserida por meio da barra de fórmula.


### <a name="outlook"></a>Outlook

- Quando um usuário copiava e colava um endereço de email no campo do destinatário com o nome de exibição, o endereço de email nem sempre era analisado corretamente e fazia aparecer um aviso informando que um endereço de email era inválido.  Foi corrigido para que o nome e o endereço de email sejam analisados ​​corretamente, de forma que o aviso não seja mais mostrado.


### <a name="word"></a>Word

- Corrigido um problema em que mostrava um pop-out de comentário quando um usuário tocava em uma alteração controlada (inserção/exclusão).


- Corrigimos um problema com a exclusão de textos explicativos de comentários no Word.


- Corrigimos um problema no Outlook com a mensagem definida como Não encaminhar.


- Corrigimos um problema que ocorria ao salvar um documento do Word que continha citação e equação.



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DE BUGDETAILS)

## <a name="version-2010-september-11"></a>Versão 2010: 11 de setembro
*Versão 2010 (Build 13304.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="excel"></a>Excel

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="onenote"></a>OneNote

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="outlook"></a>Outlook

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="powerpoint"></a>PowerPoint

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="project"></a>Project

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="publisher"></a>Publisher

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="visio"></a>Visio

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

### <a name="word"></a>Word

- **O Office pode seguir a configuração de Modo Escuro do Windows 10:** usando o Windows 10 no Modo Escuro? Agora, o Office pode mudar de temas para corresponder automaticamente. Basta escolher "Usar configuração do sistema" como tema do Office.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Correção de um problema em que podia haver um atraso perceptível ao alternar entre planilhas com grandes quantidades de dados quando 'Visualização de quebra de página ' estava habilitada.

### <a name="outlook"></a>Outlook

- Consertamos um problema com emails sendo ocultados após a desativação da Caixa de Entrada Destaques e a realização de uma classificação.

### <a name="powerpoint"></a>PowerPoint

- Solucionamos um problema em que o GIF animava apenas uma vez no editor e nas apresentações de slides.

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2010-september-04"></a>Versão 2010: 04 de setembro
*Versão 2010 (Criação 13301.20004)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **E-mail de fixação:** Esse recurso ajuda os usuários a rastrearem os e-mails que precisam reenviar para você ou terem como um lembrete, mantendo-os no topo da lista de mensagens.

- **Receba sugestões por e-mail ao pesquisar por pessoa:** ao digitar os termos de pesquisa no Outlook, você receberá os e-mails mais relevantes apresentados nas sugestões.

- **Receba sugestões por e-mail ao pesquisar por pessoa:** ao digitar os termos de pesquisa no Outlook, você receberá os e-mails mais relevantes apresentados nas sugestões.

- **O Microsoft Editor recebe uma atualização dos clientes da área de trabalho do Word e do Outlook:** estamos introduzindo um novo modelo de clique para revisar das sugestões de ortografia, gramática e estilo avançado do Editor. Essa alteração também inclui uma nova superfície de cartão dedicado para revisar as sugestões.

### <a name="word"></a>Word

- **O Microsoft Editor recebe uma atualização dos clientes da área de trabalho do Word e do Outlook:** estamos introduzindo um novo modelo de clique para revisar das sugestões de ortografia, gramática e estilo avançado do Editor. Essa alteração também inclui uma nova superfície de cartão dedicado para revisar as sugestões.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Resolvemos um problema no qual, se você abrisse um arquivo contendo a função LET, ele exibiria o alerta: "Encontramos um problema de conteúdo no "seu arquivo.xlsx". Você quer que tentemos recuperar o máximo possível? Se você confiar na origem dessa pasta de trabalho, clique em Sim".
- Corrigimos um erro relacionado às referências de suplemento XLAM e intervalos nomeados.
- Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.
- Resolvemos um problema no qual, se um usuário aplicou um estilo personalizado a uma matriz dinâmica, ele receberá o erro: "Não é possível alterar partes de uma matriz". Essa era uma restrição herdada que foi removida.
- Resolvemos um problema no qual a barra de fórmulas do Excel não será processada completamente depois que a conexão com um dispositivo for perdida, como uma sessão remota conectar/desconectar ou uma alteração de monitor.

### <a name="outlook"></a>Outlook

- Resolvemos um problema que fornece mais flexibilidade para habilitar/desabilitar as opções de log padrão através da política de grupo.
- Resolvemos um problema no qual o Nome de domínio herdado de um remetente de e-mail foi preservado e exibido depois que um rascunho de e-mail foi movido entre as caixas de correio com permissões de assistente e permissões de gerente.
- Resolvemos um problema que fazia com que alguns usuários vissem o Outlook iniciar em um estado off-line até que eles optassem por trabalhar manualmente on-line.
- Resolvemos um problema em que a execução do código VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage"), depois de habilitar a Fita de Linha Única (SLR), resultaria em um erro de tempo de execução.
- Resolvemos um problema no qual as teclas "OK" e "Cancelar" no diálogo Respostas automáticas não seriam visíveis em um sistema com alta resolução (como 1750 x 1920) combinado com um grande tamanho de texto (como 175%).
- Resolvemos uma condição na qual enviar um pedido de reunião de um grupo de contato vazio para outro grupo de contato resultaria em um acidente.
- Resolvemos um problema que fazia com que os usuários experimentassem um erro ao selecionar determinados resultados de pesquisa.
- Resolvemos um problema no qual, se a política de grupo exigir um suplemento para ser sempre habilitada, o monitoramento do suplemento ficará indisponível para impedir que os usuários desabilitem o suplemento.

### <a name="powerpoint"></a>PowerPoint

- Resolvemos um problema em que os vídeos não eram automaticamente reproduzidos nas apresentações de slides.
- Resolvemos um problema no qual, depois de iniciar o PowerPoint, inserindo um slide e abrindo e fechando o painel de comentários, os slides no painel de miniaturas eram exibidos como sendo sobrepostos.

### <a name="project"></a>Project

- Resolvemos um problema no qual, se um recurso tiver várias tabelas de taxas de custo, talvez o custo restante não seja calculado corretamente.
- Resolvemos um problema no qual a Data de término do projeto não era atualizada nos projetos conectados à lista de tarefas do SharePoint.

### <a name="word"></a>Word

- Resolvemos um problema no qual o Cartão de comentários exibia uma borda ao redor do texto do comentário se o usuário clicava no mesmo.
- Resolvemos um problema no qual o foco não ia para o painel de comentários se o documento fosse ampliado para 160% ou mais e o painel de comentários não fosse visível.
- Resolvemos um problema no qual os comentários em um documento eram exibidos em outros documentos abertos depois da alteração entre os vários documentos abertos.
- Resolvemos um problema no qual, se um usuário criasse um rascunho de comentário ancorado em uma linha que já contivesse comentários confirmados, o rascunho era organizado na ordem errada em relação ao comentário comprometido no SideTrack.
- Resolvemos um problema no qual os links longos não eram dispostos ao salvar um documento no formato HTML.
- Resolvemos um problema no qual a macro AutoOpen era executada antes do AutoExec.

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2009-august-28"></a>Versão 2009: 28 de agosto
*Versão 2009 (Build 13219.20004)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Aborda um problema que provocou os usuários a enviarem conteúdo de email que tinha uma política "Não Encaminhar" aplicada ao OneNote ao selecionar mais de uma mensagem.

### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema em que a funcionalidade para inserir um vídeo foi desabilitada.

### <a name="word"></a>Word

- Corrigimos um problema em que o usuário não conseguisse sair do cabeçalho/rodapé ao selecionar um comentário.
- Corrigimos um problema que impedia que os usuários vissem os threads de comentário que excediam o limite sidetrack porque a rolagem por meio do sidetrack não estava funcionando.
- Corrigimos um problema em que a pesquisa por comentários resolvidos no painel sidetrack não estava funcionando.

### <a name="office-suite"></a>Pacote Office

- Corrigimos um problema na Ferramenta de Implantação do Office, em que a configuração estava falhando ao usar o recurso RemoveMSI com o produto do Office 2007 "Relatório de Erros do Aplicativo da Microsoft".
- Corrigimos um problema na caixa de diálogo Compactar imagem, onde algumas configurações DPI selecionadas pelo usuário não eram mantidas.

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2009-august-21"></a>Versão 2009: 21 de agosto
*Versão 2009 (Compilação 13212.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Caneta de Ação no Excel:** Ferramenta de caneta para ajudá-lo a escrever à mão e fazer edições rápidas em seus dados

### <a name="outlook"></a>Outlook

- **Excluir conversa pelo proprietário da mensagem:** Este recurso permite excluir uma conversa pelo proprietário da mensagem.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acesso

- Corrigimos um problema onde as conexões a um banco de dados ODBC não estavam funcionando com aplicações de terceiros.

### <a name="excel"></a>Excel

- Corrigimos um problema onde usando um macro para definir a propriedade FormulaR1C1 para um intervalo, as referências de células estariam incorretas se uma planilha de gráfico fosse a planilha ativa. 
- Corrigimos um problema em que a escrita à tinta poderia fazer com que o Excel não respondesse.

### <a name="outlook"></a>Outlook

- Corrigimos um problema onde os usuários podem agora desabilitar o IRM (Gerenciamento de Direitos de Informação) para o Outlook sem ter que desabilitá-lo para o resto das aplicações do Office.

### <a name="word"></a>Word

- Corrigimos um problema em que o Word podia falhar depois que os comentários fossem excluídos.
- Corrigimos um problema onde, em alguns casos, os marcadores não são exibidos corretamente no email.

[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-2009-august-14"></a>Versão 2009: 14 de agosto
*Versão 2009 (Compilação 13205.20000)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um problema onde se um usuário digitasse um nome de fórmula, incluindo o parêntese e invocasse ajuda via F1, o tópico da ajuda específico a essa fórmula não seria exibido.
- Corrigido um problema onde os macros atribuídos a botões eram quebrados após restaurar uma versão mais antiga do arquivo.

### <a name="outlook"></a>Outlook

- Esta alteração corrige um problema onde a página da Reunião continuaria a ser exibida depois que o usuário trocasse as guias da página de Reunião para a página do Assistente de Agendamento.

### <a name="word"></a>Word

- Corrigimos um problema onde o ícone da imagem com marcadores não era exibido corretamente.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2009-august-07"></a>Versão 2009: 07 de Agosto
*Versão 2009 (Build 13130.20000)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Consertamos um problema em que os atributos da conta do usuário do Active Directory para "otherTelephone" e "otherHomePhone" não estavam mapeados para os atributos LDAP do Outlook correspondente.

### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que os usuários estavam vendo a barra da faixa de opções/ título sendo exibida em determinadas condições.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-31"></a>Versão 2008: 31 de Julho
*Versão 2008 (Build 13127.20002)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office. Não é necessário converter.<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)

### <a name="outlook"></a>Outlook

- **Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office. Não é necessário converter.<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)

### <a name="powerpoint"></a>PowerPoint

- **Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office. Não é necessário converter.<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)

### <a name="word"></a>Word

- **Insira suas fotos do iPhone diretamente no Office:** Imagens HEIC do seu telefone agora são inseridas perfeitamente no Office. Não é necessário converter.<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/insert-apple-photos-into-office-easily)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acessar

- Esta correção resolve o problema de quando na tentativa de executar determinadas consultas tenha previamente produzido a mensagem de erro 'Consulta é muito complexa'.

### <a name="excel"></a>Excel

- Corrigimos um problema em que, se a ordem de uma série de gráficos tiver sido alterada, a caixa de seleção correspondente alinhada com a série não foi reordenada juntamente com a série.
- Corrigimos um problema em que uma cópia de uma imagem com um preenchimento de gradiente radial não correspondeu ao original.

### <a name="outlook"></a>Outlook

- Isto corrige um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não teve permissões de proprietário na mensagem que está sendo respondida.
- Esta correção resolve um problema que estava causando falha no Outlook ao exibir quebras de linha corretamente em conteúdo de markdown.

### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema em que uma cópia de uma imagem com um preenchimento de gradiente radial não correspondeu ao original.
- Corrigimos um problema em que o botão Formulários no PowerPoint não permitia a criação de Formulários quando o acesso ao Office Store não era permitido.

### <a name="project"></a>Project

- Corrigimos um problema em que, para uma lista de tarefas do SharePoint, os botões da faixa de opções na segunda guia podem ficar desabilitados.

### <a name="word"></a>Word

- Corrigimos um problema em que uma cópia de uma imagem com um preenchimento de gradiente radial não correspondeu ao original.
- Corrigimos um problema em que, se um comentário foi adicionado para acompanhar uma alteração, o painel revisões seria aberto inesperadamente.
- Corrigimos um problema em que os links para documentos não estavam sendo inseridos na caixa de comentários por meio de Inserir -> Link suspenso.
- Corrigimos um problema em que a contagem de hiperlinks na coleção de hyperlinks do VBA não foi iterada corretamente após a adição de uma imagem contendo um hiperlink.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-24"></a>Versão 2008: 24 de Julho
*Versão 2008 (Compilação 13117.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha. [Saiba mais](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="onenote"></a>OneNote

- Consertamos um problema em que o texto no espaço reservado da caixa de edição Pesquisar transbordaria se a janela do aplicativo fosse redimensionada a uma menor dimensão.

### <a name="word"></a>Word

- Consertamos um problema em que o texto no espaço reservado da caixa de edição Pesquisar transbordaria se a janela do aplicativo fosse redimensionada a uma menor dimensão.
- Consertamos um problema em que a opção 'Pessoas Específicas' para o Controlar Alterações era desabilitada.
- Consertamos um travamento ocasional ao abrir arquivos HTML.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-17"></a>Versão 2008: 17 de julho
*Versão 2008 (Compilação 13115.20000)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Consertamos um problema em que a qualquer momento em que um gráfico dinâmico com linhas de preenchimento ocultas era salvo e reaberto, as linhas de preenchimento se tornavam visíveis.

- Consertamos um problema em que os gráficos nem sempre eram atualizados conforme o esperado quando o ' ForceFullCalculation ' estava habilitado via VBA para a pasta de trabalho.

### <a name="outlook"></a>Outlook

- Resolvemos um problema em torno da criação de vários perfis no Outlook a partir do mesmo domínio de email.
- Resolve um problema que provocou a falha da exibição do ícone de bloqueio no cabeçalho de mensagens criptografadas S/MIME.
- Soluciona um problema que causou a remoção dos anexos de mensagens S/MIME quando enviadas sem criptografia.
- Corrige um problema que provocou mensagens de texto S/MIME sem formatação se tornarem truncadas ao enviar.
- Resolve um problema que causa a corrupção de um arquivo ao enviar um email S/MIME não criptografado.
- Soluciona um problema que fazia com que os usuários não conseguissem salvar anexos do OneDrive de fora de seu locatário em seu computador local ao selecionar a opção 'Salvar' na caixa de diálogo de segurança.
- Resolve um problema que fazia com que os destinatários não conseguirem salvar mensagens protegidas por direitos, mesmo quando a permissão para salvar era concedida pelo remetente.
- Corrige um problema que fazia com que as etiquetas de algumas opções de Pesquisa Avançada fossem truncadas em alguns idiomas.

### <a name="project"></a>Project

- Resolvemos um problema em que as tarefas listadas no modo de exibição Quadro de Tarefas não estavam sincronizadas com as do diálogo Atribuir Recursos.
- Corrigimos um problema no qual, se você copiasse e colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.

### <a name="word"></a>Word

- Consertamos um problema em que o comando 'Editor' era desabilitado quando o foco estava em uma caixa de texto de comentário.
- Resolvemos um problema em que o comando 'Mostrar Marcação' era desabilitado quando o foco estava em uma caixa de texto de comentário.
- Corrigimos um problema no XML personalizado no qual o estado dos comentários poderia ser perdido ao abrir o documento.

### <a name="office-suite"></a>Pacote Office

- Consertamos um problema em que, após o usuário abrir uma nova janela de aplicativo na barra de tarefas e criar um novo documento em branco, arquivos adicionais eram criados.
- Resolvemos um problema em que, se um usuário estava editando um documento mas teve permissões perdidas, não estávamos notificando sobre o usuário de que ele tinha que se autenticar novamente.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-july-10"></a>Versão 2008: 10 de julho
*Versão 2008 (Build 13102.20002)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Consertamos um problema em que a opção Permitir Encaminhamento estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, caso a pasta compartilhada Download não tivesse sido verificada.
- Consertamos um problema que exibia o botão imprimir em um estado desabilitado, mesmo que o usuário tivesse as permissões de impressão apropriadas.

### <a name="project"></a>Project

- Consertamos um problema no qual quando você tentava salvar um PDF/XPS do Project em uma biblioteca de documentos do SharePoint, nada acontecia.

### <a name="word"></a>Word

- Consertamos um problema em que o Word deixava de responder depois de colar um texto e uma imagem na caixa de comentários.
- Consertamos um problema em que o botão "Novo comentário" era desabilitado após a exclusão do último comentário.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-july-03"></a>Versão 2007: 03 de julho
*Versão 2007 (Build 13029.20006)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Crie pesquisas no Outlook com a Pesquisa Rápida:** Crie facilmente uma pesquisa, colete votos e exiba os resultados em um email [Saiba mais](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Novo localizador de sala:** Pesquisar salas de conferência por diferentes recursos.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Consertamos um problema em que as tabelas do modelo de dados criadas em determinadas versões do Excel não podiam ser vistas na 'Visualização de Tabela', embora a consulta associada à tabela não tivesse sido editada.
- Consertamos um problema em que a desabilitar "Ignorar referências Relativas/absolutas" na caixa de diálogo Definir Nome \ Aplicar Nomes fazia com que as fórmulas não funcionassem.
- Consertamos um problema em que a limpeza de um filtro de dados avançado podia ocasionar a perda da formatação da tabela.
- Consertamos um problema em que o caminho completo de um documento PDF inserido era mostrado na legenda do documento, em vez de apenas o nome do arquivo.
- Consertamos um problema em que depois de desabilitar o conector em nuvem Wolfram e, depois, salvar e abrir novamente uma pasta de trabalho do Excel, podia resultar em uma falha.
- Consertamos um problema em que a inicialização do Excel com o suplemento Solver habilitado resultava em uma falha.

### <a name="outlook"></a>Outlook

- Consertamos um problema em que o Outlook travava se houvesse mais de 130 destinatários na linha "Para" e também melhoramos o desempenho da renderização do texto.
- Consertamos um problema na barra "Tarefas Pendentes", no qual os eventos que se estendiam por mais de dois dias exibiam a mesma hora de término para todos os dias subsequentes.
- Consertamos um problema que fazia com que os usuários do Outlook vissem a lista de mensagens parar de responder por vários minutos após o uso de calendários compartilhados.

### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que colar HTML em uma área de texto em um slide resultava que fosse colado em uma caixa de texto criada na parte superior do slide.
- Consertamos um problema em que selecionar todos os slides no Modo de Exibição do Apresentador e, em seguida, sair do modo de exibição do Apresentador usando Alt+Tab e retornar à apresentação de slides e clicar em "Finalizar Apresentação" poderia resultar em uma exceção não tratada.

### <a name="project"></a>Project

- Consertamos um problema em que o Project pode falhar ao abrir determinados arquivos XML.
- Consertamos um problema em que você não conseguia abrir um arquivo do Project a partir de uma biblioteca de documentos do SharePoint se a biblioteca estivesse no modo moderno.
- Consertamos um problema em que os projetos não podiam ser abertos no cliente de área de trabalho do Project a partir do Project Web App, se a URL terminasse em '.com'.

### <a name="word"></a>Word

- Consertamos um problema durante o modo de coautoria quando há um conflito de mesclagem e o usuário já optou por descartar as alterações. Não mais exibimos a opção para salvar ou descartar alterações.
- Consertamos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, fazia com que o arquivo fosse salvo com a extensão .docx e com o nome de arquivo 'WRO0004.docx', independentemente do que o usuário inseriu, tornando o documento inutilizável.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-26"></a>Versão 2007: 26 de junho
*Versão 2007 (Build 13020.20004)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Consertamos um problema em que o gerenciador de tabelas vinculadas solicitava uma chave primária se uma tabela SQL vinculada tivesse sido atualizada.
- Consertamos um problema em que as consultas no Editor de Consultas rolavam para fora da área de visualização. 
- Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. 

### <a name="outlook"></a>Outlook

- Consertamos um problema em que os usuários não conseguiam 'Enviar Como' ou 'Enviar em nome' de uma lista de distribuição.
- Consertamos um problema em que inserir uma imagem embutida em uma mensagem e, em seguida, salvar a mensagem como um rascunho resultava em um redimensionamento da imagem.
- Consertamos um problema que fazia com que o corpo de uma mensagem de NDR mudasse de Unicode para ASCII após editar o assunto.

### <a name="project"></a>Project

- Consertamos um problema em que os links do Planner do Project na Nuvem da Comunidade Governamental haviam sido desabilitados.

### <a name="office-suite"></a>Pacote Office

- Consertamos um problema em que o texto inserido em um Elemento Gráfico Vetorial Escalonável (SVG) ficava ilegível após inseri-lo em um arquivo do Word, Excel ou PowerPoint, salvando e fechando o arquivo e reabrindo o arquivo.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-19"></a>Versão 2007: 19 de junho
*Versão 2007 (Build 13012.20000)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Consertamos um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar uma pasta de trabalho no SharePoint/OneDrive.
- Consertamos um problema em que as pastas de trabalho eram somente leitura quando o arquivo só era recomendável como somente leitura.

### <a name="outlook"></a>Outlook

- Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.
- Consertamos um problema que fazia com que os usuários vissem o seguinte erro ao fechar um compromisso que foi salvo anteriormente: "O item não pode ser salvo porque foi alterado por outro usuário ou em outra janela. Deseja fazer uma cópia na pasta padrão para o item?"
- Consertamos um problema em que as datas no Minicalendário falhavam ao exibir em negrito para os usuários no Japão.
- Consertamos um problema que impedia que lembretes de calendário mostrassem os horários exatos para reuniões que aconteceriam em menos de uma semana.

### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que o indicador de cor de presença de um usuário não era atualizado na galeria de coautoria durante uma sessão de coautoria em tempo real.

### <a name="project"></a>Project

- Consertamos um problema em que, se as tarefas de duração fixa estiverem em 100% concluídas, mas o término real não for especificado, a % concluída da tarefa exibia menos de 100%.

### <a name="word"></a>Word

- Consertamos um problema em que a cor do hiperlink HTML não estava sendo processada corretamente.

### <a name="office-suite"></a>Pacote Office

- Consertamos um problema em que URLs que não eram baseadas em http ou https não eram exibidas na lista de Mais Usados Recentemente.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-june-12"></a>Versão 2007: 12 de junho
*Versão 2007 (Build 13006.20002)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Obtenha Dados da Organização com o Power BI usando Tipos de Dados:** Os tipos de dados do Excel no Power BI agora estão sendo disponibilizados para os participantes do programa Office Insider em organizações com o Office 365 E5/A5 ou o Microsoft 365 E5/A5. Obter as informações necessárias e atualizá-las facilmente é fundamental para muitos fluxos de trabalho diários. Estamos oferecendo acesso às informações da sua empresa ou organização a partir do Power BI como tipo de dados no Excel, o amplia a capacidade de inserir informações vinculadas nas suas planilhas. [Saiba mais](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Consertamos um problema que fazia com que o Microsoft Access não conseguisse identificar uma Coluna de Identidade em uma tabela do Servidor SQL vinculada, o que poderia fazer com que as linhas fossem relatadas como excluídas incorretamente.

### <a name="excel"></a>Excel

- Consertamos um problema em que as linhas de grade principais de gráficos de radar não podiam ser formatadas corretamente.

### <a name="project"></a>Project

- Consertamos um problema em que o evento ProjectBeforeTaskChange não era acionado quando havia uma alteração na tarefa resumo do projeto ou no campo início/tarefa do projeto.
- Consertamos um problema em que uma redefinição de linha de base ou uma atualização poderia alterar os recursos de custo/trabalho e a linha de base poderia refletir valores de orçamento.

### <a name="word"></a>Word

- Consertamos um problema em que a capacidade de limpar a formatação dentro do Painel comentários por meio do botão Limpar Formatação na Faixa de Opções do Office não estava funcionando.
- Consertamos um problema em que alterar o tamanho de uma tabela quando a régua não é exibida fazia com que outros aplicativos executados em segundo plano começassem a piscar.
- Consertamos um problema em que, em modo de coautoria, as respostas a comentários, às vezes, não apareciam no painel comentários, mas ficavam visíveis no painel revisões.
- Consertamos um problema em que o Word tinha uma lista com mais de 50 documentos abertos com frequência e, depois que você salvava e abria um documento, um histórico de revisão era exibido, ainda que nenhuma revisão tivesse sido realizada no documento.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-june-05"></a>Versão 2006: 05 de junho
*Versão 2006 (Build 13001.20002)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Classificar/filtrar enquanto estiver colaborando no Excel:** Agora você pode classificar e filtrar o arquivo do Excel e colaborar com outras pessoas. Esse novo recurso impede que você seja afetado pelas classificações e filtros de outros usuários durante a coautoria do documento.

- **Crie Tabelas Dinâmicas a partir de Conjuntos de Dados no Power BI no Excel:** Você pode criar tabelas dinâmicas no Excel conectadas a conjuntos de dados armazenados no Power BI com alguns cliques. Isso permite que você obtenha o melhor das Tabelas Dinâmicas e do Power BI. Calcule, resuma e analise seus dados com Tabelas Dinâmicas a partir dos conjuntos de dados seguros do Power BI. [Saiba mais](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Reabra rapidamente os itens de uma sessão anterior:** Adicionamos a opção de reabrir rapidamente os itens de uma sessão anterior do Outlook. Se o Outlook falhar ou você fechá-lo, agora será possível reiniciar rapidamente os itens quando você reabrir o aplicativo. Esse recurso não está habilitado por padrão. Para desativá-lo, vá até Opções > Gerais > Opções de Inicialização.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Consertamos um problema em que os valores personalizados no eixo do gráfico não eram aplicados corretamente.
- Consertamos um problema em que as planilhas que continham várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.

### <a name="outlook"></a>Outlook

- Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.
- Consertamos um problema em que exibir um modelo ao redigir uma nova mensagem de email resultaria em uma falha.
- Resolvemos um problema em que os usuários não conseguiam acessar as pastas públicas do Exchange 2010 após a versão 1911 do Outlook.
- Consertamos um problema em que o botão Categorizar para calendários de grupo na Faixa de Opções do Office estava desabilitado.
- Consertamos um problema que fazia com que os usuários com contatos conflitantes experimentassem falhas no Outlook.
- Consertamos um problema que resultava na falta do menu suspenso Arquivo Online em propriedades da pasta para usuários em monitores de DPI alto.
- Consertamos um problema que fazia com que os usuários experimentassem uma falha no Outlook ao trabalhar com hiperlinks em emails de Texto sem Formatação.
- Consertamos um problema que fazia com que o Outlook fosse incapaz de analisar os nomes de arquivo longos codificados com o RFC2231.
- Consertamos um problema que estava fazendo com que os usuários do Outlook experimentassem travamentos intermitentes ao usar leitores de tela.

### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema com a abertura de arquivos configurados pelo servidor com autenticação baseada em formulários.
- Consertamos um problema em que os arquivos do PowerPoint com gráficos/pastas de trabalho inseridas poderiam resultar em falhas ao salvar o arquivo.
- Consertamos um problema em que um painel de Comentários fechado pelo usuário abria automaticamente.
- Consertamos um problema em que o editor de slide de um slide poderia se sobrepor ao próximo slide.

### <a name="project"></a>Project

- Consertamos um problema que impedia que tarefas órfãs fossem excluídas ou reatribuídas após o plano pai ser excluído.

### <a name="word"></a>Word

- Consertamos um problema em que os carimbos de data/hora nos painéis de Comentários não eram baseados no tempo de localidade do sistema.
- Consertamos um problema em que os comentários entre o aplicativo Web e o aplicativo da área de trabalho não estavam sincronizados.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version2006may29"></a>Versão 2006: 29 de maio
*Versão 2006 (Build 12920.20000)*

### <a name="featureupdates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Botões adicionais adicionados às notificações do sistema do Outlook:** Os botões de Ação Rápida agora aparecem nas notificações do Outlook ao executar o Outlook no Windows 10.

### <a name="powerpoint"></a>PowerPoint

- **Melhor desempenho de Streaming de vídeo no PowerPoint:** Fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável.  Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolvedissues"></a>Problemas resolvidos

### <a name="excel"></a>Excel

- Consertamos um problema em que o Excel era, ocasionalmente, encerrado ao iniciar o OneDrive.
- Consertamos um problema eu que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.
- Consertamos um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.
- Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.

### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que os slides não eram centralizados após o zoom usando a roda do mouse.

### <a name="word"></a>Word

- Consertamos um problema em que não era possível copiar e colar o texto em um painel de comentários.
- Consertamos um problema em que os balões de dicas de comentário apareciam borradas com zoom 100%.
- Resolvemos um problema em que a habilitação da política do Word 2007 e Documentos Binários e Templates posteriores causavam falha em alguns casos de coautoria.
- Consertamos um problema em que os arquivos com nomes de caminho longos (superiores a 32K) não abriam e uma mensagem de erro apropriada não estava sendo exibida.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>Versão 2006: 22 de maio
*Versão 2006 (Build 12914.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office. Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo. Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar. Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office. Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo. Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar. Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office. Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo. Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar. Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Consertamos um problema em que a mensagem de erro "Esta pasta de trabalho está, atualmente, referenciada por outro e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.
- Consertamos um problema em que a memória estava sendo corrompida durante o gerenciamento de fontes entre o Excel e alguns aplicativos de tecnologia adaptativa de terceiros.
- Consertamos um problema em que o Excel falhava quando os Suplementos pedem Itens de Host em planilhas que contêm formas com bloqueios não selecionados.

### <a name="outlook"></a>Outlook

- Consertamos um problema em que o evento Folder.BeforeItemMove não era acionado corretamente quando um usuário movia itens entre pastas.
- Consertamos um problema em que os usuários viam os itens de calendários que ultrapassavam o limite da meia-noite como Eventos de dia inteiro.
- Consertamos um problema em que o Outlook travava quando dois suplementos adicionavam um botão ao mesmo grupo na faixa de opções.
- Consertamos um problema em que os usuários não conseguiam compartilhar um calendário com um usuário convidado.

### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.

### <a name="project"></a>Project

- Consertamos um problema em que o Project falhava após clicar em Opções.

### <a name="word"></a>Word

- Consertamos um problema em que os hiperlinks nos comentários não estavam funcionando.
- Consertamos um problema em que aumentar e diminuir o zoom da área de apresentação resultavam em um espaço entre a marca de seleção ampliada e o ponteiro do mouse.
- Consertamos um problema em que a colagem de HTML no WordMail para o Calendário não estava funcionando.
- Consertamos um problema em que responder a um comentário em uma sessão de coautoria poderia fazer com que o Word congelasse.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-may-15"></a>Versão 2006: 15 de maio
*Versão 2006 (Build 12905.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Fazer uma conexão em PDF:** Conectar, importar, atualizar dados de um PDF. [Saiba mais](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a>Outlook

- **Encontre o que você precisa:** Restrinja sua pesquisa com opções como pasta, remetente, data, informações do anexo e muito mais.

### <a name="powerpoint"></a>PowerPoint

- **Não é preciso dar um clique: seus earbuds fazem isso por você** Use seu Surface Earbuds para controlar suas apresentações de PowerPoint. Importante: Você deve parear seu Surface Earbuds com o aplicativo Surface Audio para Windows 10 para usar gestos para controlar as apresentações. As instruções sobre como começar a usar o aplicativo de áudio Surface no Windows 10 estão disponíveis aqui. [Saiba mais](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a>Word

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel
- Consertamos um problema que resultou em um melhor tempo de desempenho para os usuários quando eles excluíam colunas mescladas.
- <div>Consertamos um problema que causava a duplicação de nomes de impressora na lista de impressoras disponíveis.</div>

### <a name="powerpoint"></a>PowerPoint
- Consertamos um problema em que os atalhos de teclado e a verificação ortográfica não funcionavam conforme o esperado ao usar um teclado QWERTZ.

### <a name="word"></a>Word
- Resolvemos um problema em que a adição de um novo comentário em um documento em branco não faria nada.
- Consertamos um problema em que inserir ou atualizar um índice em um documento que contém mais de cem entradas resultaria no travamento do aplicativo.
- Consertamos um problema em que os arquivos com valores XML personalizados abriam muito lentamente.

### <a name="office-suite"></a>Pacote Office
- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-may-08"></a>Versão 2006: 08 de maio
*Version 2006 (Build 12829.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

### <a name="outlook"></a>Outlook

- **Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca. [Saiba mais](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

### <a name="powerpoint"></a>PowerPoint

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos. [Saiba mais](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Investigamos e resolvemos o problema em que uma implantação do Office 365 ProPlus via InTune era pausada após um desligamento do sistema operacional.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-01"></a>Versão 2005: 1 de maio
*Version 2005 (Build 12827.20030)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Links aprimorados no email:** quando você incluir um link a um arquivo, o nome do arquivo substituirá a URL. Você pode alterar as permissões para que todos os destinatários tenham acesso. [Saiba mais](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um problema em que a tabela de dados do gráfico poderia processar incorretamente valores em um eixo de datas.
- Corrigimos um problema em que as quebras de página poderiam não ser desabilitadas após entrar no Layout da Página ou na Visualização da Quebra de Página.
- Corrigimos um problema em que os estilos de linha do gráfico poderiam ser perdidos após ocultar e reexibir colunas com dados de série.
- Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.
- Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".
- Corrigimos um problema em que a formatação personalizada em gráficos dinâmicos pode não ser salva quando a opção "inverter se negativo" estiver habilitada.
- Corrigimos um problema em que a formatação personalizada de um único ponto de dados em um Gráfico dinâmico não era salva se a opção "inverter se negativo" tivesse sido selecionada.
- Essa alteração corrige um problema em que o caractere ' @ ' carregado em um arquivo CSV resultaria na conversão da cadeia de caracteres após o caractere ' @ ' em uma fórmula.
- Corrigimos um problema em que os valores decimais na função SEQUÊNCIA não eram arredondados corretamente.

### <a name="outlook"></a>Outlook

- Soluciona um problema que causava falhas nos safelinks muito longos, nos quais os usuários clicavam no cliente do Outlook Desktop devido ao truncamento.
- Corrigimos um problema em que as pastas do Outlook com nomes que continham caracteres DBCS (conjunto de caracteres de dois bytes) poderiam desaparecer de forma intermitente ao sincronizar com o servidor. Para que isso aconteça, o Outlook tinha que ser configurado com uma conta IMAP e estar sendo executado em um sistema com a localidade definida como japonês.

### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema em que, se um usuário criasse um comentário sem postá-lo, fechasse o painel Comentários, abrisse uma nova janela, navegasse por vários slides, fechasse a janela e, por fim, reabrisse o painel Comentários na apresentação original, os comentários de rascunho não estariam disponíveis.

### <a name="project"></a>Project

- Corrigimos um problema em que, se o Project estivesse conectado ao Project Web App e o separador decimal fosse uma vírgula, o método Adicionar TaskDependencies falharia quando o retardo fosse adicionado.

### <a name="word"></a>Word

- Corrigimos um problema em que a inserção de comentários em um documento no modo de colaboração nem sempre funcionava.
- Essa alteração corrige um problema em que o cartão Pessoas piscava se o @ da menção estivesse selecionado.
- Corrigimos um problema em que o fechamento de um documento com comentários de rascunho perguntaria para o usuário se eles gostaria de fechar o documento sem salvar os comentários. Cancelar a solicitação fechava o documento, em vez de deixá-lo aberto.
- Corrigimos um problema em que a tradução de um comentário postado resultaria na mensagem de erro "ocorreu falha na inserção de texto traduzido".
- No leitor Exibição da Web/Imersivo, clicar em uma dica rolaria a tela para cima, mesmo que ele já estivesse em exibição. Isso foi corrigido.
- Corrigimos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, o arquivo poderia ser salvo com a extensão. docx e com o nome de arquivo WRO0004.docx, independentemente de qual nome o usuário inseriu, tornando o documento inutilizável.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2005-april-24"></a>Versão 2005: 24 de abril
*Versão 2005 (Build 12816.20006)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel
- Essa alteração corrige um problema em que o valor do R-quadrado da linha de tendência do gráfico (no caso de interceptação em y forçado) estava incorreto, mesmo que a função PROJ.LIN retorne o valor correto.
- Essa alteração corrige um problema em que a formatação personalizada da linha de tendência do gráfico nem sempre estava sendo salva.

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que o botão Categorizar de calendários de grupo na Faixa de Opções do Office estava desabilitado.
- Corrigimos um problema em que os clientes corporativos com pastas de grupo não implementadas ou que não funcionavam resultaria na exibição da mensagem “não respondendo” no Outlook.

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema em que passar o mouse sobre o símbolo de asterisco (*) não exibia o nome de usuário e a data da última pessoa a atualizar o documento.

### <a name="word"></a>Word
- Habilitar a opção "Mostrar indicadores" não exibia os indicadores. Isso foi corrigido.
- Essa alteração corrige um problema em que o texto com hiperlinks pode não ser exibido se a opção "Mostrar códigos de campo em vez de seus valores" estiver habilitada.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)


## <a name="version-2005-april-17"></a>Versão 2005: 17 de abril
*Versão 2005 (Build 12810.20002)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel
- Foi aumentado o tamanho dos controles de edição de referência de célula na caixa de diálogo Barras de Erros Personalizadas usada com gráficos.
- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.
- Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.
- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.
- Essa alteração corrige um problema em que as informações de formatação condicional (CF) não estavam sendo salvas nos arquivos XLSB corretamente.

### <a name="onenote"></a>OneNote
- Foi corrigido um problema em que as quebras de linha estavam sendo armazenadas como guias verticais.

### <a name="outlook"></a>Outlook
- Resolve um problema que fazia com que os usuários não pudessem adicionar um Grupo de Contatos Pessoais como participante da reunião.
- Resolve um problema que fazia com que o assunto de reuniões a mais de 2 meses da data prevista não fosse exibido no Assistente de Agendamento.
- Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.
- Foi adicionada a capacidade de impor a configuração de assinatura padrão S/MIME pela política de grupo.
- Resolve um problema que tornava inválidas as regras de exclusão criadas para caixas de correio diferentes da caixa de correio principal do usuário.
- Resolve um problema que fazia com que os anexos fossem descartados ao encaminhar uma mensagem criptografada.

### <a name="project"></a>Project
- Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.
- Corrigimos um problema em que o Project podia falhar ao alterar o campo de status do quadro em um projeto conectado a uma lista de tarefas do Microsoft Office SharePoint Online.
- Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


## <a name="version-2004-april-10"></a>Versão 2004: 10 de abril
*Versão 2004 (Build 12730.20024)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Acessar

- **Ignore a caixa de diálogo Mostrar Tabela, vá diretamente para um painel de tarefas e simplifique a adição de tabelas a relacionamentos e consultas:** Adicione tabelas e consultas clicando em quatro guias, selecionando vários nomes, pesquisando por texto e arrastando de um painel de tarefas que permanece aberto enquanto você trabalha.

### <a name="excel"></a>Excel

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Mantenha suas fotos em alta definição ao enviá-las como parte de um email:** Uma nova configuração do Outlook está disponível para limitar a compactação de imagem quando você envia fotos como parte do conteúdo de emails

### <a name="powerpoint"></a>PowerPoint

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.

### <a name="word"></a>Word

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Faça anotações na sua cópia particular:** crie anotações redigidas à mão para você mesmo, fazendo uma cópia privada de um documento compartilhado. Vá para Exibir > Criar uma cópia privada para começar.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acessar

- Foram corrigidos problemas com o redimensionamento e a atualização de tabelas no painel de tarefas.

### <a name="excel"></a>Excel

- Foi corrigido um problema em que a seleção de um intervalo de células em uma planilha resultava na seleção de uma única célula.

- Foi corrigido um problema que podia fazer o Excel parar de responder quando se reduzia o tamanho de um gráfico com alguns intervalos de eixo x.

- Foi corrigido um problema em que a inserção de um modelo de gráfico definido pelo usuário poderia resultar no salvamento dele como um gráfico de colunas.

- Foi corrigido um problema em que os rótulos de Dados de gráficos eram exibidos como em branco quando as células de dados subjacentes não possuíam uma legenda.

- Foi corrigido um problema em que, em uma planilha do Excel com referência de célula L1C1 habilitada que estivesse sendo criada em coautoria/compartilhada, passar o mouse sobre o ícone de presença do usuário não exibia a referência de célula ativa no modo L1C1.

### <a name="outlook"></a>Outlook

- Resolve um problema que fazia as categorias desaparecerem ocasionalmente das mensagens de email.

- Resolve um problema que fazia com que os representantes vissem diferentes hierarquias de pastas em computadores diferentes para caixas de correio compartilhadas.

- Resolve um problema que fazia com que os usuários experimentassem uma falha ao tentar exibir as propriedades de um Formulário Organizacional.

- Resolve um problema que fazia com que alguns lembretes falhassem ao alterar o fuso horário em um computador.

### <a name="powerpoint"></a>PowerPoint

- Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.

- Corrigimos um problema em que copiar texto do Excel para o PowerPoint poderia alterar a formatação.

- Essa alteração corrige um problema em que encontrar caracteres especiais usando "localizar somente palavras inteiras" nem sempre funcionava como esperado.

### <a name="project"></a>Project

- Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.

### <a name="word"></a>Word

- Essa alteração corrige um problema em que passar o cursor do mouse sobre uma dica não realçava o seu cartão.

- Essa alteração corrige um problema que fazia com que o texto em formas agrupadas desaparecesse temporariamente ao usar a ferramenta Seleção de laço.

- Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.

- Essa alteração corrige um problema no modo de exibição de duas páginas em que, ao criar um comentário, a âncora de comentário nem sempre chegava a ser exibida.

- Corrigido um problema em que, para um parágrafo cujo estilo é um ancestral de um estilo vinculado a uma lista, a numeração dessa lista poderia ser perdida.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-27"></a>Versão 2004: 27 de março
*Versão 2004 (Build 12718.20010)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Nova opção para desabilitar sugestões de @menções ao redigir emails:** você acha o seletor de @menções mais irritante do que útil? Agora, você pode desativá-lo, se preferir.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook
- Corrige um problema que fazia com que o botão “Salvar na nuvem” não aparecesse nas Ferramentas de Anexo.
- Corrige um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não tem permissão de proprietário na mensagem que está sendo respondida.
- Corrige um problema que fazia com que os usuários não conseguissem adicionar anexos adicionais de um local da Web a uma reunião criada anteriormente.

### <a name="powerpoint"></a>PowerPoint
- Essa alteração corrige um erro que poderia fazer com que arquivos do PowerPoint com emojis falhassem ao salvar.

### <a name="project"></a>Project
- Correção de um problema em que, se ‘CustomFieldValueListGetItem’ fosse executado e uma tabela de pesquisa do campo personalizado não existisse, uma tabela de pesquisa vazia era criada, mesmo que não devesse ser.

### <a name="word"></a>Word
- Essa alteração corrige um problema em várias páginas selecionadas no menu Exibir, onde o painel de comentários poderia ser exibido em branco.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-20"></a>Versão 2004: 20 de março
*Versão 2004 (Build 12711.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Atualização visual de calendário:** ano passado, trouxemos uma experiência de email atualizada e, esse ano, é a vez do calendário ser transformado! As atualizações são novas, mas familiarmente, como um usuário experiente do Outlook, você pode entrar e ser mais produtivo imediatamente.

- **Ajude a proteger os dados de seu grupo:** o rótulo de sensibilidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe

### <a name="powerpoint"></a>PowerPoint

- **Atualizar slides durante a apresentação de slides:** os slides de atualização alterados por outros autores durante a sua apresentação.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.

### <a name="outlook"></a>Outlook

- Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.

- Essa alteração corrige um problema em que as últimas alterações em rascunhos de emails não foram atualizadas.

- Correção de um problema em que clicar com o botão direito do mouse em um arquivo e usar ' enviar para ' não funcionará.

- Correção de um problema em que o usuário tinha um caminho de pesquisa personalizado para o catálogo de endereços, o escopo de resolução de nome do Outlook seria limitado ao caminho personalizado, em vez de incluir a lista de endereços global (GAL).

- Correção de um problema em que, em um conjunto de resultados de pesquisa retornados, classificar os resultados por categorias, não exibiria as cores da categoria.

### <a name="project"></a>Projeto

- Correção de um problema em que o evento de "ProjectBeforeTaskChange ' aplicativos Visual Basic (VBA) não foi disparado quando um usuário clica no botão" inativo "encontrado na faixa de opções tarefas no agrupamento de agendamento.

- Se você definir os detalhes da predecessora ou da sucessora de dentro de um modo de exibição de tipo de formulário, o evento ProjectBeforeTaskChange Visual Basic Applications (VBA) não capturaria as alterações. Por exemplo, se você excluiu uma dependência e clicou em OK no formulário, o evento não foi acionado. Esse problema foi corrigido.

- Correção de um problema em que os valores mais recentes para o custo real do trabalho realizado (CRTR) não seriam exibidos depois de fazer uma alteração, como uma alteração de data.

- Correção de um problema em que abrir um projeto usando o menu mais recentemente utilizado (MRU) abriu o arquivo do projeto com acesso de leitura/gravação.

- Essa alteração corrige um problema em que, se você criou uma tarefa manual com uma data de início e uma hora (mas não duração), ela seria exibida com um horário incorreto na linha do tempo.

- Correção de um problema em que imprimir uma linha do tempo usando o calendário islâmico resultaria em um mês sendo ignorado ou duplicado no modo de exibição de impressão.

- Essa alteração resolve um problema em que trabalhar no planejador de equipe com objetos GDI pode resultar na alocação total de objetos GDI e criar condições de pouca memória.

### <a name="word"></a>Word

- Correção de um problema em que a funcionalidade para postar comentários foi desabilitada.

- Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.

- Essa alteração resolve um problema em que o gerente de conta não despacha mensagens, resultando em um travamento com aplicativos de terceiros.

- Essa alteração corrige um problema em que o Sumário seria atualizado com estilos de título que não estão presentes no documento.

- Correção de um problema em que as assinaturas digitais salvas em documentos do Word seriam removidas durante a mala direta dos documentos.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-march-13"></a>Versão 2004: 13 de março
*Versão 2004 (Build 12703.20010)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos

### <a name="excel"></a>Excel
- **Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas. [Saiba Mais](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas. [Saiba Mais](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas. [Saiba Mais](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="access"></a>Access
- Correção de um problema em que as versões internacionais do Access exibiam as cadeias de caracteres em inglês na interface do usuário.

### <a name="excel"></a>Excel
- Corrigido um problema de desempenho que os usuários podem ter experimentado ao editar por programação um intervalo grande de células.
- Corrigido um problema de desempenho que acontecia ao abrir arquivos csv em ambientes japoneses.

### <a name="outlook"></a>Outlook
- Soluciona um problema que fazia com que a data "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um e-mail ou salvá-lo, arrastando e soltando-o (ao contrário de um menu).
- Resolve um problema que fez com que pressionar Enter no painel de localização expandido falhe ao iniciar uma pesquisa, exigindo que os usuários cliquem no botão de pesquisa.
- Correção de um problema em que a pesquisa não exibe informações sobre os usuários quando a opção "mostrar fotografias de usuário quando disponíveis" está desabilitada.

### <a name="project"></a>Project
- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.
- Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.

### <a name="word"></a>Word
- Corrigido um problema ao digitar ou editar um comentário e usar Ctrl + A resultaria na seleção de texto na tela, em vez de selecionar o texto apenas dentro do cartão de comentário.
- Resolvemos um problema em que o alinhamento de palavras em um documento fica embaralhado quando você tenta editar após imprimir usando a impressão rápida.
- Consertamos um problema ao mesclar dois documentos em um único documento.
- Correção de um problema em que a marcação de revisões envolvendo equações podem resultar em uma falha ao salvar o arquivo.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-06"></a>Versão 2003: 06 de março
*Versão 2003 (Build 12624.20086)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Foi corrigido um problema em que a criação de uma regra com o Outlook Web Access não persistia no servidor Exchange e resultava em um conflito.
- Foi corrigido um problema em que o Outlook no modo escuro não exibia a lista suspensa do campo 'De:'.
- Resolve um problema que fazia com que os usuários não conseguissem anexar um arquivo à mensagem de email por meio do explorador de arquivos se esse arquivo estivesse aberto em outro aplicativo.

### <a name="powerpoint"></a>PowerPoint

- Foi corrigido um problema em que as miniaturas recomendadas acendiam e apagavam ao passar o mouse sobre elas. Em alguns casos, isso pode causar uma falha no PowerPoint.

### <a name="word"></a>Word

- Foi corrigido um problema com o recurso comparar em documentos protegidos para edição.

### <a name="office-suite"></a>Pacote do Office

- Foi corrigido um problema com o Word/Excel/PowerPoint, em que o nome de usuário principal (UPN) não diferenciava maiúsculas de minúsculas, resultando em menos falhas ao trabalhar com arquivos no SharePoint.

- Foi corrigido um problema estético em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não era afetada.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

## <a name="version-2003-february-28"></a>Versão 2003: 28 de fevereiro
*Versão 2003 (Criação 12619.20002)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows. [Saiba mais](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **Tinta aprimorada para moldar a experiência de diagramação:** Desenhe diagramas melhores e faça com que seja convertidos para que você possa manipular objetos do escritório [Saiba mais](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrido um problema em que o texto em uma segmentação de dados não é dimensionado corretamente na visualização de impressão.

### <a name="outlook"></a>Outlook

- Soluciona um problema que fazia com que a data "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um e-mail ou salvá-lo, arrastando e soltando-o (ao contrário de um menu).

### <a name="word"></a>Word

- Corrigido um problema que, ao percorrer um cartão de comentários, o foco na caixa de edição de comentários não ficava visível.

- Inserir um controle (como um Controle de Conteúdo de Texto) em uma equação e salvar e abrir o arquivo resulta em um erro de conteúdo não legível.

- Corrigido um problema em que o salvamento de um arquivo anteriormente protegido por senha em um armazenamento em nuvem não funcionava.

### <a name="office-suite"></a>Pacote do Office

- Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-february-21"></a>Versão 2003: 21 de fevereiro
*Versão 2003 (Build 12615.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="office-suite"></a>Pacote do Office

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel
- Corrigido um problema que os usuários podem ter ao renomear medidas de tabela dinâmica.
- Corrigido um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.
- Corrigido um problema que fazia a interface do usuário piscar quando os usuários executavam uma macro que interagia com a faixa de opções.
- Corrigido um problema em que os arquivos CSV eram carregados incorretamente quando a primeira palavra no arquivo era TABLE.
- Corrigido um problema em que os usuários podem ter sofrido falhas ao alternar entre duas pastas de trabalho com diferentes níveis de zoom.

### <a name="outlook"></a>Outlook
- Corrigido um problema que fazia com que os usuários não conseguissem abrir mensagens de pasta pública quando o Outlook permanecia em execução durante a noite.
- Corrigida uma condição de corrida em que os botões 'Permitir' e 'Negar' na página de permissões são desativados durante o fluxo de trabalho de autenticação da adição de uma conta do Gmail.
- Resolvido um problema que fazia o Outlook gerar de forma inesperada a saída do log em alguns cenários, mesmo quando o log estava desativado.

### <a name="word"></a>Word
- Corrigido um problema em que os cartões de comentários nem sempre são destacados quando um ponteiro do mouse passa sobre o cartão de comentários.
- Durante uma sessão ativa de coautoria de documentos, adicionar uma imagem diretamente a um cartão de comentários pode resultar na adição de uma marca. Esse problema foi corrigido.

### <a name="office-suite"></a>Pacote do Office
- Ao usar as propriedades do MultiChoice/Lookup/Managed-metadata com documentos do Word/Excel/PowerPoint e salvá-los em uma biblioteca de documentos do SharePoint, essas propriedades anteriormente eram limitadas a 255 caracteres. Quando essas propriedades excederem 255 caracteres, esses documentos não puderam ser salvos. Com essa mudança, esse limite aumentou para 2048 caracteres.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-february-14"></a>Versão 2003: 14 de fevereiro
*Versão 2003 (Build 12607.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar? O Outlook agora detecta isso e ajuda você a se conectar.

### <a name="word"></a>Word

- **Encontre o Editor de Tinta na caixa de ferramentas de desenho:** Selecione Desenhar e, em seguida, escolha a caneta do Editor de Tinta para editar seu documento com o dedo ou uma caneta digital. [Saiba Mais](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Pacote do Office

- **Ícones mais claros da barra de status:** Agora é mais fácil visualizar os ícones da barra de status.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários perdessem o acesso à caixa de diálogo de permissões de calendário "Opções de Disponibilidade".

- Correção de um problema que pode resultar no alerta: "Infelizmente, estamos com problemas para abrir este item" ao abrir algumas instâncias de reunião recorrente enviadas de um fuso horário diferente.

- Solucionamos um problema que pode fazer com que os usuários não consigam reabrir um arquivo. msg depois de arrastar e soltar um anexo da mensagem.

- Correção de um problema em que, após carregar um anexo de arquivo do Outlook para o OneDrive, poderia resultar no nome do arquivo sendo alterado se o nome do anexo contivesse parênteses.

### <a name="powerpoint"></a>PowerPoint

- Correção de um problema que pode resultar em uma falha no salvamento de um documento no PowerPoint ou no Word com um gráfico do Excel.

### <a name="word"></a>Word

- Correção de um problema em que imagens em documentos perdem a transparência quando exportadas para PDF.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-february-07"></a>Versão 2002: 7 de fevereiro
*Versão 2002 (Build 12527.20040)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la. Pesquise e substitua o texto no SQL View. Selecione várias tabelas na janela Relações.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esta atualização corrige um problema no uso de um ADODB. O objeto gravador no código VB pode incorretamente relatar um erro.

- Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.

### <a name="excel"></a>Excel

- Corrigido um problema em que o Excel falhava ao usar colunas de texto em com matrizes dinâmicas.

### <a name="outlook"></a>Outlook

- Corrigido um problema em que a rolagem no calendário com a exibição do mês não mostrava eventos anteriores do calendário.

- Soluciona um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.

### <a name="powerpoint"></a>PowerPoint

- Corrigido um problema em que, após fechar um arquivo, o PowerPoint não o removia imediatamente da coleção Apresentações, se houvesse algum manipulador de eventos em execução. Portanto, o número de apresentações abertas relatadas pelo modelo de objeto ficava incorreto, e o desligamento do PowerPoint era impedido.

- Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.

### <a name="word"></a>Word

- Às vezes, atualizar e rolar um índice pode exibir uma área cinza sobre o documento.

- Corrigido um problema em que, se um documento fosse usado em coautoria, a versão de rascunho de um comentário raiz poderia não ser preservada.

- Corrigido um problema em que alternar entre os cartões de comentários às vezes exibia o comentário selecionado inicialmente com um destaque de seleção.

- Corrigido um problema em que o uso de "Procurar" para salvar um arquivo não funcionava se um comentário fosse escrito, mas não postado, e o usuário tentasse salvar o arquivo.

- Com o SlideTrack habilitado e o painel de comentários fechado, Ctrl+Alt+M pode não abrir o painel de comentários.

- Corrigido um problema ao adicionar @menção em uma tabela poderia gerar a mensagem de erro: "Uma tabela neste documento foi corrompida".

### <a name="office-suite"></a>Pacote do Office

- Resolve um problema que pode ter causado a instalação incorreta do pacote de ferramentas de revisão Nynorsk da Noruega (nn-no).

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|DevMain|Insiders| |16.0.13318.20000|version-2010-september-25|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13312.20006|version-2010-september-18|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13304.20000|version-2010-september-11|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13301.20004|version-2010-september-04|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13219.20004|version-2009-august-28|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13212.20000|version-2009-august-21|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13205.20000|version-2009-august-14|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13130.20000|version-2009-august-07|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13127.20002|version-2008-july-31|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13117.20000|version-2008-july-24|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

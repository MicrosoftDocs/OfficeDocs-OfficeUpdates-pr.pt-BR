---
title: Notas de Versão do Canal Mensal (Direcionado
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece a lista mais recente de novos recursos, correções ou problemas conhecidos para o público do Insider
ms.openlocfilehash: 2213653fbbc529ab849142e1bf5427952299ff2a
ms.sourcegitcommit: 9d2fb1f431933f304b68891c07a3b4eed5fdb936
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/09/2020
ms.locfileid: "44618927"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a>Notas de Versão do Canal Mensal do Office (Direcionado)

Este artigo contém notas de versão para builds de Canal Mensal (Direcionado) do Word, Excel, PowerPoint, Outlook, Access e Project para área de trabalho do Windows. Toda semana, vamos destacar novos e interessantes recursos, correções importantes e quaisquer problemas significativos que você queira conhecer. Observe que muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Mensal (Direcionado) durante um período de tempo. Isso nos permite garantir que tudo esteja funcionando bem antes de liberarmos o recurso para um público maior. Portanto, se você não vir algo descrito abaixo, não se preocupe, você receberá eventualmente.  

> [!IMPORTANT]
> Estamos fazendo algumas alterações nos canais de atualização do Microsoft 365 Apps, incluindo a adição de um novo canal de atualização (Canal corporativo mensal) e a alteração dos nomes dos canais de atualização existentes. Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - A data de publicação das notas de versão pode não corresponder com a data de lançamento da compilação atual.


[//]: # (NÃO REMOVA)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

## <a name="version-2005-june-08"></a>Versão 2005:8 de junho
*Versão 2005 (Build 12827,20336)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema com a caixa de diálogo substituir fontes em que Replace Font DropDown só mostra fontes na apresentação, em vez de fontes instaladas no sistema.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-june-04"></a>Versão 2005:04 de junho
*Versão 2005 (Build 12827,20320)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Mantenha-se atualizado com os tempos! O tipo de dados estendidos de data/hora tem uma precisão melhor.:** apresentando um novo e aprimorado tipo de dados.  Para aprimorar a compatibilidade de sintaxe com o SQL e para aumentar a precisão e o nível de detalhes nos registros que incluem datas e horas, estamos implementando o tipo de dados DateTime2 no Access. Essa data adicional & o tipo de dados de hora incluirá um intervalo de datas maior (0001-01-01 a 9999-12-31), com precisão de tempo mais elevada (nanossegundos, em vez de segundos) que você poderá fornecer e realizar cálculos. Para habilitar, selecione novo campo > data & tempo estendido. [Saiba mais](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **Criar tabelas dinâmicas a partir de conjuntos de no Power bi no Excel:** Você pode criar tabelas dinâmicas no Excel que estão conectadas a conjuntos de os DataSets armazenados no Power BI com alguns cliques.Isso permite obter o melhor das tabelas dinâmicas e do Power BI. Calcule, resuma e analise os dados com tabelas dinâmicas de seus conjuntos de dados do Power BI seguro.

### <a name="outlook"></a>Outlook

- **Opção para reabrir rapidamente os itens da sessão anterior do Outlook:** Adicionamos uma opção para reabrir rapidamente os itens de uma sessão anterior do Outlook.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="powerpoint"></a>PowerPoint

- Isso corrige uma falha quando os usuários têm comentários modernos e antigos em um arquivo, disparando uma atualização nos comentários.


### <a name="office-suite"></a>Pacote do Office

- Resolvemos o problema de taxa de falha do ValidateInstall Configurando a validação de instalação de Complementos do Bing como true por padrão e considerando o MSI Return Success como uma instalação bem-sucedida.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-29"></a>Versão 2005:29 de maio
*Versão 2005 (Build 12827,20268)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos

### <a name="excel"></a>Excel

- **Modo de exibição de planilha:** Classificar/filtrar ao colaborar com outras pessoas na área de trabalho do Excel.

### <a name="outlook"></a>Outlook

- **Botões adicionais adicionados às notificações de notificação do Outlook:** Agora, os botões de ação rápida aparecem nas notificações do Outlook em caso de execução do Outlook no Windows 10.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos



### <a name="outlook"></a>Outlook

- Foi corrigido um problema que fazia com que os usuários das versões do Windows 10 Server vejam o status de aviso de antivírus: inválido. Esta versão do Windows oferece suporte à detecção de antivírus, mas nenhum antivírus foi encontrado, apesar de ter o antivírus instalado corretamente.

### <a name="office-suite"></a>Pacote do Office

- O host do Office estava falhando no Windows, quando um suplemento é ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth é definida como zero. Essa alteração resolveria esse problema.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-21"></a>Versão 2005:21 de maio
*Versão 2005 (Build 12827,20210)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Obter dados de organização do Power bi usando os tipos de dados do Excel:** Você pode inserir dados da sua organização usando tipos de dados do Excel. Converta uma célula na sua pasta de trabalho e obtenha informações adicionais e atualize os dados sempre que precisar!


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Correção de um problema em que o Excel pode parar de responder após usar Ctrl + Shift + teclas de direção para rolar quando a janela do Excel é compartilhada por meio do teams.


- Em alguns casos, clicar em um hiperlink para um local dentro da mesma pasta de trabalho fará com que a pasta de trabalho fique oculta.


### <a name="outlook"></a>Outlook

- Foi corrigido um problema com o evento CLP de auditoria para o rótulo de resposta/encaminhamento.


- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma notificação de administrador.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-may-14"></a>Versão 2005:14 de maio
*Versão 2005 (Build 12827,20160)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.

### <a name="powerpoint"></a>PowerPoint

- **Não é preciso dar um clique: seus earbuds fazem isso por você** Use seu Surface Earbuds para controlar suas apresentações de PowerPoint. Importante: Você deve parear seu Surface Earbuds com o aplicativo Surface Audio para Windows 10 para usar gestos para controlar as apresentações. As instruções sobre como começar a usar o aplicativo de áudio Surface no Windows 10 estão disponíveis aqui. [Saiba mais](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.

### <a name="word"></a>Word

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel

- Foi aumentado o tamanho dos controles de edição de referência de célula na caixa de diálogo Barras de Erros Personalizadas usada com gráficos.

- Corrigimos um problema em que a tabela de dados do gráfico poderia processar incorretamente valores em um eixo de datas.

- Corrigimos um problema em que as quebras de página poderiam não ser desabilitadas após entrar no Layout da Página ou na Visualização da Quebra de Página.

- Corrigimos um problema em que os estilos de linha do gráfico poderiam ser perdidos após ocultar e reexibir colunas com dados de série.

- Correção de um problema em que a inserção de uma coluna em uma lista filtrada levaria mais tempo do que o esperado.

- Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.

- Correção de um problema em que o link externo para de funcionar depois que o arquivo for reaberto se o caminho do arquivo for muito longo.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- Essa alteração corrige um problema em que as informações de formatação condicional (CF) não estavam sendo salvas nos arquivos XLSB corretamente.

- Essa alteração corrige um problema em que o valor do R-quadrado da linha de tendência do gráfico (no caso de interceptação em y forçado) estava incorreto, mesmo que a função PROJ.LIN retorne o valor correto.

- Essa alteração corrige um problema em que a formatação personalizada da linha de tendência do gráfico nem sempre estava sendo salva.

- Uma falha pode ocorrer ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "pasta de trabalho compartilhada" herdado.

- Corrigimos um problema em que a formatação personalizada em gráficos dinâmicos pode não ser salva quando a opção "inverter se negativo" estiver habilitada.

- Corrigimos um problema em que a formatação personalizada de um único ponto de dados em um Gráfico dinâmico não era salva se a opção "inverter se negativo" tivesse sido selecionada.

- Essa alteração corrige um problema em que o caractere ' @ ' carregado em um arquivo CSV resultaria na conversão da cadeia de caracteres após o caractere ' @ ' em uma fórmula.

- Corrigimos um problema em que os valores decimais na função SEQUÊNCIA não eram arredondados corretamente.

### <a name="onenote"></a>OneNote

- Foi corrigido um problema em que as quebras de linha estavam sendo armazenadas como guias verticais.

### <a name="outlook"></a>Outlook

- Resolve um problema que fazia com que os usuários não pudessem adicionar um Grupo de Contatos Pessoais como participante da reunião.

- Correção de um problema em que o botão categorizar para calendários de grupo na faixa de opções do Office foi desabilitado.

- Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.

- Corrigimos um problema em que os clientes corporativos com pastas de grupo não implementadas ou que não funcionavam resultaria na exibição da mensagem “não respondendo” no Outlook.

- Solucionamos um problema que causaria um safelinks muito longo que os usuários clicaram no cliente da área de trabalho do Outlook para falha ao carregar devido ao truncamento.

- Corrigimos um problema em que as pastas do Outlook com nomes que continham caracteres DBCS (conjunto de caracteres de dois bytes) poderiam desaparecer de forma intermitente ao sincronizar com o servidor. Para que isso aconteça, o Outlook tinha que ser configurado com uma conta IMAP e estar sendo executado em um sistema com a localidade definida como japonês.

- Foi corrigido um problema que provocou as regras de exclusão criadas para caixas de correio diferentes da caixa de correio principal do usuário para se tornarem inválidas.

- Solucionamos um problema que fazia com que os anexos sejam descartados ao encaminhar uma mensagem criptografada.

- Solucionamos um problema que causaria reuniões com mais de dois meses de falha para exibir um assunto de reunião no assistente de agendamento.

- Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.

- Foi adicionada a capacidade de impor a configuração de assinatura padrão S/MIME pela política de grupo.

### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema em que, se um usuário criasse um comentário sem postá-lo, fechasse o painel Comentários, abrisse uma nova janela, navegasse por vários slides, fechasse a janela e, por fim, reabrisse o painel Comentários na apresentação original, os comentários de rascunho não estariam disponíveis.

- Corrigimos um problema em que passar o mouse sobre o símbolo de asterisco (*) não exibia o nome de usuário e a data da última pessoa a atualizar o documento.

### <a name="project"></a>Project

- Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.

- Corrigimos um problema em que o Project podia falhar ao alterar o campo de status do quadro em um projeto conectado a uma lista de tarefas do Microsoft Office SharePoint Online.

- Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.

- Correção de um problema em que, se o projeto estiver conectado ao Project Web App e o separador decimal for uma vírgula, o método TaskDependencies Add falhará quando o retardo for adicionado.


### <a name="word"></a>Word

- Corrigimos um problema em que a inserção de comentários em um documento no modo de colaboração nem sempre funcionava.

- Essa alteração corrige um problema em que o cartão Pessoas piscava se o @ da menção estivesse selecionado.

- Habilitar a opção "Mostrar indicadores" não exibia os indicadores. Isso foi corrigido.

- Corrigimos um problema em que o fechamento de um documento com comentários de rascunho perguntaria para o usuário se eles gostaria de fechar o documento sem salvar os comentários. Cancelar a solicitação fechava o documento, em vez de deixá-lo aberto.

- Corrigimos um problema na cópia e na colagem de cabeçalhos.

- Correção de um problema em que a conversão de um comentário Postado resultaria no erro "falha ao inserir texto traduzido".

- Essa alteração corrige um problema em que o texto com hiperlinks pode não ser exibido se a opção: "mostrar códigos de campo em vez de seus valores" estiver habilitada.

- No leitor Exibição da Web/Imersivo, clicar em uma dica rolaria a tela para cima, mesmo que ele já estivesse em exibição. Isso foi corrigido.

- Corrigimos um problema em que, ao tentar salvar um arquivo que contém uma macro com um novo nome, o arquivo poderia ser salvo com a extensão. docx e com o nome de arquivo WRO0004.docx, independentemente de qual nome o usuário inseriu, tornando o documento inutilizável.

### <a name="office-suite"></a>Pacote do Office

- Quando um usuário recebe uma política que as transfere apenas para o Microsoft Teams, ainda era possível usar o suplemento do Outlook para o Skype for Business para agendar reuniões.  Após esta atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente lê a política que indica que o usuário é apenas o Microsoft Teams e insere o modo somente ingresso na reunião.  Além disso, o suplemento do Outlook para o Skype for Business não se ativará enquanto é iniciado se ele estiver no modo somente ingresso na reunião.

- Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-11"></a>Versão 2004: 11 de maio
*Versão 2004 (Criação 12730.20270)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

### <a name="outlook"></a>Outlook

- **Links aprimorados no email:** quando você incluir um link a um arquivo, o nome do arquivo substituirá a URL. Você pode alterar as permissões para que todos os destinatários tenham acesso. [Saiba mais](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)

- **Conte suas histórias com GIFs animados:** Os GIFs animados já possuem suporte no editor do Office - seus documentos ficaram mais estilosos.

### <a name="powerpoint"></a>PowerPoint

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.  [Saiba mais](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir notificações do sistema.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-04"></a>Versão 2004: 04 de maio
*Versão 2004 (Build 12730.20250)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca. [Saiba mais](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2004-april-29"></a>Versão 2004: 29 de abril
*Versão 2004 (Build 12730.20236)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Ajude a proteger os dados de seu grupo:** o rótulo de Confidencialidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Aborda um problema que causa falha no Outlook em algumas versões do Windows.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-april-25"></a>Versão 2004: 25 de abril
*Versão 2004 (Build 12730.20206)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.

### <a name="project"></a>Project

- Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.


### <a name="office-suite"></a>Pacote Office

- Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2004-april-21"></a>Versão 2004: 21 de abril
*Versão 2004 (Build 12730.20182)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Corrige um problema que fazia com que a largura do painel de pastas fosse alterada inesperadamente.

- Corrige um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-april-15"></a>Versão 2004: 15 de abril
*Versão 2004 (Build 12730.20150)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **O suporte ao conector do Facebook terminou:** a partir de abril de 2020, o Excel não dará mais suporte a conexões de dados externos que usam o conector do Facebook.

### <a name="outlook"></a>Outlook

- **Nova opção para desabilitar sugestões de @menções ao redigir emails no Outlook:** você considera o seletor @mencionar mais irritante que útil? Agora você pode desativá-lo, se preferir.

### <a name="powerpoint"></a>PowerPoint

- **Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides.

### <a name="word"></a>Word

- **Faça anotações na sua cópia particular:** crie anotações redigidas à mão para você mesmo, fazendo uma cópia privada de um documento compartilhado. Vá para Exibir > Criar uma cópia privada para começar.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Foram corrigidos problemas com o redimensionamento e a atualização de tabelas no painel de tarefas.

- Correção de um problema em que as versões internacionais do Access exibiam as cadeias de caracteres em inglês na interface do usuário.

### <a name="excel"></a>Excel

- Foi corrigido um problema em que a seleção de um intervalo de células em uma planilha resultava na seleção de uma única célula.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma tabela dinâmica.

- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.

- Corrigido um problema de desempenho que os usuários podem ter experimentado ao editar por programação um intervalo grande de células.

- Corrigido um problema de desempenho que acontecia ao abrir arquivos csv em ambientes japoneses.

- Foi corrigido um problema em que a inserção de um modelo de gráfico definido pelo usuário poderia resultar no salvamento dele como um gráfico de colunas.

- Foi corrigido um problema em que os rótulos de Dados de gráficos eram exibidos como em branco quando as células de dados subjacentes não possuíam uma legenda.

- Foi corrigido um problema que podia fazer o Excel parar de responder quando se reduzia o tamanho de um gráfico com alguns intervalos de eixo x.

- Foi corrigido um problema em que, em uma planilha do Excel com referência de célula L1C1 habilitada que estivesse sendo criada em coautoria/compartilhada, passar o mouse sobre o ícone de presença do usuário não exibia a referência de célula ativa no modo L1C1.

- Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.

### <a name="outlook"></a>Outlook

- Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.

- Essa alteração corrige um problema em que as últimas alterações em rascunhos de emails não foram atualizadas.

- Correção de um problema em que clicar com o botão direito do mouse em um arquivo e usar ' enviar para ' não funcionará.

- Foi resolvido um problema que fazia os delegados verem diferentes hierarquias de pastas em computadores diferentes para caixas de correio compartilhadas.

- Foi resolvido um problema que fazia com que as categorias desaparecessem ocasionalmente de mensagens de email.

- Foi solucionado um problema que fazia com que alguns lembretes não fossem exibidos ao alterar o fuso horário em um computador.

- Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao tentar exibir as propriedades de um formulário organizacional.

- Correção de um problema em que o usuário tinha um caminho de pesquisa personalizado para o catálogo de endereços, o escopo de resolução de nome do Outlook seria limitado ao caminho personalizado, em vez de incluir a lista de endereços global (GAL).

- Foi solucionado um problema que fazia com que o botão "Salvar na nuvem" não tivesse as Ferramentas de Anexo.

- Foi solucionado um problema que fazia com que os usuários não conseguissem adicionar uma assinatura ao responder a uma mensagem gerenciada por direitos digitais de uma janela do inspetor quando o usuário não tivesse permissão de proprietário na mensagem que estivesse sendo respondida.

- Foi solucionado um problema que fazia com que os usuários não consiguissem adicionar outros anexos de um local da Web a uma reunião criada anteriormente.

- Foi solucionado um problema que fazia com que a data da "Última modificação" em um arquivo fosse atualizada ao adicionar um anexo a um email ou salvar um anexo de um email arrastando e soltando (em vez de por meio de um menu).

- Foi solucionado um problema que fazia com que pressionar Enter no painel de localização expandido falhasse em iniciar uma pesquisa, exigindo que os usuários clicassem no botão de pesquisa.

- Correção de um problema em que, em um conjunto de resultados de pesquisa retornados, classificar os resultados por categorias, não exibiria as cores da categoria.

- Correção de um problema em que a pesquisa não exibe informações sobre os usuários quando a opção "mostrar fotografias de usuário quando disponíveis" está desabilitada.


### <a name="powerpoint"></a>PowerPoint

- Essa alteração corrige um erro que poderia fazer com que arquivos do PowerPoint com emojis falhassem ao salvar.

- Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.

- Corrigimos um problema em que copiar texto do Excel para o PowerPoint poderia alterar a formatação.

- Essa alteração corrige um problema em que encontrar caracteres especiais usando "localizar somente palavras inteiras" nem sempre funcionava como esperado.

### <a name="project"></a>Projeto

- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.

- Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.

- Foi corrigido um problema em que o evento 'ProjectBeforeTaskChange' do Visual Basic Applications (VBA) não era acionado quando um usuário clicava no botão "Inativar" encontrado na Faixa de Opções de Tarefas no agrupamento de Agendamento.

- Se você definir os detalhes da predecessora ou da sucessora de dentro de um modo de exibição de tipo de formulário, o evento ProjectBeforeTaskChange Visual Basic Applications (VBA) não capturaria as alterações. Por exemplo, se você excluiu uma dependência e clicou em OK no formulário, o evento não foi acionado. Esse problema foi corrigido.

- Correção de um problema em que os valores mais recentes para o custo real do trabalho realizado (CRTR) não seriam exibidos depois de fazer uma alteração, como uma alteração de data.

- Correção de um problema em que abrir um projeto usando o menu mais recentemente utilizado (MRU) abriu o arquivo do projeto com acesso de leitura/gravação.

- Essa alteração corrige um problema em que, se você criou uma tarefa manual com uma data de início e uma hora (mas não duração), ela seria exibida com um horário incorreto na linha do tempo.

- Foi corrigido um problema em que imprimir uma linha do tempo usando um calendário islâmico resultava em um mês sendo ignorado ou duplicado no modo de exibição de impressão.

- Essa alteração resolve um problema em que trabalhar no planejador de equipe com objetos GDI pode resultar na alocação total de objetos GDI e criar condições de pouca memória.

- Foi corrigido um problema em que, se CustomFieldValueListGetItem fosse executado e uma tabela de pesquisa para o campo personalizado não existisse, uma tabela de pesquisa vazia era criada, mesmo que não devesse ser.

- Quando os dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado

- Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.

### <a name="word"></a>Word

- Essa alteração corrige um problema em que passar o cursor do mouse sobre uma dica não realçava o seu cartão.

- Essa alteração corrige um problema em várias páginas selecionadas no menu Exibir, onde o painel de comentários poderia ser exibido em branco.

- Correção de um problema em que a funcionalidade para postar comentários foi desabilitada.

- Essa alteração corrige um problema que fazia com que o texto em formas agrupadas desaparecesse temporariamente ao usar a ferramenta Seleção de Laço.

- Essa alteração corrige atrasos ao processar imagens com informações de protocolo malformadas ou incorretas.

- Esta alteração corrige um problema em que a renderização de um gráfico herdado do Excel incorporado como um objeto OLE no PowerPoint ou no Word nem sempre exibia o título do gráfico.

- Essa alteração resolve um problema em que o gerente de conta não despacha mensagens, resultando em um travamento com aplicativos de terceiros.

- Essa alteração corrige um problema no modo de exibição de duas páginas em que, ao criar um comentário, a âncora de comentário nem sempre chegava a ser exibida.

- Corrigido um problema ao digitar ou editar um comentário e usar Ctrl + A resultaria na seleção de texto na tela, em vez de selecionar o texto apenas dentro do cartão de comentário.

- Corrigido um problema em que, para um parágrafo cujo estilo é um ancestral de um estilo vinculado a uma lista, a numeração dessa lista poderia ser perdida.

- Essa alteração corrige um problema em que o Sumário seria atualizado com estilos de título que não estão presentes no documento.

- Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.

- Corrigimos um problema ao mesclar 2 documentos em um único documento.

- Correção de um problema em que as assinaturas digitais salvas em documentos do Word seriam removidas durante a mala direta dos documentos.

- Correção de um problema em que a marcação de revisões envolvendo equações podem resultar em uma falha ao salvar o arquivo.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-april-14"></a>Versão 2003: 14 de abril
*Versão 2003 (Build 12624.20466)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

- Várias correções de bugs e desempenho.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

## <a name="version-2003-april-09"></a>Versão 2003: 09 de abril
*Versão 2003 (Build 12624.20442)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="powerpoint"></a>PowerPoint

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="word"></a>Word

- **Seletor de conteúdo M365 Premium:** dê vida aos seus documentos! Explore milhares de imagens, ícones e adesivos isentos de direitos autorais [Saiba mais](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)




[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-april-03"></a>Versão 2003: 03 de abril
*Versão 2003 (Criação 12624.20410)*

[//]: # (NÃO REMOVA O INÍCIO DO CONTEÚDO DO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Em alguns casos, o uso do Application.Evaluate do VBA não funcionava para funções definidas pelo usuário.

### <a name="outlook"></a>Outlook

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.

### <a name="project"></a>Projeto

- Quando os dados do Predecessor/Sucessor são editados em uma exibição de Formulário, um evento adicional do ProjectBeforeTaskChange é acionado.

### <a name="word"></a>Word

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DO BUGDETAILS)

## <a name="version-2003-march-31"></a>Versão 2003: 31 de março
*Versão 2003 (Build 12624.20382)*

 (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Painel de Tarefas "Adicionar Tabelas": ** O novo Painel de Tarefas "Adicionar Tabelas" do Access finalmente chegou! Esse recurso permite que você selecione/multi-selecione com facilidade quais tabelas gostaria de adicionar/remover à uma janela de consulta, sem navegar para a caixa de diálogo "Mostrar Tabelas" para consultas e para o modo de exibição de relação. Isso também inclui uma nova guia "links" para exibir tabelas vinculadas, uma caixa de pesquisa para filtrar a lista atual, comportamento "arrastar e soltar" e muito mais!


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="project"></a>Project

- <div><span style="display:inline !important;">Correção de um problema em que o usuário não conseguiu entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.</span><br></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-25"></a>Versão 2003: 25 de março
*Versão 2003 (Build 12624.20320)*

- Várias correções de bugs e de desempenho.

## <a name="version-2003-march-23"></a>Versão 2003: 23 de março
*Versão 2003 (Build 12624.20296)*

- Várias correções de bugs e desempenho.

## <a name="version-2003-march-21"></a>Versão 2003: 21 de março
*Versão 2003 (Build 12624.20276)*

 (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online. Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.

- **Atualização visual de calendário:** ano passado, trouxemos uma experiência de email atualizada e, este ano, é a vez do calendário ser transformado! As atualizações são novas, mas usuais e, como um usuário experiente do Outlook, você pode entrar e ser mais produtivo imediatamente.

### <a name="powerpoint"></a>PowerPoint

- **Atualizar slides durante a apresentação de slides:** os slides de atualização alterados por outros autores durante a sua apresentação.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

## <a name="version-2003-march-16"></a>Versão 2003: 16 de março
*Versão 2003 (Build 12624.20224)*


 (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.

### <a name="outlook"></a>Outlook

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.

### <a name="powerpoint"></a>PowerPoint

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.

### <a name="word"></a>Word

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.

### <a name="office-suite"></a>Pacote Office

- **Painéis com Guias:** Agora, você pode alterar entre vários painéis usando uma interface de usuário de guia à direita do aplicativo. A interface de usuário ficará visível apenas quando você tiver dois painéis ou mais abertos.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.

### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários vissem o processo do Outlook persistir no gerenciador de tarefas após sair.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-10"></a>Versão 2003: 10 de março
*Versão 2003 (Build 12624.20176)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)
### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel
- **Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas. [Saiba Mais](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas. [Saiba Mais](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Rótulos de confidencialidade**: agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas. [Saiba Mais](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Correção de um problema superficial em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não foi afetada.

- Corrigido um problema que os usuários podem ter ao renomear medidas de tabela dinâmica.

- Correção de um problema em que o texto em uma segmentação de dados não é dimensionado corretamente na visualização de impressão.

- Corrigido um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.

- Corrigido um problema que fazia a interface do usuário piscar quando os usuários executavam uma macro que interagia com a faixa de opções.

- Corrigido um problema em que os arquivos CSV eram carregados incorretamente quando a primeira palavra no arquivo era TABLE.

- Corrigido um problema em que os usuários podem ter sofrido falhas ao alternar entre duas pastas de trabalho com diferentes níveis de zoom.

- Correção de um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.

- Essa alteração corrige um erro em tempo de execução no modelo de objeto e a possível falha do aplicativo (Excel, Word) quando os suplementos pedem itens de host em documentos ou planilhas que contêm formas com bloqueios não selecionados.

- Aborda um problema que causou a falha dos usuários do Outlook durante a sincronização das configurações.



### <a name="outlook"></a>Outlook

- Foi corrigido um problema em que a criação de uma regra com o Outlook Web Access não persistia no servidor Exchange e resultava em um conflito.

- Aborda um problema que causou a falha dos usuários do Outlook durante a sincronização das configurações.

- Correção de um problema em que o Outlook no modo escuro não exibia a lista suspensa do campo 'De:'.

- Aborda um problema que fazia o Outlook gerar de forma inesperada a saída do log em alguns cenários, mesmo quando o log estava desativado.

- Corrigido um problema que fazia com que os usuários não conseguissem abrir mensagens de pasta pública quando o Outlook permanecia em execução durante a noite.

- Corrigida uma condição de corrida em que os botões 'Permitir' e 'Negar' na página de permissões são desativados durante o fluxo de trabalho de autenticação da adição de uma conta do Gmail.

- Solucionamos um problema que fazia com que os usuários perdessem o acesso à caixa de diálogo&quot;opções de disponibilidade&quot; de permissões de calendário.

- Correção de um problema que pode resultar no alerta: &quot;Infelizmente, estamos com problemas para abrir este item&quot; ao abrir algumas instâncias de reunião recorrente enviadas de um fuso horário diferente.

- Solucionamos um problema que pode fazer com que os usuários não consigam reabrir um arquivo. msg depois de arrastar e soltar um anexo da mensagem.

- Correção de um problema em que, após carregar um anexo de arquivo do Outlook para o OneDrive, poderia resultar no nome do arquivo sendo alterado se o nome do anexo contivesse parênteses.

- Solucionamos um problema que fazia com que os usuários não conseguissem anexar um arquivo à mensagem de email por meio do explorador de arquivos se esse arquivo estivesse aberto em outro aplicativo.

- Aborda um problema que causou a falha dos usuários do Outlook durante a sincronização das configurações.

### <a name="powerpoint"></a>PowerPoint

- Foi corrigido um problema em que as miniaturas recomendadas acendiam e apagavam ao passar o mouse sobre elas. Em alguns casos, isso pode causar uma falha no PowerPoint.

- Correção de um problema superficial em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não foi afetada.

- Correção de um problema que pode resultar em uma falha no salvamento de um documento no PowerPoint ou no Word com um gráfico do Excel.



### <a name="project"></a>Projeto

- Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.

- Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.

- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.

### <a name="visio"></a>Visio

- O painel de informações de forma estava mostrando detalhes inconsistentes na seção dados da forma, com relação ao arquivo quando aberto na área de trabalho do Visio. Esse problema foi corrigido.

- Bitmaps importados em versões anteriores a 2016 não estavam sendo renderizados devido a algumas verificações de segurança. Corrigimos esse problema na assinatura do Visio.

### <a name="word"></a>Word

- Corrigido um problema em que os cartões de comentários nem sempre são destacados quando um ponteiro do mouse passa sobre o cartão de comentários.

- Correção de um problema que, ao usar o cartão de comentários, o foco na caixa de edição de comentários não ficava visível.

- Correção de um problema superficial em que o botão 'OK' na caixa de diálogo Arquivo \ Opções era exibido em cinza, mas a funcionalidade não foi afetada.

- Durante uma sessão ativa de coautoria de documentos, adicionar uma imagem diretamente a um cartão de comentários pode resultar na adição de uma marca. Esse problema foi corrigido.

- Inserir um controle (como um Controle de Conteúdo de Texto) em uma equação e salvar e abrir o arquivo resulta em um erro de conteúdo não legível.

- Corrigido um problema em que o salvamento de um arquivo anteriormente protegido por senha em um armazenamento em nuvem não funcionava.

- Correção de um problema com o recurso comparar em documentos protegidos para edição.




### <a name="office-suite"></a>Pacote Office

- Ao usar as propriedades do MultiChoice/Lookup/Managed-metadata com documentos do Word/Excel/PowerPoint e salvá-los em uma biblioteca de documentos do SharePoint, essas propriedades anteriormente eram limitadas a 255 caracteres. Quando essas propriedades excederem 255 caracteres, esses documentos não puderam ser salvos. Com essa mudança, esse limite aumentou para 2048 caracteres.

- Foi corrigido um problema com o Word/Excel/PowerPoint, em que o nome de usuário principal (UPN) não diferenciava maiúsculas de minúsculas, resultando em menos falhas ao trabalhar com arquivos no SharePoint.

- Correção de um problema em que, quando vários documentos da mesma biblioteca do SharePoint estivessem abertos no Word/Excel/PowerPoint, somente o primeiro documento aberto era verificado quanto à conformidade com Políticas.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-march-05"></a>Versão 2002: março de 2005
*Versão 2002 (Build 12527.20278)*

- Várias correções de bugs e de desempenho.


## <a name="version-2002-march-04"></a>Versão 2002: 04 de março
*Versão 2002 (Build 12527.20264)*


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="project"></a>Project
- <div>Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.</div>


### <a name="office-suite"></a>Pacote do Office
- <div>Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.</div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-01"></a>Versão 2002: 01º de março
*Versão 2002 (Criação 12527.20242)*

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- <div>Resolve um problema que fazia com que aplicativos de terceiros não pudessem enviar e-mails.</div>



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-february-24"></a>Versão 2002: 24 de fevereiro
*Versão 2002 (Criação 12527.20194)*

- Várias correções de bugs e desempenho.

## <a name="version-2002-february-22"></a>Versão 2002: 22 de fevereiro
*Versão 2002 (Criação 12527.20186)*

- Várias correções de bugs e desempenho.

## <a name="version-2002-february-21"></a>Versão 2002: 21 de fevereiro
Versão 2002 (Build 12527.20174)


 (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la. Pesquise e substitua o texto no SQL View. Selecione várias tabelas na janela Relações.

### <a name="outlook"></a>Outlook

- **Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar? O Outlook agora detecta isso e ajuda você a se conectar.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- <div style="box-sizing:border-box;">Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.&nbsp;</div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a>Outlook

- <div>Corrige um problema que fazia com que as vírgulas no campo local de uma reunião se transformassem em ponto e vírgula.</div>


- <div>Resolve um problema que pode resultar em uma falha ao exibir o mesmo item em várias janelas.</div>


- <div>Resolve um problema que fez com que o Outlook sincronize inesperadamente todos os e-mails, mesmo quando o controle deslizante de sincronização estiver definido como uma configuração menor.&nbsp;</div>


- <div>Resolve um problema que fez com que os usuários com o Tema Preto consultem o &quot;De&quot; da lista suspensa mostrem um texto branco sobre um fundo branco..</div>


- <div><span style="display:inline !important;">Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.</span><br></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-february-18"></a>Versão 2002: 18 de fevereiro
*Versão 2002 (Build 12527.20138)*

## <a name="version-2002-february-11"></a>Versão 2002: 11 de fevereiro
*Versão 2002 (Build 12527.20092)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada. As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.

### <a name="word"></a>Word

- **Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.

### <a name="office-suite"></a>Pacote do Office

- **Ícones mais claros da barra de status:** Agora é mais fácil visualizar os ícones da barra de status.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados. Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.

- Esta atualização corrige um problema no uso de um ADODB. O objeto gravador no código VB pode incorretamente relatar um erro.

- Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.


### <a name="excel"></a>Excel

- Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.


- Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.


- Corrigido um problema em que o Excel falhava ao usar colunas de texto em com matrizes dinâmicas.

### <a name="outlook"></a>Outlook

- Corrigido um problema em que a rolagem no calendário com a exibição do mês não mostrava eventos anteriores do calendário.

- As pastas salvas em ‘Favoritos’ no painel de navegação à esquerda podem desaparecer continuamente.


- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.


- Solucionado um problema que fazia com que a opção desativar o realce do item sinalizado deixasse de ser respeitada em alguns cenários.

- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.


- Correção de um problema em que os emails que expiravam com base em uma política de retenção exibiam dois rótulos. Um que mostrava que o email expiraria em um dia e outro exibindo a expiração em dois dias.


- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix.


### <a name="powerpoint"></a>PowerPoint

- Correção de um problema em que a Tinta não era processada completamente ou era pulado ao ser usada em uma animação de tinta do PowerPoint.

- Corrigido um problema em que, após fechar um arquivo, o PowerPoint não o removia imediatamente da coleção Apresentações, se houvesse algum manipulador de eventos em execução. Portanto, o número de apresentações abertas relatadas pelo modelo de objeto ficava incorreto, e o desligamento do PowerPoint era impedido.


- Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.


### <a name="project"></a>Project

- Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.


### <a name="word"></a>Word

- Às vezes, atualizar e rolar um índice pode exibir uma área cinza sobre o documento.


- Corrigido um problema em que o uso de "Procurar" para salvar um arquivo não funcionava se um comentário fosse escrito, mas não postado, e o usuário tentasse salvar o arquivo.


- Corrigido um problema em que alternar entre os cartões de comentários às vezes exibia o comentário selecionado inicialmente com um destaque de seleção.


- Correção de um problema em que a formatação em itálico era perdida após a edição de um comentário, pondo o texto em itálico e, em seguida, fazendo a postagem do mesmo.


- Correção de um problema em que a dica de comentário não estava visível no modo de leitura com a cor da página Invertida.


- Corrigido um problema em que, se um documento fosse usado em coautoria, a versão de rascunho de um comentário raiz poderia não ser preservada.


- Com o SlideTrack habilitado e o painel de comentários fechado, Ctrl+Alt+M pode não abrir o painel de comentários.


- Corrigido um problema ao adicionar @menção em uma tabela poderia gerar a mensagem de erro: "Uma tabela neste documento foi corrompida".


- Correção de um problema em que os comandos de comentário (Editar comentário, Responder ao comentário, Excluir comentário, Resolver comentário) não estavam sendo exibidos no menu de contexto comentários.


### <a name="office-suite"></a>Pacote do Office

- Resolve um problema que pode ter causado a instalação incorreta do pacote de ferramentas de revisão Nynorsk da Noruega (nn-no).


- Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


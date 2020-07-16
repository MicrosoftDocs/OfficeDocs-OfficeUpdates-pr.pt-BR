---
title: Notas de versão para os lançamentos do Canal Corporativo Mensal em 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI as notas de versão para o Canal Corporativo Mensal dos Aplicativos do Microsoft 365 em 2020
ms.openlocfilehash: f76ceaf76f505d9a4301f2bba66c9efcb6278ca4
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138677"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>Notas de versão para os lançamentos do Canal Corporativo Mensal em 2020

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionadas à segurança que estão inclusos em atualizações mensais do Canal Corporativo Mensal em 2020 para Microsoft 365 Apps para Grandes Empresas, Microsoft 365 Apps para Pequenos e Médios negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.

> [!IMPORTANT]
> Estamos fazendo algumas alterações nos canais de atualização para os aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes. Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

[//]: # (NÃO REMOVA)



## <a name="version-2005-july-14"></a>Versão 2005: 14 de julho
*Versão 2005 (Build 12827.20538)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca. [Saiba mais](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="word"></a>Word

- **Fale de outra maneira:** quando você quiser dizer algo de forma diferente, o Reescrever estará lá para ajudar. O Reescrever oferece alternativas para refinar a suas frases.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acesso

- Corrige um problema para possibilitar o uso do tipo de dados de Data/Hora Estendida em seu código sem o aplicativo falhar.

- Corrige um problema para poder reverter para a versão mais atualizada do Access e usar o DAO/VBA para gerenciar e editar um tipo de dados decimais.

### <a name="excel"></a>Excel

- Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.

- Em alguns casos, clicar em um hiperlink para um local na mesma pasta de trabalho fará com que a pasta de trabalho seja ocultada.

- Corrige um problema que causava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.

- Soluciona um problema no qual o Excel poderia falhar ao tentar inserir Tabelas Dinâmicas em uma planilha de gráfico.

### <a name="outlook"></a>Outlook

- Soluciona uma falha que ocorria ao enviar comentários de uma Notificação de Administrador.

- Corrige um problema que fazia com que a pesquisa de um recurso em Sugerir um recurso não retornasse resultados e deixasse o usuário sem a opção de enviar uma nova ideia de recurso.

- Corrige um problema que fazia com que o Outlook solicitasse continuamente para os usuários executarem a Ferramenta Reparo da Caixa de Entrada.

- Corrige um problema em versões do Windows 10 Server que exibia o aviso “Status da proteção antivírus: Inválido. Esta versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus foi encontrado” mesmo após a instalação correta do antivírus.

- Soluciona um problema que causava falhas e travas intermitentes em algumas situações.

- Corrige um problema que causava falhas no calendário em aperfeiçoamentos do Calendário Compartilhado.

- Soluciona um problema que exibia a mensagem &quot;As regras neste computador não correspondem às regras no Microsoft Exchange&quot; ao atualizar as regras no Outlook.

- Corrige um problema que exibia a data de criação dos anexos&nbsp; que os usuários copiavam para o sistema de arquivos arrastando e soltando, definido para 1 de janeiro, 4501.

- Soluciona um problema que causava falha no Outlook ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.

- Corrige um problema com o evento de auditoria clp do rótulo responder/encaminhar.


### <a name="powerpoint"></a>PowerPoint

- Isso corrige uma falha quando os usuários têm comentários modernos e antigos em um arquivo, disparando uma atualização nos comentários.

- Soluciona um problema que causava falha no painel de sugestões.


### <a name="project"></a>Project

- Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa resumo do projeto, o campo início/tarefa do projeto.

- Correção de um problema em que uma tarefa marcada como 100% concluída mudava incorretamente para menos do que 100% concluída.

### <a name="skype"></a>Skype

- Quando um usuário recebe uma política que os move para o modo Teams Only, ele ainda poderá usar o suplemento do Outlook do Skype for Business para agendar reuniões. Após essa atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente ler a política, indicando que o usuário está no modo Teams Only, e entrar no modo somente ingresso na reunião. Além disso, o suplemento Skype for Business no Outlook não será ativado durante a inicialização, caso veja que o cliente do Skype for Business está no modo somente ingresso na reunião.

### <a name="word"></a>Word

- Soluciona um problema que pode ter causado uma falha ao arrastar conteúdo do aplicativo.

### <a name="office-suite"></a>Pacote Office

- Essa alteração soluciona as possíveis travas ao carregar e reproduzir conteúdo animado, como GIFs ou modelos 3D.

- Resolvemos o problema de taxa de falha do ValidateInstall configurando a validação de instalação do Bing Addon como verdadeira por padrão e considerando o sucesso do retorno MSI como um sucesso na instalação.

- Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

- O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero. Essa alteração corrigiria esse problema.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-july-14"></a>Versão 2004: 14 de julho
*Versão 2004 (Build 12730.20602)*

Atualizações de segurança estão listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2004-june-09"></a>Versão 2004: 09 de junho
*Versão 2004 (Build 12730.20430)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Adicionar tabelas com menos cliques:** usar o painel de tarefas Adicionar Tabelas, que permanece aberto enquanto você trabalha, para adicionar tabelas a relações e consultas. [Saiba mais](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **O suporte ao conector do Facebook terminou:** a partir de abril de 2020, o Excel não dará mais suporte a conexões de dados externos que usam o conector do Facebook.

- **Novas imagens para dar vida às suas pastas de trabalho:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em suas pastas de trabalho. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="outlook"></a>Outlook

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada. As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **O calendário recebe um novo formato:** ver atualizações visuais que facilitam a pesquisa do calendário. [Saiba mais](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **Novas imagens para dar vida às suas mensagens:** milhares de imagens de estoque, ícones e adesivos gratuitas que você pode usar em suas mensagens de email. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="powerpoint"></a>PowerPoint

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides. [Saiba mais](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Novas imagens para dar vida aos seus slides:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em suas apresentações. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="word"></a>Word

- **Laço a tinta:** a ferramenta laço na guia desenhar ajuda a selecionar objetos desenhados à tinta. Selecione traços individuais ou palavras inteiras. [Saiba mais](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Novas imagens para dar vida aos seus documentos:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em seus documentos. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="office-suite"></a>Pacote Office

- **Rótulos de confidencialidade:** agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.

- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma Tabela Dinâmica.

### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma Notificação de Administrador.

- Solucionamos um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.

- Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir notificações do sistema.

- Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.

- Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.

- Solucionamos um problema que provocava a alteração inesperada da largura do painel de pasta.

### <a name="project"></a>Project

- Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.

- Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.

### <a name="office-suite"></a>Pacote Office

- Corrigido um problema com Clique para Executar, o que resultava na falha de atualização durante a tentativa de vincular links simbólicos.

- O host do Office estava falhando no Windows, quando um suplemento está sendo ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth está definida como zero. Essa alteração corrigiria esse problema.

- Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

- Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-june-09"></a>Versão 2003: 09 de junho
*Versão 2003 (Build 12624.20708)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-may-12"></a>Versão 2003: 12 de maio
*Versão 2003 (Build 12624.20588)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la. Pesquise e substitua o texto no SQL View. Selecione várias tabelas na janela Relações.

### <a name="excel"></a>Excel

- **Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão automaticamente enviados para as células vizinhas. [Saiba mais](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE e RANDARRAY. [Saiba mais](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!:** Linha por linha, encontre tudo o que você precisa em uma tabela ou intervalo com o XLOOKUP. [Saiba mais](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)

- **Leia e responda instantaneamente:** Responda a comentários e menções diretamente do e-mail sem abrir a pasta de trabalho.

### <a name="outlook"></a>Outlook

- **Obter sugestões de email ao procurar por alguém:** Quando você digitar o nome de uma pessoa na Caixa de pesquisa, os emails mais relevantes serão incluídos nas sugestões de pesquisa. [Saiba mais](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **Política de Nome de Grupo:** Uma política de nome de grupo permite que o administrador de TI padronize e gerencie os nomes do grupos criados pelos usuários na organização. O administrador pode exigir o uso de um prefixo ou sufixo específico para o nome de um grupo quando ele é criado e pode bloquear o uso de palavras específicas. Isso ajuda a minimizar o uso de palavras inadequadas em nomes de grupos, além de gerenciar a representação de grupos no diretório. A Política de Nome também ajuda as organizações que implantam sites de equipe a categorizar com base no departamento.

- **Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online. Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.

- **Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar? O Outlook agora detecta isso e ajuda você a se conectar.

### <a name="powerpoint"></a>PowerPoint

- **Colaboração rápida e em tempo real no PowerPoint:** Colaboração rápida e em tempo real no PowerPoint

- **Os vídeos online têm um novo lar:** salve um vídeo no Microsoft Stream para que qualquer pessoa em sua organização possa vê-lo. Insira o link de vídeo e desfrute de uma apresentação multimídia com uma fração do tamanho do arquivo. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **GIFs em instantes:** Um slide, um quadro. Crie facilmente GIFs de loop no PowerPoint. [Saiba mais](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)

- **Diagramas melhores:** Com conectores melhores e um processo de conversão de tinta mais suave, você pode usar a tinta em suas ideias de forma mais confiante. [Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Atualizar slides durante a apresentação de slides:** Atualize slides alterados por outros autores durante a sua apresentação.<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

### <a name="word"></a>Word

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.

### <a name="office-suite"></a>Pacote Office

- **Abrir Arquivos Grandes de Forma Incremental:**  A capacidade de baixar, abrir e interagir com grandes apresentações do powerpoint, mesmo que partes da apresentação (por exemplo, um vídeo ou imagem grande) ainda não tenham concluído o download.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel

- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.

- Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.


### <a name="onenote"></a>OneNote

- Melhoria na sincronização e estabilidade do serviço, alterando temporariamente a frequência com que os históricos de versão de página são criados.


- Melhoria na sincronização e estabilidade do servidor ao desabilitar, temporariamente, a transferências de páginas para a lixeira. Os usuários que desejam excluir uma página, em vez disso, receberão uma caixa de diálogo perguntando se gostariam de excluir permanentemente a página.


- Melhoria da sincronização e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016. Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.


- Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016. Os blocos de anotações locais não são afetados por essa medida.


- Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.


- Informa os usuários, por meio da barra de informações, sobre ajustes temporários no Microsoft OneNote que ajudarão a melhorar a sincronização e o serviço durante o uso intenso pelo mundo inteiro.


### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários vissem o processo do Outlook persistir no gerenciador de tarefas após sair.


- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão no mouse.


- Solucionamos um problema que fazia com que os usuários experimentassem falhas em aplicativos MAPI de terceiros.


- Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.


- Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.


- Solucionamos um problema que provocava a alteração inesperada da largura do painel de pasta.


### <a name="project"></a>Project

- Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.


- Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.


- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.


- Solucionamos um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.


- Correção de um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.


- Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.


- Solucionamos um problema em que o usuário não conseguia entrar no trabalho da Linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.


- Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.


### <a name="word"></a>Word

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.

### <a name="office-suite"></a>Pacote Office

- Essa correção resolve um erro que ocorre impedindo o acesso restrito e protegendo os arquivos com uma senha simultaneamente.

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER FIM)

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|MEC|Production|Feature|16.0.12827.20538|version-2005-july-14|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

---
title: Notas de versão do Office Insiders
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece a lista mais recente de novos recursos, correções ou problemas conhecidos para o público-alvo do Insider − Modo Rápido.
ms.openlocfilehash: 860ec2d6bbd8623442ecc10657fee71a62c8d89d
ms.sourcegitcommit: 941b77865c5b2d92e0f98b961fc702e865589ec3
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/13/2019
ms.locfileid: "40019847"
---
# <a name="release-notes-for-office-insiders"></a>Notas de versão do Office Insiders

Este artigo contém notas de versão para versões Insider do Word, Excel, PowerPoint, Outlook, Access e Project para área de trabalho do Windows. Toda semana, vamos destacar novos e interessantes recursos, correções importantes e quaisquer problemas significativos que você queira conhecer. Em geral, disponibilizamos recursos (e, às vezes, até mesmo correções) para os participantes do programa Office Insider ao longo do tempo. Isso nos permite garantir que tudo esteja funcionando bem antes de liberarmos o recurso para um público maior. Portanto, se você não vir algo descrito abaixo, não se preocupe, você receberá eventualmente.  

> [!NOTE]
> - As notas de versão são publicadas semanalmente e podem ser uma compilação de várias compilações.
> - A data de publicação das notas de versão pode não corresponder com a data de lançamento da compilação atual.
> - Microsoft Teams em instalações existentes do Office 365 ProPlus - A partir do final de Junho, o Microsoft Teams será incluído nas atualizações de instalações existentes do Office 365 ProPlus (e do Office 365 Business). A data em que o Teams será adicionado depende de qual canal de atualização você está usando. Confira [Implantar o Microsoft Teams com o Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) para obter informações adicionais.

[//]: # (NÃO REMOVA)

## <a name="version-2001-december-13"></a>Versão 2001: 13 de dezembro
*Versão 2001 (Build 12410.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada. As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access
- A execução de uma consulta união que faça referência a tabelas ODBC vinculadas e contenha uma cláusula Ordenar Por falha com o Access de 64 bits.
- A soma dos dados de consultas união no Access (O365) pode resultar em truncamento de dados decimais.
- As interfaces COM para ACE não são expostas para uso fora dos aplicativos do Office.

### <a name="excel"></a>Excel
- A inserção de um modelo 3D (animado ou estático) e a tentativa de "Salvar como Imagem" não funcionam.
- A tecla de atalho (Alt+Ctrl + 7/8) para iniciar o feedback do backstage está em conflito com os teclados AZERTY (Alt-Gr + 7/8). Impacto: os usuários não poderão usar alguns caracteres, como: '\'.

### <a name="outlook"></a>Outlook
- Resolvido um problema que fazia com que o email fosse enviado para o endereço de destinatário errado.
- Resolvido um problema que fazia com que o Outlook permitia, de forma incorreta, que os usuários com acesso de &quot;leitura&quot; acessassem uma caixa de correio para alterar o estado lido/não lido de uma mensagem.
- A revogação do certificado de segurança no site não é reproduzível pelo Suporte ao Produto. O registro em log deve ser adicionado para ajudar a causa raiz do problema.
- Resolvido um problema que fazia com que os usuários vissem falhas de sincronização.

### <a name="powerpoint"></a>PowerPoint
- A inserção de um modelo 3D (animado ou estático) e a tentativa de "Salvar como Imagem" não funcionam.

### <a name="project"></a>Project
- O trabalho da tarefa não é calculado no Resumo de acúmulo para tarefas filho agendadas manualmente.
- O código VBA do projeto invocado a partir de um botão da faixa de opções pode não funcionar ao tentar salvar Projetos baseados em servidor.
- A menos que o Project já esteja em execução, a abertura dos arquivos do Project em uma biblioteca de documentos do SharePoint exibe um erro e o arquivo não será aberto.

### <a name="word"></a>Word
- A salvamento de arquivos existentes pode não funcionar.
- O uso de teclas de direção na janela do editor de Ortografia e Gramática pode resultar em tremulações intermitentes.
- Ao resolver um acompanhamento, os comentários associados podem não ser convertidos em comentários de ponto.
- A inserção de um modelo 3D (animado ou estático) e a tentativa de "Salvar como Imagem" não funcionam.

### <a name="office-suite"></a>Pacote Office
- Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado. Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1912-december-06"></a>Versão 1912: 06 de dezembro
*Versão 1912 (Build 12325.20012)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Configurações avançadas de email do grupo:** Esse recurso ajuda os usuários de grupos a personalizar quais emails ou eventos receber/acompanhar na caixa de entrada.

- **Política de Nome de Grupo:** Uma política de nome de grupo permite que o administrador de TI padronize e gerencie os nomes do grupos criados pelos usuários na organização. O administrador pode exigir o uso de um prefixo ou sufixo específico para o nome de um grupo quando ele é criado e pode bloquear o uso de palavras específicas. Isso ajuda a minimizar o uso de palavras inadequadas em nomes de grupos, além de gerenciar a representação de grupos no diretório. A Política de Nome também ajuda as organizações que implantam sites de equipe a categorizar com base no departamento.

### <a name="office-suite"></a>Pacote Office

- **Painéis com Guias:** Agora, você pode alterar entre vários painéis usando uma interface de usuário de guia à direita do aplicativo. A interface de usuário ficará visível apenas quando você tiver dois painéis ou mais abertos.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel
- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.
- Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.
- A desativação da aceleração de gráficos de hardware com resolução de 4K poderá causar um atraso na renderização de células.
- A limpeza de uma fórmula extensa que se sobrepõe ao limite de uma célula ainda pode ser exibida no limite da célula.
- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.
- O menu suspenso de Margem pode não ser renderizado corretamente.

### <a name="onenote"></a>OneNote
- O OneNote pode não abrir através do suplemento “Anotações da Reunião” do Outlook.

### <a name="outlook"></a>Outlook
- Os rótulos da política de retenção podem exibir o período de retenção entre parênteses.
- Espaços em branco podem aparecer nos cartões de Contato com o pacote de idioma japonês.
- As imagens inseridas embutidas nas mensagens de email do Outlook às vezes podem ser redimensionadas.

### <a name="powerpoint"></a>PowerPoint
- Se um usuário tiver dois (ou mais) vídeos diferentes em um slide de um arquivo na nuvem, as imagens de vídeos são processadas corretamente, mas quando o usuário clica em cada uma delas, o conteúdo do vídeo é o mesmo.
- Em alguns casos, rolar com dispositivos de toque não funcionará.
- O menu suspenso de Margem pode não ser renderizado corretamente.
- Os links seguros de um aplicativo do Office para outro podem não iniciar o aplicativo vinculado.

### <a name="project"></a>Project
- O Project pode falhar ao usar o recurso de Comparar Projetos.
- Se você estiver no modo Escuro, ao acessar o painel do inspetor de tarefas em uma tarefa com um recurso alocado em excesso, não será possível ler a tabela.
- O esforço para definir tarefas que não têm atribuições está arredondado para um dia.

### <a name="word"></a>Word
- Salvar um arquivo após fazer uma mala direta pode não funcionar em determinadas condições.
- O organizador de blocos de construção pode exibir um alerta inválido: &quot;Você modificou estilos, blocos de construção&quot;.
- Às vezes, o painel de comentários é recarregado ao usar a opção de copiar/colar.
- Às vezes, os comentários não são colados na ordem correta.
- A aplicação de um modelo que consiste em uma lista de vários níveis com estilos personalizados para documentos existentes pode não preservar o estilo sob determinadas condições.
- O redimensionamento de uma borda da tela dividida poderá introduzir uma tela dividida adicional.
- O menu suspenso de Margem pode não ser renderizado corretamente.
- Ao mencionar um usuário em um cartão de comentários, um JSON poderá ser exibido.
- Os links seguros de um aplicativo do Office para outro podem não iniciar o aplicativo vinculado.

### <a name="office-suite"></a>Pacote Office
- Para produtos com base japonesa, o nome do usuário da conta e o sobrenome podem aparecer em ordem incorreta.
- Passar o cursor do mouse sobre os comentários poderá exibir uma estrutura de tópicos de caixa de texto em torno do comentário.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1912-november-15"></a>Versão 1912: 15 de novembro
*Versão 1912 (Build 12307.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="insights-services"></a>Serviços de Insights
- **Consultas com o Idioma Natural no Ideias do Excel:** Novo recurso de Ideias do Excel para consultar seus dados com o idioma natural.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel
- A funcionalidade Texto em Coluna pode falhar em algumas localizações.
- Editar fórmulas de matriz dinâmica dentro de uma célula pode fazer o texto ficar alinhado fora do limite da célula.

### <a name="outlook"></a>Outlook
- Adicionada a capacidade de forçar a configuração S/MIME pela política de grupo.
- Imagens inseridas podem ser exibidas menor que o esperado.

### <a name="powerpoint"></a>PowerPoint
- O cursor pode desaparecer após mover o foco do texto.

### <a name="project"></a>Project
- Os usuários podem ter um erro de licenciamento.
- O botão Hoje no seletor de data pode, às vezes, definir a data incorreta.

### <a name="word"></a>Word
- O clique com o botão direito do mouse às vezes pode não resultar na seleção da palavra inteira.
- O cursor pode permanecer ativo dentro de um objeto após convertê-lo para um formato sugerido.
- As imagens nas mensagens podem ser dimensionadas incorretamente em alguns cenários.
- Alguns temas podem dificultar a determinação do comentário selecionado.
- Selecionar uma dica de comentário agora mostra o painel de comentários modernos quando oculto no seletor do painel.

### <a name="office-suite"></a>Pacote Office
- Responder a um comentário pode fazer com que a caixa de texto se expanda verticalmente além da borda do painel.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1912-november-08"></a>Version 1912: 08 de novembro
*Versão 1912 (Build 12231.20000)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="user-lifecycle"></a>Ciclo de vida do usuário
- **Melhorias da experiência da ativação do AFO:** atualizações das telas que os clientes veem ao ativar o Office que vem com o novo computador.

### <a name="word"></a>Word
- **Nova e aprimorada experiência de vídeo online no Word:** Nova e mais segura experiência de vídeo online para ajudá-lo a inserir novos vídeos e reproduzir vídeos existentes no Word.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook
- Falha intermitente envolvendo conteúdo de pastas cruzadas.

### <a name="office-suite"></a>Pacote Office
- Colar um gráfico do Excel para o PowerPoint pode reduzir o tamanho do gráfico.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1911-november-01"></a>Version 1911: 01 de novembro
*Versão 1911 (Build 12228.20020)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel
- **Traga o contexto junto com seus objetos SVG!:** Agora, você pode manter o texto em mapas, gráficos e outros vetores SVG ao converter esses objetos no Office.

- **Confira as opções da caneta ao selecionar a caneta Surface:** ao selecionar pela primeira vez a caneta Surface no Word, Excel ou PowerPoint, a guia Desenhar será ativada para facilitar a seleção de cores da caneta.

### <a name="powerpoint"></a>PowerPoint
- **Traga o contexto junto com seus objetos SVG!:** Agora, você pode manter o texto em mapas, gráficos e outros vetores SVG ao converter esses objetos no Office.

- **Confira as opções da caneta ao selecionar a caneta Surface:** ao selecionar pela primeira vez a caneta Surface no Word, Excel ou PowerPoint, a guia Desenhar será ativada para facilitar a seleção de cores da caneta.

### <a name="visio"></a>Visio
- **Crie diagramas elegantes do Visio no Excel:** visualize seus dados de forma rápida e fácil nos diagramas elegantes do Visio no Excel. [Saiba mais](https://support.office.com/pt-BR/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).

### <a name="word"></a>Word
- **Confira as opções da caneta ao selecionar a caneta Surface:** ao selecionar pela primeira vez a caneta Surface no Word, Excel ou PowerPoint, a guia Desenhar será ativada para facilitar a seleção de cores da caneta.

- **Melhorias de coautoria:** experiência de coautoria melhorada, tornando mais provável que as alterações de conteúdo sejam recebidas por outras pessoas em tempo real.

- **Outras pessoas veem suas alterações rapidamente:** os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas alterações mais rápido do que nunca.

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel
- Resolvido um problema em que o Excel falhava ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.
- Resolvido um problema em que a exclusão de planilhas com dados que faziam referência a dados de outra planilha fazia o arquivo ser identificado como corrompido ao ser aberto novamente.
- Resolvido um problema em que resultados incorretos eram obtidos ao converter filtros de relatórios com o restante da tabela dinâmica para consultas a servidores de tabela SQL.
- Usar o Narrador e a Lupa ao mesmo tempo pode causar uma falha.
- Usar o Narrador e a Lupa ao mesmo tempo pode causar uma falha.

### <a name="outlook"></a>Outlook
- Um email encaminhado pode não apresentar imagens inseridas.
- A ferramenta Localizador de Sala pode estar exibindo &quot;Nenhuma&quot; para salas disponíveis.
- Os usuários talvez não consigam criar perfis do Outlook com restrição estrita de locatário.

### <a name="powerpoint"></a>PowerPoint
- Usar o Narrador e a Lupa ao mesmo tempo pode causar uma falha.

### <a name="project"></a>Project
- O usuário não consegue marcar uma tarefa como concluída, e ela é definida como 99%.
- As superalocações não são resolvidas por nivelamento.

### <a name="word"></a>Word
- Usar o Narrador e a Lupa ao mesmo tempo pode causar uma falha.
- Abrir documentos herdados e acessar a guia Informações pode causar uma falha.
- As sugestões de revisão não estão sendo exibidas nos menus de contexto.
- As políticas de conteúdo estão sendo aplicadas incorretamente a comentários.
- Comentários herdados escritos com texto escuro não são visíveis no Modo Escuro.
- Caracteres incorretos podem ser exibidos ao usar a AutoCorreção de coreano/inglês.
- Rótulos de políticas mais baixos poderão ser aplicados quando um rótulo de política mais alto precisar ter prioridade.
- Os links de cid: imagens de mensagens do Outlook&nbsp;podem ser interrompidos com sucesso quando solicitado.
- Usar o Narrador e a Lupa ao mesmo tempo pode causar uma falha.
- A pesquisa no Painel navegação pode falhar.

### <a name="office-suite"></a>Pacote Office
- Alguns desenhos podem não ser exibidos na visualização ou na apresentação de slides.
- Alguns caracteres Katakana podem ser exibidos incorretamente em uma caixa de texto vertical.
- As tentativas de salvar um arquivo em um compartilhamento de rede desconectado podem ocasionar uma falha.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1911-october-25"></a>Versão 1911: 25 de outubro
*Versão 1911 (Build 12215.20006)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="visio"></a>Visio

- **Crie diagramas elegantes do Visio no Excel:** visualize seus dados de forma rápida e fácil nos diagramas elegantes do Visio no Excel. [Saiba mais](https://support.office.com/pt-BR/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Melhorias de coautoria:** experiência de coautoria melhorada, tornando mais provável que as alterações de conteúdo sejam recebidas por outras pessoas em tempo real.

- **Outras pessoas veem suas alterações rapidamente:** os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas alterações mais rápido do que nunca.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- <div><span>A contagem de registros pode estar incorreta</span></div>


### <a name="excel"></a>Excel

- <div><span>Melhoramos significativamente o desempenho da exclusão de colunas com células mescladas</span></div>


- <div><span>Os usuários podem ser impedidos de salvar no Office 365 formato de pasta de trabalho do Excel</span></div>


- <div><span>As caixas de seleção não podem ser processadas corretamente</span></div>


- <div><span>As alterações feitas em um tamanho de gráfico não puderam ser salvas</span></div>


- <div><span>Algumas funções do VBA retornariam um erro em novos tipos de gráfico</span></div>


- <div><span>As caixas de diálogo selecionar fonte de dados não diferenciam maiúsculas de minúsculas em alguns campos</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>As alterações feitas em um tamanho de gráfico não puderam ser salvas</span></div>


### <a name="publisher"></a>Editor

- <div><span>As formas podem aparecer fora da borda do gráfico</span></div>


### <a name="word"></a>Word

- <div><span>As formas podem aparecer fora da borda do gráfico</span></div>


- <div><span>O realce do texto pode ser desafiador</span></div>


- <div><span>Um usuário poderia ser impedido de navegar para um item individual no editor</span></div>


- <div><span>Os erros de gramática ou ortografia podem não estar realçados</span></div>


- <div><span>As alterações feitas em um tamanho de gráfico não puderam ser salvas</span></div>


- <div><span>Um cartão de visita pode ser impedido de abrir após aplicar a formatação a uma @ menção</span></div>


- <div><span>Resolvido um problema em que os usuários podem não conseguir salvar documentos do Word, Excel e PowerPoint. &nbsp; Esse problema afeta os usuários que criam um novo arquivo e exibir a caixa de diálogo &quot;salvar como modelo &quot;após clicar no ícone Salvar ou pressionar Ctrl + S.</span></div>


### <a name="office-suite"></a>Pacote Office

- <div><span>Problema de desempenho ao usar formas no Windows 7</span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1911-october-18"></a>Versão 1911: 18 de outubro
*Versão 1911 (Build 12209.20010)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Envie email acessível para quem mais precisa:** O Outlook exibirá uma dica de email para ajudar a garantir que seu conteúdo seja acessível ao enviar para um usuário que prefira este tipo de conteúdo.

### <a name="powerpoint"></a>PowerPoint

- **Otimize sua apresentação para todos:** O Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.

### <a name="office-suite"></a>Pacote do Office

- **O Upload Center está sendo substituído pela experiência de Arquivos Que Precisam de Atenção:** O Upload Center está sendo substituído pela experiência de Arquivos Que Precisam de Atenção, que será mostrado dentro dos aplicativos do Office em Arquivo > Abrir. Essa nova experiência é mais moderna, integrada e menos invasiva em comparação ao Upload Center.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Resolvido um problema em que os controles da caixa de seleção podiam diminuir ao usar o AutoAjuste para ajustar a altura da linha</span></div>


- <div><span>Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Identificado um problema que poderia fazer com que assinaturas digitais fossem corrompidas ao assinar um email com um anexo assinado digitalmente</span></div>


- <div><span>Identificado um problema em que os nomes de arquivos longos eram truncados após arrastar e soltar no corpo da mensagem</span></div>


- <div>Identificado um problema em que a caixa de pesquisa podia desaparecer quando a faixa de opções estivesse configurada para ocultar automaticamente</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Identificado um problema em que a taxa de proporção da visualização do slide não estava sendo bloqueada/desbloqueada corretamente</span></div>

### <a name="project"></a>Project

- <div>Identificado um problema em que as anotações podiam não persistir se inseridas durante a realização de tarefas de atualização<br></div>


- <div>Identificado um problema em que um arquivo podia ser bloqueado por um usuário, mas nenhum nome de usuário seria exibido na mensagem de erro</div>


- <div><span>Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura</span></div>


### <a name="word"></a>Word

- <div><span>Identificado um problema ao visualizar comentários usando um leitor de tela</span></div>


- <div><span>Identificado um problema em que algumas críticas foram identificadas incorretamente como sendo críticas de ortografia ou gramática</span></div>


- <div><span>Identificado um problema em que um nova caixa de diálogo comentários podia, às vezes, não ter foco</span></div>


### <a name="office-suite"></a>Pacote do Office

- <div><span>Corrigimos um problema que uma atualização poderia ser impedida por uma mensagem de erro incorreta de &quot;Outra instalação em andamento&quot;</span></div>

- <div><span>Identificado um problema que podia afetar a sincronização de um recurso local para um recurso na nuvem</span></div>

- <div><span>Identificado um problema em que uma mensagem de boas-vindas continha um link inválido</span></div>


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1910-october-11"></a>Versão 1910: 11 de outubro
*Versão 1910 (build 12130.20112)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)
[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)
[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div>Resolvido um problema ao inserir arquivos como objeto no OneDrive</div>


- <div>Resolvido um problema em que o formato do hiperlink não podia ser aplicado adequadamente a algum conteúdo</div>


- <div>Resolvido um problema em que as fórmulas que contêm referências absolutas estruturadas eram ajustadas incorretamente</div>


- <div>Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office</div>


- <div>Resolvido um problema em que o conteúdo copiado do Excel poderia parecer incorreto quando colado em outros aplicativos do Office</div>


- <div>Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico</div>


### <a name="powerpoint"></a>PowerPoint

- <div>Foi identificado um problema em que os dispositivos ARC poderiam perder a conexão ao serem executados no AirSpace WinComp</div>


### <a name="word"></a>Word

- <div>Resolvido um problema ao inserir arquivos como objeto no OneDrive</div>


- <div>Melhoramos nossas etapas de recuperação para <span>corrigir um problema que fazia com que o conteúdo gráfico fosse excluído dos threads de email.&nbsp;</span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1910-october-04"></a>Versão 1910: 04 de outubro
*Versão 1910 (Build 12126.20000)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel. [Saiba mais](https://support.office.com/pt-BR/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta</span></div>


- <div><span>Corrigimos um problema que poderia impedir a atualização de tabelas dinâmicas durante uma sessão de coautoria</span></div>


### <a name="access"></a>Access

- <div>Corrigimos um problema em que usuários poderiam receber um erro de &quot;estado inconsistente&quot; ao usar um banco de dados compartilhado.</div>


### <a name="outlook"></a>Outlook

- <div><span>Corrigimos um problema que poderia ter causado a duplicação de pastas de email</span></div>


- <div><span>Corrigimos um problema que poderia ter causado uma mensagem de erro incorreta ao tentar enviar email criptografado s/MIME</span></div>


- <div><span>Corrigimos um problema que às vezes poderia resultar em falha quando um usuário recebia uma mensagem de “Conversa Perdida” do Skype</span></div>


- <div><span>Corrigimos um problema que poderia resultar em um vazamento de memória</span></div>


- <div><span>Corrigimos um problema que poderia causar uma alteração no nome do remetente quando salvo como um rascunho</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>Corrigimos um problema que poderia causar a quebra de TextRanges após colar o texto nos espaços reservados de cabeçalho/rodapé/número de slide no slide mestre e no layout do slide


- <div><span></span></div>Corrigimos um problema que impedia a criação de hiperlink ao colar texto com hiperlink.


- <div>Corrigimos um problema que impedia o funcionamento correto das estatísticas.</div>


### <a name="word"></a>Word

- <div><span>Corrigimos um problema em que as cores da fonte não estavam sendo confirmadas</span></div>


### <a name="office-suite"></a>Pacote do Office

- <div>Corrigimos um problema que poderia oferecer histórico de versões quando esse recurso estava desativado</div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1910-september-27"></a>Versão 1910: 27 de setembro
*Versão 1910 (Build 12119.20000)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)
[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)
[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Corrigimos um problema que poderia ter relatado erros de permissão ao interagir com pastas de calendário compartilhadas</span></div>


- <div><span>Corrigimos um problema que poderia impedir os usuários de adicionarem anexos a calendários</span></div>


- <div><span>Corrigimos um problema que causou a exibição de mensagens de erro ao responder a uma mensagem assinada digitalmente</span></div>


### <a name="word"></a>Word

- <div><span>Corrigimos um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet</span></div>


### <a name="office-suite"></a>Pacote Office

- <div><span>Corrigimos um problema em que o texto médio em negrito poderia ser estilizado de forma incorreta</span></div>


- <div><span>Corrigimos um problema em que um usuário poderia receber uma mensagem de erro incorreta ao fechar um arquivo com um carregamento pendente.</span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1910-september-20"></a>Versão 1910: 20 de setembro
*Versão 1910 (Build 12112.20000)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema em que o Excel podia, às vezes, parar durante a inicialização</span></div>

### <a name="outlook"></a>Outlook

- <div><span>Melhoramos significativamente o desempenho da seleção de sala quando há um grande número de salas disponíveis</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Corrigimos um problema que podia impedir a sincronização de caixa de correio para clientes com várias caixas de correio no Outlook durante a migração para a autenticação moderna no Office 365</span><br></div>


- <div><span>Corrigimos um problema em que alguns caracteres em rótulos de assinatura não eram exibidos no menu suspenso</span></div>


### <a name="project"></a>Project

- <div><span>Corrigimos um problema que podia causar uma falha ao substituir um recurso da empresa por um recurso local</span></div>


### <a name="word"></a>Word

- <div><span>Corrigimos um problema que podia impedir que a rolagem sincronizada funcionasse corretamente no modo de exibição de rascunho</span></div>


- <div>Corrigimos um problema que podia impedir a exibição adequada das Dicas de Ferramenta após salvar um documento pela primeira vez.</div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1910-september-13"></a>Versão 1910: 13 de setembro
*Versão 1910 (Build 12105.20000)*


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Consertamos um problema que poderia impedir que um usuário colasse hiperlinks em algumas planilhas protegidas</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Consertamos um problema em que a IU poderia ficar presa em um modo de exibição compacto</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Consertamos um problema em que um usuário poderia ter um erro ao imprimir em PDF</span></div>


### <a name="project"></a>Project

- <div><span>Consertamos um problema em que<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;"> as alterações feitas em um valor de trabalho em uma tarefa de resumo poderiam causar uma falha se o trabalho protegido estivesse habilitado</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">Consertamos um problema que poderia inibir a capacidade de sincronizar eventos com calendários da empresa</font>


### <a name="office-suite"></a>Pacote Office

- <div><span>Consertamos um problema que poderia causar um aviso repetido para descartar versões locais de um arquivo</span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1910-september-06"></a>Versão 1910: 06 de setembro
*Versão 1910 (Build 12030.20004)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Pronto, definir, desenhar:** quando você selecionar sua caneta Surface, estará pronto para desenhar. [Saiba mais](https://support.office.com/pt-BR/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **Pronto, definir, desenhar:** quando você selecionar sua caneta Surface, estará pronto para desenhar. [Saiba mais](https://support.office.com/pt-BR/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **Pronto, definir, desenhar:** quando você selecionar sua caneta Surface, estará pronto para desenhar. [Saiba mais](https://support.office.com/pt-BR/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema que poderia fazer com que o nome da fonte na faixa de opções fosse diferente da fonte usada</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Corrigimos um problema que poderia resultar em consumo inapropriado de recursos pelo Outlook quando o modo protegido estivesse desabilitado para sites restritos no Internet Explorer</span></div>


- <div><span>Corrigimos um problema que poderia fazer com que caracteres Unicode aparecessem ao colar texto de uma fonte ANSI</span></div>


- <div><span>Corrigimos um problema onde alguns usuários apareciam incorretamente como Offline em um modo de exibição de Agenda de Grupo</span></div>


### <a name="word"></a>Word

- <div><span>Corrigimos um problema em que a formatação da tabela poderia ser perdida</span></div>


- <div><span>Corrigimos um problema que poderia quebrar o atalho de teclado ctrl+v</span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1909-august-30"></a>Versão 1909: 30 de agosto
*Versão 1909 (Build 12026.20000)*


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos

### <a name="access"></a>Access

- **Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas.

### <a name="powerpoint"></a>PowerPoint

- **Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem. [Saiba mais](https://support.office.com/pt-BR/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema em que a dica de tecla para&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensibilidade </span>estava&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">em conflito com outra dica de tecla.</span></span></div>

- <div><span>Corrigimos um problema que ocorria trabalhando em uma pasta de trabalho compartilhada ao tentar salvar.</span></div>

- <div><span>Corrigimos um problema em que o Excel só lista os primeiros 16 suplementos localizados nos valores de registro do “Gerenciador de Complementos\Excel\”<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>Corrigimos um problema em que a função Frequency() retornava resultados incorretos.</span></div>


- <div><span>Melhoramos significativamente o desempenho da filtragem por cor.</span></div>


- <div><span>Corrigimos um problema com usuários do Surface em que mover o mouse poderia ser interpretado como um clique do mouse.</span></div>


- <div><span>Corrigimos um problema que impedia a navegação de teclado na caixa de diálogo Localizar/Substituir</span></div>


- <div><span>Corrigimos um problema em que o nome de algumas fontes não era exibido corretamente</span></div>


- <div><span>Corrigimos um problema que impedia que o CSV fosse exibido como um tipo de arquivo compatível</span></div>


### <a name="access"></a>Access

- <div>Corrigimos um problema em que usuários poderiam receber um erro de &quot;estado inconsistente&quot; ao usar um banco de dados compartilhado.</div>


- <div><span>Corrigimos um problema que poderia fazer com que o selecionador de data aparecer quando não deveria</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Corrigimos um problema que impedia que o conteúdo HTML fosse exibido para alguns usuários POP3</span></div>


- <div><span>Corrigimos um problema para remover o link “Planner” não funcional do menu excedente no cartão de visita ao trabalhar em ambientes em que ele não está disponível.</span></div>

### <a name="onenote"></a>OneNote

- <div><span>Corrigimos um problema em que a &nbsp;sincronização do plano de fundo do OneNote poderia roubava o foco.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Corrigimos um problema que poderia afetar a orientação de rotação de uma Plataforma Giratória 3D.</span></div>

- <div><span>Corrigimos um problema que impedia que alguns hiperlinks funcionassem caso possuíssem caracteres especiais.</span></div>

- <div><span>Corrigimos um problema que causava a abertura de vários painéis de comentários ao mesmo tempo.</span></div>

### <a name="project"></a>Project

- <div><span>Corrigimos um problema que poderia causar uma falha após imprimir um modo de exibição do Planejador de Equipe.</span></div>

### <a name="word"></a>Word

- <div><span>Corrigimos um problema em que caracteres de vários bytes na caixa de texto vertical eram exibidos sobrepostos no modo de exibição de leitura.<br></span></div>

- <div><span>Corrigimos&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);"> um problema em que recursos de suplemento relacionados a cartões de mensagem japoneses não eram encontrados quando o usuário realizava uma ação no assistente de suplemento.</span></span></div>

- <div><span>Corrigimos um problema que poderia causar problemas com a interface do usuário da barra de título, quando estava no modo de exibição protegido</span></div>

### <a name="office-suite"></a>Pacote do Office

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Corrigimos um problema de arquivo corrompido ao Alterar uma Forma em uma seleção contendo uma forma normal e uma forma de conector.</span></span></div>

- <div><span>Corrigimos um problema que <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">causava um problema em aplicativo ao usar encaixar/desencaixar de várias exibições externas.</span></span></div>



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="august-23-2019br"></a>**23 de agosto de 2019**<br/>
Versão 1909 (Build 12015.20004)<br/>



## <a name="non-security-updates"></a>Atualizações não relacionadas à segurança:

### <a name="excel"></a>Excel

- <div><span>Melhoramos significativamente o desempenho da exclusão de colunas com células mescladas</span></div>


### <a name="office-suite"></a>Pacote do Office

- <div><span>Corrigimos um problema que poderia impedir que alguns caracteres Unicode fossem exibidos quando acessados em um navegador</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Corrigimos um problema que poderia impedir que os arquivos fossem salvos em um local de WebDAV</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Corrigimos um problema em que um usuário clicava em um comentário, mas outro comentário era selecionado</span></div>





## <a name="august-16-2019br"></a>**16 de agosto de 2019**<br/>
Versão 1909 (Build 12013.20000)<br/>

### <a name="powerpoint-feature-updates"></a>Atualizações de recursos do PowerPoint:

- **Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos. Deixá-los ou não ativados depende de você.




## <a name="non-security-updates"></a>Atualizações não relacionadas à segurança:

### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema que poderia fazer com o que o Salvamento Automático fosse habilitado</span></div>


- <div>Corrigimos um problema que poderia resultar em uma medição incorreta da altura de células </div>


### <a name="office-suite"></a>Pacote do Office

- <div><span>Corrigimos um problema que melhora significativamente o desempenho do recurso Comentários</span></div>


- <div><span>Corrigimos um problema que poderia causar uma falha ao usar as teclas de setas durante a pesquisa</span></div>


- <div><span>Corrigimos um problema que poderia impedir uma menção usando o sinal @ se o símbolo @ fosse colocado após determinados caracteres</span></div>


- <div><span>Corrigimos um problema que poderia causar uma falha ao excluir menções com o @</span></div>


- <div><span>Corrigimos um problema que impedia que emojis fossem exibidos corretamente em cartões de comentário</span></div>


- <div><span>Corrigimos um problema com a Área de Transferência Ativa que poderia resultar em uma falha</span></div>


- <div><span>Corrigimos um problema que poderia fazer com que os botões da Barra de Ferramentas de Acesso Rápido parassem de funcionar</span></div>


- <div><span>Corrigimos um problema que poderia impedir a Visualização da Formatação do Documento alternasse para o plano de fundo</span></div>

### <a name="onenote"></a>OneNote

- Consertamos um problema em que os nomes das seções apareciam em branco na lista suspensa da seção quando o tema do Office era configurado como Preto.

### <a name="outlook"></a>Outlook

- <div><span>Corrigimos um problema com Enviar Eventos, o que poderia fazer com que o Outlook ganhasse ou perdesse o foco repetidamente</span></div>


- <div><span>Corrigimos um problema que impedia que o atalho Postar Resposta na Pasta funcionasse</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Corrigimos um problema com o Modo de Exibição Protegido que poderia causar problemas durante a colaboração</span></div>


- <div><span>Corrigimos um problema que poderia impedir a correta exibição de tarefas em painéis de comentários</span></div>


- <div><span>Corrigimos um problema que poderia causar uma falha ao inserir novos slides</span></div>


### <a name="user-lifecycle"></a>Ciclo de vida do usuário

- <div><span>Corrigimos um problema que poderia resultar no desaparecimento de recursos da assinatura</span></div>


### <a name="word"></a>Word

- <div><span>Corrigimos um problema em que os hiperlinks poderiam ser desfeitos se o hiperlink contivesse determinados caracteres</span></div>


- <div><span>Corrigimos um problema onde as imagens poderiam ser inadequadamente dimensionadas ao exibir um comentário para essa imagem</span></div>


- <div><span>Corrigimos um problema com o menu suspenso da Lista com Marcadores, o que poderia resultar em uma falha</span></div>





## <a name="august-09-2019br"></a>**09 de agosto de 2019**<br/>
Versão 1909 (Build 12001.20000)<br/>

### <a name="excel-feature-updates"></a>Atualizações de recursos do Excel:

- **A colaboração ficou mais fácil** : Os aperfeiçoamentos de coautoria significam que, ao trabalhar com acesso condicional, estilos de célula e muito mais, suas alterações são mescladas perfeitamente com as de seus colaboradores.


- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.


### <a name="office-suite-feature-updates"></a>Atualizações de recursos do pacote do Office:

- **Novos Ícones de aplicativos do Office:** ícones de aplicativo reprojetados para refletir as experiências simples, avançadas e inteligentes do Office.


### <a name="outlook-feature-updates"></a>Atualizações de recursos do Outlook:

- **Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.


- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.


### <a name="powerpoint-feature-updates"></a>Atualizações de recursos do PowerPoint:

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.


### <a name="word-feature-updates"></a>Atualizações de recursos do Word:

- **Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.


- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu.




## <a name="non-security-updates"></a>Atualizações não relacionadas à segurança:

### <a name="outlook"></a>Outlook

- <div><span>Consertamos um problema que fazia com que os destinatários da reunião recebessem duas notificações depois da reunião estar cancelada</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Consertamos um problema que pode causar uma falha quando o usuário selecionava sem contorno ou sem preenchimento para formas e ícones</span></div>





## <a name="august-02-2019br"></a>**2 de agosto de 2019**<br/>
Versão 1908 (Build 11929.20002)<br/>

### <a name="excel-feature-updates"></a>Atualizações de recursos do Excel:

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.


- **Aplique rótulos de confidencialidade aos documentos:** aplique rótulos de confidencialidade aos documentos para ficarem em conformidade com as políticas de proteção de informações da sua organização.


### <a name="outlook-feature-updates"></a>Atualizações de recursos do Outlook:

- **Aplique rótulos de confidencialidade aos documentos:** aplique rótulos de confidencialidade aos documentos para ficarem em conformidade com as políticas de proteção de informações da sua organização.


### <a name="powerpoint-feature-updates"></a>Atualizações de recursos do PowerPoint:

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.


- **Aplique rótulos de confidencialidade aos documentos:** aplique rótulos de confidencialidade aos documentos para ficarem em conformidade com as políticas de proteção de informações da sua organização.


### <a name="word-feature-updates"></a>Atualizações de recursos do Word:

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.


- **Fale de outra maneira:** quando você quiser dizer algo de forma diferente, o Reescrever estará lá para ajudar. O Reescrever oferece alternativas para refinar a suas frases.


- **Aplique rótulos de confidencialidade aos documentos:** aplique rótulos de confidencialidade aos documentos e emails para que fiquem em conformidade com as políticas de proteção de informações da sua organização.




## <a name="non-security-updates"></a>Atualizações não relacionadas à segurança:

### <a name="access"></a>Access
- Várias correções de desempenho e estabilidade

### <a name="excel"></a>Excel

- <div><span>Corrigimos um problema que exibia &quot;repetir todos os rótulos&quot; como se tivesse sido aplicado durante a impressão em um PDF.</span></div>

### <a name="office-suite"></a>Pacote do Office

- <div><span>Corrigimos um problema que poderia impedir os usuários de abrir um documento da área de trabalho</span></div>

- <div><span>Corrigimos um problema que uma atualização poderia ser impedida por uma mensagem de erro incorreta de &quot;Outra instalação em andamento&quot;</span></div>

- <div><span>Corrigimos um problema que um usuário poderia ver mensagens de erro quando as atualizações de segurança eram instaladas.</span></div>

- <div><span>Corrigimos um problema que poderia fazer com que o cursor desaparecesse.</span></div>

- <div><span>Corrigimos um problema que um usuário poderia ser padronizado para a guia Desenhar, em vez da guia Página Inicial</span></div>

- <div><span>Corrigimos um problema que grandes modos de exibição em árvore poderiam resultar em falha.</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Corrigimos um problema que poderia causar solicitações de senha.</span>

- <div><span>Corrigimos um problema que poderia impedir que um endereço de email fosse consultado corretamente.</span></div>

- <div><span>Corrigimos um problema que poderia impedir que os usuários abrissem os itens de calendário criados pelas versões herdadas do Outlook.</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Corrigimos um problema que poderia impedir a inicialização de algumas animações.</span></div>

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

### <a name="word"></a>Word

- <div><span>Corrigimos um problema que as respostas aos comentários poderiam ser exibidas fora de ordem.</span></div>

- <div><span>Corrigimos um problema que, em algumas situações, as dicas eram exibidas em vez de comentários.</span></div>

- <div><span>Corrigimos um problema que o painel Revisões poderia ser exibido quando o usuário tentasse adicionar um novo comentário.</span></div>

- <div><span>Corrigimos um problema que poderia impedir a exibição de desfazer lista suspensa.</span></div>

- <div><span>Corrigimos um problema que poderia impedir a adição de novos comentários</span></div>


## <a name="july-26-2019"></a>26 de julho de 2019
Versão 1908 (Build 11916.20000)

## <a name="whats-new"></a>O que há de novo:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="create-more-accessible-pdfs"></a>Criar PDFs mais acessíveis

Crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="all"></a>Todos

- Consertamos um problema em que a associação de tipo de arquivo e os ícones do Office poderiam, às vezes, quebrar após uma atualização do Office.

### <a name="word"></a>Word 
- Correções diversas de desempenho e estabilidade

### <a name="excel"></a>Excel
- Consertamos um problema em que uma mudança de gráfico poderia resultar em uma falha.
- Consertamos um problema onde obter o objeto de pasta de trabalho do objeto de Gráfico após alterar os tipos de gráfico, algumas vezes poderia resultar em um erro

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Consertamos um problema em que, na faixa de opções simplificada, um controle desabilitado poderia, às vezes, não estar acinzentado na faixa de opções.

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="july-19-2019"></a>19 de julho de 2019
Versão 1908 (Build 11911.20000)

## <a name="whats-new"></a>O que há de novo:

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>Saiba o significado de Acrônimos ao ler no Word Online

Quando houver um acrônimo, tentaremos defini-lo usando dados de dentro da sua organização.


## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="word"></a>Word 
- Consertamos um problema em que a marca BookMarkEnd estava ausente.
- Consertamos um problema que poderia fazer com que a seleção de fonte mudasse enquanto o usuário digitava caracteres especiais.
- Consertamos um problema que poderia gerar respostas em branco a um novo cartão de comentário.
- Consertamos um problema que poderia causar a perda de formatação durante o compartilhamento de um email.

### <a name="excel"></a>Excel
- Consertamos um problema em que uma matriz com um intervalo grande poderia causar falha.
- Melhoramos significativamente o desempenho da cópia de dados de intervalos filtrados.
- Resolvemos um problema que impedia que alguns arquivos fossem abertos, caso seus nomes possuíssem caracteres especiais.

### <a name="powerpoint"></a>PowerPoint
- Consertamos um problema em que o nome da seção não houvesse sido selecionado por padrão para a seção recém-criada no PowerPoint.
- Consertamos um problema que poderia fazer com que a IU se tornasse difícil de usar em uma exibição 4:3.

### <a name="outlook"></a>Outlook
- Consertamos um problema que poderia impedir a listagem de salas disponíveis.
- Consertamos um problema que impedia a formatação HTML para alguns usuários POP3.

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="july-12-2019"></a>12 de julho de 2019
Versão 1907 (build 11901.20038)

## <a name="whats-new"></a>O que há de novo:

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>Usar a reprodução de tinta em suas apresentações
 
Aplique uma animação de reprodução para tinta no PowerPoint para se expressar e se comunicar mais nas apresentações. 

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Correções diversas de desempenho e estabilidade

### <a name="excel"></a>Excel
- Correções diversas de desempenho e estabilidade

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Correções diversas de desempenho e estabilidade

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="july-5-2019"></a>5 de julho de 2019
Versão 1907 (build 11901.20018)

## <a name="whats-new"></a>O que há de novo:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="sketchy-shapes"></a>Formas de Esboço!

Elaborando uma apresentação? Aplique o estilo de esboço para mostrar que você ainda está trabalhando nele. Ele dá um toque pessoal aos seus objetos sem transformá-los em uma forma livre ou com aparência de desenhados à mão.

### <a name="excel"></a>Excel

- **Compartilhamento rápido de arquivos**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.
### <a name="powerpoint"></a>PowerPoint

- **A configuração para imprimir números de slide em folhetos foi movida para o menu Imprimir para facilitar o acesso : **Encontre-o na lista suspensa imprimir > layout de impressão quando um layout de folheto estiver selecionado. Isso também facilita a alternância de configurações por apresentação. [Saiba Mais](https://support.office.com/pt-BR/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.

### <a name="word"></a>Word

- **Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all"></a>Todos
- Melhoramos significativamente o desempenho das dicas de ferramentas da faixa de opções.
- Corrigimos um problema que impedia que a caixa de diálogo “Veja as novidades que chegam em breve” fosse exibida corretamente.
- Corrigimos um problema que pode fazer com que as fotos ficassem desalinhadas no submenu da Galeria de coautenticação

### <a name="word"></a>Word 
- Corrigimos um problema que, às vezes, podia impedir que novos comentários fossem adicionados
- Corrigimos um problema em que as tabelas poderiam causar falha
- Corrigimos um problema em que os dados inválidos podiam, às vezes, ser adicionados ao final de uma mala direta.
- Corrigimos um problema que podia fazer que algumas equações LaTeX fossem processadas incorretamente

### <a name="excel"></a>Excel
- Corrigimos um problema em que alteração dos tipos de gráfico poderia resultar uma exceção de tempo de execução
- Corrigimos um problema em que a faixa de opções incorreta poderia ser exibida quando várias janelas eram abertas
- Corrigimos um problema que poderia causar um erro quando uma macro abria uma segunda instância da pasta de trabalho
- Corrigimos um problema que poderia causar uma falha ao abrir ou criar uma pasta de trabalho ou ao alternar entre pastas de trabalho
- Corrigimos um problema que impedia que os usuários abrissem um PDF criado no Word no Teams

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema que podia prejudicar a qualidade de um gráfico quando exportado como um pdf
- Corrigimos um problema que impedia a exibição de uma dica de ferramenta indicando a distância até o centro

### <a name="outlook"></a>Outlook
- Corrigimos um problema que poderia impedir a exibição de um erro de Disco Cheio
- Corrigimos um problema que poderia causar a duplicação de anexos durante a atualização de uma solicitação de reunião

### <a name="access"></a>Access
- Corrigimos um problema que impedia algumas consultas de retornar valores inteiros grandes
- Corrigimos um problema que poderia tornar a caixa de texto SQL não editável
- Corrigimos um problema em que as dicas de ferramentas poderiam ser difíceis de ver em alguns monitores de DPI Alto

### <a name="project"></a>Project
- Corrigimos um problema que poderia fazer com que os valores de sinalizador se tornassem não editáveis em novas tarefas
- Corrigimos um problema que poderia fazer que uma atualização de status definisse incorretamente a Data de Início Real em Atribuições e Tarefas
- Corrigimos um problema que poderia fazer com que alguns recursos aparecessem incorretamente como superalocados
- Corrigimos um problema em que o método Adicionar TaskDependencies poderia falhar quando o Retardo era adicionado, quando o separador decimal era uma vírgula e quando conectado a um servidor
- Corrigimos um problema em que a atualização de valores de tabela de pesquisa do campo personalizado local por meio do CSOM poderia ser PCS
- Corrigimos um problema em que os valores de trabalho total apareciam incorretos se contivessem um número decimal

</BR></BR>

## <a name="june-28-2019"></a>28 de junho de 2019
Versão 1907 (build 11819.20002)

## <a name="whats-new"></a>O que há de novo:

### <a name="excel"></a>Excel

- **Códifique rapidamente com as melhorias do Power Query:** chegue rapidamente à conclusão de código com as cores de sintaxe e o preenchimento automático. Também descubra facilmente funções, colunas e parâmetros

- **Una tabelas em colunas similares:** Obter e Transformar (Power Query) agora apresenta lógica de texto correspondente aproximado (também chamada de correspondência difusa) ao comparar colunas para mesclar tabelas.

### <a name="word"></a>Word

- **Melhorias na coautoria** Confiabilidade aprimorada durante a coautoria.
 
### <a name="word-excel-powerpoint-and-visio"></a>Word, Excel, PowerPoint e Visio

#### <a name="recommended-documents"></a>Documentos Recomendados

Encontre documentos com atividades relevantes recomendadas para você.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema que poderia impedir que alguns arquivos .DOC fossem abertos
- Corrigimos um problema que poderia impedir o carregamento correto de comentários

### <a name="excel"></a>Excel
- Melhoramos o desempenho de Power Queries

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema relacionado ao uso de uma caneta em um dispositivo Surface que poderia fazer a tela piscar

### <a name="outlook"></a>Outlook
- Corrigimos um problema que poderia alterar o status de disponibilidade de um compromisso quando convertido em uma reunião
- Corrigimos um problema onde o modelo e a descrição errados eram exibidos quando um e-mail estava protegido com um modelo ad hoc

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="june-21-2019"></a>21 de junho de 2019
Versão 1907 (build 11815.20002)

## <a name="whats-new"></a>Novidades:

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Modo Escuro para Tema Preto no Outlook Desktop

Com o modo escuro, usuários com o tema preto conseguirão ver o painel de leitura em uma tela de fundo escura ao ler emails, e a experiência de composição em uma tela de fundo escura ao escrever emails. Há um botão de alternância sol/lua no painel de leitura e na faixa de opções, caso os usuários queiram visualizar como a mensagem ficaria em um fundo claro.

#### <a name="getting-started"></a>Introdução:

1. Ative o tema preto e o modo escuro será habilitado por padrão.
2. Uso o botão de alternância lua/sol (no painel de leitura e na faixa de opções) para visualizar como a mensagem ficaria para usuários que não estão no modo escuro

#### <a name="scenarios-to-try"></a>Cenários possíveis

1. Ler emails no modo escuro. Se você não conseguir ler algo, use o botão de alternância de sol no Painel de Leitura para alternar para uma tela de fundo clara. 
2. Escrever emails no modo escuro. Visualize como a mensagem ficará em uma tela de fundo clara usando o botão de alternância sol na faixa de opções. 

Se você encontrar emails que não foram processados corretamente, envie-os (como anexo) para OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>Obter sugestões de local

Comece a digitar e o Outlook procurará por locais correspondentes.

Isso se aplica ao campo Local ao criar Compromissos e Reuniões.

#### <a name="getting-started"></a>Introdução:

- Criar um Compromisso ou Reunião em um O365 ou calendário Outlook.com no Outlook. 
- Clique no campo Local e comece a digitar...

#### <a name="scenarios-to-try"></a>Cenários possíveis

Ao adicionar uma sala de conferência a uma reunião, clique no campo Local em vez de usar o suplemento Localizador de Salas ou Catálogo de Endereços.
Para compromissos em um local físico com um local público como um restaurante, cafeteria ou até mesmo o consultório do dentista, tente encontrar o local exato usando o novo seletor. Dessa forma, você poderá receber notificações no Outlook Mobile quando chegar a hora de sair.

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="all"></a>Todos
- Corrigimos um problema que mantinha a Caixa de Pesquisa habilitada enquanto offline

### <a name="word"></a>Word 
- Corrigimos um problema onde o foco do teclado ficava difícil de ver
- Corrigimos um problema onde o texto copiado em um novo documento ficava com o alinhamento de texto errado
- Corrigimos um problema que impedia que alguns usuários salvassem alterações depois de suspender o computador
- Corrigimos um problema em que em determinados casos um documento inteiro era impresso em vez do intervalo selecionado
- Corrigimos um problema que tornava comentários difíceis de ler em telas menores
- Corrigimos um problema que causava uma falha ao capturar um dispositivo.

### <a name="excel"></a>Excel
- Correções diversas de desempenho e estabilidade

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema onde o foco do teclado ficava difícil de ver

### <a name="outlook"></a>Outlook
- Corrigimos um problema que exibia um suplemento incorretamente como habilitado quando não estava.
- Corrigimos um problema que impedia que um cliente visualizasse todas as políticas de retenção se houvesse um grande número delas

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="june-14-2019"></a>14 de junho de 2019
Versão 1907 (build 11807.20000)

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema que impedia que um usuário fizesse logon ao salvar no OneDrive
- Corrigimos um problema em que um usuário era impedido de alterar as propriedades do SharePoint enquanto estava no modo de acesso restrito
- Corrigimos um problema em que o conteúdo do cabeçalho e do rodapé mudava ao ajustar as margens
- Corrigimos um problema em que a formatação era interrompida ao alternar para a exibição da Web
- Corrigimos um problema que impedia que um usuário usasse campos personalizados quando abertos a partir do SharePoint

### <a name="excel"></a>Excel
- Corrigimos um problema de desempenho ao excluir linhas de um conjunto filtrado
- Corrigimos um problema que, às vezes, fazia o mouse piscar na exibição protegida
- Corrigimos um problema que poderia ter causado uma falha ao excluir uma série
- Corrigimos um problema em que alguns usuários tinham a opção de adicionar o histórico de versões quando isso não estava disponível
- Corrigimos um problema que poderia ter causado uma exceção ao usar a ferramenta Comparação de planilhas

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema em que ocorria uma falha ao clicar em um link para o SharePoint
- Corrigimos um problema que poderia levar o usuário para a próxima página durante a digitação usando uma Caneta Surface.

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que, em alguns casos, o campo Para era maior que o normal

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="june-7-2019"></a>7 de junho de 2019
Versão 1907 (build 11727.20064)

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema em que o Word às vezes travava quando a correção automática estava definida para colocar em maiúscula a primeira letra de uma frase.
- Melhoramos o desempenho ao editar um documento no SharePoint
- Corrigimos um problema em que imagens baseadas em vetores criadas no Adobe Illustrator não eram exibidas corretamente

### <a name="excel"></a>Excel
- Corrigimos um problema em que os campos de classificação às vezes não eram definidos corretamente ao gravar uma macro
- Corrigimos um problema que causa travamento ou falha durante o recálculo de uma fórmula de matriz

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que os anexos embutidos às vezes eram dimensionados incorretamente

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Corrigimos um problema em que quadros de horários em um período fixo às vezes alteravam a data de término da atribuição
- Corrigimos um problema em que os valores de Porcentagem Concluída poderiam estar errados ao abrir um projeto de uma versão anterior

</BR></BR>

## <a name="may-31-2019"></a>31 de maio de 2019
Versão 1906 (build 11722.20008)

## <a name="whats-new"></a>Novidades:

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>Caixa de diálogo para Entrar em Contato com o Suporte agora é acoplável e aparece à direita

A caixa de diálogo usada para Entrar em contato com o suporte aparecerá em um painel à direita e iniciará como uma janela acoplável.

#### <a name="ink-in-your-email"></a>Tinta em seu email!

Agora, você pode desenhar e fazer anotações em seus emails do Outlook.

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>Abrir links de documentos no Word

Ao clicar em um link de documento no office, você pode atualizar suas preferências para abrir o aplicativo do Word por padrão.  Para atualizar suas preferências, vá até Arquivo->Opções->Avançado->Tratamento de Links. Saiba mais: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Introdução:

O recurso padrão será desativado. Os usuários podem habilitá-lo por meio de configuração Opções->Avançado->Tratamento de Links ou podem aceitar quando os aplicativos Win32 WXP os levam em uma experiência de aceitação.
Quando os usuários clicam em links para arquivos do Word/PowerPoint/Excel armazenados no OneDrive/OneDrive for Business/SharePoint do Outlook/Word/PowerPoint/Excel, esses links serão abertos no aplicativo apropriado do Office, em vez do navegador, por padrão.

Para alterar esse padrão, os usuários podem atualizar a configuração a seguir no Outlook/Word/Excel/PowerPoint:

Arquivo->Opções->Avançado->Tratamento de Links

Essa configuração é compartilhada entre o Outlook/Word/PowerPoint/Excel e pode ser definida em qualquer um desses aplicativos.

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Para acionar a experiência de aceitação: abrir um link tot um documento do Word armazenado no OneDrive/SharePoint do Outlook/Word/PowerPoint/Excel; clique em abrir no cliente do Office Online. Faça isso duas vezes em um período de 30 dias. Após aceitar, os links serão abertos nos aplicativos Win32 por padrão.

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>Abrir links de apresentação no PowerPoint

Ao clicar em um link de apresentação no Office, você pode atualizar suas preferências para abrir o aplicativo do PowerPoint por padrão. Para atualizar suas preferências, vá até Arquivo->Opções->Avançado->Tratamento de Links. Saiba mais: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Introdução:

O recurso padrão será desativado. Os usuários podem habilitá-lo por meio de configuração Opções->Avançado->Tratamento de Links ou podem aceitar quando os aplicativos Win32 WXP os levam em uma experiência de aceitação.
Quando os usuários clicam em links para arquivos do Word/PowerPoint/Excel armazenados no OneDrive/OneDrive for Business/SharePoint do Outlook/Word/PowerPoint/Excel, esses links serão abertos no aplicativo apropriado do Office, em vez do navegador, por padrão.

Para alterar esse padrão, os usuários podem atualizar a configuração a seguir no Outlook/Word/Excel/PowerPoint:

Arquivo->Opções->Avançado->Tratamento de Links

Essa configuração é compartilhada entre o Outlook/Word/PowerPoint/Excel e pode ser definida em qualquer um desses aplicativos.

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Para acionar a experiência de aceitação: abra um link para uma apresentação do PowerPoint armazenada no OneDrive/SharePoint do Outlook/Word/PowerPoint/Excel; clique em abrir no cliente do Office Online. Faça isso duas vezes em um período de 30 dias. Após aceitar, os links serão abertos nos aplicativos Win32 por padrão.

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>Abrir links de pasta de trabalho no Excel

Ao clicar em um link de pasta de trabalho no Office, você pode atualizar suas preferências para abrir o aplicativo do Excel por padrão. Para atualizar suas preferências, vá até Arquivo->Opções->Avançado->Tratamento de Links. Saiba mais: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Introdução:

O recurso padrão será desativado. Os usuários podem habilitá-lo por meio de configuração Opções->Avançado->Tratamento de Links ou podem aceitar quando os aplicativos Win32 WXP os levam em uma experiência de aceitação.
Quando os usuários clicam em links para arquivos do Word/PowerPoint/Excel armazenados no OneDrive/OneDrive for Business/SharePoint do Outlook/Word/PowerPoint/Excel, esses links serão abertos no aplicativo apropriado do Office, em vez do navegador, por padrão.

Para alterar esse padrão, os usuários podem atualizar a configuração a seguir no Outlook/Word/Excel/PowerPoint:

Arquivo->Opções->Avançado->Tratamento de Links

Essa configuração é compartilhada entre o Outlook/Word/PowerPoint/Excel e pode ser definida em qualquer um desses aplicativos.

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Para acionar a experiência de aceitação: abra um link para uma pasta de trabalho do Excel armazenada no OneDrive/SharePoint do Outlook/Word/PowerPoint/Excel; clique em abrir no cliente do Office Online. Faça isso duas vezes em um período de 30 dias. Após aceitar, os links serão abertos nos aplicativos Win32 por padrão.

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="all"></a>Todos
- Corrigimos um problema onde, às vezes, os arquivos poderiam ser salvos automaticamente mesmo quando o salvamento automático estava desabilitado

### <a name="word"></a>Word 
- Corrigimos um problema que pode ter impedido alguns usuários de salvar no SharePoint

### <a name="excel"></a>Excel
- Corrigimos um problema onde um ícone incorreto poderia ser exibido para filtros inativos

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Corrigimos um problema onde alguns usuários apareciam incorretamente como Offline em um modo de exibição de Agenda de Grupo
- Corrigimos um problema que impediu que o SafeLink analisasse uma URL com espaços à direita
- Corrigimos um problema onde salas eram exibidas como disponíveis em períodos de folga

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="may-24-2019"></a>24 de maio de 2019
Versão 1906 (Build 11715.20002)

## <a name="whats-new"></a>Novidades:

#### <a name="user-experience-updates"></a>Atualizações da Experiência do Usuário

As atualizações que estiveram em Em Breve agora estão prontas, apresentando a Faixa Simplificada e uma atualização visual do painel de pastas, lista de mensagens e painel de leitura.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all"></a>Todos

- Corrigimos um problema em que o painel de chat não era exibido.

### <a name="word"></a>Word 
- Corrigimos um problema em que, em alguns casos, o Word realçava o texto incorretamente para erros gramaticais

### <a name="excel"></a>Excel
- Corrigimos um problema em que um ícone incorreto foi usado nos Elementos do Gráfico.
- Corrigimos um problema em que a pasta de trabalho incorreta poderia ser ativada em um script VBA quando a mesma pasta de trabalho já estava aberta

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Correções diversas de desempenho e estabilidade

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Corrigimos um problema onde o Project podia falhar após alternar para a barra de tarefas.

</BR></BR>

## <a name="may-17-2019"></a>17 de maio de 2019
Versão 1906 (build 11708.20006)

## <a name="whats-new"></a>Novidades:

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>Atualizações da Experiência do Usuário

As atualizações que estiveram em Em Breve agora estão prontas, apresentando a Faixa Simplificada e uma atualização visual do painel de pastas, lista de mensagens e painel de leitura.

##### <a name="getting-started"></a>Introdução:

Essas alterações farão parte da nova interface do usuário padrão; está disponível sob a opção "Em Breve" desde meados de dezembro para 100% prod

#### <a name="customizable-simplified-ribbon"></a>Faixa Simplificada Personalizável

Facilmente personalizável para alternar entre visualizações clássicas e simplificadas e comandos de fixar/desafixar.

##### <a name="getting-started"></a>Introdução:

Os usuários podem acessar a faixa simplificada ativando Em Breve (inicialmente) e clicando na divisa na faixa de opções para alternar entre a faixa clássica de várias linhas e a nova faixa simplificada de linha única.

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Mudar de faixa clássica para faixa simplificada

#### <a name="pick-your-favorite-action"></a>Escolha sua ação favorita

Não usar Sinalizar e Excluir? E quanto a Arquivar ou Marcar como Lida? Personalize o menu de ação rápida com os comandos que você mais usa.

##### <a name="getting-started"></a>Introdução:

Para selecionar suas Ações Rápidas, clique com o botão direito do mouse em um email na lista de mensagens para abrir o Menu de Contexto. Em seguida, clique em "Definir ações rápidas..."

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Altere os padrões de sinalizar e excluir para ou arquivar, mover, marcar como lido, ou nenhum, para obter uma lista de mensagens mais limpa

#### <a name="relaxed-or-tighter-layout-you-choose"></a>Layout espaçado ou mais ajustado? Você escolhe

Usar Espaçamento Menor permite que você decida se quer mais espaço entre os itens ou um layout mais justo para ver mais.

##### <a name="getting-started"></a>Introdução:

Guia Exibir, caixa de seleção usar espaçamento menor - no grupo de Mensagens para a faixa de opções clássica, configurações da Exibição Atual para faixa de opções simplificada

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Use o Outlook para fazer triagem e escrever emails com e sem a configuração habilitada. Com o uso do espaçamento menor, mais mensagens cabem por página e os controles nos formulários de redação são mais simplificados.

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>Eliminar entradas duplicadas de MRU ao usar o cliente de sincronização do OneDrive

Permita uma melhor integração com o cliente de sincronização do OneDrive com anexos na nuvem, eliminando as entradas duplicadas de MRU e permitindo anexar como cópia mais rapidamente para dados sincronizados.

##### <a name="getting-started"></a>Introdução:

Se você usar o cliente de sincronização do OneDrive, não verá mais duplicatas de arquivo no MRU de Anexo de Arquivos.

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Habilite o cliente de sincronização do OneDrive e use o menu Anexar Arquivo no Outlook para a área de trabalho

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>Sincronização de pastas compartilhadas aprimorada para caixas de correio com muitas pastas

Por anos, o Outlook foi limitado a um máximo de 500 pastas ao sincronizar caixas de correio compartilhadas. Com essa alteração, a sincronização do Outlook foi aprimorada, de maneira que não se encontrará mais esse limite de 500 pastas.

##### <a name="getting-started"></a>Introdução:

Crie 1000 pastas em uma caixa de correio, dê a outra pessoa acesso à caixa de correio, crie um perfil do Outlook para "outra pessoa" e verifique se a sincronização funciona.

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>Apague só um pouquinho

##### <a name="getting-started"></a>Introdução:

Vá para a guia Desenhar. Selecione o menu suspenso Borracha. Escolha Borracha Pequena ou Borracha Média.

##### <a name="scenarios-to-try"></a>Cenários possíveis:

Vá para a guia Desenhar. Selecione uma caneta. Desenhe um traço de tinta. Selecione o menu suspenso Borracha. Escolha Borracha Pequena ou Borracha Média. Apague apenas pedaços do traço de tinta.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all"></a>Todos 
- Corrigimos um problema que impedia que alguns usuários salvassem como PDF
- Corrigimos um problema que afetava os usuários salvando arquivos grandes em um sistema de 32 bits

### <a name="word"></a>Word 
- Melhoramos significativamente a capacidade de resposta do recurso de ditado

### <a name="excel"></a>Excel
- Corrigimos um problema em que os eventos de duplo clique falhavam nos dispositivos de tela sensível ao toque
- Corrigimos um problema que impedia que alguns usuários pudessem editar macros do VBA
- Corrigimos um problema que afetava o desempenho ao usar segmentações de dados

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que o modelo errado era exibido a partir do que estava selecionado

### <a name="access"></a>Access
- Corrigimos um problema em que o construtor de zoom para exibir rich text longo era difícil de ler

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="may-10-2019"></a>10 de maio de 2019
Versão 1906 (build 11702.20000)

## <a name="whats-new"></a>O que há de novo:

### <a name="outlook"></a>Outlook

**Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all"></a>Todos
- Corrigimos um problema em que a caixa de diálogo Salvar Como exibia o caminho incorreto

### <a name="word"></a>Word 
- Corrigimos um problema em que algumas seleções do Diga-me não eram inseridas

### <a name="excel"></a>Excel
- Correções diversas de desempenho e estabilidade

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Correções diversas de desempenho e estabilidade

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Corrigimos um problema em que os IDs de tarefas poderiam exigir ser destacados para exibição

</BR></BR>

## <a name="may-3-2019"></a>3 de maio de 2019
Versão 1906 (build 11629.20008)

## <a name="whats-new"></a>O que há de novo:

### <a name="outlook"></a>Outlook

**Todas as opções de criptografia em um só lugar:** Basta ir em Opções > Criptografar para escolher como proteger sua mensagem de email.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all"></a>Todos
- Corrigimos um problema em que alguns usuários enfrentavam problemas ao sincronizar com o OneDrive for Business

### <a name="word"></a>Word 
- Corrigimos um problema em que, em alguns casos, o Word levava muito tempo para começar

### <a name="excel"></a>Excel
- Corrigimos um problema em que os links externos às vezes eram removidos das pastas de trabalho após a atualização para uma versão mais recente do Excel
- Corrigimos um problema em que alguns usuários podiam ter dificuldade em selecionar células em uma nova pasta de trabalho.

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema em que os tamanhos de fonte não eram consistentes ao converter desenhos em texto

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que salvar um contato de um arquivo .VCF resultava em campos vazios
- Corrigimos um problema em que uma mensagem ficava presa na pasta de caixa de saída, embora ela tivesse sido enviada
- Corrigimos um problema em que o Outlook falhava ao exibir uma mensagem DRM

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Corrigimos um problema em que o editor mudava de chinês para inglês
- Corrigimos um problema em que tarefas não publicadas apareciam na cópia publicada de um projeto principal

</BR></BR>

## <a name="april-26-2019"></a>26 de abril de 2019
Versão 1905 (build 11617.20002)

## <a name="new-features"></a>Novos Recursos

### <a name="outlook"></a>Outlook

**As tualizações de calendário compartilhadas ficaram mais rápidas**: No caso de calendários compartilhados no Office 365, o Outlook pode atualizá-los usando a API REST. Ative a visualização para atualizações mais rápidas e confiáveis de calendários compartilhados.

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>Melhorias de coautoria

Melhor experiência de coautoria, tornando mais provável que as alterações de conteúdo sejam recebidas por outras pessoas em tempo real.

### <a name="visio"></a>Visio

- **Exportar elementos visuais do Visio a partir do Power BI:** Os elementos visuais do Visio para o Power BI agora estão sendo exibidos corretamente ao exportar relatórios do Power BI como PDFs, arquivos do PowerPoint e muito mais.

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="word"></a>Word 
- Correções diversas de desempenho e estabilidade

### <a name="excel"></a>Excel
- Corrigimos um problema em que as macros do Solver não funcionavam
- Corrigimos um problema que impedia que arquivos do Excel fossem importados para o SharePoint

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Correções diversas de desempenho e estabilidade

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="april-19-2019"></a>19 de abril de 2019
Versão 1905 (build 11609.20002)

## <a name="whats-new"></a>O que há de novo:

### <a name="outlook"></a>Outlook

**Obter sugestões de email ao procurar por alguém:** Quando você digitar o nome de uma pessoa na Caixa de pesquisa, os emails mais relevantes serão incluídos nas sugestões de pesquisa.

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>Experiência de Mapas Preenchidos aprimorados usando Tipos de Dados


Este recurso é uma melhoria para usuários que plotam Gráficos de Mapa Preenchido usando Tipos de Dados Geográficos do Excel. O benefício aos usuários finais será uma integração mais avançada entre os recursos e uma maior precisão da região que o usuário final deseja mapear. Benefícios adicionais incluem - capacidade de mapear polígonos de cidade.

##### <a name="getting-started"></a>Introdução:

- Este recurso é uma melhoria dos recursos existentes no Excel. Para usar a melhoria - Converta locais em Entidades Avançadas e plotagem com Mapas Preenchidos. 

##### <a name="scenarios-to-try"></a>Cenários possíveis:

- Os usuários podem experimentar o mapeamento de cidades, estados, municípios, países/regiões e códigos postais. 


## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all-applications"></a>Todos os Aplicativos
- Corrigimos um problema em que a caixa de diálogo de Primeira Execução era exibida sempre que um aplicativo era iniciado
- Corrigimos um problema em que um link do SharePoint na caixa de diálogo "salvar como" poderia estar ausente.
- Corrigimos um problema em que os usuários poderiam ver incorretamente uma caixa de diálogo "Corrigir Agora"

### <a name="word"></a>Word 
- Corrigimos um problema em que alguns usuários poderiam receber um erro de memória insuficiente ou de espaço em disco ao solicitar uma fonte
- Corrigimos um problema em que uma janela poderia perder o foco ao migrar do painel de comentários

### <a name="excel"></a>Excel
- Correções diversas de desempenho e estabilidade

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema impedindo o redimensionamento de formas com marca
- Corrigimos um problema em que o PowerPoint poderia falhar ao abrir um arquivo no modo de exibição protegido

### <a name="outlook"></a>Outlook
- Corrigimos um problema que impedia alguns usuários de selecionar palavras em chinês.
- Corrigimos um problema em que as datas de expiração não eram calculadas corretamente

### <a name="access"></a>Access
- Corrigimos um problema que impedia alguns usuários de usar o Construtor de Macros
- Corrigimos um problema em que ao imprimir um relatório só era impresso a primeira página
- Corrigimos um problema em que o aplicativo poderia falhar ao focalizar um hiperlink
- Corrigimos um problema que fazia com que alguns itens aparecessem fora da tela ao usar a exibição de relações

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="april-12-2019"></a>12 de abril de 2019
Versão 1905 (build 11601.20042)

## <a name="whats-new"></a>Novidades:

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>Fique inteligente com o Microsoft Graph

Importar ou vincular dados inteligentes e reinventar a área de trabalho banco de dados com a tecnologia inteligente.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="all-applications"></a>Todos os Aplicativos
 - Corrigimos um problema que impedia que alguns usuários salvassem arquivos em locais de nuvem
 - Corrigimos um problema em que o painel errado abria a partir da faixa de opções

### <a name="word"></a>Word 
- Correções diversas de desempenho e estabilidade

### <a name="excel"></a>Excel
- Corrigimos um problema em que os usuários viam uma mensagem de erro para tipos de dados vinculados quando a pasta de trabalho não continha tipos de dados vinculados
- Corrigimos um problema em que os links de URL em um documento do Word eram alterados quando visualizados localmente versus online.

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema em que o aplicativo travava depois de desfazer as alterações da guia "animações"

### <a name="outlook"></a>Outlook
- Corrigimos um problema que impedia que alguns usuários modificassem o campo de Anotações para contatos em uma Pasta Pública.
- Corrigimos um problema em que um conflito ocorria entre as datas de expiração e as datas de exclusão

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="april-5-2019"></a>5 de abril de 2019
Versão 1904 (build 11527.20014)

## <a name="whats-new"></a>Novidades:

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Outlook for Windows:  definir e compartilhar as configurações da Caixa de Entrada Destaques

Suas preferências da Caixa de Entrada Destaques são armazenadas na nuvem para que você possa aproveitar a mesma experiência consistente ao usar o Outlook para Windows e o Outlook na Web em qualquer computador.

#### <a name="getting-started"></a>Introdução:

Na guia Arquivo > Opções > Geral, há uma nova preferência para 'Armazenar minhas configurações do Outlook na nuvem'. Os usuários precisarão marcar a caixa para permitir que sua configuração da Caixa de Entrada Destaques seja transferida para outras instalações do Outlook para Área de Trabalho e para o OWA.

#### <a name="scenarios-to-try"></a>Cenários possíveis:

Altere a Caixa de Entrada Destaques na máquina que esteja com a preferência de configurações de nuvem ativada. Navegue até OWA e confira a preferência aplicada também. Alterar a Caixa de Entrada Destaques no OWA e iniciar o Office para Área de Trabalho para ver a preferência refletida.

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>O modo Ferramentas de Aprendizagem tem suporte adicional para mais cores de página

As ferramentas de aprendizagem no Word adicionam suporte para mais cores de tema de página, o que permite a alteração da cor da tela de fundo da página.  Várias pessoas têm desafios de leitura com um plano de fundo todo branco ou preto, então ampliamos as opções de cores no Word para PC e para Mac.

#### <a name="getting-started"></a>Introdução:

Para experimentar isso, vá para a guia Exibir e escolha Ferramentas de Aprendizagem e, em seguida, Cor da Página.

#### <a name="scenarios-to-try"></a>Cenários possíveis:

Para experimentar isso, vá para a guia Exibir e escolha Ferramentas de Aprendizagem e, em seguida, Cor da Página.

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>Elevar a Criatividade com Modelos 3D Animados

O Office agora dá suporte a modelos animados, que serão reproduzidos no editor, para que você possa dar vida às suas planilhas!

#### <a name="getting-started"></a>Introdução:

1. Abra o Excel.
2. Insira um Modelo 3D animado (chegará em breve ao Remix, mas por enquanto, acesse os modelos animados aqui: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)
3. O modelo animado será reproduzido no editor! Verificar o Modo de Apresentação de slides - ele também será reproduzido!
4. Na Faixa de Opções do formato 3D, explore mais cenas de animação no modelo

#### <a name="scenarios-to-try"></a>Cenários possíveis:

1. Inserir um modelo animado e ver a reprodução no editor
2. Explore as cenas de animação disponíveis no modelo animado através da Galeria de Cenas, disponível na Faixa de Opções de Formato 3D.
3. Reproduza/pause facilmente a animação pela faixa de opções, barra flutuante ou barra de espaço.

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="all-applications"></a>Todos os Aplicativos
- Corrigimos um problema em que um ícone incorreto do aplicativo aparecia em menus contextuais no Excel
- Corrigimos um problema em que o botão do menu Arquivo desaparecia após a instalação de uma atualização
- Corrigimos um problema que poderia alterar sua licença de usuário

### <a name="word"></a>Word 
- Corrigimos um problema em que o texto não era renderizado corretamente em determinados níveis de zoom

### <a name="excel"></a>Excel
- Corrigimos um problema em que não era solicitado que os usuários salvassem uma pasta de trabalho depois de fazer edições
- Corrigimos um problema em que um evento BeforeSave não era acionado se o usuário compartilhasse a pasta de trabalho.
- Corrigimos um problema em que redimensionar uma coluna para menos de 6 pixels poderia gerar uma mensagem de erro incorreta.
- Corrigimos um problema em que o Excel ignorava o sinalizador Application.Visible.
- Corrigimos um problema em que as setas rastreadoras permaneciam em painéis congelados não ativos
- Corrigimos um problema em que a formatação de células de datas e moedas era alterada ao se abrir uma pasta de trabalho
- Corrigimos um problema em que as dicas de ferramenta se moviam inesperadamente
- Corrigimos problemas de localização para o editor do Power Query
- Corrigimos um problema em que uma pasta de trabalho era removida dos anexos ao ser enviada por email

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema em que a cópia de formas demorava mais do que o esperado

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que o Outlook travava ao se usar a ferramenta de desenho
- Corrigimos um problema de localização ao compor emails em html
- Corrigimos um problema em que o usuário tinha dificuldade em selecionar o painel inferior

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="march-22-2019"></a>22 de março de 2019
Versão 1904 (build 11514.20004)

## <a name="new-features"></a>Novos recursos

- **Controles de privacidade:** controles novos, atualizados e melhorados para dados de diagnóstico e experiências conectadas. Saiba Mais <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Os produtos do Ofiice estão com um novo visual**Os ícones de produtos foram recriados para refletir as experiências simples, poderosas e inteligentes do Office.

## <a name="notable-fixes"></a>Correções Notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema em que a interface do usuário exibia constantemente "Verificando se há alterações"

### <a name="excel"></a>Excel
- Corrigimos um problema em que o aplicativo travava depois de se mover uma planilha
- Corrigimos um problema em que o aplicativo falhava após salvar como PDF
- Corrigimos um problema em que a caixa de diálogo salvar não aceitava alguns caracteres coreanos

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Correções diversas de desempenho e estabilidade

### <a name="access"></a>Access
- Corrigimos a mensagem de erro no Access em que um atalho extra para o Access era criado
- Corrigimos um problema em que dados de um SharePoint vinculado eram exibidos incorretamente

### <a name="project"></a>Project
- Corrigimos um problema em que as configurações de idioma mudavam de chinês para inglês
- Corrigimos um problema em que o aplicativo travava ao ser sincronizado com o SharePoint

</BR></BR>

## <a name="march-15-2019"></a>15 de março de 2019
Versão 1904 (build 11504.20000)

## <a name="whats-new"></a>Novidades:

### <a name="word"></a>Word

#### <a name="focus-mode"></a>Modo Foco

Alterne para o modo Foco no menu Exibir para remover distrações e se concentrar no trabalho. Somente para assinantes do Office 365.

#### <a name="getting-started"></a>Introdução:

Botão "Foco" na guia exibição no Botão "Foco" na Barra de Status da Faixa de Opções

#### <a name="scenarios-to-try"></a>Cenários possíveis:

Entrar no Modo Foco e experimentar uma Experiência Focalizada

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema em que as imagens de um documento salvo como PDF tinham DPI incorreto

### <a name="excel"></a>Excel
- Correções diversas de desempenho e estabilidade

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema em que o painel de comentários não abria ou fechava corretamente
- Corrigimos um problema em que o aplicativo falhava ao se excluir um vídeo
- Corrigimos um problema em que, em alguns casos, o aplicativo falhava em inicializar

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que as confirmações de leitura estavam incorretas quando vistas em japonês

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>

## <a name="march-8-2019"></a>8 de março de 2019 
Versão 1903 (build 11425.20036)

## <a name="whats-new"></a>O que há de novo:

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Encontre o que está procurando com a Pesquisa da Microsoft

Com a Pesquisa da Microsoft, você pode encontrar todos os arquivos, ações, pessoas e a ajuda de que precisa para realizar seu trabalho.

#### <a name="getting-started"></a>Introdução:

- O recurso é exibido em destaque na parte superior da interface do usuário, no cabeçalho.

#### <a name="scenarios-to-try"></a>Cenários possíveis:

- Pesquisar uma faculdade, um documento recente ou pesquisar os comandos da faixa de opções que você usa com mais frequência
- Procure um tópico ou assunto para obter mais informações
- 
#### <a name="coauthoring"></a>Coautoria

Cansado de ser bloqueado em documentos que contêm macros? Agora, os arquivos docm no OneDrive for Business permitem edição simultânea por vários autores.

#### <a name="getting-started"></a>Introdução:

O usuário não precisa pressionar nenhum botão da interface de usuário para acessar este recurso. Ela está habilitada por padrão em arquivos docm do OneDrive for Business.
Portanto, o usuário deve salvar um arquivo docm no OneDrive for Business para experimentar.

#### <a name="scenarios-to-try"></a>Cenários possíveis:

Crie um arquivo docm no OneDrive for Business, compartilhe-o com seus colegas e colabore!

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Nós corrigimos um problema de travamento que ocorria quando a tecla “ESC” era pressionada com o menu Opções aberto
- Corrigimos um problema de travamento que ocorria ao responder comentários
- Corrigimos um problema com a opção de copiar e colar do Word para o PowerPoint Online

### <a name="excel"></a>Excel
- Corrigimos um problema no qual, quando uma célula do Excel era copiada de um documento protegido e um documento editável estavam abertos, isso levava ao alto uso da CPU 

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que a Pesquisa do Outlook não executava a classificação cronológica selecionada
- Corrigimos um problema em que o botão “Abrir essa tarefa” da faixa de opções de fluxo de trabalho não respondia a determinados emails
- Corrigimos um problema em que Outlook não limpava salas locais depois que os usuários selecionassem uma sala disponível no Localizador de Salas

### <a name="access"></a>Access
- Corrigimos a caixa de diálogo de importação/exportação salva com texto branco em um fundo branco no tema Escuro
- Corrigimos um problema em que os usuários não conseguiam definir a propriedade de Controle de Exibição como um campo Sim/Não na Caixa de texto no design da tabela

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade


## <a name="march-1-2019"></a>1º de março de 2019 
Versão 1903 (build 11414.20014)

## <a name="whats-new"></a>Novidades

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>Cores sincronizadas para Controlar Alterações, Comentários e Colaboração em Tempo Real

Correções em nosso produto agora garantem que os comentários, o acompanhamento de alterações e o cursor de um colaborador apareçam na mesma cor.

#### <a name="getting-started"></a>Introdução:

Abrir um documento do SharePoint ou do OneDrive que outras pessoas abriram. Verifique se a cor da opção controlar alterações e dos comentários do usuário corresponde à cor do cursor desse usuário.

#### <a name="scenarios-to-try"></a>Cenários possíveis:

Abrir um documento do SharePoint ou do OneDrive que outras pessoas abriram. Verifique se a cor da opção controlar alterações e dos comentários do usuário corresponde à cor do cursor desse usuário.

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Nós corrigimos um problema de travamento que ocorria quando a tecla “ESC” era pressionada com o menu Opções aberto
- Corrigimos um problema com a opção de copiar e colar do Word para o PowerPoint Online

### <a name="excel"></a>Excel
- Corrigimos um problema no qual, quando uma célula do Excel era copiada de um documento protegido e um documento editável estavam abertos, isso levava ao alto uso da CPU 

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema com o tamanho de imagem do slide ao usar @menções no PowerPoint

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que a Pesquisa do Outlook não executava a classificação cronológica selecionada
- Corrigimos um problema em que o botão “Abrir essa tarefa” da faixa de opções de fluxo de trabalho não respondia a determinados emails
- Corrigimos um problema em que Outlook não limpava salas locais depois que os usuários selecionassem uma sala disponível no Localizador de Salas

### <a name="access"></a>Access
- Atualizamos o texto de aviso que era exibido ao confirmar tabelas de revinculação com uma fonte de dados
- Corrigimos a caixa de diálogo de importação/exportação salva com texto branco em um fundo branco no tema Escuro
- Corrigimos um problema em que os usuários não conseguiam definir a propriedade de Controle de Exibição como um campo Sim/Não na Caixa de texto no design da tabela

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>



## <a name="february-15-2019"></a>15 de fevereiro de 2019 
Versão 1903 (build 11310.20016)

## <a name="whats-new"></a>O que há de novo:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Melhorias de Transição Transformar, Transformar por Nome

Especifique as formas que você deseja transformar

#### <a name="getting-started"></a>Introdução:

- Para utilizar o Transformar para tratar dois objetos ao mesmo objeto, o usuário pode renomear as formas usando o painel seleção.
- O nome deve ser precedido por "!!" (dois pontos exclamação) para Transformar usado para substituir nosso padrão de comportamento de correspondência. Por exemplo: “!!Nome”
- Os usuários podem continuar renomeando formas com qualquer nome que não comece com “!!” sem precisar se preocupar que isso mudará a maneira como a opção Transformar funciona

#### <a name="scenarios-to-try"></a>Cenários possíveis:

- Insira uma forma em um slide, por exemplo um retângulo
- Criar um novo slide 

- Insira uma forma diferente no 2º slide, por exemplo um triângulo
- Abra SelectionPane, renomeie o retângulo do slide 1 como "!!forma" e renomeie o triângulo do slide 2 como "!!forma"
- Aplique o Transformar no 2º slide

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Melhorias de Transição Transformar, SmartArt

Transforma o SmartArt com transições mais suaves

#### <a name="getting-started"></a>Introdução:

Use o recurso Transformar da mesma maneira que faria com o SmartArt

#### <a name="scenarios-to-try"></a>Cenários possíveis:

- Insira um SmartArt em um slide
- Duplique o slide.
- Redimensione/altere/mova o SmartArt no slide duplicado
- Aplique Transformar no slide duplicado

</BR>

### <a name="morph-transition-enhancements---tables"></a>Melhorias de Transição Transformar: tabelas

Transforme tabelas com transições mais suaves

#### <a name="getting-started"></a>Introdução:
Use o recurso Transformar da mesma maneira que faria com tabelas

#### <a name="scenarios-to-try"></a>Cenários possíveis:

- Inserir uma tabela em um slide
- Duplique o slide.
- Redimensionar/alterar/mover a tabela no slide duplicado
- Aplique Transformar no slide duplicado

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher e Visio

### <a name="seamlessly-switch-between-accounts"></a>Alternar facilmente entre contas

O novo gerente de contas mostra todas as suas contas pessoais e profissionais em um só lugar, e você pode alternar facilmente entre elas. Essa experiência de atualização deixa claro em qual conta você está conectado e agora você pode alternar entre contas pessoais e profissionais sem precisar sair primeiro e sem precisar lidar com caixas de diálogo complexas.


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Cenários possíveis:
- Alternar entre contas
- Adicionar uma nova conta [anotação: talvez seja necessário acessar Arquivo | Conta | Serviços conectados e remover os serviços pessoais conectados para trabalhar as contas ou vice-versa]
- Sair de uma conta
</BR>

## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema com a visualização de contexto para tabelas e imagens

### <a name="excel"></a>Excel
- Corrigimos um problema em que o texto no campo de pesquisa do AutoFiltro está branco no tema preto
- Corrigimos um problema consentimento de interface do usuário com o novo suplemento do Office

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um problema com a exibição automática de extensão ao apresentar os SlideShows em laptops ou tablets.

### <a name="outlook"></a>Outlook
- Corrigimos um problema com a exibição do botão Enviar para o OneNote

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade


</BR></BR>
## <a name="february-11-2019"></a>11 de fevereiro de 2019
Versão 1903 (build 11330.20014)


## <a name="notable-fixes"></a>Correções notáveis:

### <a name="word"></a>Word 
- Corrigimos um problema em que alguns estilos personalizados não podiam ser aplicados ao word online
- Corrigimos problemas de visualização de contexto com objetos avançados no Word
- Corrigimos um problema em que colar listas resultava em falhas no Word

### <a name="excel"></a>Excel
- Corrigimos um problema em que os espaços anexados após formatos de número não eram mais exibidos quando não havia nenhum símbolo de moeda
- Corrigimos um problema com a detecção automática para ações

### <a name="powerpoint"></a>PowerPoint
- Correções diversas de desempenho e estabilidade

### <a name="outlook"></a>Outlook
- Correções diversas de desempenho e estabilidade

### <a name="access"></a>Access
- Correções diversas de desempenho e estabilidade

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

</BR></BR>


## <a name="february-1-2019"></a>1º de fevereiro de 2019 
Versão 1902 (build 11326.20000)


## <a name="notable-fixes"></a>Correções notáveis

### <a name="word"></a>Word 
- Corrigimos um problema ao redimensionar células em uma tabela do Excel inserida.
- Corrigimos um problema ao copiar/colar formas em uma tela de desenho

### <a name="excel"></a>Excel
- Corrigimos um problema ao abrir arquivos do Excel Web app
- Corrigimos um problema quando salvar um arquivo CSV como. XLSX resultava em uma falha devido ao tamanho do nome do arquivo
- Corrigimos o menu de contexto para exibir as opções de menu de contexto

### <a name="powerpoint"></a>PowerPoint
- Corrigimos um erro onde os usuários não conseguiam usar o atalho ctrl+alt+7/ctrl+alt+8 para inserir colchetes
- Corrigimos um problema onde inserir um vídeo local no PPT reduzia o espaço no disco rígido "C"
- Corrigimos o botão Publicar no Microsoft Stream que não era exibido para alguns usuários

### <a name="outlook"></a>Outlook
- Corrigimos um problema em que a exibição de tarefa no calendário não mostrava corretamente o assunto da tarefa

### <a name="access"></a>Access
- Corrigimos um problema de dimensionamento com gráficos

### <a name="project"></a>Project
- Várias correções de desempenho e estabilidade

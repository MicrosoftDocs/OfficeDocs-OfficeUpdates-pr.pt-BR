---
title: Notas de versão para lançamentos do Canal Semestral (Direcionado) em 2019 arquivadas
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece notas de versão aos profissionais de TI para lançamentos do Canal Semestral (Direcionado) do Office 365 ProPlus em 2019
ms.openlocfilehash: 2b9b90ef7e1d9bc792be381ba35a94f883156e90
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169600"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>Notas de versão para lançamentos do Canal Empresarial Semestral (Pré-visualização) arquivadas

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionados à segurança incluídos nas atualizações do Canal Empresarial Semestral (Pré-visualização) para o Office 365 ProPlus, o Visio Pro para Office 365, o Cliente da Área de Trabalho do Microsoft Project Online e o Office 365 Business.

> [!NOTE]
> - Muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Empresarial Semestral (Pré-visualização) durante um período de tempo. Se você não vir algo descrito abaixo, aguarde que estará em breve. [Saiba mais](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - O Microsoft Teams está incluído nas novas instalações do Canal Empresarial Semestral (Pré-visualização), começando com a Versão 1902. As equipes serão adicionadas às instalações existentes do Canal Empresarial Semestral (Pré-visualização) quando elas forem atualizadas para a Versão 1908 ou posterior. Para obter mais informações, confira [Implantar o Microsoft Teams com Office 365 ProPlus](/deployoffice/teams-install).

## <a name="version-1908-december-10"></a>Versão 1908: 10 de dezembro 
*Versão 1908 (Build 11929.20516)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Corrigido um problema em que uma consulta da União que inclui referências a tabelas remotas (por exemplo, tabelas do SQL Server) pode fazer o Access fechar e reiniciar.

- Corrigido um problema em que agregados como Soma podem truncar o resultado para um valor inteiro.

### <a name="excel"></a>Excel

- Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.

- Corrigido um problema onde o filtro de uma Tabela Dinâmica OLAP era definido como um valor que havia sido removido do cubo.

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

- Resolvido um problema em que a função Proc poderia retornar um erro.

- Melhorias significativas no desempenho da exclusão de colunas com células mescladas.

- Resolvido um problema que causava um erro no tempo de execução da macro ao ativar janelas minimizadas.

### <a name="outlook"></a>Outlook

- Corrigido um problema com a seleção de algoritmo SMIME.

- Solucionamos um problema que fazia com que usuários vissem um prompt &quot;As regras neste computador não correspondem às regras no Microsoft Exchange&quot; ao abrir a caixa de diálogo de Regras.

- Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais quando não deveriam.

### <a name="word"></a>Word

- Corrigimos um problema no controle de alterações que, às vezes, entravam em loop infinito.

### <a name="office-suite"></a>Pacote Office

- Corrigido um problema em que os caracteres katakana de meia largura não giravam corretamente nas caixas de texto verticais no PowerPoint.

- Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.

- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-november-22"></a>Versão 1908: 22 de novembro
*Versão 1908 (Build 11929.20494)*


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="access"></a>Access

- Corrigido um problema em que ao executar uma consulta de Atualização uma mensagem de erro era dada incorretamente: "A consulta está corrompida".

### <a name="excel"></a>Excel

- Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.

- Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta.

- O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.

- Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.

### <a name="outlook"></a>Outlook

- Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão &quot;OK&quot; ao tentar contatar o suporte do contexto de Criação de Conta.

- Foi feita uma alteração que permite que os administradores habilitem uma política para preferir o email da conta fornecida nos prompts de autenticação da Descoberta Automática no UPN. Por padrão, a Descoberta Automática prefere o UPN da conta, quando disponível.

- Solucionamos um problema que fazia com que os usuários ver falhas de pesquisa em Grupos Modernos.

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao tentar criar uma regra a partir de uma mensagem de &quot;Conversa Perdida&quot;.

- Solucionamos um problema que fazia com que os usuários vissem falhas de pesquisa em Grupos Modernos.

### <a name="word"></a>Word

- Corrigimos um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet.

### <a name="office-suite"></a>Pacote Office

- Corrigimos um problema para impedir que os usuários do PowerPoint encontrem erros ao tentar Apresentar Online.

- Confiabilidade aprimorada do processo de atualização do Office em relação à integridade do registro.

- Corrigimos um problema em que as atualizações poderiam ser bloqueadas inesperadamente em redes limitadas.

- Corrigimos um problema na ODT e na configuração da data limite da atualização do GPO, onde a data limite só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-november-12"></a>Versão 1908: 12 de novembro
*Versão 1908 (Build 11929.20436)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel

- Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico.
- Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.
- Resolvemos um problema que causou interrupções na coautoria ao alterar propriedades personalizadas com macros.
- Resolvemos um problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.
- Melhoramos significativamente o desempenho da filtragem por cor.
- Resolvemos um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.
- Os links de cid: imagens de mensagens do Outlook podem ser interrompidos com sucesso quando solicitado.

### <a name="outlook"></a>Outlook

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidos com sucesso quando solicitado.
- Solucionamos um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.
- Solucionamos um problema que causou um vazamento de memória em sessões muito longas do Outlook.
- Solucionamos um problema que faria com que os usuários experimentassem uma falha no Outlook ao interagir com determinados safelinks.
- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.
- Solucionamos um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.
- Solucionamos um problema que causava um travamento na experiência de Comentários de Pesquisa.

### <a name="powerpoint"></a>PowerPoint

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidos com sucesso quando solicitado.
- Correção de confiabilidade: Corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.

### <a name="project"></a>Project

- Corrigido um problema em que o comando Nivelar Tudo não estava resolvendo corretamente uma superalocação de recursos.
- Corregido um problema em que, caso você tenha uma tarefa com zero trabalho em uma tarefa, a tarefa poderia não ser marcada como concluída e sempre aparecerá em 99%.
- Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.

### <a name="word"></a>Word

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidos com sucesso quando solicitado.
- Corrigidos vários problemas em que o aplicativo pode travar no desligamento. Além disso, corrigimos determinadas falhas relacionadas aos suplementos.

### <a name="office-suite"></a>Pacote Office

- Solucionados problemas relacionados à propriedade AutoAjuste da Caixa de texto/ Forma em plug-ins de terceiros.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="october-15"></a>15 de outubro

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança

### <a name="office-suite"></a>Pacote do Office
- Desativamos temporariamente a caixa de diálogo Salvar na Nuvem para solucionar o problema de salvamento que publicamos em 14 de outubro de 2019 em builds anteriores a 16.0.11929.20396. Este recurso será reabilitado em breve.

## <a name="version-1908-october-14"></a>Versão 1908: 14 de outubro
*Versão 1908 (Build 11929.20396)*


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- <div>Resolvemos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item.</div>

### <a name="office-suite"></a>Pacote Office

- Resolvemos um problema em que os usuários poderiam não conseguir salvar documentos do Word, Excel e PowerPoint 2019 em builds anteriores a 16.0.11929.20396.  Esse problema afeta os usuários que criam um novo arquivo e exibem a caixa de diálogo “Salvar como" depois de clicar no ícone Salvar ou pressionar Ctrl + S.

- Resolvemos um problema em que, em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização.  Essa atualização melhora a confiabilidade ao publicar os atalhos do Office.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-october-08"></a>Versão 1908:8 de outubro
*Versão 1908 (Build 11929.20388)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.

- Corrigido um problema que permitia que mais de 16 suplementos fossem mostrados ao navegar no gerenciador de suplementos.

- Corrigido um problema no recurso Ideias do Excel, um erro ao carregar o suplemento clicando no botão Ideias no cliente Win32.

### <a name="outlook"></a>Outlook

- Corrigimos um problema que provocou falha na exibição de URLs de foco simples para alguns safelinks.

- Atualizamos a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.

- Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.

### <a name="powerpoint"></a>PowerPoint

- Corrigido um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.

### <a name="office-suite"></a>Pacote do Office

- Corrigido um problema de falha que os usuários podiam encontrar ao abrir um arquivo.

- Corrigido um problema em que as informações de acessibilidade não estavam sendo exibidas no slab do Local de Informações do Backstage.

- Maior confiabilidade ao baixar as atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.

- Para proteger a segurança do cliente do Office, as atualizações do Microsoft Office agora são assinadas usando somente o algoritmo SHA-2.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-september-10"></a>Versão 1908: 10 de setembro
*Versão 1908 (Build 11929.20300)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Aplicar zoom com mais espaço:** aumente a caixa Zoom, altere a fonte e o Zoom lembrará de tudo. [Saiba mais](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **Manter as guias dos objetos de banco de dados:** Veja as guias ativas, arraste as guias facilmente para reorganizá-las, e feche os objetos de banco de dados com apenas um clique.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **Saiba mais sobre seus dados:** O novo botão Ideias procura padrões em seus dados e os usa para criar sugestões inteligentes e personalizadas. [Saiba mais](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Dê vida às suas planilhas:** insira gráficos animados em 3D para ver corações pulsando, planetas orbitando e a fúria do T-Rex na pasta de trabalho. [Saiba mais](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **A colaboração ficou mais fácil:** o aperfeiçoamentos de coautoria significam que, ao trabalhar com formatação condicional, estilos de célula e muito mais, suas alterações são mescladas perfeitamente com as de seus colaboradores.

- **Una tabelas em colunas similares:** Obter e Transformar (Power Query) agora apresenta lógica de texto correspondente aproximado (também chamada de correspondência difusa) ao comparar colunas para mesclar tabelas. [Saiba mais](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Codifique rapidamente com as melhorias do Power Query:** chegue rapidamente à conclusão de código com as cores de sintaxe e o preenchimento automático. Também descubra facilmente funções, colunas e parâmetros.

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba Mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **Continue trabalhando enquanto move mensagens:** Agora, o Outlook move mensagens em segundo plano para que você pode continuar trabalhando enquanto move uma grande quantidade de mensagens entre pastas.

- **Crie intervalos entre reuniões consecutivas:** dê um tempo para os participantes descansarem ou se deslocarem entre os locais definindo o término antecipado das reuniões para entre cinco a dez minutos por padrão.

- **As pessoas verão o Meme que você usou:** se o texto ou as imagens estáticas não forem suficientes, use GIFs animados para convencer. [Saiba mais](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b).

- **Atualizamos a experiência de usuário do Outlook para você:** uma experiência simplificada, previamente disponível para visualização com Em Breve, projetada para ajudar você a se concentrar no que é mais importante. [Saiba mais](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Layout com mais ou menos espaçamento? Você escolhe:** um espaçamento menor permite decidir se quer mais espaço entre itens ou um layout com menos espaçamento para poder ver mais.

- **Uma faixa de opções simplificada também personalizável:** desfrute de uma única linha simplificada com os botões usados com mais frequência. Alterne facilmente entre visualizações clássicas e simplificadas e comandos para fixar/desafixar. [Saiba mais](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Uma maneira mais rápida de adicionar contas:** graças às melhorias de configuração de conta, ficou mais fácil adicionar contas do Outlook.com e do Gmail que usam a autenticação de dois fatores no Outlook. [Saiba mais](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Escolha a sua ação favorita:** não use Sinalizar e Excluir? E quanto a Arquivar ou Marcar como Lida? Personalize o menu de ação rápida com os comandos mais usados.

- **Diga adeus aos limites de sincronização:** melhorias do Outlook acabou com o limite de pastas, então vá em frente e sincronize suas caixas de correio compartilhadas.

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba Mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Saiba a opinião de seu público através de um questionário ou pesquisa:** coloque um questionário ou uma pesquisa em um slide. O Office coleta e armazena as respostas para você. [Saiba mais](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Inserir um vídeo online está mais fácil do que nunca:** Deseja colocar um vídeo do Vimeo ou YouTube no slide? O link da página de vídeo é tudo o que você precisa. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Melhoria na mudança de formas:** nomeie suas formas para ter mais controle sobre como elas são transformadas. [Saiba mais](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Os vídeos online têm um novo lar:** salve um vídeo no Microsoft Stream para que qualquer pessoa em sua organização possa vê-lo. Insira o link de vídeo e desfrute de uma apresentação multimídia com uma fração do tamanho do arquivo. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Diga adeus aos links desfeitos do Excel:** não consegue encontrar a pasta de trabalho do Excel vinculada ao seu diagrama do Visualizador de Dados? Vincule-o novamente para que tudo volte ao normal. [Saiba mais](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Estênceis criados diretamente no Azure:** crie um aplicativo de nuvem ou planeje uma arquitetura usando dezenas de estênceis do Azure. [Saiba mais](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Captura dupla em fluxogramas de dados:** os novos e deslumbrantes layouts para os fluxogramas do Visualizador de Dados são limpos, nítidos e fáceis de entender. Clique na guia Design para ver as opções.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exporte diagramas de processo para o Word:** Adicione automaticamente conteúdo de diagrama, como formas e metadados, a um documento do Word. Personalize o documento para criar as diretrizes de processo e os manuais de operação. [Saiba mais](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Exporte elementos visuais do Visio a partir do Power BI:** os elementos visuais do Visio para o Power BI agora estão sendo exibidos corretamente ao exportar relatórios do Power BI como PDFs, arquivos do PowerPoint e muito mais. [Saiba mais](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **A edição ocorre naturalmente com o Editor por Tinta:** com um único traçado, divida ou una palavras, adicione uma nova linha ou insira palavras usando uma caneta. [Saiba mais](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Transforme seu documento de estático para incrível:** transforme seu documento em uma página da web interativa e fácil de compartilhar, com uma aparência ótima em qualquer dispositivo. [Saiba mais](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Chame a atenção das pessoas com \@Menções:** use @menções nos comentários para que outras pessoas saibam quando precisa da contribuição delas. [Saiba mais](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Melhore a compreensão com Line Focus:** percorra a linha de um documento sem distrações. Ajuste o foco para colocar uma, três ou cinco linhas na visualização de cada vez. [Saiba mais](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Aumente o alcance do seu conteúdo:** precisa tornar seus documentos acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **O modo Ferramentas de Aprendizagem tem suporte adicional para mais cores de página:** as Ferramentas de Aprendizagem no Word adicionam suporte para mais cores de tema de página, o que permite a alteração da cor da tela de fundo da página. Várias pessoas têm desafios de leitura com um plano de fundo todo branco ou preto, então ampliamos as opções de cores no Word para PC e para Mac.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba Mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Pacote do Office

- **Instalação do Microsoft Teams:** O Teams foi adicionado nas instalações existentes do Office 365 ProPlus. [Saiba Mais](/deployoffice/teams-install)

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Controles de privacidade:** controles novos, atualizados e melhorados para dados de diagnóstico e experiências conectadas. [Saiba mais](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Os produtos do Ofiice estão com um novo visual** Os ícones de produtos foram recriados para refletir as experiências simples, poderosas e inteligentes do Office.

- **Instalação do Microsoft Teams:** o Microsoft Teams vem instalado por padrão nas instalações existentes do Office 365 ProPlus. [Saiba mais](/DeployOffice/teams-install)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- Correção de um problema no Excel em que as macros atribuídas a formas ou controles de formulário podem exibir mensagem de erro incorreta ou podem funcionar em intervalos de destino incorretos.

- Correção de um problema em que é possível alterar a forma como uma Tabela Dinâmica é classificada e atualizá-la durante uma sessão de coautoria com outros usuários poderia causar falha.

- Correção de um problema que fazia com que os gráficos de cascata e funil ficassem fora de sincronia com as tabelas quando as células eram inseridas ou excluídas.

- Correção de um problema de conflito de mesclagem no Excel, que resultaria na reabertura de uma pasta de trabalho para os usuários.

- Correção de um problema que fazia com que as operações de recortar e colar próximas de uma tabela falhassem durante a coautoria com outras pessoas.

### <a name="outlook"></a>Outlook

- Correção de um problema em que os usuários que atualizavam a caixa de correio de uma autenticação básica para a moderna acabavam com a conta errada associada ao perfil do Outlook.

- Correção de um problema que fazia com que um subconjunto de usuários POP3 visualizasse todos os seus e-mails formatados em texto simples, independentemente das configurações. Essa correção restaurará o modo de exibição das mensagens formatadas como HTML.

- Correção de um problema que impedia o acesso dos usuários de sugestões de localização por meio de um leitor de tela.

- Correção de um problema que fazia com que alguns usuários encontrassem erros de autenticação ao tentar recuperar as configurações de nuvem do Outlook.

- Correção de um problema que causava ambiguidade para os gerentes se um representante já havia respondido ou não a uma determinada solicitação de reunião.

- Correção de um problema que fazia com que os usuários do Outlook não passassem do estado "senha necessária" em determinados cenários.

- Correção de um problema que causava falha intermitente na pesquisa da pasta atual.

- Correção de um problema que fazia com que os usuários vissem sugestões de salas para reuniões que não eram compatíveis com o horário disponível da sala.

- Correção de um problema temporário no serviço que exibia o erro "não foi possível encontrar este arquivo. Verifique se o caminho e o nome do arquivo estão corretos" ao usar anexos na nuvem. [Saiba Mais](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Correção de um problema que fazia com que os usuários vissem arquivos carregados do Outlook para o OneDrive ou o SharePoint com o nome do arquivo alterado onde vários caracteres foram substituídos por sublinhados.

- Correção de um problema para usuários não falantes do inglês, onde a linha de assunto de um email seria muito pequena.


### <a name="powerpoint"></a>PowerPoint

- Correção de um problema em que alguns suplementos lançavam erros inesperados relacionados às formas nos gráficos.

- Correção de um problema para restaurar o nome acessível para controles de vídeo do PowerPoint.

- Correção de um problema que poderia impedir a inicialização de algumas animações.

### <a name="project"></a>Project

- Correção de um problema para que os usuários do Windows 7 possam abrir projetos do Project Web App e sites do SharePoint.


### <a name="visio"></a>Visio

- Exportar para SVG a partir do Visio não estava funcionando para várias formas.

### <a name="word"></a>Word

- Correção de um problema em que os usuários recebiam mensagens de erro durante a colaboração com outras pessoas em um documento do Word.

- Correção de um problema em que os usuários recebiam a mensagem "Algo está nos impedindo de compartilhar isso" ao tentar compartilhar arquivos armazenados no SharePoint 2016.


### <a name="office-suite"></a>Pacote Office

- Correção de um problema que em alguns casos um arquivo do mecanismo de sincronização do SharePoint poderia exibir “salvo”, mas não salvava as alterações.

- Correção de um problema em que grandes modos de exibição de árvore falhavam.

- Correção de um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-august-13"></a>Versão 1902: 13 de agosto
*Versão 1902 (Build 11328.20392)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
- Correção de um problema em que o ícone limpar filtro era mostrado para segmentações de dados filtradas e não filtradas nas tabelas.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança
- Correção de um problema em que os usuários atualizando a caixa de correio de uma autenticação básica para moderna acabavam com a conta errada associada

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
- Correção de um problema em que o aplicativo poderia ser encerrado inesperadamente ao colaborar em um documento com outros usuários.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
- Correção de um problema em que os campos de atualização do VBA estavam lentos.
- Correção de um problema que, ao abrir um arquivo DOC, diz-se estar corrompido.
- Correção de um problema em que o aplicativo poderia ser encerrado inesperadamente ao colaborar em um documento com outros usuários.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
- Correção de um problema em que a configuração da API não funciona na biblioteca JavaScript do Office em determinados cenários [Saiba mais](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>Versão 1902: 09 de julho
*Versão 1902 (Build 11328.20368)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
- Problema de extrema lentidão corrigido na exclusão das linhas filtradas do Excel.
- A rolagem de dois dedos fixos faz com que os retângulos cinzas sejam desenhados na planilha e o Excel congele.


### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança
- Aborda um problema que fazia com que os usuários vejam ocasionalmente o Outlook inserindo letras do piniyn em inglês, em vez de manter a janela do candidato a IME aberta para permitir a seleção de palavras em chinês.
- Aborda um problema que fazia com que os usuários vissem sugestões de salas que não estavam disponíveis sendo agendadas para reuniões.
- Aborda um problema que fazia com que os usuários tentassem abrir uma exceção a uma série de reuniões para, ao invés disso, abrir a série principal.
- Aborda um problema que fazia com que os usuários vissem datas de vencimento sendo calculadas incorretamente para itens da pasta de Itens Excluídos.


### <a name="teams-non-security-updates"></a>Teams: Atualizações não relacionadas à segurança

- O instalador do Teams agora tem Política disponível para desativar o recurso de iniciar automaticamente após a conclusão da instalação.


### <a name="visio-non-security-updates"></a>Visio: Atualizações não relacionadas à segurança

- Aborda problemas relacionados a soluções ActiveX para o Visio não funcionando no Office 365, expresso como uma mensagem de erro informando que o riched20.dll não pode ser localizado.


### <a name="word--non-security-updates"></a>Word:  Atualizações não relacionadas à segurança

- Configuração de GPO fixo para desabilitar a barra de pesquisa de modelos
- Correção de um problema em que os usuários podem perder algumas de suas alterações após estar offline e editar um documento que era somente de servidor.
- Melhor desempenho durante a habilitação de Partes Rápidas de propriedades do documento
- Correção de um problema em que a primeira revisão baixada do servidor pode falhar


### <a name="office-suite--non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Aborda um problema em que os dispositivos que usam a ativação de computador compartilhado podem reverter inesperadamente para a ativação baseada no usuário durante a instalação de outros produtos do Office ou de pacotes de idiomas.
- Correção de um problema que bloqueou as atualizações do Office quando a autenticação de proxy é executada como SISTEMA.
- As correções para lidar com os suplementos do Office desaparecem nas alterações de perfil do usuário.


## <a name="version-1902-june-11"></a>Versão 1902: 11 de junho
*Versão 1902 (Build 11328.20318)*
<br/>Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
 - Foi resolvido um problema que causava uma falha ao salvar um arquivo contendo um mapa XML em PDF.
 - Foi resolvido um problema que fazia com que links externos fossem removidos quando pastas de trabalho contendo nomes de planilha inválidos eram carregadas.
 - Foi corrigido um problema em que o uso da ferramenta Câmera no Excel fazia com que a planilha fosse interrompida.
 - Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.
 - Foi resolvida uma falha de quando uma tabela de dados é recalculada durante o cálculo da planilha com uma fórmula de matriz em outra planilha, dependendo da tabela. 
 - Foi resolvido um problema que impedia que pastas de trabalho protegidas por senha fossem abertas a partir do SharePoint sem fazer o check-out do arquivo primeiro.
 - Foi feita uma alteração para garantir que o evento BeforeSave seja tratado ao compartilhar ou alternar o recurso AutoSalvar.

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
 - Foi solucionado um problema que fazia com que as tarefas dos clientes aparentemente desaparecessem ao adicionar uma segunda condição a "Agrupar por".

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
 - Foi corrigido um problema em que, ao compartilhar um documento no momento em que este recebia colaborações, o documento produzia anexos com a extensão .asd.
 - Foi corrigido um problema com comentários atribuídos a autores aleatórios.
 - Foi corrigido um problema na remoção de assinatura ao finalizar um documento.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
 - Isso corrigiu um erro no VBA relatando um estado incorreto de preenchimento de forma após uma ação de "desfazer".


## <a name="version-1902-may-14"></a>Versão 1902: 14 de maio
*Versão 1902 (Build 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
 -  Corrigido um problema em que o uso da ferramenta Câmera no Excel fazia com que a planilha fosse interrompida.
 - Um problema que causava uma falha ao usar a roda de rolagem do mouse em uma janela inativa com uma planilha de gráfico foi corrigido.
 - Foi solucionado um problema que causava a mensagem "Erro inesperado" ao importar uma planilha no SharePoint.
 - Um problema que causava a falha do Excel ao abrir uma pasta de trabalho contendo formatação condicional que usa um Nome para sua regra e uma exibição personalizada é aplicada foi resolvido.
 - Macros usando validação de dados com fórmulas com mais de 255 caracteres podem ter produzido erros de tempo de execução. Esse problema foi agora corrigido.
 - Um problema que fazia com que arquivos contendo Tabelas Dinâmicas vinculadas a outras pastas de trabalho fossem carregados lentamente. Esse problema foi resolvido.
 - Um problema com a abertura de arquivos HTML e o recebimento do erro "o formato de arquivo e a extensão não correspondem" foi solucionado.
 - Uma alteração foi feita para resolver problemas com a rolagem da roda do mouse em janelas inativas.  

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
 - Soluciona um problema que fazia com que os clientes não conseguissem editar alguns campos em itens que foram migrados.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
- Corrigido um problema no qual o PowerPoint parava de fazer o upload de alterações do usuário para a nuvem em raras situações.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
 - Corrigido um problema no Lync (Skype for Business) onde para qualquer reunião online com mais de 7 participantes, a janela da reunião poderia desaparecer.
 - Entre no Skype for Business com as credenciais usadas para entrar em outro aplicativo do Office.
 - Ative corretamente o aplicativo do Skype for Business quando instalado com ativação de computador compartilhado.

### <a name="visio-non-security-updates"></a>Visio: atualizações não relacionadas à segurança
 - Corrigido um problema que estava causando problemas de hierarquia de janela interrompida para soluções de terceiros estendendo o Visio desabilitando o recurso DPI Dinâmico.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
 - Corrigido um problema em que a edição de uma Pessoa Relacionada adicionada pelo SharePoint falhava.
 - Corrigido um problema em que aparecia a caixa de diálogo "Falha ao carregar recurso" ao abrir o Word.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
 - Esta é uma correção para um problema em que os arquivos não podem ser salvos em pastas Apache WebDAV.
 - Corrige um problema em que o Office é fechado abruptamente quando os clientes abrem alguns arquivos armazenados na nuvem.
 - Corrigiu um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como uma expressão de erros ortográfico ou gramatical.
 - Corrigido um problema em que a lista de arquivos recentes parecia ter sido limpa para muitos usuários no Windows 10.
 - Corrigido um problema que fazia com que um usuário final visse uma barra de negócios de Atualização do Office, mesmo que houvesse uma atualização acionada pelo administrador em andamento.
 - Correção de problemas relacionados a avisos de logon em branco intermitentes.
 

## <a name="version-1902-april-9"></a>Versão 1902: 9 de abril
*Versão 1902 (Build 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança

- Resolvido um problema em que pressionar a tecla Tab não movia para a próxima célula quando em uma célula com uma fórmula que terminava em um nome definido.
- Resolvido um problema em que a formatação das células estava fazendo com que o tamanho do arquivo expandisse desnecessariamente.
- Resolvido um problema em que recortar e colar uma tabela dinâmica entre pastas de trabalho podia resultar em dados sendo colados sem uma tabela dinâmica para outras pessoas com as quais você está colaborando.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança

- Corrigimos um problema no qual o Windows não aparecia no local correto quando a barra de tarefas do sistema era mantida à esquerda ou no topo da tela.
- Soluciona um problema que fazia com que os clientes sofressem uma falha ao carregar fotos no cartão de contato.
- Soluciona um problema que fazia com que alguns clientes sofressem falhas ao iniciar aplicativos do Office.
- Corrigimos um problema no qual o Windows não aparecia no local correto quando a barra de tarefas do sistema era mantida à esquerda ou no topo da tela.
- Soluciona um problema que fazia com que os clientes não conseguissem editar alguns campos em itens que foram migrados.

### <a name="visio-non-security-updates"></a>Visio: Atualizações não relacionadas à segurança

- Corrigido um problema que estava causando problemas de hierarquia de janela quebrada para o Visio extendido a soluções de terceiros desabilitando o recurso de DPI dinâmico.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança

- Se um arquivo for aberto no modo somente leitura e você clicar em 'Salvar como' no painel 'Informações', o problema será corrigido para que a interface do usuário de salvar seja exibida.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Corrigido um problema em que partes de uma atualização do Office não usava o cache de pares de Otimização de Entrega. [Saiba mais](/windows/deployment/update/waas-delivery-optimization)
- Corrigido um bug que pode levar a remoção ou não ativação se o Office foi instalado usando a Ferramenta de Implantação do Office e houve uma incompatibilidade de caso.
- Corrigimos um problema que estava causando prompts de login excessivos nos dispositivos Windows 10 (versão 1803 ou posterior).
- Corrigimos a regressão que causava interrupções durante o download de imagens vinculadas.
- Corrigimos o desfoque de arquivos EMF grandes colados no Word, Excel, PowerPoint.
- Corrigimos o erro na lógica de análise do histórico de versões que, em alguns casos, fazia com que os documentos fossem abertos em modo somente leitura.

## <a name="version-1902-march-12"></a>Versão 1902: 12 de março
*Versão 1902 (Build 11328.20158)*

### <a name="access-feature-updates"></a>Access: Atualizações de recursos

- **Atualizar, vincular novamente ou remover tabelas vinculadas:** o Gerenciador de tabelas vinculadas atualizado é o local para gerenciar todas as fontes de dados e tabelas vinculadas. [Saiba mais](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Pinte de preto, pinte de cinza:** Altere a aparência do Access quantas vezes quiser. Quatro temas para escolher: colorido, cinza escuro, preto ou branco. [Saiba mais](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos

- **Comece mais rápido** A Página de Início recém-projetada coloca seus documentos abertos recentemente em destaque. Acesse os arquivos com menos cliques e abra as Configurações da conta ou Opções daqui mesmo.
- **Colaborar com os comentários:** Mantenha a conversa em andamento na sua planilha com a caixa de resposta integrada. [Saiba mais](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Ícones da faixa de opções têm uma aparência nova:** não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Ver o que está atrás de uma imagem:** coloque uma imagem em uma planilha, selecione o valor predefinido e observe a alteração de transparência. É isso![Saiba mais](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Chamar todos os fãs do Obter e Transformar:** se você usa muito o Obter e Transformar, ficará feliz em saber que o recurso da Coluna de exemplo foi aprimorado. E muitos conectores foram melhorados também. [Saiba mais](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Pesquisa rápida** Nós carregamos seus cálculos VLOOKUP, HLOOKUP e MATCH para que você possa obter respostas mais rápidas. [Saiba mais](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: atualizações de recursos

- **Usar Ler em Voz Alta para ouvir seu email** O Outlook pode ler seu email em voz alta, realçando o texto conforme lê. para ativar Ler em Voz Alta, vá para as configurações de facilidade de acesso [Saiba mais](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Digitar com as mãos livres:** tem um microfone? Clique em Ditar e veja o Outlook digitar enquanto você fala.  [Saiba mais](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Ícones da faixa de opções têm uma aparência nova:** não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Bloquear o download de conteúdo externo por padrão em emails criptografados e assinados SMIME:** devido a uma vulnerabilidade de protocolo SMIME, o Outlook bloqueará o download de conteúdo externo em mensagens criptografadas ou assinadas em SMIME. Os usuários não poderão clicar em download de conteúdo externo por meio da interface do usuário do Outlook para se proteger da vulnerabilidade de segurança. Há uma nova opção na caixa de diálogo Opções para permitir que os usuários retornem ao comportamento antigo.
- **Desabilitar o encaminhamento para uma reunião:** impede que os participantes encaminhem a reunião para outras pessoas. Basta acessar a faixa de opções e clicar em opções de resposta. [Saiba mais](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Sugestões de pessoas no Assistente de Agendamento:** Confira recomendações para adicionar participantes quando agendar uma reunião. Não é mais preciso alternar entre a linha e o Assistente de agendamento. [Saiba mais](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Reservar uma sala acabou de ficar mais fácil:** procure uma sala de conferência usando mais de uma lista de salas e troque as listas sem perder as salas que você selecionou.
- **Novo padrão de intervalo da recorrência:** Na caixa de diálogo de Recorrência, o intervalo de recorrência usado como padrão é "Sem data de término". Isso facilita a criação de série recorrente, que pode ficar corrompida ao longo do tempo. Estamos atualizando o padrão da caixa de diálogo Recorrência para "Terminar em,", para que nosso valor padrão corresponda às melhores práticas recomendadas para o calendário.
- **Ingresse em reuniões do Teams pela caixa de diálogo Lembretes do Outlook:** quando o Outlook lembrar os usuários de uma reunião, o botão Participar online será exibido se a futura reunião for online no Teams. Isso é semelhante à experiência de entrar em uma reunião do Skype for Business pela caixa de diálogo Lembretes do Outlook.
- **Continuar a ver lembretes de eventos anteriores:** Você pode configurar seu calendário para ignorar lembretes de eventos depois que você terminou automaticamente. [Saiba mais](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Conferir a URL atrás de Links seguros:** os Links seguros protegem você contra URLs mal-intencionadas recebidas por email, mas ocultam a URL original. Para ver o original, passe o mouse sobre a URL. Requer uma licença da Proteção Avançada Contra Ameaças. [Saiba mais](https://products.office.com/exchange/advance-threat-protection)
- **Aplicar zoom e manter:** em vez de ajustar o Zoom sempre que quiser ler uma mensagem, escolha um padrão para todas as suas mensagens. [Saiba mais](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Criptografia de mensagem: política de IRM somente criptografia:** a nova opção de somente criptografar é exibida no menu Opções > Permissões para usuários da Criptografia de Mensagem do Office 365. Essa opção permite que você criptografe e envie uma mensagem a qualquer pessoa dentro ou fora da organização.
- **Aviso quando você for adicionado a uma cópia oculta:** a infodica de Cco irá alertá-lo antes de você responder acidentalmente a todos em um email no qual você foi adicionado a uma cópia oculta.
- **Linha Para: mais inteligente:** ao clicar na linha Para: para endereçar a mensagem, sugerimos os destinatários com mais chances de serem escolhidos. Além disso, você verá a imagem do destinatário para saber que está enviando para a pessoa certa. [Saiba mais](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: atualizações de recursos

- **Comece mais rápido** A Página de Início recém-projetada coloca seus documentos abertos recentemente em destaque. Acesse os arquivos com menos cliques e abra as Configurações da conta ou Opções daqui mesmo.
- **Digitar com as mãos livres:** tem um microfone? Clique em Ditar e veja o PowerPoint digitar enquanto você fala.  [Saiba mais](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Ícones da faixa de opções têm uma aparência nova:** não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Hyperlinks em cor vibrante:** os hiperlinks não são mais apenas azuis. Aplique as cores de fonte que desejar. [Saiba mais](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Ver seus slides ganharem vida:** insira gráficos animados em 3D para ver batidas de corações, órbita de planetas e a fúria do T-Rex em toda a tela. [Saiba mais](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Você esboça, nós melhoramos:** transformamos textos e formas desenhadas em diagramas refinados. Basta selecionar seus traços de tinta para começar. [Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Ver o que está atrás de uma imagem:** coloque uma imagem em uma planilha, selecione o valor predefinido e observe a alteração de transparência. É isso![Saiba mais](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Publicar no Microsoft Stream:** use o Microsoft Stream para compartilhar uma apresentação como vídeo de forma mais segura na organização. [Saiba mais](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- **Exportar para vídeo 4K:** quando você exporta uma apresentação para vídeo, a resolução 4K agora é uma opção.  [Saiba mais](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Arquivos grandes agora são abertos mais rapidamente:** imagens, vídeos e outros elementos grandes agora são baixados em segundo plano quando você abre arquivos armazenados no OneDrive ou no SharePoint.

### <a name="word-feature-updates"></a>Word: Atualizações de recursos

- **Comece mais rápido** A Página de Início recém-projetada coloca seus documentos abertos recentemente em destaque. Acesse os arquivos com menos cliques e abra as Configurações da conta ou Opções daqui mesmo.
- **Digitar com as mãos livres:** tem um microfone? Clique em Ditar e veja o Word digitar enquanto você fala.  [Saiba mais](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Assista seus documentos ganharem vida:** insira gráficos animados em 3D para ver batidas de corações, órbita de planetas e a fúria do T-Rex em toda a página. [Saiba mais](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Ícones da faixa de opções têm uma aparência nova:** não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Ver o que está atrás de uma imagem:** coloque uma imagem em uma planilha, selecione o valor predefinido e observe a alteração de transparência. É isso![Saiba mais](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Faça o seu melhor currículo ou CV com a ajuda do LinkedIn:** Com o Assistente de Currículos, é possível ver experiências profissionais, qualificações sugeridas e muito mais para uma determinada função. [Saiba mais](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: atualizações de recursos

- **Ver mais informações nos cartões do quadro de tarefas:** quando apenas o título não conta a história, personalize seus cartões de quadro de tarefas para mostrar a todos os detalhes mais importantes. [Saiba mais](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="publisher-feature-updates"></a>Publisher: atualizações de recursos

- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos

- **Aproveitar um momento icônico em seu próximo diagrama:** escolha entre 26 estênceis novos com ícones de análise, artes, comemoração, rostos, esportes e muito mais.
- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="office-suite-feature-updates"></a>Pacote do Office: atualizações de recursos

- **Os aplicativos de terceiros do Office agora têm suporte para inserir imagens em SVG usando a API do Office.js:** agora, os aplicativos de terceiros, também conhecidos como suplementos do Office, têm a capacidade de inserir imagens em SVG. Os usuários já podem conectar a coleção pessoal de imagens em SVG ao Office e os desenvolvedores podem usar esse recurso com a API do Office.js.
- **Instalação do Microsoft Teams:**  o Microsoft Teams já vem instalado por padrão nas instalações existentes do Office 365 ProPlus. [Saiba mais](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Atualizações de recursos

- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: Atualizações de recursos

- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>Versão 1808: 12 de fevereiro
*Versão 1808 (build 10730.20280)* 

### <a name="access-non-security-updates"></a>Access: Atualizações não relacionadas à segurança 

- Esta atualização adiciona suporte para as novas eras japonesas no Access.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança 

- Corrige o problema que levava os usuários que possuem regras que fazem referência a uma pasta que não existe mais a ver um erro ao tentar gerenciar as regras e ver as regras do lado cliente não funcionarem.
- Corrige o problema que levava os usuários com o caixas de correio delegadas em cache a encontrar paradas frequentes em intervalos imprevisíveis.
- Corrige o problema que fazia com que todas as Reuniões de Dia Inteiro abrangesse um dia a mais do que desejado em alguns modos de exibição, por a hora de término da reunião ser configurada para meia-noite do dia seguinte.
- Corrigiu o travamento durante a criação de novos compromissos ou reuniões que fazem referência ás eras japonesas.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Corrigiu o problema em que os Suplementos, implantados usando [implantação centralizada do O365 Office ](/office/dev/add-ins/publish/centralized-deployment), foram congelados e inutilizáveis.


## <a name="version-1808-january-8"></a>Versão 1808: 8 de janeiro
*Versão 1808 (Build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança 

- Correção um problema que levava os usuários a enfrentar problemas de sincronização do calendário.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança

- Melhore o desempenho abrir.

## <a name="version-1808-december-11"></a>Versão 1808: 11 de dezembro
*Versão 1808 (build 10730.20262)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): vulnerabilidade de execução remota de código do Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): vulnerabilidade de execução remota de código do Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): vulnerabilidade de execução remota de código do Microsoft PowerPoint 

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança 

- Corrigido um problema de sessões de coautoria em que uma segmentação de dados não é corretamente atualizada após outro usuário aplicar um filtro de coluna para os dados na segmentação de dados.
- Correção de um problema em uma sessão de co-autoria em que um dos usuários limpa a legenda de uma segmentação de dados e isso faz com que outro usuário na sessão de co-autoria experiencie uma falha do Excel.
- Correção de possível falha ao criar várias segmentações de dados de tabela vinculadas à mesma coluna de dados e excluir essa coluna de dados.
- Corrigido um problema em que o Excel às vezes travava ao atualizar uma tabela de consulta filtrada que contém texto agrupado nas células quando a opção de ajustar automaticamente as larguras das colunas estava desativada.
- Correção de um problema em que as segmentações de dados salvas no Excel 2007 podem disparar uma falha quando abertas em versões mais recentes do Excel, se o número de itens mostrados na segmentação de dados for alterado.
- Introduz o suporte para o botão Obter Diagnóstico para simplificar a investigação de solicitações de suporte.

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança

- Correção de um problema que fazia com que os usuários vissem um erro ao iniciar a caixa de diálogo "Gerenciar regras e alertas".
- Corrigido um problema que fazia com que os usuários não conseguissem conectar suas caixas de correio pelo DirectAccess ao usar uma conexão limitada.
- Corrigido um problema que fazia com que os usuários visualizassem documentos gratuitos armazenados em Pastas Públicas erroneamente abertos na "Modo de Exibição Protegido".
- Corrigido um problema que fazia com que os usuários vissem anexos inesperados ao encaminhar itens com anexos embutidos.
- Corrigido um problema que fazia com que os arquivos OFT apresentassem problemas após serem enviados como anexos.
- Correção de um problema que fazia com que alguns usuários experienciem falhas ao adicionar uma reunião a um calendário compartilhado.
- Correção de um problema que fazia com que os usuários experimentassem interrupções ao abrir a pasta Histórico de Conversas.

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança

- Corrigido um problema em torno do suporte a uma nova moeda venezuelana no Project.
- Corrigido um problema onde o projeto pode responder ao usar um Surface 4 que está conectado a um monitor externo.
- Corrigido um problema onde o Project pode falhar ao salvar o projeto em formato XML.
- Corrigido um problema em que os campos personalizados de recursos da empresa podem ser excluídos após a edição do calendário do recurso.
- Corrigido um problema que levava os usuários a enfrentar falhas ao pesquisar nomes em coreano.

## <a name="version-1808-november-13"></a>Versão 1808: 13 de novembro
*Versão 1808 (build 10730.20205)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): vulnerabilidade de execução remota de código do Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): vulnerabilidade de execução remota de código do Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Vulnerabilidade de execução remota de código do Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Vulnerabilidade de divulgação de informações do Microsoft Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): vulnerabilidade de Execução Remota de Código do Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Vulnerabilidade de divulgação de informações do Microsoft Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): vulnerabilidade de execução remota de código do Microsoft Outlook 

### <a name="project-security-updates"></a>Project: atualizações de segurança 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): vulnerabilidade de execução remota de código do Microsoft Project 

### <a name="word-security-updates"></a>Word: atualizações de segurança 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): vulnerabilidade de execução remota de código do Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Vulnerabilidade de negação de serviço do Microsoft Skype for Business 

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança 

- Corrigido um bug em que o Power Pivot não aparece em algumas versões/versões.

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança 

- Corrigido um problema que levava os usuários a não poderem usar o botão controle de contas com êxito para alternar entre contas em formulários personalizados.
- Corrigido um problema que levava os usuários a terem uma falha ao usar ScanPST reparar um arquivo PST/OST.
- Corrigido um problema que causa a CC: o campo em determinadas mensagens de email não é exibido para os usuários com perfis do modo online.

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações que não são de segurança 

- Foi corrigido um problema estabilidade que pode ocorrer envolvendo sincronização e navegação para uma seção excluída.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança 

- Corrigido um problema em que, se você estivesse trabalhando com arquivos do projeto em uma biblioteca de documentos do SharePoint que estava na nova experiência moderna, as ações Check-Out obrigatório e somente leitura não estão sendo seguidas corretamente.


## <a name="version-1808-october-9"></a>Versão 1808: 9 de outubro
*Versão 1808 (build 10730.20155)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): vulnerabilidade de execução remota de código do Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): atualização de proteção abrangente do Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): vulnerabilidade de execução remota de código do Microsoft PowerPoint

### <a name="word-security-updates"></a>Word: atualizações de segurança 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): vulnerabilidade de execução remota de código do Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): atualização de proteção abrangente do Microsoft Office 

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): vulnerabilidade de execução remota de código do componente do Microsoft Graphics 

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança 
-   Corrigir o problema quando símbolos no intervalo entre 2190 2194 são alternados para Cambria Math. Isso está fazendo a altura de célula do Excel aumentar 3 vezes.
-   Essa corrige o problema no Excel na qual o Excel pode ficar sem resposta, quando o usuário passa o mouse sobre as opções de formatação em uma pasta de trabalho com vários nomes definidos e o Excel onde pode não responder na ferramenta Análise Rápida mesmo quando visualização dinâmica foi desabilitada em Opções.
-   Estamos atualmente investigando o desempenho lento ao mover a janela do aplicativo Excel uma área de trabalho para outra. Enquanto isso, se você perceber essa lentidão, uma solução alternativa a considerar é selecionar "Otimizar a compatibilidade" para "ao usar várias exibições" na guia "Geral" na caixa de diálogo Opções de arquivo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Corrigido um problema de possíveis corrupção de arquivo ao salvar arquivos com o conteúdo do ActiveX.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Corrigido um problema em que ao inserir um objeto de documento do Word, o editor de equações aparece.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Corrigido um problema em que se você definir um cabeçalho ou rodapé de uma impressão, a alteração não era mantida na próxima vez que você entrava para imprimir seu projeto.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigido um problema de aplicativos mostrando animações apesar das animações pelas configurações de acessibilidade e desempenho estar desativada. 
-   Corrigido problema da tela de fundo ficar em branco ao usar o marca-texto na ferramenta de desenho.

## <a name="version-1808-september-11"></a>Versão 1808: 11 de setembro
*Versão 1808 (build 10730.20102)*

### <a name="access-feature-updates"></a>Access: Atualizações de recursos
 - **Visualizar dados com gráficos novos:** escolha entre 11 gráficos e adicione um deles aos formulários e relatórios para visualizar melhor os dados e tomar decisões informadas. [Saiba mais](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidade Use-After-Free de execução remota de código do Microsoft Access

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
 - **Edição colaborativa:** trabalhe com outras pessoas em simultâneo na pasta de trabalho.[Saiba mais](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **O salvamento automático arquivos da nuvem agora está habilitado por padrão:** O salvamento automático foi habilitado por padrão na versão semestral do canal (direcionado) em setembro de 2018. Essa mudança significa que os usuários não precisarão se preocupar em perder as alterações em documentos armazenados no OneDrive ou no SharePoint Online. As alterações serão salvas na nuvem automaticamente e usuários não terão mais que pressionar Ctrl + S ou o botão Salvar. No entanto, será necessário entender essa alteração no comportamento para que não façam alterações acidentais em documentos. Observe que os usuários podem desativar o salvamento automático usando a alternância de salvamento automático na parte superior da tela. É recomendável notificar os usuários sobre essa mudança futura e informar sobre como tirar o melhor proveito desse recurso novo no Office 365. [Saiba mais sobre o salvamento automático](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Saiba mais sobre o que os administradores de TI devem saber sobre o salvamento automático](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edição aprimorada para células e barra de fórmulas**: agora, é possível usar o comando Ctrl+T para selecionar texto em uma célula ou na barra de fórmulas. Há também um aprimoramento de suporte para emojis e outros caracteres complexos.[Saiba mais](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar as pastas de trabalho mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitar edições indesejadas:** configurar as pastas de trabalho abertos como somente leitura para impedir alterações acidentais. Acessar Arquivo > Informações > Proteger Pasta de Trabalho > Sempre Aberto Como Somente Leitura

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): vulnerabilidade de divulgação de informações do Microsoft Excel
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [/CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): vulnerabilidade de divulgação de informações do Microsoft Excel
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilidade de divulgação de informações confidenciais do Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilidade de divulgação de informações do Microsoft Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Corrige um problema em que o Excel pode falhar quando os dados de origem do gráfico do conjunto original de células são alterados.
-   Corrige um problema em que o recálculo pode não ocorrer ao abrir mesmo que a propriedade FullCalcOnLoad esteja definida.  
-   Corrige um problema em que o ano errado é exibido quando o calendário de Era japonesa é usado no formato de célula de data.
-   Ao importar dados para o modelo de dados do Excel, os valores de entrada abaixo de zero resultavam em um erro. A correção importa esses valores como zero.
-   Correção de um problema em que a operação agrupar ou desagrupar em uma Tabela Dinâmica do Excel podia, às vezes, gerar uma falha.
-   Correção um problema em que as ações de gráficos podem causar uma falha no Excel.
-   Correção de um problema em que o suplemento Power View é inadvertidamente desabilitado para alguns usuários.
-   Correção de um problema em que os arquivos temporários de recuperação automática criados durante a recuperação de documentos nunca são limpos.
-   Correção de um problema em que ao tentar fazer uma nova conexão com um arquivo de texto em uma pasta de trabalho protegida gera como resultado uma mensagem de erro "A pasta de trabalho está protegida e não pode ser alterada".
-   Correção de um problema em que a Impressão Rápida de uma pasta de trabalho do Excel anexada ao email do Outlook pode não ser impressa.
-   Correção de um problema em que clicar em um hiperlink pode causar uma falha no Excel.
-   Correção de um problema em que usar funções de cubo pode causar uma falha no Excel.

### <a name="outlook-feature-updates"></a>Outlook: atualizações de recursos
 - **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar as mensagens mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Gerenciar perfis a partir do Seletor de Perfil:** Se você usar o seletor de perfil ao iniciar o Outlook, agora você pode fazer alterações sem acessar o painel de controle. Crie e exclua perfis, altere as configurações, tudo pelo seletor de perfil.
- **Acessibilidade integrada no:** Torna suas mensagens acessíveis para todos, adicionando texto alt descritivo às suas imagens.
- **Avisos de suplemento do Outlook:** ocasionalmente, um suplemento do Outlook COM pode encontrar problemas que deixam mais lento o restante do Outlook. Esses problemas podem ser decorrentes da latência dos eventos, como alternar entre as pastas do Outlook, da chegada de novos emails, da abertura de itens do Calendário, entre outros. Quando problemas surgirem, o Outlook exibirá um aviso na barra de notificações.
- **Saiba com quem você vai se encontrar:** agora é possível ver as respostas de outras pessoas a uma solicitação de reunião, mesmo se você não for o organizador.
- **Nunca mais perca um lembrete:** defina lembretes a serem abertos sobre as janelas nas quais você está trabalhando. Caso contrário, o Outlook pisca na barra de ferramentas para chamar sua atenção.[Saiba mais](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Marque itens excluídos como lidos:** agora você pode definir qualquer mensagem excluída como lida. Para isso, vá para Arquivo \> Opções \> Email \> Outras.
- **Veja três fusos horários:** Precisa agendar uma reunião em diferentes fusos horários? Adicione vários fusos ao seu calendário para ver facilmente a disponibilidade dos participantes e escolha um horário que funcione para todos. [Saiba mais](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Experiência refinada do usuário para criação de um grupo:** Aperfeiçoamos a experiência do usuário para criar o  grupo para torná-la mais moderna e organizada.[ Saiba Mais](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidade de adulteração do Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilidade de elevação de privilégios do Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): atualização de proteção abrangente do Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Corrige um problema em que, se você mudar o idioma do sistema para japonês e tentar digitar caracteres japoneses no VBA IDE quando carregados no Outlook, eles são congelados.
-   Correção de um problema em que mudar para a pasta Itens Enviados ou Caixa de Saída causa uma falha no Outlook.
-   Correção de um problema em que todos os participantes recebem atualizações da reunião quando o corpo da reunião ou anexos mudam, em vez de o envio de uma atualização de reunião aos participantes ser opcional.
-   Correção de um problema que impossibilita o usuário de se conectar a pontos de extremidade de EWS e REST devido a uma alteração na cadeia de caracteres Usuário-Agente.
-   Correção de um problema em que atualizar o local da reunião para os participantes mostra o local antigo em vez de o novo local.
-   Correção de um problema em que o usuário vê uma mensagem de erro quando visualiza um anexo no painel de leitura.
-   Correção de um problema em que o Outlook falha ao resolver a exibição de nomes para endereços de email quando o usuário estiver redigindo um email.
-   Correção de um problema em que alguns usuários não recebem os recursos de suporte que foram habilitados pelo administrador de locatários.

### <a name="powerpoint-feature-updates"></a>PowerPoint: atualizações de recursos 
- **O salvamento automático arquivos da nuvem agora está habilitado por padrão:** O salvamento automático foi habilitado por padrão na versão semestral do canal (direcionado) em setembro de 2018. Essa mudança significa que os usuários não precisarão se preocupar em perder as alterações em documentos armazenados no OneDrive ou no SharePoint Online. As alterações serão salvas na nuvem automaticamente e usuários não terão mais que pressionar Ctrl + S ou o botão Salvar. No entanto, será necessário entender essa alteração no comportamento para que não façam alterações acidentais nas apresentações. Observe que os usuários podem desativar o salvamento automático usando a alternância de salvamento automático na parte superior da tela. É recomendável notificar os usuários sobre essa mudança futura e informar sobre como tirar o melhor proveito desse recurso novo no Office 365. [Saiba mais sobre o salvamento automático](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Saiba mais sobre o que os administradores de TI devem saber sobre o salvamento automático](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Converta suas notas escritas:** faça anotações e desenhos e converta-os em texto legível e formas simples para criar uma apresentação elegante. [Saiba mais](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Suporte aprimorado para SVG:** agora, é possível inserir imagens SVG que tenham filtros aplicados. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Dê um título aos slides com uma caneta**: use a caneta para escrever um título com tinta e veja o PowerPoint converter a tinta em texto. [Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Evitar edições indesejadas:** configurar as pastas de trabalho abertos como somente leitura para impedir alterações acidentais. Acessar Arquivo > Informações > Proteger Pasta de Trabalho > Sempre Aberto Como Somente Leitura
- **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar as apresentações mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que as tabelas são renderizadas incorretamente com bordas espessas.
-   Correção de um problema em que podia ocorrer uma falha ao alterar a propriedade Shape.Visibile.
-   Correção de um problema em que ocorre uma falha ao mesclar alterações em documentos criados em coautoria.
-   Correção de um problema em que os documentos contendo Controles ActiveX poderiam causar falha durante a coautoria.
-   Correção de um problema em que a correção ortográfica nas formas causa uma falha no PowerPoint.
-   Correção de um problema em que o PowerPoint falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que o Painel de Recuperação é exibido de forma incorreta quando o Salvamento Automático está ativado.
-   Correção de um problema em que a opção para entrar não é exibida, impedindo o usuário de acessar um arquivo.
-   Correção de um problema em que a coautoria de vários usuários na mesma apresentação gera uma duplicação incorreta dos slides mestres.
-   Correção de um problema em que abrir um arquivo salvo no OneDrive resulta em falha no PowerPoint ao sair do Modo de Exibição Protegido.

### <a name="project-feature-updates"></a>Project: atualizações de recursos 
- **Gerenciamento de Sprint :** rapidamente adicionar, atualizar ou excluir agile sprints.
- **Filtragem do painel de tarefas:** simplifique seus painéis de tarefas filtrando os principais recursos ou tarefas resumos.
- **Defina a porcentagem concluída de um quadro de tarefas:** escolha a porcentagem concluída de cada coluna e atualize a conclusão da tarefa ao arrastar e soltar.
- **Navegação Sprint:** alterne de uma exibição sprint para outra e mova rapidamente as tarefas entre sprints.
- **Uma nova maneira de gerenciar sprints:** adote uma abordagem ágil trabalhando com os Painéis de Tarefas. Acesse Gerenciar Sprints para adicionar e remover sprints durante o projeto.
- **Mantenha a organização com locais de salvamento Recentes**: o Project mantém uma lista ativa de locais em que você salvou outros projetos. Quando estiver pronto para salvar um projeto, basta escolher um dos Locais de salvamento recentes e continuar trabalhando.

### <a name="project-non-security-updates"></a>Atualizações do Project não relacionadas à segurança
- Correção de um problema em que você era impedido de salvar um subprojeto ao trabalhar com eles por meio do contexto de um projeto mestre.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Corrige um problema relacionado ao suporte TLS 1,2. (Observação: esta é a mesma correção que foi mencionada nas anotações de 10 de abril e mencionada aqui novamente como parte da acúmulo de setembro.)
-   Correção de um problema quando, ao adicionar usuários escolhendo "Chamada do Skype" em uma reunião causa um erro.
-   Remove o prompt que pede ao usuário para adicionar coordenadas do Skype a uma reunião se uma Sala de Skype for adicionada como o local e a reunião já contiver as coordenadas de reunião das Equipes.
-   Correção de um problema em que o local é preenchido, mesmo quando UseLocationForE911Only é definido como verdadeiro.
-   Correção de um problema em que o Skype for Business trava ao usar a opção "ligar usando o centro de conferências" para convidar usuários da lista de participantes.
-   Correção de um problema em que o Outlook em execução no servidor de área de trabalho remota congela ao criar uma reunião do Skype for Business.
-   Altere o valor padrão de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket para TRUE.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos
- **Mantenha seu diagrama e fonte em sincronia:** ao editar um diagrama do Visualizador de dados no Visio, você tem a opção para atualizar os dados de origem vinculados do Excel com o conteúdo mais recente do diagrama.
- **Modelo de auditoria do Visualizador de dados** importar o conteúdo do Excel e criar diagramas de auditoria para transações financeiras, gerenciamento de estoque e muito mais.
- **Diagramas iniciais:** os modelos Gráfico da Organização, Debate e SDL têm novos diagramas iniciais para você começar a trabalhar rapidamente.
 - **Use formas do Visio para criar um documento do Word:** adicione automaticamente o conteúdo de diagramas, incluindo formas e metadados, em um documento do Word. Personalize o documento para criar diretrizes de processo e manuais de operação. [Saiba mais](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word: atualizações de recursos
- **O salvamento automático arquivos da nuvem agora está habilitado por padrão:** O salvamento automático foi habilitado por padrão na versão semestral do canal (direcionado) em setembro de 2018. Essa mudança significa que os usuários não precisarão se preocupar em perder as alterações em documentos armazenados no OneDrive ou no SharePoint Online. As alterações serão salvas na nuvem automaticamente e usuários não terão mais que pressionar Ctrl + S ou o botão Salvar. No entanto, será necessário entender essa alteração no comportamento para que não façam alterações acidentais nas apresentações. Observe que os usuários podem desativar o salvamento automático usando a alternância de salvamento automático na parte superior da tela. É recomendável notificar os usuários sobre essa mudança futura e informar sobre como tirar o melhor proveito desse recurso novo no Office 365. [Saiba mais sobre o salvamento automático](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Saiba mais sobre o que os administradores de TI devem saber sobre o salvamento automático]
- **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar os documentos mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Suporte aprimorado para SVG:** agora, é possível inserir imagens SVG que tenham filtros aplicados. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Vulnerabilidade de execução remota de código em PDFs no Windows
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema que causa a exibição de uma mensagem de memória insuficiente.
-   Correção de um conjunto de problemas que impedia alguns usuários de abrir emails e documentos protegidos por IRM que eram compartilhados com eles por pessoas de outras organizações.
-   Corrigidos alguns problemas de desempenho.

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Vulnerabilidade de execução remota de gráficos Win32k
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilidade de Divulgação de Informações do Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilidade de execução remota de código do Microsoft Office
-   
  **Controles Flash, Silverlight e Shockwave impedidos de ativar o Office por motivos de segurança:** por motivos de segurança os novos builds do Microsoft Office para o Office 365 na ativação do Windows bloqueiam a ativação dos controles Flash, Silverlight, e Shockwave. Saiba mais [aqui](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)e[aqui](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-  Correção de um problema que causava a demora na instalação de atualização em determinadas situações.
-  Correção de um problema em que, ao abrir um aplicativo, às vezes o usuário via uma mensagem sobre a inicialização no modo de segurança e, em seguida, o aplicativo não abria.
-  Corrigidos alguns problemas de desempenho.

## <a name="version-1803-august-14"></a>Versão 1803: 14 de agosto
*Versão 1803 (build 9126.2275)*

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidade Use-After-Free de execução remota de código do Microsoft Access

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [/CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): vulnerabilidade de divulgação de informações do Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): atualização de proteção abrangente do Microsoft Office 

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilidade de Divulgação de Informações do Microsoft Office 

## <a name="version-1803-july-10"></a>Versão 1803: 10 de julho
*Versão 1803 (build 9126.2259)*

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidade Use-After-Free de execução remota de código do Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidade de adulteração do Microsoft Office

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidade de execução remota de código do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Corrige um problema em que o ano errado é exibido quando o calendário de Era japonesa é usado no formato de célula de data.
-   Ao importar dados para o modelo de dados do Excel, os valores de entrada abaixo de zero resultavam em um erro. A correção importa esses valores como zero.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Corrige o problema em que as tabelas são renderizadas incorretamente com bordas espessas.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Corrigido um problema em que, se uma tarefa fosse dividida com um recurso de custo, o recurso de custo não seria atualizado corretamente, e o custo seria perdido.
-   Corrigido um problema em que, ao adicionar tarefas existentes à caixa de diálogo da Linha do Tempo, somente as tarefas da primeira tarefa resumo eram exibidas no Modo de Exibição da Linha do Tempo.
-   Corrigido um problema onde salvar como XML poderia falhar para projetos mestres no Project Online ou no Project Server.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Correção de um bug que causava a demora na instalação de atualização em determinadas situações. 
-   Corrige um problema em que os testes SVG estão falhando
-   Corrija um problema em que, ao implantar atualizações usando o Gerenciador de Configurações em um cliente que executa aplicativos do Office, a atualização não é aplicada após a reinicialização do dispositivo enquanto os aplicativos do Office estiverem em execução.


## <a name="version-1803-june-12"></a>Versão 1803: 12 de junho
*Versão 1803 (build 9126.2227)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilidade de divulgação de informações confidenciais do Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que a operação agrupar ou desagrupar em uma Tabela Dinâmica do Excel podia, às vezes, gerar uma falha.

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilidade de elevação de privilégios do Microsoft Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que podia ocorrer uma falha ao alterar a propriedade Shape.Visibile.
-   Correção de um problema em que ocorre uma falha ao mesclar alterações em documentos criados em coautoria.
-   Correção de um problema em que os documentos contendo Controles ActiveX poderiam causar falha durante a coautoria.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao adicionar tarefas existentes à caixa de diálogo da Linha do Tempo, somente as tarefas da primeira tarefa resumo eram exibidas no Modo de Exibição da Linha do Tempo.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
-   Corrija um problema em que, ao implantar atualizações usando o Gerenciador de Configurações em um cliente que executa aplicativos do Office, a atualização não é aplicada após a reinicialização do dispositivo enquanto os aplicativos do Office estiverem em execução.



## <a name="version-1803-may-18"></a>Versão 1803: 18 de maio
*Versão 1803 (build 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
- Correção um problema em que as ações de gráficos podem causar uma falha no Excel.
- Correção de um problema em que o suplemento Power View é inadvertidamente desabilitado para alguns usuários.
- Correção de um problema em que os arquivos temporários de recuperação automática criados durante a recuperação de documentos nunca são limpos.
- Correção de um problema em que ao tentar fazer uma nova conexão com um arquivo de texto em uma pasta de trabalho protegida gera como resultado uma mensagem de erro "A pasta de trabalho está protegida e não pode ser alterada".

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
- Correção de um problema em que a correção ortográfica nas formas causa uma falha no PowerPoint.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
- Correção de um problema em que, ao abrir um aplicativo, às vezes o usuário via uma mensagem sobre a inicialização no modo de segurança e, em seguida, o aplicativo não abria.



## <a name="version-1803-may-8"></a>Versão 1803: 8 de maio
*Versão 1803 (build 9126.2191)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilidade de divulgação de informações do Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que o Excel falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que impressão ou visualização da impressão só imprime ou exibe uma parte da planilha, com o conteúdo truncado em uma segmentação de dados na planilha.

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que mudar para a pasta Itens Enviados ou Caixa de Saída causa uma falha no Outlook.
-   Correção de um problema em que todos os participantes recebem atualizações da reunião quando o corpo da reunião ou anexos mudam, em vez de o envio de uma atualização de reunião aos participantes ser opcional.
-   Correção de um problema que impossibilita o usuário de se conectar a pontos de extremidade de EWS e REST devido a uma alteração na cadeia de caracteres Usuário-Agente.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que o PowerPoint falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que o Painel de Recuperação é exibido de forma incorreta quando o Salvamento Automático está ativado.
-   Correção de um problema em que a opção para entrar não é exibida, impedindo o usuário de acessar um arquivo.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema em que usar o menu suspenso Filtro Automático em uma coluna de datas faz com que todas as tarefas do projeto sejam ocultas.
-   Correção de um problema em que somente a primeira tarefa resumo é exibida na caixa de diálogo ao adicionar tarefas existentes a uma linha do tempo quando no modo de exibição de Linha do Tempo.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema em que o Word falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que a numeração de página em algarismos romanos minúsculos são alterados de forma incorreta para maiúsculos.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1803-april-10"></a>Versão 1803: 10 de abril
*Versão 1803 (build 9126.2152)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que a coautoria de vários usuários na mesma apresentação gera uma duplicação incorreta dos slides mestres.
-   Correção de um problema em que abrir um arquivo salvo no OneDrive resulta em falha no PowerPoint ao sair do Modo de Exibição Protegido.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Correção de um problema relacionado ao suporte do TLS 1.2.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Correção de um problema que causa a exibição de uma mensagem de memória insuficiente.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1803-march-20"></a>Versão 1803: 20 de março
*Versão 1803 (build 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que a Impressão Rápida de uma pasta de trabalho do Excel anexada ao email do Outlook pode não ser impressa.
-   Correção de um problema em que clicar em um hiperlink pode causar uma falha no Excel.
-   Correção de um problema em que usar funções de cubo pode causar uma falha no Excel.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: atualizações não relacionadas à segurança
-   Corrigir um problema em que o OneDrive for Business (Groove.exe) consome um núcleo dos núcleos da CPU (por exemplo, 25% em uma CPU de 4 núcleos) no Gerenciador de Tarefas por longos períodos de tempo.

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que atualizar o local da reunião para os participantes mostra o local antigo em vez de o novo local.
-   Correção de um problema em que o usuário vê uma mensagem de erro quando visualiza um anexo no painel de leitura.
-   Correção de um problema em que o Outlook falha ao resolver a exibição de nomes para endereços de email quando o usuário estiver redigindo um email.
-   Correção de um problema em que alguns usuários não recebem os recursos de suporte que foram habilitados pelo administrador de locatários.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Corrige um problema onde o Word não abre em um computador executando o Windows 7 e que não têm a [atualização para telemetria de diagnóstico e experiência do usuário](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry) instalado.
-   Correção de um problema em que os marcadores não são impressos em listas.



## <a name="version-1803-march-13"></a>Versão 1803: 13 de março
*Versão 1803 (build 9126.2072)*

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): vulnerabilidade de execução remota de código do Microsoft Access

### <a name="access-non-security-updates"></a>Access: atualizações não relacionadas à segurança
-   Correção de um problema em que o aplicativo em tempo de execução do Access (arquivo .accde) gera a mensagem de erro "Este banco de dados está em um formato desconhecido" e não abre.
-   Correção de um problema em que tentar selecionar o texto em uma caixa de texto ou caixa de combinação parecia selecionar todo o texto, em vez da seleção de indicação.

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
-   **Microsoft Translator:** traduza palavras, frases ou sentenças para outro idioma com o Microsoft Translator. Você pode fazer isso na guia Revisão na faixa de opções.
-   **Converter ícones SVG em formas:** transforme todas as imagens e ícones SVG em formas do Office para que você possa alterar a cor, o tamanho ou a textura.
-   **Anular seleção de células:** faça seleções na planilha e anule a seleção de células clicadas acidentalmente sem ter que começar tudo do início.
-   **Acesse rapidamente sites e grupos:** use o menu Arquivo para trabalhar com documentos armazenados em seus sites e grupos usados frequentemente.
-   **Lápis Digital:** escreva ou esboce suas ideias com nossa nova textura de lápis. Basta inclinar as canetas digitais compatíveis para fazer sombreamento.
-   **Configuração de recursos do LinkedIn:** vá para Arquivo \> Opções \> Geral para controlar a exibição dos recursos do LinkedIn nos aplicativos do Office. [Saiba mais](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelos 3D:** Use o 3D para aumentar o impacto visual e criativo de suas pastas de trabalho.  Insira facilmente um modelo 3D: em seguida, você poderá girá-lo 360 graus. [Saiba mais](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Novos efeitos de tinta:** expresse suas ideias com estilo usando efeitos de tinta e canetas metálicas, como arco-íris, galáxia, lava, oceano, ouro, prata e muito mais.
-   **Compartilhar arquivos da interface do usuário:** no caso de arquivos do OneDrive for Business ou do SharePoint, clique no botão Compartilhar, no canto superior direito da faixa de opções, ou vá para Arquivo \> Compartilhar a fim de inicializar a caixa de diálogo Compartilhar aprimorada e simplificada. Para arquivos novos ou salvos localmente, a interface do usuário permite aos usuários enviar facilmente os arquivos para o OneDrive para começar a colaborar.
-   **Bloqueie extensões perigosas:** as extensões consideradas de alto risco inseridas como objetos de pacote OLE são bloqueadas de ativação por padrão. Por exemplo, .exe, .vbs e .js. [Saiba mais](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Sons úteis melhoram a acessibilidade:** ative as indicações de áudio para orientá-lo durante o trabalho. Para encontrar o recurso, vá para Arquivo \> Opções \> Facilidade de Acesso. Não é necessário usar suplementos. [Saiba mais](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Locais de arquivos por conta:** ao abrir ou salvar um arquivo, a lista de locais é organizada pela conta associada a eles.
-   **Personalização de canetas:** escolha um conjunto pessoal de canetas e marca-textos para escrita à tinta. O conjunto personalizado ficará disponível em todos os computadores Windows.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): vulnerabilidade de bypass do recurso de segurança do Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilidade de corrupção de memória do Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilidade de Corrupção de Memória do Microsoft Office
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilidade de Execução Remota de Código do Microsoft Excel
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): vulnerabilidade de Execução Remota de Código do Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): bypass de Recursos de Segurança do Microsoft Office Excel
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que, se o idioma de edição for o japonês, chinês ou coreano, o Excel congela quando você tenta escolher uma nova fonte na guia Página Inicial ou editar.
-   Correção de um problema em que as barras de rolagem ficavam ausentes quando uma pasta de trabalho era aberta ao minimizar o Excel.
-   Correção de um problema em que as referências da pasta de trabalho falham ao abrir várias pastas de trabalho clicando nos nomes dos arquivos no Explorador de Arquivos.
-   Correção de um problema em que a criação programática de uma Tabela Dinâmica seguida de uma atualização programática causa uma falha no Excel.
-   Correção de um problema em que chamar programaticamente o Workbook.Open() pode levar a uma falha no Excel.
-   Correção de um problema em que é exibida incorretamente ao usuário a mensagem de erro "Falha catastrófica" ao abrir uma pasta de trabalho com macros no Office 2007 ou versão anterior (.xls ou .xla).
-   Correção de um problema em que o Excel pode falhar quando um usuário abre um menu de contexto.
-   Correção de um problema em que, quando o usuário tenta inserir um objeto em uma pasta de trabalho existente, o Excel falha quando o usuário clica em Navegar.
-   Correção de um problema em que, ao proteger um intervalo com senha, a caixa de diálogo destinada a inserir a senha para desbloquear o intervalo não é exibida.
-   Correção de um problema em que o usuário não conseguia fechar uma pasta de trabalho no modo de exibição protegido quando o nome do arquivo continha colchetes.
-   Corrigido um problema em que o posicionamento da dica de ferramenta é desalinhado ao arrastar ou preencher arrastando.
-   Corrigido um problema em que, ao salvar uma pasta de trabalho usando Arquivo \> Salvar Como, um nome de arquivo que contém pontos aparece em branco ou truncado na caixa de diálogo Salvar arquivo.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.

### <a name="outlook-feature-updates"></a>Outlook: atualizações de recursos
-   **Classifique seus emails com facilidade:** graças aos seus comentários, trouxemos de volta a classificação acima da lista de mensagens e o filtro Não lidos para pessoas que não usam a Caixa de Entrada Destaques.
-   **Converter ícones SVG em formas:** transforme todas as imagens e ícones SVG em formas do Office para que você possa alterar a cor, o tamanho ou a textura.
-   **Melhorias nos Grupos do Office 365:** ficou mais fácil do que nunca ler e responder as conversas em grupo. Basta clicar duas vezes em uma mensagem de grupo para abri-la em sua própria janela.
-   **Configuração de recursos do LinkedIn:** vá para Arquivo \> Opções \> Geral para controlar a exibição dos recursos do LinkedIn nos aplicativos do Office. [Saiba mais](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelos 3D:** Use o 3D para aumentar o impacto visual e criativo do seu email. Insira facilmente um modelo 3D e, em seguida, você poderá girá-lo 360 graus. [Saiba mais](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Cartão de perfil:** mostra os detalhes mais relevantes sobre pessoas e grupos, esteja você na área de trabalho, na Web ou usando um aplicativo móvel.
-   **Adicione um compromisso a um calendário de grupo:** agora você pode permitir que todos no seu grupo saibam quando você estará ausente sem enviar um email.
-   **Baixando anexos de nuvem:** quando você salva ou arrasta e solta os anexos do OneDrive no computador, nosso sistema baixa os arquivos para você.
-   **Sons úteis melhoram a acessibilidade:** Ative as indicações de áudio para orientá-lo durante o trabalho. Para encontrar o recurso, vá para Arquivo \> Opções \> Facilidade de Acesso. Não é necessário usar suplementos. [Saiba mais](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Caixa de Entrada Destaques:** A Caixa de Entrada é separada em duas guias – Destaques e Outros. As mensagens são classificadas com base no conteúdo da mensagem e com quem você interage com mais frequência. [Saiba mais](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **Acesse rapidamente os grupos que você mais usa:** agora, os grupos com os quais é mais provável que você interaja aparecem no topo da lista em Grupos no painel Pasta.

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidade de Execução Remota de Código do Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): vulnerabilidade de elevação de privilégio do Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): vulnerabilidade de corrupção de memória do Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que a pesquisa falhava com "Nenhuma correspondência encontrada" quando a pesquisa estava com escopo para Todas as Caixas de Correio.
-   Correção de um problema em que o Outlook falha ao alternar entre pastas durante o monitoramento com a ferramenta Accessible Event Watcher (AccEvent.exe).

### <a name="powerpoint-feature-updates"></a>PowerPoint: atualizações de recursos
-   **Microsoft Translator:** traduza palavras, frases ou sentenças para outro idioma com o Microsoft Translator. Você pode fazer isso na guia Revisão na faixa de opções.
-   **Animações 3D:** dê vida aos modelos 3D com animações como balançar suavemente ou saltar e girar.
-   **Converter ícones SVG em formas:** transforme todas as imagens e ícones SVG em formas do Office para que você possa alterar a cor, o tamanho ou a textura.
-   **Roaming de informações de acompanhamento de revisão:** o status de lido/não lido para realçar os slides compartilhados que foram modificados por outras pessoas agora está armazenado em um serviço de roaming (em vez de no computador local do usuário) para que essas informações possam ser sincronizadas em vários dispositivos ou plataformas.
-   **Acesse rapidamente sites e grupos:** use o menu Arquivo para trabalhar com documentos armazenados em seus sites e grupos usados frequentemente.
-   **Lápis Digital:** escreva ou esboce suas ideias com nossa nova textura de lápis. Basta inclinar as canetas digitais compatíveis para fazer sombreamento.
-   **Configuração de recursos do LinkedIn:** vá para Arquivo \> Opções \> Geral para controlar a exibição dos recursos do LinkedIn nos aplicativos do Office. [Saiba mais](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Execute uma apresentação de slides com sua caneta digital:** use a Caneta Surface ou outra caneta com um botão Bluetooth, para avançar os slides. Windows 10 Fall Creators Update necessário. [Saiba mais](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **Modelos 3D:** Use o 3D para aumentar o impacto visual e criativo das suas apresentações. Dê vida a modelos 3D nas suas apresentações com transições como Transformar, que criam animações espetaculares entre os slides. [Saiba mais](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Novos efeitos de tinta:** expresse suas ideias com estilo usando efeitos de tinta e canetas metálicas, como arco-íris, galáxia, lava, oceano, ouro, prata e muito mais.
-   **Compartilhar arquivos da interface do usuário:** no caso de arquivos do OneDrive for Business ou do SharePoint, clique no botão Compartilhar, no canto superior direito da faixa de opções, ou vá para Arquivo \> Compartilhar a fim de inicializar a caixa de diálogo Compartilhar aprimorada e simplificada. Para arquivos novos ou salvos localmente, a interface do usuário permite aos usuários enviar facilmente os arquivos para o OneDrive para começar a colaborar.
-   **Bloqueie extensões perigosas:** as extensões consideradas de alto risco inseridas como objetos de pacote OLE são bloqueadas de ativação por padrão. Por exemplo, .exe, .vbs e .js. [Saiba mais](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Realce de revisão:** os slides modificados por outros usuários são realçados.
-   **Enquanto você estava fora:** o PowerPoint mostra quem editou sua apresentação compartilhada desde sua última visita.
-   **Melhoria do Designer:** agora, o Designer recomenda Ideias de Design para linhas do tempo em uma lista com marcadores.
-   **Sons úteis melhoram a acessibilidade:** Ative as indicações de áudio para orientá-lo durante o trabalho. Para encontrar o recurso, vá para Arquivo \> Opções \> Facilidade de Acesso. Não é necessário usar suplementos. [Saiba mais](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Locais de arquivos por conta:** ao abrir ou salvar um arquivo, a lista de locais é organizada pela conta associada a eles.
-   **Personalização de canetas:** escolha um conjunto pessoal de canetas e marca-textos para escrita à tinta. O conjunto personalizado ficará disponível em todos os computadores Windows.
-   **Melhoria do Designer:** agora, o Designer recomenda ideias de design para gráficos adicionados aos slides.
-   **Iniciador Rápido:** cria uma estrutura de tópicos automaticamente para ajudar os usuários a iniciar a pesquisa de um tema. [Saiba mais](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **Régua digital:** Em dispositivos com tela touch, vá para Desenhar \> Régua, use a caneta ou o dedo para desenhar linhas retas ou alinhar um conjunto de objetos. [Saiba mais](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilidade de divulgação não autorizada de informações do Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que remover propriedades do documento e informações pessoais podem causar uma falha no salvamento do SharePoint.
-   Correção de um problema em que as referências a códigos de inserção do YouTube com base no Flash Player resultam na abertura de uma nova janela para reproduzir o vídeo. Antigos códigos de inserção agora foram atualizados para fazer referência a vídeos do YouTube com base em HTML5 para que possam ser reproduzidos corretamente no lugar.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.

### <a name="project-feature-updates"></a>Project: atualizações de recursos
-   **Modo de exibição Painel de Tarefas:** classifique as tarefas nos cartões no modo de exibição Painel de Tarefas. Reordene e mova os cartões entre colunas no quadro, assim como em projetos Agile.
-   **Projetos Agile:** gerencie os projetos Agile usando listas de pendências, painéis de tarefas, sprints e muito mais. As metodologias Scrum ou Kanban são compatíveis. [Saiba mais](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Gerencie uma tarefa no Planner:** vincule uma tarefa do Project ao Planner e crie um plano para ela. Divida a tarefa em subtarefas, adicione uma equipe, atribua tarefas e gerencie o trabalho em um quadro de tarefas.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao definir mais de uma linha de base em uma sessão, o valor MOD\_DATE é definido como o mesmo.
-   Correção de um problema em que o Trabalho Real continuava a ser mostrado nas tabelas de relatório depois de ser removido de uma sessão de Salvar para Compartilhamento.
-   Correção de um problema na versão do idioma alemão em que usar o formato de data Semanas retornava um erro ao agendar.
-   Correção de um problema em que, ao editar as datas de término na Web Part de Agenda, as tarefas permaneciam oito horas por dia em vez de serem distribuídas ao longo do tempo.
-   Correção de um problema em que a "Forma do ponto de andamento" era desenhada em um local inesperado.
-   Correção de um problema em que o código VBA perde-se dos projetos.
-   Correção de um problema em que as tarefas são exibidas como concluídas mesmo quando ainda há trabalho restante.
-   Correção de um problema em que o Project trava ao usar o recurso Caminho da Tarefa.
-   Correção de um problema em que a escala de tempo não mostra os rótulos de escala de tempo.
-   Correção de um problema em que os relatórios visuais mostram informações incompletas ou falham completamente.
-   Correção de um problema em que uma falha no salvamento pode corromper um arquivo e fazer o Project falhar ao abrir.
-   Correção de um problema em que não é possível arrastar tarefas no modo de exibição de Linha do Tempo e Planejador de Equipe.
-   Correção de um problema em que a disponibilidade de recursos não é exibida no Criador de Equipe.
-   Correção de um problema em que os indicadores gráficos não são exibidos corretamente.
-   Correção de um problema em que o Project trava durante o nivelamento de hora em hora ou de dia a dia.
-   Correção de um problema ao trabalhar em projetos mestre ou subprojetos de uma biblioteca de documentos do SharePoint.
-   Correção de um problema em que, ao adicionar atribuições a uma tarefa de duração fixa, o recurso pode ficar sem nome.
-   Correção de um problema em que uma mensagem de erro incorreta era gerada indicando alterações em uma pasta protegida.
-   Foi corrigido um problema no qual o Project podia falhar ao acessar relatórios com várias imagens.

### <a name="publisher-feature-updates"></a>Publisher: atualizações de recursos
-   **Bloqueie extensões perigosas:** as extensões consideradas de alto risco inseridas como objetos de pacote OLE são bloqueadas de ativação por padrão. Por exemplo, .exe, .vbs e .js. [Saiba mais](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher: atualizações não relacionadas à segurança
-   Corrigido um problema em que a filtragem de campos de fontes de dados que contêm valores nulos (vazios) falha ao executar o Assistente de Mala Direta.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Correção de um problema quando, ao adicionar usuários escolhendo "Chamada do Skype" em uma reunião causa um erro.
-   Remove o prompt que pede ao usuário para adicionar coordenadas do Skype a uma reunião se uma Sala de Skype for adicionada como o local e a reunião já contiver as coordenadas de reunião das Equipes.
-   Correção de um problema em que o local é preenchido, mesmo quando UseLocationForE911Only é definido como verdadeiro.
-   Correção de um problema em que o Skype for Business trava ao usar a opção "ligar usando o centro de conferências" para convidar usuários da lista de participantes.
-   Correção de um problema em que o Outlook em execução no servidor de área de trabalho remota congela ao criar uma reunião do Skype for Business.
-   Altere o valor padrão de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket para TRUE.
-   Correção de um problema em que os botões "Mais Opções" e "Convidar Mais Pessoas" ficavam ocultos quando uma reunião estava ocorrendo no modo de tela inteira.
-   Correção de um problema em que a janela de chamada de áudio P2P ou a janela de chamada em conferência ficava transparente quando você tentava ingressar.
-   Correção de um problema em que as futuras reuniões do Skype não eram mostradas na guia Reunião.
-   Correção de um problema em que, quando o Skype for Business estava configurado para ingressar em reuniões sem áudio, ao adicionar áudio a uma reunião, uma chamada P2P era iniciada para o usuário em vez de adicionar áudio à reunião existente.
-   Correção de um problema em que o usuário recebia a mensagem de erro "Não foi possível encontrar esta reunião do Skype" quando clicava no link "Ingressar na Reunião do Skype" em uma solicitação de reunião do Outlook.
-   Adição de um botão de transferência de chamada na interface do usuário do sistema para chamadas PSTN de entrada.
-   Avisa aos usuários que as chamadas e o chat estão sendo enviados para o Teams quando ChatDefaultClient e CallDefaultClient estão definidos para o Teams.
-   Mostra a presença do usuário como Offline quando o usuário não está em uma reunião e desativado no Skype for Business e a experiência de ingresso da reunião está definida como Cliente Nativo Limitado.
-   Desabilita todas as opções exceto Abrir e Sair quando o Skype for Business é minimizado para a área de notificação.
-   Suprime novas chamadas e conversas quando combinado com telefones Aries e RedirectClient está habilitado.
-   Correção de um problema em que a pesquisa por mensagens no PChat por data falha quando o formato de data é diferente do formato americano (mm/dd/aa).
-   Correção de um problema em que, quando a política EnableExternalP2PFileTransfer está definida como false, os usuários ainda podem anexar arquivos em reuniões.
-   Correção de um problema em que o programa mostra o autor da chamada em vez de mostrar o destinatário no Histórico da Conversa. Isso ocorre quando o número comercial do destinatário da chamada é modificado por meio do Active Directory.
-   Correção de um problema em que as informações do destinatário ficam ausentes no histórico de chamadas do Histórico da Conversa, no caso das chamadas PSTN de saída para números de celular.
-   Correção de um problema em que, ao iniciar uma mensagem instantânea em um email do Outlook, a linha do assunto do email não é incluída no assunto da mensagem instantânea.
-   Correção de um problema em que, quando as janelas da conversa de uma mensagem instantânea são ajustadas em um único lado, as conversas parecem empilhadas duplamente.
-   Correção de um problema em que as solicitações de compartilhamento de tela VBSS são exibidas como solicitações baseadas em RDP, em um ambiente VDIv2.
-   Correção de um problema em que, em uma transferência de chamada com falha, o autor da chamada é exibido em vez de o destinatário na notificação de falha.
-   Correção de um problema em que o botão "Comece a usar o Teams" fica oculto na faixa de redirecionamento de atualização do cliente.
-   Correção de problemas de ajuste de DPI em janelas de mensagens instantâneas.
-   Correção de um problema em que os dados do LinkedIn não são exibidos no Cartão de Visita do Skype for Business.
-   Adicione o recurso para que os usuários possam parar de receber chamadas em nome de um grupo de busca.
-   Adicione a capacidade de reter chamadas automaticamente quando uma chamada estiver ativa no Skype for Business ou Teams e uma nova chamada for recebida ou iniciada.
-   Correção de um problema em que os usuários não conseguem enviar mensagens instantâneas após o compartilhamento em tela cheia.
-   Correção de um problema em que os usuários no lobby não são notificados quando o acesso deles à reunião é negado.
-   Correção de um problema em que o controle de ganho automático aumenta incontrolavelmente durante as chamadas.
-   Foi corrigido um problema no qual os usuários não conseguiam selecionar um apresentador nas Opções de Reunião quando uma caixa de correio de recursos de sala de conferência era adicionada a um convite para reunião.
-   Foi corrigido um problema no qual o botão de compartilhamento de área de trabalho ficava esmaecido durante uma chamada de vídeo ponto a ponto se AllowlPVideo estivesse definido como False.
-   Foi corrigido um problema no qual as mensagens instantâneas permaneciam desabilitadas após alterar a configuração Opção de Reunião para Habilitar Mensagens Instantâneas para reuniões existentes criadas com Desabilitar Mensagens Instantâneas.
-   Foi corrigido um problema no qual a dica de ferramenta não era mostrada ao passar o mouse sobre o botão "Inserir Link" na janela de bate-papo, e não havia um nome de acessibilidade quando o botão era selecionado.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos
-   **Diagramas de modelo de banco de dados integrado:** use um modelo do novo recurso Diagrama de Modelo de Banco de Dados para modelar o banco de dados de forma precisa como um diagrama do Visio, sem precisar usar suplementos.
-   **Mais estênceis para os diagramas de negócios:** usando formas modernas, compare e contraste os dados com um diagrama de Venn, ou desenhe os diagramas de Ciclo, Matriz ou Pirâmide para ajudá-lo a contar sua história.
-   **Crie um diagrama delineado para um site:** crie rapidamente um diagrama delineado de um site incluindo uma interface, navegação e como eles funcionam em conjunto. [Saiba mais](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Criar um delineado do aplicativo móvel:** use um modelo para criar um delineado do aplicativo móvel. [Saiba mais](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Aplicar dados gráficos aos diagramas do Visualizador de Dados:** Economize tempo ao criar um diagrama do Visualizador de Dados aplicando automaticamente dados de formas como gráficos de dados. [Saiba mais](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **Colabore em desenhos:** trabalhe com outras pessoas, compartilhando seus desenhos no OneDrive for Business ou SharePoint Online. Você pode ver quem está trabalhando no desenho, adicionar comentários e ver a atividade no arquivo.[Saiba mais](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **Bloqueie extensões perigosas:** as extensões consideradas de alto risco inseridas como objetos de pacote OLE são bloqueadas de ativação por padrão. Por exemplo, .exe, .vbs e .js. [Saiba mais](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word: atualizações de recursos
-   **Converter ícones SVG em formas:** transforme todas as imagens e ícones SVG em formas do Office para que você possa alterar a cor, o tamanho ou a textura.
-   **Contagem de caracteres:** exiba a contagem de caracteres na barra de status enquanto digita. Habilite esta opção no menu Personalizar Barra de Status.
-   **Acesse rapidamente sites e grupos:** use o menu Arquivo para trabalhar com documentos armazenados em seus sites e grupos usados frequentemente.
-   **Microsoft Translator:** traduza palavras, frases ou o documento inteiro para outro idioma usando o Microsoft Translator, diretamente do Word. [Saiba mais](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **Lápis Digital:** escreva ou esboce suas ideias com nossa nova textura de lápis. Basta inclinar as canetas digitais compatíveis para fazer sombreamento.
-   **Configuração de recursos do LinkedIn:** vá para Arquivo \> Opções \> Geral para controlar a exibição dos recursos do LinkedIn nos aplicativos do Office. [Saiba mais](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Painel de propriedades do SharePoint:** Exiba e edite valores da coluna de biblioteca do SharePoint a partir de um documento. Um botão da faixa de opções na guia Exibir fornece acesso fácil ao painel, e os administradores do SharePoint podem usar a configuração da biblioteca de documentos para abrir automaticamente o painel de propriedades.
-   **Modelos 3D:** Use o 3D para aumentar o impacto visual e criativo dos seus documentos. Insira facilmente um modelo 3D e, em seguida, você poderá girá-lo 360 graus. [Saiba mais](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Novos efeitos de tinta:** expresse suas ideias com estilo usando efeitos de tinta e canetas metálicas, como arco-íris, galáxia, lava, oceano, ouro, prata e muito mais.
-   **Compartilhar arquivos da interface do usuário:** no caso de arquivos do OneDrive for Business ou do SharePoint, clique no botão Compartilhar, no canto superior direito da faixa de opções, ou vá para Arquivo \> Compartilhar a fim de inicializar a caixa de diálogo Compartilhar aprimorada e simplificada. Para arquivos novos ou salvos localmente, a interface do usuário permite aos usuários enviar facilmente os arquivos para o OneDrive para começar a colaborar.
-   **Bloqueie extensões perigosas:** as extensões consideradas de alto risco inseridas como objetos de pacote OLE são bloqueadas de ativação por padrão. Por exemplo, .exe, .vbs e .js. [Saiba mais](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Editar usando Ferramentas de Aprendizagem:** as Ferramentas de Aprendizagem já estão disponíveis no modo de exibição de layout da Web do Word. Ajuste o espaçamento de texto e mostre as sílabas durante a edição. Em qualquer modo de exibição, veja cada letra realçada à medida que o documento é lido em voz alta. [Saiba mais](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **Sintaxe LaTeX:** crie e edite equações matemáticas usando a sintaxe LaTeX.
-   **Sons úteis melhoram a acessibilidade:** Ative as indicações de áudio para orientá-lo durante o trabalho. Para encontrar o recurso, vá para Arquivo \> Opções \> Facilidade de Acesso. Não é necessário usar suplementos. [Saiba mais](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Locais de arquivos por conta:** ao abrir ou salvar um arquivo, a lista de locais é organizada pela conta associada a eles.
-   **Personalização de canetas:** escolha um conjunto pessoal de canetas e marca-textos para escrita à tinta. O conjunto personalizado ficará disponível em todos os computadores Windows.
-   **Assistência de escrita aprimorada com o painel Editor:** Use o painel Editor para obter recomendações de estilo de escrita, ortografia e gramática. Ele foi criado para ser acessado com suporte aprimorado a tecnologias adaptativas.

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): vulnerabilidade de Corrupção de Memória do Microsoft Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [Supervisão 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): atualização de proteção abrangente do Microsoft Office

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Corrigido um problema em que o Word falha quando um usuário tenta Salvar Como para um documento existente no OneDrive for Business e cancela o salvamento ou tenta mesclar alterações existentes.
-   Corrigido um problema em que a filtragem de campos de fontes de dados que contêm valores nulos (vazios) falha ao executar o Assistente de Mala Direta.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Corrigido um problema em que remover a proteção de IRM em um documento não remove a proteção.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [Supervisão 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): atualização de proteção abrangente do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao abrir um aplicativo, às vezes o usuário via uma mensagem sobre a inicialização no modo de segurança e, em seguida, o aplicativo não abria.
-   A opção Atualizar Agora fica oculta em Opções de Atualização da \> Conta \> do Arquivo quando um objeto COM do Office está habilitado para que as atualizações de cliente do Office 365 sejam gerenciadas pelo Gerenciador de Configurações.
-   Correção de um problema em que o aplicativo do Office falha quando o usuário tenta ativá-lo usando a caixa de diálogo Ativar o Office.
-   Correção de um problema com o zoom e dimensionamento em Suplementos do Office em um ambiente de DPI dinâmico.
-   Correção de um problema em que o nó CurrentStatus do provedor de serviços de configuração (CSP) do Office retorna uma cadeia de caracteres vazia mesmo se o Office 365 ProPlus estiver instalado atualmente.
-   Correção de um problema que causa mudanças de formato no arquivo .box, o que afeta a funcionalidade de versões mais antigas do Office instaladas no mesmo computador, porque os arquivos .box são compartilhados entre todas as versões de um aplicativo do Office no mesmo computador.



## <a name="version-1708-february-13"></a>Versão 1708: 13 de fevereiro
*Versão 1708 (build 8431.2215)*

### <a name="access-non-security-updates"></a>Access: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao usar um formulário com vários itens, ajustar a posição do botão de rolagem do mouse ou miniatura da barra de rolagem não altera os itens exibidos no formulário.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): vulnerabilidade de elevação de privilégio do Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): vulnerabilidade de corrupção de memória do Microsoft Outlook

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office



## <a name="version-1708-january-9"></a>Versão 1708: 9 de janeiro
*Versão 1708 (build 8431.2153)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilidade de execução remota de código do Microsoft Excel
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que a criação programática de uma Tabela Dinâmica seguida de uma atualização programática causa uma falha no Excel.

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidade de execução remota de código do Microsoft Outlook

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): vulnerabilidade de execução remota de código do Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): vulnerabilidade de corrupção de memória do Microsoft Word

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilidade de execução remota de código do Microsoft Office
-   [Supervisão 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): atualização de Proteção Abrangente do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Adição de suporte para logon único (SSO) para usuários do domínio de planos do Office 365 Germany em que a identidade for federada com um Active Directory local.
-   Adição de funcionalidade para evitar que menores de idade comprem e ativem suplementos do Office provenientes da Office Store.


> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).
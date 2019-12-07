---
title: Notas de versão para lançamentos do Canal Semestral (Direcionado) em 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece notas de versão aos profissionais de TI para lançamentos do Canal Semestral (Direcionado) do Office 365 ProPlus em 2019
ms.openlocfilehash: 45a382ee14fc4d9b2e92b7b911f1c8d1cb1ac67a
ms.sourcegitcommit: cdd69a3af5873fd60a3dabc010339acc19265db3
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/06/2019
ms.locfileid: "39890445"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a>Notas de versão para lançamentos do Canal Semestral (Direcionado) em 2019

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionados à segurança incluídos nas atualizações do Canal Semestral (Direcionado) para o Office 365 ProPlus em 2019, Visio Pro para Office 365, o cliente de Área de Trabalho do Project Online e o Office 365 Business.

> [!NOTE]
> - Muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Semestral (direcionado) durante um período de tempo. Se você não encontrar imediatamente algo descrito abaixo, aguarde que muito em breve estará disponível. [Saiba mais](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - O Microsoft Teams está incluído nas novas instalações do Canal Semestral (Direcionado), começando com a Versão 1902. As equipes serão adicionadas às instalações existentes do Canal Semestral (Direcionado) quando elas forem atualizadas para a Versão 1908 ou posterior. Para obter mais informações, confira [Implantar o Microsoft Teams com Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).

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

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

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

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidos com sucesso quando solicitado.</div>
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

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

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

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

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

### <a name="powerpoint"></a>PowerPoint

- **Saiba a opinião de seu público através de um questionário ou pesquisa:** coloque um questionário ou uma pesquisa em um slide. O Office coleta e armazena as respostas para você. [Saiba mais](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Inserir um vídeo online está mais fácil do que nunca:** Deseja colocar um vídeo do Vimeo ou YouTube no slide? O link da página de vídeo é tudo o que você precisa. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Melhoria na mudança de formas:** nomeie suas formas para ter mais controle sobre como elas são transformadas. [Saiba mais](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Os vídeos online têm um novo lar:** salve um vídeo no Microsoft Stream para que qualquer pessoa em sua organização possa vê-lo. Insira o link de vídeo e desfrute de uma apresentação multimídia com uma fração do tamanho do arquivo. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

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

- **Transforme seu documento de estático para incrível: ** transforme seu documento em uma página da web interativa e fácil de compartilhar, com uma aparência ótima em qualquer dispositivo. [Saiba mais](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Chame a atenção das pessoas com \@Menções:** use @menções nos comentários para que outras pessoas saibam quando precisa da contribuição delas. [Saiba mais](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Melhore a compreensão com Line Focus:** percorra a linha de um documento sem distrações. Ajuste o foco para colocar uma, três ou cinco linhas na visualização de cada vez. [Saiba mais](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Aumente o alcance do seu conteúdo:** precisa tornar seus documentos acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **O modo Ferramentas de Aprendizagem tem suporte adicional para mais cores de página:** as Ferramentas de Aprendizagem no Word adicionam suporte para mais cores de tema de página, o que permite a alteração da cor da tela de fundo da página. Várias pessoas têm desafios de leitura com um plano de fundo todo branco ou preto, então ampliamos as opções de cores no Word para PC e para Mac.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Diga adeus às distrações** um dos recursos favoritos do Mac acaba de chegar no Windows. Alterne para o modo Foco no menu Exibir para remover distrações e se concentrar no trabalho. [Saiba mais](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

### <a name="office-suite"></a>Pacote do Office

- **Instalação do Microsoft Teams:** O Teams foi adicionado nas instalações existentes do Office 365 ProPlus. [Saiba Mais](https://docs.microsoft.com/DeployOffice/teams-install)

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Controles de privacidade:** controles novos, atualizados e melhorados para dados de diagnóstico e experiências conectadas. [Saiba mais](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Os ícones do Office estão com um novo visual:** os ícones do Office foram reprojetados para refletir as experiências simples, poderosas e inteligentes do Office.

- **Instalação do Microsoft Teams:** o Microsoft Teams é instalado por padrão nas novas instalações do Office 365 ProPlus. [Saiba mais](https://docs.microsoft.com/DeployOffice/teams-install)


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

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

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

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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
<br/>Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

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

- Corrigido um problema em que partes de uma atualização do Office não usava o cache de pares de Otimização de Entrega. [Saiba mais](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
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
- **Digitação não assistida:** Você tem um microfone? Clique em Ditar e veja o PowerPoint digitar enquanto você fala.  [Saiba mais](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Ícones da faixa de opções têm uma aparência nova:** não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Hyperlinks em cor vibrante:** os hiperlinks não são mais apenas azuis. Aplique as cores de fonte que desejar. [Saiba mais](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Ver seus slides ganharem vida:** insira gráficos animados em 3D para ver batidas de corações, órbita de planetas e a fúria do T-Rex em toda a tela. [Saiba mais](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Você esboça, nós melhoramos:** transformamos textos e formas desenhadas em diagramas refinados. Basta selecionar seus traços de tinta para começar. [Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Ver o que está atrás de uma imagem:** coloque uma imagem em uma planilha, selecione o valor predefinido e observe a alteração de transparência. É isso![Saiba mais](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint. [Saiba mais](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Publicar no Microsoft Stream:** use o Microsoft Stream para compartilhar uma apresentação como vídeo de forma mais segura na organização. [Saiba mais](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Exportar para vídeo 4K:** quando você exporta uma apresentação para vídeo, a resolução 4K agora é uma opção.  [Saiba mais](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Arquivos grandes agora são abertos mais rapidamente: ** imagens, vídeos e outros elementos grandes agora são baixados em segundo plano quando você abre arquivos armazenados no OneDrive ou no SharePoint.

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
- **Instalação do Microsoft Teams:**  o Microsoft Teams é instalado por padrão nas novas instalações do Office 365 ProPlus. [Saiba mais](https://docs.microsoft.com/DeployOffice/teams-install)

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

- Corrigiu o problema em que os Suplementos, implantados usando [implantação centralizada do O365 Office ](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment), foram congelados e inutilizáveis.


## <a name="version-1808-january-8"></a>Versão 1808: 8 de janeiro
*Versão 1808 (Build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança 

- Correção um problema que levava os usuários a enfrentar problemas de sincronização do calendário.

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança

- Melhore o desempenho abrir.


> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).
---
title: Notas de versão para lançamentos do Canal Semestral arquivadas
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece notas de versão aos profissionais de TI para lançamentos do Canal Semestral do Office 365 ProPlus
ms.openlocfilehash: 983782e92fbcaeebe5bbcfceee691fee57134da3
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026336"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel"></a>Notas de versão para lançamentos do Canal Empresarial Semestral arquivadas

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionados à segurança incluídos nas atualizações do Canal Semestral para o Office 365 ProPlus, Visio Pro para Office 365, o cliente da Área de Trabalho do Project Online e o Office 365 Business.

> [!NOTE]
> - Muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Empresarial Semestral durante um período de tempo. Se você não vir algo descrito abaixo, aguarde que, muito em breve, estará disponível. [Saiba mais](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
> - O OneNote 2016 não será incluído por padrão, quando um usuário no Canal Empresarial Semestral baixar e instalar o Office 365 no Windows 10 do Portal do Office.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-december-08"></a>Versão 2002: 8 de setembro
*Versão 2002 (Build 12527.21416)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Melhor kerning de texto no PowerPoint quando o conteúdo é copiado do Excel e colado no PowerPoint com a opção embed.


- Corrigimos um problema em que o Excel para de funcionar durante o recálculo.


- Corrigimos um problema em que um usuário não podia abrir diretamente um arquivo atomsvc (UTF8+BOM) do Microsoft Office SharePoint Online.


- Correção de um problema que impedia a mudança da visualização da tabela e do editor de consulta no PowerPivot.


- Desempenho aprimorado para arquivos que estão usando muitas das funções liberadas recentemente.


### <a name="outlook"></a>Outlook

- Corrigido um problema em que a configuração da configuração do OME estava adicionando anexos estranhos no item de email que estava forçando o Outlook a criptografar a mensagem, mesmo que a opção DecryptAttachmentsForEncryptOnly fosse configurada no lado do serviço.


### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema em que o gráfico vinculado do Excel se altera incorretamente para a planilha do Excel quando o usuário altera o caminho de origem para a pasta local do OneDrive.


### <a name="project"></a>Microsoft Project

- Consertamos um problema em que os projetos não podiam ser abertos no cliente de área de trabalho do Project a partir do Project Web App, se a URL terminasse em '.com'.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-december-08"></a>Versão 1908: 8 de dezembro
*Versão 1908 (Build 11929.20984)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

## <a name="version-2002-november-10"></a>Versão 2002: 10 de novembro
*Versão 2002 (Build 12527.21330)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.


- Corrigimos um problema que poderia causar um travamento ao atualizar as tabelas dinâmicas OLAP.


- Corrigido um bug em que certas funções teriam um resultado incorreto após carregar uma pasta de trabalho.


- Corrigimos um problema em que o aplicativo fechava inesperadamente, o que estava relacionado a referências do suplemento XLAM e intervalos nomeados.


- Corrigido um problema em que a execução da macro de filtro avançado relatava erros incorretamente.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que os suplementos internos fossem inesperadamente desabilitados quando as experiências conectadas opcionais eram desabilitadas.


- Corrigimos um problema que impedia os usuários de enviar como ou em nome de uma Lista de Distribuição que estava oculta na Lista de Endereços Global.



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-1908-november-10"></a>Version 1908: 10 de novembro
*Versão 1908 (Build 11929.20974)*

Atualizações de segurança listadas[ aqui](./microsoft365-apps-security-updates.md)

## <a name="version-2002-october-13"></a>Version 2002: 13 de outubro
*Versão 2002 (Compilação 12527.21236)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Você não deve mais receber a menagem "A consulta é muito complexa" ou "um recurso do sistema excedeu o erro" na versão de 64 bits do Access", desde que você esteja obedecendo as diretrizes e requisitos de banco de dados do Access.


- Depois de usar nosso recurso de filtro após nosso designer de consulta, seu banco de dados não deve mais falhar. Verifique se.


### <a name="excel"></a>Excel

- Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.


### <a name="powerpoint"></a>PowerPoint

- As novas apresentações criadas a partir de um modelo podem herdar uma configuração que impedia uma boa experiência de coautoria. Essa correção garante que a configuração esteja limpa neste caso.


### <a name="word"></a>Word

- Consertamos um problema no qual ao abrir documentos com quebras de página e colunas, o usuário pode encontrar uma mensagem de erro "você ultrapassou o número máximo de páginas permitidas pelo Microsoft Word ou o documento pode estar danificado"


### <a name="office-suite"></a>Pacote Office

- Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners. Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-october-13"></a>Versão 1908: 13 de outubro
*Versão 1908 (Compilação 11929.20966)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners. Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-september-08"></a>Versão 2002: 8 de setembro
*Versão 2002 (Build 12527.21104)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Isso aborda um problema em que as conexões criadas pelo provedor de dados SQL nas versões anteriores do Office definem as propriedades da tabela interna de modo diferente do Office 365. Isso fazia com que a lista suspensa da Visualização de tabela / Editor de consulta fosse desabilitada para arquivos com conexões criadas em versões mais antigas do Office quando eram abertas usando o Office 365.


- Resolvemos um problema em que a escrita à tinta poderia fazer com que o Excel não respondesse.


### <a name="outlook"></a>Outlook

- Corrige um problema que fazia com que os usuários não conseguissem se conectar às Pastas Públicas após adicionar uma caixa de correio compartilhada.


### <a name="office-suite"></a>Pacote Office

- Essa alteração corrige um problema com a caixa de diálogos Compactar imagem que não mantém determinadas configurações do usuário.



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO REGISTRO DE ERROS)

## <a name="version-1908-september-08"></a>Versão 1908: 8 de setembro
*Versão 1908 (Build 11929.20946)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

## <a name="version-2002-august-11"></a>Versão 2002: 11 de agosto
*Versão 2002 (Compilação 12527.20988)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema que impedia a capacidade de mudar para editar arquivos que foram abertos como "leitura somente recomendado".

### <a name="onenote"></a>OneNote

- Removido as chamadas de identidade redundantes para reduzir a utilização de recursos

- Melhoria na detecção de status de coautoria para reduzir a utilização de recursos.

- Melhoria na capacidade de detecção de erros e na experiência de sincronização com qualidade.

### <a name="outlook"></a>Outlook

- Foi abordado um problema que causava um problema de desempenho significativo ao iniciar o Outlook para alguns locatários.

### <a name="skype"></a>Skype

- Corrigido um problema em que iniciar um compartilhamento de tela pode falhar em um cliente do Skype for Business de 32 bits após ele estiver sendo executado por vários dias.

### <a name="office-suite"></a>Pacote do Office

- Corrigido um problema em que, quando o salvamento automático estava desativado na política de grupo, alguns documentos não podiam mostrar o conteúdo mais recente do servidor na abertura até o usuário clicar em "Atualizações disponíveis".

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-august-11"></a>Versão 1908: 11 de agosto
*Versão 1908 (Compilação 11929.20934)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

## <a name="version-1902-august-11"></a>Versão 1902: 11 de agosto
*Versão 1902 (Compilação 11328.20644)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-july-14"></a>Versão 2002: 14 de julho
*Versão 2002 (Build 12527.20880)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas. [Saiba mais](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.

- **Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel. [Saiba mais](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar. [Saiba mais](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)

- **Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones. Encontre-os em Inserir > Ícones. [Saiba mais](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)

- **Foco no que precisa ser feito:** selecione Resolver para recolher comentários e destacar os itens abertos.

- **Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão automaticamente enviados para as células vizinhas. [Saiba mais](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Faça um Esboço:** Deixe as formas do Office da sua pasta de trabalho com uma aparência casual de desenhado à mão. [Saiba mais](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)

- **Encontre o que está procurando:** Pesquise comandos, pessoas, arquivos, fotos, artigos da Web e muito mais. [Saiba mais](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE e RANDARRAY. [Saiba mais](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!:** Linha por linha, encontre tudo o que você precisa em uma tabela ou intervalo com o XLOOKUP. [Saiba mais](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)

- **Controle sua pasta de trabalho grande:** células, fórmulas, gráficos, tabelas. Obtenha um instantâneo da sua pasta de trabalho com Estatísticas de Pasta de Trabalho.

- **Leia e responda instantaneamente:** responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.

- **Chame a atenção com \@@Menções:** Use @menções nos comentários para informar a seus colegas de trabalho quando precisar deles. [Saiba mais](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a>Outlook

- **Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens. [Saiba Mais](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones. Encontre-os em Inserir > Ícones. [Saiba mais](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Deixe-me desenhar:** Rabisque em fotos ou adicione uma Tela de Desenho para enviar seus pensamentos com tinta. [Saiba Mais](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Obtenha sugestões de locais:** comece a digitar em Local ao agendar compromissos e reuniões, e o Outlook irá sugerir salas, endereços e outros locais recentes. [Saiba mais](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)

- **Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.

- **O menu Inserir Link no Outlook inserirá um link com a permissão definida pelo administrador do locatário:** um link do Inserir Link MRU no Outlook insere um link que só funcionou para usuários que já tinham permissões. Isso causou uma troca de emails frequente entre os usuários solicitando o acesso a um documento. Atualizamos essa experiência e agora o link é inserido com a permissão padrão definida pelo administrador do locatário. No MSIT, é "A organização pode editar", para que todos os usuários internos que recebem um link compartilhado dessa maneira possam acessá-lo.

- **Veja suas mensagens sob uma perspectiva diferente:** use o botão Sol/Lua para alternar entre planos de fundo claros e escuros no painel de leitura. [Saiba Mais](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **Emails de phishing fáceis de identificar:** As mensagens de spam e phishing têm uma aparência diferente, para que você possa identificá-las e eliminá-las facilmente na caixa de entrada.

- **Todas as opções de criptografia em um só lugar:** Basta ir para Opções > Criptografar para escolher como proteger sua mensagem de email. [Saiba mais](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Pesquisar com erros de ortografia ou digitação:** o Outlook encontrará o que você está procurando, mesmo quando a ortografia não corresponder.

- **Conecte sua rede do LinkedIn ao Outlook:** Conecte sua conta do LinkedIn com segurança à sua conta da Microsoft para ver informações de perfis do LinkedIn diretamente no cartão de Pessoas. [Saiba Mais](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Veja as mensagens relevantes nos resultados de pesquisa:** o Outlook analisa os termos de pesquisa e mostra as mensagens de email mais relevantes na parte superior dos resultados da pesquisa. Você também verá todos os resultados classificados por data, na seção Resultados Principais. [Saiba Mais](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a>PowerPoint

- **Você calcula, nós formatamos:** Nós trocamos expressões matemáticas difíceis de desenhar por caracteres padrão. Basta escolher Tinta para Matemática e selecionar suas anotações manuscritas para começar.[Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais. [Saiba mais](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint. [Saiba mais](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Faça um Esboço:** deixe as formas do Office da sua apresentação com uma aparência casual de desenhado à mão. [Saiba mais](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)

- **Repe-tinta-ção Instantânea:** Ao escrever à tinta nos slides, aplique uma animação de repetição para reproduzir o desenho real da sua tinta durante a apresentação de slides. [Saiba mais](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)

- **Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.

- **Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem. [Saiba Mais](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos. Deixá-los ou não ativados depende de você. [Saiba Mais](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Localize e corrija títulos de slides ausentes:** Títulos de slides reforçam o seu discurso e tornam os seus slides acessíveis a usuários de todas as habilidades. O Verificador de Acessibilidade mostra onde os títulos estão ausentes para que você possa adicioná-los imediatamente. [Saiba mais](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)

- **Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones. Encontre-os em Inserir > Ícones. [Saiba mais](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)

- **Compartilhamento rápido de arquivo**: compartilhe seus documentos diretamente da lista usada recentemente sem precisar abrir o arquivo.

- **Colaboração rápida e em tempo real no PowerPoint:** colaboração rápida e em tempo real no PowerPoint

- **Não é mais necessário voltar ao navegador:** você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Novas ferramentas de revisão:** não se preocupe com suas palavras. Agora, o PowerPoint fornece sugestões de gramática e ortografia. [Saiba mais](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **Legendas em tempo real:** As palavras do apresentador aparecem na tela automaticamente como legendas ou traduzidas para o idioma que escolher. [Saiba mais](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Otimize sua apresentação para todos:** o Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)

- **Por que reinventar quando você pode reutilizar?:** economize tempo reutilizando slides que você criou ou que outras pessoas compartilharam com você. [Saiba mais](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a>Visio

- **Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha. [Saiba mais](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Voltando para a cena do crime:** Use os novos estênceis de Evidência, Interno e Externo no modelo de Investigação de Cena de Crime para recriar cenas de crimes em detalhes.

### <a name="word"></a>Word

- **Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você. [Saiba mais](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar. [Saiba mais](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)

- **Compartilhamento rápido de arquivo**: compartilhe seus documentos diretamente da lista usada recentemente sem precisar abrir o arquivo.

- **Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones. Encontre-os em Inserir > Ícones. [Saiba mais](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)

- **Apagar com precisão:** Escolha entre dois tamanhos de borracha para corrigir pequenas imperfeições à tinta. [Saiba mais](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)

- **Faça um Esboço:** deixe as formas do Office do seu documento com uma aparência casual de desenhado à mão. [Saiba mais](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)

- **Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais. [Saiba mais](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo. [Saiba mais](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **O Editor de Currículos se une ao Assistente de Currículos do LinkedIn:** O Editor de Currículos oferece uma seleção de verificações gramaticais e de estilo especialmente adaptadas para currículos, para tornar a sua escrita mais precisa e profissional.

- **Outras pessoas veem suas alterações rapidamente:** os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas alterações mais rápido do que nunca.

- **Corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D:** corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D.

- **Aperfeiçoamentos de coautoria**: desempenho aperfeiçoado do Word durante a coautoria em documentos com alterações controladas.

- **Melhorias na coautoria** confiabilidade aprimorada durante a coautoria.

- **Colabore em cores:** Comentários e alterações são codificados por cores por colaborador, para que seja fácil ver quem está entre seus colaboradores.

- **Edite documentos habilitados para macro de maneira colaborativa:** Salve arquivos docm no OneDrive for Business e edite-os com seus colaboradores em tempo real.

### <a name="office-suite"></a>Pacote Office

- **Transforme tinta manuscrita em formas, texto ou expressões matemáticas no PowerPoint para Office 365:** Vá de tinta de forma livre para formas, texto ou uma expressão matemática com apenas alguns traços. [Saiba Mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esta atualização corrige um problema no uso de um ADODB. O objeto gravador no código VB pode incorretamente relatar um erro.

- Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados. Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.

- Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.

- Esta atualização corrige um problema no Microsoft Access que pode causar o erro “A consulta está corrompida” quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada no SQL.

### <a name="excel"></a>Excel

- Acelerar o carregamento de arquivos disponíveis na pasta local do OneDrive.

- Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

- O Excel falhava em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.

- Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.

- Corrigimos o menu do botão direito do mouse de Gráficos Dinâmicos para habilitar a opção Mostrar Detalhes.

- Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.

- Corrigido um problema em que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.

- Ao salvar como um arquivo CSV, o Excel poderia mesclar todas as colunas em uma única coluna em alguns casos.

- Usar Range.ClearContents em um intervalo de uma planilha protegida pode levar mais tempo do que o esperado.

- Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.

- As macros do VBA que interagem com a faixa de opções podem ser executadas com o conjunto de ScreenUpdating definido como Verdadeiro inesperadamente.

- Corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos após copiar uma planilha contendo uma Tabela Dinâmica.

- A abertura de arquivos CSV estava demorando mais do que o esperado em algumas circunstâncias.

- O Excel pode falhar em algumas circunstâncias ao alternar entre pastas de trabalho com diferentes níveis de zoom.

- Correção de um problema com o VBA no qual a escrita de valores em um intervalo seria mais lento do que o esperado.

- Os dados copiados de uma coluna filtrada por cores às vezes não serão colados corretamente.

- Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, principalmente com janelas ocultas, era mais lento do que o esperado.

- Solucionado um problema em que os links externos não eram atualizados durante o preenchimento (preencher abaixo, preencher entre, etc.) se o livro de origem estivesse& fechado.

- Corrigido um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- Corrigido um problema em que a propriedade "O Valor Cruza Em" no eixo do gráfico se altera inesperadamente ao salvar e reabrir um arquivo.

- Correção de um problema que causava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.

- Desempenho aprimorado ao excluir colunas com células mescladas.

- Correção de um problema em que os nomes de impressora poderiam ser repetidos na lista de impressoras na caixa de diálogo Imprimir.

- Corrigido um problema em que o link externo para de funcionar depois que o arquivo é reaberto se o caminho do arquivo é muito longo.

- Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.

- Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".

- Inserir uma coluna em uma lista filtrada poderia demorar mais do que o esperado.

- Corrigido um problema em que alguns dos links de gráfico copiado e colado usavam endereços de unidade mapeados, em vez de endereços universais.

- Correção de um problema em que a mensagem de erro "Esta pasta de trabalho está referenciada por outra pasta e não pode ser fechada" poderia ser exibida porque os suplementos estavam sendo carregados em ordem alfabética, em vez de em um pedido especificado pelo usuário.

- Correção de um problema em que uma pasta de trabalho poderia ficar oculta ao clicar em um hiperlink em uma pasta de trabalho já aberta.

- Abrir uma pasta de trabalho com referências a várias outras pastas de trabalho, principalmente com janelas ocultas, era mais lento do que o esperado.

- Em alguns casos, o uso do Application.Evaluate do VBA não funcionava em funções definidas pelo usuário.

- Corrigido um problema que alguns usuários podem ter tido com objetos inseridos e vinculados (OLE).

- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.

- Esta atualização corrige um problema que fazia com que a barra de fórmulas exibisse texto em uma fonte diferente da esperada.

- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.

- Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.

- Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.

- O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.

- A funcionalidade Texto em Coluna pode falhar em algumas localizações.

- Solucionado um problema de desempenho durante a criação de gráficos de modelos.

- Corrigido um problema que fazia com que alguns usuários encontrassem falhas ao converter texto em colunas com células com uma matriz despejada.

- Usar um Range.Value e Range.Value2 (VBA) faria com que as fórmulas fossem inseridas como matrizes dinâmicas.

- Correção de um problema em que um símbolo @ iniciando uma fórmula seria considerado um operador de interseção implícito.

- Correção de um problema em que as planilhas com várias fórmulas com nomes definidos resultavam em demora ao salvar arquivos.

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

- Soluciona um problema que fazia com que os usuários encontrassem falhas ao renomear uma assinatura.

### <a name="onenote"></a>OneNote

- Melhoria da sincronia e estabilidade do serviço ajustando temporariamente a frequência de sincronia no OneNote 2016.

- Melhoria da estabilidade do serviço e da sincronia referindo-se temporariamente ao download de arquivos e imagens inseridas em blocos de anotações online até o usuário navegar para a página no OneNote 2016.

- Melhoria da sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016. Quando um usuário tenta excluir dados que normalmente seriam enviados para a lixeira, os usuários serão solicitados a optar por manter ou excluir permanentemente os dados.

- Melhoria da estabilidade do serviço e de sincronização, reduzindo temporariamente a frequência do número e da sincronia das páginas do histórico de versão no OneNote 2016.

- Exibe uma notificação que permite ao usuário saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade do serviço e de sincronia.

- Melhoria da sincronização e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB no OneNote 2016. Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.

- Melhoria da sincronização e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016. Os blocos de anotações locais não são afetados por essa medida.

- Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.

### <a name="outlook"></a>Outlook

- Consertamos um problema em que o IME (Editor de Método de Entrada) poderia se sobrepor ao texto subjacente sendo inserido por meio do IME ao usar vários monitores com resoluções diferentes.

- Corrige um problema que provocava falhas ocasionais no Outlook.

- Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.

- Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais.

- Soluciona um problema em que compromissos ou reuniões recorrentes eram exibidos na hora errada ao alterar a definição de fuso horário.

- Ao usar o fuso horário de Brasília no ano de 2019, reuniões e compromissos recorrentes são exibidos no timeslot incorreto para o ano 2020. Essa alteração é revelante para clientes no fuso horário de Brasília ou para reuniões e compromissos nesse fuso horário.<br><br>Essa alteração permite que o Outlook substitua determinadas configurações de fuso horário do Outlook. Para invocar uma substituição de fuso horário, você deve configurar uma chave do registro para o usuário atual. O nome da chave do registro deve corresponder ao nome interno do fuso horário. O valor indica o ano da regra de fuso horário a ser usado no lugar do ano vigente. Por exemplo, o valor de substituição da chave do registro a seguir usará a regra de fuso horário brasileiro para o ano de 2020 como regra efetiva. HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E. Hora Oficial do Brasil"=dword:000007e4.

- Corrigido um problema que fazia com que os usuários vissem o campo local nas reuniões mudar inesperadamente.

- Corrigimos um problema que fazia com que o campo Local nas reuniões fosse atualizado inesperadamente.

- Corrige um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após esvaziá-lo.

- Corrige um problema que fazia com que as vírgulas no campo local de uma reunião se transformassem em ponto e vírgula.

- Permite ingressar em uma reunião do Teams diretamente por meio do cliente nativo do Teams.

- Solucionado um problema que fazia com que os usuários com caixas de correio no Exchange 2010 Server tivessem problemas ao adicionar anexos a itens de calendário.

- Solucionado um problema que fazia com que os usuários tivessem problemas ao responder a mensagens assinadas digitalmente.

- Solucionado um problema que fazia com que os usuários não conseguissem abrir algumas instâncias de itens de calendário recorrentes.

- Solucionado um problema que fazia com que o Título do Grupo se expandisse inesperadamente em algumas situações.

- Corrige um problema que fazia com que a largura do painel de pastas fosse alterada inesperadamente.

- Soluciona um problema que causava falha no Outlook ao habilitar as dicas da política de Proteção Contra Perda de Dados para usuários que pagaram pelo serviço nos planos M365 Business Plus.

- Solucionado um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.

- Resolve um problema que pode resultar em uma falha ao exibir o mesmo item em várias janelas.

- Soluciona um problema que exibia a mensagem “A regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.

- Resolvido um problema que causou perda de memória em sessões muito longas do Outlook.

- Solucionado um problema que fazia com que os usuários encontrassem um falha ao especificar um Endereço do Remetendo inválido.

- Solucionado um problema que fazia com que usuários vissem um prompt “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo Regras.

- Corrige um problema que causava falha na opção para desabilitar o realce de item sinalizado, não sendo respeitado em alguns cenários.

- Corrigido um problema que fazia com que emails fossem enviados inesperadamente ao pressionar a tecla “S” após fechar o painel do verificador de acessibilidade.

- Soluciona um problema que fazia com que os usuários encontrassem falhas ao renomear uma assinatura.

- Soluciona um problema que fazia com que os usuários encontrassem uma falha ao cancelar a configuração da conta.

- Corrige um problema que fazia com que o Outlook sincronizasse inesperadamente todos os e-mails, mesmo quando o controle deslizante de sincronização estivesse definido como uma configuração menor.

- Resolve um problema que fazia com que os usuários com o Tema Preto vissem a lista suspensa “De” como um texto branco sobre um fundo branco.

- Soluciona um problema que fazia com que os usuários encontrassem uma falha durante a criação do perfil.

- Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.

- Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.

- Resolve um problema que fazia com que aplicativos de terceiros não pudessem enviar e-mails.

- Resolve um problema que fazia as categorias desaparecerem ocasionalmente das mensagens de email.

- Solucionamos um problema que fazia com que os usuários do Outlook nos sistemas operacionais de servidor vissem o erro "Status do antivírus: inválido". Esta versão do Windows oferece suporte à detecção de proteção antivírus, mas nenhum antivírus foi encontrado” mesmo após a configuração correta do antivírus.

- Resolve um problema que fazia com que representantes vissem diferentes hierarquias de pastas em caixas de correio compartilhadas em computadores diferentes.

- Aborda um problema que fazia com que os representantes recebessem uma mensagem de erro ao editar um compromisso existente no calendário de um gerenciador.

- Solucionamos um problema que fazia com que os usuários com a configuração de emulação do navegador incorreta não conseguissem concluir o prompt de autenticação do Gmail.

- Consertamos um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, caso a pasta compartilhada Download não fosse verificada.

- Soluciona um problema que fazia com que os usuários encontrassem uma falha ao tentar abrir arquivos .msg e .oft após uma atualização do Windows.

- Soluciona um problema que fazia com que os usuários encontrassem uma falha ao pressionar o botão X no mouse.

- Solucionado um problema que fazia com que os usuários encontrassem uma falha ao selecionar determinados resultados de pesquisa.

- Corrige um problema que fazia com que o botão Salvar na nuvem não aparecesse nas Ferramentas de Anexo.

- Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.

- Correção de um problema que causava uma falha quando dois suplementos adicionam um botão ao mesmo grupo da faixa de opções.

- Correção de um problema que fazia com que os links não fossem adicionados aos emails com a permissão de locatário padrão correta quando a permissão de locatário padrão está configurada como "qualquer pessoa".

- Solucionamos um problema que fazia com que os usuários não conseguissem endereçar os emails em uma lista de distribuição pessoal.

- Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.

- Corrige um problema com a seleção de algoritmo SMIME.

- Consertamos um problema que podia impedir que os arquivos fossem salvos em um local do WebDAV.

- Aborda um problema que fazia com que os usuários não conseguissem salvar anexos do OneDrive de fora de seu locatário em seu computador local ao selecionar a opção “Salvar” na caixa de diálogo de segurança.

- Correção de um problema que fazia com que o corpo de uma mensagem de Notificação de Falha na Entrega mudasse de Unicode para ASCII após editar o assunto.

- Corrigido um problema que fazia com que usuários observassem uma perda de memória no processo do Outlook.

- Solucionamos um problema que fazia com que os usuários vissem os emails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.

- Corrigido um problema que provocava um alinhamento inadequado da caixa de pesquisa no modo de DPI alto.

- Soluciona um problema que fazia com que os usuários encontrassem travamentos no Outlook ao recuperar as configurações da nuvem.

- Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.

- Corrige um problema que provocava falhas ocasionais no Outlook.

- Soluciona um problema que fazia com que os usuários encontrassem falhas ao renomear uma assinatura.

- Soluciona um problema que fazia com que os usuários encontrassem uma falha durante a criação do perfil.

- Corrige um problema que provocava falhas ocasionais no Outlook.

### <a name="powerpoint"></a>PowerPoint

- Soluciona um problema que pode ter causado uma falha ao usar o menu de contexto em comentários de PPT herdados.

- Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-la em outro slide em um loop.

- Corrige de um problema de retransmissão de mensagens corretas para os usuários que abrirem uma cópia de um arquivo que tenha comentários melhorados.

### <a name="project"></a>Project

- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.

- Correção de um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.

- Solucionamos um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.

- Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.

- Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura

- Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.

### <a name="word"></a>Word

- Soluciona um problema que fazia com que os usuários encontrassem uma falha ao pressionar o botão X no mouse.

- Resolvemos um problema em que o alinhamento de palavras no documento ficava embaralhado quando você tentava editar após imprimir usando a Impressão Rápida.

- Corrigimos um problema com o ajuste de texto em uma tabela.

- Corrigimos um problema em que não era possível inserir linhas horizontais e centralizar.

- O organizador de blocos de construção pode exibir um alerta inválido: “Você modificou estilos, blocos de construção”.

- Correção de um problema na coautoria se habilitarmos a política FileBlick\Word2007Files.

- Correção de um problema em que partes rápidas no Word não funcionava ao adicionar um campo de pesquisa que foi renomeado.

- Corrigimos um problema ao unir dois documentos em um único documento.

- Corrigimos um problema com o recurso comparar em documentos protegidos para edição.

- Esta atualização corrige um problema no Microsoft Word, em que textos com mais de 255 caracteres inseridos durante a aplicação de um rótulo de sensibilidade não poderiam ser subsequentemente identificados e removidos alterando ou removendo a etiqueta se a política de rótulo tiver aplicado um cabeçalho, rodapé ou marca-d ' água.

### <a name="office-suite"></a>Pacote Office

- Correção de um problema em que poderia ocorrer uso excessivo da rede e da CPU durante a coautoria em arquivos grandes do PowerPoint.

- Esta é uma correção para que o aplicativo do Project não bloqueie rede quando o arquivo estiver armazenado em cache no cliente.


- Resolvemos esse problema atualizando os nomes dos canais no backstage para os nomes dos novos canais na bifurcação de Janeiro de 2020.

- Corrigimos esse problema e no futuro, se um dispositivo for gerenciado por política, ele não chamará a API de audiência do DMS.

- Resolvido o problema em que há uma remoção incompleta ao adicionar e remover aplicativos em uma única transação.

- Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.

- Corrige um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Gerenciador de Configurações.

- Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.

- Fizemos um novo AppV51 para corrigir uma regressão no AppV51 anterior.

- Resolvemos o problema em que uma operação interna estava gerando uma exceção na falha, em vez de fazer o logon e continuar. Os usuários afetados não serão mais impedidos de receber as atualizações.

- A nossa equipe adicionou o suporte ao cliente para informar os domínios CDN do Office na Visualização Semestral Anual.

- Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.

- Essa alteração garante que a estrutura de tópicos Esboçada funcione corretamente na faixa de opções.

- Corrigimos um problema ao abrir arquivos de locais no ambiente local com algumas configurações específicas de proxy.

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

- Correção de um problema que elimina panes durante as sessões de entrega do Office e maior confiabilidade na experiência do usuário.

- Esse bug atualiza o ponto de extremidade da URL do serviço de configuração avançada (ECS). Chamar esse ponto de extremidade mais recente tem uma taxa de sucesso maior para buscar a partir de ECS.

- Esta atualização corrige um problema com o Microsoft Outlook, que não exibia o rótulo de confidencialidade atual ao exibir ou redigir mensagens.

- Corrige um problema quando vários documentos são abertos no Word/Excel/PowerPoint da mesma biblioteca do SharePoint, apenas o primeiro documento aberto será verificado quanto à conformidade com a Diretiva.

- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.

- O host do Office estava falhando no Windows quando um suplemento era ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era definida como zero. Essa alteração corrigiria esse problema.

- Resolvemos o problema em que o Access e o Publisher podiam não inicializar corretamente dependendo de quais idiomas foram instalados.



[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)





[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-july-14"></a>Versão 1908: 14 de julho
*Versão 1908 (Build 11929.20904)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Essa atualização corrige um problema em que agregados como Soma podem truncar o resultado para um valor inteiro.

- Essa atualização corrige um problema em que uma consulta da União que inclui referências a tabelas remotas (por exemplo, tabelas do SQL Server) pode fazer o Access fechar e reiniciar.

- Esta atualização corrige um problema no Microsoft Access que pode causar o erro “A consulta está corrompida” quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada no SQL.

### <a name="excel"></a>Excel

- A dica de tecla holandesa para o título do documento foi alterada para Alt-G.

- Correção de um problema no Excel em que as macros atribuídas a formas ou controles de formulário podem exibir mensagem de erro incorreta ou podem funcionar em intervalos de destino incorretos.

- Resolvemos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item.

- Isso corrige um problema em que é possível alterar a forma como uma Tabela Dinâmica é classificada e atualizá-la durante uma sessão de coautoria com outros usuários poderia causar uma falha.

- Corrigido um problema onde o filtro de uma Tabela Dinâmica OLAP era definido como um valor que havia sido removido do cubo.

- Esta atualização corrige um problema que causava um erro sempre que o VBA era usado para adicionar uma imagem ao cabeçalho/rodapé de um gráfico.

- Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série

- Correção relacionada às cores utilizadas nas visualizações ao inserir gráficos usando modelos de gráfico.

- Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.

- Correção de um problema de conflito de mesclagem no Excel, que resultaria na reabertura de uma pasta de trabalho para os usuários.

- Resolvido um problema que causava um erro no tempo de execução da macro ao ativar janelas minimizadas.

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

- Resolveu um problema que fazia com que as operações de recortar e colar próximas de uma tabela falhassem durante coautoria com outras pessoas.

- Resolvemos um problema que causou interrupções na coautoria ao alterar propriedades personalizadas com a execução de macros.

- Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.

- Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.

- Corrigido um problema em que a borda de um controle de Caixa de Grupo não ficava visível na visualização de impressão ou quando impressa.

- Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.

- Corrigimos um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.

- Corrigimos um problema com o VBA no qual a escrita de valores em um intervalo seria menor do que o esperado.

- Corrigido um problema em que a propriedade "O Valor Cruza Em" no eixo do gráfico se altera inesperadamente ao salvar e reabrir um arquivo.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- Foi corrigido um problema que levava à lentidão no desempenho ao excluir colunas contendo células mescladas.

- Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.

- Ao copiar dados filtrados por cor para uma coluna com uma largura diferente, os valores não seriam colados.

- Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.

- Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.

- Corrigido um problema em que clicar em um hiperlink marcado dentro da mesma pasta de trabalho fazia com que a pasta de trabalho fosse ocultada.

- Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".

- A funcionalidade Texto em Coluna pode falhar para algumas localidades.

- Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.

- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.

- Corrigido um problema em que o tamanho do arquivo de imagens nos cabeçalhos do gráfico aumentava quando a pasta de trabalho que continha o gráfico era salva.

- Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.

- Melhorias significativas no desempenho da exclusão de colunas com células mescladas.

- Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.

- Resolvido um problema em que a função Proc poderia retornar um erro.

- Corrigido um problema que causa corrupção de caracteres DBCS em livros de referência cruzada, mantendo os intervalos de seleção sincronizados com o catálogo de referência cruzada.

- Resolvido um problema que poderia causar a redução dos controles da caixa de seleção ao usar o AutoAjuste para ajustar a altura da linha.

- Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.

- Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta.

- O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.

- Melhoramos significativamente o desempenho da filtragem por cor.

- Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.

- Habilitamos mais de 16 suplementos para serem exibidos ao navegar no gerenciador de suplementos.

- Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Esta atualização corrige um erro em que os documentos do Office podem falhar ao carregar no OneDrive for Business com a mensagem "Falha no Carregamento".

- Corrigimos um problema no recurso Ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32. 

### <a name="onenote"></a>OneNote

- Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.

### <a name="outlook"></a>Outlook

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Correção de um problema em que os usuários que atualizavam a caixa de correio de uma autenticação básica para a moderna acabavam com a conta errada associada ao perfil do Outlook.

- Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais quando não deveriam.

- Resolvido um problema que provocou falha na exibição de URLs de foco simples em alguns safelinks.

- Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.

- Corrige um problema que fazia com que um subconjunto de usuários POP3 visualizasse todos os seus e-mails formatados em texto simples, independentemente das configurações. Essa correção restaurará o modo de exibição das mensagens formatadas como HTML.

- Resolvido um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.

- Resolvido um problema que fazia com que os usuários não conseguissem acessar sugestões de localização por meio de um leitor de tela.

- Solucionado um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.

- Resolvido um problema que causou perda de memória em sessões muito longas do Outlook.

- Solucionado um problema que fazia com que os usuários encontrassem um falha ao especificar um Endereço do Remetendo inválido.

- Solucionado um problema que fazia com que usuários vissem um prompt “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo Regras.

- Resolvido um problema que faria com que os usuários encontrassem uma falha no Outlook ao interagir com determinados safelinks.

- Corrige um problema que causava ambiguidade para os gerentes em que um representante já havia ou não respondido a uma determinada solicitação de reunião.

- Resolvido um problema que fazia com que os usuários encontrassem uma falha ao processar algumas respostas de Descoberta Automática.

- Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.

- Essa alteração permite que os administradores habilitem uma política para preferir o email da conta fornecida nos prompts de autenticação da Descoberta Automática no UPN. Por padrão, a Descoberta Automática prefere o UPN da conta, quando disponível.

- Soluciona um problema que fazia com que os usuários vissem falhas de pesquisa em Grupos Modernos.

- Resolvido um problema que fazia com que os usuários do Outlook não saíssem do estado "Senha Necessária" em determinadas situações.

- Solucionado um problema que fazia com que os usuários experimentassem falhas de sincronização ao processar mensagens de conflito.

- Solucionado um problema que fazia com que os usuários encontrassem uma falha ao abrir arquivos msg e .oft após aplicar uma atualização recente do Windows.

- Solucionado um problema que fazia com que os usuários encontrassem um travamento na tela Carregando perfil ao iniciar o Outlook.

- Solucionado um problema que fazia com que os usuários encontrassem uma falha ao selecionar determinados resultados de pesquisa.

- Corrige um problema que fazia com que o botão “Salvar na nuvem” não aparecesse nas Ferramentas de Anexo.

- Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses. Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido. HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = exibirá apenas o PolicyName no texto da Política de retenção.

- Solucionado um problema que fazia com que os usuários encontrassem uma falha ao desligar o Outlook.

- Solucionado um problema que fazia com que uma lista de salas vazia fosse exibida para os clientes em algumas situações.

- Solucionado um problema que fazia com que os usuários vissem falhas intermitentes ao alterar as visualizações.

- Solucionado um problema que fazia com que os usuários tivessem problemas com as pastas de calendário compartilhadas sincronizadas com o OST, resultando em erros de permissão quando tentavam interagir com essas pastas.

- Soluciona um problema que fazia com que os usuários encontrassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix. Aqui está o [KB individual em que isso foi documentado para versões anteriores](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)

- Corrigido um problema com a seleção de algoritmo SMIME.

- Corrige um problema que fazia com que as Dicas de política deixassem de ser exibidas ao usar um remetente alternativo.

- Resolvido um problema que fazia com que os usuários vissem sugestões de salas para reuniões que ocorriam fora do horário de disponibilidade dessa sala.

- Corrigido um problema para usuários não falantes de inglês, onde a linha de assunto em um email seria muito pequena.

- Resolvido um problema que fazia com que os usuários encontrassem uma falha ao tentar criar uma regra a partir de uma mensagem de “Conversa Perdida”.

- Corrigido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.

- Resolve um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.

- Corrigido um problema que fazia com que usuários observassem uma perda de memória no processo do Outlook.

- Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.

- Aborda um problema que causou falha intermitente na pesquisa da pasta atual.

- Corrigido um problema que fazia com que alguns usuários encontrassem erros de autenticação ao tentar recuperar as configurações de nuvem do Outlook.

- Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.

- Resolvido um problema que fazia com que os usuários encontrassem uma falha ao processar algumas respostas de Descoberta Automática.

- Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.

### <a name="powerpoint"></a>PowerPoint

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Essa alteração restaura o nome acessível para os controles de vídeo do PowerPoint.

- Corrigido um problema que poderia impedir a inicialização de algumas animações.

- Corrigido um problema que poderia criar mestres ao copiar um slide de uma apresentação para outra.<br>

- Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-la em outro slide em um loop.

- Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.

- Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada.

- Corrigido um problema que causava lentidão no desempenho entre os usuários da colaboração.

- Correção de confiabilidade: corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.

- Corrigido um problema que pode ocorrer quando um arquivo que está sendo aberto incrementalmente contém um slide com mais de um fluxo de mídia incorporado.

- Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.

- Corrigido um problema em que a barra de mensagens de aviso de segurança pode não aparecer para suplementos não confiáveis ​​no primeiro lançamento do PowerPoint.

- Correção de um problema em que alguns suplementos lançavam erros inesperados relacionados às formas nos gráficos.

- Impede que os usuários do PowerPoint se deparem com erro ao tentar Apresentar Online.

### <a name="project"></a>Project

- Correção de um problema para que os usuários do Windows 7 possam abrir projetos do Project Web App e sites do SharePoint.

- Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.

- O comando Nivelar Tudo não resolve adequadamente uma superalocação de recursos.

- Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.

- Corrigido de um problema em que o trabalho real pode ser diferente entre o quadro de horários e o plano do projeto, devido ao fato de os calendários de recursos não serem atualizados quando o calendário base é alterado.

### <a name="skype"></a>Skype

- Nome do título fixo da conversa com guias enquanto mais de uma conversa está em andamento.

### <a name="visio"></a>Visio

- A exportação como SVG do Visio falhou em várias formas.

### <a name="word"></a>Word

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Corrigido um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet

- Corrigido um problema no ajuste de texto de tabela.

- Corrigido um problema no controle de alterações que, às vezes, entravam em loop infinito.

- Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.

- Corrigimos um problema ao unir dois documentos em um único documento.

- Corrigimos um problema com o recurso comparar em documentos protegidos para edição.

- Correção de vários problemas em que o aplicativo pode travar no desligamento. E também corrige determinadas falhas relacionadas aos suplementos.

### <a name="office-suite"></a>Pacote Office

- Corrigido de um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.

- Corrigido um problema que fazia com que os usuários recebessem a mensagem "Algo está nos impedindo de compartilhar isso" ao tentar compartilhar arquivos armazenados no SharePoint 2016.

- Corrigido um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.

- Esta é uma correção para uma falha que os usuários podem encontrar ao abrir um arquivo.

- Em alguns casos, um arquivo do mecanismo de sincronização do SharePoint poderia exibir "Salvo", mas não ter salvado alterações, o que resulta em perda de dados.

- Resolvemos um problema em que os usuários poderiam não conseguir salvar documentos do Word, Excel e PowerPoint. Esse problema afeta os usuários que criam um novo arquivo e escolhem a opção "caixa de diálogo Salvar como" depois de clicar no ícone Salvar ou pressionar Ctrl + S.

- Corrigida uma falha no Word afastando-se de uma API preterida.

- Corrigido um problema em que os caracteres katakana de meia largura não giravam corretamente nas caixas de texto verticais no PowerPoint.

- Corrigido um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.

- Corrigido um bug em que as informações de acessibilidade não estavam sendo exibidas na laje Info Place dos bastidores.

- Melhora a confiabilidade do processo de atualização do Office referente à integridade do registro.

- Atualizamos os nomes dos canais das bifurcações de janeiro e julho de 2019 para os novos nomes de canal.

- Corrigido um problema em que as atualizações poderiam ser bloqueadas inesperadamente em redes limitadas.

- Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.

- Em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização. Essa atualização melhora a confiabilidade ao publicar os atalhos do Office.

- Corrige um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Gerenciador de Configurações.

- Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a conta do sistema não tinha conectividade de rede.

- Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado. Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.

- Maior confiabilidade ao baixar as atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.

- Correção de problemas relacionados à propriedade AutoAjuste da Caixa de Texto/Forma em plug-ins de terceiros.

- Essa alteração soluciona a renderização correta de imagens após a abertura de um arquivo corrompido.

- Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.

- Correção de um problema que grandes modos de exibição em árvore poderiam resultar em falha.

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.

- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-july-14"></a>Versão 1902: 14 de julho
*Versão 1902 (Build 11328.20624)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

## <a name="version-1908-june-09"></a>Versão 1908: 09 de junho
*Versão 1908 (Build 11929.20838)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Consertamos um problema em que o Excel poderia ficar sem resposta após usar Ctrl+Shift+Teclas de direção para rolar quando a janela do Excel era compartilhada por meio do Teams.

- Foi corrigido um problema com o dimensionamento de caixas de seleção nos controles de formulário quando impressos.

- Pode ocorrer uma falha ao tentar listar alterações em uma nova planilha para uma pasta de trabalho usando o modo de "Pasta de Trabalho Compartilhada".

### <a name="outlook"></a>Outlook

- Resolvemos um problema que fazia com que os usuários vissem truncamento do corpo da mensagem ao encaminhar mensagens HTML grandes.

### <a name="office-suite"></a>Pacote Office

- Atualizamos os nomes dos canais para as bifurcações de janeiro e julho de 2019 para os novos nomes de canal.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-june-09"></a>Versão 1902: 09 de junho
*Versão 1902 (Build 11328.20602)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Atualizamos os nomes dos canais para as bifurcações de janeiro e julho de 2019 para os novos nomes de canal.

- Removemos referências obsoletas dos arquivos de linha de base que estavam dividindo a compilação C2R.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-may-12"></a>Versão 1908: 12 de maio
*Versão 1908 (Build 11929.20776)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Ao copiar dados filtrados por cor para uma coluna com uma largura diferente, os valores não seriam colados.

### <a name="outlook"></a>Outlook

- Resolvido um problema que fazia com que os usuários travassem ao abrir arquivos msg e oft após a aplicação de uma atualização recente do Windows.

### <a name="word"></a>Word

- Corrigimos um problema ao unir dois documentos em um único documento.

- Corrigimos um problema com o recurso comparar em documentos protegidos para edição.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-may-12"></a>Versão 1902: 12 de maio
*Versão 1902 (Build 11328.20586)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao abrir arquivos. msg e. oft após aplicar uma atualização recente do Windows.

- Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses. Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido. HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration. 0 = Padrão.  1 = mostraremos apenas a política de texto de política de retenção.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-may-04"></a>Versão 1908: 04 de maio
*Versão 1908 (Criação 11929.20752)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Foi solucionado um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.

- Foi solucionado um problema que fazia com que o botão "Salvar na nuvem" não estivesse presente nas Ferramentas de Anexo.

- Por padrão, os rótulos da política de retenção podem exibir o período de retenção entre parênteses. Isso fornece uma chave do registro para permitir que os administradores especifiquem que apenas o nome da política deve ser exibido. HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration. 0 = Padrão 1 = mostraremos apenas o PolicyName para o texto da política de Retenção.

### <a name="office-suite"></a>Pacote Office

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

## <a name="version-1902-may-04"></a>Versão 1902: 04 de maio
*Versão 1902 (Build 11328.20572)*

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

## <a name="version-1908-april-26"></a>Versão 1908: 26 de abril
*Versão 1908 (Build 11929.20736)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um problema de desempenho que os usuários podem ter ao usar uma VBA macro para limpar o conteúdo de um intervalo.

- Corrigimos um problema com o VBA no qual a escrita de valores em um intervalo seria menor do que o esperado.

- Corrigimos um problema em que a propriedade "O Valor Cruza Em" se altera inesperadamente ao salvar e reabrir um arquivo.

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.


### <a name="onenote"></a>OneNote

- Localiza a notificação de que o usuário pode saber mais sobre as medidas temporárias que estão sendo aplicadas na experiência de usuário do OneNote para melhorar a estabilidade e o serviço.


## <a name="version-1908-april-14"></a>Versão 1908: 14 de abril
*Versão 1908 (Build 11929.20708)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Foi corrigido um problema que levava à lentidão no desempenho ao excluir colunas contendo células mescladas.

- Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.

### <a name="skype"></a>Skype

- Nome do título fixo da conversa com guias enquanto mais de uma conversa está em andamento.

### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao desligar o Outlook.

- Solucionamos um problema que fazia com que uma lista de salas vazia fosse exibida para os clientes em alguns cenários.

### <a name="powerpoint"></a>PowerPoint

- Corrigido um problema com o marcador: textos em branco com cores escuras do marcador são impressos em preto na escala de cinza.

### <a name="word"></a>Word

- Foi corrigido um problema no ajuste de texto de tabela.


## <a name="version-1902-april-14"></a>Versão 1902: 14 de abril
*Versão 1902 (Build 11328.20564)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-march-10"></a>Versão 1908: 10 de março
*Versão 1908 (Build 11929.20648)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.


- A funcionalidade Texto em Coluna pode falhar para algumas localidades.


- Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.


### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.


### <a name="word"></a>Word

- Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.


### <a name="office-suite"></a>Pacote Office

- Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.

## <a name="version-1902-march-10"></a>Versão 1902: 10 de março
*Versão 1902 (Build 11328.20554)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a>Versão 1908: 11 de fevereiro
*Versão 1908 (Build 11929.20606)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


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


- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao exibir mais de 30 calendários em um ambiente Citrix. [Aqui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) está o KB individual em que isso foi documentado para versões anteriores.

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

## <a name="version-1902-february-11"></a>Versão 1902: 11 de fevereiro
*Versão 1902 (Build 11328.20526)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Solucionado um problema que fazia com que os usuários encontrassem erros no algoritmo de criptografia ao enviar um email criptografado.


### <a name="word"></a>Word

- Corrigida uma falha no Word afastando-se de uma API reprovada.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

## <a name="version-1808-february-11"></a>Versão 1808: 11 de fevereiro
*Versão 1808 (Build 10730.20438)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1908-january-14"></a>Versão 1908:14 de janeiro
*Versão 1908 (Build 11929,20562)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Manter as guias dos objetos de banco de dados:** Veja as guias ativas, arraste as guias facilmente para reorganizá-las, e feche os objetos de banco de dados com apenas um clique.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Aplicar zoom com mais espaço:** aumente a caixa Zoom, altere a fonte e o Zoom lembrará de tudo. [Saiba mais](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a>Excel

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Dê vida às suas planilhas:** insira gráficos animados em 3D para ver corações pulsando, planetas orbitando e a fúria do T-Rex na pasta de trabalho. [Saiba mais](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **Saiba mais sobre seus dados:** O novo botão Ideias procura padrões em seus dados e os usa para criar sugestões inteligentes e personalizadas. [Saiba mais](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **A colaboração ficou mais fácil** : Os aperfeiçoamentos de coautoria significam que, ao trabalhar com acesso condicional, estilos de célula e muito mais, suas alterações são mescladas perfeitamente com as de seus colaboradores.

- **Una tabelas em colunas similares:** Obter e Transformar (Power Query) agora apresenta lógica de texto correspondente aproximado (também chamada de correspondência difusa) ao comparar colunas para mesclar tabelas. [Saiba mais](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Codifique rapidamente com as melhorias do Power Query:** chegue rapidamente à conclusão de código com as cores de sintaxe e o preenchimento automático. Também descubra facilmente funções, colunas e parâmetros.

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba Mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **Atualizamos a experiência de usuário do Outlook para você:** uma experiência simplificada, previamente disponível para visualização com Em Breve, projetada para ajudar você a se concentrar no que é mais importante. [Saiba mais](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Uma faixa de opções simplificada também personalizável:** desfrute de uma única linha simplificada com os botões usados com mais frequência. Alterne facilmente entre visualizações clássicas e simplificadas e comandos para fixar/desafixar. [Saiba mais](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Continue trabalhando enquanto move mensagens:** Agora, o Outlook move mensagens em segundo plano para que você pode continuar trabalhando enquanto move uma grande quantidade de mensagens entre pastas.

- **Crie intervalos entre reuniões consecutivas:** dê um tempo para os participantes descansarem ou se deslocarem entre os locais definindo o término antecipado das reuniões para entre cinco a dez minutos por padrão.

- **Escolha a sua ação favorita:** não use Sinalizar e Excluir? E quanto a Arquivar ou Marcar como Lida? Personalize o menu de ação rápida com os comandos que você mais usa.

- **As pessoas verão o Meme que você usou:** se o texto ou as imagens estáticas não forem suficientes, use GIFs animados para convencer. [Saiba mais](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b).

- **Uma maneira mais rápida de adicionar contas:** graças às melhorias de configuração de conta, ficou mais fácil adicionar contas do Outlook.com e do Gmail que usam a autenticação de dois fatores no Outlook. [Saiba mais](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Diga adeus aos limites de sincronização:** melhorias do Outlook acabou com o limite de pastas, então vá em frente e sincronize suas caixas de correio compartilhadas.

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba Mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Melhoria na mudança de formas:** nomeie suas formas para ter mais controle sobre como elas são transformadas. [Saiba mais](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Aumente o alcance do seu conteúdo:** precisa tornar suas apresentações acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Os vídeos online têm um novo lar:** salve um vídeo no Microsoft Stream para que qualquer pessoa em sua organização possa vê-lo. Insira o link de vídeo e desfrute de uma apresentação multimídia com uma fração do tamanho do arquivo. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Saiba a opinião de seu público através de um questionário ou pesquisa:** coloque um questionário ou uma pesquisa em um slide. O Office coleta e armazena as respostas para você. [Saiba mais](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Inserir um vídeo online está mais fácil do que nunca:** Deseja colocar um vídeo do Vimeo ou YouTube no slide? O link da página de vídeo é tudo o que você precisa. [Saiba mais](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Exporte diagramas de processo para o Word:** Adicione automaticamente conteúdo de diagrama, como formas e metadados, a um documento do Word. Personalize o documento para criar as diretrizes de processo e os manuais de operação. [Saiba mais](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Captura dupla em fluxogramas de dados:** os novos e deslumbrantes layouts para os fluxogramas do Visualizador de Dados são limpos, nítidos e fáceis de entender. Clique na guia Design para ver as opções.

- **Estênceis criados diretamente no Azure:** crie um aplicativo de nuvem ou planeje uma arquitetura usando dezenas de estênceis do Azure. [Saiba mais](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Diga adeus aos links desfeitos do Excel:** não consegue encontrar a pasta de trabalho do Excel vinculada ao seu diagrama do Visualizador de Dados? Vincule-o novamente para que tudo volte ao normal. [Saiba mais](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exporte elementos visuais do Visio a partir do Power BI:** os elementos visuais do Visio para o Power BI agora estão sendo exibidos corretamente ao exportar relatórios do Power BI como PDFs, arquivos do PowerPoint e muito mais. [Saiba mais](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **O modo Ferramentas de Aprendizagem tem suporte adicional para mais cores de página:** as Ferramentas de Aprendizagem no Word adicionam suporte para mais cores de tema de página, o que permite a alteração da cor da tela de fundo da página. Várias pessoas têm desafios de leitura com um plano de fundo todo branco ou preto, então ampliamos as opções de cores no Word para PC e para Mac.

- **A edição ocorre naturalmente com o Editor por Tinta:** com um único traçado, divida ou una palavras, adicione uma nova linha ou insira palavras usando uma caneta. [Saiba mais](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Transforme seu documento de estático para incrível:** transforme seu documento em uma página da web interativa e fácil de compartilhar, com uma aparência ótima em qualquer dispositivo. [Saiba mais](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Aumente o alcance do seu conteúdo:** precisa tornar seus documentos acessíveis? Deixe o verificador de acessibilidade fazer isso por você, sem atrapalhar seu trabalho. Experimente clicando em Revisão > Verificar Acessibilidade. Informaremos quando encontrarmos algo que você precise ver na barra de status.

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Página inicial para localizar o arquivo procurado.

- **Alterne facilmente:** o novo gerente de contas exibe todas as suas contas pessoais e profissionais do Office 365 em um só lugar. Nunca foi tão fácil alternar entre elas. [Saiba mais](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Melhore a compreensão com Line Focus:** percorra a linha de um documento sem distrações. Ajuste o foco para colocar uma, três ou cinco linhas na visualização de cada vez. [Saiba mais](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Salve suas alterações assim que forem realizadas:** Carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Chame a atenção com \@@Menções:** Use @menções nos comentários para informar a seus colegas de trabalho quando precisar deles. [Saiba mais](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Pesquisar e desfrutar:** adicionamos a Pesquisa para Inserir Ícones para facilitar a localização do ícone desejado. Enquanto você está selecionando, o botão Inserir informa quantos você escolheu. [Saiba Mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Pacote Office

- **Localize um arquivo rapidamente:** Procurando um arquivo no qual você trabalhou recentemente? Basta digitar na caixa Pesquisar na guia Arquivo > Abrir para encontrar o arquivo que você está procurando.

- **Salve suas alterações assim que forem realizadas:** carregue seus arquivos no OneDrive para garantir que todas as atualizações sejam salvas automaticamente.

- **Controles de privacidade:** controles novos, atualizados e melhorados para dados de diagnóstico e experiências conectadas. [Saiba mais](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Os produtos do Ofiice estão com um novo visual** Os ícones de produtos foram recriados para refletir as experiências simples, poderosas e inteligentes do Office.

- **Instalação do Microsoft Teams:** o Microsoft Teams vem instalado por padrão nas instalações existentes do Office 365 ProPlus. [Saiba mais](/DeployOffice/teams-install)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Essa atualização corrige um problema em que agregados como Soma podem truncar o resultado para um valor inteiro.

- Essa atualização corrige um problema em que uma consulta da União que inclui referências a tabelas remotas (por exemplo, tabelas do SQL Server) pode fazer o Access fechar e reiniciar.

- Esta atualização corrige um problema no Microsoft Access que pode causar o erro &quot;A consulta está corrompida&quot; quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada em SQL.

### <a name="excel"></a>Excel

- A dica de tecla holandesa para o título do documento foi alterada para Alt-G.

- Correção de um problema no Excel em que as macros atribuídas a formas ou controles de formulário podem exibir mensagem de erro incorreta ou podem funcionar em intervalos de destino incorretos.

- Resolvemos um problema em Localizar e Substituir que alterou o local em que o foco estava na caixa de diálogo após encontrar o primeiro item.

- Isso corrige um problema em que é possível alterar a forma como uma Tabela Dinâmica é classificada e atualizá-la durante uma sessão de coautoria com outros usuários poderia causar uma falha.

- Corrigido um problema onde o filtro de uma Tabela Dinâmica OLAP era definido como um valor que havia sido removido do cubo.

- Correção relacionada às cores usadas nas visualizações ao inserir gráficos usando modelos de gráfico.

- Corrigimos um problema que poderia ter causado a renderização incorreta de gráficos de linhas de dispersão na alteração da coleção de série.

- Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.

- Correção de um problema de conflito de mesclagem no Excel, que resultaria na reabertura de uma pasta de trabalho para os usuários.

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

- Resolvido um problema que causava um erro no tempo de execução da macro ao ativar janelas minimizadas.

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

- Resolveu um problema que fazia com que as operações de recortar e colar próximas de uma tabela falhassem durante coautoria com outras pessoas.

- Resolvemos um problema que causou interrupções na coautoria ao alterar propriedades personalizadas com a execução de macros.

- Ocorreu um problema no qual você não conseguiria selecionar itens da caixa de combinação de um formulário WPF (Windows Presentation Foundation) que foi aberto por um suplemento.

- Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.

- Problema de desempenho com funções Assíncronas Definidas pelo Usuário que causavam a execução Síncrona.

- Melhorias significativas no desempenho da exclusão de colunas com células mescladas.

- Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.

- Resolvido um problema em que a função Proc poderia retornar um erro.

- Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.

- Problema com desempenho lento ao clicar no botão Cor da Fonte quando um arquivo tem uma formatação condicional extensa.

- Corrigimos um problema em que a área de impressão na visualização de impressão não estava correta.

- O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.

- Melhoramos significativamente o desempenho da filtragem por cor.

- Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.

- Habilitamos mais de 16 suplementos para serem exibidos ao navegar no gerenciador de suplementos.

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Esta atualização corrige um erro em que os documentos do Office podem falhar ao carregar no OneDrive for Business com a mensagem "Falha no Carregamento".

- Corrigimos um problema no recurso Ideias do Excel, um erro ao carregar o suplemento clicando no botão ideias no cliente Win32.

### <a name="outlook"></a>Outlook

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Correção de um problema em que os usuários que atualizavam a caixa de correio de uma autenticação básica para a moderna acabavam com a conta errada associada ao perfil do Outlook.

- Resolvido um problema que fazia com que os suplementos da Web acessassem mensagens Gerenciadas por Direitos Digitais quando não deveriam.

- Resolvido um problema que provocou falha na exibição de URLs de foco simples para alguns safelinks.

- Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.

- Resolvido um problema que fazia com que um subconjunto de usuários POP3 visualizasse todos os seus e-mails formatados em texto sem formatação, independentemente das configurações. Essa correção restaurará o modo de exibição das mensagens formatadas como HTML.

- Resolvido um problema que causava um erro de permissão ao copiar itens do calendário principal para um calendário de grupo.

- Resolvido um problema que fazia com que os usuários não conseguissem acessar sugestões de localização por meio de um leitor de tela.

- Resolvido um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.

- Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.

- Resolvido um problema que fazia com que usuários vissem um aviso “As regras neste computador não correspondem às regras no Microsoft Exchange” ao abrir a caixa de diálogo de Regras.

- Resolvido um problema que faria com que os usuários experimentassem uma falha no Outlook ao interagir com determinados safelinks.

- Resolvido um problema que causava ambiguidade para os gerentes sobre se um representante já havia ou não respondido a uma determinada solicitação de reunião.

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.

- Resolvido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão “OK” ao tentar contatar o suporte do contexto de Criação de Conta.

- Essa alteração permite que os administradores habilitem uma política para preferir o email da conta fornecida nos prompts de autenticação da Descoberta Automática no UPN. Por padrão, a Descoberta Automática prefere o UPN da conta, quando disponível.

- Solucionamos um problema que fazia com que os usuários ver falhas de pesquisa em Grupos Modernos.

- Resolvido um problema que fazia com que os usuários do Outlook travassem no estado "Senha Necessária" em determinados cenários.

- Resolvido um problema que fazia com que os usuários vissem sugestões de salas para reuniões que ocorriam fora do horário de disponibilidade dessa sala.

- Corrigido um problema que fazia com que os usuários encontrassem erros de "Não há suporte para algoritmo de criptografia" ao enviar um email criptografado.

- Corrigido um problema para usuários não falantes de inglês, onde a linha de assunto em um e-mail seria incrivelmente pequena.

- Resolvido um problema que fazia com que alguns usuários vissem pastas especiais duplicadas criadas ao adicionar uma conta secundária do Exchange.

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ao tentar criar uma regra a partir de uma mensagem de “Conversa Perdida”.

- Corrigido um problema com a seleção de algoritmo SMIME.

- Corrigido um problema que fazia com que as Dicas de Política deixassem de ser exibidas ao usar um remetente alternativo.

- Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.

- Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.

- Corrigido um problema que fazia com que a pesquisa de pasta atual falhasse intermitentemente.

- Corrigido um problema que fazia com que alguns usuários encontrassem erros de autenticação ao tentar recuperar as configurações de nuvem do Outlook.

- Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ao processar algumas respostas de Descoberta Automática.

- Corrigido um problema que fazia com que os usuários experimentassem falhas intermitentes ao atualizar as informações de presença.

### <a name="powerpoint"></a>PowerPoint

- Correção de um problema em que alguns suplementos lançavam erros inesperados relacionados às formas nos gráficos.

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Essa alteração restaura o nome acessível para os controles de vídeo do PowerPoint.

- Corrigimos um problema que poderia impedir a inicialização de algumas animações.

- Corrigimos um problema ao copiar um slide de uma apresentação para outra, criando mestres duplicados.

- Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada

- Correção de confiabilidade: Corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.

- Corrigido um problema em que os caracteres katakana de meia largura não giravam corretamente nas caixas de texto verticais no PowerPoint.

### <a name="project"></a>Project

- Correção de um problema para que os usuários do Windows 7 possam abrir projetos do Project Web App e sites do SharePoint.

- Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.

- O comando Nivelar Tudo não resolve adequadamente uma superalocação de recursos.

- Uma atribuição com zero trabalho em uma tarefa, a tarefa pode não ser marcada como concluída e sempre aparecerá em 99%.

### <a name="visio"></a>Visio

- A exportação como SVG do Visio falhou em várias formas.

### <a name="word"></a>Word

- Essa alteração levará a melhorias de desempenho na abertura de documentos usando o Word.

- Os links de cid: imagens de mensagens do Outlook podem ser interrompidas com sucesso quando solicitado.

- Corrigimos um problema que poderia ter causado problemas de dimensionamento ao imprimir em impressoras DeskJet.

- Corrigimos um problema no controle de alterações que, às vezes, entravam em loop infinito.

- Corrigidos vários problemas em que o aplicativo pode travar no desligamento. E também corrige determinadas falhas relacionadas aos suplementos.

### <a name="office-suite"></a>Pacote Office

- Corrigido de um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.

- Corrigido um problema que fazia com que os usuários recebessem a mensagem "Algo está nos impedindo de compartilhar isso" ao tentar compartilhar arquivos armazenados no SharePoint 2016.

- Corrigido um problema que poderia causar perda de dados em sessões que envolviam coautoria e edição offline no PowerPoint.

- Esta é uma correção para uma falha que os usuários podem encontrar ao abrir um arquivo.

- Impede que os usuários do PowerPoint se deparem com erro ao tentar Apresentar Online.

- Em alguns casos, um arquivo do mecanismo de sincronização do SharePoint poderia exibir "Salvo", mas não ter salvado alterações, o que resulta em perda de dados.

- Resolvemos um problema em que os usuários poderiam não conseguir salvar documentos do Word, Excel e PowerPoint. Esse problema afeta os usuários que criam um novo arquivo e escolhem a opção "caixa de diálogo Salvar como" depois de clicar no ícone Salvar ou pressionar Ctrl + S.

- Corrigido um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.

- Corrigido um bug em que as informações de acessibilidade não estavam sendo exibidas na laje Info Place dos bastidores.

- Melhora a confiabilidade do processo de atualização do Office referente à integridade do registro.

- Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.

- Corrigido um problema em que as mensagens de atualização do Office eram exibidas em um idioma diferente do esperado. Em seguida, as mensagens de atualização do Office correspondem corretamente ao idioma de exibição do Windows.

- Resolvido um problema em que uma atualização não se aplicava em certos casos em que o usuário não era administrador e a Conta do sistema não tinha conectividade de rede.

- Em determinadas circunstâncias, os atalhos do Office poderiam desaparecer após uma atualização. Essa atualização melhora a confiabilidade ao publicar os atalhos do Office.

- Corrigimos um problema em que as atualizações poderiam ser bloqueadas inesperadamente em redes limitadas.

- Corrigimos um prolema na ODT e na configuração da Data Limite da Atualização do GPO, onde a data limite relativa só funciona na primeira vez que é definida, a correção habilita a data limite relativa para as atualizações subsequentes.

- Maior confiabilidade ao baixar as atualizações do Office retomando downloads que podem ter sido interrompidos anteriormente.

- Corrigido problemas relacionados à propriedade AutoAjuste da Caixa de texto/ Forma em plug-ins de terceiros.

- Corrigimos um problema em que grandes modos de exibição em árvore poderiam resultar em falha.

- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-january-14"></a>Versão 1902: 14 de janeiro
*Versão 1902 (Build 11328.20512)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

### <a name="outlook"></a>Outlook

- Corrigido um problema que fazia com que os usuários encontrassem erros de "algoritmo de criptografia não é suportado" ao enviar um email criptografado.

### <a name="powerpoint"></a>PowerPoint

- Os arquivos com novos comentários modernos exibirão um aviso amarelo se abertos em uma versão não suportada.

### <a name="word"></a>Word

- Essa alteração levará a melhorias de desempenho na abertura de documentos usando o Word.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-january-14"></a>Versão 1808: 14 de janeiro
*Versão 1808 (Build 10730.20432)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-december-10"></a>Versão 1902 (10 de dezembro)
*Versão 1902 (Build 11328.20492)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

### <a name="outlook"></a>Outlook

- Os itens de calendário do próximo ano podem exibir um horário incorreto no Outlook. [Saiba Mais](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ao tentar criar uma regra a partir de uma mensagem de &quot;conversa perdida&quot;.

### <a name="powerpoint"></a>PowerPoint

- Corrigido um problema relacionado à impressão na página de anotações que tinha problemas de layout em alguns casos.

## <a name="version-1808-december-10"></a>Versão 1808: 10 de dezembro
*Versão 1808 (Build 10730.20426)*

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Os itens de calendário do próximo ano podem exibir um horário incorreto no Outlook. [Saiba Mais](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-november-22"></a>Versão 1902: 22 de novembro 
*Versão 1902 (Build 11328.20480)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Corrigido um problema em que ao executar uma consulta de Atualização uma mensagem de erro era dada incorretamente: "A consulta está corrompida".

### <a name="outlook"></a>Outlook

- Resolvido um problema que fazia com que os usuários observassem vazamentos de memória quando as notificações de sistema estavam ativadas.

### <a name="office-suite"></a>Pacote Office

- Com essa alteração, a sincronização não será limitada a erros de sincronização que não estão relacionados à limitação.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-november-22"></a>Versão 1808: 22 de novembro
*Versão 1808 (Build 10730.20422)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="access"></a>Access

- Corrigido um problema em que ao executar uma consulta de Atualização uma mensagem de erro era dada incorretamente: "A consulta está corrompida".

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-november-12"></a>Versão 1902: 12 de novembro
*Versão 1902 (Build 11328.20468)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel

- Resolvido um problema que estava causando atrasos na exibição de valores digitados após a exclusão de um intervalo.
- Resolvido um problema em que as pastas de trabalho criadas em versões anteriores do Office poderiam fazer com que o Excel travasse quando aberto nas versões atuais do Office.

### <a name="outlook"></a>Outlook

- Resolvido um problema que fazia com que os usuários observassem vazamentos de memória quando as notificações de sistema estavam ativadas.
- Resolvido um problema que fazia com que os clientes percebessem um vazamento de memória no Outlook.

### <a name="powerpoint"></a>PowerPoint

- Correção de confiabilidade: Corrigido um problema em que o suplemento de terceiros poderia causar falha no PowerPoint.

### <a name="word"></a>Word

- Corrigimos um problema com a fonte alterada para MS Mincho ao tentar finalizar alguns caracteres especiais.

### <a name="office-suite"></a>Pacote Office

- Corrigido um problema de desempenho no Win7, em que a galeria de formas de inserção da faixa de opções de todos os aplicativos demorava aproximadamente 4 segundos para aparecer.
- Corrigido um problema em que os atalhos do Menu Iniciar e as extensões de arquivo do Office desapareciam inesperadamente após uma atualização.
- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-november-12"></a>Versão 1808: 12 de novembro
*Versão 1808 (Build 10730.20416)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="outlook"></a>Outlook

- Corrige um problema que faz com que os usuários com um "email para manter a configuração offline" de algo além de "Tudo" vejam a perda de dados ao mover itens para fora da janela de sincronização de um armazenamento local para a caixa de correio do Exchange Online.

### <a name="office-suite"></a>Pacote Office

- Para proteger a segurança dos clientes do Office, as atualizações do Microsoft Office agora são assinadas usando o algoritmo SHA-2 exclusivamente.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1902-october-08"></a>Versão 1902: 08 de outubro
*Versão 1902 (Build 11328.20438)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="excel"></a>Excel

- Resolvemos um problema que impedia que os hiperlinks fossem colados em algumas planilhas protegidas.

### <a name="project"></a>Project

- Foi corrigido um problema em que o PDF do arquivo XPS não era criado no seguinte cenário:<ul><li>Você abre um projeto.</li><li>Você clica no menu Arquivo, clica em Exportar e, em seguida, clica no botão <b>Criar PDF/XPS</b>.</li><li>Na caixa de diálogo Procurar, digite um nome de arquivo e clique em OK.</li></ul>

### <a name="word"></a>Word

- Foi corrigido um problema em que as versões atuais do JAWS no Windows não anunciam palavras ao usar a seta Caps + Seta para a direita.

### <a name="office-suite"></a>Pacote do Office

- Agora, os usuários poderão salvar os arquivos do Office sincronizados pelo cliente de sincronização do OneDrive com as propriedades necessárias ausentes. As propriedades do documento continuarão disponíveis para exibição e edição nos bastidores do documento, acessando Arquivo > Informações. Essa alteração levará a melhorias de desempenho.

- Foi corrigido um problema em que a notificação &quot;Corrigir minha conta&quot; não desaparecia após o logon com êxito.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-october-08"></a>Versão 1808: 08 de outubro

*Versão 1808 (Build 10730.20386)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

## <a name="version-1902-september-10"></a>Versão 1902: 10 de setembro
*Versão 1902 (Build 11328.20420)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="access"></a>Access

- Correção de um problema que fazia com que determinadas consultas no Microsoft Access fossem executadas mais devagar do que em versões anteriores.

### <a name="outlook"></a>Outlook

- Correção de um problema temporário no serviço que exibia o erro "não foi possível encontrar este arquivo. Verifique se o caminho e o nome do arquivo estão corretos" ao usar anexos na nuvem. [Saiba mais](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Correção de um problema que fazia com que os usuários vissem arquivos carregados do Outlook para o OneDrive ou o SharePoint com o nome do arquivo alterado onde vários caracteres foram substituídos por sublinhados.

### <a name="word"></a>Word

- Correção de um problema em que os usuários recebiam mensagens de erro durante a colaboração com outras pessoas em um documento do Word.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1808-september-10"></a>Versão 1808: 10 de setembro
*Versão 1808 (Build 10730.20380)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="non-security-updates"></a>Atualizações não relacionadas à segurança
### <a name="access"></a>Access

- Correção de um problema que fazia com que determinadas consultas no Microsoft Access fossem executadas mais devagar do que em versões anteriores.

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

## <a name="version-1808-august-13"></a>Versão 1808 13 de agosto
*Versão 1808 (Build 10730.20370)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
- Correção de um problema em que a configuração da API não funciona na biblioteca JavaScript do Office em determinados cenários [Saiba mais](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)


## <a name="version-1803-august-13"></a>Versão 1803 13 de agosto
*Versão 1803 (Build 9126.2432)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
- Correção de um problema em que a configuração da API não funciona na biblioteca JavaScript do Office em determinados cenários [Saiba mais](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)


## <a name="version-1902-july-09"></a>Versão 1902: 09 de julho
*Versão 1902 (Build 11328.20368)*
<br/>Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


### <a name="access-feature-updates"></a>Access: atualizações de recursos

- **Atualizar, vincular novamente ou remover tabelas vinculadas:** o Gerenciador de tabelas vinculadas atualizado é o local para gerenciar todas as fontes de dados e tabelas vinculadas. [Saiba mais](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Pinte de preto, pinte de cinza:** Altere a aparência do Access quantas vezes quiser. Quatro temas para escolher: colorido, cinza escuro, preto ou branco. [Saiba mais](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos

- **Comece mais rápido** A Página de Início recém-projetada coloca seus documentos abertos recentemente em destaque. Acesse os arquivos com menos cliques e abra as Configurações da conta ou Opções daqui mesmo.
- **Colaborar com os comentários:** Mantenha a conversa em andamento na sua planilha com a caixa de resposta integrada. [Saiba mais](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Seus ícones da faixa de opções têm uma aparência nova:** Não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Ver o que está atrás de uma imagem:** coloque uma imagem em uma planilha, selecione o valor predefinido e observe a alteração de transparência. É isso![Saiba mais](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Chamar todos os fãs do Obter e Transformar:** se você usa muito o Obter e Transformar, ficará feliz em saber que o recurso da Coluna de exemplo foi aprimorado. E muitos conectores foram melhorados também. [Saiba mais](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Pesquisa rápida** Nós carregamos seus cálculos VLOOKUP, HLOOKUP e MATCH para que você possa obter respostas mais rápidas. [Saiba mais](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: atualizações de recursos

- **Usar Ler em Voz Alta para ouvir seu email** O Outlook pode ler seu email em voz alta, realçando o texto conforme lê. para ativar Ler em Voz Alta, vá para as configurações de facilidade de acesso [Saiba mais](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Digitar com as mãos livres:** tem um microfone? Clique em Ditar e veja o Outlook digitar enquanto você fala.  [Saiba mais](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Seus ícones da faixa de opções têm uma aparência nova:** Não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
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
- **Seus ícones da faixa de opções têm uma aparência nova:** Não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
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
- **Seus ícones da faixa de opções têm uma aparência nova:** Não se preocupe, tudo funciona da mesma maneira. Além disso, elas ficam ótimas em telas de todos os tamanhos. [Saiba mais](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Ver o que está atrás de uma imagem:** coloque uma imagem em uma planilha, selecione o valor predefinido e observe a alteração de transparência. É isso![Saiba mais](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Capacidade de inserir SVG com filtros aplicados:** Usuários do Office agora têm a capacidade de inserir SVG que têm filtros aplicados a eles. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Faça o seu melhor currículo ou CV com a ajuda do LinkedIn:** Com o Assistente de Currículos, é possível ver experiências profissionais, qualificações sugeridas e muito mais para uma determinada função. [Saiba mais](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: atualizações de recursos

- **Veja mais informações nos cartões do Quadro de Tarefas:** Quando apenas o título não conta a história, personalize seus cartões do Quadro de Tarefas para mostrar a todos os detalhes mais importantes. [Saiba mais](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="publisher-feature-updates"></a>Publisher: atualizações de recursos

- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos

- **Aproveitar um momento icônico em seu próximo diagrama:** escolha entre 26 estênceis novos com ícones de análise, artes, comemoração, rostos, esportes e muito mais.
- **O Office tem um visual novo:**  os aplicativos do Office agora têm ícones modernos mais simples e mais acessíveis, e a faixa de opções traz recursos visuais atualizados que destacam os recursos avançados de colaboração disponíveis nos aplicativos do Office.

### <a name="office-suite-feature-updates"></a>Pacote do Office: atualizações de recursos

- **Os aplicativos de terceiros do Office agora têm suporte para inserir imagens em SVG usando a API do Office.js:** agora, os aplicativos de terceiros, também conhecidos como suplementos do Office, têm a capacidade de inserir imagens em SVG. Os usuários já podem conectar a coleção pessoal de imagens em SVG ao Office e os desenvolvedores podem usar esse recurso com a API do Office.js.
- **Instalação do Microsoft Teams:**  o Microsoft Teams é instalado por padrão nas novas instalações do Office 365 ProPlus. [Saiba mais](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Atualizações de recursos

- **Suporte aprimorado para telas de alta definição:** se você usa vários monitores ou uma plataforma para laptop, os aplicativos do Office terão uma aparência mais nítida em cada tela, mesmo que elas tenham diferentes definições de dimensionamento. [Saiba mais](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança

- Foi resolvido um problema que causava uma falha ao salvar um arquivo contendo um mapa XML em PDF.
- Foi resolvido um problema que fazia com que links externos fossem removidos quando pastas de trabalho contendo nomes de planilha inválidos eram carregadas.
- Foi corrigido um problema em que o uso da ferramenta Câmera no Excel fazia com que a planilha fosse interrompida.
- Foi resolvido um problema que fazia com que os gráficos de Cascata e Funil ficassem dessincronizados com as tabelas quando as células eram inseridas ou excluídas.
- Foi resolvido um problema onde uma tabela de dados era recalculada durante o cálculo da planilha com uma fórmula de matriz em outra planilha, dependendo da tabela. 
- Foi resolvido um problema que impedia que pastas de trabalho protegidas por senha fossem abertas a partir do SharePoint sem fazer o check-out do arquivo primeiro.
- Foi feita uma alteração para garantir que o evento BeforeSave seja tratado ao compartilhar ou alternar o recurso Salvamento Automático. 
- Um problema ao usar a roda de rolagem do mouse em uma janela inativa com uma planilha de gráfico foi corrigido.
- Foi solucionado um problema que causava a mensagem "Erro inesperado" ao importar uma planilha no SharePoint.
- Um problema que ocorria ao abrir uma pasta de trabalho contendo formatação condicional que usa um Nome como regra e uma exibição personalizada foi resolvido.
- Macros usando validação de dados com fórmulas com mais de 255 caracteres podem ter produzido erros de tempo de execução. Esse problema foi agora corrigido.
- Um problema que fazia com que arquivos contendo Tabelas Dinâmicas vinculadas a outras pastas de trabalho fossem carregados lentamente. Esse problema foi resolvido.
- Um problema com a abertura de arquivos HTML e o recebimento do erro "o formato de arquivo e a extensão não correspondem" foi solucionado.
- Uma alteração foi feita para resolver problemas com a rolagem da roda do mouse em janelas inativas.
- Resolvido um problema em que pressionar a tecla Tab não movia para a próxima célula quando em uma célula com uma fórmula que terminava em um nome definido.
- Resolvido um problema em que a formatação das células estava fazendo com que o tamanho do arquivo expandisse desnecessariamente.
- Resolvido um problema em que recortar e colar uma tabela dinâmica entre pastas de trabalho podia resultar em dados sendo colados sem uma tabela dinâmica para outras pessoas com as quais você está colaborando.


### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança

- Solucionado um problema que fazia com que as tarefas dos clientes aparentemente desaparecessem ao adicionar uma segunda condição a "Agrupar por".
- Soluciona um problema que fazia com que os clientes não conseguissem editar alguns campos em itens que foram migrados.
- Corrigimos um problema no qual o Windows não aparecia no local correto quando a barra de tarefas do sistema era mantida à esquerda ou no topo da tela.
- Soluciona um problema que fazia com que os clientes sofressem uma falha ao carregar fotos no cartão de contato.
- Soluciona um problema que fazia com que alguns clientes sofressem falhas ao iniciar aplicativos do Office.
- Corrigimos um problema no qual o Windows não aparecia no local correto quando a barra de tarefas do sistema era mantida à esquerda ou no topo da tela.
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

 - Foi corrigido um problema em que, ao compartilhar um documento no momento em que este recebia colaborações, o documento produzia anexos com a extensão .asd.
 - Foi corrigido um problema com comentários atribuídos a autores aleatórios.
 - Corrigido um problema na remoção de assinatura ao finalizar um documento.
 - Corrigido um problema em que a edição de uma Pessoa Relacionada adicionada pelo SharePoint falhava.
 - Corrigido um problema em que aparecia a caixa de diálogo "Falha ao carregar recurso" ao abrir o Word.
 - Se um arquivo for aberto no modo somente leitura e você clicar em 'Salvar como' no painel 'Informações', o problema será corrigido para que a interface do usuário de salvar seja exibida.


### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

 - Isso corrigiu um erro no VBA relatando um estado incorreto de preenchimento de forma após uma ação de "desfazer".
 - Essa é uma correção de um problema em que os arquivos não podem ser salvos em pastas Apache WebDAV.
 - Corrige um problema em que o Office é fechado abruptamente quando os clientes abrem alguns arquivos armazenados na nuvem.
 - Corrigimos um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.
 - Corrigido um problema em que a lista de arquivos recentes parecia ter sido limpa para muitos usuários no Windows 10.
 - Corrigido um problema que fazia com que um usuário final visse uma barra de negócios de Atualização do Office, mesmo que houvesse uma atualização acionada pelo administrador em andamento.
 - Correção de problemas relacionados a avisos de logon em branco intermitentes.
 - Corrigido um problema em que partes de uma atualização do Office não usava o cache de pares de Otimização de Entrega. [Saiba mais](/windows/deployment/update/waas-delivery-optimization)
- Corrigido um bug que pode levar a remoção ou não ativação se o Office foi instalado usando a Ferramenta de Implantação do Office e houve uma incompatibilidade de caso.
- Corrigimos um problema que estava causando prompts de login excessivos nos dispositivos Windows 10 (versão 1803 ou posterior).
- Corrigimos a regressão que causava interrupções durante o download de imagens vinculadas.
- Corrigimos o desfoque de arquivos EMF grandes colados no Word, Excel, PowerPoint.
- Corrigimos o erro na lógica de análise do histórico de versões que, em alguns casos, fazia com que os documentos fossem abertos em modo somente leitura.


## <a name="version-1808-july-09"></a>Versão 1808: 09 de julho
*Versão 1808 (Build 10730.20360)*
<br/>Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança

- Melhor desempenho durante a habilitação de Partes Rápidas de propriedades do documento.
- Corrigido um problema na remoção de assinatura ao finalizar um documento.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Corrigido um problema que afeta os aplicativos do Office que estão sendo executados no Windows virtualizado. 


## <a name="version-1803-july-09"></a>Versão 1803: 09 de julho
*Versão 1803 (Build 9126.2428)*
<br/>Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


## <a name="version-1808-june-11"></a>Versão 1808: 11 de junho
*Versão 1808 (Build 10730.20348)*
<br/>Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
 - Corrigido um problema na remoção de assinatura ao finalizar um documento.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
 - Corrigido um problema que podia causar falhas em aplicativos do Office que estivessem sendo executados no Windows virtualizado.

## <a name="version-1803-june-11"></a>Versão 1803: 11 de junho
*Versão 1803 (Build 9126.2388)*
<br/>Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md) 

## <a name="version-1808-may-14"></a>Versão 1808: 14 de maio
*Versão 1808 (Build 10730.20344)*   

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
 - Soluciona um problema que fazia com que os clientes não conseguissem editar alguns campos em itens que foram migrados.

### <a name="visio-non-security-updates"></a>Visio: Atualizações não relacionadas à segurança
 - Corrigido um problema que estava causando problemas de hierarquia de janela interrompida para soluções de terceiros estendendo o Visio desabilitando o recurso DPI Dinâmico.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
 - Corrigido um problema em que a edição de uma Pessoa Relacionada adicionada pelo SharePoint falhava.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
 - Corrigimos um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.
  
## <a name="version-1803-may-14"></a>Version 1803: 14 de maio
*Versão 1803 (Build 9126.2387)*

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
 - Soluciona um problema que fazia com que os clientes não conseguissem editar alguns campos em itens que foram migrados.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
 - Corrigimos um problema de identificação incorreta do nome da nova era "Reiwa" em Hiragana e Kanji como um erro ortográfico ou expressão gramaticalmente incorreta.

## <a name="version-1808-april-9"></a>Versão 1808: 9 de abril
*Versão 1808 (Build 10730.20334)*

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
- Corrigido um problema no Lync (Skype for Business) onde para qualquer reunião online com mais de 7 participantes, a janela da reunião poderia desaparecer.

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança

- Corrigimos um problema em que os usuários não conseguiam abrir documentos anonimamente no IE ou no Edge.
- Corrigimos um problema em que a formatação da cor do realce de texto aplicada a qualquer campo PAGE e/ou NUMPAGES do cabeçalho/rodapé de qualquer documento do Word renderizava o campo como preto em vez da cor de realce de texto aplicada.
- Adicionamos suporte ao suplemento do assistente de cartão postal japonês do Word para a nova era japonesa. 

## <a name="version-1803-april-9"></a>Versão 1803: 9 de abril
- Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)

## <a name="version-1808-march-12"></a>Versão 1808: 12 de março
*Versão 1808 (Build 10730.20304)*

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança

- Correção do problema que ocorria quando o VBA retornava um número de página incorreto.
- Melhorar o tempo para salvar no arquivo do Word local. 

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança

- Foi fornecida uma regkey para desativar a opção "Somente Criptografar" no menu Criptografia de Mensagens do Office 365.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança

- Correção de um problema em que a atualização do Office pode ficar parada por algum tempo tentando fazer o download.

## <a name="version-1803-march-12"></a>Versão 1803: 12 de março 
- Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)

## <a name="version-1808-february-12"></a>Versão 1808: 12 de fevereiro
*Versão 1808 (build 10730.20280)*

### <a name="access-non-security-updates"></a>Access: Atualizações não relacionadas à segurança 

- Esta atualização adiciona suporte para as novas eras japonesas no Access.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança 

- Corrige o problema que levava os usuários que possuem regras que fazem referência a uma pasta que não existe mais. 1. Ver um erro ao tentar gerenciar as regras e 2. Ver as regras do lado cliente não funcionarem.
- Corrige o problema que levava os usuários com o caixas de correio delegadas em cache a encontrar paradas frequentes em intervalos imprevisíveis.
- Corrige o problema que fazia com que todas as Reuniões de Dia Inteiro abrangesse um dia a mais do que desejado em alguns modos de exibição, por a hora de término da reunião ser configurada para meia-noite do dia seguinte.
- Corrigiu o travamento durante a criação de novos compromissos ou reuniões que fazem referência ás eras japonesas.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Corrigiu o problema em que os Suplementos, implantados usando [implantação centralizada do O365 Office ](/office/dev/add-ins/publish/centralized-deployment), foram congelados e inutilizáveis.


## <a name="version-1803-february-12"></a>Versão 1803: 12 de fevereiro
*Versão 1803 (Build 9126.2356)*

*Este lançamento do Canal Semestral está disponível desde julho de 2018. Ele continuará com suporte e receberá atualizações de segurança até setembro de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral — Versão 1808 (Build 10730.20280) — que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

### <a name="access-non-security-updates"></a>Access: Atualizações não relacionadas à segurança 

- Esta atualização adiciona suporte para as novas eras japonesas no Access.

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança 

- Esta atualização adiciona suporte para as novas eras japonesas no Excel.

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança

- Corrigiu o travamento durante a criação de novos compromissos ou reuniões que fazem referência ás eras japonesas.

### <a name="project-non-security-updates"></a>Project: Atualizações não relacionadas à segurança
- Esta atualização adiciona suporte para as novas eras japonesas no Project

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança

- Esta atualização adiciona suporte para as novas eras japonesas no Word.

### <a name="visio-non-security-updates"></a>Visio: Atualizações não relacionadas à segurança

- Esta atualização adiciona suporte para as novas eras japonesas no Visio.

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Corrigiu o problema em que os Suplementos, implantados usando [implantação centralizada do O365 Office ](/office/dev/add-ins/publish/centralized-deployment), foram congelados e inutilizáveis.

## <a name="version-1708-february-12"></a>Versão 1708: 12 de fevereiro
*Versão 1708 (Build 8431.2372)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a — versão 1808 (Build 10730.20280) — que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança

- Corrigiu o problema em que os Suplementos, implantados usando [implantação centralizada do O365 Office ](/office/dev/add-ins/publish/centralized-deployment), foram congelados e inutilizáveis.


## <a name="version-1808-january-8"></a>Versão 1808: 8 de janeiro
*Versão 1808 (Build 10730.20264)*

### <a name="access-feature-updates"></a>Access: Atualizações de recursos

 - **Visualizar dados com gráficos novos:** escolha entre 11 gráficos e adicione um deles aos formulários e relatórios para visualizar melhor os dados e tomar decisões informadas. [Saiba mais](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)

### <a name="excel-feature-updates"></a>Excel: Atualizações de recursos
 - **Edição colaborativa:** trabalhe com outras pessoas em simultâneo na pasta de trabalho.[Saiba mais](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **O Salvamento Automático de arquivos da nuvem agora está habilitado por padrão:** Essa mudança significa que os usuários não precisarão se preocupar em perder as alterações em documentos armazenados no OneDrive ou no SharePoint Online. As alterações serão salvas na nuvem automaticamente e os usuários não terão mais que pressionar Ctrl + S ou o botão Salvar. No entanto, será necessário entender essa alteração de comportamento para que não façam alterações acidentais nos documentos. Observe que os usuários podem desativar o salvamento automático usando a alternância de salvamento automático na parte superior da tela. É recomendável notificar os usuários sobre essa mudança futura e informar sobre como tirar o melhor proveito desse novo recurso do Office 365. [Saiba mais sobre o Salvamento Automático](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) e [Saiba mais sobre o que os administradores de TI devem saber sobre o Salvamento Automático](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edição aprimorada para células e barra de fórmulas**: agora, é possível usar o comando Ctrl+T para selecionar texto em uma célula ou na barra de fórmulas. Há também um aprimoramento de suporte para emojis e outros caracteres complexos. [Saiba mais](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar as pastas de trabalho mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitar edições indesejadas:** configurar as pastas de trabalho abertos como somente leitura para impedir alterações acidentais. Acessar Arquivo > Informações > Proteger Pasta de Trabalho > Sempre Aberto Como Somente Leitura

### <a name="excel-non-security-updates"></a>Excel: Atualizações não relacionadas à segurança 

- Corrigido um problema de sessões de coautoria em que uma segmentação de dados não é corretamente atualizada após outro usuário aplicar um filtro de coluna para os dados na segmentação de dados.
- Correção de um problema em uma sessão de co-autoria em que um dos usuários limpa a legenda de uma segmentação de dados e isso faz com que outro usuário na sessão de co-autoria experiencie uma falha do Excel.
- Correção de possível falha ao criar várias segmentações de dados de tabela vinculadas à mesma coluna de dados e excluir essa coluna de dados.
- Corrigido um problema em que o Excel às vezes travava ao atualizar uma tabela de consulta filtrada que contém texto agrupado nas células quando a opção de ajustar automaticamente as larguras das colunas estava desativada.
- Correção de um problema em que as segmentações de dados salvas no Excel 2007 podem disparar uma falha quando abertas em versões mais recentes do Excel, se o número de itens mostrados na segmentação de dados for alterado.
- Introduz o suporte para o botão Obter Diagnóstico para simplificar a investigação de solicitações de suporte.
- Correção de um bug em que o Power Pivot não aparece em algumas compilações/versões.
- Correção de um problema no Excel no qual o Excel poderia ficar sem resposta, ao usuário passar o mouse sobre as opções de formatação em uma pasta de trabalho com vários nomes definidos e quando Excel se tornava não responsivo na ferramenta Análise Rápida mesmo quando Visualização Dinâmica estava desabilitada nas opções.
- Estamos atualmente investigando o desempenho lento ao mover a janela do aplicativo Excel uma área de trabalho para outra. Enquanto isso, se você perceber essa lentidão, uma solução alternativa a considerar é selecionar "Otimizar a compatibilidade" para "ao usar várias exibições" na guia "Geral" na caixa de diálogo Opções de arquivo.
- Correção de um problema em que o Excel pode falhar quando os dados de origem do gráfico do conjunto original de células são alterados.
- Correção de um problema em que o recálculo poderia não ocorrer ao abrir, mesmo que a propriedade FullCalcOnLoad esteja definida.  
- Correção um problema em que o ano errado é exibido quando o calendário de Era Japonesa é usado no formato de célula de data.
- Ao importar dados para o modelo de dados do Excel, os valores de entrada abaixo de zero resultavam em um erro. A correção importa esses valores como zero.
- Correção de um problema em que a operação agrupar ou desagrupar em uma Tabela Dinâmica do Excel podia, às vezes, gerar uma falha.
- Correção um problema em que as ações de gráficos poderiam causar uma falha no Excel.
- Correção de um problema em que o suplemento Power View é inadvertidamente desabilitado para alguns usuários.
- Correção de um problema em que os arquivos temporários de recuperação automática criados durante a recuperação do documentos nunca são limpos.
- Correção de um problema em que tentar fazer uma nova conexão com um arquivo de texto em uma pasta de trabalho protegida resultava em uma mensagem de erro "A pasta de trabalho está protegida e não pode ser alterada".
- Correção de um problema em que a Impressão Rápida de uma pasta de trabalho do Excel anexada ao email do Outlook poderia não ser impressa.
- Correção de um problema em que clicar em um hiperlink poderia causar uma falha no Excel.
- Correção de um problema em que usar funções de cubo causava uma falha no Excel.

### <a name="outlook-feature-updates"></a>Outlook: Atualizações de recursos
 - **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar as mensagens mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Gerenciar perfis a partir do Seletor de Perfil:** Se você usar o seletor de perfil ao iniciar o Outlook, agora você pode fazer alterações sem acessar o painel de controle. Crie e exclua perfis, altere as configurações, tudo pelo seletor de perfil.
- **Acessibilidade integrada no:** Torna suas mensagens acessíveis para todos, adicionando texto alt descritivo às suas imagens.
- **Avisos de suplemento do Outlook:** ocasionalmente, um suplemento do Outlook COM pode encontrar problemas que deixam mais lento o restante do Outlook. Esses problemas podem ser decorrentes da latência dos eventos, como alternar entre as pastas do Outlook, da chegada de novos emails, da abertura de itens do Calendário, entre outros. Quando problemas surgirem, o Outlook exibirá um aviso na barra de notificações.
- **Saiba com quem você vai se encontrar:** agora é possível ver as respostas de outras pessoas a uma solicitação de reunião, mesmo se você não for o organizador.
- **Nunca mais perca um lembrete:** defina lembretes a serem exibidos sobre as janelas nas quais você está trabalhando. Caso contrário, o Outlook piscará na barra de ferramentas para chamar a atenção. [Saiba mais](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Marque itens excluídos como lidos:** agora você pode definir qualquer mensagem excluída como lida. Para isso, vá para Arquivo \> Opções \> Email \> Outras.
- **Veja três fusos horários:** Precisa agendar uma reunião em diferentes fusos horários? Adicione vários fusos ao seu calendário para ver facilmente a disponibilidade dos participantes e escolha um horário que funcione para todos. [Saiba mais](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Experiência refinada do usuário para criação de um grupo:** aperfeiçoamos a experiência do usuário para criação de grupos para torná-la mais moderna e organizada. [ Saiba mais](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
- Correção um problema que levava os usuários a enfrentar problemas de sincronização do calendário.
- Correção de um problema que fazia com que os usuários vissem um erro ao iniciar a caixa de diálogo "Gerenciar regras e alertas".
- Corrigido um problema que fazia com que os usuários não conseguissem conectar suas caixas de correio pelo DirectAccess ao usar uma conexão limitada.
- Corrigido um problema que fazia com que os usuários visualizassem documentos gratuitos armazenados em Pastas Públicas erroneamente abertos na "Modo de Exibição Protegido".
- Corrigido um problema que fazia com que os usuários vissem anexos inesperados ao encaminhar itens com anexos embutidos.
- Corrigido um problema que fazia com que os arquivos OFT apresentassem problemas após serem enviados como anexos.
- Correção de um problema que fazia com que alguns usuários experienciem falhas ao adicionar uma reunião a um calendário compartilhado.
- Correção de um problema que fazia com que os usuários experimentassem interrupções ao abrir a pasta Histórico de Conversas.
- Correção de um problema em que, se você mudasse o idioma do sistema para japonês e tentasse digitar caracteres japoneses no VBA IDE quando carregados no Outlook, ele congelava.
- Correção de um problema em que mudar para a pasta Itens Enviados ou Caixa de Saída causava uma falha no Outlook.
- Correção de um problema em que todos os participantes recebiam atualizações da reunião quando o corpo da reunião ou anexos mudavam, ao invés de enviar uma atualização de reunião aos participantes ser opcional.
- Correção de um problema que impossibilitava o usuário de se conectar a pontos de extremidade EWS e REST devido a uma alteração na cadeia de caracteres Usuário-Agente.
- Correção de um problema em que atualizar o local da reunião para os participantes mostrava o local antigo ao invés do novo local.
- Correção de um problema em que o usuário via uma mensagem de erro quando visualizava um anexo no painel de leitura.
- Correção de um problema em que o Outlook falhava ao mudar a exibição de nomes para endereços de email quando o usuário estava redigindo um email.
- Correção de um problema em que alguns usuários não recebiam os recursos de suporte que foram habilitados pelo administrador de locatários.

### <a name="onenote-non-security-updates"></a>OneNote: Atualizações não relacionadas à segurança 

- Correção de um problema de estabilidade que poderia ocorrer envolvendo a sincronização e a navegação para uma seção excluída.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Atualizações de recursos 
- **O Salvamento Automático de arquivos da nuvem agora está habilitado por padrão:** Essa mudança significa que os usuários não precisarão se preocupar em perder as alterações em documentos armazenados no OneDrive ou no SharePoint Online. As alterações serão salvas na nuvem automaticamente e os usuários não terão mais que pressionar Ctrl + S ou o botão Salvar. No entanto, será necessário entender essa alteração de comportamento para que não façam alterações acidentais nas apresentações. Observe que os usuários podem desativar o salvamento automático usando a alternância de salvamento automático na parte superior da tela. É recomendável notificar os usuários sobre essa mudança futura e informar sobre como tirar o melhor proveito desse novo recurso do Office 365. [Saiba mais sobre o Salvamento Automático](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) e [Saiba mais sobre o que os administradores de TI devem saber sobre o Salvamento Automático](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Edição aprimorada para células e barra de fórmulas**: agora, é possível usar o comando Ctrl+T para selecionar texto em uma célula ou na barra de fórmulas. Há também um aprimoramento de suporte para emojis e outros caracteres complexos. [Saiba mais](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Converta suas notas escritas:** faça anotações e desenhos e converta-os em texto legível e formas simples para criar uma apresentação elegante. [Saiba mais](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Suporte aprimorado para SVG:** agora, é possível inserir imagens SVG que tenham filtros aplicados. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Dê um título aos slides com uma caneta**: use a caneta para escrever um título com tinta e veja o PowerPoint converter a tinta em texto. [Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Evitar edições indesejadas:** configurar as pastas de trabalho abertos como somente leitura para impedir alterações acidentais. Acessar Arquivo > Informações > Proteger Pasta de Trabalho > Sempre Aberto Como Somente Leitura
- **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar as apresentações mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)


### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
- Correção de um problema de possível corrupção de arquivo ao salvar arquivos com o conteúdo do ActiveX.
- Correção de um problema em que as tabelas eram renderizadas incorretamente com bordas espessas.
- Correção de um problema em que uma falha potencial poderia ocorrer ao alterar a propriedade Shape.Visibile.
- Correção de um problema em que ocorria uma falha ao mesclar alterações em documentos criados em coautoria.
- Correção de um problema em que os documentos contendo Controles ActiveX poderiam causar falha durante a coautoria.
- Correção de um problema em que a correção ortográfica nas formas causava uma falha no PowerPoint.
- Correção de um problema em que o PowerPoint falhava ao abrir um arquivo do SharePoint Online.
- Correção de um problema em que o Painel de Recuperação era exibido de forma incorreta quando o Salvamento Automático estava ativado.
- Correção de um problema em que a opção para entrar não era exibida, impedindo o usuário de acessar um arquivo.
- Correção de um problema em que a coautoria de vários usuários na mesma apresentação gerava uma duplicação incorreta dos slides mestres.
- Correção de um problema em que abrir um arquivo salvo no OneDrive resultava em uma falha no PowerPoint ao sair do Modo de Exibição Protegida.

### <a name="project-feature-updates"></a>Projeto: Atualizações de recursos 
- **Gerenciamento de Sprint :** rapidamente adicionar, atualizar ou excluir agile sprints.
- **Filtragem do painel de tarefas:** simplifique seus painéis de tarefas filtrando os principais recursos ou tarefas resumos.
- **Defina a porcentagem concluída de um quadro de tarefas:** escolha a porcentagem concluída de cada coluna e atualize a conclusão da tarefa ao arrastar e soltar.
- **Navegação Sprint:** alterne de uma exibição sprint para outra e mova rapidamente as tarefas entre sprints.
- **Uma nova maneira de gerenciar sprints:** adote uma abordagem ágil trabalhando com os Painéis de Tarefas. Acesse Gerenciar Sprints para adicionar e remover sprints durante o projeto.
- **Mantenha a organização com locais de salvamento Recentes**: o Project mantém uma lista ativa de locais em que você salvou outros projetos. Quando estiver pronto para salvar um projeto, basta escolher um dos Locais de salvamento recentes e continuar trabalhando.

### <a name="project-non-security-updates"></a>Projeto: Atualizações não relacionadas à segurança

- Corrigido um problema em torno do suporte a uma nova moeda venezuelana no Project.
- Corrigido um problema onde o projeto pode responder ao usar um Surface 4 que está conectado a um monitor externo.
- Corrigido um problema onde o Project pode falhar ao salvar o projeto em formato XML.
- Corrigido um problema em que os campos personalizados de recursos da empresa podem ser excluídos após a edição do calendário do recurso.
- Correção de um problema que levava os usuários a enfrentar falhas ao pesquisar nomes em coreano.
- Correção de um problema em que você era impedido de salvar um subprojeto ao trabalhar com eles por meio do contexto de um projeto mestre.

### <a name="word-feature-updates"></a>Word: Atualizações de recursos
- **O Salvamento Automático de arquivos da nuvem agora está habilitado por padrão:** Essa mudança significa que os usuários não precisarão se preocupar em perder as alterações em documentos armazenados no OneDrive ou no SharePoint Online. As alterações serão salvas na nuvem automaticamente e os usuários não terão mais que pressionar Ctrl + S ou o botão Salvar. No entanto, será necessário entender essa alteração de comportamento para que não façam alterações acidentais nas apresentações. Observe que os usuários podem desativar o salvamento automático usando a alternância de salvamento automático na parte superior da tela. É recomendável notificar os usuários sobre essa mudança futura e informar sobre como tirar o melhor proveito desse novo recurso do Office 365. [Saiba mais sobre o Salvamento Automático](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) e [Saiba mais sobre o que os administradores de TI devem saber sobre o Salvamento Automático](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Aprimoramentos do Verificador de Acessibilidade:** o Verificador de Acessibilidade atualizou o suporte para padrões e recomendações internacionais para deixar os documentos mais acessíveis.[Saiba mais](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Suporte aprimorado para SVG:** Agora, é possível inserir imagens SVG que tenham filtros aplicados. [Saiba mais](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-non-security-updates"></a>Word: Atualizações não relacionadas à segurança
- Correção de um problema que causava a exibição de uma mensagem de memória insuficiente.
- Correção de um conjunto de problemas que impedia alguns usuários de abrir emails e documentos protegidos por IRM que eram compartilhados com eles por pessoas de outras organizações.
- Correção de alguns problemas de desempenho.
- Melhore o desempenho abrir.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Atualizações não relacionadas à segurança
- Corrige um problema relacionado ao suporte TLS 1,2. (Observação: esta é a mesma correção que foi mencionada nas anotações de 10 de abril e mencionada aqui novamente como parte da acúmulo de setembro.)
- Correção de um problema quando, ao adicionar usuários escolhendo "Chamada do Skype" em uma reunião causa um erro.
- Remove o prompt que pede ao usuário para adicionar coordenadas do Skype a uma reunião se uma Sala de Skype for adicionada como o local e a reunião já contiver as coordenadas de reunião das Equipes.
- Correção de um problema em que o local é preenchido, mesmo quando UseLocationForE911Only é definido como verdadeiro.
- Correção de um problema em que o Skype for Business trava ao usar a opção "ligar usando o centro de conferências" para convidar usuários da lista de participantes.
- Correção de um problema em que o Outlook em execução no servidor de área de trabalho remota congela ao criar uma reunião do Skype for Business.
- Altere o valor padrão de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket para TRUE.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos
- **Mantenha seu diagrama e fonte em sincronia:** ao editar um diagrama do Visualizador de dados no Visio, você tem a opção para atualizar os dados de origem vinculados do Excel com o conteúdo mais recente do diagrama.
- **Modelo de auditoria do Visualizador de dados** importar o conteúdo do Excel e criar diagramas de auditoria para transações financeiras, gerenciamento de estoque e muito mais.
- **Diagramas iniciais:** os modelos Gráfico da Organização, Debate e SDL têm novos diagramas iniciais para você começar a trabalhar rapidamente.
- **Use formas do Visio para criar um documento do Word:** adicione automaticamente o conteúdo de diagramas, incluindo formas e metadados, em um documento do Word. Personalize o documento para criar diretrizes de processo e manuais de operação. [Saiba mais](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-security-update"></a>Pacote Office: Atualizações de segurança

- 
  **Controles Flash, Silverlight e Shockwave impedidos de ativar o Office por motivos de segurança:** por motivos de segurança os novos builds do Microsoft Office para o Office 365 na ativação do Windows bloqueiam a ativação dos controles Flash, Silverlight, e Shockwave. Saiba mais [aqui](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)e[aqui](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1).
 
### <a name="office-suite-non-security-updates"></a>Pacote do Office: Atualizações não relacionadas à segurança
- Correção de um problema que causava a demora na instalação de atualização em determinadas situações.
- Correção de um problema em que, ao abrir um aplicativo, às vezes o usuário via uma mensagem sobre a inicialização no modo de segurança e, em seguida, o aplicativo não abria.
- Correção de alguns problemas de desempenho.


## <a name="version-1803-january-8"></a>Versão 1803: 8 de janeiro
*Versão 1803 (Build 9126.2351)*

*Este lançamento do Canal Semestral que está disponível desde julho de 2018. Ele continuará com suporte e receberá atualizações de segurança até setembro de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral — Versão 1808 — que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Atualizações não relacionadas à segurança
- Correção de um problema para garantir a paridade de recursos da opção LinkedIn entre aplicativos do Office.

## <a name="version-1803-december-11"></a>Versão 1803: 11 de dezembro
*Versão 1803 (build 9126.2336)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): vulnerabilidade de execução remota de código do Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): vulnerabilidade de execução remota de código do Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): vulnerabilidade de execução remota de código do Microsoft PowerPoint 


### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança

- Corrigido um problema que fazia com que o Outlook fechasse inesperadamente ao atualizar determinados campos de contato.
- Soluciona um problema que fazia com que os usuários vissem um erro ao iniciar a caixa de diálogo "Gerenciar regras e alertas".
- Soluciona um problema que fazia com que os usuários do Outlook enfrentassem falhas durante a execução de alguns suplementos..


## <a name="version-1708-december-11"></a>Versão 1708: 11 de dezembro
*Versão 1708 (build 8431.2351)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1803 (build 16.0.9126.2336), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): vulnerabilidade de execução remota de código do Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): vulnerabilidade de execução remota de código do Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): vulnerabilidade de execução remota de código do Microsoft PowerPoint 

### <a name="outlook-non-security-updates"></a>Outlook: Atualizações não relacionadas à segurança

- Corrigido um problema que fazia com que o Outlook fechasse inesperadamente ao atualizar determinados campos de contato.
- Soluciona um problema que fazia com que os usuários vissem um erro ao iniciar a caixa de diálogo "Gerenciar regras e alertas".
- Soluciona um problema que fazia com que os usuários do Outlook enfrentassem falhas durante a execução de alguns suplementos..


## <a name="version-1803-november-13"></a>Versão 1803: 13 de novembro
*Versão 1803 (build 9126.2315)*

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

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): vulnerabilidade de negação de serviço do Microsoft Skype for Business 

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas com a segurança 

- Essa alteração permite aos usuários Salvar Todos os arquivos físicos em um compartilhamento de rede, incluindo uma unidade de rede mapeada. 

## <a name="version-1708-november-13"></a>Versão 1708: 13 de novembro
*Versão 1708 (build 8431.2329)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1803 (build 16.0.9126.2315), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

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

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): vulnerabilidade de negação de serviço do Microsoft Skype for Business 

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas com a segurança 

- Essa alteração permite aos usuários Salvar Todos os arquivos físicos em um compartilhamento de rede, incluindo uma unidade de rede mapeada. 


## <a name="version-1803-october-9"></a>Versão 1803: 9 de outubro
*Versão 1803 (build 9126.2295)*

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

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrigido um problema de aplicativos mostrando animações apesar das animações pelas configurações de acessibilidade e desempenho estar desativada.
-   Corrigido problema da tela de fundo ficar em branco ao usar o marca-texto na ferramenta de desenho.

## <a name="version-1708-october-9"></a>Versão 1708: 9 de outubro
*Versão 1708 (build 8431.2316)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1803 (build 16.0.9126.2282), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

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


## <a name="version-1803-september-11"></a>Versão 1803: 11 de setembro
*Versão 1803 (build 9126.2282)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): vulnerabilidade de execução remota de código do Microsoft Excel
-   [/CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): vulnerabilidade de divulgação de informações do Microsoft Excel

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Vulnerabilidade de execução remota de código em PDFs no Windows

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): vulnerabilidade de execução remota de gráficos Win32k


## <a name="version-1708-september-11"></a>Versão 1708: 11 de setembro
*Versão 1708 (build 8431.2309)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1803 (build 16.0.9126.2282), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): vulnerabilidade de execução remota de código do Microsoft Excel
-   [/CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): vulnerabilidade de divulgação de informações do Microsoft Excel

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Vulnerabilidade de execução remota de código em PDFs no Windows

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): vulnerabilidade de execução remota de gráficos Win32k


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


## <a name="version-1708-august-14"></a>Versão 1708: 14 de agosto
*Versão 1708 (build 8431.2299)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1803 (build 16.0.9126.2275), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

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
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): vulnerabilidade de execução remota de código do Microsoft Access
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidade Use-After-Free de execução remota de código do Microsoft Access 

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
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): bypass de recursos de segurança do Microsoft Office Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilidade de execução remota de código do Microsoft Excel 
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilidade de divulgação de informações do Microsoft Excel 
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilidade de divulgação de informações confidenciais do Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): bypass de recursos de segurança do Microsoft Office Excel
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança

-   Corrige um problema em que o ano errado é exibido quando o calendário de Era japonesa é usado no formato de célula de data.
-   Ao importar dados para o modelo de dados do Excel, os valores de entrada abaixo de zero resultavam em um erro. A correção importa esses valores como zero.
-   Correção de um problema em que a operação agrupar ou desagrupar em uma Tabela Dinâmica do Excel podia, às vezes, gerar uma falha.
-   Correção um problema em que as ações de gráficos podem causar uma falha no Excel.
-   Correção de um problema em que o suplemento Power View é inadvertidamente desabilitado para alguns usuários.
-   Correção de um problema em que os arquivos temporários de recuperação automática criados durante a recuperação de documentos nunca são limpos.
-   Correção de um problema em que o Excel falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que a Impressão Rápida de uma pasta de trabalho do Excel anexada ao email do Outlook pode não ser impressa.
-   Correção de um problema em que clicar em um hiperlink pode causar uma falha no Excel.
-   Correção de um problema em que usar funções de cubo pode causar uma falha no Excel.
-   Correção de um problema em que impressão ou visualização da impressão só imprime ou exibe uma parte da planilha, com o conteúdo truncado em uma segmentação de dados na planilha.
-   Correção de um problema em que ao tentar fazer uma nova conexão com um arquivo de texto em uma pasta de trabalho protegida gera como resultado uma mensagem de erro "A pasta de trabalho está protegida e não pode ser alterada". Correção de um problema em que, se o idioma de edição for o japonês, chinês ou coreano, o Excel congelará quando você tentar escolher uma nova fonte na guia Página Inicial ou editar.
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
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilidade de elevação de privilégios do Microsoft Outlook
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidade de adulteração do Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que mudar para a pasta Itens Enviados ou Caixa de Saída causa uma falha no Outlook.
-   Correção de um problema em que todos os participantes recebem atualizações da reunião quando o corpo da reunião ou anexos mudam, em vez de o envio de uma atualização de reunião aos participantes ser opcional.
-   Correção de um problema que impossibilita o usuário de se conectar a pontos de extremidade de EWS e REST devido a uma alteração na cadeia de caracteres Usuário-Agente.
-   Correção de um problema em que atualizar o local da reunião para os participantes mostra o local antigo em vez de o novo local.
-   Correção de um problema em que o usuário vê uma mensagem de erro quando visualiza um anexo no painel de leitura.
-   Correção de um problema em que o Outlook falha ao resolver a exibição de nomes para endereços de email quando o usuário estiver redigindo um email.
-   Correção de um problema em que alguns usuários não recebem os recursos de suporte que foram habilitados pelo administrador de locatários
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
-   Correção de um problema em que as tabelas são renderizadas incorretamente com bordas espessas.
-   Correção de um problema em que podia ocorrer uma falha ao alterar a propriedade Shape.Visibile.
-   Correção de um problema em que ocorre uma falha ao mesclar alterações em documentos criados em coautoria.
-   Correção de um problema em que os documentos contendo Controles ActiveX poderiam causar falha durante a coautoria.
-   Correção de um problema em que a correção ortográfica nas formas causa uma falha no PowerPoint.
-   Correção de um problema em que o PowerPoint falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que o Painel de Recuperação é exibido de forma incorreta quando o Salvamento Automático está ativado.
-   Correção de um problema em que a opção para entrar não é exibida, impedindo o usuário de acessar um arquivo.
-   Correção de um problema em que a coautoria de vários usuários na mesma apresentação gera uma duplicação incorreta dos slides mestres.
-   Correção de um problema em que abrir um arquivo salvo no OneDrive resulta em falha no PowerPoint ao sair do Modo de Exibição Protegido. Correção de um problema em que remover propriedades do documento e informações pessoais podem causar uma falha no salvamento do SharePoint.
-   Correção de um problema em que as referências a códigos de inserção do YouTube com base no Flash Player resultam na abertura de uma nova janela para reproduzir o vídeo. Antigos códigos de inserção agora foram atualizados para fazer referência a vídeos do YouTube com base em HTML5 para que possam ser reproduzidos corretamente no lugar.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.

### <a name="project-feature-updates"></a>Project: atualizações de recursos
-   **Modo de exibição Painel de Tarefas:** classifique as tarefas nos cartões no modo de exibição Painel de Tarefas. Reordene e mova os cartões entre colunas no quadro, assim como em projetos Agile.
-   **Projetos Agile:** gerencie os projetos Agile usando listas de pendências, painéis de tarefas, sprints e muito mais. As metodologias Scrum ou Kanban são compatíveis. [Saiba mais](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Gerencie uma tarefa no Planner:** vincule uma tarefa do Project ao Planner e crie um plano para ela. Divida a tarefa em subtarefas, adicione uma equipe, atribua tarefas e gerencie o trabalho em um quadro de tarefas.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema em que, se uma tarefa fosse dividida com um recurso de custo, o recurso de custo não era atualizado corretamente e o custo era perdido.
-   Correção de um problema em que, ao adicionar tarefas existentes à caixa de diálogo da Linha do Tempo, somente as tarefas da primeira tarefa resumo eram exibidas no Modo de Exibição da Linha do Tempo.
-   Correção de um problema onde salvar como XML poderia falhar para projetos mestres no Project Online ou no Project Server.
-   Correção de um problema em que, ao adicionar tarefas existentes à caixa de diálogo da Linha do Tempo, somente as tarefas da primeira tarefa resumo eram exibidas no Modo de Exibição da Linha do Tempo.
-   Correção de um problema em que usar o menu suspenso Filtro Automático em uma coluna de datas faz com que todas as tarefas do projeto sejam ocultas.
-   Correção de um problema em que somente a primeira tarefa resumo é exibida na caixa de diálogo ao adicionar tarefas existentes a uma linha do tempo quando no modo de exibição de Linha do Tempo.
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
-   Correção de um problema relacionado ao suporte do TLS 1.2.
-   Correção de um problema em que adicionar usuários escolhendo "Chamada do Skype" em uma reunião causa um erro
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
-   Correção de um problema em que o Word falha ao abrir um arquivo do SharePoint Online.
-   Correção de um problema em que a numeração de página em algarismos romanos minúsculos são alterados de forma incorreta para maiúsculos.
-   Correção de um problema que causa a exibição de uma mensagem de memória insuficiente.
-   Corrige um problema onde o Word não abre em um computador executando o Windows 7 e que não têm a atualização para telemetria de diagnóstico e experiência do usuário instalado.
-   Correção de um problema em que os marcadores não são impressos em listas.
-   Corrigido um problema em que o Word falha quando um usuário tenta Salvar Como para um documento existente no OneDrive for Business e cancela o salvamento ou tenta mesclar alterações existentes.
-   Corrigido um problema em que a filtragem de campos de fontes de dados que contêm valores nulos (vazios) falha ao executar o Assistente de Mala Direta.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Corrigido um problema em que remover a proteção de IRM em um documento não remove a proteção.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidade de execução remota de código do Microsoft Office
-   [Supervisão 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): atualização de Proteção Abrangente do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Corrija um problema em que, ao implantar atualizações usando o Gerenciador de Configurações em um cliente que executa aplicativos do Office, a atualização não é aplicada após a reinicialização do dispositivo enquanto os aplicativos do Office estiverem em execução.
-   Correção de um problema em que, ao abrir um aplicativo, às vezes o usuário via uma mensagem sobre a inicialização no modo de segurança e, em seguida, o aplicativo não abria.
-   A opção Atualizar Agora fica oculta em Opções de Atualização da \> Conta \> do Arquivo quando um objeto COM do Office está habilitado para que as atualizações de cliente do Office 365 sejam gerenciadas pelo Gerenciador de Configurações.
-   Correção de um problema em que o aplicativo do Office falha quando o usuário tenta ativá-lo usando a caixa de diálogo Ativar o Office.
-   Correção de um problema com o zoom e dimensionamento em Suplementos do Office em um ambiente de DPI dinâmico.
-   Correção de um problema em que o nó CurrentStatus do provedor de serviços de configuração (CSP) do Office retorna uma cadeia de caracteres vazia mesmo se o Office 365 ProPlus estiver instalado atualmente.
-   Correção de um problema que causa mudanças de formato no arquivo .box, o que afeta a funcionalidade de versões mais antigas do Office instaladas no mesmo computador, porque os arquivos .box são compartilhados entre todas as versões de um aplicativo do Office no mesmo computador.
-   Correção de um bug que causava a demora na instalação de atualização em determinadas situações. 
-   Corrige um problema em que os testes SVG estão falhando
-   Corrija um problema em que, ao implantar atualizações usando o Gerenciador de Configurações em um cliente que executa aplicativos do Office, a atualização não é aplicada após a reinicialização do dispositivo enquanto os aplicativos do Office estiverem em execução.


## <a name="version-1708-july-10"></a>Versão 1708: 10 de julho
*Versão 1708 (build 8431.2280)*

*Este é o lançamento do Canal Semestral que está disponível desde janeiro de 2018. Ele continuará com suporte e receberá atualizações de segurança até março de 2019. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1803 (build 9126.2259), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança.*

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilidade Use-After-Free de execução remota de código do Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilidade de adulteração do Microsoft Office

### <a name="office-suite-security-updates"></a>Pacote do Office: Atualizações de segurança
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilidade de execução remota de código do Microsoft Office


## <a name="version-1708-june-12"></a>Versão 1708: 12 de junho
*Versão 1708 (build 8431.2270)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilidade de divulgação de informações confidenciais do Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilidade de elevação de privilégios do Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que os usuários do Windows 7 SP1 não conseguiam adicionar membros aos Grupos Modernos.



## <a name="version-1705-june-12"></a>Versão 1705: 12 de junho
*Versão 1705 (build 8201.2294)*

*Este é o lançamento do Canal Adiado que está disponível desde setembro de 2017. Ele continuará com suporte e receberá atualizações de segurança até julho de 2018. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1708 (build 8431.2270), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança*.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilidade de divulgação de informações confidenciais do Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilidade de elevação de privilégios do Microsoft Outlook



## <a name="version-1708-may-8"></a>Versão 1708: 8 de maio
*Versão 1708 (build 8431.2250)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilidade de divulgação de informações do Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1705-may-8"></a>Versão 1705: 8 de maio
*Versão 1705 (build 8201.2278)*

*Este é o lançamento do Canal Adiado que está disponível desde setembro de 2017. Ele continuará com suporte e receberá atualizações de segurança até julho de 2018. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1708 (build 8431.2250), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança*.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilidade de divulgação de informações do Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1708-april-10"></a>Versão 1708: 10 de abril
*Versão 1708 (build 8431.2242)*

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Correção de um problema relacionado ao suporte do TLS 1.2.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1705-april-10"></a>Versão 1705: 10 de abril
*Versão 1705 (build 8201.2272)*

*Este é o lançamento do Canal Adiado que está disponível desde setembro de 2017. Ele continuará com suporte e receberá atualizações de segurança até julho de 2018. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1708 (build 8431.2242), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança*.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilidade de execução remota de código do Microsoft Excel

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Vulnerabilidade de Execução Remota de Código do Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilidade de execução remota de código do Microsoft Office



## <a name="version-1708-march-13"></a>Versão 1708: 13 de março
*Versão 1708 (build 8431.2236)*

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): vulnerabilidade de execução remota de código do Microsoft Access

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): bypass de recursos de segurança do Microsoft Office Excel

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office



## <a name="version-1705-march-13"></a>Versão 1705: 13 de março
*Versão 1705 (build 8201.2265)*

*Este é o lançamento do Canal Adiado que está disponível desde setembro de 2017. Ele continuará com suporte e receberá atualizações de segurança até julho de 2018. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1708 (build 8431.2236), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança*.

### <a name="access-security-updates"></a>Access: atualizações de segurança
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): vulnerabilidade de execução remota de código do Microsoft Access

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): bypass de recursos de segurança do Microsoft Office Excel

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office



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



## <a name="version-1705-february-13"></a>Versão 1705: 13 de fevereiro
*Versão 1705 (build 8201.2258)*

*Este é o lançamento do Canal Adiado que está disponível desde setembro de 2017. Ele continuará com suporte e receberá atualizações de segurança até julho de 2018. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1708 (build 8431.2215), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança*.

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

### <a name="access-feature-updates"></a>Access: atualizações de recursos
-   **Propriedade Label Name:** melhora a acessibilidade associando um rótulo a um controle ou formulário.
-   **A edição de itens novos ficou mais acessível:** use um atalho de teclado (Ctrl+E) rápido para editar um novo item em uma caixa de combinação ou em uma caixa de listagem.
-   **Dynamics Connector:** importar dados ou vincular a dados armazenados no Microsoft Dynamics. [Saiba mais](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Conector do Salesforce:** importar dados ou vincular a dados armazenados na Salesforce. [Saiba mais](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="access-non-security-updates"></a>Access: atualizações não relacionadas à segurança
-   Correção de um problema em que tentar selecionar o texto em uma caixa de texto ou caixa de combinação parecia selecionar todo o texto, em vez da seleção de indicação.
-   Correção de um problema em que uma consulta não era executada se ela tivesse uma junção com uma chave primária de uma tabela vinculada do Microsoft Dynamics.
-   Correção de um problema em que as casas decimais não eram mostradas para valores monetários em uma tabela do Microsoft Dynamics.

### <a name="excel-feature-updates"></a>Excel: atualizações de recursos
-   **Melhorias do recurso "Adicionar Coluna de Exemplos":** com suporte para mais transformações de Data/Hora, Matemática e coluna de índice.
-   **Melhorias de desempenho:** O Excel abre pastas de trabalho complexas com várias planilhas mais rápido, para que você possa processar fórmulas com intervalos grandes, filtrar muitas linhas, ou copiar e colar mais rápido.
-   **Inserir imagens online:** a nova página de chegada para seleção de imagens e informações de atribuição são inseridas automaticamente com a imagem.
-   **Conector do Azure Data Lake Store:** os usuários já podem importar dados do Azure Data Lake Store.
-   **Melhorias "Adicionar coluna de Exemplos":** com suporte para sugestões, mais operações de Data/Hora e outras transformações.
-   **Guia Dados**: os botões da faixa de opções na guia Dados foram reorganizados em dois novos grupos: Obter e Transformar Dados e Consultas e Conexões.
-   **Compartilhar consultas**: exporte qualquer definição de consulta em um arquivo ODC (Conexão do banco de dados do Office) e compartilhe-o entre pastas de trabalho ou com outras pessoas.
-   **Carregar dados:** Carregue dados de uma consulta diretamente em tabelas dinâmicas ou gráficos dinâmicos sem precisar salvar os dados no modelo de dados.
-   **Atividade de arquivo compartilhado:** Escolha o botão Atividade, no canto superior direito do arquivo, para ver quando ele foi compartilhado, editado, renomeado ou restaurado no OneDrive for Business ou no SharePoint.
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Funcionalidade de importação de dados melhorada:** Importe facilmente e molde dados de várias fontes. Gerencie conexões e consultas de pastas de trabalho com o painel lateral Consultas e Conexões, e compartilhe as consultas com outras pessoas por meio dos arquivos ODC. [Mais informações](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Alterações em arquivos compartilhados**: veja quem fez alterações em pastas de trabalho compartilhadas e restaure versões anteriores. [Saiba mais](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Seleção de Laço com um botão de caneta:** use botões de caneta digital compatíveis para Seleção de Laço com tinta sem ter que acessar a Faixa de Opções.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): vulnerabilidade de bypass do recurso de segurança do Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilidade de corrupção de memória do Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): vulnerabilidade de execução remota de código do Microsoft Excel
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilidade de execução remota de código do Microsoft Excel
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: atualizações não relacionadas à segurança
-   Correção de um problema em que a criação programática de uma Tabela Dinâmica seguida de uma atualização programática causa uma falha no Excel.
-   Correção de um problema em que é exibida incorretamente ao usuário a mensagem de erro "Falha catastrófica" ao abrir uma pasta de trabalho com macros no Office 2007 ou versão anterior (.xls ou .xla).
-   Correção de um problema em que abrir uma pasta de trabalho na linha de comando pode causar perda de formatação em rich text na célula.
-   Correção de um problema em que o usuário não conseguia fechar uma pasta de trabalho no modo de exibição protegido quando o nome do arquivo continha colchetes.
-   Correção de um problema em que, quando o usuário tenta inserir um objeto em uma pasta de trabalho existente, o Excel falha quando o usuário clica em Navegar.
-   Correção de um problema em que selecionar "Redimensionar a forma para corrigir o texto" (na parte da Opções de Texto/Caixa de Texto do painel Formatar Forma) não resulta em uma mudança na forma.
-   Correção de um problema em que, ao abrir uma pasta de trabalho clicando duas vezes nela, as fontes e formatos das células de texto não são carregados ou duas pastas de trabalho idênticas são abertas para um único modelo.
-   Correção de um problema em que a primeira pasta de trabalho criada ao iniciar o Excel não fecha quando uma nova pasta de trabalho é aberta ou criada.
-   Corrigido um problema em que o posicionamento da dica de ferramenta é desalinhado ao arrastar ou preencher arrastando.
-   Corrigido um problema em que, ao salvar uma pasta de trabalho usando Arquivo \> Salvar Como, um nome de arquivo que contém pontos aparece em branco ou truncado na caixa de diálogo Salvar arquivo.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Correção um problema com a renderização onde linhas e cabeçalhos pretos aparecem devido a falhas no driver de gráfico.
-   Correção de um problema em que o Excel falha ou não consegue salvar a pasta de trabalho após a inserção de um gráfico.
-   Correção de um problema em que a linha de quebra de página na visualização de quebra de página está posicionada incorretamente.
-   Correção de um problema em que o Excel falha ao abrir um arquivo .XLL.
-   Correção de um problema em que o estilo de padrão de uma célula não renderiza corretamente depois de adicionar um cabeçalho ou rodapé no modo de exibição Layout de Página.
-   Correção de um problema em que colar uma cópia de uma Tabela Dinâmica em outra pasta de trabalho pode resultar em uma falha.
-   Correção de um problema em que, quando você seleciona o comando Substituir e a caixa de diálogo Localizar e Substituir se abre, o foco da caixa de diálogo fica na guia Localizar em vez de na guia Substituir.
-   Correção de um problema em que o Excel falha ao abrir o painel Atividade de uma pasta de trabalho aberta em um servidor do SharePoint mais antigo do que o SharePoint Server 2016.
-   Correção de um problema em que o Excel abre e exibe uma janela em branco quando um ou mais suplementos XLL são habilitados.
-   Correção de um problema em que o Excel falha depois de usar o botão Formulários em uma pasta de trabalho já fechada.
-   Correção de um problema em que, ao usar o evento SheetBeforeRightClick, inserir uma coluna que cruza células mescladas não expande as células mescladas.
-   Correção de um problema no qual o Excel trava temporariamente quando você expande ou recolhe uma Tabela Dinâmica, e os cabeçalhos dela se movem para fora da tela.
-   Correção de um problema em que as guias são ignoradas ao copiar e colar um texto delimitado por tabulação do Word, o que resulta na não análise do texto em colunas
-   Correção de um problema no qual o Excel trava ao abrir a caixa de diálogo Publicar como Página da Web.
-   Correção de um problema em que a atualização de dados não funciona ou o Excel falha durante o uso de dados de um servidor SQL Server Analysis Services, e as localidades do Excel e do servidor SQL Server Analysis Services são diferentes.
-   Correção de um problema em que o programa exibe erros ao tentar salvar alterações em documentos sincronizados com o cliente do OneDrive.
-   Correção de um problema em que não é possível fazer alterações na planilha quando há uma Tabela Dinâmica com campos na área do Filtro, mas nenhum campo em outros locais.

### <a name="outlook-feature-updates"></a>Outlook: atualizações de recursos
-   **Melhorias de acessibilidade:** facilitamos a leitura e a edição de textos, tabelas, listas e imagens no email durante o uso de um leitor de tela.
-   **Nova configuração de conta:** configure novas contas com um novo assistente que requer menos etapas manuais.
-   **Caixa de diálogo "Anexar" para links:** ao anexar um link usando o recurso "Anexar Arquivo" na Faixa de Opções, é possível escolher entre adicioná-lo como link ou como anexo. Caso prefira não exibir sempre esta caixa de diálogo, vá para Arquivo \> Opções \> Geral e especifique como deseja anexar os links em "Opções de Anexo".
-   **Suporte para anexos no local:** Os arquivos do SharePoint Server no local são exibidos como arquivos recentes em Mensagem \> Anexar Arquivo, os sites da equipe do OneDrive for Business e do SharePoint no local são exibidos em Anexar Arquivo \> Procurar Locais na Web e os arquivos locais podem ser carregados para os sites do OneDrive for Business no local.
-   **Setor de atividade para grupos:**  Um nível de setor de atividade definido pelo administrador do locatário, como Confidencial, pode ser atribuído ao criar ou ao editar um grupo e esse setor é exibido no cabeçalho do grupo.
-   **Acesso para convidado para Grupos do Office 365:** para colaborar com pessoas de fora da organização, conceda a elas acesso para conversas em grupo, arquivos, convites do calendário e Bloco de Anotações do Grupo. [Mais informações](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Mensagens acionáveis:** os desenvolvedores podem criar mensagens para tornar mais fácil para os usuários a realização de ações simples e rápidas no Outlook, sem ter que mudar para um site externo ou outro aplicativo. [Saiba mais](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: atualizações de segurança
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): vulnerabilidade de bypass do recurso de segurança do Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilidade de corrupção de memória do Microsoft Office Outlook
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): vulnerabilidade de bypass do recurso de segurança do Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office Outlook
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilidade de divulgação não autorizada de informações do Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): vulnerabilidade de execução remota de código do Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilidade de execução remota de código do Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: atualizações não relacionadas à segurança
-   Correção de um problema em que o usuário vê o foco na lista de mensagens saltar inesperadamente ao excluir as mensagens.
-   Correção de um problema que faz com que o usuário veja solicitações de autenticação durante a interação com anexos.
-   Correção de um problema em que o link "Saiba mais" nas Dicas de Políticas não fica visível ao usar o tema Cinza Escuro.
-   Correção de um problema em que o Outlook falha quando o usuário está tentando configurar uma nova conta e fecha a janela sem concluir a configuração da conta.
-   Correção de um problema em que Marcar como Lido e Marcar como Não Lido são exibidos como opções para mensagens na caixa de entrada compartilhada de um grupo.
-   Correção de um problema em que não é possível configurar uma conta IMAP no Outlook.
-   Correção de um problema que causa falhas intermitentes ao abrir o Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: atualizações de recursos
-   **Inserir imagens online:** a nova página de chegada para seleção de imagens e informações de atribuição são inseridas automaticamente com a imagem.
-   **Legendas Codificadas:** adicione Legendas Codificadas a um vídeo para torná-lo mais acessível. [Saiba mais](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Narrar uma gravação:** Inclua vídeo de si mesmo narrando quando fizer uma gravação de uma apresentação. É possível incluir animações, link, áudio e vídeo nas gravações.
-   **Atividade de arquivo compartilhado:** Escolha o botão Atividade, no canto superior direito do arquivo, para ver quando ele foi compartilhado, editado, renomeado ou restaurado no OneDrive for Business ou no SharePoint.
-   **Criação de texto Alt:** um serviço baseado em nuvem gera automaticamente um texto alternativo para as imagens de uma apresentação.
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Melhorias do Designer:** recomenda ideias de design profissionais para listas orientadas para ações.
-   **Alterações em arquivos compartilhados:** veja quem fez alterações em apresentações compartilhadas e restaure versões anteriores. [Saiba mais](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: atualizações de segurança
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): vulnerabilidade de execução remota de código do PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): vulnerabilidade de execução remota de código do PowerPoint
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilidade de divulgação não autorizada de informações do Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: atualizações não relacionadas à segurança
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Correção de um problema em que editar e formatar o texto após desfazer algo em uma tabela faz o PowerPoint falhar.
-   Correção de um problema em que as referências a códigos de inserção do YouTube com base no Flash Player resultam na abertura de uma nova janela para reproduzir o vídeo. Antigos códigos de inserção agora foram atualizados para fazer referência a vídeos do YouTube com base em HTML5 para que possam ser reproduzidos corretamente no lugar.
-   Correção de um problema em que o PowerPoint falha ao abrir uma apresentação de um servidor do SharePoint mais antigo do que o SharePoint Server 2016.
-   Correção de um problema em que ocorre uma falha na exibição dos caracteres definidos pelo usuário final (EUDCs) que estão vinculados às fontes.

### <a name="project-non-security-updates"></a>Project: atualizações não relacionadas à segurança
-   Correção de um problema em que os dados do campo personalizado de nível de projeto podem ser perdidos ao salvar.
-   Correção de um problema em que uma falha no salvamento pode corromper um arquivo e fazer o Project falhar ao abrir.
-   Correção de um problema em que abrir um plano de projeto pode causar uma falha.
-   Correção de um problema no qual abrir determinados arquivos no Project Online faz com que o projeto falhe.
-   Correção de um problema em que o Início Real pode ser limpo por engano ao definir o trabalho restante.
-   Correção de um problema onde a Data de Início Real da Tarefa pode mostrar dados diferentes dos que foram relatados pelo recurso por meio de status no Project Web App.
-   Correção de um problema em que o trabalho real pode ser reprogramado se a data de término da tarefa for alterada.
-   Correção de um problema em que se você copiar e colar os campos de custo, os valores colados podem não corresponder exatamente aos valores copiados devido a um problema de arredondamento.
-   Correção de um problema em que os dados divididos ao longo do tempo para recursos de Orçamento não são copiados quando você salva de uma linha de base para outra.
-   Correção de um problema em que o campo de status nem sempre é calculado corretamente para tarefas de resumo.
-   Correção de um problema em que o trabalho real erroneamente é transferido para um recurso da empresa quando ela substitui um recurso local e o trabalho protegido está habilitado.
-   Correção de um problema em que o projeto trava se você tiver uma tabela cuja primeira coluna é o nome da tarefa, a coluna esteja bloqueada e você clicar em uma tarefa.
-   Correção de um problema em que você pode atribuir o mesmo recurso várias vezes à mesma tarefa por meio do modo de exibição de Uso da Tarefa.
-   Correção de um problema em que os valores contidos nos campos numéricos personalizados podem ser perdidos ao abrir arquivos XML.
-   Correção de um problema em que o recuo de tarefas de nível superior não sincroniza corretamente do Project para uma lista de tarefas do SharePoint.
-   Correção de um problema em que, se você importar tarefas, recursos ou informações sobre atribuição de uma pasta de trabalho no Excel, os valores no campo de trabalho podem ser ignorados.
-   Correção de um problema em que os valores de linha de base divididos em fases não correspondem aos valores iniciais ao salvar um projeto no formato de arquivo XML.
-   Correção de um problema em que o cliente do Project não abre um projeto por julgar que o respectivo check-out já foi feito, quando na verdade não foi.
-   Correção de um problema de modo que seja mais rápido abrir arquivos do Project em um servidor de arquivos com alta latência.

### <a name="skype-for-business-security-updates"></a>Skype for Business: atualizações de segurança
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): vulnerabilidade de divulgação de informações confidenciais do Windows GDI+
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): vulnerabilidade de divulgação de informações de componente do Graphics
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): execução remota de código do componente do Microsoft Graphics

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: atualizações não relacionadas à segurança
-   Adicionar caixa de diálogo explicando por que um usuário não pode ingressar em uma reunião quando certas portas estão bloqueadas ou IPs não são permitidos.
-   Correção de um problema em que as mensagens não lidas em salas de chat persistentes são marcadas como lidas ao clicar nas guias de conversas de mensagens instantâneas.
-   Correção de um problema em que as notificações do sistema de mensagens instantâneas são exibidas com atraso de vários segundos.
-   Correção de um problema em que o contato do AD é exibido como um número de telefone em vez de um nome de contato, quando a sincronização com o Exchange está desabilitada.
-   Correção de um problema em que usuários de ingresso anônimo são impedidos de ingressar quando a federação está desabilitada e o ingresso anônimo não foi bloqueado explicitamente pelo organizador da reunião.
-   Correção de um problema em que o número de convidados é exibido incorretamente para o organizador da reunião, no caso de reuniões que excedem o limite.
-   Correção de um problema em que o número de telefone não é exibido na notificação do sistema, em chamadas PSTN de entrada.
-   Correção de um problema em que, ao usar a tecla Delete para renomear um grupo da lista de contatos, o grupo inteiro é excluído.
-   Correção de um problema em que a notificação de compartilhamento na conversa de mensagem instantânea é ignorada antes da interrupção do compartilhamento.
-   Correção de um problema em que a tela de entrada fica em branco para alguns idiomas diferentes do inglês.
-   Correção de um problema em que os caracteres que não fazem parte da língua inglesa no chat e no histórico do chat apareciam ilegíveis.
-   Exibir o número de telefone do chamador em uma chamada de entrada manipulada pelo Atendedor Automático corporativo, se o nome do usuário for desconhecido.
-   Adição de uma configuração de inband liberando a restrição para "Qualquer pessoa (sem restrições)" como uma opção para "Essas pessoas não precisam aguardar no lobby".
-   Adição da capacidade de exibir ou ocultar a visualização do próprio vídeo para chamadas de vídeo P2P em VDIv2.
-   Correção de um problema em que os números dos contatos são exibidos em duplicado no menu suspenso Telefonar.
-   Correção de um problema em que representantes são removidos por usuários que alternam entre o Skype for Business e o Skype for Business Basic.
-   Correção de um problema em que o item Invisível não é exibido ao usar as políticas de cliente Habilitar Status para Invisível e URL de Estado Personalizado.
-   Ampliação do botão Ingressar na Reunião para corrigir o truncamento de alguns idiomas localizados.
-   Aumentar a importância das mensagens de Alta prioridade nos chats.
-   Adicionar tipos de extensão de arquivo do Office e do Skype for Business a listas de bloqueios de transferência de arquivos permitidos.
-   Correções de localização em convites para reunião do Outlook para Texto do Rodapé de reunião definido em idioma não inglês.
-   Correção de um problema em que é possível alterar os nomes dos remetentes em conversas de vários usuários.
-   Correção de um problema em que há uma falha na exibição da janela de conversa em branco, até que uma reunião seja incluída com êxito.
-   Correção de um problema em que as informações do campo Departamento de um Cartão de Visita aparecem em branco nos resultados de pesquisa, quando o campo Título está em branco.
-   Correção de falhas de entrada para usuários que migraram de ambientes locais para ambientes online devido a regras de firewall.
-   Adição de uma chave de registro DWORD para corrigir um problema em que, quando o usuário entra no cliente por meio de uma rede externa executando o serviço de Descoberta Automática do Lync, o cliente redefine a chave de registro OAuthUsed como falsa. Para corrigir o problema, defina o valor como 1 para EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket, em HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: atualizações de recursos
-   **Criar diagramas de dados do Excel:** Criar automaticamente um Fluxograma Básico ou um Fluxograma Multifuncional de dados do Excel usando novos modelos do Visualizador de Dados. [Mais informações](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: atualizações não relacionadas à segurança
-   Correção de um problema em que os suplementos de COM não recebem eventos de abertura do documento ao abrir um arquivo do Visio clicando duas vezes no respectivo ícone ou nome do arquivo.

### <a name="word-feature-updates"></a>Word: atualizações de recursos
-   **Inserir imagens online:** a nova página de chegada para seleção de imagens e informações de atribuição são inseridas automaticamente com a imagem.
-   **Criação de texto Alt:** um serviço baseado em nuvem gera automaticamente texto alternativo (texto alt) para imagens em um documento.
-   **Atividade de arquivo compartilhado:** Escolha o botão Atividade, no canto superior direito do arquivo, para ver quando ele foi compartilhado, editado, renomeado ou restaurado no OneDrive for Business ou no SharePoint.
-   **Links seguros:** Quando um usuário clica em um link, a ATP (Proteção Avançada contra Ameaças) do Office 365 inspeciona o link para ver se é mal-intencionado. Se o link for considerado mal-intencionado, o usuário será redirecionado para uma página de aviso em vez da URL de destino original. [Mais informações](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Alterações em arquivos compartilhados:** veja quem fez alterações em documentos compartilhados e restaure versões anteriores. [Saiba mais](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-security-updates"></a>Word: atualizações de segurança
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): vulnerabilidade de corrupção de memória do Microsoft Office
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
-   [Supervisão 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): atualização de proteção abrangente do Microsoft Office
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office

### <a name="word-non-security-updates"></a>Word: atualizações não relacionadas à segurança
-   Corrigido um problema em que o Word falha quando um usuário tenta Salvar Como para um documento existente no OneDrive for Business e cancela o salvamento ou tenta mesclar alterações existentes.
-   Correção de um problema em que, ao salvar um arquivo com suporte para sincronização, a gravação em disco falha, mas o Office continua carregando o arquivo para o OneDrive. Com esta correção, os usuários passam a receber uma mensagem de erro e o carregamento é interrompido.
-   Correção de um problema em que o Word pode desligar se o usuário navegar para a guia Inserir logo após abrir o Word.
-   Correção de um problema em que, depois de clicar na margem, os caracteres são exibidos no canto superior esquerdo da tela ao inserir caracteres.
-   Correção de um problema em que o Word falha ao abrir o painel Atividade de um documento aberto em um servidor do SharePoint mais antigo do que o SharePoint Server 2016.
-   Correção de um problema em que o Word fecha inesperadamente ao carregar o suplemento Grammarly.
-   Correção de um problema em que, em determinadas condições, o Word falha ao tentar recuperar arquivos baseados na nuvem.
-   Correção de um problema em que não é possível girar formas dentro da tela de desenho.
-   Correção de um problema em que, ao digitar em coreano, as consoantes e vogais são separadas de forma incorreta.
-   Ao salvar um documento em PDF, ele é salvo na versão 1.7 do PDF.

### <a name="office-suite-security-updates"></a>Pacote do Office: atualizações de segurança
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Vulnerabilidade de execução remota de código do Microsoft Office
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Vulnerabilidade de corrupção de memória do Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Vulnerabilidade de execução remota de código do Microsoft Office
-   [Supervisão 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): atualização de Proteção Abrangente do Microsoft Office

### <a name="office-suite-non-security-updates"></a>Pacote do Office: atualizações não relacionadas à segurança
-   Adição de suporte para logon único (SSO) para usuários do domínio de planos do Office 365 Germany em que a identidade for federada com um Active Directory local.
-   Adição de funcionalidade para evitar que menores de idade comprem e ativem suplementos do Office provenientes da Office Store.
-   Correção de um problema com o zoom e dimensionamento em suplementos do Office em um ambiente de DPI dinâmico.
-   Correção de um problema em que o nó CurrentStatus do provedor de serviços de configuração (CSP) do Office retorna uma cadeia de caracteres vazia mesmo se o Office 365 ProPlus estiver instalado atualmente.
-   Correção de um problema que causa mudanças de formato no arquivo .box, o que afeta a funcionalidade de versões mais antigas do Office instaladas no mesmo computador, porque os arquivos .box são compartilhados entre todas as versões de um aplicativo do Office no mesmo computador.
-   Correção de um problema em que, em determinadas circunstâncias ao usar a ativação de computador compartilhado, uma mensagem de erro é exibida informando que o aplicativo encontrou um erro que o está impedindo de funcionar corretamente e perguntando se o usuário deseja executar um reparo.
-   Correção de um problema em que o progresso de Reparo Online não é exibido ao usuário.
-   Correção de um problema em que as propriedades de arquivo do Office não são exibidas no Explorador de Arquivos.
-   Correção de um problema em que os botões de suplemento do Office desaparecem da faixa de opções quando há um segundo documento aberto.
-   Correção de um problema em que alguns módulos de VBA com nomes com caracteres de dois bytes não podem ser abertos.
-   Correção de um problema que impede que a caixa de diálogo Novidades seja exibida.
-   Correção de um problema em que o aplicativo falha para alguns usuários ao clicar na guia Desenhar.
-   Correção de um problema em que o aplicativo falha ao passar o cursor sobre um Controle Comum que contém uma dica de ferramenta.
-   Correção de um problema em que um Erro de Licenciamento é exibido ao usar Controles Comuns.
-   Correção de um problema relacionado à maneira pela qual alguns arquivos de programas são conectados fazendo com que programas antivírus sinalizem esses arquivos, além de problemas para proteger ou acessar dados no WIP (Proteção de Informações do Windows).
-   Adição de suporte para permitir que os usuários que trabalham em versões de 64 bits do Office abram arquivos de macro contendo controles mscomctl.ocx.
-   Melhoria de acessibilidade dos controles usados no mscomctl.ocx.
-   Correção de um problema em que os comandos estão ausentes das caixas de diálogo Personalizar Faixa de Opções ou Personalizar a Barra de Ferramentas de Acesso Rápido.



## <a name="version-1705-january-9"></a>Versão 1705: 9 de janeiro
*Versão 1705 (build 8201.2217)*

*Este é o lançamento do Canal Adiado que está disponível desde setembro de 2017. Ele continuará com suporte e receberá atualizações de segurança até julho de 2018. No entanto, já está disponível um novo lançamento do Canal Semestral, a versão 1708 (build 8431.2153), que contém novos recursos, atualizações de segurança e outras atualizações não relacionadas à segurança*.

### <a name="excel-security-updates"></a>Excel: atualizações de segurança
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilidade de execução remota de código do Microsoft Excel
-   [Supervisão 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): atualização de proteção abrangente do Microsoft Office

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


> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).
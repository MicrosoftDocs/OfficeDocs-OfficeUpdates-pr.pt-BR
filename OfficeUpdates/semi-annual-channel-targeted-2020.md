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
description: Fornece aos profissionais de TI notas de versão dos lançamentos do canal semestral (direcionado) dos aplicativos do Microsoft 365 em 2020
ms.openlocfilehash: 5c9535a000544238e1c68eee98817eb52d12449c
ms.sourcegitcommit: beff319f87f2fbecd15468f3ffa9bb99416ed165
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714686"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>Notas de versão para lançamentos do Canal Semestral (Direcionado) em 2020

Essas notas de versão fornecem informações dos novos recursos e atualizações não relacionadas à segurança incluídas nas atualizações de Canal semestral (Direcionado) em 2020 do Microsoft 365 Apps para empresas, Microsoft 365 Apps para negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.

> [!NOTE]
>
> - Muitas vezes disponibilizamos recursos (e, às vezes, até mesmo correções) para o Canal Semestral (direcionado) durante um período de tempo. Se você não encontrar imediatamente algo descrito abaixo, aguarde que muito em breve estará disponível. [Saiba mais](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)


## <a name="version-2002-april-14"></a>Versão 2002: 14 de abril
*Versão 2002 (Build 12527.20442)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Digite uma fórmula que retorna vários valores:** digite rapidamente uma fórmula que retorna vários valores e eles serão enviados para as células vizinhas automaticamente. [Saiba mais](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Seis funções avançadas:** adicionamos seis novas funções para turbinar suas planilhas: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.  [Saiba mais](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!** Linha por linha, encontre tudo o que precisa em uma tabela ou intervalo com XLOOKUP.  [Saiba mais](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- O Excel falharia em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.

- Ao salvar como um arquivo CSV, o Excel poderia mesclar todas as colunas em uma única coluna em alguns casos.

- Usar Range.ClearContents em um intervalo de uma planilha protegida pode levar mais tempo do que o esperado.

- Foi corrigido um problema com a escala de texto em controles de formulário quando exibido na Visualização de Impressão.

- As macros do VBA que interagem com a faixa de opções podem ser executadas com o conjunto de ScreenUpdating definido como Verdadeiro inesperadamente.

- Foi solucionado um problema em que os links externos não eram atualizados durante o preenchimento (preencher abaixo, preencher entre, etc.) se o livro de origem estivesse fechado.

- Em alguns casos, o uso do Application.Evaluate do VBA não funcionava para funções definidas pelo usuário.

- Solucionamos um problema de desempenho durante a criação de gráficos de modelos.


### <a name="outlook"></a>Outlook

- Foi solucionado um problema que fazia com que o Título do Grupo se expandisse inesperadamente em alguns cenários.

- Foi resolvido um problema que fazia com que os usuários experimentassem uma falha ao selecionar determinados resultados de pesquisa.

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.

- Foi solucionado um problema que fazia com que o botão Salvar na nuvem estivesse ausente nas Ferramentas de anexo.


### <a name="powerpoint"></a>PowerPoint

- Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-lo em outro slide em um loop.


### <a name="project"></a>Project

- Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.

- Correção de um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.

### <a name="word"></a>Word

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao usar o botão X no mouse.

- Corrigimos um problema com o ajuste de texto em uma tabela.

- Corrigimos um problema em que não era possível inserir linhas horizontais e centralizar.



[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-10"></a>Versão 2002: 10 de março
*Versão 2002 (Build 12527.20278)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Localizar tabelas vinculadas rapidamente** Nossa nova caixa de pesquisa facilita a localização de tabelas vinculadas. [Saiba mais](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Chame a atenção com \@menções**: use @menções nos comentários para informar a seus colegas de trabalho quando precisar da opinião deles. [Saiba Mais](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Encontre o que está procurando:** Pesquise comandos, pessoas, arquivos, fotos, artigos da Web e muito mais. [Saiba mais](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Faça um Esboço:** Deixe as formas do Office da sua pasta de trabalho com uma aparência casual de desenhado à mão. [Saiba Mais](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Foco no que precisa ser feito:** Selecione Resolver para recolher comentários e dar destaque aos itens abertos.

- **Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar. [Saiba mais](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.

- **Suplemento visualizador de dados:** cria rapidamente fluxogramas do Visio a partir do Excel. [Saiba Mais](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Leia e responda instantaneamente:** Responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.

- **Obtenha estatísticas em sua pasta de trabalho:** As Estatísticas da Pasta de Trabalho fornecem uma visão geral do conteúdo de uma pasta de trabalho, para ajudar você a descobrir o conteúdo com mais facilidade.

- **Salvar formas como imagens:** em apenas alguns cliques, salve uma forma, ícone ou outro objeto como arquivo de imagem para reutilizá-lo em outro lugar. [Saiba mais](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



### <a name="outlook"></a>Outlook



- **Conecte sua rede do LinkedIn ao Outlook:** Conecte sua conta do LinkedIn com segurança à sua conta da Microsoft para ver informações de perfis do LinkedIn diretamente no cartão de Pessoas. [Saiba Mais](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Todas as opções de criptografia em um só lugar:** Basta ir para Opções > Criptografar para escolher como proteger sua mensagem de email. [Saiba mais](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **O menu Inserir Link no Outlook inserirá um link com a permissão definida pelo administrador do locatário:** um link do Inserir Link MRU no Outlook insere um link que só funcionou para usuários que já tinham permissões. Isso causou uma troca de emails frequente entre os usuários solicitando o acesso a um documento. Atualizamos essa experiência e agora o link é inserido com a permissão padrão definida pelo administrador do locatário. No MSIT, é "A organização pode editar", para que todos os usuários internos que recebem um link compartilhado dessa maneira possam acessá-lo.

- **Pesquisar com erros de ortografia ou digitação:** O Outlook encontrará o que você está procurando, mesmo quando a ortografia não corresponder.

- **Emails de phishing fáceis de identificar:** As mensagens de spam e phishing têm uma aparência diferente, para que você possa identificá-las e eliminá-las facilmente na caixa de entrada.

- **Proteção avançada contra ataque:** com a proteção avançada contra ameaças do Office 365, você está protegido contra ataques por meio de hiperlinks dentro de assuntos de email, mensagens anexadas, mensagens assinadas, caminhos de rede e assim por diante.

- **Deixe-me desenhar:** Rabisque em fotos ou adicione uma Tela de Desenho para enviar seus pensamentos com tinta. [Saiba Mais](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Veja as mensagens relevantes nos resultados de pesquisa:** o Outlook analisa os termos de pesquisa e mostra as mensagens de email mais relevantes na parte superior dos resultados da pesquisa. Você também verá todos os resultados classificados por data, na seção Resultados Principais. [Saiba Mais](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **Obtenha sugestões de locais:** comece a digitar em Local ao agendar compromissos e reuniões, e o Outlook irá sugerir salas, endereços e outros locais recentes. [Saiba Mais](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Por mais mensagens na tela:** Selecione Exibir > Usar Espaçamento Apertado para ajustar o espaçamento entre as mensagens. [Saiba Mais](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Veja suas mensagens sob uma perspectiva diferente:** use o botão Sol/Lua para alternar entre planos de fundo claros e escuros no painel de leitura. [Saiba mais](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)



### <a name="powerpoint"></a>PowerPoint

- **Colaboração rápida e em tempo real no PowerPoint:** Colaboração rápida e em tempo real no PowerPoint

- **Novas ferramentas de revisão:** não se preocupe com suas palavras. Agora, o PowerPoint fornece sugestões de gramática e ortografia. [Saiba mais](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- **Legendas em tempo real:** As palavras do apresentador aparecem na tela automaticamente como legendas ou traduzidas para o idioma que escolher. [Saiba Mais](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Você calcula, nós formatamos:** Nós trocamos expressões matemáticas difíceis de desenhar por caracteres padrão. Basta escolher Tinta para Matemática e selecionar suas anotações manuscritas para começar.[Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais. [Saiba mais](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Localize e corrija títulos de slides ausentes:** Títulos de slides reforçam o seu discurso e tornam os seus slides acessíveis a usuários de todas as habilidades. O Verificador de Acessibilidade mostra onde os títulos estão ausentes para que você possa adicioná-los imediatamente. [Saiba Mais](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Faça um Esboço:** deixe as formas do Office da sua apresentação com uma aparência casual de desenhado à mão. [Saiba Mais](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Salve uma ilustração como SVG:** salve um gráfico, uma forma ou outra ilustração como um gráfico vetorial escalonável, que pode ser redimensionado sem perder a qualidade da imagem. [Saiba Mais](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Imprimir números de slide em folhetos:** os números de slide são incluídos automaticamente nos folhetos. Deixá-los ou não ativados depende de você. [Saiba Mais](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Repe-tinta-ção Instantânea:** Ao escrever à tinta nos slides, aplique uma animação de repetição para reproduzir o desenho real da sua tinta durante a apresentação de slides. [Saiba mais](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar.

- **Otimize sua apresentação para todos:** O Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.

- **Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você.

- **Por que reinventa quando você pode reutilizar?:** poupar tempo usando novamente slides que você criou ou que outras pessoas compartilharam com você. [Saiba mais](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **Transforme tinta manuscrita em formas, texto ou expressões matemáticas no PowerPoint para Office 365:** Vá de tinta de forma livre para formas, texto ou uma expressão matemática com apenas alguns traços. [Saiba mais](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Pintar um slide esplêndido:** converta sua tinta para texto e formas padrão e obtenha ideias inteligentes de design de slides do Designer do PowerPoint. [Saiba mais](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

### <a name="visio"></a>Visio

- **Voltando para a cena do crime:** Use os novos estênceis de Evidência, Interno e Externo no modelo de Investigação de Cena de Crime para recriar cenas de crimes em detalhes.

- **Crie diagramas elegantes do Visio no Excel:** Crie um fluxograma ou organograma da organização colocando os dados em uma planilha. [Saiba Mais](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **O Editor de Currículos se une ao Assistente de Currículos do LinkedIn:** O Editor de Currículos oferece uma seleção de verificações gramaticais e de estilo especialmente adaptadas para currículos, para tornar a sua escrita mais precisa e profissional.

- **Corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D:** corrigido um problema de corrupção de documento causado pela mesclagem de objetos 3D.

- **Encontre o que está procurando:** Use a caixa de pesquisa para localizar texto, comandos, ajuda e muito mais. [Saiba Mais](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Colabore em cores:** Comentários e alterações são codificados por cores por colaborador, para que seja fácil ver quem está entre seus colaboradores.

- **Edite documentos habilitados para macro de maneira colaborativa:** Salve arquivos docm no OneDrive for Business e edite-os com seus colaboradores em tempo real.

- **Aperfeiçoamentos de coautoria**: melhor desempenho do Word durante a coautoria em documentos com alterações controladas.

- **Mais ícones para corresponder ao seu humor:** Adicionamos mais de 300 novos ícones. Encontre-os em Inserir > Ícones. [Saiba Mais](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.

- **Faça um Esboço:** deixe as formas do Office do seu documento com uma aparência casual de desenhado à mão. [Saiba Mais](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Apagar com precisão:** Escolha entre dois tamanhos de borracha para corrigir pequenas imperfeições à tinta. [Saiba Mais](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Compartilhamento rápido de arquivo**: Compartilhe os seus documentos diretamente da lista usada recentemente sem ter que abrir o arquivo.

- **Não é mais necessário voltar ao navegador:** Você decide como os links para documentos do Office são abertos: no navegador ou no aplicativo.

- **Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.

- **Melhorias na coautoria** Confiabilidade aprimorada durante a coautoria.

- **Criar PDFs mais acessíveis:** crie um PDF e o verificador de acessibilidade informará os problemas de acessibilidade para corrigir antes de salvar. [Saiba mais](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Converta arquivos para melhorar a acessibilidade:** atualize seus arquivos para o formato moderno para torná-los mais acessíveis para todas as pessoas.

- **Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você. [Saiba mais](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Salvar formas como imagens:** em apenas alguns cliques, salve uma forma, ícone ou outro objeto como arquivo de imagem para reutilizá-lo em outro lugar. [Saiba mais](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esta atualização corrige um problema no Microsoft Access que pode causar o erro &quot;A consulta está corrompida&quot; quando uma Consulta Atualização é executada ou uma instrução UPDATE é usada em SQL.

- Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.

- Esta atualização corrige um problema no uso de um ADODB. O objeto gravador no código VB pode incorretamente relatar um erro.

- Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados. Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.

### <a name="excel"></a>Excel

- Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

- Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.

- Esta atualização corrige um problema que fazia com que barra de fórmulas exibisse texto em uma fonte diferente da esperada.

- A funcionalidade Texto em Coluna pode falhar para algumas localidades.

- Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.

- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.

- Resolvido um problema em que a seleção de uma célula após a rolagem poderia resultar na seleção da célula errada.

- O Excel pode apresentar problemas ao editar um arquivo protegido a partir de um compartilhamento de rede não confiável.

- A funcionalidade Texto em Coluna pode falhar em algumas localizações.

- Os usuários podem encontrar um erro ao acessar um intervalo nomeado oculto.

- Os usuários podem encontrar um erro ao salvar as alterações enquanto usam alguns conjuntos de caracteres que não estão em inglês.

- Foi corrigido um problema que alguns usuários podem ter tido com objetos inseridos e vinculados (OLE).

- Corrigimos o menu do botão direito do mouse de Gráficos Dinâmicos para habilitar a opção Mostrar Detalhes.

- Corrigimos um problema que pode ter causado uma falha ao procurar arquivos recentes quando a pasta de trabalho não está aberta.

- Foi corrigido um problema em que alguns usuários podem ter experienciado várias janelas pop-up quando havia links externos na pasta de trabalho.

- Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.

- Resolvido um problema com a personalização da faixa de opções que não carregava ao abrir a pasta de trabalho inserida.

- Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.

### <a name="outlook"></a>Outlook

- Corrigido um problema que causava um travamento na experiência de Comentários de Pesquisa.

- Solucionamos um problema que fazia com que os usuários experimentassem travamentos no Outlook ao recuperar as configurações da Nuvem.

- Foi corrigido um problema que provocava um alinhamento inadequado da caixa de pesquisa no modo de DPI alto.

- Corrigido um problema que fazia com que usuários observassem um vazamento de memória no processo do Outlook.

- Solucionamos um problema que fazia com que os usuários vissem os e-mails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.

- Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.

- Consertamos um problema que podia impedir que os arquivos fossem salvos em um local do WebDAV.

- Corrigido um problema com a seleção de algoritmo SMIME.

- Solucionamos um problema que fazia com que aplicativos de terceiros não conseguissem enviar emails.

- Corrigido um problema que fazia com que os usuários vissem uma caixa de mensagem vazia com um botão &quot;OK&quot; ao tentar contatar o suporte do contexto de Criação de Conta.

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.

- Solucionamos um problema que fazia o Outlook sincronizar inesperadamente todos os emails, mesmo quando o controle deslizante de sincronização estivesse definido com uma configuração menor.

- Solucionamos um problema que fazia com que a suspensa &quot;De&quot; mostrasse texto branco em um fundo branco para usuários com o Tema Preto.

- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.

- Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.

- Solucionado um problema que fazia com que a opção desativar o realce do item sinalizado deixasse de ser respeitada em alguns cenários.

- Solucionamos um problema que fazia com que usuários vissem um prompt &quot;As regras neste computador não correspondem às regras no Microsoft Exchange&quot; ao abrir a caixa de diálogo de Regras.

- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.

- Resolvido um problema que causou um vazamento de memória em sessões muito longas do Outlook.

- Solucionamos um problema que podia resultar em uma falha ao exibir o mesmo item em várias janelas.

- Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.

- Solucionamos um problema que fazia com que os usuários não conseguissem abrir algumas instâncias de itens de calendário recorrentes.

- Solucionamos um problema que fazia com que os usuários com caixas de correio em servidores do Exchange 2010 tivessem problemas ao adicionar anexos a itens de calendário.

- Solucionamos um problema que fazia com que os usuários tivessem problemas ao responder a mensagens assinadas digitalmente.

- Corrigimos um problema que fazia com que o campo Local nas reuniões fosse atualizado inesperadamente.

- Solucionamos um problema que fazia com que as vírgulas no campo de local de uma reunião se transformassem em pontos-e-vírgulas.

- Solucionamos um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após a limpeza.

- Solucionamos problemas relacionados a reuniões e compromissos no fuso horário de Brasília.

- Foi corrigido um problema que fazia com que emails fossem enviados inesperadamente ao pressionar a tecla &quot;S&quot; após fechar o painel do verificador de acessibilidade.

- Isso atualiza a lógica de bloqueio de anexos no Outlook para também bloquear anexos de python.

- Solucionamos um problema que fazia com que suplementos da Web acessassem mensagens com Gerenciamento de Direitos Digitais.

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha durante a criação do perfil.

- Solucionamos um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.

### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema com o método Shape.Paste: quando o usuário copia e cola a forma usando o método Shape.Paste ele altera a seleção para a forma colada.

- Solucionamos um problema que pode ter causado uma falha ao usar o menu de contexto em comentários de PPT herdados.

### <a name="project"></a>Projeto

- Identificado um problema em que os usuários podiam receber várias mensagens ao abrir um projeto somente leitura.

- Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.

- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.

- Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.

### <a name="word"></a>Word

- Corrigimos um problema em que, em alguns casos, ao tentar salvar um arquivo existente a caixa de diálogo Salvar Como aparecia e o arquivo nunca era realmente salvo.

- O organizador de blocos de construção pode exibir um alerta inválido: &quot;Você modificou estilos, blocos de construção&quot;.

### <a name="office-suite"></a>Pacote do Office

- Essa alteração corrige a renderização lenta de alguns gráficos de dispersão com marcadores.

- Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.

- Correção de um bug na configuração de Data Limite de Atualização ODT e GPO, em que o prazo relativo só funcionava na primeira vez que era definido. A correção permite definir a data limite relativa nas atualizações subsequentes.

- Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.

- Foi corrigido um problema em que, quando vários documentos da mesma biblioteca do SharePoint estivessem abertos no Word/Excel/PowerPoint, somente o primeiro documento aberto era verificado quanto à conformidade com Políticas.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-1908-february-11"></a>Versão 1908: 11 de fevereiro
*Versão 1908 (Build 11929.20606)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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

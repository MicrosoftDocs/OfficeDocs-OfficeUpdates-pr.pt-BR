---
title: Notas de versão para os lançamentos do Canal Corporativo Mensal em 2020
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI as notas de versão para o Canal Corporativo Mensal dos Aplicativos do Microsoft 365 em 2020
ms.openlocfilehash: 44a77260e0e674eccf53a76a0a451a3bfa2d7566
ms.sourcegitcommit: 244f8fded28adafd66397baee0418254db5c9de2
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/10/2020
ms.locfileid: "49623122"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>Notas de versão para os lançamentos do Canal Corporativo Mensal em 2020

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionadas à segurança que estão inclusos em atualizações mensais do Canal Corporativo Mensal em 2020 para Microsoft 365 Apps para Grandes Empresas, Microsoft 365 Apps para Pequenos e Médios negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.

> [!IMPORTANT]
> Estamos fazendo algumas alterações nos canais de atualização para os aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes. Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

[//]: # (NÃO REMOVA)



## <a name="version-2010-december-08"></a>Versão 2010: 8 de dezembro
*Versão 2010 (Build 13328.20478)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Obtenha Dados da Organização com o Power BI usando Tipos de Dados:** Os tipos de dados do Excel no Power BI agora estão sendo disponibilizados para os participantes do programa Office Insider em organizações com o Office 365 E5/A5 ou o Microsoft 365 E5/A5. Obter as informações necessárias e atualizá-las facilmente é fundamental para muitos fluxos de trabalho diários. Estamos oferecendo acesso às informações da sua empresa ou organização a partir do Power BI como tipo de dados no Excel, o amplia a capacidade de inserir informações vinculadas nas suas planilhas.

### <a name="outlook"></a>Outlook

- **Atualizações da Experiência do Usuário para Tasks:** Uma atualização visual dos itens de tarefa

- **Links aprimorados no email:** quando você incluir um link a um arquivo, o nome do arquivo substituirá a URL. Você pode alterar as permissões para que todos os destinatários tenham acesso.

### <a name="powerpoint"></a>PowerPoint

- **Exportar GIF animado em um intervalo:** selecione um intervalo de slides ao exportar para GIF animado

- **Crie GIFs com telas de fundo transparentes:** Ao exportar para um GIF animado, uma nova opção permitirá que você torne a tela de fundo transparente.<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Corrigimos um problema em que ao usar o DAO em aplicativos não pertencentes ao Office fazia com que o aplicativo fechasse inesperadamente.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que o Outlook criasse uma segunda assinatura vazia para pessoas que estavam com as configurações de nuvem ativadas.


- Corrigimos um problema que fazia com que as configurações de nuvem não fossem ativadas para os usuários por padrão.


- Corrigimos um problema que fazia com que as alterações na assinatura de um usuário não fossem salvas.


- Corrigimos um problema que tornava os cabeçalhos das mensagens em chinês ilegíveis ao responder ou encaminhar.


- Corrigimos um problema que fazia com que os caracteres chineses fossem alterados para pontos de interrogação ao salvar como um arquivo OFT.


- Adicionamos uma regkey que permite que os clientes desabilitem a inclusão de filetime para anexos nas operações do IDataObject (ou seja, arrastar e soltar, área de transferência).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.  REG_DWORD IncludeFileTimesInDataObject.  0 = filetimes são excluídos.  1 = (padrão) filetimes são incluídos.


- Corrigimos um problema que causava a interrupção do evento MailItem.BeforeAttachmentAdd.


- Corrigimos um problema que fazia com que os participantes originais de algumas reuniões fossem cancelados quando outro participante encaminhava a reunião.


- Corrigimos um problema que impedia os usuários de conceder permissão de Editor aos seus delegados.


### <a name="powerpoint"></a>PowerPoint

- Esta é uma correção para um problema em que o prompt de salvamento mostra em um loop ao fechar o documento quando há um suplemento que escuta o evento PresentationBeforeClose e verifica a propriedade Presentation.Saved como parte do manipulador de eventos.


- Correção para resolver um problema ao usar documentos IRM/protegidos durante um erro de mesclagem.


- Correção de um problema com a cópia/colagem de uma equação do Word para o PowerPoint.


### <a name="project"></a>Microsoft Project

- Corrigido um problema onde o Project podia terminar inesperadamente ao abrir arquivos onde os contornos dos recursos foram especificados de uma determinada maneira.


- Corrigido um problema em que, ao salvar um projeto do PWA em um arquivo mpp local, o ProjectBeforeTaskChangeEvent disparava para dados que não foram realmente alterados pelo usuário.


- Corrigido um problema em que o NewVal no evento ProjectBeforeTaskChange não tinha o valor correto se um atraso fosse alterado em uma exibição do tipo Formulário de Tarefa.


### <a name="visio"></a>Visio

- Corrigimos um problema em que os usuários poderão criar linhas retas usando conectores no Visio para Office 365 para estênceis personalizados do Visio e modelos internos.


### <a name="word"></a>Word

- Correção de um problema com a cópia/colagem de uma equação do Word para o PowerPoint.


### <a name="office-suite"></a>Pacote Office

- Corrigido um problema em que a prevenção contra perda de dados do ponto de extremidade do Microsoft 365 não conseguia classificar os documentos do Office no disco.


- Quando o usuário imprime qualquer documento/arquivo em impressoras jato de tinta do Office e a tinta da impressora está baixa, a mensagem "Pouco toner" ou "Sem toner" será exibida, mesmo que as impressoras jato de tinta não tenham toners. Alterar a mensagem para exibir "Pouco(a) toner/tinta" e "Sem toner/tinta".


- Correção de um problema em que ocorre um erro ao copiar/colar texto de um comentário para o Excel.


- Corrigido um problema em que ao tentar SalvarComo falhava em determinados cenários.


- Corrigimos um problema que estava causando uma falha ao tentar salvar arquivos que passaram de sincronizados para somente servidor.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2009-december-08"></a>Versão 2009: 8 de dezembro
*Versão 2009 (Build 13231.20620)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2009-november-10"></a>Versão 2009: 10 de novembro
*Versão 2009 (Build 13231.20514)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.

### <a name="powerpoint"></a>PowerPoint

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.

### <a name="word"></a>Word

- **Aplicar automaticamente ou recomendar rótulos de confidencialidade:** O Office pode recomendar ou aplicar automaticamente um rótulo de confidencialidade com base no conteúdo confidencial detectado.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Corrigimos um problema que tornava os cabeçalhos das mensagens em Chinês ilegíveis ao responder ou encaminhar.


- Resolvido um problema que fazia com que os delegados vissem falhas intermitentes ao abrir pastas compartilhadas em outra caixa de correio.


- Resolvido um problema que fazia com que alguns emails gerados automaticamente fossem enviados com um corpo em branco quando a linha de assunto estava em branco.


- Resolvido um problema que causava com que alguns usuários observassem o Outlook iniciando inesperadamente em um estado offline.


- Resolvido um problema que fazia com que a Pesquisa não retornasse nenhum resultado ao pesquisar calendários compartilhados não armazenados em cache.


- Corrigimos um problema que fazia com que os usuários experimentassem o aplicativo encerrar inesperadamente ao selecionar um resultado de pesquisa.


- Corrigimos um problema que impedia os usuários de conceder permissão de Editor a seus delegados.


### <a name="powerpoint"></a>PowerPoint

- Correção de um problema que causa a coautoria em arquivos que contêm grandes números de um determinado tipo de objeto de dados (E2o).


- Corrigimos um problema que desabilitava as proteções IRM ao abrir um arquivo do PowerPoint no Modo de Exibição Protegido.


- Corrigimos um problema em que o suplemento de conteúdo do Microsoft Forms não renderiza após a inserção até que o usuário clique em outro slide para mostrá-lo.


### <a name="project"></a>Project

- Correção de um problema em que, se você tiver um código de eventos em execução e tentar fazer alterações por meio de um modo de exibição Formulário de Tarefas, clicar no botão OK pode não confirmar as alterações.


- Corrigido um problema onde o Project podia terminar inesperadamente ao abrir arquivos onde os contornos dos recursos foram especificados de uma determinada maneira.


- Corrigido um problema em que, ao salvar um projeto do PWA em um arquivo mpp local, o ProjectBeforeTaskChangeEvent disparava para dados que não foram realmente alterados pelo usuário.


### <a name="word"></a>Word

- Corrigimos um problema com a caixa de diálogo Galeria de Estilos.


### <a name="office-suite"></a>Pacote Office

- Corrigimos um problema com a caixa de diálogo Compactar Imagem, que não mantinha certas configurações do usuário.


- Corrigido um problema em que a prevenção contra perda de dados do Ponto de extremidade do Microsoft 365 não conseguia classificar os documentos do Office no disco.


- Quando o usuário imprime qualquer documento/arquivo em impressoras jato de tinta do Office e a tinta da impressora está baixa, a mensagem "Pouco toner" ou "Sem toner" será exibida, mesmo que as impressoras jato de tinta não tenham toners. Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2008-november-10"></a>Versão 2008: 10 de novembro
*Versão 2008 (Build 13127.20760)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um problema onde usando um macro para definir a propriedade FormulaR1C1 para um intervalo, as referências de células estariam incorretas se uma planilha de gráfico fosse a planilha ativa. 


- Corrigido um problema que poderia causar um erro de que "Excel esgotou os recursos ao tentar calcular uma ou mais fórmulas".


- Corrigido um problema que ocorria quando o idioma do Office era definido como espanhol, no qual as listas de validação de dados não mostravam todos os itens na lista.


- Corrigimos um problema que poderia causar um travamento ao atualizar as tabelas dinâmicas OLAP.


- Corrigimos um problema em que certas funções apresentavam resultados incorretos após o carregamento de uma pasta de trabalho.


- Corrigimos um problema onde o aplicativo fechava inesperadamente, o que estava relacionado a referências do suplemento XLAM e intervalos nomeados.

### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que os cabeçalhos das mensagens em Chinês ficassem distorcidos ao responder ou encaminhar.


- Resolvido um problema que fazia com que alguns emails gerados automaticamente fossem enviados com um corpo em branco quando a linha de assunto estava em branco.


- Resolvido um problema que fazia com que os delegados vissem falhas intermitentes ao abrir pastas compartilhadas em outra caixa de correio.


- Corrigimos um problema que fazia com que as pesquisas nos calendários do Grupo não retornassem nenhum resultado.


- Corrigimos um problema que fazia com que os usuários experimentassem o aplicativo encerrar inesperadamente ao selecionar um resultado de pesquisa.


- Corrigimos um problema onde os usuários podem agora desabilitar o IRM (Gerenciamento de Direitos de Informação) para o Outlook sem ter que desabilitá-lo para o resto das aplicações do Office.


- Corrigimos um problema que impedia os usuários de conceder permissão de Editor a seus delegados.


- Corrigimos um problema em que experiências conectadas opcionais impediam o carregamento de suplementos da web.<br />Consulte os detalhes na [postagem do blog](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)


### <a name="powerpoint"></a>PowerPoint

- Esta é uma correção para um problema em que o prompt de salvamento mostra em um loop ao fechar o documento quando há um suplemento que escuta o evento PresentationBeforeClose e verifica a propriedade Presentation.Saved como parte do manipulador de eventos.


- Corrigimos um problema em que o suplemento de conteúdo do Microsoft Forms não processa após a inserção até que o usuário clique em outro slide para mostrá-lo.


### <a name="office-suite"></a>Pacote do Office

- Resolvido um problema para clientes comerciais que utilizam o Centro do Sistema de Gerenciador de Configurações ou outra ferramenta de gerenciamento para o Atualização do Office usando a prevenção contra perda de dados do Ponto de extremidade do Microsoft 365.

- Corrigido um problema de que a API de Mensagens para suplementos do Office não está funcionando.



[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DOS DETALHES DO BUG)

## <a name="version-2008-october-13"></a>Versão 2008: 13 de outubro
*Versão 2008 (Compilação 13127.20638)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Tem alguma pergunta? Pergunte ao Excel:** Agora o Excel ideias permite que você faça perguntas sobre seus dados. não é necessário gastar horas de escrita (disponível somente em inglês). [Saiba mais](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.  Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo. Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar. Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint. [Saiba mais](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **Fazer uma conexão em PDF:** Conectar, importar, atualizar dados de um PDF. [Saiba mais](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Salvar formas como imagens:** em apenas alguns cliques, salve uma forma, ícone ou outro objeto como arquivo de imagem para reutilizá-lo em outro lugar. [Saiba Mais](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook

- **Criar pesquisas no Outlook com a Pesquisa Rápida:** criar facilmente uma votação, coletar votos e exibir resultados em um email [Saiba mais](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Novo cartão de perfil do Outlook:** Novo cartão de perfil do Outlook, incluindo uma melhor visão da Organização e correspondência ao estilo de cartão do Outlook Web. [Saiba mais](https://support.office.com/article/e80f931f-5fc4-4a59-ba6e-c1e35a85b501)

### <a name="powerpoint"></a>PowerPoint

- **Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.  Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo. Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar. Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint. [Saiba mais](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Salvar nas Pastas Fixadas:** Fixar suas pastas facilita o salvamento dos arquivos do Office.  Recebemos comentários que os usuários desejam ter mais controle sobre as pastas disponíveis quando um novo arquivo é salvo. Estamos animados para apresentar um novo recurso para você: fixar suas pastas na caixa de diálogo Salvar. Esse novo recurso facilita o salvamento dos arquivos do Word, do Excel e do PowerPoint. [Saiba mais](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acesso

- Este problema foi resolvido - agora você pode usar nosso driver ODBC fora das aplicações de Clicar para Executar do Office.


- Essa alteração corrige um problema que poderia fazer com que Access falhasse ao lançar a caixa Zoom (Shift + F2) para editar texto.


- Esse problema foi resolvido e você não deve mais experimentar um travamento.


### <a name="excel"></a>Excel

- Resolvemos um problema que poderia causar um aviso sobre uma pasta de trabalho corrompida se contivesse fórmulas usando IFNA().


- Resolvemos um problema em que o Excel poderia falhar ao usar a Análise Rápida após congelar a linha superior da planilha.


- Resolvemos um problema no qual os usuários não conseguiam modificar um filtro PivotTable porque ele estava definido com um valor que não estava mais presente em um banco de dados do Analysis Services.


- Resolvemos um problema em que o Excel poderia falhar em determinadas circunstâncias ao usar o Pincel de Formatação.


- Corrigimos um bug com APIs PivotDateFilter nas quais as condições de filtragem 'Antes' e 'Depois' eram invertidas.


### <a name="outlook"></a>Outlook

- Aborda um problema que fez com que os usuários recebessem o seguinte erro ao responder ou a redigir um novo email: “Alguns arquivos desta página da Web não estão no local esperado. Deseja baixá-los mesmo assim? Se tiver certeza de que a página da Web é de uma fonte confiável, clique em Sim.”


- Resolvemos um problema que fazia com que o menu de contexto do botão direito do mouse não fosse exibido nos controles de pesquisa.


- Corrige um problema que fazia com que os usuários vissem anormalidades ao usar o modo de exibição compacto.


- Corrige um problema que causava falhas ocasionais quando os usuários editavam destinatários.


- Resolveu um problema que provocava falha na exibição da página do Assistente de Agendamento.


- Corrige um problema de desempenho com o carregamento de anexos.


- Tratamos de um problema que fazia com que os usuários experimentassem uma falha ao excluir 4 ou mais emails de uma conta POP com a opção "Baixar Apenas Cabeçalhos" selecionada.


- Corrige um problema que fazia com que os usuários vissem um erro na página de links seguros, em vez de no documento que tentavam abrir ao abrir um anexo na nuvem.


- Corrige um problema que causava falhas ocasionais quando os usuários interagiam com anexos na Nuvem.


- Corrige um problema que fazia com que os usuários não conseguissem fechar os calendários compartilhados, clicando no "X" no canto.


- Corrige um problema que fazia com que os usuários não conseguissem se conectar à pastas públicas após adicionar uma caixa de correio compartilhada.


- Resolveu um problema que fazia com que as reuniões não fossem retiradas do calendário de um gerente, quando recusadas por um representante em algumas circunstâncias.


- Resolveu um problema que impedia alguns usuários do recurso de Melhorias do Calendário Compartilhado de poderem visualizar um calendário compartilhado recém-adicionado.


- Corrige um problema que fazia com que a configuração "Habilitar melhorias no calendário compartilhado" falhasse, ocasionalmente, ao aplicar a calendários compartilhados existentes.


- Corrige um problema que provocou os usuários que tentaram criar uma solicitação de reunião de uma conta secundária adicionada ao perfil, a não verem um campo em branco De: em vez de seus endereços de email.


### <a name="powerpoint"></a>PowerPoint

- Consertamos um problema que estava causando a falha no aplicativo PowerPoint.


- Correção de segurança para solucionar um problema que desativava as proteções de IRM ao abrir um arquivo do PowerPoint no modo de Exibição Protegida.


- Essa alteração corrige um problema com o recurso Exportar para GIF Animado em que clicar no botão Exportar não exportava.


### <a name="project"></a>Project

- Corrigiu um problema em que a data de término do Projeto não está sendo atualizada para projetos conectados à lista de tarefas do SharePoint.


- Corrigiu um problema em que, se um recurso tivesse mais de uma tabela de taxas de custo definida, os custos restantes nem sempre eram calculados corretamente.

### <a name="skype"></a>Skype

- Alterou o tom de pele do emoticon que dança para uma cor neutra.


### <a name="visio"></a>Visio

- A visualização dinâmica trava no alinhamento do texto relatado pelos clientes. Principais travamentos da bifurcação de julho.


### <a name="word"></a>Word

- Resolvemos um problema em que a macro AutoOpen era executada antes do AutoExec


- Corrigimos um problema com a caixa de diálogo Galeria de Estilos.


- Resolveu um problema que pode ter causado uma falha durante a inicialização do Word.


- Resolvemos um problema em que os estilos básicos não eram atualizados com o estilo Normal.


- Consertamos um problema em que o usuário poderia receber uma falha ao abrir um documento.


- Resolvemos um problema em que o usuário poderia perder conteúdo ao redimensionar uma forma.


- Resolvemos um problema que fazia com que os usuários experimentassem um travamento ao abrir certos emails muito grandes.


- Soluciona um problema que fazia com que os usuários experimentassem uma falha ao responder ou redigir um novo email.


- Essa alteração corrige um problema em que os aplicativos do Office poderiam ficar presos em um estado de falha silencioso de Salvamento após uma sessão anterior de coautoria.


### <a name="office-suite"></a>Pacote Office

- Essa alteração corrige uma falha ao iniciar os aplicativos do Office devido à falha no carregamento de d2d1.dll.


- Corrige o alto uso de CPUs em ociosidade com GIF/modelo em 3D animado


- Quando o usuário imprimir um documento/arquivo em impressoras Inkjet a partir do Office e a tinta da impressora estiver baixa, a mensagem "Toner Baixo" ou "Sem Toner" será exibida, mesmo que as impressoras da Inkjet não tenham toners. Alterar a mensagem para exibir "Toner/tinta Baixo" e "Sem toner/tinta".



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-october-13"></a>Versão 2007: 13 de outubro
*Versão 2007 (Compilação 13029.20708)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um bug com APIs PivotDateFilter nas quais as condições de filtragem 'Antes' e 'Depois' eram invertidas.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2007-september-08"></a>Versão 2007: 8 de setembro
*Versão 2007 (Build 13029.20534)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows. [Saiba mais](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **Reabra rapidamente os itens de uma sessão anterior:** Adicionamos a opção de reabrir rapidamente os itens de uma sessão anterior do Outlook. Se o Outlook falhar ou você fechá-lo, agora será possível reiniciar rapidamente os itens quando você reabrir o aplicativo. Esse recurso não está habilitado por padrão. Para desativá-lo, vá até Opções > Gerais > Opções de Inicialização.

### <a name="word"></a>Word

- **Manter o texto em vetores:** Agora, você pode manter o texto em mapas, gráficos e outros vetores SVG ao converter esses objetos no Excel, no Word e no PowerPoint.

### <a name="office-suite"></a>Pacote Office

- **Painéis com Guias:** Agora, você pode alterar entre vários painéis usando uma interface de usuário de guia à direita do aplicativo. A interface de usuário ficará visível apenas quando você tiver dois painéis ou mais abertos.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acessar

- Esta correção resolve o problema de quando na tentativa de executar determinadas consultas tenha previamente produzido a mensagem de erro 'Consulta é muito complexa'.


### <a name="excel"></a>Excel

- Corrigimos um problema no qual um erro ou falha poderiam ocorrer ao se carregar uma pasta de trabalho com diversas planilhas no modo de visualização com quebra de página.


- Pode ocorrer um erro ao tentar salvar um arquivo que contenha uma fórmula usando a função LET ().


### <a name="outlook"></a>Outlook

- Solucionamos um problema que causa problemas de formatação em alertas de notificação de incidente.


- Solucionamos um problema que fazia com que os usuários do Outlook vissem problemas com a navegação no modo de exibição compacto.


- Resolvido um problema que causava um ocasional travamento para os usuários ao recuperar informações pessoais.


- Solucionamos um problema que provocou falha na exibição da página do Assistente de Agendamento.


- Solucionado um problema que fazia com que os usuários não conseguissem salvar os anexos do OneDrive de fora de seu locatário no computador local ao selecionar a opção "Salvar" na caixa de diálogo de segurança.


- Correção de um problema em que a opção “Permitir Encaminhamento” estava ausente das "Opções de Resposta" da reunião com calendário compartilhado, quando a pasta compartilhada Download não era verificada.


- Resolvido um problema que fazia com que o Outlook não recuperasse as sugestões de pesquisa.


- Tratamos de um problema que fazia com que os usuários de alguns conjuntos de caracteres vissem os nomes de arquivos exibidos incorretamente ao adicionar um Smart Link a um arquivo do SharePoint.


- Solucionamos um problema que fazia com que os usuários do CLP experimentassem uma falha ao mudar o endereço de um contexto de um contexto protegido para um não protegido.

- Soluciona um problema que fazia com que os usuários experimentassem um travamento ao responder ou redigir um novo email.


### <a name="powerpoint"></a>PowerPoint

- Solucionamos um problema de falha no aplicativo PowerPoint.


### <a name="project"></a>Project

- Corrigimos um problema no qual não era possível salvar um PDF/XPS do Project em uma biblioteca de documentos no SharePoint.


- Corrigimos um problema no qual, se você colasse uma tarefa que tivesse várias dependências, nem todas as dependências eram copiadas corretamente.


- Corrigimos um problema no qual a tarefa selecionada na caixa de diálogo para atribuir recursos não era a mesma que a tarefa selecionada no modo de exibição do quadro de tarefas.


- Corrigido um problema onde um projeto que estava em um estado ruim não podia ser aberto.



### <a name="office-suite"></a>Pacote Office

- Solucionamos um problema em que os usuários estavam vendo os elementos da interface do usuário ou o conteúdo que não estava sendo exibido em determinadas condições, em particular, no Modo de Exibição do Apresentador ou no uso de vários monitores.


- Corrigido um problema que provocou uma mensagem do tempo de execução, mesmo que foi demonstrado que a transição para o produto completo tenha sido concluída. A correção para esse problema foi garantir que o serviço computasse corretamente os produtos adicionados. Filtramos os produtos recém-adicionados (garantindo que também estejam presentes na nova configuração) e os adicionamos no final das IDs de lançamento dos produtos existentes.


- Para o antigo painel de Compartilhamento não baseado na Web, ao fechar o documento enquanto o painel de Compartilhamento abria, isso poderia causar uma falha. Isto agora está corrigido.



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2006-september-08"></a>Versão 2006: 8 de setembro
*Versão 2006 (Build 13001.20648)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2006-august-11"></a>Versão 2006: 11 de agosto
*Versão 2006 (Compilação 13001.20520)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

- **Filtre e classifique sem interromper os outros:** Agora você pode classificar e filtrar seu arquivo do Excel enquanto colabora com outras pessoas através do Modo de Exibição de Planilha. Esse novo recurso impede que você seja afetado pelas classificações e filtros de outros usuários durante a coautoria do documento. [Saiba mais](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a>Outlook

- **Ajude a proteger os dados de seu grupo:** o rótulo de Confidencialidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe.

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

- **Nova opção para desabilitar sugestões de @menções ao redigir emails no Outlook:** você considera o seletor @mencionar mais irritante que útil? Agora você pode desativá-lo, se preferir.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)

- **Mantenha suas fotos em alta definição ao enviá-las como parte de um email:** Uma nova configuração do Outlook está disponível para limitar a compactação de imagem quando você envia fotos como parte do conteúdo de emails.

### <a name="powerpoint"></a>PowerPoint

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

- **Melhor desempenho de streaming de vídeo no PowerPoint:** fizemos melhorias no desempenho da reprodução do Microsoft Stream para minimizar o tempo de carregamento de vídeos e criar uma experiência de exibição agradável. Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.

### <a name="word"></a>Word

- **Conte suas histórias com GIFs animados:** Os GIFs animados agora são têm suporte no editor do Office - seus documentos ficaram mais estilosos.

- **Fale de outra maneira:** quando você quiser dizer algo de forma diferente, o Reescrever estará lá para ajudar. O Reescrever oferece alternativas para refinar a suas frases.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Acesso

- Consertamos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais para ser terminada do que o esperado. 

- Resolveu um problema com a inserção de tabelas SQL vinculadas que incluem um campo identidade (por exemplo, numeração automática).


### <a name="excel"></a>Excel

- Correção de um problema que provocava a remoção de XML do CustomUI de uma guia da faixa de opções personalizada ao salvar no SharePoint/OneDrive.

- Corrigimos um problema no qual um erro ou falha poderiam ocorrer ao se carregar uma pasta de trabalho com diversas planilhas no modo de visualização com quebra de página.

- Correção de uma falha que poderia ocorrer quando você tentasse criar uma conexão de dados se tivesse saído da sua conta.

- A classificação automática de documentos pode ter ocorrido para as pastas de trabalho que estavam e modo somente leitura.

### <a name="onenote"></a>OneNote

- Melhore a detecção de status de coautoria para reduzir a utilização de recursos.

### <a name="outlook"></a>Outlook

- Corrigimos um problema ao copiar e colar imagem SVG.

- Corrige um problema que fazia com que a pesquisa de um recurso em Sugerir um recurso não retornasse resultados e deixasse o usuário sem a opção de enviar uma nova ideia de recurso.

- Corrige um problema que fazia com que Ctrl+clique parasse de funcionar quando as configurações de nuvem estavam habilitadas.

- Aborda um problema que fazia com que os usuários não conseguissem salvar anexos do OneDrive de fora de seu locatário para seu computador local ao selecionar a opção “Salvar” no diálogo de segurança.

- Corrige um problema que fazia com que o Outlook solicitasse continuamente para os usuários executarem a Ferramenta Reparo da Caixa de Entrada.

- Corrige um problema que causava falhas no calendário em aperfeiçoamentos do Calendário Compartilhado.

- Corrige um problema que fazia com que os usuários vissem a data de criação de  anexos que haviam copiado para seu sistema de arquivos por meio de arrastar e colar sendo  definida como 1° de janeiro de 4501.

### <a name="project"></a>Project

- Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa resumo do projeto, o campo início/tarefa do projeto.

- Correção de um problema em que uma tarefa marcada como 100% concluída mudava incorretamente para menos do que 100% concluída.

- Corrigimos um problema no qual não era possível abrir projetos no cliente da área de trabalho do Project a partir do aplicativo web do Project caso o URL terminasse em .com.

### <a name="word"></a>Word

- Corrigimos um problema ao copiar e colar imagem SVG.

### <a name="office-suite"></a>Pacote do Office

- Fizemos uma nova AppV51 para corrigir uma regressão no AppV51 anterior.

- Um problema de tempo poderia causar uma falha ao se fechar arquivos do Office

- Foi corrigido um problema de falha com o host do Office no Windows quando um suplemento é ativado enquanto o valor TabProcGrowth do registro é tipo REG_SZ.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-august-11"></a>Versão 2005: 11 de agosto
*Versão 2005 (Compilação 12827.20656)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2005-july-14"></a>Versão 2005: 14 de julho
*Versão 2005 (Build 12827.20538)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca. [Saiba mais](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

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

- Soluciona um problema que exibia a mensagem “A regras neste computador não correspondem às regras no Microsoft Exchange” ao atualizar as regras no Outlook.

- Aborda um problema que fazia com que os usuários vissem a data de criação de anexos que haviam copiado para seu sistema de arquivos por meio de arrastar e colar sendo definida como 1° de janeiro de 4501.

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

- **Novas imagens para dar vida às suas mensagens:** milhares de imagens de estoque, ícones e adesivos gratuitas que você pode usar em suas mensagens de email. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="powerpoint"></a>PowerPoint

- **Escolha a cor perfeita:** usar códigos de cor hexa para escolher a cor que você quer para a sua fonte, realce de texto e muito mais.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides. [Saiba mais](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Novas imagens para dar vida aos seus slides:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em suas apresentações. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

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
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.12827.20538|version-2005-july-14|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

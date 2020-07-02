---
title: Notas de versão para lançamentos de canais atuais no 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI as notas de versão para as versões do Canal Mensal para Aplicativos do Microsoft 365 em 2020
ms.openlocfilehash: 7003006056b0cd045d6a21111aee512cef07e040
ms.sourcegitcommit: f92dbf2ec2e2f11a344e97327e9cef08e9569670
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45015623"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a>Notas de versão para lançamentos de canais atuais no 2020

Estas notas de versão fornecem informações sobre os novos recursos e atualizações que não são de segurança incluídas nas atualizações de canal atuais no 2020 para aplicativos da Microsoft 365 para empresas, aplicativos do Microsoft 365 para empresas e as versões de assinatura dos aplicativos da área de trabalho para o Project e o Visio.

> [!IMPORTANT]
> Estamos fazendo algumas alterações nos canais de atualização para os Aplicativos do Microsoft 365, incluindo adicionar um novo canal de atualização (Canal Empresarial Mensal) e alterar os nomes dos canais de atualização existentes. Para saber mais, [leia este artigo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

 > [!NOTE]
>
>- Muitas vezes, os recursos são distribuídos (e às vezes até mesmo) para o atual por um período de tempo.  Se você não vir algo descrito abaixo, aguarde que estará em breve. [Saiba mais](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2006-june-30"></a>Versão 2006:30 de junho
*Versão 2006 (Build 13001,20266)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Nomes de arquivo mais longos:** A área de trabalho do Excel para Windows agora oferece suporte a arquivos do OneDrive/SharePoint com nomes e caminhos de até 400 caracteres.

### <a name="outlook"></a>Outlook

- **Nova opção para desabilitar sugestões de @menções ao redigir emails no Outlook:** você considera o seletor @mencionar mais irritante que útil? Agora você pode desativá-lo, se preferir.<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)

- **Notificação de incidentes para administradores de TI:** os administradores globais do locatário do Microsoft 365 e os administradores do Office serão notificados quanto aos incidentes do Outlook e do Office 365 que afetam seus usuários com uma nova notificação no painel direito no Outlook para Windows. [Saiba mais](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **Botões adicionais adicionados às notificações de notificação do Outlook:** Agora, os botões de ação rápida aparecem nas notificações do Outlook para executar o Outlook no Windows 10

### <a name="powerpoint"></a>PowerPoint

- **Desempenho aprimorado de vídeo de fluxo no PowerPoint:** Fizemos melhorias no desempenho de reprodução dos vídeos de Stream da Microsoft para minimizar o tempo de carregamento do vídeo e criar uma experiência de exibição tranqüila. Use seus vídeos corporativos do Microsoft Stream para criar apresentações melhores.

### <a name="teams"></a>Teams

- **Os números de telefone do participante PSTN são mascarados de usuários externos:** Para clientes com audioconferência habilitado para suas reuniões do Teams, iremos mascarar o número de telefone do participante PSTN para os usuários que ingressaram de fora da sua organização.

- **Maneira simplificada de gerenciar suas configurações de notificação de canal:** Por meio da lista de equipes e canais ou do cabeçalho do canal, os usuários podem gerenciar rapidamente suas configurações de notificação, ativando ou desativando todas as atividades com um único clique ou mergulhando em Personalizar para definir suas permutações preferidas.

- **Walkie talkie:** Comunicação de voz instantânea usando Push-to-Talk.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVA O INÍCIO DO CONTEÚDO DO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Corrigimos um problema em que a execução da consulta estava levando aproximadamente duas vezes mais tempo para ser concluída do que o esperado.


### <a name="excel"></a>Excel

- Correção de um problema que causou a remoção de XML CustomUI para uma guia de faixa de opções personalizada ao salvar no SharePoint/OneDrive.


### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários vejam a data de criação de anexos copiados para o sistema de arquivos por meio do recurso de arrastar e soltar por meio de 1 de janeiro de 4501.

- Solucionamos um problema que fazia com que os usuários dos aprimoramentos do calendário compartilhado vejam as falhas de calendário.


- Solucionamos um problema que fazia com que os usuários vejam o Outlook para que eles executem a ferramenta de reparo da caixa de entrada.


- Foi corrigido um problema que fazia com que CTRL + clique para parar de funcionar quando as configurações de nuvem foram habilitadas.


- Solucionamos um problema que causou a pesquisa de um recurso que sugere um recurso para não retornar nenhum resultado e deixar o usuário sem opção para enviar uma nova ideia de recurso.


### <a name="project"></a>Project

- Correção de um problema em que os projetos não puderam ser abertos no cliente de área de trabalho do Project a partir do Project Web App, se a URL terminou no. com.


- Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa de resumo do projeto-o campo Iniciar/tarefa do projeto.


- Correção de um problema em que uma tarefa marcada 100% conclusão está incorreta para ser inferior a 100% concluída.


### <a name="word"></a>Word

- Resolvido um problema ao abrir documentos do Word a partir de uma entrega de documento personalizada (aspx) quando a URL contém um componente de consulta.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-june-24"></a>Versão 2005:24 de junho
*Versão 2005 (Build 12827,20470)*

[//]: # (NÃO REMOVA O INÍCIO DO CONTEÚDO DO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esse bug já foi corrigido; Você deve ser capaz de chamar o tipo de dados estendido de data/hora para o seu código sem ter ocorrido nenhuma falha em seu aplicativo. Informe a equipe se você tiver problemas adicionais.


- Esse problema foi corrigido. Agora você pode reverter para a versão mais atualizada do Access e usar o DAO/VBA para gerenciar e editar um tipo de dados decimal. Deixe a equipe do Access saber se você encontrou outros problemas ao usar nosso tipo de dados.


### <a name="excel"></a>Excel

- Correção de um problema que causou a remoção de XML CustomUI para uma guia de faixa de opções personalizada ao salvar no SharePoint/OneDrive.





### <a name="outlook"></a>Outlook

- Foi corrigido um problema em que o Outlook falhou ao habilitar a política de proteção contra perda de dados pessoas para usuários que tenham pago pelo serviço que estão nos planos do M365 Business Plus.


- Solucionamos um problema que fazia com que os usuários vejam a data de criação de anexos copiados para o sistema de arquivos por meio do recurso de arrastar e soltar por meio de 1 de janeiro de 4501.


- Foi corrigido um problema que fazia com que os usuários vejam as &quot; regras deste computador que não correspondem às regras da mensagem do Microsoft Exchange &quot; ao atualizar suas regras no Outlook.


- Solucionamos um problema que fazia com que os usuários dos aprimoramentos do calendário compartilhado vejam as falhas de calendário.


- Solucionamos um problema que fazia com que os usuários experimentassem interrupções intermitentes e falhas em alguns cenários.


- Solucionamos um problema que fazia com que os usuários vejam o Outlook para que eles executem a ferramenta de reparo da caixa de entrada.


- Solucionamos um problema que causou a pesquisa de um recurso que sugere um recurso para não retornar nenhum resultado e deixar o usuário sem opção para enviar uma nova ideia de recurso.


### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema de falha com o painel de sugestões.


### <a name="project"></a>Project

- Correção de um problema em que uma tarefa marcada 100% conclusão está incorreta para ser inferior a 100% concluída.

### <a name="word"></a>Word

- Resolvido um problema que pode ter causado uma falha ao arrastar parte do conteúdo do aplicativo.


### <a name="office-suite"></a>Pacote do Office

- Essa alteração atende a possíveis interrupções ao carregar e reproduzir conteúdo animado, como GIFs ou modelos 3D.




[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-june-09"></a>Versão 2005:9 de junho
*Versão 2005 (Build 12827,20336)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVA O INÍCIO DO CONTEÚDO DO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Trata de um problema em que o Excel pode falhar ao tentar inserir tabelas dinâmicas em uma planilha de gráfico.

### <a name="powerpoint"></a>PowerPoint

- Isso corrige uma falha quando os usuários têm comentários modernos e antigos em um arquivo, disparando uma atualização nos comentários.

### <a name="project"></a>Project

- Correção de um problema em que o evento ProjectBeforeTaskChange não é acionado quando há uma alteração na tarefa de resumo do projeto-o campo Iniciar/tarefa do projeto.

### <a name="office-suite"></a>Pacote do Office

- Resolvemos o problema de taxa de falha do ValidateInstall Configurando a validação de instalação de Complementos do Bing como true por padrão e considerando o MSI Return Success como uma instalação bem-sucedida.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2005-june-02"></a>Versão 2005: junho de 2002
*Versão 2005 (Build 12827,20268)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Usar automaticamente novos tipos de dados:** Quando você digita um valor de dados que se assemelha a um estoque ou uma localização geográfica, o Excel oferece a conversão para o tipo de dados conectado à direita-ações ou geografia. [Saiba mais](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Diga suas histórias com gifs animados:** GIFs animados agora têm suporte no editor do Office-seus documentos acabam de ter snazzier

### <a name="outlook"></a>Outlook

- **Ajude a proteger os dados de seu grupo:** o rótulo de sensibilidade que você escolheu ao criar um grupo é aplicado a emails de grupo, documentos e sites de equipe

- **Melhores resultados — em uma piscar olhos:** atualizamos a experiência de pesquisa para torná-la mais inteligente, rápida e mais confiável do que nunca. [Saiba mais](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Diga suas histórias com gifs animados:** GIFs animados agora têm suporte no editor do Office-seus documentos acabam de ter snazzier

- **O calendário Obtém uma remodelação:** Veja atualizações visuais que facilitam a verificação do calendário. [Saiba mais](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Ver detalhes na [postagem do blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

### <a name="powerpoint"></a>PowerPoint

- **Diga suas histórias com gifs animados:** GIFs animados agora são compatíveis com o editor do Office-seus documentos acabam de [obter mais](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01) snazzier

- **Sincronizar alterações durante a apresentação:** Sincronizar alterações sempre que elas forem feitas, mesmo quando a apresentação estiver no modo de apresentação de slides. [Saiba mais](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Não é preciso dar um clique: seus earbuds fazem isso por você** Use seu Surface Earbuds para controlar suas apresentações de PowerPoint. Como funciona: uma vez emparelhado, você precisará habilitar o recurso no PowerPoint. Inicie uma apresentação pressionando F5 ou selecionando apresentação de slides > do início.  Na apresentação de slides, clique com o botão direito do mouse no slide e, em seguida, em configurações da superfície earbuds, escolha usar gestos para controlar a apresentação.  Essa configuração será lembrada para todas as apresentações futuras. Agora você pode passar para frente e para trás no earbud esquerdo para navegar em suas apresentações no modo de apresentação de slides.  Dê um toque duplo para reproduzir ou pausar vídeos incorporados.  Importante: Você deve parear seu Surface Earbuds com o aplicativo Surface Audio para Windows 10 para usar gestos para controlar as apresentações. As instruções sobre como começar a usar o aplicativo de áudio Surface no Windows 10 estão disponíveis aqui. [Saiba mais](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **Alterações no layout de vídeo em reuniões do teams:** Em breve, o número de participantes que podem ser exibidos simultaneamente durante uma reunião do teams aumentará de 4 para 9.

- **Incluir áudio do sistema em eventos ao vivo:** Os apresentadores e produtores em eventos ao vivo agora podem incluir áudio do sistema ao compartilhar uma tela de área de trabalho ou de janela durante o evento Live. Isso permitirá que os usuários escutem qualquer parte de áudio do conteúdo que você está compartilhando.

- **Permitir que os organizadores alterem as configurações de lobby para participantes de discagem:** Esta configuração controla se as pessoas que discam por telefone participam diretamente da reunião ou esperam no lobby independentemente da configuração admitir pessoas automaticamente.

- **Levante sua mão em reuniões:** Os usuários agora podem elevar uma mão virtual em uma reunião! Outros participantes verão a mão levantada ao lado do seu nome no estágio da reunião e ao lado do seu nome na lista.

- **Personalizar planos de fundo da reunião:** Ao se reunir com vídeo, agora você tem a opção de imagens de plano de fundo estáticas diferentes para usar. Isso permitirá que você mostre essa imagem e não o plano de fundo real de onde você está sentado.

- **Adicionar mais pessoas ao chat:** Tornamos possível adicionar até 350 pessoas a um único thread de chat.

- **Configurações de engrenagem no feed de atividades:** Agora, os usuários podem acessar diretamente a configuração de feed de atividades e notificação do trilho esquerdo de alimentação por meio de um engrenagem de configurações.

- **Acessar facilmente as opções de reunião de dentro de uma reunião do teams em andamento:** Estamos facilitando que os organizadores de reunião mudem de forma rápida e fácil suas configurações de apresentador e de lobby depois que uma reunião do teams inicia, fornecendo um link de fácil acesso diretamente no painel de participantes. Essa nova funcionalidade estará presente para reuniões programadas e "reunir agora".

- **Análise de canal e equipe:** Além do Team Analytics, agora você também pode exibir métricas de nível de canal e insights. Também aprimoramos o período de tempo para 90 dias, para que você possa analisar os dados por períodos mais longos. Além disso, essa versão também inclui novas métricas e gráficos ao redor da contagem de postagens, respostas e reuniões para uma equipe ou canal.

- **Anúncios de entrada/saída:** Adicionamos este recurso que permite que os organizadores de reunião possam ativar ou desativar anúncios de entrada e saída para uma reunião.

### <a name="word"></a>Word

- **Decodificar acrônimos sem sair do Word:** Quando você encontrar um acrônimo, o Word tentará defini-lo com base em como os outros o utilizam.

- **Diga suas histórias com gifs animados:** GIFs animados agora têm suporte no editor do Office-seus documentos acabam de ter snazzier


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos

### <a name="excel"></a>Excel

- Correção de um problema em que o Excel pode parar de responder após usar Ctrl + Shift + teclas de direção para rolar quando a janela do Excel é compartilhada por meio do teams.

- Em alguns casos, clicar em um hiperlink para um local dentro da mesma pasta de trabalho fará com que a pasta de trabalho fique oculta.

### <a name="outlook"></a>Outlook

- Foi corrigido um problema com o evento CLP de auditoria para o rótulo de resposta/encaminhamento.

- Solucionamos um problema que fazia com que os usuários das versões do Windows 10 Server vejam o aviso "status de antivírus: inválido". Esta versão do Windows oferece suporte à detecção de antivírus, mas nenhum antivírus foi encontrado, apesar de ter o antivírus instalado corretamente.

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma notificação de administrador.

### <a name="skype"></a>Skype

- Quando um usuário recebe uma política que as transfere apenas para o Microsoft Teams, ainda era possível usar o suplemento do Outlook para o Skype for Business para agendar reuniões. Após esta atualização, você não poderá mais agendar reuniões do Skype for Business depois que o cliente lê a política que indica que o usuário é apenas o Microsoft Teams e insere o modo somente ingresso na reunião. Além disso, o suplemento do Outlook para o Skype for Business não se ativará enquanto é iniciado se ele estiver no modo somente ingresso na reunião.

### <a name="office-suite"></a>Pacote Office

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.

- Esta atualização corrige um problema no Microsoft Office, em que os projetos do Visual Basic for Applications com referências esperadas para localizar localizações especificadas na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução VBA.

- O host do Office estava falhando no Windows, quando um suplemento é ativado enquanto a chave do registro HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth é definida como zero. Essa alteração resolveria esse problema.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-21"></a>Versão 2004:21 de maio
*Versão 2004 (Build 12730,20352)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Correção de um problema em que o link externo para de funcionar depois que o arquivo for reaberto se o caminho do arquivo for muito longo.


### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários experimentassem uma falha ao enviar comentários de uma notificação de administrador.


### <a name="office-suite"></a>Pacote do Office

- Correção de um problema de clique para executar que resultava em falhas de atualização ocasionais nas versões mais recentes.

- Correção de um problema no Microsoft Office em que os projetos do Visual Basic for Applications com referências que devem ser encontradas pesquisando locais especificados na variável de ambiente PATH podem não ser encontrados corretamente no tempo de execução, levando a erros de tempo de execução do VBA.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-12"></a>Versão 2004: 12 de maio
*Version 2004 (Criação 12730.20270)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Soluciona um problema que fazia com que os usuários experimentassem uma falha ao exibirem notificações do sistema.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-may-04"></a>Versão 2004: 04 de maio
*Versão 2004 (Build 12730.20250)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="office-suite"></a>Pacote Office

- Correção de um problema no Visual Basic for Applications no Microsoft Office, em que determinados projetos VBA que continham referências a bibliotecas de códigos com caracteres DBCS no nome da biblioteca ou no caminho da biblioteca eram exibidos pelo aplicativo do Office como corrompidos durante o carregamento.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2004-april-29"></a>Versão 2004: 29 de abril
*Versão 2004 (Build 12730.20236)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Seja mais produtivo trabalhando no Query Designer, no SQL View e na janela Relações:** clique com o botão direito em uma tabela para abrir, criar, dimensionar e ocultá-la. Pesquise e substitua o texto no SQL View. Selecione várias tabelas na janela Relações.

- **Adicionar tabelas com menos cliques:** usar o painel de tarefas Adicionar Tabelas, que permanece aberto enquanto você trabalha, para adicionar tabelas a relações e consultas. [Saiba mais](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **O suporte ao conector do Facebook terminou:** a partir de abril de 2020, o Excel não dará mais suporte a conexões de dados externos que usam o conector do Facebook.

- **Tem uma pergunta? Pergunte ao Excel:** agora, as ideias do Excel permitem que você faça perguntas sobre seus dados, sem a necessidade de gastar horas de gravação (disponível somente em inglês). [Saiba mais](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Novas imagens para dar vida às suas pastas de trabalho:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em suas pastas de trabalho. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **Participe de reuniões sem sair da sua caixa de entrada:** não é necessário mudar para o calendário para ingressar em reuniões online. Com o calendário fixado no painel de Tarefas pendentes, participe de uma reunião com apenas um clique.

- **Novas imagens para dar vida às suas mensagens:** milhares de imagens de estoque, ícones e adesivos gratuitas que você pode usar em suas mensagens de email. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **Suporte a sugestões de local para reunião recorrente:** pesquisar salas de conferência com o agendamento de reuniões recorrentes.

### <a name="powerpoint"></a>PowerPoint

- **Atualizar slides durante a apresentação de slides:** os slides de atualização alterados por outros autores durante a sua apresentação.

- **Novas imagens para dar vida aos seus slides:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em suas apresentações. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **Aperfeiçoamentos do calendário do Teams:** clique com o botão direito do mouse em um item no seu calendário para obter as opções de RSVP, iniciar um chat com os participantes da reunião ou participar rapidamente de uma reunião quando ela for iniciada. Também fizemos aperfeiçoamentos no formulário de agendamento de eventos.

- **Você está pronto!:** Crie marcas e atribua às pessoas para que você possa @mencionar um grupo, função, departamento etc. Proprietários da equipe, tente você mesmo. Vá para uma equipe, selecione Mais opções, Gerenciar marcas.

### <a name="word"></a>Word

- **Mantenha suas ferramentas úteis:** Na sua caixa de ferramentas de desenho, encontre a caneta inteligente que permite adicionar gestos de tinta ao texto. [Saiba mais](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Novas imagens para dar vida aos seus documentos:** Milhares de imagens de estoque, ícones e figurinhas gratuitas que você pode usar em seus documentos. Vá para Inserir > Imagens > Imagens de estoque para começar. [Saiba Mais](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- As pastas de trabalho salvas com uma assinatura digital no Excel 2016 podem ter a assinatura invalidada ao serem abertas na versão atual do Excel.

- Foi corrigido um problema que poderia fazer com que o Excel falhasse em alguns casos, depois de copiar uma planilha contendo uma tabela dinâmica.

- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.

### <a name="outlook"></a>Outlook

- Corrigido um problema que provocou a alteração inesperada da largura do painel de pasta.


- Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.


- Foi solucionado um problema que causava uma falha no Outlook ao abrir arquivos .msg ou .oft que eram salvos localmente após uma atualização do Windows.


- Solucionamos um problema que causa falha no Outlook em algumas versões do Windows.


- Solucionamos um problema que fazia com que os usuários experimentassem um travamento ao sair do Outlook.


### <a name="project"></a>Project

- Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.


- Corrigido um problema em que, se você estivesse usando o Project conectado ao Project Web App e o separador decimal fosse vírgula, o método Adicionar TaskDependencies falhará ao tentar adicionar retardo a uma dependência.

### <a name="office-suite"></a>Pacote Office

- Resolvia um erro que ocorre porque é possível restringir o acesso e a proteção de arquivos com uma senha simultaneamente.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2003-april-15"></a>Versão 2003: 15 de abril
*Versão 2003 (Build 12624.20466)*
* Várias correções de bugs e desempenho.

## <a name="version-2003-april-14"></a>Versão 2003: 14 de abril
*Versão 2003 (Build 12624.20442)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- O Application.Evaluate (VBA) não estava funcionando para funções definidas pelo usuário em alguns casos.

### <a name="outlook"></a>Outlook

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.

### <a name="project"></a>Projeto

- Quando dados do Predecessor/Sucessor são editados em um modo de exibição de Formulário, um evento ProjectBeforeTaskChange adicional é acionado.

### <a name="word"></a>Word

- Resolvido um problema que fazia com que os usuários experimentassem uma falha ocasional ao usarem o botão "X" no mouse.


[//]: # (NÃO REMOVA O FIM DO CONTEÚDO DO BUGDETAILS)

## <a name="version-2003-march-31"></a>Versão 2003: 31 de março
*Versão 2003 (Build 12624.20382)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="onenote"></a>OneNote

- Informa os usuários, por meio da barra de informações, sobre ajustes temporários no Microsoft OneNote que ajudarão a melhorar a sincronização e o serviço durante o uso intenso pelo mundo inteiro.

### <a name="project"></a>Project

- Correção de um problema em que o usuário não conseguia entrar no trabalho da linha de base com divisão ao longo do tempo quando a configuração para proteger o trabalho real está ativada.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2003-march-25"></a>Versão 2003: 25 de março
*Versão 2003 (Build 12624.20320)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="outlook"></a>Outlook

- **Arraste o email para um grupo que você possui:** Mova e copie mensagens e conversas arrastando-as da sua caixa de entrada. As mensagens que você arrastar serão compartilhadas com todos os membros do grupo.

- **Nova experiência para redes sem fio prisioneiras:** Já se conectou a uma rede WiFi que exigia uma página da Web para entrar? O Outlook agora detecta isso e ajuda você a se conectar.

### <a name="word"></a>Word

- **Outras pessoas veem suas alterações rapidamente:** Os aperfeiçoamentos de coautoria significam que seus colaboradores podem ver suas mudanças mais rápido do que nunca.

### <a name="office-suite"></a>Pacote do Office

- **Rótulos de confidencialidade:** agora você pode aplicar um rótulo de confidencialidade que sua organização configurou para solicitar permissões personalizadas.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- O Excel falharia em alguns casos ao reabrir uma pasta de trabalho inserida no Word ou no PowerPoint.

- Solucionamos um problema em que links externos não eram atualizados no preenchimento se o livro de origem estivesse fechado.

- Solucionamos um problema de desempenho durante a criação de gráficos de modelos.

### <a name="onenote"></a>OneNote

- Melhor sincronia e estabilidade do serviço, reduzindo temporariamente o tamanho máximo permitido de novos anexos inseridos para 50 MB. Para os arquivos que excederem esse limite, os usuários terão a opção de carregar o arquivo para o OneDrive e inserir um link para o OneNote.

- Melhor sincronia e estabilidade do serviço desabilitando temporariamente a gravação de vídeo no aplicativo no OneNote 2016.

### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que os usuários vissem o processo do Outlook persistir no gerenciador de tarefas após sair.

### <a name="powerpoint"></a>PowerPoint

- Melhoria de um cenário de copiar e colar: poderia ocorrer uma falha, com exceção, ao copiar a Forma no slide do powerpoint e colá-lo em outro slide em um loop.


### <a name="project"></a>Project

- Correção de um problema em que o evento ProjectBeforeTaskChange não detecta quando uma tarefa foi desabilitada/ativada por meio do botão Desativar.

- Correção de um problema em que o Project pode falhar ao salvar projetos criados com versões anteriores do Project.

- Correção de um problema em que a porcentagem concluída da tarefa estava incorretamente alterando para um valor menor que 100% concluído depois de ser marcado como concluído.

- Correção de um problema em que as datas da tarefa resumo não eram sempre calculadas corretamente.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2002-march-10"></a>Versão 2002: 10 de março
*Versão 2002 (Build 12527.20278)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="project"></a>Projeto

- Foi corrigido um problema em que o evento OnUndoOrRedo não era acionado sem executar o método OpenUndoTransaction.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-march-01"></a>Versão 2002: 01º de março
*Versão 2002 (Build 12527.20242)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="outlook"></a>Outlook

- Resolve um problema que fazia com que aplicativos de terceiros não pudessem enviar e-mails.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO DE BUGDETAILS)

## <a name="version-2002-february-25"></a>Versão 2002: 25 de Fevereiro
*Versão 2002 (Criação 12527.20194)*

 (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Estatísticas da pasta de trabalho:** células, fórmulas, gráficos, tabelas... Contamos para que você não precise contar.

- **Criação de perfil de dados no editor de consultas:** obtenha uma análise rápida dos dados em suas colunas, identifique erros e valores vazios, consulte histogramas de distribuição e muito mais.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema em que as funções do CUBEVALUE, às vezes, retornavam um resultado incorreto.

### <a name="outlook"></a>Outlook

- Corrige um problema que fazia com que as vírgulas no campo local de uma reunião se transformassem em ponto e vírgula.

- Resolve um problema que pode resultar em uma falha ao exibir o mesmo item em várias janelas.

- Corrige um problema que causava falha na opção para desabilitar o realce de item sinalizado, deixando que isso não fosse respeitado em alguns cenários.

- Corrige um problema que fazia com que o Outlook sincronize inesperadamente todos os e-mails, mesmo quando o controle deslizante de sincronização estiver definido como uma configuração menor.


- Aborda um problema que fazia com que os usuários com tema preto vejam o menu suspenso "de" mostrar texto branco em um plano de fundo branco.


- Essa alteração restaura a capacidade de visualizar assuntos de várias linhas no cabeçalho da mensagem.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2001-february-19"></a>Versão 2001: 19 de fevereiro
*Versão 2001 (Build 12430.20288)*
* Várias correções de bugs e desempenho.

## <a name="version-2001-february-11"></a>Versão 2001: 11 de fevereiro
*Versão 2001 (Build 12430.20264)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Os modelos do Access não devem mais causar falha nas colunas do anexo em um banco de dados. Após instanciar um modelo, agora você poderá adicionar um campo de anexo ao seu banco de dados.

### <a name="excel"></a>Excel

- Corrigido um problema em que os comandos de comentário no menu de contexto não estavam sendo exibidos.

- Corrigido um problema que fazia com que alguns usuários experimentassem falhas ao converter texto em colunas com células com uma matriz derramada.


### <a name="outlook"></a>Outlook

- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao especificar um endereço De inválido.


- Solucionado um problema que fazia com que os usuários experimentassem uma falha ao cancelar a configuração da conta.


### <a name="project"></a>Project

- Corrigido um problema em que 100% das tarefas do tipo duração fixa podem ter a % concluído incorretamente calculado com menos de 100%.


### <a name="office-suite"></a>Pacote do Office

- Essa alteração soluciona problemas relatados com adaptadores gráficos que utilizam a GPU integrada da Intel.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2001-january-30"></a>Versão 2001: 30 de janeiro
*Versão 2001 (Build 12430.20184)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Leia e responda instantaneamente:** Responda a comentários e menções diretamente do email sem abrir a pasta de trabalho.

- **Olhe para a esquerda, olhe para a direita... XLOOKUP está aqui!:** Linha por linha, encontre tudo o que você precisa em uma tabela ou intervalo com o XLOOKUP. [Saiba mais](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **Configurações avançadas de email do grupo:** Esse recurso ajuda os usuários de grupos a personalizar quais emails ou eventos receber/acompanhar na caixa de entrada.

- **Política de Nome de Grupo:** Uma política de nome de grupo permite que o administrador de TI padronize e gerencie os nomes do grupos criados pelos usuários na organização. O administrador pode exigir o uso de um prefixo ou sufixo específico para o nome de um grupo quando ele é criado e pode bloquear o uso de palavras específicas. Isso ajuda a minimizar o uso de palavras inadequadas em nomes de grupos, além de gerenciar a representação de grupos no diretório. A Política de Nome também ajuda as organizações que implantam sites de equipe a categorizar com base no departamento.

### <a name="word"></a>Word

- **Uma experiência de vídeo mais segura:** aperfeiçoamentos de segurança significam uma experiência de vídeo mais segura para você. [Saiba mais](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Laço a tinta:** a ferramenta laço na guia desenhar ajuda a selecionar objetos desenhados à tinta. Selecione traços individuais ou palavras inteiras. [Saiba mais](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Salvar formas como imagens:** em apenas alguns cliques, salve uma forma, ícone ou outro objeto como arquivo de imagem para reutilizá-lo em outro lugar. [Saiba mais](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esta atualização corrige um problema no uso de um ADODB. O objeto gravador no código VB pode incorretamente relatar um erro.


- Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.


### <a name="excel"></a>Excel

- Soluciona um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.


### <a name="outlook"></a>Outlook

- Soluciona um problema que fazia com que os usuários experimentassem falhas ao renomear uma assinatura.


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1912-january-22"></a>Versão 1912: 22 de janeiro
*Versão 1912 (Build 12325.20344)*

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esta atualização corrige um problema que pode fazer com que o Microsoft Access não consiga identificar uma coluna de identidade em uma tabela do SQL Server vinculada, o que pode fazer com que as linhas sejam relatadas como excluídas incorretamente.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-1912-january-14"></a>Versão 1912: 14 de janeiro
*Versão 1912 (Build 12325.20298)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-1912-january-08"></a>Versão 1912: 08 de janeiro
*Versão 1912 (Build 12325.20288)*

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos

### <a name="outlook"></a>Outlook

- **Envie email acessível para quem mais precisa:** O Outlook exibirá uma dica de email para ajudar a garantir que seu conteúdo seja acessível ao enviar para um usuário que prefira este tipo de conteúdo.

### <a name="powerpoint"></a>PowerPoint

- **Otimize sua apresentação para todos:** O Verificador de Acessibilidade ajuda a organizar os objetos em seus slides pensando nos leitores de tela.

- **GIFs em instantes:** Um slide, um quadro. Crie facilmente GIFs de loop no PowerPoint. [Saiba mais](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Essa alteração contorna um problema com certos drivers gráficos Intel, aproveitando a renderização do software.

### <a name="outlook"></a>Outlook

- Solucionamos um problema que fazia com que o local de uma reunião fosse adicionado novamente à reunião após a limpeza.

- Solucionamos um problema que fazia com que os usuários percebessem um atraso notável ao interagir com as pastas da caixa de correio por meio dos atalhos de teclado.

- Solucionamos um problema que fazia com que os usuários vissem os e-mails enviados para um endereço que não correspondia ao endereço SMTP exibido em algumas circunstâncias.

- Solucionamos um problema que fazia com que os usuários experimentassem travamentos no Outlook ao recuperar as configurações da Nuvem.

### <a name="word"></a>Word

- O organizador de blocos de construção pode exibir um alerta inválido: "você modificou estilos, blocos de construção".

### <a name="office-suite"></a>Pacote Office

- Corrigimos um problema em que as atualizações do Office podem ter baixado arquivos da CDN do Office inesperadamente, em vez da origem pretendida, como um compartilhamento de rede ou local ou um local fornecido pelo Configuration Manager.

[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).

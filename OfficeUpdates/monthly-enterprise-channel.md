---
title: Notas de versão para os lançamentos do Canal Empresarial Mensal
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fornece aos profissionais de TI as notas de versão para o Canal Empresarial Mensal dos Aplicativos do Microsoft 365 Apps
ms.openlocfilehash: 1795f0a150b8b18d50e462cd6d30a285c055f8b1
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851861"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>Notas de versão para os lançamentos do Canal Empresarial Mensal

Estas notas de versão fornecem informações sobre novos recursos e atualizações não relacionadas à segurança que estão inclusos em atualizações mensais do Canal Corporativo Mensal para Microsoft 365 Apps para Grandes Empresas, Microsoft 365 Apps para Pequenos e Médios negócios e as versões de assinatura dos aplicativos da área de trabalho do Project e do Visio.


[//]: # (NÃO REMOVA)



## <a name="version-2104-june-08"></a>Versão 2104: 08 de junho
*Versão 2104 (Build 13929.20408)*

Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Salvamento automático e coautoria em documentos criptografados confidenciais:** Não troque produtividade por segurança. Com a Proteção de Informações da Microsoft, os documentos criptografados com rótulos de sensibilidade agora podem ser salvos no AutoSave e em coautoria com outras pessoas em tempo real, assim como os documentos não criptografados. Requer adesão do locatário (mais informações: https://aka.ms/mipcoauth).

### <a name="powerpoint"></a>PowerPoint

- **Salvamento automático e coautoria em documentos criptografados confidenciais:** Não troque produtividade por segurança. Com a Proteção de Informações da Microsoft, os documentos criptografados com rótulos de sensibilidade agora podem ser salvos no AutoSave e em coautoria com outras pessoas em tempo real, assim como os documentos não criptografados. Requer adesão do locatário (mais informações: https://aka.ms/mipcoauth).

### <a name="word"></a>Word

- **Salvamento automático e coautoria em documentos criptografados confidenciais:** Não troque produtividade por segurança. Com a Proteção de Informações da Microsoft, os documentos criptografados com rótulos de sensibilidade agora podem ser salvos no AutoSave e em coautoria com outras pessoas em tempo real, assim como os documentos não criptografados. Requer adesão do locatário (mais informações: https://aka.ms/mipcoauth).


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um problema onde alguns os arquivos ocasionalmente não abriam no Modo de Exibição Protegido.


- Corrigimos um problema que fazia com que a formatação de data fosse exibida incorretamente em alguns idiomas ao adicionar suplementos.


- Corrigido um problema em que o suplemento Ferramentas de Análise não funcionava para alguns usuários.


- Corrigimos um problema em que as entradas extras apareciam na lista de suplementos do Excel para alguns usuários.


- Correção de um problema em que uma reversão da compilação da versão principal poderia resultar no fechamento do aplicativo ao abrir o arquivo.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que alguns usuários do recurso de melhorias de compartilhamento do calendário tivessem problemas de interação com o calendário deles no painel de navegação.


- Adicionamos uma chave do Registro que desabilitava a nova experiência do Localizador de Salas (a mesma experiência do Outlook para Web) e habilita o Localizador de Salas herdado com Horários Sugeridos.
    
    Chave do Registro:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    > 0 (padrão) – O Outlook usa a nova plataforma OWA Powered eXperience de Localizador de Salas quando o usuário clica no botão "Localizador de Salas" para pesquisar salas disponíveis  </br>
    > 1 - O Outlook usa a interface de usuário herdada do Localizador de Salas para procurar salas disponíveis </br>


- Corrigimos um problema que fez com que a resolução de nomes falhasse ao enviar em nome de outro usuário e resolver contra um catálogo de endereços que não é a Lista de Endereços Global.


- Corrigimos um problema que fazia com que a opção de comentários não aparecesse para usuários da versão prévia do Office Permanente 2021.


- Corrigimos um problema que poderia fazer com que os usuários vissem a mensagem que eles estão compondo perdendo o foco da IU.


- Resolvemos um problema que fez com que o Outlook anulasse as preferências da Caixa de Entrada Destaques configurada no OWA.


- Corrigimos um problema que fazia com que os usuários vissem as assinaturas desaparecerem inesperadamente.


- Corrigimos um problema que fazia com que os usuários com configurações móveis experimentassem falta de resposta.


- Corrigimos um problema que causava um fechamento inesperado do processo para os usuários ao pesquisar.


- Corrigimos um fechamento inesperado relacionado à pesquisa.


- Corrigimos um problema que fazia com que o seletor de pessoas no Outlook expandisse para cima em vez de para baixo para usuários com uma licença permanente.


### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema em que a opção Reutilizar Slides não estava disponível para alguns usuários.


- Corrigimos um problema relacionado a imagens vinculadas.


- Corrigimos um problema em que uma reversão da compilação da versão principal poderia resultar em um fechamento inesperado ao abrir o arquivo.


### <a name="project"></a>Project

- Corrigido um problema em que os usuários não conseguiam remover projetos do pool de recursos.


### <a name="word"></a>Word

- Corrigimos um problema que exigia um alteração na edição do objeto OLE.


- Corrigimos um problema em que alguns textos selecionados não ficavam visíveis ao usar o tema de modo escuro no modo de leitura.


- Corrigimos um problema que poderia fazer com que o Word fechasse inesperadamente quando o usuário fizesse logoff ou reiniciasse o computador.


- Corrigimos um problema onde se atualizava o texto sobre a chamada automática para arquivos salvos localmente.


- Corrigimos um problema em que uma reversão da compilação da versão principal poderia resultar em um fechamento inesperado ao abrir o arquivo.


### <a name="office-suite"></a>Pacote do Office

- Corrigimos um problema que fazia com que o documento na nuvem não abrisse.


- Essa mudança analisa o novo atributo TenantId enviado nas respostas do Cobalt e o armazena na Tabela Central.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2103-june-08"></a>Versão 2103: 08 de junho
*Versão 2103 (Build 13901.20554)*

Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema em que as entradas extras apareciam na lista de suplementos do Excel para alguns usuários.


### <a name="office-suite"></a>Pacote do Office

- Corrige um problema que fazia com que o Word, PowerPoint e Excel não abrisse um documento na nuvem se voltasse para uma versão anterior



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2103-may-11"></a>Versão 2103: 11 de maio
*Versão 2103 (Build 13901.20516)*

Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Usar os novos tipos de dados automaticamente:** Ao digitar um valor de dados semelhante a um estoque ou uma localização geográfica, o Excel oferece a conversão para o tipo de dados conectado certo, ações ou geografia. [Saiba mais](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Tipos de dados vinculados – dados reais para a vida real:** novos tipos de dados vinculados trazem fatos e dados sobre centenas de assuntos para ajudar você a alcançar seus objetivos diretamente no Excel.

### <a name="outlook"></a>Outlook

- **Quebre a barreira do idioma com um tradutor interno:** Os suplementos para tradução não são mais necessários! Agora você pode usar o Tradutor Inteligente no Outlook. Quando você receber uma mensagem em outro idioma, um aviso aparecerá na parte superior da mensagem perguntando se você deseja que o Outlook a traduza para o seu idioma padrão.
Você também pode clicar com o botão direito para traduzir palavras, frases específicas ou a mensagem inteira. [Saiba mais](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **Gráficos prontos para seus diagramas:** escolha entre uma grande biblioteca de ícones, fotos de catálogo, pessoas removidas da imagem e figurinhas que você pode adicionar aos seus desenhos do Visio. [Saiba mais](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/access-illustrations-icons-in-visio)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Corrigimos um problema quando um aplicativo externo solicita uma interface de acessibilidade. Isso nos impedirá de desligar até que eles liberem sua referência.


- Esta alteração corrige um problema em que, em alguns casos, executar uma consulta passagem do SQL Server poderia resultar em uma mensagem de erro indicando que havia um “estado do cursor inválido”.


### <a name="excel"></a>Excel

- Corrigimos um problema que fazia com que a formatação de data fosse exibida incorretamente em alguns idiomas ao adicionar suplementos.


- Corrigido um problema em que o suplemento Ferramentas de Análise não funcionava para alguns usuários.


- Corrigido um travamento potencial no Word ao desenhar uma imagem.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fez com que a resolução de nomes falhasse ao enviar em nome de outro usuário e resolver contra um catálogo de endereços que não é a Lista de Endereços Global.


- Corrigimos um problema que fez com que o Outlook anulasse as preferências da Caixa de Entrada Destaques configurada no OWA.


- Corrigimos um problema que fazia com que algumas pessoas não conseguissem acessar as assinaturas associadas a contas de email secundárias.


- Corrigimos um problema que fazia com que os usuários vissem mais assinaturas do que o esperado.


- Corrigimos um problema que fazia com que alguns usuários vissem suas agendas principal e secundária trocando de lugar no Painel de Navegação.


- Corrigimos um problema que faz com que os usuários vejam incorretamente uma mensagem "Isso pode demorar um pouco" ao adicionar um calendário.


- Corrigimos um problema que fazia com que os representantes aparecessem como o organizador de reuniões criadas em calendários recém-adicionados.  As reuniões neste estado não aparecem no calendário do diretor.


- Corrigimos um problema em um componente do Outlook usado por aplicativos habilitados para MAPI em computadores com processadores ARM. O problema pode fazer com que a pesquisa falhe ou causar uma carga extra no computador, pois os aplicativos em segundo plano são reiniciados repetidamente.


- Corrigimos um problema que fazia com que alguns usuários experimentassem um fechamento inesperado do Outlook sincronizar alterações na hierarquia de pastas.


- Corrigido um travamento potencial no Word ao desenhar uma imagem.


### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema relacionado a imagens vinculadas.


- Corrigido um travamento potencial no Word ao desenhar uma imagem.


### <a name="project"></a>Project

- Corrigido um problema em que o Visio podia parar de funcionar durante o fechamento.


### <a name="visio"></a>Visio

- Corrigido um problema em que o Visio podia parar de funcionar durante o fechamento.


### <a name="word"></a>Word

- Corrigido um problema para otimizar as condições para as previsões de texto a serem oferecidas.


- Corrigido um problema onde se atualizava o texto sobre a chamada automática para arquivos salvos localmente.


- Corrigido um problema de coautoria de um documento, o rascunho ativo não era apagado quando a ordem do comentário era alterada.


- Corrige um problema onde Visualizar Impressão era fechado inesperadamente.


- Corrigido um travamento potencial no Word ao desenhar uma imagem.



### <a name="office-suite"></a>Pacote Office

- Corrige um problema de confiabilidade relacionado ao suporte de aplicativos do Office em execução na sessão 0.


- Corrigido um problema em que a renomeação não estava respondendo quando um arquivo SyncBacked era aberto offline e, em seguida, renomeava o arquivo no aplicativo antes de salvá-lo.



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2102-may-11"></a>Versão 2102: 11 de maio
*Versão 2102 (Build 13801.20638)*

Atualizações de segurança listadas [aqui](microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigimos um problema que fazia com que a formatação da data fosse exibida incorretamente em alguns idiomas ao usar Suplementos.


- Corrigimos um problema que impedia a capacidade de colar como fórmulas em uma página protegida.


### <a name="outlook"></a>Outlook

- Isto permite aos usuários finais configurem o Outlook para adicionar uma reunião online a cada reunião que eles criarem.


### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema relacionado a imagens vinculadas.


### <a name="word"></a>Word

- Corrige um problema no Wordmail em que alguém não poderia enviar este item quando o 2084º caractere em um link fosse um caractere de escape.


### <a name="office-suite"></a>Pacote Office

- Corrigido um problema que fazia com que o Word fechasse inesperadamente durante a impressão de documentos longos.


- Antes dessa alteração, os modelos do Office eram exibidos mesmo que o GPO estivesse ativada para desabilitá-los. Com essa alteração, os modelos agora respeitam corretamente o GPO e são exibidos/ocultados conforme solicitado.



[//]: # (NÃO REMOVA O CONTEÚDO FINAL DO BUGDETAILS)

## <a name="version-2102-april-13"></a>Versão 2102: 13 de abril
*Versão 2102 (Build 13801.20506)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Use a caixa de diálogo avançado para criar tipos de dados:** a caixa de diálogo avançada permite que você selecione manualmente as colunas que combinam o tipo de dados que você está criando.

- **Reexibir várias páginas ao mesmo tempo:** não há mais necessidade de exibir uma página por vez - exibir várias páginas ocultas de uma vez. [Saiba mais](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a>Outlook

- **As configurações da Caixa de Entrada Destaques permanecem as mesmas em todos os dispositivos:** as suas preferências da Caixa de Entrada Destaques agora são armazenadas na nuvem. Desfrute da mesma experiência ao usar o Outlook para Windows em qualquer computador e o Outlook na Web. [Saiba mais](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **As configurações do Outlook na nuvem:** escolha as configurações do Outlook para Windows, como Respostas Automáticas, Caixa de Entrada Destaques, Privacidade, e acesse-as em qualquer PC.

- **Escolha onde Pesquisar:** O novo escopo da pesquisa a lista suspensa permite que você modifique a pesquisa com mais facilidade e alterne entre as pastas atuais e a caixa de correio atual. Agradecer a todas as pessoas no Em Breve, que forneceram comentários sobre a nova pesquisa na primeira experiência. Esse design e essa atualização acabaram com esse comentário!

- **Rascunho de mensagens com sua voz:** Utilize a nova barra de ferramentas de ditado, comandos de voz, pontuação automática e muito mais para escrever mensagens.

### <a name="word"></a>Word

- **Rascunho de documentos com sua voz:** Utilize a nova barra de ferramentas de ditado, comandos de voz e pontuação automática para rascunhar documentos.


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="access"></a>Access

- Esta alteração corrige um problema em que, em alguns casos, executar uma consulta passagem do SQL Server resultava em uma mensagem de erro indicando que havia um “estado do cursor inválido”.



### <a name="excel"></a>Excel

- Corrigimos um problema no qual a validação de dados podia ser aplicada a células inesperadamente após adicionar linhas a uma tabela em outra planilha.


- Corrigimos um problema em que a função para exibir DialogSheets não funcionava nas versões de 32 bits do Excel


- Corrigimos um problema que fazia com que as imagens fossem menores do que o esperado ao usar a opção Colar Imagem Vinculada.


- Corrigimos um problema que fazia com que a formatação de algumas tabelas dinâmicas corrompesse a pasta de trabalho ao salvar no formato .xls ou .xlt.


- Corrigimos um problema que impedia que os usuários exportassem uma pasta de trabalho do Excel para PDF.


- Foi corrigido um problema em que comandos desativados na Faixa de Opções do Office só teriam o ícone acinzentado, mas não o texto no Tema do Office Cinza Escuro.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que os usuários de tradução embutida não pudessem enviar comentários.


- Corrigimos um problema que fazia com que os usuários vissem as assinaturas com conteúdo Unicode danificadas.


- Corrigimos um problema que fazia com que os usuários vissem mais assinaturas do que o esperado.


- Corrigimos um problema que fazia o Outlook travar quando estava ocioso.


- Corrigimos um problema que fazia com que alguns usuários experimentassem o desligamento do aplicativo ao fechar as janelas de mensagens.


- Corrigimos um problema que fazia com que os usuários do Calendário Compartilhado não conseguissem definir a cor de um calendário para amarelo ou marrom.


- Corrigimos um problema que fazia com que os usuários vissem grupos de calendário duplicados aparecerem após a criação de um novo grupo.


- Corrigimos um problema que fazia com que os usuários vissem os calendários recém-adicionados não aparecendo no painel de navegação até que o Outlook fosse reiniciado.


### <a name="powerpoint"></a>PowerPoint

- Foi corrigido um problema em que comandos desativados na Faixa de Opções do Office só teriam o ícone acinzentado, mas não o texto no Tema do Office Cinza Escuro.


### <a name="word"></a>Word

- Corrigimos um problema na resolução de conflitos durante a coautoria.


- Corrigimos um problema com os controles de conteúdo de rich text.


- Corrigimos um problema com a digitação no final de um parágrafo oculto que pode resultar no travamento do aplicativo.


- Corrigimos um problema em que o Narrador podia pular um parágrafo.


- Corrigimos um problema relacionado a copiar e colar.


- Corrige um problema com cores aplicadas a ícones e gráficos SVG com efeitos 3D.


- Foi corrigido um problema em que comandos desativados na Faixa de Opções do Office só teriam o ícone acinzentado, mas não o texto no Tema do Office Cinza Escuro.


### <a name="office-suite"></a>Pacote Office

- Corrigimos um problema de confiabilidade relacionado ao suporte de aplicativos do Office em execução na sessão 0.


- Foi corrigido um erro que ocasionalmente fazia com que o texto no Outlook se tornasse transparente e, portanto, não legível.


- Corrigido um problema que poderia acontecer ao usar o narrador dentro de um texto que contém equações matemáticas.


- Foi corrigido um problema em que o Ditado estava desabilitado para usuários da Nuvem da Comunidade Governamental


- Corrigimos um problema em que os usuários não conseguiam salvar um arquivo ao abrir um arquivo aberto anteriormente com edições não salvas, mas agora o arquivo foi excluído. Após a correção, os usuários receberão uma mensagem amigável para informá-los que o arquivo foi excluído, portanto, o usuário pode escolher descartar as alterações ou SalvarComo o arquivo.


- Foi corrigido o problema de falha de renomeação ao abrir um arquivo SyncBacked offline e, em seguida, renomear o arquivo no aplicativo antes de salvá-lo.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2101-april-13"></a>Versão 2101: 13 de abril
*Versão 2101 (Build 13628.20664)*

Atualizações de segurança listadas [aqui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2101-march-09"></a>Versão 2101: 09 de Março
*Versão 2101 (Build 13628.20528)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrige um problema em que o Excel falhava ao iniciar ou fechava inesperadamente se certas configurações de proteção contra exploits de Segurança do Windows (SimExec, CallerCheck) estivessem em uso


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que o ícone de criptografia não fosse exibido para emails enviados usando a somente a opção de criptografia.


- Corrigimos um problema que fazia com que os emails fossem enviados como assinados digitalmente depois que o usuário desmarcou essa opção.


- Corrigimos um problema que causava problemas ao exibir a assinatura padrão correta no OWA.


- Corrigimos um problema que causava um travamento dos usuários das Configurações de Nuvem ao atualizar as configurações.


- Corrigimos um problema que algumas vezes fez com que o aplicativo fechasse inesperadamente quando os usuários estavam pesquisando no Outlook.


- Corrigimos um problema que fazia com que usuários com Caixas de Correio Compartilhadas ou Delegadas com grandes hierarquias em seus perfis travassem.


- Corrigimos um problema que fazia com que alguns usuários experimentassem o Outlook para fechar inesperadamente em determinados cenários de pesquisa.


### <a name="project"></a>Project

- Corrigimos um problema em que, quando um recurso de custo era atribuído a uma tarefa de marco, o custo da linha de base não era acumulado corretamente.


- Correção de um problema em que a bordas não apareciam para tarefas no modo de exibição Planejador de Equipe.


- Correção de um problema em que arrastar e soltar não funcionava para tarefas no modo de exibição Planejador de Equipe.


### <a name="office-suite"></a>Pacote do Office

- Corrige um problema relacionado às notificações de eventos do controlador de mídia.


- Corrige um problema relacionado ao tempo do motor do media player.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2012-march-09"></a>Versão 2012: 09 de Março
*Versão 2012 (Compilação 13530.20628)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Requer que os usuários apliquem rótulos de confidencialidade:** Os usuários serão solicitados a aplicar um rótulo de confidencialidade se a política da sua organização exigir isso.

### <a name="powerpoint"></a>PowerPoint

- **Requer que os usuários apliquem rótulos de confidencialidade:** Os usuários serão solicitados a aplicar um rótulo de confidencialidade se a política da sua organização exigir isso.

### <a name="word"></a>Word

- **Requer que os usuários apliquem rótulos de confidencialidade:** Os usuários serão solicitados a aplicar um rótulo de confidencialidade se a política da sua organização exigir isso.


## <a name="version-2012-february-09"></a>Versão 2012: 09 de fevereiro
*Versão 2012 (Build 13530.20528)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="excel"></a>Excel

- **Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros. [Saiba mais](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.

- **Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H. [Saiba mais](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros. [Saiba mais](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Aumente o tempo entre as reuniões consecutivas:** Dê aos participantes tempo para recuperar o fôlego ou viajar entre os locais, configurando as reuniões para começarem 5-10 minutos atrasado por padrão. [Saiba mais](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.

- **Cada reunião online:** atualize suas configurações de calendário para tornar todas as reuniões que você criar uma Reunião de Equipe por padrão, para que você não precise mais se lembrar de clicar na opção Reunião de Equipes.

- **Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H. [Saiba mais](/microsoft-365/compliance/sensitivity-labels)

- **Cada reunião online:** atualize suas configurações de calendário para tornar todas as reuniões que você criar uma Reunião de Equipe por padrão, para que você não precise mais se lembrar de clicar na opção Reunião de Equipes.

- **Novo localizador de sala:** Pesquisar salas de conferência por diferentes recursos.

- **Nova experiência de reserva de sala de conferência e espaço de trabalho**: a experiência de reserva de sala de conferência foi atualizada e, com ela, adicionamos recursos que permitem que você agende também espaços de trabalho individuais


### <a name="powerpoint"></a>PowerPoint

- **Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros. [Saiba mais](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />Consulte os detalhes na [postagem do blog](https://insider.office.com/pt-BR/blog/svg-content-office-third-party-apps)

- **Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.

- **Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H. [Saiba mais](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **Novos estênceis e formas do Azure:** Nós adicionamos muitos outros estênceis para ajudá-lo a criar diagramas do Azure atualizados. [Saiba mais](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **Suporte à área de transferência SVG:** agora você pode colar conteúdo SVG do Office em aplicativos de terceiros. [Saiba mais](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Registro em log de auditoria de rótulos de confidencialidade:** Quando os usuários aplicam, alteram ou removem rótulos de confidencialidade em seus documentos e emails, essas informações são agora disponibilizadas aos administradores nos logs de auditoria do Microsoft 365.

- **Clientes governamentais: aplique rótulos de confidencialidade aos seus documentos e emails:** Recursos de rótulos de confidencialidade agora estão disponíveis para clientes nos ambientes GCC e GCC-H. [Saiba mais](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Esta alteração resolve um problema com a exibição adequada de fontes em equações.


- Corrigido um problema em que alguns usuários veriam incorretamente uma barra de mensagens informando-os de uma nova versão de um arquivo durante a coautoria.


- Corrigido um problema em que o Excel podia deixar as macros desabilitadas sem que fosse solicitado ao abrir um arquivo de suplemento do Excel contendo Macros do Excel 4.0.


- Corrige um problema em que o Excel não pode ser iniciado ou encerrado inesperadamente se determinadas configurações de proteção do Windows Security Exploit (SimExec, CallerCheck) estiverem em uso.


- Corrigido um problema em que o Excel poderia fechar inesperadamente ao usar o menu "Mostrar Valores Como" para uma Tabela Dinâmica.


- Corrigimos um problema que quebrava algumas macros legadas do Excel 4.0 e Excel 5.0, bem como algumas chamadas VBA para dialogsheets.show.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que uma assinatura editada não salvasse depois de solicitar que o usuário o fizesse.


- Corrigimos um problema que fazia com que alguns usuários experimentassem o fechamento inesperado do Outlook em determinados cenários de pesquisa.


- Corrigimos um problema que fazia com que alguns clientes se deparassem com um travamento durante o carregamento de seus calendários.


- Corrigimos um problema que fazia com que usuários que têm Caixas de Correio Compartilhadas ou Delegadas com grandes hierarquias em seus perfis se deparassem com um travamento.


### <a name="powerpoint"></a>PowerPoint

- Corrigimos um problema em que o comando de tamanho de fonte, adicionado ao QAT, completava automaticamente para o tamanho de fonte definido mais próximo ao atualizá-lo.


- Esta alteração resolve um problema com a exibição adequada de fontes em equações.


- Esta alteração resolve um problema com os preenchimentos de caminho ao aplicar operações de Mesclar Formas com determinadas geometrias.


### <a name="office-suite"></a>Pacote do Office

- O Anaheim WebView ainda não oferece suporte ao Proteção de Informações do Windows (WIP). Com essa correção, a plataforma de suplemento do Office volta ao nível inferior do WebView em um ambiente habilitado para WIP. Pode ser Edge Spartan WebView ou Trident WebView, dependendo do ambiente do computador do cliente. Ambos os WebViews de nível inferior suportam WIP.


- Dimensionamento binário otimizado.


- Corrigida a sequência de fechamento do arquivo para que todos os componentes interdependentes sejam fechados normalmente.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2011-february-09"></a>Versão 2011: 09 de fevereiro
*Versão 2011 (Build 13426.20658)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)

## <a name="version-2011-january-12"></a>Versão 2011: 12 de janeiro
*Versão 2011 (Build 13426.20526)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)


[//]: # (NÃO REMOVER O INÍCIO DO CONTEÚDO DE DETALHES FEATUREDETAILS)

### <a name="feature-updates"></a>Atualizações de recursos
### <a name="access"></a>Access

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **Criar variáveis para usar em fórmulas:** Melhorar o desempenho, a legibilidade e a capacidade de composição com a função LET. Esta função permite que você crie variáveis nomeadas em fórmulas novas ou pré-existentes. [Saiba mais](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Consulte os detalhes na [postagem do blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Criar um tipo de dados personalizado no Power Query:** use uma fonte de dados para criar um tipo de dados personalizado que permite que você carregue várias informações relacionadas em uma coluna. [Saiba mais](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />Consulte os detalhes na [postagem do blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)

- **Nomeie a nova planilha após a consulta fonte:** quando os dados são carregados na nova planilha, a planilha será nomeada baseada no nome da consulta de origem.

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a>PowerPoint

- **Biblioteca de Vídeo:** eleve seus documentos com uma biblioteca de vídeo de royalties livres e gratuitas selecionadas disponíveis no aplicativo.

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **Alterne automaticamente os temas do Office:** o Office pode alternar automaticamente entre temas para corresponder às suas configurações de tema do Windows 10. Vá até Arquivo > Conta, e escolha "Usar configuração do sistema" no menu suspenso do Tema do Office. [Saiba mais](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NÃO REMOVER O FINAL DO CONTEÚDO DE DETALHES FEATUREDETAILS)

<br/>

[//]: # (NÃO REMOVER O INÍCIO DE CONTEÚDO BUGDETAILS)

### <a name="resolved-issues"></a>Problemas resolvidos
### <a name="excel"></a>Excel

- Corrigido um problema em que o Excel mostrava incorretamente uma barra de mensagens de que uma nova versão do arquivo está disponível e forçava o usuário a salvar suas alterações em uma cópia da pasta de trabalho ou descartar suas alterações.


- Corrigido um problema em que o Excel pode deixar macros desativadas sem avisar ao abrir um arquivo de Suplemento do Excel contendo Macros do Excel 4.0.


### <a name="outlook"></a>Outlook

- Corrigimos um problema que fazia com que alguns usuários não vissem assinaturas no menu suspenso de assinaturas, apesar de terem uma ou mais assinaturas configuradas.


- Adicionamos uma regkey que permite que os clientes desabilitem a inclusão de filetime para anexos nas operações do IDataObject (ou seja, arrastar e soltar, área de transferência).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments. REG_DWORD IncludeFileTimesInDataObject. 0 = filetimes são excluídos. 1 = (padrão) filetimes são incluídos.


- Corrigimos um problema que fazia com que as imagens embutidas desaparecessem ao responder a uma mensagem com um rótulo de proteção da Proteção de Informações do Azure.


- Corrigimos um problema que causava a interrupção do evento MailItem.BeforeAttachmentAdd.


- Corrigimos um problema que fazia com que o campo Para ficasse em branco ao enviar um relatório de status em uma tarefa.


- Corrigimos um problema que fazia com que os participantes originais de algumas reuniões recebessem um cancelamento quando outro participante encaminhava a reunião.


### <a name="powerpoint"></a>PowerPoint

- Corrigido um problema que fazia com que alguns arquivos do PowerPoint corrompidos não abrissem corretamente mesmo após uma operação de reparo de documento.


- Corrigimos um problema que causava um erro ao salvar o arquivo após duplicar um slide que continha um áudio recém-gravado.


- Resolvemos um problema de VBA em que Slide.Shapes.AddMediaObject2 travava com formatos de vídeo herdados (MPG-1,Mpeg-2).


- Essa alteração resolve um problema com a manipulação de erros que podem ocorrer durante o carregamento do vídeo.


- Corrigido um problema com copiar/colar uma equação do Word para o PowerPoint.


### <a name="project"></a>Microsoft Project

- Corrigido um problema em que projetos específicos podiam ser abertos se houvesse um problema com o arquivo de projeto em uma parte específica da carga.


### <a name="word"></a>Word

- Corrigido um bug de declaração exposto por portas otimizadas que afetavam o Word.


- Corrigimos um problema no qual os estilos de documento são substituídos por outros estilos do modelo.


- Essa alteração resolve um problema com o cursor ao editar um documento.


- Corrigido um problema com copiar/colar uma equação do Word para o PowerPoint.


### <a name="office-suite"></a>Pacote do Office

- Corrigido um problema em que a instalação de uma versão mais recente do Office em relação a certas versões mais antigas pode resultar em funcionalidade prejudicada (como a impossibilidade de usar o Power Query) devido à falta de entradas de registro.


- Corrigido um problema de arquivo que seria aberto como NOT SyncBacked quando o URL do cache e o URL do OneDrive NÃO correspondessem.


- Corrigimos um problema em que o SaveRequestManagerCam estava fazendo com que o aplicativo fosse fechado em vez de retornar um erro.



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

## <a name="version-2010-january-12"></a>Versão 2010: 12 de janeiro
*Versão 2010 (Build 13328.20550)*

Atualizações de segurança listadas [aqui](./microsoft365-apps-security-updates.md)



[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)


[//]: # (NÃO REMOVER O FIM DO CONTEÚDO BUGDETAILS)

[//]: # (NÃO REMOVER FIM)

> [!NOTE]
> Se precisar de ajuda com um problema ao usar o Office, recomendamos que você publique suas dúvidas no [Fórum de Respostas da Microsoft](https://answers.microsoft.com/) ou na [Comunidade de Tecnologia](https://techcommunity.microsoft.com/) ou contate o [suporte](https://support.microsoft.com/contactus).


[//]: # (NÃO MODIFICAR O INÍCIO DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)
[//]: # (|Win32|MEC|Production|Feature|16.0.13929.20408|version-2104-june-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (NÃO MODIFICAR O FIM DE CONTEÚDO DE METADADOS DO CENTRO DE ADMINISTRAÇÃO)

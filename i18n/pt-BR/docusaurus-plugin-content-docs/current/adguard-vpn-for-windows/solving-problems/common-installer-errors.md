---
title: Erros comuns do instalador
sidebar_position: 2
---

Este artigo contém alguns dos erros mais comuns que você pode encontrar durante a instalação do AdGuard VPN para Windows e possíveis maneiras de resolvê-los.

### Erro 5: Acesso negado {#error-5}

Este erro ocorre quando há algo errado com as permissões. Pode haver vários motivos diferentes pelos quais o instalador do AdGuard VPN não possui as permissões necessárias para concluir corretamente o processo de instalação. Você pode tentar os seguintes passos:

- Desative temporariamente seus antivírus. Alguns deles podem interferir na instalação, dependendo de suas configurações.

- Escolha uma pasta de instalação diferente. É possível que a pasta de instalação atual tenha algumas restrições de acesso. Certifique-se também de não selecionar uma unidade externa, um drive virtual, etc.

- Reinicie o computador. Às vezes, os problemas de permissão são temporários e podem ser resolvidos reiniciando o PC.

### Erro 112: O disco está cheio, Erro 1632: Pasta temporária cheia ou inacessível {#error-112}

Estes são dois erros diferentes com soluções muito semelhantes. Como seus nomes sugerem, o instalador AdGuard VPN não encontrou espaço em disco suficiente para concluir a instalação. Há várias coisas que você pode fazer para tentar corrigir o problema:

- Desinstale alguns programas ou exclua arquivos desnecessários da unidade em que você estava tentando instalar o AdGuard VPN.

- Baixe, instale e execute [AdwCleaner](http://www.bleepingcomputer.com/download/adwcleaner/), um software gratuito da Malwarebytes. Entre outras coisas, ele irá limpar seu sistema de todos os "restos" de arquivos que permanecem após a desinstalação incorreta de programas e similares. Isso ajudará a limpar algum espaço em disco.

- Reinicie o computador. Às vezes, os arquivos temporários podem ocupar uma quantidade considerável de espaço em disco e reiniciar o PC é a maneira mais simples de se livrar deles.

### Erro 1601: o instalador do Windows não está acessível {#error-1601}

Pode-se dizer que este é um subtipo específico do Erro 1603. As soluções possíveis são semelhantes:

- Inicie e registre novamente o serviço Instalador Microsoft. Isso dá um pouco de trabalho.

    1) Pressione *Win + R* e digite **services.msc**. 2) Localize-o na lista e clique duas vezes em *Instalador do Windows*. 3) Pressione o botão *Iniciar* em *Status do serviço* e pressione *OK*. Se o status do serviço for **executando**, você precisa clicar em *Parar* primeiro e depois em *Iniciar*. 4) Pressione *Win + R*, digite ***msiexec /unregister*** e pressione *Enter*. 5) Pressione *Win + R* novamente, digite ***msiexec /regserver*** e pressione *Enter*

- Reinicie o PC e inicie a instalação novamente. Às vezes, isso é suficiente para resolver o problema.

### Erro 1602: Cancelado pelo usuário {#error-1602}

Se você recebeu esse código de erro, é provável que tenha interrompido o processo de instalação manualmente de uma forma ou de outra. O que você pode fazer:

- Não feche a janela do instalador. Quando a instalação estiver concluída, ela será fechada automaticamente.

- Se uma janela de diálogo aparecer durante a instalação, clique em "Sim" para conceder ao instalador as permissões necessárias. Clicar em "Não" cancelará a instalação.

- Não inicie outros processos enquanto a instalação estiver em andamento.

### Erro 1603: Erro fatal durante a instalação {#error-1603}

Este erro parece mais assustador do que realmente é. Na realidade, esse é um erro bastante genérico que pode ter muitas causas diferentes e algumas delas são facilmente corrigidas. Tente as seguintes soluções:

- Pressione a tecla *Win*, procure por *Prompt de comando*e execute-o. Lá, digite `sfc /scannow` e pressione *Enter*.

- Escolha uma pasta de instalação diferente. É possível que a pasta de instalação atual tenha algumas restrições de acesso. Certifique-se também de não selecionar uma unidade externa, um drive virtual, etc.

- Desinstale o AdGuard VPN usando nossa ferramenta de desinstalação especial [](../../installation#advanced) e repita a instalação.

- Inicie e registre novamente o serviço Microsoft Installer. Isso dá um pouco de trabalho.

    1) Pressione *Win + R* e digite ***services.msc***. 2) Encontre na lista e clique duas vezes em *Instalador do Windows*. 3) Pressione o botão *Iniciar* em *Status do serviço* e pressione *OK*. Se o status do serviço for **executando**, você precisa clicar em *Parar* primeiro e depois em *Iniciar*. 4) Pressione *Win + R*, digite ***msiexec /unregister*** e pressione *Enter*. 5) Pressione *Win + R* novamente, digite ***msiexec /regserver*** e aperte *Enter*

- É preciso ter todas as permissões da unidade para a instalação. É possível que o erro 1603 ocorra porque você não tem permissões totais no local do arquivo. Além disso, esta opção não é tão fácil quanto algumas das outras soluções:

    1) Abra *File Explorer*, clique com o botão direito do mouse na unidade que contém o local de instalação e selecione *Propriedades*. 2) Vá para a aba *Segurança* e clique em *Editar*. 3) Clique uma vez em *SISTEMA* e certifique-se de que a caixa *Permitir* de cada item em *Permissões para SISTEMA* esteja marcada (se isso for possível). Faça a mesma verificação para *Administradores*. 4) Clique em *OK* para voltar para a caixa de diálogo *Propriedades*. Em seguida, clique em *Avançado*. 5) Clique em *Alterar permissões*. 6) Na aba *Permissões*, clique duas vezes em *Administradores*. 7) Selecione *Esta pasta, subpastas e arquivos* para o campo *Aplica-se a* e marque todas as *Permissões básicas*disponíveis. Depois disso, aperte *OK*. 8) Faça a mesma operação acima (a partir do item 7) para *SYSTEM*. 9) Clique em *OK* até o fim. Tente instalar o AdGuard novamente.

### Erro 1618: Outra instalação já está em andamento {#error-1618}

Este erro ocorre quando várias instâncias do instalador do AdGuard VPN são iniciadas ao mesmo tempo. O que fazer se você receber esta mensagem de erro:

- Reinicie o seu PC e inicie o instalador novamente. Quando você reiniciar o computador, todos os processos em andamento serão interrompidos, incluindo todas as cópias do instalador.

- Não faça vários cliques no instalador, mesmo que ele não inicie imediatamente. Pode ser que a exibição da IU do instalador leve alguns segundos.

### Erro 1638: outra versão deste produto já está instalada {#error-1638}

É muito provável que você já tenha instalado o AdGuard VPN antes.

- Verifique se o AdGuard VPN já está instalado no seu computador. Você pode fazer isso pressionando a tecla *Win* e digitando ***AdGuard VPN***.

- Pode ser que haja alguns arquivos restantes de uma instalação anterior do AdGuard VPN. Desinstale o AdGuard usando nossa [ferramenta de desinstalação](../../installation#advanced) e repita a instalação.

### Outros erros {#other}

Se você encontrou um erro que não está listado acima, é possível que possamos resolvê-lo sozinhos. Mas, para isso, precisamos de seus arquivos de log. Por favor, execute as seguintes etapas:

- Localize e arquive os **registros de instalação do AdGuard VPN** conforme descrito [neste artigo](https://adguard.com/kb/adguard-for-windows/solving-problems/installation-logs/).

- Localize e salve os registros no disco **Visualizador de Eventos**. [Este artigo](https://adguard.com/kb/adguard-for-windows/solving-problems/system-logs/) explica como fazer isso.

Envie por e-mail todos esses arquivos das duas etapas anteriores para **support@adguard.com** e descreva o problema no corpo da mensagem. Nossa equipe de suporte responderá o mais rápido possível.

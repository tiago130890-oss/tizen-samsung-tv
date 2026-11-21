# tizen-samsung-tv
tizen samsung tv

Passo 1: Preparar a TV Samsung
Na sua TV, abra a loja Apps.

Com o controle remoto, digite 12345 (se o seu controle não tiver números, aperte o botão 123 ou 123/Configurações na tela para abrir o teclado numérico virtual).

Na janela Developer Mode que vai abrir:

Mude para ON.

Digite o IP do seu computador (ou celular Android) que está na mesma rede Wi-Fi.

Clique em OK.

Reinicie a TV completamente: Segure o botão de desligar no controle remoto por uns 5 segundos até a TV reiniciar e mostrar o logotipo da Samsung (apenas apertar para desligar coloca em standby e não ativa o modo desenvolvedor).

Passo 2: Baixar e rodar o TizenBrew Installer (PC ou Android)
Você não precisa instalar o Tizen Studio complexo. O desenvolvedor criou o TizenBrew Installer exatamente para automatizar tudo:

Acesse a página oficial de lançamentos no GitHub:

[github.com/reisxd/TizenBrewInstaller/releases](https://github.com/reisxd/TizenBrewInstaller/releases)

Baixe a versão para o seu sistema:

Windows: TizenBrewInstaller-win-x64.exe

Linux: TizenBrewInstaller-linux-x64

Android (via Termux): você pode rodar a versão CLI, ou usar o Apps2Samsung no Android apontando para o arquivo TizenBrew.wgt (disponível em [github.com/reisxd/TizenBrew/releases](https://github.com/reisxd/TizenBrew/releases)).

Abra o TizenBrew Installer no PC (na mesma rede Wi-Fi da TV):

Ele vai procurar e listar o IP da sua TV automaticamente (ou você pode digitar o IP da TV manualmente).

Clique para conectar e selecione a opção de instalar o TizenBrew.

Nota: Se a sua TV for modelo 2023 ou mais recente (Tizen 7 ou 8+), o próprio instalador vai pedir para você fazer login rápido na sua conta Samsung para gerar e assinar o certificado digital automaticamente.

Passo 3: Configurar o TizenTube dentro do TizenBrew (na TV)
Depois que o ícone da caneca de cerveja (TizenBrew) aparecer na barra de aplicativos da TV:

Abra o TizenBrew.

Na tela inicial dele, o módulo @foxreis/tizentube geralmente já vem pré-instalado.

Dica importante para parar de ver propagandas:

Se ele já estiver lá, aperte o botão Azul (ou navegue até Module Manager / Gerenciador de Módulos) para garantir que ele baixe a versão mais recente do pacote NPM.

Caso não esteja na lista, vá em Add Module (Adicionar Módulo), selecione NPM e digite exatamente:@foxreis/tizentube

Ative a inicialização automática (opcional, mas recomendado):

NOVO APP TIZEN TUBE COBALT MAIS ATUAL LINK ..https://github.com/reisxd/TizenTube/releases


Nas configurações do TizenBrew (botão Verde/Settings), ative o Auto Launch selecionando o @foxreis/tizentube. Assim, toda vez que você clicar no ícone da cerveja na TV, ele já abre direto no YouTube sem anúncios.

Como saber se funcionou: Assim que abrir um vídeo, aperte para cima/baixo para abrir a barra de reprodução e veja se aparece o ícone de configurações do TizenTube (ou o botão verde/vermelho/azul funcionando para pular patrocínios). Se o botão do TizenTube estiver lá, o bloqueio está ativo!

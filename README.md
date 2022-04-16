
## AutoHotkey - NumLock - Mantendo o teclado numérico sempre ativo.

**Problema** -   No mundo atual a tecla NumLock é uma das teclas mais inúteis. Eu nunca precisei usar as outras funções do teclado numérico... já que elas estão a poucos centímetros.



**Solução** -   Desta forma eu uso o AutoHotKey com o script de uma linha só para desativar a capacidade da tecla NumLock ser alternada.

O AutoHotkey é um excelente aplicativo gratuito para Windows que permite criar atalhos de teclado para automatizar várias tarefas do Windows de forma rápida e personalizada. Ele pode ser baixado no site:

	https://www.autohotkey.com/


* Copie/cole a linha abaixo no Bloco de Notas.

 		SetNumLockState, AlwaysOn 

* Salve como algo como *numlock-always-on.ahk*

    Atenção para não salvar como arquivo txt, não salve como numlock-always-on.ahk .txt


_

## Iniciar Script Automaticamente
Aqui está como você pode agendar o AutoHotkey para inicializar com o Windows.
 
### Adicionar AutoHotkey à pasta de inicialização


TECLA WIN - Neste tutorial quando fizermos menção a tecla WIN, estamos nos referindo a tecla com o símbolo do windows localizada no teclado no lado esquerdo, enter as teclas Control e Alt.

Esta é a forma mais rápida de iniciar um script AutoHotkey: incluir o seu script na pasta de inicialização. 

* Para isso, pressione Win+ R, cole o trecho mostrado abaixo e pressione o botão Enter.


         %APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup


Este comando abrirá a pasta de inicialização específica do usuário. 


* Clique com o botão direito do mouse no espaço vazio, selecione a opção “Novo” e depois “Criar atalho”.

* Na janela “Criar atalho”, clique no botão “Procurar”. Selecione seu script AutoHotkey e clique em “Avançar” para continuar.

* Nesta tela digite o nome do atalho e clique no botão “Finish” para concluir o procedimento.
 

Caso você deseje que o script AutoHotkey seja iniciado independentemente de qual usuário esteja conectado, crie o atalho na pasta abaixo. É a pasta de inicialização para todos os usuários em seu sistema.


         %programdata%\Microsoft\Windows\Start Menu\Programs\Startup
		 

Seu item de inicialização personalizado foi criado. Sempre que você iniciar seu sistema e efetuar login, o script AutoHotkey será iniciado automaticamente.


### Outras aplicações para o AutoHotKey 
Eu tenho um AutoHotkey que funciona o tempo todo para fornecer todos os tipos de automação - como alterar @@ automaticamente para meu endereço de e-mail bastante longo para evitar que eu precise digitar tudo vez após vez ou corrigir automaticamente alguns dos meus erros de digitação - então foi muito fácil para mim adicionar uma das frases acima ao script.


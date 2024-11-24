<h1 align="left">AndroidBox app player</h1>

###

<p align="left">Este é um emulador Android baseado no QEMU, projetado para rodar Android-x86 em sua máquina. Ele suporta a execução de Android usando o QEMU, com opções para personalizar a experiência, incluindo opções de controle, tela e aceleração.</p>

###

<h3 align="left">Recursos</h3>

###

<p align="left"></p>

###

<p align="left">Emulador Android-x86: Roda o sistema Android-x86 em seu computador usando QEMU.<br><br>Controle: Suporta joystick genérico e controle Xbox 360.<br><br>Tela: Suporte para tela cheia e janela.<br><br>SDL2: Suporte para exibição através da biblioteca SDL2.<br><br>Configuração Simples: Use a linha de comando para controlar as configurações do emulador<br><br>criador do projeto: matheus souza 10 studios.</p>

###

<p align="left"></p>

###

<h3 align="left">Instalação</h3>

###

<h4 align="left">Passo 1: Instale o pacote</h4>

###

<h5 align="left">Você pode instalar o emulador via pip diretamente do PyPI:</h5>

###

<p align="left">pip install androidbox-emulator</p>

###

<p align="left"></p>

###

<h4 align="left">Passo 2: Como Usar</h4>

###

<p align="left">Após a instalação, você pode executar o emulador utilizando o comando androidbox-app-player.</p>

###

<h4 align="left">Comandos Suportados</h4>

###

<p align="left">Você pode configurar o emulador com diferentes opções via linha de comando. Aqui estão os comandos que você pode usar:</p>

###

<h5 align="left"></h5>

###

<p align="left">--window: Executa o emulador em uma janela normal.<br><br>--fullscreen: Executa o emulador em tela cheia.<br><br>--sdl2: Usa a biblioteca SDL2 para exibir a interface gráfica.<br><br>--joystick: Ativa um joystick genérico.<br><br>--joystick-x360: Ativa um controle Xbox 360.</p>

###

<h5 align="left"></h5>

###

<h3 align="left">Exemplo de Comando</h3>

###

<p align="left">Aqui estão alguns exemplos de como executar o emulador com diferentes opções:</p>

###

<h4 align="left">Emulador em janela normal:</h4>

###

<p align="left">androidbox-app-player --window</p>

###

<h4 align="left">Emulador em tela cheia com SDL2 e joystick genérico:</h4>

###

<p align="left">androidbox-app-player --fullscreen --sdl2 --joystick</p>

###

<h4 align="left">Emulador em janela normal com joystick Xbox 360:</h4>

###

<p align="left">androidbox-app-player --window --joystick-x360</p>

###

<h5 align="left"></h5>

###

<h3 align="left">Arquivos Necessários</h3>

###

<p align="left">O pacote já inclui todos os arquivos necessários para rodar o emulador, como o QEMU, o SDL2, os arquivos de sistema e dados, e os ícones.<br><br>Esses arquivos são necessários para o funcionamento do emulador.</p>

###

<p align="left"></p>

###

<h3 align="left">Passo 3: Inicializando o Emulador</h3>

###

<p align="left">Para iniciar o emulador, basta rodar o comando desejado após a instalação. O código abaixo mostra como ele pode ser executado com diferentes configurações:</p>

###

<p align="left">androidbox-app-player --fullscreen --sdl2 --joystick-x360</p>

###

<p align="left">Este comando irá:<br><br>Iniciar o emulador em tela cheia.<br><br>Usar a SDL2 para a interface gráfica.<br><br>Ativar o joystick Xbox 360 como dispositivo de entrada.</p>

###

<p align="left"></p>

###

<h3 align="left">Passo 4: Usando o ADB</h3>

###

<p align="left">Após iniciar o emulador, você pode se conectar a ele usando o ADB. O servidor ADB será automaticamente iniciado pelo script. Para verificar se o dispositivo está disponível, execute:</p>

###

<p align="left"></p>

###

<p align="left">adb devices</p>

###

<p align="left"></p>

###

<p align="left">Se o dispositivo estiver funcionando corretamente, você verá o emulador listado.</p>

###

<p align="left"></p>

###

<h3 align="left">Licença</h3>

###

<p align="left">Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.</p>

###

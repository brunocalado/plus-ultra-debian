# Descrição #
Esse script habilita funcionalidades e instala programas essenciais após a instalação do Debian Squeeze.
<br><br><br>

<hr />
<h1>Instruções do Script Principal</h1>
<h2>Instalação</h2>
<ul><li>Faça o download da última versão desse script na guia <a href='http://code.google.com/p/plus-ultra-debian/downloads/list'>Downloads</a>
</li><li>Entre no terminal<br>
<ul><li><pre><code>Pressione Alt+F2 e digite gnome-terminal</code></pre>
</li></ul></li><li>Descompacte o arquivo<br>
<ul><li><pre><code>tar xvf sourceV????.tar</code></pre>
</li></ul></li><li>Altere o nome do usuário na linha 3 para nome de usuário desejado<br>
<ul><li><pre><code>nano debian_pos-instalacao.sh</code></pre>
</li></ul></li><li>Mude o usuário para root<br>
<ul><li><pre><code>su</code></pre>
</li></ul></li><li>Passe permissão de execução para o script<br>
<ul><li><pre><code>chmod +x debian_pos-instalacao.sh</code></pre>
</li></ul></li><li>Execute o script<br>
<ul><li><pre><code>./debian_pos-instalacao.sh</code></pre>
<h2>Observação</h2>
Durante o processo o usuário será solicitado para selecionar algumas opções.<br>
<br><br>
<hr />
<h1>Repositórios, Configurações e Instalações Realizadas</h1></li></ul></li></ul>

<h2>Repositórios</h2>
<ul><li>Debian Multimedia<br>
</li><li>Debian Backports<br>
<br><br>
<h2>Funcionalidades</h2>
</li><li>Habilita o sudo. Permite que o usuário use sudo sem senha para realizar tarefas de root.<br>
</li><li>Habilita auto completar para o root<br>
</li><li>Fornece alias úteis para o usuário e root<br>
</li><li>Habilita terminal colorido para o root<br>
<br><br>
<h2>Programas Instalados</h2>
</li><li>Google Chrome<br>
</li><li>Dropbox<br>
</li><li>Wine<br>
</li><li>VirtualBox<br>
</li><li>Java Sun<br>
</li><li>Compactadores e Descompactadores<br>
<ul><li>bzip2<br>
</li><li>rar<br>
</li><li>zip<br>
</li><li>p7zip-full<br>
</li></ul></li><li>Servidor SSH<br>
</li><li>Pacotes Multimedia<br>
<ul><li>VLC<br>
</li><li>Avidemux<br>
</li><li>Recordmydesktop<br>
</li><li>Audacity<br>
</li><li>youtube2mp3<br>
</li><li>mpg321 (com alias para play)<br>
</li></ul></li><li>Editores<br>
<ul><li>VIM<br>
</li></ul></li><li>Desenvolvimento<br>
<ul><li>gcc/g++<br>
</li><li>binutils<br>
</li><li>mercurial<br>
</li></ul></li><li>Ferramentas Administrativas<br>
<ul><li>htop<br>
</li><li>iftop<br>
</li><li>galternatives<br>
</li><li>macchanger<br>
<br><br>
<h1>Instruções para os Scripts Secundários</h1>
<h2>Lista com os Scripts Secundários</h2>
</li></ul></li><li>instalar-rvm.sh - Instala RVM, Ruby e Rails<br>
<h2>Instalação</h2>
</li><li>Junto com o download existem arquivos com o nome no seguinte formato instalar-XXXXX.sh<br>
</li><li>Leia e siga as instruções no início do arquivo<br>
<ul><li><pre><code>nano instalar-XXXXX.sh</code></pre>
</li></ul></li><li>Passe permissão de execução para o script<br>
<ul><li><pre><code>chmod +x instalar-XXXXX.sh</code></pre>
</li></ul></li><li>Execute o script<br>
<ul><li><pre><code>./instalar-XXXXX.sh</code></pre>
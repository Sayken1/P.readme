<p style="font-size: 25px;" align="center">
blz</p>
<br>

<p align="center">
<img src="https://i.pinimg.com/736x/cd/ec/78/cdec7857e6f1f50355600f0ebe14b45f.jpg" width="75%">
</p>

### [comercimento](https://www.youtube.com/watch?v=BtpilbMdN-w&pp=ugUHEgVwdC1CUg%3D%3D)
</p>
<br>
<br>

<p style="font-size: 25px;" align="center">
<b>Comandos CMD</b>
</p>

<ul style="font-size: 20px;">
    <li><b>cd</b></li>
    <ul style="font-size: 15px;">
        <li><u>Seleciona e se locomove por um caminho</u> entre as pastas do Windows.</br></br>
        Importante:</br>
        <b>\</b> indica o início ou separação de pastas em um caminho.</br>
        <b>cd /d</b> permite trocar de disco e entrar em uma pasta.</br>
        Ex: <b>cd /d D:\projeto</b></li>
        </br>
        <li><b>" "</b> usar aspas duplas em caminhos que possuem espaços.</br>
        Ex: <b>cd "C:\Meus Projetos\Programa"</b></li>
        </br>
        <li>Pode se usar <b>cd ..</b> para <u>voltar uma pasta</u>.</li>
        </br>
        <li><b>cd \</b> volta diretamente para a raiz do disco atual.</li>
        </br>
        <li><b>cd</b> sozinho mostra o caminho atual.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>dir</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra todos os arquivos e pastas</u> existentes no caminho atual.</li>
        <li><b>dir /a</b> mostra também arquivos e pastas ocultos.</li>
        <li><b>dir /p</b> mostra o resultado página por página.</li>
        <li><b>dir /s</b> procura e mostra arquivos e pastas também dentro dos subdiretórios.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>mkdir / md</b></li>
    <ul style="font-size: 15px;">
        <li><u>Cria um novo diretório (pasta).</u></li>
        <li><b>mkdir projeto</b> cria uma pasta chamada projeto no caminho atual.</li>
        <li><b>mkdir "Meu Projeto"</b> cria uma pasta que possui espaço no nome.</li>
        <li><b>mkdir pasta1\pasta2</b> pode criar uma estrutura de diretórios conforme os diretórios-pai existentes ou a capacidade do comando.</li>
        <li><b>md</b> é uma forma abreviada de usar mkdir.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>type nul ></b></li>
    <ul style="font-size: 15px;">
        <li><u>Cria um arquivo vazio</u> no caminho atual.</li>
        <li>Ex: <b>type nul > arquivo.txt</b></li>
        <li>Também pode ser utilizado para criar arquivos com outros tipos.</li>
        <li>Ex: <b>type nul > programa.c</b></li>
        <li>Se o arquivo já existir, esse comando pode substituir seu conteúdo por um arquivo vazio. Cuidado ao utilizá-lo em arquivos existentes.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>echo</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra um texto no CMD ou pode ser utilizado para escrever conteúdo dentro de um arquivo.</li>
        <li>Ex: <b>echo Ola Mundo</b></li>
        <li><b>echo Ola > arquivo.txt</b> cria o arquivo e escreve "Ola" dentro dele.</li>
        <li><b>echo Nova linha >> arquivo.txt</b> adiciona o texto ao final do arquivo sem apagar o conteúdo existente.</li>
        <li><b>echo.</b> pula uma linha.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>del</b></li>
    <ul style="font-size: 15px;">
        <li><u>Deleta arquivos</u> no caminho atual ou no caminho especificado.</li>
        <li>Ex: <b>del arquivo.txt</b></li>
        <li>Ex: <b>del E:\Downloads\surskitola.png</b></li>
        <li><b>del *.txt</b> remove arquivos .txt do local indicado.</li>
        <li><b>del /q arquivo.txt</b> remove o arquivo sem solicitar confirmação em situações em que a confirmação seria exibida.</li>
        <li>Cuidado: arquivos removidos pelo del normalmente não vão para a Lixeira.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>rmdir / rd</b></li>
    <ul style="font-size: 15px;">
        <li><u>Remove uma pasta.</u></li>
        <li><b>rmdir pasta</b> remove uma pasta vazia.</li>
        <li><b>rmdir /s pasta</b> remove a pasta e todo o conteúdo dentro dela.</li>
        <li><b>rmdir /s /q pasta</b> remove a pasta e seu conteúdo sem pedir confirmação.</li>
        <li>Cuidado: o uso de <b>/s</b> pode apagar muitos arquivos de uma só vez.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>copy</b></li>
    <ul style="font-size: 15px;">
        <li><u>Copia arquivos</u> de um local para outro.</li>
        <li><b>copy arquivo.txt D:\Backup</b> copia o arquivo para a pasta Backup.</li>
        <li><b>copy arquivo.txt novo.txt</b> copia o arquivo e cria uma cópia com outro nome.</li>
        <li>Para copiar pastas inteiras, normalmente utilize comandos como <b>xcopy</b> ou <b>robocopy</b>.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>move</b></li>
    <ul style="font-size: 15px;">
        <li><u>Move arquivos ou pastas</u> de um local para outro.</li>
        <li><b>move arquivo.txt D:\Backup</b> move o arquivo para a pasta Backup.</li>
        <li><b>move antigo.txt novo.txt</b> também pode ser utilizado para renomear um arquivo.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>ren / rename</b></li>
    <ul style="font-size: 15px;">
        <li><u>Renomeia arquivos ou pastas.</u></li>
        <li><b>ren antigo.txt novo.txt</b> renomeia o arquivo.</li>
        <li><b>rename pasta antiga pasta_nova</b> pode ser usado para renomear uma pasta.</li>
        <li>O conteúdo do arquivo não é alterado, apenas seu nome.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>cls</b></li>
    <ul style="font-size: 15px;">
        <li><u>Limpa todo o conteúdo visual</u> que está aparecendo no CMD.</li>
        <li><b>cls</b> limpa a tela, mas não apaga arquivos nem desfaz comandos executados.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>exit</b></li>
    <ul style="font-size: 15px;">
        <li><u>Fecha o CMD</u> ou encerra o interpretador de comandos atual.</li>
        <li>Ex: <b>exit</b></li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>start</b></li>
    <ul style="font-size: 15px;">
        <li><u>Abre um programa, arquivo, pasta ou endereço</u> utilizando o Windows.</li>
        <li><b>start .</b> abre a pasta atual no Explorador de Arquivos.</li>
        <li><b>start notepad</b> abre o Bloco de Notas.</li>
        <li><b>start https://www.google.com</b> abre o endereço no navegador padrão.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>where</b></li>
    <ul style="font-size: 15px;">
        <li><u>Localiza onde um programa está instalado</u> ou disponível no PATH.</li>
        <li><b>where git</b> mostra onde o executável do Git está localizado.</li>
        <li><b>where gcc</b> pode mostrar onde o compilador GCC está instalado.</li>
        <li>É muito útil para verificar se um programa está configurado no PATH.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>where /r</b></li>
    <ul style="font-size: 15px;">
        <li><u>Procura um arquivo dentro de uma pasta e suas subpastas.</u></li>
        <li>Ex: <b>where /r C:\ projeto.exe</b></li>
        <li>Pode ser utilizado quando você sabe o nome do arquivo, mas não sabe onde ele está.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>tree</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra a estrutura de pastas</u> de um diretório em formato de árvore.</li>
        <li><b>tree</b> mostra a estrutura de pastas do local atual.</li>
        <li><b>tree /f</b> mostra também os arquivos existentes dentro das pastas.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>find</b></li>
    <ul style="font-size: 15px;">
        <li><u>Procura um texto dentro de arquivos.</u></li>
        <li><b>find "palavra" arquivo.txt</b> procura a palavra dentro do arquivo.</li>
        <li><b>find /i "palavra" arquivo.txt</b> faz a procura ignorando diferenças entre letras maiúsculas e minúsculas.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>findstr</b></li>
    <ul style="font-size: 15px;">
        <li><u>Procura textos em arquivos</u> e possui mais recursos de busca que o comando find.</li>
        <li><b>findstr "main" *.c</b> procura "main" nos arquivos .c da pasta atual.</li>
        <li><b>findstr /s /i "printf" *.c</b> procura "printf" nos arquivos .c da pasta atual e das subpastas, ignorando maiúsculas e minúsculas.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>ipconfig</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra informações de rede</u> do computador.</li>
        <li><b>ipconfig</b> mostra informações básicas das interfaces de rede.</li>
        <li><b>ipconfig /all</b> mostra informações mais detalhadas, como endereço IP, máscara, gateway e DNS.</li>
        <li><b>ipconfig /release</b> libera o endereço IP obtido por DHCP.</li>
        <li><b>ipconfig /renew</b> solicita um novo endereço IP ao servidor DHCP.</li>
        <li><b>ipconfig /flushdns</b> limpa o cache de resolução DNS do Windows.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>ping</b></li>
    <ul style="font-size: 15px;">
        <li><u>Testa a comunicação</u> entre o computador e outro endereço de rede.</li>
        <li><b>ping 8.8.8.8</b> testa a comunicação com esse endereço IP.</li>
        <li><b>ping google.com</b> testa o endereço e também verifica a resolução do nome.</li>
        <li>É muito utilizado para verificar problemas básicos de conectividade.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>tracert</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra o caminho percorrido</u> pelos pacotes até chegar a um destino de rede.</li>
        <li><b>tracert google.com</b> mostra os saltos entre o computador e o destino.</li>
        <li>É útil para investigar em qual ponto do caminho pode existir um problema de comunicação.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>tasklist</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra os processos</u> atualmente em execução no Windows.</li>
        <li><b>tasklist</b> lista os processos em execução.</li>
        <li><b>tasklist | findstr chrome</b> procura processos relacionados ao Chrome.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>taskkill</b></li>
    <ul style="font-size: 15px;">
        <li><u>Encerra um processo</u> que está sendo executado no Windows.</li>
        <li><b>taskkill /IM programa.exe</b> tenta encerrar o processo pelo nome.</li>
        <li><b>taskkill /PID 1234</b> tenta encerrar o processo pelo número identificador PID.</li>
        <li><b>taskkill /F /IM programa.exe</b> força o encerramento do processo.</li>
        <li>Cuidado ao finalizar processos, pois alguns são necessários para o funcionamento do Windows ou de outros programas.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>systeminfo</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra informações detalhadas sobre o computador e o Windows.</u></li>
        <li>Exibe informações como versão do Windows, memória, processador, nome do computador e outras configurações do sistema.</li>
        <li><b>systeminfo</b> executa a consulta no CMD.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>hostname</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra o nome do computador</u> na rede.</li>
        <li><b>hostname</b> exibe o nome configurado para o computador.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>set</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra ou cria variáveis de ambiente</u> na sessão do CMD.</li>
        <li><b>set</b> mostra as variáveis de ambiente disponíveis.</li>
        <li><b>set nome=valor</b> cria ou altera uma variável na sessão atual.</li>
        <li><b>echo %nome%</b> mostra o valor da variável.</li>
        <li>Variáveis criadas dessa forma normalmente permanecem apenas na sessão atual do CMD.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>path</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra ou altera os caminhos utilizados pelo Windows para localizar executáveis.</u></li>
        <li><b>path</b> mostra o PATH atual.</li>
        <li>O PATH permite executar programas pelo nome sem precisar informar o caminho completo do arquivo executável.</li>
        <li>Ex: se o caminho do GCC estiver no PATH, você pode executar <b>gcc</b> diretamente no CMD.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>help</b></li>
    <ul style="font-size: 15px;">
        <li><u>Mostra ajuda sobre os comandos disponíveis no CMD.</u></li>
        <li><b>help</b> mostra uma lista de comandos.</li>
        <li><b>help cd</b> mostra informações sobre o comando cd.</li>
        <li>Também é possível utilizar <b>comando /?</b> para consultar as opções de um comando.</li>
        <li>Ex: <b>dir /?</b></li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>cls</b></li>
    <ul style="font-size: 15px;">
        <li><u>Limpa a tela</u> do CMD.</li>
        <li><b>cls</b> remove visualmente os comandos e resultados anteriores da tela.</li>
        <li>Não apaga arquivos, pastas ou histórico de comandos do sistema.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>exit</b></li>
    <ul style="font-size: 15px;">
        <li><u>Fecha o CMD</u> ou encerra a sessão atual do interpretador.</li>
        <li>Ex: <b>exit</b></li>
    </ul>
</ul>

</br>
</br>
</br>
</br>
</br>
</br>

<p style="font-size: 25px;" align="center">
<b>Comandos Git/GitHub</b> 
</p>
</br>
</br>




<ul style="font-size: 20px;">
    <li><b>git init</b></li>
    <ul style="font-size: 15px;">
        <li>Inicializa um repositório Git na pasta atual, permitindo que o Git rastreie as alterações dos arquivos.</li>
        <li>Cria a pasta oculta .git, onde ficam armazenados o histórico e as configurações do repositório.</li>
        <li>Use dentro da pasta do projeto que deseja controlar com Git.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git status</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra a branch atual, arquivos novos, arquivos modificados, arquivos preparados para commit e outras informações.</li>
        <li><b>git status -s</b> mostra uma versão resumida do estado dos arquivos.</li>
        <li>É um dos comandos mais úteis para verificar o estado do projeto antes de executar outras operações.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>touch</b></li>
    <ul style="font-size: 15px;">
        <li>Cria um arquivo vazio caso ele ainda não exista.</li>
        <li><b>touch arquivo.txt</b> cria o arquivo arquivo.txt na pasta atual.</li>
        <li>Se o arquivo já existir, o comando normalmente atualiza sua data de modificação sem apagar seu conteúdo.</li>
        <li>É um comando do terminal, não do Git. Está disponível em ambientes como Git Bash e Linux.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>ls</b></li>
    <ul style="font-size: 15px;">
        <li>Lista os arquivos e as pastas do diretório atual.</li>
        <li><b>ls -l</b> mostra informações detalhadas dos arquivos.</li>
        <li><b>ls -a</b> também mostra arquivos e pastas ocultos.</li>
        <li>É um comando do terminal, não do Git. No Windows CMD, o comando equivalente mais comum é dir.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>cd</b></li>
    <ul style="font-size: 15px;">
        <li>Permite navegar entre pastas pelo terminal.</li>
        <li><b>cd nomepasta</b> entra em uma pasta.</li>
        <li><b>cd ..</b> volta para a pasta anterior na hierarquia.</li>
        <li><b>cd /d D:\Projetos</b> no CMD permite mudar de unidade e entrar na pasta indicada.</li>
        <li>É um comando do terminal, não do Git.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>pwd</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra o caminho completo do diretório atual.</li>
        <li>É útil para conferir em qual pasta você está trabalhando.</li>
        <li>É um comando comum no Git Bash e no Linux.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>mkdir</b></li>
    <ul style="font-size: 15px;">
        <li>Cria uma nova pasta.</li>
        <li><b>mkdir projeto</b> cria uma pasta chamada projeto.</li>
        <li>É um comando do terminal, não do Git.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>rm / git rm</b></li>
    <ul style="font-size: 15px;">
        <li><b>rm arquivo.txt</b> remove um arquivo do computador, mas não prepara automaticamente uma remoção específica no índice do Git.</li>
        <li><b>git rm arquivo.txt</b> remove o arquivo do computador e prepara a remoção para o próximo commit.</li>
        <li><b>git rm --cached arquivo.txt</b> remove o arquivo do controle de versão, mas mantém sua cópia local.</li>
        <li><b>git rm -r pasta</b> remove uma pasta rastreada e seus arquivos recursivamente.</li>
        <li>Cuidado ao remover arquivos, pois eles podem ser difíceis de recuperar dependendo da operação realizada.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git mv</b></li>
    <ul style="font-size: 15px;">
        <li>Move ou renomeia arquivos, preparando a mudança para o próximo commit.</li>
        <li><b>git mv antigo.txt novo.txt</b> renomeia o arquivo.</li>
        <li><b>git mv arquivo.txt pasta/arquivo.txt</b> move o arquivo para outra pasta existente.</li>
        <li>O Git identifica renomeações pelo conteúdo e pelo histórico, não por um registro separado obrigatório de renomeação.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git add</b></li>
    <ul style="font-size: 15px;">
        <li>Adiciona arquivos e alterações à área de staging, preparando-os para o próximo commit.</li>
        <li><b>git add arquivo.txt</b> prepara um arquivo específico.</li>
        <li><b>git add .</b> prepara as alterações reconhecidas pelo Git no diretório atual e em seus subdiretórios.</li>
        <li><b>git add -A</b> prepara todas as alterações reconhecidas no repositório, incluindo adições, modificações e remoções.</li>
        <li>O comando não cria um commit nem envia arquivos ao GitHub.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git commit</b></li>
    <ul style="font-size: 15px;">
        <li>Registra um ponto no histórico do repositório com as alterações que estão na área de staging.</li>
        <li><b>git commit -m "Descrição"</b> cria um commit com a mensagem indicada.</li>
        <li><b>git commit</b> abre o editor configurado para escrever a mensagem do commit.</li>
        <li>O commit fica salvo no repositório local até que seja enviado para um remoto, por exemplo, usando git push.</li>
        <li>É recomendado escrever mensagens curtas e claras sobre o que foi alterado.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git commit --amend</b></li>
    <ul style="font-size: 15px;">
        <li>Permite corrigir a mensagem do último commit ou incluir nele novas alterações preparadas com git add.</li>
        <li><b>git commit --amend -m "Nova mensagem"</b> substitui a mensagem do último commit.</li>
        <li>Esse comando substitui o commit anterior por outro, alterando o histórico.</li>
        <li>Evite alterar commits que já foram compartilhados com outras pessoas sem considerar as consequências.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git log</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra o histórico de commits, incluindo autor, data, mensagem e identificador do commit.</li>
        <li><b>git log --oneline</b> mostra cada commit em uma linha resumida.</li>
        <li><b>git log --oneline --graph --all</b> mostra o histórico em formato gráfico, incluindo diferentes branches.</li>
        <li><b>git log -5</b> mostra os cinco commits mais recentes.</li>
        <li><b>git log --stat</b> mostra um resumo dos arquivos alterados em cada commit.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>.gitignore</b></li>
    <ul style="font-size: 15px;">
        <li>É um arquivo de configuração que define quais arquivos e pastas o Git deve ignorar quando ainda não são rastreados.</li>
        <li>Crie um arquivo chamado .gitignore na pasta do projeto e escreva nele os nomes ou padrões que deseja ignorar.</li>
        <li><b>*.exe</b> ignora arquivos com extensão .exe.</li>
        <li><b>nomepasta/</b> ignora uma pasta chamada nomepasta.</li>
        <li><b>*.log</b> ignora arquivos de log.</li>
        <li><b>.env</b> ignora um arquivo chamado .env, que pode conter senhas, tokens e outras informações privadas.</li>
        <li><b>!arquivo.txt</b> pode deixar de ignorar um arquivo específico, dependendo das demais regras.</li>
        <li>O .gitignore não deixa de rastrear arquivos que já foram adicionados ao repositório. Para isso, pode ser necessário usar git rm --cached.</li>
        <li>Nunca envie senhas ou chaves de API ao GitHub. Se um segredo já foi publicado, removê-lo do arquivo não basta: revogue ou substitua a credencial.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git branch</b></li>
    <ul style="font-size: 15px;">
        <li>Permite listar, criar, renomear e excluir branches.</li>
        <li><b>git branch</b> lista as branches locais.</li>
        <li><b>git branch -a</b> lista as branches locais e as referências de branches remotas conhecidas.</li>
        <li><b>git branch nome</b> cria uma nova branch sem mudar para ela.</li>
        <li><b>git branch -d nome</b> exclui uma branch local que já foi integrada ou cuja exclusão é considerada segura pelo Git.</li>
        <li><b>git branch -D nome</b> força a exclusão de uma branch local, mesmo que existam alterações não integradas nela.</li>
        <li><b>git branch -M novo-nome</b> renomeia a branch atual, substituindo uma branch de mesmo nome se necessário.</li>
        <li>Uma branch permite desenvolver funcionalidades separadamente sem precisar alterar diretamente a branch principal.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git checkout / git switch</b></li>
    <ul style="font-size: 15px;">
        <li>Permitem trocar de branch. O git checkout também possui outras funções, como recuperar arquivos.</li>
        <li><b>git switch main</b> muda para a branch main.</li>
        <li><b>git switch -c nova-branch</b> cria uma branch e entra nela.</li>
        <li><b>git checkout nome</b> também pode ser utilizado para mudar para uma branch existente.</li>
        <li><b>git checkout -b nome</b> cria uma branch e muda para ela.</li>
        <li>Para novos usos, git switch é mais específico para operações com branches e git restore para restaurar arquivos.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git merge</b></li>
    <ul style="font-size: 15px;">
        <li>Integra as alterações de uma branch à branch atual.</li>
        <li>Primeiro, entre na branch que receberá as alterações.</li>
        <li><b>git switch main</b> muda para a branch principal.</li>
        <li><b>git merge nova-branch</b> integra as alterações da nova-branch à branch atual.</li>
        <li>Se houver alterações incompatíveis nos mesmos trechos de um arquivo, podem ocorrer conflitos que precisam ser resolvidos manualmente.</li>
        <li>Depois de resolver os conflitos, prepare os arquivos com git add e conclua o merge quando necessário com git commit.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git remote</b></li>
    <ul style="font-size: 15px;">
        <li>Permite visualizar e configurar as conexões com repositórios remotos.</li>
        <li><b>git remote -v</b> mostra os endereços dos repositórios remotos cadastrados.</li>
        <li><b>git remote add origin URL</b> conecta o projeto local a um repositório remoto.</li>
        <li><b>git remote remove origin</b> remove a conexão chamada origin, sem apagar os arquivos locais.</li>
        <li><b>origin</b> é o nome mais utilizado para identificar o repositório remoto, mas pode ser substituído por outro nome.</li>
        <li>Substitua URL pelo endereço HTTPS ou SSH do repositório remoto.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git push</b></li>
    <ul style="font-size: 15px;">
        <li>Envia commits locais para um repositório remoto, como o GitHub.</li>
        <li><b>git push</b> envia os commits da branch atual para o remoto configurado como upstream.</li>
        <li><b>git push -u origin main</b> envia a branch main para origin e configura o acompanhamento para os próximos pushes e pulls.</li>
        <li><b>git push origin nome-branch</b> envia uma branch específica ao remoto.</li>
        <li>É necessário ter permissão de acesso ao repositório remoto.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git pull</b></li>
    <ul style="font-size: 15px;">
        <li>Busca as atualizações do repositório remoto e tenta integrá-las à branch local atual.</li>
        <li><b>git pull</b> utiliza o remoto e a branch de acompanhamento configurados.</li>
        <li><b>git pull origin main</b> busca e integra as alterações de origin/main à branch atual.</li>
        <li>O processo pode gerar conflitos caso as alterações locais e remotas sejam incompatíveis.</li>
        <li>Normalmente, o pull utiliza merge, mas também pode ser configurado para utilizar rebase.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git fetch</b></li>
    <ul style="font-size: 15px;">
        <li>Busca informações e atualizações do repositório remoto sem integrar automaticamente essas mudanças à branch local atual.</li>
        <li><b>git fetch origin</b> busca as atualizações do remoto origin.</li>
        <li><b>git log HEAD..origin/main --oneline</b> mostra commits que estão em origin/main e ainda não estão alcançáveis a partir do HEAD atual.</li>
        <li>É útil para verificar o que mudou no remoto antes de decidir como integrar as atualizações.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git clone</b></li>
    <ul style="font-size: 15px;">
        <li>Cria uma cópia local de um repositório remoto, incluindo seus arquivos e histórico.</li>
        <li><b>git clone URL</b> clona o repositório indicado pelo endereço.</li>
        <li><b>git clone URL nomepasta</b> clona o repositório para uma pasta com o nome escolhido.</li>
        <li>É utilizado para baixar projetos existentes no GitHub para o computador.</li>
        <li>Após clonar, entre na pasta criada com cd nomepasta para trabalhar no projeto.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git diff</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra as diferenças entre arquivos e versões, permitindo verificar o que foi alterado.</li>
        <li><b>git diff</b> mostra as alterações não preparadas na área de staging.</li>
        <li><b>git diff --staged</b> mostra as alterações que já foram preparadas para o próximo commit.</li>
        <li><b>git diff HEAD</b> compara o estado atual dos arquivos com o commit apontado pelo HEAD.</li>
        <li>Linhas com + representam adições e linhas com - representam remoções.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git restore</b></li>
    <ul style="font-size: 15px;">
        <li>Permite descartar alterações em arquivos ou retirar arquivos da área de staging.</li>
        <li><b>git restore arquivo.txt</b> descarta as alterações não preparadas do arquivo, recuperando a versão do commit atual.</li>
        <li><b>git restore --staged arquivo.txt</b> retira o arquivo da área de staging, mas mantém suas alterações no diretório de trabalho.</li>
        <li><b>git restore .</b> descarta as alterações não preparadas nos arquivos afetados do diretório atual e seus subdiretórios.</li>
        <li>Cuidado: alterações descartadas podem ser difíceis ou impossíveis de recuperar. Confira o git status e o git diff antes de executar.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>staging (área de preparação)</b></li>
    <ul style="font-size: 15px;">
        <li>É a área intermediária entre os arquivos modificados e o commit.</li>
        <li>Permite escolher quais alterações serão incluídas no próximo commit.</li>
        <li><b>git add arquivo.txt</b> prepara um arquivo específico.</li>
        <li><b>git diff --staged</b> permite conferir as alterações preparadas.</li>
        <li><b>git status</b> mostra quais arquivos estão preparados e quais ainda possuem alterações não preparadas.</li>
        <li>O fluxo comum é modificar os arquivos, executar git add, conferir as mudanças e criar o commit com git commit.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git revert</b></li>
    <ul style="font-size: 15px;">
        <li>Cria um novo commit que desfaz as alterações introduzidas por um commit anterior.</li>
        <li><b>git revert HASH</b> reverte o commit identificado pelo hash informado.</li>
        <li><b>git log --oneline</b> ajuda a localizar o hash do commit que você deseja reverter.</li>
        <li>É útil para desfazer alterações sem apagar o histórico existente.</li>
        <li>Em geral, é uma opção adequada para desfazer commits que já foram compartilhados com outras pessoas.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git reset</b></li>
    <ul style="font-size: 15px;">
        <li>Move a referência da branch atual para outro commit e pode alterar a área de staging e os arquivos locais, dependendo da opção utilizada.</li>
        <li><b>git reset --soft HEAD~1</b> remove o último commit da branch atual, mantendo as alterações na área de staging.</li>
        <li><b>git reset --mixed HEAD~1</b> remove o último commit e retira suas alterações da área de staging, mas mantém os arquivos modificados. É a opção padrão.</li>
        <li><b>git reset --hard HEAD~1</b> remove o último commit da branch atual e descarta as alterações correspondentes nos arquivos e na área de staging.</li>
        <li><b>HEAD~1</b> representa o primeiro commit anterior ao commit atual.</li>
        <li>Cuidado: o reset pode reescrever o histórico da branch e descartar trabalho. Evite utilizá-lo em commits compartilhados sem entender as consequências.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>HEAD</b></li>
    <ul style="font-size: 15px;">
        <li>É uma referência que normalmente indica o commit atual da sua cópia local do repositório.</li>
        <li>Ao trocar de branch, o HEAD normalmente passa a acompanhar a branch selecionada.</li>
        <li><b>HEAD~1</b> representa o primeiro commit anterior ao atual.</li>
        <li><b>HEAD~2</b> representa dois commits antes do atual.</li>
        <li><b>git show HEAD</b> mostra informações e alterações do commit atual.</li>
        <li><b>git diff HEAD</b> mostra diferenças entre os arquivos atuais e o commit apontado pelo HEAD.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git tag</b></li>
    <ul style="font-size: 15px;">
        <li>Cria identificações para commits específicos, sendo muito utilizada para marcar versões do projeto.</li>
        <li><b>git tag</b> lista as tags existentes.</li>
        <li><b>git tag v1.0</b> cria uma tag simples no commit atual.</li>
        <li><b>git tag -a v1.0 -m "Versão 1.0"</b> cria uma tag anotada com uma mensagem.</li>
        <li><b>git show v1.0</b> mostra informações sobre a tag e o commit associado.</li>
        <li><b>git push origin v1.0</b> envia a tag v1.0 para o remoto.</li>
        <li><b>git push origin --tags</b> envia as tags locais para o remoto.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git stash</b></li>
    <ul style="font-size: 15px;">
        <li>Guarda temporariamente alterações locais para que você possa trabalhar em outra tarefa sem criar um commit naquele momento.</li>
        <li><b>git stash</b> guarda alterações rastreadas do projeto, incluindo alterações preparadas na área de staging.</li>
        <li><b>git stash -u</b> também inclui arquivos novos que ainda não são rastreados pelo Git.</li>
        <li><b>git stash list</b> mostra as alterações guardadas temporariamente.</li>
        <li><b>git stash pop</b> reaplica as alterações mais recentes e remove essa entrada da lista se a aplicação for concluída.</li>
        <li><b>git stash apply</b> reaplica as alterações sem remover a entrada da lista.</li>
        <li><b>git stash drop</b> remove uma entrada guardada. Confira a lista antes de executar.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git show</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra informações de um commit e as alterações realizadas nele.</li>
        <li><b>git show</b> mostra detalhes do commit atual.</li>
        <li><b>git show HASH</b> mostra detalhes de um commit específico.</li>
        <li>É útil para conferir as alterações feitas em uma versão do projeto.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git cherry-pick</b></li>
    <ul style="font-size: 15px;">
        <li>Aplica as alterações de um commit específico na branch atual, criando um novo commit.</li>
        <li><b>git cherry-pick HASH</b> aplica o commit indicado na branch atual.</li>
        <li>É útil quando você deseja aproveitar uma alteração específica de outra branch sem integrar todas as suas alterações.</li>
        <li>Podem ocorrer conflitos que precisam ser resolvidos antes de concluir a operação.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git rebase</b></li>
    <ul style="font-size: 15px;">
        <li>Reaplica os commits de uma branch sobre outra base, reorganizando o histórico.</li>
        <li><b>git rebase main</b> reaplica os commits da branch atual sobre a versão atual de main.</li>
        <li>Pode deixar o histórico mais linear, sem necessariamente criar um commit de merge.</li>
        <li>Conflitos podem ocorrer durante o processo e precisam ser resolvidos.</li>
        <li><b>git rebase --continue</b> continua o processo depois da resolução dos conflitos e da preparação das alterações.</li>
        <li><b>git rebase --abort</b> cancela a operação e retorna ao estado anterior ao rebase.</li>
        <li>Cuidado: o rebase reescreve os commits reaplicados. Evite utilizá-lo em histórico compartilhado sem combinar com a equipe.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git clean</b></li>
    <ul style="font-size: 15px;">
        <li>Remove arquivos não rastreados pelo Git.</li>
        <li><b>git clean -n</b> mostra quais arquivos seriam removidos sem removê-los.</li>
        <li><b>git clean -f</b> remove os arquivos não rastreados selecionados pela operação.</li>
        <li><b>git clean -fd</b> também pode remover diretórios não rastreados.</li>
        <li>Arquivos ignorados pelo .gitignore normalmente não são removidos sem opções adicionais.</li>
        <li>Cuidado: arquivos removidos podem não ser recuperáveis. Execute primeiro git clean -n para conferir o resultado.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git config</b></li>
    <ul style="font-size: 15px;">
        <li>Configura opções do Git, como nome, e-mail e preferências de funcionamento.</li>
        <li><b>git config --global user.name "Seu Nome"</b> define o nome utilizado nos commits.</li>
        <li><b>git config --global user.email "seu@email.com"</b> define o e-mail utilizado nos commits.</li>
        <li><b>git config --list</b> lista as configurações efetivas do Git.</li>
        <li>O argumento --global aplica a configuração ao usuário do computador, enquanto --local aplica a configuração ao repositório atual.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git ls-files</b></li>
    <ul style="font-size: 15px;">
        <li>Lista os arquivos rastreados pelo Git no índice atual.</li>
        <li><b>git ls-files</b> mostra os arquivos que o Git está rastreando.</li>
        <li>É útil para verificar quais arquivos estão sob controle de versão.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git grep</b></li>
    <ul style="font-size: 15px;">
        <li>Procura palavras ou trechos de texto nos arquivos rastreados pelo Git.</li>
        <li><b>git grep "palavra"</b> procura a palavra nos arquivos do projeto.</li>
        <li><b>git grep -n "palavra"</b> também mostra o número da linha em que o texto aparece.</li>
        <li>É útil para localizar funções, variáveis e trechos de código sem abrir cada arquivo individualmente.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git archive</b></li>
    <ul style="font-size: 15px;">
        <li>Gera um arquivo compactado com os arquivos de uma versão do projeto, sem incluir o histórico completo do Git.</li>
        <li><b>git archive --format=zip -o projeto.zip HEAD</b> gera um arquivo ZIP com os arquivos do commit atual.</li>
        <li>É útil para compartilhar uma versão do projeto sem enviar a pasta .git.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git reflog</b></li>
    <ul style="font-size: 15px;">
        <li>Registra movimentações recentes das referências locais do Git, como mudanças de branch, commits e resets.</li>
        <li><b>git reflog</b> mostra o histórico recente dessas movimentações.</li>
        <li>É útil para localizar commits que deixaram de aparecer no histórico normal depois de operações como git reset.</li>
        <li>As entradas do reflog são locais e não funcionam como um histórico permanente ou compartilhado.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git shortlog</b></li>
    <ul style="font-size: 15px;">
        <li>Resume o histórico de commits, agrupando as mensagens por autor.</li>
        <li><b>git shortlog</b> apresenta um resumo dos commits por autor.</li>
        <li><b>git shortlog -s -n</b> mostra a quantidade de commits por autor, ordenada da maior para a menor.</li>
        <li>É útil para consultar contribuições registradas no histórico do projeto.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git blame</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra qual commit e autor estão associados às últimas alterações de cada linha de um arquivo.</li>
        <li><b>git blame arquivo.c</b> apresenta informações linha por linha do arquivo.</li>
        <li>É útil para investigar quando determinado trecho foi alterado e em qual commit a mudança apareceu.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git describe</b></li>
    <ul style="font-size: 15px;">
        <li>Gera uma identificação legível para um commit com base em tags existentes.</li>
        <li><b>git describe --tags</b> tenta identificar o commit atual usando as tags disponíveis.</li>
        <li>É útil para relacionar versões de desenvolvimento com versões marcadas por tags.</li>
    </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>git help</b></li>
    <ul style="font-size: 15px;">
        <li>Mostra a documentação e as opções de uso dos comandos do Git.</li>
        <li><b>git help commit</b> abre a documentação do comando git commit.</li>
        <li><b>git commit -h</b> mostra um resumo das opções de git commit.</li>
        <li>É útil para descobrir argumentos e opções que você ainda não conhece.</li>
    </ul>
</ul>


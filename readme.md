<p style="font-size: 25px;" align="center">
<i>ta complicado isso ai</i></p>
<br>

<p align="center">
<img src="https://i.pinimg.com/736x/81/9f/24/819f242ade8476ab80b0f256e08f4234.jpg" width="75%">
</p>

<p align="center"><a https://www.youtube.com/watch?v=dQw4w9WgXcQ>tutorial foda🔥</a>
</p>
<br>
<br>

<p style="font-size: 25px;" align="center">
<b>Comandos CMD</b> 
</p>

<ul style="font-size: 20px;">
<li><b>cd</b></li>
    <ul style="font-size: 15px;">
        <li><u>Seleciona e se locomove por um caminho</u> entre as pastas do windows.</br></br>Importante: </br><b>\</b> indica pasta </br> <b>cd /d </b>trocar de disco</br>  Ex: cd /d d:\projeto</li>
        </br>
        <li>Pode se usar: <b>cd .. ou \ </b><u>para voltar</u> uma pasta</li>
    </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>dir e mkdir</b></li>
        <ul style="font-size: 15px;">
        <li>dir faz você <u>vê todos os arquivos e pastas</u> no caminho atual.</li>
        <li>mkdir criar um novo diretório(pasta). </li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>type nul ></b></li>
        <ul style="font-size: 15px;">
            <li><u>Cria</u> um arquivo no caminho atual.</br>Ex: type nul> arquivo.tipo"</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>del</b></li>
        <ul style="font-size: 15px;">
            <li><u>Deleta</u> um arquivo no caminho atual.</br>Ex: del E:\Downloads\surskitola.png</li>
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
</br>
</br>
</br>
</br>

<ul style="font-size: 20px;">
    <li><b>git init</b></li>
        <ul style="font-size: 15px;">
            <li>Inicia o git no repositório, tudo dentro dele o git poderá mexer.</li>
        </ul>
</ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git status</b></li>
        <ul style="font-size: 15px;">
            <li>git status mostra a branch atual, arquivos novos/modificados, arquivos para <b>commit</b> e entre outras informações.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>touch</b></li>
    <ul style="font-size: 15px;">
            <li>Cria um arquivo.</li>
        </ul>
</ul>

<ul style="font-size: 20px;">
    <li><b>ls</b></li>
        <ul style="font-size: 15px;">
            <li>Visualiza todos os arquivos/pastas de dentro do caminho atual.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>rm / git rm</b></li>
        <ul style="font-size: 15px;">
            <li>rm + "arquivo" remove o arquivo.</li>
            <li>Se o git estiver na pasta, use git rm para remove, além de colocar pro proximo <b>commit</b>.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git mv</b></li>
        <ul style="font-size: 15px;">
            <li>git mv + "antigo.txt" + "novo.txt", renomeia o arquivo e gera uma mudança para o <b>commit</b>.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git add</b></li>
        <ul style="font-size: 15px;">
            <li>git add + "arquivo" prepara uma mudança para esse arquivo para um <b>commit</b>.</li>
            <li>git add . ele manda tudo da pasta como mudança para o <b>commit</b>.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git commit</b></li>
        <ul style="font-size: 15px;">
            <li>git commit -m "descrição" cria um ponto de histórico. Podendo acessar e saber oque mudou em cada ponto.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git log</b></li>
        <ul style="font-size: 15px;">
            <li>git log permite ver o histórico de alterações, com nome do commit e quem fez com horário e dia.</li>
            <li>Pode se usar <b>git log --oneline --graph --all</b> para algo melhor visualmente.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>.gitignore</b></li>
        <ul style="font-size: 15px;">
            <li>.gitignore é um arquivo que você escolhe oque não quer enviar para o github, dentro dele escreva o nome dos arquivos e ele não enviará.</li>
            <li>Pode se usar "*" para escolher um tipo de arquivo para não enviar.</br>
            Ex:" *.exe". </br>
            Usando "/" no final determina uma pasta para que ele ignore. </br>
            Ex: "nomepasta/".</br>
            Importante usar o .env para esconder arquivos da api que armazenam senhas.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git branch</b></li>
        <ul style="font-size: 15px;">
            <li>git branch permite você ver as branchs.</li>
            <li>git branch + nome, cria uma branch.</li>
            <li>O argumento -d ou -D deleta a branch. </br> A diferença é que -D força a exclução.</li>
            <li>Com o argumento -M renomeia o nome da branch atual.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git checkout / switch</b></li>
        <ul style="font-size: 15px;">
            <li>git checkout ou git switch permitem trocar de branch</li>
            <li>Com argumento -c você pode criar e ja entrar na branch. </br>Ex: git switch -c nome </li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git merge</b></li>
        <ul style="font-size: 15px;">
            <li>git merge permite juntar duas branchs. Primeiro você vai para branch que você quer que seja a receptora, e depois use git merge + nomebranch, para juntar as duas branchs.</li>
            <li>Pode haver conflito entre as branchs por ter o mesmo arquivo, com isso ele salvará o codigo das duas junto, com isso você decide qual código manter.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git remote</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git push</b></li>
        <ul style="font-size: 15px;">
            <li>git push envia as alterações para o github.</li>
            <li>Pode se usar git push -u origin main na primeira vez para estabelecer uma relação entre sua branch local e a branch remota.</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git pull</b></li>
        <ul style="font-size: 15px;">
            <li>Busca alterações no github e incorpora no seu projeto local</li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git fetch</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git clone</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git diff</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git restore</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>stagging</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git revert</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git reset</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>HEAD</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git tag</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b>git stash</b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b></b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b></b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b></b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>
<ul style="font-size: 20px;">
    <li><b></b></li>
        <ul style="font-size: 15px;">
            <li></li>
        </ul>
</ul>

<!--
Arquivo .mdtxt

#git init: inicia o git no repositório

#git add (.) + arquivo: preparo uma mudança para esse arquivo

#git commit -m + "descrição": upo o arquivo

#git status: vejo mudanças e arquivos novos na branch

#git log (--oneline --graph --all): vejo o histórico de todos os commits

#git branch: vejo as branchs e em qual estou

#git branch + nome: crio uma branch

#git checkout/switch + nome: troco de branch

#git switch -c +nome: crio e entro em uma branch

#git switch -d (ou -D) + nome: excluo a branch (-D força a exclusão)

#git branch -M: troco o nome de uma branch

#git merge: junta as duas branchs em uma

#git remote add origin + link: conecta seu projeto local ao projeto no GitHub

#git push / git push -u origin main: envia commits pro git hub

#git pull: busca mudanças e incorpora no seu

#git fetch: baixa as informações do GitHub, mas não mistura automaticamente essas alterações com sua branch atual

#git clone + link do projeto: clono um projeto

#.gitignore: ignora mudanças em arquivos selecionados, não entendi bem como faz pra funcionar

#touch: crio um arquivo

#ls: vejo todos os arquivos dentro da pasta

#cd: seleciona a pasta


#tem muitas outras mas vou deixar para depois


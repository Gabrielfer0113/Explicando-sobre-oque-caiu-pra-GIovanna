# CLONANDO REPOSITÓRIO
<img src="./img/clonando repositório.jpg"/>

<p>Para clonar um repositório basta usar o comando <code>git clone</code> e após esse comando coloque o link do seu repositório do Github.

Exemplo: </p>

<code>
    <pre>
        git clone (link_do_repositório)
    </pre>
</code>



## Entrando no arquivo e criando uma Branch

<img src="./img/Entrando na pasta e criando uma Branch.jpg"/>

<ul>
    <li><h3>Entrando em pastas</h3></li>
</ul>

<p>Para entrar em uma pasta você deve usar o comando <code>cd</code> e logo após o comando o nome do repositórito/pasta que esta na sua maquina.

Exemplo: </p>
<code>
    <pre>
        cd (nome_da_pasta)
    </pre>
</code>

<ul>
    <li><h3>Criando a Branch</h3></li>
    <p>Para criar uma Branch, você deve usar o comando <code>checkout -b (nome_da_nova_branch)</code>. 

Exemplo: </p>
</ul>
<code>
    <pre>
        git checkout -b NovaBranch
    </pre>
</code>

<ul>
    <li><h3>Descobrindo sua Branch</h3></li>
</ul>
<img src="./img/Descobrindo qual a sua Branch.jpg"/>
<p>Para descobrir em qual Branch você esta, basta usar o código <code>git branch</code>, o nome que aparecer em verde é a Branch que você esta, e o resto que estiver em branco
é as outras Branch's que existem.</p>

## Git status e Git add

<img src="./img/Git status e git add.jpg"/>


<ul>
    <li><h3>Git status</h3></li>
</ul>
<p>O comando <code>git status</code> serve para ver os status do repositório que você clonou, ele equipara com o ultimo save dele para ver quais arquivos foram modificados,
um exemplo disso é a imagem acima, caso esteja em <mark style="background: 0; color: red">vermelho</mark> é porque você modificou o arquivo do repositório e não salvou eles, caso esteja <mark style="background: 0; color: lightgreen">verde</mark> o arquivo foi modificado e foi salvo.</p>

<ul>
    <li><h3>Git add</h3></li>
</ul>

<p>O comando <code>git add</code> faz que o arquivo faça o processo de salvamento dentro do repositório, mas podemos usar ele de duas maneiras
<code>git add .</code> -- <code>git add (nome_do_arquivo)</code>

Exemplo: </p>

<code>
    <p>// Isso faz que ele salve todos os arquivos modificados</p>
    <pre>
        git add .
    </pre>
</code>

<hr>

<code>
    <p>// Isso faz que ele salve um arquivo a sua escolha</p>
    <pre>
        git add LEIA_ESSE_ARQUIVO.md
    </pre>
</code>

# Git commit

<img src="./img/Git commit.jpg"/>

<p>Após você usar os comandos <code>git add</code> você tem que comitar esses arquivos, o <code>git commit -m ""</code> seria meio que uma explicação sobre oque foi feito no arquivo alterado

Exemplo:</p>

<code>
    <pre>
        git commit -m "Arquivos alterados e novo arquivo .md criado juntamente com pasta de imagens"
    </pre>
</code>

# Git push

<img src="./img/Git push.jpg"/>

<p>O comando <code>git push (link_do_repositório)</code> serve para você mandar os arquivos para o repositório do GitHub</p>

# GitHub

<img src="./img/GitHub.jpg"/><br>

<p>Agora dentro do Github você podera ver as branchs existentes dentro do repositório, e fazer o <code>pull request</code></p>

## Pull Request

<p>O <code>pull request</code> é para ver as diferenças do código novo com o antigo, ver onde ele vai se encaixar na main.</p>

<img src="./img/Merge_e_Pullrequest.jpg"/>

<p>compare os arquivos no pullrequest e de uma <code>merge</code> para mesclar eles</p>
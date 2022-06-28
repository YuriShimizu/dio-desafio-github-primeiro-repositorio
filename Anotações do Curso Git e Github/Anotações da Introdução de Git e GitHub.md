COMANDOS:
cd = change directory
ls = list (listar)
ls -a = mostrar repositórios ocultos
echo = printa de volta uma frase/mensagem
(echo "mensagem" "> direcionador de mensagem p/arquivo" "mensagem.txt)
pwd = mostrar caminho completo
ctrl L = limpar tela
git = sistema distribuido seguro
mkdir = criar pasta (ex: mk dir livro-receitas)
ls -a = listar itens ocultos
mv = mover - (mv "arquivo"./nome da pasta/)
git clone "colar link" = clonar
ci:
git status = status do arquivo, dizer se foi modificado
git commit -m = commitar com mensagem
git remote -v 
git remote add origin "https..."
git push origin master "ou" main = pra mandar os commits
(se der errado, é por haver modificações)
aí tem que puxar (pull) pra arrumar
git pull origin master "ou" main - mostra o erro

cat id_ed25519.pub
eval $(ssh-agent -s) (validar a chave ssh)
ssh-add id_ed25519 (adicionar chave)

echo > README.md


Estrutura Blob: (bloco básico da composição) (sha1)
blob tamanho 42

\0
Ola mundo

Estrutura Tree: (Armazenam e apontando para Blobs)

Tree
\0
blob sa4d8s texto.txt

Estrutura Commit <tamanho> (impossíveis de serem alterados)

tree s4a5sq1
parente a98acq1
autor ---
mensagem "inicia..."
timestamp


Chaves SSH e Tokens

dado SSH (É uma forma de estabelecer conexão segura com outra máquina)

quando for fazer uma cópia de repositório, usar a chave ssh 

Tokens de acesso pessoal

Meu token de acesso 

****************
----------
---criar pasta /c/workspace/token-test 

para testar e clonar

git add * (adiciona tudo ao git)

primeiramente, quando for usar o git pra fazer algo pela primeira vez(projeto), 
tem que configurar email e nome(apelido), usando os códigos :
git config --global user.email "email"
git config --global user.name "nome"

* obs remover aspas nas linhas*

usar markdown(MD), tipo os "< h1 >" de html
"#" = "< h1 >"
"# #" = "< h2 >"
"# # #" = "< h3 >"
...                   forma de escrever html sem ter contato com html de fato

typora
"- -" cria bolinha (lista)
":nameemoji"
"[-namelink-]"(link)"

-----------

commit inicial deixa mensagem

"( https ://wwww.markdownguide .org/basic-syntax/ )
markdownguide.org/basic-syntax/"

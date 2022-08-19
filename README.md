## Git/Github

- REPOSITÓRIO -> conjunto de branchs;
- MERGE -> juntar várias branchs;
![stoneGIT](https://user-images.githubusercontent.com/85708747/185693465-500b4d56-0f2f-4d00-8115-c6240e0e20a7.png)

**commit =** palavra utilizada para representar cada alteração. 

**git init =** inicializa o repositório local e cria a branch master;

**git status =** mostra a situação atual do repositório, todas as alterações. 

**git add** index.html = esse arquivo será adicionado no próximo commit no próximo ponto de alteração da história. 

**git commit  -m** ‘adicionando o index.html’ = forma que temos para descrever a alteração feita no projeto 

(seta para cima volta para os comandos que já foram dados)

root commit significa que o commit foi realizado no repositório local 

**git add .** = adiciona todas as alterações que foram feitas no projeto no commit 

### Github e repositório remoto

Caso já tenha rodado o git init, git add e git commit basta conectar o repositório local ao repositório do github. 

**git remote add origin** [https://github.com/patticavalcantte/projeto.git](https://github.com/patticavalcantte/projeto.git) 

**Git remote →** Para verificar se os repositórios estão conectados: git remote (aparecendo origin está conectado). 

**git status → mostra se houve algum commit** 

git add . ⇒ adiciona os arquivos, mas ainda n foi feito o commit. Colocou os arquivos na caixa, mas precisa dar uma descrição para essa alteração. 

**git commit  -m** ‘add index.html’ (colocou a descrição na caixa) 

git push u origin master  (só usa o u a primeira vez que faz o push), desta forma sobe os arquivos. 

### Branch e merge

**git checkout -b novabranch** → cria uma nova branch; 

- touch  novoarquivo.html → cria novo arquivo 

- git merge novabranch → se tiver na branch master;

- git fetch → garante que está tudo certo com a branch nova. 

- git checkout novabranch → muda para novabranch, navega entre as branchs

- git merge master → faz o merge com a master. (atualiza pega o que tem na branchnova e junta com o que tem na master)

**git push -u** origin master 

### Fork, pull request e Github Pages

### Fork:

![fork](https://user-images.githubusercontent.com/85708747/185694004-2d9abaec-6258-4498-ac4d-12dff8170fb6.png)

Clicar em fork no repositório remoto que se quer copiar; 

### Pull request

Geralmente, existe a branch principal, que é a versão estável e para você subir as suas alterações naquela branch é necessário fazer uma requisição e isso é o pull request. 

**Clonando repositório:**

- Copiar a url em code;

- git clone urldoprojetoquequerclonar.git

- ls → mostra todos os arquivos 

- cd entranapasta; 

- Altera o arquivo, faz o git add ., git commit e o push.



jcbombardelli/gama-no-pullrequest

### Git hub Pages

Serve para publicar o projeto com HTML, CSS e JS. 

- Setting;
- Pages → seleciona a branch que quer publicar;
- ERRO 404 → acontece quando não consegue encontrar o arquivo index.html, para solucionar o problema, pode-se adicionar ao final da url o nome do arquivo, por exemplo, admin.html ou renomear o arquivo para index.html.

![octobiwan](https://user-images.githubusercontent.com/85708747/185694379-0bf728f5-7c41-4a76-92ba-70041225a2cd.jpg)

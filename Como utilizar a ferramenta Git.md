# O que é Git ? :mag:

O Git é um projeto de código aberto maduro e com manutenção ativa  desenvolvido em 2005 por Linus Torvalds, o famoso criador do kernel do  sistema operacional Linux. Um número impressionante de projetos de  software depende do Git para controle de versão, incluindo projetos comerciais e de código-fonte aberto. 

# Passo a passo para a utlização de comandos do Git :mag:
 #### :heavy_exclamation_mark:*OBS: É necessario que você tenha a ferramenta do Git intalada em seu computador. Caso use Ubuntu, por exemplo, basta abrir o seu terminal e digitar o seguinte comando `$ sudo apt-get install git-all`. Mas caso use Windows basta acessar o site e baixar a ferramenta -> [Link para baixar o Git.](https://git-scm.com/downloads)*:heavy_exclamation_mark:
 #### 
  
* Para darmos inicio ao processo inicialmente criaremos uma pasta em nosso computador com um nome de sua preferência, por exemplo: `UsandoGit`.
* Crie um arquivo .md (MarkDown) dentro da pasta criada apenas para um exemplo, se preferir edite-o usando um editor de texto de sua preferência, como o VSCode, por exemplo.
* Acesse em seu terminal o diretório dessa pasta, caso esteja no windows basta acessa-la clicando com o botão direito dentro dela e abrindo com o `Git Bash Here`.
* Após ter acessado a pasta pelo terminal ou pelo Git bash agora iremos inicializar o repositório com o comando `git init`.
* Agora vamos colocar os arquivos dentro do nosso repositório *local* em um ambiente de "*staging area*", são onde os arquivos ficarão para posteriormente serem "commitados". Exemplo: `git add <nome do arquivo .md>`.
* Com os arquivos na *staging area* agora eles estão prontos para serem commitados. Para realizar nosso primeito commit usaremos o comando `git commit -m "primeiro commit"`.

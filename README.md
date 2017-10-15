# hello-world

I'm IT Architect learning news technologies.


GIT Initial Commands:
=======================

## **Configurando o git**
### $ git config --global user.name "YOUR NAME"
### $ git config --global user.email "YOUR EMAIL ADDRESS"



## **Clone Projects**
### git clone https://github.com/<username>/site.git

Example: 
### git clone https://github.com/sziliotti/kaggle-titanic-ml-disaster.git

Or
## **Add to Remote Repository**
### git remote add origin git@github.com:sziliotti/kaggle-titanic-ml-disaster.git



## **Comandos iniciais do git**
Com o repositório na sua máquina, vamos aprender 4 comandos iniciais que farão parte da sua vida a partir de agora:

-git add <arquivos...> Este comando adiciona o(s) arquivo(s) em um lugar que chamamos de INDEX, que funciona como uma área do git no qual os arquivos possam ser enviados ao Github. É importante saber que ADD não está adicionando um arquivo novo ao repositório, mas sim dizendo que o arquivo (sendo novo ou não) está sendo preparado para entrar na próxima revisão do repositório.
-git commit -m "comentário qualquer" Este comando realiza o que chamamos de “commit”, que significa pegar todos os arquivos que estão naquele lugar INDEX que o comando add adicionou e criar uma revisão com um número e um comentário, que será vista por todos.
-git push Push (empurrar) é usado para publicar todos os seus commits para o github. Neste momento, será pedido a sua senha.
-git status Exibe o status do seu repositório atual

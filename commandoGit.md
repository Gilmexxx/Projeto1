# LISTA DE COMMANDOS GIT NO VS CODE

|Comando| O que faz |
|-:|-|
|git init| Inicia o monitoramento do projeto |
| git branch -M main | Renomeia o branch principal ( ramificação principal ) de 'master para 'main' |
| git add | Manda o arquivo para area de stating |
| git add . | Manda todos os arquivos para a área de staging |
| git status | Verifica a sitauacao atual dos arquivos  |
| git config --global user.name <'Nome do usuario'> | Informa o nome do usuario proprietario |
| git config --global user.email <'email@dousuario.com.br'> | Informa o nome do usuario proprietario |
| git config --list | Verifica da um status dos dados do usuario - User name e email |
| git commit -m 'Primei commit' | Faz o commit de atualização |
| git log | Verifica o historico de commits |
| git checkout -b + <'NomeDaBranch'> | Cria sub branch do projeto |
| git branch | Lista as branchs do projeto |
| git checkout <'NomeDaBranch'>  | Alterna entre as branch |
| git merge <'NomeDaBranch'> | Mescla os dados da branche. Esteja na branch principal e faz o comando puxando a Sub Branch |
| git branch -d <'NomeDaBranch'> | Deleta a branch -d (minisculo) so possivel com todos os commits |
| git branch -D <'NomeDaBranch'> | Deleta a branch -D (MAISCULO) deleta a branch mesmo sem terem sido feitos os commits |
|git remote add origin https://github.com/Gilmexxx/Projeto1.git | Copia a linha la no GitHub e executa este comando no VS code local que no caso é `https://github.com/Gilmexxx/Projeto1.git`|
|git push -u origin main | Este comando envia todos os commits feitos no ramo `main` do seu repositório local para o repositório remoto chamado `origin` |


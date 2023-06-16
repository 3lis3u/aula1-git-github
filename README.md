# aula1-git-github
Este repositório é para fins de estudo do módulo git e github.
 - Para criar pasta: mkdir nome da pasta 
 - Para entrar na pasta:Cd nome da pasta 
 - Incia repositore: git init
 - Para sair de uma para: cd ..
 - Para listar arquivos da pasta: ls
 - Para criar arquivo: echo ou touch "# nome da pasta onde vai ser criado o arquivo" >> nome do arquivo .extensão	
 - Para adcionar conteudo (arquivos): git add nome do arquivo ou pasta
 - Para adcionar todos arquivos ou pasta: git add . 
 - Para desfazer um add especifico: git reset nome do arquivo
 - Para desfazer um add geral: git reset
 - Para listar o que foi feito: git status
 - Para registrar o comentario: git commit  -m "cometario aqui" 
 - Para retorna ao último commit, mantendo as alterações feitas nos arquivos: git reset --soft HEAD~1
 - Para retona ao último commit, removendo as alterações feitas nos arquivos: git reset --hard HEAD~1
 - Para retorna ao commit do ID especificado, mantendo as alterações (soft) ou removendo as alterações (hard): git reset --soft [id do commit] / git reset --hard [id do commit]

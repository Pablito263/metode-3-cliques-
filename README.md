# adiciona remote (se ainda não adicionou)
git remote add origin https://github.com/Pablito263/metodo-3-cliques.git

# buscar o que tem no remoto e rebasear seu trabalho em cima (evita conflitos no push)
git pull --rebase origin main

# resolver conflitos se houver, depois:
git push -u origin main

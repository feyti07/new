# Les commandes
  history
    1  ssh-keygen -t rsa -b 4096 -C feyti.ti@gmail.com
    2  cat ~/.ssh/id_rsa.pub
    3  git config --global user.name "Fatimetou"
    4  git config --global user.email feyti.ti@gmail.com
    5  git clone https://github.com/feyti07/new.git
    6  cd new
    7  git add index.html
    8  git log
    9  git branch ma-fonctionnalite
   10   git checkout ma-fonctionnalite
   11  git add .
   12  git status
   13  git commit -m "Modification de ma-fonctionnalite"
   14  git push origin ma-fonctionnalite
   15  git checkout master
   16  git checkout main
   17  git commit -am "Modification dans master"
   18  git merge ma-fonctionnalite
   19  git add .
   20  git commit -m "Résolution du conflit"
   21  git flow init
   22  git flow init
   23  git flow feature start ma-fonctionnalite
   24  git flow release start ma-version
   25  git flow feature finish ma-fonctionnalite
   26  git flow hotfix start mon-correctif
   27  history




github komutlari
github commands

first time initializing 
$ git config --global user.name "Your Name"
$ git config --global user.email "you@youraddress.com"
$ git config --global push.default matching
$ git config --global alias.co checkout
$ git init  == bu projeyi git repositorye cevirir


git add . / bulunan klasore git filelari at
/.ssh keyleri kullanilacak soran yerde

cat id_rsa.pub    komutuyla ssh keyimizi alalim	

…or create a new repository on the command line

echo "# TodoAppNode.js" >> README.md
git init
git add README.md
git add -A .gitignore haric proje icinde tum dosyalari git e ekliyor sanirim
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:kutaycosar/setream.git
git push -u origin main
s
…or push an existing repository from the command line

git remote add origin https://github.com/kutaycosar/TodoAppNode.js.git
git branch -M main
git push -u origin main

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


commit eklmeke icin once bu -  git add .

sonra bu git commit -am 'stupid comment added'

en son bu git push 

.gitignore files olusturup dahil etmek istemedigimiz folder veya filelarini icine yazabiliriz
node_modules/   mesela bu ikisi yazarak ignore ettik
markdown/

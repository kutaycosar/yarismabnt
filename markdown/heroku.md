heroku login  -once bu
anaklasorde Procfile file i olusturulur
procfile a su yazilir : web: node server.js ve save edilir

server.js(todoappdeki main file oldugu icin seciyoruz) de let db tanimladigimiz yere ustlere  su yazilir(asagida)
let port = process.env.PORT
if (port == null || port == ""){
  port = 3000
}

ve port listen 3000 veya hangi yerdeyse ondan tasinip olusturdugumuz port atanir

proje icinde git init edilir
git init yapilir git add -A diyerek gitognore haric her sey eklenir ve git commit i yazilir

heroku git:remote -a todoappforkutay -- herokudan girilen app ismi neyse o yazilir istegit

git push heroku HEAD:master herokuya pushlanir

-onemli-
hali hazirda herokuya push ettigimiz appde degisiklikler yapmak icin:
git add -A
Then this command:
git commit -m 'Your message to yourself regarding what you changed'
Then finally this command:
git push heroku master

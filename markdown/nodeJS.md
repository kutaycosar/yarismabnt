[express.jsWEB](https://expressjs.com/)  -- express js icinde guzel site

router = applikasyonun farkli route larini listelemek icin
controller = router in fonksiyonlarini tutuyor, middle man model ve view arasindaki
view = html gosterdigimiz sayfa iste
model = kisaca controllerlarda kullanabilecegimiz objeler


Our app.js file uses our router, the router uses our controller, our controller uses the model, and finally the model relies on a database being ready in our db.js file in order to successfully work with the collection

MVC - MODEL, VIEW, CONTROLLER




require() metodu hem set yapiyor hem return ediyor / bir nevi req,res 
ProductControllerissa on metodi GetProducts() joka tekee listan tuotteista, mitkä luetaan products.json tiedostosta. Sitten metodi Product() palauttaa ViewResultin tuotteista, eli näyttää tuotteiden tiedot. 
Product.json:sta löytyy tuotteiden nimi, hinta, kuvaus ja kuva. GetProducts() metodi käyttää näitä tietoja listatessaan tuotteet.
Product.cshtml luo käyttäjälle näytettävät asiat. Se luo otsikon ja käy läpi kaikki tuottwwt ja näyttää jokaisen kuvan, nimen, kuvauksen ja hinnan.

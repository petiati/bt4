# Bootstrap


Header-ben van egy ilyen beállítás, ami azt jelenti, hogy a weblap tartalmának a szélessége egyezzen meg az eszköz szélességével. Ezzel a vizszintes görgetéstől óvjuk meg a felhasználót.
`<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">`

Így kell beállítani, hogy milyen felbontásnál hány oszlop látszik. (12-t kell annyival osztani, ami a col után szerepel, tehát a col-sm-6 azt jelenti, hogy 'small' képernyőnél 2 oszlop lesz)

    <div class="row">
        <div class="col-12 col-sm-6 col-md-4 col-lg-3 col-xl-2 blue-bg">
                ez itt változó oszlop széles
        </div>
    </div>

Sortörést is be tudunk tenni `<div class="w-100"></div>` sort kell beilleszteni.
Tartalmat lehet igazítani, például meg lehet adni, hogy md méret felett igazítsa középre.
`<div class="row justify-content-md-center">`


## Bootstrap beállítások:

* alapok: https://getbootstrap.com/docs/4.4/layout/grid/#grid-options
* azonos szélesség: https://getbootstrap.com/docs/4.4/layout/grid/#grid-options
* egy oszlopot állítunk csak - a többi kitölti a teret https://getbootstrap.com/docs/4.4/layout/grid/#setting-one-column-width
* játék a szélességekkel: https://getbootstrap.com/docs/4.4/layout/grid/#variable-width-content
* igazítás: https://getbootstrap.com/docs/4.4/layout/grid/#alignment
*oszlop sorrend rendezés: https://getbootstrap.com/docs/4.4/layout/grid/#reordering
* offset: https://getbootstrap.com/docs/4.4/layout/grid/#offsetting-columns
* margó: https://getbootstrap.com/docs/4.4/layout/grid/#margin-utilities
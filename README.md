# test-mt

https://github.com/Manuel-spec-cell/test-mt.git


SELECT zaposlenik.id, zaposlenik_ime_prezime
FROM zaposlenik
JOIN evidencija
ON ZAPOSLENIK.id = evidencija.zaposlenik
ORDER BY evidencija.broj_sati ESC 

# Primena Šamirovog tajnog deljenja na audio fajlove
## Projekat za predmet "Numerički algoritmi i numerički softver"

U ovom projektu, koristiću princip Šamirovog tajnog deljenja
(Shamir’s Secret Sharing) kako bih omogućio bezbednu dekompoziciju i
rekonstrukciju audio fajlova. Šamirovo tajno deljenje (SSS) je
kriptografski algoritam koji omogućava podelu tajne (npr. ključa, fajla ili
informacije) na n delova (senki) tako da je za rekonstrukciju tajne
potrebno najmanje k od tih delova. Svaka pojedinačna senka ne otkriva
informacije o originalnoj tajni. Umesto klasične primene na slike, ovaj
projekat će se fokusirati na audio fajlove specifično .wav format. Glavni
cilj je podela audio fajla na „senke“ (eng. shadows) koje pojedinačno ne
otkrivaju informacije o originalnom fajlu, dok će se uz minimalan 
potreban broj senki moći rekonstruisati originalni audio.
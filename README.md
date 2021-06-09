

# ProjektOrmari 


## Opis domene
Hrvatska ima razvijen turistički sektor koji konstantno bilježi pozitivne rezultate. Ova aplikacija orijentirana je na turizam. Aplikacija rješava možda i najveći problem ljeti, a to su krađe. Korištenjem naše aplikacije korisnici bi bez ikakvog straha mogli brzo i sigurno ostaviti svoje stvari u ormariće. Prednost naše aplikacije je taj što korisnik u bilo kojem trenutku može vidjeti koliko je ormarića trenutno slobodno. Također može se korisiti u ne sezonskim okolinama kao u sportskim ustanovama ili nešto slično.

Aplikacija bi bila korištena od dvije strane, zaposlenika i korisnika. Korisnici mogu registrirati svoje račune besplatno, korisnici također mogu modificirati svoje podatke ili izbrisati račun/e. Ulogirani korisnici mogu pregledavati podatke o slobodnim i svojim iznamljenim ormarima. Za potvrdu iznajme ormara, korisnik unosi šifru dobivenu od zaposlenika objekta. Ormari se otključavaju pomoću šifre, u slučaju krivoga unosa šifre ili nekakve detekcije zloupotrebe aktivira se alarm. Alarm obaviještava korisnika o potencijalnoj zloupotrebi ormara, te daje opciju za zaštitu ormara ili deaktivaciju alarma, u slučaju nikakvog odgovora u određenom roku vremena, zaštita se aktivira. 
Zaposlenik imas vlastiti prikaz o ormarima, koji su slobodni, zauzeti i pod zaštitom. Deaktivacija zaštite se radi od strane zaposlenika koji su obaviješteni o aktivacij zaštite ormara.

## Specifikacija projekta



Oznaka | Naziv | Kratki opis
------ | ----- | -----------
F01 | Registracija i prijava računa | Za uspostavu korisničkog računa potrebna je registracijska funkcionalnost. Za pristup računu potrebna je autentifikacija korisnika pomoću login funkcionalnosti. Korisnik se prijavljuje s podatcima koji su mu dodijeljeni prilikom registracije ili daljne modifikacije korisničkog računa.
F02 | Modifikacija korisničkih podataka | Nakon prijave na korisnički račun, korisnik će imati opciju da modificira svoje podatke ili obriše svoj račun.
F03 | Pregled i iznajmljivanje ormara | Pruža pregled svih slobodnih ormara, pregled svojih iznajmljenih ormara.
F04 | VasiOrmarici | Omogućava korisniku pregled njihovih iznajmljenih ormara, mogućnost objavljivanja komentara vezano za iznajmljen ormar, otkazivanja iznajmljenog ormara, produživanje vremena iznajmljenog ormara.
F05 | Komentari | Omogućava korisniku prikaz komentara za ormare, te obavijesti objavljene od strane administatora za ormare.
F06 | Administrator | Omogućava administratoru kreiranje ormara, brisanje ormara, anžuriranje ormara uz objavu obavijesti, prikaz slobodnih i zauzetih ormara.
F07 | Detekcija zloupotrebe | Detektiranje zloupotrebe ormara ostvaruje se kada korisnik, nakon prijave na sustav, pokuša otvoriti ormarić koji nije registriran pod njegovim imenom.
F08 | Aktivacija zaštite | U slučaju alarma, aktivira se automatska zaštita (zaključavanje) ormara i stvara se alarm za administratora i trenutnog korisnika ormarica (ukoliko je ormaric iznajmljen).
F09 | Deaktivacija zaštite | Nakon što je ormarić zaštićen, postoji mogućnost za deaktivaciju zaštite kroz administratorski račun.
F10 | Prodaje aplikacije različitim tvrtkama.
F11 | IznajmiOrmaric | Omogućava korisniku iznajmljivanje ormara / generira račun u pdf formatu, te šalje pdf na email korisnika.
F12 | Statistički podatci | Administrator ima pristup formi koja prikazuje različite statističke podatke u grafičkom i tabličnom obliku te postoji mogućnost ispisa u PDF. Zatim je moguće isprintati pdf dokument.


## Tehnologije i oprema
* Microsoft Visual Studio 2019
* Microsfot excel
* Bitrix 24
* Mysql workbench
* Github
* Microsoft Office
* Visual paradigm
* C#.NET Framework

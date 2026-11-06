# Ringette E-juniori vaihtokello

Yksinkertainen selainpohjainen ajastin E-junioreiden otteluiden vaihtovihellysten seuraamiseen.

Sovellus on suunniteltu ottelutoimitsijoille helpottamaan 50–70 sekunnin vaihtosäännön noudattamista.

## Ominaisuudet

- Suurikokoinen koko näytön ajastin
- Ajan näyttö 0,1 sekunnin tarkkuudella
- Musta tausta alle 50 sekuntiin asti
- Oranssi tausta 50 sekunnin jälkeen
- Äänimerkki 50 sekunnin kohdalla
- Punainen vilkkuva hälytys 70 sekunnin jälkeen
- Voimakkaampi hälytysääni 70 sekunnin kohdalla
- Ajastin jatkaa laskemista myös 70 sekunnin jälkeen
- Korjauspainikkeet (+1 s / -1 s)
- Näytön sammumisen esto (Wake Lock API)
- Koko näytön tila yhdellä painalluksella

## Käyttö

1. Avaa https://swd1tn002.github.io/ringette selaimessa.
2. Paina **Start** ottelun käynnistyessä tai vaihdon jälkeen.
3. Kun peli katkeaa vaihtoa varten:
   - suorita vaihto
   - paina **Reset**
   - paina **Start**
4. Tarvittaessa korjaa aikaa painikkeilla:
   - **+1 s**
   - **-1 s**

## Pikanäppäimet

| Näppäin   | Toiminto              |
|-----------|-----------------------|
| Space     | Käynnistä / Pysäytä   |
| Enter     | Nollaa                |
| ←         | -1 sekunti            |
| →         | +1 sekunti            |

## Sääntötausta

Sovellus perustuu Suomen Ringetteliiton E-junioreiden harrastesääntöihin:

- Vaihto tapahtuu seuraavasta pelikatkosta, kun tehokasta peliaikaa on kulunut 50 sekuntia.
- Jos pelikatkoa ei tule 70 sekuntiin mennessä, toimitsijat antavat äänimerkin ja peli pysäytetään vaihtoa varten.


## Tekoälyn käyttö

Tämä sovellus on toteutettu Microsoft Copilotin ja GitHub Copilotin avulla.

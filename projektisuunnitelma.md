ELEC-A4010 Sähköpaja, projektisuunnitelma
PVM: 15.02.2024
!(Drone)[Images/Drone.webp]
Ryhmä: 
- Niklas Eloranta, niklas.eloranta@aalto.fi
- Juho Aikio, 
- Leo Di Poi, 
- Veli-Pekka Saarinen, 

Nimikkoassistentti: Henrik Toikka

Rainbow Six Siege -Drone

Tarkoituksena on rakentaa lähes samankaltainen drone kuin pelissä Rainbow Six Siege. Joitain muutoksia on tehtävä, koska dronen osien toiminnallisuus ei aina vastaa todellisuutta. Esimerkiksi pelkästään kaksi mecanum tyyppistä pyörää ei mahdollista pelissä nähtävää vapaata vaakatasoista liikettä. Päätimme käyttää niiden sijasta kolmea omnipyörää. Dronen rakenne on suurimmilta osin vain yksi putki, jonka sisälle kaikki on mahdutettava. Putki tulostetaan kahdessa osassa, jotka yhdistetään ruuveilla. Pituutta tulee jonkun verran, koska moottorit on mahdutettava sivuille. Putki suunniteltiin niin, että raspberry mahtuisi makaamaan sivuittain sen sisälle. Akun paikkaa ei ole vielä suunniteltu ja kolmannen pyörän moottori olisi myös jotenkin mahdutettava keskelle dronea. Akun tyypistäkään ei ole vielä käyty keskustelua, koska moottoreita ei ole valittu. 

Ohjauksen vastaanottamiseen sekä kameran kuvan lähettämiseen käytetään Raspberry Pi 3B:tä. Käytettävä kamera on Raspberry Pi Camera Module V2 ja sen kuvaa lähetetään samassa (ja myöhemmin mahdollisesti eri) verkossa oleville laitteille niin, että suoratoistoa voi seurata selaimesta. Tähän käytettiin apuna Picamera2 python kirjastoa ja kirjaston dokumentoinnista löytyvää valmista koodia. Drone tulee olemaan kauko-ohjattava. Emme ole vielä päättäneet miten toteuttaisimme tämän. Paras tapa olisi varmaankin käyttää jotain valmista ohjainta, jos joltain sellainen löytyy, tai kännykän sovelluskaupasta löytyvää ohjainta. Jos aikaa löytyy, voisi sen myös koittaa tehdä pajalta löytyvistä joystickeistä ja napeista itse.

Tarvittavat osat:
- Raspberry Pi 3B
- Raspberry Pi Camera Module V2
- 3 omnipyörää
- 3 DC-moottoria
- Akku (tai paristot?)
- Moottorinohjain
- Jokin kauko-ohjain
- 3D-printtaus
  - Runko

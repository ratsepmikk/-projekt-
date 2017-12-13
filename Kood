#Tekitab muutuja nime kasutaja sisendiga
import time
päevik = ""
sugu = input("Sisesta oma sugu: ")
nimi = input("Sa sündisid ja su vanemad valivad sulle nime, mis see olla võiks: ").title()
print("Sa oled " + nimi + ", oled " + sugu + " ja sa sündisid Euroopas.")
time.sleep(2)
essa = input("Sa kasvad ja saad vanemaks, õpid rääkima, mis on sinu esimene sõna? ")
print("Ema : Oi, sa ütlesid " + essa + ", see tuleb küll päevikusse kirja panna.")
päevik += "Esimene sõna : " + essa.title() + "\n"
time.sleep(3)
print("Möödub paar aastat ja sa saad kolme aastaseks. Sul on kolmas sünnipäev, sulle on laul lauldud ja sa pead küünlad ära puhuma.")
time.sleep(2)
from random import *
võimalus = randint(1,100)
if võimalus <= 25:
print("Ilastasid koogi peale, kuid kustutasid küünlad ära. keegi ei taha enam kooki ja sa said kõik endale.")
päevik += ("Kolmas sünnipäev: Ilastasid koogile ja said kogu koogi endale" + "\n")
else:
print("Puhusid küünlad ära ja kõik naudivad torti. Oli hea sünnipäev.")
päevik += ("Kolmas sünnipäev: Oli üks parimaid mälestusi su elus." + "\n")
time.sleep(5)
pahatahtlik = randint(1,10)
sõbralik = randint(1,100)
rahulik = randint(1,100)
print("Möödub kolm aastat ja sa oled lasteaias.")
time.sleep(2)
valik1 = ""
while valik1 != "pahatahtlik" or valik1 != "sõbralik" or valik1 != "rahulik": 
valik1 = input("Vali, kas sa oled sõbralik, pahatahtlik või rahulik: ")
if valik1 == ("sõbralik"):
if sõbralik > pahatahtlik:
print("Oled paljude lasteaiakaaslastega sõber. Sul on lasteaias tore")
päevik += ("Lasteaed : Möödus toredalt" + "\n")
break
elif pahatahtlik > sõbralik:
print("Üritasid palju, et sõbruneda lasteaiakaaslastega, kuid see ei õnnestunud.")
päevik += ("Lasteaed : Lasteaias ei olnud sul väga sõpru ja sa olid üksik" + "\n")
break
elif valik1 == "pahatahtlik":
if pahatahtlik >= 3:
print("Sa oled väga pahatahtlik ja sul pole palju sõpru.")
päevik+= ("Lasteaed : Lastead oli väga probleemne" + "\n")
break
elif pahatahtlik < 3:
print("Sa ei olnud lasteaias eriti sõbralik, aga su rühmakaaslased võtsid sind vastu")
päevik += ("Lastead : Sa käitusid halvasti!" + "\n")
break
elif valik1 == "rahulik":
if rahulik <= 50:
print("Sul on paar head sõpra, kuid ülejäänutega ei suhtle")
päevik += ("Lasteaed : Möödus rahulikult ja hästi" + "\n")
break
elif rahulik > 50:
print("Suhtled kõigiga, kuid sul pole häid sõpru")
päevik += ("Lasteaed : Möödus hästi, aga oleks saanud paremini" + "\n")
break
time.sleep(3)
print("Sa oled nüüd 7 aastane ja sa lähed põhikooli. On 1. september 2001. Toimus tutvusring")
time.sleep(3)
sõber = "Valdis"
print("Sa tutvusid " + sõber + "ega ja ta sai su parimaks sõbraks")
time.sleep(3)
if valik1 == "sõbralik":
print("Te saite omavahel hästi läbi ja te tegite kõike koos. Temast saab kindlasti sõber terveks eluks.")
päevik += ("Klassikaaslane : Said uue sõbra " + sõber + " koguks eluks." + "\n")
elif valik1 == "pahatahtlik":
print("Vahel sa käitusid oma uue sõbra vastu halvasti, aga te saite kenasti läbi. Tegite koos pahandusi.")
päevik += ("Klassikaaslane : Olite kaks paharätti" + "\n")
elif valik1 == "rahulik":
print("Suhtlesite sõbraga rahulikult ja veetsite enamus aja koos")
päevik += ("Klassikaaslane : Käitusite normaalselt ja saite häid hindeid" + "\n")

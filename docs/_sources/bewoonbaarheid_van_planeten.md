# 3. Bewoonbaarheid van planeten

<span style="color: green;"><em>expertgroep natuurkunde</em></span>


## 3.1 Evenwichtstemperatuur

In de voorbereidende opdracht heb je een formule afgeleid waarmee je een ruwe schatting kunt geven van de temperatuur op een planeet. We gingen daarbij uit van stralingsevenwicht: het stralingsvermogen dat de planeet van de ster ontvangt is gelijk aan het stralingsvermogen dat de planeet zelf uitstraalt.

De intensiteit $I$ die op de planeet valt is te berekenen met de kwadratenwet:

$$
I = \frac{L}{4 \pi d^2}
$$

waarbij $L$ de lichtkracht van de ster is en $d$ de afstand van de planeet tot de ster.  
De lichtkracht van de ster volgt uit de wet van Stefan-Boltzmann:

$$
L = 4 \pi R_s^2 \sigma T_s^4
$$

waarbij $R_s$ en $T_s$ de straal en temperatuur van de ster zijn. Substitueren geeft:

$$
I = \frac{R_s^2 \sigma T_s^4}{d^2}
$$

Van het invallend vermogen wordt een fractie $A$ door de planeet teruggekaatst (albedo). Het opgenomen vermogen is:

$$
P_{in} = (1 - A) \cdot I \cdot \pi R_p^2
$$

De planeet straalt zelf ook energie uit:

$$
P_{uit} = 4 \pi R_p^2 \sigma T_p^4
$$

Uit stralingsevenwicht volgt:

$$
(1 - A) \cdot \frac{L}{4 \pi d^2} \cdot \pi R_p^2 = 4 \pi R_p^2 \sigma T_p^4
$$

Vereenvoudiging geeft:

$$
(1 - A) \cdot \frac{L}{4 \pi d^2} = 4 \sigma T_p^4
$$

Evenwichtstemperatuur:

$$
T_p = \left( \frac{(1 - A) \cdot L}{16 \pi \sigma d^2} 
\right)^{1/4}
$$

## 3.2 Bewoonbare zone

De bewoonbare zone is de zone waarin vloeibaar water op een planeet mogelijk is.

### Naïeve aanpak

Neem aan dat het vriespunt van water 273 K is en het kookpunt 373 K.

**Opdracht 1**  
Waarom zou deze aanname onjuist kunnen zijn? Wat is de invloed van de massa van de planeet op de geldigheid van deze waarden?

**Opdracht 2**  
Schrijf de formule voor $T_p$ om naar een uitdrukking waarmee je $d$ kunt berekenen voor het vries- of kookpunt van water.  
Wat zijn volgens deze aanpak de grenswaarden voor de bewoonbare zone rond de zon, gegeven in AU?

### Gedetailleerder model

Zoals eerder gezegd houdt de eenvoudige aanpak geen rekening met het broeikaseffect of albedo. Deze factoren beïnvloeden de ligging van de bewoonbare zone.

De intensiteit op een planeet is:

$$
I = \frac{L}{4 \pi d^2} 	
$$

**Opdracht 3**  
Laat zien dat als $I_{exo} = I_{aarde}$, dan geldt:

$$
d_{AU} = \sqrt{ \frac{L_{ster}}{L_{zon}} } 	
$$

We introduceren de effectieve zonneflux $S_{eff}$:

$$
S_{eff} = \frac{I_{exo}}{I_{aarde}} 	
$$

**Opdracht 4**  
Leid m.b.v. formule (1) en (3) de volgende vergelijking af:

$$
d = \sqrt{ \frac{L_{ster}}{L_{zon} \cdot S_{eff}} } 	
$$

Conservatieve grenzen van de habitable zone (AU):

- $S_{eff} = 1{,}1$ → binnenrand (runaway greenhouse)  
- $S_{eff} = 0{,}53$ → buitenrand (maximum greenhouse)

**Opdracht 5**  
Laat zien dat dit de grenswaardes zijn voor de habitable zone rond de zon. Vergelijk dit met opdracht 2.  
Vallen Mars en Venus binnen deze grenzen?

## 3.3 Rekenen aan exoplaneten

Bezoek: [https://phl.upr.edu/hwc](https://phl.upr.edu/hwc)  
De lijst toont potentieel bewoonbare exoplaneten. De benodigde gegevens staan per planeet vermeld.

**Opdracht 6**  
a) Bereken m.b.v. formules (2) en (4) de habitable zone rond Trappist-1. Vergelijk met de afstand tot haar exoplaneten.  
Let op: $L_* = \log \left( \frac{L_{ster}}{L_{zon}} 
\right)$  Dus:

$$
\frac{L_{ster}}{L_{zon}} = 10^{L_*}
$$

b) Doe hetzelfde voor twee andere stelsels.

**Opdracht 7**  
Bereken voor de gevonden exoplaneten $S_{eff}$ en vergelijk met de opgegeven flux $S$ in de tabel.  
Bespreek eventuele verschillen.

## 3.4 Earth Similarity Index en Planet Habitability Index

De bewoonbare zone geeft een eerste indicatie op basis van afstand tot de ster. Als er meer data is (massa, straal, temperatuur), dan kunnen aanvullende indices worden gebruikt:

- **ESI (Earth Similarity Index)**: hoe sterk lijkt de planeet op aarde?
- **PHI (Planetary Habitability Index)**: hoe groot is de kans dat leven mogelijk is?

**Opdracht 8**  
Bedenk een voorbeeld van een planeet die buiten de habitable zone ligt en toch bewoonbaar kan zijn. Hoe zou dat kunnen?


# Climate System Modelling

Notes for classes of course part of M.Sc. in Science of Climate at UniBo.

## Brief timeline of climate modelling

1. 4th century BCE: first book on meteorology, De Meteorologica by **Aristotle**
    1. Argumentative approach vs factual
    2. Mentions climate change
2. 1904: Vilhelm **Bjerkenes**, two rules to create a climate model:
    1. knowing the initial state
    2. knowing the laws that connect two subsequent states
3. 1922: Lewis Fry **Richardson** first attempted to do a climate model (still useful blueprint). Reasons for failure:
    1. equations were too complex (not all wave solutions are equally important for climate)
    2. calculations were almost impossible to do by hand
4. 1930s: Carl Gustav **Rossby** found the required approximations
5. late 1940s, early 1950s: Jule **Charney** group at Princeton with Von Neumann computer at IAS
6. 1956: **Philips** introduced simple forcing and carried out time integration independent of initial state
7. 1950s and 1960s: first computer centers for numerical climate simulations (GFDL --> NOAA and others)

## Climate vs weather

Components:
1. Atmosphere
2. Hydrosphere (oceans, rivers, underground water, water cycle)
3. Cryosphere
4. Biosphere (terrestrial and marine ecosystems)
5. Ground, mountains
6. Sun --> only source of energy

## General circulation

Modern view (Tor **Bergeron**) --> 3 cells:
1. **Hadley**, direct --> high precipitation InterTropical Convergence Zone (**ICTZ**)
2. **Farrel**, indirect --> rectified effect, a statistical remnant
3. Polar (direct, weaker)

### Winds

#### Zonal winds

East-west or west-east wind component.  
Zonal winds exhibit a strong seasonal cycle.  

1. Trade winds (easterlies) --> negative $u < 0$
2. Westerlies --> positive $u > 0$, due to Coriolis force
3. Jet stream, tropospheric westerly with max $u >$ Earth's speed of rotation, circumpolar vortex is contained by jet stream

#### Meridional winds

North-south or south-north wind component.  
Meridional winds are due to 3-cell circulation, they can reverse the direction with the season.  

#### Surface winds

Surface winds create torque over oceans.

### Temperature

Lapse rate:
1. Polar vs. mid-latitude vs. tropics
2. Summer vs. winter
3. Near surface inversion in polar winter

Average surface temperature:
1. Continentality --> mostly northern empisphere
2. Ocean currents can mitigate temperatures at higher latitudes

### Humidity

Most atmospheric water is along the equatorial area and in the lower levels.

### Geopotential

The geopotential (height) is the height at which a specific level of pressure can be found (e.g. 500 or 800 or 1000 hPa).  
Wind blows keeping high geopotential to the right.  

**Eddy field**: $ \phi = \overline\phi + \phi' $

### Mean sea level pressure

Integrates all features due to the other quantities.

### Sea surface temperature (SST)

Higher at the equator and east-west gradient.

## Energy

### Energy budget

$ F_{RAD} - F_{SH} - F_{LH} - F_{G} - F_{H} = 0 $

Workshop 2: Nonlinear Models
================
Meredith Emery
1/17/2020

# Objectives

The primary objectives of this analysis is to fit monthly light response
curves for Harvard forest to understand annual patterns ecosystem
photosynthetic potential and respiration rates in temperate mixed
forests..

# Methods

## Site Information

### Harvard Forest

The Harvard Forest has been part of the Long-Term Ecological Research
(LTER) since 1988. There are several towers that collect different
aspects of the forest, including; light, temperature and CO2. The data
for this project is from the Environmental Measurement Station Eddy Flux
Tower (EMS), shown as a yellow dot located on the right side of the
picture near the border and the NEON Tower, which is shown as a red dot.
Two variables that we will use from the EMS tower is the irradiance
(light) and temperature of the forest.

**Location:** Massachusetts, USA

**Climate:** Cool, moist temperate July mean temperature 20°C January
mean temperature -7°C; Annual mean precipitation 110 cm, distributed
fairly evenly throughout the year.

**Vegetation:** Transition Hardwood - White Pine - Hemlock Region
Dominant species: Red oak (*Quercus rubra*) Red maple (*Acer rubrum*)
Black birch (*Betula lenta*) White pine (*Pinus strobus*) Eastern
hemlock (*Tsuga canadensis*)

![Hardvard Forest
Map](https://harvardforest.fas.harvard.edu/sites/harvardforest.fas.harvard.edu/files/data/p07/hf070/site-map.jpg)

Figure 1. Hardvard Forest Map of the tower location.
(<https://harvardforest.fas.harvard.edu/>)

## Photosynthetic Potential

The maximum amount of carbon dioxide that the forest can fix depends on
the amount of light the forest experiences. The photosynthetically
active radiation (PAR) is the radiation range between 400-700nm wave
band. Thus, the photosynthetic potential is the most carbon fixed when
experience a certain amount of radiation, also called the Pmax. The
amount of photosynthesis with respect to a given irradiance does not
follow a linear equation, instead it follows the Michaelis-Menten
Approach equation given below.

\[NEE_{day}= R_{eco} - \frac{\alpha\phi P_{max}}{\alpha\phi + P_{max}}\]

\[NEE_{day}\] is the Net Ecosystem Exchange during the day \[R_{eco}\]
is the Ecosystem respiration \[\alpha\] is the apparent quatum effiency
\[\phi\] is the maximum ecosystem CO\_{2} uptake rate

![Photosynthesis-irradiation
curve](https://upload.wikimedia.org/wikipedia/commons/6/6d/Photosynthesis-irradiance_curve.gif)

Figure 2. Photosynthesis-irradiation curve. Shows the maximum
photosynthetic potential (\(P_{max}\)).
(<https://en.wikipedia.org/wiki/PI_curve>).

## Ecosystem Respiration

The amount of carbon dioxide that is release back into the atmosphere
from autotrophic and heterotrophic production is called ecosystem
respiration. Plants respire carbon dioxide at night and the amount is
temperature dependent. Therefore, the ecosystem respiration follows the
Arrhenius Approach equation given below.

\(NEE_{night}= R_{eco} = R_{0}exp^{b-T_{air}}\)

\(NEE_{night}\) is the Net Ecosystem Exchange during the night, which is
the same as the Ecosystem Respiraiton (\(R_{eco}\)) \(R_{0}\) is base
repiration rate when the air temperature = 0 b is the emperical
coefficent \(T_{air}\) is the air temperature

![Carbon Movement
Diagram](https://www.nceas.ucsb.edu/files/news/images/Carbone_CarbonMovementDiagram_0.png)

Figure 3. Carbon movement between photosynthesis, carbon uptake, and
ecosystem respiration, carbon release. (www.nceas.ucsb.edu)

# Results

NEE per
Year

<img src="Assignments_Workshop-2-Nonlinear-models_files/figure-gfm/unnamed-chunk-1-1.png" style="display: block; margin: auto;" />

Light Response Curve
<img src="Assignments_Workshop-2-Nonlinear-models_files/figure-gfm/unnamed-chunk-2-1.png" style="display: block; margin: auto;" />

<img src="Assignments_Workshop-2-Nonlinear-models_files/figure-gfm/unnamed-chunk-3-1.png" style="display: block; margin: auto;" />

Temperature Response Curve
<img src="Assignments_Workshop-2-Nonlinear-models_files/figure-gfm/unnamed-chunk-4-1.png" style="display: block; margin: auto;" />

# Discussion (1 paragraph)

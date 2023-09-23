# DarkMatterOrbits

Repo for Dark Matter orbits crossing Normal Matter objects until better repo is found

Here you can find the paper in which I describe the Dark Matter interaction with dense normal matter objects and a simulator in which you can configure a layered sphere setting densitiy on each of the layers to validate the hypothetical dark matter particle trajectory

# Simulator

Simulator consists on a dark matter particle and a the possibility to set several densities for a layered sphere centered in (0,0). 

Simulator can be found [here](https://f-alonso-vendrell.github.io/DarkMatterOrbits/CentralForce_Simulation.html)

There are some scenarios you can test:

## Scenario 1 - Non interecting orbits, inverse square force, kepplerian orbit

set p(r<1) to 0.5 other values to cero, everything else default values... you should see a keplerian orbit around it with one of the focus of the ellipse in the center of the sphere.

## Scenario 2 - Full intersecting orbit in uniform density sphere, linear force, closed orbit

set all p's to the same value (e.g. 0.5), everything else defautl values... you should also see an ellipse, but this time the center of the ellipse is the center of the sphere. This is the same as if an ideal spring is fixed at the center

## Scenario 3 - Mix, non closed orbit

set all as defaults, you will see the combination of the two abova which causes a non-closed orbit

## Scenario 4 - The hollow planet, zero gravity inside

set all densities to zero except the last one, set p(3<r<4) to 1. You will see that orbit within the hollow space is an straight line.

## Scenario 5 - Play with parameters

Play with densities, parameters, see how the different trajectories. You can also play with the original simulator in [OSP](https://www.compadre.org/osp/EJSS/3561/5.htm?F=1) writting a central force in a continuous way.

# Paper

Papers in pdf can be found in this [repository](https://f-alonso-vendrell.github.io/DarkMatterOrbits/DarkMatterOrbits.pdf) and in [Academia](https://www.academia.edu/105948768/Dark_Matter_orbits_intersecting_dense_Normal_Matter_objects?sm=b)

A text version is also copied here:

# Dark Matter orbits intersecting dense Normal Matter objects

Fernando Alonso Vendrell
(Aug 13th-21st, 2023)

I present a simple analysis of the orbits of dark matter particle or clump of particles should follow when crossing a dense normal matter object such as a planet or a star. This simple analysis should serve to correct existing publications and could be used a starting point for a more detailed analysis which will require better modeling of the dark matter and the dense normal matter object.


## I. BACKGROUND

Dark Matter models are one of the existing proposals to explain galaxy level and cosmological level dynamics discrepancies if only matter and energy from the Standard Model and General Relativity is taken into account.

As such, this Dark Matter (DM onward) should have little or no electromagnetic, strong or weak interaction with Normal Matter (NM onward).

The only noticeable effects we can test are gravitational effects DM produces in NM.

Previous gravitational analysis known to the author focus on how dark matter distribution affects known observational data and only dark matter heating [1] in which bursts of NM out of galaxies also alter the distribution of DM to higher orbits

Some articles found for general public “What Would Happen If You Became Dark Matter? (2017)”[2] and later “Que se passerait-il si la matière ordinaire qui nous compose était convertie en matière noire? (2018)” [3] present DM particles orbiting within dense objects following Kepler orbits, nevertheless that should not be the case if those hypothetical particles exists as I will show in this paper.

## II.- GLOBAL ASSUMPTIONS

Since this is a simple approach there are some assumptions which align with what is assumed today for DM and dense NM bodies like asteroids, planets or stars:

    • DM only interacts with NM via gravitation.
      
    • DM is modeled as one indivisible distribution of mass (in particular it will be a point-like mass). We will refer to the DM particle.
      
    • NM object will be modeled as a spherical symmetrical non rotating object hold together by its gravity in equilibrium by electromagnetic forces between the atoms.
      
    • The regime of the study will be considered in the low energies so no relativistic effects are relevant (like motion of DM and NM is small, radius of NM object is big in comparison to the Schwarzschild radius…).
      
    • The mass of the DM particle is very low in comparison with the mass of the NM object
      
    • The DM particle is bounded to the NM object (it has not enough energy to escape to infinite) and there are no other massive objects that affect the analysis

## III. INITIAL ANALYSIS 

To simplify initial approach we will add an initial assumption that will be later be dropped which can be expressed like the DM doesn’t loose any energy from interaction with NM.

This initial analysis cover the case of a DM particle orbiting a NM object without crossing the NM object at any time.

In this case the DM orbit is an ellipse with one of the focus in the center of the NM object, this orbit is closed. That scenario is represented in Figure 1. where the NM object is the first circle.


 
which follows a central force of the form:


With M being the mass of the NM object and G is the Gravitational Constant.

The second scenario is that in which the whole orbit of the DM particle is embedded into the NM body.

As a first step we will consider the NM body of uniform density.

In this case we need to take into account the Shell Theorem [4] and only the mass of the sphere centered in the NM object center up limited to the position of the DM particle really accounts for gravitation force, so the inverse square law does not apply and rather as Wikipedia says “inside a solid sphere of constant density, the gravitational force within the object varies linearly with distance from the center, becoming zero by symmetry at the center of mass".




Where ρ is the NM object density.

That kind of force F=kr is the kind of force a spring exerts on an object and the resulting orbit for it is also an ellipse but this time with the center of the ellipse being the center of the NM object. That scenario is represented in Figure 2. where the NM object covers all the area represented.


The third and last scenario in this chapter is that in which we keep the NM object properties but part of the orbit of the DM particle is inside of the NM object while other part is outside of the NM object.



In this third scenario the central force field is not aligned to either isotropic oscillator or Kepler orbits, and as per Brentand’s Theorem [5] in general (e.g. excluding circular orbits) the orbits will not be closed.

This third scenario will also be present if we consider the NM body made of layers of different density, or where the density varies as a function of depth, expecting to be higher in the center.

An example of such scenario is represented in the following figure in which the radius of the NM object has been set to 3. 


As we can see there will be a maximum height and maximum depth where the DM particle will be, deviating clearly from the initial version of the articles that triggered the creation of this paper. [2][3]

## IV.- DYNAMICAL FRICTION EFFECTS

The previous analysis is based on the assumption that no energy is transferred from the DM particle to the NM object or the surrounding space-time.

It is known that via gravitation objects can exchange energy, like the slingshot effect used by space probes to get or loose kinetic energy assisted by the gravity of an orbiting planet or moon. 

In this particular case I will cover the effect called Dynamical friction [6] which as in the case of Dark Matter topic has been studied on solar system scales or bigger, but not the cases covered in this paper, at least known to the author.

A bounded DM particle that crosses NM object should loose energy in this form, giving part of the DM kinetic energy to compress the NM around it and that work is ultimately converted to heat in the NM.

As the DM particle looses energy it should end up in (or quite near) the center of gravity of the NM object.

As an initial estimate we can consider what is the dynamical friction produced by a cylinder of NM of radius R, density ρ, compressibility k that is traversed by a DM particle of mass M


Assuming that the work done in an object of mass m by increasing the pressure and keeping temperature constant can be approximated as:



(taken from stackexchange question [7])

Assuming Pi=0 and to calculate the work done on a single ring we have:



with



Also Pmax for the ring will be when the DM particle is at the ring center and we can assume that we have hydro static equilibrium with:



Integrating the differential then Pmax for the ring of radius r is



so now the differential of work is:



which can be simplified to:



Assuming in the vicinity ε of the DM particle is empty space (as it is for distances below the inter atomic distances) we can calculate the work done on a dl section of the cylinder from that empty space to a radius R integrating the rings, we then get:



Also since the work done compressing the slice comes from DM kinetic energy loss we can estimate the energy and its lost as:

Ek = ½ M v2

As such then the differential lost is given by:



Equating both expressions we get that:





So after a length of cylinder L we get



which satisfies the velocity squared units, being the logarithm dimensionless:



And is only physically valid until vf is zero.

This formula can be compared with the one in Wikipedia for which also there is an inverse relationship with velocity (cubed) but in this case, the formula is bounded.

 For some reference numbers we can use Earth as a reference and check if there is some possibility to capture DM particles that hit earth with a velocity above escape velocity (around 11Km/s):

k=6.9×10−10 m2/N [8] 
ρ = 5.51Kg/m3
G=6.674×10−11 m3⋅kg−1⋅s−2 
M (hypothetical) = 1Kg
R=1m (affects as logarithmic)
ε=10−10 meters (as a reference of inter-atomic distance in solids)

We get that the difference of the square of the velocities per 1000 km is around 5.86⋅10-21 which is quite small to trap any DM particle that hit earth on a normal meteorite velocity well above Earth’s escape velocity. 

## V. CONCLUSION:

I have shown that DM particles should follow non-keplerian orbits when crossing NM objects, also given that those objects are not uniform the orbits will not be closed, although limited between a maximum and minimum radius. Articles that triggered this paper [2] and [3] should be revisited and corrected.

I have also shown that DM should loose energy when crossing NM objects and that an initial estimate of that shows a very small number when crossing earth, making it impossible to capture DM particles. 

Similar estimates could be done with stars in which higher density, escape velocity and radius could allow for certain DM particles to be captured inside.

## VI. ACKNOWLEDGMENTS AND DISCLAIMER

This paper was initially triggered by an article in “starts with a bang” in Forbes [2] which gave me initial discomfort in some of the sentences, nevertheless I have learned a lot from the articles by Ethan Siegel so I would like to thank him for his work in making hard science reachable to general public.

I have done some search in Arxiv ( https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=Dark+Matter&terms-0-field=all&terms-1-operator=AND&terms-1-term=Orbit&terms-1-field=title&classification-physics=y&classification-physics_archives=astro-ph&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first)  or Google about this topic and haven’t found any article about these two particular topics.

Nevertheless, it is very likely that this topic has already be presented before this paper, should that be the case, I recognize credit of it to whoever did it before me and I present apologies to not referencing it in this version.

Additionally, I have based the model on a limited set of information (mostly Wikipedia), Nicholas Wheeler Central Force Probleams,  Ethan Siegel, and Wolfgang Cristian for the central force simulator [9] which I used and modified to show 3rd diagram, I would like to thank all the authors for the time taken to provide such useful information.

I would also like to thank my wife for her patience when I dedicate time for these ideas and my daughters for the notebook where I started sketching this idea.

I would also like to thank my brother Enrique Alonso and my cousin Guillermo Padilla as unaware reviewers of this paper once I publish it (note: this version is not reviewed)

## VII. - REFERENCES

[1]https://www.forbes.com/sites/startswithabang/2019/02/15/cold-dark-matter-is-heated-up-by-stars-even-though-it-cannot-feel-them/?sh=8783883f1149

[2]https://www.forbes.com/sites/startswithabang/2017/11/02/what-would-happen-if-you-became-dark-matter/?sh=14679ab3fd29 

[3]https://trustmyscience.com/que-se-passerait-il-si-la-matiere-ordinaire-qui-nous-compose-etait-convertie-en-matiere-noire/ 

[4]https://en.m.wikipedia.org/wiki/Shell_theorem

[5]https://en.wikipedia.org/wiki/Bertrand%27s_theorem

[6]https://en.wikipedia.org/wiki/Dynamical_friction 

[7]https://physics.stackexchange.com/questions/67513/deriving-work-done-on-a-solid

[8]https://en.wikipedia.org/wiki/Compressibility 

[9]https://www.compadre.org/osp/items/detail.cfm?ID=12989 







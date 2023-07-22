# Acoustic_energy_harvester
The aim of this project is to design a model of Helmholtz resonator which
could give maximum output(in terms of current output etc..) in real life
scenario(roads, railways).

Acoustic energy is the energy concerning the mechanical vibrations from its
components. The acoustics are mainly classified into environmental acoustics,
musical acoustics, ultrasounds, infrasound etc.. based on the source and frequency of
waves. Here, in this project the main concentration is on environmental acoustics.
Noise caused by roadways, aircraft and activities that are related to the environment
which releases sound into environment(unwanted noise) comes under environmental
noise(environmental acoustics). Therefore, the AEH(acoustic energy harvester) is a
model which absorbs this unwanted energy released into atmosphere(sound energy)
and coverts into electrical energy which we humans almost use every moment in our
lives. The importance and need of Acoustic energy harvester can be well understood
by looking at the advantages of using solar panels, wind mills etc. <br/>

Why do we need AEH? <br/>
- It absorbs the energy which is almost redundantly present in atmosphere and makes sense out of it! <br/>
- It helps in producing electric energy which can be either used instantly or stored for later use. <br/>

Statistics says that the contribution of fossil fuels in electric energy production is more than 70 percent. So, the use of acoustic energy harvester to produce electric energy ‘efficiently’ can save large amounts of fossil fuels which are non-renewable and can thereby contribute its part to decreasing environmental pollution. <br/>

<code style="color : red ">Contributions of various sources to electrical energy production</code> <br/>
![image](https://github.com/112101011/Acoustic_energy_harvester/assets/111628378/1644448e-9891-40ac-ab8c-1825ce518f09)

A field survey is conducted to observe the frequencies of noise at nearby places
of IIT Palakkad, like at the entrance of Nila campus IIT Palakkad, at railways, at
traffic signal etc.. Based on the frequencies of noise observe at different places we
can construct AEH model to get maximum output. <br/>
Observation of absorption, reflection and transmission of sound waves by the
AEH model to get maximum output. This is done using with the help of COMSOL
simulations. By which we can get maximum absorption frequency range.

## Theory:

The idea of converting acoustic energy(sound) to electric energy looks so
simple but actually it is not. It is so simple to convert electrical to sound using
speakers but the other way round is not all and that can be understood by the end if
this report. The main agenda that is converting renewable energy to electric energy is
similar to that of windmills and solar panels. It is rather complex than converting
solar energy or wind energy to electrical energy. <br/>
The two main reasons which are making difficult to convert sound energy to electrical
when compared to solar and wind are:
1) Low energy density
2) Less abundant <br/>
‘Low energy density’ : The energy density of sound is very less compared to
solar and wind energy. Due to which energy extracted from it on gross scale will be
much lower than electrical energy obtained from solar, wind, hydro energy(dams).
The technique used here to overcome the limiting factor of efficiency of AEH (low
energy density) is ‘pressure amplification’ which can be done by Helmholtz
resonator. <br/>
‘Less abundant’ : Though sound energy is available in abundant, but it is not as
abundant as solar and wind. Even though sound energy is abundantly present in
atmosphere due to noise pollution, in industries etc.., most of the sound cannot be
harvested to get electric energy either due to high frequency or low frequency of
sound which is difficult to harvest.

![image](https://github.com/112101011/Acoustic_energy_harvester/assets/111628378/95eb9b78-dbcd-45cf-a74e-b2ddc9147c1c)

### Pressure amplification by ‘Helmholtz Resonator’:  <br/>
Helmholtz resonator consists of an acoustical cavity contained by rigid walls
and connected to the exterior by a small opening called the neck. It is a special type of
air-spring oscillator. The name comes from a device created in the 1850s by [Hermann von Helmholtz](https://en.wikipedia.org/wiki/Hermann_von_Helmholtz), the Helmholtz resonator, which he used to identify the various
frequencies or musical pitches present in music and other complex sounds. The
acoustical cavity could be any shape like sphere, cylinder, cuboid etc.. The size that is
volume of cavity and length, radius of neck defines the frequency at which the
resonator resonates <br/>
3-D model of Helmholtz resonator: <br/>
![image](https://github.com/112101011/Acoustic_energy_harvester/assets/111628378/763e2b03-c153-49a5-ab00-ea60817ecc9a) <br/>
**Condition of Helmholtz resonator**: V <<< 𝜆^3 <br/>
That is resonating volume should be much less than cube of target wavelength. <br/>
If it is a sphere then radius of sphere should be less than wavelength. And similarly so
on… <br/>
The Helmholtz resonator resonates at certain frequencies and one of such
frequencies is fundamental frequency. This frequency is generally referred to as
natural frequency of resonator. Whenever the natural frequency of the Helmholtz
resonator system is equal to the driving frequency that is incident frequency(from
surroundings) acoustic coupling takes place. This acoustic coupling will drive air
molecules back and forth inside neck. The oscillations are maximum at resonant
frequency. <br/>
Incident sound waves causes air molecules in the neck to vibrate back and
forth, while air inside the cavity provides the restoring spring force. Helmholtz
resonator behaves like an acoustical mass-spring system, where <br/>
• Mass of air in neck ~ Mass in spring-mass system. <br/>
• Bulk modulus of air in the cavity ~ spring constant. (provides restoring force) <br/>

**Resemblance of Helmholtz resonator with spring-mass system:** <br/>
![image](https://github.com/112101011/Acoustic_energy_harvester/assets/111628378/88307ce1-1dab-471a-8ea7-374a31bec65c) <br/>
The damping forces are like viscosity of air, very minute cohesive and adhesive forces
between air and wall molecules. <br/>

![image](https://github.com/112101011/Acoustic_energy_harvester/assets/111628378/00b2c763-9ed2-478d-8533-d13262de1d73)


![image](https://github.com/112101011/Acoustic_energy_harvester/assets/111628378/584ea181-3726-4088-910c-c9167e0b9e98) <br/>

[3-d printing](https://youtu.be/bFFjTVrW8AE)

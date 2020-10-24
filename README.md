# UNESP-MAGNOLIA: MAGNetO-eLastIc beAm from UNESP SHM Lab/Ilha Solteira

To download the data set of a magneto-elastic system composed of a clamped beam interacting with a permanent magnet in a mono-stable configuration with hardening behavior:


__________________________________________________________________________________________________
# Description

The current structure consists of a magneto-elastic system composed of a clamped beam interacting with a permanent magnet in mono-stable configurations with hardening behavior. The experimental setup is composed of a cantilever aluminum beam with 300 mm x 19 mm x 3.2 mm. The structure has a small steel mass attached to the free end of the beam and a neodymium magnet with a 2 mm gap to the mass.

A small bolt with four masses (nuts) was placed in the middle of the beam to simulate small structural variations. Each mass has 2 grams.

<img src="setup.jpg " width="60%">

The equipment, sensors, and actuators used for the experimental tests are:

  <li> Modal Shop Shaker 2004E</li>
	  <li> Polytec OFV-525/-5000-S modular laser vibrometer</li>
  <li> Dytran load cell model 1022V (IEPE force sensor)</li>
  <li> Three PCB IEPE Accelerometers</li>
  <li> m+p VibPilot acquisition system</li><br>

The shaker was attached 50 mm distant from the clamp. Velocity was measured through the laser vibrometer in the free end of the beam. Three accelerometers were placed in: the driving point, the position of the bolt and the four masses, and in the free end of the beam.

Each experiment generated a mat file with the variables recorded during the modal tests. Table 1 shows the variables included in each file with the respective description.

<img src="tab1.jpg " width="50%">

Four different input signals were used to characterize the baseline condition of the structure ("healthy" state): chirp, random noise, sine, and stepped sine excitation:

<li> Chirp input from 20 to 50 Hz, with 4096 samples and input levels of: 0.01, 0.09, 0.10, 0.11, 0.12, 0.13, 0.14 and 0.15 V. Each test was repeated 50 times in order to check repeatability</li>
<li>Random noise input band-pass filtered from 10 to 420 Hz, with 4096 samples and input levels of: 0.01, 0.05, 0.10, 0.11, 0.12, 0.13, 0.14 and 0.15 VRMS. Each test was repeated 50 times in order to check repeatability</li>
<li>Sine input with a frequency of 20.5 Hz, with 81920 samples and input levels of: 0.01, 0.09, 0.10, 0.11, 0.12, 0.13, 0.14 and 0.15 V</li>
<li> Stepped sine input from 10 to 40 Hz with steps of 0.5 Hz and total duration of 249856 samples using input levels of: 0.01, 0.05, 0.10, 0.11, 0.12, 0.13, 0.14 and 0.15 V</li><br>

The description of the files of these experiments is presented in Table 2. The character "0pXY" denotes Volts' input level, where "XY" represents the digits after the floating-point.

<img src="tab2.jpg " width="50%">

The masses were gradually removed from a total of 4 masses to simulate a structural variation. Table 3 shows the structural states simulated in the system, while the figure below exhibits a view of the bolt and nuts in the magneto-elastic system.

<img src="damage.jpg " width="40%">

<img src="tab3.jpg " width="50%">

For the damage detection, only two signals were used to excite the nonlinear beam:

<li>Chirp input from 20 to 50 Hz, with 4096 samples and input levels of: 0.01, 0.09, 0.10, 0.11, 0.12, 0.13, 0.14 and 0.15 V. Each test was repeated 50 times in order to check repeatability</li><br>
<li>Random noise input band-pass filtered from 10 to 420 Hz, with 4096 samples and input levels of: 0.01, 0.05, 0.10, 0.11, 0.12, 0.13, 0.14 and 0.15 VRMS. Each test was repeated 50 times in order to check repeatability</li><br>

The description of the files of these experiments is presented in Table 4. The character "0pXY" denotes Volts' input level, where "XY" represents the digits after the floating-point.

<img src="tab4.jpg " width="50%">

__________________________________________________________________________________________________
# Authors

  <li>Sidney Bruce Shiki</li>
  <li>Samuel da Silva</li>

__________________________________________________________________________________________________
# How to cite

The data are still available for non-commercial research under the following terms: (i) the SHM Lab at UNESP/Ilha Solteira should be acknowledged as the source of the data; (ii) in publications, relevant publications by members of the SHM Lab at UNESP/Ilha Solteira should be cited; (iii) this benchmark should be cited as UNESP-MAGNOLIA.

This dataset was used in these papers:

  <li>Shiki, Sidney B.; da Silva, Samuel; TODD, Michael D. On the application of discrete-time Volterra series for the damage detection problem in initially nonlinear systems. Structural Health Monitoring, v. 16, n. 1, p. 62-78, 2017.</li><br>

  <li>Shiki, Sidney Bruce. Application of Volterra series in nonlinear mechanical system identification and in structural health monitoring problems. PhD Thesis in Mechanical Engineering; S\~ao Paulo State University, Ilha Solteira/SP, Brazil, March 2016.</li><br>

If you are using a LaTeX Editor, you can cite the papers above using these BibTeX citations:

```
@article{shiki2017application,
  title={On the application of discrete-time Volterra series for the damage detection problem in initially nonlinear systems},
  author={Shiki, Sidney B and da Silva, Samuel and Todd, Michael D},
  journal={Structural Health Monitoring},
  volume={16},
  number={1},
  pages={62--78},
  year={2017},
  publisher={SAGE Publications Sage UK: London, England}
}

@article{shiki2016application,
  title={Application of Volterra series in nonlinear mechanical system identification and in structural health monitoring problems},
  author={Shiki, Sidney Bruce},
  year={2016},
  publisher={Universidade Estadual Paulista (UNESP)}
}
```
__________________________________________________________________________________________________
# License

<img src="licenca.png" width="10%">
Creative Commons Attribution-NonCommercial-ShareAlike (CC-BY-NC-SA):

A creative commons license that bans commercial use and requires you to release any modified works under this license.

__________________________________________________________________________________________________
# Funding

São Paulo Research Foundation (<a href="http://www.fapesp.br">FAPESP</a>), grant numbers 	12/09135-3,	12/04757-6, 13/25148-0, and 15/03560-2, Brazilian National Council for Scientific and Technological Development (<a href="http://www.cnpq.br/">CNPq</a>), and Brazilian Coordination for the Improvement of Higher Education Personnel (<a href="https://www.gov.br">CAPES</a>)-Finance Code 001 funded this experimental setup.

<img src="sponsors.jpg " width="50%">

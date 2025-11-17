# Tube gel digestion
### Developed in the Saito Lab and adapted for phosphoproteomics by Noelle Held. See also Lu and Zhu Mol Cel Proteomics 2005

### Key concerns: avoid acidic pH and high temperatures, as these can destroy the delicate phosphopeptide bond. Consider also avoiding the use of DTT, which inactivates the phosphatase inhibitor sodium orthovanadate

### Materials
Make everything in LCMS grade H2O, use only LCMS grade reagents
* 1M Tris HCL, pH 7.5
* 40% Bis-acrylmide L 29:1
* 1% Ammonium persulfate (10mg/1mL H2O)
* Ethanol washed 0.5mL and 2mL tubes, one per sample
* TE buffer
* At least 25ug sample protein
* gel fix solution
* gel destain solution
* 50/50 wash
* LCMS grade acetonitrile
* 10mM DTT in ambic 25 (make fresh solution) (1.55mg/mL)
* Ambic 25
* 55mM Ioda in ambic 25 (9.3mg/mL)
* 500mM solutions of sodium pyrophosate, sodium fluoride, and activated sodium orthovanadate in LCMS grade water
* TEMED (full concentration)
* 1% ammonium persulfate
* bis-acryl L


### Preparation
* Prepare premix on ice: 1 part Tris HCL, 3 parts 40% Bis-acryl L (typically 252uL Tris HCL, 736.5uL Bis-acryl L)
* Prepare fresh DTT solution, if using
* Fill out the following table:

| Sample | Sample concentration | Amt sample to be digested | Volume sample to be digested | Premix | Sodium pyrophosphate | Sodium fluoride | Sodium orthovanadate | 1% APS | TEMED | TE buffer | Final volume |
|--------|----------------------|---------------------------|------------------------------|--------|----------------------|-----------------|----------------------|--------|-------|-----------|--------------|
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
|        |                      |                           |                              | 103uL  | 2uL                  | 2uL             | 2uL                  | 7uL    | 3uL   |           | 200uL        |
### Protocol
* Place sample in clean 0.5mL tube, then add phosphatase inhibitors and TE buffer in volume recorded above (such that final volume is 200uL)
* Add the Premix
* Add TEMED and APS, vortex speed 3 and and mix by pipetting. Work quickly.
* Allow to polymerize in thermomixer 1hr at 20C. START:
* Add 200uL gel fix solution to gels, incubate RT 20min
* Remove liquid, transfer gels to 2mL tubes
* fix in 1200-1600uL gel fix solution (enough to cover) at RT 350RPM for 1 hr. START:
* Remove liquid, add 1600uL destain solution an dincubate 2hrs RT 350RPM. START:
* Remove liquid, decant gels onto a clean surface and cut into 1mm cubes with a clean scalpel or razor blade, return to tube
* Add 1mL 50:50 wash, shake 350RPM for 1hr
<u> Note: This is a good place to break, gels can remain in incubator over night if needed </u>
* Remove solution, repeat above step
* Dehydrate gels by adding 0.8mL acetonitrile, leave RT 10min and remove. Repeat 2x
* Add 600uL DTT solution, mix 1hr 56C 350RPM
* Remove liquid, note how much was absorbed by the gels (hydrated gel volume)
* Add 600uL Ambick vortex, and remove (rinse step)
* Add 600uL Ioda solution, incubate 1hr RT 350RPM
* Remove Ioda, add 1mL ambic, vortex, incubate 10min RT 350RPM and remove solution
* Dehydrate with 1mL ACN, 10min room temperature and remove solution, repeat 2x
* Meanwhile, resuspend 100ug trypsin in 1000uL ambic on ice, allow to sit at least 30 mins to dissolve fully
* The desired trypsin:protein ratio in the digestion solution is 1:20. Calculate the desired concentration of trypsin to reach this amount below:


| Sample | ug protein used in digestion | ug Trypsin to equal 1:20 ratio | Volume of hydrated pellets (record from DTT addition) | Desired concentration of trypsin (=ug trypsin desired/volume of hydrated pellets) | Starting concentration of trypsin (typically 0.1ug/uL) | Volume starting trypsin solution (= desired conc * volume / starting conc) | Volume ambic to acheive desired concentration (= starting volume - volume starting trypsin solution) |
|--------|------------------------------|--------------------------------|-------------------------------------------------------|-----------------------------------------------------------------------------------|--------------------------------------------------------|----------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |
|        |                              |                                |                                                       |                                                                                   |                                                        |                                                                            |                                                                                                      |

* Add the desired volume of trypsin to each sample (see table above), incubate 37C for 20mins
* Add minimal amount of ambic to ensure rehydrated gels are covered with liquid
* Vortex, briefly spin down and incubate 37C 350RPM overnight. START:
* END of digestion period:
* Spin down, collect liquid supernatant into clean 1.5mL tubes
* Add 50uL peptide extraction buffer, incubate 20mins RT
* Spin down and collect suspension
* Repeat extraction step, combining the suspensions
* Spin the samples 20mins at high speed to remove any remainign debris
* Collect the top 90% off the centrifuged samples and concentrate on speed vac on low (as needed). Note the volumes and calculate the final estimated concentration of protein:

| Sample | ug protein digested | Volume of sample after concentrating | Final concentration |
|--------|---------------------|:-------------------------------------:|---------------------|
|        |                     |                                       |                     |
|        |                     |                                       |                     |
|        |                     |                                       |                     |
|        |                     |                                       |                     |
|        |                     |                                       |                     |
|        |                     |                                       |                     |

* These samples are now ready for fractionation and/or LC-MS/MS analysis
* For phosphoproteomics, particularly for histidine phosphorylations, be sure to acidify <b> gently </b>, i.e. do not allow to go below pH 5.5, the pKa of the histidine phosphorylation.

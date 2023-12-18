
# Time-frequency diffraction acoustic modeling of the Epidaurus ancient theatre

Official repository of the paper:
[Kaleris, K., Moiragias, G., Hatziantoniou, P., & Mourjopoulos, J. (2023). Time-frequency diffraction acoustic modeling of the Epidaurus ancient theatre. Acta Acustica, 7, 67.](https://acta-acustica.edpsciences.org/articles/aacus/full_html/2023/01/aacus230052/aacus230052.html)





## Abstract
This work provides an in-depth investigation on the effect of sound diffraction in the acoustics of the ancient theatres, with reference to the theatre of Epidaurus. It is increasingly evident that in such theaters, sound diffraction at the edges of the multiple tiers generates significant source signal amplification. Especially for the distant listener positions, an accumulation (“avalanche”) effect from lower tier diffracted energy is identified. This study examines a 3D model of an elementary slice of the seating benches (“koilon”), evaluating the generated sound field in the time, frequency, and spatial domains. The analysis accounts for direct, reflected, diffracted and mixed reflected – diffracted paths and the theatre’s acoustic response is numerically evaluated in various positions along the koilon slice, accurately matching to in-situ measurements. The contribution of the diffracted sound to the total sound field is identified through a detailed and novel analysis of energy-based acoustic parameters, via the time and frequency responses as well as of the spatial parameters
20 relating to listener-perceived effects. In all cases, the contribution of sound diffraction components is examined via its contribution to speech intelligibility from signals generated in the theatre’s orchestra and from a virtual reconstruction of the stage-scenic building.

![Slice of koilon of the ancient theatre of Epidaurus](https://github.com/YorgosMoiragias/epidaurus_simulations/blob/main/Images/Theatre.png)
## Data
Folder __Measurement and Processed Simulation__:
 - __Measurement_R7.wav__: Impulse response measurement at position R7 [1].
 - __proc_Simulation_R7.wav__: Processed simulated impulse response at position R7, that matches the respective measured IR.
 
Folder __Simulations__:
 - __wav_files__: Simulated unprocessed impulse responses at positions R1, R4, R7 and R10.
 - __mat_files__: Contains the distinct components of each of the above impulse responses:
    - signal_D: Direct signal
    - reflections: First order reflections
    - reflections2: Second order reflections
    - Signal_Front_Diff: Ascending diffractions
    - Signal_Back_Diff: Descending diffractions
    - Signal_Front_ReflDiff: Ascending reflections-diffractions
    - Signal_Back_ReflDiff: Descending reflections-diffractions

All the diffracted components of the soundfield were computed according to [2].


[1]: [Psarras, S., Hatziantoniou, P., Kountouras, M., Tatlas, N. A., Mourjopoulos, J. N., & Skarlatos, D. (2013). Measurements and analysis of the Epidaurus Ancient Theatre acoustics. Acta Acustica United with Acustica, 99(1), 30-39](https://www.ingentaconnect.com/content/dav/aaua/2013/00000099/00000001/art00006).

[2]: [Menounou, P., & Nikolaou, P. (2017). Analytical model for predicting edge diffraction in the time domain. The Journal of the Acoustical Society of America, 142(6), 3580-3592.](https://pubs.aip.org/asa/jasa/article/142/6/3580/694907/Analytical-model-for-predicting-edge-diffraction).
## Remarks
The audio files of __Measurement and Processed Simulation__ folder have a sampling frequency of 44100 Hz, while  the audio files of __Simulations__ folder have a sampling frequency of 96000 Hz for a finer time resolution of the diffraction effects.

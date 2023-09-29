# BinaryStarAnalysis

## Introduction

In order to have a grasp on and understanding of the “chemical and dynamical evolution of galaxies,” it is critically
important to study massive stars, particularly O-type stars [5]. Characteristics of these stars that are worthy of note
include their short life spans, their behavior within their surroundings such as the launching of strong stellar winds,
their emission of UV radiation, and climactic deaths (i.e. supernovae) [5]. Furthermore, a significant fraction of these
massive stars reside in multiple star systems, and binary systems especially so [5]. In fact, in general, most stars are
paired in binary systems. The field of stellar evolution also has major holes left to be filled, and studying binary
systems can be most fruitful because not only do these stars evolve together, but, with the present information of
the system and a large sample size to compare with, we can trace the history behind these systems. Stellar lifetimes
are much too long to be studied over the course of a human life. A single, dim star might not be terribly difficult to
detect, but attempting to calculate its mass is an immensely laborious task with the equipment we have available,
but it is more than doable otherwise. Instead, if we are able to detect similar stars in binary systems, we can infer
their mass from the interaction they have with their stellar partner, or at least the constraints on the mass of the
secondary. Along the same line, there are other abnormal stars such as white dwarfs and neutron stars that are far
too dim for normal detection in isolation, which can be readily found in binary systems and studied closely.
An application of binary-star-system investigation can be found in the work of Pablo et al. [4]. The high
luminosities of massive stars and their “mass-loss rates make them important to the ecology of the Universe” [4]. If
we wish to understand the processes behind these things, it is necessary to determine the intrinsic stellar parameters
of the most massive stars through their observation [4]. However, we either need reliable distance estimates to these
stars, or a detached, non-interacting binary star system [4]. It is helpful to examine O stars in such binaries because
the fraction of O stars in binary systems in general is approximately unity at their birth, although the fraction
“degrades” during their evolution [4]. That is, mergers and dynamical interactions take place [4]. It was discovered
from several studies that “at least half of the massive stars are found in multiple systems” [7]. Furthermore, if massive
stars are in close binary systems they may experience “significant tidal forces, mass-transfer, additional supernova
kicks, and mutual irradiation effects,” which means that it is critical to examine such systems given the large fraction
of massive stars being in multiple-star systems [7]. Much can be learned from taking our physical models to their
limits.

## Target Selection

Pablo et al. find that δ Orionis is an “excellent choice” of a system to investigate O-star evolution given that
it contains the detached binary Aa and there is minimal mass-loss [4]. Shenar et al. provide a similar line of
reasoning to investigate this massive-star system, highlighting the present-day issues surrounding studies of massive
stars, which they denote as those with masses Á 10 M@ [7]. Shenar et al. mention the clear advantages of studying
binaries, and, in particular, eclipsing binaries such as δ Orionis because we can “empirically determine stellar masses”
and ”investigate different characteristics of stellar winds by taking advantage of occultation” [7]. Despite the latter
advantage not being one of the reasons we are investigating δ Orionis, it is nonetheless clear that if we even so much
as determine basic parameters such as mass constraint, radial velocity, and spectral line shifts we can provide a
starting point for further, more complex astronomy that can be done by experts. Or, instead, our work may help to
confirm the most recent observations of the system, such as that of Oplistilov ́a et al., who published a paper at the
end of January 2023 [3]. “δ Orionis is the closest massive multiple stellar system” to us “and one of the brightest
members of the Orion OB association” [3].

Our target of interest was a binary that has a right ascension of 05h33m11.3s and a declination of -00017’02.0”,
with its primary component (Aa1) being an O9.5 II star, and the secondary (Aa2), a B2V star [3]. Their masses
are 17.8 M@ and 8.5 M@, respectively, with uncertainties of 1 M@ [3]. Their radii are 13.1 R@ and 4.1 R@ [3]. The
orbit is nearly circular with an eccentricity of 0.08, its orbital period is P “ 5.732436 d, and each star has apparent
magnitudes of VAa1 “ 2.55 mag and VAa2 “ 5.5 mag, respectively [3]. This means that the primary star is much
more luminous than that of the secondary, causing the system to be a single-line spectroscopic binary instead of a
double-line spectroscopic binary. The primary is “one of the nearest of the luminous O-type stars” [6]. As an O
star, the primary will have strong He II absorption lines and He I absorption lines [1]. The binary is actually in a
triple system which has a collective visual magnitude of VAa1+Aa2+Ab “ 2.223 mag [3]. The period of the three-body
system is approximately 152 yr, and the tertiary has a mass of 8.7 M@, a radius of 12.0 R@, a visual magnitude of
3.7 mag, and is a B0 V star [3]. The measured inclination of the binary according to Oplistilov ́a et al. and their
three-body model of the system is 79.124  ̆ 1 ̋, whereas the inclination of the binary-tertiary system is 105.710  ̆ 1 ̋
[3]. From this same model, they acquired temperatures of 31385  ̆ 1000 K for Aa1, 24515  ̆ 1000 K for Aa2, and
27906  ̆ 1000 K for Ab, all found in Table 11 of the paper [3]. If we take the combined magnitude, and use the
extinction given in Table 3 of Oplistilov ́a et al, and apply the distance modulus, we acquire a distance to the triple
system of 380.2 pc [3]. The Gaia DR3 measurements of the parallax of the other binary in the system give a distance
of 381  ̆ 8 pc [3]. The three-body model gives a distance of 382 pc (no uncertainty given) [3]. This other binary,
denoted as Ca+Cb, is spectroscopic, but not eclipsing, and has a combined magnitude VCa+Cb “ 6.85 mag, and an
orbital period of 29.96 d [3]. Both stars are B3 V and A0 V stars, respectively [3].
For each night of observation, only one hour was needed per epoch. This was due to the fact that Mintaka is
of magnitude 2.2. Therefore, ten exposures of 300 seconds were adequate and attained a signal-to-noise ratio of
approximately 219. This signal-to-noise allowed us to get extremely well defined absorption features that could then
be used to calculate the radial velocities. In addition, each night we took ten 10 second flats, twenty 15-second
calibration images, ten 0-second biases, and three 350-second darks. In order to maximize the quality of data, all
observations were made while the Mintaka was crossing the meridian to minimize the air mass. By minimizing the
air mass, we are decreasing the possibility of the Earth’s atmosphere from altering our data. This, in turn, may
cause shifts in some of our main absorption lines, creating a bias in our data.

## Data Processing

In order to reduce the raw spectra into a more manageable form, a spectroscopy software called Demetra was
utilized. This software takes observational data, along with the proper calibration images from that night to obtain
a spectrum ready for data analysis. Figure 2 is an example raw spectrum of our system.

Demetra begins by taking all of the flats, biases, and darks and creating master version of those to reduce the
original spectrum. This is done by subtracting the biases and darks and then dividing by the flats. From there, each
of the spectra are aligned and stacked to get a final full spectrum which is then calibrated with with the Thorium-
Argon lamp calibration images taken from the same night as the object images. The spectrum is then sliced into
each of the orders and the flux is plotted over the wavelengths. Both absorption and emission lines can then be easily
seen in the spectrum and data analysis can be performed.

Data reduction was one of the most time consuming tasks of the entire project. We has to handle multiple errors
outputted from Demetra, including poorly identifying orders, failing to properly calibrate images, and not noticing
emissions in the calibrated images. To be more specific, each reduction of data required manually applying order 34
to the correct line. This was done by going into the reference order tab on the Demetra software and moving the line
to Order 34, which is easily identifiable by three bright emissions in a row. In addition to not correctly identifying
Order 34, some of the orders would stray away from their actual shapes. Either the order would rise up, down, or,
in some cases, completely cross into a different order. In order to resolve this issue, the back-rate was increased.

Another common error with the Demetra software came from recognizing emissions with the calibration images.
For instance, Demetra would not be able to determine the wavelengths of some of the Thorium-Argon lines, pro-
hibiting the proper wavelength identification within the raw spectra. Again, this could be fixed by increasing the
back-rate within the calibration portion of the Demetra software.

## Data Analysis

In order to perform the proper data analysis on the spectra obtained from the six nights of successful observations,
coding through the language of Python, along with various packages such as MatPlotLib, Astropy, and Specutils
was used. Using the Spectrum1D function from Specutils, the fits files exported from Demetra were converted into
useful arrays containing the flux and wavelengths for each of the order for all nights. The original goal for the data
analysis of the spectra were to convert them into log space using a flux conservation function also from Specutils.
With this new log space version of the spectra, a correlation function, again from Specutils, can be applied to our
”template” spectrum which was from the date of February 23rd, 2023. Each of the remaining dates of observations
(February 28th, March 12th, March 13th, March 21st, and April 4th) were then compared to the template spectrum
to calculate the shift in each of the lines. By using the correlation function and the spectra being in log space, no
specific features needed to be identified. Rather, the peak (or trough) of the correlation function represented the
shift in the spectrum. Each corresponding order would be compared to the template spectrum and averaged for the
average radial velocity of the star for that specific night.

However, after converting all of the spectra to log space, the correlation function continuously obtained a value
of zero, resulting in a shift and radial of velocity of 0. However, this was obviously wrong since a shift between each
observation date was noticeable by inspection. Therefore, a more rudimentary technique was used to calculate the
radial velocities using the known features of Helium I at 6678  ̊A and Hydrogen Balmer Alpha at 6563  ̊A. Instead
of using the correlation function in conjunction with the log space spectra, Gaussian curves were fit to the original
spectra. Furthermore, the center of these Gaussians were then found and represented the center wavelength for the
absorption features. 

## References

[1] Carroll, B. W., & Ostlie, D. A. (2017). An Introduction to Modern Astrophysics (2nd ed.). Cambridge University
Press.

[2] Harvin, J.A. et al. (2002) “Tomographic Separation of Composite Spectra. VIII. The Physical Properties of the
Massive Compact Binary in the Triple Star System HD 36486 (δ Orionis A),” The Astrophysical Journal, 565(2),
pp. 1216–1230. Available at: https://doi.org/10.1086/324705.

[3] Opliˇstilov ́a, A. et al. (2023) “Spectrum of the Secondary Component and New Orbital Elements of the Massive
Triple Star δ Ori A,” Astronomy & Astrophysics, 672. Available at: https://doi.org/10.1051/0004-6361/
202245272.

[4] Pablo, H. et al. (2015) “A Coordinated X-ray and Optical Campaign of the Nearest massive Eclipsing Binary,
δ Orionis Aa. III. Analysis of Optical Photometric (most) and Spectroscopic (Ground-Based) Variations,” The
Astrophysical Journal, 809(2), p. 134. Available at: https://doi.org/10.1088/0004-637x/809/2/134.

[5] P ́aez, E.T. (2021) “MONOS: Multiplicity Of Northern O-type Spectroscopic Systems. II. Orbit review and analysis
for 35 single-lined spectroscopic binary systems and candidates,” Astronomy & Astrophysics, 655. Available at:
https://doi.org/https://doi.org/10.48550/arXiv.2106.08865.

[6] Richardson, N.D. et al. (2015) “HST/STIS Ultraviolet Spectroscopy of the Components of the Massive Triple
Star δ Ori A,” The Astrophysical Journal, 808(1), p. 88. Available at: https://doi.org/10.1088/0004-637x/
808/1/88.
[7] Shenar, T. et al. (2015) “A Coordinated X-ray and Optical Campaign of the Nearest Massive Eclipsing Binary,
δ Orionis Aa. IV. A Multiwavelength, NON-LTE Spectroscopic Analysis,” The Astrophysical Journal, 809(2), p.
135. Available at: https://doi.org/10.1088/0004-637x/809/2/135.

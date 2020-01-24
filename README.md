# Estudio del modo plasmónico colectivo en sistemas monocapa desordenados formados por nanopartículas esféricas y su análisis para biosensado
#### by Jonathan Alexis Urrutia Anguiano
#### Directed by Dr. Alejandro Reyes Coronado (http://sistemas.fciencias.unam.mx/~coronado/)
Bachelor thesis for obtaining the title of Physisist.
Dissertation at the National Autonomous University of Mexico

#### Abstract:
Commercial plasmonic biosensors use traditionally surface plasmon-polaritons excited on a continuous gold film. Periodic and disordered nanostructured arrays have been recently proposed for biosensing by employing plasmonic surface lattice resonances and localized surface plasmon resonances. However their production is generally expensive and time consuming due to their fabrication techniques such as hole-mask colloidal lithography or sputtering deposition followed by pore formation. As an alternative, in this bachelor thesis it is studied the possibility to use disordered monolayers of gold and silver spherical nanoparticles as a biosensor, by analyzing theoretically their reflectance and transmittance by means of the coherent scattering model. This model predicts a collective-like plasmonic mode, excited in an internal reflectance configuration and for both polarizations, which can be tuned by choosing the radius ($a$) of the nanoparticles in the monolayer and its cover fraction $\Theta$. The obtained results show that a monolayer of gold nanoparticles with $ a = 30 $ nm and $ \Theta = 0.125 $  could be used for biosensing, as well as a monolayer of silver nanoparticles with $a=40$ nm and $\Theta=0.1$. The performed comparison for the bulk sensitivity between the collective-like plasmonic mode and both the plasmonic surface lattice resonances and the localized surface plasmon resonance shows it is similar for angles of incidence close to the critical angle. In addition, the sensitivity of the collective-like plasmonic mode and the surface plasmon-polariton were compared, showing that under particular conditions the sensitivity of a monolayer formed by gold nanoparticles is comparable to that of a thin gold film; this result is also observed when silver is used.

<p align="center">
![bar](LaTeX-files/2-Resultados/figs/0-nmBar_h.png?raw=true style=center "bar")
![Reflectance](LaTeX-files/2-Resultados/figs/11-SPPCSM/2-RpRs.png?raw=true "Reflectance")
</p>

## Thesis template information:
=============
Modification, of a modification from a LaTeX template (not longer aviable in Overleaf) aimed for the a UNAM's College of Engineering Thesis.

Based on Harish Bhanderi's PhD/MPhil template, then Uni Cambridge (http://www-h.eng.cam.ac.uk/help/tpl/textprocessing/ThesisStyle/).
Corrected and extended in 2007 by Jakob Suckale, then MPI-iCBG PhD programme
and made available through OpenWetWare.org - the free biology wiki. Adapted to FI-UNAM by Jesús Velázquez & Marco Ruiz. Adapted to FC-UNAM by Jonathan Urrutia.

What to modify if you want to use this template
-----------------

All packages, as well as the file properties can be found in

    Latex/Classes/PhDthesisPSnPDF.cls

there, all the packages info is comments. Additional to the FI-UNAM template, the bibtex package can be used, as well as the imakeidx package. Also the footnote space is now well integrated to the text pages and the margin of the text were diminished.

Compilación
-----------

"PDFLaTeX"

Grad school (UNAM) options
--------
Uncomment or write in the tesis.tex file

    \posgradotrue

The programm and field commands are now usable

    \programa{Programa de Maestría y Doctorado en Ingeniería}
    \campo{Ingeniería Eléctrica - Control}

The tutor comitee can be defeined

    \comitetrue
    \ctutoruno{Nombre 1}
    \ctutoruno{Nombre 2}

As well as the jury

    \presidente{Nombre}
    \secretario{Nombre}
    \vocal{Nombre}
    \supuno{Suplente 1}
    \supdos{Suplente 2}
    \institucion{el lugar donde se hizo la tesis}


Warnings
--------
If used in spanish, the  \blindtext will show errors since it is aimed for inglish-based texts. After removal the blind text-related issued should disappear.
The outside of the margin-warnings are due the cover.

Thesis template:
=============
Modification, of a modification from a LaTeX template (not longer aviable in Overleaf) aimed for the a UNAM's College of Engineering Thesis.

Based on Harish Bhanderi's PhD/MPhil template, then Uni Cambridge (http://www-h.eng.cam.ac.uk/help/tpl/textprocessing/ThesisStyle/).
Corrected and extended in 2007 by Jakob Suckale, then MPI-iCBG PhD programme
and made available through OpenWetWare.org - the free biology wiki
. Adapted to FI-UNAM by Jesús Velázquez & Marco Ruiz.
. Adapted to FC-UNAM by Jonathan Urrutia


What to modify if you want to use this template
-----------------

All packages, as well as the file properties can be found in

    Latex/Classes/PhDthesisPSnPDF.cls

there, all the packages info is commentes. Additional to the FI-UNAM template, the bibtex package can be used, as well as the imakeidx package. Also the footnote space is now well integrated to the text pages and the margin of the text were diminished.

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
If used in spanish, the  \blindtext will show errors sinces it is aimed for inglish-based texts. After removal the blind text-related issued should disappear.

The outside of the margin-warnings are due the cover.

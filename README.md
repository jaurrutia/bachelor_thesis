# Tesis de licenciatura
## Respuesta electromagnética de sistema bidimensionales desordenados de nanopartículas plasmónicas y su uso en el biosensado

Information about the template is found at the end of the README.md file.

### Cosas por hacer
- [x] Revisar el índice analítico
  - [ ] Completar el índice analítico
- [ ] Considerar hacer un índice de abreviaciones
- [x] Gráficas del ajuste de Drude de Johnson & Christy
  - [x] Poner la gráfica correcta
- [x] Gráficas de la corrección por tamaño para NPs esféricas
- [x] Explicación de los plasmones
- [ ] Explicación de las extinción de luz y su relación con los plasmones
  - [ ] Diagramas de extinción para a = 30 nm con \omega_p= 4.3 eV, 10 eV y oro y plata
- [x] CSM
- [ ] Hacer el límite de partícula pequeña de las SPRs con Drude, que no me sale... :(
- [x] Introducir el sustrato en el CSM
- [x] Integrar cálculos con Drude
- [x] Realizar cálculos con la corrección de tamaño
- [x] Rehacer las figuras de los cálculos con Drude para que queden bien en el documento
- [x] Considerar calcular T de una vez
- [x] Hacer los cálculos con la corrección por tamaño de J&C
- [ ] Hacer análisis de los diagramas de esparcimiento de una sola nanopartículas
- [x] Introducir información de la distancia promedio entre nanopartículas
- [ ] Jugar con BEM (URGE)
- [ ] Programar 3 medios y calcular la sensibilidad de un sersor comercial
- [ ] Calcular la función de mérito para la monocapa con oro y plata

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

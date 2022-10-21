# kepr_plot

Visualize KEPR (kinetic electron paramagnetic resonance) data with PGFPlots & TikZ.

## Compilation

Compile the document ``main.tex`` with XeLaTeX using MikTeX. When displaying scatter data it may be necessary to 
expand the main memory size with the additional compiler argument ``--extra-mem-top=100000000``.

## Experimental Data

This work contains example KEPR data acquired during a practical in the directory ``data``. The files also include the 
corresponding fits and residuals. For complementary stationary EPR spectra check out the repository 
[``esr_plot``](https://github.com/Rastow/esr_plot).

- ``esr_daten-6_kepr.txt``: _tert_-Butylperoxyl radical generated through UV-irradiation of 10uL 
2,2,4,4-tetramethyl-3-pentanone (5.79M) in 90uL _tert_-butylbenzene.
- ``esr_daten-7_kepr.txt``: Stannyloxy nitroxide generated through two reaction pathways:
  - Pathway 1: 7uL 0.921M 2-methyl-2-nitropropane solution (12.9mM) and 63uL bis(tributyltin) (0.249M) in 430uL 
_tert_-butylbenzene.
  - Pathway 2: 7uL 0.921M 2-methyl-2-nitropropane (12.9mM), 33uL tributyltinhydride (0.247M) and 10 uL 
di-_tert_-butylperoxide (0.109M) in 450uL _tert_-butylbenzene.

## Further Reading

- Lucarini, M.; Pedulli, G. F.; Alberti, A.; Benaglia, M. Kinetic EPR studies of the decay of
tert-butyl alkoxy, silyloxy, germyloxy, and stannyloxy nitroxides. _Journal of the American
Chemical Society_ **1992**, _114_, 9603–9607, DOI: [10.1021/ja00050a046](https://doi.org/10.1021/ja00050a046).

## License

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License. This work has 
the LPPL maintenance status `maintained'.
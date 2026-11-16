# Median search: dichotomy and gradient descent
Elie Youndje
2026-11-05

### Citation

Submitted to Computo.

### Badges

[![build and
publish](https://github.com/e-youndje/repo-mediane/actions/workflows/build.yml/badge.svg)](https://github.com/e-youndje/repo-mediane/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/e-youndje/repo-mediane/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/e-youndje/repo-mediane)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/e-youndje/repo-mediane)
[![DOI:10.5072/computo.0000](https://img.shields.io/badge/DOI-10.5072%2Fcomputo.0000-034E79.svg)](https://doi.org/10.5072/computo.0000)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Elie Youndje](https://lmrs.univ-rouen.fr/fr/persopage/elie-youndje) (Univ Rouen Normandie, CNRS, Normandie Univ, LMRS UMR 6085)

### Abstract

This paper shows how to compute the median of a sample by minimizing the
sum of absolute deviations function. The minimization is done using the
left hand gradient of the sum of absolute deviations. The point where
the left hand derivative changes sign is searched using dichotomy or
gradient descent. Simulations conducted in the article reveal that these
approaches are very promising. In particular, for each sample size
considered, there is one among our methods that outperforms the matlab
build-in function in terms of runtime.

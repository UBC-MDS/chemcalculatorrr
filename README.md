
<!-- README.md is generated from README.Rmd. Please edit that file -->

# chemcalculatorrr

<!-- badges: start -->
<!-- badges: end -->

The goal of chemcalculatorrr is R package useful for chemistry for purpose of calculating chemical formular mass in g/mol. The pacakage is designed to perform the same function as the [python pacakge](https://github.com/UBC-MDS/chemcalculator). The mole allows scientists to calculate the number of elementary entities (usually atoms or molecules) in a certain mass of a given substance. Another property of Avogadro’s number is that the mass of one mole of a substance is equal to that substance’s molecular weight. For example, the mean molecular weight of water is 18.015 atomic mass units (amu), so one mole of water weighs 18.015 grams. This property simplifies many chemical computations. This R package will be helpful to easily calculate the chemical formula mass, convert moles to grams and vice versa, and lastly calculate the percentage mass for the atomic nature of the elements in chemistry.

This package of basic chemistry calculations is meant to supplement an existing package, [ChemPy](https://github.com/bjodah/chempy), which already handles complex calculations for primarily physical/inorganic/analytical chemistry consisting of, but not limited to, the following:

- Solver for equilibria (including multiphase systems)
- Numerical integration routines for chemical kinetics (ODE solver front-end)
- Integrated rate expressions (and convenience fitting routines)
- Relations in Physical chemistry
- Debye-Hückel expressions
- Arrhenius equation
- Einstein-Smoluchowski equation
- Properties, such as : water density as function of temperature, water permittivity as function of temperature and pressure, and water diffusivity as function of temperature

## Features

This package contains three functions. Each function will have it's own required and optional arguments.

1. `compute_mass`: Calculate the mass of the atoms or chemical formula for the input chemical formula.
2. `moles_grams_converter`: Convert moles to grams and convert grams to moles.
3. `percent_mass`: Calculate percentage mass for the desired atom or molecule.

## Installation

You can install the released version of chemcalculatorrr from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("chemcalculatorrr")
```

## Relevance to the R Ecosystem

To our knowledge, while `chemcalculatorrr` library generates wordcloud visualization for a given corpus, there is no general-purpose library for calculating chemical formula mass in g/mol in the R ecosystem. We believe that `chemcalculatorrr` will provide some useful functionality to know how to calculate moles, and provide a grams to moles calculator, or even a moles to grams calculator. With our moles to grams converter, you can seamlessly convert between mass, molecular weight and moles.

## Usage

- TODO

``` r
library(chemcalculatorrr)
## basic example code
```

## Documentation

The help file can be viewed by:

``` r
?compute_mass
?moles_grams_converter
?percent_mass
```

## Contributors
### Development Lead

|Contributor Name     | GitHub Username|
|---------------------|-----------|
|Kingslin Lv | [Kingslin0810](https://github.com/Kingslin0810)|
|Joyce Wang      | [jo4356](https://github.com/jo4356)     |
|Allyson Stoll       | [datallurgy](https://github.com/datallurgy) |

We welcome and recognize all contributions. Please find the guide for contribution in [Contributing Document](https://github.com/UBC-MDS/chemcalculatorrr/blob/main/.github/CONTRIBUTING.md).



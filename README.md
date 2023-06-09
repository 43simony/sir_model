## sir_model for CIDD workshop
## Repository Title

### About This Project

This is a test SIR model based on Ottars book code from ch. 2.

```math
\begin{align}
\frac{dS}{dt} &= \mu (N - S) -\beta S \frac{I}{N} \\
\frac{dI}{dt} &= \beta S \frac{I}{N} - \gamma I - \mu I \\
\frac{dR}{dt} &= \gamma I - \mu R
\end{align}
```

```math
\begin{align}
\mu &= \frac{1}{50*52} \\
\beta &= 2 \\
\gamma &= \frac{1}{2} \\\\

N &= 1000 \\
S_0 &= 999.0 \\
I_0 &= 1.0 \\
R_0 &= 0.0
\end{align}
```

### Repository Structure
```
.
├── data/
├── figs/
├── funs/
├── out/
└── src/
```

- `data/` contains ...
- `figs/` contains ...
- `funs/` contains ...
- `out/` contains ...
- `src/` contains ...

### Built With

- [`{deSolve}`](https://cran.r-project.org/web/packages/deSolve/index.html) for solving differential equations

### Getting Started
- [R version 4.2.1 (2022-06-23)](https://cran.r-project.org/bin/macosx/)
- [`{renv}`](https://rstudio.github.io/renv/articles/renv.html) for package management
### Usage
Uses fractional populations
### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

### Contact

bbs5582@psu.edu

### Acknowledgements

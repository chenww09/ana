[Download PDF file](https://github.com/mazurov/ana/blob/master/main.pdf?raw=true)

## Analysis note

### Changes

**19 Jul 2011**
Initial commit. 

* (7) Determination of selection efficiencies
    * Monte Carlo efficiency plot
* (8) Determination of selection efficiencies
    * Fraction plots

* (Appendix A) Fitting parameters summary
    1. Data fits plots
    1. Summary table
    1. Monte carlo fits to determine yild widths

### How to build and send a patch

```sh
lxplus$> git clone https://github.com/mazurov/ana.git
lxplus$> cd ana
lxplus$> git checkout -b mybranch
lxplus$> ... edit ...
lxplus$> make

lxplus$> git commit -am "My changes"
lxplus$> git format-patch master --stdout *.tex > my_patch.patch
```

Send my_patch.patch
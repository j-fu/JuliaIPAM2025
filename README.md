# JuliaIPAM2025

Material for thbe  Julia intro during the [IPAM Long Program
"Bridging the Gap: Transitioning from Deterministic to Stochastic Interaction Modeling in Electrochemistry"](https://www.ipam.ucla.edu/programs/long-programs/bridging-the-gap-transitioning-from-deterministic-to-stochastic-interaction-modeling-in-electrochemistry/).

## Installation

Material is provided in the [Julia](https://julialang.org) scientific computing language in form of [Pluto](https://plutojl.org) computational notebooks.

### [Julia installation instructions](https://julialang.org/downloads)
  - Linux/Mac: go to your command prompt and issue
```
$ curl -fsSL https://install.julialang.org | sh
```

  - Windows: go to your command prompt and issue
```
> winget install julia -s msstore
```
  - These provide the [`julia` command  line application](https://docs.julialang.org/en/v1/manual/command-line-interface/) and the [`juliaup` installation manager](https://github.com/JuliaLang/juliaup?tab=readme-ov-file#using-juliaup) wich allows to update Julia versions and to choose between them. 
  - One can change the default version of Julia running to the long term service release (lts; currently 1.10) via
```
$ juliaup add lts
$ juliaup default lts
```
  
  
### [Pluto installation instructions](https://plutojl.org/#install)
- In a command window, go to the directory where you downloaded the notebooks
- Start Julia using the `julia` command
- At the Julia prompt issue
```
julia> using Pkg
julia> Pkg.add("Pluto")
julia> Pluto.run()
```
This will open a browser window with a view on the current directory, click at one of the notebooks and start it.
At the first start of a notebook, all Julia packages used in by the notebook will be downloaded and precompiled. This may take
a while.


## Notebooks
In order to download them, you can clone this repository, or download then here. Pluto notebooks contain package manifests which are specific for the different Julia minor versions. As Julia 1.10 (the current long term service release) has a lower package loading time, they are provided here for both Julia 1.10 and 1.12.

- Julia Overview ([pluto + 1.12](https://raw.githubusercontent.com/j-fu/VoronoiFVOT/refs/heads/main/JuliaOverview-jl1.12.jl)|[html](https://www.wias-berlin.de/people/fuhrmann/blobs/JuliaOverview-jl1.12.html)|[pluto + 1.10](https://www.wias-berlin.de/people/fuhrmann/blobs/JuliaOverview-jl1.10.jl))
- Intro to VoronoiFVM.jl  ([pluto + 1.12](https://raw.githubusercontent.com/j-fu/VoronoiFVOT/refs/heads/main/VoronoiFVMIntro-jl1.12.jl)|[html](https://www.wias-berlin.de/people/fuhrmann/blobs/VoronoiFVMIntro-jl1.12.html)|[pluto + 1.10](https://www.wias-berlin.de/people/fuhrmann/blobs/VoronoiFVMIntro-jl1.10.jl))
- Template notebook  ([pluto + 1.12](https://raw.githubusercontent.com/j-fu/VoronoiFVOT/refs/heads/main/VoronoiFVMTemplate-jl1.12.jl)|[html](https://www.wias-berlin.de/people/fuhrmann/blobs/VoronoiFVMTemplate-jl1.12.html)|[pluto + 1.10](https://www.wias-berlin.de/people/fuhrmann/blobs/VoronoiFVMTemplate-jl1.10.jl))

## Some additional links

- [From Zero to Julia!](https://techytok.com/from-zero-to-julia/)
- [Modern Julia Workflows](https://modernjuliaworkflows.org/)
- [My (J.Fuhrmann's) remarks on Julia](https://j-fu.github.io/marginalia/julia/)

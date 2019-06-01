# JuliaCon2019-DataFrames-Tutorial

A hands-on tutorial on the DataFrames.jl package prepared for JuliaCon2019.

It consists of two files:
* `DataFramesIntroduction.ipynb` containing essential examples to start working with DataFrames.jl package and related package ecosystem
* `DataFramesExercises.ipynb` intended as a sandbox for additional exercises

The repository contains source data files `bank-additional-full.csv`, `data.txt` and `meta.txt` to facilitate the workflow. Their original source is https://archive.ics.uci.edu (the notebook using them give exact references).

Please make sure that you have the following packages installed before starting using the tutorial: DataFrames.jl, CSV.jl, FreqTables.jl, Tables.jl, Plots.jl, StatsPlots.jl, GLM.jl. You can add them by issuing the following commands:

```
using Pkg
Pkg.add("DataFrames.jl")
Pkg.add("CSV.jl")
Pkg.add("FreqTables.jl")
Pkg.add("Tables.jl")
Pkg.add("Plots.jl")
Pkg.add("StatsPlots.jl")
Pkg.add("GLM.jl")
```

# JuliaCon2019-DataFrames-Tutorial

A hands-on tutorial on the DataFrames.jl package prepared for JuliaCon2019.

It consists of two files:
* `DataFramesIntroduction.ipynb` containing essential examples to start working
* with DataFrames.jl package and related package ecosystem
* `DataFramesExercises.ipynb` intended as a sandbox for additional exercises

The repository contains source data files `bank-additional-full.csv`, `data.txt`
and `meta.txt` to facilitate the workflow. Their original source is
https://archive.ics.uci.edu (the notebooks using them give the source
references).

In order to run these examples first make sure that you have cloned the
repository to your local machine from GitHub. Then run the following command:
```
julia --project=. -e 'using IJulia; notebook(dir=pwd())'
```
in the folder where you have cloned the repository. It will start a Jupyter
Notebook session and you can then run he example notebooks.

If it is the first time you run the tutorial you might need to run
the following command before:
```
julia --project=. -e 'using Pkg; Pkg.instantiate(); Pkg.precompile()'
```
It will make sure that Julia downloads and precompiles all the packages that
are required in this tutorial.

[Here](https://bkamins.github.io/julialang/2020/05/18/project-workflow.html)
you can read more what `--project=.` option does when starting a fresh Julia
session.

---

Additional resources you might want to check out are:

* [DataFrames.jl manual](https://juliadata.github.io/DataFrames.jl/stable/)
* [DataFrames.jl Tutorial](https://github.com/bkamins/Julia-DataFrames-Tutorial/)
* [JuliaAcademy Introduction to DataFrames.jl](https://juliaacademy.com/p/introduction-to-dataframes-jl)

---

If you want to access the old version of this tutorial that was presented during
JuliaCon 2019 please go to
[JuliaCon2019 tag](https://github.com/bkamins/JuliaCon2019-DataFrames-Tutorial/tree/JuliaCon2019)
in this repository.

# Introduction to Statistical Learning with Julia

## Introduction
[An Introduction to Statistical Learning: With Applications in R](http://faculty.marshall.usc.edu/gareth-james/ISL/) is a great book to learn data science. The associated code is [R](https://www.r-project.org/about.html) which is a nice programming language for statisticians. However, R is not fast and in my opinion, it does not have nice syntax. There is a project named [ISLR-python](https://github.com/JWarmenhoven/ISLR-python) which ports the book to Python. I was inspired by the Python project and try to implement the introduced materials of this book in [Julialang](https://julialang.org/). Julia is a new language which is faster and more friendly to scientific computing than Python. Hopefully, this code is helpful for Julia lovers when they read the book.

## Library

In this project, I use Julia v1.5.1 and the following library
- [Plots.jl](https://github.com/JuliaPlots/PlotDocs.jl) for visualization
- [CSV.jl](https://csv.juliadata.org/v0.4.0/) for reading csv file
- [Clustering.jl](https://github.com/JuliaStats/Clustering.jl) for clustering algorithms 
- [LIBSVM.jl](https://github.com/JuliaML/LIBSVM.jl) for LibSVM implementation
- [StatsPlots.jl](https://github.com/JuliaPlots/StatsPlots.jl) for plotting statistic
- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) for data frame 
- [GLM.jl](https://github.com/JuliaStats/GLM.jl) for generalized linear model
- [Distributions.jl](https://github.com/JuliaStats/Distributions.jl) for stat distributions

## Note

I write a [blog post](http://tndoan.com/2020/12/25/lessons-learned-from-islr/) to summarize the lessons that I learn after doing this project.

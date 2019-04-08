# PDSampler.jl Documentation

[PDSampler.jl](https://github.com/alan-turing-institute/PDSampler.jl) is a package designed to provide an efficient, flexible, and expandable framework for samplers based on *Piecewise Deterministic Markov Processes* and their applications.
This includes the **Bouncy Particle Sampler** and the **Zig-Zag Sampler**.
See the references at the bottom of this page.

```@contents
Pages = [
    "aboutpdsampler.md",
    ]
Depth = 1
```

The project is hosted by the [Alan Turing Institute](https://www.turing.ac.uk) (ATI). If you encounter problems, please [open an issue on Github](https://github.com/alan-turing-institute/PDSampler.jl/issues).
If you have comments or wish to collaborate, please open an issue on Github. 

## Using the Package

To install the package, use the following command inside the Julia REPL:

```julia
Pkg.clone("PDSampler")
```

To load the package, use the command:

```julia
using PDSampler
```

You can also run the tests with ```Pkg.test("PDSampler")``` and update to the latest Github version with ```Pkg.update("PDSampler")```.

## Examples

The following examples will introduce you to the functionalities of the package.

```@contents
Pages = [
    "examples/ex_gbps1.md",
    "examples/ex_lbps1.md"
    ]
Depth = 1
```

### Code documentation

These pages introduce you to the core of the package and its interface.
This is useful if you are looking into expanding the code yourself to add a capacity or a specific model.

```@contents
Pages = [
    "techdoc/structure.md",
    "techdoc/coretools.md",
    "techdoc/models.md",
    "techdoc/global.md",
    "techdoc/local.md"
    ]
Depth = 1
```

## Contributing

```@contents
Pages = [
    "contributing/addingexample.md",
    "contributing/addingfeature.md"
]
Depth = 1
```

## References

* Alexandre Bouchard-Côté, Sebastian J. Vollmer and Arnaud Doucet, [*The Bouncy Particle Sampler: A Non-Reversible Rejection-Free Markov Chain Monte Carlo Method*](https://arxiv.org/abs/1510.02451), arXiv preprint, 2015.
* Joris Bierkens, Alexandre Bouchard-Côté, Arnaud Doucet, Andrew B. Duncan, Paul Fearnhead, Gareth Roberts and Sebastian J. Vollmer, [*Piecewise Deterministic Markov Processes for Scalable Monte Carlo on Restricted Domains*](https://arxiv.org/pdf/1701.04244.pdf), arXiv preprint, 2017.
* Joris Bierkens, Paul Fearnhead and Gareth Roberts, [*The Zig-Zag Process and Super-Efficient Sampling for Bayesian Analysis of Big Data*](https://arxiv.org/pdf/1607.03188.pdf), arXiv preprint, 2016.
* Changye Wu, Christian Robert, [*Generalized Bouncy Particle Sampler*](https://arxiv.org/pdf/1706.04781.pdf), arXiv preprint, 2017.

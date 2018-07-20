# [r-limsolve](https://anaconda.org/grst/r-limsolve)
![travis ci](https://api.travis-ci.org/grst-anaconda/r-limsolve.svg?branch=master)

Recipies for my anaconda packages.

## How to build
Summary of the [conda tutorial](https://conda.io/docs/user-guide/tutorials/build-pkgs.html).

The following command builds the package and lists an output path of
the compiled package.
```
conda build .
```

The following command gives a plain output of the output filename that will be generated:
```
conda build . --output
```

Convert the packages for all platforms:
```
conda convert --platform all <output_package.tar.bz2> -o ./build
```

Upload the package to anaconda cloud
```
# anaconda login
anaconda upload <path to compiled package>
```


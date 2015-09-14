
# tamper

> Easier Debugging of 'magrittr' Pipes

[![Linux Build Status](https://travis-ci.org//tamper.svg?branch=master)](https://travis-ci.org//tamper)

[![Windows Build status](https://ci.appveyor.com/api/projects/status/github//tamper?svg=true)](https://ci.appveyor.com/project//tamper)
[![](http://www.r-pkg.org/badges/version/tamper)](http://www.r-pkg.org/pkg/tamper)
[![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/tamper)](http://www.r-pkg.org/pkg/tamper)


One difficulty of 'magrittr' pipes is that they make debugging harder. If you don't always write correct code, and you use pipes, then you'll find tamper very useful. It is the 'magrittr' specific alternative of the 'recover' function: when used with 'options(error=tamper)', after an error, it displays the whole pipeline, marks the place of the error, and helps saving the temporary results.

## Installation

```r
devtools::install_github("/tamper")
```

## Usage

```r
library(tamper)
```

## License

MIT + file LICENSE © [Gabor Csardi](https://github.com/).
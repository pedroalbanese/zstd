# zstd(2)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/zstd/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/zstd?status.png)](http://godoc.org/github.com/pedroalbanese/zstd)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/zstd)](https://goreportcard.com/report/github.com/pedroalbanese/zstd)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/zstd)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/zstd)](https://github.com/pedroalbanese/zstd/releases)
### Command:
<pre>Usage: zstd [OPTION]... [FILE]
Compress or uncompress FILE (by default, compress FILE in-place).

  -c    write on standard output, keep original files unchanged
  -cores int
        number of cores to use for parallelization (default 1)
  -d    decompress; see also -c and -k
  -f    force overwrite of output file
  -h    print this help message
  -k    keep original files unchaned
  -s string
        use provided suffix on compressed files (default "zst")

With no FILE, or when FILE is -, read standard input.</pre>

## License

This project is licensed under the ISC License.

##### Copyright (c) 2020-2021 Pedro Albanese - ALBANESE Research Lab.

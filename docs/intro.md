## Introduction

This workflow uses [Clair3](https://www.github.com/HKU-BAL/Clair3) for calling small
variants from long reads. Clair3 makes the best of two methods: pileup (for fast
calling of variant candidates in high confidence regions), and full-alignment
(to improve precision of calls of more complex candidates).

This workflow uses [sniffles2](https://github.com/fritzsedlazeck/Sniffles) for
calling structural variants.

This workflow uses [modkit](https://github.com/nanoporetech/modkit) to
aggregate modified base calls into a [bedMethyl](https://www.encodeproject.org/data-standards/wgbs/) file.

This workflow uses [Dorado](https://github.com/nanoporetech/dorado/tree/master/dorado)
for basecalling `pod5` or `fast5` signal data.

This workflow uses [QDNAseq](https://bioconductor.org/packages/release/bioc/html/QDNAseq.html) for calling copy number variants.

This workflow uses a fork of [Straglr](https://github.com/philres/straglr) for genotyping short tandem repeat expansions.

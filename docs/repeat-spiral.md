# Repeat Spiral Plot

A tutorial by David Eccles about representing a repetitive DNA sequence in a visually-interesting form. This tutorial uses data from the [nanopore WGS consortium](https://github.com/nanopore-wgs-consortium/) and describes a process for generating an image similar to the following:

<img src="pics/repeat_spiral_small.png" alt="Repeat spiral plot for NA12878" title="Repeat spiral plot for NA12878" width="512"/>

## Accessory scripts

* [Repeat finder](https://github.com/gringer/bioinfscripts/blob/master/fastx-rlength.pl)
* [Spiral-generating R script](https://github.com/gringer/bioinfscripts/blob/master/seqmat.r)
* [Kmer dotplots](https://github.com/gringer/bioinfscripts/blob/master/fastx-kdotplot.pl)

## Process

1. Download sequence data
2. Troll for repetitive regions
3. Identify repetitive subsequence
4. Generate spiral plot
5. Generate kmer dotplots
6. Create montage using GIMP

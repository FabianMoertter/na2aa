# na2aa
Convert DNA sequences to longest amino acide sequence for all six reading frames

## Installation
I suppose you do not want to keep the package installed, thus I recommend
to install it in a fresh virtual environment.


Clone the repository then change into the directory and execute:
```
pip install .
```

## Usage

```
na2aa -s <sequences.fasta> -i <intervals.gff> -c <standard_code.txt>
```

## Example

In the example folder, run:
```
na2aa -s sequences.fasta -i intervals.gff -c standard_code.txt
```
The output is printed to the command line but you can
find the example output also in the file `genes.fasta`.

## Issues

  * input formats should be exactly the same format as in the example
  * slightly different results possible depending on whether start and stop are inclusive or exclusive and if the intervals are zero or one-based
  * start codon not properly implemented

## Future Development
  * this is just a small showcase project


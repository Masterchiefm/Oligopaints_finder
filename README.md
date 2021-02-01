# Oligopaints_finder
It's a very simple script to sort FISH probes form [Oligopaint database](https://oligopaints.hms.harvard.edu/). I don't know how the Oligopaints works, and I have to use the data they provided. My leader told me I need to chose the probes manually, which is a boring and time comsum work. I am not an AI, so I wrote this script.

# Usage
## Windows users:
1. Download the zip file from the release. Then unzip it, execute the exe file.
2. The screen reads: " input data set path: "  . You can type the file path or just drag the data set, for example, the hg19_chr1s.bed, to the terminal.
3. Then input the start site of the gene and the terminal site.
4. input output file path and name. Then the results will be there.

## Linux or Mac users:
Install dependences:
```
pip3 install cython, primer3
```
Run the script:
```
python3 get_FISH_probes.py
```


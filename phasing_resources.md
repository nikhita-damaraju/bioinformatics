# Variant callers and phasing software

## Variant callers
1. Short-read: GATK, VarScan, MuTect, and LoFreq
2. Long-read: Clair3, DeepVariant

## Phasing software
### Population-based phasing
Both of these methods need reference panels. The 1000G Phase3 reference panels can be found [here](http://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20130502/).
1. [ Beagle](https://faculty.washington.edu/browning/beagle/beagle.html)
2. [ShapeIT4](https://odelaneau.github.io/shapeit4/#installation)

### Read-based phasing
1. WhatsHap works well for both short and long reads
2. HAT is a method for short reads

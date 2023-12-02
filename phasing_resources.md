# Variant callers and phasing software

## Variant callers
1. Short-read: [GATK](https://gatk.broadinstitute.org/hc/en-us), [VarScan](https://varscan.sourceforge.net), [MuTect](https://gatk.broadinstitute.org/hc/en-us/articles/360037593851-Mutect2), and [LoFreq](https://csb5.github.io/lofreq/)
2. Long-read: [Clair3](https://github.com/HKU-BAL/Clair3), [DeepVariant](https://github.com/google/deepvariant)

## Phasing software
### Population-based phasing
Both of these methods need reference panels. The 1000G Phase3 reference panels can be found [here](http://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20130502/).
1. [ Beagle](https://faculty.washington.edu/browning/beagle/beagle.html)
2. [ShapeIT4](https://odelaneau.github.io/shapeit4/#installation)

### Read-based phasing
1. [WhatsHap](https://whatshap.readthedocs.io/en/latest/) works well for both short and long reads
2. [HAT](https://pypi.org/project/HAT-phasing/) is a method for short reads and long-reads

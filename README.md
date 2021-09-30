# SSPACE-LONGREAD

## Descriptions

SSPACE-longread

## Requirements

+ [x] Perl
  - [x] File::Path
  - [x] FindBin
  - [x] Getopt::Std
  - [x] Text::Wrap

## How to use

```
#format the contigs;
perl format_scaffolds.pl <CONTIG-sequences> > <CONTIG-sequences>_format.fa
#run blasr alsvolgt;
#blasr ../pacbio_reads.fasta <format-contigs> -minMatch 10 -minPctIdentity 70 -bestn 10 -noSplitSubreads -advanceExactMatches 1 -nCandidates 1 -maxAnchorsPerPosition 1 -nproc 8 -out <BLASR-output>
# perl pacbio_scaffolder.pl <BLASR-output> <CONTIG-sequences>_format.fa
```

## Citation

    Marten Boetzer and Walter Pirovano. SSPACE-LongRead: scaffolding bacterial draft genomes using long read sequence information. BMC Bioinformatics 2014, 15:211. doi:[10.1186/1471-2105-15-211](https://doi.org/10.1186/1471-2105-15-211)

# Maintainer

    卢福浩(Fu-Hao Lu)
    
    Professor, PhD
    
    作物逆境适应与改良国家重点实验室，生命科学学院
    
    State Key Labortory of Crop Stress Adaptation and Improvement
    
    College of Life Science
    
    河南大学金明校区
    
    Jinming Campus, Henan University
    
    开封 475004， 中国
    
    Kaifeng 475004, P.R.China
    
    E-mail: LUFUHAO@HENU.EDU.CN

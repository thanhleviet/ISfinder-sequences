# Insertion Sequence (IS) database

Update: 

- 2020-Oct
- 2019-09-25
- 2018-07-25

Collected from [ISfinder](https://isfinder.biotoul.fr/howto.php) , so when you use this sequence compilation, please cite:

**For ISfinder please cite**: Siguier P. et al. (2006) ISfinder: the reference centre for bacterial insertion sequences. Nucleic Acids Res. 34: D32-D36 (link pubmed) and the database URL (http://www-is.biotoul.fr).

**For ISbrowser please cite:** Kichenaradja P. et al. (2010) ISbrowser: an extension of ISfinder for visualizing insertion sequences in prokaryotic genomes. Nucleic Acids Res. 38: D62-D68 (link pubmed).`

**For ISsaga please cite:** Varani A. et al. (2011) ISsaga: an ensemble of web-based methods for high throughput identification and semi-automatic annotation of insertion sequences in prokaryotic genomesGenome Biology 2011, 12:R30

# Files

- **IS.csv**: Summary of IS collected from ISfinder
- **IS.fna**: DNA sequences (Description line: `>(IS name)_(IS group)_(IS family)`)
- **IS.faa**: AA sequences,  (Description line: `>(IS name) ~~~(IS name)_(IS group)_(IS family)_ORF~~~(IS function)~~~`). This file is formated to run with [Prokka](https://github.com/tseemann/prokka#fasta-database-format)


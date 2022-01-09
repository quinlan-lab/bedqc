# BEDQC

BEDQC is a tool to validate and profile genomic intervals in BED format.

Once you upload a file to BEDQC, it will automatically  
compare your file to the BED specifications, including 
checking the delimiter and line endings. A count
of intervals and their lengths will also tabulated 
and presented. No data is transferred from your local environment.

Once a BED file is uploaded, you can choose to perform more complex tasks
on your BED file including calculating metrics based on the
intervals and intersecting your file with various other
annotations. For instance, since most annotations will not overlap 
gaps in the same genome build, you can use this tool to help
determine your file's genome build comparing to gaps from various 
builds to find which has the fewest intersecting hits.

[BED file specification](https://samtools.github.io/hts-specs/BEDv1.pdf).

This tool utilizes the [biowasm project](https://github.com/biowasm/aioli)
to execute [bedtools](https://bedtools.readthedocs.io/en/latest/) in the browser.

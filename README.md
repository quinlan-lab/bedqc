# BED QC

A tool to profile BED formatted intervals (.bed).

BED QC will check your file against BED specifications,
including checking the delimiter and line endings. A count
of intervals and their lengths will tabulated and presented
upon upload into your browser's memory. No data is
transferred from your local environment.

Once uploaded, you can choose to perform more complex tasks
on your BED file including calculating metrics based on the
intervals and intersecting your file with various other
artifacts. For instance, you can use this tool to help
determine the genome build upon which your intervals are based
using Gaps from various builds to find which has the fewest
intersecting hits.

[BED file specification](https://bedtools.readthedocs.io/en/latest/content/general-usage.html).

This tool makes use of the [biowasm project](https://github.com/biowasm/aioli).

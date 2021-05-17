## Computational Biologist/Bioinformatician: Prep for follow-up interview

In this repository, you'll find several data files on SARS-CoV-2.

 * `data/{region}-small_alignment.fasta.xz` and `data/{region}-small_metadata.tsv.xz` for `region` in `europe`, `north-america`, `oceania`: These files are subsets of the SARS-CoV-2 genomes available on genbank.
 * `data/metadata.tsv.gz` with meta data associated with a much larger set of sequences from Genbank.


### Sequence availability by geographic region

Please use `data/metadata.tsv.gz` to summarize sequence availability for each of the major geographic regions over time (month or week).
Furthermore, write a script that extracts the breakdown of `Nextstrain_clade` for a specific country and time interval.
You can tackle this in your favorite programming language -- whichever way you feel like you'd do the best job.

### Mutation frequencies
In each of the alignments given above, determine the fraction of sequences with aminoacid `Y` at position `501` in the spike protein.
These sequences are aligned the annotated reference sequence [Wuhan/Hu1/2019](https://github.com/nextstrain/ncov/blob/master/defaults/reference_seq.gb).

### Build phylogenetic trees
Assembly a pipeline/script/workflow to build phylogenetic trees for the data sets above.
Feel free to use any tools you think are appropriate for the job.
If you don't have a preference, have a look at [augur](https://github.com/nextstrain/augur).

Please give instructions on how to run the pipeline (specify and conda environment, container, pip-file...).






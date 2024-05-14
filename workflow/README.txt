# Differentiated between the 2 snakefile present in this folder

You will see 2 snakefiles in this directory, one has the trimming steps include in the pipeline and the other Snakefile we excluded the trimming step in it.
If you see from the fastqc reports that the raw data doesn't need to be trimmed then opt for the Snakefile where the trimming step is excluded. Otherwise use the other snakefile that includes trimmomatic step.

# Stranded vs Unstranded Data

If the data is unstranded, you can fetch column n.2 from the file in sample_counts rule in Snakefile. If the data is stranded, you can fetch either column 3 or 4 from the same file in the same rule.


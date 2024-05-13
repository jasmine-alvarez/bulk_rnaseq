# Differentiated between the 2 snakefile present in this folder

You will see 2 snakefiles in this directory, one has the trimming steps include in the pipeline and the other Snakefile we excluded the trimming step in it.
If you see from the fastqc reports that the raw data doesn't need to be trimmed then opt for the Snakefile where the trimming step is excluded. Otherwise use the other snakefile that includes trimmomatic step.


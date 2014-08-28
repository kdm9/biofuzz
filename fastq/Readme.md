Fastq format breakers
=====================


These files (apart from good.fastq) break the fastq format in weird and
wonderfull ways:

 - `diff_lens.fastq`: Sequence and quality string have different lengths
 - `empty.fastq`: Only contains a single `@` charachter.
 - `good.fastq`: Valid fastq file with a single record
 - `nohdr.fastq`: Fastq file missing the header line
 - `noqual.fastq`: Fastq missing the quality line
 - `noqualhdrchr.fastq`: Fastq missing the quality header line (The line
   starting with `+`).
 - `noqualhdreol.fastq`: Fastq file truncated midway through the quality header
   line (the line starting with `+`).


# From [this](http://pb-falcon.readthedocs.io/en/latest/tutorial.html) tutorial

Download ecoli dataset

`$ wget https://downloads.pacbcloud.com/public/data/git-sym/ecoli.m140913_050931_42139_c100713652400000001823152404301535_s1_p0.subreads.tar.gz`

`$ tar -xvzf ecoli.m140913_050931_42139_c100713652400000001823152404301535_s1_p0.subreads.tar.gz`

Make a fofn
`/my/path/to/data/ecoli.1.subreads.fasta`
`/my/path/to/data/ecoli.2.subreads.fasta`
`/my/path/to/data/ecoli.3.subreads.fasta`

fc_run.py is what runs the assembly process.

Input:  fc_run.cfg

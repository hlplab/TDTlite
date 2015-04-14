# The TGrep2 Database Tools

## Getting started

Set the following environment variables in your profile:

`TGREP2ABLE` Set this to the directory that contains the TGrep2 corpora. For example, on `corn.stanford.edu`:

`setenv TGREP2ABLE /afs/ir/data/linguistic-data/Treebank/tgrep2able/`

`TGREP2_CORPUS` Set this to the TGrep2 default corpus. If you run TGrep2 without a corpus argument, it will run on this corpus. For example, on `corn.stanford.edu`:

`setenv TGREP2_CORPUS $TGREP2ABLE/swbd.t2c.gz`

`TDTlite` Set this to the directory that contains the TDT scripts. For example, on `corn.stanford.edu`:

`setenv TDTlite /afs/ir/data/linguistic-data/TDTlite/`

`TDT_DATABASES` Set this to the directory that contains the TDT databases. For example, on `corn.stanford.edu`:

`setenv TDT_DATABASES /afs/ir/data/linguistic-data/TDTlite/databases`

Then add the TDTlite directory to your `PATH`. For example, on `corn.stanford.edu`:

`setenv PATH $PATH:/afs/ir/data/linguistic-data/TDTlite/`

With this in place, you should be able to use the basic `run` command from within a project directory. Follow the instructions in `example_project` to test that everything is set up properly.

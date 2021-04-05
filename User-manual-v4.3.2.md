April 2021, version 4.3.2

=Introduction=
=Databases=
=Usage=
==Overview==
===Work directory===
Sortmerna uses a Work directory with the default location <code>$USER/sortmerna/run/</code>.
The work directory has the following structure
    $USER/sortmerna/run/
        kvdb/       key-value datastore for alignment results
        idx/        index database
        out/        output files like aligned.blast

==Options==
==Choosing parameters for filtering and read mapping==
===Example: multiple databases and the fastest alignment option===
===Filtering paired-end reads===
===Mapping reads for classification===
==OTU-picking==
=Help=

Any issues or bug reports should be reported to https://github.com/biocore/sortmerna/issues. Comments and suggestions are also always appreciated! 

=Citation=

If you use SortMeRNA please cite,

Kopylova E., Noe L. and Touzet H., "SortMeRNA: Fast and accurate filtering of ribosomal RNAs in metatranscriptomic data", Bioinformatics (2012), doi: 10.1093/bioinformatics/bts611.

Copyright (C) 2016-2021 Clarity Genomics BVBA
Turnhoutseweg 30, 2340 Beerse, Belgium
http://www.clarity-genomics.com

Copyright (C) 2014-2016 Knight Lab
Department of Pediatrics, UCSD School of Medicine, La Jolla, California, USA
https://knightlab.colorado.edu

Copyright (C) 2012-2014 Bonsai Bioinformatics Research Group
(LIFL - Université Lille 1), CNRS UMR 8022, INRIA Nord-Europe, France
http://bioinfo.lifl.fr/RNA/sortmerna/
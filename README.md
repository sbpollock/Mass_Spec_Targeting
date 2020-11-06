# Mass_Spec_Targeting

This is a Shiny dashboard designed to determine m/z search values for one or more peptide targets, then extract retention time and intensity data against MS1 spectra using .raw files as an input.

You can use it to, for instance, monitor retention times and intensity values of control BSA peptides across runs for quality control.

Alternatively, if the retention time of your target peptides of interest is know, you can search for their presence in an experimental run with a bit better sensitivity (and quantitativeness, in my experience) than using a database search program like PEAKS.
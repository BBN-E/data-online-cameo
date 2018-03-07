== cameo_files/

This folder contains the CAMEOXML files extracted from a subset of files from 
the English Gigaword V5 using BBN ACCENT. The sentence contents have
been stripped to protect copyright. They can be reconstructed using the 
character offset indices mapped to the original SGML files (newlines included).

== ground_truth.csv

This file contains a table mapping keys for event mentions coming from the 
CAMEOXML files constructed of the form:
filename_eventcode_mentionorder

to group ids "gids" indicating event mentions referring to the same event.

A 'yes' in the 'wrong' column marks an event that was incorrectly
extracted. These were ignored in the evaluation as to keep evaluation
of the event mention clustering method separate from event mention
extraction evaluation.

# fix-do_alignment-multisyn
Fix for do_alignment in multisyn build for being able to use htk labeller with a large database.
Error RROR [+7031] PutTransMat: Row 4 of transition mat sum = 1.064684 FATAL ERROR – Terminating program HERest 
Solved using -p option dividing list in 1000 chunks

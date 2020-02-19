# ChIP-Seq-motif

1. SequencesBackground   ## Subset of genome sequences in FASTA format file

2. Remap		## Peaks from each biological condition in a BED format file

3. GSE36354   	##Study con several ChIP-Seq experiments

3.1. Bio_Condition  ## CMYC_0H, CMYC_1H and CMCY_24H

3.1.1. Sequences    ##Peak sequences for the sets Raw, 50, 100 and 200

3.1.2. Homer		##Folds and files with the results of running Homer tool-kit on the set of peak sequences Raw, 50, 100 and 200

3.1.3. Clustering   
	3.1.3.1. logo_selected.pdf		##Logo sequences of all pre-selected motifs for the sets Raw, 50, 100 and 200
	
	3.1.3.2. heatmap_selected.pdf 	##Heatmap and dendogram of all pre-selected motifs for the sets Raw, 50, 100 and 200

	3.1.3.3. distanceMatrix.txt		##Distances matrix of all pre-selected motifs for the sets Raw, 50, 100 and 200

3.1.4. Refinement  
	3.1.4.1. refined_motif_SET.motif	##Motif derived from scanning the corresponding Homer-motif belonging to the selected cluster on the peak sequences for each set Raw, 50, 100 and 200
	
	3.1.4.2. logomotif_SET.pdf			##Logo sequence of the motif refined for each set Raw, 50, 100 and 200
	
	3.1.4.3. seq_motif_SET.txt			##Hits of the peak sequences that present a match score equal or higher than the established threshold, with which the refined motif has been generated

3.1.5. Merging
	3.1.5.1. merged_motif.motif			##Motif merged from the refined motifs of each set Raw, 50, 100 and 200
	
	3.1.5.2. logo_merged_motif.pdf		##Logo sequence of the motif merged
	
	3.1.5.3. seq_merged_motif.txt		##Hits resulting from scanning the merged motif on the peaks sequences for the Raw set 
	
	3.1.5.4. alignment_merged.pdf		##Alignment corresponding to the four refined-motifs of each set and the merged-motif

3.1.6. Validation
	3.1.6.1. StampResults.pdf			##Result of running Stamp tool-kit 

3.2. Analysis
	3.2.1. alignment_merged.pdf			##Alignment corresponding to the three merged-motifs of each bio_condition
	
	3.2.2. heatmap_total.pdf			##Heatmap and dendogram of all refined-motifs and merged-motifs of all bio_conditions
	
	3.2.3. distanceMatrix.txt			##Distances matrix of all refined-motifs and merged-motifs of all bio_conditons
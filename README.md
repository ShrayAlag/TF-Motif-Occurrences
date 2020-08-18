# TF-Motif-Occurrences
This repository will have a few python notebooks which can find occurrences and co-occurrences of Transcription Factor motifs in genomic data (FASTA files).

Motif_Co-occurrence_Calculation: To find co-occurrences of motifs (either inputted by hand or chosen from the MEME tool results which will be displayed) in a fasta file. This notebook will then print out extensive statistical results about the co-occurrences (histograms with the frequencies of the length between the two motifs) and display the sequence logos of the most common sequences before and after the motif

HT-SELEX_CNN_Model: Deep Learning (Convolutional Neural Network) Model Architecture to predict the count and probabilities of a kmer sequence occurring in a .counts file (good for HT-SELEX and other sequencing techniques)

Motif_ZNF436_End: Goes through a fasta sequence file and sees the genomic sequences of what comes before and after a motif/sequence the user wants to search for. Outputs those sequences (the sequences before and after the searched for motif) in an png sequence logo format. Compares to expected sequence and user can search for either an output of MEME or a manually inputted sequence. 

AffSeq_Motif_Finder: This notebook is to find occurrences of a motif (either inputted by hand or via a MEME Tool .txt result file) in an .counts data file. Many sequencing techniques like HT-SELEX and AffSeq may use this type of file (.counts) to convey their reads.

ALL_DATA_Motif_Co-occurance_Calculation: Programmatically finds the co-occurrences of any two motif/sequences (either inputted through a MEME txt file result or typed in) over all of the data files in a directory. Outputs plots containing the sequences of the motifs used to get the co-occurrences and the stastical analysis. Very useful when running over lots of genomic sequence data, and it is extremely efficent (~7 seconds for each dataset). 

Generic_Motif_Fasta_Search: Finds an occurrence of a sequence in a fasta file (very common format for genomic sequences). Very generalizable and can be adapted for many other more complex tasks. Additionally, outputs some basic statistics of the search. Some of the more advanced adaptations of this notebook are seen in this repository. 

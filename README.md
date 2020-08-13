# TF-Motif-Occurrences
This repository will have a few python notebooks which can find occurrences and co-occurrences of Transcription Factor motifs in genomic data (FASTA files).

Motif_Co-occurrence_Calculation: To find co-occurrences of motifs (either inputted by hand or chosen from the MEME tool results which will be displayed) in a fasta file. This notebook will then print out extensive statistical results about the co-occurrences (histograms with the frequencies of the length between the two motifs) and display the sequence logos of the most common sequences before and after the motif

HT-SELEX_CNN_Model: Deep Learning (Convolutional Neural Network) Model Architecture to predict the count and probabilities of a kmer sequence occurring in a .counts file (good for HT-SELEX and other sequencing techniques)

Motif_ZNF436_End:

AffSeq_Motif_Finder: This notebook is to find occurrences of a motif (either inputted by hand or via a MEME Tool .txt result file) in an .counts data file. Many sequencing techniques like HT-SELEX and AffSeq may use this type of file (.counts) to convey their reads.

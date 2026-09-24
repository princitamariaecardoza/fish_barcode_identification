Fish Identification Using DNA Barcoding and Machine Learning

This project uses DNA barcoding and machine learning to identify fish species from COI (Cytochrome c oxidase subunit I) DNA sequences.
We obtained COI sequences of Indian fishes from NCBI GenBank and processed them to remove low-quality and unsuitable sequences. Instead of aligning the DNA sequences, the project uses k-mer frequencies to convert DNA sequences into numerical features for machine-learning classification.
Three machine-learning models are compared:k-Nearest Neighbours (kNN), Random Forest, Linear Support Vector Machine (SVM)

The project also tests how well the models perform when a species is completely absent from the training dataset. In this case, the model attempts to identify the genus rather than the exact species.
Finally, the project explores whether the model can recognize when it is uncertain about a prediction, rather than incorrectly assigning an unknown species to a known species.

Main Goal: The main aim is to investigate whether alignment-free machine learning using COI DNA barcodes can be used for fish identification, particularly when the reference database does not contain the exact species being identified.

These python notebooks are here for future reference pre-GAT attempts. These strategies instead used the Morgan Fingerprint to break down ligands into all possible substructures, then reclassified ligands as a one-hot encoded array of what substructures were present. Then, I trained the model using the one-hot encoded array as predictors for pIC50. 

The current state of the model has since migrated to a GAT accounting for stereochemistry. 

# Raup
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)
# Tested with: PluMA 1.0, R 3.2.5

PluMA plugin to run the Raup-Crick (Raup and Crick, 1979) algorithm
and compute dissimilarities.

The plugin accepts input in the form of a CSV file with rows representing samples
and columns community members, with entry (i, j) representing the abundance of member j
in sample i.

The plugin produces output as a CSV file with rows and columns representing samples
and entry (i, j) contains the level of dissimilarity between sample i and sample j.

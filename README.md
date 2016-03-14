# Characters' frequention in wikipedia articles
This sample dataset contains two sets of equal size - 5400 feature vectors.

The files are in the *.csv* format. Each vector contains 26 features
representing relative frequencies of respective characters of the alphabet.
The target is language code.

The data were obtained from *wikipedia.org* articles. Three languages were
explored, namely Czech(Cs), English(En) and German(Ge).

Note that languages are not equally frequent in the dataset.

The files *\*\_biased0p.csv* contains modified vectors, where values were
randomly substituted by question marks in *p* percent of cases.
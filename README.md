# Background

Word frequency consistently demonstrates a power-law distribution where the frequency $(f)$ of a word is approximately inversely proportional to its rank $(r)$ in a frequency table [(Zipf, 1936)](https://www.scirp.org/reference/referencespapers?referenceid=2902324). 

$$
f(r) \propto \frac{1}{r^s}
$$

Where:
- $f(r)$ = frequency of the word with rank $\(r\) $ 
- $r$ = rank of the word in a frequency table  
- $s$ = power-law exponent (typically $s \approx 1 $)

Why does this Zipfian distribution emerge? I present a definitional framework and accompanying code to investigate [Manin (2008's)](https://www.scirp.org/reference/referencespapers?referenceid=2902324) hypothesis that Zipf’s law arises from the semantic organization of language.

Specifically, I use [Princeton Wordnet 3.0](https://wordnet.princeton.edu/) to derive a quantitative measure of semantic organization from hyponymy and evaluate whether it predicts lemma frequencies in a Zipfian manner. 

# Definitions

# FAQ


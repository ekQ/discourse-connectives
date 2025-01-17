# Wikipedia discourse connectives

This is a data release accompaning this paper:

-  Title: "Automatic Prediction of Discourse Connectives"
-  Authors: Eric Malmi, Daniele Pighin, Sebastian Krause, Mikhail Kozhevnikov
-  To be presented at LREC 2018
-  Paper: https://arxiv.org/abs/1702.00992

## Contents

This dataset consists of:

- 2.9 million pairs of adjacent sentences extracted from the English Wikipedia
  on September 5, 2016, including the discourse connective at the beginning of
  the second sentence, if any, i.e., the "gold" connective
  - The data has been split into ten files:
    connective_examples/discourse_connectives_wikipedia_part[0-9] (see the 
    first file for field descriptions).
  - NB: One should either uppercase the first character of the second sentence
    or lowercase the whole second sentence before trying to predict the
    connective to avoid giving away the presence of a connective.
- Training, development and test splits used in our experiments (in the splits
  directory).
- For 10,000 sentences, the connectives independently imputed by three human
  raters (file: human_ratings.tsv).

## License

The data is licensed under the
Creative Commons Attribution-ShareAlike 3.0 license.

For more details: https://creativecommons.org/licenses/by-sa/3.0/us/

## Contacts

For further information, you can contact:

  - eric dot malmi at gmail dot com
  - daniele dot pighin at gmail dot com

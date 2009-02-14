This is a pute Python library that allows you to compare texts or
strings using an n-gram model and cosine similarity. N-grams are
tuples of length n consisting of subsequent tokens from a text. For
example, if we treat words as tokens, then the first few trigrams
(3-grams) of the license will be:

 * 'this work ‘as-is’',
 * 'work ‘as-is’ we',
 * '‘as-is’ we provide',
 * 'we provide no',
 * 'provide no warranty'.
 * ...

Depending on what you choose as the basic token (words or characters)
you can use this library for approximate string matching (finding
misspellings, etc.) or as a "good enough" method of checking whether
two texts [are similar] [Lee].

[Lee]: http://www.citeulike.org/group/2914/article/1230941 "A Comparison of Machine Measures of Text Document Similarity with Human Judgments"